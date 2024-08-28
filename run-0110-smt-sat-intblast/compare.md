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
Job tag: smt-sat-intblast
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 85d3041a808b64c9d8491cd1084bdd0431618ece
Z3 branch: master
Z3 options: "-T:20 -v:2 -st smt.bv.solver=2 sat.smt=true tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt-sls)" model_validate=true"
Z3 inputs: inputs/alive-arm-tv-smt-benchmarks
Z3 commit message: avoid platform non-reproducibility due to argument evaluation ordering

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sat-intblast
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 85d3041a808b64c9d8491cd1084bdd0431618ece
Z3 branch: master
Z3 options: "-T:20 -v:2 -st smt.bv.solver=2 sat.smt=true tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt-sls)" model_validate=true"
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
|COOTIM7Cm0pX.smt2                                                                          |   0.018s |18.204MiB|
|08yBgkc5Y0dJ.smt2                                                                          |   0.018s |18.024MiB|
|09pDui3xULjl.smt2                                                                          |   0.017s |18.08MiB|
|2CrQZxbXNkYi.smt2                                                                          |   0.017s |17.996MiB|
|07nVoqWtQ3Gm.smt2                                                                          |   0.017s |18.136MiB|
|08esiXFLPnnn.smt2                                                                          |   0.017s |18.168MiB|
|1DGx3BoWdlCg.smt2                                                                          |   0.016s |18.192MiB|
|3XEBiGlg9ea2.smt2                                                                          |   0.016s |18.052MiB|
|3W3FExxeiS3z.smt2                                                                          |   0.016s |18.116MiB|
|07MoYiBt3TDM.smt2                                                                          |   0.016s |18.188MiB|
|3e8H3oplyqdk.smt2                                                                          |   0.016s |17.996MiB|
|2PGu55IPNjrw.smt2                                                                          |   0.016s |18.188MiB|
|0SmTL0qhWXKB.smt2                                                                          |   0.016s |18.144MiB|
|08lBkwAD9EDX.smt2                                                                          |   0.016s |18.024MiB|
|0TR0XhriO5Kz.smt2                                                                          |   0.015s |18.196MiB|
|prTagF8g3sDX.smt2                                                                          |   0.015s |17.996MiB|
|fT3gfpsvV09q.smt2                                                                          |   0.015s |18.056MiB|
|2fgsx5hwingD.smt2                                                                          |   0.015s |18.212MiB|
|1ddyk8qw0Ly6.smt2                                                                          |   0.015s |18.204MiB|
|078LLiuFCwCP.smt2                                                                          |   0.015s |18.164MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|COOTIM7Cm0pX.smt2                                                                          |   0.018s |18.204MiB|
|08yBgkc5Y0dJ.smt2                                                                          |   0.018s |18.024MiB|
|09pDui3xULjl.smt2                                                                          |   0.017s |18.08MiB|
|2CrQZxbXNkYi.smt2                                                                          |   0.017s |17.996MiB|
|07nVoqWtQ3Gm.smt2                                                                          |   0.017s |18.136MiB|
|08esiXFLPnnn.smt2                                                                          |   0.017s |18.168MiB|
|1DGx3BoWdlCg.smt2                                                                          |   0.016s |18.192MiB|
|3XEBiGlg9ea2.smt2                                                                          |   0.016s |18.052MiB|
|3W3FExxeiS3z.smt2                                                                          |   0.016s |18.116MiB|
|07MoYiBt3TDM.smt2                                                                          |   0.016s |18.188MiB|
|3e8H3oplyqdk.smt2                                                                          |   0.016s |17.996MiB|
|2PGu55IPNjrw.smt2                                                                          |   0.016s |18.188MiB|
|0SmTL0qhWXKB.smt2                                                                          |   0.016s |18.144MiB|
|08lBkwAD9EDX.smt2                                                                          |   0.016s |18.024MiB|
|0TR0XhriO5Kz.smt2                                                                          |   0.015s |18.196MiB|
|prTagF8g3sDX.smt2                                                                          |   0.015s |17.996MiB|
|fT3gfpsvV09q.smt2                                                                          |   0.015s |18.056MiB|
|2fgsx5hwingD.smt2                                                                          |   0.015s |18.212MiB|
|1ddyk8qw0Ly6.smt2                                                                          |   0.015s |18.204MiB|
|078LLiuFCwCP.smt2                                                                          |   0.015s |18.164MiB|
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
|SelU37jGL7BS.smt2                                                                          |   0.006s |19.008MiB|
|PbM2F8Gjh9At.smt2                                                                          |   0.007s |18.948MiB|
|r94ebBg94WXD.smt2                                                                          |   0.004s |18.948MiB|
|icvzDBwFlYYU.smt2                                                                          |   0.004s |18.892MiB|
|ho7A6E8Thhql.smt2                                                                          |   0.005s |18.872MiB|
|Rr7d5DM8oLqc.smt2                                                                          |   0.005s |18.84MiB|
|KOjKC86tcpzk.smt2                                                                          |   0.005s |18.828MiB|
|FM1YciVoEgpS.smt2                                                                          |   0.007s |18.824MiB|
|ounUNc4OzMS5.smt2                                                                          |   0.005s |18.8MiB|
|gOv4PWmbqhSq.smt2                                                                          |   0.004s |18.792MiB|
|e61PvX2ynbNo.smt2                                                                          |   0.009s |18.788MiB|
|uQDpZda7EZmY.smt2                                                                          |   0.005s |18.788MiB|
|s6gEGlcmoma0.smt2                                                                          |   0.006s |18.784MiB|
|huKIJvREa9hP.smt2                                                                          |   0.004s |18.78MiB|
|PoptgJWYXpMd.smt2                                                                          |   0.006s |18.776MiB|
|FsX6uVWhNJEL.smt2                                                                          |   0.008s |18.772MiB|
|SzUBb6t8sgGU.smt2                                                                          |   0.005s |18.772MiB|
|hen1HZHyMqVz.smt2                                                                          |   0.007s |18.768MiB|
|u89cLeFzTo0H.smt2                                                                          |   0.005s |18.764MiB|
|uNVCvTHlRwfI.smt2                                                                          |   0.005s |18.76MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|SelU37jGL7BS.smt2                                                                          |   0.006s |19.008MiB|
|PbM2F8Gjh9At.smt2                                                                          |   0.007s |18.948MiB|
|r94ebBg94WXD.smt2                                                                          |   0.004s |18.948MiB|
|icvzDBwFlYYU.smt2                                                                          |   0.004s |18.892MiB|
|ho7A6E8Thhql.smt2                                                                          |   0.005s |18.872MiB|
|Rr7d5DM8oLqc.smt2                                                                          |   0.005s |18.84MiB|
|KOjKC86tcpzk.smt2                                                                          |   0.005s |18.828MiB|
|FM1YciVoEgpS.smt2                                                                          |   0.007s |18.824MiB|
|ounUNc4OzMS5.smt2                                                                          |   0.005s |18.8MiB|
|gOv4PWmbqhSq.smt2                                                                          |   0.004s |18.792MiB|
|e61PvX2ynbNo.smt2                                                                          |   0.009s |18.788MiB|
|uQDpZda7EZmY.smt2                                                                          |   0.005s |18.788MiB|
|s6gEGlcmoma0.smt2                                                                          |   0.006s |18.784MiB|
|huKIJvREa9hP.smt2                                                                          |   0.004s |18.78MiB|
|PoptgJWYXpMd.smt2                                                                          |   0.006s |18.776MiB|
|FsX6uVWhNJEL.smt2                                                                          |   0.008s |18.772MiB|
|SzUBb6t8sgGU.smt2                                                                          |   0.005s |18.772MiB|
|hen1HZHyMqVz.smt2                                                                          |   0.007s |18.768MiB|
|u89cLeFzTo0H.smt2                                                                          |   0.005s |18.764MiB|
|uNVCvTHlRwfI.smt2                                                                          |   0.005s |18.76MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
