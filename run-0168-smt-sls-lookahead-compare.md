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
Job description: with lookahead
Job tag: smt-sls-lookahead
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 9770c005926e2085d4ede18f03d56cb67d762d84
Z3 branch: master
Z3 options: "-T:20 -v:2 -st sls.arith_use_lookahead=true tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: adjust heuristic in random-inc-dec for finite domains

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: with lookahead
Job tag: smt-sls-lookahead
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 9770c005926e2085d4ede18f03d56cb67d762d84
Z3 branch: master
Z3 options: "-T:20 -v:2 -st sls.arith_use_lookahead=true tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: adjust heuristic in random-inc-dec for finite domains

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   3.288s  |   3.288s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  19.920s  |  19.920s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   5.755s  |   5.755s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.617s  |  19.617s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   3.230s  |   3.230s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  19.930s  |  19.930s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   3.288s  |   3.288s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  19.920s  |  19.920s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   5.755s  |   5.755s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.617s  |  19.617s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   3.230s  |   3.230s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  19.930s  |  19.930s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   3.288s  |   3.288s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  19.920s  |  19.920s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   5.755s  |   5.755s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.617s  |  19.617s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   3.230s  |   3.230s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  19.930s  |  19.930s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   3.288s  |   3.288s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  19.920s  |  19.920s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   5.755s  |   5.755s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.617s  |  19.617s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   3.230s  |   3.230s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  19.930s  |  19.930s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|185.smt2                                                                                   |  20.035s |245.0MiB|
|155.smt2                                                                                   |  20.013s |34.188MiB|
|180.smt2                                                                                   |  20.012s |179.0MiB|
|61.smt2                                                                                    |  20.012s |23.856MiB|
|11.smt2                                                                                    |  20.011s |21.112MiB|
|126.smt2                                                                                   |  20.008s |39.264MiB|
|35.smt2                                                                                    |  20.008s |22.764MiB|
|75.smt2                                                                                    |  20.007s |23.572MiB|
|134.smt2                                                                                   |  20.006s |38.676MiB|
|127.smt2                                                                                   |  20.006s |38.58MiB|
|169.smt2                                                                                   |  20.006s |92.12MiB|
|144.smt2                                                                                   |  20.006s |41.372MiB|
|183.smt2                                                                                   |  20.006s |321.0MiB|
|120.smt2                                                                                   |  20.005s |38.732MiB|
|140.smt2                                                                                   |  20.005s |37.844MiB|
|62.smt2                                                                                    |  20.005s |24.396MiB|
|74.smt2                                                                                    |  20.005s |24.46MiB|
|96.smt2                                                                                    |  20.004s |24.348MiB|
|174.smt2                                                                                   |  20.004s |152.0MiB|
|130.smt2                                                                                   |  20.003s |36.448MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|185.smt2                                                                                   |  20.035s |245.0MiB|
|155.smt2                                                                                   |  20.013s |34.188MiB|
|180.smt2                                                                                   |  20.012s |179.0MiB|
|61.smt2                                                                                    |  20.012s |23.856MiB|
|11.smt2                                                                                    |  20.011s |21.112MiB|
|126.smt2                                                                                   |  20.008s |39.264MiB|
|35.smt2                                                                                    |  20.008s |22.764MiB|
|75.smt2                                                                                    |  20.007s |23.572MiB|
|134.smt2                                                                                   |  20.006s |38.676MiB|
|127.smt2                                                                                   |  20.006s |38.58MiB|
|169.smt2                                                                                   |  20.006s |92.12MiB|
|144.smt2                                                                                   |  20.006s |41.372MiB|
|183.smt2                                                                                   |  20.006s |321.0MiB|
|120.smt2                                                                                   |  20.005s |38.732MiB|
|140.smt2                                                                                   |  20.005s |37.844MiB|
|62.smt2                                                                                    |  20.005s |24.396MiB|
|74.smt2                                                                                    |  20.005s |24.46MiB|
|96.smt2                                                                                    |  20.004s |24.348MiB|
|174.smt2                                                                                   |  20.004s |152.0MiB|
|130.smt2                                                                                   |  20.003s |36.448MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |22.724MiB|22.724MiB|0B| 0.0%|
|02.smt2                                                                                     |22.228MiB|22.228MiB|0B| 0.0%|
|03.smt2                                                                                     |22.168MiB|22.168MiB|0B| 0.0%|
|04.smt2                                                                                     |21.312MiB|21.312MiB|0B| 0.0%|
|05.smt2                                                                                     |22.352MiB|22.352MiB|0B| 0.0%|
|06.smt2                                                                                     |19.764MiB|19.764MiB|0B| 0.0%|
|07.smt2                                                                                     |21.78MiB|21.78MiB|0B| 0.0%|
|08.smt2                                                                                     |20.908MiB|20.908MiB|0B| 0.0%|
|09.smt2                                                                                     |21.112MiB|21.112MiB|0B| 0.0%|
|10.smt2                                                                                     |21.932MiB|21.932MiB|0B| 0.0%|
|100.smt2                                                                                    |23.384MiB|23.384MiB|0B| 0.0%|
|101.smt2                                                                                    |22.312MiB|22.312MiB|0B| 0.0%|
|102.smt2                                                                                    |24.48MiB|24.48MiB|0B| 0.0%|
|103.smt2                                                                                    |23.428MiB|23.428MiB|0B| 0.0%|
|104.smt2                                                                                    |24.3MiB|24.3MiB|0B| 0.0%|
|105.smt2                                                                                    |33.528MiB|33.528MiB|0B| 0.0%|
|106.smt2                                                                                    |36.944MiB|36.944MiB|0B| 0.0%|
|107.smt2                                                                                    |22.22MiB|22.22MiB|0B| 0.0%|
|108.smt2                                                                                    |33.804MiB|33.804MiB|0B| 0.0%|
|109.smt2                                                                                    |22.86MiB|22.86MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |22.724MiB|22.724MiB|0B| 0.0%|
|02.smt2                                                                                     |22.228MiB|22.228MiB|0B| 0.0%|
|03.smt2                                                                                     |22.168MiB|22.168MiB|0B| 0.0%|
|04.smt2                                                                                     |21.312MiB|21.312MiB|0B| 0.0%|
|05.smt2                                                                                     |22.352MiB|22.352MiB|0B| 0.0%|
|06.smt2                                                                                     |19.764MiB|19.764MiB|0B| 0.0%|
|07.smt2                                                                                     |21.78MiB|21.78MiB|0B| 0.0%|
|08.smt2                                                                                     |20.908MiB|20.908MiB|0B| 0.0%|
|09.smt2                                                                                     |21.112MiB|21.112MiB|0B| 0.0%|
|10.smt2                                                                                     |21.932MiB|21.932MiB|0B| 0.0%|
|100.smt2                                                                                    |23.384MiB|23.384MiB|0B| 0.0%|
|101.smt2                                                                                    |22.312MiB|22.312MiB|0B| 0.0%|
|102.smt2                                                                                    |24.48MiB|24.48MiB|0B| 0.0%|
|103.smt2                                                                                    |23.428MiB|23.428MiB|0B| 0.0%|
|104.smt2                                                                                    |24.3MiB|24.3MiB|0B| 0.0%|
|105.smt2                                                                                    |33.528MiB|33.528MiB|0B| 0.0%|
|106.smt2                                                                                    |36.944MiB|36.944MiB|0B| 0.0%|
|107.smt2                                                                                    |22.22MiB|22.22MiB|0B| 0.0%|
|108.smt2                                                                                    |33.804MiB|33.804MiB|0B| 0.0%|
|109.smt2                                                                                    |22.86MiB|22.86MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |22.724MiB|22.724MiB|0B| 0.0%|
|02.smt2                                                                                     |22.228MiB|22.228MiB|0B| 0.0%|
|03.smt2                                                                                     |22.168MiB|22.168MiB|0B| 0.0%|
|04.smt2                                                                                     |21.312MiB|21.312MiB|0B| 0.0%|
|05.smt2                                                                                     |22.352MiB|22.352MiB|0B| 0.0%|
|06.smt2                                                                                     |19.764MiB|19.764MiB|0B| 0.0%|
|07.smt2                                                                                     |21.78MiB|21.78MiB|0B| 0.0%|
|08.smt2                                                                                     |20.908MiB|20.908MiB|0B| 0.0%|
|09.smt2                                                                                     |21.112MiB|21.112MiB|0B| 0.0%|
|10.smt2                                                                                     |21.932MiB|21.932MiB|0B| 0.0%|
|100.smt2                                                                                    |23.384MiB|23.384MiB|0B| 0.0%|
|101.smt2                                                                                    |22.312MiB|22.312MiB|0B| 0.0%|
|102.smt2                                                                                    |24.48MiB|24.48MiB|0B| 0.0%|
|103.smt2                                                                                    |23.428MiB|23.428MiB|0B| 0.0%|
|104.smt2                                                                                    |24.3MiB|24.3MiB|0B| 0.0%|
|105.smt2                                                                                    |33.528MiB|33.528MiB|0B| 0.0%|
|106.smt2                                                                                    |36.944MiB|36.944MiB|0B| 0.0%|
|107.smt2                                                                                    |22.22MiB|22.22MiB|0B| 0.0%|
|108.smt2                                                                                    |33.804MiB|33.804MiB|0B| 0.0%|
|109.smt2                                                                                    |22.86MiB|22.86MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |22.724MiB|22.724MiB|0B| 0.0%|
|02.smt2                                                                                     |22.228MiB|22.228MiB|0B| 0.0%|
|03.smt2                                                                                     |22.168MiB|22.168MiB|0B| 0.0%|
|04.smt2                                                                                     |21.312MiB|21.312MiB|0B| 0.0%|
|05.smt2                                                                                     |22.352MiB|22.352MiB|0B| 0.0%|
|06.smt2                                                                                     |19.764MiB|19.764MiB|0B| 0.0%|
|07.smt2                                                                                     |21.78MiB|21.78MiB|0B| 0.0%|
|08.smt2                                                                                     |20.908MiB|20.908MiB|0B| 0.0%|
|09.smt2                                                                                     |21.112MiB|21.112MiB|0B| 0.0%|
|10.smt2                                                                                     |21.932MiB|21.932MiB|0B| 0.0%|
|100.smt2                                                                                    |23.384MiB|23.384MiB|0B| 0.0%|
|101.smt2                                                                                    |22.312MiB|22.312MiB|0B| 0.0%|
|102.smt2                                                                                    |24.48MiB|24.48MiB|0B| 0.0%|
|103.smt2                                                                                    |23.428MiB|23.428MiB|0B| 0.0%|
|104.smt2                                                                                    |24.3MiB|24.3MiB|0B| 0.0%|
|105.smt2                                                                                    |33.528MiB|33.528MiB|0B| 0.0%|
|106.smt2                                                                                    |36.944MiB|36.944MiB|0B| 0.0%|
|107.smt2                                                                                    |22.22MiB|22.22MiB|0B| 0.0%|
|108.smt2                                                                                    |33.804MiB|33.804MiB|0B| 0.0%|
|109.smt2                                                                                    |22.86MiB|22.86MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|183.smt2                                                                                   |  20.006s |321.0MiB|
|182.smt2                                                                                   |  19.697s |320.0MiB|
|185.smt2                                                                                   |  20.035s |245.0MiB|
|186.smt2                                                                                   |  19.982s |245.0MiB|
|178.smt2                                                                                   |  19.848s |188.0MiB|
|181.smt2                                                                                   |  19.994s |183.0MiB|
|179.smt2                                                                                   |  19.970s |180.0MiB|
|180.smt2                                                                                   |  20.012s |179.0MiB|
|172.smt2                                                                                   |  20.000s |177.0MiB|
|176.smt2                                                                                   |  19.993s |177.0MiB|
|173.smt2                                                                                   |  19.974s |159.0MiB|
|174.smt2                                                                                   |  20.004s |152.0MiB|
|175.smt2                                                                                   |  19.949s |152.0MiB|
|184.smt2                                                                                   |  19.981s |137.0MiB|
|165.smt2                                                                                   |  19.990s |92.952MiB|
|169.smt2                                                                                   |  20.006s |92.12MiB|
|161.smt2                                                                                   |  19.993s |89.336MiB|
|163.smt2                                                                                   |  19.881s |85.916MiB|
|168.smt2                                                                                   |  19.947s |76.96MiB|
|171.smt2                                                                                   |  19.875s |69.4MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|183.smt2                                                                                   |  20.006s |321.0MiB|
|182.smt2                                                                                   |  19.697s |320.0MiB|
|185.smt2                                                                                   |  20.035s |245.0MiB|
|186.smt2                                                                                   |  19.982s |245.0MiB|
|178.smt2                                                                                   |  19.848s |188.0MiB|
|181.smt2                                                                                   |  19.994s |183.0MiB|
|179.smt2                                                                                   |  19.970s |180.0MiB|
|180.smt2                                                                                   |  20.012s |179.0MiB|
|172.smt2                                                                                   |  20.000s |177.0MiB|
|176.smt2                                                                                   |  19.993s |177.0MiB|
|173.smt2                                                                                   |  19.974s |159.0MiB|
|174.smt2                                                                                   |  20.004s |152.0MiB|
|175.smt2                                                                                   |  19.949s |152.0MiB|
|184.smt2                                                                                   |  19.981s |137.0MiB|
|165.smt2                                                                                   |  19.990s |92.952MiB|
|169.smt2                                                                                   |  20.006s |92.12MiB|
|161.smt2                                                                                   |  19.993s |89.336MiB|
|163.smt2                                                                                   |  19.881s |85.916MiB|
|168.smt2                                                                                   |  19.947s |76.96MiB|
|171.smt2                                                                                   |  19.875s |69.4MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   3.288s  |   3.288s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  19.920s  |  19.920s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   5.755s  |   5.755s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.617s  |  19.617s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   3.230s  |   3.230s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  19.930s  |  19.930s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|110.smt2                                                                                    |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  19.685s  |  19.685s  |   0.000s  | 0.0%|
|112.smt2                                                                                    |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|114.smt2                                                                                    |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   1.741s  |   1.741s  |   0.000s  | 0.0%|
|116.smt2                                                                                    |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|117.smt2                                                                                    |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|118.smt2                                                                                    |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|119.smt2                                                                                    |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|12.smt2                                                                                     |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|120.smt2                                                                                    |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|121.smt2                                                                                    |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|122.smt2                                                                                    |  19.815s  |  19.815s  |   0.000s  | 0.0%|
|123.smt2                                                                                    |  19.953s  |  19.953s  |   0.000s  | 0.0%|
|124.smt2                                                                                    |  19.924s  |  19.924s  |   0.000s  | 0.0%|
|125.smt2                                                                                    |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|126.smt2                                                                                    |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|128.smt2                                                                                    |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|129.smt2                                                                                    |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|13.smt2                                                                                     |  19.926s  |  19.926s  |   0.000s  | 0.0%|
|130.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|131.smt2                                                                                    |  19.874s  |  19.874s  |   0.000s  | 0.0%|
|132.smt2                                                                                    |  19.929s  |  19.929s  |   0.000s  | 0.0%|
|133.smt2                                                                                    |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|134.smt2                                                                                    |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|135.smt2                                                                                    |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|136.smt2                                                                                    |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|137.smt2                                                                                    |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|138.smt2                                                                                    |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|139.smt2                                                                                    |  18.970s  |  18.970s  |   0.000s  | 0.0%|
|14.smt2                                                                                     |   5.132s  |   5.132s  |   0.000s  | 0.0%|
|140.smt2                                                                                    |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|141.smt2                                                                                    |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|142.smt2                                                                                    |  19.657s  |  19.657s  |   0.000s  | 0.0%|
|143.smt2                                                                                    |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|144.smt2                                                                                    |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|145.smt2                                                                                    |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|146.smt2                                                                                    |  19.918s  |  19.918s  |   0.000s  | 0.0%|
|147.smt2                                                                                    |  19.795s  |  19.795s  |   0.000s  | 0.0%|
|148.smt2                                                                                    |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|150.smt2                                                                                    |  19.914s  |  19.914s  |   0.000s  | 0.0%|
|151.smt2                                                                                    |  19.921s  |  19.921s  |   0.000s  | 0.0%|
|152.smt2                                                                                    |   5.322s  |   5.322s  |   0.000s  | 0.0%|
|153.smt2                                                                                    |  19.843s  |  19.843s  |   0.000s  | 0.0%|
|154.smt2                                                                                    |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|155.smt2                                                                                    |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|156.smt2                                                                                    |  19.278s  |  19.278s  |   0.000s  | 0.0%|
|157.smt2                                                                                    |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|158.smt2                                                                                    |  19.782s  |  19.782s  |   0.000s  | 0.0%|
|159.smt2                                                                                    |  19.834s  |  19.834s  |   0.000s  | 0.0%|
|16.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|160.smt2                                                                                    |  19.920s  |  19.920s  |   0.000s  | 0.0%|
|161.smt2                                                                                    |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|163.smt2                                                                                    |  19.881s  |  19.881s  |   0.000s  | 0.0%|
|164.smt2                                                                                    |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|165.smt2                                                                                    |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|166.smt2                                                                                    |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|168.smt2                                                                                    |  19.947s  |  19.947s  |   0.000s  | 0.0%|
|169.smt2                                                                                    |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|17.smt2                                                                                     |  19.947s  |  19.947s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|171.smt2                                                                                    |  19.875s  |  19.875s  |   0.000s  | 0.0%|
|172.smt2                                                                                    |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|173.smt2                                                                                    |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|174.smt2                                                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|175.smt2                                                                                    |  19.949s  |  19.949s  |   0.000s  | 0.0%|
|176.smt2                                                                                    |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |   1.572s  |   1.572s  |   0.000s  | 0.0%|
|178.smt2                                                                                    |  19.848s  |  19.848s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|18.smt2                                                                                     |  19.900s  |  19.900s  |   0.000s  | 0.0%|
|180.smt2                                                                                    |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|181.smt2                                                                                    |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|182.smt2                                                                                    |  19.697s  |  19.697s  |   0.000s  | 0.0%|
|183.smt2                                                                                    |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|184.smt2                                                                                    |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|185.smt2                                                                                    |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|186.smt2                                                                                    |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|19.smt2                                                                                     |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|21.smt2                                                                                     |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|22.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|24.smt2                                                                                     |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|25.smt2                                                                                     |  19.758s  |  19.758s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|27.smt2                                                                                     |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|28.smt2                                                                                     |  19.875s  |  19.875s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|30.smt2                                                                                     |  19.888s  |  19.888s  |   0.000s  | 0.0%|
|31.smt2                                                                                     |  19.910s  |  19.910s  |   0.000s  | 0.0%|
|32.smt2                                                                                     |  19.770s  |  19.770s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.766s  |  19.766s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |  19.865s  |  19.865s  |   0.000s  | 0.0%|
|35.smt2                                                                                     |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|36.smt2                                                                                     |  19.931s  |  19.931s  |   0.000s  | 0.0%|
|37.smt2                                                                                     |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|38.smt2                                                                                     |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|39.smt2                                                                                     |  19.846s  |  19.846s  |   0.000s  | 0.0%|
|40.smt2                                                                                     |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|42.smt2                                                                                     |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|43.smt2                                                                                     |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|44.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|45.smt2                                                                                     |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|46.smt2                                                                                     |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|47.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|48.smt2                                                                                     |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|49.smt2                                                                                     |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|50.smt2                                                                                     |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|51.smt2                                                                                     |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|52.smt2                                                                                     |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|53.smt2                                                                                     |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|54.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|55.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|56.smt2                                                                                     |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|57.smt2                                                                                     |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|58.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|59.smt2                                                                                     |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|60.smt2                                                                                     |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|61.smt2                                                                                     |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|62.smt2                                                                                     |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|63.smt2                                                                                     |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  19.823s  |  19.823s  |   0.000s  | 0.0%|
|65.smt2                                                                                     |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|66.smt2                                                                                     |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|67.smt2                                                                                     |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|68.smt2                                                                                     |  19.631s  |  19.631s  |   0.000s  | 0.0%|
|69.smt2                                                                                     |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|70.smt2                                                                                     |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|71.smt2                                                                                     |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|72.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|73.smt2                                                                                     |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|76.smt2                                                                                     |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|77.smt2                                                                                     |  19.875s  |  19.875s  |   0.000s  | 0.0%|
|78.smt2                                                                                     |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|79.smt2                                                                                     |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|81.smt2                                                                                     |  19.792s  |  19.792s  |   0.000s  | 0.0%|
|82.smt2                                                                                     |  19.642s  |  19.642s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|84.smt2                                                                                     |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|85.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|86.smt2                                                                                     |  19.944s  |  19.944s  |   0.000s  | 0.0%|
|87.smt2                                                                                     |  19.944s  |  19.944s  |   0.000s  | 0.0%|
|88.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|89.smt2                                                                                     |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  19.751s  |  19.751s  |   0.000s  | 0.0%|
|91.smt2                                                                                     |  19.823s  |  19.823s  |   0.000s  | 0.0%|
|92.smt2                                                                                     |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |  19.768s  |  19.768s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|95.smt2                                                                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|96.smt2                                                                                     |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|97.smt2                                                                                     |  19.903s  |  19.903s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  19.958s  |  19.958s  |   0.000s  | 0.0%|
</details>
