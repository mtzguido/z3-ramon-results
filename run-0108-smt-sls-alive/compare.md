Comparing data and data


# SUMMARY
- LHS tests = 12951
- RHS tests = 12951
- LHS success = 0  (0.0%)
- RHS success = 0  (0.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-alive
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 85d3041a808b64c9d8491cd1084bdd0431618ece
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt-sls)" model_validate=true"
Z3 inputs: inputs/alive-arm-tv-smt-benchmarks
Z3 commit message: avoid platform non-reproducibility due to argument evaluation ordering

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-alive
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 85d3041a808b64c9d8491cd1084bdd0431618ece
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt-sls)" model_validate=true"
Z3 inputs: inputs/alive-arm-tv-smt-benchmarks
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
|33gjFZbaDUwg.smt2                                                                          |   0.016s |18.104MiB|
|XMyUwG9eoRJ2.smt2                                                                          |   0.015s |18.028MiB|
|GLysNc1bVPfT.smt2                                                                          |   0.015s |17.988MiB|
|AihKVWf44teQ.smt2                                                                          |   0.015s |18.056MiB|
|XLNprx59zSKn.smt2                                                                          |   0.015s |17.988MiB|
|GNjtIBwrSfVx.smt2                                                                          |   0.015s |18.148MiB|
|AiegbRD6n0gC.smt2                                                                          |   0.015s |17.996MiB|
|wLr8VYbZPpiW.smt2                                                                          |   0.015s |18.08MiB|
|ck9YUcwlwIPJ.smt2                                                                          |   0.015s |17.944MiB|
|4Dyx7L8CTvRd.smt2                                                                          |   0.015s |18.18MiB|
|GMfsOTI2Bzmm.smt2                                                                          |   0.015s |18.18MiB|
|GP3qsd6uhf6W.smt2                                                                          |   0.015s |18.152MiB|
|93x4uK1y66N2.smt2                                                                          |   0.015s |17.996MiB|
|4EbmHrH4xIxw.smt2                                                                          |   0.015s |18.0MiB|
|hQzdTZkZqBPW.smt2                                                                          |   0.015s |17.992MiB|
|D8IOmYK261Gs.smt2                                                                          |   0.015s |18.152MiB|
|04yIptroA1HN.smt2                                                                          |   0.015s |18.024MiB|
|13WAwcX69QQi.smt2                                                                          |   0.015s |18.132MiB|
|71cFoj7Eg7fm.smt2                                                                          |   0.015s |17.988MiB|
|BWkxcp4lzeFK.smt2                                                                          |   0.015s |18.016MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|33gjFZbaDUwg.smt2                                                                          |   0.016s |18.104MiB|
|XMyUwG9eoRJ2.smt2                                                                          |   0.015s |18.028MiB|
|GLysNc1bVPfT.smt2                                                                          |   0.015s |17.988MiB|
|AihKVWf44teQ.smt2                                                                          |   0.015s |18.056MiB|
|XLNprx59zSKn.smt2                                                                          |   0.015s |17.988MiB|
|GNjtIBwrSfVx.smt2                                                                          |   0.015s |18.148MiB|
|AiegbRD6n0gC.smt2                                                                          |   0.015s |17.996MiB|
|wLr8VYbZPpiW.smt2                                                                          |   0.015s |18.08MiB|
|ck9YUcwlwIPJ.smt2                                                                          |   0.015s |17.944MiB|
|4Dyx7L8CTvRd.smt2                                                                          |   0.015s |18.18MiB|
|GMfsOTI2Bzmm.smt2                                                                          |   0.015s |18.18MiB|
|GP3qsd6uhf6W.smt2                                                                          |   0.015s |18.152MiB|
|93x4uK1y66N2.smt2                                                                          |   0.015s |17.996MiB|
|4EbmHrH4xIxw.smt2                                                                          |   0.015s |18.0MiB|
|hQzdTZkZqBPW.smt2                                                                          |   0.015s |17.992MiB|
|D8IOmYK261Gs.smt2                                                                          |   0.015s |18.152MiB|
|04yIptroA1HN.smt2                                                                          |   0.015s |18.024MiB|
|13WAwcX69QQi.smt2                                                                          |   0.015s |18.132MiB|
|71cFoj7Eg7fm.smt2                                                                          |   0.015s |17.988MiB|
|BWkxcp4lzeFK.smt2                                                                          |   0.015s |18.016MiB|
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
|jYf5cejk1QcB.smt2                                                                          |   0.007s |19.044MiB|
|Wa7kU7F0sPOU.smt2                                                                          |   0.005s |18.984MiB|
|tDFiKAkfoXnX.smt2                                                                          |   0.004s |18.984MiB|
|wCYBtu7WqcaX.smt2                                                                          |   0.007s |18.96MiB|
|y1U62FqEmcAQ.smt2                                                                          |   0.007s |18.908MiB|
|Wbj0jSWs2er3.smt2                                                                          |   0.007s |18.88MiB|
|UMEz6lzjoFVA.smt2                                                                          |   0.005s |18.856MiB|
|QVV8OsQy1SCe.smt2                                                                          |   0.005s |18.844MiB|
|Y6sLYdQFAV4u.smt2                                                                          |   0.005s |18.828MiB|
|p1ZWBzJN47Wv.smt2                                                                          |   0.004s |18.828MiB|
|wEdxYs1kjLUS.smt2                                                                          |   0.005s |18.804MiB|
|NyVpfN1yjJaY.smt2                                                                          |   0.007s |18.776MiB|
|vDwXanFgrDJ8.smt2                                                                          |   0.005s |18.772MiB|
|EyF4jcy6dMJY.smt2                                                                          |   0.008s |18.768MiB|
|Hcvycmed8TV7.smt2                                                                          |   0.005s |18.768MiB|
|QbCd3VJcBPd9.smt2                                                                          |   0.005s |18.76MiB|
|ngd4RCXdNCcR.smt2                                                                          |   0.004s |18.76MiB|
|Ex7F49PzQ7QX.smt2                                                                          |   0.009s |18.752MiB|
|14mUbVobTEcW.smt2                                                                          |   0.006s |18.752MiB|
|0L43LLTi1JtL.smt2                                                                          |   0.008s |18.74MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|jYf5cejk1QcB.smt2                                                                          |   0.007s |19.044MiB|
|Wa7kU7F0sPOU.smt2                                                                          |   0.005s |18.984MiB|
|tDFiKAkfoXnX.smt2                                                                          |   0.004s |18.984MiB|
|wCYBtu7WqcaX.smt2                                                                          |   0.007s |18.96MiB|
|y1U62FqEmcAQ.smt2                                                                          |   0.007s |18.908MiB|
|Wbj0jSWs2er3.smt2                                                                          |   0.007s |18.88MiB|
|UMEz6lzjoFVA.smt2                                                                          |   0.005s |18.856MiB|
|QVV8OsQy1SCe.smt2                                                                          |   0.005s |18.844MiB|
|Y6sLYdQFAV4u.smt2                                                                          |   0.005s |18.828MiB|
|p1ZWBzJN47Wv.smt2                                                                          |   0.004s |18.828MiB|
|wEdxYs1kjLUS.smt2                                                                          |   0.005s |18.804MiB|
|NyVpfN1yjJaY.smt2                                                                          |   0.007s |18.776MiB|
|vDwXanFgrDJ8.smt2                                                                          |   0.005s |18.772MiB|
|EyF4jcy6dMJY.smt2                                                                          |   0.008s |18.768MiB|
|Hcvycmed8TV7.smt2                                                                          |   0.005s |18.768MiB|
|QbCd3VJcBPd9.smt2                                                                          |   0.005s |18.76MiB|
|ngd4RCXdNCcR.smt2                                                                          |   0.004s |18.76MiB|
|Ex7F49PzQ7QX.smt2                                                                          |   0.009s |18.752MiB|
|14mUbVobTEcW.smt2                                                                          |   0.006s |18.752MiB|
|0L43LLTi1JtL.smt2                                                                          |   0.008s |18.74MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
