Comparing data and data


# SUMMARY
- LHS tests = 2000
- RHS tests = 2000
- LHS success = 1937  (96.85%)
- RHS success = 1937  (96.85%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: eufinc
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: f136d46fb4f0eab6968572e2b11954a13a037154
Z3 branch: sls
Z3 options: "-T:20 -v:2 sls.euf_incremental=1 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_UF_SAT
Z3 commit message: bug fixes

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: eufinc
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: f136d46fb4f0eab6968572e2b11954a13a037154
Z3 branch: sls
Z3 options: "-T:20 -v:2 sls.euf_incremental=1 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_UF_SAT
Z3 commit message: bug fixes

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00002.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00011.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00019.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00060.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00081.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00152.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00002.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00011.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00019.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00060.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00081.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00152.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00002.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00011.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00019.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00060.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00081.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00152.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00002.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00011.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00019.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00060.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00081.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00152.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|gensys_brn1127.smt2                                                                        |  20.010s |19.536MiB|
|gensys_brn583.smt2                                                                         |  20.009s |19.496MiB|
|gensys_brn191.smt2                                                                         |  20.009s |19.792MiB|
|gensys_brn483.smt2                                                                         |  20.008s |19.7MiB|
|iso_brn_sk008.smt2                                                                         |  20.008s |19.88MiB|
|gensys_brn856.smt2                                                                         |  20.008s |19.788MiB|
|iso_brn417.smt2                                                                            |  20.008s |19.48MiB|
|gensys_brn783.smt2                                                                         |  20.008s |19.808MiB|
|iso_brn_repgen_sk045.smt2                                                                  |  20.008s |21.008MiB|
|gensys_brn744.smt2                                                                         |  20.007s |19.656MiB|
|gensys_brn940.smt2                                                                         |  20.007s |19.744MiB|
|gensys_brn1193.smt2                                                                        |  20.007s |19.472MiB|
|iso_brn778.smt2                                                                            |  20.007s |19.908MiB|
|iso_brn530.smt2                                                                            |  20.007s |19.68MiB|
|iso_brn920.smt2                                                                            |  20.006s |19.784MiB|
|iso_brn432.smt2                                                                            |  20.006s |19.488MiB|
|gensys_brn298.smt2                                                                         |  20.006s |19.696MiB|
|gensys_brn726.smt2                                                                         |  20.006s |19.764MiB|
|iso_brn1046.smt2                                                                           |  20.006s |20.032MiB|
|iso_brn080.smt2                                                                            |  20.006s |19.74MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|gensys_brn1127.smt2                                                                        |  20.010s |19.536MiB|
|gensys_brn583.smt2                                                                         |  20.009s |19.496MiB|
|gensys_brn191.smt2                                                                         |  20.009s |19.792MiB|
|gensys_brn483.smt2                                                                         |  20.008s |19.7MiB|
|iso_brn_sk008.smt2                                                                         |  20.008s |19.88MiB|
|gensys_brn856.smt2                                                                         |  20.008s |19.788MiB|
|iso_brn417.smt2                                                                            |  20.008s |19.48MiB|
|gensys_brn783.smt2                                                                         |  20.008s |19.808MiB|
|iso_brn_repgen_sk045.smt2                                                                  |  20.008s |21.008MiB|
|gensys_brn744.smt2                                                                         |  20.007s |19.656MiB|
|gensys_brn940.smt2                                                                         |  20.007s |19.744MiB|
|gensys_brn1193.smt2                                                                        |  20.007s |19.472MiB|
|iso_brn778.smt2                                                                            |  20.007s |19.908MiB|
|iso_brn530.smt2                                                                            |  20.007s |19.68MiB|
|iso_brn920.smt2                                                                            |  20.006s |19.784MiB|
|iso_brn432.smt2                                                                            |  20.006s |19.488MiB|
|gensys_brn298.smt2                                                                         |  20.006s |19.696MiB|
|gensys_brn726.smt2                                                                         |  20.006s |19.764MiB|
|iso_brn1046.smt2                                                                           |  20.006s |20.032MiB|
|iso_brn080.smt2                                                                            |  20.006s |19.74MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00002.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.404MiB|18.404MiB|0B| 0.0%|
|00011.smt2                                                                                  |19.016MiB|19.016MiB|0B| 0.0%|
|00019.smt2                                                                                  |19.792MiB|19.792MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00060.smt2                                                                                  |19.024MiB|19.024MiB|0B| 0.0%|
|00081.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.992MiB|18.992MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.992MiB|18.992MiB|0B| 0.0%|
|00104.smt2                                                                                  |19.016MiB|19.016MiB|0B| 0.0%|
|00105.smt2                                                                                  |18.768MiB|18.768MiB|0B| 0.0%|
|00152.smt2                                                                                  |18.256MiB|18.256MiB|0B| 0.0%|
|00194.smt2                                                                                  |18.536MiB|18.536MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.776MiB|18.776MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00002.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.404MiB|18.404MiB|0B| 0.0%|
|00011.smt2                                                                                  |19.016MiB|19.016MiB|0B| 0.0%|
|00019.smt2                                                                                  |19.792MiB|19.792MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00060.smt2                                                                                  |19.024MiB|19.024MiB|0B| 0.0%|
|00081.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.992MiB|18.992MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.992MiB|18.992MiB|0B| 0.0%|
|00104.smt2                                                                                  |19.016MiB|19.016MiB|0B| 0.0%|
|00105.smt2                                                                                  |18.768MiB|18.768MiB|0B| 0.0%|
|00152.smt2                                                                                  |18.256MiB|18.256MiB|0B| 0.0%|
|00194.smt2                                                                                  |18.536MiB|18.536MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.776MiB|18.776MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00002.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.404MiB|18.404MiB|0B| 0.0%|
|00011.smt2                                                                                  |19.016MiB|19.016MiB|0B| 0.0%|
|00019.smt2                                                                                  |19.792MiB|19.792MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00060.smt2                                                                                  |19.024MiB|19.024MiB|0B| 0.0%|
|00081.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.992MiB|18.992MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.992MiB|18.992MiB|0B| 0.0%|
|00104.smt2                                                                                  |19.016MiB|19.016MiB|0B| 0.0%|
|00105.smt2                                                                                  |18.768MiB|18.768MiB|0B| 0.0%|
|00152.smt2                                                                                  |18.256MiB|18.256MiB|0B| 0.0%|
|00194.smt2                                                                                  |18.536MiB|18.536MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.776MiB|18.776MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00002.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.404MiB|18.404MiB|0B| 0.0%|
|00011.smt2                                                                                  |19.016MiB|19.016MiB|0B| 0.0%|
|00019.smt2                                                                                  |19.792MiB|19.792MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00060.smt2                                                                                  |19.024MiB|19.024MiB|0B| 0.0%|
|00081.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.992MiB|18.992MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.992MiB|18.992MiB|0B| 0.0%|
|00104.smt2                                                                                  |19.016MiB|19.016MiB|0B| 0.0%|
|00105.smt2                                                                                  |18.768MiB|18.768MiB|0B| 0.0%|
|00152.smt2                                                                                  |18.256MiB|18.256MiB|0B| 0.0%|
|00194.smt2                                                                                  |18.536MiB|18.536MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.776MiB|18.776MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_UF_sokoban.2.prop1_ab_cti_max.smt2                                                      |  19.998s |25.184MiB|
|SEQ018_size8.smt2                                                                          |  20.001s |23.552MiB|
|QF_UF_needham.4.prop2_ab_cti_max.smt2                                                      |  20.003s |23.364MiB|
|QF_UF_sokoban.2.prop1_ab_fp_max.smt2                                                       |  20.002s |23.356MiB|
|QF_UF_lifts.1.prop1_ab_cti_max.smt2                                                        |  19.972s |23.248MiB|
|QF_UF_needham.4.prop3_ab_cti_max.smt2                                                      |  19.965s |23.232MiB|
|QF_UF_synapse.2.prop1_ab_cti_max.smt2                                                      |  19.999s |23.208MiB|
|QF_UF_needham.4.prop4_ab_cti_max.smt2                                                      |  19.954s |23.144MiB|
|QF_UF_lifts.2.prop1_ab_cti_max.smt2                                                        |  19.999s |23.104MiB|
|QF_UF_telephony.8.prop1_ab_cti_max.smt2                                                    |  20.004s |22.98MiB|
|QF_UF_leader_election.1.prop1_ab_cti_max.smt2                                              |  19.959s |22.916MiB|
|QF_UF_leader_election.2.prop1_ab_cti_max.smt2                                              |  20.001s |22.896MiB|
|QF_UF_cambridge.7.prop1_ab_cti_max.smt2                                                    |   0.597s |22.852MiB|
|00793.smt2                                                                                 |   0.039s |22.752MiB|
|QF_UF_synapse.1.prop1_ab_cti_max.smt2                                                      |  20.000s |22.704MiB|
|QF_UF_cambridge.7.prop2_ab_cti_max.smt2                                                    |   0.045s |22.704MiB|
|QF_UF_extinction.4.prop1_ab_cti_max.smt2                                                   |  19.999s |22.7MiB|
|QF_UF_at.5.prop1_ab_cti_max.smt2                                                           |  19.994s |22.696MiB|
|QF_UF_bridge.3.prop1_ab_cti_max.smt2                                                       |  20.002s |22.668MiB|
|QF_UF_telephony.5.prop1_ab_cti_max.smt2                                                    |  19.984s |22.644MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_UF_sokoban.2.prop1_ab_cti_max.smt2                                                      |  19.998s |25.184MiB|
|SEQ018_size8.smt2                                                                          |  20.001s |23.552MiB|
|QF_UF_needham.4.prop2_ab_cti_max.smt2                                                      |  20.003s |23.364MiB|
|QF_UF_sokoban.2.prop1_ab_fp_max.smt2                                                       |  20.002s |23.356MiB|
|QF_UF_lifts.1.prop1_ab_cti_max.smt2                                                        |  19.972s |23.248MiB|
|QF_UF_needham.4.prop3_ab_cti_max.smt2                                                      |  19.965s |23.232MiB|
|QF_UF_synapse.2.prop1_ab_cti_max.smt2                                                      |  19.999s |23.208MiB|
|QF_UF_needham.4.prop4_ab_cti_max.smt2                                                      |  19.954s |23.144MiB|
|QF_UF_lifts.2.prop1_ab_cti_max.smt2                                                        |  19.999s |23.104MiB|
|QF_UF_telephony.8.prop1_ab_cti_max.smt2                                                    |  20.004s |22.98MiB|
|QF_UF_leader_election.1.prop1_ab_cti_max.smt2                                              |  19.959s |22.916MiB|
|QF_UF_leader_election.2.prop1_ab_cti_max.smt2                                              |  20.001s |22.896MiB|
|QF_UF_cambridge.7.prop1_ab_cti_max.smt2                                                    |   0.597s |22.852MiB|
|00793.smt2                                                                                 |   0.039s |22.752MiB|
|QF_UF_synapse.1.prop1_ab_cti_max.smt2                                                      |  20.000s |22.704MiB|
|QF_UF_cambridge.7.prop2_ab_cti_max.smt2                                                    |   0.045s |22.704MiB|
|QF_UF_extinction.4.prop1_ab_cti_max.smt2                                                   |  19.999s |22.7MiB|
|QF_UF_at.5.prop1_ab_cti_max.smt2                                                           |  19.994s |22.696MiB|
|QF_UF_bridge.3.prop1_ab_cti_max.smt2                                                       |  20.002s |22.668MiB|
|QF_UF_telephony.5.prop1_ab_cti_max.smt2                                                    |  19.984s |22.644MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00002.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00011.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00019.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00060.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00081.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00152.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00324.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00379.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00402.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00415.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00428.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00793.smt2                                                                                  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|01052.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_AR_ab_cti_max.smt2                                                                    |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_UF_AR_ab_fp_max.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_Heap_ab_cti_max.smt2                                                                  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|QF_UF_Heap_ab_fp_max.smt2                                                                   |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|QF_UF_Huffman_enc_ab_reg_max.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_adding.1.prop1_ab_cti_max.smt2                                                        |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|QF_UF_adding.1.prop1_ab_reg_max.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_adding.2.prop1_ab_cti_max.smt2                                                        |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_adding.2.prop1_ab_reg_max.smt2                                                        |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|QF_UF_adding.3.prop1_ab_reg_max.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_adding.4.prop1_ab_reg_max.smt2                                                        |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_adding.5.prop1_ab_cti_max.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_adding.5.prop1_ab_reg_max.smt2                                                        |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_adding.6.prop1_ab_cti_max.smt2                                                        |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_adding.6.prop1_ab_reg_max.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_anderson.1.prop1_ab_reg_max.smt2                                                      |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_anderson.2.prop1_ab_reg_max.smt2                                                      |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_anderson.3.prop1_ab_reg_max.smt2                                                      |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_anderson.5.prop1_ab_reg_max.smt2                                                      |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_anderson.6.prop1_ab_reg_max.smt2                                                      |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_anderson.7.prop1_ab_cti_max.smt2                                                      |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|QF_UF_anderson.7.prop1_ab_reg_max.smt2                                                      |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_at.1.prop1_ab_cti_max.smt2                                                            |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|QF_UF_at.1.prop1_ab_reg_max.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_at.2.prop1_ab_reg_max.smt2                                                            |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_at.3.prop1_ab_reg_max.smt2                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_at.4.prop1_ab_cti_max.smt2                                                            |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|QF_UF_at.4.prop1_ab_reg_max.smt2                                                            |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_at.5.prop1_ab_cti_max.smt2                                                            |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|QF_UF_at.6.prop1_ab_cti_max.smt2                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|QF_UF_at.6.prop1_ab_reg_max.smt2                                                            |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_at.7.prop1_ab_cti_max.smt2                                                            |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|QF_UF_at.7.prop1_ab_reg_max.smt2                                                            |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_bakery.2.prop1_ab_reg_max.smt2                                                        |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_bakery.3.prop1_ab_reg_max.smt2                                                        |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_bakery.5.prop1_ab_cti_max.smt2                                                        |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|QF_UF_bakery.6.prop1_ab_cti_max.smt2                                                        |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|QF_UF_bakery.6.prop1_ab_reg_max.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_bakery.7.prop1_ab_reg_max.smt2                                                        |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_bakery.8.prop1_ab_cti_max.smt2                                                        |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|QF_UF_bakery.8.prop1_ab_reg_max.smt2                                                        |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_bit-vector_ab_br_max.smt2                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_bit-vector_ab_cti_max.smt2                                                            |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_blocks.4.prop1_ab_cti_max.smt2                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|QF_UF_bridge.3.prop1_ab_cti_max.smt2                                                        |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|QF_UF_brp.1.prop1_ab_cti_max.smt2                                                           |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|QF_UF_brp2.1.prop1_ab_cti_max.smt2                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|QF_UF_brp2.1.prop2_ab_cti_max.smt2                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|QF_UF_brp2.1.prop3_ab_cti_max.smt2                                                          |   1.186s  |   1.186s  |   0.000s  | 0.0%|
|QF_UF_brp2.2.prop1_ab_cti_max.smt2                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|QF_UF_brp2.2.prop2_ab_cti_max.smt2                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|QF_UF_brp2.2.prop3_ab_cti_max.smt2                                                          |   1.113s  |   1.113s  |   0.000s  | 0.0%|
|QF_UF_brp2.3.prop1_ab_cti_max.smt2                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|QF_UF_brp2.3.prop2_ab_cti_max.smt2                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|QF_UF_brp2.4.prop3_ab_cti_max.smt2                                                          |   1.156s  |   1.156s  |   0.000s  | 0.0%|
|QF_UF_brp2.5.prop1_ab_cti_max.smt2                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|QF_UF_brp2.5.prop2_ab_cti_max.smt2                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|QF_UF_brp2.5.prop3_ab_cti_max.smt2                                                          |   1.162s  |   1.162s  |   0.000s  | 0.0%|
|QF_UF_brp2.6.prop1_ab_cti_max.smt2                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|QF_UF_brp2.6.prop2_ab_cti_max.smt2                                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|QF_UF_brp2.6.prop3_ab_cti_max.smt2                                                          |   1.191s  |   1.191s  |   0.000s  | 0.0%|
|QF_UF_bug-1_ab_reg_max.smt2                                                                 |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_cache_coherence_three_ab_cti_max.smt2                                                 |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|QF_UF_cache_coherence_two_ab_cti_max.smt2                                                   |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|QF_UF_cambridge.1.prop1_ab_cti_max.smt2                                                     |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|QF_UF_cambridge.3.prop1_ab_cti_max.smt2                                                     |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|QF_UF_cambridge.3.prop2_ab_cti_max.smt2                                                     |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|QF_UF_cambridge.4.prop1_ab_cti_max.smt2                                                     |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|QF_UF_cambridge.4.prop2_ab_cti_max.smt2                                                     |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|QF_UF_cambridge.5.prop1_ab_cti_max.smt2                                                     |   1.256s  |   1.256s  |   0.000s  | 0.0%|
|QF_UF_cambridge.6.prop1_ab_cti_max.smt2                                                     |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|QF_UF_cambridge.6.prop2_ab_cti_max.smt2                                                     |   0.582s  |   0.582s  |   0.000s  | 0.0%|
|QF_UF_cav14_example_v_ab_cti_max.smt2                                                       |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_collision.3.prop1_ab_cti_max.smt2                                                     |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|QF_UF_collision.4.prop1_ab_cti_max.smt2                                                     |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|QF_UF_collision.6.prop1_ab_cti_max.smt2                                                     |   1.067s  |   1.067s  |   0.000s  | 0.0%|
|QF_UF_counter_ab_reg_max.smt2                                                               |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_counter_v_ab_cti_max.smt2                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_counter_v_ab_fp_max.smt2                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_cyclic_scheduler.2.prop1_ab_cti_max.smt2                                              |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|QF_UF_cyclic_scheduler.3.prop1_ab_cti_max.smt2                                              |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|QF_UF_cyclic_scheduler.4.prop1_ab_cti_max.smt2                                              |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|QF_UF_diagonal_ab_cti_max.smt2                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_diagonal_ab_reg_max.smt2                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_diagonal_v_ab_cti_max.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_driving_phils.1.prop1_ab_reg_max.smt2                                                 |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_driving_phils.2.prop1_ab_reg_max.smt2                                                 |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_driving_phils.3.prop1_ab_reg_max.smt2                                                 |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_driving_phils.5.prop1_ab_reg_max.smt2                                                 |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_dyn_partition_ab_reg_max.smt2                                                         |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_elevator_planning.1.prop1_ab_cti_max.smt2                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|QF_UF_elevator_planning.3.prop1_ab_cti_max.smt2                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v1_ab_cti_max.smt2                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v2_ab_cti_max.smt2                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v2_ab_reg_max.smt2                                                             |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v3_ab_cti_max.smt2                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v4_ab_cti_max.smt2                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v6_ab_cti_max.smt2                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_exit.1.prop1_ab_cti_max.smt2                                                          |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|QF_UF_exit.3.prop1_ab_cti_max.smt2                                                          |  19.953s  |  19.953s  |   0.000s  | 0.0%|
|QF_UF_extinction.1.prop1_ab_reg_max.smt2                                                    |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_extinction.3.prop1_ab_cti_max.smt2                                                    |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|QF_UF_extinction.3.prop1_ab_reg_max.smt2                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_extinction.4.prop1_ab_cti_max.smt2                                                    |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|QF_UF_extinction.4.prop1_ab_reg_max.smt2                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_fischer.1.prop1_ab_cti_max.smt2                                                       |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|QF_UF_fischer.4.prop1_ab_cti_max.smt2                                                       |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|QF_UF_fischer.4.prop1_ab_reg_max.smt2                                                       |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_fischer.5.prop1_ab_cti_max.smt2                                                       |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|QF_UF_fischer.5.prop1_ab_reg_max.smt2                                                       |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_fischer.6.prop1_ab_reg_max.smt2                                                       |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_fischer.7.prop1_ab_reg_max.smt2                                                       |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_frogs.3.prop1_ab_cti_max.smt2                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|QF_UF_frogs.4.prop1_ab_reg_max.smt2                                                         |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|QF_UF_frogs.5.prop1_ab_cti_max.smt2                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|QF_UF_gear.1.prop1_ab_reg_max.smt2                                                          |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_gear.1.prop2_ab_cti_max.smt2                                                          |   1.731s  |   1.731s  |   0.000s  | 0.0%|
|QF_UF_gear.1.prop3_ab_cti_max.smt2                                                          |   1.675s  |   1.675s  |   0.000s  | 0.0%|
|QF_UF_gear.1.prop4_ab_cti_max.smt2                                                          |   1.667s  |   1.667s  |   0.000s  | 0.0%|
|QF_UF_gear.2.prop1_ab_reg_max.smt2                                                          |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_gear.2.prop2_ab_cti_max.smt2                                                          |   1.709s  |   1.709s  |   0.000s  | 0.0%|
|QF_UF_gear.2.prop3_ab_cti_max.smt2                                                          |   1.684s  |   1.684s  |   0.000s  | 0.0%|
|QF_UF_h_Arbiter_ab_cti_max.smt2                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_h_BufAl_ab_br_max.smt2                                                                |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|QF_UF_h_BufAl_ab_cti_max.smt2                                                               |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|QF_UF_h_FIFO_ab_cti_max.smt2                                                                |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|QF_UF_h_FIFO_ab_reg_max.smt2                                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_h_TreeArb_ab_cti_max.smt2                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_UF_h_Vending_ab_cti_max.smt2                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|QF_UF_h_b07_ab_reg_max.smt2                                                                 |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_iprotocol.1.prop1_ab_cti_max.smt2                                                     |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|QF_UF_itc99_b12_ab_fp_max.smt2                                                              |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|QF_UF_itc99_b13_ab_reg_max.smt2                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_krebs.1.prop1_ab_cti_max.smt2                                                         |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|QF_UF_krebs.2.prop1_ab_cti_max.smt2                                                         |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|QF_UF_krebs.2.prop1_ab_reg_max.smt2                                                         |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|QF_UF_krebs.3.prop1_ab_cti_max.smt2                                                         |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|QF_UF_krebs.3.prop1_ab_reg_max.smt2                                                         |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|QF_UF_krebs.4.prop1_ab_cti_max.smt2                                                         |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|QF_UF_krebs.4.prop1_ab_reg_max.smt2                                                         |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|QF_UF_lamport.1.prop1_ab_reg_max.smt2                                                       |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|QF_UF_lamport.2.prop1_ab_reg_max.smt2                                                       |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_lamport.6.prop1_ab_reg_max.smt2                                                       |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|QF_UF_lamport.8.prop1_ab_cti_max.smt2                                                       |   2.229s  |   2.229s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.1.prop1_ab_cti_max.smt2                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.1.prop1_ab_reg_max.smt2                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.2.prop1_ab_cti_max.smt2                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.2.prop1_ab_reg_max.smt2                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.3.prop1_ab_cti_max.smt2                                             |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.4.prop1_ab_reg_max.smt2                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_lann.1.prop1_ab_reg_max.smt2                                                          |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|QF_UF_lann.2.prop1_ab_cti_max.smt2                                                          |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|QF_UF_lann.2.prop1_ab_reg_max.smt2                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|QF_UF_lann.3.prop1_ab_cti_max.smt2                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|QF_UF_lann.5.prop1_ab_cti_max.smt2                                                          |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|QF_UF_lann.7.prop1_ab_reg_max.smt2                                                          |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|QF_UF_lann.8.prop1_ab_reg_max.smt2                                                          |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|QF_UF_leader_election.1.prop1_ab_cti_max.smt2                                               |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|QF_UF_leader_election.2.prop1_ab_cti_max.smt2                                               |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|QF_UF_leader_election.2.prop1_ab_reg_max.smt2                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_leader_election.5.prop1_ab_reg_max.smt2                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_leader_election.6.prop1_ab_reg_max.smt2                                               |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.1.prop1_ab_cti_max.smt2                                                |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.1.prop1_ab_reg_max.smt2                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.2.prop1_ab_reg_max.smt2                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.3.prop1_ab_reg_max.smt2                                                |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.4.prop1_ab_cti_max.smt2                                                |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.4.prop1_ab_reg_max.smt2                                                |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.5.prop1_ab_cti_max.smt2                                                |  19.900s  |  19.900s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.5.prop1_ab_reg_max.smt2                                                |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_lifts.1.prop1_ab_cti_max.smt2                                                         |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|QF_UF_lifts.2.prop1_ab_cti_max.smt2                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|QF_UF_lup.2.prop1_ab_cti_max.smt2                                                           |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|QF_UF_lup.3.prop1_ab_cti_max.smt2                                                           |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|QF_UF_lup.4.prop1_ab_cti_max.smt2                                                           |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|QF_UF_mcs.1.prop1_ab_cti_max.smt2                                                           |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|QF_UF_mcs.3.prop1_ab_reg_max.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_mcs.4.prop1_ab_reg_max.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_mcs.5.prop1_ab_reg_max.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_mcs.6.prop1_ab_reg_max.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_miim_ab_cti_max.smt2                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_miim_ab_reg_max.smt2                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_mpeg_ab_cti_max.smt2                                                                  |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|QF_UF_mpeg_ab_reg_max.smt2                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_msmie.1.prop1_ab_cti_max.smt2                                                         |   2.554s  |   2.554s  |   0.000s  | 0.0%|
|QF_UF_needham.1.prop1_ab_cti_max.smt2                                                       |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|QF_UF_needham.1.prop2_ab_cti_max.smt2                                                       |  10.170s  |  10.170s  |   0.000s  | 0.0%|
|QF_UF_needham.1.prop3_ab_cti_max.smt2                                                       |  10.646s  |  10.646s  |   0.000s  | 0.0%|
|QF_UF_needham.2.prop1_ab_cti_max.smt2                                                       |  19.952s  |  19.952s  |   0.000s  | 0.0%|
|QF_UF_needham.2.prop3_ab_cti_max.smt2                                                       |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|QF_UF_needham.3.prop1_ab_cti_max.smt2                                                       |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|QF_UF_needham.3.prop2_ab_cti_max.smt2                                                       |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|QF_UF_needham.3.prop3_ab_cti_max.smt2                                                       |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|QF_UF_needham.3.prop4_ab_cti_max.smt2                                                       |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|QF_UF_needham.4.prop2_ab_cti_max.smt2                                                       |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|QF_UF_needham.4.prop3_ab_cti_max.smt2                                                       |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|QF_UF_needham.4.prop4_ab_cti_max.smt2                                                       |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|QF_UF_paper_v3_ab_cti_max.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_peg_solitaire.2.prop1_ab_reg_max.smt2                                                 |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|QF_UF_peg_solitaire.5.prop1_ab_reg_max.smt2                                                 |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|QF_UF_peg_solitaire.6.prop1_ab_cti_max.smt2                                                 |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|QF_UF_peg_solitaire.6.prop1_ab_reg_max.smt2                                                 |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|QF_UF_peterson.1.prop1_ab_cti_max.smt2                                                      |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|QF_UF_peterson.2.prop1_ab_reg_max.smt2                                                      |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_peterson.3.prop1_ab_reg_max.smt2                                                      |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_peterson.4.prop1_ab_cti_max.smt2                                                      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|QF_UF_peterson.4.prop1_ab_reg_max.smt2                                                      |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_peterson.5.prop1_ab_reg_max.smt2                                                      |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_peterson.6.prop1_ab_cti_max.smt2                                                      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|QF_UF_peterson.6.prop1_ab_reg_max.smt2                                                      |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_peterson.7.prop1_ab_reg_max.smt2                                                      |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_pgm_protocol.1.prop5_ab_reg_max.smt2                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_pgm_protocol.3.prop5_ab_reg_max.smt2                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_pgm_protocol.5.prop5_ab_reg_max.smt2                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_pgm_protocol.8.prop5_ab_reg_max.smt2                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_pipeline_ab_reg_max.smt2                                                              |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_plc.2.prop2_ab_reg_max.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_plc.3.prop2_ab_reg_max.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_plc.4.prop2_ab_reg_max.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_production_cell.3.prop1_ab_reg_max.smt2                                               |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_production_cell.6.prop1_ab_reg_max.smt2                                               |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_protocols.1.prop1_ab_cti_max.smt2                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_protocols.2.prop1_ab_cti_max.smt2                                                     |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|QF_UF_protocols.3.prop1_ab_cti_max.smt2                                                     |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|QF_UF_protocols.4.prop1_ab_cti_max.smt2                                                     |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|QF_UF_reader_writer.1.prop1_ab_cti_max.smt2                                                 |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|QF_UF_reader_writer.2.prop1_ab_cti_max.smt2                                                 |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|QF_UF_resistance.2.prop3_ab_reg_max.smt2                                                    |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|QF_UF_rether.1.prop1_ab_cti_max.smt2                                                        |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|QF_UF_rether.2.prop1_ab_cti_max.smt2                                                        |   1.924s  |   1.924s  |   0.000s  | 0.0%|
|QF_UF_rether.3.prop1_ab_cti_max.smt2                                                        |  19.924s  |  19.924s  |   0.000s  | 0.0%|
|QF_UF_schedule_world.1.prop1_ab_cti_max.smt2                                                |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_UF_schedule_world.2.prop1_ab_cti_max.smt2                                                |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|QF_UF_schedule_world.3.prop1_ab_reg_max.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|QF_UF_sdlx_ab_cti_max.smt2                                                                  |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|QF_UF_sdlx_ab_reg_max.smt2                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_seq_ab_cti_max.smt2                                                                   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_sokoban.2.prop1_ab_cti_max.smt2                                                       |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|QF_UF_sokoban.2.prop1_ab_fp_max.smt2                                                        |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|QF_UF_sw_ball2001_ab_cti_max.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_sw_ball2004_1_ab_cti_max.smt2                                                         |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_sw_ball2004_2_ab_cti_max.smt2                                                         |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_sw_loop_ab_cti_max.smt2                                                               |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_sw_loop_ab_fp_max.smt2                                                                |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_sw_loop_v_ab_cti_max.smt2                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_sw_state_machine_ab_cti_max.smt2                                                      |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_sw_sym_ex_ab_cti_max.smt2                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_sw_sym_ex_v_ab_cti_max.smt2                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_swap_three_ab_br_max.smt2                                                             |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_swap_three_ab_cti_max.smt2                                                            |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_swap_two_ab_br_max.smt2                                                               |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_swap_two_ab_cti_max.smt2                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_synabs2_ab_cti_max.smt2                                                               |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_synabs2_ab_reg_max.smt2                                                               |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_synapse.1.prop1_ab_cti_max.smt2                                                       |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|QF_UF_synapse.2.prop1_ab_cti_max.smt2                                                       |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|QF_UF_szymanski.1.prop1_ab_cti_max.smt2                                                     |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|QF_UF_szymanski.1.prop1_ab_reg_max.smt2                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_szymanski.2.prop1_ab_cti_max.smt2                                                     |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|QF_UF_szymanski.2.prop1_ab_reg_max.smt2                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_szymanski.3.prop1_ab_cti_max.smt2                                                     |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|QF_UF_szymanski.3.prop1_ab_reg_max.smt2                                                     |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_szymanski.4.prop1_ab_reg_max.smt2                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_szymanski.5.prop1_ab_reg_max.smt2                                                     |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_telephony.1.prop1_ab_cti_max.smt2                                                     |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|QF_UF_telephony.2.prop1_ab_cti_max.smt2                                                     |   7.702s  |   7.702s  |   0.000s  | 0.0%|
|QF_UF_telephony.4.prop1_ab_cti_max.smt2                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|QF_UF_telephony.5.prop1_ab_cti_max.smt2                                                     |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|QF_UF_telephony.6.prop1_ab_cti_max.smt2                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|QF_UF_telephony.7.prop1_ab_cti_max.smt2                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|QF_UF_telephony.8.prop1_ab_cti_max.smt2                                                     |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|QF_UF_train-gate.2.prop1_ab_cti_max.smt2                                                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|QF_UF_train-gate.3.prop1_ab_cti_max.smt2                                                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|QF_UF_train-gate.4.prop1_ab_cti_max.smt2                                                    |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|QF_UF_train-gate.7.prop1_ab_cti_max.smt2                                                    |   1.225s  |   1.225s  |   0.000s  | 0.0%|
|QF_UF_usb_phy_ab_cti_max.smt2                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_v_DAIO_ab_cti_max.smt2                                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_v_DAIO_ab_reg_max.smt2                                                                |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|SEQ004_size7.smt2                                                                           |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|SEQ015_size4.smt2                                                                           |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|SEQ017_size6.smt2                                                                           |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|SEQ018_size8.smt2                                                                           |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|SEQ020_size4.smt2                                                                           |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|SEQ050_size4.smt2                                                                           |  19.920s  |  19.920s  |   0.000s  | 0.0%|
|gensys_brn001.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn002.smt2                                                                          |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|gensys_brn056.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn057.smt2                                                                          |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|gensys_brn058.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn061.smt2                                                                          |  19.934s  |  19.934s  |   0.000s  | 0.0%|
|gensys_brn062.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn063.smt2                                                                          |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn064.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn065.smt2                                                                          |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|gensys_brn066.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn067.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn068.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn069.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn070.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn071.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn072.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn074.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn076.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn078.smt2                                                                          |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|gensys_brn079.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn080.smt2                                                                          |  19.936s  |  19.936s  |   0.000s  | 0.0%|
|gensys_brn081.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn082.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn083.smt2                                                                          |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|gensys_brn084.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn086.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn087.smt2                                                                          |  19.704s  |  19.704s  |   0.000s  | 0.0%|
|gensys_brn089.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn092.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn093.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn094.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn097.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn098.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn099.smt2                                                                          |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|gensys_brn100.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1001.smt2                                                                         |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|gensys_brn1005.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1006.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1007.smt2                                                                         |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn1009.smt2                                                                         |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|gensys_brn101.smt2                                                                          |  19.881s  |  19.881s  |   0.000s  | 0.0%|
|gensys_brn1012.smt2                                                                         |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|gensys_brn1013.smt2                                                                         |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|gensys_brn1014.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1016.smt2                                                                         |  19.930s  |  19.930s  |   0.000s  | 0.0%|
|gensys_brn1017.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1019.smt2                                                                         |  19.872s  |  19.872s  |   0.000s  | 0.0%|
|gensys_brn102.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1020.smt2                                                                         |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|gensys_brn1021.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1022.smt2                                                                         |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn1023.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1026.smt2                                                                         |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|gensys_brn1027.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1029.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn103.smt2                                                                          |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|gensys_brn1032.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1033.smt2                                                                         |  19.931s  |  19.931s  |   0.000s  | 0.0%|
|gensys_brn1035.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn104.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1040.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn1043.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1044.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1045.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1046.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1047.smt2                                                                         |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|gensys_brn1049.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1051.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1053.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1054.smt2                                                                         |  19.796s  |  19.796s  |   0.000s  | 0.0%|
|gensys_brn1055.smt2                                                                         |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn1056.smt2                                                                         |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn1058.smt2                                                                         |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn1059.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1060.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1062.smt2                                                                         |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn1063.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1064.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1065.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1066.smt2                                                                         |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn1067.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn1069.smt2                                                                         |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|gensys_brn107.smt2                                                                          |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn1072.smt2                                                                         |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn1076.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1077.smt2                                                                         |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn108.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn1080.smt2                                                                         |  19.716s  |  19.716s  |   0.000s  | 0.0%|
|gensys_brn1082.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1086.smt2                                                                         |  19.925s  |  19.925s  |   0.000s  | 0.0%|
|gensys_brn1089.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn109.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn1090.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1091.smt2                                                                         |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn1093.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1094.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1095.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1099.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn110.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1101.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1105.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1106.smt2                                                                         |  19.934s  |  19.934s  |   0.000s  | 0.0%|
|gensys_brn1107.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1108.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1109.smt2                                                                         |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|gensys_brn111.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1111.smt2                                                                         |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn1112.smt2                                                                         |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn1116.smt2                                                                         |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|gensys_brn1118.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn112.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1120.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1121.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn1122.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1123.smt2                                                                         |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn1125.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1126.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1127.smt2                                                                         |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|gensys_brn1128.smt2                                                                         |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn1129.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn113.smt2                                                                          |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|gensys_brn1130.smt2                                                                         |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|gensys_brn1131.smt2                                                                         |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn1132.smt2                                                                         |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|gensys_brn1133.smt2                                                                         |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|gensys_brn1134.smt2                                                                         |  19.926s  |  19.926s  |   0.000s  | 0.0%|
|gensys_brn1135.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1137.smt2                                                                         |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|gensys_brn1138.smt2                                                                         |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn114.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1141.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1142.smt2                                                                         |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|gensys_brn1144.smt2                                                                         |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn1145.smt2                                                                         |  19.924s  |  19.924s  |   0.000s  | 0.0%|
|gensys_brn1146.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1147.smt2                                                                         |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|gensys_brn1151.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1152.smt2                                                                         |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|gensys_brn1153.smt2                                                                         |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn1154.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1155.smt2                                                                         |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn1156.smt2                                                                         |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|gensys_brn1157.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1162.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1163.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1166.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1168.smt2                                                                         |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn1169.smt2                                                                         |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn117.smt2                                                                          |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|gensys_brn1171.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1172.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1177.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1178.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1179.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn118.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn1180.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1181.smt2                                                                         |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn1182.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1184.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn1185.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1187.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1188.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn119.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1193.smt2                                                                         |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|gensys_brn1194.smt2                                                                         |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn1196.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1199.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn120.smt2                                                                          |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|gensys_brn1200.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1201.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1202.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1204.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1206.smt2                                                                         |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn1207.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1208.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1209.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn121.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1210.smt2                                                                         |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|gensys_brn1211.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1212.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1213.smt2                                                                         |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn1215.smt2                                                                         |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|gensys_brn1216.smt2                                                                         |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|gensys_brn1217.smt2                                                                         |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|gensys_brn1218.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1219.smt2                                                                         |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|gensys_brn1220.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1221.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1222.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1224.smt2                                                                         |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn1227.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1228.smt2                                                                         |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn1229.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1235.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn1236.smt2                                                                         |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|gensys_brn1237.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1239.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1241.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1242.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1243.smt2                                                                         |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|gensys_brn1244.smt2                                                                         |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|gensys_brn1245.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn1246.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1247.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1248.smt2                                                                         |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn1249.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn125.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1250.smt2                                                                         |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|gensys_brn1251.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1252.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn1253.smt2                                                                         |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn1255.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1256.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn126.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn1265.smt2                                                                         |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|gensys_brn1267.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1268.smt2                                                                         |  19.924s  |  19.924s  |   0.000s  | 0.0%|
|gensys_brn1269.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1270.smt2                                                                         |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn1272.smt2                                                                         |  19.921s  |  19.921s  |   0.000s  | 0.0%|
|gensys_brn1273.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1274.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1275.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn1276.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1277.smt2                                                                         |  19.913s  |  19.913s  |   0.000s  | 0.0%|
|gensys_brn1278.smt2                                                                         |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn128.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1281.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1282.smt2                                                                         |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn1283.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1284.smt2                                                                         |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|gensys_brn1285.smt2                                                                         |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn1286.smt2                                                                         |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn1289.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn129.smt2                                                                          |  19.862s  |  19.862s  |   0.000s  | 0.0%|
|gensys_brn1291.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1292.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1293.smt2                                                                         |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn1294.smt2                                                                         |  19.849s  |  19.849s  |   0.000s  | 0.0%|
|gensys_brn1296.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1297.smt2                                                                         |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|gensys_brn1298.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1299.smt2                                                                         |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn1300.smt2                                                                         |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn1302.smt2                                                                         |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn1303.smt2                                                                         |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|gensys_brn1304.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1305.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1307.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1309.smt2                                                                         |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn1310.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1311.smt2                                                                         |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|gensys_brn1312.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1313.smt2                                                                         |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|gensys_brn1314.smt2                                                                         |  19.933s  |  19.933s  |   0.000s  | 0.0%|
|gensys_brn1317.smt2                                                                         |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|gensys_brn1318.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1320.smt2                                                                         |  19.740s  |  19.740s  |   0.000s  | 0.0%|
|gensys_brn1322.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1323.smt2                                                                         |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|gensys_brn1324.smt2                                                                         |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn1325.smt2                                                                         |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn1327.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn135.smt2                                                                          |  19.940s  |  19.940s  |   0.000s  | 0.0%|
|gensys_brn136.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn137.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn138.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn139.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn140.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn141.smt2                                                                          |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|gensys_brn142.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn143.smt2                                                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn144.smt2                                                                          |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn145.smt2                                                                          |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn147.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn148.smt2                                                                          |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|gensys_brn150.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn151.smt2                                                                          |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn152.smt2                                                                          |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|gensys_brn153.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn154.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn155.smt2                                                                          |  19.963s  |  19.963s  |   0.000s  | 0.0%|
|gensys_brn156.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn157.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn158.smt2                                                                          |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn160.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn161.smt2                                                                          |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|gensys_brn162.smt2                                                                          |  19.853s  |  19.853s  |   0.000s  | 0.0%|
|gensys_brn164.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn165.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn167.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn168.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn169.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn171.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn172.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn173.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn174.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn177.smt2                                                                          |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|gensys_brn178.smt2                                                                          |  19.898s  |  19.898s  |   0.000s  | 0.0%|
|gensys_brn179.smt2                                                                          |  19.818s  |  19.818s  |   0.000s  | 0.0%|
|gensys_brn182.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn185.smt2                                                                          |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn187.smt2                                                                          |  19.941s  |  19.941s  |   0.000s  | 0.0%|
|gensys_brn189.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn190.smt2                                                                          |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|gensys_brn191.smt2                                                                          |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|gensys_brn192.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn193.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn194.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn195.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn196.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn197.smt2                                                                          |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|gensys_brn199.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn201.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn202.smt2                                                                          |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|gensys_brn203.smt2                                                                          |  19.906s  |  19.906s  |   0.000s  | 0.0%|
|gensys_brn204.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn205.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn207.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn208.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn211.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn212.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn213.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn216.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn217.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn218.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn219.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn221.smt2                                                                          |  19.944s  |  19.944s  |   0.000s  | 0.0%|
|gensys_brn222.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn223.smt2                                                                          |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn226.smt2                                                                          |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|gensys_brn227.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn229.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn231.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn232.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn234.smt2                                                                          |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|gensys_brn235.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn236.smt2                                                                          |  19.913s  |  19.913s  |   0.000s  | 0.0%|
|gensys_brn237.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn239.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn240.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn241.smt2                                                                          |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|gensys_brn245.smt2                                                                          |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|gensys_brn246.smt2                                                                          |  19.197s  |  19.197s  |   0.000s  | 0.0%|
|gensys_brn247.smt2                                                                          |  19.963s  |  19.963s  |   0.000s  | 0.0%|
|gensys_brn250.smt2                                                                          |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|gensys_brn252.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn254.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn255.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn256.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn257.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn258.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn259.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn260.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn262.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn263.smt2                                                                          |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|gensys_brn266.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn269.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn273.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn274.smt2                                                                          |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|gensys_brn275.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn277.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn278.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn280.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn281.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn282.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn285.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn286.smt2                                                                          |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|gensys_brn287.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn289.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn290.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn292.smt2                                                                          |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|gensys_brn293.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn294.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn296.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn297.smt2                                                                          |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|gensys_brn298.smt2                                                                          |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|gensys_brn299.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn300.smt2                                                                          |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|gensys_brn301.smt2                                                                          |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|gensys_brn305.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn307.smt2                                                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn308.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn310.smt2                                                                          |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|gensys_brn312.smt2                                                                          |  19.953s  |  19.953s  |   0.000s  | 0.0%|
|gensys_brn319.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn320.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn322.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn327.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn328.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn329.smt2                                                                          |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn330.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn331.smt2                                                                          |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn333.smt2                                                                          |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|gensys_brn334.smt2                                                                          |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|gensys_brn335.smt2                                                                          |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|gensys_brn336.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn337.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn340.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn341.smt2                                                                          |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|gensys_brn343.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn344.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn345.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn346.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn347.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn351.smt2                                                                          |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|gensys_brn352.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn353.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn355.smt2                                                                          |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|gensys_brn356.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn357.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn359.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn361.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn363.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn366.smt2                                                                          |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn369.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn370.smt2                                                                          |  19.883s  |  19.883s  |   0.000s  | 0.0%|
|gensys_brn372.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn374.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn375.smt2                                                                          |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|gensys_brn377.smt2                                                                          |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|gensys_brn379.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn380.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn382.smt2                                                                          |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|gensys_brn383.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn385.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn386.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn387.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn389.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn390.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn391.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn394.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn397.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn398.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn399.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn401.smt2                                                                          |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|gensys_brn403.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn404.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn405.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn409.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn411.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn413.smt2                                                                          |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|gensys_brn414.smt2                                                                          |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|gensys_brn419.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn422.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn424.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn426.smt2                                                                          |  19.947s  |  19.947s  |   0.000s  | 0.0%|
|gensys_brn429.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn430.smt2                                                                          |  19.851s  |  19.851s  |   0.000s  | 0.0%|
|gensys_brn431.smt2                                                                          |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|gensys_brn432.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn437.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn438.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn441.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn443.smt2                                                                          |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|gensys_brn445.smt2                                                                          |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|gensys_brn446.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn449.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn450.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn451.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn452.smt2                                                                          |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn454.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn455.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn456.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn458.smt2                                                                          |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|gensys_brn459.smt2                                                                          |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|gensys_brn460.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn463.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn465.smt2                                                                          |  19.785s  |  19.785s  |   0.000s  | 0.0%|
|gensys_brn466.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn467.smt2                                                                          |  19.858s  |  19.858s  |   0.000s  | 0.0%|
|gensys_brn468.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn471.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn472.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn473.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn474.smt2                                                                          |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn477.smt2                                                                          |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|gensys_brn479.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn480.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn481.smt2                                                                          |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|gensys_brn482.smt2                                                                          |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|gensys_brn483.smt2                                                                          |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|gensys_brn486.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn490.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn491.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn492.smt2                                                                          |  19.917s  |  19.917s  |   0.000s  | 0.0%|
|gensys_brn493.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn495.smt2                                                                          |  19.890s  |  19.890s  |   0.000s  | 0.0%|
|gensys_brn496.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn497.smt2                                                                          |  19.936s  |  19.936s  |   0.000s  | 0.0%|
|gensys_brn498.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn501.smt2                                                                          |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|gensys_brn504.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn505.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn507.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn509.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn510.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn513.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn515.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn517.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn520.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn522.smt2                                                                          |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|gensys_brn523.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn524.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn525.smt2                                                                          |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|gensys_brn528.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn529.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn530.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn531.smt2                                                                          |  19.963s  |  19.963s  |   0.000s  | 0.0%|
|gensys_brn532.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn534.smt2                                                                          |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn535.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn538.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn539.smt2                                                                          |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|gensys_brn540.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn541.smt2                                                                          |  19.953s  |  19.953s  |   0.000s  | 0.0%|
|gensys_brn542.smt2                                                                          |  19.927s  |  19.927s  |   0.000s  | 0.0%|
|gensys_brn544.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn546.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn547.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn548.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn550.smt2                                                                          |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|gensys_brn551.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn554.smt2                                                                          |  19.920s  |  19.920s  |   0.000s  | 0.0%|
|gensys_brn555.smt2                                                                          |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|gensys_brn556.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn558.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn559.smt2                                                                          |  19.896s  |  19.896s  |   0.000s  | 0.0%|
|gensys_brn563.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn564.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn566.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn567.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn568.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn569.smt2                                                                          |  19.838s  |  19.838s  |   0.000s  | 0.0%|
|gensys_brn571.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn574.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn575.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn576.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn577.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn578.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn579.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn580.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn581.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn582.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn583.smt2                                                                          |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|gensys_brn584.smt2                                                                          |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn585.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn587.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn588.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn590.smt2                                                                          |  19.914s  |  19.914s  |   0.000s  | 0.0%|
|gensys_brn592.smt2                                                                          |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|gensys_brn594.smt2                                                                          |  19.932s  |  19.932s  |   0.000s  | 0.0%|
|gensys_brn595.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn596.smt2                                                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn598.smt2                                                                          |  19.941s  |  19.941s  |   0.000s  | 0.0%|
|gensys_brn599.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn600.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn602.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn603.smt2                                                                          |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|gensys_brn605.smt2                                                                          |  19.940s  |  19.940s  |   0.000s  | 0.0%|
|gensys_brn608.smt2                                                                          |  19.913s  |  19.913s  |   0.000s  | 0.0%|
|gensys_brn609.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn610.smt2                                                                          |  19.911s  |  19.911s  |   0.000s  | 0.0%|
|gensys_brn612.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn613.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn614.smt2                                                                          |  19.934s  |  19.934s  |   0.000s  | 0.0%|
|gensys_brn615.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn616.smt2                                                                          |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|gensys_brn617.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn620.smt2                                                                          |  19.832s  |  19.832s  |   0.000s  | 0.0%|
|gensys_brn625.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn626.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn627.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn628.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn629.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn630.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn631.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn632.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn633.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn635.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn636.smt2                                                                          |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|gensys_brn639.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn641.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn645.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn646.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn648.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn650.smt2                                                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn653.smt2                                                                          |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|gensys_brn654.smt2                                                                          |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|gensys_brn656.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn658.smt2                                                                          |  19.864s  |  19.864s  |   0.000s  | 0.0%|
|gensys_brn660.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn661.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn662.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn663.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn664.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn665.smt2                                                                          |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|gensys_brn666.smt2                                                                          |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|gensys_brn667.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn668.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn669.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn673.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn674.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn675.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn676.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn677.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn678.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn680.smt2                                                                          |  19.897s  |  19.897s  |   0.000s  | 0.0%|
|gensys_brn681.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn682.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn685.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn687.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn688.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn689.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn690.smt2                                                                          |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|gensys_brn691.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn692.smt2                                                                          |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|gensys_brn693.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn694.smt2                                                                          |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|gensys_brn695.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn698.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn699.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn701.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn706.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn707.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn708.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn709.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn711.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn713.smt2                                                                          |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|gensys_brn715.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn716.smt2                                                                          |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|gensys_brn717.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn720.smt2                                                                          |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|gensys_brn726.smt2                                                                          |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|gensys_brn730.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn731.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn733.smt2                                                                          |  19.944s  |  19.944s  |   0.000s  | 0.0%|
|gensys_brn734.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn736.smt2                                                                          |  19.943s  |  19.943s  |   0.000s  | 0.0%|
|gensys_brn739.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn740.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn741.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn743.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn744.smt2                                                                          |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|gensys_brn745.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn746.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn747.smt2                                                                          |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|gensys_brn748.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn749.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn750.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn754.smt2                                                                          |  19.927s  |  19.927s  |   0.000s  | 0.0%|
|gensys_brn756.smt2                                                                          |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|gensys_brn757.smt2                                                                          |  19.915s  |  19.915s  |   0.000s  | 0.0%|
|gensys_brn758.smt2                                                                          |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|gensys_brn759.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn760.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn762.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn763.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn765.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn768.smt2                                                                          |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|gensys_brn770.smt2                                                                          |  19.911s  |  19.911s  |   0.000s  | 0.0%|
|gensys_brn771.smt2                                                                          |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|gensys_brn772.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn774.smt2                                                                          |  19.903s  |  19.903s  |   0.000s  | 0.0%|
|gensys_brn778.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn780.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn782.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn783.smt2                                                                          |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|gensys_brn784.smt2                                                                          |  19.879s  |  19.879s  |   0.000s  | 0.0%|
|gensys_brn785.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn786.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn788.smt2                                                                          |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|gensys_brn790.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn791.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn792.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn796.smt2                                                                          |  19.857s  |  19.857s  |   0.000s  | 0.0%|
|gensys_brn797.smt2                                                                          |  19.918s  |  19.918s  |   0.000s  | 0.0%|
|gensys_brn798.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn799.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn800.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn801.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn803.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn804.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn808.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn809.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn810.smt2                                                                          |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|gensys_brn811.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn812.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn814.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn818.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn822.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn823.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn826.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn828.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn829.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn830.smt2                                                                          |  19.894s  |  19.894s  |   0.000s  | 0.0%|
|gensys_brn831.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn833.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn837.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn839.smt2                                                                          |  19.879s  |  19.879s  |   0.000s  | 0.0%|
|gensys_brn840.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn841.smt2                                                                          |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|gensys_brn842.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn843.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn847.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn848.smt2                                                                          |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|gensys_brn850.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn852.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn853.smt2                                                                          |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|gensys_brn856.smt2                                                                          |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|gensys_brn857.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn858.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn860.smt2                                                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn861.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn862.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn864.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn865.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn870.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn871.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn872.smt2                                                                          |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|gensys_brn877.smt2                                                                          |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|gensys_brn879.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn881.smt2                                                                          |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|gensys_brn882.smt2                                                                          |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|gensys_brn883.smt2                                                                          |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn884.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn885.smt2                                                                          |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|gensys_brn886.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn887.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn890.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn892.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn893.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn896.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn899.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn901.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn902.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn904.smt2                                                                          |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn906.smt2                                                                          |  19.926s  |  19.926s  |   0.000s  | 0.0%|
|gensys_brn907.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn908.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn909.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn911.smt2                                                                          |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|gensys_brn912.smt2                                                                          |  19.831s  |  19.831s  |   0.000s  | 0.0%|
|gensys_brn915.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn916.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn917.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn920.smt2                                                                          |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|gensys_brn921.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn922.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn924.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn925.smt2                                                                          |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|gensys_brn926.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn927.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn928.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn929.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn930.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn931.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn936.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn937.smt2                                                                          |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|gensys_brn938.smt2                                                                          |  19.859s  |  19.859s  |   0.000s  | 0.0%|
|gensys_brn940.smt2                                                                          |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|gensys_brn941.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn942.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn943.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn944.smt2                                                                          |  19.903s  |  19.903s  |   0.000s  | 0.0%|
|gensys_brn947.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn948.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn950.smt2                                                                          |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|gensys_brn951.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn952.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn953.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn955.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn958.smt2                                                                          |  19.867s  |  19.867s  |   0.000s  | 0.0%|
|gensys_brn960.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn964.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn966.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn967.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn968.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn970.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn971.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn972.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn975.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn976.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn978.smt2                                                                          |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn979.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn980.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn982.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn983.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn985.smt2                                                                          |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|gensys_brn987.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn989.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn990.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn992.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn994.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn996.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn999.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn002.smt2                                                                             |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|iso_brn003.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn004.smt2                                                                             |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|iso_brn006.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn007.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn008.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn009.smt2                                                                             |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|iso_brn011.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn012.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn013.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn014.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn015.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn016.smt2                                                                             |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|iso_brn017.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn020.smt2                                                                             |  19.850s  |  19.850s  |   0.000s  | 0.0%|
|iso_brn021.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn022.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn023.smt2                                                                             |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|iso_brn024.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn025.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn026.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn029.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn031.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn032.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn033.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn035.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn036.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn037.smt2                                                                             |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|iso_brn040.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn041.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn042.smt2                                                                             |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|iso_brn043.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn044.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn046.smt2                                                                             |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|iso_brn047.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn050.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn051.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn052.smt2                                                                             |  19.949s  |  19.949s  |   0.000s  | 0.0%|
|iso_brn053.smt2                                                                             |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|iso_brn055.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn056.smt2                                                                             |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|iso_brn057.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn059.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn061.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn063.smt2                                                                             |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|iso_brn064.smt2                                                                             |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|iso_brn065.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn068.smt2                                                                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|iso_brn069.smt2                                                                             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|iso_brn071.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn072.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn073.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn076.smt2                                                                             |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|iso_brn077.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn078.smt2                                                                             |  19.919s  |  19.919s  |   0.000s  | 0.0%|
|iso_brn080.smt2                                                                             |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|iso_brn081.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn082.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn083.smt2                                                                             |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|iso_brn084.smt2                                                                             |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|iso_brn085.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn086.smt2                                                                             |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|iso_brn087.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn088.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn089.smt2                                                                             |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|iso_brn091.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn092.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn093.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn094.smt2                                                                             |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|iso_brn095.smt2                                                                             |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|iso_brn096.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn097.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn098.smt2                                                                             |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|iso_brn099.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn100.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn1000.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn1001.smt2                                                                            |  19.853s  |  19.853s  |   0.000s  | 0.0%|
|iso_brn1003.smt2                                                                            |  19.888s  |  19.888s  |   0.000s  | 0.0%|
|iso_brn1007.smt2                                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn1008.smt2                                                                            |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|iso_brn1010.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn1011.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1013.smt2                                                                            |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|iso_brn1017.smt2                                                                            |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|iso_brn1018.smt2                                                                            |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn102.smt2                                                                             |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|iso_brn1021.smt2                                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn1024.smt2                                                                            |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn1025.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn1030.smt2                                                                            |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn1031.smt2                                                                            |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn1034.smt2                                                                            |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn1039.smt2                                                                            |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn104.smt2                                                                             |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|iso_brn1040.smt2                                                                            |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn1042.smt2                                                                            |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|iso_brn1043.smt2                                                                            |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn1046.smt2                                                                            |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|iso_brn105.smt2                                                                             |  19.834s  |  19.834s  |   0.000s  | 0.0%|
|iso_brn1051.smt2                                                                            |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|iso_brn1052.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn1053.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1054.smt2                                                                            |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|iso_brn1056.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1057.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn106.smt2                                                                             |  19.922s  |  19.922s  |   0.000s  | 0.0%|
|iso_brn1062.smt2                                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn1064.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1065.smt2                                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn1066.smt2                                                                            |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|iso_brn1071.smt2                                                                            |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|iso_brn1072.smt2                                                                            |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|iso_brn1074.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn1076.smt2                                                                            |  19.689s  |  19.689s  |   0.000s  | 0.0%|
|iso_brn1077.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn108.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1081.smt2                                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn1083.smt2                                                                            |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn1085.smt2                                                                            |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn1087.smt2                                                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn1089.smt2                                                                            |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn1091.smt2                                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn1095.smt2                                                                            |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|iso_brn1096.smt2                                                                            |  19.912s  |  19.912s  |   0.000s  | 0.0%|
|iso_brn1100.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn1101.smt2                                                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn1102.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1103.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn1104.smt2                                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn1106.smt2                                                                            |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|iso_brn111.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn1111.smt2                                                                            |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|iso_brn1112.smt2                                                                            |  19.941s  |  19.941s  |   0.000s  | 0.0%|
|iso_brn1115.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1117.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn1118.smt2                                                                            |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn1119.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn112.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn1120.smt2                                                                            |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn1123.smt2                                                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn1125.smt2                                                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn1128.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn1129.smt2                                                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn1130.smt2                                                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn1131.smt2                                                                            |  19.947s  |  19.947s  |   0.000s  | 0.0%|
|iso_brn1132.smt2                                                                            |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn1133.smt2                                                                            |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn1136.smt2                                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn1138.smt2                                                                            |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn1142.smt2                                                                            |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|iso_brn1145.smt2                                                                            |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn1148.smt2                                                                            |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|iso_brn1149.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn115.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn1150.smt2                                                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn1153.smt2                                                                            |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn1154.smt2                                                                            |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|iso_brn1155.smt2                                                                            |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn1157.smt2                                                                            |  19.929s  |  19.929s  |   0.000s  | 0.0%|
|iso_brn1158.smt2                                                                            |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn1159.smt2                                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn1160.smt2                                                                            |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn1161.smt2                                                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn1162.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn1164.smt2                                                                            |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|iso_brn1165.smt2                                                                            |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn1167.smt2                                                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn1169.smt2                                                                            |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn1170.smt2                                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn1171.smt2                                                                            |  19.906s  |  19.906s  |   0.000s  | 0.0%|
|iso_brn1173.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1176.smt2                                                                            |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn118.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn1188.smt2                                                                            |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|iso_brn1191.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1192.smt2                                                                            |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|iso_brn1193.smt2                                                                            |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn1194.smt2                                                                            |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|iso_brn1195.smt2                                                                            |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|iso_brn1196.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn1197.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn1198.smt2                                                                            |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|iso_brn120.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn1200.smt2                                                                            |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|iso_brn1201.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn1202.smt2                                                                            |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|iso_brn1203.smt2                                                                            |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn1205.smt2                                                                            |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|iso_brn1206.smt2                                                                            |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn1209.smt2                                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn1214.smt2                                                                            |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|iso_brn1216.smt2                                                                            |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn1217.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn1218.smt2                                                                            |  19.932s  |  19.932s  |   0.000s  | 0.0%|
|iso_brn1219.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn122.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn1223.smt2                                                                            |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|iso_brn1226.smt2                                                                            |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn1229.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn123.smt2                                                                             |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|iso_brn1230.smt2                                                                            |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn1234.smt2                                                                            |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn1235.smt2                                                                            |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn1238.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn124.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn1240.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn1241.smt2                                                                            |   8.403s  |   8.403s  |   0.000s  | 0.0%|
|iso_brn1242.smt2                                                                            |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|iso_brn1243.smt2                                                                            |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|iso_brn1244.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn1245.smt2                                                                            |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn1246.smt2                                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn1247.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1248.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn1249.smt2                                                                            |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|iso_brn1252.smt2                                                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn1254.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1256.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn1260.smt2                                                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn1261.smt2                                                                            |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|iso_brn1262.smt2                                                                            |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn1263.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1269.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1270.smt2                                                                            |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn1271.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn1272.smt2                                                                            |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|iso_brn1276.smt2                                                                            |  19.885s  |  19.885s  |   0.000s  | 0.0%|
|iso_brn1277.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn1278.smt2                                                                            |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|iso_brn128.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1280.smt2                                                                            |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn1282.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn1283.smt2                                                                            |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn1287.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1289.smt2                                                                            |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn129.smt2                                                                             |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|iso_brn1290.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1293.smt2                                                                            |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|iso_brn1294.smt2                                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn1296.smt2                                                                            |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|iso_brn1298.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1301.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1302.smt2                                                                            |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|iso_brn1305.smt2                                                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn1307.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn1308.smt2                                                                            |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn1310.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn1315.smt2                                                                            |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn1316.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn1317.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn132.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn1321.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn1325.smt2                                                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn1326.smt2                                                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn134.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn135.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn137.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn143.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn150.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn151.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn152.smt2                                                                             |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|iso_brn160.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn161.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn162.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn163.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn164.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn165.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn166.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn173.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn174.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn175.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn176.smt2                                                                             |  19.924s  |  19.924s  |   0.000s  | 0.0%|
|iso_brn177.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn178.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn181.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn183.smt2                                                                             |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|iso_brn184.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn187.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn192.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn193.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn196.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn197.smt2                                                                             |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|iso_brn198.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn199.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn200.smt2                                                                             |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|iso_brn201.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn205.smt2                                                                             |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|iso_brn206.smt2                                                                             |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|iso_brn207.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn209.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn210.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn214.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn216.smt2                                                                             |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|iso_brn218.smt2                                                                             |  19.939s  |  19.939s  |   0.000s  | 0.0%|
|iso_brn222.smt2                                                                             |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|iso_brn224.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn225.smt2                                                                             |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|iso_brn226.smt2                                                                             |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|iso_brn227.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn230.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn234.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn238.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn241.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn242.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn243.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn247.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn248.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn249.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn250.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn251.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn253.smt2                                                                             |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|iso_brn254.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn255.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn256.smt2                                                                             |  19.949s  |  19.949s  |   0.000s  | 0.0%|
|iso_brn259.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn260.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn261.smt2                                                                             |  19.885s  |  19.885s  |   0.000s  | 0.0%|
|iso_brn262.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn263.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn265.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn268.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn270.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn271.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn272.smt2                                                                             |  19.536s  |  19.536s  |   0.000s  | 0.0%|
|iso_brn273.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn274.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn276.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn278.smt2                                                                             |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|iso_brn283.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn284.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn286.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn288.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn289.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn293.smt2                                                                             |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|iso_brn294.smt2                                                                             |  19.921s  |  19.921s  |   0.000s  | 0.0%|
|iso_brn295.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn297.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn298.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn299.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn300.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn301.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn302.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn303.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn304.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn306.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn310.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn312.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn320.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn321.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn323.smt2                                                                             |  19.930s  |  19.930s  |   0.000s  | 0.0%|
|iso_brn325.smt2                                                                             |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|iso_brn326.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn327.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn329.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn332.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn334.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn335.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn336.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn339.smt2                                                                             |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|iso_brn340.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn342.smt2                                                                             |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|iso_brn343.smt2                                                                             |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|iso_brn347.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn348.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn349.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn350.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn354.smt2                                                                             |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|iso_brn355.smt2                                                                             |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|iso_brn356.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn357.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn358.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn359.smt2                                                                             |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|iso_brn361.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn364.smt2                                                                             |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|iso_brn365.smt2                                                                             |  19.944s  |  19.944s  |   0.000s  | 0.0%|
|iso_brn367.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn368.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn371.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn373.smt2                                                                             |  19.854s  |  19.854s  |   0.000s  | 0.0%|
|iso_brn375.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn376.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn377.smt2                                                                             |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|iso_brn378.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn381.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn382.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn383.smt2                                                                             |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|iso_brn390.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn393.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn394.smt2                                                                             |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|iso_brn395.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn396.smt2                                                                             |  19.892s  |  19.892s  |   0.000s  | 0.0%|
|iso_brn398.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn400.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn401.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn402.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn403.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn404.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn405.smt2                                                                             |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|iso_brn406.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn407.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn408.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn410.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn412.smt2                                                                             |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|iso_brn417.smt2                                                                             |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|iso_brn418.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn420.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn421.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn422.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn423.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn427.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn428.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn429.smt2                                                                             |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|iso_brn430.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn432.smt2                                                                             |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|iso_brn433.smt2                                                                             |  19.813s  |  19.813s  |   0.000s  | 0.0%|
|iso_brn434.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn435.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn436.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn437.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn438.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn441.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn442.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn444.smt2                                                                             |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|iso_brn447.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn448.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn450.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn451.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn453.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn455.smt2                                                                             |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|iso_brn456.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn459.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn462.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn464.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn466.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn468.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn469.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn470.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn472.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn473.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn475.smt2                                                                             |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|iso_brn476.smt2                                                                             |  19.899s  |  19.899s  |   0.000s  | 0.0%|
|iso_brn478.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn480.smt2                                                                             |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|iso_brn481.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn482.smt2                                                                             |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|iso_brn487.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn488.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn490.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn494.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn496.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn497.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn498.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn499.smt2                                                                             |  19.838s  |  19.838s  |   0.000s  | 0.0%|
|iso_brn501.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn503.smt2                                                                             |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|iso_brn508.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn509.smt2                                                                             |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|iso_brn510.smt2                                                                             |   0.962s  |   0.962s  |   0.000s  | 0.0%|
|iso_brn511.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn512.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn513.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn515.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn521.smt2                                                                             |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|iso_brn522.smt2                                                                             |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|iso_brn523.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn525.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn527.smt2                                                                             |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|iso_brn530.smt2                                                                             |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|iso_brn533.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn534.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn535.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn536.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn537.smt2                                                                             |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|iso_brn538.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn543.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn544.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn545.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn547.smt2                                                                             |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|iso_brn548.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn553.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn555.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn557.smt2                                                                             |  19.868s  |  19.868s  |   0.000s  | 0.0%|
|iso_brn560.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn561.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn564.smt2                                                                             |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|iso_brn565.smt2                                                                             |  19.560s  |  19.560s  |   0.000s  | 0.0%|
|iso_brn570.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn573.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn574.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn575.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn576.smt2                                                                             |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|iso_brn580.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn581.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn582.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn583.smt2                                                                             |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|iso_brn585.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn587.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn591.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn592.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn593.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn597.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn598.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn599.smt2                                                                             |  19.886s  |  19.886s  |   0.000s  | 0.0%|
|iso_brn601.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn602.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn603.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn607.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn609.smt2                                                                             |  19.882s  |  19.882s  |   0.000s  | 0.0%|
|iso_brn611.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn614.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn617.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn618.smt2                                                                             |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|iso_brn619.smt2                                                                             |  19.920s  |  19.920s  |   0.000s  | 0.0%|
|iso_brn620.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn621.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn622.smt2                                                                             |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|iso_brn624.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn625.smt2                                                                             |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|iso_brn628.smt2                                                                             |  19.919s  |  19.919s  |   0.000s  | 0.0%|
|iso_brn631.smt2                                                                             |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|iso_brn632.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn633.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn634.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn636.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn637.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn638.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn639.smt2                                                                             |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|iso_brn643.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn645.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn647.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn648.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn649.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn652.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn653.smt2                                                                             |  19.912s  |  19.912s  |   0.000s  | 0.0%|
|iso_brn654.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn656.smt2                                                                             |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|iso_brn657.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn659.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn668.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn669.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn671.smt2                                                                             |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|iso_brn672.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn676.smt2                                                                             |  19.897s  |  19.897s  |   0.000s  | 0.0%|
|iso_brn678.smt2                                                                             |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|iso_brn680.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn681.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn682.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn685.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn686.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn688.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn690.smt2                                                                             |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|iso_brn692.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn694.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn696.smt2                                                                             |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|iso_brn700.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn705.smt2                                                                             |  19.925s  |  19.925s  |   0.000s  | 0.0%|
|iso_brn707.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn708.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn709.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn710.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn712.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn713.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn714.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn715.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn716.smt2                                                                             |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|iso_brn719.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn721.smt2                                                                             |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|iso_brn722.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn724.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn727.smt2                                                                             |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|iso_brn728.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn729.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn730.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn731.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn732.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn734.smt2                                                                             |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|iso_brn736.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn737.smt2                                                                             |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|iso_brn738.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn742.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn747.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn752.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn753.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn754.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn755.smt2                                                                             |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|iso_brn758.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn759.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn760.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn761.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn766.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn768.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn770.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn771.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn777.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn778.smt2                                                                             |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|iso_brn784.smt2                                                                             |  19.941s  |  19.941s  |   0.000s  | 0.0%|
|iso_brn786.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn792.smt2                                                                             |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|iso_brn795.smt2                                                                             |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|iso_brn800.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn803.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn806.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn809.smt2                                                                             |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|iso_brn814.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn815.smt2                                                                             |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|iso_brn818.smt2                                                                             |  19.923s  |  19.923s  |   0.000s  | 0.0%|
|iso_brn821.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn823.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn824.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn827.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn828.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn835.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn836.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn837.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn838.smt2                                                                             |  19.852s  |  19.852s  |   0.000s  | 0.0%|
|iso_brn840.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn842.smt2                                                                             |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|iso_brn846.smt2                                                                             |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|iso_brn847.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn848.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn849.smt2                                                                             |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|iso_brn851.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn853.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn856.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn861.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn862.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn863.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn867.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn868.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn871.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn872.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn873.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn874.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn875.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn876.smt2                                                                             |  19.868s  |  19.868s  |   0.000s  | 0.0%|
|iso_brn878.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn881.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn883.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn884.smt2                                                                             |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|iso_brn885.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn886.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn888.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn891.smt2                                                                             |  19.866s  |  19.866s  |   0.000s  | 0.0%|
|iso_brn892.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn893.smt2                                                                             |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|iso_brn895.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn896.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn897.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn898.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn899.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn900.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn901.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn902.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn903.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn904.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn905.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn908.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn910.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn913.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn914.smt2                                                                             |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|iso_brn915.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn916.smt2                                                                             |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|iso_brn918.smt2                                                                             |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|iso_brn919.smt2                                                                             |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|iso_brn920.smt2                                                                             |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|iso_brn926.smt2                                                                             |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|iso_brn927.smt2                                                                             |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|iso_brn930.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn932.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn933.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn935.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn936.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn937.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn938.smt2                                                                             |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|iso_brn943.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn945.smt2                                                                             |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|iso_brn946.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn949.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn950.smt2                                                                             |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|iso_brn953.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn954.smt2                                                                             |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|iso_brn956.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn957.smt2                                                                             |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|iso_brn958.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn959.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn961.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn962.smt2                                                                             |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|iso_brn963.smt2                                                                             |   7.572s  |   7.572s  |   0.000s  | 0.0%|
|iso_brn964.smt2                                                                             |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|iso_brn966.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn968.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn973.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn974.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn978.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn979.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn981.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn982.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn990.smt2                                                                             |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|iso_brn991.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn994.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn995.smt2                                                                             |  19.953s  |  19.953s  |   0.000s  | 0.0%|
|iso_brn997.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn998.smt2                                                                             |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|iso_brn_repgen001.smt2                                                                      |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|iso_brn_repgen002.smt2                                                                      |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|iso_brn_repgen003.smt2                                                                      |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|iso_brn_repgen004.smt2                                                                      |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn_repgen006.smt2                                                                      |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|iso_brn_repgen007.smt2                                                                      |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|iso_brn_repgen009.smt2                                                                      |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn_repgen010.smt2                                                                      |  19.821s  |  19.821s  |   0.000s  | 0.0%|
|iso_brn_repgen011.smt2                                                                      |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|iso_brn_repgen012.smt2                                                                      |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn_repgen013.smt2                                                                      |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn_repgen014.smt2                                                                      |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn_repgen015.smt2                                                                      |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn_repgen016.smt2                                                                      |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|iso_brn_repgen018.smt2                                                                      |  19.820s  |  19.820s  |   0.000s  | 0.0%|
|iso_brn_repgen019.smt2                                                                      |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn_repgen020.smt2                                                                      |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn_repgen021.smt2                                                                      |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn_repgen022.smt2                                                                      |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn_repgen023.smt2                                                                      |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|iso_brn_repgen024.smt2                                                                      |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn_repgen025.smt2                                                                      |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|iso_brn_repgen026.smt2                                                                      |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|iso_brn_repgen028.smt2                                                                      |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|iso_brn_repgen029.smt2                                                                      |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn_repgen031.smt2                                                                      |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn_repgen032.smt2                                                                      |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn_repgen033.smt2                                                                      |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn_repgen034.smt2                                                                      |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn_repgen035.smt2                                                                      |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn_repgen036.smt2                                                                      |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn_repgen037.smt2                                                                      |  19.912s  |  19.912s  |   0.000s  | 0.0%|
|iso_brn_repgen038.smt2                                                                      |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn_repgen041.smt2                                                                      |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn_repgen043.smt2                                                                      |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|iso_brn_repgen044.smt2                                                                      |  19.869s  |  19.869s  |   0.000s  | 0.0%|
|iso_brn_repgen045.smt2                                                                      |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn_repgen046.smt2                                                                      |  19.941s  |  19.941s  |   0.000s  | 0.0%|
|iso_brn_repgen048.smt2                                                                      |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn_repgen049.smt2                                                                      |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn_repgen050.smt2                                                                      |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|iso_brn_repgen051.smt2                                                                      |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|iso_brn_repgen052.smt2                                                                      |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn_repgen053.smt2                                                                      |  19.963s  |  19.963s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk001.smt2                                                                   |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk002.smt2                                                                   |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk003.smt2                                                                   |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk004.smt2                                                                   |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk005.smt2                                                                   |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk006.smt2                                                                   |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk008.smt2                                                                   |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk009.smt2                                                                   |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk010.smt2                                                                   |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk011.smt2                                                                   |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk012.smt2                                                                   |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk013.smt2                                                                   |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk014.smt2                                                                   |  19.920s  |  19.920s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk015.smt2                                                                   |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk016.smt2                                                                   |  19.834s  |  19.834s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk017.smt2                                                                   |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk018.smt2                                                                   |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk019.smt2                                                                   |  19.893s  |  19.893s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk020.smt2                                                                   |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk021.smt2                                                                   |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk022.smt2                                                                   |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk023.smt2                                                                   |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk025.smt2                                                                   |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk027.smt2                                                                   |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk028.smt2                                                                   |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk029.smt2                                                                   |  19.925s  |  19.925s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk032.smt2                                                                   |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk033.smt2                                                                   |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk034.smt2                                                                   |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk036.smt2                                                                   |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk038.smt2                                                                   |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk039.smt2                                                                   |  19.898s  |  19.898s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk040.smt2                                                                   |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk041.smt2                                                                   |  19.871s  |  19.871s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk043.smt2                                                                   |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk044.smt2                                                                   |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk045.smt2                                                                   |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk046.smt2                                                                   |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk047.smt2                                                                   |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk048.smt2                                                                   |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk050.smt2                                                                   |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk051.smt2                                                                   |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk052.smt2                                                                   |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk053.smt2                                                                   |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk054.smt2                                                                   |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk055.smt2                                                                   |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|iso_brn_sk001.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn_sk002.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn_sk003.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn_sk005.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn_sk007.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn_sk008.smt2                                                                          |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|iso_brn_sk010.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn_sk011.smt2                                                                          |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|iso_brn_sk013.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn_sk014.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn_sk016.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn_sk017.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn_sk019.smt2                                                                          |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|iso_brn_sk024.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn_sk029.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn_sk030.smt2                                                                          |  19.912s  |  19.912s  |   0.000s  | 0.0%|
|iso_brn_sk041.smt2                                                                          |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|iso_brn_sk045.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn_sk046.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn_sk048.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn_sk049.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn_sk053.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn_sk055.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|smt2831655880469397696.smt2                                                                 |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|smt3232867547761696161.smt2                                                                 |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|smt3248576982810563470.smt2                                                                 |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|smt3508124013603727984.smt2                                                                 |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|smt3910673230463462036.smt2                                                                 |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|smt4027072204816894856.smt2                                                                 |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|smt4480564921249140261.smt2                                                                 |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|smt6109211130895037835.smt2                                                                 |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|smt6377531776677660648.smt2                                                                 |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|smt834303034702425531.smt2                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|smt862177804180920815.smt2                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
</details>
