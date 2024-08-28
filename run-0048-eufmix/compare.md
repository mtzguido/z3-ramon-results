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
Z3 commit: ef20237edd57061e8bac94f0fd895b96fc1d259b
Z3 branch: sls
Z3 options: "-T:20 -v:2 sls.euf_incremental=2-st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_UF_SAT
Z3 commit message: fixes

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: eufmix
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: ef20237edd57061e8bac94f0fd895b96fc1d259b
Z3 branch: sls
Z3 options: "-T:20 -v:2 sls.euf_incremental=2-st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_UF_SAT
Z3 commit message: fixes

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
|iso_brn1013.smt2                                                                           |   0.004s |1096.0KiB|
|gensys_brn924.smt2                                                                         |   0.004s |1072.0KiB|
|iso_brn084.smt2                                                                            |   0.004s |844.0KiB|
|QF_UF_train-gate.4.prop1_ab_cti_max.smt2                                                   |   0.004s |840.0KiB|
|iso_brn051.smt2                                                                            |   0.004s |1092.0KiB|
|QF_UF_adding.6.prop1_ab_reg_max.smt2                                                       |   0.004s |840.0KiB|
|gensys_brn401.smt2                                                                         |   0.004s |1088.0KiB|
|QF_UF_cache_coherence_two_ab_cti_max.smt2                                                  |   0.004s |832.0KiB|
|gensys_brn390.smt2                                                                         |   0.004s |840.0KiB|
|QF_UF_needham.1.prop1_ab_cti_max.smt2                                                      |   0.004s |1056.0KiB|
|iso_brn1154.smt2                                                                           |   0.004s |964.0KiB|
|gensys_brn237.smt2                                                                         |   0.004s |840.0KiB|
|iso_brn243.smt2                                                                            |   0.004s |836.0KiB|
|gensys_brn345.smt2                                                                         |   0.004s |952.0KiB|
|QF_UF_brp2.5.prop1_ab_cti_max.smt2                                                         |   0.004s |1096.0KiB|
|iso_brn574.smt2                                                                            |   0.004s |844.0KiB|
|gensys_brn987.smt2                                                                         |   0.004s |1096.0KiB|
|QF_UF_at.6.prop1_ab_reg_max.smt2                                                           |   0.004s |1096.0KiB|
|gensys_brn571.smt2                                                                         |   0.004s |1092.0KiB|
|gensys_brn139.smt2                                                                         |   0.004s |848.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|iso_brn1013.smt2                                                                           |   0.004s |1096.0KiB|
|gensys_brn924.smt2                                                                         |   0.004s |1072.0KiB|
|iso_brn084.smt2                                                                            |   0.004s |844.0KiB|
|QF_UF_train-gate.4.prop1_ab_cti_max.smt2                                                   |   0.004s |840.0KiB|
|iso_brn051.smt2                                                                            |   0.004s |1092.0KiB|
|QF_UF_adding.6.prop1_ab_reg_max.smt2                                                       |   0.004s |840.0KiB|
|gensys_brn401.smt2                                                                         |   0.004s |1088.0KiB|
|QF_UF_cache_coherence_two_ab_cti_max.smt2                                                  |   0.004s |832.0KiB|
|gensys_brn390.smt2                                                                         |   0.004s |840.0KiB|
|QF_UF_needham.1.prop1_ab_cti_max.smt2                                                      |   0.004s |1056.0KiB|
|iso_brn1154.smt2                                                                           |   0.004s |964.0KiB|
|gensys_brn237.smt2                                                                         |   0.004s |840.0KiB|
|iso_brn243.smt2                                                                            |   0.004s |836.0KiB|
|gensys_brn345.smt2                                                                         |   0.004s |952.0KiB|
|QF_UF_brp2.5.prop1_ab_cti_max.smt2                                                         |   0.004s |1096.0KiB|
|iso_brn574.smt2                                                                            |   0.004s |844.0KiB|
|gensys_brn987.smt2                                                                         |   0.004s |1096.0KiB|
|QF_UF_at.6.prop1_ab_reg_max.smt2                                                           |   0.004s |1096.0KiB|
|gensys_brn571.smt2                                                                         |   0.004s |1092.0KiB|
|gensys_brn139.smt2                                                                         |   0.004s |848.0KiB|
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
|gensys_brn741.smt2                                                                         |   0.002s |1584.0KiB|
|gensys_brn1128.smt2                                                                        |   0.002s |1352.0KiB|
|gensys_brn881.smt2                                                                         |   0.003s |1316.0KiB|
|gensys_brn1067.smt2                                                                        |   0.002s |1304.0KiB|
|00002.smt2                                                                                 |   0.002s |1236.0KiB|
|gensys_brn920.smt2                                                                         |   0.002s |1116.0KiB|
|iso_brn592.smt2                                                                            |   0.002s |1112.0KiB|
|iso_brn327.smt2                                                                            |   0.002s |1112.0KiB|
|gensys_brn1314.smt2                                                                        |   0.002s |1112.0KiB|
|QF_UF_lann.1.prop1_ab_cti_max.smt2                                                         |   0.001s |1108.0KiB|
|gensys_brn1282.smt2                                                                        |   0.002s |1104.0KiB|
|QF_UF_hanoi.2.prop1_ab_reg_max.smt2                                                        |   0.002s |1104.0KiB|
|gensys_brn708.smt2                                                                         |   0.002s |1104.0KiB|
|gensys_brn468.smt2                                                                         |   0.002s |1104.0KiB|
|gensys_brn1156.smt2                                                                        |   0.003s |1100.0KiB|
|gensys_brn179.smt2                                                                         |   0.003s |1100.0KiB|
|iso_brn_repgen_sk036.smt2                                                                  |   0.003s |1100.0KiB|
|gensys_brn760.smt2                                                                         |   0.003s |1100.0KiB|
|gensys_brn529.smt2                                                                         |   0.003s |1100.0KiB|
|iso_brn815.smt2                                                                            |   0.002s |1100.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|gensys_brn741.smt2                                                                         |   0.002s |1584.0KiB|
|gensys_brn1128.smt2                                                                        |   0.002s |1352.0KiB|
|gensys_brn881.smt2                                                                         |   0.003s |1316.0KiB|
|gensys_brn1067.smt2                                                                        |   0.002s |1304.0KiB|
|00002.smt2                                                                                 |   0.002s |1236.0KiB|
|gensys_brn920.smt2                                                                         |   0.002s |1116.0KiB|
|iso_brn592.smt2                                                                            |   0.002s |1112.0KiB|
|iso_brn327.smt2                                                                            |   0.002s |1112.0KiB|
|gensys_brn1314.smt2                                                                        |   0.002s |1112.0KiB|
|QF_UF_lann.1.prop1_ab_cti_max.smt2                                                         |   0.001s |1108.0KiB|
|gensys_brn1282.smt2                                                                        |   0.002s |1104.0KiB|
|QF_UF_hanoi.2.prop1_ab_reg_max.smt2                                                        |   0.002s |1104.0KiB|
|gensys_brn708.smt2                                                                         |   0.002s |1104.0KiB|
|gensys_brn468.smt2                                                                         |   0.002s |1104.0KiB|
|gensys_brn1156.smt2                                                                        |   0.003s |1100.0KiB|
|gensys_brn179.smt2                                                                         |   0.003s |1100.0KiB|
|iso_brn_repgen_sk036.smt2                                                                  |   0.003s |1100.0KiB|
|gensys_brn760.smt2                                                                         |   0.003s |1100.0KiB|
|gensys_brn529.smt2                                                                         |   0.003s |1100.0KiB|
|iso_brn815.smt2                                                                            |   0.002s |1100.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
