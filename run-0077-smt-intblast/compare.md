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
Job tag: smt-intblast
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 040c29a1528f8add3bd2109b601071b005686540
Z3 branch: sls
Z3 options: "-T:20 -v:2 smb.bv.solver=2 smt.sls.enable=false sat.smt=false -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: update model generation to fix model bug

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-intblast
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 040c29a1528f8add3bd2109b601071b005686540
Z3 branch: sls
Z3 options: "-T:20 -v:2 smb.bv.solver=2 smt.sls.enable=false sat.smt=false -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: update model generation to fix model bug

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
|bench_4065.smt2                                                                            |   0.005s |1096.0KiB|
|bench_4873.smt2                                                                            |   0.005s |840.0KiB|
|rand_150_600_1159731678_15.lp.smt2                                                         |   0.005s |932.0KiB|
|bench_3221.smt2                                                                            |   0.005s |1084.0KiB|
|bench_3268.smt2                                                                            |   0.004s |840.0KiB|
|bench_1680.smt2                                                                            |   0.004s |1088.0KiB|
|bench_1761.smt2                                                                            |   0.004s |840.0KiB|
|bench_2070.smt2                                                                            |   0.004s |1052.0KiB|
|bench_5377.smt2                                                                            |   0.004s |1056.0KiB|
|bench_8562.smt2                                                                            |   0.004s |852.0KiB|
|try5_small_noof_functions_flanagansaxe_touch.quoting_options_from_style.il.flanagansaxe.smt2 |   0.004s |840.0KiB|
|bench_253.smt2                                                                             |   0.004s |836.0KiB|
|bench_9535.smt2                                                                            |   0.004s |960.0KiB|
|bin_libsmbsharemodes_vc7750.smt2                                                           |   0.004s |960.0KiB|
|bench_4555.smt2                                                                            |   0.004s |840.0KiB|
|bench_2044.smt2                                                                            |   0.004s |1096.0KiB|
|bench_4375.smt2                                                                            |   0.004s |840.0KiB|
|bench_4412.smt2                                                                            |   0.004s |1076.0KiB|
|bench_3239.smt2                                                                            |   0.004s |840.0KiB|
|bench_16640.smt2                                                                           |   0.004s |840.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_4065.smt2                                                                            |   0.005s |1096.0KiB|
|bench_4873.smt2                                                                            |   0.005s |840.0KiB|
|rand_150_600_1159731678_15.lp.smt2                                                         |   0.005s |932.0KiB|
|bench_3221.smt2                                                                            |   0.005s |1084.0KiB|
|bench_3268.smt2                                                                            |   0.004s |840.0KiB|
|bench_1680.smt2                                                                            |   0.004s |1088.0KiB|
|bench_1761.smt2                                                                            |   0.004s |840.0KiB|
|bench_2070.smt2                                                                            |   0.004s |1052.0KiB|
|bench_5377.smt2                                                                            |   0.004s |1056.0KiB|
|bench_8562.smt2                                                                            |   0.004s |852.0KiB|
|try5_small_noof_functions_flanagansaxe_touch.quoting_options_from_style.il.flanagansaxe.smt2 |   0.004s |840.0KiB|
|bench_253.smt2                                                                             |   0.004s |836.0KiB|
|bench_9535.smt2                                                                            |   0.004s |960.0KiB|
|bin_libsmbsharemodes_vc7750.smt2                                                           |   0.004s |960.0KiB|
|bench_4555.smt2                                                                            |   0.004s |840.0KiB|
|bench_2044.smt2                                                                            |   0.004s |1096.0KiB|
|bench_4375.smt2                                                                            |   0.004s |840.0KiB|
|bench_4412.smt2                                                                            |   0.004s |1076.0KiB|
|bench_3239.smt2                                                                            |   0.004s |840.0KiB|
|bench_16640.smt2                                                                           |   0.004s |840.0KiB|
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
|bin_libsmbsharemodes_vc7068.smt2                                                           |   0.002s |1352.0KiB|
|bench_5081.smt2                                                                            |   0.002s |1304.0KiB|
|bench_5532.smt2                                                                            |   0.001s |1276.0KiB|
|innd_innd_vc33538.smt2                                                                     |   0.002s |1176.0KiB|
|bench_2022.smt2                                                                            |   0.002s |1156.0KiB|
|rand_200_800_1159728969_10.lp.smt2                                                         |   0.002s |1104.0KiB|
|bench_4706.smt2                                                                            |   0.001s |1104.0KiB|
|bin_libsmbsharemodes_vc7116.smt2                                                           |   0.003s |1100.0KiB|
|bin_libsmbsharemodes_vc4243.smt2                                                           |   0.003s |1100.0KiB|
|bench_3351.smt2                                                                            |   0.002s |1100.0KiB|
|bench_3367.smt2                                                                            |   0.002s |1100.0KiB|
|innd_innd_vc32648.smt2                                                                     |   0.002s |1100.0KiB|
|bench_10832.smt2                                                                           |   0.002s |1100.0KiB|
|bench_1414.smt2                                                                            |   0.002s |1100.0KiB|
|bench_302.smt2                                                                             |   0.002s |1100.0KiB|
|bench_12246.smt2                                                                           |   0.002s |1100.0KiB|
|bin_libsmbsharemodes_vc6328.smt2                                                           |   0.002s |1100.0KiB|
|bv-term-small-rw_356.smt2                                                                  |   0.002s |1100.0KiB|
|bench_1946.smt2                                                                            |   0.002s |1100.0KiB|
|bench_3951.smt2                                                                            |   0.002s |1100.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bin_libsmbsharemodes_vc7068.smt2                                                           |   0.002s |1352.0KiB|
|bench_5081.smt2                                                                            |   0.002s |1304.0KiB|
|bench_5532.smt2                                                                            |   0.001s |1276.0KiB|
|innd_innd_vc33538.smt2                                                                     |   0.002s |1176.0KiB|
|bench_2022.smt2                                                                            |   0.002s |1156.0KiB|
|rand_200_800_1159728969_10.lp.smt2                                                         |   0.002s |1104.0KiB|
|bench_4706.smt2                                                                            |   0.001s |1104.0KiB|
|bin_libsmbsharemodes_vc7116.smt2                                                           |   0.003s |1100.0KiB|
|bin_libsmbsharemodes_vc4243.smt2                                                           |   0.003s |1100.0KiB|
|bench_3351.smt2                                                                            |   0.002s |1100.0KiB|
|bench_3367.smt2                                                                            |   0.002s |1100.0KiB|
|innd_innd_vc32648.smt2                                                                     |   0.002s |1100.0KiB|
|bench_10832.smt2                                                                           |   0.002s |1100.0KiB|
|bench_1414.smt2                                                                            |   0.002s |1100.0KiB|
|bench_302.smt2                                                                             |   0.002s |1100.0KiB|
|bench_12246.smt2                                                                           |   0.002s |1100.0KiB|
|bin_libsmbsharemodes_vc6328.smt2                                                           |   0.002s |1100.0KiB|
|bv-term-small-rw_356.smt2                                                                  |   0.002s |1100.0KiB|
|bench_1946.smt2                                                                            |   0.002s |1100.0KiB|
|bench_3951.smt2                                                                            |   0.002s |1100.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
