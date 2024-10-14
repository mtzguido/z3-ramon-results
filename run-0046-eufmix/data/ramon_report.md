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
Job tag: eufmix
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 54cce7b10b3682b8984ebdc63fb7a0f20528df7c
Z3 branch: sls
Z3 options: "-T:20 -v:2 sls.euf_incremental=2-st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_UF_SAT
Z3 commit message: restore use of value_hash

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: eufmix
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 54cce7b10b3682b8984ebdc63fb7a0f20528df7c
Z3 branch: sls
Z3 options: "-T:20 -v:2 sls.euf_incremental=2-st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_UF_SAT
Z3 commit message: restore use of value_hash

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
|QF_UF_brp2.5.prop1_ab_cti_max.smt2                                                         |   0.005s |912.0KiB|
|iso_brn755.smt2                                                                            |   0.004s |1096.0KiB|
|iso_brn1071.smt2                                                                           |   0.004s |840.0KiB|
|iso_brn991.smt2                                                                            |   0.004s |896.0KiB|
|gensys_brn449.smt2                                                                         |   0.004s |1020.0KiB|
|iso_brn037.smt2                                                                            |   0.004s |1096.0KiB|
|iso_brn_repgen041.smt2                                                                     |   0.004s |1096.0KiB|
|iso_brn1136.smt2                                                                           |   0.004s |1096.0KiB|
|gensys_brn1046.smt2                                                                        |   0.004s |1100.0KiB|
|QF_UF_counter_v_ab_cti_max.smt2                                                            |   0.004s |924.0KiB|
|QF_UF_gear.2.prop1_ab_reg_max.smt2                                                         |   0.004s |840.0KiB|
|iso_brn1246.smt2                                                                           |   0.004s |1096.0KiB|
|iso_brn1252.smt2                                                                           |   0.004s |892.0KiB|
|iso_brn597.smt2                                                                            |   0.004s |840.0KiB|
|QF_UF_bakery.8.prop1_ab_cti_max.smt2                                                       |   0.004s |1096.0KiB|
|QF_UF_miim_ab_reg_max.smt2                                                                 |   0.004s |1064.0KiB|
|iso_brn760.smt2                                                                            |   0.004s |988.0KiB|
|QF_UF_mpeg_ab_reg_max.smt2                                                                 |   0.004s |840.0KiB|
|gensys_brn968.smt2                                                                         |   0.004s |1064.0KiB|
|gensys_brn1145.smt2                                                                        |   0.004s |1048.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_UF_brp2.5.prop1_ab_cti_max.smt2                                                         |   0.005s |912.0KiB|
|iso_brn755.smt2                                                                            |   0.004s |1096.0KiB|
|iso_brn1071.smt2                                                                           |   0.004s |840.0KiB|
|iso_brn991.smt2                                                                            |   0.004s |896.0KiB|
|gensys_brn449.smt2                                                                         |   0.004s |1020.0KiB|
|iso_brn037.smt2                                                                            |   0.004s |1096.0KiB|
|iso_brn_repgen041.smt2                                                                     |   0.004s |1096.0KiB|
|iso_brn1136.smt2                                                                           |   0.004s |1096.0KiB|
|gensys_brn1046.smt2                                                                        |   0.004s |1100.0KiB|
|QF_UF_counter_v_ab_cti_max.smt2                                                            |   0.004s |924.0KiB|
|QF_UF_gear.2.prop1_ab_reg_max.smt2                                                         |   0.004s |840.0KiB|
|iso_brn1246.smt2                                                                           |   0.004s |1096.0KiB|
|iso_brn1252.smt2                                                                           |   0.004s |892.0KiB|
|iso_brn597.smt2                                                                            |   0.004s |840.0KiB|
|QF_UF_bakery.8.prop1_ab_cti_max.smt2                                                       |   0.004s |1096.0KiB|
|QF_UF_miim_ab_reg_max.smt2                                                                 |   0.004s |1064.0KiB|
|iso_brn760.smt2                                                                            |   0.004s |988.0KiB|
|QF_UF_mpeg_ab_reg_max.smt2                                                                 |   0.004s |840.0KiB|
|gensys_brn968.smt2                                                                         |   0.004s |1064.0KiB|
|gensys_brn1145.smt2                                                                        |   0.004s |1048.0KiB|
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
|QF_UF_bakery.7.prop1_ab_reg_max.smt2                                                       |   0.002s |1352.0KiB|
|gensys_brn419.smt2                                                                         |   0.001s |1324.0KiB|
|gensys_brn1012.smt2                                                                        |   0.002s |1312.0KiB|
|gensys_brn1218.smt2                                                                        |   0.001s |1308.0KiB|
|iso_brn914.smt2                                                                            |   0.002s |1304.0KiB|
|smt3508124013603727984.smt2                                                                |   0.002s |1276.0KiB|
|gensys_brn680.smt2                                                                         |   0.002s |1272.0KiB|
|iso_brn671.smt2                                                                            |   0.002s |1228.0KiB|
|gensys_brn445.smt2                                                                         |   0.002s |1112.0KiB|
|gensys_brn885.smt2                                                                         |   0.003s |1104.0KiB|
|QF_UF_driving_phils.3.prop1_ab_reg_max.smt2                                                |   0.003s |1104.0KiB|
|QF_UF_mcs.4.prop1_ab_reg_max.smt2                                                          |   0.002s |1104.0KiB|
|gensys_brn285.smt2                                                                         |   0.002s |1104.0KiB|
|gensys_brn294.smt2                                                                         |   0.002s |1104.0KiB|
|gensys_brn1046.smt2                                                                        |   0.004s |1100.0KiB|
|QF_UF_brp.4.prop1_ab_cti_max.smt2                                                          |   0.003s |1100.0KiB|
|QF_UF_h_TreeArb_ab_cti_max.smt2                                                            |   0.003s |1100.0KiB|
|gensys_brn840.smt2                                                                         |   0.003s |1100.0KiB|
|gensys_brn1168.smt2                                                                        |   0.003s |1100.0KiB|
|iso_brn1308.smt2                                                                           |   0.003s |1100.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_UF_bakery.7.prop1_ab_reg_max.smt2                                                       |   0.002s |1352.0KiB|
|gensys_brn419.smt2                                                                         |   0.001s |1324.0KiB|
|gensys_brn1012.smt2                                                                        |   0.002s |1312.0KiB|
|gensys_brn1218.smt2                                                                        |   0.001s |1308.0KiB|
|iso_brn914.smt2                                                                            |   0.002s |1304.0KiB|
|smt3508124013603727984.smt2                                                                |   0.002s |1276.0KiB|
|gensys_brn680.smt2                                                                         |   0.002s |1272.0KiB|
|iso_brn671.smt2                                                                            |   0.002s |1228.0KiB|
|gensys_brn445.smt2                                                                         |   0.002s |1112.0KiB|
|gensys_brn885.smt2                                                                         |   0.003s |1104.0KiB|
|QF_UF_driving_phils.3.prop1_ab_reg_max.smt2                                                |   0.003s |1104.0KiB|
|QF_UF_mcs.4.prop1_ab_reg_max.smt2                                                          |   0.002s |1104.0KiB|
|gensys_brn285.smt2                                                                         |   0.002s |1104.0KiB|
|gensys_brn294.smt2                                                                         |   0.002s |1104.0KiB|
|gensys_brn1046.smt2                                                                        |   0.004s |1100.0KiB|
|QF_UF_brp.4.prop1_ab_cti_max.smt2                                                          |   0.003s |1100.0KiB|
|QF_UF_h_TreeArb_ab_cti_max.smt2                                                            |   0.003s |1100.0KiB|
|gensys_brn840.smt2                                                                         |   0.003s |1100.0KiB|
|gensys_brn1168.smt2                                                                        |   0.003s |1100.0KiB|
|iso_brn1308.smt2                                                                           |   0.003s |1100.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
