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
Job tag: bvsls-inc
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: d278a1651df24590cd032469871202a2011c2b02
Z3 branch: sls
Z3 options: "-T:20 -v:2 -sls.euf_incremental=true st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)""
Z3 inputs: inputs/QF_UF_SAT
Z3 commit message: fix build

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: bvsls-inc
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: d278a1651df24590cd032469871202a2011c2b02
Z3 branch: sls
Z3 options: "-T:20 -v:2 -sls.euf_incremental=true st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)""
Z3 inputs: inputs/QF_UF_SAT
Z3 commit message: fix build

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
|gensys_brn1283.smt2                                                                        |   0.005s |844.0KiB|
|iso_brn1246.smt2                                                                           |   0.005s |840.0KiB|
|gensys_brn255.smt2                                                                         |   0.005s |832.0KiB|
|gensys_brn218.smt2                                                                         |   0.004s |832.0KiB|
|gensys_brn231.smt2                                                                         |   0.004s |840.0KiB|
|gensys_brn614.smt2                                                                         |   0.004s |1056.0KiB|
|iso_brn051.smt2                                                                            |   0.004s |836.0KiB|
|gensys_brn308.smt2                                                                         |   0.004s |828.0KiB|
|gensys_brn985.smt2                                                                         |   0.004s |840.0KiB|
|QF_UF_brp2.5.prop1_ab_cti_max.smt2                                                         |   0.004s |1000.0KiB|
|00251.smt2                                                                                 |   0.004s |1032.0KiB|
|gensys_brn976.smt2                                                                         |   0.004s |836.0KiB|
|gensys_brn429.smt2                                                                         |   0.004s |840.0KiB|
|00011.smt2                                                                                 |   0.003s |836.0KiB|
|gensys_brn144.smt2                                                                         |   0.003s |864.0KiB|
|iso_brn487.smt2                                                                            |   0.003s |840.0KiB|
|iso_brn734.smt2                                                                            |   0.003s |944.0KiB|
|gensys_brn756.smt2                                                                         |   0.003s |840.0KiB|
|gensys_brn551.smt2                                                                         |   0.003s |840.0KiB|
|gensys_brn692.smt2                                                                         |   0.003s |1068.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|gensys_brn1283.smt2                                                                        |   0.005s |844.0KiB|
|iso_brn1246.smt2                                                                           |   0.005s |840.0KiB|
|gensys_brn255.smt2                                                                         |   0.005s |832.0KiB|
|gensys_brn218.smt2                                                                         |   0.004s |832.0KiB|
|gensys_brn231.smt2                                                                         |   0.004s |840.0KiB|
|gensys_brn614.smt2                                                                         |   0.004s |1056.0KiB|
|iso_brn051.smt2                                                                            |   0.004s |836.0KiB|
|gensys_brn308.smt2                                                                         |   0.004s |828.0KiB|
|gensys_brn985.smt2                                                                         |   0.004s |840.0KiB|
|QF_UF_brp2.5.prop1_ab_cti_max.smt2                                                         |   0.004s |1000.0KiB|
|00251.smt2                                                                                 |   0.004s |1032.0KiB|
|gensys_brn976.smt2                                                                         |   0.004s |836.0KiB|
|gensys_brn429.smt2                                                                         |   0.004s |840.0KiB|
|00011.smt2                                                                                 |   0.003s |836.0KiB|
|gensys_brn144.smt2                                                                         |   0.003s |864.0KiB|
|iso_brn487.smt2                                                                            |   0.003s |840.0KiB|
|iso_brn734.smt2                                                                            |   0.003s |944.0KiB|
|gensys_brn756.smt2                                                                         |   0.003s |840.0KiB|
|gensys_brn551.smt2                                                                         |   0.003s |840.0KiB|
|gensys_brn692.smt2                                                                         |   0.003s |1068.0KiB|
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
|gensys_brn1216.smt2                                                                        |   0.001s |1328.0KiB|
|gensys_brn887.smt2                                                                         |   0.001s |1240.0KiB|
|gensys_brn650.smt2                                                                         |   0.001s |1228.0KiB|
|SEQ004_size7.smt2                                                                          |   0.002s |1220.0KiB|
|iso_brn945.smt2                                                                            |   0.001s |1188.0KiB|
|gensys_brn828.smt2                                                                         |   0.002s |1144.0KiB|
|QF_UF_bakery.6.prop1_ab_cti_max.smt2                                                       |   0.002s |1112.0KiB|
|iso_brn_repgen_sk003.smt2                                                                  |   0.002s |1096.0KiB|
|00379.smt2                                                                                 |   0.002s |1096.0KiB|
|QF_UF_brp2.3.prop1_ab_cti_max.smt2                                                         |   0.002s |1096.0KiB|
|iso_brn_repgen_sk005.smt2                                                                  |   0.002s |1096.0KiB|
|gensys_brn076.smt2                                                                         |   0.002s |1096.0KiB|
|gensys_brn791.smt2                                                                         |   0.002s |1096.0KiB|
|iso_brn1269.smt2                                                                           |   0.001s |1096.0KiB|
|gensys_brn363.smt2                                                                         |   0.001s |1096.0KiB|
|QF_UF_bug-1_ab_reg_max.smt2                                                                |   0.001s |1096.0KiB|
|gensys_brn1201.smt2                                                                        |   0.001s |1096.0KiB|
|gensys_brn426.smt2                                                                         |   0.001s |1096.0KiB|
|gensys_brn1155.smt2                                                                        |   0.001s |1096.0KiB|
|QF_UF_at.1.prop1_ab_reg_max.smt2                                                           |   0.001s |1096.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|gensys_brn1216.smt2                                                                        |   0.001s |1328.0KiB|
|gensys_brn887.smt2                                                                         |   0.001s |1240.0KiB|
|gensys_brn650.smt2                                                                         |   0.001s |1228.0KiB|
|SEQ004_size7.smt2                                                                          |   0.002s |1220.0KiB|
|iso_brn945.smt2                                                                            |   0.001s |1188.0KiB|
|gensys_brn828.smt2                                                                         |   0.002s |1144.0KiB|
|QF_UF_bakery.6.prop1_ab_cti_max.smt2                                                       |   0.002s |1112.0KiB|
|iso_brn_repgen_sk003.smt2                                                                  |   0.002s |1096.0KiB|
|00379.smt2                                                                                 |   0.002s |1096.0KiB|
|QF_UF_brp2.3.prop1_ab_cti_max.smt2                                                         |   0.002s |1096.0KiB|
|iso_brn_repgen_sk005.smt2                                                                  |   0.002s |1096.0KiB|
|gensys_brn076.smt2                                                                         |   0.002s |1096.0KiB|
|gensys_brn791.smt2                                                                         |   0.002s |1096.0KiB|
|iso_brn1269.smt2                                                                           |   0.001s |1096.0KiB|
|gensys_brn363.smt2                                                                         |   0.001s |1096.0KiB|
|QF_UF_bug-1_ab_reg_max.smt2                                                                |   0.001s |1096.0KiB|
|gensys_brn1201.smt2                                                                        |   0.001s |1096.0KiB|
|gensys_brn426.smt2                                                                         |   0.001s |1096.0KiB|
|gensys_brn1155.smt2                                                                        |   0.001s |1096.0KiB|
|QF_UF_at.1.prop1_ab_reg_max.smt2                                                           |   0.001s |1096.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
