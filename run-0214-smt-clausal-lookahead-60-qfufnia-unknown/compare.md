Comparing data and data


# SUMMARY
- LHS tests = 297
- RHS tests = 297
- LHS success = 288  (96.96969696969697%)
- RHS success = 288  (96.96969696969697%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-clausal-lookahead-60-qfufnia-unknown
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: d3bf25ce856f3ea316b69e82dd762f907dbd8e4b
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_UNKNOWN
Z3 commit message: throttle value smt -> sls

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-clausal-lookahead-60-qfufnia-unknown
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: d3bf25ce856f3ea316b69e82dd762f907dbd8e4b
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_UNKNOWN
Z3 commit message: throttle value smt -> sls

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.043s  |  60.043s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.064s  |  60.064s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  60.122s  |  60.122s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.808s  |  59.808s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   8.266s  |   8.266s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   4.963s  |   4.963s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  12.370s  |  12.370s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.963s  |  59.963s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.043s  |  60.043s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.064s  |  60.064s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  60.122s  |  60.122s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.808s  |  59.808s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   8.266s  |   8.266s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   4.963s  |   4.963s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  12.370s  |  12.370s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.963s  |  59.963s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.043s  |  60.043s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.064s  |  60.064s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  60.122s  |  60.122s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.808s  |  59.808s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   8.266s  |   8.266s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   4.963s  |   4.963s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  12.370s  |  12.370s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.963s  |  59.963s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.043s  |  60.043s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.064s  |  60.064s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  60.122s  |  60.122s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.808s  |  59.808s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   8.266s  |   8.266s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   4.963s  |   4.963s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  12.370s  |  12.370s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.963s  |  59.963s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n112-0016.smt2                                                                             |  60.267s |857.0MiB|
|0064.smt2                                                                                  |  60.122s |630.0MiB|
|0063.smt2                                                                                  |  60.064s |2014.0MiB|
|n39-0046.smt2                                                                              |  60.052s |1694.0MiB|
|n43-0050.smt2                                                                              |  60.043s |1101.0MiB|
|0062.smt2                                                                                  |  60.043s |2698.0MiB|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                |  60.035s |652.0MiB|
|n95-0050.smt2                                                                              |  60.034s |916.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                |  60.033s |776.0MiB|
|n118-0022.smt2                                                                             |  60.029s |506.0MiB|
|int_check_eq_bvlshr0_rtl.smt2                                                              |  60.026s |118.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  60.018s |1021.0MiB|
|n117-0021.smt2                                                                             |  60.018s |375.0MiB|
|n131-0035.smt2                                                                             |  60.018s |66.584MiB|
|n62-0016.smt2                                                                              |  60.015s |325.0MiB|
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                                                  |  60.015s |336.0MiB|
|n77-0031.smt2                                                                              |  60.014s |668.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2                                    |  60.013s |243.0MiB|
|n85-0039.smt2                                                                              |  60.013s |720.0MiB|
|n111-0015.smt2                                                                             |  60.013s |965.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n112-0016.smt2                                                                             |  60.267s |857.0MiB|
|0064.smt2                                                                                  |  60.122s |630.0MiB|
|0063.smt2                                                                                  |  60.064s |2014.0MiB|
|n39-0046.smt2                                                                              |  60.052s |1694.0MiB|
|n43-0050.smt2                                                                              |  60.043s |1101.0MiB|
|0062.smt2                                                                                  |  60.043s |2698.0MiB|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                |  60.035s |652.0MiB|
|n95-0050.smt2                                                                              |  60.034s |916.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                |  60.033s |776.0MiB|
|n118-0022.smt2                                                                             |  60.029s |506.0MiB|
|int_check_eq_bvlshr0_rtl.smt2                                                              |  60.026s |118.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  60.018s |1021.0MiB|
|n117-0021.smt2                                                                             |  60.018s |375.0MiB|
|n131-0035.smt2                                                                             |  60.018s |66.584MiB|
|n62-0016.smt2                                                                              |  60.015s |325.0MiB|
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                                                  |  60.015s |336.0MiB|
|n77-0031.smt2                                                                              |  60.014s |668.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2                                    |  60.013s |243.0MiB|
|n85-0039.smt2                                                                              |  60.013s |720.0MiB|
|n111-0015.smt2                                                                             |  60.013s |965.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1408.0MiB|1408.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1405.0MiB|1405.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |267.0MiB|267.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |222.0MiB|222.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |788.0MiB|788.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |844.0MiB|844.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |180.0MiB|180.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |183.0MiB|183.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2698.0MiB|2698.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2014.0MiB|2014.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |630.0MiB|630.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |230.0MiB|230.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2890.0MiB|2890.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |449.0MiB|449.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |79.06MiB|79.06MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.604MiB|67.604MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |56.888MiB|56.888MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |96.364MiB|96.364MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |73.288MiB|73.288MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |134.0MiB|134.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1408.0MiB|1408.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1405.0MiB|1405.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |267.0MiB|267.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |222.0MiB|222.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |788.0MiB|788.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |844.0MiB|844.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |180.0MiB|180.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |183.0MiB|183.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2698.0MiB|2698.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2014.0MiB|2014.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |630.0MiB|630.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |230.0MiB|230.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2890.0MiB|2890.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |449.0MiB|449.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |79.06MiB|79.06MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.604MiB|67.604MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |56.888MiB|56.888MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |96.364MiB|96.364MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |73.288MiB|73.288MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |134.0MiB|134.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1408.0MiB|1408.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1405.0MiB|1405.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |267.0MiB|267.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |222.0MiB|222.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |788.0MiB|788.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |844.0MiB|844.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |180.0MiB|180.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |183.0MiB|183.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2698.0MiB|2698.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2014.0MiB|2014.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |630.0MiB|630.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |230.0MiB|230.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2890.0MiB|2890.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |449.0MiB|449.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |79.06MiB|79.06MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.604MiB|67.604MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |56.888MiB|56.888MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |96.364MiB|96.364MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |73.288MiB|73.288MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |134.0MiB|134.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1408.0MiB|1408.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1405.0MiB|1405.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |267.0MiB|267.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |222.0MiB|222.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |788.0MiB|788.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |844.0MiB|844.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |180.0MiB|180.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |183.0MiB|183.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2698.0MiB|2698.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2014.0MiB|2014.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |630.0MiB|630.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |230.0MiB|230.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2890.0MiB|2890.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |449.0MiB|449.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |79.06MiB|79.06MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.604MiB|67.604MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |56.888MiB|56.888MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |96.364MiB|96.364MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |73.288MiB|73.288MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |134.0MiB|134.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|0066.smt2                                                                                  |  59.990s |2890.0MiB|
|0062.smt2                                                                                  |  60.043s |2698.0MiB|
|0063.smt2                                                                                  |  60.064s |2014.0MiB|
|n29-0036.smt2                                                                              |  59.971s |1719.0MiB|
|n39-0046.smt2                                                                              |  60.052s |1694.0MiB|
|0054.smt2                                                                                  |  59.923s |1408.0MiB|
|0055.smt2                                                                                  |  60.011s |1405.0MiB|
|n45-0052.smt2                                                                              |  60.008s |1298.0MiB|
|n1-0001.smt2                                                                               |  11.651s |1129.0MiB|
|n43-0050.smt2                                                                              |  60.043s |1101.0MiB|
|n70-0024.smt2                                                                              |  59.959s |1045.0MiB|
|n76-0030.smt2                                                                              |  59.805s |1039.0MiB|
|n71-0025.smt2                                                                              |  59.976s |1024.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  60.018s |1021.0MiB|
|n111-0015.smt2                                                                             |  60.013s |965.0MiB|
|n95-0050.smt2                                                                              |  60.034s |916.0MiB|
|n20-0026.smt2                                                                              |  60.005s |869.0MiB|
|n112-0016.smt2                                                                             |  60.267s |857.0MiB|
|0059.smt2                                                                                  |  59.926s |844.0MiB|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                |  23.761s |823.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|0066.smt2                                                                                  |  59.990s |2890.0MiB|
|0062.smt2                                                                                  |  60.043s |2698.0MiB|
|0063.smt2                                                                                  |  60.064s |2014.0MiB|
|n29-0036.smt2                                                                              |  59.971s |1719.0MiB|
|n39-0046.smt2                                                                              |  60.052s |1694.0MiB|
|0054.smt2                                                                                  |  59.923s |1408.0MiB|
|0055.smt2                                                                                  |  60.011s |1405.0MiB|
|n45-0052.smt2                                                                              |  60.008s |1298.0MiB|
|n1-0001.smt2                                                                               |  11.651s |1129.0MiB|
|n43-0050.smt2                                                                              |  60.043s |1101.0MiB|
|n70-0024.smt2                                                                              |  59.959s |1045.0MiB|
|n76-0030.smt2                                                                              |  59.805s |1039.0MiB|
|n71-0025.smt2                                                                              |  59.976s |1024.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  60.018s |1021.0MiB|
|n111-0015.smt2                                                                             |  60.013s |965.0MiB|
|n95-0050.smt2                                                                              |  60.034s |916.0MiB|
|n20-0026.smt2                                                                              |  60.005s |869.0MiB|
|n112-0016.smt2                                                                             |  60.267s |857.0MiB|
|0059.smt2                                                                                  |  59.926s |844.0MiB|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                |  23.761s |823.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.043s  |  60.043s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.064s  |  60.064s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  60.122s  |  60.122s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.808s  |  59.808s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   8.266s  |   8.266s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   4.963s  |   4.963s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  12.370s  |  12.370s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2                                     |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2                                     |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                     |  59.909s  |  59.909s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2                                     |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                  |  60.018s  |  60.018s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                                                  |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                                                  |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                                                  |   1.559s  |   1.559s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2                                      |  24.357s  |  24.357s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                                                 |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                                                 |   4.863s  |   4.863s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                                                 |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                                                 |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                 |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                                                 |  13.032s  |  13.032s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                                                 |  59.919s  |  59.919s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                                                 |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                                                 |   0.785s  |   0.785s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                                                 |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                                                 |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                                                 |  59.893s  |  59.893s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                                                 |  59.919s  |  59.919s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                                                 |   3.293s  |   3.293s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                                                 |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                                                 |   4.601s  |   4.601s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                 |  60.035s  |  60.035s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2                                     |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                                                 |   4.264s  |   4.264s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                                                 |   6.632s  |   6.632s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                                                 |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                                                 |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                                                 |  59.890s  |  59.890s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2                                     |   5.815s  |   5.815s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2                                     |   4.258s  |   4.258s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                     |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2                                     |  46.975s  |  46.975s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                                                 |  10.523s  |  10.523s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                                                 |   8.834s  |   8.834s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                                                 |  25.173s  |  25.173s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                                                 |  31.700s  |  31.700s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2                                        |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                  |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                                                  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                                                  |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                                                  |   1.392s  |   1.392s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                 |  23.761s  |  23.761s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                 |  60.033s  |  60.033s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                                                 |  10.043s  |  10.043s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                                                 |  59.906s  |  59.906s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                                                 |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                                                     |   0.945s  |   0.945s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                                                     |   8.288s  |   8.288s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                                                     |  32.387s  |  32.387s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                                                     |  59.572s  |  59.572s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                                                     |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2                                     |  36.040s  |  36.040s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2                                     |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2                                     |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                                                 |  10.242s  |  10.242s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                                                   |  60.015s  |  60.015s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                                                   |  23.270s  |  23.270s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                                                   |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                                                   |   9.517s  |   9.517s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                                                   |  60.010s  |  60.010s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr1_rtl.smt2                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_ltr_inv_g.smt2                                                      |   3.254s  |   3.254s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_rtl.smt2                                                            |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvsge_bvneg_ltr_inv_g.smt2                                                        |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|int_check_bvsge_bvudiv1_rtl.smt2                                                            |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem1_ltr_inv_g.smt2                                                      |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_rtl.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr0_rtl.smt2                                                            |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr1_ltr_inv_g.smt2                                                      |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr0_rtl.smt2                                                            |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr1_rtl.smt2                                                            |   0.360s  |   0.360s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvshl0_ltr_inv_g.smt2                                                       |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvshl0_rtl.smt2                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem0_rtl.smt2                                                            |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem1_rtl.smt2                                                            |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|int_check_bvsle_bvadd_ltr_inv_g.smt2                                                        |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr0_ltr_inv_g.smt2                                                      |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr0_rtl.smt2                                                            |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr1_rtl.smt2                                                            |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl0_ltr_inv_g.smt2                                                       |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv0_rtl.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_ltr_inv_g.smt2                                                      |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr0_rtl.smt2                                                            |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr1_rtl.smt2                                                            |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr0_ltr_inv_g.smt2                                                      |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr0_rtl.smt2                                                            |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv0_ltr_inv_g.smt2                                                      |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr1_ltr_inv_g.smt2                                                      |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr1_rtl.smt2                                                            |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvuge_bvshl0_rtl.smt2                                                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem0_rtl.smt2                                                            |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr0_ltr_inv_g.smt2                                                      |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr1_ltr_inv_g.smt2                                                      |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr1_rtl.smt2                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|int_check_bvugt_bvudiv0_rtl.smt2                                                            |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvugt_bvudiv1_rtl.smt2                                                            |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvugt_bvurem0_rtl.smt2                                                            |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|int_check_bvule_bvneg_ltr_inv_g.smt2                                                        |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv1_ltr_inv_g.smt2                                                      |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvule_bvurem0_ltr_inv_g.smt2                                                      |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvule_bvurem1_ltr_inv_g.smt2                                                      |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr1_rtl.smt2                                                            |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|int_check_bvult_bvneg_ltr_inv_g.smt2                                                        |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvult_bvurem0_ltr_inv_g.smt2                                                      |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvult_bvurem1_ltr_inv_g.smt2                                                      |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_eq_bvashr0_rtl.smt2                                                               |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|int_check_eq_bvlshr0_rtl.smt2                                                               |  60.026s  |  60.026s  |   0.000s  | 0.0%|
|int_check_eq_bvudiv0_rtl.smt2                                                               |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|int_check_eq_bvudiv1_rtl.smt2                                                               |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|int_check_eq_bvurem0_ltr_inv_g.smt2                                                         |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|int_check_eq_bvurem0_rtl.smt2                                                               |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|int_check_ne_bvashr0_ltr_inv_g.smt2                                                         |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_ltr_inv_g.smt2                                                         |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|n0-0000.smt2                                                                                |  42.267s  |  42.267s  |   0.000s  | 0.0%|
|n1-0001.smt2                                                                                |  11.651s  |  11.651s  |   0.000s  | 0.0%|
|n10-0010.smt2                                                                               |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|n100-0003.smt2                                                                              |   2.765s  |   2.765s  |   0.000s  | 0.0%|
|n101-0004.smt2                                                                              |   1.900s  |   1.900s  |   0.000s  | 0.0%|
|n102-0005.smt2                                                                              |  11.693s  |  11.693s  |   0.000s  | 0.0%|
|n103-0006.smt2                                                                              |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|n104-0007.smt2                                                                              |   2.228s  |   2.228s  |   0.000s  | 0.0%|
|n106-0009.smt2                                                                              |  47.368s  |  47.368s  |   0.000s  | 0.0%|
|n107-0011.smt2                                                                              |   8.450s  |   8.450s  |   0.000s  | 0.0%|
|n108-0012.smt2                                                                              |   2.384s  |   2.384s  |   0.000s  | 0.0%|
|n109-0013.smt2                                                                              |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|n11-0012.smt2                                                                               |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|n110-0014.smt2                                                                              |   2.849s  |   2.849s  |   0.000s  | 0.0%|
|n111-0015.smt2                                                                              |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|n112-0016.smt2                                                                              |  60.267s  |  60.267s  |   0.000s  | 0.0%|
|n113-0017.smt2                                                                              |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|n114-0018.smt2                                                                              |  19.738s  |  19.738s  |   0.000s  | 0.0%|
|n115-0019.smt2                                                                              |  59.854s  |  59.854s  |   0.000s  | 0.0%|
|n116-0020.smt2                                                                              |  59.828s  |  59.828s  |   0.000s  | 0.0%|
|n117-0021.smt2                                                                              |  60.018s  |  60.018s  |   0.000s  | 0.0%|
|n118-0022.smt2                                                                              |  60.029s  |  60.029s  |   0.000s  | 0.0%|
|n119-0023.smt2                                                                              |   8.003s  |   8.003s  |   0.000s  | 0.0%|
|n12-0013.smt2                                                                               |   4.220s  |   4.220s  |   0.000s  | 0.0%|
|n120-0024.smt2                                                                              |  59.825s  |  59.825s  |   0.000s  | 0.0%|
|n121-0025.smt2                                                                              |  59.932s  |  59.932s  |   0.000s  | 0.0%|
|n122-0026.smt2                                                                              |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|n123-0027.smt2                                                                              |  59.765s  |  59.765s  |   0.000s  | 0.0%|
|n126-0030.smt2                                                                              |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|n127-0031.smt2                                                                              |   9.251s  |   9.251s  |   0.000s  | 0.0%|
|n128-0032.smt2                                                                              |   1.886s  |   1.886s  |   0.000s  | 0.0%|
|n129-0033.smt2                                                                              |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|n13-0015.smt2                                                                               |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|n130-0034.smt2                                                                              |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|n131-0035.smt2                                                                              |  60.018s  |  60.018s  |   0.000s  | 0.0%|
|n132-0036.smt2                                                                              |  59.903s  |  59.903s  |   0.000s  | 0.0%|
|n133-0037.smt2                                                                              |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|n135-0039.smt2                                                                              |   2.827s  |   2.827s  |   0.000s  | 0.0%|
|n136-0040.smt2                                                                              |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|n137-0041.smt2                                                                              |  22.334s  |  22.334s  |   0.000s  | 0.0%|
|n16-0019.smt2                                                                               |  59.894s  |  59.894s  |   0.000s  | 0.0%|
|n17-0021.smt2                                                                               |   2.302s  |   2.302s  |   0.000s  | 0.0%|
|n18-0022.smt2                                                                               |   3.992s  |   3.992s  |   0.000s  | 0.0%|
|n19-0024.smt2                                                                               |  56.140s  |  56.140s  |   0.000s  | 0.0%|
|n2-0002.smt2                                                                                |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|n20-0026.smt2                                                                               |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|n21-0027.smt2                                                                               |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|n22-0029.smt2                                                                               |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|n23-0030.smt2                                                                               |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|n24-0031.smt2                                                                               |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|n25-0032.smt2                                                                               |  22.945s  |  22.945s  |   0.000s  | 0.0%|
|n26-0033.smt2                                                                               |   5.756s  |   5.756s  |   0.000s  | 0.0%|
|n27-0034.smt2                                                                               |   4.369s  |   4.369s  |   0.000s  | 0.0%|
|n28-0035.smt2                                                                               |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|n29-0036.smt2                                                                               |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|n3-0003.smt2                                                                                |  37.664s  |  37.664s  |   0.000s  | 0.0%|
|n30-0037.smt2                                                                               |   4.478s  |   4.478s  |   0.000s  | 0.0%|
|n31-0038.smt2                                                                               |  24.695s  |  24.695s  |   0.000s  | 0.0%|
|n32-0039.smt2                                                                               |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|n33-0040.smt2                                                                               |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|n34-0041.smt2                                                                               |  12.449s  |  12.449s  |   0.000s  | 0.0%|
|n35-0042.smt2                                                                               |  23.681s  |  23.681s  |   0.000s  | 0.0%|
|n36-0043.smt2                                                                               |  59.888s  |  59.888s  |   0.000s  | 0.0%|
|n37-0044.smt2                                                                               |  10.427s  |  10.427s  |   0.000s  | 0.0%|
|n38-0045.smt2                                                                               |  14.455s  |  14.455s  |   0.000s  | 0.0%|
|n39-0046.smt2                                                                               |  60.052s  |  60.052s  |   0.000s  | 0.0%|
|n4-0004.smt2                                                                                |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|n40-0047.smt2                                                                               |  60.008s  |  60.008s  |   0.000s  | 0.0%|
|n41-0048.smt2                                                                               |   6.322s  |   6.322s  |   0.000s  | 0.0%|
|n42-0049.smt2                                                                               |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|n43-0050.smt2                                                                               |  60.043s  |  60.043s  |   0.000s  | 0.0%|
|n44-0051.smt2                                                                               |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|n45-0052.smt2                                                                               |  60.008s  |  60.008s  |   0.000s  | 0.0%|
|n46-0053.smt2                                                                               |  30.292s  |  30.292s  |   0.000s  | 0.0%|
|n47-0000.smt2                                                                               |  59.909s  |  59.909s  |   0.000s  | 0.0%|
|n48-0001.smt2                                                                               |  59.914s  |  59.914s  |   0.000s  | 0.0%|
|n49-0002.smt2                                                                               |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|n5-0005.smt2                                                                                |  10.352s  |  10.352s  |   0.000s  | 0.0%|
|n50-0003.smt2                                                                               |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|n51-0004.smt2                                                                               |  59.919s  |  59.919s  |   0.000s  | 0.0%|
|n52-0005.smt2                                                                               |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|n53-0006.smt2                                                                               |   9.015s  |   9.015s  |   0.000s  | 0.0%|
|n54-0007.smt2                                                                               |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|n55-0008.smt2                                                                               |   6.942s  |   6.942s  |   0.000s  | 0.0%|
|n56-0009.smt2                                                                               |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|n57-0010.smt2                                                                               |   7.406s  |   7.406s  |   0.000s  | 0.0%|
|n58-0011.smt2                                                                               |   8.385s  |   8.385s  |   0.000s  | 0.0%|
|n6-0006.smt2                                                                                |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|n60-0014.smt2                                                                               |  59.854s  |  59.854s  |   0.000s  | 0.0%|
|n61-0015.smt2                                                                               |  10.434s  |  10.434s  |   0.000s  | 0.0%|
|n62-0016.smt2                                                                               |  60.015s  |  60.015s  |   0.000s  | 0.0%|
|n63-0017.smt2                                                                               |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|n64-0018.smt2                                                                               |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|n66-0020.smt2                                                                               |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|n67-0021.smt2                                                                               |  59.811s  |  59.811s  |   0.000s  | 0.0%|
|n68-0022.smt2                                                                               |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|n69-0023.smt2                                                                               |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|n7-0007.smt2                                                                                |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|n70-0024.smt2                                                                               |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|n71-0025.smt2                                                                               |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|n72-0026.smt2                                                                               |  60.004s  |  60.004s  |   0.000s  | 0.0%|
|n73-0027.smt2                                                                               |   8.689s  |   8.689s  |   0.000s  | 0.0%|
|n74-0028.smt2                                                                               |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|n75-0029.smt2                                                                               |  59.893s  |  59.893s  |   0.000s  | 0.0%|
|n76-0030.smt2                                                                               |  59.805s  |  59.805s  |   0.000s  | 0.0%|
|n77-0031.smt2                                                                               |  60.014s  |  60.014s  |   0.000s  | 0.0%|
|n78-0032.smt2                                                                               |  59.889s  |  59.889s  |   0.000s  | 0.0%|
|n79-0033.smt2                                                                               |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|n8-0008.smt2                                                                                |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|n80-0034.smt2                                                                               |  59.771s  |  59.771s  |   0.000s  | 0.0%|
|n81-0035.smt2                                                                               |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|n82-0036.smt2                                                                               |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|n83-0037.smt2                                                                               |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|n84-0038.smt2                                                                               |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|n85-0039.smt2                                                                               |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|n87-0041.smt2                                                                               |  59.879s  |  59.879s  |   0.000s  | 0.0%|
|n89-0044.smt2                                                                               |  56.344s  |  56.344s  |   0.000s  | 0.0%|
|n9-0009.smt2                                                                                |   9.997s  |   9.997s  |   0.000s  | 0.0%|
|n90-0045.smt2                                                                               |   7.223s  |   7.223s  |   0.000s  | 0.0%|
|n91-0046.smt2                                                                               |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|n92-0047.smt2                                                                               |   1.154s  |   1.154s  |   0.000s  | 0.0%|
|n93-0048.smt2                                                                               |  59.875s  |  59.875s  |   0.000s  | 0.0%|
|n94-0049.smt2                                                                               |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|n95-0050.smt2                                                                               |  60.034s  |  60.034s  |   0.000s  | 0.0%|
|n96-0051.smt2                                                                               |  12.252s  |  12.252s  |   0.000s  | 0.0%|
|n97-0000.smt2                                                                               |  59.328s  |  59.328s  |   0.000s  | 0.0%|
|n98-0001.smt2                                                                               |  59.905s  |  59.905s  |   0.000s  | 0.0%|
|qf_AddSub_1165_values_0.smt2                                                                |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|qf_AddSub_1574_values_0.smt2                                                                |   0.608s  |   0.608s  |   0.000s  | 0.0%|
|qf_AddSub_1619_values_0.smt2                                                                |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|qf_AndOrXor_1869_values_0.smt2                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_1894_values_0.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_210_values_0.smt2                                                               |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_230_values_0.smt2                                                               |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_2443_values_0.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_290_values_7.smt2                                                               |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_794_values_121.smt2                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_InstCombineShift497a_values_0.smt2                                                       |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_InstCombineShift497b_values_0.smt2                                                       |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_InstCombineShift497c_values_0.smt2                                                       |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_InstCombineShift497d_values_0.smt2                                                       |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|qf_Select_510_values_0.smt2                                                                 |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|qf_Select_575a_values_0.smt2                                                                |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_Select_575b_values_0.smt2                                                                |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_Select_700_values_123.smt2                                                               |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_Select_705_values_0.smt2                                                                 |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_Select_727_values_0.smt2                                                                 |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_muldivrem_152_values_0.smt2                                                              |  10.951s  |  10.951s  |   0.000s  | 0.0%|
|qf_muldivrem_229_values_0.smt2                                                              |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|qf_muldivrem_239_values_0.smt2                                                              |  59.980s  |  59.980s  |   0.000s  | 0.0%|
</details>
