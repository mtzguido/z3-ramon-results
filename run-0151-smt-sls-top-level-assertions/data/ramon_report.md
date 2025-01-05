Comparing data and data


# SUMMARY
- LHS tests = 2000
- RHS tests = 2000
- LHS success = 1984  (99.2%)
- RHS success = 1984  (99.2%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-top-level-assertions
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 71a4801c1d39f36db00f1dfdedc1b10cf9cdfb34
Z3 branch: master
Z3 options: "-T:20 -v:2  sls.bv_use_top_level_assertions=true -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true "
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: add shortcuts to convert to python objects in cases of numerals and strings

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-top-level-assertions
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 71a4801c1d39f36db00f1dfdedc1b10cf9cdfb34
Z3 branch: master
Z3 options: "-T:20 -v:2  sls.bv_use_top_level_assertions=true -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true "
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: add shortcuts to convert to python objects in cases of numerals and strings

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.823s  |  19.823s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.842s  |  19.842s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |  19.867s  |  19.867s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |  19.643s  |  19.643s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  19.692s  |  19.692s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  19.811s  |  19.811s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  19.896s  |  19.896s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  19.793s  |  19.793s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.634s  |  19.634s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.737s  |  19.737s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  19.637s  |  19.637s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  19.651s  |  19.651s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  19.662s  |  19.662s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.740s  |  19.740s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.823s  |  19.823s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.842s  |  19.842s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |  19.867s  |  19.867s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |  19.643s  |  19.643s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  19.692s  |  19.692s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  19.811s  |  19.811s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  19.896s  |  19.896s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  19.793s  |  19.793s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.634s  |  19.634s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.737s  |  19.737s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  19.637s  |  19.637s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  19.651s  |  19.651s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  19.662s  |  19.662s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.740s  |  19.740s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.823s  |  19.823s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.842s  |  19.842s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |  19.867s  |  19.867s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |  19.643s  |  19.643s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  19.692s  |  19.692s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  19.811s  |  19.811s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  19.896s  |  19.896s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  19.793s  |  19.793s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.634s  |  19.634s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.737s  |  19.737s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  19.637s  |  19.637s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  19.651s  |  19.651s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  19.662s  |  19.662s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.740s  |  19.740s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.823s  |  19.823s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.842s  |  19.842s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |  19.867s  |  19.867s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |  19.643s  |  19.643s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  19.692s  |  19.692s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  19.811s  |  19.811s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  19.896s  |  19.896s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  19.793s  |  19.793s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.634s  |  19.634s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.737s  |  19.737s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  19.637s  |  19.637s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  19.651s  |  19.651s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  19.662s  |  19.662s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.740s  |  19.740s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_4256.smt2                                                                            |  20.003s |18.76MiB|
|bin_libsmbsharemodes_vc5748.smt2                                                           |  20.001s |27.968MiB|
|bin_libsmbsharemodes_vc5794.smt2                                                           |  20.000s |23.688MiB|
|fig5.phx.smt2                                                                              |  20.000s |19.564MiB|
|bin_libsmbsharemodes_vc6255.smt2                                                           |  19.999s |25.704MiB|
|bench_1496.smt2                                                                            |  19.999s |18.744MiB|
|bench_6882.smt2                                                                            |  19.998s |20.488MiB|
|bench_5223.smt2                                                                            |  19.998s |18.716MiB|
|bin_libsmbsharemodes_vc7727.smt2                                                           |  19.998s |27.704MiB|
|rand_150_600_1159731678_15.lp.smt2                                                         |  19.997s |26.84MiB|
|bench_208.smt2                                                                             |  19.997s |20.388MiB|
|bin_libsmbsharemodes_vc7120.smt2                                                           |  19.996s |24.696MiB|
|bench_826.smt2                                                                             |  19.996s |19.88MiB|
|bench_368.smt2                                                                             |  19.996s |20.24MiB|
|bench_5421.smt2                                                                            |  19.996s |18.832MiB|
|bench_2974.smt2                                                                            |  19.995s |20.496MiB|
|bench_247.smt2                                                                             |  19.994s |20.304MiB|
|bench_2831.smt2                                                                            |  19.994s |18.772MiB|
|bin_libmsrpc_vc1225824.smt2                                                                |  19.993s |23.972MiB|
|bin_libsmbsharemodes_vc5749.smt2                                                           |  19.993s |27.476MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_4256.smt2                                                                            |  20.003s |18.76MiB|
|bin_libsmbsharemodes_vc5748.smt2                                                           |  20.001s |27.968MiB|
|bin_libsmbsharemodes_vc5794.smt2                                                           |  20.000s |23.688MiB|
|fig5.phx.smt2                                                                              |  20.000s |19.564MiB|
|bin_libsmbsharemodes_vc6255.smt2                                                           |  19.999s |25.704MiB|
|bench_1496.smt2                                                                            |  19.999s |18.744MiB|
|bench_6882.smt2                                                                            |  19.998s |20.488MiB|
|bench_5223.smt2                                                                            |  19.998s |18.716MiB|
|bin_libsmbsharemodes_vc7727.smt2                                                           |  19.998s |27.704MiB|
|rand_150_600_1159731678_15.lp.smt2                                                         |  19.997s |26.84MiB|
|bench_208.smt2                                                                             |  19.997s |20.388MiB|
|bin_libsmbsharemodes_vc7120.smt2                                                           |  19.996s |24.696MiB|
|bench_826.smt2                                                                             |  19.996s |19.88MiB|
|bench_368.smt2                                                                             |  19.996s |20.24MiB|
|bench_5421.smt2                                                                            |  19.996s |18.832MiB|
|bench_2974.smt2                                                                            |  19.995s |20.496MiB|
|bench_247.smt2                                                                             |  19.994s |20.304MiB|
|bench_2831.smt2                                                                            |  19.994s |18.772MiB|
|bin_libmsrpc_vc1225824.smt2                                                                |  19.993s |23.972MiB|
|bin_libsmbsharemodes_vc5749.smt2                                                           |  19.993s |27.476MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |23.756MiB|23.756MiB|0B| 0.0%|
|100.smt2                                                                                    |24.776MiB|24.776MiB|0B| 0.0%|
|102.smt2                                                                                    |26.08MiB|26.08MiB|0B| 0.0%|
|108.smt2                                                                                    |38.28MiB|38.28MiB|0B| 0.0%|
|111.smt2                                                                                    |38.396MiB|38.396MiB|0B| 0.0%|
|113.smt2                                                                                    |23.516MiB|23.516MiB|0B| 0.0%|
|115.smt2                                                                                    |27.864MiB|27.864MiB|0B| 0.0%|
|15.smt2                                                                                     |23.288MiB|23.288MiB|0B| 0.0%|
|162.smt2                                                                                    |32.164MiB|32.164MiB|0B| 0.0%|
|170.smt2                                                                                    |32.06MiB|32.06MiB|0B| 0.0%|
|20.smt2                                                                                     |24.632MiB|24.632MiB|0B| 0.0%|
|26.smt2                                                                                     |23.564MiB|23.564MiB|0B| 0.0%|
|29.smt2                                                                                     |24.544MiB|24.544MiB|0B| 0.0%|
|33.smt2                                                                                     |23.444MiB|23.444MiB|0B| 0.0%|
|41.smt2                                                                                     |22.484MiB|22.484MiB|0B| 0.0%|
|64.smt2                                                                                     |26.312MiB|26.312MiB|0B| 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |25.356MiB|25.356MiB|0B| 0.0%|
|80.smt2                                                                                     |26.084MiB|26.084MiB|0B| 0.0%|
|90.smt2                                                                                     |26.076MiB|26.076MiB|0B| 0.0%|
|94.smt2                                                                                     |26.084MiB|26.084MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |23.756MiB|23.756MiB|0B| 0.0%|
|100.smt2                                                                                    |24.776MiB|24.776MiB|0B| 0.0%|
|102.smt2                                                                                    |26.08MiB|26.08MiB|0B| 0.0%|
|108.smt2                                                                                    |38.28MiB|38.28MiB|0B| 0.0%|
|111.smt2                                                                                    |38.396MiB|38.396MiB|0B| 0.0%|
|113.smt2                                                                                    |23.516MiB|23.516MiB|0B| 0.0%|
|115.smt2                                                                                    |27.864MiB|27.864MiB|0B| 0.0%|
|15.smt2                                                                                     |23.288MiB|23.288MiB|0B| 0.0%|
|162.smt2                                                                                    |32.164MiB|32.164MiB|0B| 0.0%|
|170.smt2                                                                                    |32.06MiB|32.06MiB|0B| 0.0%|
|20.smt2                                                                                     |24.632MiB|24.632MiB|0B| 0.0%|
|26.smt2                                                                                     |23.564MiB|23.564MiB|0B| 0.0%|
|29.smt2                                                                                     |24.544MiB|24.544MiB|0B| 0.0%|
|33.smt2                                                                                     |23.444MiB|23.444MiB|0B| 0.0%|
|41.smt2                                                                                     |22.484MiB|22.484MiB|0B| 0.0%|
|64.smt2                                                                                     |26.312MiB|26.312MiB|0B| 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |25.356MiB|25.356MiB|0B| 0.0%|
|80.smt2                                                                                     |26.084MiB|26.084MiB|0B| 0.0%|
|90.smt2                                                                                     |26.076MiB|26.076MiB|0B| 0.0%|
|94.smt2                                                                                     |26.084MiB|26.084MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |23.756MiB|23.756MiB|0B| 0.0%|
|100.smt2                                                                                    |24.776MiB|24.776MiB|0B| 0.0%|
|102.smt2                                                                                    |26.08MiB|26.08MiB|0B| 0.0%|
|108.smt2                                                                                    |38.28MiB|38.28MiB|0B| 0.0%|
|111.smt2                                                                                    |38.396MiB|38.396MiB|0B| 0.0%|
|113.smt2                                                                                    |23.516MiB|23.516MiB|0B| 0.0%|
|115.smt2                                                                                    |27.864MiB|27.864MiB|0B| 0.0%|
|15.smt2                                                                                     |23.288MiB|23.288MiB|0B| 0.0%|
|162.smt2                                                                                    |32.164MiB|32.164MiB|0B| 0.0%|
|170.smt2                                                                                    |32.06MiB|32.06MiB|0B| 0.0%|
|20.smt2                                                                                     |24.632MiB|24.632MiB|0B| 0.0%|
|26.smt2                                                                                     |23.564MiB|23.564MiB|0B| 0.0%|
|29.smt2                                                                                     |24.544MiB|24.544MiB|0B| 0.0%|
|33.smt2                                                                                     |23.444MiB|23.444MiB|0B| 0.0%|
|41.smt2                                                                                     |22.484MiB|22.484MiB|0B| 0.0%|
|64.smt2                                                                                     |26.312MiB|26.312MiB|0B| 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |25.356MiB|25.356MiB|0B| 0.0%|
|80.smt2                                                                                     |26.084MiB|26.084MiB|0B| 0.0%|
|90.smt2                                                                                     |26.076MiB|26.076MiB|0B| 0.0%|
|94.smt2                                                                                     |26.084MiB|26.084MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |23.756MiB|23.756MiB|0B| 0.0%|
|100.smt2                                                                                    |24.776MiB|24.776MiB|0B| 0.0%|
|102.smt2                                                                                    |26.08MiB|26.08MiB|0B| 0.0%|
|108.smt2                                                                                    |38.28MiB|38.28MiB|0B| 0.0%|
|111.smt2                                                                                    |38.396MiB|38.396MiB|0B| 0.0%|
|113.smt2                                                                                    |23.516MiB|23.516MiB|0B| 0.0%|
|115.smt2                                                                                    |27.864MiB|27.864MiB|0B| 0.0%|
|15.smt2                                                                                     |23.288MiB|23.288MiB|0B| 0.0%|
|162.smt2                                                                                    |32.164MiB|32.164MiB|0B| 0.0%|
|170.smt2                                                                                    |32.06MiB|32.06MiB|0B| 0.0%|
|20.smt2                                                                                     |24.632MiB|24.632MiB|0B| 0.0%|
|26.smt2                                                                                     |23.564MiB|23.564MiB|0B| 0.0%|
|29.smt2                                                                                     |24.544MiB|24.544MiB|0B| 0.0%|
|33.smt2                                                                                     |23.444MiB|23.444MiB|0B| 0.0%|
|41.smt2                                                                                     |22.484MiB|22.484MiB|0B| 0.0%|
|64.smt2                                                                                     |26.312MiB|26.312MiB|0B| 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |25.356MiB|25.356MiB|0B| 0.0%|
|80.smt2                                                                                     |26.084MiB|26.084MiB|0B| 0.0%|
|90.smt2                                                                                     |26.076MiB|26.076MiB|0B| 0.0%|
|94.smt2                                                                                     |26.084MiB|26.084MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|servers_slapd_a_vc149789.smt2                                                              |  19.977s |178.0MiB|
|smulov4bw1024.smt2                                                                         |  19.871s |94.432MiB|
|servers_slapd_a_vc149572.smt2                                                              |   1.023s |75.964MiB|
|ndist.b.28982.smt2                                                                         |   2.039s |72.792MiB|
|ndist.b.27984.smt2                                                                         |   1.928s |69.416MiB|
|ndist.b.21996.smt2                                                                         |   1.270s |50.136MiB|
|111.smt2                                                                                   |  19.988s |38.396MiB|
|108.smt2                                                                                   |  19.842s |38.28MiB|
|run_00012.trace.cond_057573_0x16388_00.smt2                                                |   0.028s |35.404MiB|
|162.smt2                                                                                   |  19.962s |32.164MiB|
|170.smt2                                                                                   |  19.935s |32.06MiB|
|gryzzles.22.lp.smt2                                                                        |  19.961s |31.516MiB|
|knightTour.in01.smt2                                                                       |  19.676s |31.132MiB|
|div.c.20.smt2                                                                              |  19.772s |30.48MiB|
|div3.c.20.smt2                                                                             |  19.443s |30.416MiB|
|gryzzles.8.lp.smt2                                                                         |  19.971s |30.348MiB|
|rand_200_800_1159728969_10.lp.smt2                                                         |  19.892s |29.988MiB|
|mobiledevice_bit8_na6_nr3_twocond.smt2                                                     |  19.505s |29.204MiB|
|bench_3945.smt2                                                                            |   0.097s |29.108MiB|
|bin_libsmbsharemodes_vc7750.smt2                                                           |  19.856s |29.032MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|servers_slapd_a_vc149789.smt2                                                              |  19.977s |178.0MiB|
|smulov4bw1024.smt2                                                                         |  19.871s |94.432MiB|
|servers_slapd_a_vc149572.smt2                                                              |   1.023s |75.964MiB|
|ndist.b.28982.smt2                                                                         |   2.039s |72.792MiB|
|ndist.b.27984.smt2                                                                         |   1.928s |69.416MiB|
|ndist.b.21996.smt2                                                                         |   1.270s |50.136MiB|
|111.smt2                                                                                   |  19.988s |38.396MiB|
|108.smt2                                                                                   |  19.842s |38.28MiB|
|run_00012.trace.cond_057573_0x16388_00.smt2                                                |   0.028s |35.404MiB|
|162.smt2                                                                                   |  19.962s |32.164MiB|
|170.smt2                                                                                   |  19.935s |32.06MiB|
|gryzzles.22.lp.smt2                                                                        |  19.961s |31.516MiB|
|knightTour.in01.smt2                                                                       |  19.676s |31.132MiB|
|div.c.20.smt2                                                                              |  19.772s |30.48MiB|
|div3.c.20.smt2                                                                             |  19.443s |30.416MiB|
|gryzzles.8.lp.smt2                                                                         |  19.971s |30.348MiB|
|rand_200_800_1159728969_10.lp.smt2                                                         |  19.892s |29.988MiB|
|mobiledevice_bit8_na6_nr3_twocond.smt2                                                     |  19.505s |29.204MiB|
|bench_3945.smt2                                                                            |   0.097s |29.108MiB|
|bin_libsmbsharemodes_vc7750.smt2                                                           |  19.856s |29.032MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.823s  |  19.823s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.842s  |  19.842s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |  19.867s  |  19.867s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |  19.643s  |  19.643s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  19.692s  |  19.692s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  19.811s  |  19.811s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  19.896s  |  19.896s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  19.793s  |  19.793s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.634s  |  19.634s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.737s  |  19.737s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  19.637s  |  19.637s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  19.651s  |  19.651s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  19.662s  |  19.662s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.740s  |  19.740s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  19.813s  |  19.813s  |   0.000s  | 0.0%|
|Example_16.txt.smt2                                                                         |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|Example_17.txt.smt2                                                                         |  19.939s  |  19.939s  |   0.000s  | 0.0%|
|Example_9.txt.smt2                                                                          |  19.483s  |  19.483s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                       |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.4.prop1_cc_ref_max.smt2                                       |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_schedule_world.1.prop1_cc_ref_max.smt2                                         |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_swap_three_cc_ref_max.smt2                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                        |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_eq_sdp_v4_cc_ref_max.smt2                                                       |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_resistance.2.prop1_cc_ref_max.smt2                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_swap_two_cc_ref_max.smt2                                                        |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_synabs_cc_ref_max.smt2                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_BV_counter_v_cc_ref_max.smt2                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_BV_eq_sdp_v5_cc_ref_max.smt2                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_BV_protocols.1.prop1_cc_ref_max.smt2                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_BV_v_Unidec_cc_ref_max.smt2                                                              |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|Sz512_15128_0.smt2                                                                          |  19.904s  |  19.904s  |   0.000s  | 0.0%|
|Sz512_15128_1.smt2                                                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Sz512_15128_2.smt2                                                                          |  19.417s  |  19.417s  |   0.000s  | 0.0%|
|Sz512_15128_3.smt2                                                                          |  19.908s  |  19.908s  |   0.000s  | 0.0%|
|VS3-benchmark-S1.smt2                                                                       |  19.904s  |  19.904s  |   0.000s  | 0.0%|
|a128test0016.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a164test0005.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a167test0001.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a185test0001.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a208test0005.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a213test0012.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a214test0017.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a217test0011.smt2                                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|a218test0003.smt2                                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|a222test0008.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a324test0010.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a330test0007.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a331test0008.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a333test0009.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a335test0041.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a392test0051.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|a393test0014.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a397test0029.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a402test0032.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a406test0030.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a407test0024.smt2                                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|a409test0002.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a421test0007.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a423test0008.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a430test0028.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a434test0027.smt2                                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|a448test0003.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a479test0010.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a494test0007.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a497test0020.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a503test0089.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a55test0003.smt2                                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a58test0007.smt2                                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a600test0040.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a601test0056.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|a603test0055.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a605test0062.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a60test0004.smt2                                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a611test0014.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a613test0087.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a614test0091.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a616test0001.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a620test0100.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a623test0035.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a625test0095.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a628test0066.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a631test0073.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a640test0019.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a649test0047.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a653test0023.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a657test0107.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a658test0026.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a663test0096.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a664test0013.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a665test0064.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a668test0098.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a669test0063.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a674test0008.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a676test0004.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a681test0048.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a683test0094.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a685test0080.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a689test0069.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a695test0015.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a97test0001.smt2                                                                            |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|adpcm.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|b188test0002.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|b265test0001.smt2                                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|b26test0001.smt2                                                                            |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1.smt2                                                                                |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|bench_10033.smt2                                                                            |  19.730s  |  19.730s  |   0.000s  | 0.0%|
|bench_10096.smt2                                                                            |  10.433s  |  10.433s  |   0.000s  | 0.0%|
|bench_10111.smt2                                                                            |  19.912s  |  19.912s  |   0.000s  | 0.0%|
|bench_1012.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_10127.smt2                                                                            |   2.066s  |   2.066s  |   0.000s  | 0.0%|
|bench_1013.smt2                                                                             |  19.948s  |  19.948s  |   0.000s  | 0.0%|
|bench_10144.smt2                                                                            |   2.623s  |   2.623s  |   0.000s  | 0.0%|
|bench_1017.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_102.smt2                                                                              |  19.765s  |  19.765s  |   0.000s  | 0.0%|
|bench_10228.smt2                                                                            |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_10306.smt2                                                                            |  19.731s  |  19.731s  |   0.000s  | 0.0%|
|bench_1041.smt2                                                                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|bench_1043.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_10451.smt2                                                                            |   9.027s  |   9.027s  |   0.000s  | 0.0%|
|bench_1050.smt2                                                                             |  19.889s  |  19.889s  |   0.000s  | 0.0%|
|bench_1053.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_1055.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_10579.smt2                                                                            |  19.908s  |  19.908s  |   0.000s  | 0.0%|
|bench_1059.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1063.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_10696.smt2                                                                            |  19.861s  |  19.861s  |   0.000s  | 0.0%|
|bench_10714.smt2                                                                            |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_10726.smt2                                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_10737.smt2                                                                            |  19.808s  |  19.808s  |   0.000s  | 0.0%|
|bench_10784.smt2                                                                            |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|bench_10791.smt2                                                                            |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|bench_10800.smt2                                                                            |   0.762s  |   0.762s  |   0.000s  | 0.0%|
|bench_1081.smt2                                                                             |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|bench_10815.smt2                                                                            |   1.717s  |   1.717s  |   0.000s  | 0.0%|
|bench_1082.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_10832.smt2                                                                            |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_10841.smt2                                                                            |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|bench_1088.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1093.smt2                                                                             |  19.679s  |  19.679s  |   0.000s  | 0.0%|
|bench_1094.smt2                                                                             |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|bench_10940.smt2                                                                            |  19.815s  |  19.815s  |   0.000s  | 0.0%|
|bench_1099.smt2                                                                             |  19.949s  |  19.949s  |   0.000s  | 0.0%|
|bench_11014.smt2                                                                            |  19.627s  |  19.627s  |   0.000s  | 0.0%|
|bench_11027.smt2                                                                            |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_11032.smt2                                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_11033.smt2                                                                            |  19.820s  |  19.820s  |   0.000s  | 0.0%|
|bench_1106.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1111.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1113.smt2                                                                             |  19.851s  |  19.851s  |   0.000s  | 0.0%|
|bench_11151.smt2                                                                            |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|bench_112.smt2                                                                              |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|bench_1123.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_11232.smt2                                                                            |  19.762s  |  19.762s  |   0.000s  | 0.0%|
|bench_113.smt2                                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_11341.smt2                                                                            |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bench_11357.smt2                                                                            |  12.411s  |  12.411s  |   0.000s  | 0.0%|
|bench_1136.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_11408.smt2                                                                            |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|bench_1143.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_1145.smt2                                                                             |  19.674s  |  19.674s  |   0.000s  | 0.0%|
|bench_11473.smt2                                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_1159.smt2                                                                             |  19.767s  |  19.767s  |   0.000s  | 0.0%|
|bench_1166.smt2                                                                             |  19.854s  |  19.854s  |   0.000s  | 0.0%|
|bench_1168.smt2                                                                             |  19.919s  |  19.919s  |   0.000s  | 0.0%|
|bench_11696.smt2                                                                            |  19.856s  |  19.856s  |   0.000s  | 0.0%|
|bench_11708.smt2                                                                            |  19.858s  |  19.858s  |   0.000s  | 0.0%|
|bench_11736.smt2                                                                            |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|bench_1179.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_1180.smt2                                                                             |  19.839s  |  19.839s  |   0.000s  | 0.0%|
|bench_11811.smt2                                                                            |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_11826.smt2                                                                            |  19.893s  |  19.893s  |   0.000s  | 0.0%|
|bench_1184.smt2                                                                             |  19.562s  |  19.562s  |   0.000s  | 0.0%|
|bench_1187.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_119.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_11931.smt2                                                                            |   9.003s  |   9.003s  |   0.000s  | 0.0%|
|bench_1196.smt2                                                                             |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|bench_11971.smt2                                                                            |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_1199.smt2                                                                             |   7.709s  |   7.709s  |   0.000s  | 0.0%|
|bench_120.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_12006.smt2                                                                            |  19.926s  |  19.926s  |   0.000s  | 0.0%|
|bench_1201.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1202.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_1204.smt2                                                                             |  17.838s  |  17.838s  |   0.000s  | 0.0%|
|bench_12059.smt2                                                                            |  19.895s  |  19.895s  |   0.000s  | 0.0%|
|bench_12158.smt2                                                                            |  19.840s  |  19.840s  |   0.000s  | 0.0%|
|bench_1218.smt2                                                                             |  19.746s  |  19.746s  |   0.000s  | 0.0%|
|bench_12204.smt2                                                                            |  19.768s  |  19.768s  |   0.000s  | 0.0%|
|bench_1222.smt2                                                                             |  19.644s  |  19.644s  |   0.000s  | 0.0%|
|bench_12224.smt2                                                                            |  19.519s  |  19.519s  |   0.000s  | 0.0%|
|bench_12246.smt2                                                                            |  19.561s  |  19.561s  |   0.000s  | 0.0%|
|bench_1228.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1229.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1233.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1235.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1236.smt2                                                                             |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|bench_12422.smt2                                                                            |  19.910s  |  19.910s  |   0.000s  | 0.0%|
|bench_12473.smt2                                                                            |  19.940s  |  19.940s  |   0.000s  | 0.0%|
|bench_1249.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_1250.smt2                                                                             |  19.892s  |  19.892s  |   0.000s  | 0.0%|
|bench_1252.smt2                                                                             |  19.827s  |  19.827s  |   0.000s  | 0.0%|
|bench_1253.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1256.smt2                                                                             |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|bench_12625.smt2                                                                            |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_12655.smt2                                                                            |  19.806s  |  19.806s  |   0.000s  | 0.0%|
|bench_1266.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_1270.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1278.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1280.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_12821.smt2                                                                            |   3.791s  |   3.791s  |   0.000s  | 0.0%|
|bench_1283.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1285.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1286.smt2                                                                             |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|bench_129.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1306.smt2                                                                             |  19.841s  |  19.841s  |   0.000s  | 0.0%|
|bench_1307.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_13129.smt2                                                                            |  19.776s  |  19.776s  |   0.000s  | 0.0%|
|bench_13147.smt2                                                                            |   1.873s  |   1.873s  |   0.000s  | 0.0%|
|bench_1318.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1323.smt2                                                                             |   9.882s  |   9.882s  |   0.000s  | 0.0%|
|bench_13284.smt2                                                                            |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|bench_1329.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_1332.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_13336.smt2                                                                            |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|bench_1335.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1336.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1338.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_13483.smt2                                                                            |  19.924s  |  19.924s  |   0.000s  | 0.0%|
|bench_1349.smt2                                                                             |  19.800s  |  19.800s  |   0.000s  | 0.0%|
|bench_135.smt2                                                                              |  19.906s  |  19.906s  |   0.000s  | 0.0%|
|bench_1350.smt2                                                                             |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|bench_1355.smt2                                                                             |  16.814s  |  16.814s  |   0.000s  | 0.0%|
|bench_1359.smt2                                                                             |  19.901s  |  19.901s  |   0.000s  | 0.0%|
|bench_1361.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1365.smt2                                                                             |  19.675s  |  19.675s  |   0.000s  | 0.0%|
|bench_1367.smt2                                                                             |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|bench_1374.smt2                                                                             |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|bench_13744.smt2                                                                            |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|bench_13773.smt2                                                                            |   1.633s  |   1.633s  |   0.000s  | 0.0%|
|bench_1379.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_13790.smt2                                                                            |  19.908s  |  19.908s  |   0.000s  | 0.0%|
|bench_1386.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1388.smt2                                                                             |  19.747s  |  19.747s  |   0.000s  | 0.0%|
|bench_1389.smt2                                                                             |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|bench_1391.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1400.smt2                                                                             |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|bench_1401.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1405.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_141.smt2                                                                              |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|bench_1412.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1414.smt2                                                                             |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|bench_14156.smt2                                                                            |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|bench_14161.smt2                                                                            |  19.324s  |  19.324s  |   0.000s  | 0.0%|
|bench_14165.smt2                                                                            |  19.923s  |  19.923s  |   0.000s  | 0.0%|
|bench_1417.smt2                                                                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bench_142.smt2                                                                              |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|bench_14209.smt2                                                                            |   0.452s  |   0.452s  |   0.000s  | 0.0%|
|bench_1424.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_14284.smt2                                                                            |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|bench_143.smt2                                                                              |  19.899s  |  19.899s  |   0.000s  | 0.0%|
|bench_1434.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_14358.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1440.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1441.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1442.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1445.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1446.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_14461.smt2                                                                            |  19.825s  |  19.825s  |   0.000s  | 0.0%|
|bench_1447.smt2                                                                             |   9.596s  |   9.596s  |   0.000s  | 0.0%|
|bench_14486.smt2                                                                            |  19.875s  |  19.875s  |   0.000s  | 0.0%|
|bench_145.smt2                                                                              |  19.734s  |  19.734s  |   0.000s  | 0.0%|
|bench_1453.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1455.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_14595.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_14598.smt2                                                                            |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|bench_1465.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1467.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_1470.smt2                                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_14720.smt2                                                                            |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_1476.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_1477.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1478.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1481.smt2                                                                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|bench_14817.smt2                                                                            |  19.860s  |  19.860s  |   0.000s  | 0.0%|
|bench_14861.smt2                                                                            |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|bench_14875.smt2                                                                            |  19.136s  |  19.136s  |   0.000s  | 0.0%|
|bench_14885.smt2                                                                            |   8.040s  |   8.040s  |   0.000s  | 0.0%|
|bench_14932.smt2                                                                            |  19.948s  |  19.948s  |   0.000s  | 0.0%|
|bench_14941.smt2                                                                            |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|bench_1495.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_1496.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|bench_1498.smt2                                                                             |  19.865s  |  19.865s  |   0.000s  | 0.0%|
|bench_14984.smt2                                                                            |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_15.smt2                                                                               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1504.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|bench_15105.smt2                                                                            |  19.741s  |  19.741s  |   0.000s  | 0.0%|
|bench_15128.smt2                                                                            |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_1522.smt2                                                                             |  19.913s  |  19.913s  |   0.000s  | 0.0%|
|bench_1523.smt2                                                                             |  19.797s  |  19.797s  |   0.000s  | 0.0%|
|bench_15255.smt2                                                                            |  19.506s  |  19.506s  |   0.000s  | 0.0%|
|bench_1532.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_15365.smt2                                                                            |  19.883s  |  19.883s  |   0.000s  | 0.0%|
|bench_154.smt2                                                                              |  19.844s  |  19.844s  |   0.000s  | 0.0%|
|bench_1545.smt2                                                                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|bench_1549.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_15547.smt2                                                                            |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|bench_1555.smt2                                                                             |  19.869s  |  19.869s  |   0.000s  | 0.0%|
|bench_1559.smt2                                                                             |  19.484s  |  19.484s  |   0.000s  | 0.0%|
|bench_1560.smt2                                                                             |  19.855s  |  19.855s  |   0.000s  | 0.0%|
|bench_1567.smt2                                                                             |  19.747s  |  19.747s  |   0.000s  | 0.0%|
|bench_1568.smt2                                                                             |   2.224s  |   2.224s  |   0.000s  | 0.0%|
|bench_15711.smt2                                                                            |  19.854s  |  19.854s  |   0.000s  | 0.0%|
|bench_15719.smt2                                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|bench_1573.smt2                                                                             |   1.312s  |   1.312s  |   0.000s  | 0.0%|
|bench_1578.smt2                                                                             |  19.763s  |  19.763s  |   0.000s  | 0.0%|
|bench_15783.smt2                                                                            |   1.228s  |   1.228s  |   0.000s  | 0.0%|
|bench_1583.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_15833.smt2                                                                            |  19.557s  |  19.557s  |   0.000s  | 0.0%|
|bench_1585.smt2                                                                             |  19.855s  |  19.855s  |   0.000s  | 0.0%|
|bench_1586.smt2                                                                             |  19.863s  |  19.863s  |   0.000s  | 0.0%|
|bench_1588.smt2                                                                             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|bench_160.smt2                                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_1603.smt2                                                                             |  19.810s  |  19.810s  |   0.000s  | 0.0%|
|bench_16064.smt2                                                                            |  19.730s  |  19.730s  |   0.000s  | 0.0%|
|bench_1608.smt2                                                                             |  19.716s  |  19.716s  |   0.000s  | 0.0%|
|bench_1610.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1614.smt2                                                                             |  15.971s  |  15.971s  |   0.000s  | 0.0%|
|bench_1621.smt2                                                                             |  19.860s  |  19.860s  |   0.000s  | 0.0%|
|bench_16245.smt2                                                                            |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|bench_1627.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1629.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_163.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1630.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1636.smt2                                                                             |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|bench_16382.smt2                                                                            |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_16409.smt2                                                                            |  19.794s  |  19.794s  |   0.000s  | 0.0%|
|bench_1643.smt2                                                                             |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|bench_16467.smt2                                                                            |  19.854s  |  19.854s  |   0.000s  | 0.0%|
|bench_165.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1652.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_1657.smt2                                                                             |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|bench_166.smt2                                                                              |  19.526s  |  19.526s  |   0.000s  | 0.0%|
|bench_1663.smt2                                                                             |  19.926s  |  19.926s  |   0.000s  | 0.0%|
|bench_16640.smt2                                                                            |   3.440s  |   3.440s  |   0.000s  | 0.0%|
|bench_1665.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1670.smt2                                                                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|bench_16707.smt2                                                                            |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|bench_1674.smt2                                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_168.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1680.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1686.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_16862.smt2                                                                            |  19.898s  |  19.898s  |   0.000s  | 0.0%|
|bench_1697.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_17033.smt2                                                                            |  19.910s  |  19.910s  |   0.000s  | 0.0%|
|bench_1707.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_17082.smt2                                                                            |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_171.smt2                                                                              |  19.711s  |  19.711s  |   0.000s  | 0.0%|
|bench_1710.smt2                                                                             |  19.819s  |  19.819s  |   0.000s  | 0.0%|
|bench_1712.smt2                                                                             |  19.940s  |  19.940s  |   0.000s  | 0.0%|
|bench_1717.smt2                                                                             |  19.854s  |  19.854s  |   0.000s  | 0.0%|
|bench_1720.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1721.smt2                                                                             |  19.619s  |  19.619s  |   0.000s  | 0.0%|
|bench_1724.smt2                                                                             |  19.358s  |  19.358s  |   0.000s  | 0.0%|
|bench_17324.smt2                                                                            |  19.877s  |  19.877s  |   0.000s  | 0.0%|
|bench_17335.smt2                                                                            |   0.971s  |   0.971s  |   0.000s  | 0.0%|
|bench_1739.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1748.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1756.smt2                                                                             |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|bench_1757.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1759.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_1760.smt2                                                                             |  19.837s  |  19.837s  |   0.000s  | 0.0%|
|bench_1761.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1763.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1769.smt2                                                                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|bench_1770.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1778.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_179.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1802.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1810.smt2                                                                             |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|bench_1811.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_1816.smt2                                                                             |  19.829s  |  19.829s  |   0.000s  | 0.0%|
|bench_1822.smt2                                                                             |  19.799s  |  19.799s  |   0.000s  | 0.0%|
|bench_1829.smt2                                                                             |  19.821s  |  19.821s  |   0.000s  | 0.0%|
|bench_183.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1837.smt2                                                                             |  19.607s  |  19.607s  |   0.000s  | 0.0%|
|bench_1839.smt2                                                                             |  19.786s  |  19.786s  |   0.000s  | 0.0%|
|bench_1841.smt2                                                                             |  19.390s  |  19.390s  |   0.000s  | 0.0%|
|bench_1844.smt2                                                                             |  19.912s  |  19.912s  |   0.000s  | 0.0%|
|bench_1851.smt2                                                                             |  19.866s  |  19.866s  |   0.000s  | 0.0%|
|bench_1858.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1863.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1864.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1869.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_187.smt2                                                                              |  19.940s  |  19.940s  |   0.000s  | 0.0%|
|bench_1872.smt2                                                                             |  19.677s  |  19.677s  |   0.000s  | 0.0%|
|bench_1873.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1878.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1880.smt2                                                                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|bench_1882.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1888.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1897.smt2                                                                             |  19.907s  |  19.907s  |   0.000s  | 0.0%|
|bench_1900.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1904.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1905.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1907.smt2                                                                             |  19.911s  |  19.911s  |   0.000s  | 0.0%|
|bench_1909.smt2                                                                             |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|bench_1937.smt2                                                                             |  19.934s  |  19.934s  |   0.000s  | 0.0%|
|bench_1942.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1946.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1953.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1957.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_1958.smt2                                                                             |  17.957s  |  17.957s  |   0.000s  | 0.0%|
|bench_1961.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_1963.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1976.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1977.smt2                                                                             |  19.609s  |  19.609s  |   0.000s  | 0.0%|
|bench_1981.smt2                                                                             |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|bench_1985.smt2                                                                             |  19.896s  |  19.896s  |   0.000s  | 0.0%|
|bench_1992.smt2                                                                             |  19.741s  |  19.741s  |   0.000s  | 0.0%|
|bench_1993.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1996.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_200.smt2                                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2021.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2022.smt2                                                                             |  19.863s  |  19.863s  |   0.000s  | 0.0%|
|bench_2034.smt2                                                                             |   5.282s  |   5.282s  |   0.000s  | 0.0%|
|bench_204.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2044.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_2050.smt2                                                                             |  19.669s  |  19.669s  |   0.000s  | 0.0%|
|bench_2059.smt2                                                                             |  19.883s  |  19.883s  |   0.000s  | 0.0%|
|bench_2067.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2070.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2072.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2075.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2076.smt2                                                                             |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|bench_2077.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_208.smt2                                                                              |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|bench_2083.smt2                                                                             |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|bench_2097.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2099.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2102.smt2                                                                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|bench_2108.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2113.smt2                                                                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bench_2115.smt2                                                                             |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|bench_2117.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2121.smt2                                                                             |  19.901s  |  19.901s  |   0.000s  | 0.0%|
|bench_2122.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2129.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_214.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2141.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_2144.smt2                                                                             |  19.480s  |  19.480s  |   0.000s  | 0.0%|
|bench_2148.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2149.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2150.smt2                                                                             |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|bench_2152.smt2                                                                             |  19.550s  |  19.550s  |   0.000s  | 0.0%|
|bench_2155.smt2                                                                             |  19.861s  |  19.861s  |   0.000s  | 0.0%|
|bench_2161.smt2                                                                             |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|bench_2162.smt2                                                                             |  19.603s  |  19.603s  |   0.000s  | 0.0%|
|bench_2167.smt2                                                                             |  19.929s  |  19.929s  |   0.000s  | 0.0%|
|bench_2169.smt2                                                                             |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|bench_2170.smt2                                                                             |  19.785s  |  19.785s  |   0.000s  | 0.0%|
|bench_2174.smt2                                                                             |  19.900s  |  19.900s  |   0.000s  | 0.0%|
|bench_2175.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2183.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_2188.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2189.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2192.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2197.smt2                                                                             |   3.261s  |   3.261s  |   0.000s  | 0.0%|
|bench_2202.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2207.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2211.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2221.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2225.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2229.smt2                                                                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|bench_2233.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_224.smt2                                                                              |   4.922s  |   4.922s  |   0.000s  | 0.0%|
|bench_2248.smt2                                                                             |  19.917s  |  19.917s  |   0.000s  | 0.0%|
|bench_225.smt2                                                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_2257.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2258.smt2                                                                             |  19.867s  |  19.867s  |   0.000s  | 0.0%|
|bench_2261.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2263.smt2                                                                             |  19.922s  |  19.922s  |   0.000s  | 0.0%|
|bench_2264.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2265.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2268.smt2                                                                             |  19.400s  |  19.400s  |   0.000s  | 0.0%|
|bench_2269.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2272.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2278.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|bench_228.smt2                                                                              |  19.836s  |  19.836s  |   0.000s  | 0.0%|
|bench_2284.smt2                                                                             |  19.588s  |  19.588s  |   0.000s  | 0.0%|
|bench_2291.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2293.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_2295.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_230.smt2                                                                              |  19.748s  |  19.748s  |   0.000s  | 0.0%|
|bench_2304.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_2308.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2309.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2312.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_232.smt2                                                                              |  19.792s  |  19.792s  |   0.000s  | 0.0%|
|bench_2325.smt2                                                                             |  19.889s  |  19.889s  |   0.000s  | 0.0%|
|bench_2326.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_2327.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2330.smt2                                                                             |  19.847s  |  19.847s  |   0.000s  | 0.0%|
|bench_234.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2349.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2351.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_2358.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2360.smt2                                                                             |  19.809s  |  19.809s  |   0.000s  | 0.0%|
|bench_238.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2380.smt2                                                                             |  19.570s  |  19.570s  |   0.000s  | 0.0%|
|bench_2384.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2386.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2395.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|bench_2397.smt2                                                                             |  19.910s  |  19.910s  |   0.000s  | 0.0%|
|bench_2400.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2406.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2420.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2425.smt2                                                                             |  19.717s  |  19.717s  |   0.000s  | 0.0%|
|bench_2428.smt2                                                                             |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|bench_243.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2431.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2432.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2433.smt2                                                                             |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|bench_2435.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2436.smt2                                                                             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|bench_2443.smt2                                                                             |  19.815s  |  19.815s  |   0.000s  | 0.0%|
|bench_2463.smt2                                                                             |  19.811s  |  19.811s  |   0.000s  | 0.0%|
|bench_2469.smt2                                                                             |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|bench_247.smt2                                                                              |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|bench_2475.smt2                                                                             |  19.923s  |  19.923s  |   0.000s  | 0.0%|
|bench_248.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2493.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2499.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2503.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2507.smt2                                                                             |   1.270s  |   1.270s  |   0.000s  | 0.0%|
|bench_2514.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2517.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2521.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2524.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_253.smt2                                                                              |  17.936s  |  17.936s  |   0.000s  | 0.0%|
|bench_2547.smt2                                                                             |  19.939s  |  19.939s  |   0.000s  | 0.0%|
|bench_2548.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2550.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_2551.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2552.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2558.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2566.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_2567.smt2                                                                             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|bench_2573.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2574.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2579.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2580.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2582.smt2                                                                             |  19.888s  |  19.888s  |   0.000s  | 0.0%|
|bench_2586.smt2                                                                             |  19.895s  |  19.895s  |   0.000s  | 0.0%|
|bench_259.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2594.smt2                                                                             |  19.910s  |  19.910s  |   0.000s  | 0.0%|
|bench_2599.smt2                                                                             |  19.807s  |  19.807s  |   0.000s  | 0.0%|
|bench_2602.smt2                                                                             |  19.307s  |  19.307s  |   0.000s  | 0.0%|
|bench_2606.smt2                                                                             |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|bench_261.smt2                                                                              |  19.849s  |  19.849s  |   0.000s  | 0.0%|
|bench_2612.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2613.smt2                                                                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|bench_2620.smt2                                                                             |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|bench_2621.smt2                                                                             |  19.691s  |  19.691s  |   0.000s  | 0.0%|
|bench_2628.smt2                                                                             |  19.423s  |  19.423s  |   0.000s  | 0.0%|
|bench_2629.smt2                                                                             |  19.953s  |  19.953s  |   0.000s  | 0.0%|
|bench_2635.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2639.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2642.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2644.smt2                                                                             |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|bench_2645.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2646.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_2650.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2653.smt2                                                                             |  19.911s  |  19.911s  |   0.000s  | 0.0%|
|bench_2659.smt2                                                                             |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|bench_267.smt2                                                                              |  15.783s  |  15.783s  |   0.000s  | 0.0%|
|bench_2671.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2675.smt2                                                                             |  19.845s  |  19.845s  |   0.000s  | 0.0%|
|bench_2676.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2682.smt2                                                                             |  19.601s  |  19.601s  |   0.000s  | 0.0%|
|bench_2688.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_270.smt2                                                                              |   0.753s  |   0.753s  |   0.000s  | 0.0%|
|bench_2701.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2704.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2710.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2717.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2724.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2727.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_2729.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2735.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_2737.smt2                                                                             |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|bench_2747.smt2                                                                             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|bench_2750.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2755.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2757.smt2                                                                             |  19.947s  |  19.947s  |   0.000s  | 0.0%|
|bench_276.smt2                                                                              |  19.893s  |  19.893s  |   0.000s  | 0.0%|
|bench_2767.smt2                                                                             |  19.952s  |  19.952s  |   0.000s  | 0.0%|
|bench_2779.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2789.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_279.smt2                                                                              |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|bench_2798.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_28.smt2                                                                               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_281.smt2                                                                              |  19.527s  |  19.527s  |   0.000s  | 0.0%|
|bench_2811.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2817.smt2                                                                             |  19.259s  |  19.259s  |   0.000s  | 0.0%|
|bench_2826.smt2                                                                             |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|bench_2831.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|bench_2832.smt2                                                                             |  19.931s  |  19.931s  |   0.000s  | 0.0%|
|bench_2839.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2841.smt2                                                                             |   1.573s  |   1.573s  |   0.000s  | 0.0%|
|bench_2842.smt2                                                                             |  19.781s  |  19.781s  |   0.000s  | 0.0%|
|bench_2844.smt2                                                                             |  19.720s  |  19.720s  |   0.000s  | 0.0%|
|bench_2846.smt2                                                                             |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|bench_2849.smt2                                                                             |  19.912s  |  19.912s  |   0.000s  | 0.0%|
|bench_285.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2855.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2858.smt2                                                                             |  19.512s  |  19.512s  |   0.000s  | 0.0%|
|bench_2864.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2866.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2867.smt2                                                                             |  19.816s  |  19.816s  |   0.000s  | 0.0%|
|bench_2868.smt2                                                                             |  19.873s  |  19.873s  |   0.000s  | 0.0%|
|bench_2875.smt2                                                                             |   9.034s  |   9.034s  |   0.000s  | 0.0%|
|bench_2876.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_288.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2880.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2897.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_29.smt2                                                                               |  10.213s  |  10.213s  |   0.000s  | 0.0%|
|bench_290.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2915.smt2                                                                             |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|bench_2917.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2931.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_295.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2957.smt2                                                                             |  19.906s  |  19.906s  |   0.000s  | 0.0%|
|bench_296.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2961.smt2                                                                             |  19.730s  |  19.730s  |   0.000s  | 0.0%|
|bench_2962.smt2                                                                             |  19.664s  |  19.664s  |   0.000s  | 0.0%|
|bench_2965.smt2                                                                             |  18.086s  |  18.086s  |   0.000s  | 0.0%|
|bench_2974.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|bench_2983.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_299.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2992.smt2                                                                             |  18.323s  |  18.323s  |   0.000s  | 0.0%|
|bench_2994.smt2                                                                             |  19.731s  |  19.731s  |   0.000s  | 0.0%|
|bench_2995.smt2                                                                             |  19.838s  |  19.838s  |   0.000s  | 0.0%|
|bench_301.smt2                                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3010.smt2                                                                             |  19.901s  |  19.901s  |   0.000s  | 0.0%|
|bench_3011.smt2                                                                             |  19.828s  |  19.828s  |   0.000s  | 0.0%|
|bench_3015.smt2                                                                             |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|bench_3018.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3019.smt2                                                                             |  19.843s  |  19.843s  |   0.000s  | 0.0%|
|bench_302.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_303.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3031.smt2                                                                             |  19.894s  |  19.894s  |   0.000s  | 0.0%|
|bench_3032.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_3041.smt2                                                                             |  19.910s  |  19.910s  |   0.000s  | 0.0%|
|bench_3048.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3058.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_306.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3062.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3065.smt2                                                                             |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|bench_3068.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3080.smt2                                                                             |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|bench_3082.smt2                                                                             |  19.209s  |  19.209s  |   0.000s  | 0.0%|
|bench_3087.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3091.smt2                                                                             |  19.875s  |  19.875s  |   0.000s  | 0.0%|
|bench_3093.smt2                                                                             |   2.008s  |   2.008s  |   0.000s  | 0.0%|
|bench_3094.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3099.smt2                                                                             |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|bench_3103.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3105.smt2                                                                             |  19.896s  |  19.896s  |   0.000s  | 0.0%|
|bench_3111.smt2                                                                             |  19.801s  |  19.801s  |   0.000s  | 0.0%|
|bench_3113.smt2                                                                             |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|bench_3114.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_3121.smt2                                                                             |  14.511s  |  14.511s  |   0.000s  | 0.0%|
|bench_3145.smt2                                                                             |  19.844s  |  19.844s  |   0.000s  | 0.0%|
|bench_3156.smt2                                                                             |  19.853s  |  19.853s  |   0.000s  | 0.0%|
|bench_3159.smt2                                                                             |  19.572s  |  19.572s  |   0.000s  | 0.0%|
|bench_3168.smt2                                                                             |   9.347s  |   9.347s  |   0.000s  | 0.0%|
|bench_3169.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_317.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3171.smt2                                                                             |  19.808s  |  19.808s  |   0.000s  | 0.0%|
|bench_3173.smt2                                                                             |  19.747s  |  19.747s  |   0.000s  | 0.0%|
|bench_3174.smt2                                                                             |  19.706s  |  19.706s  |   0.000s  | 0.0%|
|bench_3177.smt2                                                                             |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|bench_3181.smt2                                                                             |  19.886s  |  19.886s  |   0.000s  | 0.0%|
|bench_3191.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_3194.smt2                                                                             |  19.866s  |  19.866s  |   0.000s  | 0.0%|
|bench_3196.smt2                                                                             |  19.923s  |  19.923s  |   0.000s  | 0.0%|
|bench_3206.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3207.smt2                                                                             |  19.688s  |  19.688s  |   0.000s  | 0.0%|
|bench_3209.smt2                                                                             |  19.941s  |  19.941s  |   0.000s  | 0.0%|
|bench_3218.smt2                                                                             |  19.863s  |  19.863s  |   0.000s  | 0.0%|
|bench_3221.smt2                                                                             |  19.893s  |  19.893s  |   0.000s  | 0.0%|
|bench_3223.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_323.smt2                                                                              |  19.694s  |  19.694s  |   0.000s  | 0.0%|
|bench_3239.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3240.smt2                                                                             |  19.739s  |  19.739s  |   0.000s  | 0.0%|
|bench_3246.smt2                                                                             |  19.925s  |  19.925s  |   0.000s  | 0.0%|
|bench_325.smt2                                                                              |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|bench_3263.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3266.smt2                                                                             |  19.556s  |  19.556s  |   0.000s  | 0.0%|
|bench_3268.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3275.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3279.smt2                                                                             |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|bench_3295.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3297.smt2                                                                             |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|bench_3307.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3308.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3311.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3317.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3320.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3326.smt2                                                                             |  19.936s  |  19.936s  |   0.000s  | 0.0%|
|bench_3329.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3333.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3335.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3338.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3339.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_335.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3351.smt2                                                                             |  19.827s  |  19.827s  |   0.000s  | 0.0%|
|bench_3352.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3358.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3360.smt2                                                                             |   1.889s  |   1.889s  |   0.000s  | 0.0%|
|bench_3367.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3379.smt2                                                                             |  19.914s  |  19.914s  |   0.000s  | 0.0%|
|bench_3394.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3411.smt2                                                                             |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|bench_3415.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3416.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3420.smt2                                                                             |  19.353s  |  19.353s  |   0.000s  | 0.0%|
|bench_3421.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3431.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3434.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3437.smt2                                                                             |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|bench_3446.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3451.smt2                                                                             |  19.786s  |  19.786s  |   0.000s  | 0.0%|
|bench_3460.smt2                                                                             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|bench_3461.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3465.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3469.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_347.smt2                                                                              |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|bench_3475.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3476.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_348.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3484.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3485.smt2                                                                             |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|bench_3489.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3499.smt2                                                                             |  19.556s  |  19.556s  |   0.000s  | 0.0%|
|bench_3500.smt2                                                                             |  19.787s  |  19.787s  |   0.000s  | 0.0%|
|bench_3502.smt2                                                                             |   4.409s  |   4.409s  |   0.000s  | 0.0%|
|bench_3509.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3516.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_3521.smt2                                                                             |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|bench_3522.smt2                                                                             |   2.290s  |   2.290s  |   0.000s  | 0.0%|
|bench_3524.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_353.smt2                                                                              |  19.873s  |  19.873s  |   0.000s  | 0.0%|
|bench_3538.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3539.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3541.smt2                                                                             |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|bench_3548.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3551.smt2                                                                             |  19.827s  |  19.827s  |   0.000s  | 0.0%|
|bench_3557.smt2                                                                             |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|bench_3558.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3561.smt2                                                                             |  19.779s  |  19.779s  |   0.000s  | 0.0%|
|bench_3575.smt2                                                                             |  19.626s  |  19.626s  |   0.000s  | 0.0%|
|bench_3578.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3587.smt2                                                                             |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|bench_3588.smt2                                                                             |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|bench_3598.smt2                                                                             |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|bench_36.smt2                                                                               |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|bench_360.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3603.smt2                                                                             |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|bench_3623.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3636.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_3637.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_3642.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_365.smt2                                                                              |  19.815s  |  19.815s  |   0.000s  | 0.0%|
|bench_366.smt2                                                                              |  19.832s  |  19.832s  |   0.000s  | 0.0%|
|bench_3671.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3672.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_3675.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_368.smt2                                                                              |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|bench_3681.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3688.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3689.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_369.smt2                                                                              |  19.861s  |  19.861s  |   0.000s  | 0.0%|
|bench_3697.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3699.smt2                                                                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|bench_3707.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3715.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3716.smt2                                                                             |  19.779s  |  19.779s  |   0.000s  | 0.0%|
|bench_3719.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_372.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3721.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3739.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_375.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3750.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3754.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3755.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3757.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3765.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3787.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3788.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3789.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_379.smt2                                                                              |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_3794.smt2                                                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|bench_3795.smt2                                                                             |   6.894s  |   6.894s  |   0.000s  | 0.0%|
|bench_3799.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3813.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3815.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_3818.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3819.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3832.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3834.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3838.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3846.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3847.smt2                                                                             |  19.683s  |  19.683s  |   0.000s  | 0.0%|
|bench_385.smt2                                                                              |  19.888s  |  19.888s  |   0.000s  | 0.0%|
|bench_3866.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_387.smt2                                                                              |  19.781s  |  19.781s  |   0.000s  | 0.0%|
|bench_3879.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_388.smt2                                                                              |  19.391s  |  19.391s  |   0.000s  | 0.0%|
|bench_3881.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3882.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3885.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3886.smt2                                                                             |  19.556s  |  19.556s  |   0.000s  | 0.0%|
|bench_3888.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_3890.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3894.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_390.smt2                                                                              |  19.575s  |  19.575s  |   0.000s  | 0.0%|
|bench_3906.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_3915.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3926.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3936.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3937.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3943.smt2                                                                             |  19.469s  |  19.469s  |   0.000s  | 0.0%|
|bench_3945.smt2                                                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|bench_3951.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3953.smt2                                                                             |  19.542s  |  19.542s  |   0.000s  | 0.0%|
|bench_3963.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3964.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3968.smt2                                                                             |  19.857s  |  19.857s  |   0.000s  | 0.0%|
|bench_3992.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3995.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3997.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4007.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4010.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4015.smt2                                                                             |  19.541s  |  19.541s  |   0.000s  | 0.0%|
|bench_4019.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_402.smt2                                                                              |   0.510s  |   0.510s  |   0.000s  | 0.0%|
|bench_4021.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4023.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4031.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4037.smt2                                                                             |  19.734s  |  19.734s  |   0.000s  | 0.0%|
|bench_404.smt2                                                                              |  19.858s  |  19.858s  |   0.000s  | 0.0%|
|bench_4040.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4046.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4051.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4058.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4065.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4069.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4097.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4099.smt2                                                                             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|bench_4100.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4112.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4115.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4137.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_414.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4141.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4143.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4154.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4156.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4157.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4160.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4164.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4170.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4173.smt2                                                                             |   5.343s  |   5.343s  |   0.000s  | 0.0%|
|bench_4175.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4192.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4208.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4219.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4220.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4231.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4233.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_424.smt2                                                                              |  19.678s  |  19.678s  |   0.000s  | 0.0%|
|bench_4253.smt2                                                                             |   0.565s  |   0.565s  |   0.000s  | 0.0%|
|bench_4256.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|bench_4261.smt2                                                                             |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|bench_4273.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4275.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4279.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4289.smt2                                                                             |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|bench_4304.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4312.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4313.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4319.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4321.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4340.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4346.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4350.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4352.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4356.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4359.smt2                                                                             |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|bench_436.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4368.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_437.smt2                                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_4375.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4387.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4390.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4397.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4399.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_440.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4405.smt2                                                                             |  19.895s  |  19.895s  |   0.000s  | 0.0%|
|bench_4412.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4435.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_4444.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_4447.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_445.smt2                                                                              |  19.535s  |  19.535s  |   0.000s  | 0.0%|
|bench_4461.smt2                                                                             |   1.604s  |   1.604s  |   0.000s  | 0.0%|
|bench_4467.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4472.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4477.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4481.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_449.smt2                                                                              |  19.758s  |  19.758s  |   0.000s  | 0.0%|
|bench_4494.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4505.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4508.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_451.smt2                                                                              |  19.514s  |  19.514s  |   0.000s  | 0.0%|
|bench_4516.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4518.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_452.smt2                                                                              |  19.817s  |  19.817s  |   0.000s  | 0.0%|
|bench_4520.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4522.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4526.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4553.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4555.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_456.smt2                                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4560.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4565.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4568.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_457.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4570.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4576.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4580.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4581.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4583.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4588.smt2                                                                             |  19.625s  |  19.625s  |   0.000s  | 0.0%|
|bench_4594.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_46.smt2                                                                               |  19.826s  |  19.826s  |   0.000s  | 0.0%|
|bench_4605.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4607.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4614.smt2                                                                             |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|bench_4617.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4626.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4627.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4628.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4635.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4642.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4644.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4650.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4654.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4662.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4669.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4689.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4692.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4696.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4706.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4710.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_472.smt2                                                                              |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|bench_4724.smt2                                                                             |   5.437s  |   5.437s  |   0.000s  | 0.0%|
|bench_4725.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4728.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4738.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4740.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4753.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4755.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4759.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4768.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4775.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4788.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_479.smt2                                                                              |  19.948s  |  19.948s  |   0.000s  | 0.0%|
|bench_480.smt2                                                                              |  19.824s  |  19.824s  |   0.000s  | 0.0%|
|bench_4813.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4818.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4820.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4822.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4834.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4838.smt2                                                                             |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|bench_4839.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4840.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4873.smt2                                                                             |  19.932s  |  19.932s  |   0.000s  | 0.0%|
|bench_4879.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4888.smt2                                                                             |   0.863s  |   0.863s  |   0.000s  | 0.0%|
|bench_489.smt2                                                                              |  19.744s  |  19.744s  |   0.000s  | 0.0%|
|bench_4890.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4893.smt2                                                                             |  19.911s  |  19.911s  |   0.000s  | 0.0%|
|bench_4894.smt2                                                                             |  19.755s  |  19.755s  |   0.000s  | 0.0%|
|bench_4900.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4906.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4908.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4919.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4920.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4921.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_4933.smt2                                                                             |  19.885s  |  19.885s  |   0.000s  | 0.0%|
|bench_4937.smt2                                                                             |  11.673s  |  11.673s  |   0.000s  | 0.0%|
|bench_494.smt2                                                                              |  19.824s  |  19.824s  |   0.000s  | 0.0%|
|bench_4954.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4957.smt2                                                                             |  19.788s  |  19.788s  |   0.000s  | 0.0%|
|bench_4963.smt2                                                                             |  19.835s  |  19.835s  |   0.000s  | 0.0%|
|bench_4964.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4965.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4968.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_497.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4971.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_498.smt2                                                                              |  19.797s  |  19.797s  |   0.000s  | 0.0%|
|bench_4985.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4990.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5.smt2                                                                                |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_50.smt2                                                                               |  19.602s  |  19.602s  |   0.000s  | 0.0%|
|bench_500.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5005.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5019.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_502.smt2                                                                              |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|bench_5030.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_5034.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5036.smt2                                                                             |  19.807s  |  19.807s  |   0.000s  | 0.0%|
|bench_5037.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5041.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5077.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5081.smt2                                                                             |  19.878s  |  19.878s  |   0.000s  | 0.0%|
|bench_5084.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5086.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5096.smt2                                                                             |  18.089s  |  18.089s  |   0.000s  | 0.0%|
|bench_51.smt2                                                                               |  19.903s  |  19.903s  |   0.000s  | 0.0%|
|bench_5123.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5127.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5131.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5136.smt2                                                                             |   5.950s  |   5.950s  |   0.000s  | 0.0%|
|bench_5137.smt2                                                                             |  19.901s  |  19.901s  |   0.000s  | 0.0%|
|bench_5139.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5150.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5153.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5154.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5155.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5157.smt2                                                                             |  19.819s  |  19.819s  |   0.000s  | 0.0%|
|bench_5159.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5165.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_5170.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5183.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_5187.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5188.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5190.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5191.smt2                                                                             |  19.833s  |  19.833s  |   0.000s  | 0.0%|
|bench_5192.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_52.smt2                                                                               |  19.888s  |  19.888s  |   0.000s  | 0.0%|
|bench_5209.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5210.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5218.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5222.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_5223.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bench_5234.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5236.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5238.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_525.smt2                                                                              |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|bench_5257.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5261.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_527.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5270.smt2                                                                             |  19.619s  |  19.619s  |   0.000s  | 0.0%|
|bench_528.smt2                                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_5284.smt2                                                                             |  18.241s  |  18.241s  |   0.000s  | 0.0%|
|bench_5292.smt2                                                                             |  19.880s  |  19.880s  |   0.000s  | 0.0%|
|bench_5296.smt2                                                                             |  19.580s  |  19.580s  |   0.000s  | 0.0%|
|bench_5301.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5302.smt2                                                                             |  19.799s  |  19.799s  |   0.000s  | 0.0%|
|bench_5303.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5309.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_531.smt2                                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_5326.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5329.smt2                                                                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bench_5332.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5340.smt2                                                                             |  19.714s  |  19.714s  |   0.000s  | 0.0%|
|bench_5349.smt2                                                                             |  19.693s  |  19.693s  |   0.000s  | 0.0%|
|bench_535.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5358.smt2                                                                             |  17.546s  |  17.546s  |   0.000s  | 0.0%|
|bench_536.smt2                                                                              |  19.873s  |  19.873s  |   0.000s  | 0.0%|
|bench_5360.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_5365.smt2                                                                             |  19.848s  |  19.848s  |   0.000s  | 0.0%|
|bench_5371.smt2                                                                             |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|bench_5373.smt2                                                                             |  19.857s  |  19.857s  |   0.000s  | 0.0%|
|bench_5377.smt2                                                                             |   7.680s  |   7.680s  |   0.000s  | 0.0%|
|bench_5392.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_5395.smt2                                                                             |  19.685s  |  19.685s  |   0.000s  | 0.0%|
|bench_5401.smt2                                                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|bench_5408.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5417.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_542.smt2                                                                              |  19.900s  |  19.900s  |   0.000s  | 0.0%|
|bench_5421.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|bench_5424.smt2                                                                             |  19.902s  |  19.902s  |   0.000s  | 0.0%|
|bench_5432.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5435.smt2                                                                             |  19.900s  |  19.900s  |   0.000s  | 0.0%|
|bench_5440.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5445.smt2                                                                             |   0.624s  |   0.624s  |   0.000s  | 0.0%|
|bench_5449.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5457.smt2                                                                             |   0.608s  |   0.608s  |   0.000s  | 0.0%|
|bench_5459.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5466.smt2                                                                             |  19.796s  |  19.796s  |   0.000s  | 0.0%|
|bench_5492.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5499.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5503.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5509.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5517.smt2                                                                             |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|bench_5525.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5526.smt2                                                                             |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|bench_5532.smt2                                                                             |   0.623s  |   0.623s  |   0.000s  | 0.0%|
|bench_5536.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5543.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5545.smt2                                                                             |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|bench_556.smt2                                                                              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_5575.smt2                                                                             |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|bench_5581.smt2                                                                             |  19.843s  |  19.843s  |   0.000s  | 0.0%|
|bench_559.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_5590.smt2                                                                             |   1.928s  |   1.928s  |   0.000s  | 0.0%|
|bench_5593.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_561.smt2                                                                              |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|bench_5613.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_5623.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5636.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5645.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_5649.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_565.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5658.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5662.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5666.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5674.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_571.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5718.smt2                                                                             |   2.701s  |   2.701s  |   0.000s  | 0.0%|
|bench_5722.smt2                                                                             |   2.836s  |   2.836s  |   0.000s  | 0.0%|
|bench_5723.smt2                                                                             |   2.857s  |   2.857s  |   0.000s  | 0.0%|
|bench_5733.smt2                                                                             |   2.857s  |   2.857s  |   0.000s  | 0.0%|
|bench_5744.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5752.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5765.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_5779.smt2                                                                             |  19.898s  |  19.898s  |   0.000s  | 0.0%|
|bench_581.smt2                                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_5898.smt2                                                                             |  19.839s  |  19.839s  |   0.000s  | 0.0%|
|bench_5944.smt2                                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_5974.smt2                                                                             |  19.701s  |  19.701s  |   0.000s  | 0.0%|
|bench_6016.smt2                                                                             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|bench_607.smt2                                                                              |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|bench_609.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_6097.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_613.smt2                                                                              |  19.941s  |  19.941s  |   0.000s  | 0.0%|
|bench_619.smt2                                                                              |  19.801s  |  19.801s  |   0.000s  | 0.0%|
|bench_620.smt2                                                                              |  19.726s  |  19.726s  |   0.000s  | 0.0%|
|bench_6215.smt2                                                                             |  19.786s  |  19.786s  |   0.000s  | 0.0%|
|bench_629.smt2                                                                              |  19.701s  |  19.701s  |   0.000s  | 0.0%|
|bench_630.smt2                                                                              |  19.918s  |  19.918s  |   0.000s  | 0.0%|
|bench_631.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_637.smt2                                                                              |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|bench_639.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_640.smt2                                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_6408.smt2                                                                             |   6.572s  |   6.572s  |   0.000s  | 0.0%|
|bench_6458.smt2                                                                             |  19.918s  |  19.918s  |   0.000s  | 0.0%|
|bench_6462.smt2                                                                             |  19.799s  |  19.799s  |   0.000s  | 0.0%|
|bench_650.smt2                                                                              |  19.609s  |  19.609s  |   0.000s  | 0.0%|
|bench_6560.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_657.smt2                                                                              |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|bench_658.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_659.smt2                                                                              |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|bench_66.smt2                                                                               |  19.753s  |  19.753s  |   0.000s  | 0.0%|
|bench_6606.smt2                                                                             |  19.949s  |  19.949s  |   0.000s  | 0.0%|
|bench_6614.smt2                                                                             |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|bench_663.smt2                                                                              |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|bench_6665.smt2                                                                             |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|bench_668.smt2                                                                              |   1.480s  |   1.480s  |   0.000s  | 0.0%|
|bench_6691.smt2                                                                             |  19.632s  |  19.632s  |   0.000s  | 0.0%|
|bench_6699.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6713.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6731.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6734.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_674.smt2                                                                              |  19.838s  |  19.838s  |   0.000s  | 0.0%|
|bench_6742.smt2                                                                             |  14.239s  |  14.239s  |   0.000s  | 0.0%|
|bench_6756.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6765.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6791.smt2                                                                             |  19.916s  |  19.916s  |   0.000s  | 0.0%|
|bench_6813.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6826.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6828.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6830.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6837.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6843.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6848.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_685.smt2                                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_6854.smt2                                                                             |   2.800s  |   2.800s  |   0.000s  | 0.0%|
|bench_6857.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6861.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_6866.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6867.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6882.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bench_6886.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6898.smt2                                                                             |  19.876s  |  19.876s  |   0.000s  | 0.0%|
|bench_690.smt2                                                                              |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|bench_6901.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6902.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6906.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6908.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_6911.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_6917.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_6923.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6924.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6929.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6938.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_6943.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6953.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6954.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6966.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6973.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6986.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6987.smt2                                                                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|bench_6998.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_700.smt2                                                                              |  19.687s  |  19.687s  |   0.000s  | 0.0%|
|bench_7005.smt2                                                                             |   1.652s  |   1.652s  |   0.000s  | 0.0%|
|bench_702.smt2                                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7021.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7024.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7030.smt2                                                                             |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|bench_7033.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_704.smt2                                                                              |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|bench_705.smt2                                                                              |  19.944s  |  19.944s  |   0.000s  | 0.0%|
|bench_7056.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_706.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7070.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7076.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7081.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7082.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7083.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7085.smt2                                                                             |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|bench_7086.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7088.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_709.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7095.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_710.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7116.smt2                                                                             |   6.991s  |   6.991s  |   0.000s  | 0.0%|
|bench_7119.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_712.smt2                                                                              |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|bench_7127.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7138.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7139.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7140.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7142.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7146.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7150.smt2                                                                             |  13.719s  |  13.719s  |   0.000s  | 0.0%|
|bench_7152.smt2                                                                             |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|bench_7166.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_717.smt2                                                                              |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|bench_7171.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_7182.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7185.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7188.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_720.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_721.smt2                                                                              |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|bench_7219.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7229.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7233.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7242.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7270.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7274.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7278.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7304.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7306.smt2                                                                             |  16.179s  |  16.179s  |   0.000s  | 0.0%|
|bench_7310.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7314.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7319.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7329.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7331.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7339.smt2                                                                             |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|bench_7357.smt2                                                                             |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_7375.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7382.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_7383.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7388.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7406.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7412.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7415.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7421.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_743.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7438.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7454.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_746.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7465.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_748.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7489.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_749.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7494.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7495.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7496.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7498.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7517.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7523.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7528.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_753.smt2                                                                              |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|bench_7532.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7534.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7537.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7539.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7550.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7552.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7556.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7563.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7565.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7573.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7575.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_76.smt2                                                                               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_760.smt2                                                                              |   7.340s  |   7.340s  |   0.000s  | 0.0%|
|bench_7601.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7612.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7627.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7633.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7636.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7641.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7642.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7655.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7663.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7669.smt2                                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_7670.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7671.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7673.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7686.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7696.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7705.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7708.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_7714.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7729.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7736.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7749.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7754.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7758.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7765.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_778.smt2                                                                              |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_78.smt2                                                                               |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7800.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7807.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_7811.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7819.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7823.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7826.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7828.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7832.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7833.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7834.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_7835.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7842.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7851.smt2                                                                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|bench_7862.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_7863.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7867.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_787.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7872.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7878.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7881.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_789.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_791.smt2                                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_793.smt2                                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_7943.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_796.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_797.smt2                                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_7973.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8019.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8030.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8042.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8049.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8051.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8053.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_8054.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8055.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_8070.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8073.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_808.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8082.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8084.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_8088.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8093.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8103.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8110.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8116.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8117.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8147.smt2                                                                             |  19.788s  |  19.788s  |   0.000s  | 0.0%|
|bench_815.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8165.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8170.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8178.smt2                                                                             |   2.243s  |   2.243s  |   0.000s  | 0.0%|
|bench_820.smt2                                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_8200.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8228.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_823.smt2                                                                              |  19.670s  |  19.670s  |   0.000s  | 0.0%|
|bench_8234.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_824.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8245.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_825.smt2                                                                              |  19.882s  |  19.882s  |   0.000s  | 0.0%|
|bench_826.smt2                                                                              |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|bench_8260.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_8271.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8282.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8283.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8289.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8294.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8296.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8298.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_830.smt2                                                                              |  19.891s  |  19.891s  |   0.000s  | 0.0%|
|bench_8306.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8309.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_831.smt2                                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8315.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8320.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8342.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8344.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8357.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8379.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_838.smt2                                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8393.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8394.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8461.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_8462.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8478.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_8487.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8492.smt2                                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_8495.smt2                                                                             |  19.742s  |  19.742s  |   0.000s  | 0.0%|
|bench_8507.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8512.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_856.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8562.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_8564.smt2                                                                             |  19.752s  |  19.752s  |   0.000s  | 0.0%|
|bench_858.smt2                                                                              |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|bench_86.smt2                                                                               |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|bench_864.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_868.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_875.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_881.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_883.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_888.smt2                                                                              |  19.912s  |  19.912s  |   0.000s  | 0.0%|
|bench_894.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_900.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_9009.smt2                                                                             |   0.977s  |   0.977s  |   0.000s  | 0.0%|
|bench_905.smt2                                                                              |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|bench_91.smt2                                                                               |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_914.smt2                                                                              |  19.740s  |  19.740s  |   0.000s  | 0.0%|
|bench_9173.smt2                                                                             |   9.115s  |   9.115s  |   0.000s  | 0.0%|
|bench_919.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_92.smt2                                                                               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_924.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_926.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_9280.smt2                                                                             |   8.234s  |   8.234s  |   0.000s  | 0.0%|
|bench_9299.smt2                                                                             |  19.515s  |  19.515s  |   0.000s  | 0.0%|
|bench_930.smt2                                                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_9337.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_9343.smt2                                                                             |  19.817s  |  19.817s  |   0.000s  | 0.0%|
|bench_9360.smt2                                                                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bench_938.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_941.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_944.smt2                                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_945.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_9535.smt2                                                                             |  19.470s  |  19.470s  |   0.000s  | 0.0%|
|bench_954.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_957.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_961.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_964.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_965.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_9653.smt2                                                                             |  19.755s  |  19.755s  |   0.000s  | 0.0%|
|bench_97.smt2                                                                               |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|bench_972.smt2                                                                              |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|bench_974.smt2                                                                              |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|bench_975.smt2                                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_979.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_98.smt2                                                                               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_981.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_983.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_9846.smt2                                                                             |  19.883s  |  19.883s  |   0.000s  | 0.0%|
|bench_985.smt2                                                                              |  19.906s  |  19.906s  |   0.000s  | 0.0%|
|bench_988.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_991.smt2                                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|bench_992.smt2                                                                              |  19.884s  |  19.884s  |   0.000s  | 0.0%|
|bench_993.smt2                                                                              |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|bench_994.smt2                                                                              |  19.572s  |  19.572s  |   0.000s  | 0.0%|
|bench_9946.smt2                                                                             |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|bench_996.smt2                                                                              |  19.806s  |  19.806s  |   0.000s  | 0.0%|
|bench_997.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bgpd_bgpd_vc76751.smt2                                                                      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|bgpd_bgpd_vc76752.smt2                                                                      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc330950.smt2                                                               |   5.756s  |   5.756s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc330976.smt2                                                               |   3.353s  |   3.353s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc330978.smt2                                                               |   1.452s  |   1.452s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331001.smt2                                                               |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331002.smt2                                                               |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331003.smt2                                                               |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331007.smt2                                                               |  10.898s  |  10.898s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331044.smt2                                                               |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331052.smt2                                                               |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331054.smt2                                                               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331082.smt2                                                               |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331086.smt2                                                               |  10.778s  |  10.778s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331088.smt2                                                               |   1.202s  |   1.202s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331089.smt2                                                               |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331092.smt2                                                               |   7.533s  |   7.533s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331097.smt2                                                               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331106.smt2                                                               |  19.347s  |  19.347s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331114.smt2                                                               |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331126.smt2                                                               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331137.smt2                                                               |  11.163s  |  11.163s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331146.smt2                                                               |  19.892s  |  19.892s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331148.smt2                                                               |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331154.smt2                                                               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331156.smt2                                                               |   0.868s  |   0.868s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331161.smt2                                                               |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331166.smt2                                                               |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331167.smt2                                                               |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331169.smt2                                                               |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc351277.smt2                                                               |  19.929s  |  19.929s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc351344.smt2                                                               |   3.118s  |   3.118s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc351348.smt2                                                               |   8.954s  |   8.954s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc352293.smt2                                                               |  19.742s  |  19.742s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc352302.smt2                                                               |  19.665s  |  19.665s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc352355.smt2                                                               |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225139.smt2                                                                 |   1.120s  |   1.120s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225280.smt2                                                                 |  19.891s  |  19.891s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225299.smt2                                                                 |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225305.smt2                                                                 |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225312.smt2                                                                 |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225316.smt2                                                                 |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225318.smt2                                                                 |   1.033s  |   1.033s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225320.smt2                                                                 |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225324.smt2                                                                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225330.smt2                                                                 |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225332.smt2                                                                 |   4.132s  |   4.132s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225336.smt2                                                                 |   3.825s  |   3.825s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225346.smt2                                                                 |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225380.smt2                                                                 |  19.722s  |  19.722s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225392.smt2                                                                 |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225394.smt2                                                                 |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225395.smt2                                                                 |   0.864s  |   0.864s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225399.smt2                                                                 |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225405.smt2                                                                 |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225408.smt2                                                                 |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225412.smt2                                                                 |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225454.smt2                                                                 |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225601.smt2                                                                 |   0.677s  |   0.677s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225626.smt2                                                                 |   1.443s  |   1.443s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225628.smt2                                                                 |   2.604s  |   2.604s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225745.smt2                                                                 |   0.937s  |   0.937s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225756.smt2                                                                 |   1.556s  |   1.556s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225762.smt2                                                                 |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225779.smt2                                                                 |   1.126s  |   1.126s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225786.smt2                                                                 |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225800.smt2                                                                 |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225806.smt2                                                                 |  19.846s  |  19.846s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225815.smt2                                                                 |   3.100s  |   3.100s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225816.smt2                                                                 |   0.891s  |   0.891s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225820.smt2                                                                 |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225824.smt2                                                                 |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225843.smt2                                                                 |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225858.smt2                                                                 |   1.315s  |   1.315s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225895.smt2                                                                 |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225900.smt2                                                                 |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225910.smt2                                                                 |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225912.smt2                                                                 |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225939.smt2                                                                 |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228446.smt2                                                                 |   1.752s  |   1.752s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228463.smt2                                                                 |  19.856s  |  19.856s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228472.smt2                                                                 |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228474.smt2                                                                 |   4.802s  |   4.802s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228478.smt2                                                                 |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228479.smt2                                                                 |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228487.smt2                                                                 |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228491.smt2                                                                 |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228492.smt2                                                                 |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228509.smt2                                                                 |  19.526s  |  19.526s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228512.smt2                                                                 |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228514.smt2                                                                 |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228524.smt2                                                                 |   1.248s  |   1.248s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228527.smt2                                                                 |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228571.smt2                                                                 |  13.144s  |  13.144s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228577.smt2                                                                 |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228610.smt2                                                                 |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232002.smt2                                                                 |   2.569s  |   2.569s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232007.smt2                                                                 |  19.757s  |  19.757s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232013.smt2                                                                 |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232030.smt2                                                                 |   7.914s  |   7.914s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232034.smt2                                                                 |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232036.smt2                                                                 |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232066.smt2                                                                 |   5.380s  |   5.380s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232071.smt2                                                                 |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232117.smt2                                                                 |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232128.smt2                                                                 |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232137.smt2                                                                 |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232138.smt2                                                                 |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225164.smt2                                                             |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225207.smt2                                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225211.smt2                                                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225213.smt2                                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225231.smt2                                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225236.smt2                                                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225237.smt2                                                             |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225238.smt2                                                             |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225246.smt2                                                             |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225256.smt2                                                             |   0.895s  |   0.895s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225257.smt2                                                             |   5.387s  |   5.387s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225263.smt2                                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225264.smt2                                                             |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225271.smt2                                                             |   1.399s  |   1.399s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225275.smt2                                                             |   5.059s  |   5.059s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225279.smt2                                                             |   4.006s  |   4.006s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225303.smt2                                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225668.smt2                                                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225676.smt2                                                             |  19.794s  |  19.794s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225689.smt2                                                             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225692.smt2                                                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225731.smt2                                                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225733.smt2                                                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225736.smt2                                                             |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225745.smt2                                                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225748.smt2                                                             |   0.967s  |   0.967s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225758.smt2                                                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225761.smt2                                                             |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225764.smt2                                                             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225771.smt2                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225773.smt2                                                             |   5.738s  |   5.738s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225779.smt2                                                             |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225783.smt2                                                             |  19.895s  |  19.895s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225826.smt2                                                             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225835.smt2                                                             |  19.911s  |  19.911s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225841.smt2                                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225860.smt2                                                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225887.smt2                                                             |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228430.smt2                                                             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228442.smt2                                                             |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228448.smt2                                                             |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228452.smt2                                                             |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228479.smt2                                                             |   4.569s  |   4.569s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228491.smt2                                                             |  19.856s  |  19.856s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228496.smt2                                                             |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228508.smt2                                                             |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228531.smt2                                                             |  13.088s  |  13.088s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4232.smt2                                                            |   8.964s  |   8.964s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4243.smt2                                                            |  19.503s  |  19.503s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4289.smt2                                                            |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4296.smt2                                                            |  19.775s  |  19.775s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4297.smt2                                                            |  19.877s  |  19.877s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4773.smt2                                                            |  19.936s  |  19.936s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4791.smt2                                                            |  19.870s  |  19.870s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5285.smt2                                                            |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5327.smt2                                                            |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5331.smt2                                                            |   0.831s  |   0.831s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5680.smt2                                                            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5689.smt2                                                            |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5711.smt2                                                            |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5712.smt2                                                            |  19.877s  |  19.877s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5729.smt2                                                            |   0.624s  |   0.624s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5733.smt2                                                            |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5735.smt2                                                            |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5742.smt2                                                            |  19.630s  |  19.630s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5748.smt2                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5749.smt2                                                            |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5751.smt2                                                            |  17.858s  |  17.858s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5769.smt2                                                            |   2.414s  |   2.414s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5771.smt2                                                            |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5782.smt2                                                            |  19.870s  |  19.870s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5793.smt2                                                            |  16.944s  |  16.944s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5794.smt2                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5806.smt2                                                            |   8.388s  |   8.388s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5817.smt2                                                            |   3.471s  |   3.471s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5840.smt2                                                            |  13.575s  |  13.575s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5848.smt2                                                            |  19.947s  |  19.947s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6049.smt2                                                            |  16.299s  |  16.299s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6074.smt2                                                            |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6105.smt2                                                            |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6117.smt2                                                            |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6120.smt2                                                            |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6139.smt2                                                            |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6150.smt2                                                            |   1.049s  |   1.049s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6161.smt2                                                            |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6178.smt2                                                            |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6181.smt2                                                            |   2.763s  |   2.763s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6182.smt2                                                            |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6195.smt2                                                            |   3.174s  |   3.174s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6199.smt2                                                            |  19.884s  |  19.884s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6205.smt2                                                            |  19.561s  |  19.561s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6217.smt2                                                            |  19.790s  |  19.790s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6229.smt2                                                            |  19.902s  |  19.902s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6241.smt2                                                            |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6242.smt2                                                            |   1.354s  |   1.354s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6250.smt2                                                            |  19.675s  |  19.675s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6255.smt2                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6266.smt2                                                            |  19.743s  |  19.743s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6270.smt2                                                            |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6271.smt2                                                            |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6272.smt2                                                            |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6280.smt2                                                            |  19.820s  |  19.820s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6287.smt2                                                            |   0.953s  |   0.953s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6288.smt2                                                            |  19.921s  |  19.921s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6289.smt2                                                            |  19.921s  |  19.921s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6291.smt2                                                            |   1.353s  |   1.353s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6295.smt2                                                            |   7.739s  |   7.739s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6297.smt2                                                            |   1.274s  |   1.274s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6298.smt2                                                            |   2.417s  |   2.417s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6299.smt2                                                            |   1.777s  |   1.777s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6305.smt2                                                            |   0.741s  |   0.741s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6308.smt2                                                            |   0.986s  |   0.986s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6309.smt2                                                            |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6314.smt2                                                            |  19.931s  |  19.931s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6315.smt2                                                            |   1.024s  |   1.024s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6325.smt2                                                            |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6328.smt2                                                            |   0.738s  |   0.738s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6336.smt2                                                            |   4.677s  |   4.677s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6339.smt2                                                            |  19.810s  |  19.810s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6343.smt2                                                            |   0.803s  |   0.803s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6346.smt2                                                            |  19.842s  |  19.842s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6845.smt2                                                            |  19.878s  |  19.878s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7060.smt2                                                            |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7064.smt2                                                            |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7068.smt2                                                            |  19.815s  |  19.815s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7072.smt2                                                            |  19.795s  |  19.795s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7086.smt2                                                            |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7087.smt2                                                            |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7094.smt2                                                            |   2.335s  |   2.335s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7104.smt2                                                            |   0.806s  |   0.806s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7105.smt2                                                            |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7116.smt2                                                            |  19.765s  |  19.765s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7117.smt2                                                            |  19.727s  |  19.727s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7119.smt2                                                            |  19.887s  |  19.887s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7120.smt2                                                            |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7124.smt2                                                            |   2.829s  |   2.829s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7130.smt2                                                            |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7131.smt2                                                            |  19.842s  |  19.842s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7133.smt2                                                            |   9.225s  |   9.225s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7225.smt2                                                            |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7281.smt2                                                            |   6.296s  |   6.296s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7285.smt2                                                            |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7296.smt2                                                            |   2.190s  |   2.190s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7636.smt2                                                            |  19.837s  |  19.837s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7637.smt2                                                            |  17.348s  |  17.348s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7643.smt2                                                            |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7644.smt2                                                            |   3.199s  |   3.199s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7652.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7666.smt2                                                            |  19.913s  |  19.913s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7727.smt2                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7750.smt2                                                            |  19.856s  |  19.856s  |   0.000s  | 0.0%|
|bitops7.smt2                                                                                |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bv-term-small-rw_1391.smt2                                                                  |  19.874s  |  19.874s  |   0.000s  | 0.0%|
|bv-term-small-rw_1516.smt2                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|bv-term-small-rw_166.smt2                                                                   |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|bv-term-small-rw_207.smt2                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bv-term-small-rw_230.smt2                                                                   |  16.013s  |  16.013s  |   0.000s  | 0.0%|
|bv-term-small-rw_250.smt2                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bv-term-small-rw_260.smt2                                                                   |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|bv-term-small-rw_314.smt2                                                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|bv-term-small-rw_318.smt2                                                                   |  19.936s  |  19.936s  |   0.000s  | 0.0%|
|bv-term-small-rw_327.smt2                                                                   |  19.799s  |  19.799s  |   0.000s  | 0.0%|
|bv-term-small-rw_337.smt2                                                                   |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bv-term-small-rw_356.smt2                                                                   |  19.771s  |  19.771s  |   0.000s  | 0.0%|
|bv-term-small-rw_36.smt2                                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bv-term-small-rw_45.smt2                                                                    |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bv-term-small-rw_465.smt2                                                                   |  12.254s  |  12.254s  |   0.000s  | 0.0%|
|bv-term-small-rw_47.smt2                                                                    |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|bv-term-small-rw_521.smt2                                                                   |  19.822s  |  19.822s  |   0.000s  | 0.0%|
|bv-term-small-rw_720.smt2                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|bv-term-small-rw_904.smt2                                                                   |   4.511s  |   4.511s  |   0.000s  | 0.0%|
|bvsdiv.smt2                                                                                 |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|cvs_vc105319.smt2                                                                           |   0.452s  |   0.452s  |   0.000s  | 0.0%|
|cvs_vc105322.smt2                                                                           |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|cvs_vc105323.smt2                                                                           |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|cvs_vc105357.smt2                                                                           |   0.360s  |   0.360s  |   0.000s  | 0.0%|
|cvs_vc105369.smt2                                                                           |   0.992s  |   0.992s  |   0.000s  | 0.0%|
|cvs_vc105421.smt2                                                                           |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|cvs_vc105422.smt2                                                                           |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|cvs_vc105458.smt2                                                                           |   0.582s  |   0.582s  |   0.000s  | 0.0%|
|div.c.20.smt2                                                                               |  19.772s  |  19.772s  |   0.000s  | 0.0%|
|div3.c.20.smt2                                                                              |  19.443s  |  19.443s  |   0.000s  | 0.0%|
|e1_1.c.smt2                                                                                 |  17.612s  |  17.612s  |   0.000s  | 0.0%|
|e2_2.c.smt2                                                                                 |  19.896s  |  19.896s  |   0.000s  | 0.0%|
|f23.smt2                                                                                    |  19.582s  |  19.582s  |   0.000s  | 0.0%|
|fig5.phx.smt2                                                                               |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gryzzles.22.lp.smt2                                                                         |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|gryzzles.8.lp.smt2                                                                          |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|inf1.smt2                                                                                   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|innd_innd_vc32473.smt2                                                                      |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|innd_innd_vc32478.smt2                                                                      |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|innd_innd_vc32492.smt2                                                                      |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|innd_innd_vc32642.smt2                                                                      |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|innd_innd_vc32648.smt2                                                                      |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|innd_innd_vc32659.smt2                                                                      |   0.986s  |   0.986s  |   0.000s  | 0.0%|
|innd_innd_vc32740.smt2                                                                      |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|innd_innd_vc33153.smt2                                                                      |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|innd_innd_vc33158.smt2                                                                      |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|innd_innd_vc33162.smt2                                                                      |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|innd_innd_vc33342.smt2                                                                      |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|innd_innd_vc33343.smt2                                                                      |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|innd_innd_vc33347.smt2                                                                      |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|innd_innd_vc33349.smt2                                                                      |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|innd_innd_vc33528.smt2                                                                      |   1.455s  |   1.455s  |   0.000s  | 0.0%|
|innd_innd_vc33538.smt2                                                                      |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|innd_innd_vc33544.smt2                                                                      |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|innd_innd_vc33561.smt2                                                                      |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|innd_innd_vc33564.smt2                                                                      |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|innd_innd_vc33728.smt2                                                                      |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|innd_innd_vc33732.smt2                                                                      |   0.699s  |   0.699s  |   0.000s  | 0.0%|
|innd_innd_vc33738.smt2                                                                      |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|innd_innd_vc33741.smt2                                                                      |   1.798s  |   1.798s  |   0.000s  | 0.0%|
|innd_innd_vc33743.smt2                                                                      |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24623.smt2                                                               |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24627.smt2                                                               |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24797.smt2                                                               |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24827.smt2                                                               |  19.543s  |  19.543s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24828.smt2                                                               |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24829.smt2                                                               |   7.779s  |   7.779s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24830.smt2                                                               |   0.622s  |   0.622s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc25420.smt2                                                               |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc25433.smt2                                                               |   1.140s  |   1.140s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc25444.smt2                                                               |   0.568s  |   0.568s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc25456.smt2                                                               |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36443.smt2                                                                |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36459.smt2                                                                |  19.748s  |  19.748s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36461.smt2                                                                |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36615.smt2                                                                |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36634.smt2                                                                |  19.913s  |  19.913s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37055.smt2                                                                |   0.984s  |   0.984s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37058.smt2                                                                |   2.642s  |   2.642s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37224.smt2                                                                |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37255.smt2                                                                |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37260.smt2                                                                |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|knightTour.in01.smt2                                                                        |  19.676s  |  19.676s  |   0.000s  | 0.0%|
|matrixsqrt.smt2                                                                             |  19.747s  |  19.747s  |   0.000s  | 0.0%|
|mobiledevice_bit8_na6_nr3_twocond.smt2                                                      |  19.505s  |  19.505s  |   0.000s  | 0.0%|
|mult1.c.20.smt2                                                                             |  19.485s  |  19.485s  |   0.000s  | 0.0%|
|mult2.c.10.smt2                                                                             |  19.933s  |  19.933s  |   0.000s  | 0.0%|
|ndist.b.21996.smt2                                                                          |   1.270s  |   1.270s  |   0.000s  | 0.0%|
|ndist.b.27984.smt2                                                                          |   1.928s  |   1.928s  |   0.000s  | 0.0%|
|ndist.b.28982.smt2                                                                          |   2.039s  |   2.039s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc20411.smt2                                                                    |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21034.smt2                                                                    |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21209.smt2                                                                    |   1.168s  |   1.168s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21211.smt2                                                                    |   0.856s  |   0.856s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21221.smt2                                                                    |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21229.smt2                                                                    |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21232.smt2                                                                    |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21244.smt2                                                                    |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21422.smt2                                                                    |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21427.smt2                                                                    |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21428.smt2                                                                    |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21434.smt2                                                                    |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21435.smt2                                                                    |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21446.smt2                                                                    |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21451.smt2                                                                    |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21636.smt2                                                                    |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21648.smt2                                                                    |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21666.smt2                                                                    |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|predicate_1245.smt2                                                                         |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|predicate_1246.smt2                                                                         |   0.520s  |   0.520s  |   0.000s  | 0.0%|
|predicate_169_0.smt2                                                                        |  12.644s  |  12.644s  |   0.000s  | 0.0%|
|predicate_1898.smt2                                                                         |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|predicate_2077.smt2                                                                         |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|predicate_2801.smt2                                                                         |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|predicate_484.smt2                                                                          |   3.307s  |   3.307s  |   0.000s  | 0.0%|
|predicate_490.smt2                                                                          |   1.314s  |   1.314s  |   0.000s  | 0.0%|
|predicate_493.smt2                                                                          |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|predicate_496.smt2                                                                          |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|problem_1.smt2                                                                              |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|problem_7.smt2                                                                              |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|problem_8.smt2                                                                              |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|problem_9.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|rand_100_400_1159666138_9.lp.smt2                                                           |  19.825s  |  19.825s  |   0.000s  | 0.0%|
|rand_150_600_1159731678_14.lp.smt2                                                          |  19.841s  |  19.841s  |   0.000s  | 0.0%|
|rand_150_600_1159731678_15.lp.smt2                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|rand_200_800_1159728969_10.lp.smt2                                                          |  19.892s  |  19.892s  |   0.000s  | 0.0%|
|rand_20_100_1235851242_0_k-3_v-15_e-25_sat.gph.smt2                                         |  19.810s  |  19.810s  |   0.000s  | 0.0%|
|rand_65_500_1235857888_0_k-6_sat.gph.smt2                                                   |  19.939s  |  19.939s  |   0.000s  | 0.0%|
|rand_80_500_1235848939_0_k-9_sat.gph.smt2                                                   |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|rfunit_flat-64.smt2                                                                         |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__011273.smt2                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__018344.smt2                                                     |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__019220.smt2                                                     |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__020079.smt2                                                     |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|run_00000.trace.cond_016653_0x95026e6_00.smt2                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|run_00000.trace.cond_017116_0x950130a_00.smt2                                               |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|run_00000.trace.cond_017924_0x950130a_00.smt2                                               |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|run_00000.trace.cond_018783_0x950130a_00.smt2                                               |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|run_00000.trace.cond_019196_0x95026e6_00.smt2                                               |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|run_00000.trace.cond_019659_0x950130a_00.smt2                                               |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|run_00000.trace.cond_020055_0x95026e6_00.smt2                                               |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|run_00000.trace.cond_285172_0xe7af40_00.smt2                                                |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|run_00000.trace.cond_285198_0xe7af87_00.smt2                                                |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|run_00000.trace.cond_455476_0xe7af69_00.smt2                                                |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|run_00012.trace.cond_057573_0x16388_00.smt2                                                 |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|run_03230.trace.cond_000028_0x40201f_00.smt2                                                |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|run_03230.trace.cond_000032_0x40248d_00.smt2                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011742_0x4066e2_00.smt2                                                |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011923_0x4182b4_00.smt2                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011951_0x4182b4_00.smt2                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011955_0x4182de_00.smt2                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011969_0x4182de_00.smt2                                                |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012011_0x4182de_00.smt2                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012035_0x4182b4_00.smt2                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012053_0x4182de_00.smt2                                                |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012133_0x4182b4_00.smt2                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012161_0x4182b4_00.smt2                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012175_0x4182b4_00.smt2                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025314_0x41821d_00.smt2                                                |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025405_0x418209_00.smt2                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025439_0x418209_00.smt2                                                |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025442_0x41821d_00.smt2                                                |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025454_0x418209_00.smt2                                                |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025469_0x418209_00.smt2                                                |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025506_0x41821d_00.smt2                                                |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025552_0x41820e_00.smt2                                                |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025570_0x41821d_00.smt2                                                |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025582_0x418209_00.smt2                                                |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025597_0x418209_00.smt2                                                |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025600_0x41821d_00.smt2                                                |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025616_0x41820e_00.smt2                                                |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025638_0x41821d_00.smt2                                                |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|send-more-money.smt2                                                                        |  13.688s  |  13.688s  |   0.000s  | 0.0%|
|servers_slapd_a_vc149572.smt2                                                               |   1.023s  |   1.023s  |   0.000s  | 0.0%|
|servers_slapd_a_vc149789.smt2                                                               |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|simple_bit8_na1_nr1_twocond.smt2                                                            |   0.893s  |   0.893s  |   0.000s  | 0.0%|
|smulov4bw1024.smt2                                                                          |  19.871s  |  19.871s  |   0.000s  | 0.0%|
|sort.smt2                                                                                   |  19.953s  |  19.953s  |   0.000s  | 0.0%|
|src_wget_vc17453.smt2                                                                       |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|src_wget_vc17891.smt2                                                                       |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|src_wget_vc17906.smt2                                                                       |   2.260s  |   2.260s  |   0.000s  | 0.0%|
|src_wget_vc17911.smt2                                                                       |   1.272s  |   1.272s  |   0.000s  | 0.0%|
|src_wget_vc17912.smt2                                                                       |   0.831s  |   0.831s  |   0.000s  | 0.0%|
|src_wget_vc17913.smt2                                                                       |   1.683s  |   1.683s  |   0.000s  | 0.0%|
|src_wget_vc18169.smt2                                                                       |   1.057s  |   1.057s  |   0.000s  | 0.0%|
|src_wget_vc18506.smt2                                                                       |   8.672s  |   8.672s  |   0.000s  | 0.0%|
|test_v3_r3_vr10_c1_s24300.smt2                                                              |  19.936s  |  19.936s  |   0.000s  | 0.0%|
|try3_noof_functions_dwp_stty.visible.il.dwp.smt2                                            |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|try3_noof_functions_dwp_touch.yyerror.il.dwp.smt2                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_dwp_cut.hash_int.il.dwp.smt2                                      |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_noof_functions_dwp_expr.nomoreargs.il.dwp.smt2                                   |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_noof_functions_dwp_stty.visible.il.dwp.smt2                                      |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_cat.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_chgrp.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_cut.hash_int.il.flanagansaxe.smt2                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_echo.quoting_options_from_style.il.flanagansaxe.smt2  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_env.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_fold.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_hostid.quoting_options_from_style.il.flanagansaxe.smt2  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_kill.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_link.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_mkfifo.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_nice.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_nl.quoting_options_from_style.il.flanagansaxe.smt2   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_pinky.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_ptx.quoting_options_from_style.il.flanagansaxe.smt2  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_seq.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_sleep.quoting_options_from_style.il.flanagansaxe.smt2  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_sum.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_tac.quoting_options_from_style.il.flanagansaxe.smt2  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_test.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_touch.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_true.quoting_options_from_style.il.flanagansaxe.smt2  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_tsort.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_tty.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_unexpand.quoting_options_from_style.il.flanagansaxe.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_users.quoting_options_from_style.il.flanagansaxe.smt2  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_vdir.quoting_options_from_style.il.flanagansaxe.smt2  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_wc.quoting_options_from_style.il.flanagansaxe.smt2   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_fse-bfs_shuf.input_numbers_option_used.il.fse-bfs.smt2            |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_true_functions_dwp_stty.visible.il.dwp.smt2                                      |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_true_functions_dwp_yes.close_stdout_set_file_name.il.dwp.smt2                    |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_chgrp.i_ring_init.il.flanagansaxe.smt2               |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_join.initseq.il.flanagansaxe.smt2                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_md5sum.md5_init_ctx.il.flanagansaxe.smt2             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_sha1sum.sha1_read_ctx.il.flanagansaxe.smt2           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_stty.visible.il.flanagansaxe.smt2                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_tac.rpl_re_set_syntax.il.flanagansaxe.smt2           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_vdir.hash_get_n_entries.il.flanagansaxe.smt2         |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_vdir.unsigned_file_size.il.flanagansaxe.smt2         |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|try5_small_true_functions_fse-bfs_stty.visible.il.fse-bfs.smt2                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|unconstrained04.smt2                                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|unconstrained07.smt2                                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|unconstrained08.smt2                                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
</details>
