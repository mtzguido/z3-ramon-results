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
|0054.smt2                                                                                   |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  59.811s  |  59.811s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.896s  |  59.896s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.065s  |  60.065s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  60.050s  |  60.050s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  59.734s  |  59.734s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.056s  |   1.056s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   6.264s  |   6.264s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  19.538s  |  19.538s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  28.353s  |  28.353s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.934s  |  59.934s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  59.811s  |  59.811s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.896s  |  59.896s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.065s  |  60.065s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  60.050s  |  60.050s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  59.734s  |  59.734s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.056s  |   1.056s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   6.264s  |   6.264s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  19.538s  |  19.538s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  28.353s  |  28.353s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.934s  |  59.934s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  59.811s  |  59.811s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.896s  |  59.896s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.065s  |  60.065s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  60.050s  |  60.050s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  59.734s  |  59.734s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.056s  |   1.056s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   6.264s  |   6.264s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  19.538s  |  19.538s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  28.353s  |  28.353s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.934s  |  59.934s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  59.811s  |  59.811s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.896s  |  59.896s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.065s  |  60.065s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  60.050s  |  60.050s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  59.734s  |  59.734s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.056s  |   1.056s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   6.264s  |   6.264s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  19.538s  |  19.538s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  28.353s  |  28.353s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.934s  |  59.934s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n43-0050.smt2                                                                              |  60.125s |1122.0MiB|
|n80-0034.smt2                                                                              |  60.109s |80.66MiB|
|0063.smt2                                                                                  |  60.065s |2076.0MiB|
|0066.smt2                                                                                  |  60.050s |2929.0MiB|
|n85-0039.smt2                                                                              |  60.046s |738.0MiB|
|n76-0030.smt2                                                                              |  60.031s |1042.0MiB|
|n33-0040.smt2                                                                              |  60.024s |608.0MiB|
|n39-0046.smt2                                                                              |  60.024s |1713.0MiB|
|n67-0021.smt2                                                                              |  60.024s |579.0MiB|
|n29-0036.smt2                                                                              |  60.018s |1715.0MiB|
|n70-0024.smt2                                                                              |  60.017s |1048.0MiB|
|n136-0040.smt2                                                                             |  60.016s |464.0MiB|
|n78-0032.smt2                                                                              |  60.016s |525.0MiB|
|n20-0026.smt2                                                                              |  60.016s |825.0MiB|
|n6-0006.smt2                                                                               |  60.015s |75.86MiB|
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                                                  |  60.014s |309.0MiB|
|n68-0022.smt2                                                                              |  60.013s |340.0MiB|
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                                                |  60.010s |67.768MiB|
|n3-0003.smt2                                                                               |  60.009s |164.0MiB|
|n42-0049.smt2                                                                              |  60.007s |364.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n43-0050.smt2                                                                              |  60.125s |1122.0MiB|
|n80-0034.smt2                                                                              |  60.109s |80.66MiB|
|0063.smt2                                                                                  |  60.065s |2076.0MiB|
|0066.smt2                                                                                  |  60.050s |2929.0MiB|
|n85-0039.smt2                                                                              |  60.046s |738.0MiB|
|n76-0030.smt2                                                                              |  60.031s |1042.0MiB|
|n33-0040.smt2                                                                              |  60.024s |608.0MiB|
|n39-0046.smt2                                                                              |  60.024s |1713.0MiB|
|n67-0021.smt2                                                                              |  60.024s |579.0MiB|
|n29-0036.smt2                                                                              |  60.018s |1715.0MiB|
|n70-0024.smt2                                                                              |  60.017s |1048.0MiB|
|n136-0040.smt2                                                                             |  60.016s |464.0MiB|
|n78-0032.smt2                                                                              |  60.016s |525.0MiB|
|n20-0026.smt2                                                                              |  60.016s |825.0MiB|
|n6-0006.smt2                                                                               |  60.015s |75.86MiB|
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                                                  |  60.014s |309.0MiB|
|n68-0022.smt2                                                                              |  60.013s |340.0MiB|
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                                                |  60.010s |67.768MiB|
|n3-0003.smt2                                                                               |  60.009s |164.0MiB|
|n42-0049.smt2                                                                              |  60.007s |364.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1406.0MiB|1406.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1410.0MiB|1410.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |326.0MiB|326.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |192.0MiB|192.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |805.0MiB|805.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |808.0MiB|808.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |188.0MiB|188.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |189.0MiB|189.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2695.0MiB|2695.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2076.0MiB|2076.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |571.0MiB|571.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |226.0MiB|226.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2929.0MiB|2929.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |460.0MiB|460.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |73.168MiB|73.168MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.372MiB|67.372MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |56.808MiB|56.808MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |80.544MiB|80.544MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |74.116MiB|74.116MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |145.0MiB|145.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1406.0MiB|1406.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1410.0MiB|1410.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |326.0MiB|326.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |192.0MiB|192.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |805.0MiB|805.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |808.0MiB|808.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |188.0MiB|188.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |189.0MiB|189.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2695.0MiB|2695.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2076.0MiB|2076.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |571.0MiB|571.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |226.0MiB|226.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2929.0MiB|2929.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |460.0MiB|460.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |73.168MiB|73.168MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.372MiB|67.372MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |56.808MiB|56.808MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |80.544MiB|80.544MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |74.116MiB|74.116MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |145.0MiB|145.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1406.0MiB|1406.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1410.0MiB|1410.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |326.0MiB|326.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |192.0MiB|192.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |805.0MiB|805.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |808.0MiB|808.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |188.0MiB|188.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |189.0MiB|189.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2695.0MiB|2695.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2076.0MiB|2076.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |571.0MiB|571.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |226.0MiB|226.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2929.0MiB|2929.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |460.0MiB|460.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |73.168MiB|73.168MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.372MiB|67.372MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |56.808MiB|56.808MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |80.544MiB|80.544MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |74.116MiB|74.116MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |145.0MiB|145.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1406.0MiB|1406.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1410.0MiB|1410.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |326.0MiB|326.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |192.0MiB|192.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |805.0MiB|805.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |808.0MiB|808.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |188.0MiB|188.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |189.0MiB|189.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2695.0MiB|2695.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2076.0MiB|2076.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |571.0MiB|571.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |226.0MiB|226.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2929.0MiB|2929.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |460.0MiB|460.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |73.168MiB|73.168MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.372MiB|67.372MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |56.808MiB|56.808MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |80.544MiB|80.544MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |74.116MiB|74.116MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |145.0MiB|145.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|0066.smt2                                                                                  |  60.050s |2929.0MiB|
|0062.smt2                                                                                  |  59.981s |2695.0MiB|
|0063.smt2                                                                                  |  60.065s |2076.0MiB|
|n29-0036.smt2                                                                              |  60.018s |1715.0MiB|
|n39-0046.smt2                                                                              |  60.024s |1713.0MiB|
|0055.smt2                                                                                  |  59.982s |1410.0MiB|
|0054.smt2                                                                                  |  59.992s |1406.0MiB|
|n45-0052.smt2                                                                              |  59.977s |1306.0MiB|
|n1-0001.smt2                                                                               |  12.541s |1127.0MiB|
|n43-0050.smt2                                                                              |  60.125s |1122.0MiB|
|n70-0024.smt2                                                                              |  60.017s |1048.0MiB|
|n76-0030.smt2                                                                              |  60.031s |1042.0MiB|
|n71-0025.smt2                                                                              |  59.618s |1028.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  59.980s |1001.0MiB|
|n111-0015.smt2                                                                             |  59.995s |905.0MiB|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                |  27.803s |843.0MiB|
|n20-0026.smt2                                                                              |  60.016s |825.0MiB|
|n112-0016.smt2                                                                             |  59.981s |814.0MiB|
|n95-0050.smt2                                                                              |  59.285s |813.0MiB|
|0059.smt2                                                                                  |  59.811s |808.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|0066.smt2                                                                                  |  60.050s |2929.0MiB|
|0062.smt2                                                                                  |  59.981s |2695.0MiB|
|0063.smt2                                                                                  |  60.065s |2076.0MiB|
|n29-0036.smt2                                                                              |  60.018s |1715.0MiB|
|n39-0046.smt2                                                                              |  60.024s |1713.0MiB|
|0055.smt2                                                                                  |  59.982s |1410.0MiB|
|0054.smt2                                                                                  |  59.992s |1406.0MiB|
|n45-0052.smt2                                                                              |  59.977s |1306.0MiB|
|n1-0001.smt2                                                                               |  12.541s |1127.0MiB|
|n43-0050.smt2                                                                              |  60.125s |1122.0MiB|
|n70-0024.smt2                                                                              |  60.017s |1048.0MiB|
|n76-0030.smt2                                                                              |  60.031s |1042.0MiB|
|n71-0025.smt2                                                                              |  59.618s |1028.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  59.980s |1001.0MiB|
|n111-0015.smt2                                                                             |  59.995s |905.0MiB|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                |  27.803s |843.0MiB|
|n20-0026.smt2                                                                              |  60.016s |825.0MiB|
|n112-0016.smt2                                                                             |  59.981s |814.0MiB|
|n95-0050.smt2                                                                              |  59.285s |813.0MiB|
|0059.smt2                                                                                  |  59.811s |808.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  59.811s  |  59.811s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.896s  |  59.896s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.065s  |  60.065s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  60.050s  |  60.050s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  59.734s  |  59.734s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.056s  |   1.056s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   6.264s  |   6.264s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  19.538s  |  19.538s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  28.353s  |  28.353s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2                                     |   4.645s  |   4.645s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2                                     |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                     |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2                                     |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                  |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                                                  |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                                                  |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                                                  |   1.523s  |   1.523s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2                                      |  24.069s  |  24.069s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                                                 |  59.909s  |  59.909s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                                                 |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                                                 |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                                                 |   2.510s  |   2.510s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                 |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                                                 |  59.914s  |  59.914s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                                                 |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                                                 |   9.640s  |   9.640s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                                                 |  14.951s  |  14.951s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                                                 |   1.571s  |   1.571s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                                                 |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                                                 |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                                                 |  59.880s  |  59.880s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                                                 |   1.570s  |   1.570s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                                                 |   0.510s  |   0.510s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                                                 |  10.086s  |  10.086s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                 |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2                                     |  41.370s  |  41.370s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                                                 |   3.905s  |   3.905s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                                                 |   7.244s  |   7.244s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                                                 |  60.010s  |  60.010s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                                                 |  59.878s  |  59.878s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                                                 |  59.922s  |  59.922s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2                                     |   5.158s  |   5.158s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2                                     |   4.320s  |   4.320s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                     |  59.908s  |  59.908s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2                                     |  57.148s  |  57.148s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                                                 |  11.199s  |  11.199s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                                                 |   9.620s  |   9.620s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                                                 |  42.636s  |  42.636s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                                                 |  58.163s  |  58.163s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2                                        |   1.036s  |   1.036s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                  |  59.844s  |  59.844s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                                                  |   1.656s  |   1.656s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                                                  |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                                                  |   2.164s  |   2.164s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                 |  27.803s  |  27.803s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                 |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                                                 |   2.880s  |   2.880s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                                                 |  59.931s  |  59.931s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                                                 |   5.019s  |   5.019s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                                                     |   1.196s  |   1.196s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                                                     |  59.895s  |  59.895s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                                                     |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                                                     |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                                                     |  59.924s  |  59.924s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2                                     |  56.828s  |  56.828s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2                                     |  32.220s  |  32.220s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2                                     |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                                                 |  21.058s  |  21.058s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                                                   |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                                                   |  25.582s  |  25.582s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                                                   |  59.611s  |  59.611s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                                                   |   9.664s  |   9.664s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                                                   |  60.014s  |  60.014s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr1_rtl.smt2                                                            |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_ltr_inv_g.smt2                                                      |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_rtl.smt2                                                            |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|int_check_bvsge_bvneg_ltr_inv_g.smt2                                                        |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|int_check_bvsge_bvudiv1_rtl.smt2                                                            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem1_ltr_inv_g.smt2                                                      |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_rtl.smt2                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr0_rtl.smt2                                                            |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr1_ltr_inv_g.smt2                                                      |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr0_rtl.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr1_rtl.smt2                                                            |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvshl0_ltr_inv_g.smt2                                                       |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvshl0_rtl.smt2                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem0_rtl.smt2                                                            |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem1_rtl.smt2                                                            |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|int_check_bvsle_bvadd_ltr_inv_g.smt2                                                        |   0.452s  |   0.452s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr0_ltr_inv_g.smt2                                                      |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr0_rtl.smt2                                                            |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr1_rtl.smt2                                                            |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl0_ltr_inv_g.smt2                                                       |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv0_rtl.smt2                                                            |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_ltr_inv_g.smt2                                                      |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr0_rtl.smt2                                                            |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr1_rtl.smt2                                                            |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr0_ltr_inv_g.smt2                                                      |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr0_rtl.smt2                                                            |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv0_ltr_inv_g.smt2                                                      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr1_ltr_inv_g.smt2                                                      |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr1_rtl.smt2                                                            |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|int_check_bvuge_bvshl0_rtl.smt2                                                             |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem0_rtl.smt2                                                            |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr0_ltr_inv_g.smt2                                                      |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr1_ltr_inv_g.smt2                                                      |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr1_rtl.smt2                                                            |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|int_check_bvugt_bvudiv0_rtl.smt2                                                            |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvugt_bvudiv1_rtl.smt2                                                            |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvugt_bvurem0_rtl.smt2                                                            |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|int_check_bvule_bvneg_ltr_inv_g.smt2                                                        |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv1_ltr_inv_g.smt2                                                      |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvule_bvurem0_ltr_inv_g.smt2                                                      |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|int_check_bvule_bvurem1_ltr_inv_g.smt2                                                      |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr1_rtl.smt2                                                            |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|int_check_bvult_bvneg_ltr_inv_g.smt2                                                        |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_bvult_bvurem0_ltr_inv_g.smt2                                                      |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvult_bvurem1_ltr_inv_g.smt2                                                      |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_eq_bvashr0_rtl.smt2                                                               |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|int_check_eq_bvlshr0_rtl.smt2                                                               |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|int_check_eq_bvudiv0_rtl.smt2                                                               |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|int_check_eq_bvudiv1_rtl.smt2                                                               |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|int_check_eq_bvurem0_ltr_inv_g.smt2                                                         |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|int_check_eq_bvurem0_rtl.smt2                                                               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|int_check_ne_bvashr0_ltr_inv_g.smt2                                                         |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_ltr_inv_g.smt2                                                         |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|n0-0000.smt2                                                                                |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|n1-0001.smt2                                                                                |  12.541s  |  12.541s  |   0.000s  | 0.0%|
|n10-0010.smt2                                                                               |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|n100-0003.smt2                                                                              |   2.289s  |   2.289s  |   0.000s  | 0.0%|
|n101-0004.smt2                                                                              |  59.853s  |  59.853s  |   0.000s  | 0.0%|
|n102-0005.smt2                                                                              |   6.331s  |   6.331s  |   0.000s  | 0.0%|
|n103-0006.smt2                                                                              |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|n104-0007.smt2                                                                              |   2.223s  |   2.223s  |   0.000s  | 0.0%|
|n105-0008.smt2                                                                              |  59.873s  |  59.873s  |   0.000s  | 0.0%|
|n106-0009.smt2                                                                              |  34.345s  |  34.345s  |   0.000s  | 0.0%|
|n107-0011.smt2                                                                              |   7.908s  |   7.908s  |   0.000s  | 0.0%|
|n108-0012.smt2                                                                              |   2.304s  |   2.304s  |   0.000s  | 0.0%|
|n109-0013.smt2                                                                              |  59.858s  |  59.858s  |   0.000s  | 0.0%|
|n11-0012.smt2                                                                               |  52.874s  |  52.874s  |   0.000s  | 0.0%|
|n110-0014.smt2                                                                              |   4.322s  |   4.322s  |   0.000s  | 0.0%|
|n111-0015.smt2                                                                              |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|n112-0016.smt2                                                                              |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|n113-0017.smt2                                                                              |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|n114-0018.smt2                                                                              |  59.829s  |  59.829s  |   0.000s  | 0.0%|
|n115-0019.smt2                                                                              |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|n116-0020.smt2                                                                              |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|n117-0021.smt2                                                                              |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|n118-0022.smt2                                                                              |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|n119-0023.smt2                                                                              |   8.246s  |   8.246s  |   0.000s  | 0.0%|
|n12-0013.smt2                                                                               |   4.500s  |   4.500s  |   0.000s  | 0.0%|
|n120-0024.smt2                                                                              |  59.932s  |  59.932s  |   0.000s  | 0.0%|
|n121-0025.smt2                                                                              |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|n122-0026.smt2                                                                              |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|n123-0027.smt2                                                                              |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|n124-0028.smt2                                                                              |   1.833s  |   1.833s  |   0.000s  | 0.0%|
|n125-0029.smt2                                                                              |   1.757s  |   1.757s  |   0.000s  | 0.0%|
|n126-0030.smt2                                                                              |  59.840s  |  59.840s  |   0.000s  | 0.0%|
|n127-0031.smt2                                                                              |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|n128-0032.smt2                                                                              |   1.940s  |   1.940s  |   0.000s  | 0.0%|
|n129-0033.smt2                                                                              |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|n13-0015.smt2                                                                               |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|n130-0034.smt2                                                                              |  59.920s  |  59.920s  |   0.000s  | 0.0%|
|n131-0035.smt2                                                                              |  17.287s  |  17.287s  |   0.000s  | 0.0%|
|n132-0036.smt2                                                                              |  10.689s  |  10.689s  |   0.000s  | 0.0%|
|n133-0037.smt2                                                                              |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|n134-0038.smt2                                                                              |   3.010s  |   3.010s  |   0.000s  | 0.0%|
|n135-0039.smt2                                                                              |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|n136-0040.smt2                                                                              |  60.016s  |  60.016s  |   0.000s  | 0.0%|
|n137-0041.smt2                                                                              |  59.913s  |  59.913s  |   0.000s  | 0.0%|
|n16-0019.smt2                                                                               |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|n17-0021.smt2                                                                               |   2.346s  |   2.346s  |   0.000s  | 0.0%|
|n18-0022.smt2                                                                               |  17.932s  |  17.932s  |   0.000s  | 0.0%|
|n19-0024.smt2                                                                               |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|n2-0002.smt2                                                                                |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|n20-0026.smt2                                                                               |  60.016s  |  60.016s  |   0.000s  | 0.0%|
|n21-0027.smt2                                                                               |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|n22-0029.smt2                                                                               |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|n23-0030.smt2                                                                               |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|n24-0031.smt2                                                                               |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|n25-0032.smt2                                                                               |  24.939s  |  24.939s  |   0.000s  | 0.0%|
|n26-0033.smt2                                                                               |   6.228s  |   6.228s  |   0.000s  | 0.0%|
|n27-0034.smt2                                                                               |   4.436s  |   4.436s  |   0.000s  | 0.0%|
|n28-0035.smt2                                                                               |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|n29-0036.smt2                                                                               |  60.018s  |  60.018s  |   0.000s  | 0.0%|
|n3-0003.smt2                                                                                |  60.009s  |  60.009s  |   0.000s  | 0.0%|
|n30-0037.smt2                                                                               |  59.574s  |  59.574s  |   0.000s  | 0.0%|
|n31-0038.smt2                                                                               |  34.370s  |  34.370s  |   0.000s  | 0.0%|
|n32-0039.smt2                                                                               |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|n33-0040.smt2                                                                               |  60.024s  |  60.024s  |   0.000s  | 0.0%|
|n34-0041.smt2                                                                               |  10.489s  |  10.489s  |   0.000s  | 0.0%|
|n35-0042.smt2                                                                               |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|n36-0043.smt2                                                                               |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|n37-0044.smt2                                                                               |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|n38-0045.smt2                                                                               |  16.871s  |  16.871s  |   0.000s  | 0.0%|
|n39-0046.smt2                                                                               |  60.024s  |  60.024s  |   0.000s  | 0.0%|
|n4-0004.smt2                                                                                |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|n40-0047.smt2                                                                               |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|n41-0048.smt2                                                                               |   6.921s  |   6.921s  |   0.000s  | 0.0%|
|n42-0049.smt2                                                                               |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|n43-0050.smt2                                                                               |  60.125s  |  60.125s  |   0.000s  | 0.0%|
|n44-0051.smt2                                                                               |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|n45-0052.smt2                                                                               |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|n46-0053.smt2                                                                               |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|n47-0000.smt2                                                                               |   5.291s  |   5.291s  |   0.000s  | 0.0%|
|n48-0001.smt2                                                                               |  56.776s  |  56.776s  |   0.000s  | 0.0%|
|n49-0002.smt2                                                                               |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|n5-0005.smt2                                                                                |   9.445s  |   9.445s  |   0.000s  | 0.0%|
|n50-0003.smt2                                                                               |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|n51-0004.smt2                                                                               |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|n52-0005.smt2                                                                               |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|n53-0006.smt2                                                                               |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|n54-0007.smt2                                                                               |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|n55-0008.smt2                                                                               |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|n56-0009.smt2                                                                               |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|n57-0010.smt2                                                                               |   7.157s  |   7.157s  |   0.000s  | 0.0%|
|n58-0011.smt2                                                                               |  59.895s  |  59.895s  |   0.000s  | 0.0%|
|n59-0012.smt2                                                                               |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|n6-0006.smt2                                                                                |  60.015s  |  60.015s  |   0.000s  | 0.0%|
|n60-0014.smt2                                                                               |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|n61-0015.smt2                                                                               |  10.706s  |  10.706s  |   0.000s  | 0.0%|
|n62-0016.smt2                                                                               |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|n63-0017.smt2                                                                               |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|n64-0018.smt2                                                                               |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|n65-0019.smt2                                                                               |  41.048s  |  41.048s  |   0.000s  | 0.0%|
|n66-0020.smt2                                                                               |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|n67-0021.smt2                                                                               |  60.024s  |  60.024s  |   0.000s  | 0.0%|
|n68-0022.smt2                                                                               |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|n69-0023.smt2                                                                               |  59.906s  |  59.906s  |   0.000s  | 0.0%|
|n7-0007.smt2                                                                                |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|n70-0024.smt2                                                                               |  60.017s  |  60.017s  |   0.000s  | 0.0%|
|n71-0025.smt2                                                                               |  59.618s  |  59.618s  |   0.000s  | 0.0%|
|n72-0026.smt2                                                                               |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|n73-0027.smt2                                                                               |   7.114s  |   7.114s  |   0.000s  | 0.0%|
|n74-0028.smt2                                                                               |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|n75-0029.smt2                                                                               |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|n76-0030.smt2                                                                               |  60.031s  |  60.031s  |   0.000s  | 0.0%|
|n77-0031.smt2                                                                               |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|n78-0032.smt2                                                                               |  60.016s  |  60.016s  |   0.000s  | 0.0%|
|n79-0033.smt2                                                                               |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|n8-0008.smt2                                                                                |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|n80-0034.smt2                                                                               |  60.109s  |  60.109s  |   0.000s  | 0.0%|
|n81-0035.smt2                                                                               |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|n82-0036.smt2                                                                               |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|n83-0037.smt2                                                                               |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|n84-0038.smt2                                                                               |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|n85-0039.smt2                                                                               |  60.046s  |  60.046s  |   0.000s  | 0.0%|
|n86-0040.smt2                                                                               |   1.885s  |   1.885s  |   0.000s  | 0.0%|
|n87-0041.smt2                                                                               |  13.105s  |  13.105s  |   0.000s  | 0.0%|
|n88-0042.smt2                                                                               |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|n89-0044.smt2                                                                               |  58.835s  |  58.835s  |   0.000s  | 0.0%|
|n9-0009.smt2                                                                                |   9.076s  |   9.076s  |   0.000s  | 0.0%|
|n90-0045.smt2                                                                               |   6.003s  |   6.003s  |   0.000s  | 0.0%|
|n91-0046.smt2                                                                               |  59.899s  |  59.899s  |   0.000s  | 0.0%|
|n92-0047.smt2                                                                               |   1.265s  |   1.265s  |   0.000s  | 0.0%|
|n93-0048.smt2                                                                               |  59.286s  |  59.286s  |   0.000s  | 0.0%|
|n94-0049.smt2                                                                               |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|n95-0050.smt2                                                                               |  59.285s  |  59.285s  |   0.000s  | 0.0%|
|n96-0051.smt2                                                                               |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|n97-0000.smt2                                                                               |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|n98-0001.smt2                                                                               |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|n99-0002.smt2                                                                               |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|qf_AddSub_1165_values_0.smt2                                                                |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|qf_AddSub_1574_values_0.smt2                                                                |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|qf_AddSub_1619_values_0.smt2                                                                |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|qf_AndOrXor_1869_values_0.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_1894_values_0.smt2                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_210_values_0.smt2                                                               |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_230_values_0.smt2                                                               |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_2443_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_290_values_7.smt2                                                               |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|qf_AndOrXor_794_values_121.smt2                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_InstCombineShift497a_values_0.smt2                                                       |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_InstCombineShift497b_values_0.smt2                                                       |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_InstCombineShift497c_values_0.smt2                                                       |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_InstCombineShift497d_values_0.smt2                                                       |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|qf_Select_510_values_0.smt2                                                                 |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|qf_Select_575a_values_0.smt2                                                                |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|qf_Select_575b_values_0.smt2                                                                |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_Select_700_values_123.smt2                                                               |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_Select_705_values_0.smt2                                                                 |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_Select_727_values_0.smt2                                                                 |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_muldivrem_152_values_0.smt2                                                              |  11.530s  |  11.530s  |   0.000s  | 0.0%|
|qf_muldivrem_229_values_0.smt2                                                              |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|qf_muldivrem_239_values_0.smt2                                                              |  59.778s  |  59.778s  |   0.000s  | 0.0%|
</details>
