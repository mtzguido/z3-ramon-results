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
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 49703f8bba0e73fbd2aa6b180f8afdaeadd4d7a4
Z3 branch: 
Z3 options: "-T:30 -f z3_inputs=inputs/QF_NIA_small -f job_tag=smt-baseline -f z3_prepo=Z3Prover/z3 -f z3_ref=master"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: remove debug out

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 49703f8bba0e73fbd2aa6b180f8afdaeadd4d7a4
Z3 branch: 
Z3 options: "-T:30 -f z3_inputs=inputs/QF_NIA_small -f job_tag=smt-baseline -f z3_prepo=Z3Prover/z3 -f z3_ref=master"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: remove debug out

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
|bench_2308.smt2                                                                            |   0.067s |1564.0KiB|
|bench_14595.smt2                                                                           |   0.059s |1564.0KiB|
|bench_8110.smt2                                                                            |   0.054s |1564.0KiB|
|bench_335.smt2                                                                             |   0.052s |1560.0KiB|
|bench_248.smt2                                                                             |   0.050s |1560.0KiB|
|bench_16862.smt2                                                                           |   0.050s |1436.0KiB|
|bench_3885.smt2                                                                            |   0.049s |1536.0KiB|
|bench_2867.smt2                                                                            |   0.049s |1788.0KiB|
|bench_3239.smt2                                                                            |   0.049s |1776.0KiB|
|bench_7242.smt2                                                                            |   0.049s |1532.0KiB|
|bench_3094.smt2                                                                            |   0.048s |1764.0KiB|
|bench_2070.smt2                                                                            |   0.048s |1560.0KiB|
|bench_3890.smt2                                                                            |   0.048s |1780.0KiB|
|bench_7329.smt2                                                                            |   0.048s |1576.0KiB|
|bench_2642.smt2                                                                            |   0.048s |1564.0KiB|
|bench_630.smt2                                                                             |   0.046s |1560.0KiB|
|bench_7749.smt2                                                                            |   0.045s |1780.0KiB|
|bench_16594.smt2                                                                           |   0.045s |1784.0KiB|
|bench_3358.smt2                                                                            |   0.043s |1560.0KiB|
|bench_7454.smt2                                                                            |   0.042s |1560.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_2308.smt2                                                                            |   0.067s |1564.0KiB|
|bench_14595.smt2                                                                           |   0.059s |1564.0KiB|
|bench_8110.smt2                                                                            |   0.054s |1564.0KiB|
|bench_335.smt2                                                                             |   0.052s |1560.0KiB|
|bench_248.smt2                                                                             |   0.050s |1560.0KiB|
|bench_16862.smt2                                                                           |   0.050s |1436.0KiB|
|bench_3885.smt2                                                                            |   0.049s |1536.0KiB|
|bench_2867.smt2                                                                            |   0.049s |1788.0KiB|
|bench_3239.smt2                                                                            |   0.049s |1776.0KiB|
|bench_7242.smt2                                                                            |   0.049s |1532.0KiB|
|bench_3094.smt2                                                                            |   0.048s |1764.0KiB|
|bench_2070.smt2                                                                            |   0.048s |1560.0KiB|
|bench_3890.smt2                                                                            |   0.048s |1780.0KiB|
|bench_7329.smt2                                                                            |   0.048s |1576.0KiB|
|bench_2642.smt2                                                                            |   0.048s |1564.0KiB|
|bench_630.smt2                                                                             |   0.046s |1560.0KiB|
|bench_7749.smt2                                                                            |   0.045s |1780.0KiB|
|bench_16594.smt2                                                                           |   0.045s |1784.0KiB|
|bench_3358.smt2                                                                            |   0.043s |1560.0KiB|
|bench_7454.smt2                                                                            |   0.042s |1560.0KiB|
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
|bench_4010.smt2                                                                            |   0.006s |1828.0KiB|
|bench_5188.smt2                                                                            |   0.015s |1812.0KiB|
|bench_3421.smt2                                                                            |   0.030s |1804.0KiB|
|bench_720.smt2                                                                             |   0.039s |1792.0KiB|
|bench_1405.smt2                                                                            |   0.033s |1792.0KiB|
|bin_libsmbsharemodes_vc7225.smt2                                                           |   0.032s |1792.0KiB|
|bv-term-small-rw_47.smt2                                                                   |   0.026s |1792.0KiB|
|bench_91.smt2                                                                              |   0.024s |1792.0KiB|
|bench_3964.smt2                                                                            |   0.021s |1792.0KiB|
|bench_4957.smt2                                                                            |   0.017s |1792.0KiB|
|a60test0004.smt2                                                                           |   0.015s |1792.0KiB|
|bin_libsmbclient_vc1225779.smt2                                                            |   0.014s |1792.0KiB|
|bench_5326.smt2                                                                            |   0.014s |1792.0KiB|
|bench_2867.smt2                                                                            |   0.049s |1788.0KiB|
|bench_4894.smt2                                                                            |   0.039s |1788.0KiB|
|bench_12422.smt2                                                                           |   0.036s |1788.0KiB|
|src_wget_vc17913.smt2                                                                      |   0.036s |1788.0KiB|
|bin_libsmbsharemodes_vc6271.smt2                                                           |   0.034s |1788.0KiB|
|bench_208.smt2                                                                             |   0.034s |1788.0KiB|
|bench_2050.smt2                                                                            |   0.033s |1788.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_4010.smt2                                                                            |   0.006s |1828.0KiB|
|bench_5188.smt2                                                                            |   0.015s |1812.0KiB|
|bench_3421.smt2                                                                            |   0.030s |1804.0KiB|
|bench_720.smt2                                                                             |   0.039s |1792.0KiB|
|bench_1405.smt2                                                                            |   0.033s |1792.0KiB|
|bin_libsmbsharemodes_vc7225.smt2                                                           |   0.032s |1792.0KiB|
|bv-term-small-rw_47.smt2                                                                   |   0.026s |1792.0KiB|
|bench_91.smt2                                                                              |   0.024s |1792.0KiB|
|bench_3964.smt2                                                                            |   0.021s |1792.0KiB|
|bench_4957.smt2                                                                            |   0.017s |1792.0KiB|
|a60test0004.smt2                                                                           |   0.015s |1792.0KiB|
|bin_libsmbclient_vc1225779.smt2                                                            |   0.014s |1792.0KiB|
|bench_5326.smt2                                                                            |   0.014s |1792.0KiB|
|bench_2867.smt2                                                                            |   0.049s |1788.0KiB|
|bench_4894.smt2                                                                            |   0.039s |1788.0KiB|
|bench_12422.smt2                                                                           |   0.036s |1788.0KiB|
|src_wget_vc17913.smt2                                                                      |   0.036s |1788.0KiB|
|bin_libsmbsharemodes_vc6271.smt2                                                           |   0.034s |1788.0KiB|
|bench_208.smt2                                                                             |   0.034s |1788.0KiB|
|bench_2050.smt2                                                                            |   0.033s |1788.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
