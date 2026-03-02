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
Job tag: qp_false_certora2
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 9b30560b617f35b45d3704d99dce09c021636fca
Z3 branch: modgb
Z3 options: "-T:200 smt.arith.nl.grobner_quotient_pairs=false"
Z3 inputs: inputs/certora2
Z3 commit message: nla: add quotient reasoning for equation combinations

Extend grobner quotient propagation to combine pairs and triples
of equations sharing a nonlinear variable. When equations of the
form v*lc_i + r_i = 0 share variable v, their linear combinations
produce v*lc_comb + r_comb = 0. If |v| > |r_comb| > 0 and v does
not divide r_comb, generate a conflict lemma.

This handles mod arithmetic patterns like:
  (mod (- x y) m) = 0 AND (mod x m) != (mod y m)
where the three mod expansions produce equations sharing m as
nonlinear factor, and combining them yields m*(q2-q1+q3) = r2-r3
with |r2-r3| < m, forcing r2 = r3 (contradiction).

Co-authored-by: Copilot <223556219+Copilot@users.noreply.github.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: quotient_pairs=false inputs/certora2
Job tag: qp_false_certora2
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 9b30560b617f35b45d3704d99dce09c021636fca
Z3 branch: modgb
Z3 options: "-T:200 smt.arith.nl.grobner_quotient_pairs=false"
Z3 inputs: inputs/certora2
Z3 commit message: nla: add quotient reasoning for equation combinations

Extend grobner quotient propagation to combine pairs and triples
of equations sharing a nonlinear variable. When equations of the
form v*lc_i + r_i = 0 share variable v, their linear combinations
produce v*lc_comb + r_comb = 0. If |v| > |r_comb| > 0 and v does
not divide r_comb, generate a conflict lemma.

This handles mod arithmetic patterns like:
  (mod (- x y) m) = 0 AND (mod x m) != (mod y m)
where the three mod expansions produce equations sharing m as
nonlinear factor, and combining them yields m*(q2-q1+q3) = r2-r3
with |r2-r3| < m, forcing r2 = r3 (contradiction).

