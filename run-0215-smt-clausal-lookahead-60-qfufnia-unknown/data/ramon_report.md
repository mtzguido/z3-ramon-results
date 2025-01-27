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
Z3 commit: f5749502379a3fdecdbae07053f6f188c56c3c3f
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_UNKNOWN
Z3 commit message: fix #7521 (#7531)

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-clausal-lookahead-60-qfufnia-unknown
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: f5749502379a3fdecdbae07053f6f188c56c3c3f
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_UNKNOWN
Z3 commit message: fix #7521 (#7531)

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.051s  |  60.051s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.026s  |  60.026s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.180s  |  59.180s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  59.831s  |  59.831s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   8.007s  |   8.007s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   4.485s  |   4.485s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  60.008s  |  60.008s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  11.929s  |  11.929s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.963s  |  59.963s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.051s  |  60.051s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.026s  |  60.026s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.180s  |  59.180s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  59.831s  |  59.831s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   8.007s  |   8.007s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   4.485s  |   4.485s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  60.008s  |  60.008s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  11.929s  |  11.929s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.963s  |  59.963s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.051s  |  60.051s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.026s  |  60.026s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.180s  |  59.180s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  59.831s  |  59.831s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   8.007s  |   8.007s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   4.485s  |   4.485s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  60.008s  |  60.008s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  11.929s  |  11.929s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.963s  |  59.963s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.051s  |  60.051s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.026s  |  60.026s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.180s  |  59.180s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  59.831s  |  59.831s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   8.007s  |   8.007s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   4.485s  |   4.485s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  60.008s  |  60.008s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  11.929s  |  11.929s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.963s  |  59.963s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2                                    |  61.226s |107.0MiB|
|n62-0016.smt2                                                                              |  60.062s |325.0MiB|
|n29-0036.smt2                                                                              |  60.056s |1714.0MiB|
|0062.smt2                                                                                  |  60.055s |2695.0MiB|
|0055.smt2                                                                                  |  60.055s |1408.0MiB|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2                                    |  60.054s |229.0MiB|
|0059.smt2                                                                                  |  60.051s |841.0MiB|
|n45-0052.smt2                                                                              |  60.042s |1293.0MiB|
|n39-0046.smt2                                                                              |  60.035s |1697.0MiB|
|n20-0026.smt2                                                                              |  60.034s |861.0MiB|
|0063.smt2                                                                                  |  60.026s |2067.0MiB|
|n81-0035.smt2                                                                              |  60.026s |391.0MiB|
|n85-0039.smt2                                                                              |  60.026s |740.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  60.023s |1023.0MiB|
|n67-0021.smt2                                                                              |  60.023s |590.0MiB|
|n95-0050.smt2                                                                              |  60.021s |917.0MiB|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                |  60.021s |653.0MiB|
|n71-0025.smt2                                                                              |  60.015s |1025.0MiB|
|n24-0031.smt2                                                                              |  60.014s |356.0MiB|
|0058.smt2                                                                                  |  60.012s |790.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2                                    |  61.226s |107.0MiB|
|n62-0016.smt2                                                                              |  60.062s |325.0MiB|
|n29-0036.smt2                                                                              |  60.056s |1714.0MiB|
|0062.smt2                                                                                  |  60.055s |2695.0MiB|
|0055.smt2                                                                                  |  60.055s |1408.0MiB|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2                                    |  60.054s |229.0MiB|
|0059.smt2                                                                                  |  60.051s |841.0MiB|
|n45-0052.smt2                                                                              |  60.042s |1293.0MiB|
|n39-0046.smt2                                                                              |  60.035s |1697.0MiB|
|n20-0026.smt2                                                                              |  60.034s |861.0MiB|
|0063.smt2                                                                                  |  60.026s |2067.0MiB|
|n81-0035.smt2                                                                              |  60.026s |391.0MiB|
|n85-0039.smt2                                                                              |  60.026s |740.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  60.023s |1023.0MiB|
|n67-0021.smt2                                                                              |  60.023s |590.0MiB|
|n95-0050.smt2                                                                              |  60.021s |917.0MiB|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                |  60.021s |653.0MiB|
|n71-0025.smt2                                                                              |  60.015s |1025.0MiB|
|n24-0031.smt2                                                                              |  60.014s |356.0MiB|
|0058.smt2                                                                                  |  60.012s |790.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1405.0MiB|1405.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1408.0MiB|1408.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |268.0MiB|268.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |222.0MiB|222.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |790.0MiB|790.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |841.0MiB|841.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |180.0MiB|180.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |184.0MiB|184.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2695.0MiB|2695.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2067.0MiB|2067.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |628.0MiB|628.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |231.0MiB|231.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2562.0MiB|2562.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |449.0MiB|449.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |79.068MiB|79.068MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.592MiB|67.592MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |57.0MiB|57.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |96.172MiB|96.172MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |73.068MiB|73.068MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |134.0MiB|134.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1405.0MiB|1405.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1408.0MiB|1408.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |268.0MiB|268.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |222.0MiB|222.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |790.0MiB|790.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |841.0MiB|841.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |180.0MiB|180.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |184.0MiB|184.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2695.0MiB|2695.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2067.0MiB|2067.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |628.0MiB|628.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |231.0MiB|231.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2562.0MiB|2562.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |449.0MiB|449.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |79.068MiB|79.068MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.592MiB|67.592MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |57.0MiB|57.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |96.172MiB|96.172MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |73.068MiB|73.068MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |134.0MiB|134.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1405.0MiB|1405.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1408.0MiB|1408.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |268.0MiB|268.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |222.0MiB|222.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |790.0MiB|790.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |841.0MiB|841.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |180.0MiB|180.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |184.0MiB|184.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2695.0MiB|2695.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2067.0MiB|2067.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |628.0MiB|628.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |231.0MiB|231.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2562.0MiB|2562.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |449.0MiB|449.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |79.068MiB|79.068MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.592MiB|67.592MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |57.0MiB|57.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |96.172MiB|96.172MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |73.068MiB|73.068MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |134.0MiB|134.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |1405.0MiB|1405.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1408.0MiB|1408.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |268.0MiB|268.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |222.0MiB|222.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |790.0MiB|790.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |841.0MiB|841.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |180.0MiB|180.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |184.0MiB|184.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2695.0MiB|2695.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2067.0MiB|2067.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |628.0MiB|628.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |231.0MiB|231.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2562.0MiB|2562.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |449.0MiB|449.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |79.068MiB|79.068MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |67.592MiB|67.592MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |57.0MiB|57.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |96.172MiB|96.172MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |73.068MiB|73.068MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |134.0MiB|134.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|0062.smt2                                                                                  |  60.055s |2695.0MiB|
|0066.smt2                                                                                  |  59.831s |2562.0MiB|
|0063.smt2                                                                                  |  60.026s |2067.0MiB|
|n29-0036.smt2                                                                              |  60.056s |1714.0MiB|
|n39-0046.smt2                                                                              |  60.035s |1697.0MiB|
|0055.smt2                                                                                  |  60.055s |1408.0MiB|
|0054.smt2                                                                                  |  59.957s |1405.0MiB|
|n45-0052.smt2                                                                              |  60.042s |1293.0MiB|
|n1-0001.smt2                                                                               |  11.691s |1131.0MiB|
|n43-0050.smt2                                                                              |  59.973s |1095.0MiB|
|n70-0024.smt2                                                                              |  59.942s |1047.0MiB|
|n76-0030.smt2                                                                              |  59.856s |1045.0MiB|
|n71-0025.smt2                                                                              |  60.015s |1025.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  60.023s |1023.0MiB|
|n111-0015.smt2                                                                             |  60.010s |951.0MiB|
|n95-0050.smt2                                                                              |  60.021s |917.0MiB|
|n20-0026.smt2                                                                              |  60.034s |861.0MiB|
|n112-0016.smt2                                                                             |  59.994s |859.0MiB|
|0059.smt2                                                                                  |  60.051s |841.0MiB|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                |  22.846s |827.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|0062.smt2                                                                                  |  60.055s |2695.0MiB|
|0066.smt2                                                                                  |  59.831s |2562.0MiB|
|0063.smt2                                                                                  |  60.026s |2067.0MiB|
|n29-0036.smt2                                                                              |  60.056s |1714.0MiB|
|n39-0046.smt2                                                                              |  60.035s |1697.0MiB|
|0055.smt2                                                                                  |  60.055s |1408.0MiB|
|0054.smt2                                                                                  |  59.957s |1405.0MiB|
|n45-0052.smt2                                                                              |  60.042s |1293.0MiB|
|n1-0001.smt2                                                                               |  11.691s |1131.0MiB|
|n43-0050.smt2                                                                              |  59.973s |1095.0MiB|
|n70-0024.smt2                                                                              |  59.942s |1047.0MiB|
|n76-0030.smt2                                                                              |  59.856s |1045.0MiB|
|n71-0025.smt2                                                                              |  60.015s |1025.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  60.023s |1023.0MiB|
|n111-0015.smt2                                                                             |  60.010s |951.0MiB|
|n95-0050.smt2                                                                              |  60.021s |917.0MiB|
|n20-0026.smt2                                                                              |  60.034s |861.0MiB|
|n112-0016.smt2                                                                             |  59.994s |859.0MiB|
|0059.smt2                                                                                  |  60.051s |841.0MiB|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                |  22.846s |827.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  60.051s  |  60.051s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  60.026s  |  60.026s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  59.180s  |  59.180s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  59.831s  |  59.831s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   8.007s  |   8.007s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   4.485s  |   4.485s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  60.008s  |  60.008s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  11.929s  |  11.929s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2                                     |  61.226s  |  61.226s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2                                     |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                     |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2                                     |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                  |  60.023s  |  60.023s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                                                  |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                                                  |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                                                  |   1.590s  |   1.590s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2                                      |  22.905s  |  22.905s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                                                 |  59.868s  |  59.868s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                                                 |   4.588s  |   4.588s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                                                 |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                                                 |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                 |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                                                 |  12.324s  |  12.324s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                                                 |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                                                 |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                                                 |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                                                 |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                                                 |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                                                 |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                                                 |  59.911s  |  59.911s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                                                 |   2.050s  |   2.050s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                                                 |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                                                 |   4.935s  |   4.935s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                 |  60.021s  |  60.021s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2                                     |  60.054s  |  60.054s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                                                 |   4.273s  |   4.273s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                                                 |   6.713s  |   6.713s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                                                 |  59.754s  |  59.754s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                                                 |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                                                 |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2                                     |   6.192s  |   6.192s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2                                     |   4.274s  |   4.274s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                     |  59.888s  |  59.888s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2                                     |  47.628s  |  47.628s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                                                 |  11.372s  |  11.372s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                                                 |   8.903s  |   8.903s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                                                 |  23.372s  |  23.372s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                                                 |  32.509s  |  32.509s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2                                        |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                  |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                                                  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                                                  |  58.379s  |  58.379s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                                                  |   1.364s  |   1.364s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                 |  22.846s  |  22.846s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                 |  59.594s  |  59.594s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                                                 |   9.351s  |   9.351s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                                                 |  59.731s  |  59.731s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                                                 |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                                                     |   0.911s  |   0.911s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                                                     |   7.757s  |   7.757s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                                                     |  31.153s  |  31.153s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                                                     |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                                                     |  59.890s  |  59.890s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2                                     |  34.212s  |  34.212s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2                                     |  59.883s  |  59.883s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2                                     |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                                                 |  10.468s  |  10.468s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                                                   |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                                                   |  24.478s  |  24.478s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                                                   |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                                                   |   9.108s  |   9.108s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                                                   |  59.909s  |  59.909s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr1_rtl.smt2                                                            |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_ltr_inv_g.smt2                                                      |   3.052s  |   3.052s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_rtl.smt2                                                            |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvsge_bvneg_ltr_inv_g.smt2                                                        |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|int_check_bvsge_bvudiv1_rtl.smt2                                                            |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem1_ltr_inv_g.smt2                                                      |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_rtl.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr0_rtl.smt2                                                            |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr1_ltr_inv_g.smt2                                                      |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr0_rtl.smt2                                                            |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr1_rtl.smt2                                                            |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvshl0_ltr_inv_g.smt2                                                       |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvshl0_rtl.smt2                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem0_rtl.smt2                                                            |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem1_rtl.smt2                                                            |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|int_check_bvsle_bvadd_ltr_inv_g.smt2                                                        |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr0_ltr_inv_g.smt2                                                      |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr0_rtl.smt2                                                            |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr1_rtl.smt2                                                            |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl0_ltr_inv_g.smt2                                                       |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv0_rtl.smt2                                                            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_ltr_inv_g.smt2                                                      |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr0_rtl.smt2                                                            |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr1_rtl.smt2                                                            |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr0_ltr_inv_g.smt2                                                      |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr0_rtl.smt2                                                            |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv0_ltr_inv_g.smt2                                                      |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr1_ltr_inv_g.smt2                                                      |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr1_rtl.smt2                                                            |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvuge_bvshl0_rtl.smt2                                                             |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem0_rtl.smt2                                                            |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr0_ltr_inv_g.smt2                                                      |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr1_ltr_inv_g.smt2                                                      |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr1_rtl.smt2                                                            |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|int_check_bvugt_bvudiv0_rtl.smt2                                                            |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvugt_bvudiv1_rtl.smt2                                                            |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvugt_bvurem0_rtl.smt2                                                            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|int_check_bvule_bvneg_ltr_inv_g.smt2                                                        |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv1_ltr_inv_g.smt2                                                      |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvule_bvurem0_ltr_inv_g.smt2                                                      |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvule_bvurem1_ltr_inv_g.smt2                                                      |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr1_rtl.smt2                                                            |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|int_check_bvult_bvneg_ltr_inv_g.smt2                                                        |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvult_bvurem0_ltr_inv_g.smt2                                                      |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvult_bvurem1_ltr_inv_g.smt2                                                      |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_eq_bvashr0_rtl.smt2                                                               |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|int_check_eq_bvlshr0_rtl.smt2                                                               |  59.924s  |  59.924s  |   0.000s  | 0.0%|
|int_check_eq_bvudiv0_rtl.smt2                                                               |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|int_check_eq_bvudiv1_rtl.smt2                                                               |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|int_check_eq_bvurem0_ltr_inv_g.smt2                                                         |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|int_check_eq_bvurem0_rtl.smt2                                                               |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|int_check_ne_bvashr0_ltr_inv_g.smt2                                                         |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_ltr_inv_g.smt2                                                         |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|n0-0000.smt2                                                                                |  43.828s  |  43.828s  |   0.000s  | 0.0%|
|n1-0001.smt2                                                                                |  11.691s  |  11.691s  |   0.000s  | 0.0%|
|n10-0010.smt2                                                                               |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|n100-0003.smt2                                                                              |   2.849s  |   2.849s  |   0.000s  | 0.0%|
|n101-0004.smt2                                                                              |   1.891s  |   1.891s  |   0.000s  | 0.0%|
|n102-0005.smt2                                                                              |  11.106s  |  11.106s  |   0.000s  | 0.0%|
|n103-0006.smt2                                                                              |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|n104-0007.smt2                                                                              |   2.355s  |   2.355s  |   0.000s  | 0.0%|
|n105-0008.smt2                                                                              |   8.994s  |   8.994s  |   0.000s  | 0.0%|
|n106-0009.smt2                                                                              |  49.034s  |  49.034s  |   0.000s  | 0.0%|
|n107-0011.smt2                                                                              |   8.428s  |   8.428s  |   0.000s  | 0.0%|
|n108-0012.smt2                                                                              |   2.394s  |   2.394s  |   0.000s  | 0.0%|
|n109-0013.smt2                                                                              |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|n11-0012.smt2                                                                               |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|n110-0014.smt2                                                                              |   2.434s  |   2.434s  |   0.000s  | 0.0%|
|n111-0015.smt2                                                                              |  60.010s  |  60.010s  |   0.000s  | 0.0%|
|n112-0016.smt2                                                                              |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|n113-0017.smt2                                                                              |  59.604s  |  59.604s  |   0.000s  | 0.0%|
|n114-0018.smt2                                                                              |  19.480s  |  19.480s  |   0.000s  | 0.0%|
|n115-0019.smt2                                                                              |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|n116-0020.smt2                                                                              |  59.915s  |  59.915s  |   0.000s  | 0.0%|
|n117-0021.smt2                                                                              |  59.909s  |  59.909s  |   0.000s  | 0.0%|
|n118-0022.smt2                                                                              |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|n119-0023.smt2                                                                              |   7.841s  |   7.841s  |   0.000s  | 0.0%|
|n12-0013.smt2                                                                               |   4.316s  |   4.316s  |   0.000s  | 0.0%|
|n120-0024.smt2                                                                              |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|n121-0025.smt2                                                                              |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|n122-0026.smt2                                                                              |  59.904s  |  59.904s  |   0.000s  | 0.0%|
|n123-0027.smt2                                                                              |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|n124-0028.smt2                                                                              |   1.374s  |   1.374s  |   0.000s  | 0.0%|
|n125-0029.smt2                                                                              |   1.109s  |   1.109s  |   0.000s  | 0.0%|
|n126-0030.smt2                                                                              |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|n127-0031.smt2                                                                              |   9.405s  |   9.405s  |   0.000s  | 0.0%|
|n128-0032.smt2                                                                              |   1.999s  |   1.999s  |   0.000s  | 0.0%|
|n129-0033.smt2                                                                              |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|n13-0015.smt2                                                                               |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|n130-0034.smt2                                                                              |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|n131-0035.smt2                                                                              |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|n132-0036.smt2                                                                              |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|n133-0037.smt2                                                                              |  59.899s  |  59.899s  |   0.000s  | 0.0%|
|n134-0038.smt2                                                                              |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|n135-0039.smt2                                                                              |   2.934s  |   2.934s  |   0.000s  | 0.0%|
|n136-0040.smt2                                                                              |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|n137-0041.smt2                                                                              |  20.640s  |  20.640s  |   0.000s  | 0.0%|
|n16-0019.smt2                                                                               |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|n17-0021.smt2                                                                               |   2.321s  |   2.321s  |   0.000s  | 0.0%|
|n18-0022.smt2                                                                               |   4.322s  |   4.322s  |   0.000s  | 0.0%|
|n19-0024.smt2                                                                               |  56.100s  |  56.100s  |   0.000s  | 0.0%|
|n2-0002.smt2                                                                                |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|n20-0026.smt2                                                                               |  60.034s  |  60.034s  |   0.000s  | 0.0%|
|n21-0027.smt2                                                                               |  59.850s  |  59.850s  |   0.000s  | 0.0%|
|n22-0029.smt2                                                                               |  59.850s  |  59.850s  |   0.000s  | 0.0%|
|n23-0030.smt2                                                                               |  55.186s  |  55.186s  |   0.000s  | 0.0%|
|n24-0031.smt2                                                                               |  60.014s  |  60.014s  |   0.000s  | 0.0%|
|n25-0032.smt2                                                                               |  22.877s  |  22.877s  |   0.000s  | 0.0%|
|n26-0033.smt2                                                                               |   6.128s  |   6.128s  |   0.000s  | 0.0%|
|n27-0034.smt2                                                                               |   4.295s  |   4.295s  |   0.000s  | 0.0%|
|n28-0035.smt2                                                                               |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|n29-0036.smt2                                                                               |  60.056s  |  60.056s  |   0.000s  | 0.0%|
|n3-0003.smt2                                                                                |  37.592s  |  37.592s  |   0.000s  | 0.0%|
|n30-0037.smt2                                                                               |   4.432s  |   4.432s  |   0.000s  | 0.0%|
|n31-0038.smt2                                                                               |  24.809s  |  24.809s  |   0.000s  | 0.0%|
|n32-0039.smt2                                                                               |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|n33-0040.smt2                                                                               |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|n34-0041.smt2                                                                               |  11.301s  |  11.301s  |   0.000s  | 0.0%|
|n35-0042.smt2                                                                               |  24.755s  |  24.755s  |   0.000s  | 0.0%|
|n36-0043.smt2                                                                               |  59.902s  |  59.902s  |   0.000s  | 0.0%|
|n37-0044.smt2                                                                               |  10.594s  |  10.594s  |   0.000s  | 0.0%|
|n38-0045.smt2                                                                               |  15.052s  |  15.052s  |   0.000s  | 0.0%|
|n39-0046.smt2                                                                               |  60.035s  |  60.035s  |   0.000s  | 0.0%|
|n4-0004.smt2                                                                                |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|n40-0047.smt2                                                                               |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|n41-0048.smt2                                                                               |   6.620s  |   6.620s  |   0.000s  | 0.0%|
|n42-0049.smt2                                                                               |  59.797s  |  59.797s  |   0.000s  | 0.0%|
|n43-0050.smt2                                                                               |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|n44-0051.smt2                                                                               |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|n45-0052.smt2                                                                               |  60.042s  |  60.042s  |   0.000s  | 0.0%|
|n46-0053.smt2                                                                               |  29.271s  |  29.271s  |   0.000s  | 0.0%|
|n47-0000.smt2                                                                               |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|n48-0001.smt2                                                                               |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|n49-0002.smt2                                                                               |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|n5-0005.smt2                                                                                |  10.223s  |  10.223s  |   0.000s  | 0.0%|
|n50-0003.smt2                                                                               |  59.653s  |  59.653s  |   0.000s  | 0.0%|
|n51-0004.smt2                                                                               |  59.909s  |  59.909s  |   0.000s  | 0.0%|
|n52-0005.smt2                                                                               |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|n53-0006.smt2                                                                               |   8.614s  |   8.614s  |   0.000s  | 0.0%|
|n54-0007.smt2                                                                               |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|n55-0008.smt2                                                                               |   7.415s  |   7.415s  |   0.000s  | 0.0%|
|n56-0009.smt2                                                                               |  59.821s  |  59.821s  |   0.000s  | 0.0%|
|n57-0010.smt2                                                                               |   6.958s  |   6.958s  |   0.000s  | 0.0%|
|n58-0011.smt2                                                                               |   8.361s  |   8.361s  |   0.000s  | 0.0%|
|n59-0012.smt2                                                                               |  14.844s  |  14.844s  |   0.000s  | 0.0%|
|n6-0006.smt2                                                                                |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|n60-0014.smt2                                                                               |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|n61-0015.smt2                                                                               |  11.056s  |  11.056s  |   0.000s  | 0.0%|
|n62-0016.smt2                                                                               |  60.062s  |  60.062s  |   0.000s  | 0.0%|
|n63-0017.smt2                                                                               |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|n64-0018.smt2                                                                               |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|n65-0019.smt2                                                                               |   2.053s  |   2.053s  |   0.000s  | 0.0%|
|n66-0020.smt2                                                                               |  59.870s  |  59.870s  |   0.000s  | 0.0%|
|n67-0021.smt2                                                                               |  60.023s  |  60.023s  |   0.000s  | 0.0%|
|n68-0022.smt2                                                                               |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|n69-0023.smt2                                                                               |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|n7-0007.smt2                                                                                |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|n70-0024.smt2                                                                               |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|n71-0025.smt2                                                                               |  60.015s  |  60.015s  |   0.000s  | 0.0%|
|n72-0026.smt2                                                                               |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|n73-0027.smt2                                                                               |   8.809s  |   8.809s  |   0.000s  | 0.0%|
|n74-0028.smt2                                                                               |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|n75-0029.smt2                                                                               |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|n76-0030.smt2                                                                               |  59.856s  |  59.856s  |   0.000s  | 0.0%|
|n77-0031.smt2                                                                               |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|n78-0032.smt2                                                                               |  59.933s  |  59.933s  |   0.000s  | 0.0%|
|n79-0033.smt2                                                                               |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|n8-0008.smt2                                                                                |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|n80-0034.smt2                                                                               |  59.866s  |  59.866s  |   0.000s  | 0.0%|
|n81-0035.smt2                                                                               |  60.026s  |  60.026s  |   0.000s  | 0.0%|
|n82-0036.smt2                                                                               |  59.892s  |  59.892s  |   0.000s  | 0.0%|
|n83-0037.smt2                                                                               |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|n84-0038.smt2                                                                               |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|n85-0039.smt2                                                                               |  60.026s  |  60.026s  |   0.000s  | 0.0%|
|n86-0040.smt2                                                                               |   0.817s  |   0.817s  |   0.000s  | 0.0%|
|n87-0041.smt2                                                                               |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|n88-0042.smt2                                                                               |  12.611s  |  12.611s  |   0.000s  | 0.0%|
|n89-0044.smt2                                                                               |  59.147s  |  59.147s  |   0.000s  | 0.0%|
|n9-0009.smt2                                                                                |   9.563s  |   9.563s  |   0.000s  | 0.0%|
|n90-0045.smt2                                                                               |   7.142s  |   7.142s  |   0.000s  | 0.0%|
|n91-0046.smt2                                                                               |  56.217s  |  56.217s  |   0.000s  | 0.0%|
|n92-0047.smt2                                                                               |   1.340s  |   1.340s  |   0.000s  | 0.0%|
|n93-0048.smt2                                                                               |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|n94-0049.smt2                                                                               |  59.688s  |  59.688s  |   0.000s  | 0.0%|
|n95-0050.smt2                                                                               |  60.021s  |  60.021s  |   0.000s  | 0.0%|
|n96-0051.smt2                                                                               |  11.913s  |  11.913s  |   0.000s  | 0.0%|
|n97-0000.smt2                                                                               |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|n98-0001.smt2                                                                               |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|n99-0002.smt2                                                                               |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|qf_AddSub_1165_values_0.smt2                                                                |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|qf_AddSub_1574_values_0.smt2                                                                |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|qf_AddSub_1619_values_0.smt2                                                                |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|qf_AndOrXor_1869_values_0.smt2                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_1894_values_0.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_210_values_0.smt2                                                               |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_230_values_0.smt2                                                               |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_2443_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_290_values_7.smt2                                                               |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_AndOrXor_794_values_121.smt2                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_InstCombineShift497a_values_0.smt2                                                       |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_InstCombineShift497b_values_0.smt2                                                       |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_InstCombineShift497c_values_0.smt2                                                       |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|qf_InstCombineShift497d_values_0.smt2                                                       |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|qf_Select_510_values_0.smt2                                                                 |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|qf_Select_575a_values_0.smt2                                                                |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_Select_575b_values_0.smt2                                                                |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_Select_700_values_123.smt2                                                               |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|qf_Select_705_values_0.smt2                                                                 |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_Select_727_values_0.smt2                                                                 |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_muldivrem_152_values_0.smt2                                                              |  11.410s  |  11.410s  |   0.000s  | 0.0%|
|qf_muldivrem_229_values_0.smt2                                                              |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|qf_muldivrem_239_values_0.smt2                                                              |  59.977s  |  59.977s  |   0.000s  | 0.0%|
</details>
