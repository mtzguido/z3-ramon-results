Comparing data and data


# SUMMARY
- LHS tests = 191
- RHS tests = 191
- LHS success = 191  (100.0%)
- RHS success = 191  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: quotient_pairs=true inputs/certora2
Job tag: fix_in_qp_true_certora2
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 186ef6a0cd3f0fc8821795515994089cfc4e65db
Z3 branch: modgb
Z3 options: "-T:200 smt.arith.nl.grobner_quotient_pairs=true"
Z3 inputs: inputs/certora2
Z3 commit message: fix unsound grobner-quotient-pair lemma: skip lc with non-integral coefficients

pdd::reduce() can introduce non-integral coefficients via leading-term
division. The quotient lemma reasoning assumed lc_comb = lc_i - lc_j
was always integer-valued, which failed when lc had non-integral coefficients.
Filter out such entries when building var_to_facts.

Co-authored-by: Copilot <223556219+Copilot@users.noreply.github.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: quotient_pairs=true inputs/certora2
Job tag: fix_in_qp_true_certora2
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 186ef6a0cd3f0fc8821795515994089cfc4e65db
Z3 branch: modgb
Z3 options: "-T:200 smt.arith.nl.grobner_quotient_pairs=true"
Z3 inputs: inputs/certora2
Z3 commit message: fix unsound grobner-quotient-pair lemma: skip lc with non-integral coefficients

pdd::reduce() can introduce non-integral coefficients via leading-term
division. The quotient lemma reasoning assumed lc_comb = lc_i - lc_j
was always integer-valued, which failed when lc had non-integral coefficients.
Filter out such entries when building var_to_facts.

