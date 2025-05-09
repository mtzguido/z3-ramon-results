Comparing data and data


# SUMMARY
- LHS tests = 2000
- RHS tests = 2000
- LHS success = 1917  (95.85%)
- RHS success = 1917  (95.85%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: eufmix
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: f136d46fb4f0eab6968572e2b11954a13a037154
Z3 branch: sls
Z3 options: "-T:20 -v:2 sls.euf_incremental=2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_UF_SAT
Z3 commit message: bug fixes

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: eufmix
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: f136d46fb4f0eab6968572e2b11954a13a037154
Z3 branch: sls
Z3 options: "-T:20 -v:2 sls.euf_incremental=2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
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
|00003.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00011.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00019.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00060.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00081.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00152.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00002.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00011.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00019.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00060.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00081.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00152.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00002.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00011.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00019.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00060.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00081.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00152.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00002.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00011.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00019.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00060.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00081.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00152.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|gensys_brn1132.smt2                                                                        |  20.008s |19.676MiB|
|QF_UF_needham.4.prop2_ab_cti_max.smt2                                                      |  20.008s |23.116MiB|
|gensys_brn099.smt2                                                                         |  20.007s |19.56MiB|
|iso_brn_repgen028.smt2                                                                     |  20.007s |22.432MiB|
|gensys_brn1273.smt2                                                                        |  20.006s |19.48MiB|
|gensys_brn1169.smt2                                                                        |  20.006s |19.62MiB|
|gensys_brn539.smt2                                                                         |  20.006s |19.716MiB|
|gensys_brn1296.smt2                                                                        |  20.006s |19.3MiB|
|QF_UF_at.5.prop1_ab_cti_max.smt2                                                           |  20.006s |22.68MiB|
|gensys_brn765.smt2                                                                         |  20.006s |19.736MiB|
|gensys_brn887.smt2                                                                         |  20.006s |19.708MiB|
|gensys_brn580.smt2                                                                         |  20.005s |19.424MiB|
|gensys_brn674.smt2                                                                         |  20.005s |19.936MiB|
|gensys_brn486.smt2                                                                         |  20.005s |19.628MiB|
|gensys_brn999.smt2                                                                         |  20.005s |19.936MiB|
|gensys_brn1017.smt2                                                                        |  20.005s |19.272MiB|
|iso_brn498.smt2                                                                            |  20.005s |19.252MiB|
|gensys_brn257.smt2                                                                         |  20.004s |19.552MiB|
|QF_UF_lamport_nonatomic.3.prop1_ab_cti_max.smt2                                            |  20.004s |22.24MiB|
|gensys_brn555.smt2                                                                         |  20.004s |20.108MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|gensys_brn1132.smt2                                                                        |  20.008s |19.676MiB|
|QF_UF_needham.4.prop2_ab_cti_max.smt2                                                      |  20.008s |23.116MiB|
|gensys_brn099.smt2                                                                         |  20.007s |19.56MiB|
|iso_brn_repgen028.smt2                                                                     |  20.007s |22.432MiB|
|gensys_brn1273.smt2                                                                        |  20.006s |19.48MiB|
|gensys_brn1169.smt2                                                                        |  20.006s |19.62MiB|
|gensys_brn539.smt2                                                                         |  20.006s |19.716MiB|
|gensys_brn1296.smt2                                                                        |  20.006s |19.3MiB|
|QF_UF_at.5.prop1_ab_cti_max.smt2                                                           |  20.006s |22.68MiB|
|gensys_brn765.smt2                                                                         |  20.006s |19.736MiB|
|gensys_brn887.smt2                                                                         |  20.006s |19.708MiB|
|gensys_brn580.smt2                                                                         |  20.005s |19.424MiB|
|gensys_brn674.smt2                                                                         |  20.005s |19.936MiB|
|gensys_brn486.smt2                                                                         |  20.005s |19.628MiB|
|gensys_brn999.smt2                                                                         |  20.005s |19.936MiB|
|gensys_brn1017.smt2                                                                        |  20.005s |19.272MiB|
|iso_brn498.smt2                                                                            |  20.005s |19.252MiB|
|gensys_brn257.smt2                                                                         |  20.004s |19.552MiB|
|QF_UF_lamport_nonatomic.3.prop1_ab_cti_max.smt2                                            |  20.004s |22.24MiB|
|gensys_brn555.smt2                                                                         |  20.004s |20.108MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |18.508MiB|18.508MiB|0B| 0.0%|
|00002.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00011.smt2                                                                                  |19.016MiB|19.016MiB|0B| 0.0%|
|00019.smt2                                                                                  |20.04MiB|20.04MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00060.smt2                                                                                  |19.048MiB|19.048MiB|0B| 0.0%|
|00081.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.736MiB|18.736MiB|0B| 0.0%|
|00104.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00105.smt2                                                                                  |18.78MiB|18.78MiB|0B| 0.0%|
|00152.smt2                                                                                  |18.664MiB|18.664MiB|0B| 0.0%|
|00194.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.568MiB|18.568MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.736MiB|18.736MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.992MiB|18.992MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.676MiB|18.676MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |18.508MiB|18.508MiB|0B| 0.0%|
|00002.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00011.smt2                                                                                  |19.016MiB|19.016MiB|0B| 0.0%|
|00019.smt2                                                                                  |20.04MiB|20.04MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00060.smt2                                                                                  |19.048MiB|19.048MiB|0B| 0.0%|
|00081.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.736MiB|18.736MiB|0B| 0.0%|
|00104.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00105.smt2                                                                                  |18.78MiB|18.78MiB|0B| 0.0%|
|00152.smt2                                                                                  |18.664MiB|18.664MiB|0B| 0.0%|
|00194.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.568MiB|18.568MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.736MiB|18.736MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.992MiB|18.992MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.676MiB|18.676MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |18.508MiB|18.508MiB|0B| 0.0%|
|00002.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00011.smt2                                                                                  |19.016MiB|19.016MiB|0B| 0.0%|
|00019.smt2                                                                                  |20.04MiB|20.04MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00060.smt2                                                                                  |19.048MiB|19.048MiB|0B| 0.0%|
|00081.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.736MiB|18.736MiB|0B| 0.0%|
|00104.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00105.smt2                                                                                  |18.78MiB|18.78MiB|0B| 0.0%|
|00152.smt2                                                                                  |18.664MiB|18.664MiB|0B| 0.0%|
|00194.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.568MiB|18.568MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.736MiB|18.736MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.992MiB|18.992MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.676MiB|18.676MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |18.508MiB|18.508MiB|0B| 0.0%|
|00002.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00011.smt2                                                                                  |19.016MiB|19.016MiB|0B| 0.0%|
|00019.smt2                                                                                  |20.04MiB|20.04MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00060.smt2                                                                                  |19.048MiB|19.048MiB|0B| 0.0%|
|00081.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.736MiB|18.736MiB|0B| 0.0%|
|00104.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00105.smt2                                                                                  |18.78MiB|18.78MiB|0B| 0.0%|
|00152.smt2                                                                                  |18.664MiB|18.664MiB|0B| 0.0%|
|00194.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.568MiB|18.568MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.736MiB|18.736MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.76MiB|18.76MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.992MiB|18.992MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.676MiB|18.676MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_UF_sokoban.2.prop1_ab_cti_max.smt2                                                      |  19.999s |24.892MiB|
|iso_brn_repgen009.smt2                                                                     |  19.988s |23.856MiB|
|SEQ018_size8.smt2                                                                          |  19.997s |23.76MiB|
|SEQ035_size6.smt2                                                                          |  19.910s |23.472MiB|
|iso_brn_repgen011.smt2                                                                     |  19.997s |23.428MiB|
|QF_UF_lifts.1.prop1_ab_cti_max.smt2                                                        |  19.969s |23.416MiB|
|QF_UF_needham.4.prop4_ab_cti_max.smt2                                                      |  20.002s |23.408MiB|
|QF_UF_sokoban.2.prop1_ab_fp_max.smt2                                                       |  19.963s |23.396MiB|
|iso_brn_repgen018.smt2                                                                     |  19.996s |23.3MiB|
|QF_UF_synapse.2.prop1_ab_cti_max.smt2                                                      |  19.998s |23.204MiB|
|QF_UF_lifts.2.prop1_ab_cti_max.smt2                                                        |  19.967s |23.184MiB|
|iso_brn_repgen014.smt2                                                                     |  10.496s |23.184MiB|
|QF_UF_leader_election.2.prop1_ab_cti_max.smt2                                              |  20.002s |23.16MiB|
|QF_UF_needham.4.prop3_ab_cti_max.smt2                                                      |  19.995s |23.16MiB|
|iso_brn_repgen051.smt2                                                                     |  19.994s |23.14MiB|
|QF_UF_needham.4.prop2_ab_cti_max.smt2                                                      |  20.008s |23.116MiB|
|iso_brn_repgen016.smt2                                                                     |  17.880s |23.104MiB|
|iso_brn_repgen_sk012.smt2                                                                  |  19.972s |23.08MiB|
|iso_brn_repgen_sk028.smt2                                                                  |  19.999s |22.936MiB|
|QF_UF_leader_election.1.prop1_ab_cti_max.smt2                                              |  19.991s |22.916MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_UF_sokoban.2.prop1_ab_cti_max.smt2                                                      |  19.999s |24.892MiB|
|iso_brn_repgen009.smt2                                                                     |  19.988s |23.856MiB|
|SEQ018_size8.smt2                                                                          |  19.997s |23.76MiB|
|SEQ035_size6.smt2                                                                          |  19.910s |23.472MiB|
|iso_brn_repgen011.smt2                                                                     |  19.997s |23.428MiB|
|QF_UF_lifts.1.prop1_ab_cti_max.smt2                                                        |  19.969s |23.416MiB|
|QF_UF_needham.4.prop4_ab_cti_max.smt2                                                      |  20.002s |23.408MiB|
|QF_UF_sokoban.2.prop1_ab_fp_max.smt2                                                       |  19.963s |23.396MiB|
|iso_brn_repgen018.smt2                                                                     |  19.996s |23.3MiB|
|QF_UF_synapse.2.prop1_ab_cti_max.smt2                                                      |  19.998s |23.204MiB|
|QF_UF_lifts.2.prop1_ab_cti_max.smt2                                                        |  19.967s |23.184MiB|
|iso_brn_repgen014.smt2                                                                     |  10.496s |23.184MiB|
|QF_UF_leader_election.2.prop1_ab_cti_max.smt2                                              |  20.002s |23.16MiB|
|QF_UF_needham.4.prop3_ab_cti_max.smt2                                                      |  19.995s |23.16MiB|
|iso_brn_repgen051.smt2                                                                     |  19.994s |23.14MiB|
|QF_UF_needham.4.prop2_ab_cti_max.smt2                                                      |  20.008s |23.116MiB|
|iso_brn_repgen016.smt2                                                                     |  17.880s |23.104MiB|
|iso_brn_repgen_sk012.smt2                                                                  |  19.972s |23.08MiB|
|iso_brn_repgen_sk028.smt2                                                                  |  19.999s |22.936MiB|
|QF_UF_leader_election.1.prop1_ab_cti_max.smt2                                              |  19.991s |22.916MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00002.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00011.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00019.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00060.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00081.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00152.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00324.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00379.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00402.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00415.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00428.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00793.smt2                                                                                  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|01052.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_AR_ab_cti_max.smt2                                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_AR_ab_fp_max.smt2                                                                     |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_Heap_ab_cti_max.smt2                                                                  |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|QF_UF_Heap_ab_fp_max.smt2                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|QF_UF_Huffman_enc_ab_reg_max.smt2                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_adding.1.prop1_ab_cti_max.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_adding.1.prop1_ab_reg_max.smt2                                                        |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_adding.2.prop1_ab_cti_max.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_adding.2.prop1_ab_reg_max.smt2                                                        |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_adding.3.prop1_ab_reg_max.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_adding.4.prop1_ab_reg_max.smt2                                                        |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_adding.5.prop1_ab_cti_max.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_adding.5.prop1_ab_reg_max.smt2                                                        |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_adding.6.prop1_ab_cti_max.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_adding.6.prop1_ab_reg_max.smt2                                                        |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_anderson.1.prop1_ab_reg_max.smt2                                                      |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_anderson.2.prop1_ab_cti_max.smt2                                                      |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|QF_UF_anderson.2.prop1_ab_reg_max.smt2                                                      |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_anderson.3.prop1_ab_cti_max.smt2                                                      |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|QF_UF_anderson.3.prop1_ab_reg_max.smt2                                                      |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_anderson.5.prop1_ab_reg_max.smt2                                                      |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_anderson.6.prop1_ab_cti_max.smt2                                                      |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|QF_UF_anderson.6.prop1_ab_reg_max.smt2                                                      |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_anderson.7.prop1_ab_cti_max.smt2                                                      |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|QF_UF_anderson.7.prop1_ab_reg_max.smt2                                                      |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_at.1.prop1_ab_cti_max.smt2                                                            |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|QF_UF_at.1.prop1_ab_reg_max.smt2                                                            |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|QF_UF_at.2.prop1_ab_reg_max.smt2                                                            |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_at.3.prop1_ab_reg_max.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_at.4.prop1_ab_cti_max.smt2                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|QF_UF_at.4.prop1_ab_reg_max.smt2                                                            |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_at.5.prop1_ab_cti_max.smt2                                                            |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|QF_UF_at.6.prop1_ab_cti_max.smt2                                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|QF_UF_at.6.prop1_ab_reg_max.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_at.7.prop1_ab_cti_max.smt2                                                            |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|QF_UF_at.7.prop1_ab_reg_max.smt2                                                            |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_bakery.2.prop1_ab_reg_max.smt2                                                        |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_bakery.3.prop1_ab_reg_max.smt2                                                        |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_bakery.4.prop1_ab_cti_max.smt2                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|QF_UF_bakery.5.prop1_ab_cti_max.smt2                                                        |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|QF_UF_bakery.6.prop1_ab_cti_max.smt2                                                        |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|QF_UF_bakery.6.prop1_ab_reg_max.smt2                                                        |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_bakery.7.prop1_ab_reg_max.smt2                                                        |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_bakery.8.prop1_ab_cti_max.smt2                                                        |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|QF_UF_bakery.8.prop1_ab_reg_max.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_bit-vector_ab_br_max.smt2                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_bit-vector_ab_cti_max.smt2                                                            |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_blocks.2.prop1_ab_cti_max.smt2                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|QF_UF_blocks.4.prop1_ab_cti_max.smt2                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|QF_UF_bridge.2.prop1_ab_cti_max.smt2                                                        |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|QF_UF_bridge.3.prop1_ab_cti_max.smt2                                                        |   1.093s  |   1.093s  |   0.000s  | 0.0%|
|QF_UF_brp.1.prop1_ab_cti_max.smt2                                                           |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|QF_UF_brp.2.prop1_ab_cti_max.smt2                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|QF_UF_brp.4.prop1_ab_cti_max.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|QF_UF_brp.5.prop1_ab_cti_max.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|QF_UF_brp2.1.prop1_ab_cti_max.smt2                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|QF_UF_brp2.1.prop2_ab_cti_max.smt2                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|QF_UF_brp2.1.prop3_ab_cti_max.smt2                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|QF_UF_brp2.2.prop1_ab_cti_max.smt2                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|QF_UF_brp2.2.prop2_ab_cti_max.smt2                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|QF_UF_brp2.2.prop3_ab_cti_max.smt2                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|QF_UF_brp2.3.prop1_ab_cti_max.smt2                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|QF_UF_brp2.3.prop2_ab_cti_max.smt2                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|QF_UF_brp2.4.prop3_ab_cti_max.smt2                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|QF_UF_brp2.5.prop1_ab_cti_max.smt2                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|QF_UF_brp2.5.prop2_ab_cti_max.smt2                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|QF_UF_brp2.5.prop3_ab_cti_max.smt2                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|QF_UF_brp2.6.prop1_ab_cti_max.smt2                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|QF_UF_brp2.6.prop2_ab_cti_max.smt2                                                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|QF_UF_brp2.6.prop3_ab_cti_max.smt2                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|QF_UF_bug-1_ab_reg_max.smt2                                                                 |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|QF_UF_cache_coherence_three_ab_cti_max.smt2                                                 |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|QF_UF_cache_coherence_two_ab_br_max.smt2                                                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_cache_coherence_two_ab_cti_max.smt2                                                   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_cambridge.1.prop1_ab_cti_max.smt2                                                     |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|QF_UF_cambridge.2.prop1_ab_cti_max.smt2                                                     |   0.562s  |   0.562s  |   0.000s  | 0.0%|
|QF_UF_cambridge.2.prop2_ab_cti_max.smt2                                                     |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|QF_UF_cambridge.3.prop1_ab_cti_max.smt2                                                     |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|QF_UF_cambridge.3.prop2_ab_cti_max.smt2                                                     |   0.667s  |   0.667s  |   0.000s  | 0.0%|
|QF_UF_cambridge.4.prop1_ab_cti_max.smt2                                                     |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|QF_UF_cambridge.4.prop2_ab_cti_max.smt2                                                     |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|QF_UF_cambridge.5.prop1_ab_cti_max.smt2                                                     |   1.189s  |   1.189s  |   0.000s  | 0.0%|
|QF_UF_cambridge.6.prop1_ab_cti_max.smt2                                                     |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|QF_UF_cambridge.6.prop2_ab_cti_max.smt2                                                     |   0.588s  |   0.588s  |   0.000s  | 0.0%|
|QF_UF_cambridge.7.prop1_ab_cti_max.smt2                                                     |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|QF_UF_cambridge.7.prop2_ab_cti_max.smt2                                                     |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|QF_UF_cav14_example_v_ab_cti_max.smt2                                                       |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_collision.2.prop1_ab_cti_max.smt2                                                     |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|QF_UF_collision.3.prop1_ab_cti_max.smt2                                                     |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|QF_UF_collision.4.prop1_ab_cti_max.smt2                                                     |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|QF_UF_collision.6.prop1_ab_cti_max.smt2                                                     |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|QF_UF_counter_ab_cti_max.smt2                                                               |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_counter_ab_reg_max.smt2                                                               |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_counter_v_ab_cti_max.smt2                                                             |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_counter_v_ab_fp_max.smt2                                                              |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_cyclic_scheduler.2.prop1_ab_cti_max.smt2                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|QF_UF_cyclic_scheduler.3.prop1_ab_cti_max.smt2                                              |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|QF_UF_cyclic_scheduler.4.prop1_ab_cti_max.smt2                                              |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|QF_UF_diagonal_ab_cti_max.smt2                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_diagonal_ab_reg_max.smt2                                                              |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_diagonal_v_ab_cti_max.smt2                                                            |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_diagonal_v_ab_reg_max.smt2                                                            |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_driving_phils.1.prop1_ab_reg_max.smt2                                                 |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_driving_phils.2.prop1_ab_reg_max.smt2                                                 |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_driving_phils.3.prop1_ab_reg_max.smt2                                                 |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_driving_phils.5.prop1_ab_reg_max.smt2                                                 |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_dyn_partition_ab_reg_max.smt2                                                         |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_elevator.2.prop1_ab_cti_max.smt2                                                      |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|QF_UF_elevator.3.prop1_ab_cti_max.smt2                                                      |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|QF_UF_elevator.4.prop1_ab_cti_max.smt2                                                      |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|QF_UF_elevator.5.prop1_ab_cti_max.smt2                                                      |   7.729s  |   7.729s  |   0.000s  | 0.0%|
|QF_UF_elevator_planning.1.prop1_ab_cti_max.smt2                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|QF_UF_elevator_planning.2.prop1_ab_cti_max.smt2                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|QF_UF_elevator_planning.3.prop1_ab_cti_max.smt2                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|QF_UF_elevator_planning.3.prop1_ab_reg_max.smt2                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v1_ab_cti_max.smt2                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v2_ab_cti_max.smt2                                                             |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v2_ab_reg_max.smt2                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v3_ab_cti_max.smt2                                                             |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v4_ab_cti_max.smt2                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v6_ab_cti_max.smt2                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_exit.1.prop1_ab_cti_max.smt2                                                          |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|QF_UF_exit.3.prop1_ab_cti_max.smt2                                                          |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|QF_UF_extinction.1.prop1_ab_reg_max.smt2                                                    |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_extinction.3.prop1_ab_cti_max.smt2                                                    |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|QF_UF_extinction.3.prop1_ab_reg_max.smt2                                                    |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_extinction.4.prop1_ab_cti_max.smt2                                                    |  19.933s  |  19.933s  |   0.000s  | 0.0%|
|QF_UF_extinction.4.prop1_ab_reg_max.smt2                                                    |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_fischer.1.prop1_ab_cti_max.smt2                                                       |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|QF_UF_fischer.3.prop1_ab_cti_max.smt2                                                       |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|QF_UF_fischer.4.prop1_ab_cti_max.smt2                                                       |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|QF_UF_fischer.4.prop1_ab_reg_max.smt2                                                       |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_fischer.5.prop1_ab_cti_max.smt2                                                       |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|QF_UF_fischer.5.prop1_ab_reg_max.smt2                                                       |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_fischer.6.prop1_ab_reg_max.smt2                                                       |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_fischer.7.prop1_ab_reg_max.smt2                                                       |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_frogs.3.prop1_ab_cti_max.smt2                                                         |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|QF_UF_frogs.5.prop1_ab_cti_max.smt2                                                         |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|QF_UF_gear.1.prop1_ab_reg_max.smt2                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_gear.1.prop2_ab_cti_max.smt2                                                          |   1.713s  |   1.713s  |   0.000s  | 0.0%|
|QF_UF_gear.1.prop3_ab_cti_max.smt2                                                          |   1.649s  |   1.649s  |   0.000s  | 0.0%|
|QF_UF_gear.1.prop4_ab_cti_max.smt2                                                          |   1.686s  |   1.686s  |   0.000s  | 0.0%|
|QF_UF_gear.2.prop1_ab_reg_max.smt2                                                          |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_gear.2.prop2_ab_cti_max.smt2                                                          |   1.689s  |   1.689s  |   0.000s  | 0.0%|
|QF_UF_gear.2.prop3_ab_cti_max.smt2                                                          |   1.644s  |   1.644s  |   0.000s  | 0.0%|
|QF_UF_h_Arbiter_ab_cti_max.smt2                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_h_BufAl_ab_br_max.smt2                                                                |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|QF_UF_h_BufAl_ab_cti_max.smt2                                                               |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_h_FIFO_ab_cti_max.smt2                                                                |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|QF_UF_h_FIFO_ab_reg_max.smt2                                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_h_TreeArb_ab_cti_max.smt2                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_UF_h_Vending_ab_cti_max.smt2                                                             |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|QF_UF_h_Vending_ab_reg_max.smt2                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_h_b02_ab_br_max.smt2                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_h_b07_ab_reg_max.smt2                                                                 |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_hanoi.2.prop1_ab_reg_max.smt2                                                         |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_UF_hanoi.3.prop1_ab_reg_max.smt2                                                         |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|QF_UF_iprotocol.1.prop1_ab_cti_max.smt2                                                     |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|QF_UF_iprotocol.2.prop1_ab_cti_max.smt2                                                     |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|QF_UF_iprotocol.4.prop1_ab_cti_max.smt2                                                     |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|QF_UF_iprotocol.5.prop1_ab_cti_max.smt2                                                     |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|QF_UF_itc99_b12_ab_fp_max.smt2                                                              |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|QF_UF_itc99_b13_ab_reg_max.smt2                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_krebs.1.prop1_ab_cti_max.smt2                                                         |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_krebs.2.prop1_ab_cti_max.smt2                                                         |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|QF_UF_krebs.2.prop1_ab_reg_max.smt2                                                         |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|QF_UF_krebs.3.prop1_ab_cti_max.smt2                                                         |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|QF_UF_krebs.3.prop1_ab_reg_max.smt2                                                         |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_UF_krebs.4.prop1_ab_cti_max.smt2                                                         |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|QF_UF_krebs.4.prop1_ab_reg_max.smt2                                                         |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|QF_UF_lamport.1.prop1_ab_reg_max.smt2                                                       |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_lamport.2.prop1_ab_cti_max.smt2                                                       |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|QF_UF_lamport.2.prop1_ab_reg_max.smt2                                                       |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_lamport.6.prop1_ab_reg_max.smt2                                                       |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_lamport.8.prop1_ab_cti_max.smt2                                                       |   2.151s  |   2.151s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.1.prop1_ab_cti_max.smt2                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.1.prop1_ab_reg_max.smt2                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.2.prop1_ab_cti_max.smt2                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.2.prop1_ab_reg_max.smt2                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.3.prop1_ab_cti_max.smt2                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.4.prop1_ab_reg_max.smt2                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_lann.1.prop1_ab_reg_max.smt2                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|QF_UF_lann.2.prop1_ab_cti_max.smt2                                                          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|QF_UF_lann.2.prop1_ab_reg_max.smt2                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|QF_UF_lann.3.prop1_ab_cti_max.smt2                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|QF_UF_lann.5.prop1_ab_cti_max.smt2                                                          |   0.559s  |   0.559s  |   0.000s  | 0.0%|
|QF_UF_lann.5.prop1_ab_reg_max.smt2                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|QF_UF_lann.6.prop1_ab_reg_max.smt2                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|QF_UF_lann.7.prop1_ab_reg_max.smt2                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|QF_UF_lann.8.prop1_ab_reg_max.smt2                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|QF_UF_leader_election.1.prop1_ab_cti_max.smt2                                               |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|QF_UF_leader_election.2.prop1_ab_cti_max.smt2                                               |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|QF_UF_leader_election.2.prop1_ab_reg_max.smt2                                               |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_leader_election.5.prop1_ab_reg_max.smt2                                               |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_leader_election.6.prop1_ab_reg_max.smt2                                               |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.1.prop1_ab_cti_max.smt2                                                |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.1.prop1_ab_reg_max.smt2                                                |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.2.prop1_ab_reg_max.smt2                                                |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.3.prop1_ab_reg_max.smt2                                                |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.4.prop1_ab_cti_max.smt2                                                |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.4.prop1_ab_reg_max.smt2                                                |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.5.prop1_ab_cti_max.smt2                                                |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.5.prop1_ab_reg_max.smt2                                                |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_lifts.1.prop1_ab_cti_max.smt2                                                         |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|QF_UF_lifts.2.prop1_ab_cti_max.smt2                                                         |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|QF_UF_loyd.3.prop1_ab_cti_max.smt2                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|QF_UF_lup.1.prop1_ab_cti_max.smt2                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|QF_UF_lup.2.prop1_ab_cti_max.smt2                                                           |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|QF_UF_lup.3.prop1_ab_cti_max.smt2                                                           |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|QF_UF_lup.4.prop1_ab_cti_max.smt2                                                           |  19.726s  |  19.726s  |   0.000s  | 0.0%|
|QF_UF_mcs.1.prop1_ab_cti_max.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|QF_UF_mcs.3.prop1_ab_cti_max.smt2                                                           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|QF_UF_mcs.3.prop1_ab_reg_max.smt2                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_mcs.4.prop1_ab_reg_max.smt2                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_mcs.5.prop1_ab_reg_max.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_mcs.6.prop1_ab_reg_max.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_miim_ab_cti_max.smt2                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_miim_ab_reg_max.smt2                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_mpeg_ab_cti_max.smt2                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_mpeg_ab_reg_max.smt2                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_msmie.1.prop1_ab_cti_max.smt2                                                         |   2.567s  |   2.567s  |   0.000s  | 0.0%|
|QF_UF_needham.1.prop1_ab_cti_max.smt2                                                       |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|QF_UF_needham.2.prop1_ab_cti_max.smt2                                                       |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|QF_UF_needham.2.prop3_ab_cti_max.smt2                                                       |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|QF_UF_needham.3.prop1_ab_cti_max.smt2                                                       |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|QF_UF_needham.3.prop2_ab_cti_max.smt2                                                       |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|QF_UF_needham.3.prop3_ab_cti_max.smt2                                                       |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|QF_UF_needham.3.prop4_ab_cti_max.smt2                                                       |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|QF_UF_needham.4.prop2_ab_cti_max.smt2                                                       |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|QF_UF_needham.4.prop3_ab_cti_max.smt2                                                       |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|QF_UF_needham.4.prop4_ab_cti_max.smt2                                                       |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|QF_UF_paper_v3_ab_cti_max.smt2                                                              |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_peg_solitaire.1.prop1_ab_reg_max.smt2                                                 |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|QF_UF_peg_solitaire.2.prop1_ab_reg_max.smt2                                                 |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|QF_UF_peg_solitaire.4.prop1_ab_reg_max.smt2                                                 |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|QF_UF_peg_solitaire.5.prop1_ab_reg_max.smt2                                                 |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|QF_UF_peg_solitaire.6.prop1_ab_cti_max.smt2                                                 |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|QF_UF_peg_solitaire.6.prop1_ab_reg_max.smt2                                                 |  18.590s  |  18.590s  |   0.000s  | 0.0%|
|QF_UF_peterson.1.prop1_ab_cti_max.smt2                                                      |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|QF_UF_peterson.2.prop1_ab_reg_max.smt2                                                      |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_peterson.3.prop1_ab_cti_max.smt2                                                      |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|QF_UF_peterson.3.prop1_ab_reg_max.smt2                                                      |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_peterson.4.prop1_ab_cti_max.smt2                                                      |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|QF_UF_peterson.4.prop1_ab_reg_max.smt2                                                      |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_peterson.5.prop1_ab_reg_max.smt2                                                      |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_peterson.6.prop1_ab_cti_max.smt2                                                      |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|QF_UF_peterson.6.prop1_ab_reg_max.smt2                                                      |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_peterson.7.prop1_ab_cti_max.smt2                                                      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|QF_UF_peterson.7.prop1_ab_reg_max.smt2                                                      |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_pgm_protocol.1.prop5_ab_reg_max.smt2                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_pgm_protocol.3.prop5_ab_reg_max.smt2                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_pgm_protocol.5.prop5_ab_reg_max.smt2                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_pgm_protocol.8.prop5_ab_reg_max.smt2                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_pipeline_ab_reg_max.smt2                                                              |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_pj_icu_ab_fp_max.smt2                                                                 |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_plc.2.prop2_ab_reg_max.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_plc.3.prop2_ab_reg_max.smt2                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_plc.4.prop2_ab_reg_max.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_production_cell.2.prop1_ab_cti_max.smt2                                               |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|QF_UF_production_cell.3.prop1_ab_reg_max.smt2                                               |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_production_cell.6.prop1_ab_reg_max.smt2                                               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_protocols.1.prop1_ab_cti_max.smt2                                                     |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_protocols.2.prop1_ab_cti_max.smt2                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_UF_protocols.3.prop1_ab_cti_max.smt2                                                     |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|QF_UF_protocols.4.prop1_ab_cti_max.smt2                                                     |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|QF_UF_reader_writer.1.prop1_ab_cti_max.smt2                                                 |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|QF_UF_reader_writer.2.prop1_ab_cti_max.smt2                                                 |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|QF_UF_resistance.2.prop1_ab_cti_max.smt2                                                    |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|QF_UF_resistance.2.prop3_ab_reg_max.smt2                                                    |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|QF_UF_rether.1.prop1_ab_cti_max.smt2                                                        |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|QF_UF_rether.2.prop1_ab_cti_max.smt2                                                        |   2.030s  |   2.030s  |   0.000s  | 0.0%|
|QF_UF_rether.3.prop1_ab_cti_max.smt2                                                        |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|QF_UF_schedule_world.1.prop1_ab_cti_max.smt2                                                |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|QF_UF_schedule_world.2.prop1_ab_cti_max.smt2                                                |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|QF_UF_schedule_world.3.prop1_ab_reg_max.smt2                                                |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|QF_UF_sdlx_ab_fp_max.smt2                                                                   |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|QF_UF_sdlx_ab_reg_max.smt2                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_seq_ab_cti_max.smt2                                                                   |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_sokoban.2.prop1_ab_cti_max.smt2                                                       |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|QF_UF_sokoban.2.prop1_ab_fp_max.smt2                                                        |  19.963s  |  19.963s  |   0.000s  | 0.0%|
|QF_UF_sw_ball2001_ab_cti_max.smt2                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_sw_ball2004_1_ab_cti_max.smt2                                                         |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_sw_ball2004_2_ab_cti_max.smt2                                                         |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_sw_loop_ab_cti_max.smt2                                                               |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_sw_loop_ab_fp_max.smt2                                                                |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_sw_loop_v_ab_cti_max.smt2                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_sw_state_machine_ab_cti_max.smt2                                                      |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_sw_sym_ex_ab_cti_max.smt2                                                             |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_sw_sym_ex_v_ab_cti_max.smt2                                                           |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_swap_three_ab_br_max.smt2                                                             |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|QF_UF_swap_three_ab_cti_max.smt2                                                            |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_swap_two_ab_br_max.smt2                                                               |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_swap_two_ab_cti_max.smt2                                                              |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_synabs2_ab_cti_max.smt2                                                               |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_synabs2_ab_reg_max.smt2                                                               |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_synapse.1.prop1_ab_cti_max.smt2                                                       |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|QF_UF_synapse.2.prop1_ab_cti_max.smt2                                                       |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|QF_UF_szymanski.1.prop1_ab_cti_max.smt2                                                     |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|QF_UF_szymanski.1.prop1_ab_reg_max.smt2                                                     |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_szymanski.2.prop1_ab_cti_max.smt2                                                     |   2.414s  |   2.414s  |   0.000s  | 0.0%|
|QF_UF_szymanski.2.prop1_ab_reg_max.smt2                                                     |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_szymanski.3.prop1_ab_cti_max.smt2                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|QF_UF_szymanski.3.prop1_ab_reg_max.smt2                                                     |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_szymanski.4.prop1_ab_reg_max.smt2                                                     |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_szymanski.5.prop1_ab_reg_max.smt2                                                     |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|QF_UF_telephony.1.prop1_ab_cti_max.smt2                                                     |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|QF_UF_telephony.2.prop1_ab_cti_max.smt2                                                     |   7.329s  |   7.329s  |   0.000s  | 0.0%|
|QF_UF_telephony.4.prop1_ab_cti_max.smt2                                                     |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|QF_UF_telephony.5.prop1_ab_cti_max.smt2                                                     |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|QF_UF_telephony.6.prop1_ab_cti_max.smt2                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|QF_UF_telephony.7.prop1_ab_cti_max.smt2                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|QF_UF_telephony.8.prop1_ab_cti_max.smt2                                                     |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|QF_UF_train-gate.2.prop1_ab_cti_max.smt2                                                    |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|QF_UF_train-gate.3.prop1_ab_cti_max.smt2                                                    |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|QF_UF_train-gate.4.prop1_ab_cti_max.smt2                                                    |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|QF_UF_usb_phy_ab_cti_max.smt2                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_v_DAIO_ab_cti_max.smt2                                                                |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_v_DAIO_ab_fp_max.smt2                                                                 |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|QF_UF_v_DAIO_ab_reg_max.smt2                                                                |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|SEQ004_size7.smt2                                                                           |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|SEQ013_size6.smt2                                                                           |  19.930s  |  19.930s  |   0.000s  | 0.0%|
|SEQ015_size4.smt2                                                                           |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|SEQ017_size6.smt2                                                                           |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|SEQ018_size8.smt2                                                                           |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|SEQ020_size4.smt2                                                                           |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|SEQ032_size4.smt2                                                                           |   2.418s  |   2.418s  |   0.000s  | 0.0%|
|SEQ035_size6.smt2                                                                           |  19.910s  |  19.910s  |   0.000s  | 0.0%|
|SEQ050_size4.smt2                                                                           |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn001.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn002.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn056.smt2                                                                          |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|gensys_brn057.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn058.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn061.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn062.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn063.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn064.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn065.smt2                                                                          |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|gensys_brn066.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn067.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn068.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn069.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn070.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn071.smt2                                                                          |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|gensys_brn072.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn074.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn076.smt2                                                                          |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|gensys_brn078.smt2                                                                          |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|gensys_brn079.smt2                                                                          |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|gensys_brn080.smt2                                                                          |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|gensys_brn081.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn082.smt2                                                                          |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|gensys_brn083.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn084.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn086.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn087.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn089.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn092.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn093.smt2                                                                          |  19.914s  |  19.914s  |   0.000s  | 0.0%|
|gensys_brn094.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn097.smt2                                                                          |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|gensys_brn098.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn099.smt2                                                                          |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|gensys_brn100.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1001.smt2                                                                         |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|gensys_brn1005.smt2                                                                         |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn1006.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1007.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1009.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn101.smt2                                                                          |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|gensys_brn1012.smt2                                                                         |  19.929s  |  19.929s  |   0.000s  | 0.0%|
|gensys_brn1013.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1014.smt2                                                                         |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn1016.smt2                                                                         |  19.922s  |  19.922s  |   0.000s  | 0.0%|
|gensys_brn1017.smt2                                                                         |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|gensys_brn1019.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn102.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1020.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1021.smt2                                                                         |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn1022.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1023.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1026.smt2                                                                         |  19.949s  |  19.949s  |   0.000s  | 0.0%|
|gensys_brn1027.smt2                                                                         |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn1029.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn103.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1032.smt2                                                                         |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|gensys_brn1033.smt2                                                                         |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|gensys_brn1035.smt2                                                                         |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn104.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn1040.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1043.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1044.smt2                                                                         |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn1045.smt2                                                                         |  19.922s  |  19.922s  |   0.000s  | 0.0%|
|gensys_brn1046.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1047.smt2                                                                         |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn1049.smt2                                                                         |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn1051.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1053.smt2                                                                         |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn1054.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1055.smt2                                                                         |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|gensys_brn1056.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1058.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1059.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1060.smt2                                                                         |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|gensys_brn1062.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1063.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1064.smt2                                                                         |  19.932s  |  19.932s  |   0.000s  | 0.0%|
|gensys_brn1065.smt2                                                                         |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn1066.smt2                                                                         |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|gensys_brn1067.smt2                                                                         |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn1069.smt2                                                                         |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn107.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn1072.smt2                                                                         |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|gensys_brn1076.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1077.smt2                                                                         |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|gensys_brn108.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1080.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1082.smt2                                                                         |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|gensys_brn1086.smt2                                                                         |  19.931s  |  19.931s  |   0.000s  | 0.0%|
|gensys_brn1089.smt2                                                                         |  19.921s  |  19.921s  |   0.000s  | 0.0%|
|gensys_brn109.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1090.smt2                                                                         |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn1091.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1093.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1094.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1095.smt2                                                                         |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn1099.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn110.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1101.smt2                                                                         |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|gensys_brn1105.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1106.smt2                                                                         |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn1107.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1108.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1109.smt2                                                                         |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|gensys_brn111.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1111.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1112.smt2                                                                         |  19.882s  |  19.882s  |   0.000s  | 0.0%|
|gensys_brn1116.smt2                                                                         |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|gensys_brn1118.smt2                                                                         |  19.939s  |  19.939s  |   0.000s  | 0.0%|
|gensys_brn112.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn1120.smt2                                                                         |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|gensys_brn1121.smt2                                                                         |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|gensys_brn1122.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1123.smt2                                                                         |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|gensys_brn1125.smt2                                                                         |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn1126.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1127.smt2                                                                         |  19.931s  |  19.931s  |   0.000s  | 0.0%|
|gensys_brn1128.smt2                                                                         |  19.579s  |  19.579s  |   0.000s  | 0.0%|
|gensys_brn1129.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn113.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1130.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1131.smt2                                                                         |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn1132.smt2                                                                         |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|gensys_brn1133.smt2                                                                         |  19.923s  |  19.923s  |   0.000s  | 0.0%|
|gensys_brn1134.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1135.smt2                                                                         |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn1137.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1138.smt2                                                                         |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn114.smt2                                                                          |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|gensys_brn1141.smt2                                                                         |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|gensys_brn1142.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn1144.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1145.smt2                                                                         |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn1146.smt2                                                                         |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|gensys_brn1147.smt2                                                                         |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|gensys_brn1151.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1152.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn1153.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1154.smt2                                                                         |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|gensys_brn1155.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1156.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1157.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1162.smt2                                                                         |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|gensys_brn1163.smt2                                                                         |  19.896s  |  19.896s  |   0.000s  | 0.0%|
|gensys_brn1166.smt2                                                                         |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|gensys_brn1168.smt2                                                                         |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|gensys_brn1169.smt2                                                                         |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|gensys_brn117.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1171.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1172.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1177.smt2                                                                         |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|gensys_brn1178.smt2                                                                         |  19.941s  |  19.941s  |   0.000s  | 0.0%|
|gensys_brn1179.smt2                                                                         |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn118.smt2                                                                          |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|gensys_brn1180.smt2                                                                         |  19.891s  |  19.891s  |   0.000s  | 0.0%|
|gensys_brn1181.smt2                                                                         |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn1182.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1184.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn1185.smt2                                                                         |  19.864s  |  19.864s  |   0.000s  | 0.0%|
|gensys_brn1187.smt2                                                                         |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn1188.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn119.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1193.smt2                                                                         |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|gensys_brn1194.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1196.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1199.smt2                                                                         |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|gensys_brn120.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1200.smt2                                                                         |  19.952s  |  19.952s  |   0.000s  | 0.0%|
|gensys_brn1201.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1202.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1204.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1206.smt2                                                                         |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|gensys_brn1207.smt2                                                                         |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn1208.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1209.smt2                                                                         |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|gensys_brn121.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn1210.smt2                                                                         |  19.903s  |  19.903s  |   0.000s  | 0.0%|
|gensys_brn1211.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1212.smt2                                                                         |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|gensys_brn1213.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1215.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1216.smt2                                                                         |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn1217.smt2                                                                         |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|gensys_brn1218.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1219.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1220.smt2                                                                         |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn1221.smt2                                                                         |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|gensys_brn1222.smt2                                                                         |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn1224.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1227.smt2                                                                         |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn1228.smt2                                                                         |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|gensys_brn1229.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1235.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1236.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1237.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1239.smt2                                                                         |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn1241.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1242.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1243.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1244.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1245.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1246.smt2                                                                         |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn1247.smt2                                                                         |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|gensys_brn1248.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn1249.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn125.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn1250.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1251.smt2                                                                         |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|gensys_brn1252.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1253.smt2                                                                         |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|gensys_brn1255.smt2                                                                         |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn1256.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn126.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1265.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1267.smt2                                                                         |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn1268.smt2                                                                         |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|gensys_brn1269.smt2                                                                         |  19.941s  |  19.941s  |   0.000s  | 0.0%|
|gensys_brn1270.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1272.smt2                                                                         |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|gensys_brn1273.smt2                                                                         |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|gensys_brn1274.smt2                                                                         |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|gensys_brn1275.smt2                                                                         |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|gensys_brn1276.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1277.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1278.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn128.smt2                                                                          |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|gensys_brn1281.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1282.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn1283.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn1284.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1285.smt2                                                                         |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|gensys_brn1286.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1289.smt2                                                                         |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|gensys_brn129.smt2                                                                          |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|gensys_brn1291.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1292.smt2                                                                         |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|gensys_brn1293.smt2                                                                         |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|gensys_brn1294.smt2                                                                         |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn1296.smt2                                                                         |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|gensys_brn1297.smt2                                                                         |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn1298.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1299.smt2                                                                         |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|gensys_brn1300.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1302.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1303.smt2                                                                         |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn1304.smt2                                                                         |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn1305.smt2                                                                         |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|gensys_brn1307.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1309.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1310.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1311.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1312.smt2                                                                         |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn1313.smt2                                                                         |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|gensys_brn1314.smt2                                                                         |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn1317.smt2                                                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn1318.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn1320.smt2                                                                         |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn1322.smt2                                                                         |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn1323.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1324.smt2                                                                         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn1325.smt2                                                                         |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn1327.smt2                                                                         |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn135.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn136.smt2                                                                          |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|gensys_brn137.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn138.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn139.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn140.smt2                                                                          |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|gensys_brn141.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn142.smt2                                                                          |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn143.smt2                                                                          |  19.887s  |  19.887s  |   0.000s  | 0.0%|
|gensys_brn144.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn145.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn147.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn148.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn150.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn151.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn152.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn153.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn154.smt2                                                                          |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|gensys_brn155.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn156.smt2                                                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn157.smt2                                                                          |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|gensys_brn158.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn160.smt2                                                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn161.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn162.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn164.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn165.smt2                                                                          |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|gensys_brn167.smt2                                                                          |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|gensys_brn168.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn169.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn171.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn172.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn173.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn174.smt2                                                                          |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn177.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn178.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn179.smt2                                                                          |  19.953s  |  19.953s  |   0.000s  | 0.0%|
|gensys_brn182.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn185.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn187.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn189.smt2                                                                          |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|gensys_brn190.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn191.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn192.smt2                                                                          |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|gensys_brn193.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn194.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn195.smt2                                                                          |  19.766s  |  19.766s  |   0.000s  | 0.0%|
|gensys_brn196.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn197.smt2                                                                          |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|gensys_brn199.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn201.smt2                                                                          |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|gensys_brn202.smt2                                                                          |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|gensys_brn203.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn204.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn205.smt2                                                                          |  19.823s  |  19.823s  |   0.000s  | 0.0%|
|gensys_brn207.smt2                                                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn208.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn211.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn212.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn213.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn216.smt2                                                                          |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|gensys_brn217.smt2                                                                          |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|gensys_brn218.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn219.smt2                                                                          |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|gensys_brn221.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn222.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn223.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn226.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn227.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn229.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn231.smt2                                                                          |  19.927s  |  19.927s  |   0.000s  | 0.0%|
|gensys_brn232.smt2                                                                          |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|gensys_brn234.smt2                                                                          |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|gensys_brn235.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn236.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn237.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn239.smt2                                                                          |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|gensys_brn240.smt2                                                                          |  19.794s  |  19.794s  |   0.000s  | 0.0%|
|gensys_brn241.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn245.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn246.smt2                                                                          |  19.867s  |  19.867s  |   0.000s  | 0.0%|
|gensys_brn247.smt2                                                                          |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|gensys_brn250.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn252.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn254.smt2                                                                          |  19.936s  |  19.936s  |   0.000s  | 0.0%|
|gensys_brn255.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn256.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn257.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn258.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn259.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn260.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn262.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn263.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn266.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn269.smt2                                                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn273.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn274.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn275.smt2                                                                          |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|gensys_brn277.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn278.smt2                                                                          |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn280.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn281.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn282.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn285.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn286.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn287.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn289.smt2                                                                          |  19.923s  |  19.923s  |   0.000s  | 0.0%|
|gensys_brn290.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn292.smt2                                                                          |  19.947s  |  19.947s  |   0.000s  | 0.0%|
|gensys_brn293.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn294.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn296.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn297.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn298.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn299.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn300.smt2                                                                          |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn301.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn305.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn307.smt2                                                                          |  19.896s  |  19.896s  |   0.000s  | 0.0%|
|gensys_brn308.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn310.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn312.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn319.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn320.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn322.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn327.smt2                                                                          |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn328.smt2                                                                          |  19.947s  |  19.947s  |   0.000s  | 0.0%|
|gensys_brn329.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn330.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn331.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn333.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn334.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn335.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn336.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn337.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn340.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn341.smt2                                                                          |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn343.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn344.smt2                                                                          |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|gensys_brn345.smt2                                                                          |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|gensys_brn346.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn347.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn351.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn352.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn353.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn355.smt2                                                                          |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn356.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn357.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn359.smt2                                                                          |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|gensys_brn361.smt2                                                                          |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|gensys_brn363.smt2                                                                          |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|gensys_brn366.smt2                                                                          |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|gensys_brn369.smt2                                                                          |  19.939s  |  19.939s  |   0.000s  | 0.0%|
|gensys_brn370.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn372.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn374.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn375.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn377.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn379.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn380.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn382.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn383.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn385.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn386.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn387.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn389.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn390.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn391.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn394.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn397.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn398.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn399.smt2                                                                          |  19.941s  |  19.941s  |   0.000s  | 0.0%|
|gensys_brn401.smt2                                                                          |  19.939s  |  19.939s  |   0.000s  | 0.0%|
|gensys_brn403.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn404.smt2                                                                          |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn405.smt2                                                                          |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|gensys_brn409.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn411.smt2                                                                          |  19.939s  |  19.939s  |   0.000s  | 0.0%|
|gensys_brn413.smt2                                                                          |  19.909s  |  19.909s  |   0.000s  | 0.0%|
|gensys_brn414.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn419.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn422.smt2                                                                          |  19.907s  |  19.907s  |   0.000s  | 0.0%|
|gensys_brn424.smt2                                                                          |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn426.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn429.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn430.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn431.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn432.smt2                                                                          |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|gensys_brn437.smt2                                                                          |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn438.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn441.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn443.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn445.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn446.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn449.smt2                                                                          |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|gensys_brn450.smt2                                                                          |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|gensys_brn451.smt2                                                                          |  19.910s  |  19.910s  |   0.000s  | 0.0%|
|gensys_brn452.smt2                                                                          |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|gensys_brn454.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn455.smt2                                                                          |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|gensys_brn456.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn458.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn459.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn460.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn463.smt2                                                                          |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|gensys_brn465.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn466.smt2                                                                          |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn467.smt2                                                                          |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|gensys_brn468.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn471.smt2                                                                          |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|gensys_brn472.smt2                                                                          |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn473.smt2                                                                          |  19.837s  |  19.837s  |   0.000s  | 0.0%|
|gensys_brn474.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn477.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn479.smt2                                                                          |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|gensys_brn480.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn481.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn482.smt2                                                                          |  19.888s  |  19.888s  |   0.000s  | 0.0%|
|gensys_brn483.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn486.smt2                                                                          |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|gensys_brn490.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn491.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn492.smt2                                                                          |  19.865s  |  19.865s  |   0.000s  | 0.0%|
|gensys_brn493.smt2                                                                          |  19.900s  |  19.900s  |   0.000s  | 0.0%|
|gensys_brn495.smt2                                                                          |  19.323s  |  19.323s  |   0.000s  | 0.0%|
|gensys_brn496.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn497.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn498.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn501.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn504.smt2                                                                          |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|gensys_brn505.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn507.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn509.smt2                                                                          |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|gensys_brn510.smt2                                                                          |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn513.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn515.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn517.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn520.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn522.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn523.smt2                                                                          |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|gensys_brn524.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn525.smt2                                                                          |  19.912s  |  19.912s  |   0.000s  | 0.0%|
|gensys_brn528.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn529.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn530.smt2                                                                          |  19.926s  |  19.926s  |   0.000s  | 0.0%|
|gensys_brn531.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn532.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn534.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn535.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn538.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn539.smt2                                                                          |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|gensys_brn540.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn541.smt2                                                                          |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn542.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn544.smt2                                                                          |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|gensys_brn546.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn547.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn548.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn550.smt2                                                                          |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|gensys_brn551.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn554.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn555.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn556.smt2                                                                          |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|gensys_brn558.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn559.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn563.smt2                                                                          |  19.925s  |  19.925s  |   0.000s  | 0.0%|
|gensys_brn564.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn566.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn567.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn568.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn569.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn571.smt2                                                                          |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn574.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn575.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn576.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn577.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn578.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn579.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn580.smt2                                                                          |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|gensys_brn581.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn582.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn583.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn584.smt2                                                                          |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|gensys_brn585.smt2                                                                          |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|gensys_brn587.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn588.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn590.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn592.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn594.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn595.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn596.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn598.smt2                                                                          |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|gensys_brn599.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn600.smt2                                                                          |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn602.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn603.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn605.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn608.smt2                                                                          |  19.871s  |  19.871s  |   0.000s  | 0.0%|
|gensys_brn609.smt2                                                                          |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn610.smt2                                                                          |  19.922s  |  19.922s  |   0.000s  | 0.0%|
|gensys_brn612.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn613.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn614.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn615.smt2                                                                          |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|gensys_brn616.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn617.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn620.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn625.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn626.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn627.smt2                                                                          |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|gensys_brn628.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn629.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn630.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn631.smt2                                                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn632.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn633.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn635.smt2                                                                          |  19.818s  |  19.818s  |   0.000s  | 0.0%|
|gensys_brn636.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn639.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn641.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn645.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn646.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn648.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn650.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn653.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn654.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn656.smt2                                                                          |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|gensys_brn658.smt2                                                                          |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn660.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn661.smt2                                                                          |  19.920s  |  19.920s  |   0.000s  | 0.0%|
|gensys_brn662.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn663.smt2                                                                          |  19.915s  |  19.915s  |   0.000s  | 0.0%|
|gensys_brn664.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn665.smt2                                                                          |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|gensys_brn666.smt2                                                                          |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|gensys_brn667.smt2                                                                          |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn668.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn669.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn673.smt2                                                                          |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn674.smt2                                                                          |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|gensys_brn675.smt2                                                                          |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|gensys_brn676.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn677.smt2                                                                          |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|gensys_brn678.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn680.smt2                                                                          |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|gensys_brn681.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn682.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn685.smt2                                                                          |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|gensys_brn687.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn688.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn689.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn690.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn691.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn692.smt2                                                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn693.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn694.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn695.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn698.smt2                                                                          |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|gensys_brn699.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn701.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn706.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn707.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn708.smt2                                                                          |  19.952s  |  19.952s  |   0.000s  | 0.0%|
|gensys_brn709.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn711.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn713.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn715.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn716.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn717.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn720.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn726.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn730.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn731.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn733.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn734.smt2                                                                          |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|gensys_brn736.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn739.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn740.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn741.smt2                                                                          |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|gensys_brn743.smt2                                                                          |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|gensys_brn744.smt2                                                                          |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|gensys_brn745.smt2                                                                          |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|gensys_brn746.smt2                                                                          |  19.909s  |  19.909s  |   0.000s  | 0.0%|
|gensys_brn747.smt2                                                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn748.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn749.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn750.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn754.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn756.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn757.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn758.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn759.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn760.smt2                                                                          |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn762.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn763.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn765.smt2                                                                          |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|gensys_brn768.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn770.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn771.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn772.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn774.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn778.smt2                                                                          |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|gensys_brn780.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn782.smt2                                                                          |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|gensys_brn783.smt2                                                                          |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|gensys_brn784.smt2                                                                          |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|gensys_brn785.smt2                                                                          |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn786.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn788.smt2                                                                          |  19.830s  |  19.830s  |   0.000s  | 0.0%|
|gensys_brn790.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn791.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn792.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn796.smt2                                                                          |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|gensys_brn797.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn798.smt2                                                                          |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|gensys_brn799.smt2                                                                          |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|gensys_brn800.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|gensys_brn801.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn803.smt2                                                                          |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|gensys_brn804.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn808.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn809.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn810.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn811.smt2                                                                          |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|gensys_brn812.smt2                                                                          |  19.883s  |  19.883s  |   0.000s  | 0.0%|
|gensys_brn814.smt2                                                                          |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|gensys_brn818.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn822.smt2                                                                          |  19.896s  |  19.896s  |   0.000s  | 0.0%|
|gensys_brn823.smt2                                                                          |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|gensys_brn826.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn828.smt2                                                                          |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|gensys_brn829.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn830.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn831.smt2                                                                          |  19.932s  |  19.932s  |   0.000s  | 0.0%|
|gensys_brn833.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn837.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn839.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn840.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn841.smt2                                                                          |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|gensys_brn842.smt2                                                                          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|gensys_brn843.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn847.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|gensys_brn848.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn850.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn852.smt2                                                                          |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|gensys_brn853.smt2                                                                          |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|gensys_brn856.smt2                                                                          |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn857.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn858.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn860.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn861.smt2                                                                          |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|gensys_brn862.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn864.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn865.smt2                                                                          |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|gensys_brn870.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn871.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn872.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn877.smt2                                                                          |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|gensys_brn879.smt2                                                                          |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|gensys_brn881.smt2                                                                          |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|gensys_brn882.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn883.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn884.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn885.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn886.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn887.smt2                                                                          |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|gensys_brn890.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn892.smt2                                                                          |  19.908s  |  19.908s  |   0.000s  | 0.0%|
|gensys_brn893.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn896.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn899.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn901.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn902.smt2                                                                          |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|gensys_brn904.smt2                                                                          |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|gensys_brn906.smt2                                                                          |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|gensys_brn907.smt2                                                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn908.smt2                                                                          |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|gensys_brn909.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn911.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn912.smt2                                                                          |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|gensys_brn915.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn916.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn917.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn920.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn921.smt2                                                                          |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|gensys_brn922.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn924.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn925.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn926.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn927.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn928.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn929.smt2                                                                          |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|gensys_brn930.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn931.smt2                                                                          |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|gensys_brn936.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn937.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn938.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn940.smt2                                                                          |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|gensys_brn941.smt2                                                                          |  19.798s  |  19.798s  |   0.000s  | 0.0%|
|gensys_brn942.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn943.smt2                                                                          |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|gensys_brn944.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|gensys_brn947.smt2                                                                          |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|gensys_brn948.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn950.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn951.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn952.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn953.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn955.smt2                                                                          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|gensys_brn958.smt2                                                                          |  19.918s  |  19.918s  |   0.000s  | 0.0%|
|gensys_brn960.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn964.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn966.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|gensys_brn967.smt2                                                                          |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|gensys_brn968.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn970.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn971.smt2                                                                          |  19.789s  |  19.789s  |   0.000s  | 0.0%|
|gensys_brn972.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn975.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|gensys_brn976.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn978.smt2                                                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|gensys_brn979.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn980.smt2                                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|gensys_brn982.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gensys_brn983.smt2                                                                          |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|gensys_brn985.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|gensys_brn987.smt2                                                                          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|gensys_brn989.smt2                                                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|gensys_brn990.smt2                                                                          |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|gensys_brn992.smt2                                                                          |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|gensys_brn994.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|gensys_brn996.smt2                                                                          |  19.912s  |  19.912s  |   0.000s  | 0.0%|
|gensys_brn999.smt2                                                                          |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|iso_brn002.smt2                                                                             |   2.497s  |   2.497s  |   0.000s  | 0.0%|
|iso_brn003.smt2                                                                             |   0.817s  |   0.817s  |   0.000s  | 0.0%|
|iso_brn004.smt2                                                                             |   2.579s  |   2.579s  |   0.000s  | 0.0%|
|iso_brn006.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn007.smt2                                                                             |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|iso_brn008.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn009.smt2                                                                             |   3.620s  |   3.620s  |   0.000s  | 0.0%|
|iso_brn011.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn012.smt2                                                                             |   2.827s  |   2.827s  |   0.000s  | 0.0%|
|iso_brn014.smt2                                                                             |   1.643s  |   1.643s  |   0.000s  | 0.0%|
|iso_brn015.smt2                                                                             |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|iso_brn016.smt2                                                                             |   2.386s  |   2.386s  |   0.000s  | 0.0%|
|iso_brn017.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn020.smt2                                                                             |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|iso_brn022.smt2                                                                             |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|iso_brn023.smt2                                                                             |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|iso_brn024.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn025.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn026.smt2                                                                             |   0.724s  |   0.724s  |   0.000s  | 0.0%|
|iso_brn029.smt2                                                                             |   1.855s  |   1.855s  |   0.000s  | 0.0%|
|iso_brn031.smt2                                                                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|iso_brn032.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn033.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn035.smt2                                                                             |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|iso_brn036.smt2                                                                             |  19.963s  |  19.963s  |   0.000s  | 0.0%|
|iso_brn037.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|iso_brn040.smt2                                                                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|iso_brn041.smt2                                                                             |   0.577s  |   0.577s  |   0.000s  | 0.0%|
|iso_brn042.smt2                                                                             |   1.469s  |   1.469s  |   0.000s  | 0.0%|
|iso_brn043.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn044.smt2                                                                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|iso_brn046.smt2                                                                             |   2.654s  |   2.654s  |   0.000s  | 0.0%|
|iso_brn047.smt2                                                                             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|iso_brn050.smt2                                                                             |   1.715s  |   1.715s  |   0.000s  | 0.0%|
|iso_brn051.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn052.smt2                                                                             |   4.028s  |   4.028s  |   0.000s  | 0.0%|
|iso_brn053.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn055.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn057.smt2                                                                             |   0.922s  |   0.922s  |   0.000s  | 0.0%|
|iso_brn059.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn061.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn063.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn064.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn069.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|iso_brn071.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|iso_brn072.smt2                                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|iso_brn073.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn076.smt2                                                                             |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|iso_brn077.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn078.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn080.smt2                                                                             |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|iso_brn081.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn082.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn083.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn084.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn085.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn086.smt2                                                                             |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|iso_brn087.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn088.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn089.smt2                                                                             |   0.907s  |   0.907s  |   0.000s  | 0.0%|
|iso_brn091.smt2                                                                             |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|iso_brn092.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn093.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn094.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn095.smt2                                                                             |  19.888s  |  19.888s  |   0.000s  | 0.0%|
|iso_brn096.smt2                                                                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|iso_brn097.smt2                                                                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|iso_brn098.smt2                                                                             |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|iso_brn099.smt2                                                                             |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|iso_brn1000.smt2                                                                            |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|iso_brn1001.smt2                                                                            |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|iso_brn1003.smt2                                                                            |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|iso_brn1007.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|iso_brn1011.smt2                                                                            |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|iso_brn1013.smt2                                                                            |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|iso_brn1017.smt2                                                                            |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|iso_brn1018.smt2                                                                            |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|iso_brn102.smt2                                                                             |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|iso_brn1021.smt2                                                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|iso_brn1024.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1025.smt2                                                                            |   0.663s  |   0.663s  |   0.000s  | 0.0%|
|iso_brn1030.smt2                                                                            |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|iso_brn1031.smt2                                                                            |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|iso_brn1034.smt2                                                                            |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|iso_brn1039.smt2                                                                            |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|iso_brn104.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn1040.smt2                                                                            |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|iso_brn1042.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|iso_brn1043.smt2                                                                            |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|iso_brn1046.smt2                                                                            |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|iso_brn105.smt2                                                                             |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|iso_brn1051.smt2                                                                            |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|iso_brn1052.smt2                                                                            |   0.719s  |   0.719s  |   0.000s  | 0.0%|
|iso_brn1053.smt2                                                                            |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|iso_brn1054.smt2                                                                            |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|iso_brn106.smt2                                                                             |  13.479s  |  13.479s  |   0.000s  | 0.0%|
|iso_brn1062.smt2                                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|iso_brn1064.smt2                                                                            |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|iso_brn1065.smt2                                                                            |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|iso_brn1066.smt2                                                                            |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|iso_brn1071.smt2                                                                            |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|iso_brn1072.smt2                                                                            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|iso_brn1074.smt2                                                                            |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|iso_brn1076.smt2                                                                            |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|iso_brn1077.smt2                                                                            |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|iso_brn108.smt2                                                                             |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|iso_brn1081.smt2                                                                            |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|iso_brn1083.smt2                                                                            |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|iso_brn1085.smt2                                                                            |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|iso_brn1088.smt2                                                                            |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|iso_brn1089.smt2                                                                            |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|iso_brn1091.smt2                                                                            |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|iso_brn1095.smt2                                                                            |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|iso_brn1096.smt2                                                                            |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|iso_brn1100.smt2                                                                            |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|iso_brn1101.smt2                                                                            |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|iso_brn1102.smt2                                                                            |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|iso_brn1103.smt2                                                                            |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|iso_brn1104.smt2                                                                            |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|iso_brn1106.smt2                                                                            |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|iso_brn1111.smt2                                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|iso_brn1112.smt2                                                                            |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|iso_brn1115.smt2                                                                            |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|iso_brn1117.smt2                                                                            |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|iso_brn1118.smt2                                                                            |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|iso_brn1119.smt2                                                                            |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|iso_brn112.smt2                                                                             |   0.848s  |   0.848s  |   0.000s  | 0.0%|
|iso_brn1120.smt2                                                                            |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|iso_brn1123.smt2                                                                            |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|iso_brn1125.smt2                                                                            |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|iso_brn1128.smt2                                                                            |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|iso_brn1129.smt2                                                                            |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|iso_brn1130.smt2                                                                            |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|iso_brn1131.smt2                                                                            |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|iso_brn1132.smt2                                                                            |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|iso_brn1133.smt2                                                                            |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|iso_brn1136.smt2                                                                            |   2.256s  |   2.256s  |   0.000s  | 0.0%|
|iso_brn1138.smt2                                                                            |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|iso_brn1142.smt2                                                                            |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|iso_brn1145.smt2                                                                            |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|iso_brn1148.smt2                                                                            |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|iso_brn1149.smt2                                                                            |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|iso_brn115.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn1150.smt2                                                                            |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|iso_brn1154.smt2                                                                            |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|iso_brn1155.smt2                                                                            |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|iso_brn1157.smt2                                                                            |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|iso_brn1158.smt2                                                                            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|iso_brn1159.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|iso_brn1160.smt2                                                                            |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|iso_brn1161.smt2                                                                            |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|iso_brn1165.smt2                                                                            |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|iso_brn1167.smt2                                                                            |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|iso_brn1170.smt2                                                                            |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|iso_brn1171.smt2                                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|iso_brn1173.smt2                                                                            |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|iso_brn1176.smt2                                                                            |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|iso_brn1179.smt2                                                                            |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|iso_brn118.smt2                                                                             |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|iso_brn1191.smt2                                                                            |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|iso_brn1192.smt2                                                                            |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|iso_brn1193.smt2                                                                            |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|iso_brn1194.smt2                                                                            |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|iso_brn1195.smt2                                                                            |   0.657s  |   0.657s  |   0.000s  | 0.0%|
|iso_brn1196.smt2                                                                            |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|iso_brn1198.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|iso_brn120.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn1200.smt2                                                                            |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|iso_brn1201.smt2                                                                            |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|iso_brn1203.smt2                                                                            |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|iso_brn1205.smt2                                                                            |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|iso_brn1206.smt2                                                                            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|iso_brn1209.smt2                                                                            |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|iso_brn1214.smt2                                                                            |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|iso_brn1216.smt2                                                                            |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|iso_brn1217.smt2                                                                            |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|iso_brn1218.smt2                                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|iso_brn1219.smt2                                                                            |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|iso_brn122.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn1226.smt2                                                                            |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|iso_brn1229.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|iso_brn123.smt2                                                                             |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|iso_brn1230.smt2                                                                            |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|iso_brn1234.smt2                                                                            |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|iso_brn1235.smt2                                                                            |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|iso_brn1238.smt2                                                                            |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|iso_brn124.smt2                                                                             |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|iso_brn1240.smt2                                                                            |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|iso_brn1241.smt2                                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|iso_brn1242.smt2                                                                            |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|iso_brn1243.smt2                                                                            |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|iso_brn1244.smt2                                                                            |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|iso_brn1245.smt2                                                                            |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|iso_brn1246.smt2                                                                            |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|iso_brn1247.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|iso_brn1248.smt2                                                                            |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|iso_brn1249.smt2                                                                            |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|iso_brn1252.smt2                                                                            |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|iso_brn1254.smt2                                                                            |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|iso_brn1256.smt2                                                                            |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|iso_brn1260.smt2                                                                            |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|iso_brn1261.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|iso_brn1262.smt2                                                                            |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|iso_brn1263.smt2                                                                            |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|iso_brn1269.smt2                                                                            |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|iso_brn1270.smt2                                                                            |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|iso_brn1272.smt2                                                                            |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|iso_brn1276.smt2                                                                            |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|iso_brn1278.smt2                                                                            |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|iso_brn128.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn1280.smt2                                                                            |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|iso_brn1282.smt2                                                                            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|iso_brn1287.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|iso_brn1289.smt2                                                                            |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|iso_brn129.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn1290.smt2                                                                            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|iso_brn1293.smt2                                                                            |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|iso_brn1296.smt2                                                                            |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|iso_brn1298.smt2                                                                            |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|iso_brn1301.smt2                                                                            |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|iso_brn1302.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|iso_brn1305.smt2                                                                            |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|iso_brn1308.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|iso_brn1310.smt2                                                                            |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|iso_brn1316.smt2                                                                            |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|iso_brn1317.smt2                                                                            |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|iso_brn132.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn1321.smt2                                                                            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|iso_brn1325.smt2                                                                            |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|iso_brn1326.smt2                                                                            |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|iso_brn134.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn135.smt2                                                                             |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|iso_brn137.smt2                                                                             |  19.952s  |  19.952s  |   0.000s  | 0.0%|
|iso_brn143.smt2                                                                             |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|iso_brn150.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn151.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn152.smt2                                                                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|iso_brn160.smt2                                                                             |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|iso_brn161.smt2                                                                             |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|iso_brn162.smt2                                                                             |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|iso_brn163.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn164.smt2                                                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|iso_brn165.smt2                                                                             |   0.821s  |   0.821s  |   0.000s  | 0.0%|
|iso_brn166.smt2                                                                             |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|iso_brn173.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn175.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn178.smt2                                                                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|iso_brn181.smt2                                                                             |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|iso_brn183.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn184.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn187.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn192.smt2                                                                             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|iso_brn193.smt2                                                                             |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|iso_brn196.smt2                                                                             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|iso_brn197.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn198.smt2                                                                             |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|iso_brn199.smt2                                                                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|iso_brn200.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn201.smt2                                                                             |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|iso_brn205.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn207.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn209.smt2                                                                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|iso_brn214.smt2                                                                             |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|iso_brn216.smt2                                                                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|iso_brn218.smt2                                                                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|iso_brn221.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|iso_brn222.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|iso_brn224.smt2                                                                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|iso_brn225.smt2                                                                             |  19.898s  |  19.898s  |   0.000s  | 0.0%|
|iso_brn226.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn227.smt2                                                                             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|iso_brn230.smt2                                                                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|iso_brn234.smt2                                                                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|iso_brn238.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn241.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn243.smt2                                                                             |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|iso_brn248.smt2                                                                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|iso_brn249.smt2                                                                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|iso_brn250.smt2                                                                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|iso_brn251.smt2                                                                             |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|iso_brn253.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn254.smt2                                                                             |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|iso_brn255.smt2                                                                             |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|iso_brn256.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn259.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn260.smt2                                                                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|iso_brn261.smt2                                                                             |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|iso_brn262.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn263.smt2                                                                             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|iso_brn265.smt2                                                                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|iso_brn268.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn270.smt2                                                                             |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|iso_brn271.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|iso_brn272.smt2                                                                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|iso_brn273.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn274.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn276.smt2                                                                             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|iso_brn278.smt2                                                                             |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|iso_brn283.smt2                                                                             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|iso_brn284.smt2                                                                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|iso_brn286.smt2                                                                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|iso_brn288.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn289.smt2                                                                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|iso_brn293.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn294.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn295.smt2                                                                             |  19.873s  |  19.873s  |   0.000s  | 0.0%|
|iso_brn297.smt2                                                                             |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|iso_brn298.smt2                                                                             |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|iso_brn299.smt2                                                                             |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|iso_brn300.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn301.smt2                                                                             |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|iso_brn302.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn303.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn304.smt2                                                                             |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|iso_brn306.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn310.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn312.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn320.smt2                                                                             |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|iso_brn321.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn323.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn325.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn326.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn327.smt2                                                                             |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|iso_brn329.smt2                                                                             |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|iso_brn332.smt2                                                                             |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|iso_brn334.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn335.smt2                                                                             |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|iso_brn336.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn339.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn340.smt2                                                                             |  19.880s  |  19.880s  |   0.000s  | 0.0%|
|iso_brn342.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn343.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn347.smt2                                                                             |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|iso_brn348.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn349.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn350.smt2                                                                             |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|iso_brn354.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn355.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn356.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn357.smt2                                                                             |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|iso_brn358.smt2                                                                             |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|iso_brn359.smt2                                                                             |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|iso_brn361.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn364.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn365.smt2                                                                             |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|iso_brn367.smt2                                                                             |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|iso_brn368.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn371.smt2                                                                             |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|iso_brn373.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn375.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn376.smt2                                                                             |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|iso_brn377.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn378.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn381.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn382.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn383.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn390.smt2                                                                             |  19.939s  |  19.939s  |   0.000s  | 0.0%|
|iso_brn393.smt2                                                                             |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|iso_brn394.smt2                                                                             |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|iso_brn395.smt2                                                                             |  19.913s  |  19.913s  |   0.000s  | 0.0%|
|iso_brn396.smt2                                                                             |  19.844s  |  19.844s  |   0.000s  | 0.0%|
|iso_brn398.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn400.smt2                                                                             |  19.790s  |  19.790s  |   0.000s  | 0.0%|
|iso_brn401.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn402.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn403.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn404.smt2                                                                             |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|iso_brn405.smt2                                                                             |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|iso_brn406.smt2                                                                             |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|iso_brn407.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn408.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|iso_brn410.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn412.smt2                                                                             |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|iso_brn417.smt2                                                                             |  19.933s  |  19.933s  |   0.000s  | 0.0%|
|iso_brn418.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn420.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn421.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn422.smt2                                                                             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|iso_brn423.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn427.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn428.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn429.smt2                                                                             |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|iso_brn430.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn432.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn433.smt2                                                                             |  19.924s  |  19.924s  |   0.000s  | 0.0%|
|iso_brn434.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|iso_brn435.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn436.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn437.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn438.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn441.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn442.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn444.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn447.smt2                                                                             |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|iso_brn448.smt2                                                                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|iso_brn450.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn451.smt2                                                                             |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|iso_brn453.smt2                                                                             |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|iso_brn455.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn456.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn459.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn462.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn464.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn466.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn468.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn469.smt2                                                                             |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|iso_brn470.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn472.smt2                                                                             |  19.912s  |  19.912s  |   0.000s  | 0.0%|
|iso_brn473.smt2                                                                             |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|iso_brn475.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn476.smt2                                                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|iso_brn478.smt2                                                                             |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|iso_brn480.smt2                                                                             |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|iso_brn481.smt2                                                                             |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|iso_brn482.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn487.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn488.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn490.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn494.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn496.smt2                                                                             |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|iso_brn497.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn498.smt2                                                                             |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|iso_brn499.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn501.smt2                                                                             |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|iso_brn503.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn508.smt2                                                                             |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|iso_brn510.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|iso_brn511.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|iso_brn512.smt2                                                                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|iso_brn513.smt2                                                                             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|iso_brn515.smt2                                                                             |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|iso_brn521.smt2                                                                             |   1.665s  |   1.665s  |   0.000s  | 0.0%|
|iso_brn522.smt2                                                                             |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|iso_brn523.smt2                                                                             |   1.102s  |   1.102s  |   0.000s  | 0.0%|
|iso_brn525.smt2                                                                             |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|iso_brn527.smt2                                                                             |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|iso_brn530.smt2                                                                             |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|iso_brn533.smt2                                                                             |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|iso_brn534.smt2                                                                             |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|iso_brn535.smt2                                                                             |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|iso_brn536.smt2                                                                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|iso_brn537.smt2                                                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|iso_brn538.smt2                                                                             |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|iso_brn543.smt2                                                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|iso_brn544.smt2                                                                             |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|iso_brn547.smt2                                                                             |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|iso_brn548.smt2                                                                             |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|iso_brn553.smt2                                                                             |   1.515s  |   1.515s  |   0.000s  | 0.0%|
|iso_brn557.smt2                                                                             |   0.804s  |   0.804s  |   0.000s  | 0.0%|
|iso_brn560.smt2                                                                             |   0.515s  |   0.515s  |   0.000s  | 0.0%|
|iso_brn561.smt2                                                                             |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|iso_brn564.smt2                                                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|iso_brn565.smt2                                                                             |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|iso_brn570.smt2                                                                             |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|iso_brn573.smt2                                                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|iso_brn574.smt2                                                                             |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|iso_brn575.smt2                                                                             |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|iso_brn576.smt2                                                                             |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|iso_brn580.smt2                                                                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|iso_brn581.smt2                                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|iso_brn582.smt2                                                                             |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|iso_brn585.smt2                                                                             |   0.590s  |   0.590s  |   0.000s  | 0.0%|
|iso_brn587.smt2                                                                             |   0.627s  |   0.627s  |   0.000s  | 0.0%|
|iso_brn591.smt2                                                                             |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|iso_brn593.smt2                                                                             |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|iso_brn597.smt2                                                                             |   1.325s  |   1.325s  |   0.000s  | 0.0%|
|iso_brn598.smt2                                                                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|iso_brn599.smt2                                                                             |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|iso_brn601.smt2                                                                             |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|iso_brn602.smt2                                                                             |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|iso_brn603.smt2                                                                             |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|iso_brn607.smt2                                                                             |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|iso_brn609.smt2                                                                             |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|iso_brn611.smt2                                                                             |   1.208s  |   1.208s  |   0.000s  | 0.0%|
|iso_brn614.smt2                                                                             |   0.558s  |   0.558s  |   0.000s  | 0.0%|
|iso_brn617.smt2                                                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|iso_brn618.smt2                                                                             |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|iso_brn619.smt2                                                                             |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|iso_brn620.smt2                                                                             |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|iso_brn624.smt2                                                                             |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|iso_brn625.smt2                                                                             |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|iso_brn631.smt2                                                                             |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|iso_brn632.smt2                                                                             |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|iso_brn633.smt2                                                                             |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|iso_brn636.smt2                                                                             |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|iso_brn637.smt2                                                                             |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|iso_brn639.smt2                                                                             |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|iso_brn643.smt2                                                                             |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|iso_brn645.smt2                                                                             |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|iso_brn647.smt2                                                                             |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|iso_brn648.smt2                                                                             |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|iso_brn649.smt2                                                                             |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|iso_brn652.smt2                                                                             |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|iso_brn653.smt2                                                                             |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|iso_brn654.smt2                                                                             |   0.473s  |   0.473s  |   0.000s  | 0.0%|
|iso_brn657.smt2                                                                             |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|iso_brn659.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|iso_brn669.smt2                                                                             |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|iso_brn671.smt2                                                                             |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|iso_brn672.smt2                                                                             |   0.772s  |   0.772s  |   0.000s  | 0.0%|
|iso_brn676.smt2                                                                             |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|iso_brn678.smt2                                                                             |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|iso_brn680.smt2                                                                             |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|iso_brn681.smt2                                                                             |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|iso_brn682.smt2                                                                             |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|iso_brn685.smt2                                                                             |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|iso_brn686.smt2                                                                             |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|iso_brn688.smt2                                                                             |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|iso_brn692.smt2                                                                             |   0.724s  |   0.724s  |   0.000s  | 0.0%|
|iso_brn694.smt2                                                                             |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|iso_brn696.smt2                                                                             |   0.661s  |   0.661s  |   0.000s  | 0.0%|
|iso_brn700.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn705.smt2                                                                             |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|iso_brn707.smt2                                                                             |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|iso_brn708.smt2                                                                             |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|iso_brn709.smt2                                                                             |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|iso_brn710.smt2                                                                             |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|iso_brn712.smt2                                                                             |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|iso_brn713.smt2                                                                             |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|iso_brn714.smt2                                                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|iso_brn715.smt2                                                                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|iso_brn716.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|iso_brn719.smt2                                                                             |   1.284s  |   1.284s  |   0.000s  | 0.0%|
|iso_brn721.smt2                                                                             |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|iso_brn722.smt2                                                                             |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|iso_brn724.smt2                                                                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|iso_brn727.smt2                                                                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|iso_brn728.smt2                                                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|iso_brn729.smt2                                                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|iso_brn730.smt2                                                                             |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|iso_brn731.smt2                                                                             |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|iso_brn732.smt2                                                                             |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|iso_brn734.smt2                                                                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|iso_brn736.smt2                                                                             |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|iso_brn738.smt2                                                                             |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|iso_brn742.smt2                                                                             |   0.628s  |   0.628s  |   0.000s  | 0.0%|
|iso_brn747.smt2                                                                             |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|iso_brn752.smt2                                                                             |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|iso_brn753.smt2                                                                             |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|iso_brn754.smt2                                                                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|iso_brn759.smt2                                                                             |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|iso_brn761.smt2                                                                             |   0.942s  |   0.942s  |   0.000s  | 0.0%|
|iso_brn766.smt2                                                                             |   0.937s  |   0.937s  |   0.000s  | 0.0%|
|iso_brn768.smt2                                                                             |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|iso_brn770.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|iso_brn771.smt2                                                                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|iso_brn777.smt2                                                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|iso_brn778.smt2                                                                             |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|iso_brn784.smt2                                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|iso_brn786.smt2                                                                             |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|iso_brn792.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn795.smt2                                                                             |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|iso_brn800.smt2                                                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|iso_brn803.smt2                                                                             |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|iso_brn806.smt2                                                                             |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|iso_brn809.smt2                                                                             |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|iso_brn814.smt2                                                                             |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|iso_brn815.smt2                                                                             |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|iso_brn818.smt2                                                                             |   0.600s  |   0.600s  |   0.000s  | 0.0%|
|iso_brn821.smt2                                                                             |   0.921s  |   0.921s  |   0.000s  | 0.0%|
|iso_brn823.smt2                                                                             |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|iso_brn824.smt2                                                                             |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|iso_brn827.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|iso_brn828.smt2                                                                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|iso_brn835.smt2                                                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|iso_brn836.smt2                                                                             |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|iso_brn837.smt2                                                                             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|iso_brn838.smt2                                                                             |   0.785s  |   0.785s  |   0.000s  | 0.0%|
|iso_brn840.smt2                                                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|iso_brn842.smt2                                                                             |   2.203s  |   2.203s  |   0.000s  | 0.0%|
|iso_brn846.smt2                                                                             |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|iso_brn847.smt2                                                                             |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|iso_brn848.smt2                                                                             |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|iso_brn851.smt2                                                                             |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|iso_brn853.smt2                                                                             |   1.098s  |   1.098s  |   0.000s  | 0.0%|
|iso_brn856.smt2                                                                             |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|iso_brn861.smt2                                                                             |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|iso_brn862.smt2                                                                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|iso_brn863.smt2                                                                             |   0.568s  |   0.568s  |   0.000s  | 0.0%|
|iso_brn867.smt2                                                                             |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|iso_brn868.smt2                                                                             |   0.721s  |   0.721s  |   0.000s  | 0.0%|
|iso_brn871.smt2                                                                             |   1.941s  |   1.941s  |   0.000s  | 0.0%|
|iso_brn872.smt2                                                                             |   0.919s  |   0.919s  |   0.000s  | 0.0%|
|iso_brn873.smt2                                                                             |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|iso_brn874.smt2                                                                             |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|iso_brn875.smt2                                                                             |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|iso_brn876.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn878.smt2                                                                             |  19.927s  |  19.927s  |   0.000s  | 0.0%|
|iso_brn881.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|iso_brn884.smt2                                                                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|iso_brn885.smt2                                                                             |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|iso_brn886.smt2                                                                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|iso_brn888.smt2                                                                             |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|iso_brn891.smt2                                                                             |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|iso_brn892.smt2                                                                             |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|iso_brn893.smt2                                                                             |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|iso_brn895.smt2                                                                             |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|iso_brn896.smt2                                                                             |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|iso_brn897.smt2                                                                             |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|iso_brn898.smt2                                                                             |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|iso_brn899.smt2                                                                             |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|iso_brn900.smt2                                                                             |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|iso_brn901.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|iso_brn902.smt2                                                                             |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|iso_brn903.smt2                                                                             |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|iso_brn904.smt2                                                                             |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|iso_brn905.smt2                                                                             |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|iso_brn908.smt2                                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|iso_brn910.smt2                                                                             |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|iso_brn913.smt2                                                                             |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|iso_brn914.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|iso_brn915.smt2                                                                             |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|iso_brn916.smt2                                                                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|iso_brn918.smt2                                                                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|iso_brn919.smt2                                                                             |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|iso_brn920.smt2                                                                             |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|iso_brn926.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn927.smt2                                                                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|iso_brn930.smt2                                                                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|iso_brn932.smt2                                                                             |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|iso_brn933.smt2                                                                             |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|iso_brn935.smt2                                                                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|iso_brn936.smt2                                                                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|iso_brn937.smt2                                                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|iso_brn938.smt2                                                                             |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|iso_brn943.smt2                                                                             |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|iso_brn946.smt2                                                                             |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|iso_brn949.smt2                                                                             |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|iso_brn950.smt2                                                                             |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|iso_brn953.smt2                                                                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|iso_brn956.smt2                                                                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|iso_brn957.smt2                                                                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|iso_brn958.smt2                                                                             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|iso_brn959.smt2                                                                             |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|iso_brn961.smt2                                                                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|iso_brn962.smt2                                                                             |   0.562s  |   0.562s  |   0.000s  | 0.0%|
|iso_brn963.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|iso_brn964.smt2                                                                             |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|iso_brn966.smt2                                                                             |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|iso_brn968.smt2                                                                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|iso_brn973.smt2                                                                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|iso_brn974.smt2                                                                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|iso_brn978.smt2                                                                             |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|iso_brn979.smt2                                                                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|iso_brn981.smt2                                                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|iso_brn982.smt2                                                                             |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|iso_brn990.smt2                                                                             |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|iso_brn991.smt2                                                                             |   0.601s  |   0.601s  |   0.000s  | 0.0%|
|iso_brn994.smt2                                                                             |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|iso_brn995.smt2                                                                             |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|iso_brn997.smt2                                                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|iso_brn998.smt2                                                                             |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|iso_brn_repgen001.smt2                                                                      |   1.288s  |   1.288s  |   0.000s  | 0.0%|
|iso_brn_repgen002.smt2                                                                      |   5.906s  |   5.906s  |   0.000s  | 0.0%|
|iso_brn_repgen004.smt2                                                                      |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn_repgen006.smt2                                                                      |   5.335s  |   5.335s  |   0.000s  | 0.0%|
|iso_brn_repgen007.smt2                                                                      |   8.355s  |   8.355s  |   0.000s  | 0.0%|
|iso_brn_repgen009.smt2                                                                      |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|iso_brn_repgen010.smt2                                                                      |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn_repgen011.smt2                                                                      |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn_repgen012.smt2                                                                      |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|iso_brn_repgen013.smt2                                                                      |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|iso_brn_repgen014.smt2                                                                      |  10.496s  |  10.496s  |   0.000s  | 0.0%|
|iso_brn_repgen015.smt2                                                                      |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn_repgen016.smt2                                                                      |  17.880s  |  17.880s  |   0.000s  | 0.0%|
|iso_brn_repgen018.smt2                                                                      |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn_repgen019.smt2                                                                      |   5.179s  |   5.179s  |   0.000s  | 0.0%|
|iso_brn_repgen020.smt2                                                                      |   5.989s  |   5.989s  |   0.000s  | 0.0%|
|iso_brn_repgen021.smt2                                                                      |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn_repgen022.smt2                                                                      |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|iso_brn_repgen023.smt2                                                                      |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|iso_brn_repgen024.smt2                                                                      |  13.901s  |  13.901s  |   0.000s  | 0.0%|
|iso_brn_repgen025.smt2                                                                      |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|iso_brn_repgen026.smt2                                                                      |   7.498s  |   7.498s  |   0.000s  | 0.0%|
|iso_brn_repgen028.smt2                                                                      |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|iso_brn_repgen029.smt2                                                                      |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn_repgen031.smt2                                                                      |   6.851s  |   6.851s  |   0.000s  | 0.0%|
|iso_brn_repgen033.smt2                                                                      |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|iso_brn_repgen034.smt2                                                                      |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|iso_brn_repgen035.smt2                                                                      |  16.576s  |  16.576s  |   0.000s  | 0.0%|
|iso_brn_repgen036.smt2                                                                      |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn_repgen037.smt2                                                                      |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn_repgen041.smt2                                                                      |   4.986s  |   4.986s  |   0.000s  | 0.0%|
|iso_brn_repgen043.smt2                                                                      |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn_repgen044.smt2                                                                      |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn_repgen045.smt2                                                                      |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|iso_brn_repgen046.smt2                                                                      |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|iso_brn_repgen048.smt2                                                                      |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn_repgen049.smt2                                                                      |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|iso_brn_repgen050.smt2                                                                      |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|iso_brn_repgen051.smt2                                                                      |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn_repgen052.smt2                                                                      |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|iso_brn_repgen053.smt2                                                                      |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk001.smt2                                                                   |   5.557s  |   5.557s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk002.smt2                                                                   |   4.989s  |   4.989s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk003.smt2                                                                   |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk004.smt2                                                                   |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk008.smt2                                                                   |  11.197s  |  11.197s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk009.smt2                                                                   |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk010.smt2                                                                   |  15.520s  |  15.520s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk011.smt2                                                                   |  19.527s  |  19.527s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk012.smt2                                                                   |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk013.smt2                                                                   |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk014.smt2                                                                   |  11.986s  |  11.986s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk015.smt2                                                                   |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk016.smt2                                                                   |  10.756s  |  10.756s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk017.smt2                                                                   |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk018.smt2                                                                   |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk020.smt2                                                                   |   7.267s  |   7.267s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk023.smt2                                                                   |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk028.smt2                                                                   |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk029.smt2                                                                   |  19.900s  |  19.900s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk032.smt2                                                                   |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk033.smt2                                                                   |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk034.smt2                                                                   |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk036.smt2                                                                   |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk038.smt2                                                                   |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk039.smt2                                                                   |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk040.smt2                                                                   |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk041.smt2                                                                   |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk043.smt2                                                                   |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk044.smt2                                                                   |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk045.smt2                                                                   |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk046.smt2                                                                   |  13.541s  |  13.541s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk047.smt2                                                                   |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk048.smt2                                                                   |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk051.smt2                                                                   |  17.263s  |  17.263s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk052.smt2                                                                   |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk053.smt2                                                                   |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|iso_brn_repgen_sk055.smt2                                                                   |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|iso_brn_sk001.smt2                                                                          |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|iso_brn_sk002.smt2                                                                          |   0.548s  |   0.548s  |   0.000s  | 0.0%|
|iso_brn_sk003.smt2                                                                          |   0.515s  |   0.515s  |   0.000s  | 0.0%|
|iso_brn_sk005.smt2                                                                          |   1.197s  |   1.197s  |   0.000s  | 0.0%|
|iso_brn_sk007.smt2                                                                          |   0.731s  |   0.731s  |   0.000s  | 0.0%|
|iso_brn_sk008.smt2                                                                          |   1.646s  |   1.646s  |   0.000s  | 0.0%|
|iso_brn_sk010.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn_sk011.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn_sk013.smt2                                                                          |   3.728s  |   3.728s  |   0.000s  | 0.0%|
|iso_brn_sk014.smt2                                                                          |   1.679s  |   1.679s  |   0.000s  | 0.0%|
|iso_brn_sk016.smt2                                                                          |   1.627s  |   1.627s  |   0.000s  | 0.0%|
|iso_brn_sk017.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|iso_brn_sk024.smt2                                                                          |   1.088s  |   1.088s  |   0.000s  | 0.0%|
|iso_brn_sk029.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|iso_brn_sk030.smt2                                                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|iso_brn_sk041.smt2                                                                          |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|iso_brn_sk045.smt2                                                                          |   7.649s  |   7.649s  |   0.000s  | 0.0%|
|iso_brn_sk046.smt2                                                                          |   1.611s  |   1.611s  |   0.000s  | 0.0%|
|iso_brn_sk048.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|iso_brn_sk049.smt2                                                                          |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|iso_brn_sk053.smt2                                                                          |   0.985s  |   0.985s  |   0.000s  | 0.0%|
|iso_brn_sk055.smt2                                                                          |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|smt2831655880469397696.smt2                                                                 |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|smt3232867547761696161.smt2                                                                 |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|smt3248576982810563470.smt2                                                                 |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|smt3508124013603727984.smt2                                                                 |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|smt3910673230463462036.smt2                                                                 |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|smt4027072204816894856.smt2                                                                 |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|smt4480564921249140261.smt2                                                                 |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|smt6109211130895037835.smt2                                                                 |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|smt6377531776677660648.smt2                                                                 |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|smt834303034702425531.smt2                                                                  |   0.004s  |   0.004s  |   0.000s  | 0.0%|
|smt862177804180920815.smt2                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
</details>
