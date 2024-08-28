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
Job tag: smt-sls-no-lookahead
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 05f166f736476e628909829e0d5e1da242223d15
Z3 branch: master
Z3 options: "-T:20 -v:2 -st use_lookahead_bv=false tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: add py_value to selected classes in python bindings, add mode for input-assertion based lookahead solving

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-no-lookahead
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 05f166f736476e628909829e0d5e1da242223d15
Z3 branch: master
Z3 options: "-T:20 -v:2 -st use_lookahead_bv=false tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: add py_value to selected classes in python bindings, add mode for input-assertion based lookahead solving

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
|bench_17082.smt2                                                                           |   0.005s |840.0KiB|
|bench_5150.smt2                                                                            |   0.005s |1100.0KiB|
|bench_1349.smt2                                                                            |   0.004s |1072.0KiB|
|bench_4894.smt2                                                                            |   0.004s |1096.0KiB|
|bench_808.smt2                                                                             |   0.004s |1048.0KiB|
|bench_8282.smt2                                                                            |   0.004s |1096.0KiB|
|bench_1712.smt2                                                                            |   0.004s |836.0KiB|
|bench_1400.smt2                                                                            |   0.004s |984.0KiB|
|bench_17033.smt2                                                                           |   0.004s |1096.0KiB|
|QF_BV_bv_bv_resistance.2.prop1_cc_ref_max.smt2                                             |   0.004s |1092.0KiB|
|nnrpd_nnrpd_vc21209.smt2                                                                   |   0.004s |1096.0KiB|
|bench_2248.smt2                                                                            |   0.004s |1076.0KiB|
|bench_1332.smt2                                                                            |   0.004s |1096.0KiB|
|predicate_2801.smt2                                                                        |   0.004s |840.0KiB|
|bench_1250.smt2                                                                            |   0.004s |956.0KiB|
|bench_6848.smt2                                                                            |   0.004s |1096.0KiB|
|bench_988.smt2                                                                             |   0.004s |1068.0KiB|
|bench_3881.smt2                                                                            |   0.004s |1096.0KiB|
|bench_993.smt2                                                                             |   0.003s |1096.0KiB|
|cvs_vc105458.smt2                                                                          |   0.003s |844.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_17082.smt2                                                                           |   0.005s |840.0KiB|
|bench_5150.smt2                                                                            |   0.005s |1100.0KiB|
|bench_1349.smt2                                                                            |   0.004s |1072.0KiB|
|bench_4894.smt2                                                                            |   0.004s |1096.0KiB|
|bench_808.smt2                                                                             |   0.004s |1048.0KiB|
|bench_8282.smt2                                                                            |   0.004s |1096.0KiB|
|bench_1712.smt2                                                                            |   0.004s |836.0KiB|
|bench_1400.smt2                                                                            |   0.004s |984.0KiB|
|bench_17033.smt2                                                                           |   0.004s |1096.0KiB|
|QF_BV_bv_bv_resistance.2.prop1_cc_ref_max.smt2                                             |   0.004s |1092.0KiB|
|nnrpd_nnrpd_vc21209.smt2                                                                   |   0.004s |1096.0KiB|
|bench_2248.smt2                                                                            |   0.004s |1076.0KiB|
|bench_1332.smt2                                                                            |   0.004s |1096.0KiB|
|predicate_2801.smt2                                                                        |   0.004s |840.0KiB|
|bench_1250.smt2                                                                            |   0.004s |956.0KiB|
|bench_6848.smt2                                                                            |   0.004s |1096.0KiB|
|bench_988.smt2                                                                             |   0.004s |1068.0KiB|
|bench_3881.smt2                                                                            |   0.004s |1096.0KiB|
|bench_993.smt2                                                                             |   0.003s |1096.0KiB|
|cvs_vc105458.smt2                                                                          |   0.003s |844.0KiB|
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
|bench_1467.smt2                                                                            |   0.001s |1356.0KiB|
|bench_1222.smt2                                                                            |   0.001s |1352.0KiB|
|bench_15547.smt2                                                                           |   0.001s |1348.0KiB|
|bench_1318.smt2                                                                            |   0.002s |1340.0KiB|
|bench_7278.smt2                                                                            |   0.002s |1328.0KiB|
|bench_3539.smt2                                                                            |   0.002s |1320.0KiB|
|try3_noof_functions_dwp_stty.visible.il.dwp.smt2                                           |   0.002s |1308.0KiB|
|bench_1355.smt2                                                                            |   0.001s |1300.0KiB|
|bench_142.smt2                                                                             |   0.002s |1216.0KiB|
|bench_8487.smt2                                                                            |   0.002s |1216.0KiB|
|bench_5440.smt2                                                                            |   0.002s |1184.0KiB|
|bin_libmsrpc_vc1228472.smt2                                                                |   0.002s |1112.0KiB|
|try5_small_noof_functions_flanagansaxe_tty.quoting_options_from_style.il.flanagansaxe.smt2 |   0.002s |1104.0KiB|
|bench_5150.smt2                                                                            |   0.005s |1100.0KiB|
|bench_6906.smt2                                                                            |   0.003s |1100.0KiB|
|bench_2757.smt2                                                                            |   0.003s |1100.0KiB|
|VS3-benchmark-S1.smt2                                                                      |   0.003s |1100.0KiB|
|bench_2844.smt2                                                                            |   0.003s |1100.0KiB|
|bench_2574.smt2                                                                            |   0.003s |1100.0KiB|
|bench_5191.smt2                                                                            |   0.003s |1100.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_1467.smt2                                                                            |   0.001s |1356.0KiB|
|bench_1222.smt2                                                                            |   0.001s |1352.0KiB|
|bench_15547.smt2                                                                           |   0.001s |1348.0KiB|
|bench_1318.smt2                                                                            |   0.002s |1340.0KiB|
|bench_7278.smt2                                                                            |   0.002s |1328.0KiB|
|bench_3539.smt2                                                                            |   0.002s |1320.0KiB|
|try3_noof_functions_dwp_stty.visible.il.dwp.smt2                                           |   0.002s |1308.0KiB|
|bench_1355.smt2                                                                            |   0.001s |1300.0KiB|
|bench_142.smt2                                                                             |   0.002s |1216.0KiB|
|bench_8487.smt2                                                                            |   0.002s |1216.0KiB|
|bench_5440.smt2                                                                            |   0.002s |1184.0KiB|
|bin_libmsrpc_vc1228472.smt2                                                                |   0.002s |1112.0KiB|
|try5_small_noof_functions_flanagansaxe_tty.quoting_options_from_style.il.flanagansaxe.smt2 |   0.002s |1104.0KiB|
|bench_5150.smt2                                                                            |   0.005s |1100.0KiB|
|bench_6906.smt2                                                                            |   0.003s |1100.0KiB|
|bench_2757.smt2                                                                            |   0.003s |1100.0KiB|
|VS3-benchmark-S1.smt2                                                                      |   0.003s |1100.0KiB|
|bench_2844.smt2                                                                            |   0.003s |1100.0KiB|
|bench_2574.smt2                                                                            |   0.003s |1100.0KiB|
|bench_5191.smt2                                                                            |   0.003s |1100.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