Co-authored-by: Copilot <223556219+Copilot@users.noreply.github.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.911s  |   0.911s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |   2.379s  |   2.379s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               | 200.022s  | 200.022s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.018s  | 200.018s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.215s  |   0.215s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.911s  |   0.911s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |   2.379s  |   2.379s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               | 200.022s  | 200.022s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.018s  | 200.018s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.215s  |   0.215s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.911s  |   0.911s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |   2.379s  |   2.379s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               | 200.022s  | 200.022s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.018s  | 200.018s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.215s  |   0.215s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.911s  |   0.911s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |   2.379s  |   2.379s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               | 200.022s  | 200.022s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.018s  | 200.018s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.215s  |   0.215s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0188.smt2                                                                              | 200.068s |565.0MiB|
|auk-0151.smt2                                                                              | 200.025s |59.812MiB|
|auk-0086.smt2                                                                              | 200.025s |118.0MiB|
|auk-0187.smt2                                                                              | 200.025s |96.064MiB|
|auk-0001.smt2                                                                              | 200.023s |46.764MiB|
|auk-0092.smt2                                                                              | 200.023s |113.0MiB|
|auk-0011.smt2                                                                              | 200.022s |74.644MiB|
|auk-0085.smt2                                                                              | 200.020s |103.0MiB|
|auk-0185.smt2                                                                              | 200.020s |63.54MiB|
|auk-0147.smt2                                                                              | 200.020s |71.76MiB|
|auk-0015.smt2                                                                              | 200.018s |86.472MiB|
|auk-0189.smt2                                                                              | 200.018s |79.492MiB|
|auk-0191.smt2                                                                              | 200.012s |39.736MiB|
|auk-0087.smt2                                                                              | 104.517s |84.236MiB|
|auk-0081.smt2                                                                              |  73.859s |36.472MiB|
|auk-0184.smt2                                                                              |  42.855s |50.02MiB|
|auk-0137.smt2                                                                              |  35.198s |43.112MiB|
|auk-0088.smt2                                                                              |  33.426s |92.724MiB|
|auk-0099.smt2                                                                              |  31.425s |198.0MiB|
|auk-0089.smt2                                                                              |  30.347s |69.4MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0188.smt2                                                                              | 200.068s |565.0MiB|
|auk-0151.smt2                                                                              | 200.025s |59.812MiB|
|auk-0086.smt2                                                                              | 200.025s |118.0MiB|
|auk-0187.smt2                                                                              | 200.025s |96.064MiB|
|auk-0001.smt2                                                                              | 200.023s |46.764MiB|
|auk-0092.smt2                                                                              | 200.023s |113.0MiB|
|auk-0011.smt2                                                                              | 200.022s |74.644MiB|
|auk-0085.smt2                                                                              | 200.020s |103.0MiB|
|auk-0185.smt2                                                                              | 200.020s |63.54MiB|
|auk-0147.smt2                                                                              | 200.020s |71.76MiB|
|auk-0015.smt2                                                                              | 200.018s |86.472MiB|
|auk-0189.smt2                                                                              | 200.018s |79.492MiB|
|auk-0191.smt2                                                                              | 200.012s |39.736MiB|
|auk-0087.smt2                                                                              | 104.517s |84.236MiB|
|auk-0081.smt2                                                                              |  73.859s |36.472MiB|
|auk-0184.smt2                                                                              |  42.855s |50.02MiB|
|auk-0137.smt2                                                                              |  35.198s |43.112MiB|
|auk-0088.smt2                                                                              |  33.426s |92.724MiB|
|auk-0099.smt2                                                                              |  31.425s |198.0MiB|
|auk-0089.smt2                                                                              |  30.347s |69.4MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |46.764MiB|46.764MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |34.872MiB|34.872MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |28.116MiB|28.116MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |35.66MiB|35.66MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |33.244MiB|33.244MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |36.54MiB|36.54MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |38.016MiB|38.016MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |28.232MiB|28.232MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |20.372MiB|20.372MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |32.964MiB|32.964MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |74.644MiB|74.644MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.24MiB|20.24MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |28.236MiB|28.236MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |28.284MiB|28.284MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |86.472MiB|86.472MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.212MiB|25.212MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |27.196MiB|27.196MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |26.212MiB|26.212MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |26.16MiB|26.16MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.796MiB|25.796MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |46.764MiB|46.764MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |34.872MiB|34.872MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |28.116MiB|28.116MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |35.66MiB|35.66MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |33.244MiB|33.244MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |36.54MiB|36.54MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |38.016MiB|38.016MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |28.232MiB|28.232MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |20.372MiB|20.372MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |32.964MiB|32.964MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |74.644MiB|74.644MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.24MiB|20.24MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |28.236MiB|28.236MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |28.284MiB|28.284MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |86.472MiB|86.472MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.212MiB|25.212MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |27.196MiB|27.196MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |26.212MiB|26.212MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |26.16MiB|26.16MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.796MiB|25.796MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |46.764MiB|46.764MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |34.872MiB|34.872MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |28.116MiB|28.116MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |35.66MiB|35.66MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |33.244MiB|33.244MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |36.54MiB|36.54MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |38.016MiB|38.016MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |28.232MiB|28.232MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |20.372MiB|20.372MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |32.964MiB|32.964MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |74.644MiB|74.644MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.24MiB|20.24MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |28.236MiB|28.236MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |28.284MiB|28.284MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |86.472MiB|86.472MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.212MiB|25.212MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |27.196MiB|27.196MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |26.212MiB|26.212MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |26.16MiB|26.16MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.796MiB|25.796MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |46.764MiB|46.764MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |34.872MiB|34.872MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |28.116MiB|28.116MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |35.66MiB|35.66MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |33.244MiB|33.244MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |36.54MiB|36.54MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |38.016MiB|38.016MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |28.232MiB|28.232MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |20.372MiB|20.372MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |32.964MiB|32.964MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |74.644MiB|74.644MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.24MiB|20.24MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |28.236MiB|28.236MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |28.284MiB|28.284MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |86.472MiB|86.472MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.212MiB|25.212MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |27.196MiB|27.196MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |26.212MiB|26.212MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |26.16MiB|26.16MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.796MiB|25.796MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0188.smt2                                                                              | 200.068s |565.0MiB|
|auk-0099.smt2                                                                              |  31.425s |198.0MiB|
|auk-0098.smt2                                                                              |  14.966s |169.0MiB|
|auk-0086.smt2                                                                              | 200.025s |118.0MiB|
|auk-0092.smt2                                                                              | 200.023s |113.0MiB|
|auk-0085.smt2                                                                              | 200.020s |103.0MiB|
|auk-0082.smt2                                                                              |   2.870s |99.0MiB|
|auk-0083.smt2                                                                              |   2.825s |99.0MiB|
|auk-0187.smt2                                                                              | 200.025s |96.064MiB|
|auk-0131.smt2                                                                              |   1.733s |92.82MiB|
|auk-0088.smt2                                                                              |  33.426s |92.724MiB|
|auk-0015.smt2                                                                              | 200.018s |86.472MiB|
|auk-0087.smt2                                                                              | 104.517s |84.236MiB|
|auk-0189.smt2                                                                              | 200.018s |79.492MiB|
|auk-0011.smt2                                                                              | 200.022s |74.644MiB|
|auk-0147.smt2                                                                              | 200.020s |71.76MiB|
|auk-0186.smt2                                                                              |  11.514s |69.504MiB|
|auk-0089.smt2                                                                              |  30.347s |69.4MiB|
|auk-0181.smt2                                                                              |  10.843s |67.524MiB|
|auk-0185.smt2                                                                              | 200.020s |63.54MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0188.smt2                                                                              | 200.068s |565.0MiB|
|auk-0099.smt2                                                                              |  31.425s |198.0MiB|
|auk-0098.smt2                                                                              |  14.966s |169.0MiB|
|auk-0086.smt2                                                                              | 200.025s |118.0MiB|
|auk-0092.smt2                                                                              | 200.023s |113.0MiB|
|auk-0085.smt2                                                                              | 200.020s |103.0MiB|
|auk-0082.smt2                                                                              |   2.870s |99.0MiB|
|auk-0083.smt2                                                                              |   2.825s |99.0MiB|
|auk-0187.smt2                                                                              | 200.025s |96.064MiB|
|auk-0131.smt2                                                                              |   1.733s |92.82MiB|
|auk-0088.smt2                                                                              |  33.426s |92.724MiB|
|auk-0015.smt2                                                                              | 200.018s |86.472MiB|
|auk-0087.smt2                                                                              | 104.517s |84.236MiB|
|auk-0189.smt2                                                                              | 200.018s |79.492MiB|
|auk-0011.smt2                                                                              | 200.022s |74.644MiB|
|auk-0147.smt2                                                                              | 200.020s |71.76MiB|
|auk-0186.smt2                                                                              |  11.514s |69.504MiB|
|auk-0089.smt2                                                                              |  30.347s |69.4MiB|
|auk-0181.smt2                                                                              |  10.843s |67.524MiB|
|auk-0185.smt2                                                                              | 200.020s |63.54MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.911s  |   0.911s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |   2.379s  |   2.379s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               | 200.022s  | 200.022s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.018s  | 200.018s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|auk-0021.smt2                                                                               |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|auk-0022.smt2                                                                               |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|auk-0023.smt2                                                                               |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|auk-0024.smt2                                                                               |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|auk-0025.smt2                                                                               |   1.640s  |   1.640s  |   0.000s  | 0.0%|
|auk-0026.smt2                                                                               |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|auk-0027.smt2                                                                               |   2.225s  |   2.225s  |   0.000s  | 0.0%|
|auk-0028.smt2                                                                               |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|auk-0029.smt2                                                                               |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|auk-0030.smt2                                                                               |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|auk-0031.smt2                                                                               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|auk-0032.smt2                                                                               |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|auk-0033.smt2                                                                               |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|auk-0034.smt2                                                                               |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|auk-0035.smt2                                                                               |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|auk-0036.smt2                                                                               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|auk-0037.smt2                                                                               |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|auk-0038.smt2                                                                               |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|auk-0039.smt2                                                                               |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|auk-0040.smt2                                                                               |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|auk-0041.smt2                                                                               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|auk-0042.smt2                                                                               |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|auk-0043.smt2                                                                               |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|auk-0044.smt2                                                                               |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|auk-0045.smt2                                                                               |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|auk-0046.smt2                                                                               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|auk-0047.smt2                                                                               |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|auk-0048.smt2                                                                               |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|auk-0049.smt2                                                                               |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|auk-0050.smt2                                                                               |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|auk-0051.smt2                                                                               |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|auk-0052.smt2                                                                               |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|auk-0053.smt2                                                                               |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|auk-0054.smt2                                                                               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|auk-0055.smt2                                                                               |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|auk-0056.smt2                                                                               |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|auk-0057.smt2                                                                               |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|auk-0058.smt2                                                                               |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|auk-0059.smt2                                                                               |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|auk-0060.smt2                                                                               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|auk-0061.smt2                                                                               |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|auk-0062.smt2                                                                               |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|auk-0063.smt2                                                                               |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|auk-0064.smt2                                                                               |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|auk-0065.smt2                                                                               |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|auk-0066.smt2                                                                               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|auk-0067.smt2                                                                               |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|auk-0068.smt2                                                                               |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|auk-0069.smt2                                                                               |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|auk-0070.smt2                                                                               |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|auk-0071.smt2                                                                               |   1.160s  |   1.160s  |   0.000s  | 0.0%|
|auk-0072.smt2                                                                               |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|auk-0073.smt2                                                                               |   1.174s  |   1.174s  |   0.000s  | 0.0%|
|auk-0074.smt2                                                                               |  13.560s  |  13.560s  |   0.000s  | 0.0%|
|auk-0075.smt2                                                                               |   1.474s  |   1.474s  |   0.000s  | 0.0%|
|auk-0076.smt2                                                                               |   1.271s  |   1.271s  |   0.000s  | 0.0%|
|auk-0077.smt2                                                                               |   1.101s  |   1.101s  |   0.000s  | 0.0%|
|auk-0078.smt2                                                                               |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|auk-0079.smt2                                                                               |  14.178s  |  14.178s  |   0.000s  | 0.0%|
|auk-0080.smt2                                                                               |   1.594s  |   1.594s  |   0.000s  | 0.0%|
|auk-0081.smt2                                                                               |  73.859s  |  73.859s  |   0.000s  | 0.0%|
|auk-0082.smt2                                                                               |   2.870s  |   2.870s  |   0.000s  | 0.0%|
|auk-0083.smt2                                                                               |   2.825s  |   2.825s  |   0.000s  | 0.0%|
|auk-0084.smt2                                                                               |   9.849s  |   9.849s  |   0.000s  | 0.0%|
|auk-0085.smt2                                                                               | 200.020s  | 200.020s  |   0.000s  | 0.0%|
|auk-0086.smt2                                                                               | 200.025s  | 200.025s  |   0.000s  | 0.0%|
|auk-0087.smt2                                                                               | 104.517s  | 104.517s  |   0.000s  | 0.0%|
|auk-0088.smt2                                                                               |  33.426s  |  33.426s  |   0.000s  | 0.0%|
|auk-0089.smt2                                                                               |  30.347s  |  30.347s  |   0.000s  | 0.0%|
|auk-0090.smt2                                                                               |  13.592s  |  13.592s  |   0.000s  | 0.0%|
|auk-0091.smt2                                                                               |   5.547s  |   5.547s  |   0.000s  | 0.0%|
|auk-0092.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0093.smt2                                                                               |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|auk-0094.smt2                                                                               |   0.976s  |   0.976s  |   0.000s  | 0.0%|
|auk-0095.smt2                                                                               |   2.079s  |   2.079s  |   0.000s  | 0.0%|
|auk-0096.smt2                                                                               |   0.783s  |   0.783s  |   0.000s  | 0.0%|
|auk-0097.smt2                                                                               |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|auk-0098.smt2                                                                               |  14.966s  |  14.966s  |   0.000s  | 0.0%|
|auk-0099.smt2                                                                               |  31.425s  |  31.425s  |   0.000s  | 0.0%|
|auk-0100.smt2                                                                               |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|auk-0101.smt2                                                                               |   1.753s  |   1.753s  |   0.000s  | 0.0%|
|auk-0102.smt2                                                                               |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|auk-0103.smt2                                                                               |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|auk-0104.smt2                                                                               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|auk-0105.smt2                                                                               |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|auk-0106.smt2                                                                               |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|auk-0107.smt2                                                                               |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|auk-0108.smt2                                                                               |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|auk-0109.smt2                                                                               |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|auk-0110.smt2                                                                               |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|auk-0111.smt2                                                                               |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|auk-0112.smt2                                                                               |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|auk-0113.smt2                                                                               |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|auk-0114.smt2                                                                               |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|auk-0115.smt2                                                                               |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|auk-0116.smt2                                                                               |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|auk-0117.smt2                                                                               |   0.697s  |   0.697s  |   0.000s  | 0.0%|
|auk-0118.smt2                                                                               |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|auk-0119.smt2                                                                               |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|auk-0120.smt2                                                                               |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|auk-0121.smt2                                                                               |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|auk-0122.smt2                                                                               |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|auk-0123.smt2                                                                               |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|auk-0124.smt2                                                                               |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|auk-0125.smt2                                                                               |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|auk-0126.smt2                                                                               |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|auk-0127.smt2                                                                               |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|auk-0128.smt2                                                                               |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|auk-0129.smt2                                                                               |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|auk-0130.smt2                                                                               |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|auk-0131.smt2                                                                               |   1.733s  |   1.733s  |   0.000s  | 0.0%|
|auk-0132.smt2                                                                               |   1.350s  |   1.350s  |   0.000s  | 0.0%|
|auk-0133.smt2                                                                               |   0.823s  |   0.823s  |   0.000s  | 0.0%|
|auk-0134.smt2                                                                               |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|auk-0135.smt2                                                                               |   1.151s  |   1.151s  |   0.000s  | 0.0%|
|auk-0136.smt2                                                                               |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|auk-0137.smt2                                                                               |  35.198s  |  35.198s  |   0.000s  | 0.0%|
|auk-0138.smt2                                                                               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|auk-0139.smt2                                                                               |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|auk-0140.smt2                                                                               |  10.474s  |  10.474s  |   0.000s  | 0.0%|
|auk-0141.smt2                                                                               |  10.612s  |  10.612s  |   0.000s  | 0.0%|
|auk-0142.smt2                                                                               |   3.361s  |   3.361s  |   0.000s  | 0.0%|
|auk-0143.smt2                                                                               |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|auk-0144.smt2                                                                               |   1.569s  |   1.569s  |   0.000s  | 0.0%|
|auk-0145.smt2                                                                               |   1.120s  |   1.120s  |   0.000s  | 0.0%|
|auk-0146.smt2                                                                               |   1.967s  |   1.967s  |   0.000s  | 0.0%|
|auk-0147.smt2                                                                               | 200.020s  | 200.020s  |   0.000s  | 0.0%|
|auk-0148.smt2                                                                               |   2.530s  |   2.530s  |   0.000s  | 0.0%|
|auk-0149.smt2                                                                               |   0.900s  |   0.900s  |   0.000s  | 0.0%|
|auk-0150.smt2                                                                               |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|auk-0151.smt2                                                                               | 200.025s  | 200.025s  |   0.000s  | 0.0%|
|auk-0152.smt2                                                                               |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|auk-0153.smt2                                                                               |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|auk-0154.smt2                                                                               |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|auk-0155.smt2                                                                               |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|auk-0156.smt2                                                                               |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|auk-0157.smt2                                                                               |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|auk-0158.smt2                                                                               |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|auk-0159.smt2                                                                               |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|auk-0160.smt2                                                                               |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|auk-0161.smt2                                                                               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|auk-0162.smt2                                                                               |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|auk-0163.smt2                                                                               |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|auk-0164.smt2                                                                               |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|auk-0165.smt2                                                                               |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|auk-0166.smt2                                                                               |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|auk-0167.smt2                                                                               |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|auk-0168.smt2                                                                               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|auk-0169.smt2                                                                               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|auk-0170.smt2                                                                               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|auk-0171.smt2                                                                               |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|auk-0172.smt2                                                                               |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|auk-0173.smt2                                                                               |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|auk-0174.smt2                                                                               |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|auk-0175.smt2                                                                               |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|auk-0176.smt2                                                                               |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|auk-0177.smt2                                                                               |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|auk-0178.smt2                                                                               |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|auk-0179.smt2                                                                               |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|auk-0180.smt2                                                                               |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|auk-0181.smt2                                                                               |  10.843s  |  10.843s  |   0.000s  | 0.0%|
|auk-0182.smt2                                                                               |   3.778s  |   3.778s  |   0.000s  | 0.0%|
|auk-0183.smt2                                                                               |   3.383s  |   3.383s  |   0.000s  | 0.0%|
|auk-0184.smt2                                                                               |  42.855s  |  42.855s  |   0.000s  | 0.0%|
|auk-0185.smt2                                                                               | 200.020s  | 200.020s  |   0.000s  | 0.0%|
|auk-0186.smt2                                                                               |  11.514s  |  11.514s  |   0.000s  | 0.0%|
|auk-0187.smt2                                                                               | 200.025s  | 200.025s  |   0.000s  | 0.0%|
|auk-0188.smt2                                                                               | 200.068s  | 200.068s  |   0.000s  | 0.0%|
|auk-0189.smt2                                                                               | 200.018s  | 200.018s  |   0.000s  | 0.0%|
|auk-0190.smt2                                                                               |   0.560s  |   0.560s  |   0.000s  | 0.0%|
</details>
