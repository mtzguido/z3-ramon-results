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
Job tag: smt-clausal-lookahead-60-qfufnia-unknown
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
Job tag: smt-clausal-lookahead-60-qfufnia-unknown
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
|0054.smt2                                                                                   |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.025s  |  60.025s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.035s  |  60.035s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.065s  |  60.065s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  60.017s  |  60.017s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  59.880s  |  59.880s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   0.932s  |   0.932s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   5.977s  |   5.977s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  20.427s  |  20.427s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  29.742s  |  29.742s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.987s  |  59.987s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.025s  |  60.025s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.035s  |  60.035s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.065s  |  60.065s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  60.017s  |  60.017s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  59.880s  |  59.880s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   0.932s  |   0.932s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   5.977s  |   5.977s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  20.427s  |  20.427s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  29.742s  |  29.742s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.987s  |  59.987s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.025s  |  60.025s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.035s  |  60.035s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.065s  |  60.065s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  60.017s  |  60.017s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  59.880s  |  59.880s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   0.932s  |   0.932s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   5.977s  |   5.977s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  20.427s  |  20.427s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  29.742s  |  29.742s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.987s  |  59.987s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.025s  |  60.025s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.035s  |  60.035s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.065s  |  60.065s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  60.017s  |  60.017s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  59.880s  |  59.880s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   0.932s  |   0.932s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   5.977s  |   5.977s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  20.427s  |  20.427s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  29.742s  |  29.742s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.987s  |  59.987s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|0063.smt2                                                                                  |  60.065s |2090.0MiB|
|n43-0050.smt2                                                                              |  60.051s |1112.0MiB|
|n74-0028.smt2                                                                              |  60.040s |156.0MiB|
|n112-0016.smt2                                                                             |  60.039s |814.0MiB|
|n32-0039.smt2                                                                              |  60.036s |427.0MiB|
|0062.smt2                                                                                  |  60.035s |2697.0MiB|
|n33-0040.smt2                                                                              |  60.031s |598.0MiB|
|n117-0021.smt2                                                                             |  60.031s |645.0MiB|
|n45-0052.smt2                                                                              |  60.030s |1308.0MiB|
|n79-0033.smt2                                                                              |  60.030s |343.0MiB|
|n20-0026.smt2                                                                              |  60.028s |822.0MiB|
|n70-0024.smt2                                                                              |  60.028s |1045.0MiB|
|0059.smt2                                                                                  |  60.025s |808.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  60.023s |1002.0MiB|
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                                                  |  60.023s |309.0MiB|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                    |  60.022s |397.0MiB|
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                                                    |  60.018s |211.0MiB|
|0064.smt2                                                                                  |  60.017s |573.0MiB|
|n53-0006.smt2                                                                              |  60.015s |59.988MiB|
|n72-0026.smt2                                                                              |  60.014s |528.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|0063.smt2                                                                                  |  60.065s |2090.0MiB|
|n43-0050.smt2                                                                              |  60.051s |1112.0MiB|
|n74-0028.smt2                                                                              |  60.040s |156.0MiB|
|n112-0016.smt2                                                                             |  60.039s |814.0MiB|
|n32-0039.smt2                                                                              |  60.036s |427.0MiB|
|0062.smt2                                                                                  |  60.035s |2697.0MiB|
|n33-0040.smt2                                                                              |  60.031s |598.0MiB|
|n117-0021.smt2                                                                             |  60.031s |645.0MiB|
|n45-0052.smt2                                                                              |  60.030s |1308.0MiB|
|n79-0033.smt2                                                                              |  60.030s |343.0MiB|
|n20-0026.smt2                                                                              |  60.028s |822.0MiB|
|n70-0024.smt2                                                                              |  60.028s |1045.0MiB|
|0059.smt2                                                                                  |  60.025s |808.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  60.023s |1002.0MiB|
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                                                  |  60.023s |309.0MiB|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                    |  60.022s |397.0MiB|
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                                                    |  60.018s |211.0MiB|
|0064.smt2                                                                                  |  60.017s |573.0MiB|
|n53-0006.smt2                                                                              |  60.015s |59.988MiB|
|n72-0026.smt2                                                                              |  60.014s |528.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1405.0MiB|1405.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1409.0MiB|1409.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |324.0MiB|324.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |192.0MiB|192.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |798.0MiB|798.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |808.0MiB|808.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |194.0MiB|194.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |191.0MiB|191.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2697.0MiB|2697.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2090.0MiB|2090.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |573.0MiB|573.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |226.0MiB|226.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2941.0MiB|2941.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |461.0MiB|461.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |73.38MiB|73.38MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.228MiB|67.228MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |56.808MiB|56.808MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |80.56MiB|80.56MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |74.124MiB|74.124MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |145.0MiB|145.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1405.0MiB|1405.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1409.0MiB|1409.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |324.0MiB|324.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |192.0MiB|192.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |798.0MiB|798.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |808.0MiB|808.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |194.0MiB|194.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |191.0MiB|191.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2697.0MiB|2697.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2090.0MiB|2090.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |573.0MiB|573.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |226.0MiB|226.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2941.0MiB|2941.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |461.0MiB|461.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |73.38MiB|73.38MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.228MiB|67.228MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |56.808MiB|56.808MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |80.56MiB|80.56MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |74.124MiB|74.124MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |145.0MiB|145.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1405.0MiB|1405.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1409.0MiB|1409.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |324.0MiB|324.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |192.0MiB|192.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |798.0MiB|798.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |808.0MiB|808.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |194.0MiB|194.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |191.0MiB|191.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2697.0MiB|2697.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2090.0MiB|2090.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |573.0MiB|573.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |226.0MiB|226.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2941.0MiB|2941.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |461.0MiB|461.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |73.38MiB|73.38MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.228MiB|67.228MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |56.808MiB|56.808MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |80.56MiB|80.56MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |74.124MiB|74.124MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |145.0MiB|145.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1405.0MiB|1405.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1409.0MiB|1409.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |324.0MiB|324.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |192.0MiB|192.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |798.0MiB|798.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |808.0MiB|808.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |194.0MiB|194.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |191.0MiB|191.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2697.0MiB|2697.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2090.0MiB|2090.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |573.0MiB|573.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |226.0MiB|226.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2941.0MiB|2941.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |461.0MiB|461.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |73.38MiB|73.38MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.228MiB|67.228MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |56.808MiB|56.808MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |80.56MiB|80.56MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |74.124MiB|74.124MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |145.0MiB|145.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|0066.smt2                                                                                  |  59.880s |2941.0MiB|
|0062.smt2                                                                                  |  60.035s |2697.0MiB|
|0063.smt2                                                                                  |  60.065s |2090.0MiB|
|n29-0036.smt2                                                                              |  59.979s |1720.0MiB|
|n39-0046.smt2                                                                              |  59.950s |1710.0MiB|
|0055.smt2                                                                                  |  59.987s |1409.0MiB|
|0054.smt2                                                                                  |  59.944s |1405.0MiB|
|n45-0052.smt2                                                                              |  60.030s |1308.0MiB|
|n1-0001.smt2                                                                               |  11.494s |1129.0MiB|
|n43-0050.smt2                                                                              |  60.051s |1112.0MiB|
|n76-0030.smt2                                                                              |  59.912s |1047.0MiB|
|n70-0024.smt2                                                                              |  60.028s |1045.0MiB|
|n71-0025.smt2                                                                              |  60.008s |1030.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  60.023s |1002.0MiB|
|n111-0015.smt2                                                                             |  59.947s |915.0MiB|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                |  23.017s |843.0MiB|
|n95-0050.smt2                                                                              |  59.968s |828.0MiB|
|n20-0026.smt2                                                                              |  60.028s |822.0MiB|
|n112-0016.smt2                                                                             |  60.039s |814.0MiB|
|0059.smt2                                                                                  |  60.025s |808.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|0066.smt2                                                                                  |  59.880s |2941.0MiB|
|0062.smt2                                                                                  |  60.035s |2697.0MiB|
|0063.smt2                                                                                  |  60.065s |2090.0MiB|
|n29-0036.smt2                                                                              |  59.979s |1720.0MiB|
|n39-0046.smt2                                                                              |  59.950s |1710.0MiB|
|0055.smt2                                                                                  |  59.987s |1409.0MiB|
|0054.smt2                                                                                  |  59.944s |1405.0MiB|
|n45-0052.smt2                                                                              |  60.030s |1308.0MiB|
|n1-0001.smt2                                                                               |  11.494s |1129.0MiB|
|n43-0050.smt2                                                                              |  60.051s |1112.0MiB|
|n76-0030.smt2                                                                              |  59.912s |1047.0MiB|
|n70-0024.smt2                                                                              |  60.028s |1045.0MiB|
|n71-0025.smt2                                                                              |  60.008s |1030.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  60.023s |1002.0MiB|
|n111-0015.smt2                                                                             |  59.947s |915.0MiB|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                |  23.017s |843.0MiB|
|n95-0050.smt2                                                                              |  59.968s |828.0MiB|
|n20-0026.smt2                                                                              |  60.028s |822.0MiB|
|n112-0016.smt2                                                                             |  60.039s |814.0MiB|
|0059.smt2                                                                                  |  60.025s |808.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.025s  |  60.025s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.035s  |  60.035s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.065s  |  60.065s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  60.017s  |  60.017s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  59.880s  |  59.880s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   0.932s  |   0.932s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   5.977s  |   5.977s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  20.427s  |  20.427s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  29.742s  |  29.742s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2                                     |   5.549s  |   5.549s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2                                     |  59.927s  |  59.927s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                     |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2                                     |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                  |  60.023s  |  60.023s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                                                  |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                                                  |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                                                  |   1.743s  |   1.743s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2                                      |  24.677s  |  24.677s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                                                 |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                                                 |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                                                 |  59.888s  |  59.888s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                                                 |   2.424s  |   2.424s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                 |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                                                 |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                                                 |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                                                 |   9.828s  |   9.828s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                                                 |  15.131s  |  15.131s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                                                 |   1.513s  |   1.513s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                                                 |  59.881s  |  59.881s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                                                 |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                                                 |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                                                 |   1.673s  |   1.673s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                                                 |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                                                 |  10.580s  |  10.580s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                 |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2                                     |  41.444s  |  41.444s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                                                 |   4.321s  |   4.321s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                                                 |   7.960s  |   7.960s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                                                 |  59.932s  |  59.932s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                                                 |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                                                 |  59.872s  |  59.872s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2                                     |   5.294s  |   5.294s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2                                     |   4.668s  |   4.668s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                     |  60.022s  |  60.022s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2                                     |  54.149s  |  54.149s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                                                 |  10.784s  |  10.784s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                                                 |  10.452s  |  10.452s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                                                 |  40.722s  |  40.722s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                                                 |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2                                        |   1.164s  |   1.164s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                  |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                                                  |   1.689s  |   1.689s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                                                  |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                                                  |   2.197s  |   2.197s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                 |  23.017s  |  23.017s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                 |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                                                 |   3.097s  |   3.097s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                                                 |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                                                 |   5.386s  |   5.386s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                                                     |   1.205s  |   1.205s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                                                     |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                                                     |  60.018s  |  60.018s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                                                     |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                                                     |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2                                     |  56.961s  |  56.961s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2                                     |  36.644s  |  36.644s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2                                     |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                                                 |  23.139s  |  23.139s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                                                   |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                                                   |  25.820s  |  25.820s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                                                   |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                                                   |   9.574s  |   9.574s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                                                   |  60.023s  |  60.023s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr1_rtl.smt2                                                            |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_ltr_inv_g.smt2                                                      |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_rtl.smt2                                                            |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|int_check_bvsge_bvneg_ltr_inv_g.smt2                                                        |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|int_check_bvsge_bvudiv1_rtl.smt2                                                            |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem1_ltr_inv_g.smt2                                                      |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_rtl.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr0_rtl.smt2                                                            |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr1_ltr_inv_g.smt2                                                      |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr0_rtl.smt2                                                            |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr1_rtl.smt2                                                            |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvshl0_ltr_inv_g.smt2                                                       |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvshl0_rtl.smt2                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem0_rtl.smt2                                                            |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem1_rtl.smt2                                                            |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|int_check_bvsle_bvadd_ltr_inv_g.smt2                                                        |   0.499s  |   0.499s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr0_ltr_inv_g.smt2                                                      |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr0_rtl.smt2                                                            |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr1_rtl.smt2                                                            |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl0_ltr_inv_g.smt2                                                       |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv0_rtl.smt2                                                            |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_ltr_inv_g.smt2                                                      |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr0_rtl.smt2                                                            |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr1_rtl.smt2                                                            |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr0_ltr_inv_g.smt2                                                      |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr0_rtl.smt2                                                            |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv0_ltr_inv_g.smt2                                                      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr1_ltr_inv_g.smt2                                                      |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr1_rtl.smt2                                                            |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|int_check_bvuge_bvshl0_rtl.smt2                                                             |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem0_rtl.smt2                                                            |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr0_ltr_inv_g.smt2                                                      |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr1_ltr_inv_g.smt2                                                      |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr1_rtl.smt2                                                            |   0.663s  |   0.663s  |   0.000s  | 0.0%|
|int_check_bvugt_bvudiv0_rtl.smt2                                                            |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|int_check_bvugt_bvudiv1_rtl.smt2                                                            |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|int_check_bvugt_bvurem0_rtl.smt2                                                            |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|int_check_bvule_bvneg_ltr_inv_g.smt2                                                        |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv1_ltr_inv_g.smt2                                                      |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvule_bvurem0_ltr_inv_g.smt2                                                      |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvule_bvurem1_ltr_inv_g.smt2                                                      |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr1_rtl.smt2                                                            |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|int_check_bvult_bvneg_ltr_inv_g.smt2                                                        |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvult_bvurem0_ltr_inv_g.smt2                                                      |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvult_bvurem1_ltr_inv_g.smt2                                                      |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_eq_bvashr0_rtl.smt2                                                               |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|int_check_eq_bvlshr0_rtl.smt2                                                               |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|int_check_eq_bvudiv0_rtl.smt2                                                               |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|int_check_eq_bvudiv1_rtl.smt2                                                               |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|int_check_eq_bvurem0_ltr_inv_g.smt2                                                         |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|int_check_eq_bvurem0_rtl.smt2                                                               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|int_check_ne_bvashr0_ltr_inv_g.smt2                                                         |  59.902s  |  59.902s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_ltr_inv_g.smt2                                                         |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|n0-0000.smt2                                                                                |  59.853s  |  59.853s  |   0.000s  | 0.0%|
|n1-0001.smt2                                                                                |  11.494s  |  11.494s  |   0.000s  | 0.0%|
|n10-0010.smt2                                                                               |  59.905s  |  59.905s  |   0.000s  | 0.0%|
|n100-0003.smt2                                                                              |   2.356s  |   2.356s  |   0.000s  | 0.0%|
|n101-0004.smt2                                                                              |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|n102-0005.smt2                                                                              |   6.156s  |   6.156s  |   0.000s  | 0.0%|
|n103-0006.smt2                                                                              |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|n104-0007.smt2                                                                              |   2.170s  |   2.170s  |   0.000s  | 0.0%|
|n105-0008.smt2                                                                              |  59.641s  |  59.641s  |   0.000s  | 0.0%|
|n106-0009.smt2                                                                              |  33.267s  |  33.267s  |   0.000s  | 0.0%|
|n107-0011.smt2                                                                              |   8.360s  |   8.360s  |   0.000s  | 0.0%|
|n108-0012.smt2                                                                              |   2.275s  |   2.275s  |   0.000s  | 0.0%|
|n109-0013.smt2                                                                              |  60.004s  |  60.004s  |   0.000s  | 0.0%|
|n11-0012.smt2                                                                               |  52.300s  |  52.300s  |   0.000s  | 0.0%|
|n110-0014.smt2                                                                              |   4.310s  |   4.310s  |   0.000s  | 0.0%|
|n111-0015.smt2                                                                              |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|n112-0016.smt2                                                                              |  60.039s  |  60.039s  |   0.000s  | 0.0%|
|n113-0017.smt2                                                                              |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|n114-0018.smt2                                                                              |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|n115-0019.smt2                                                                              |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|n116-0020.smt2                                                                              |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|n117-0021.smt2                                                                              |  60.031s  |  60.031s  |   0.000s  | 0.0%|
|n118-0022.smt2                                                                              |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|n119-0023.smt2                                                                              |   8.030s  |   8.030s  |   0.000s  | 0.0%|
|n12-0013.smt2                                                                               |   4.466s  |   4.466s  |   0.000s  | 0.0%|
|n120-0024.smt2                                                                              |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|n121-0025.smt2                                                                              |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|n122-0026.smt2                                                                              |  59.759s  |  59.759s  |   0.000s  | 0.0%|
|n123-0027.smt2                                                                              |  59.856s  |  59.856s  |   0.000s  | 0.0%|
|n124-0028.smt2                                                                              |   1.648s  |   1.648s  |   0.000s  | 0.0%|
|n125-0029.smt2                                                                              |   1.718s  |   1.718s  |   0.000s  | 0.0%|
|n126-0030.smt2                                                                              |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|n127-0031.smt2                                                                              |  59.856s  |  59.856s  |   0.000s  | 0.0%|
|n128-0032.smt2                                                                              |   1.848s  |   1.848s  |   0.000s  | 0.0%|
|n129-0033.smt2                                                                              |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|n13-0015.smt2                                                                               |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|n130-0034.smt2                                                                              |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|n131-0035.smt2                                                                              |  18.168s  |  18.168s  |   0.000s  | 0.0%|
|n132-0036.smt2                                                                              |  11.228s  |  11.228s  |   0.000s  | 0.0%|
|n133-0037.smt2                                                                              |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|n134-0038.smt2                                                                              |   3.266s  |   3.266s  |   0.000s  | 0.0%|
|n135-0039.smt2                                                                              |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|n136-0040.smt2                                                                              |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|n137-0041.smt2                                                                              |  59.787s  |  59.787s  |   0.000s  | 0.0%|
|n16-0019.smt2                                                                               |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|n17-0021.smt2                                                                               |   2.472s  |   2.472s  |   0.000s  | 0.0%|
|n18-0022.smt2                                                                               |  16.173s  |  16.173s  |   0.000s  | 0.0%|
|n19-0024.smt2                                                                               |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|n2-0002.smt2                                                                                |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|n20-0026.smt2                                                                               |  60.028s  |  60.028s  |   0.000s  | 0.0%|
|n21-0027.smt2                                                                               |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|n22-0029.smt2                                                                               |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|n23-0030.smt2                                                                               |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|n24-0031.smt2                                                                               |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|n25-0032.smt2                                                                               |  23.756s  |  23.756s  |   0.000s  | 0.0%|
|n26-0033.smt2                                                                               |   5.972s  |   5.972s  |   0.000s  | 0.0%|
|n27-0034.smt2                                                                               |   4.292s  |   4.292s  |   0.000s  | 0.0%|
|n28-0035.smt2                                                                               |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|n29-0036.smt2                                                                               |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|n3-0003.smt2                                                                                |  59.878s  |  59.878s  |   0.000s  | 0.0%|
|n30-0037.smt2                                                                               |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|n31-0038.smt2                                                                               |  33.700s  |  33.700s  |   0.000s  | 0.0%|
|n32-0039.smt2                                                                               |  60.036s  |  60.036s  |   0.000s  | 0.0%|
|n33-0040.smt2                                                                               |  60.031s  |  60.031s  |   0.000s  | 0.0%|
|n34-0041.smt2                                                                               |  11.377s  |  11.377s  |   0.000s  | 0.0%|
|n35-0042.smt2                                                                               |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|n36-0043.smt2                                                                               |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|n37-0044.smt2                                                                               |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|n38-0045.smt2                                                                               |  16.388s  |  16.388s  |   0.000s  | 0.0%|
|n39-0046.smt2                                                                               |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|n4-0004.smt2                                                                                |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|n40-0047.smt2                                                                               |  59.883s  |  59.883s  |   0.000s  | 0.0%|
|n41-0048.smt2                                                                               |   6.561s  |   6.561s  |   0.000s  | 0.0%|
|n42-0049.smt2                                                                               |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|n43-0050.smt2                                                                               |  60.051s  |  60.051s  |   0.000s  | 0.0%|
|n44-0051.smt2                                                                               |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|n45-0052.smt2                                                                               |  60.030s  |  60.030s  |   0.000s  | 0.0%|
|n46-0053.smt2                                                                               |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|n47-0000.smt2                                                                               |   5.980s  |   5.980s  |   0.000s  | 0.0%|
|n48-0001.smt2                                                                               |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|n49-0002.smt2                                                                               |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|n5-0005.smt2                                                                                |  10.560s  |  10.560s  |   0.000s  | 0.0%|
|n50-0003.smt2                                                                               |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|n51-0004.smt2                                                                               |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|n52-0005.smt2                                                                               |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|n53-0006.smt2                                                                               |  60.015s  |  60.015s  |   0.000s  | 0.0%|
|n54-0007.smt2                                                                               |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|n55-0008.smt2                                                                               |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|n56-0009.smt2                                                                               |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|n57-0010.smt2                                                                               |   7.434s  |   7.434s  |   0.000s  | 0.0%|
|n58-0011.smt2                                                                               |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|n59-0012.smt2                                                                               |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|n6-0006.smt2                                                                                |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|n60-0014.smt2                                                                               |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|n61-0015.smt2                                                                               |  10.901s  |  10.901s  |   0.000s  | 0.0%|
|n62-0016.smt2                                                                               |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|n63-0017.smt2                                                                               |  59.849s  |  59.849s  |   0.000s  | 0.0%|
|n64-0018.smt2                                                                               |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|n65-0019.smt2                                                                               |  44.051s  |  44.051s  |   0.000s  | 0.0%|
|n66-0020.smt2                                                                               |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|n67-0021.smt2                                                                               |  59.933s  |  59.933s  |   0.000s  | 0.0%|
|n68-0022.smt2                                                                               |  59.890s  |  59.890s  |   0.000s  | 0.0%|
|n69-0023.smt2                                                                               |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|n7-0007.smt2                                                                                |  59.877s  |  59.877s  |   0.000s  | 0.0%|
|n70-0024.smt2                                                                               |  60.028s  |  60.028s  |   0.000s  | 0.0%|
|n71-0025.smt2                                                                               |  60.008s  |  60.008s  |   0.000s  | 0.0%|
|n72-0026.smt2                                                                               |  60.014s  |  60.014s  |   0.000s  | 0.0%|
|n73-0027.smt2                                                                               |   7.256s  |   7.256s  |   0.000s  | 0.0%|
|n74-0028.smt2                                                                               |  60.040s  |  60.040s  |   0.000s  | 0.0%|
|n75-0029.smt2                                                                               |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|n76-0030.smt2                                                                               |  59.912s  |  59.912s  |   0.000s  | 0.0%|
|n77-0031.smt2                                                                               |  59.884s  |  59.884s  |   0.000s  | 0.0%|
|n78-0032.smt2                                                                               |  59.865s  |  59.865s  |   0.000s  | 0.0%|
|n79-0033.smt2                                                                               |  60.030s  |  60.030s  |   0.000s  | 0.0%|
|n8-0008.smt2                                                                                |  60.004s  |  60.004s  |   0.000s  | 0.0%|
|n80-0034.smt2                                                                               |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|n81-0035.smt2                                                                               |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|n82-0036.smt2                                                                               |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|n83-0037.smt2                                                                               |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|n84-0038.smt2                                                                               |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|n85-0039.smt2                                                                               |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|n86-0040.smt2                                                                               |   2.015s  |   2.015s  |   0.000s  | 0.0%|
|n87-0041.smt2                                                                               |  12.912s  |  12.912s  |   0.000s  | 0.0%|
|n88-0042.smt2                                                                               |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|n89-0044.smt2                                                                               |  55.065s  |  55.065s  |   0.000s  | 0.0%|
|n9-0009.smt2                                                                                |   9.276s  |   9.276s  |   0.000s  | 0.0%|
|n90-0045.smt2                                                                               |   6.196s  |   6.196s  |   0.000s  | 0.0%|
|n91-0046.smt2                                                                               |  59.825s  |  59.825s  |   0.000s  | 0.0%|
|n92-0047.smt2                                                                               |   1.233s  |   1.233s  |   0.000s  | 0.0%|
|n93-0048.smt2                                                                               |  58.707s  |  58.707s  |   0.000s  | 0.0%|
|n94-0049.smt2                                                                               |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|n95-0050.smt2                                                                               |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|n96-0051.smt2                                                                               |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|n97-0000.smt2                                                                               |  59.425s  |  59.425s  |   0.000s  | 0.0%|
|n98-0001.smt2                                                                               |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|n99-0002.smt2                                                                               |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|qf_AddSub_1165_values_0.smt2                                                                |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|qf_AddSub_1574_values_0.smt2                                                                |   0.591s  |   0.591s  |   0.000s  | 0.0%|
|qf_AddSub_1619_values_0.smt2                                                                |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|qf_AndOrXor_1869_values_0.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_1894_values_0.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_210_values_0.smt2                                                               |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_230_values_0.smt2                                                               |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_2443_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_290_values_7.smt2                                                               |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|qf_AndOrXor_794_values_121.smt2                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_InstCombineShift497a_values_0.smt2                                                       |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_InstCombineShift497b_values_0.smt2                                                       |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_InstCombineShift497c_values_0.smt2                                                       |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|qf_InstCombineShift497d_values_0.smt2                                                       |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|qf_Select_510_values_0.smt2                                                                 |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|qf_Select_575a_values_0.smt2                                                                |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|qf_Select_575b_values_0.smt2                                                                |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_Select_700_values_123.smt2                                                               |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_Select_705_values_0.smt2                                                                 |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_Select_727_values_0.smt2                                                                 |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_muldivrem_152_values_0.smt2                                                              |  11.895s  |  11.895s  |   0.000s  | 0.0%|
|qf_muldivrem_229_values_0.smt2                                                              |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|qf_muldivrem_239_values_0.smt2                                                              |  59.926s  |  59.926s  |   0.000s  | 0.0%|
</details>
