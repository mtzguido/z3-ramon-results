Comparing data and data


# SUMMARY
- LHS tests = 2000
- RHS tests = 2000
- LHS success = 0  (0.0%)
- RHS success = 0  (0.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-top
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: bed085934f4d0f5980191cecf17bb70639c6a878
Z3 branch: master
Z3 options: "-T:20 -v:2 -st sls.use_top_level_assertions=true tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: bugfixes to bv-sls

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-top
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: bed085934f4d0f5980191cecf17bb70639c6a878
Z3 branch: master
Z3 options: "-T:20 -v:2 -st sls.use_top_level_assertions=true tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: bugfixes to bv-sls

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_5645.smt2                                                                            |   0.005s |1096.0KiB|
|bv-term-small-rw_318.smt2                                                                  |   0.004s |1060.0KiB|
|bench_8051.smt2                                                                            |   0.004s |1100.0KiB|
|bench_8110.smt2                                                                            |   0.004s |1048.0KiB|
|bench_4065.smt2                                                                            |   0.004s |1092.0KiB|
|bin_libsmbsharemodes_vc7120.smt2                                                           |   0.004s |1080.0KiB|
|bench_4755.smt2                                                                            |   0.004s |848.0KiB|
|bench_4173.smt2                                                                            |   0.004s |1096.0KiB|
|bench_8492.smt2                                                                            |   0.004s |1096.0KiB|
|bench_12246.smt2                                                                           |   0.004s |1096.0KiB|
|bin_libsmbsharemodes_vc7750.smt2                                                           |   0.004s |1096.0KiB|
|bench_10726.smt2                                                                           |   0.004s |1100.0KiB|
|bench_536.smt2                                                                             |   0.004s |1096.0KiB|
|try5_small_noof_functions_flanagansaxe_tty.quoting_options_from_style.il.flanagansaxe.smt2 |   0.004s |1096.0KiB|
|bench_3239.smt2                                                                            |   0.004s |864.0KiB|
|bench_6691.smt2                                                                            |   0.004s |1096.0KiB|
|bench_2676.smt2                                                                            |   0.004s |1096.0KiB|
|bench_3906.smt2                                                                            |   0.004s |1096.0KiB|
|bench_10127.smt2                                                                           |   0.004s |1100.0KiB|
|bench_1652.smt2                                                                            |   0.004s |1076.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_5645.smt2                                                                            |   0.005s |1096.0KiB|
|bv-term-small-rw_318.smt2                                                                  |   0.004s |1060.0KiB|
|bench_8051.smt2                                                                            |   0.004s |1100.0KiB|
|bench_8110.smt2                                                                            |   0.004s |1048.0KiB|
|bench_4065.smt2                                                                            |   0.004s |1092.0KiB|
|bin_libsmbsharemodes_vc7120.smt2                                                           |   0.004s |1080.0KiB|
|bench_4755.smt2                                                                            |   0.004s |848.0KiB|
|bench_4173.smt2                                                                            |   0.004s |1096.0KiB|
|bench_8492.smt2                                                                            |   0.004s |1096.0KiB|
|bench_12246.smt2                                                                           |   0.004s |1096.0KiB|
|bin_libsmbsharemodes_vc7750.smt2                                                           |   0.004s |1096.0KiB|
|bench_10726.smt2                                                                           |   0.004s |1100.0KiB|
|bench_536.smt2                                                                             |   0.004s |1096.0KiB|
|try5_small_noof_functions_flanagansaxe_tty.quoting_options_from_style.il.flanagansaxe.smt2 |   0.004s |1096.0KiB|
|bench_3239.smt2                                                                            |   0.004s |864.0KiB|
|bench_6691.smt2                                                                            |   0.004s |1096.0KiB|
|bench_2676.smt2                                                                            |   0.004s |1096.0KiB|
|bench_3906.smt2                                                                            |   0.004s |1096.0KiB|
|bench_10127.smt2                                                                           |   0.004s |1100.0KiB|
|bench_1652.smt2                                                                            |   0.004s |1076.0KiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_1355.smt2                                                                            |   0.001s |1380.0KiB|
|bin_libsmbsharemodes_vc6328.smt2                                                           |   0.002s |1352.0KiB|
|bench_424.smt2                                                                             |   0.002s |1352.0KiB|
|bench_3114.smt2                                                                            |   0.001s |1352.0KiB|
|bench_2550.smt2                                                                            |   0.002s |1344.0KiB|
|bench_7663.smt2                                                                            |   0.001s |1224.0KiB|
|unconstrained10.smt2                                                                       |   0.002s |1216.0KiB|
|ndist.b.27984.smt2                                                                         |   0.003s |1136.0KiB|
|bench_4505.smt2                                                                            |   0.002s |1116.0KiB|
|bench_1778.smt2                                                                            |   0.003s |1112.0KiB|
|bench_3964.smt2                                                                            |   0.002s |1112.0KiB|
|bench_1614.smt2                                                                            |   0.002s |1108.0KiB|
|bench_1335.smt2                                                                            |   0.002s |1108.0KiB|
|bench_1367.smt2                                                                            |   0.002s |1108.0KiB|
|bench_712.smt2                                                                             |   0.002s |1108.0KiB|
|bench_2407.smt2                                                                            |   0.001s |1108.0KiB|
|bench_5340.smt2                                                                            |   0.003s |1104.0KiB|
|bench_749.smt2                                                                             |   0.003s |1104.0KiB|
|15.smt2                                                                                    |   0.003s |1104.0KiB|
|bench_28.smt2                                                                              |   0.002s |1104.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_1355.smt2                                                                            |   0.001s |1380.0KiB|
|bin_libsmbsharemodes_vc6328.smt2                                                           |   0.002s |1352.0KiB|
|bench_424.smt2                                                                             |   0.002s |1352.0KiB|
|bench_3114.smt2                                                                            |   0.001s |1352.0KiB|
|bench_2550.smt2                                                                            |   0.002s |1344.0KiB|
|bench_7663.smt2                                                                            |   0.001s |1224.0KiB|
|unconstrained10.smt2                                                                       |   0.002s |1216.0KiB|
|ndist.b.27984.smt2                                                                         |   0.003s |1136.0KiB|
|bench_4505.smt2                                                                            |   0.002s |1116.0KiB|
|bench_1778.smt2                                                                            |   0.003s |1112.0KiB|
|bench_3964.smt2                                                                            |   0.002s |1112.0KiB|
|bench_1614.smt2                                                                            |   0.002s |1108.0KiB|
|bench_1335.smt2                                                                            |   0.002s |1108.0KiB|
|bench_1367.smt2                                                                            |   0.002s |1108.0KiB|
|bench_712.smt2                                                                             |   0.002s |1108.0KiB|
|bench_2407.smt2                                                                            |   0.001s |1108.0KiB|
|bench_5340.smt2                                                                            |   0.003s |1104.0KiB|
|bench_749.smt2                                                                             |   0.003s |1104.0KiB|
|15.smt2                                                                                    |   0.003s |1104.0KiB|
|bench_28.smt2                                                                              |   0.002s |1104.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