Co-authored-by: Copilot <223556219+Copilot@users.noreply.github.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.027s  | 200.027s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.870s  |   0.870s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.828s  |   0.828s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               | 200.016s  | 200.016s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |   1.737s  |   1.737s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.017s  | 200.017s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.171s  |   0.171s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.027s  | 200.027s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.870s  |   0.870s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.828s  |   0.828s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               | 200.016s  | 200.016s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |   1.737s  |   1.737s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.017s  | 200.017s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.171s  |   0.171s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.027s  | 200.027s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.870s  |   0.870s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.828s  |   0.828s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               | 200.016s  | 200.016s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |   1.737s  |   1.737s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.017s  | 200.017s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.171s  |   0.171s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.027s  | 200.027s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.870s  |   0.870s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.828s  |   0.828s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               | 200.016s  | 200.016s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |   1.737s  |   1.737s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.017s  | 200.017s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.171s  |   0.171s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0086.smt2                                                                              | 200.029s |118.0MiB|
|auk-0001.smt2                                                                              | 200.027s |46.884MiB|
|auk-0187.smt2                                                                              | 200.027s |94.916MiB|
|auk-0147.smt2                                                                              | 200.027s |77.416MiB|
|auk-0085.smt2                                                                              | 200.024s |110.0MiB|
|auk-0185.smt2                                                                              | 200.023s |68.292MiB|
|auk-0092.smt2                                                                              | 200.022s |124.0MiB|
|auk-0151.smt2                                                                              | 200.021s |66.828MiB|
|auk-0089.smt2                                                                              | 200.021s |85.48MiB|
|auk-0188.smt2                                                                              | 200.021s |90.284MiB|
|auk-0088.smt2                                                                              | 200.020s |111.0MiB|
|auk-0189.smt2                                                                              | 200.019s |78.568MiB|
|auk-0015.smt2                                                                              | 200.017s |78.668MiB|
|auk-0007.smt2                                                                              | 200.016s |72.652MiB|
|auk-0191.smt2                                                                              | 200.011s |39.8MiB|
|auk-0081.smt2                                                                              |  75.283s |36.464MiB|
|auk-0090.smt2                                                                              |  32.799s |61.744MiB|
|auk-0099.smt2                                                                              |  31.002s |198.0MiB|
|auk-0183.smt2                                                                              |  29.044s |79.88MiB|
|auk-0184.smt2                                                                              |  23.013s |43.34MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0086.smt2                                                                              | 200.029s |118.0MiB|
|auk-0001.smt2                                                                              | 200.027s |46.884MiB|
|auk-0187.smt2                                                                              | 200.027s |94.916MiB|
|auk-0147.smt2                                                                              | 200.027s |77.416MiB|
|auk-0085.smt2                                                                              | 200.024s |110.0MiB|
|auk-0185.smt2                                                                              | 200.023s |68.292MiB|
|auk-0092.smt2                                                                              | 200.022s |124.0MiB|
|auk-0151.smt2                                                                              | 200.021s |66.828MiB|
|auk-0089.smt2                                                                              | 200.021s |85.48MiB|
|auk-0188.smt2                                                                              | 200.021s |90.284MiB|
|auk-0088.smt2                                                                              | 200.020s |111.0MiB|
|auk-0189.smt2                                                                              | 200.019s |78.568MiB|
|auk-0015.smt2                                                                              | 200.017s |78.668MiB|
|auk-0007.smt2                                                                              | 200.016s |72.652MiB|
|auk-0191.smt2                                                                              | 200.011s |39.8MiB|
|auk-0081.smt2                                                                              |  75.283s |36.464MiB|
|auk-0090.smt2                                                                              |  32.799s |61.744MiB|
|auk-0099.smt2                                                                              |  31.002s |198.0MiB|
|auk-0183.smt2                                                                              |  29.044s |79.88MiB|
|auk-0184.smt2                                                                              |  23.013s |43.34MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |46.884MiB|46.884MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |34.808MiB|34.808MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |28.212MiB|28.212MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |35.68MiB|35.68MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |33.076MiB|33.076MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |36.092MiB|36.092MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |72.652MiB|72.652MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |28.176MiB|28.176MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |20.196MiB|20.196MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |33.136MiB|33.136MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |37.452MiB|37.452MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.12MiB|20.12MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |28.196MiB|28.196MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |28.292MiB|28.292MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |78.668MiB|78.668MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.12MiB|25.12MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |27.244MiB|27.244MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |26.192MiB|26.192MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |25.972MiB|25.972MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.7MiB|25.7MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |46.884MiB|46.884MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |34.808MiB|34.808MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |28.212MiB|28.212MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |35.68MiB|35.68MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |33.076MiB|33.076MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |36.092MiB|36.092MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |72.652MiB|72.652MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |28.176MiB|28.176MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |20.196MiB|20.196MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |33.136MiB|33.136MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |37.452MiB|37.452MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.12MiB|20.12MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |28.196MiB|28.196MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |28.292MiB|28.292MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |78.668MiB|78.668MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.12MiB|25.12MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |27.244MiB|27.244MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |26.192MiB|26.192MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |25.972MiB|25.972MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.7MiB|25.7MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |46.884MiB|46.884MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |34.808MiB|34.808MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |28.212MiB|28.212MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |35.68MiB|35.68MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |33.076MiB|33.076MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |36.092MiB|36.092MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |72.652MiB|72.652MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |28.176MiB|28.176MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |20.196MiB|20.196MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |33.136MiB|33.136MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |37.452MiB|37.452MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.12MiB|20.12MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |28.196MiB|28.196MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |28.292MiB|28.292MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |78.668MiB|78.668MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.12MiB|25.12MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |27.244MiB|27.244MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |26.192MiB|26.192MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |25.972MiB|25.972MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.7MiB|25.7MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |46.884MiB|46.884MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |34.808MiB|34.808MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |28.212MiB|28.212MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |35.68MiB|35.68MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |33.076MiB|33.076MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |36.092MiB|36.092MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |72.652MiB|72.652MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |28.176MiB|28.176MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |20.196MiB|20.196MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |33.136MiB|33.136MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |37.452MiB|37.452MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.12MiB|20.12MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |28.196MiB|28.196MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |28.292MiB|28.292MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |78.668MiB|78.668MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.12MiB|25.12MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |27.244MiB|27.244MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |26.192MiB|26.192MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |25.972MiB|25.972MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.7MiB|25.7MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0099.smt2                                                                              |  31.002s |198.0MiB|
|auk-0098.smt2                                                                              |  15.483s |169.0MiB|
|auk-0092.smt2                                                                              | 200.022s |124.0MiB|
|auk-0086.smt2                                                                              | 200.029s |118.0MiB|
|auk-0088.smt2                                                                              | 200.020s |111.0MiB|
|auk-0085.smt2                                                                              | 200.024s |110.0MiB|
|auk-0082.smt2                                                                              |   2.869s |99.0MiB|
|auk-0083.smt2                                                                              |   2.830s |99.0MiB|
|auk-0187.smt2                                                                              | 200.027s |94.916MiB|
|auk-0131.smt2                                                                              |   1.747s |92.768MiB|
|auk-0188.smt2                                                                              | 200.021s |90.284MiB|
|auk-0089.smt2                                                                              | 200.021s |85.48MiB|
|auk-0183.smt2                                                                              |  29.044s |79.88MiB|
|auk-0015.smt2                                                                              | 200.017s |78.668MiB|
|auk-0189.smt2                                                                              | 200.019s |78.568MiB|
|auk-0147.smt2                                                                              | 200.027s |77.416MiB|
|auk-0186.smt2                                                                              |  16.187s |77.252MiB|
|auk-0007.smt2                                                                              | 200.016s |72.652MiB|
|auk-0185.smt2                                                                              | 200.023s |68.292MiB|
|auk-0151.smt2                                                                              | 200.021s |66.828MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0099.smt2                                                                              |  31.002s |198.0MiB|
|auk-0098.smt2                                                                              |  15.483s |169.0MiB|
|auk-0092.smt2                                                                              | 200.022s |124.0MiB|
|auk-0086.smt2                                                                              | 200.029s |118.0MiB|
|auk-0088.smt2                                                                              | 200.020s |111.0MiB|
|auk-0085.smt2                                                                              | 200.024s |110.0MiB|
|auk-0082.smt2                                                                              |   2.869s |99.0MiB|
|auk-0083.smt2                                                                              |   2.830s |99.0MiB|
|auk-0187.smt2                                                                              | 200.027s |94.916MiB|
|auk-0131.smt2                                                                              |   1.747s |92.768MiB|
|auk-0188.smt2                                                                              | 200.021s |90.284MiB|
|auk-0089.smt2                                                                              | 200.021s |85.48MiB|
|auk-0183.smt2                                                                              |  29.044s |79.88MiB|
|auk-0015.smt2                                                                              | 200.017s |78.668MiB|
|auk-0189.smt2                                                                              | 200.019s |78.568MiB|
|auk-0147.smt2                                                                              | 200.027s |77.416MiB|
|auk-0186.smt2                                                                              |  16.187s |77.252MiB|
|auk-0007.smt2                                                                              | 200.016s |72.652MiB|
|auk-0185.smt2                                                                              | 200.023s |68.292MiB|
|auk-0151.smt2                                                                              | 200.021s |66.828MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.027s  | 200.027s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.870s  |   0.870s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.828s  |   0.828s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               | 200.016s  | 200.016s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |   1.737s  |   1.737s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.017s  | 200.017s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|auk-0021.smt2                                                                               |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|auk-0022.smt2                                                                               |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|auk-0023.smt2                                                                               |   0.523s  |   0.523s  |   0.000s  | 0.0%|
|auk-0024.smt2                                                                               |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|auk-0025.smt2                                                                               |   1.333s  |   1.333s  |   0.000s  | 0.0%|
|auk-0026.smt2                                                                               |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|auk-0027.smt2                                                                               |   2.168s  |   2.168s  |   0.000s  | 0.0%|
|auk-0028.smt2                                                                               |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|auk-0029.smt2                                                                               |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|auk-0030.smt2                                                                               |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|auk-0031.smt2                                                                               |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|auk-0032.smt2                                                                               |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|auk-0033.smt2                                                                               |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|auk-0034.smt2                                                                               |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|auk-0035.smt2                                                                               |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|auk-0036.smt2                                                                               |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|auk-0037.smt2                                                                               |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|auk-0038.smt2                                                                               |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|auk-0039.smt2                                                                               |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|auk-0040.smt2                                                                               |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|auk-0041.smt2                                                                               |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|auk-0042.smt2                                                                               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|auk-0043.smt2                                                                               |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|auk-0044.smt2                                                                               |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|auk-0045.smt2                                                                               |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|auk-0046.smt2                                                                               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|auk-0047.smt2                                                                               |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|auk-0048.smt2                                                                               |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|auk-0049.smt2                                                                               |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|auk-0050.smt2                                                                               |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|auk-0051.smt2                                                                               |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|auk-0052.smt2                                                                               |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|auk-0053.smt2                                                                               |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|auk-0054.smt2                                                                               |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|auk-0055.smt2                                                                               |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|auk-0056.smt2                                                                               |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|auk-0057.smt2                                                                               |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|auk-0058.smt2                                                                               |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|auk-0059.smt2                                                                               |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|auk-0060.smt2                                                                               |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|auk-0061.smt2                                                                               |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|auk-0062.smt2                                                                               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|auk-0063.smt2                                                                               |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|auk-0064.smt2                                                                               |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|auk-0065.smt2                                                                               |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|auk-0066.smt2                                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|auk-0067.smt2                                                                               |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|auk-0068.smt2                                                                               |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|auk-0069.smt2                                                                               |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|auk-0070.smt2                                                                               |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|auk-0071.smt2                                                                               |   1.166s  |   1.166s  |   0.000s  | 0.0%|
|auk-0072.smt2                                                                               |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|auk-0073.smt2                                                                               |   1.199s  |   1.199s  |   0.000s  | 0.0%|
|auk-0074.smt2                                                                               |  13.840s  |  13.840s  |   0.000s  | 0.0%|
|auk-0075.smt2                                                                               |   1.494s  |   1.494s  |   0.000s  | 0.0%|
|auk-0076.smt2                                                                               |   1.284s  |   1.284s  |   0.000s  | 0.0%|
|auk-0077.smt2                                                                               |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|auk-0078.smt2                                                                               |   0.770s  |   0.770s  |   0.000s  | 0.0%|
|auk-0079.smt2                                                                               |  14.254s  |  14.254s  |   0.000s  | 0.0%|
|auk-0080.smt2                                                                               |   1.598s  |   1.598s  |   0.000s  | 0.0%|
|auk-0081.smt2                                                                               |  75.283s  |  75.283s  |   0.000s  | 0.0%|
|auk-0082.smt2                                                                               |   2.869s  |   2.869s  |   0.000s  | 0.0%|
|auk-0083.smt2                                                                               |   2.830s  |   2.830s  |   0.000s  | 0.0%|
|auk-0084.smt2                                                                               |  14.546s  |  14.546s  |   0.000s  | 0.0%|
|auk-0085.smt2                                                                               | 200.024s  | 200.024s  |   0.000s  | 0.0%|
|auk-0086.smt2                                                                               | 200.029s  | 200.029s  |   0.000s  | 0.0%|
|auk-0087.smt2                                                                               |  14.226s  |  14.226s  |   0.000s  | 0.0%|
|auk-0088.smt2                                                                               | 200.020s  | 200.020s  |   0.000s  | 0.0%|
|auk-0089.smt2                                                                               | 200.021s  | 200.021s  |   0.000s  | 0.0%|
|auk-0090.smt2                                                                               |  32.799s  |  32.799s  |   0.000s  | 0.0%|
|auk-0091.smt2                                                                               |   5.468s  |   5.468s  |   0.000s  | 0.0%|
|auk-0092.smt2                                                                               | 200.022s  | 200.022s  |   0.000s  | 0.0%|
|auk-0093.smt2                                                                               |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|auk-0094.smt2                                                                               |   0.903s  |   0.903s  |   0.000s  | 0.0%|
|auk-0095.smt2                                                                               |   2.181s  |   2.181s  |   0.000s  | 0.0%|
|auk-0096.smt2                                                                               |   0.601s  |   0.601s  |   0.000s  | 0.0%|
|auk-0097.smt2                                                                               |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|auk-0098.smt2                                                                               |  15.483s  |  15.483s  |   0.000s  | 0.0%|
|auk-0099.smt2                                                                               |  31.002s  |  31.002s  |   0.000s  | 0.0%|
|auk-0100.smt2                                                                               |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|auk-0101.smt2                                                                               |   2.871s  |   2.871s  |   0.000s  | 0.0%|
|auk-0102.smt2                                                                               |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|auk-0103.smt2                                                                               |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|auk-0104.smt2                                                                               |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|auk-0105.smt2                                                                               |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|auk-0106.smt2                                                                               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|auk-0107.smt2                                                                               |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|auk-0108.smt2                                                                               |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|auk-0109.smt2                                                                               |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|auk-0110.smt2                                                                               |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|auk-0111.smt2                                                                               |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|auk-0112.smt2                                                                               |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|auk-0113.smt2                                                                               |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|auk-0114.smt2                                                                               |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|auk-0115.smt2                                                                               |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|auk-0116.smt2                                                                               |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|auk-0117.smt2                                                                               |   0.657s  |   0.657s  |   0.000s  | 0.0%|
|auk-0118.smt2                                                                               |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|auk-0119.smt2                                                                               |   0.600s  |   0.600s  |   0.000s  | 0.0%|
|auk-0120.smt2                                                                               |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|auk-0121.smt2                                                                               |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|auk-0122.smt2                                                                               |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|auk-0123.smt2                                                                               |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|auk-0124.smt2                                                                               |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|auk-0125.smt2                                                                               |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|auk-0126.smt2                                                                               |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|auk-0127.smt2                                                                               |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|auk-0128.smt2                                                                               |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|auk-0129.smt2                                                                               |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|auk-0130.smt2                                                                               |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|auk-0131.smt2                                                                               |   1.747s  |   1.747s  |   0.000s  | 0.0%|
|auk-0132.smt2                                                                               |   1.355s  |   1.355s  |   0.000s  | 0.0%|
|auk-0133.smt2                                                                               |   0.823s  |   0.823s  |   0.000s  | 0.0%|
|auk-0134.smt2                                                                               |   0.713s  |   0.713s  |   0.000s  | 0.0%|
|auk-0135.smt2                                                                               |   1.318s  |   1.318s  |   0.000s  | 0.0%|
|auk-0136.smt2                                                                               |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|auk-0137.smt2                                                                               |  22.369s  |  22.369s  |   0.000s  | 0.0%|
|auk-0138.smt2                                                                               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|auk-0139.smt2                                                                               |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|auk-0140.smt2                                                                               |  11.039s  |  11.039s  |   0.000s  | 0.0%|
|auk-0141.smt2                                                                               |  14.314s  |  14.314s  |   0.000s  | 0.0%|
|auk-0142.smt2                                                                               |   3.567s  |   3.567s  |   0.000s  | 0.0%|
|auk-0143.smt2                                                                               |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|auk-0144.smt2                                                                               |   1.606s  |   1.606s  |   0.000s  | 0.0%|
|auk-0145.smt2                                                                               |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|auk-0146.smt2                                                                               |   1.776s  |   1.776s  |   0.000s  | 0.0%|
|auk-0147.smt2                                                                               | 200.027s  | 200.027s  |   0.000s  | 0.0%|
|auk-0148.smt2                                                                               |   2.624s  |   2.624s  |   0.000s  | 0.0%|
|auk-0149.smt2                                                                               |   1.717s  |   1.717s  |   0.000s  | 0.0%|
|auk-0150.smt2                                                                               |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|auk-0151.smt2                                                                               | 200.021s  | 200.021s  |   0.000s  | 0.0%|
|auk-0152.smt2                                                                               |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|auk-0153.smt2                                                                               |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|auk-0154.smt2                                                                               |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|auk-0155.smt2                                                                               |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|auk-0156.smt2                                                                               |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|auk-0157.smt2                                                                               |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|auk-0158.smt2                                                                               |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|auk-0159.smt2                                                                               |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|auk-0160.smt2                                                                               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|auk-0161.smt2                                                                               |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|auk-0162.smt2                                                                               |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|auk-0163.smt2                                                                               |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|auk-0164.smt2                                                                               |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|auk-0165.smt2                                                                               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|auk-0166.smt2                                                                               |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|auk-0167.smt2                                                                               |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|auk-0168.smt2                                                                               |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|auk-0169.smt2                                                                               |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|auk-0170.smt2                                                                               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|auk-0171.smt2                                                                               |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|auk-0172.smt2                                                                               |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|auk-0173.smt2                                                                               |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|auk-0174.smt2                                                                               |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|auk-0175.smt2                                                                               |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|auk-0176.smt2                                                                               |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|auk-0177.smt2                                                                               |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|auk-0178.smt2                                                                               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|auk-0179.smt2                                                                               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|auk-0180.smt2                                                                               |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|auk-0181.smt2                                                                               |  14.409s  |  14.409s  |   0.000s  | 0.0%|
|auk-0182.smt2                                                                               |   4.662s  |   4.662s  |   0.000s  | 0.0%|
|auk-0183.smt2                                                                               |  29.044s  |  29.044s  |   0.000s  | 0.0%|
|auk-0184.smt2                                                                               |  23.013s  |  23.013s  |   0.000s  | 0.0%|
|auk-0185.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0186.smt2                                                                               |  16.187s  |  16.187s  |   0.000s  | 0.0%|
|auk-0187.smt2                                                                               | 200.027s  | 200.027s  |   0.000s  | 0.0%|
|auk-0188.smt2                                                                               | 200.021s  | 200.021s  |   0.000s  | 0.0%|
|auk-0189.smt2                                                                               | 200.019s  | 200.019s  |   0.000s  | 0.0%|
|auk-0190.smt2                                                                               |   0.608s  |   0.608s  |   0.000s  | 0.0%|
</details>
