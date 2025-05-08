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
Z3 options: "-T:600 -st lp.dio=true"
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
Z3 options: "-T:600 -st lp.dio=true"
Z3 inputs: inputs/rings
Z3 commit message: filter out terms that are not solved

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |   1.234s  |   1.234s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |   2.691s  |   2.691s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |  16.933s  |  16.933s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |   0.181s  |   0.181s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |   1.234s  |   1.234s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |   2.691s  |   2.691s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |  16.933s  |  16.933s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |   0.181s  |   0.181s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |   1.234s  |   1.234s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |   2.691s  |   2.691s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |  16.933s  |  16.933s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |   0.181s  |   0.181s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |   1.234s  |   1.234s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |   2.691s  |   2.691s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |  16.933s  |  16.933s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |   0.181s  |   0.181s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ring_2exp12_9vars_8ite_unsat.smt2                                                          | 599.961s |46.144MiB|
|ring_2exp8_9vars_8ite_unsat.smt2                                                           | 599.957s |46.552MiB|
|ring_2exp14_9vars_8ite_unsat.smt2                                                          | 599.953s |41.34MiB|
|ring_2exp10_9vars_8ite_unsat.smt2                                                          | 599.951s |52.084MiB|
|ring_2exp6_9vars_8ite_unsat.smt2                                                           | 599.946s |42.104MiB|
|ring_2exp6_8vars_5ite_unsat.smt2                                                           | 599.945s |38.18MiB|
|ring_2exp6_9vars_7ite_unsat.smt2                                                           | 599.944s |46.856MiB|
|ring_2exp4_9vars_6ite_unsat.smt2                                                           | 599.941s |38.08MiB|
|ring_2exp4_9vars_8ite_unsat.smt2                                                           | 599.939s |37.992MiB|
|ring_2exp16_9vars_8ite_unsat.smt2                                                          | 599.935s |42.824MiB|
|ring_2exp6_8vars_7ite_unsat.smt2                                                           | 599.921s |39.752MiB|
|ring_2exp4_7vars_6ite_unsat.smt2                                                           | 495.639s |45.404MiB|
|ring_2exp4_9vars_7ite_unsat.smt2                                                           | 298.197s |30.0MiB|
|ring_2exp4_8vars_7ite_unsat.smt2                                                           | 166.669s |28.94MiB|
|ring_2exp16_9vars_7ite_unsat.smt2                                                          | 157.482s |29.324MiB|
|ring_2exp12_9vars_7ite_unsat.smt2                                                          | 147.861s |29.476MiB|
|ring_2exp8_9vars_7ite_unsat.smt2                                                           | 146.890s |31.04MiB|
|ring_2exp10_9vars_7ite_unsat.smt2                                                          | 144.722s |30.124MiB|
|ring_2exp14_9vars_7ite_unsat.smt2                                                          | 143.606s |28.756MiB|
|ring_2exp14_8vars_7ite_unsat.smt2                                                          | 122.216s |28.136MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ring_2exp12_9vars_8ite_unsat.smt2                                                          | 599.961s |46.144MiB|
|ring_2exp8_9vars_8ite_unsat.smt2                                                           | 599.957s |46.552MiB|
|ring_2exp14_9vars_8ite_unsat.smt2                                                          | 599.953s |41.34MiB|
|ring_2exp10_9vars_8ite_unsat.smt2                                                          | 599.951s |52.084MiB|
|ring_2exp6_9vars_8ite_unsat.smt2                                                           | 599.946s |42.104MiB|
|ring_2exp6_8vars_5ite_unsat.smt2                                                           | 599.945s |38.18MiB|
|ring_2exp6_9vars_7ite_unsat.smt2                                                           | 599.944s |46.856MiB|
|ring_2exp4_9vars_6ite_unsat.smt2                                                           | 599.941s |38.08MiB|
|ring_2exp4_9vars_8ite_unsat.smt2                                                           | 599.939s |37.992MiB|
|ring_2exp16_9vars_8ite_unsat.smt2                                                          | 599.935s |42.824MiB|
|ring_2exp6_8vars_7ite_unsat.smt2                                                           | 599.921s |39.752MiB|
|ring_2exp4_7vars_6ite_unsat.smt2                                                           | 495.639s |45.404MiB|
|ring_2exp4_9vars_7ite_unsat.smt2                                                           | 298.197s |30.0MiB|
|ring_2exp4_8vars_7ite_unsat.smt2                                                           | 166.669s |28.94MiB|
|ring_2exp16_9vars_7ite_unsat.smt2                                                          | 157.482s |29.324MiB|
|ring_2exp12_9vars_7ite_unsat.smt2                                                          | 147.861s |29.476MiB|
|ring_2exp8_9vars_7ite_unsat.smt2                                                           | 146.890s |31.04MiB|
|ring_2exp10_9vars_7ite_unsat.smt2                                                          | 144.722s |30.124MiB|
|ring_2exp14_9vars_7ite_unsat.smt2                                                          | 143.606s |28.756MiB|
|ring_2exp14_8vars_7ite_unsat.smt2                                                          | 122.216s |28.136MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |20.124MiB|20.124MiB|0B| 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |20.32MiB|20.32MiB|0B| 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |20.264MiB|20.264MiB|0B| 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |20.28MiB|20.28MiB|0B| 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |20.428MiB|20.428MiB|0B| 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |20.492MiB|20.492MiB|0B| 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |20.472MiB|20.472MiB|0B| 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |20.524MiB|20.524MiB|0B| 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |20.628MiB|20.628MiB|0B| 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |20.616MiB|20.616MiB|0B| 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |20.892MiB|20.892MiB|0B| 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |21.2MiB|21.2MiB|0B| 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |20.748MiB|20.748MiB|0B| 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |20.796MiB|20.796MiB|0B| 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |20.996MiB|20.996MiB|0B| 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |21.048MiB|21.048MiB|0B| 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |22.348MiB|22.348MiB|0B| 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |24.752MiB|24.752MiB|0B| 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |21.048MiB|21.048MiB|0B| 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |21.228MiB|21.228MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |20.124MiB|20.124MiB|0B| 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |20.32MiB|20.32MiB|0B| 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |20.264MiB|20.264MiB|0B| 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |20.28MiB|20.28MiB|0B| 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |20.428MiB|20.428MiB|0B| 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |20.492MiB|20.492MiB|0B| 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |20.472MiB|20.472MiB|0B| 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |20.524MiB|20.524MiB|0B| 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |20.628MiB|20.628MiB|0B| 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |20.616MiB|20.616MiB|0B| 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |20.892MiB|20.892MiB|0B| 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |21.2MiB|21.2MiB|0B| 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |20.748MiB|20.748MiB|0B| 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |20.796MiB|20.796MiB|0B| 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |20.996MiB|20.996MiB|0B| 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |21.048MiB|21.048MiB|0B| 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |22.348MiB|22.348MiB|0B| 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |24.752MiB|24.752MiB|0B| 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |21.048MiB|21.048MiB|0B| 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |21.228MiB|21.228MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |20.124MiB|20.124MiB|0B| 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |20.32MiB|20.32MiB|0B| 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |20.264MiB|20.264MiB|0B| 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |20.28MiB|20.28MiB|0B| 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |20.428MiB|20.428MiB|0B| 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |20.492MiB|20.492MiB|0B| 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |20.472MiB|20.472MiB|0B| 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |20.524MiB|20.524MiB|0B| 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |20.628MiB|20.628MiB|0B| 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |20.616MiB|20.616MiB|0B| 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |20.892MiB|20.892MiB|0B| 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |21.2MiB|21.2MiB|0B| 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |20.748MiB|20.748MiB|0B| 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |20.796MiB|20.796MiB|0B| 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |20.996MiB|20.996MiB|0B| 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |21.048MiB|21.048MiB|0B| 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |22.348MiB|22.348MiB|0B| 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |24.752MiB|24.752MiB|0B| 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |21.048MiB|21.048MiB|0B| 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |21.228MiB|21.228MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |20.124MiB|20.124MiB|0B| 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |20.32MiB|20.32MiB|0B| 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |20.264MiB|20.264MiB|0B| 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |20.28MiB|20.28MiB|0B| 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |20.428MiB|20.428MiB|0B| 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |20.492MiB|20.492MiB|0B| 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |20.472MiB|20.472MiB|0B| 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |20.524MiB|20.524MiB|0B| 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |20.628MiB|20.628MiB|0B| 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |20.616MiB|20.616MiB|0B| 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |20.892MiB|20.892MiB|0B| 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |21.2MiB|21.2MiB|0B| 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |20.748MiB|20.748MiB|0B| 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |20.796MiB|20.796MiB|0B| 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |20.996MiB|20.996MiB|0B| 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |21.048MiB|21.048MiB|0B| 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |22.348MiB|22.348MiB|0B| 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |24.752MiB|24.752MiB|0B| 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |21.048MiB|21.048MiB|0B| 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |21.228MiB|21.228MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ring_2exp10_9vars_8ite_unsat.smt2                                                          | 599.951s |52.084MiB|
|ring_2exp6_9vars_7ite_unsat.smt2                                                           | 599.944s |46.856MiB|
|ring_2exp8_9vars_8ite_unsat.smt2                                                           | 599.957s |46.552MiB|
|ring_2exp12_9vars_8ite_unsat.smt2                                                          | 599.961s |46.144MiB|
|ring_2exp4_7vars_6ite_unsat.smt2                                                           | 495.639s |45.404MiB|
|ring_2exp16_9vars_8ite_unsat.smt2                                                          | 599.935s |42.824MiB|
|ring_2exp6_9vars_8ite_unsat.smt2                                                           | 599.946s |42.104MiB|
|ring_2exp14_9vars_8ite_unsat.smt2                                                          | 599.953s |41.34MiB|
|ring_2exp6_8vars_7ite_unsat.smt2                                                           | 599.921s |39.752MiB|
|ring_2exp6_8vars_5ite_unsat.smt2                                                           | 599.945s |38.18MiB|
|ring_2exp4_9vars_6ite_unsat.smt2                                                           | 599.941s |38.08MiB|
|ring_2exp4_9vars_8ite_unsat.smt2                                                           | 599.939s |37.992MiB|
|ring_2exp8_9vars_7ite_unsat.smt2                                                           | 146.890s |31.04MiB|
|ring_2exp10_9vars_7ite_unsat.smt2                                                          | 144.722s |30.124MiB|
|ring_2exp4_9vars_7ite_unsat.smt2                                                           | 298.197s |30.0MiB|
|ring_2exp10_9vars_6ite_unsat.smt2                                                          |  91.634s |29.492MiB|
|ring_2exp12_9vars_7ite_unsat.smt2                                                          | 147.861s |29.476MiB|
|ring_2exp16_9vars_7ite_unsat.smt2                                                          | 157.482s |29.324MiB|
|ring_2exp4_8vars_7ite_unsat.smt2                                                           | 166.669s |28.94MiB|
|ring_2exp14_9vars_7ite_unsat.smt2                                                          | 143.606s |28.756MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|ring_2exp10_9vars_8ite_unsat.smt2                                                          | 599.951s |52.084MiB|
|ring_2exp6_9vars_7ite_unsat.smt2                                                           | 599.944s |46.856MiB|
|ring_2exp8_9vars_8ite_unsat.smt2                                                           | 599.957s |46.552MiB|
|ring_2exp12_9vars_8ite_unsat.smt2                                                          | 599.961s |46.144MiB|
|ring_2exp4_7vars_6ite_unsat.smt2                                                           | 495.639s |45.404MiB|
|ring_2exp16_9vars_8ite_unsat.smt2                                                          | 599.935s |42.824MiB|
|ring_2exp6_9vars_8ite_unsat.smt2                                                           | 599.946s |42.104MiB|
|ring_2exp14_9vars_8ite_unsat.smt2                                                          | 599.953s |41.34MiB|
|ring_2exp6_8vars_7ite_unsat.smt2                                                           | 599.921s |39.752MiB|
|ring_2exp6_8vars_5ite_unsat.smt2                                                           | 599.945s |38.18MiB|
|ring_2exp4_9vars_6ite_unsat.smt2                                                           | 599.941s |38.08MiB|
|ring_2exp4_9vars_8ite_unsat.smt2                                                           | 599.939s |37.992MiB|
|ring_2exp8_9vars_7ite_unsat.smt2                                                           | 146.890s |31.04MiB|
|ring_2exp10_9vars_7ite_unsat.smt2                                                          | 144.722s |30.124MiB|
|ring_2exp4_9vars_7ite_unsat.smt2                                                           | 298.197s |30.0MiB|
|ring_2exp10_9vars_6ite_unsat.smt2                                                          |  91.634s |29.492MiB|
|ring_2exp12_9vars_7ite_unsat.smt2                                                          | 147.861s |29.476MiB|
|ring_2exp16_9vars_7ite_unsat.smt2                                                          | 157.482s |29.324MiB|
|ring_2exp4_8vars_7ite_unsat.smt2                                                           | 166.669s |28.94MiB|
|ring_2exp14_9vars_7ite_unsat.smt2                                                          | 143.606s |28.756MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|ring_2exp10_3vars_0ite_unsat.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_1ite_unsat.smt2                                                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|ring_2exp10_3vars_2ite_unsat.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_0ite_unsat.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_1ite_unsat.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_2ite_unsat.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|ring_2exp10_4vars_3ite_unsat.smt2                                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_0ite_unsat.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_1ite_unsat.smt2                                                           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_2ite_unsat.smt2                                                           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_3ite_unsat.smt2                                                           |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|ring_2exp10_5vars_4ite_unsat.smt2                                                           |   1.234s  |   1.234s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_0ite_unsat.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_1ite_unsat.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_2ite_unsat.smt2                                                           |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_3ite_unsat.smt2                                                           |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_4ite_unsat.smt2                                                           |   2.691s  |   2.691s  |   0.000s  | 0.0%|
|ring_2exp10_6vars_5ite_unsat.smt2                                                           |  16.933s  |  16.933s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_0ite_unsat.smt2                                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_1ite_unsat.smt2                                                           |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_2ite_unsat.smt2                                                           |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_3ite_unsat.smt2                                                           |   1.466s  |   1.466s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_4ite_unsat.smt2                                                           |  12.403s  |  12.403s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_5ite_unsat.smt2                                                           |  15.636s  |  15.636s  |   0.000s  | 0.0%|
|ring_2exp10_7vars_6ite_unsat.smt2                                                           |  48.852s  |  48.852s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_0ite_unsat.smt2                                                           |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_1ite_unsat.smt2                                                           |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_2ite_unsat.smt2                                                           |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_3ite_unsat.smt2                                                           |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_4ite_unsat.smt2                                                           |   1.834s  |   1.834s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_5ite_unsat.smt2                                                           |  28.335s  |  28.335s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_6ite_unsat.smt2                                                           |  74.687s  |  74.687s  |   0.000s  | 0.0%|
|ring_2exp10_8vars_7ite_unsat.smt2                                                           | 107.344s  | 107.344s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_0ite_unsat.smt2                                                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_1ite_unsat.smt2                                                           |   0.644s  |   0.644s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_2ite_unsat.smt2                                                           |   1.034s  |   1.034s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_3ite_unsat.smt2                                                           |   1.312s  |   1.312s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_4ite_unsat.smt2                                                           |   4.435s  |   4.435s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_5ite_unsat.smt2                                                           |  29.714s  |  29.714s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_6ite_unsat.smt2                                                           |  91.634s  |  91.634s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_7ite_unsat.smt2                                                           | 144.722s  | 144.722s  |   0.000s  | 0.0%|
|ring_2exp10_9vars_8ite_unsat.smt2                                                           | 599.951s  | 599.951s  |   0.000s  | 0.0%|
|ring_2exp12_3vars_0ite_unsat.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|ring_2exp12_3vars_1ite_unsat.smt2                                                           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ring_2exp12_3vars_2ite_unsat.smt2                                                           |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|ring_2exp12_4vars_0ite_unsat.smt2                                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|ring_2exp12_4vars_1ite_unsat.smt2                                                           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|ring_2exp12_4vars_2ite_unsat.smt2                                                           |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|ring_2exp12_4vars_3ite_unsat.smt2                                                           |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_0ite_unsat.smt2                                                           |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_1ite_unsat.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_2ite_unsat.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_3ite_unsat.smt2                                                           |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|ring_2exp12_5vars_4ite_unsat.smt2                                                           |   0.925s  |   0.925s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_0ite_unsat.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_1ite_unsat.smt2                                                           |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_2ite_unsat.smt2                                                           |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_3ite_unsat.smt2                                                           |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_4ite_unsat.smt2                                                           |   2.100s  |   2.100s  |   0.000s  | 0.0%|
|ring_2exp12_6vars_5ite_unsat.smt2                                                           |   5.019s  |   5.019s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_0ite_unsat.smt2                                                           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_1ite_unsat.smt2                                                           |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_2ite_unsat.smt2                                                           |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_3ite_unsat.smt2                                                           |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_4ite_unsat.smt2                                                           |   3.838s  |   3.838s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_5ite_unsat.smt2                                                           |  17.886s  |  17.886s  |   0.000s  | 0.0%|
|ring_2exp12_7vars_6ite_unsat.smt2                                                           |  45.992s  |  45.992s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_0ite_unsat.smt2                                                           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_1ite_unsat.smt2                                                           |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_2ite_unsat.smt2                                                           |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_3ite_unsat.smt2                                                           |   0.729s  |   0.729s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_4ite_unsat.smt2                                                           |   3.385s  |   3.385s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_5ite_unsat.smt2                                                           |  20.168s  |  20.168s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_6ite_unsat.smt2                                                           |  67.912s  |  67.912s  |   0.000s  | 0.0%|
|ring_2exp12_8vars_7ite_unsat.smt2                                                           | 113.270s  | 113.270s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_0ite_unsat.smt2                                                           |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_1ite_unsat.smt2                                                           |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_2ite_unsat.smt2                                                           |   0.558s  |   0.558s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_3ite_unsat.smt2                                                           |   1.940s  |   1.940s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_4ite_unsat.smt2                                                           |  19.823s  |  19.823s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_5ite_unsat.smt2                                                           |  28.880s  |  28.880s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_6ite_unsat.smt2                                                           |  85.377s  |  85.377s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_7ite_unsat.smt2                                                           | 147.861s  | 147.861s  |   0.000s  | 0.0%|
|ring_2exp12_9vars_8ite_unsat.smt2                                                           | 599.961s  | 599.961s  |   0.000s  | 0.0%|
|ring_2exp14_3vars_0ite_unsat.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|ring_2exp14_3vars_1ite_unsat.smt2                                                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ring_2exp14_3vars_2ite_unsat.smt2                                                           |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|ring_2exp14_4vars_0ite_unsat.smt2                                                           |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|ring_2exp14_4vars_1ite_unsat.smt2                                                           |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|ring_2exp14_4vars_2ite_unsat.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|ring_2exp14_4vars_3ite_unsat.smt2                                                           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_0ite_unsat.smt2                                                           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_1ite_unsat.smt2                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_2ite_unsat.smt2                                                           |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_3ite_unsat.smt2                                                           |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|ring_2exp14_5vars_4ite_unsat.smt2                                                           |   0.815s  |   0.815s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_0ite_unsat.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_1ite_unsat.smt2                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_2ite_unsat.smt2                                                           |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_3ite_unsat.smt2                                                           |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_4ite_unsat.smt2                                                           |   1.397s  |   1.397s  |   0.000s  | 0.0%|
|ring_2exp14_6vars_5ite_unsat.smt2                                                           |   4.299s  |   4.299s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_0ite_unsat.smt2                                                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_1ite_unsat.smt2                                                           |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_2ite_unsat.smt2                                                           |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_3ite_unsat.smt2                                                           |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_4ite_unsat.smt2                                                           |   1.454s  |   1.454s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_5ite_unsat.smt2                                                           |  22.871s  |  22.871s  |   0.000s  | 0.0%|
|ring_2exp14_7vars_6ite_unsat.smt2                                                           |  48.733s  |  48.733s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_0ite_unsat.smt2                                                           |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_1ite_unsat.smt2                                                           |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_2ite_unsat.smt2                                                           |   0.594s  |   0.594s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_3ite_unsat.smt2                                                           |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_4ite_unsat.smt2                                                           |   4.285s  |   4.285s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_5ite_unsat.smt2                                                           |  27.696s  |  27.696s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_6ite_unsat.smt2                                                           |  70.974s  |  70.974s  |   0.000s  | 0.0%|
|ring_2exp14_8vars_7ite_unsat.smt2                                                           | 122.216s  | 122.216s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_0ite_unsat.smt2                                                           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_1ite_unsat.smt2                                                           |   0.614s  |   0.614s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_2ite_unsat.smt2                                                           |   0.825s  |   0.825s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_3ite_unsat.smt2                                                           |   1.421s  |   1.421s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_4ite_unsat.smt2                                                           |   3.272s  |   3.272s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_5ite_unsat.smt2                                                           |  28.979s  |  28.979s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_6ite_unsat.smt2                                                           |  75.324s  |  75.324s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_7ite_unsat.smt2                                                           | 143.606s  | 143.606s  |   0.000s  | 0.0%|
|ring_2exp14_9vars_8ite_unsat.smt2                                                           | 599.953s  | 599.953s  |   0.000s  | 0.0%|
|ring_2exp16_3vars_0ite_unsat.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|ring_2exp16_3vars_1ite_unsat.smt2                                                           |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp16_3vars_2ite_unsat.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp16_4vars_0ite_unsat.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|ring_2exp16_4vars_1ite_unsat.smt2                                                           |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|ring_2exp16_4vars_2ite_unsat.smt2                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|ring_2exp16_4vars_3ite_unsat.smt2                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_0ite_unsat.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_1ite_unsat.smt2                                                           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_2ite_unsat.smt2                                                           |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_3ite_unsat.smt2                                                           |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|ring_2exp16_5vars_4ite_unsat.smt2                                                           |   0.889s  |   0.889s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_0ite_unsat.smt2                                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_1ite_unsat.smt2                                                           |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_2ite_unsat.smt2                                                           |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_3ite_unsat.smt2                                                           |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_4ite_unsat.smt2                                                           |   1.949s  |   1.949s  |   0.000s  | 0.0%|
|ring_2exp16_6vars_5ite_unsat.smt2                                                           |  16.045s  |  16.045s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_0ite_unsat.smt2                                                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_1ite_unsat.smt2                                                           |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_2ite_unsat.smt2                                                           |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_3ite_unsat.smt2                                                           |   0.620s  |   0.620s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_4ite_unsat.smt2                                                           |   1.636s  |   1.636s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_5ite_unsat.smt2                                                           |  15.447s  |  15.447s  |   0.000s  | 0.0%|
|ring_2exp16_7vars_6ite_unsat.smt2                                                           |  46.973s  |  46.973s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_0ite_unsat.smt2                                                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_1ite_unsat.smt2                                                           |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_2ite_unsat.smt2                                                           |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_3ite_unsat.smt2                                                           |   0.616s  |   0.616s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_4ite_unsat.smt2                                                           |   3.171s  |   3.171s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_5ite_unsat.smt2                                                           |  27.561s  |  27.561s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_6ite_unsat.smt2                                                           |  71.768s  |  71.768s  |   0.000s  | 0.0%|
|ring_2exp16_8vars_7ite_unsat.smt2                                                           | 121.431s  | 121.431s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_0ite_unsat.smt2                                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_1ite_unsat.smt2                                                           |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_2ite_unsat.smt2                                                           |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_3ite_unsat.smt2                                                           |   1.322s  |   1.322s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_4ite_unsat.smt2                                                           |  13.634s  |  13.634s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_5ite_unsat.smt2                                                           |  28.467s  |  28.467s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_6ite_unsat.smt2                                                           |  81.799s  |  81.799s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_7ite_unsat.smt2                                                           | 157.482s  | 157.482s  |   0.000s  | 0.0%|
|ring_2exp16_9vars_8ite_unsat.smt2                                                           | 599.935s  | 599.935s  |   0.000s  | 0.0%|
|ring_2exp4_3vars_0ite_unsat.smt2                                                            |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|ring_2exp4_3vars_1ite_unsat.smt2                                                            |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ring_2exp4_3vars_2ite_unsat.smt2                                                            |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|ring_2exp4_4vars_0ite_unsat.smt2                                                            |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|ring_2exp4_4vars_1ite_unsat.smt2                                                            |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|ring_2exp4_4vars_2ite_unsat.smt2                                                            |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|ring_2exp4_4vars_3ite_unsat.smt2                                                            |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_0ite_unsat.smt2                                                            |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_1ite_unsat.smt2                                                            |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_2ite_unsat.smt2                                                            |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_3ite_unsat.smt2                                                            |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|ring_2exp4_5vars_4ite_unsat.smt2                                                            |   1.707s  |   1.707s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_0ite_unsat.smt2                                                            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_1ite_unsat.smt2                                                            |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_2ite_unsat.smt2                                                            |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_3ite_unsat.smt2                                                            |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_4ite_unsat.smt2                                                            |   1.928s  |   1.928s  |   0.000s  | 0.0%|
|ring_2exp4_6vars_5ite_unsat.smt2                                                            |   2.576s  |   2.576s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_0ite_unsat.smt2                                                            |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_1ite_unsat.smt2                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_2ite_unsat.smt2                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_3ite_unsat.smt2                                                            |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_4ite_unsat.smt2                                                            |   1.469s  |   1.469s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_5ite_unsat.smt2                                                            |   3.799s  |   3.799s  |   0.000s  | 0.0%|
|ring_2exp4_7vars_6ite_unsat.smt2                                                            | 495.639s  | 495.639s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_0ite_unsat.smt2                                                            |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_1ite_unsat.smt2                                                            |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_2ite_unsat.smt2                                                            |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_3ite_unsat.smt2                                                            |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_4ite_unsat.smt2                                                            |   2.113s  |   2.113s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_5ite_unsat.smt2                                                            |  16.065s  |  16.065s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_6ite_unsat.smt2                                                            |  89.399s  |  89.399s  |   0.000s  | 0.0%|
|ring_2exp4_8vars_7ite_unsat.smt2                                                            | 166.669s  | 166.669s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_0ite_unsat.smt2                                                            |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_1ite_unsat.smt2                                                            |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_2ite_unsat.smt2                                                            |   0.690s  |   0.690s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_3ite_unsat.smt2                                                            |   0.932s  |   0.932s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_4ite_unsat.smt2                                                            |   2.668s  |   2.668s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_5ite_unsat.smt2                                                            |   4.827s  |   4.827s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_6ite_unsat.smt2                                                            | 599.941s  | 599.941s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_7ite_unsat.smt2                                                            | 298.197s  | 298.197s  |   0.000s  | 0.0%|
|ring_2exp4_9vars_8ite_unsat.smt2                                                            | 599.939s  | 599.939s  |   0.000s  | 0.0%|
|ring_2exp6_3vars_0ite_unsat.smt2                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ring_2exp6_3vars_1ite_unsat.smt2                                                            |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ring_2exp6_3vars_2ite_unsat.smt2                                                            |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ring_2exp6_4vars_0ite_unsat.smt2                                                            |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ring_2exp6_4vars_1ite_unsat.smt2                                                            |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|ring_2exp6_4vars_2ite_unsat.smt2                                                            |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|ring_2exp6_4vars_3ite_unsat.smt2                                                            |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_0ite_unsat.smt2                                                            |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_1ite_unsat.smt2                                                            |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_2ite_unsat.smt2                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_3ite_unsat.smt2                                                            |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|ring_2exp6_5vars_4ite_unsat.smt2                                                            |   2.311s  |   2.311s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_0ite_unsat.smt2                                                            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_1ite_unsat.smt2                                                            |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_2ite_unsat.smt2                                                            |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_3ite_unsat.smt2                                                            |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_4ite_unsat.smt2                                                            |  12.958s  |  12.958s  |   0.000s  | 0.0%|
|ring_2exp6_6vars_5ite_unsat.smt2                                                            |  21.949s  |  21.949s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_0ite_unsat.smt2                                                            |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_1ite_unsat.smt2                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_2ite_unsat.smt2                                                            |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_3ite_unsat.smt2                                                            |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_4ite_unsat.smt2                                                            |  16.346s  |  16.346s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_5ite_unsat.smt2                                                            |  16.375s  |  16.375s  |   0.000s  | 0.0%|
|ring_2exp6_7vars_6ite_unsat.smt2                                                            |  47.923s  |  47.923s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_0ite_unsat.smt2                                                            |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_1ite_unsat.smt2                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_2ite_unsat.smt2                                                            |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_3ite_unsat.smt2                                                            |   0.806s  |   0.806s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_4ite_unsat.smt2                                                            |   3.678s  |   3.678s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_5ite_unsat.smt2                                                            | 599.945s  | 599.945s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_6ite_unsat.smt2                                                            |  90.968s  |  90.968s  |   0.000s  | 0.0%|
|ring_2exp6_8vars_7ite_unsat.smt2                                                            | 599.921s  | 599.921s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_0ite_unsat.smt2                                                            |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_1ite_unsat.smt2                                                            |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_2ite_unsat.smt2                                                            |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_3ite_unsat.smt2                                                            |   2.101s  |   2.101s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_4ite_unsat.smt2                                                            |  11.387s  |  11.387s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_5ite_unsat.smt2                                                            |  28.571s  |  28.571s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_6ite_unsat.smt2                                                            |  69.499s  |  69.499s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_7ite_unsat.smt2                                                            | 599.944s  | 599.944s  |   0.000s  | 0.0%|
|ring_2exp6_9vars_8ite_unsat.smt2                                                            | 599.946s  | 599.946s  |   0.000s  | 0.0%|
|ring_2exp8_3vars_0ite_unsat.smt2                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ring_2exp8_3vars_1ite_unsat.smt2                                                            |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|ring_2exp8_3vars_2ite_unsat.smt2                                                            |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ring_2exp8_4vars_0ite_unsat.smt2                                                            |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|ring_2exp8_4vars_1ite_unsat.smt2                                                            |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|ring_2exp8_4vars_2ite_unsat.smt2                                                            |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|ring_2exp8_4vars_3ite_unsat.smt2                                                            |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_0ite_unsat.smt2                                                            |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_1ite_unsat.smt2                                                            |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_2ite_unsat.smt2                                                            |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_3ite_unsat.smt2                                                            |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|ring_2exp8_5vars_4ite_unsat.smt2                                                            |   1.156s  |   1.156s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_0ite_unsat.smt2                                                            |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_1ite_unsat.smt2                                                            |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_2ite_unsat.smt2                                                            |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_3ite_unsat.smt2                                                            |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_4ite_unsat.smt2                                                            |   3.234s  |   3.234s  |   0.000s  | 0.0%|
|ring_2exp8_6vars_5ite_unsat.smt2                                                            |  19.053s  |  19.053s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_0ite_unsat.smt2                                                            |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_1ite_unsat.smt2                                                            |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_2ite_unsat.smt2                                                            |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_3ite_unsat.smt2                                                            |   0.714s  |   0.714s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_4ite_unsat.smt2                                                            |  16.425s  |  16.425s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_5ite_unsat.smt2                                                            |  27.075s  |  27.075s  |   0.000s  | 0.0%|
|ring_2exp8_7vars_6ite_unsat.smt2                                                            |  47.891s  |  47.891s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_0ite_unsat.smt2                                                            |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_1ite_unsat.smt2                                                            |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_2ite_unsat.smt2                                                            |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_3ite_unsat.smt2                                                            |   2.397s  |   2.397s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_4ite_unsat.smt2                                                            |  13.975s  |  13.975s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_5ite_unsat.smt2                                                            |  21.020s  |  21.020s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_6ite_unsat.smt2                                                            |  73.440s  |  73.440s  |   0.000s  | 0.0%|
|ring_2exp8_8vars_7ite_unsat.smt2                                                            | 110.929s  | 110.929s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_0ite_unsat.smt2                                                            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_1ite_unsat.smt2                                                            |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_2ite_unsat.smt2                                                            |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_3ite_unsat.smt2                                                            |   1.760s  |   1.760s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_4ite_unsat.smt2                                                            |  26.428s  |  26.428s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_5ite_unsat.smt2                                                            |  28.623s  |  28.623s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_6ite_unsat.smt2                                                            |  78.176s  |  78.176s  |   0.000s  | 0.0%|
|ring_2exp8_9vars_7ite_unsat.smt2                                                            | 146.890s  | 146.890s  |   0.000s  | 0.0%|
</details>
