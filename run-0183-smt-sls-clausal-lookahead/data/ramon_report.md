Comparing data and data


# SUMMARY
- LHS tests = 186
- RHS tests = 186
- LHS success = 186  (100.0%)
- RHS success = 186  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-clausal-lookahead
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 22e4054674a291d83f59019273ff0b24f24295bf
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: add clausal lookahead to arithmetic solver as part of portfolio

have legacy qfbv-sls solver use nnf pre-processing. It relies on it for correctness of the score updates.

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-clausal-lookahead
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 22e4054674a291d83f59019273ff0b24f24295bf
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: add clausal lookahead to arithmetic solver as part of portfolio

have legacy qfbv-sls solver use nnf pre-processing. It relies on it for correctness of the score updates.

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  17.305s  |  17.305s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   4.777s  |   4.777s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.795s  |   0.795s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   0.922s  |   0.922s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  17.305s  |  17.305s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   4.777s  |   4.777s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.795s  |   0.795s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   0.922s  |   0.922s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  17.305s  |  17.305s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   4.777s  |   4.777s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.795s  |   0.795s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   0.922s  |   0.922s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  17.305s  |  17.305s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   4.777s  |   4.777s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.795s  |   0.795s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   0.922s  |   0.922s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|66.smt2                                                                                    |  20.505s |35.22MiB|
|18.smt2                                                                                    |  20.345s |30.932MiB|
|182.smt2                                                                                   |  20.193s |3249.0MiB|
|52.smt2                                                                                    |  20.180s |35.188MiB|
|178.smt2                                                                                   |  20.174s |2441.0MiB|
|183.smt2                                                                                   |  20.142s |3247.0MiB|
|180.smt2                                                                                   |  20.135s |2257.0MiB|
|174.smt2                                                                                   |  20.119s |1649.0MiB|
|176.smt2                                                                                   |  20.105s |2402.0MiB|
|175.smt2                                                                                   |  20.093s |1649.0MiB|
|173.smt2                                                                                   |  20.093s |1685.0MiB|
|90.smt2                                                                                    |  20.089s |35.196MiB|
|172.smt2                                                                                   |  20.088s |2036.0MiB|
|181.smt2                                                                                   |  20.079s |3034.0MiB|
|179.smt2                                                                                   |  20.065s |2258.0MiB|
|158.smt2                                                                                   |  20.063s |599.0MiB|
|163.smt2                                                                                   |  20.048s |599.0MiB|
|102.smt2                                                                                   |  20.048s |35.316MiB|
|168.smt2                                                                                   |  20.047s |594.0MiB|
|169.smt2                                                                                   |  20.043s |881.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|66.smt2                                                                                    |  20.505s |35.22MiB|
|18.smt2                                                                                    |  20.345s |30.932MiB|
|182.smt2                                                                                   |  20.193s |3249.0MiB|
|52.smt2                                                                                    |  20.180s |35.188MiB|
|178.smt2                                                                                   |  20.174s |2441.0MiB|
|183.smt2                                                                                   |  20.142s |3247.0MiB|
|180.smt2                                                                                   |  20.135s |2257.0MiB|
|174.smt2                                                                                   |  20.119s |1649.0MiB|
|176.smt2                                                                                   |  20.105s |2402.0MiB|
|175.smt2                                                                                   |  20.093s |1649.0MiB|
|173.smt2                                                                                   |  20.093s |1685.0MiB|
|90.smt2                                                                                    |  20.089s |35.196MiB|
|172.smt2                                                                                   |  20.088s |2036.0MiB|
|181.smt2                                                                                   |  20.079s |3034.0MiB|
|179.smt2                                                                                   |  20.065s |2258.0MiB|
|158.smt2                                                                                   |  20.063s |599.0MiB|
|163.smt2                                                                                   |  20.048s |599.0MiB|
|102.smt2                                                                                   |  20.048s |35.316MiB|
|168.smt2                                                                                   |  20.047s |594.0MiB|
|169.smt2                                                                                   |  20.043s |881.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |28.332MiB|28.332MiB|0B| 0.0%|
|02.smt2                                                                                     |25.332MiB|25.332MiB|0B| 0.0%|
|03.smt2                                                                                     |26.224MiB|26.224MiB|0B| 0.0%|
|04.smt2                                                                                     |23.78MiB|23.78MiB|0B| 0.0%|
|05.smt2                                                                                     |27.392MiB|27.392MiB|0B| 0.0%|
|06.smt2                                                                                     |20.124MiB|20.124MiB|0B| 0.0%|
|07.smt2                                                                                     |23.916MiB|23.916MiB|0B| 0.0%|
|08.smt2                                                                                     |22.052MiB|22.052MiB|0B| 0.0%|
|09.smt2                                                                                     |23.284MiB|23.284MiB|0B| 0.0%|
|10.smt2                                                                                     |25.172MiB|25.172MiB|0B| 0.0%|
|100.smt2                                                                                    |30.992MiB|30.992MiB|0B| 0.0%|
|101.smt2                                                                                    |27.592MiB|27.592MiB|0B| 0.0%|
|102.smt2                                                                                    |35.316MiB|35.316MiB|0B| 0.0%|
|103.smt2                                                                                    |30.98MiB|30.98MiB|0B| 0.0%|
|104.smt2                                                                                    |33.916MiB|33.916MiB|0B| 0.0%|
|105.smt2                                                                                    |99.0MiB|99.0MiB|0B| 0.0%|
|106.smt2                                                                                    |119.0MiB|119.0MiB|0B| 0.0%|
|107.smt2                                                                                    |26.296MiB|26.296MiB|0B| 0.0%|
|108.smt2                                                                                    |98.0MiB|98.0MiB|0B| 0.0%|
|109.smt2                                                                                    |27.144MiB|27.144MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |28.332MiB|28.332MiB|0B| 0.0%|
|02.smt2                                                                                     |25.332MiB|25.332MiB|0B| 0.0%|
|03.smt2                                                                                     |26.224MiB|26.224MiB|0B| 0.0%|
|04.smt2                                                                                     |23.78MiB|23.78MiB|0B| 0.0%|
|05.smt2                                                                                     |27.392MiB|27.392MiB|0B| 0.0%|
|06.smt2                                                                                     |20.124MiB|20.124MiB|0B| 0.0%|
|07.smt2                                                                                     |23.916MiB|23.916MiB|0B| 0.0%|
|08.smt2                                                                                     |22.052MiB|22.052MiB|0B| 0.0%|
|09.smt2                                                                                     |23.284MiB|23.284MiB|0B| 0.0%|
|10.smt2                                                                                     |25.172MiB|25.172MiB|0B| 0.0%|
|100.smt2                                                                                    |30.992MiB|30.992MiB|0B| 0.0%|
|101.smt2                                                                                    |27.592MiB|27.592MiB|0B| 0.0%|
|102.smt2                                                                                    |35.316MiB|35.316MiB|0B| 0.0%|
|103.smt2                                                                                    |30.98MiB|30.98MiB|0B| 0.0%|
|104.smt2                                                                                    |33.916MiB|33.916MiB|0B| 0.0%|
|105.smt2                                                                                    |99.0MiB|99.0MiB|0B| 0.0%|
|106.smt2                                                                                    |119.0MiB|119.0MiB|0B| 0.0%|
|107.smt2                                                                                    |26.296MiB|26.296MiB|0B| 0.0%|
|108.smt2                                                                                    |98.0MiB|98.0MiB|0B| 0.0%|
|109.smt2                                                                                    |27.144MiB|27.144MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |28.332MiB|28.332MiB|0B| 0.0%|
|02.smt2                                                                                     |25.332MiB|25.332MiB|0B| 0.0%|
|03.smt2                                                                                     |26.224MiB|26.224MiB|0B| 0.0%|
|04.smt2                                                                                     |23.78MiB|23.78MiB|0B| 0.0%|
|05.smt2                                                                                     |27.392MiB|27.392MiB|0B| 0.0%|
|06.smt2                                                                                     |20.124MiB|20.124MiB|0B| 0.0%|
|07.smt2                                                                                     |23.916MiB|23.916MiB|0B| 0.0%|
|08.smt2                                                                                     |22.052MiB|22.052MiB|0B| 0.0%|
|09.smt2                                                                                     |23.284MiB|23.284MiB|0B| 0.0%|
|10.smt2                                                                                     |25.172MiB|25.172MiB|0B| 0.0%|
|100.smt2                                                                                    |30.992MiB|30.992MiB|0B| 0.0%|
|101.smt2                                                                                    |27.592MiB|27.592MiB|0B| 0.0%|
|102.smt2                                                                                    |35.316MiB|35.316MiB|0B| 0.0%|
|103.smt2                                                                                    |30.98MiB|30.98MiB|0B| 0.0%|
|104.smt2                                                                                    |33.916MiB|33.916MiB|0B| 0.0%|
|105.smt2                                                                                    |99.0MiB|99.0MiB|0B| 0.0%|
|106.smt2                                                                                    |119.0MiB|119.0MiB|0B| 0.0%|
|107.smt2                                                                                    |26.296MiB|26.296MiB|0B| 0.0%|
|108.smt2                                                                                    |98.0MiB|98.0MiB|0B| 0.0%|
|109.smt2                                                                                    |27.144MiB|27.144MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |28.332MiB|28.332MiB|0B| 0.0%|
|02.smt2                                                                                     |25.332MiB|25.332MiB|0B| 0.0%|
|03.smt2                                                                                     |26.224MiB|26.224MiB|0B| 0.0%|
|04.smt2                                                                                     |23.78MiB|23.78MiB|0B| 0.0%|
|05.smt2                                                                                     |27.392MiB|27.392MiB|0B| 0.0%|
|06.smt2                                                                                     |20.124MiB|20.124MiB|0B| 0.0%|
|07.smt2                                                                                     |23.916MiB|23.916MiB|0B| 0.0%|
|08.smt2                                                                                     |22.052MiB|22.052MiB|0B| 0.0%|
|09.smt2                                                                                     |23.284MiB|23.284MiB|0B| 0.0%|
|10.smt2                                                                                     |25.172MiB|25.172MiB|0B| 0.0%|
|100.smt2                                                                                    |30.992MiB|30.992MiB|0B| 0.0%|
|101.smt2                                                                                    |27.592MiB|27.592MiB|0B| 0.0%|
|102.smt2                                                                                    |35.316MiB|35.316MiB|0B| 0.0%|
|103.smt2                                                                                    |30.98MiB|30.98MiB|0B| 0.0%|
|104.smt2                                                                                    |33.916MiB|33.916MiB|0B| 0.0%|
|105.smt2                                                                                    |99.0MiB|99.0MiB|0B| 0.0%|
|106.smt2                                                                                    |119.0MiB|119.0MiB|0B| 0.0%|
|107.smt2                                                                                    |26.296MiB|26.296MiB|0B| 0.0%|
|108.smt2                                                                                    |98.0MiB|98.0MiB|0B| 0.0%|
|109.smt2                                                                                    |27.144MiB|27.144MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|182.smt2                                                                                   |  20.193s |3249.0MiB|
|183.smt2                                                                                   |  20.142s |3247.0MiB|
|181.smt2                                                                                   |  20.079s |3034.0MiB|
|178.smt2                                                                                   |  20.174s |2441.0MiB|
|176.smt2                                                                                   |  20.105s |2402.0MiB|
|179.smt2                                                                                   |  20.065s |2258.0MiB|
|180.smt2                                                                                   |  20.135s |2257.0MiB|
|172.smt2                                                                                   |  20.088s |2036.0MiB|
|173.smt2                                                                                   |  20.093s |1685.0MiB|
|174.smt2                                                                                   |  20.119s |1649.0MiB|
|175.smt2                                                                                   |  20.093s |1649.0MiB|
|169.smt2                                                                                   |  20.043s |881.0MiB|
|165.smt2                                                                                   |  20.019s |609.0MiB|
|158.smt2                                                                                   |  20.063s |599.0MiB|
|163.smt2                                                                                   |  20.048s |599.0MiB|
|168.smt2                                                                                   |  20.047s |594.0MiB|
|160.smt2                                                                                   |  20.039s |566.0MiB|
|171.smt2                                                                                   |  19.823s |548.0MiB|
|161.smt2                                                                                   |  20.027s |440.0MiB|
|159.smt2                                                                                   |  20.029s |432.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|182.smt2                                                                                   |  20.193s |3249.0MiB|
|183.smt2                                                                                   |  20.142s |3247.0MiB|
|181.smt2                                                                                   |  20.079s |3034.0MiB|
|178.smt2                                                                                   |  20.174s |2441.0MiB|
|176.smt2                                                                                   |  20.105s |2402.0MiB|
|179.smt2                                                                                   |  20.065s |2258.0MiB|
|180.smt2                                                                                   |  20.135s |2257.0MiB|
|172.smt2                                                                                   |  20.088s |2036.0MiB|
|173.smt2                                                                                   |  20.093s |1685.0MiB|
|174.smt2                                                                                   |  20.119s |1649.0MiB|
|175.smt2                                                                                   |  20.093s |1649.0MiB|
|169.smt2                                                                                   |  20.043s |881.0MiB|
|165.smt2                                                                                   |  20.019s |609.0MiB|
|158.smt2                                                                                   |  20.063s |599.0MiB|
|163.smt2                                                                                   |  20.048s |599.0MiB|
|168.smt2                                                                                   |  20.047s |594.0MiB|
|160.smt2                                                                                   |  20.039s |566.0MiB|
|171.smt2                                                                                   |  19.823s |548.0MiB|
|161.smt2                                                                                   |  20.027s |440.0MiB|
|159.smt2                                                                                   |  20.029s |432.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  17.305s  |  17.305s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   4.777s  |   4.777s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.795s  |   0.795s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   0.922s  |   0.922s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|110.smt2                                                                                    |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|112.smt2                                                                                    |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|114.smt2                                                                                    |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|116.smt2                                                                                    |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|117.smt2                                                                                    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|118.smt2                                                                                    |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|119.smt2                                                                                    |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|12.smt2                                                                                     |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|120.smt2                                                                                    |  19.856s  |  19.856s  |   0.000s  | 0.0%|
|121.smt2                                                                                    |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|122.smt2                                                                                    |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|123.smt2                                                                                    |  15.200s  |  15.200s  |   0.000s  | 0.0%|
|124.smt2                                                                                    |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|125.smt2                                                                                    |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|126.smt2                                                                                    |  18.867s  |  18.867s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|128.smt2                                                                                    |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|129.smt2                                                                                    |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|13.smt2                                                                                     |   2.009s  |   2.009s  |   0.000s  | 0.0%|
|130.smt2                                                                                    |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|131.smt2                                                                                    |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|132.smt2                                                                                    |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|133.smt2                                                                                    |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|134.smt2                                                                                    |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|135.smt2                                                                                    |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|136.smt2                                                                                    |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|137.smt2                                                                                    |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|138.smt2                                                                                    |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|139.smt2                                                                                    |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|14.smt2                                                                                     |   1.333s  |   1.333s  |   0.000s  | 0.0%|
|140.smt2                                                                                    |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|141.smt2                                                                                    |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|142.smt2                                                                                    |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|143.smt2                                                                                    |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|144.smt2                                                                                    |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|145.smt2                                                                                    |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|146.smt2                                                                                    |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|147.smt2                                                                                    |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|148.smt2                                                                                    |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |   5.080s  |   5.080s  |   0.000s  | 0.0%|
|150.smt2                                                                                    |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|151.smt2                                                                                    |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|152.smt2                                                                                    |   9.170s  |   9.170s  |   0.000s  | 0.0%|
|153.smt2                                                                                    |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|154.smt2                                                                                    |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|155.smt2                                                                                    |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|156.smt2                                                                                    |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|157.smt2                                                                                    |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|158.smt2                                                                                    |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|159.smt2                                                                                    |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|16.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|160.smt2                                                                                    |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|161.smt2                                                                                    |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|163.smt2                                                                                    |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|164.smt2                                                                                    |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|165.smt2                                                                                    |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|166.smt2                                                                                    |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|168.smt2                                                                                    |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|169.smt2                                                                                    |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|17.smt2                                                                                     |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|171.smt2                                                                                    |  19.823s  |  19.823s  |   0.000s  | 0.0%|
|172.smt2                                                                                    |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|173.smt2                                                                                    |  20.093s  |  20.093s  |   0.000s  | 0.0%|
|174.smt2                                                                                    |  20.119s  |  20.119s  |   0.000s  | 0.0%|
|175.smt2                                                                                    |  20.093s  |  20.093s  |   0.000s  | 0.0%|
|176.smt2                                                                                    |  20.105s  |  20.105s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |   1.817s  |   1.817s  |   0.000s  | 0.0%|
|178.smt2                                                                                    |  20.174s  |  20.174s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|18.smt2                                                                                     |  20.345s  |  20.345s  |   0.000s  | 0.0%|
|180.smt2                                                                                    |  20.135s  |  20.135s  |   0.000s  | 0.0%|
|181.smt2                                                                                    |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|182.smt2                                                                                    |  20.193s  |  20.193s  |   0.000s  | 0.0%|
|183.smt2                                                                                    |  20.142s  |  20.142s  |   0.000s  | 0.0%|
|184.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|185.smt2                                                                                    |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|186.smt2                                                                                    |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|19.smt2                                                                                     |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  19.936s  |  19.936s  |   0.000s  | 0.0%|
|21.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|22.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|24.smt2                                                                                     |  19.931s  |  19.931s  |   0.000s  | 0.0%|
|25.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|27.smt2                                                                                     |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|28.smt2                                                                                     |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|30.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|31.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|32.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |   7.951s  |   7.951s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|35.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|36.smt2                                                                                     |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|37.smt2                                                                                     |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|38.smt2                                                                                     |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|39.smt2                                                                                     |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|40.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|42.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|43.smt2                                                                                     |   1.949s  |   1.949s  |   0.000s  | 0.0%|
|44.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|45.smt2                                                                                     |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|46.smt2                                                                                     |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|47.smt2                                                                                     |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|48.smt2                                                                                     |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|49.smt2                                                                                     |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|50.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|51.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|52.smt2                                                                                     |  20.180s  |  20.180s  |   0.000s  | 0.0%|
|53.smt2                                                                                     |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|54.smt2                                                                                     |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|55.smt2                                                                                     |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|56.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|57.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|58.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|59.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|60.smt2                                                                                     |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|61.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|62.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|63.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|65.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|66.smt2                                                                                     |  20.505s  |  20.505s  |   0.000s  | 0.0%|
|67.smt2                                                                                     |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|68.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|69.smt2                                                                                     |  19.930s  |  19.930s  |   0.000s  | 0.0%|
|70.smt2                                                                                     |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|71.smt2                                                                                     |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|72.smt2                                                                                     |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|73.smt2                                                                                     |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|76.smt2                                                                                     |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|77.smt2                                                                                     |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|78.smt2                                                                                     |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|79.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|81.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|82.smt2                                                                                     |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|84.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|85.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|86.smt2                                                                                     |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|87.smt2                                                                                     |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|88.smt2                                                                                     |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|89.smt2                                                                                     |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  20.089s  |  20.089s  |   0.000s  | 0.0%|
|91.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|92.smt2                                                                                     |  19.841s  |  19.841s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|95.smt2                                                                                     |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|96.smt2                                                                                     |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|97.smt2                                                                                     |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  19.987s  |  19.987s  |   0.000s  | 0.0%|
</details>
