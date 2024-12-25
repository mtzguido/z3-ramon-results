Comparing data and data


# SUMMARY
- LHS tests = 2447
- RHS tests = 2447
- LHS success = 0  (0.0%)
- RHS success = 0  (0.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-hybrid-bv
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 85d3041a808b64c9d8491cd1084bdd0431618ece
Z3 branch: master
Z3 options: "-T:20 -v:2 -st smt.sls.enable=true smt.sls.parallel=false tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt-sls)" model_validate=true"
Z3 inputs: inputs/QF_SLIA_SAT
Z3 commit message: avoid platform non-reproducibility due to argument evaluation ordering

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-hybrid-bv
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 85d3041a808b64c9d8491cd1084bdd0431618ece
Z3 branch: master
Z3 options: "-T:20 -v:2 -st smt.sls.enable=true smt.sls.parallel=false tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt-sls)" model_validate=true"
Z3 inputs: inputs/QF_SLIA_SAT
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
|1897_attack.smt2                                                                           |   0.015s |18.136MiB|
|323_attack.smt2                                                                            |   0.015s |18.104MiB|
|2102_attack.smt2                                                                           |   0.015s |18.076MiB|
|1120_attack.smt2                                                                           |   0.015s |18.156MiB|
|2982_attack.smt2                                                                           |   0.015s |18.108MiB|
|1110_attack.smt2                                                                           |   0.015s |17.992MiB|
|1807_attack.smt2                                                                           |   0.014s |17.996MiB|
|2387_attack.smt2                                                                           |   0.014s |18.36MiB|
|1721_attack.smt2                                                                           |   0.014s |17.932MiB|
|3350_attack.smt2                                                                           |   0.014s |18.156MiB|
|1916_attack.smt2                                                                           |   0.014s |18.092MiB|
|1337_attack.smt2                                                                           |   0.014s |18.072MiB|
|2220_attack.smt2                                                                           |   0.014s |18.08MiB|
|1965_attack.smt2                                                                           |   0.014s |17.996MiB|
|58_attack.smt2                                                                             |   0.014s |17.996MiB|
|170_attack.smt2                                                                            |   0.013s |18.024MiB|
|2880_attack.smt2                                                                           |   0.013s |18.16MiB|
|345_attack.smt2                                                                            |   0.013s |17.992MiB|
|3067_attack.smt2                                                                           |   0.013s |17.996MiB|
|2636_attack.smt2                                                                           |   0.013s |18.136MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|1897_attack.smt2                                                                           |   0.015s |18.136MiB|
|323_attack.smt2                                                                            |   0.015s |18.104MiB|
|2102_attack.smt2                                                                           |   0.015s |18.076MiB|
|1120_attack.smt2                                                                           |   0.015s |18.156MiB|
|2982_attack.smt2                                                                           |   0.015s |18.108MiB|
|1110_attack.smt2                                                                           |   0.015s |17.992MiB|
|1807_attack.smt2                                                                           |   0.014s |17.996MiB|
|2387_attack.smt2                                                                           |   0.014s |18.36MiB|
|1721_attack.smt2                                                                           |   0.014s |17.932MiB|
|3350_attack.smt2                                                                           |   0.014s |18.156MiB|
|1916_attack.smt2                                                                           |   0.014s |18.092MiB|
|1337_attack.smt2                                                                           |   0.014s |18.072MiB|
|2220_attack.smt2                                                                           |   0.014s |18.08MiB|
|1965_attack.smt2                                                                           |   0.014s |17.996MiB|
|58_attack.smt2                                                                             |   0.014s |17.996MiB|
|170_attack.smt2                                                                            |   0.013s |18.024MiB|
|2880_attack.smt2                                                                           |   0.013s |18.16MiB|
|345_attack.smt2                                                                            |   0.013s |17.992MiB|
|3067_attack.smt2                                                                           |   0.013s |17.996MiB|
|2636_attack.smt2                                                                           |   0.013s |18.136MiB|
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
|2505_attack.smt2                                                                           |   0.007s |18.608MiB|
|180_attack.smt2                                                                            |   0.006s |18.588MiB|
|1834_attack.smt2                                                                           |   0.007s |18.508MiB|
|293_attack.smt2                                                                            |   0.006s |18.508MiB|
|3149_attack.smt2                                                                           |   0.007s |18.5MiB|
|2557_attack.smt2                                                                           |   0.006s |18.496MiB|
|440_attack.smt2                                                                            |   0.005s |18.488MiB|
|2401_attack.smt2                                                                           |   0.005s |18.484MiB|
|1926_attack.smt2                                                                           |   0.006s |18.48MiB|
|546_attack.smt2                                                                            |   0.005s |18.46MiB|
|1853_attack.smt2                                                                           |   0.006s |18.444MiB|
|1258_attack.smt2                                                                           |   0.006s |18.424MiB|
|2607_attack.smt2                                                                           |   0.007s |18.42MiB|
|1798_attack.smt2                                                                           |   0.007s |18.416MiB|
|1421_attack.smt2                                                                           |   0.008s |18.412MiB|
|2335_attack.smt2                                                                           |   0.008s |18.412MiB|
|3035_attack.smt2                                                                           |   0.008s |18.408MiB|
|3370_attack.smt2                                                                           |   0.007s |18.408MiB|
|112_attack.smt2                                                                            |   0.007s |18.396MiB|
|522_attack.smt2                                                                            |   0.007s |18.396MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|2505_attack.smt2                                                                           |   0.007s |18.608MiB|
|180_attack.smt2                                                                            |   0.006s |18.588MiB|
|1834_attack.smt2                                                                           |   0.007s |18.508MiB|
|293_attack.smt2                                                                            |   0.006s |18.508MiB|
|3149_attack.smt2                                                                           |   0.007s |18.5MiB|
|2557_attack.smt2                                                                           |   0.006s |18.496MiB|
|440_attack.smt2                                                                            |   0.005s |18.488MiB|
|2401_attack.smt2                                                                           |   0.005s |18.484MiB|
|1926_attack.smt2                                                                           |   0.006s |18.48MiB|
|546_attack.smt2                                                                            |   0.005s |18.46MiB|
|1853_attack.smt2                                                                           |   0.006s |18.444MiB|
|1258_attack.smt2                                                                           |   0.006s |18.424MiB|
|2607_attack.smt2                                                                           |   0.007s |18.42MiB|
|1798_attack.smt2                                                                           |   0.007s |18.416MiB|
|1421_attack.smt2                                                                           |   0.008s |18.412MiB|
|2335_attack.smt2                                                                           |   0.008s |18.412MiB|
|3035_attack.smt2                                                                           |   0.008s |18.408MiB|
|3370_attack.smt2                                                                           |   0.007s |18.408MiB|
|112_attack.smt2                                                                            |   0.007s |18.396MiB|
|522_attack.smt2                                                                            |   0.007s |18.396MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
