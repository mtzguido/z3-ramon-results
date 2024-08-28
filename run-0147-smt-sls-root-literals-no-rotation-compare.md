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
Z3 options: "-T:20 -v:2 -st sls.bv_allow_rotation=false tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
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
Z3 options: "-T:20 -v:2 -st sls.bv_allow_rotation=false tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
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
|bench_4894.smt2                                                                            |   0.005s |1060.0KiB|
|bench_5123.smt2                                                                            |   0.005s |1096.0KiB|
|bench_3297.smt2                                                                            |   0.005s |944.0KiB|
|bench_9946.smt2                                                                            |   0.005s |1096.0KiB|
|bench_2659.smt2                                                                            |   0.005s |1028.0KiB|
|run_03230.trace.cond_025506_0x41821d_00.smt2                                               |   0.004s |1096.0KiB|
|run_00000.trace.Alloc_zero__020079.smt2                                                    |   0.004s |1076.0KiB|
|bin_libmsrpc_vc1225318.smt2                                                                |   0.004s |1072.0KiB|
|bin_eventlogadm_vc331114.smt2                                                              |   0.004s |1096.0KiB|
|bench_1761.smt2                                                                            |   0.004s |1092.0KiB|
|98.smt2                                                                                    |   0.004s |1096.0KiB|
|bench_808.smt2                                                                             |   0.004s |848.0KiB|
|a430test0028.smt2                                                                          |   0.004s |1088.0KiB|
|mobiledevice_bit8_na6_nr3_twocond.smt2                                                     |   0.004s |1100.0KiB|
|bench_4553.smt2                                                                            |   0.004s |1096.0KiB|
|bench_5190.smt2                                                                            |   0.004s |1084.0KiB|
|bench_4253.smt2                                                                            |   0.004s |1096.0KiB|
|bin_libsmbsharemodes_vc6250.smt2                                                           |   0.004s |1092.0KiB|
|bench_2258.smt2                                                                            |   0.004s |960.0KiB|
|bench_1270.smt2                                                                            |   0.004s |1084.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_4894.smt2                                                                            |   0.005s |1060.0KiB|
|bench_5123.smt2                                                                            |   0.005s |1096.0KiB|
|bench_3297.smt2                                                                            |   0.005s |944.0KiB|
|bench_9946.smt2                                                                            |   0.005s |1096.0KiB|
|bench_2659.smt2                                                                            |   0.005s |1028.0KiB|
|run_03230.trace.cond_025506_0x41821d_00.smt2                                               |   0.004s |1096.0KiB|
|run_00000.trace.Alloc_zero__020079.smt2                                                    |   0.004s |1076.0KiB|
|bin_libmsrpc_vc1225318.smt2                                                                |   0.004s |1072.0KiB|
|bin_eventlogadm_vc331114.smt2                                                              |   0.004s |1096.0KiB|
|bench_1761.smt2                                                                            |   0.004s |1092.0KiB|
|98.smt2                                                                                    |   0.004s |1096.0KiB|
|bench_808.smt2                                                                             |   0.004s |848.0KiB|
|a430test0028.smt2                                                                          |   0.004s |1088.0KiB|
|mobiledevice_bit8_na6_nr3_twocond.smt2                                                     |   0.004s |1100.0KiB|
|bench_4553.smt2                                                                            |   0.004s |1096.0KiB|
|bench_5190.smt2                                                                            |   0.004s |1084.0KiB|
|bench_4253.smt2                                                                            |   0.004s |1096.0KiB|
|bin_libsmbsharemodes_vc6250.smt2                                                           |   0.004s |1092.0KiB|
|bench_2258.smt2                                                                            |   0.004s |960.0KiB|
|bench_1270.smt2                                                                            |   0.004s |1084.0KiB|
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
|bin_libsmbsharemodes_vc6105.smt2                                                           |   0.001s |1428.0KiB|
|bench_3489.smt2                                                                            |   0.002s |1352.0KiB|
|bench_1455.smt2                                                                            |   0.002s |1352.0KiB|
|a167test0001.smt2                                                                          |   0.001s |1352.0KiB|
|QF_BV_counter_v_cc_ref_max.smt2                                                            |   0.002s |1324.0KiB|
|bench_5440.smt2                                                                            |   0.001s |1324.0KiB|
|bench_6458.smt2                                                                            |   0.002s |1276.0KiB|
|bench_2407.smt2                                                                            |   0.002s |1256.0KiB|
|bench_1953.smt2                                                                            |   0.002s |1220.0KiB|
|bench_1756.smt2                                                                            |   0.002s |1188.0KiB|
|bench_11696.smt2                                                                           |   0.002s |1184.0KiB|
|a214test0017.smt2                                                                          |   0.002s |1160.0KiB|
|bench_2735.smt2                                                                            |   0.002s |1160.0KiB|
|bench_12204.smt2                                                                           |   0.001s |1132.0KiB|
|bench_3882.smt2                                                                            |   0.002s |1116.0KiB|
|run_00000.trace.cond_020055_0x95026e6_00.smt2                                              |   0.002s |1116.0KiB|
|bench_13790.smt2                                                                           |   0.002s |1112.0KiB|
|bench_12655.smt2                                                                           |   0.002s |1112.0KiB|
|bench_607.smt2                                                                             |   0.002s |1112.0KiB|
|bin_eventlogadm_vc352302.smt2                                                              |   0.002s |1108.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bin_libsmbsharemodes_vc6105.smt2                                                           |   0.001s |1428.0KiB|
|bench_3489.smt2                                                                            |   0.002s |1352.0KiB|
|bench_1455.smt2                                                                            |   0.002s |1352.0KiB|
|a167test0001.smt2                                                                          |   0.001s |1352.0KiB|
|QF_BV_counter_v_cc_ref_max.smt2                                                            |   0.002s |1324.0KiB|
|bench_5440.smt2                                                                            |   0.001s |1324.0KiB|
|bench_6458.smt2                                                                            |   0.002s |1276.0KiB|
|bench_2407.smt2                                                                            |   0.002s |1256.0KiB|
|bench_1953.smt2                                                                            |   0.002s |1220.0KiB|
|bench_1756.smt2                                                                            |   0.002s |1188.0KiB|
|bench_11696.smt2                                                                           |   0.002s |1184.0KiB|
|a214test0017.smt2                                                                          |   0.002s |1160.0KiB|
|bench_2735.smt2                                                                            |   0.002s |1160.0KiB|
|bench_12204.smt2                                                                           |   0.001s |1132.0KiB|
|bench_3882.smt2                                                                            |   0.002s |1116.0KiB|
|run_00000.trace.cond_020055_0x95026e6_00.smt2                                              |   0.002s |1116.0KiB|
|bench_13790.smt2                                                                           |   0.002s |1112.0KiB|
|bench_12655.smt2                                                                           |   0.002s |1112.0KiB|
|bench_607.smt2                                                                             |   0.002s |1112.0KiB|
|bin_eventlogadm_vc352302.smt2                                                              |   0.002s |1108.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
