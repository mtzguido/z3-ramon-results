Comparing data and data


# SUMMARY
- LHS tests = 186
- RHS tests = 186
- LHS success = 185  (99.46236559139786%)
- RHS success = 185  (99.46236559139786%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: with lookahead
Job tag: smt-sls-lookahead
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: fa22b646aa5965a8e4d79eef54e26707fe9931fc
Z3 branch: master
Z3 options: "-T:20 -v:2 -st sls.arith_use_lookahead=true tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: address some build warnings.

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: with lookahead
Job tag: smt-sls-lookahead
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: fa22b646aa5965a8e4d79eef54e26707fe9931fc
Z3 branch: master
Z3 options: "-T:20 -v:2 -st sls.arith_use_lookahead=true tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: address some build warnings.

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.899s  |  19.899s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  19.006s  |  19.006s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   1.133s  |   1.133s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.298s  |  19.298s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.607s  |   0.607s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.270s  |  19.270s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  18.001s  |  18.001s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |  11.007s  |  11.007s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  19.386s  |  19.386s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.737s  |  19.737s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.940s  |  19.940s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  18.150s  |  18.150s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.174s  |  19.174s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  18.891s  |  18.891s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.899s  |  19.899s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  19.006s  |  19.006s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   1.133s  |   1.133s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.298s  |  19.298s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.607s  |   0.607s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.270s  |  19.270s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  18.001s  |  18.001s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |  11.007s  |  11.007s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  19.386s  |  19.386s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.737s  |  19.737s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.940s  |  19.940s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  18.150s  |  18.150s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.174s  |  19.174s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  18.891s  |  18.891s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.899s  |  19.899s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  19.006s  |  19.006s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   1.133s  |   1.133s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.298s  |  19.298s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.607s  |   0.607s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.270s  |  19.270s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  18.001s  |  18.001s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |  11.007s  |  11.007s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  19.386s  |  19.386s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.737s  |  19.737s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.940s  |  19.940s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  18.150s  |  18.150s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.174s  |  19.174s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  18.891s  |  18.891s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.899s  |  19.899s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  19.006s  |  19.006s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   1.133s  |   1.133s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.298s  |  19.298s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.607s  |   0.607s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.270s  |  19.270s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  18.001s  |  18.001s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |  11.007s  |  11.007s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  19.386s  |  19.386s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.737s  |  19.737s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.940s  |  19.940s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  18.150s  |  18.150s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.174s  |  19.174s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  18.891s  |  18.891s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|73.smt2                                                                                    |  20.422s |22.6MiB|
|87.smt2                                                                                    |  20.061s |21.08MiB|
|58.smt2                                                                                    |  20.060s |24.38MiB|
|185.smt2                                                                                   |  20.018s |245.0MiB|
|135.smt2                                                                                   |  20.017s |41.232MiB|
|169.smt2                                                                                   |  20.017s |92.54MiB|
|35.smt2                                                                                    |  20.011s |22.996MiB|
|172.smt2                                                                                   |  20.008s |176.0MiB|
|158.smt2                                                                                   |  20.007s |65.932MiB|
|32.smt2                                                                                    |  20.005s |22.224MiB|
|78.smt2                                                                                    |  20.003s |25.644MiB|
|123.smt2                                                                                   |  20.003s |31.132MiB|
|31.smt2                                                                                    |  20.001s |23.26MiB|
|136.smt2                                                                                   |  20.000s |38.592MiB|
|25.smt2                                                                                    |  19.998s |22.224MiB|
|54.smt2                                                                                    |  19.998s |23.348MiB|
|85.smt2                                                                                    |  19.997s |22.456MiB|
|22.smt2                                                                                    |  19.997s |23.416MiB|
|57.smt2                                                                                    |  19.997s |24.396MiB|
|95.smt2                                                                                    |  19.996s |23.456MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|73.smt2                                                                                    |  20.422s |22.6MiB|
|87.smt2                                                                                    |  20.061s |21.08MiB|
|58.smt2                                                                                    |  20.060s |24.38MiB|
|185.smt2                                                                                   |  20.018s |245.0MiB|
|135.smt2                                                                                   |  20.017s |41.232MiB|
|169.smt2                                                                                   |  20.017s |92.54MiB|
|35.smt2                                                                                    |  20.011s |22.996MiB|
|172.smt2                                                                                   |  20.008s |176.0MiB|
|158.smt2                                                                                   |  20.007s |65.932MiB|
|32.smt2                                                                                    |  20.005s |22.224MiB|
|78.smt2                                                                                    |  20.003s |25.644MiB|
|123.smt2                                                                                   |  20.003s |31.132MiB|
|31.smt2                                                                                    |  20.001s |23.26MiB|
|136.smt2                                                                                   |  20.000s |38.592MiB|
|25.smt2                                                                                    |  19.998s |22.224MiB|
|54.smt2                                                                                    |  19.998s |23.348MiB|
|85.smt2                                                                                    |  19.997s |22.456MiB|
|22.smt2                                                                                    |  19.997s |23.416MiB|
|57.smt2                                                                                    |  19.997s |24.396MiB|
|95.smt2                                                                                    |  19.996s |23.456MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |22.572MiB|22.572MiB|0B| 0.0%|
|02.smt2                                                                                     |22.0MiB|22.0MiB|0B| 0.0%|
|03.smt2                                                                                     |22.184MiB|22.184MiB|0B| 0.0%|
|04.smt2                                                                                     |21.336MiB|21.336MiB|0B| 0.0%|
|05.smt2                                                                                     |22.312MiB|22.312MiB|0B| 0.0%|
|06.smt2                                                                                     |20.02MiB|20.02MiB|0B| 0.0%|
|07.smt2                                                                                     |21.82MiB|21.82MiB|0B| 0.0%|
|08.smt2                                                                                     |20.74MiB|20.74MiB|0B| 0.0%|
|09.smt2                                                                                     |21.132MiB|21.132MiB|0B| 0.0%|
|10.smt2                                                                                     |22.1MiB|22.1MiB|0B| 0.0%|
|100.smt2                                                                                    |23.292MiB|23.292MiB|0B| 0.0%|
|101.smt2                                                                                    |22.344MiB|22.344MiB|0B| 0.0%|
|102.smt2                                                                                    |24.384MiB|24.384MiB|0B| 0.0%|
|103.smt2                                                                                    |23.46MiB|23.46MiB|0B| 0.0%|
|104.smt2                                                                                    |24.316MiB|24.316MiB|0B| 0.0%|
|106.smt2                                                                                    |36.892MiB|36.892MiB|0B| 0.0%|
|107.smt2                                                                                    |22.244MiB|22.244MiB|0B| 0.0%|
|108.smt2                                                                                    |33.36MiB|33.36MiB|0B| 0.0%|
|109.smt2                                                                                    |22.816MiB|22.816MiB|0B| 0.0%|
|11.smt2                                                                                     |21.084MiB|21.084MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |22.572MiB|22.572MiB|0B| 0.0%|
|02.smt2                                                                                     |22.0MiB|22.0MiB|0B| 0.0%|
|03.smt2                                                                                     |22.184MiB|22.184MiB|0B| 0.0%|
|04.smt2                                                                                     |21.336MiB|21.336MiB|0B| 0.0%|
|05.smt2                                                                                     |22.312MiB|22.312MiB|0B| 0.0%|
|06.smt2                                                                                     |20.02MiB|20.02MiB|0B| 0.0%|
|07.smt2                                                                                     |21.82MiB|21.82MiB|0B| 0.0%|
|08.smt2                                                                                     |20.74MiB|20.74MiB|0B| 0.0%|
|09.smt2                                                                                     |21.132MiB|21.132MiB|0B| 0.0%|
|10.smt2                                                                                     |22.1MiB|22.1MiB|0B| 0.0%|
|100.smt2                                                                                    |23.292MiB|23.292MiB|0B| 0.0%|
|101.smt2                                                                                    |22.344MiB|22.344MiB|0B| 0.0%|
|102.smt2                                                                                    |24.384MiB|24.384MiB|0B| 0.0%|
|103.smt2                                                                                    |23.46MiB|23.46MiB|0B| 0.0%|
|104.smt2                                                                                    |24.316MiB|24.316MiB|0B| 0.0%|
|106.smt2                                                                                    |36.892MiB|36.892MiB|0B| 0.0%|
|107.smt2                                                                                    |22.244MiB|22.244MiB|0B| 0.0%|
|108.smt2                                                                                    |33.36MiB|33.36MiB|0B| 0.0%|
|109.smt2                                                                                    |22.816MiB|22.816MiB|0B| 0.0%|
|11.smt2                                                                                     |21.084MiB|21.084MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |22.572MiB|22.572MiB|0B| 0.0%|
|02.smt2                                                                                     |22.0MiB|22.0MiB|0B| 0.0%|
|03.smt2                                                                                     |22.184MiB|22.184MiB|0B| 0.0%|
|04.smt2                                                                                     |21.336MiB|21.336MiB|0B| 0.0%|
|05.smt2                                                                                     |22.312MiB|22.312MiB|0B| 0.0%|
|06.smt2                                                                                     |20.02MiB|20.02MiB|0B| 0.0%|
|07.smt2                                                                                     |21.82MiB|21.82MiB|0B| 0.0%|
|08.smt2                                                                                     |20.74MiB|20.74MiB|0B| 0.0%|
|09.smt2                                                                                     |21.132MiB|21.132MiB|0B| 0.0%|
|10.smt2                                                                                     |22.1MiB|22.1MiB|0B| 0.0%|
|100.smt2                                                                                    |23.292MiB|23.292MiB|0B| 0.0%|
|101.smt2                                                                                    |22.344MiB|22.344MiB|0B| 0.0%|
|102.smt2                                                                                    |24.384MiB|24.384MiB|0B| 0.0%|
|103.smt2                                                                                    |23.46MiB|23.46MiB|0B| 0.0%|
|104.smt2                                                                                    |24.316MiB|24.316MiB|0B| 0.0%|
|106.smt2                                                                                    |36.892MiB|36.892MiB|0B| 0.0%|
|107.smt2                                                                                    |22.244MiB|22.244MiB|0B| 0.0%|
|108.smt2                                                                                    |33.36MiB|33.36MiB|0B| 0.0%|
|109.smt2                                                                                    |22.816MiB|22.816MiB|0B| 0.0%|
|11.smt2                                                                                     |21.084MiB|21.084MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |22.572MiB|22.572MiB|0B| 0.0%|
|02.smt2                                                                                     |22.0MiB|22.0MiB|0B| 0.0%|
|03.smt2                                                                                     |22.184MiB|22.184MiB|0B| 0.0%|
|04.smt2                                                                                     |21.336MiB|21.336MiB|0B| 0.0%|
|05.smt2                                                                                     |22.312MiB|22.312MiB|0B| 0.0%|
|06.smt2                                                                                     |20.02MiB|20.02MiB|0B| 0.0%|
|07.smt2                                                                                     |21.82MiB|21.82MiB|0B| 0.0%|
|08.smt2                                                                                     |20.74MiB|20.74MiB|0B| 0.0%|
|09.smt2                                                                                     |21.132MiB|21.132MiB|0B| 0.0%|
|10.smt2                                                                                     |22.1MiB|22.1MiB|0B| 0.0%|
|100.smt2                                                                                    |23.292MiB|23.292MiB|0B| 0.0%|
|101.smt2                                                                                    |22.344MiB|22.344MiB|0B| 0.0%|
|102.smt2                                                                                    |24.384MiB|24.384MiB|0B| 0.0%|
|103.smt2                                                                                    |23.46MiB|23.46MiB|0B| 0.0%|
|104.smt2                                                                                    |24.316MiB|24.316MiB|0B| 0.0%|
|106.smt2                                                                                    |36.892MiB|36.892MiB|0B| 0.0%|
|107.smt2                                                                                    |22.244MiB|22.244MiB|0B| 0.0%|
|108.smt2                                                                                    |33.36MiB|33.36MiB|0B| 0.0%|
|109.smt2                                                                                    |22.816MiB|22.816MiB|0B| 0.0%|
|11.smt2                                                                                     |21.084MiB|21.084MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|182.smt2                                                                                   |  19.591s |321.0MiB|
|183.smt2                                                                                   |  18.661s |320.0MiB|
|185.smt2                                                                                   |  20.018s |245.0MiB|
|186.smt2                                                                                   |  19.894s |245.0MiB|
|178.smt2                                                                                   |  19.470s |188.0MiB|
|181.smt2                                                                                   |  19.919s |183.0MiB|
|180.smt2                                                                                   |  19.782s |179.0MiB|
|179.smt2                                                                                   |  19.389s |179.0MiB|
|172.smt2                                                                                   |  20.008s |176.0MiB|
|176.smt2                                                                                   |  19.965s |176.0MiB|
|173.smt2                                                                                   |  18.299s |158.0MiB|
|175.smt2                                                                                   |  19.960s |152.0MiB|
|174.smt2                                                                                   |  19.832s |152.0MiB|
|184.smt2                                                                                   |  19.465s |136.0MiB|
|165.smt2                                                                                   |  18.994s |93.024MiB|
|169.smt2                                                                                   |  20.017s |92.54MiB|
|163.smt2                                                                                   |  19.770s |90.96MiB|
|161.smt2                                                                                   |  18.929s |89.944MiB|
|168.smt2                                                                                   |  18.788s |76.912MiB|
|171.smt2                                                                                   |  19.981s |68.516MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|182.smt2                                                                                   |  19.591s |321.0MiB|
|183.smt2                                                                                   |  18.661s |320.0MiB|
|185.smt2                                                                                   |  20.018s |245.0MiB|
|186.smt2                                                                                   |  19.894s |245.0MiB|
|178.smt2                                                                                   |  19.470s |188.0MiB|
|181.smt2                                                                                   |  19.919s |183.0MiB|
|180.smt2                                                                                   |  19.782s |179.0MiB|
|179.smt2                                                                                   |  19.389s |179.0MiB|
|172.smt2                                                                                   |  20.008s |176.0MiB|
|176.smt2                                                                                   |  19.965s |176.0MiB|
|173.smt2                                                                                   |  18.299s |158.0MiB|
|175.smt2                                                                                   |  19.960s |152.0MiB|
|174.smt2                                                                                   |  19.832s |152.0MiB|
|184.smt2                                                                                   |  19.465s |136.0MiB|
|165.smt2                                                                                   |  18.994s |93.024MiB|
|169.smt2                                                                                   |  20.017s |92.54MiB|
|163.smt2                                                                                   |  19.770s |90.96MiB|
|161.smt2                                                                                   |  18.929s |89.944MiB|
|168.smt2                                                                                   |  18.788s |76.912MiB|
|171.smt2                                                                                   |  19.981s |68.516MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.899s  |  19.899s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  19.006s  |  19.006s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   1.133s  |   1.133s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.298s  |  19.298s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.607s  |   0.607s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.270s  |  19.270s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  18.001s  |  18.001s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |  11.007s  |  11.007s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  19.386s  |  19.386s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.737s  |  19.737s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.940s  |  19.940s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  18.150s  |  18.150s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.174s  |  19.174s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  18.891s  |  18.891s  |   0.000s  | 0.0%|
|110.smt2                                                                                    |  19.568s  |  19.568s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  19.925s  |  19.925s  |   0.000s  | 0.0%|
|112.smt2                                                                                    |  19.925s  |  19.925s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|114.smt2                                                                                    |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|116.smt2                                                                                    |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|117.smt2                                                                                    |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|118.smt2                                                                                    |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|119.smt2                                                                                    |  14.557s  |  14.557s  |   0.000s  | 0.0%|
|12.smt2                                                                                     |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|120.smt2                                                                                    |  19.761s  |  19.761s  |   0.000s  | 0.0%|
|121.smt2                                                                                    |  19.267s  |  19.267s  |   0.000s  | 0.0%|
|122.smt2                                                                                    |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|123.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|124.smt2                                                                                    |  17.859s  |  17.859s  |   0.000s  | 0.0%|
|125.smt2                                                                                    |  19.873s  |  19.873s  |   0.000s  | 0.0%|
|126.smt2                                                                                    |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |  19.848s  |  19.848s  |   0.000s  | 0.0%|
|128.smt2                                                                                    |  19.710s  |  19.710s  |   0.000s  | 0.0%|
|129.smt2                                                                                    |  18.934s  |  18.934s  |   0.000s  | 0.0%|
|13.smt2                                                                                     |  19.195s  |  19.195s  |   0.000s  | 0.0%|
|130.smt2                                                                                    |  19.709s  |  19.709s  |   0.000s  | 0.0%|
|131.smt2                                                                                    |  19.929s  |  19.929s  |   0.000s  | 0.0%|
|132.smt2                                                                                    |  19.742s  |  19.742s  |   0.000s  | 0.0%|
|133.smt2                                                                                    |  19.823s  |  19.823s  |   0.000s  | 0.0%|
|134.smt2                                                                                    |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|135.smt2                                                                                    |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|136.smt2                                                                                    |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|137.smt2                                                                                    |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|138.smt2                                                                                    |  19.179s  |  19.179s  |   0.000s  | 0.0%|
|139.smt2                                                                                    |  19.952s  |  19.952s  |   0.000s  | 0.0%|
|14.smt2                                                                                     |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|140.smt2                                                                                    |  19.953s  |  19.953s  |   0.000s  | 0.0%|
|141.smt2                                                                                    |  19.474s  |  19.474s  |   0.000s  | 0.0%|
|142.smt2                                                                                    |  19.740s  |  19.740s  |   0.000s  | 0.0%|
|143.smt2                                                                                    |  18.436s  |  18.436s  |   0.000s  | 0.0%|
|144.smt2                                                                                    |  19.347s  |  19.347s  |   0.000s  | 0.0%|
|145.smt2                                                                                    |  18.654s  |  18.654s  |   0.000s  | 0.0%|
|146.smt2                                                                                    |  19.864s  |  19.864s  |   0.000s  | 0.0%|
|147.smt2                                                                                    |  18.967s  |  18.967s  |   0.000s  | 0.0%|
|148.smt2                                                                                    |  17.639s  |  17.639s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |  19.776s  |  19.776s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  19.640s  |  19.640s  |   0.000s  | 0.0%|
|150.smt2                                                                                    |  18.055s  |  18.055s  |   0.000s  | 0.0%|
|151.smt2                                                                                    |  19.756s  |  19.756s  |   0.000s  | 0.0%|
|152.smt2                                                                                    |   9.248s  |   9.248s  |   0.000s  | 0.0%|
|153.smt2                                                                                    |  13.700s  |  13.700s  |   0.000s  | 0.0%|
|154.smt2                                                                                    |  19.912s  |  19.912s  |   0.000s  | 0.0%|
|155.smt2                                                                                    |  19.619s  |  19.619s  |   0.000s  | 0.0%|
|156.smt2                                                                                    |  19.927s  |  19.927s  |   0.000s  | 0.0%|
|157.smt2                                                                                    |  19.231s  |  19.231s  |   0.000s  | 0.0%|
|158.smt2                                                                                    |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|159.smt2                                                                                    |  19.590s  |  19.590s  |   0.000s  | 0.0%|
|16.smt2                                                                                     |  19.747s  |  19.747s  |   0.000s  | 0.0%|
|160.smt2                                                                                    |  19.874s  |  19.874s  |   0.000s  | 0.0%|
|161.smt2                                                                                    |  18.929s  |  18.929s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|163.smt2                                                                                    |  19.770s  |  19.770s  |   0.000s  | 0.0%|
|164.smt2                                                                                    |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|165.smt2                                                                                    |  18.994s  |  18.994s  |   0.000s  | 0.0%|
|166.smt2                                                                                    |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |  19.884s  |  19.884s  |   0.000s  | 0.0%|
|168.smt2                                                                                    |  18.788s  |  18.788s  |   0.000s  | 0.0%|
|169.smt2                                                                                    |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|17.smt2                                                                                     |  16.617s  |  16.617s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|171.smt2                                                                                    |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|172.smt2                                                                                    |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|173.smt2                                                                                    |  18.299s  |  18.299s  |   0.000s  | 0.0%|
|174.smt2                                                                                    |  19.832s  |  19.832s  |   0.000s  | 0.0%|
|175.smt2                                                                                    |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|176.smt2                                                                                    |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |   2.197s  |   2.197s  |   0.000s  | 0.0%|
|178.smt2                                                                                    |  19.470s  |  19.470s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |  19.389s  |  19.389s  |   0.000s  | 0.0%|
|18.smt2                                                                                     |  16.651s  |  16.651s  |   0.000s  | 0.0%|
|180.smt2                                                                                    |  19.782s  |  19.782s  |   0.000s  | 0.0%|
|181.smt2                                                                                    |  19.919s  |  19.919s  |   0.000s  | 0.0%|
|182.smt2                                                                                    |  19.591s  |  19.591s  |   0.000s  | 0.0%|
|183.smt2                                                                                    |  18.661s  |  18.661s  |   0.000s  | 0.0%|
|184.smt2                                                                                    |  19.465s  |  19.465s  |   0.000s  | 0.0%|
|185.smt2                                                                                    |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|186.smt2                                                                                    |  19.894s  |  19.894s  |   0.000s  | 0.0%|
|19.smt2                                                                                     |  19.258s  |  19.258s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  19.633s  |  19.633s  |   0.000s  | 0.0%|
|21.smt2                                                                                     |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|22.smt2                                                                                     |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |  18.345s  |  18.345s  |   0.000s  | 0.0%|
|24.smt2                                                                                     |  19.743s  |  19.743s  |   0.000s  | 0.0%|
|25.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  19.914s  |  19.914s  |   0.000s  | 0.0%|
|27.smt2                                                                                     |  19.032s  |  19.032s  |   0.000s  | 0.0%|
|28.smt2                                                                                     |  19.879s  |  19.879s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  19.589s  |  19.589s  |   0.000s  | 0.0%|
|30.smt2                                                                                     |  15.634s  |  15.634s  |   0.000s  | 0.0%|
|31.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|32.smt2                                                                                     |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.769s  |  19.769s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|35.smt2                                                                                     |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|36.smt2                                                                                     |  17.127s  |  17.127s  |   0.000s  | 0.0%|
|37.smt2                                                                                     |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|38.smt2                                                                                     |  19.031s  |  19.031s  |   0.000s  | 0.0%|
|39.smt2                                                                                     |  19.320s  |  19.320s  |   0.000s  | 0.0%|
|40.smt2                                                                                     |  19.162s  |  19.162s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|42.smt2                                                                                     |  18.549s  |  18.549s  |   0.000s  | 0.0%|
|43.smt2                                                                                     |   0.656s  |   0.656s  |   0.000s  | 0.0%|
|44.smt2                                                                                     |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|45.smt2                                                                                     |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|46.smt2                                                                                     |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|47.smt2                                                                                     |  19.858s  |  19.858s  |   0.000s  | 0.0%|
|48.smt2                                                                                     |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|49.smt2                                                                                     |  19.034s  |  19.034s  |   0.000s  | 0.0%|
|50.smt2                                                                                     |  19.875s  |  19.875s  |   0.000s  | 0.0%|
|51.smt2                                                                                     |  19.770s  |  19.770s  |   0.000s  | 0.0%|
|52.smt2                                                                                     |  19.066s  |  19.066s  |   0.000s  | 0.0%|
|53.smt2                                                                                     |  19.662s  |  19.662s  |   0.000s  | 0.0%|
|54.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|55.smt2                                                                                     |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|56.smt2                                                                                     |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|57.smt2                                                                                     |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|58.smt2                                                                                     |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|59.smt2                                                                                     |  19.813s  |  19.813s  |   0.000s  | 0.0%|
|60.smt2                                                                                     |  16.577s  |  16.577s  |   0.000s  | 0.0%|
|61.smt2                                                                                     |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|62.smt2                                                                                     |  19.867s  |  19.867s  |   0.000s  | 0.0%|
|63.smt2                                                                                     |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  19.161s  |  19.161s  |   0.000s  | 0.0%|
|65.smt2                                                                                     |  19.774s  |  19.774s  |   0.000s  | 0.0%|
|66.smt2                                                                                     |  19.369s  |  19.369s  |   0.000s  | 0.0%|
|67.smt2                                                                                     |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|68.smt2                                                                                     |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|69.smt2                                                                                     |  19.226s  |  19.226s  |   0.000s  | 0.0%|
|70.smt2                                                                                     |  19.914s  |  19.914s  |   0.000s  | 0.0%|
|71.smt2                                                                                     |  19.018s  |  19.018s  |   0.000s  | 0.0%|
|72.smt2                                                                                     |  19.944s  |  19.944s  |   0.000s  | 0.0%|
|73.smt2                                                                                     |  20.422s  |  20.422s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |  15.747s  |  15.747s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|76.smt2                                                                                     |  19.515s  |  19.515s  |   0.000s  | 0.0%|
|77.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|78.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|79.smt2                                                                                     |  18.956s  |  18.956s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|81.smt2                                                                                     |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|82.smt2                                                                                     |  19.539s  |  19.539s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |  19.160s  |  19.160s  |   0.000s  | 0.0%|
|84.smt2                                                                                     |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|85.smt2                                                                                     |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|86.smt2                                                                                     |  19.636s  |  19.636s  |   0.000s  | 0.0%|
|87.smt2                                                                                     |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|88.smt2                                                                                     |  19.914s  |  19.914s  |   0.000s  | 0.0%|
|89.smt2                                                                                     |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  19.752s  |  19.752s  |   0.000s  | 0.0%|
|91.smt2                                                                                     |  19.020s  |  19.020s  |   0.000s  | 0.0%|
|92.smt2                                                                                     |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |  19.395s  |  19.395s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  18.937s  |  18.937s  |   0.000s  | 0.0%|
|95.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|96.smt2                                                                                     |  16.344s  |  16.344s  |   0.000s  | 0.0%|
|97.smt2                                                                                     |  19.674s  |  19.674s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  18.792s  |  18.792s  |   0.000s  | 0.0%|
</details>
