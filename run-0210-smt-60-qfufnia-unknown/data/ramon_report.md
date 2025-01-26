Comparing data and data


# SUMMARY
- LHS tests = 297
- RHS tests = 297
- LHS success = 297  (100.0%)
- RHS success = 297  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-60-qfufnia-unknown
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 04d0e9492b0066675c75fc5fb1df6b23b79607e5
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_UFNIA_UNKNOWN
Z3 commit message: set log level of revert repair down to 3

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-60-qfufnia-unknown
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 04d0e9492b0066675c75fc5fb1df6b23b79607e5
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_UFNIA_UNKNOWN
Z3 commit message: set log level of revert repair down to 3

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  59.877s  |  59.877s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  23.040s  |  23.040s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.028s  |  60.028s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.067s  |  60.067s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  48.400s  |  48.400s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  60.064s  |  60.064s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  59.914s  |  59.914s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   3.872s  |   3.872s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   1.805s  |   1.805s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  12.164s  |  12.164s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   3.006s  |   3.006s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.937s  |  59.937s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  59.877s  |  59.877s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  23.040s  |  23.040s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.028s  |  60.028s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.067s  |  60.067s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  48.400s  |  48.400s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  60.064s  |  60.064s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  59.914s  |  59.914s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   3.872s  |   3.872s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   1.805s  |   1.805s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  12.164s  |  12.164s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   3.006s  |   3.006s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.937s  |  59.937s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  59.877s  |  59.877s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  23.040s  |  23.040s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.028s  |  60.028s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.067s  |  60.067s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  48.400s  |  48.400s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  60.064s  |  60.064s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  59.914s  |  59.914s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   3.872s  |   3.872s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   1.805s  |   1.805s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  12.164s  |  12.164s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   3.006s  |   3.006s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.937s  |  59.937s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  59.877s  |  59.877s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  23.040s  |  23.040s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.028s  |  60.028s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.067s  |  60.067s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  48.400s  |  48.400s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  60.064s  |  60.064s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  59.914s  |  59.914s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   3.872s  |   3.872s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   1.805s  |   1.805s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  12.164s  |  12.164s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   3.006s  |   3.006s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.937s  |  59.937s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n114-0018.smt2                                                                             |  60.514s |106.0MiB|
|0063.smt2                                                                                  |  60.067s |1485.0MiB|
|0066.smt2                                                                                  |  60.064s |1921.0MiB|
|n43-0050.smt2                                                                              |  60.048s |852.0MiB|
|n29-0036.smt2                                                                              |  60.039s |1718.0MiB|
|0059.smt2                                                                                  |  60.028s |563.0MiB|
|n45-0052.smt2                                                                              |  60.027s |936.0MiB|
|n85-0039.smt2                                                                              |  60.021s |456.0MiB|
|n21-0027.smt2                                                                              |  60.020s |150.0MiB|
|n70-0024.smt2                                                                              |  60.020s |1046.0MiB|
|n39-0046.smt2                                                                              |  60.015s |1299.0MiB|
|0054.smt2                                                                                  |  60.013s |1406.0MiB|
|n95-0050.smt2                                                                              |  60.011s |642.0MiB|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                |  60.011s |497.0MiB|
|n42-0049.smt2                                                                              |  60.010s |169.0MiB|
|n136-0040.smt2                                                                             |  60.009s |353.0MiB|
|n8-0008.smt2                                                                               |  60.008s |198.0MiB|
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                                                |  60.007s |51.14MiB|
|n68-0022.smt2                                                                              |  60.007s |170.0MiB|
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                                                    |  60.005s |221.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n114-0018.smt2                                                                             |  60.514s |106.0MiB|
|0063.smt2                                                                                  |  60.067s |1485.0MiB|
|0066.smt2                                                                                  |  60.064s |1921.0MiB|
|n43-0050.smt2                                                                              |  60.048s |852.0MiB|
|n29-0036.smt2                                                                              |  60.039s |1718.0MiB|
|0059.smt2                                                                                  |  60.028s |563.0MiB|
|n45-0052.smt2                                                                              |  60.027s |936.0MiB|
|n85-0039.smt2                                                                              |  60.021s |456.0MiB|
|n21-0027.smt2                                                                              |  60.020s |150.0MiB|
|n70-0024.smt2                                                                              |  60.020s |1046.0MiB|
|n39-0046.smt2                                                                              |  60.015s |1299.0MiB|
|0054.smt2                                                                                  |  60.013s |1406.0MiB|
|n95-0050.smt2                                                                              |  60.011s |642.0MiB|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                |  60.011s |497.0MiB|
|n42-0049.smt2                                                                              |  60.010s |169.0MiB|
|n136-0040.smt2                                                                             |  60.009s |353.0MiB|
|n8-0008.smt2                                                                               |  60.008s |198.0MiB|
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                                                |  60.007s |51.14MiB|
|n68-0022.smt2                                                                              |  60.007s |170.0MiB|
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                                                    |  60.005s |221.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1406.0MiB|1406.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1407.0MiB|1407.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |180.0MiB|180.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |115.0MiB|115.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |520.0MiB|520.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |563.0MiB|563.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |144.0MiB|144.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |163.0MiB|163.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2700.0MiB|2700.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |1485.0MiB|1485.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |377.0MiB|377.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |202.0MiB|202.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |1921.0MiB|1921.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |295.0MiB|295.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |32.48MiB|32.48MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |26.38MiB|26.38MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.06MiB|23.06MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |40.108MiB|40.108MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |31.532MiB|31.532MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |103.0MiB|103.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1406.0MiB|1406.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1407.0MiB|1407.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |180.0MiB|180.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |115.0MiB|115.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |520.0MiB|520.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |563.0MiB|563.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |144.0MiB|144.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |163.0MiB|163.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2700.0MiB|2700.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |1485.0MiB|1485.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |377.0MiB|377.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |202.0MiB|202.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |1921.0MiB|1921.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |295.0MiB|295.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |32.48MiB|32.48MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |26.38MiB|26.38MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.06MiB|23.06MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |40.108MiB|40.108MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |31.532MiB|31.532MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |103.0MiB|103.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1406.0MiB|1406.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1407.0MiB|1407.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |180.0MiB|180.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |115.0MiB|115.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |520.0MiB|520.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |563.0MiB|563.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |144.0MiB|144.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |163.0MiB|163.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2700.0MiB|2700.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |1485.0MiB|1485.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |377.0MiB|377.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |202.0MiB|202.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |1921.0MiB|1921.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |295.0MiB|295.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |32.48MiB|32.48MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |26.38MiB|26.38MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.06MiB|23.06MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |40.108MiB|40.108MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |31.532MiB|31.532MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |103.0MiB|103.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1406.0MiB|1406.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1407.0MiB|1407.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |180.0MiB|180.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |115.0MiB|115.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |520.0MiB|520.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |563.0MiB|563.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |144.0MiB|144.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |163.0MiB|163.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2700.0MiB|2700.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |1485.0MiB|1485.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |377.0MiB|377.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |202.0MiB|202.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |1921.0MiB|1921.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |295.0MiB|295.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |32.48MiB|32.48MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |26.38MiB|26.38MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.06MiB|23.06MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |40.108MiB|40.108MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |31.532MiB|31.532MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |103.0MiB|103.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|0062.smt2                                                                                  |  60.003s |2700.0MiB|
|0066.smt2                                                                                  |  60.064s |1921.0MiB|
|n29-0036.smt2                                                                              |  60.039s |1718.0MiB|
|0063.smt2                                                                                  |  60.067s |1485.0MiB|
|0055.smt2                                                                                  |  59.877s |1407.0MiB|
|0054.smt2                                                                                  |  60.013s |1406.0MiB|
|n39-0046.smt2                                                                              |  60.015s |1299.0MiB|
|n70-0024.smt2                                                                              |  60.020s |1046.0MiB|
|n76-0030.smt2                                                                              |  59.980s |1041.0MiB|
|n71-0025.smt2                                                                              |  59.943s |1028.0MiB|
|n45-0052.smt2                                                                              |  60.027s |936.0MiB|
|n43-0050.smt2                                                                              |  60.048s |852.0MiB|
|n1-0001.smt2                                                                               |   9.834s |774.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  59.962s |686.0MiB|
|n95-0050.smt2                                                                              |  60.011s |642.0MiB|
|n111-0015.smt2                                                                             |  59.981s |589.0MiB|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                |  30.643s |588.0MiB|
|n20-0026.smt2                                                                              |  59.854s |572.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                |  58.966s |572.0MiB|
|0059.smt2                                                                                  |  60.028s |563.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|0062.smt2                                                                                  |  60.003s |2700.0MiB|
|0066.smt2                                                                                  |  60.064s |1921.0MiB|
|n29-0036.smt2                                                                              |  60.039s |1718.0MiB|
|0063.smt2                                                                                  |  60.067s |1485.0MiB|
|0055.smt2                                                                                  |  59.877s |1407.0MiB|
|0054.smt2                                                                                  |  60.013s |1406.0MiB|
|n39-0046.smt2                                                                              |  60.015s |1299.0MiB|
|n70-0024.smt2                                                                              |  60.020s |1046.0MiB|
|n76-0030.smt2                                                                              |  59.980s |1041.0MiB|
|n71-0025.smt2                                                                              |  59.943s |1028.0MiB|
|n45-0052.smt2                                                                              |  60.027s |936.0MiB|
|n43-0050.smt2                                                                              |  60.048s |852.0MiB|
|n1-0001.smt2                                                                               |   9.834s |774.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  59.962s |686.0MiB|
|n95-0050.smt2                                                                              |  60.011s |642.0MiB|
|n111-0015.smt2                                                                             |  59.981s |589.0MiB|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                |  30.643s |588.0MiB|
|n20-0026.smt2                                                                              |  59.854s |572.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                |  58.966s |572.0MiB|
|0059.smt2                                                                                  |  60.028s |563.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  59.877s  |  59.877s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  23.040s  |  23.040s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.028s  |  60.028s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.067s  |  60.067s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  48.400s  |  48.400s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  60.064s  |  60.064s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  59.914s  |  59.914s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   3.872s  |   3.872s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   1.805s  |   1.805s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  12.164s  |  12.164s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   3.006s  |   3.006s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2                                     |  59.890s  |  59.890s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2                                     |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                     |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2                                     |   5.978s  |   5.978s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                  |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                                                  |  13.987s  |  13.987s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                                                  |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                                                  |   1.523s  |   1.523s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2                                      |  26.391s  |  26.391s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                                                 |   7.030s  |   7.030s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                                                 |   3.323s  |   3.323s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                                                 |  59.958s  |  59.958s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                                                 |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                 |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                                                 |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                                                 |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                                                 |   9.295s  |   9.295s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                                                 |   1.615s  |   1.615s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                                                 |   3.385s  |   3.385s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                                                 |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                                                 |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                                                 |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                                                 |   1.432s  |   1.432s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                                                 |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                                                 |   4.924s  |   4.924s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                 |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2                                     |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                                                 |   3.870s  |   3.870s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                                                 |   6.458s  |   6.458s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                                                 |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                                                 |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                                                 |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2                                     |  12.853s  |  12.853s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2                                     |  14.138s  |  14.138s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                     |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2                                     |  59.700s  |  59.700s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                                                 |  10.620s  |  10.620s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                                                 |   8.702s  |   8.702s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                                                 |  26.702s  |  26.702s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                                                 |  43.061s  |  43.061s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2                                        |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                  |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                                                  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                                                  |  59.156s  |  59.156s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                                                  |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                 |  30.643s  |  30.643s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                 |  58.966s  |  58.966s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                                                 |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                                                 |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                                                 |  13.708s  |  13.708s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                                                     |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                                                     |   4.285s  |   4.285s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                                                     |  59.928s  |  59.928s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                                                     |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                                                     |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2                                     |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2                                     |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2                                     |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                                                 |  59.871s  |  59.871s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                                                   |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                                                   |  28.760s  |  28.760s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                                                   |   2.659s  |   2.659s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                                                   |   9.312s  |   9.312s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                                                   |  25.211s  |  25.211s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr1_rtl.smt2                                                            |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_ltr_inv_g.smt2                                                      |   0.510s  |   0.510s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_rtl.smt2                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|int_check_bvsge_bvneg_ltr_inv_g.smt2                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvsge_bvudiv1_rtl.smt2                                                            |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem1_ltr_inv_g.smt2                                                      |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_rtl.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr0_rtl.smt2                                                            |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr1_ltr_inv_g.smt2                                                      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr0_rtl.smt2                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr1_rtl.smt2                                                            |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvshl0_ltr_inv_g.smt2                                                       |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvshl0_rtl.smt2                                                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem0_rtl.smt2                                                            |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem1_rtl.smt2                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|int_check_bvsle_bvadd_ltr_inv_g.smt2                                                        |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr0_ltr_inv_g.smt2                                                      |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr0_rtl.smt2                                                            |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr1_rtl.smt2                                                            |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl0_ltr_inv_g.smt2                                                       |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv0_rtl.smt2                                                            |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_ltr_inv_g.smt2                                                      |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr0_rtl.smt2                                                            |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr1_rtl.smt2                                                            |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr0_ltr_inv_g.smt2                                                      |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr0_rtl.smt2                                                            |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv0_ltr_inv_g.smt2                                                      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr1_ltr_inv_g.smt2                                                      |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr1_rtl.smt2                                                            |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|int_check_bvuge_bvshl0_rtl.smt2                                                             |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem0_rtl.smt2                                                            |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr0_ltr_inv_g.smt2                                                      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr1_ltr_inv_g.smt2                                                      |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr1_rtl.smt2                                                            |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|int_check_bvugt_bvudiv0_rtl.smt2                                                            |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|int_check_bvugt_bvudiv1_rtl.smt2                                                            |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|int_check_bvugt_bvurem0_rtl.smt2                                                            |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|int_check_bvule_bvneg_ltr_inv_g.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv1_ltr_inv_g.smt2                                                      |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvule_bvurem0_ltr_inv_g.smt2                                                      |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvule_bvurem1_ltr_inv_g.smt2                                                      |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr1_rtl.smt2                                                            |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|int_check_bvult_bvneg_ltr_inv_g.smt2                                                        |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvult_bvurem0_ltr_inv_g.smt2                                                      |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvult_bvurem1_ltr_inv_g.smt2                                                      |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_eq_bvashr0_rtl.smt2                                                               |   2.178s  |   2.178s  |   0.000s  | 0.0%|
|int_check_eq_bvlshr0_rtl.smt2                                                               |  59.788s  |  59.788s  |   0.000s  | 0.0%|
|int_check_eq_bvudiv0_rtl.smt2                                                               |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_eq_bvudiv1_rtl.smt2                                                               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|int_check_eq_bvurem0_ltr_inv_g.smt2                                                         |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_eq_bvurem0_rtl.smt2                                                               |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|int_check_ne_bvashr0_ltr_inv_g.smt2                                                         |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_ltr_inv_g.smt2                                                         |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|n0-0000.smt2                                                                                |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|n1-0001.smt2                                                                                |   9.834s  |   9.834s  |   0.000s  | 0.0%|
|n10-0010.smt2                                                                               |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|n100-0003.smt2                                                                              |  10.922s  |  10.922s  |   0.000s  | 0.0%|
|n101-0004.smt2                                                                              |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|n102-0005.smt2                                                                              |   1.269s  |   1.269s  |   0.000s  | 0.0%|
|n103-0006.smt2                                                                              |  59.880s  |  59.880s  |   0.000s  | 0.0%|
|n104-0007.smt2                                                                              |   2.015s  |   2.015s  |   0.000s  | 0.0%|
|n105-0008.smt2                                                                              |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|n106-0009.smt2                                                                              |   0.922s  |   0.922s  |   0.000s  | 0.0%|
|n107-0011.smt2                                                                              |  15.462s  |  15.462s  |   0.000s  | 0.0%|
|n108-0012.smt2                                                                              |   2.169s  |   2.169s  |   0.000s  | 0.0%|
|n109-0013.smt2                                                                              |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|n11-0012.smt2                                                                               |  10.509s  |  10.509s  |   0.000s  | 0.0%|
|n110-0014.smt2                                                                              |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|n111-0015.smt2                                                                              |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|n112-0016.smt2                                                                              |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|n113-0017.smt2                                                                              |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|n114-0018.smt2                                                                              |  60.514s  |  60.514s  |   0.000s  | 0.0%|
|n115-0019.smt2                                                                              |  59.894s  |  59.894s  |   0.000s  | 0.0%|
|n116-0020.smt2                                                                              |  59.932s  |  59.932s  |   0.000s  | 0.0%|
|n117-0021.smt2                                                                              |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|n118-0022.smt2                                                                              |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|n119-0023.smt2                                                                              |   8.634s  |   8.634s  |   0.000s  | 0.0%|
|n12-0013.smt2                                                                               |   4.250s  |   4.250s  |   0.000s  | 0.0%|
|n120-0024.smt2                                                                              |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|n121-0025.smt2                                                                              |  59.777s  |  59.777s  |   0.000s  | 0.0%|
|n122-0026.smt2                                                                              |  59.890s  |  59.890s  |   0.000s  | 0.0%|
|n123-0027.smt2                                                                              |  59.840s  |  59.840s  |   0.000s  | 0.0%|
|n124-0028.smt2                                                                              |  29.900s  |  29.900s  |   0.000s  | 0.0%|
|n125-0029.smt2                                                                              |   8.357s  |   8.357s  |   0.000s  | 0.0%|
|n126-0030.smt2                                                                              |  26.260s  |  26.260s  |   0.000s  | 0.0%|
|n127-0031.smt2                                                                              |   2.350s  |   2.350s  |   0.000s  | 0.0%|
|n128-0032.smt2                                                                              |   1.515s  |   1.515s  |   0.000s  | 0.0%|
|n129-0033.smt2                                                                              |   1.667s  |   1.667s  |   0.000s  | 0.0%|
|n13-0015.smt2                                                                               |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|n130-0034.smt2                                                                              |  59.879s  |  59.879s  |   0.000s  | 0.0%|
|n131-0035.smt2                                                                              |   0.806s  |   0.806s  |   0.000s  | 0.0%|
|n132-0036.smt2                                                                              |   1.323s  |   1.323s  |   0.000s  | 0.0%|
|n133-0037.smt2                                                                              |  11.029s  |  11.029s  |   0.000s  | 0.0%|
|n134-0038.smt2                                                                              |   5.550s  |   5.550s  |   0.000s  | 0.0%|
|n135-0039.smt2                                                                              |  12.310s  |  12.310s  |   0.000s  | 0.0%|
|n136-0040.smt2                                                                              |  60.009s  |  60.009s  |   0.000s  | 0.0%|
|n137-0041.smt2                                                                              |   1.919s  |   1.919s  |   0.000s  | 0.0%|
|n16-0019.smt2                                                                               |  59.842s  |  59.842s  |   0.000s  | 0.0%|
|n17-0021.smt2                                                                               |   2.375s  |   2.375s  |   0.000s  | 0.0%|
|n18-0022.smt2                                                                               |   3.231s  |   3.231s  |   0.000s  | 0.0%|
|n19-0024.smt2                                                                               |  50.117s  |  50.117s  |   0.000s  | 0.0%|
|n2-0002.smt2                                                                                |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|n20-0026.smt2                                                                               |  59.854s  |  59.854s  |   0.000s  | 0.0%|
|n21-0027.smt2                                                                               |  60.020s  |  60.020s  |   0.000s  | 0.0%|
|n22-0029.smt2                                                                               |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|n23-0030.smt2                                                                               |  59.798s  |  59.798s  |   0.000s  | 0.0%|
|n24-0031.smt2                                                                               |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|n25-0032.smt2                                                                               |  22.115s  |  22.115s  |   0.000s  | 0.0%|
|n26-0033.smt2                                                                               |   5.532s  |   5.532s  |   0.000s  | 0.0%|
|n27-0034.smt2                                                                               |   4.717s  |   4.717s  |   0.000s  | 0.0%|
|n28-0035.smt2                                                                               |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|n29-0036.smt2                                                                               |  60.039s  |  60.039s  |   0.000s  | 0.0%|
|n3-0003.smt2                                                                                |  59.425s  |  59.425s  |   0.000s  | 0.0%|
|n30-0037.smt2                                                                               |   4.086s  |   4.086s  |   0.000s  | 0.0%|
|n31-0038.smt2                                                                               |  10.765s  |  10.765s  |   0.000s  | 0.0%|
|n32-0039.smt2                                                                               |  59.877s  |  59.877s  |   0.000s  | 0.0%|
|n33-0040.smt2                                                                               |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|n34-0041.smt2                                                                               |  11.699s  |  11.699s  |   0.000s  | 0.0%|
|n35-0042.smt2                                                                               |  13.130s  |  13.130s  |   0.000s  | 0.0%|
|n36-0043.smt2                                                                               |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|n37-0044.smt2                                                                               |   6.551s  |   6.551s  |   0.000s  | 0.0%|
|n38-0045.smt2                                                                               |  12.065s  |  12.065s  |   0.000s  | 0.0%|
|n39-0046.smt2                                                                               |  60.015s  |  60.015s  |   0.000s  | 0.0%|
|n4-0004.smt2                                                                                |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|n40-0047.smt2                                                                               |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|n41-0048.smt2                                                                               |   6.495s  |   6.495s  |   0.000s  | 0.0%|
|n42-0049.smt2                                                                               |  60.010s  |  60.010s  |   0.000s  | 0.0%|
|n43-0050.smt2                                                                               |  60.048s  |  60.048s  |   0.000s  | 0.0%|
|n44-0051.smt2                                                                               |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|n45-0052.smt2                                                                               |  60.027s  |  60.027s  |   0.000s  | 0.0%|
|n46-0053.smt2                                                                               |  19.315s  |  19.315s  |   0.000s  | 0.0%|
|n47-0000.smt2                                                                               |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|n48-0001.smt2                                                                               |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|n49-0002.smt2                                                                               |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|n5-0005.smt2                                                                                |   6.963s  |   6.963s  |   0.000s  | 0.0%|
|n50-0003.smt2                                                                               |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|n51-0004.smt2                                                                               |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|n52-0005.smt2                                                                               |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|n53-0006.smt2                                                                               |   5.833s  |   5.833s  |   0.000s  | 0.0%|
|n54-0007.smt2                                                                               |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|n55-0008.smt2                                                                               |  59.903s  |  59.903s  |   0.000s  | 0.0%|
|n56-0009.smt2                                                                               |   9.234s  |   9.234s  |   0.000s  | 0.0%|
|n57-0010.smt2                                                                               |   7.255s  |   7.255s  |   0.000s  | 0.0%|
|n58-0011.smt2                                                                               |  11.315s  |  11.315s  |   0.000s  | 0.0%|
|n59-0012.smt2                                                                               |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|n6-0006.smt2                                                                                |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|n60-0014.smt2                                                                               |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|n61-0015.smt2                                                                               |   9.282s  |   9.282s  |   0.000s  | 0.0%|
|n62-0016.smt2                                                                               |  59.908s  |  59.908s  |   0.000s  | 0.0%|
|n63-0017.smt2                                                                               |  59.783s  |  59.783s  |   0.000s  | 0.0%|
|n64-0018.smt2                                                                               |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|n65-0019.smt2                                                                               |   1.345s  |   1.345s  |   0.000s  | 0.0%|
|n66-0020.smt2                                                                               |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|n67-0021.smt2                                                                               |  59.828s  |  59.828s  |   0.000s  | 0.0%|
|n68-0022.smt2                                                                               |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|n69-0023.smt2                                                                               |  59.927s  |  59.927s  |   0.000s  | 0.0%|
|n7-0007.smt2                                                                                |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|n70-0024.smt2                                                                               |  60.020s  |  60.020s  |   0.000s  | 0.0%|
|n71-0025.smt2                                                                               |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|n72-0026.smt2                                                                               |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|n73-0027.smt2                                                                               |  10.340s  |  10.340s  |   0.000s  | 0.0%|
|n74-0028.smt2                                                                               |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|n75-0029.smt2                                                                               |  59.873s  |  59.873s  |   0.000s  | 0.0%|
|n76-0030.smt2                                                                               |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|n77-0031.smt2                                                                               |  59.875s  |  59.875s  |   0.000s  | 0.0%|
|n78-0032.smt2                                                                               |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|n79-0033.smt2                                                                               |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|n8-0008.smt2                                                                                |  60.008s  |  60.008s  |   0.000s  | 0.0%|
|n80-0034.smt2                                                                               |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|n81-0035.smt2                                                                               |  59.841s  |  59.841s  |   0.000s  | 0.0%|
|n82-0036.smt2                                                                               |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|n83-0037.smt2                                                                               |  59.932s  |  59.932s  |   0.000s  | 0.0%|
|n84-0038.smt2                                                                               |  59.894s  |  59.894s  |   0.000s  | 0.0%|
|n85-0039.smt2                                                                               |  60.021s  |  60.021s  |   0.000s  | 0.0%|
|n86-0040.smt2                                                                               |   0.545s  |   0.545s  |   0.000s  | 0.0%|
|n87-0041.smt2                                                                               |  59.921s  |  59.921s  |   0.000s  | 0.0%|
|n88-0042.smt2                                                                               |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|n89-0044.smt2                                                                               |  37.317s  |  37.317s  |   0.000s  | 0.0%|
|n9-0009.smt2                                                                                |   9.277s  |   9.277s  |   0.000s  | 0.0%|
|n90-0045.smt2                                                                               |   2.739s  |   2.739s  |   0.000s  | 0.0%|
|n91-0046.smt2                                                                               |  12.253s  |  12.253s  |   0.000s  | 0.0%|
|n92-0047.smt2                                                                               |   1.168s  |   1.168s  |   0.000s  | 0.0%|
|n93-0048.smt2                                                                               |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|n94-0049.smt2                                                                               |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|n95-0050.smt2                                                                               |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|n96-0051.smt2                                                                               |   8.267s  |   8.267s  |   0.000s  | 0.0%|
|n97-0000.smt2                                                                               |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|n98-0001.smt2                                                                               |  59.660s  |  59.660s  |   0.000s  | 0.0%|
|n99-0002.smt2                                                                               |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|qf_AddSub_1165_values_0.smt2                                                                |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|qf_AddSub_1574_values_0.smt2                                                                |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|qf_AddSub_1619_values_0.smt2                                                                |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|qf_AndOrXor_1869_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_1894_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_210_values_0.smt2                                                               |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|qf_AndOrXor_230_values_0.smt2                                                               |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|qf_AndOrXor_2443_values_0.smt2                                                              |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|qf_AndOrXor_290_values_7.smt2                                                               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|qf_AndOrXor_794_values_121.smt2                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_InstCombineShift497a_values_0.smt2                                                       |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|qf_InstCombineShift497b_values_0.smt2                                                       |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|qf_InstCombineShift497c_values_0.smt2                                                       |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|qf_InstCombineShift497d_values_0.smt2                                                       |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|qf_Select_510_values_0.smt2                                                                 |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|qf_Select_575a_values_0.smt2                                                                |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|qf_Select_575b_values_0.smt2                                                                |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|qf_Select_700_values_123.smt2                                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_Select_705_values_0.smt2                                                                 |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_Select_727_values_0.smt2                                                                 |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_muldivrem_152_values_0.smt2                                                              |   9.853s  |   9.853s  |   0.000s  | 0.0%|
|qf_muldivrem_229_values_0.smt2                                                              |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|qf_muldivrem_239_values_0.smt2                                                              |  59.962s  |  59.962s  |   0.000s  | 0.0%|
</details>
