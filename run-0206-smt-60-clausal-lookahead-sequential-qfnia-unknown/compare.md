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
Job tag: smt-60-clausal-lookahead-sequential-qfnia-unknown
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 04d0e9492b0066675c75fc5fb1df6b23b79607e5
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_UNKNOWN
Z3 commit message: set log level of revert repair down to 3

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-60-clausal-lookahead-sequential-qfnia-unknown
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 04d0e9492b0066675c75fc5fb1df6b23b79607e5
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_UNKNOWN
Z3 commit message: set log level of revert repair down to 3

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  60.022s  |  60.022s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.902s  |  59.902s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.040s  |  60.040s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  59.784s  |  59.784s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.054s  |  60.054s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.778s  |  59.778s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  60.084s  |  60.084s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   0.984s  |   0.984s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   6.210s  |   6.210s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  30.236s  |  30.236s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.801s  |  59.801s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  60.022s  |  60.022s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.902s  |  59.902s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.040s  |  60.040s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  59.784s  |  59.784s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.054s  |  60.054s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.778s  |  59.778s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  60.084s  |  60.084s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   0.984s  |   0.984s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   6.210s  |   6.210s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  30.236s  |  30.236s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.801s  |  59.801s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  60.022s  |  60.022s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.902s  |  59.902s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.040s  |  60.040s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  59.784s  |  59.784s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.054s  |  60.054s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.778s  |  59.778s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  60.084s  |  60.084s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   0.984s  |   0.984s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   6.210s  |   6.210s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  30.236s  |  30.236s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.801s  |  59.801s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  60.022s  |  60.022s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.902s  |  59.902s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.040s  |  60.040s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  59.784s  |  59.784s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.054s  |  60.054s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.778s  |  59.778s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  60.084s  |  60.084s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   0.984s  |   0.984s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   6.210s  |   6.210s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  30.236s  |  30.236s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.801s  |  59.801s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n76-0030.smt2                                                                              |  62.054s |1040.0MiB|
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                                                    |  60.347s |102.0MiB|
|0066.smt2                                                                                  |  60.084s |2943.0MiB|
|0063.smt2                                                                                  |  60.054s |2095.0MiB|
|n39-0046.smt2                                                                              |  60.052s |1694.0MiB|
|0059.smt2                                                                                  |  60.040s |808.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  60.034s |999.0MiB|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                    |  60.034s |397.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                |  60.030s |779.0MiB|
|n52-0005.smt2                                                                              |  60.025s |87.308MiB|
|0055.smt2                                                                                  |  60.022s |1406.0MiB|
|n29-0036.smt2                                                                              |  60.021s |1719.0MiB|
|n94-0049.smt2                                                                              |  60.019s |273.0MiB|
|n24-0031.smt2                                                                              |  60.018s |343.0MiB|
|n112-0016.smt2                                                                             |  60.018s |804.0MiB|
|n116-0020.smt2                                                                             |  60.018s |774.0MiB|
|n79-0033.smt2                                                                              |  60.012s |350.0MiB|
|0067.smt2                                                                                  |  60.012s |460.0MiB|
|n8-0008.smt2                                                                               |  60.010s |294.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                |  60.010s |356.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n76-0030.smt2                                                                              |  62.054s |1040.0MiB|
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                                                    |  60.347s |102.0MiB|
|0066.smt2                                                                                  |  60.084s |2943.0MiB|
|0063.smt2                                                                                  |  60.054s |2095.0MiB|
|n39-0046.smt2                                                                              |  60.052s |1694.0MiB|
|0059.smt2                                                                                  |  60.040s |808.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  60.034s |999.0MiB|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                    |  60.034s |397.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                |  60.030s |779.0MiB|
|n52-0005.smt2                                                                              |  60.025s |87.308MiB|
|0055.smt2                                                                                  |  60.022s |1406.0MiB|
|n29-0036.smt2                                                                              |  60.021s |1719.0MiB|
|n94-0049.smt2                                                                              |  60.019s |273.0MiB|
|n24-0031.smt2                                                                              |  60.018s |343.0MiB|
|n112-0016.smt2                                                                             |  60.018s |804.0MiB|
|n116-0020.smt2                                                                             |  60.018s |774.0MiB|
|n79-0033.smt2                                                                              |  60.012s |350.0MiB|
|0067.smt2                                                                                  |  60.012s |460.0MiB|
|n8-0008.smt2                                                                               |  60.010s |294.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                |  60.010s |356.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1407.0MiB|1407.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1406.0MiB|1406.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |326.0MiB|326.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |197.0MiB|197.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |797.0MiB|797.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |808.0MiB|808.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |202.0MiB|202.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |199.0MiB|199.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2698.0MiB|2698.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2095.0MiB|2095.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |574.0MiB|574.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |225.0MiB|225.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2943.0MiB|2943.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |460.0MiB|460.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |73.584MiB|73.584MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.368MiB|67.368MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |56.8MiB|56.8MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |80.328MiB|80.328MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |74.116MiB|74.116MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |145.0MiB|145.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1407.0MiB|1407.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1406.0MiB|1406.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |326.0MiB|326.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |197.0MiB|197.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |797.0MiB|797.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |808.0MiB|808.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |202.0MiB|202.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |199.0MiB|199.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2698.0MiB|2698.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2095.0MiB|2095.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |574.0MiB|574.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |225.0MiB|225.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2943.0MiB|2943.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |460.0MiB|460.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |73.584MiB|73.584MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.368MiB|67.368MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |56.8MiB|56.8MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |80.328MiB|80.328MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |74.116MiB|74.116MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |145.0MiB|145.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1407.0MiB|1407.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1406.0MiB|1406.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |326.0MiB|326.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |197.0MiB|197.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |797.0MiB|797.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |808.0MiB|808.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |202.0MiB|202.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |199.0MiB|199.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2698.0MiB|2698.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2095.0MiB|2095.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |574.0MiB|574.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |225.0MiB|225.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2943.0MiB|2943.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |460.0MiB|460.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |73.584MiB|73.584MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.368MiB|67.368MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |56.8MiB|56.8MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |80.328MiB|80.328MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |74.116MiB|74.116MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |145.0MiB|145.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1407.0MiB|1407.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1406.0MiB|1406.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |326.0MiB|326.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |197.0MiB|197.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |797.0MiB|797.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |808.0MiB|808.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |202.0MiB|202.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |199.0MiB|199.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2698.0MiB|2698.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2095.0MiB|2095.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |574.0MiB|574.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |225.0MiB|225.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2943.0MiB|2943.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |460.0MiB|460.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |73.584MiB|73.584MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.368MiB|67.368MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |56.8MiB|56.8MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |80.328MiB|80.328MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |74.116MiB|74.116MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |145.0MiB|145.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|0066.smt2                                                                                  |  60.084s |2943.0MiB|
|0062.smt2                                                                                  |  59.784s |2698.0MiB|
|0063.smt2                                                                                  |  60.054s |2095.0MiB|
|n29-0036.smt2                                                                              |  60.021s |1719.0MiB|
|n39-0046.smt2                                                                              |  60.052s |1694.0MiB|
|0054.smt2                                                                                  |  60.007s |1407.0MiB|
|0055.smt2                                                                                  |  60.022s |1406.0MiB|
|n45-0052.smt2                                                                              |  59.955s |1307.0MiB|
|n1-0001.smt2                                                                               |  11.513s |1128.0MiB|
|n43-0050.smt2                                                                              |  59.979s |1115.0MiB|
|n70-0024.smt2                                                                              |  59.984s |1047.0MiB|
|n76-0030.smt2                                                                              |  62.054s |1040.0MiB|
|n71-0025.smt2                                                                              |  59.984s |1030.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  60.034s |999.0MiB|
|n111-0015.smt2                                                                             |  59.977s |917.0MiB|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                |  27.915s |845.0MiB|
|n95-0050.smt2                                                                              |  59.999s |843.0MiB|
|n20-0026.smt2                                                                              |  59.975s |820.0MiB|
|0059.smt2                                                                                  |  60.040s |808.0MiB|
|n112-0016.smt2                                                                             |  60.018s |804.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|0066.smt2                                                                                  |  60.084s |2943.0MiB|
|0062.smt2                                                                                  |  59.784s |2698.0MiB|
|0063.smt2                                                                                  |  60.054s |2095.0MiB|
|n29-0036.smt2                                                                              |  60.021s |1719.0MiB|
|n39-0046.smt2                                                                              |  60.052s |1694.0MiB|
|0054.smt2                                                                                  |  60.007s |1407.0MiB|
|0055.smt2                                                                                  |  60.022s |1406.0MiB|
|n45-0052.smt2                                                                              |  59.955s |1307.0MiB|
|n1-0001.smt2                                                                               |  11.513s |1128.0MiB|
|n43-0050.smt2                                                                              |  59.979s |1115.0MiB|
|n70-0024.smt2                                                                              |  59.984s |1047.0MiB|
|n76-0030.smt2                                                                              |  62.054s |1040.0MiB|
|n71-0025.smt2                                                                              |  59.984s |1030.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  60.034s |999.0MiB|
|n111-0015.smt2                                                                             |  59.977s |917.0MiB|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                |  27.915s |845.0MiB|
|n95-0050.smt2                                                                              |  59.999s |843.0MiB|
|n20-0026.smt2                                                                              |  59.975s |820.0MiB|
|0059.smt2                                                                                  |  60.040s |808.0MiB|
|n112-0016.smt2                                                                             |  60.018s |804.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  60.022s  |  60.022s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.902s  |  59.902s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.040s  |  60.040s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  59.784s  |  59.784s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.054s  |  60.054s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.778s  |  59.778s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  60.084s  |  60.084s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   0.984s  |   0.984s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   6.210s  |   6.210s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  30.236s  |  30.236s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.801s  |  59.801s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2                                     |   4.592s  |   4.592s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2                                     |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                     |  59.922s  |  59.922s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2                                     |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                  |  60.034s  |  60.034s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                                                  |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                                                  |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                                                  |   1.731s  |   1.731s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2                                      |  24.317s  |  24.317s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                                                 |  59.903s  |  59.903s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                                                 |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                                                 |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                                                 |   2.369s  |   2.369s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                 |  60.010s  |  60.010s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                                                 |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                                                 |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                                                 |   9.723s  |   9.723s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                                                 |  15.547s  |  15.547s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                                                 |   1.535s  |   1.535s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                                                 |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                                                 |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                                                 |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                                                 |   1.696s  |   1.696s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                                                 |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                                                 |  10.063s  |  10.063s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                 |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2                                     |  41.897s  |  41.897s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                                                 |   4.090s  |   4.090s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                                                 |   7.267s  |   7.267s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                                                 |  59.880s  |  59.880s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                                                 |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                                                 |  59.893s  |  59.893s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2                                     |   5.452s  |   5.452s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2                                     |   4.393s  |   4.393s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                     |  60.034s  |  60.034s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2                                     |  57.339s  |  57.339s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                                                 |  10.853s  |  10.853s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                                                 |   9.574s  |   9.574s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                                                 |  41.450s  |  41.450s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                                                 |  58.824s  |  58.824s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2                                        |   1.058s  |   1.058s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                  |  59.841s  |  59.841s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                                                  |   1.777s  |   1.777s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                                                  |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                                                  |   2.280s  |   2.280s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                 |  27.915s  |  27.915s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                 |  60.030s  |  60.030s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                                                 |   3.077s  |   3.077s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                                                 |  59.917s  |  59.917s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                                                 |   5.050s  |   5.050s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                                                     |   1.159s  |   1.159s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                                                     |  59.887s  |  59.887s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                                                     |  59.907s  |  59.907s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                                                     |  60.347s  |  60.347s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                                                     |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2                                     |  57.346s  |  57.346s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2                                     |  34.448s  |  34.448s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2                                     |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                                                 |  21.687s  |  21.687s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                                                   |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                                                   |  25.360s  |  25.360s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                                                   |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                                                   |   9.671s  |   9.671s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                                                   |  59.647s  |  59.647s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr1_rtl.smt2                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_ltr_inv_g.smt2                                                      |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_rtl.smt2                                                            |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|int_check_bvsge_bvneg_ltr_inv_g.smt2                                                        |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|int_check_bvsge_bvudiv1_rtl.smt2                                                            |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem1_ltr_inv_g.smt2                                                      |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_rtl.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr0_rtl.smt2                                                            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr1_ltr_inv_g.smt2                                                      |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr0_rtl.smt2                                                            |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr1_rtl.smt2                                                            |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvshl0_ltr_inv_g.smt2                                                       |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvshl0_rtl.smt2                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem0_rtl.smt2                                                            |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem1_rtl.smt2                                                            |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|int_check_bvsle_bvadd_ltr_inv_g.smt2                                                        |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr0_ltr_inv_g.smt2                                                      |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr0_rtl.smt2                                                            |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr1_rtl.smt2                                                            |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl0_ltr_inv_g.smt2                                                       |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv0_rtl.smt2                                                            |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_ltr_inv_g.smt2                                                      |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr0_rtl.smt2                                                            |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr1_rtl.smt2                                                            |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr0_ltr_inv_g.smt2                                                      |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr0_rtl.smt2                                                            |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv0_ltr_inv_g.smt2                                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr1_ltr_inv_g.smt2                                                      |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr1_rtl.smt2                                                            |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|int_check_bvuge_bvshl0_rtl.smt2                                                             |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem0_rtl.smt2                                                            |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr0_ltr_inv_g.smt2                                                      |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr1_ltr_inv_g.smt2                                                      |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr1_rtl.smt2                                                            |   0.616s  |   0.616s  |   0.000s  | 0.0%|
|int_check_bvugt_bvudiv0_rtl.smt2                                                            |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|int_check_bvugt_bvudiv1_rtl.smt2                                                            |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvugt_bvurem0_rtl.smt2                                                            |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|int_check_bvule_bvneg_ltr_inv_g.smt2                                                        |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv1_ltr_inv_g.smt2                                                      |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvule_bvurem0_ltr_inv_g.smt2                                                      |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|int_check_bvule_bvurem1_ltr_inv_g.smt2                                                      |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr1_rtl.smt2                                                            |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|int_check_bvult_bvneg_ltr_inv_g.smt2                                                        |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvult_bvurem0_ltr_inv_g.smt2                                                      |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvult_bvurem1_ltr_inv_g.smt2                                                      |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_eq_bvashr0_rtl.smt2                                                               |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|int_check_eq_bvlshr0_rtl.smt2                                                               |  59.904s  |  59.904s  |   0.000s  | 0.0%|
|int_check_eq_bvudiv0_rtl.smt2                                                               |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|int_check_eq_bvudiv1_rtl.smt2                                                               |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|int_check_eq_bvurem0_ltr_inv_g.smt2                                                         |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|int_check_eq_bvurem0_rtl.smt2                                                               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|int_check_ne_bvashr0_ltr_inv_g.smt2                                                         |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_ltr_inv_g.smt2                                                         |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|n0-0000.smt2                                                                                |  59.915s  |  59.915s  |   0.000s  | 0.0%|
|n1-0001.smt2                                                                                |  11.513s  |  11.513s  |   0.000s  | 0.0%|
|n10-0010.smt2                                                                               |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|n100-0003.smt2                                                                              |   2.340s  |   2.340s  |   0.000s  | 0.0%|
|n101-0004.smt2                                                                              |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|n102-0005.smt2                                                                              |   6.328s  |   6.328s  |   0.000s  | 0.0%|
|n103-0006.smt2                                                                              |  59.794s  |  59.794s  |   0.000s  | 0.0%|
|n104-0007.smt2                                                                              |   2.217s  |   2.217s  |   0.000s  | 0.0%|
|n105-0008.smt2                                                                              |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|n106-0009.smt2                                                                              |  33.975s  |  33.975s  |   0.000s  | 0.0%|
|n107-0011.smt2                                                                              |   8.375s  |   8.375s  |   0.000s  | 0.0%|
|n108-0012.smt2                                                                              |   2.322s  |   2.322s  |   0.000s  | 0.0%|
|n109-0013.smt2                                                                              |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|n11-0012.smt2                                                                               |  52.873s  |  52.873s  |   0.000s  | 0.0%|
|n110-0014.smt2                                                                              |   3.967s  |   3.967s  |   0.000s  | 0.0%|
|n111-0015.smt2                                                                              |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|n112-0016.smt2                                                                              |  60.018s  |  60.018s  |   0.000s  | 0.0%|
|n113-0017.smt2                                                                              |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|n114-0018.smt2                                                                              |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|n115-0019.smt2                                                                              |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|n116-0020.smt2                                                                              |  60.018s  |  60.018s  |   0.000s  | 0.0%|
|n117-0021.smt2                                                                              |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|n118-0022.smt2                                                                              |  59.912s  |  59.912s  |   0.000s  | 0.0%|
|n119-0023.smt2                                                                              |   8.195s  |   8.195s  |   0.000s  | 0.0%|
|n12-0013.smt2                                                                               |   4.391s  |   4.391s  |   0.000s  | 0.0%|
|n120-0024.smt2                                                                              |  59.927s  |  59.927s  |   0.000s  | 0.0%|
|n121-0025.smt2                                                                              |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|n122-0026.smt2                                                                              |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|n123-0027.smt2                                                                              |  59.882s  |  59.882s  |   0.000s  | 0.0%|
|n124-0028.smt2                                                                              |   1.541s  |   1.541s  |   0.000s  | 0.0%|
|n125-0029.smt2                                                                              |   1.621s  |   1.621s  |   0.000s  | 0.0%|
|n126-0030.smt2                                                                              |  59.905s  |  59.905s  |   0.000s  | 0.0%|
|n127-0031.smt2                                                                              |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|n128-0032.smt2                                                                              |   1.874s  |   1.874s  |   0.000s  | 0.0%|
|n129-0033.smt2                                                                              |  59.885s  |  59.885s  |   0.000s  | 0.0%|
|n13-0015.smt2                                                                               |  59.879s  |  59.879s  |   0.000s  | 0.0%|
|n130-0034.smt2                                                                              |  59.882s  |  59.882s  |   0.000s  | 0.0%|
|n131-0035.smt2                                                                              |  17.289s  |  17.289s  |   0.000s  | 0.0%|
|n132-0036.smt2                                                                              |  11.920s  |  11.920s  |   0.000s  | 0.0%|
|n133-0037.smt2                                                                              |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|n134-0038.smt2                                                                              |   3.260s  |   3.260s  |   0.000s  | 0.0%|
|n135-0039.smt2                                                                              |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|n136-0040.smt2                                                                              |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|n137-0041.smt2                                                                              |  59.889s  |  59.889s  |   0.000s  | 0.0%|
|n16-0019.smt2                                                                               |  59.910s  |  59.910s  |   0.000s  | 0.0%|
|n17-0021.smt2                                                                               |   2.392s  |   2.392s  |   0.000s  | 0.0%|
|n18-0022.smt2                                                                               |  17.525s  |  17.525s  |   0.000s  | 0.0%|
|n19-0024.smt2                                                                               |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|n2-0002.smt2                                                                                |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|n20-0026.smt2                                                                               |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|n21-0027.smt2                                                                               |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|n22-0029.smt2                                                                               |  59.851s  |  59.851s  |   0.000s  | 0.0%|
|n23-0030.smt2                                                                               |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|n24-0031.smt2                                                                               |  60.018s  |  60.018s  |   0.000s  | 0.0%|
|n25-0032.smt2                                                                               |  25.439s  |  25.439s  |   0.000s  | 0.0%|
|n26-0033.smt2                                                                               |   6.263s  |   6.263s  |   0.000s  | 0.0%|
|n27-0034.smt2                                                                               |   4.075s  |   4.075s  |   0.000s  | 0.0%|
|n28-0035.smt2                                                                               |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|n29-0036.smt2                                                                               |  60.021s  |  60.021s  |   0.000s  | 0.0%|
|n3-0003.smt2                                                                                |  59.893s  |  59.893s  |   0.000s  | 0.0%|
|n30-0037.smt2                                                                               |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|n31-0038.smt2                                                                               |  34.896s  |  34.896s  |   0.000s  | 0.0%|
|n32-0039.smt2                                                                               |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|n33-0040.smt2                                                                               |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|n34-0041.smt2                                                                               |  10.929s  |  10.929s  |   0.000s  | 0.0%|
|n35-0042.smt2                                                                               |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|n36-0043.smt2                                                                               |  59.652s  |  59.652s  |   0.000s  | 0.0%|
|n37-0044.smt2                                                                               |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|n38-0045.smt2                                                                               |  16.659s  |  16.659s  |   0.000s  | 0.0%|
|n39-0046.smt2                                                                               |  60.052s  |  60.052s  |   0.000s  | 0.0%|
|n4-0004.smt2                                                                                |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|n40-0047.smt2                                                                               |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|n41-0048.smt2                                                                               |   6.812s  |   6.812s  |   0.000s  | 0.0%|
|n42-0049.smt2                                                                               |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|n43-0050.smt2                                                                               |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|n44-0051.smt2                                                                               |  59.851s  |  59.851s  |   0.000s  | 0.0%|
|n45-0052.smt2                                                                               |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|n46-0053.smt2                                                                               |  59.892s  |  59.892s  |   0.000s  | 0.0%|
|n47-0000.smt2                                                                               |   5.770s  |   5.770s  |   0.000s  | 0.0%|
|n48-0001.smt2                                                                               |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|n49-0002.smt2                                                                               |  59.808s  |  59.808s  |   0.000s  | 0.0%|
|n5-0005.smt2                                                                                |   7.869s  |   7.869s  |   0.000s  | 0.0%|
|n50-0003.smt2                                                                               |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|n51-0004.smt2                                                                               |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|n52-0005.smt2                                                                               |  60.025s  |  60.025s  |   0.000s  | 0.0%|
|n53-0006.smt2                                                                               |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|n54-0007.smt2                                                                               |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|n55-0008.smt2                                                                               |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|n56-0009.smt2                                                                               |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|n57-0010.smt2                                                                               |   7.289s  |   7.289s  |   0.000s  | 0.0%|
|n58-0011.smt2                                                                               |  59.834s  |  59.834s  |   0.000s  | 0.0%|
|n59-0012.smt2                                                                               |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|n6-0006.smt2                                                                                |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|n60-0014.smt2                                                                               |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|n61-0015.smt2                                                                               |  10.810s  |  10.810s  |   0.000s  | 0.0%|
|n62-0016.smt2                                                                               |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|n63-0017.smt2                                                                               |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|n64-0018.smt2                                                                               |  59.913s  |  59.913s  |   0.000s  | 0.0%|
|n65-0019.smt2                                                                               |  42.361s  |  42.361s  |   0.000s  | 0.0%|
|n66-0020.smt2                                                                               |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|n67-0021.smt2                                                                               |  60.010s  |  60.010s  |   0.000s  | 0.0%|
|n68-0022.smt2                                                                               |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|n69-0023.smt2                                                                               |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|n7-0007.smt2                                                                                |  59.884s  |  59.884s  |   0.000s  | 0.0%|
|n70-0024.smt2                                                                               |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|n71-0025.smt2                                                                               |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|n72-0026.smt2                                                                               |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|n73-0027.smt2                                                                               |   7.000s  |   7.000s  |   0.000s  | 0.0%|
|n74-0028.smt2                                                                               |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|n75-0029.smt2                                                                               |  59.836s  |  59.836s  |   0.000s  | 0.0%|
|n76-0030.smt2                                                                               |  62.054s  |  62.054s  |   0.000s  | 0.0%|
|n77-0031.smt2                                                                               |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|n78-0032.smt2                                                                               |  59.619s  |  59.619s  |   0.000s  | 0.0%|
|n79-0033.smt2                                                                               |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|n8-0008.smt2                                                                                |  60.010s  |  60.010s  |   0.000s  | 0.0%|
|n80-0034.smt2                                                                               |  59.925s  |  59.925s  |   0.000s  | 0.0%|
|n81-0035.smt2                                                                               |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|n82-0036.smt2                                                                               |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|n83-0037.smt2                                                                               |  59.898s  |  59.898s  |   0.000s  | 0.0%|
|n84-0038.smt2                                                                               |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|n85-0039.smt2                                                                               |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|n86-0040.smt2                                                                               |   1.914s  |   1.914s  |   0.000s  | 0.0%|
|n87-0041.smt2                                                                               |  12.803s  |  12.803s  |   0.000s  | 0.0%|
|n88-0042.smt2                                                                               |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|n89-0044.smt2                                                                               |  56.465s  |  56.465s  |   0.000s  | 0.0%|
|n9-0009.smt2                                                                                |   8.738s  |   8.738s  |   0.000s  | 0.0%|
|n90-0045.smt2                                                                               |   6.288s  |   6.288s  |   0.000s  | 0.0%|
|n91-0046.smt2                                                                               |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|n92-0047.smt2                                                                               |   1.301s  |   1.301s  |   0.000s  | 0.0%|
|n93-0048.smt2                                                                               |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|n94-0049.smt2                                                                               |  60.019s  |  60.019s  |   0.000s  | 0.0%|
|n95-0050.smt2                                                                               |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|n96-0051.smt2                                                                               |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|n97-0000.smt2                                                                               |  59.888s  |  59.888s  |   0.000s  | 0.0%|
|n98-0001.smt2                                                                               |  59.907s  |  59.907s  |   0.000s  | 0.0%|
|n99-0002.smt2                                                                               |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|qf_AddSub_1165_values_0.smt2                                                                |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|qf_AddSub_1574_values_0.smt2                                                                |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|qf_AddSub_1619_values_0.smt2                                                                |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|qf_AndOrXor_1869_values_0.smt2                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_1894_values_0.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_210_values_0.smt2                                                               |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_230_values_0.smt2                                                               |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_2443_values_0.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_290_values_7.smt2                                                               |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|qf_AndOrXor_794_values_121.smt2                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_InstCombineShift497a_values_0.smt2                                                       |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_InstCombineShift497b_values_0.smt2                                                       |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_InstCombineShift497c_values_0.smt2                                                       |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|qf_InstCombineShift497d_values_0.smt2                                                       |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|qf_Select_510_values_0.smt2                                                                 |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|qf_Select_575a_values_0.smt2                                                                |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|qf_Select_575b_values_0.smt2                                                                |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_Select_700_values_123.smt2                                                               |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_Select_705_values_0.smt2                                                                 |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_Select_727_values_0.smt2                                                                 |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_muldivrem_152_values_0.smt2                                                              |  11.463s  |  11.463s  |   0.000s  | 0.0%|
|qf_muldivrem_229_values_0.smt2                                                              |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|qf_muldivrem_239_values_0.smt2                                                              |  59.728s  |  59.728s  |   0.000s  | 0.0%|
</details>
