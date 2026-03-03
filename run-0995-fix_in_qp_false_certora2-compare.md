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
Job description: quotient_pairs=false inputs/certora2
Job tag: fix_in_qp_false_certora2
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 186ef6a0cd3f0fc8821795515994089cfc4e65db
Z3 branch: modgb
Z3 options: "-T:200 smt.arith.nl.grobner_quotient_pairs=false"
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
Job description: quotient_pairs=false inputs/certora2
Job tag: fix_in_qp_false_certora2
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 186ef6a0cd3f0fc8821795515994089cfc4e65db
Z3 branch: modgb
Z3 options: "-T:200 smt.arith.nl.grobner_quotient_pairs=false"
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
|auk-0002.smt2                                                                               |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.975s  |   0.975s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               | 200.025s  | 200.025s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |   1.816s  |   1.816s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.016s  | 200.016s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.201s  |   0.201s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.975s  |   0.975s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               | 200.025s  | 200.025s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |   1.816s  |   1.816s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.016s  | 200.016s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.201s  |   0.201s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.975s  |   0.975s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               | 200.025s  | 200.025s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |   1.816s  |   1.816s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.016s  | 200.016s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.201s  |   0.201s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.975s  |   0.975s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               | 200.025s  | 200.025s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |   1.816s  |   1.816s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.016s  | 200.016s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.201s  |   0.201s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0147.smt2                                                                              | 200.062s |77.78MiB|
|auk-0092.smt2                                                                              | 200.026s |124.0MiB|
|auk-0007.smt2                                                                              | 200.025s |72.804MiB|
|auk-0089.smt2                                                                              | 200.024s |85.696MiB|
|auk-0001.smt2                                                                              | 200.023s |46.84MiB|
|auk-0086.smt2                                                                              | 200.023s |119.0MiB|
|auk-0088.smt2                                                                              | 200.023s |111.0MiB|
|auk-0187.smt2                                                                              | 200.023s |94.612MiB|
|auk-0085.smt2                                                                              | 200.021s |111.0MiB|
|auk-0185.smt2                                                                              | 200.019s |68.252MiB|
|auk-0151.smt2                                                                              | 200.018s |66.612MiB|
|auk-0188.smt2                                                                              | 200.018s |90.56MiB|
|auk-0189.smt2                                                                              | 200.017s |78.488MiB|
|auk-0191.smt2                                                                              | 200.017s |39.756MiB|
|auk-0015.smt2                                                                              | 200.016s |78.544MiB|
|auk-0081.smt2                                                                              |  72.734s |36.736MiB|
|auk-0090.smt2                                                                              |  32.934s |61.436MiB|
|auk-0099.smt2                                                                              |  31.348s |198.0MiB|
|auk-0183.smt2                                                                              |  28.623s |80.0MiB|
|auk-0184.smt2                                                                              |  27.196s |45.608MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0147.smt2                                                                              | 200.062s |77.78MiB|
|auk-0092.smt2                                                                              | 200.026s |124.0MiB|
|auk-0007.smt2                                                                              | 200.025s |72.804MiB|
|auk-0089.smt2                                                                              | 200.024s |85.696MiB|
|auk-0001.smt2                                                                              | 200.023s |46.84MiB|
|auk-0086.smt2                                                                              | 200.023s |119.0MiB|
|auk-0088.smt2                                                                              | 200.023s |111.0MiB|
|auk-0187.smt2                                                                              | 200.023s |94.612MiB|
|auk-0085.smt2                                                                              | 200.021s |111.0MiB|
|auk-0185.smt2                                                                              | 200.019s |68.252MiB|
|auk-0151.smt2                                                                              | 200.018s |66.612MiB|
|auk-0188.smt2                                                                              | 200.018s |90.56MiB|
|auk-0189.smt2                                                                              | 200.017s |78.488MiB|
|auk-0191.smt2                                                                              | 200.017s |39.756MiB|
|auk-0015.smt2                                                                              | 200.016s |78.544MiB|
|auk-0081.smt2                                                                              |  72.734s |36.736MiB|
|auk-0090.smt2                                                                              |  32.934s |61.436MiB|
|auk-0099.smt2                                                                              |  31.348s |198.0MiB|
|auk-0183.smt2                                                                              |  28.623s |80.0MiB|
|auk-0184.smt2                                                                              |  27.196s |45.608MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |46.84MiB|46.84MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |34.796MiB|34.796MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |28.128MiB|28.128MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |35.784MiB|35.784MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |33.084MiB|33.084MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |36.1MiB|36.1MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |72.804MiB|72.804MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |28.112MiB|28.112MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |20.316MiB|20.316MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |33.128MiB|33.128MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |37.176MiB|37.176MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.108MiB|20.108MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |28.24MiB|28.24MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |28.256MiB|28.256MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |78.544MiB|78.544MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.088MiB|25.088MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |27.4MiB|27.4MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |26.188MiB|26.188MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |26.096MiB|26.096MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.748MiB|25.748MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |46.84MiB|46.84MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |34.796MiB|34.796MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |28.128MiB|28.128MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |35.784MiB|35.784MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |33.084MiB|33.084MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |36.1MiB|36.1MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |72.804MiB|72.804MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |28.112MiB|28.112MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |20.316MiB|20.316MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |33.128MiB|33.128MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |37.176MiB|37.176MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.108MiB|20.108MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |28.24MiB|28.24MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |28.256MiB|28.256MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |78.544MiB|78.544MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.088MiB|25.088MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |27.4MiB|27.4MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |26.188MiB|26.188MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |26.096MiB|26.096MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.748MiB|25.748MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |46.84MiB|46.84MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |34.796MiB|34.796MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |28.128MiB|28.128MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |35.784MiB|35.784MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |33.084MiB|33.084MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |36.1MiB|36.1MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |72.804MiB|72.804MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |28.112MiB|28.112MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |20.316MiB|20.316MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |33.128MiB|33.128MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |37.176MiB|37.176MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.108MiB|20.108MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |28.24MiB|28.24MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |28.256MiB|28.256MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |78.544MiB|78.544MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.088MiB|25.088MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |27.4MiB|27.4MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |26.188MiB|26.188MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |26.096MiB|26.096MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.748MiB|25.748MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |46.84MiB|46.84MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |34.796MiB|34.796MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |28.128MiB|28.128MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |35.784MiB|35.784MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |33.084MiB|33.084MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |36.1MiB|36.1MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |72.804MiB|72.804MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |28.112MiB|28.112MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |20.316MiB|20.316MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |33.128MiB|33.128MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |37.176MiB|37.176MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.108MiB|20.108MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |28.24MiB|28.24MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |28.256MiB|28.256MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |78.544MiB|78.544MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.088MiB|25.088MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |27.4MiB|27.4MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |26.188MiB|26.188MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |26.096MiB|26.096MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.748MiB|25.748MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0099.smt2                                                                              |  31.348s |198.0MiB|
|auk-0098.smt2                                                                              |  15.146s |169.0MiB|
|auk-0092.smt2                                                                              | 200.026s |124.0MiB|
|auk-0086.smt2                                                                              | 200.023s |119.0MiB|
|auk-0088.smt2                                                                              | 200.023s |111.0MiB|
|auk-0085.smt2                                                                              | 200.021s |111.0MiB|
|auk-0082.smt2                                                                              |   2.880s |99.0MiB|
|auk-0083.smt2                                                                              |   2.859s |99.0MiB|
|auk-0187.smt2                                                                              | 200.023s |94.612MiB|
|auk-0131.smt2                                                                              |   1.695s |92.664MiB|
|auk-0188.smt2                                                                              | 200.018s |90.56MiB|
|auk-0089.smt2                                                                              | 200.024s |85.696MiB|
|auk-0183.smt2                                                                              |  28.623s |80.0MiB|
|auk-0015.smt2                                                                              | 200.016s |78.544MiB|
|auk-0189.smt2                                                                              | 200.017s |78.488MiB|
|auk-0147.smt2                                                                              | 200.062s |77.78MiB|
|auk-0186.smt2                                                                              |  15.918s |76.752MiB|
|auk-0007.smt2                                                                              | 200.025s |72.804MiB|
|auk-0185.smt2                                                                              | 200.019s |68.252MiB|
|auk-0151.smt2                                                                              | 200.018s |66.612MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0099.smt2                                                                              |  31.348s |198.0MiB|
|auk-0098.smt2                                                                              |  15.146s |169.0MiB|
|auk-0092.smt2                                                                              | 200.026s |124.0MiB|
|auk-0086.smt2                                                                              | 200.023s |119.0MiB|
|auk-0088.smt2                                                                              | 200.023s |111.0MiB|
|auk-0085.smt2                                                                              | 200.021s |111.0MiB|
|auk-0082.smt2                                                                              |   2.880s |99.0MiB|
|auk-0083.smt2                                                                              |   2.859s |99.0MiB|
|auk-0187.smt2                                                                              | 200.023s |94.612MiB|
|auk-0131.smt2                                                                              |   1.695s |92.664MiB|
|auk-0188.smt2                                                                              | 200.018s |90.56MiB|
|auk-0089.smt2                                                                              | 200.024s |85.696MiB|
|auk-0183.smt2                                                                              |  28.623s |80.0MiB|
|auk-0015.smt2                                                                              | 200.016s |78.544MiB|
|auk-0189.smt2                                                                              | 200.017s |78.488MiB|
|auk-0147.smt2                                                                              | 200.062s |77.78MiB|
|auk-0186.smt2                                                                              |  15.918s |76.752MiB|
|auk-0007.smt2                                                                              | 200.025s |72.804MiB|
|auk-0185.smt2                                                                              | 200.019s |68.252MiB|
|auk-0151.smt2                                                                              | 200.018s |66.612MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.975s  |   0.975s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               | 200.025s  | 200.025s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |   1.816s  |   1.816s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.016s  | 200.016s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|auk-0021.smt2                                                                               |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|auk-0022.smt2                                                                               |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|auk-0023.smt2                                                                               |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|auk-0024.smt2                                                                               |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|auk-0025.smt2                                                                               |   1.096s  |   1.096s  |   0.000s  | 0.0%|
|auk-0026.smt2                                                                               |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|auk-0027.smt2                                                                               |   2.137s  |   2.137s  |   0.000s  | 0.0%|
|auk-0028.smt2                                                                               |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|auk-0029.smt2                                                                               |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|auk-0030.smt2                                                                               |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|auk-0031.smt2                                                                               |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|auk-0032.smt2                                                                               |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|auk-0033.smt2                                                                               |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|auk-0034.smt2                                                                               |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|auk-0035.smt2                                                                               |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|auk-0036.smt2                                                                               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|auk-0037.smt2                                                                               |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|auk-0038.smt2                                                                               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|auk-0039.smt2                                                                               |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|auk-0040.smt2                                                                               |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|auk-0041.smt2                                                                               |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|auk-0042.smt2                                                                               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|auk-0043.smt2                                                                               |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|auk-0044.smt2                                                                               |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|auk-0045.smt2                                                                               |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|auk-0046.smt2                                                                               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|auk-0047.smt2                                                                               |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|auk-0048.smt2                                                                               |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|auk-0049.smt2                                                                               |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|auk-0050.smt2                                                                               |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|auk-0051.smt2                                                                               |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|auk-0052.smt2                                                                               |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|auk-0053.smt2                                                                               |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|auk-0054.smt2                                                                               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|auk-0055.smt2                                                                               |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|auk-0056.smt2                                                                               |   0.478s  |   0.478s  |   0.000s  | 0.0%|
|auk-0057.smt2                                                                               |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|auk-0058.smt2                                                                               |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|auk-0059.smt2                                                                               |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|auk-0060.smt2                                                                               |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|auk-0061.smt2                                                                               |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|auk-0062.smt2                                                                               |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|auk-0063.smt2                                                                               |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|auk-0064.smt2                                                                               |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|auk-0065.smt2                                                                               |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|auk-0066.smt2                                                                               |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|auk-0067.smt2                                                                               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|auk-0068.smt2                                                                               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|auk-0069.smt2                                                                               |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|auk-0070.smt2                                                                               |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|auk-0071.smt2                                                                               |   1.161s  |   1.161s  |   0.000s  | 0.0%|
|auk-0072.smt2                                                                               |   0.690s  |   0.690s  |   0.000s  | 0.0%|
|auk-0073.smt2                                                                               |   1.156s  |   1.156s  |   0.000s  | 0.0%|
|auk-0074.smt2                                                                               |  13.033s  |  13.033s  |   0.000s  | 0.0%|
|auk-0075.smt2                                                                               |   1.276s  |   1.276s  |   0.000s  | 0.0%|
|auk-0076.smt2                                                                               |   1.275s  |   1.275s  |   0.000s  | 0.0%|
|auk-0077.smt2                                                                               |   1.268s  |   1.268s  |   0.000s  | 0.0%|
|auk-0078.smt2                                                                               |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|auk-0079.smt2                                                                               |  14.394s  |  14.394s  |   0.000s  | 0.0%|
|auk-0080.smt2                                                                               |   1.557s  |   1.557s  |   0.000s  | 0.0%|
|auk-0081.smt2                                                                               |  72.734s  |  72.734s  |   0.000s  | 0.0%|
|auk-0082.smt2                                                                               |   2.880s  |   2.880s  |   0.000s  | 0.0%|
|auk-0083.smt2                                                                               |   2.859s  |   2.859s  |   0.000s  | 0.0%|
|auk-0084.smt2                                                                               |  15.021s  |  15.021s  |   0.000s  | 0.0%|
|auk-0085.smt2                                                                               | 200.021s  | 200.021s  |   0.000s  | 0.0%|
|auk-0086.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0087.smt2                                                                               |  13.352s  |  13.352s  |   0.000s  | 0.0%|
|auk-0088.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0089.smt2                                                                               | 200.024s  | 200.024s  |   0.000s  | 0.0%|
|auk-0090.smt2                                                                               |  32.934s  |  32.934s  |   0.000s  | 0.0%|
|auk-0091.smt2                                                                               |   5.296s  |   5.296s  |   0.000s  | 0.0%|
|auk-0092.smt2                                                                               | 200.026s  | 200.026s  |   0.000s  | 0.0%|
|auk-0093.smt2                                                                               |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|auk-0094.smt2                                                                               |   0.818s  |   0.818s  |   0.000s  | 0.0%|
|auk-0095.smt2                                                                               |   2.137s  |   2.137s  |   0.000s  | 0.0%|
|auk-0096.smt2                                                                               |   0.603s  |   0.603s  |   0.000s  | 0.0%|
|auk-0097.smt2                                                                               |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|auk-0098.smt2                                                                               |  15.146s  |  15.146s  |   0.000s  | 0.0%|
|auk-0099.smt2                                                                               |  31.348s  |  31.348s  |   0.000s  | 0.0%|
|auk-0100.smt2                                                                               |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|auk-0101.smt2                                                                               |   2.899s  |   2.899s  |   0.000s  | 0.0%|
|auk-0102.smt2                                                                               |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|auk-0103.smt2                                                                               |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|auk-0104.smt2                                                                               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|auk-0105.smt2                                                                               |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|auk-0106.smt2                                                                               |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|auk-0107.smt2                                                                               |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|auk-0108.smt2                                                                               |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|auk-0109.smt2                                                                               |   0.560s  |   0.560s  |   0.000s  | 0.0%|
|auk-0110.smt2                                                                               |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|auk-0111.smt2                                                                               |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|auk-0112.smt2                                                                               |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|auk-0113.smt2                                                                               |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|auk-0114.smt2                                                                               |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|auk-0115.smt2                                                                               |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|auk-0116.smt2                                                                               |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|auk-0117.smt2                                                                               |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|auk-0118.smt2                                                                               |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|auk-0119.smt2                                                                               |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|auk-0120.smt2                                                                               |   0.521s  |   0.521s  |   0.000s  | 0.0%|
|auk-0121.smt2                                                                               |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|auk-0122.smt2                                                                               |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|auk-0123.smt2                                                                               |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|auk-0124.smt2                                                                               |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|auk-0125.smt2                                                                               |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|auk-0126.smt2                                                                               |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|auk-0127.smt2                                                                               |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|auk-0128.smt2                                                                               |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|auk-0129.smt2                                                                               |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|auk-0130.smt2                                                                               |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|auk-0131.smt2                                                                               |   1.695s  |   1.695s  |   0.000s  | 0.0%|
|auk-0132.smt2                                                                               |   1.373s  |   1.373s  |   0.000s  | 0.0%|
|auk-0133.smt2                                                                               |   0.922s  |   0.922s  |   0.000s  | 0.0%|
|auk-0134.smt2                                                                               |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|auk-0135.smt2                                                                               |   1.109s  |   1.109s  |   0.000s  | 0.0%|
|auk-0136.smt2                                                                               |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|auk-0137.smt2                                                                               |  22.290s  |  22.290s  |   0.000s  | 0.0%|
|auk-0138.smt2                                                                               |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|auk-0139.smt2                                                                               |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|auk-0140.smt2                                                                               |  10.561s  |  10.561s  |   0.000s  | 0.0%|
|auk-0141.smt2                                                                               |  13.838s  |  13.838s  |   0.000s  | 0.0%|
|auk-0142.smt2                                                                               |   3.433s  |   3.433s  |   0.000s  | 0.0%|
|auk-0143.smt2                                                                               |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|auk-0144.smt2                                                                               |   1.569s  |   1.569s  |   0.000s  | 0.0%|
|auk-0145.smt2                                                                               |   1.160s  |   1.160s  |   0.000s  | 0.0%|
|auk-0146.smt2                                                                               |   1.567s  |   1.567s  |   0.000s  | 0.0%|
|auk-0147.smt2                                                                               | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|auk-0148.smt2                                                                               |   2.606s  |   2.606s  |   0.000s  | 0.0%|
|auk-0149.smt2                                                                               |   1.699s  |   1.699s  |   0.000s  | 0.0%|
|auk-0150.smt2                                                                               |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|auk-0151.smt2                                                                               | 200.018s  | 200.018s  |   0.000s  | 0.0%|
|auk-0152.smt2                                                                               |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|auk-0153.smt2                                                                               |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|auk-0154.smt2                                                                               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|auk-0155.smt2                                                                               |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|auk-0156.smt2                                                                               |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|auk-0157.smt2                                                                               |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|auk-0158.smt2                                                                               |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|auk-0159.smt2                                                                               |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|auk-0160.smt2                                                                               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|auk-0161.smt2                                                                               |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|auk-0162.smt2                                                                               |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|auk-0163.smt2                                                                               |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|auk-0164.smt2                                                                               |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|auk-0165.smt2                                                                               |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|auk-0166.smt2                                                                               |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|auk-0167.smt2                                                                               |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|auk-0168.smt2                                                                               |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|auk-0169.smt2                                                                               |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|auk-0170.smt2                                                                               |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|auk-0171.smt2                                                                               |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|auk-0172.smt2                                                                               |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|auk-0173.smt2                                                                               |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|auk-0174.smt2                                                                               |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|auk-0175.smt2                                                                               |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|auk-0176.smt2                                                                               |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|auk-0177.smt2                                                                               |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|auk-0178.smt2                                                                               |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|auk-0179.smt2                                                                               |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|auk-0180.smt2                                                                               |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|auk-0181.smt2                                                                               |  13.907s  |  13.907s  |   0.000s  | 0.0%|
|auk-0182.smt2                                                                               |   4.830s  |   4.830s  |   0.000s  | 0.0%|
|auk-0183.smt2                                                                               |  28.623s  |  28.623s  |   0.000s  | 0.0%|
|auk-0184.smt2                                                                               |  27.196s  |  27.196s  |   0.000s  | 0.0%|
|auk-0185.smt2                                                                               | 200.019s  | 200.019s  |   0.000s  | 0.0%|
|auk-0186.smt2                                                                               |  15.918s  |  15.918s  |   0.000s  | 0.0%|
|auk-0187.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0188.smt2                                                                               | 200.018s  | 200.018s  |   0.000s  | 0.0%|
|auk-0189.smt2                                                                               | 200.017s  | 200.017s  |   0.000s  | 0.0%|
|auk-0190.smt2                                                                               |   0.650s  |   0.650s  |   0.000s  | 0.0%|
</details>
