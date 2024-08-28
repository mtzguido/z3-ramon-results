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
Job tag: smt-sls
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: bed085934f4d0f5980191cecf17bb70639c6a878
Z3 branch: master
Z3 options: "-T:20 -sls.use_top_level_assertions_bv=true v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: bugfixes to bv-sls

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: bed085934f4d0f5980191cecf17bb70639c6a878
Z3 branch: master
Z3 options: "-T:20 -sls.use_top_level_assertions_bv=true v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
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
|bench_4522.smt2                                                                            |   0.004s |840.0KiB|
|bench_7182.smt2                                                                            |   0.004s |844.0KiB|
|bin_libsmbclient_vc1225303.smt2                                                            |   0.004s |840.0KiB|
|bench_2701.smt2                                                                            |   0.004s |828.0KiB|
|problem_7.smt2                                                                             |   0.004s |1056.0KiB|
|bench_565.smt2                                                                             |   0.004s |840.0KiB|
|bench_5326.smt2                                                                            |   0.004s |844.0KiB|
|a407test0024.smt2                                                                          |   0.003s |844.0KiB|
|rfunit_flat-64.smt2                                                                        |   0.003s |900.0KiB|
|bench_7421.smt2                                                                            |   0.003s |840.0KiB|
|bench_5340.smt2                                                                            |   0.003s |840.0KiB|
|bench_4894.smt2                                                                            |   0.003s |840.0KiB|
|bench_1235.smt2                                                                            |   0.003s |840.0KiB|
|nnrpd_nnrpd_vc21451.smt2                                                                   |   0.003s |1052.0KiB|
|bench_3352.smt2                                                                            |   0.003s |1096.0KiB|
|bench_3561.smt2                                                                            |   0.003s |840.0KiB|
|innfeed_innfeed_vc37224.smt2                                                               |   0.003s |1032.0KiB|
|bench_3145.smt2                                                                            |   0.003s |868.0KiB|
|bv-term-small-rw_318.smt2                                                                  |   0.003s |840.0KiB|
|bin_libsmbclient_vc1225236.smt2                                                            |   0.003s |840.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_4522.smt2                                                                            |   0.004s |840.0KiB|
|bench_7182.smt2                                                                            |   0.004s |844.0KiB|
|bin_libsmbclient_vc1225303.smt2                                                            |   0.004s |840.0KiB|
|bench_2701.smt2                                                                            |   0.004s |828.0KiB|
|problem_7.smt2                                                                             |   0.004s |1056.0KiB|
|bench_565.smt2                                                                             |   0.004s |840.0KiB|
|bench_5326.smt2                                                                            |   0.004s |844.0KiB|
|a407test0024.smt2                                                                          |   0.003s |844.0KiB|
|rfunit_flat-64.smt2                                                                        |   0.003s |900.0KiB|
|bench_7421.smt2                                                                            |   0.003s |840.0KiB|
|bench_5340.smt2                                                                            |   0.003s |840.0KiB|
|bench_4894.smt2                                                                            |   0.003s |840.0KiB|
|bench_1235.smt2                                                                            |   0.003s |840.0KiB|
|nnrpd_nnrpd_vc21451.smt2                                                                   |   0.003s |1052.0KiB|
|bench_3352.smt2                                                                            |   0.003s |1096.0KiB|
|bench_3561.smt2                                                                            |   0.003s |840.0KiB|
|innfeed_innfeed_vc37224.smt2                                                               |   0.003s |1032.0KiB|
|bench_3145.smt2                                                                            |   0.003s |868.0KiB|
|bv-term-small-rw_318.smt2                                                                  |   0.003s |840.0KiB|
|bin_libsmbclient_vc1225236.smt2                                                            |   0.003s |840.0KiB|
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
|bin_libsmbsharemodes_vc4297.smt2                                                           |   0.001s |1260.0KiB|
|bench_7826.smt2                                                                            |   0.002s |1200.0KiB|
|bench_944.smt2                                                                             |   0.002s |1188.0KiB|
|bin_libsmbclient_vc1225748.smt2                                                            |   0.002s |1120.0KiB|
|smulov4bw1024.smt2                                                                         |   0.002s |1116.0KiB|
|bench_746.smt2                                                                             |   0.002s |1112.0KiB|
|bench_2995.smt2                                                                            |   0.002s |1100.0KiB|
|bench_4313.smt2                                                                            |   0.001s |1100.0KiB|
|bench_3352.smt2                                                                            |   0.003s |1096.0KiB|
|bench_2639.smt2                                                                            |   0.003s |1096.0KiB|
|bench_7828.smt2                                                                            |   0.002s |1096.0KiB|
|bench_3888.smt2                                                                            |   0.002s |1096.0KiB|
|bench_12422.smt2                                                                           |   0.002s |1096.0KiB|
|bench_3431.smt2                                                                            |   0.002s |1096.0KiB|
|a623test0035.smt2                                                                          |   0.002s |1096.0KiB|
|bench_5084.smt2                                                                            |   0.002s |1096.0KiB|
|bench_9337.smt2                                                                            |   0.002s |1096.0KiB|
|bench_3114.smt2                                                                            |   0.002s |1096.0KiB|
|bench_2659.smt2                                                                            |   0.002s |1096.0KiB|
|bin_libmsrpc_vc1228514.smt2                                                                |   0.002s |1096.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bin_libsmbsharemodes_vc4297.smt2                                                           |   0.001s |1260.0KiB|
|bench_7826.smt2                                                                            |   0.002s |1200.0KiB|
|bench_944.smt2                                                                             |   0.002s |1188.0KiB|
|bin_libsmbclient_vc1225748.smt2                                                            |   0.002s |1120.0KiB|
|smulov4bw1024.smt2                                                                         |   0.002s |1116.0KiB|
|bench_746.smt2                                                                             |   0.002s |1112.0KiB|
|bench_2995.smt2                                                                            |   0.002s |1100.0KiB|
|bench_4313.smt2                                                                            |   0.001s |1100.0KiB|
|bench_3352.smt2                                                                            |   0.003s |1096.0KiB|
|bench_2639.smt2                                                                            |   0.003s |1096.0KiB|
|bench_7828.smt2                                                                            |   0.002s |1096.0KiB|
|bench_3888.smt2                                                                            |   0.002s |1096.0KiB|
|bench_12422.smt2                                                                           |   0.002s |1096.0KiB|
|bench_3431.smt2                                                                            |   0.002s |1096.0KiB|
|a623test0035.smt2                                                                          |   0.002s |1096.0KiB|
|bench_5084.smt2                                                                            |   0.002s |1096.0KiB|
|bench_9337.smt2                                                                            |   0.002s |1096.0KiB|
|bench_3114.smt2                                                                            |   0.002s |1096.0KiB|
|bench_2659.smt2                                                                            |   0.002s |1096.0KiB|
|bin_libmsrpc_vc1228514.smt2                                                                |   0.002s |1096.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
