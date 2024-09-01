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
Job tag: bvsls
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 39eaf62040498d51c93a03a22907510a0c8992db
Z3 branch: sls
Z3 options: "-T:2 -v:2 -model_validate=true st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)""
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: Remove typename from member declarations in bv_fixed class

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: bvsls
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 39eaf62040498d51c93a03a22907510a0c8992db
Z3 branch: sls
Z3 options: "-T:2 -v:2 -model_validate=true st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)""
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: Remove typename from member declarations in bv_fixed class

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
|try5_small_noof_functions_dwp_cut.hash_int.il.dwp.smt2                                     |   0.005s |840.0KiB|
|bench_5183.smt2                                                                            |   0.004s |840.0KiB|
|bench_1196.smt2                                                                            |   0.004s |840.0KiB|
|bench_2849.smt2                                                                            |   0.004s |840.0KiB|
|bench_2265.smt2                                                                            |   0.004s |824.0KiB|
|bench_639.smt2                                                                             |   0.004s |844.0KiB|
|bench_9946.smt2                                                                            |   0.004s |1056.0KiB|
|bench_2957.smt2                                                                            |   0.004s |844.0KiB|
|bench_6848.smt2                                                                            |   0.004s |1008.0KiB|
|bench_531.smt2                                                                             |   0.004s |844.0KiB|
|bench_944.smt2                                                                             |   0.004s |840.0KiB|
|bench_6458.smt2                                                                            |   0.004s |840.0KiB|
|bench_8283.smt2                                                                            |   0.004s |840.0KiB|
|bench_7867.smt2                                                                            |   0.004s |892.0KiB|
|bin_libsmbsharemodes_vc5749.smt2                                                           |   0.004s |840.0KiB|
|Sz512_15128_1.smt2                                                                         |   0.004s |872.0KiB|
|bench_993.smt2                                                                             |   0.003s |932.0KiB|
|bench_5153.smt2                                                                            |   0.003s |836.0KiB|
|a407test0024.smt2                                                                          |   0.003s |840.0KiB|
|bench_1869.smt2                                                                            |   0.003s |960.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|try5_small_noof_functions_dwp_cut.hash_int.il.dwp.smt2                                     |   0.005s |840.0KiB|
|bench_5183.smt2                                                                            |   0.004s |840.0KiB|
|bench_1196.smt2                                                                            |   0.004s |840.0KiB|
|bench_2849.smt2                                                                            |   0.004s |840.0KiB|
|bench_2265.smt2                                                                            |   0.004s |824.0KiB|
|bench_639.smt2                                                                             |   0.004s |844.0KiB|
|bench_9946.smt2                                                                            |   0.004s |1056.0KiB|
|bench_2957.smt2                                                                            |   0.004s |844.0KiB|
|bench_6848.smt2                                                                            |   0.004s |1008.0KiB|
|bench_531.smt2                                                                             |   0.004s |844.0KiB|
|bench_944.smt2                                                                             |   0.004s |840.0KiB|
|bench_6458.smt2                                                                            |   0.004s |840.0KiB|
|bench_8283.smt2                                                                            |   0.004s |840.0KiB|
|bench_7867.smt2                                                                            |   0.004s |892.0KiB|
|bin_libsmbsharemodes_vc5749.smt2                                                           |   0.004s |840.0KiB|
|Sz512_15128_1.smt2                                                                         |   0.004s |872.0KiB|
|bench_993.smt2                                                                             |   0.003s |932.0KiB|
|bench_5153.smt2                                                                            |   0.003s |836.0KiB|
|a407test0024.smt2                                                                          |   0.003s |840.0KiB|
|bench_1869.smt2                                                                            |   0.003s |960.0KiB|
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
|cvs_vc105323.smt2                                                                          |   0.002s |1492.0KiB|
|bin_libsmbsharemodes_vc5793.smt2                                                           |   0.002s |1208.0KiB|
|bin_libmsrpc_vc1225626.smt2                                                                |   0.001s |1208.0KiB|
|bench_3091.smt2                                                                            |   0.001s |1124.0KiB|
|knightTour.in01.smt2                                                                       |   0.002s |1104.0KiB|
|bench_7833.smt2                                                                            |   0.002s |1100.0KiB|
|bin_libmsrpc_vc1228509.smt2                                                                |   0.002s |1100.0KiB|
|bench_11151.smt2                                                                           |   0.002s |1096.0KiB|
|bench_402.smt2                                                                             |   0.002s |1096.0KiB|
|bench_5222.smt2                                                                            |   0.002s |1096.0KiB|
|bench_3882.smt2                                                                            |   0.002s |1096.0KiB|
|bench_7242.smt2                                                                            |   0.002s |1096.0KiB|
|bench_1578.smt2                                                                            |   0.002s |1096.0KiB|
|bvsdiv.smt2                                                                                |   0.002s |1096.0KiB|
|bench_3886.smt2                                                                            |   0.002s |1096.0KiB|
|bench_5765.smt2                                                                            |   0.001s |1096.0KiB|
|bench_1355.smt2                                                                            |   0.001s |1096.0KiB|
|bench_1081.smt2                                                                            |   0.002s |1092.0KiB|
|bench_10726.smt2                                                                           |   0.002s |1088.0KiB|
|bench_1467.smt2                                                                            |   0.001s |1088.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|cvs_vc105323.smt2                                                                          |   0.002s |1492.0KiB|
|bin_libsmbsharemodes_vc5793.smt2                                                           |   0.002s |1208.0KiB|
|bin_libmsrpc_vc1225626.smt2                                                                |   0.001s |1208.0KiB|
|bench_3091.smt2                                                                            |   0.001s |1124.0KiB|
|knightTour.in01.smt2                                                                       |   0.002s |1104.0KiB|
|bench_7833.smt2                                                                            |   0.002s |1100.0KiB|
|bin_libmsrpc_vc1228509.smt2                                                                |   0.002s |1100.0KiB|
|bench_11151.smt2                                                                           |   0.002s |1096.0KiB|
|bench_402.smt2                                                                             |   0.002s |1096.0KiB|
|bench_5222.smt2                                                                            |   0.002s |1096.0KiB|
|bench_3882.smt2                                                                            |   0.002s |1096.0KiB|
|bench_7242.smt2                                                                            |   0.002s |1096.0KiB|
|bench_1578.smt2                                                                            |   0.002s |1096.0KiB|
|bvsdiv.smt2                                                                                |   0.002s |1096.0KiB|
|bench_3886.smt2                                                                            |   0.002s |1096.0KiB|
|bench_5765.smt2                                                                            |   0.001s |1096.0KiB|
|bench_1355.smt2                                                                            |   0.001s |1096.0KiB|
|bench_1081.smt2                                                                            |   0.002s |1092.0KiB|
|bench_10726.smt2                                                                           |   0.002s |1088.0KiB|
|bench_1467.smt2                                                                            |   0.001s |1088.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
