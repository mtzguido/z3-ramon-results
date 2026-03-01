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
Job tag: qp_true_certora2
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 9b30560b617f35b45d3704d99dce09c021636fca
Z3 branch: modgb
Z3 options: "-T:200 smt.arith.nl.grobner_quotient_pairs=true"
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
Job description: quotient_pairs=true inputs/certora2
Job tag: qp_true_certora2
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 9b30560b617f35b45d3704d99dce09c021636fca
Z3 branch: modgb
Z3 options: "-T:200 smt.arith.nl.grobner_quotient_pairs=true"
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
|auk-0001.smt2                                                                               | 200.015s  | 200.015s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   1.190s  |   1.190s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.727s  |   0.727s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |  23.307s  |  23.307s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               | 200.032s  | 200.032s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.173s  |   0.173s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.015s  | 200.015s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   1.190s  |   1.190s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.727s  |   0.727s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |  23.307s  |  23.307s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               | 200.032s  | 200.032s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.173s  |   0.173s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.015s  | 200.015s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   1.190s  |   1.190s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.727s  |   0.727s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |  23.307s  |  23.307s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               | 200.032s  | 200.032s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.173s  |   0.173s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.015s  | 200.015s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   1.190s  |   1.190s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.727s  |   0.727s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |  23.307s  |  23.307s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               | 200.032s  | 200.032s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.173s  |   0.173s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0011.smt2                                                                              | 200.032s |70.468MiB|
|auk-0188.smt2                                                                              | 200.031s |86.912MiB|
|auk-0086.smt2                                                                              | 200.030s |118.0MiB|
|auk-0092.smt2                                                                              | 200.030s |115.0MiB|
|auk-0187.smt2                                                                              | 200.026s |96.084MiB|
|auk-0191.smt2                                                                              | 200.024s |39.62MiB|
|auk-0015.smt2                                                                              | 200.023s |62.732MiB|
|auk-0147.smt2                                                                              | 200.023s |73.564MiB|
|auk-0184.smt2                                                                              | 200.023s |64.392MiB|
|auk-0185.smt2                                                                              | 200.022s |62.328MiB|
|auk-0189.smt2                                                                              | 200.019s |76.836MiB|
|auk-0151.smt2                                                                              | 200.015s |63.536MiB|
|auk-0001.smt2                                                                              | 200.015s |46.684MiB|
|auk-0089.smt2                                                                              | 122.520s |84.076MiB|
|auk-0081.smt2                                                                              |  75.902s |36.508MiB|
|auk-0087.smt2                                                                              |  60.111s |77.872MiB|
|auk-0085.smt2                                                                              |  53.130s |93.396MiB|
|auk-0088.smt2                                                                              |  43.318s |91.508MiB|
|auk-0099.smt2                                                                              |  32.108s |198.0MiB|
|auk-0007.smt2                                                                              |  23.307s |47.472MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0011.smt2                                                                              | 200.032s |70.468MiB|
|auk-0188.smt2                                                                              | 200.031s |86.912MiB|
|auk-0086.smt2                                                                              | 200.030s |118.0MiB|
|auk-0092.smt2                                                                              | 200.030s |115.0MiB|
|auk-0187.smt2                                                                              | 200.026s |96.084MiB|
|auk-0191.smt2                                                                              | 200.024s |39.62MiB|
|auk-0015.smt2                                                                              | 200.023s |62.732MiB|
|auk-0147.smt2                                                                              | 200.023s |73.564MiB|
|auk-0184.smt2                                                                              | 200.023s |64.392MiB|
|auk-0185.smt2                                                                              | 200.022s |62.328MiB|
|auk-0189.smt2                                                                              | 200.019s |76.836MiB|
|auk-0151.smt2                                                                              | 200.015s |63.536MiB|
|auk-0001.smt2                                                                              | 200.015s |46.684MiB|
|auk-0089.smt2                                                                              | 122.520s |84.076MiB|
|auk-0081.smt2                                                                              |  75.902s |36.508MiB|
|auk-0087.smt2                                                                              |  60.111s |77.872MiB|
|auk-0085.smt2                                                                              |  53.130s |93.396MiB|
|auk-0088.smt2                                                                              |  43.318s |91.508MiB|
|auk-0099.smt2                                                                              |  32.108s |198.0MiB|
|auk-0007.smt2                                                                              |  23.307s |47.472MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |46.684MiB|46.684MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |36.536MiB|36.536MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |28.196MiB|28.196MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |36.36MiB|36.36MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |33.128MiB|33.128MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |36.344MiB|36.344MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |47.472MiB|47.472MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |28.244MiB|28.244MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |20.212MiB|20.212MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |33.004MiB|33.004MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |70.468MiB|70.468MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.244MiB|20.244MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |28.096MiB|28.096MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |28.092MiB|28.092MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |62.732MiB|62.732MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.28MiB|25.28MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |27.388MiB|27.388MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |26.196MiB|26.196MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |26.052MiB|26.052MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.588MiB|25.588MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |46.684MiB|46.684MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |36.536MiB|36.536MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |28.196MiB|28.196MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |36.36MiB|36.36MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |33.128MiB|33.128MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |36.344MiB|36.344MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |47.472MiB|47.472MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |28.244MiB|28.244MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |20.212MiB|20.212MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |33.004MiB|33.004MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |70.468MiB|70.468MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.244MiB|20.244MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |28.096MiB|28.096MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |28.092MiB|28.092MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |62.732MiB|62.732MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.28MiB|25.28MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |27.388MiB|27.388MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |26.196MiB|26.196MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |26.052MiB|26.052MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.588MiB|25.588MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |46.684MiB|46.684MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |36.536MiB|36.536MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |28.196MiB|28.196MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |36.36MiB|36.36MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |33.128MiB|33.128MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |36.344MiB|36.344MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |47.472MiB|47.472MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |28.244MiB|28.244MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |20.212MiB|20.212MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |33.004MiB|33.004MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |70.468MiB|70.468MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.244MiB|20.244MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |28.096MiB|28.096MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |28.092MiB|28.092MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |62.732MiB|62.732MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.28MiB|25.28MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |27.388MiB|27.388MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |26.196MiB|26.196MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |26.052MiB|26.052MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.588MiB|25.588MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |46.684MiB|46.684MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |36.536MiB|36.536MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |28.196MiB|28.196MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |36.36MiB|36.36MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |33.128MiB|33.128MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |36.344MiB|36.344MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |47.472MiB|47.472MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |28.244MiB|28.244MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |20.212MiB|20.212MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |33.004MiB|33.004MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |70.468MiB|70.468MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.244MiB|20.244MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |28.096MiB|28.096MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |28.092MiB|28.092MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |62.732MiB|62.732MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.28MiB|25.28MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |27.388MiB|27.388MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |26.196MiB|26.196MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |26.052MiB|26.052MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.588MiB|25.588MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0099.smt2                                                                              |  32.108s |198.0MiB|
|auk-0098.smt2                                                                              |  15.748s |169.0MiB|
|auk-0086.smt2                                                                              | 200.030s |118.0MiB|
|auk-0092.smt2                                                                              | 200.030s |115.0MiB|
|auk-0082.smt2                                                                              |   2.884s |99.0MiB|
|auk-0083.smt2                                                                              |   2.818s |99.0MiB|
|auk-0187.smt2                                                                              | 200.026s |96.084MiB|
|auk-0085.smt2                                                                              |  53.130s |93.396MiB|
|auk-0131.smt2                                                                              |   1.681s |92.692MiB|
|auk-0088.smt2                                                                              |  43.318s |91.508MiB|
|auk-0188.smt2                                                                              | 200.031s |86.912MiB|
|auk-0089.smt2                                                                              | 122.520s |84.076MiB|
|auk-0087.smt2                                                                              |  60.111s |77.872MiB|
|auk-0189.smt2                                                                              | 200.019s |76.836MiB|
|auk-0147.smt2                                                                              | 200.023s |73.564MiB|
|auk-0011.smt2                                                                              | 200.032s |70.468MiB|
|auk-0186.smt2                                                                              |  12.355s |69.816MiB|
|auk-0181.smt2                                                                              |  16.283s |69.688MiB|
|auk-0184.smt2                                                                              | 200.023s |64.392MiB|
|auk-0151.smt2                                                                              | 200.015s |63.536MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0099.smt2                                                                              |  32.108s |198.0MiB|
|auk-0098.smt2                                                                              |  15.748s |169.0MiB|
|auk-0086.smt2                                                                              | 200.030s |118.0MiB|
|auk-0092.smt2                                                                              | 200.030s |115.0MiB|
|auk-0082.smt2                                                                              |   2.884s |99.0MiB|
|auk-0083.smt2                                                                              |   2.818s |99.0MiB|
|auk-0187.smt2                                                                              | 200.026s |96.084MiB|
|auk-0085.smt2                                                                              |  53.130s |93.396MiB|
|auk-0131.smt2                                                                              |   1.681s |92.692MiB|
|auk-0088.smt2                                                                              |  43.318s |91.508MiB|
|auk-0188.smt2                                                                              | 200.031s |86.912MiB|
|auk-0089.smt2                                                                              | 122.520s |84.076MiB|
|auk-0087.smt2                                                                              |  60.111s |77.872MiB|
|auk-0189.smt2                                                                              | 200.019s |76.836MiB|
|auk-0147.smt2                                                                              | 200.023s |73.564MiB|
|auk-0011.smt2                                                                              | 200.032s |70.468MiB|
|auk-0186.smt2                                                                              |  12.355s |69.816MiB|
|auk-0181.smt2                                                                              |  16.283s |69.688MiB|
|auk-0184.smt2                                                                              | 200.023s |64.392MiB|
|auk-0151.smt2                                                                              | 200.015s |63.536MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               | 200.015s  | 200.015s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   1.190s  |   1.190s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.727s  |   0.727s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |  23.307s  |  23.307s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               | 200.032s  | 200.032s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|auk-0021.smt2                                                                               |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|auk-0022.smt2                                                                               |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|auk-0023.smt2                                                                               |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|auk-0024.smt2                                                                               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|auk-0025.smt2                                                                               |   1.816s  |   1.816s  |   0.000s  | 0.0%|
|auk-0026.smt2                                                                               |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|auk-0027.smt2                                                                               |  19.211s  |  19.211s  |   0.000s  | 0.0%|
|auk-0028.smt2                                                                               |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|auk-0029.smt2                                                                               |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|auk-0030.smt2                                                                               |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|auk-0031.smt2                                                                               |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|auk-0032.smt2                                                                               |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|auk-0033.smt2                                                                               |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|auk-0034.smt2                                                                               |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|auk-0035.smt2                                                                               |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|auk-0036.smt2                                                                               |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|auk-0037.smt2                                                                               |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|auk-0038.smt2                                                                               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|auk-0039.smt2                                                                               |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|auk-0040.smt2                                                                               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|auk-0041.smt2                                                                               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|auk-0042.smt2                                                                               |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|auk-0043.smt2                                                                               |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|auk-0044.smt2                                                                               |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|auk-0045.smt2                                                                               |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|auk-0046.smt2                                                                               |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|auk-0047.smt2                                                                               |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|auk-0048.smt2                                                                               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|auk-0049.smt2                                                                               |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|auk-0050.smt2                                                                               |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|auk-0051.smt2                                                                               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|auk-0052.smt2                                                                               |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|auk-0053.smt2                                                                               |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|auk-0054.smt2                                                                               |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|auk-0055.smt2                                                                               |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|auk-0056.smt2                                                                               |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|auk-0057.smt2                                                                               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|auk-0058.smt2                                                                               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|auk-0059.smt2                                                                               |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|auk-0060.smt2                                                                               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|auk-0061.smt2                                                                               |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|auk-0062.smt2                                                                               |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|auk-0063.smt2                                                                               |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|auk-0064.smt2                                                                               |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|auk-0065.smt2                                                                               |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|auk-0066.smt2                                                                               |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|auk-0067.smt2                                                                               |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|auk-0068.smt2                                                                               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|auk-0069.smt2                                                                               |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|auk-0070.smt2                                                                               |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|auk-0071.smt2                                                                               |   1.156s  |   1.156s  |   0.000s  | 0.0%|
|auk-0072.smt2                                                                               |   0.927s  |   0.927s  |   0.000s  | 0.0%|
|auk-0073.smt2                                                                               |   1.151s  |   1.151s  |   0.000s  | 0.0%|
|auk-0074.smt2                                                                               |  13.370s  |  13.370s  |   0.000s  | 0.0%|
|auk-0075.smt2                                                                               |   1.330s  |   1.330s  |   0.000s  | 0.0%|
|auk-0076.smt2                                                                               |   1.196s  |   1.196s  |   0.000s  | 0.0%|
|auk-0077.smt2                                                                               |   1.133s  |   1.133s  |   0.000s  | 0.0%|
|auk-0078.smt2                                                                               |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|auk-0079.smt2                                                                               |  14.304s  |  14.304s  |   0.000s  | 0.0%|
|auk-0080.smt2                                                                               |   1.594s  |   1.594s  |   0.000s  | 0.0%|
|auk-0081.smt2                                                                               |  75.902s  |  75.902s  |   0.000s  | 0.0%|
|auk-0082.smt2                                                                               |   2.884s  |   2.884s  |   0.000s  | 0.0%|
|auk-0083.smt2                                                                               |   2.818s  |   2.818s  |   0.000s  | 0.0%|
|auk-0084.smt2                                                                               |   8.141s  |   8.141s  |   0.000s  | 0.0%|
|auk-0085.smt2                                                                               |  53.130s  |  53.130s  |   0.000s  | 0.0%|
|auk-0086.smt2                                                                               | 200.030s  | 200.030s  |   0.000s  | 0.0%|
|auk-0087.smt2                                                                               |  60.111s  |  60.111s  |   0.000s  | 0.0%|
|auk-0088.smt2                                                                               |  43.318s  |  43.318s  |   0.000s  | 0.0%|
|auk-0089.smt2                                                                               | 122.520s  | 122.520s  |   0.000s  | 0.0%|
|auk-0090.smt2                                                                               |  13.921s  |  13.921s  |   0.000s  | 0.0%|
|auk-0091.smt2                                                                               |   5.292s  |   5.292s  |   0.000s  | 0.0%|
|auk-0092.smt2                                                                               | 200.030s  | 200.030s  |   0.000s  | 0.0%|
|auk-0093.smt2                                                                               |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|auk-0094.smt2                                                                               |   0.881s  |   0.881s  |   0.000s  | 0.0%|
|auk-0095.smt2                                                                               |   2.052s  |   2.052s  |   0.000s  | 0.0%|
|auk-0096.smt2                                                                               |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|auk-0097.smt2                                                                               |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|auk-0098.smt2                                                                               |  15.748s  |  15.748s  |   0.000s  | 0.0%|
|auk-0099.smt2                                                                               |  32.108s  |  32.108s  |   0.000s  | 0.0%|
|auk-0100.smt2                                                                               |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|auk-0101.smt2                                                                               |   1.843s  |   1.843s  |   0.000s  | 0.0%|
|auk-0102.smt2                                                                               |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|auk-0103.smt2                                                                               |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|auk-0104.smt2                                                                               |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|auk-0105.smt2                                                                               |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|auk-0106.smt2                                                                               |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|auk-0107.smt2                                                                               |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|auk-0108.smt2                                                                               |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|auk-0109.smt2                                                                               |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|auk-0110.smt2                                                                               |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|auk-0111.smt2                                                                               |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|auk-0112.smt2                                                                               |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|auk-0113.smt2                                                                               |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|auk-0114.smt2                                                                               |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|auk-0115.smt2                                                                               |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|auk-0116.smt2                                                                               |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|auk-0117.smt2                                                                               |   0.685s  |   0.685s  |   0.000s  | 0.0%|
|auk-0118.smt2                                                                               |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|auk-0119.smt2                                                                               |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|auk-0120.smt2                                                                               |   0.452s  |   0.452s  |   0.000s  | 0.0%|
|auk-0121.smt2                                                                               |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|auk-0122.smt2                                                                               |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|auk-0123.smt2                                                                               |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|auk-0124.smt2                                                                               |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|auk-0125.smt2                                                                               |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|auk-0126.smt2                                                                               |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|auk-0127.smt2                                                                               |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|auk-0128.smt2                                                                               |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|auk-0129.smt2                                                                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|auk-0130.smt2                                                                               |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|auk-0131.smt2                                                                               |   1.681s  |   1.681s  |   0.000s  | 0.0%|
|auk-0132.smt2                                                                               |   1.361s  |   1.361s  |   0.000s  | 0.0%|
|auk-0133.smt2                                                                               |   0.834s  |   0.834s  |   0.000s  | 0.0%|
|auk-0134.smt2                                                                               |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|auk-0135.smt2                                                                               |   1.202s  |   1.202s  |   0.000s  | 0.0%|
|auk-0136.smt2                                                                               |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|auk-0137.smt2                                                                               |   3.137s  |   3.137s  |   0.000s  | 0.0%|
|auk-0138.smt2                                                                               |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|auk-0139.smt2                                                                               |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|auk-0140.smt2                                                                               |  11.407s  |  11.407s  |   0.000s  | 0.0%|
|auk-0141.smt2                                                                               |  21.408s  |  21.408s  |   0.000s  | 0.0%|
|auk-0142.smt2                                                                               |   3.579s  |   3.579s  |   0.000s  | 0.0%|
|auk-0143.smt2                                                                               |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|auk-0144.smt2                                                                               |   1.648s  |   1.648s  |   0.000s  | 0.0%|
|auk-0145.smt2                                                                               |   1.109s  |   1.109s  |   0.000s  | 0.0%|
|auk-0146.smt2                                                                               |   1.916s  |   1.916s  |   0.000s  | 0.0%|
|auk-0147.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0148.smt2                                                                               |   2.577s  |   2.577s  |   0.000s  | 0.0%|
|auk-0149.smt2                                                                               |   1.137s  |   1.137s  |   0.000s  | 0.0%|
|auk-0150.smt2                                                                               |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|auk-0151.smt2                                                                               | 200.015s  | 200.015s  |   0.000s  | 0.0%|
|auk-0152.smt2                                                                               |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|auk-0153.smt2                                                                               |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|auk-0154.smt2                                                                               |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|auk-0155.smt2                                                                               |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|auk-0156.smt2                                                                               |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|auk-0157.smt2                                                                               |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|auk-0158.smt2                                                                               |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|auk-0159.smt2                                                                               |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|auk-0160.smt2                                                                               |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|auk-0161.smt2                                                                               |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|auk-0162.smt2                                                                               |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|auk-0163.smt2                                                                               |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|auk-0164.smt2                                                                               |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|auk-0165.smt2                                                                               |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|auk-0166.smt2                                                                               |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|auk-0167.smt2                                                                               |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|auk-0168.smt2                                                                               |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|auk-0169.smt2                                                                               |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|auk-0170.smt2                                                                               |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|auk-0171.smt2                                                                               |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|auk-0172.smt2                                                                               |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|auk-0173.smt2                                                                               |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|auk-0174.smt2                                                                               |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|auk-0175.smt2                                                                               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|auk-0176.smt2                                                                               |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|auk-0177.smt2                                                                               |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|auk-0178.smt2                                                                               |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|auk-0179.smt2                                                                               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|auk-0180.smt2                                                                               |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|auk-0181.smt2                                                                               |  16.283s  |  16.283s  |   0.000s  | 0.0%|
|auk-0182.smt2                                                                               |   3.780s  |   3.780s  |   0.000s  | 0.0%|
|auk-0183.smt2                                                                               |   3.747s  |   3.747s  |   0.000s  | 0.0%|
|auk-0184.smt2                                                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|auk-0185.smt2                                                                               | 200.022s  | 200.022s  |   0.000s  | 0.0%|
|auk-0186.smt2                                                                               |  12.355s  |  12.355s  |   0.000s  | 0.0%|
|auk-0187.smt2                                                                               | 200.026s  | 200.026s  |   0.000s  | 0.0%|
|auk-0188.smt2                                                                               | 200.031s  | 200.031s  |   0.000s  | 0.0%|
|auk-0189.smt2                                                                               | 200.019s  | 200.019s  |   0.000s  | 0.0%|
|auk-0190.smt2                                                                               |   0.563s  |   0.563s  |   0.000s  | 0.0%|
</details>
