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
Job tag: smt-sls-root-literals-no-rotation
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: bed085934f4d0f5980191cecf17bb70639c6a878
Z3 branch: master
Z3 options: "-T:20 -v:2 -sls.bv_allow_rotation=false st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: bugfixes to bv-sls

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-root-literals-no-rotation
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: bed085934f4d0f5980191cecf17bb70639c6a878
Z3 branch: master
Z3 options: "-T:20 -v:2 -sls.bv_allow_rotation=false st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
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
|bench_1549.smt2                                                                            |   0.006s |840.0KiB|
|bench_3485.smt2                                                                            |   0.005s |840.0KiB|
|bench_7219.smt2                                                                            |   0.004s |836.0KiB|
|bench_313.smt2                                                                             |   0.004s |840.0KiB|
|bench_3297.smt2                                                                            |   0.004s |1096.0KiB|
|bench_14598.smt2                                                                           |   0.004s |840.0KiB|
|bench_1498.smt2                                                                            |   0.004s |936.0KiB|
|bench_9946.smt2                                                                            |   0.004s |840.0KiB|
|bench_789.smt2                                                                             |   0.004s |1012.0KiB|
|bench_3181.smt2                                                                            |   0.004s |840.0KiB|
|bench_914.smt2                                                                             |   0.004s |840.0KiB|
|bench_5499.smt2                                                                            |   0.004s |1072.0KiB|
|bench_2974.smt2                                                                            |   0.004s |1072.0KiB|
|bench_8283.smt2                                                                            |   0.004s |1016.0KiB|
|bin_libsmbsharemodes_vc6270.smt2                                                           |   0.004s |1060.0KiB|
|bench_3031.smt2                                                                            |   0.003s |840.0KiB|
|nnrpd_nnrpd_vc21428.smt2                                                                   |   0.003s |1056.0KiB|
|bench_1013.smt2                                                                            |   0.003s |884.0KiB|
|bench_8379.smt2                                                                            |   0.003s |1052.0KiB|
|bench_1349.smt2                                                                            |   0.003s |1092.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_1549.smt2                                                                            |   0.006s |840.0KiB|
|bench_3485.smt2                                                                            |   0.005s |840.0KiB|
|bench_7219.smt2                                                                            |   0.004s |836.0KiB|
|bench_313.smt2                                                                             |   0.004s |840.0KiB|
|bench_3297.smt2                                                                            |   0.004s |1096.0KiB|
|bench_14598.smt2                                                                           |   0.004s |840.0KiB|
|bench_1498.smt2                                                                            |   0.004s |936.0KiB|
|bench_9946.smt2                                                                            |   0.004s |840.0KiB|
|bench_789.smt2                                                                             |   0.004s |1012.0KiB|
|bench_3181.smt2                                                                            |   0.004s |840.0KiB|
|bench_914.smt2                                                                             |   0.004s |840.0KiB|
|bench_5499.smt2                                                                            |   0.004s |1072.0KiB|
|bench_2974.smt2                                                                            |   0.004s |1072.0KiB|
|bench_8283.smt2                                                                            |   0.004s |1016.0KiB|
|bin_libsmbsharemodes_vc6270.smt2                                                           |   0.004s |1060.0KiB|
|bench_3031.smt2                                                                            |   0.003s |840.0KiB|
|nnrpd_nnrpd_vc21428.smt2                                                                   |   0.003s |1056.0KiB|
|bench_1013.smt2                                                                            |   0.003s |884.0KiB|
|bench_8379.smt2                                                                            |   0.003s |1052.0KiB|
|bench_1349.smt2                                                                            |   0.003s |1092.0KiB|
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
|bench_1355.smt2                                                                            |   0.001s |1352.0KiB|
|bench_2122.smt2                                                                            |   0.001s |1236.0KiB|
|90.smt2                                                                                    |   0.002s |1188.0KiB|
|bin_libsmbsharemodes_vc5711.smt2                                                           |   0.001s |1136.0KiB|
|QF_BV_counter_v_cc_ref_max.smt2                                                            |   0.002s |1100.0KiB|
|bench_1252.smt2                                                                            |   0.002s |1100.0KiB|
|bin_libmsrpc_vc1225405.smt2                                                                |   0.002s |1100.0KiB|
|bench_3297.smt2                                                                            |   0.004s |1096.0KiB|
|bench_8245.smt2                                                                            |   0.003s |1096.0KiB|
|bench_17759.smt2                                                                           |   0.002s |1096.0KiB|
|bin_libsmbsharemodes_vc7116.smt2                                                           |   0.002s |1096.0KiB|
|bin_libsmbclient_vc1225164.smt2                                                            |   0.002s |1096.0KiB|
|mobiledevice_bit8_na6_nr3_twocond.smt2                                                     |   0.002s |1096.0KiB|
|bench_1770.smt2                                                                            |   0.002s |1096.0KiB|
|bench_5944.smt2                                                                            |   0.002s |1096.0KiB|
|bin_libsmbclient_vc1225835.smt2                                                            |   0.002s |1096.0KiB|
|bin_libsmbclient_vc1228531.smt2                                                            |   0.002s |1096.0KiB|
|bench_7642.smt2                                                                            |   0.002s |1096.0KiB|
|bench_456.smt2                                                                             |   0.002s |1096.0KiB|
|bench_6953.smt2                                                                            |   0.002s |1096.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_1355.smt2                                                                            |   0.001s |1352.0KiB|
|bench_2122.smt2                                                                            |   0.001s |1236.0KiB|
|90.smt2                                                                                    |   0.002s |1188.0KiB|
|bin_libsmbsharemodes_vc5711.smt2                                                           |   0.001s |1136.0KiB|
|QF_BV_counter_v_cc_ref_max.smt2                                                            |   0.002s |1100.0KiB|
|bench_1252.smt2                                                                            |   0.002s |1100.0KiB|
|bin_libmsrpc_vc1225405.smt2                                                                |   0.002s |1100.0KiB|
|bench_3297.smt2                                                                            |   0.004s |1096.0KiB|
|bench_8245.smt2                                                                            |   0.003s |1096.0KiB|
|bench_17759.smt2                                                                           |   0.002s |1096.0KiB|
|bin_libsmbsharemodes_vc7116.smt2                                                           |   0.002s |1096.0KiB|
|bin_libsmbclient_vc1225164.smt2                                                            |   0.002s |1096.0KiB|
|mobiledevice_bit8_na6_nr3_twocond.smt2                                                     |   0.002s |1096.0KiB|
|bench_1770.smt2                                                                            |   0.002s |1096.0KiB|
|bench_5944.smt2                                                                            |   0.002s |1096.0KiB|
|bin_libsmbclient_vc1225835.smt2                                                            |   0.002s |1096.0KiB|
|bin_libsmbclient_vc1228531.smt2                                                            |   0.002s |1096.0KiB|
|bench_7642.smt2                                                                            |   0.002s |1096.0KiB|
|bench_456.smt2                                                                             |   0.002s |1096.0KiB|
|bench_6953.smt2                                                                            |   0.002s |1096.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
