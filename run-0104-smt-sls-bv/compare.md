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
Job tag: smt-sls-bv
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 85d3041a808b64c9d8491cd1084bdd0431618ece
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt-sls)" model_validate=true"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: avoid platform non-reproducibility due to argument evaluation ordering

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-bv
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 85d3041a808b64c9d8491cd1084bdd0431618ece
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt-sls)" model_validate=true"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: avoid platform non-reproducibility due to argument evaluation ordering

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
|div3.c.20.smt2                                                                             |   0.047s |21.736MiB|
|div.c.20.smt2                                                                              |   0.045s |21.64MiB|
|mult1.c.20.smt2                                                                            |   0.036s |20.148MiB|
|bin_libmsrpc_vc1225392.smt2                                                                |   0.033s |19.468MiB|
|bin_libmsrpc_vc1228527.smt2                                                                |   0.033s |19.464MiB|
|bin_libmsrpc_vc1228610.smt2                                                                |   0.032s |19.34MiB|
|bin_libsmbsharemodes_vc7666.smt2                                                           |   0.032s |19.624MiB|
|bin_libsmbclient_vc1225773.smt2                                                            |   0.032s |19.448MiB|
|bin_libmsrpc_vc1225408.smt2                                                                |   0.031s |19.164MiB|
|bin_libsmbclient_vc1225841.smt2                                                            |   0.031s |19.532MiB|
|bin_libsmbclient_vc1225256.smt2                                                            |   0.031s |19.34MiB|
|bin_libsmbclient_vc1228531.smt2                                                            |   0.030s |19.408MiB|
|bin_libsmbclient_vc1228452.smt2                                                            |   0.030s |19.48MiB|
|bin_libsmbclient_vc1228442.smt2                                                            |   0.030s |19.38MiB|
|bin_libsmbclient_vc1225758.smt2                                                            |   0.030s |19.6MiB|
|bin_libmsrpc_vc1228514.smt2                                                                |   0.030s |19.372MiB|
|bin_libsmbclient_vc1228491.smt2                                                            |   0.030s |19.488MiB|
|bin_libmsrpc_vc1225895.smt2                                                                |   0.030s |19.404MiB|
|bin_libsmbclient_vc1225887.smt2                                                            |   0.029s |19.468MiB|
|bin_libmsrpc_vc1225395.smt2                                                                |   0.029s |19.384MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|div3.c.20.smt2                                                                             |   0.047s |21.736MiB|
|div.c.20.smt2                                                                              |   0.045s |21.64MiB|
|mult1.c.20.smt2                                                                            |   0.036s |20.148MiB|
|bin_libmsrpc_vc1225392.smt2                                                                |   0.033s |19.468MiB|
|bin_libmsrpc_vc1228527.smt2                                                                |   0.033s |19.464MiB|
|bin_libmsrpc_vc1228610.smt2                                                                |   0.032s |19.34MiB|
|bin_libsmbsharemodes_vc7666.smt2                                                           |   0.032s |19.624MiB|
|bin_libsmbclient_vc1225773.smt2                                                            |   0.032s |19.448MiB|
|bin_libmsrpc_vc1225408.smt2                                                                |   0.031s |19.164MiB|
|bin_libsmbclient_vc1225841.smt2                                                            |   0.031s |19.532MiB|
|bin_libsmbclient_vc1225256.smt2                                                            |   0.031s |19.34MiB|
|bin_libsmbclient_vc1228531.smt2                                                            |   0.030s |19.408MiB|
|bin_libsmbclient_vc1228452.smt2                                                            |   0.030s |19.48MiB|
|bin_libsmbclient_vc1228442.smt2                                                            |   0.030s |19.38MiB|
|bin_libsmbclient_vc1225758.smt2                                                            |   0.030s |19.6MiB|
|bin_libmsrpc_vc1228514.smt2                                                                |   0.030s |19.372MiB|
|bin_libsmbclient_vc1228491.smt2                                                            |   0.030s |19.488MiB|
|bin_libmsrpc_vc1225895.smt2                                                                |   0.030s |19.404MiB|
|bin_libsmbclient_vc1225887.smt2                                                            |   0.029s |19.468MiB|
|bin_libmsrpc_vc1225395.smt2                                                                |   0.029s |19.384MiB|
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
|div3.c.20.smt2                                                                             |   0.047s |21.736MiB|
|div.c.20.smt2                                                                              |   0.045s |21.64MiB|
|test_v3_r3_vr10_c1_s24300.smt2                                                             |   0.029s |21.348MiB|
|mult1.c.20.smt2                                                                            |   0.036s |20.148MiB|
|f23.smt2                                                                                   |   0.023s |20.072MiB|
|mult2.c.10.smt2                                                                            |   0.020s |19.956MiB|
|bin_libsmbsharemodes_vc7666.smt2                                                           |   0.032s |19.624MiB|
|bin_libmsrpc_vc1225910.smt2                                                                |   0.028s |19.62MiB|
|bin_libsmbclient_vc1225758.smt2                                                            |   0.030s |19.6MiB|
|bin_libsmbsharemodes_vc7750.smt2                                                           |   0.028s |19.6MiB|
|bin_libsmbclient_vc1225841.smt2                                                            |   0.031s |19.532MiB|
|bin_libsmbclient_vc1225860.smt2                                                            |   0.029s |19.508MiB|
|bin_libsmbclient_vc1225264.smt2                                                            |   0.024s |19.504MiB|
|bin_libmsrpc_vc1225346.smt2                                                                |   0.025s |19.492MiB|
|bin_libsmbclient_vc1228491.smt2                                                            |   0.030s |19.488MiB|
|bin_libsmbclient_vc1225783.smt2                                                            |   0.028s |19.488MiB|
|bin_libsmbclient_vc1228452.smt2                                                            |   0.030s |19.48MiB|
|bin_libsmbclient_vc1225257.smt2                                                            |   0.028s |19.472MiB|
|bin_libmsrpc_vc1225392.smt2                                                                |   0.033s |19.468MiB|
|bin_libsmbclient_vc1225887.smt2                                                            |   0.029s |19.468MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|div3.c.20.smt2                                                                             |   0.047s |21.736MiB|
|div.c.20.smt2                                                                              |   0.045s |21.64MiB|
|test_v3_r3_vr10_c1_s24300.smt2                                                             |   0.029s |21.348MiB|
|mult1.c.20.smt2                                                                            |   0.036s |20.148MiB|
|f23.smt2                                                                                   |   0.023s |20.072MiB|
|mult2.c.10.smt2                                                                            |   0.020s |19.956MiB|
|bin_libsmbsharemodes_vc7666.smt2                                                           |   0.032s |19.624MiB|
|bin_libmsrpc_vc1225910.smt2                                                                |   0.028s |19.62MiB|
|bin_libsmbclient_vc1225758.smt2                                                            |   0.030s |19.6MiB|
|bin_libsmbsharemodes_vc7750.smt2                                                           |   0.028s |19.6MiB|
|bin_libsmbclient_vc1225841.smt2                                                            |   0.031s |19.532MiB|
|bin_libsmbclient_vc1225860.smt2                                                            |   0.029s |19.508MiB|
|bin_libsmbclient_vc1225264.smt2                                                            |   0.024s |19.504MiB|
|bin_libmsrpc_vc1225346.smt2                                                                |   0.025s |19.492MiB|
|bin_libsmbclient_vc1228491.smt2                                                            |   0.030s |19.488MiB|
|bin_libsmbclient_vc1225783.smt2                                                            |   0.028s |19.488MiB|
|bin_libsmbclient_vc1228452.smt2                                                            |   0.030s |19.48MiB|
|bin_libsmbclient_vc1225257.smt2                                                            |   0.028s |19.472MiB|
|bin_libmsrpc_vc1225392.smt2                                                                |   0.033s |19.468MiB|
|bin_libsmbclient_vc1225887.smt2                                                            |   0.029s |19.468MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
