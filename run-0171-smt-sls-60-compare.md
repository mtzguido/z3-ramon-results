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
Job description: MCM with basic SLS - 60 sec
Job tag: smt-sls-60
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 9770c005926e2085d4ede18f03d56cb67d762d84
Z3 branch: master
Z3 options: "-T:60 -v:2 -st sls.arith_use_lookahead=true tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: adjust heuristic in random-inc-dec for finite domains

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: MCM with basic SLS - 60 sec
Job tag: smt-sls-60
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 9770c005926e2085d4ede18f03d56cb67d762d84
Z3 branch: master
Z3 options: "-T:60 -v:2 -st sls.arith_use_lookahead=true tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: adjust heuristic in random-inc-dec for finite domains

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  29.683s  |  29.683s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  59.777s  |  59.777s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   3.461s  |   3.461s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  59.686s  |  59.686s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   5.981s  |   5.981s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  59.873s  |  59.873s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  58.952s  |  58.952s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  59.844s  |  59.844s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   3.337s  |   3.337s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  59.667s  |  59.667s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  59.559s  |  59.559s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  59.751s  |  59.751s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  29.683s  |  29.683s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  59.777s  |  59.777s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   3.461s  |   3.461s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  59.686s  |  59.686s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   5.981s  |   5.981s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  59.873s  |  59.873s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  58.952s  |  58.952s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  59.844s  |  59.844s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   3.337s  |   3.337s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  59.667s  |  59.667s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  59.559s  |  59.559s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  59.751s  |  59.751s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  29.683s  |  29.683s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  59.777s  |  59.777s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   3.461s  |   3.461s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  59.686s  |  59.686s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   5.981s  |   5.981s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  59.873s  |  59.873s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  58.952s  |  58.952s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  59.844s  |  59.844s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   3.337s  |   3.337s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  59.667s  |  59.667s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  59.559s  |  59.559s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  59.751s  |  59.751s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  29.683s  |  29.683s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  59.777s  |  59.777s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   3.461s  |   3.461s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  59.686s  |  59.686s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   5.981s  |   5.981s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  59.873s  |  59.873s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  58.952s  |  58.952s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  59.844s  |  59.844s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   3.337s  |   3.337s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  59.667s  |  59.667s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  59.559s  |  59.559s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  59.751s  |  59.751s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|49.smt2                                                                                    |  60.024s |22.192MiB|
|19.smt2                                                                                    |  60.005s |22.316MiB|
|85.smt2                                                                                    |  60.003s |22.656MiB|
|111.smt2                                                                                   |  60.003s |33.316MiB|
|32.smt2                                                                                    |  60.002s |22.224MiB|
|92.smt2                                                                                    |  60.002s |22.364MiB|
|98.smt2                                                                                    |  60.000s |23.312MiB|
|112.smt2                                                                                   |  59.997s |33.352MiB|
|138.smt2                                                                                   |  59.997s |38.892MiB|
|51.smt2                                                                                    |  59.996s |22.484MiB|
|30.smt2                                                                                    |  59.994s |22.08MiB|
|05.smt2                                                                                    |  59.993s |22.508MiB|
|178.smt2                                                                                   |  59.991s |189.0MiB|
|13.smt2                                                                                    |  59.990s |22.432MiB|
|87.smt2                                                                                    |  59.988s |21.108MiB|
|132.smt2                                                                                   |  59.984s |40.3MiB|
|04.smt2                                                                                    |  59.984s |21.324MiB|
|35.smt2                                                                                    |  59.984s |22.764MiB|
|42.smt2                                                                                    |  59.983s |20.916MiB|
|167.smt2                                                                                   |  59.983s |68.376MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|49.smt2                                                                                    |  60.024s |22.192MiB|
|19.smt2                                                                                    |  60.005s |22.316MiB|
|85.smt2                                                                                    |  60.003s |22.656MiB|
|111.smt2                                                                                   |  60.003s |33.316MiB|
|32.smt2                                                                                    |  60.002s |22.224MiB|
|92.smt2                                                                                    |  60.002s |22.364MiB|
|98.smt2                                                                                    |  60.000s |23.312MiB|
|112.smt2                                                                                   |  59.997s |33.352MiB|
|138.smt2                                                                                   |  59.997s |38.892MiB|
|51.smt2                                                                                    |  59.996s |22.484MiB|
|30.smt2                                                                                    |  59.994s |22.08MiB|
|05.smt2                                                                                    |  59.993s |22.508MiB|
|178.smt2                                                                                   |  59.991s |189.0MiB|
|13.smt2                                                                                    |  59.990s |22.432MiB|
|87.smt2                                                                                    |  59.988s |21.108MiB|
|132.smt2                                                                                   |  59.984s |40.3MiB|
|04.smt2                                                                                    |  59.984s |21.324MiB|
|35.smt2                                                                                    |  59.984s |22.764MiB|
|42.smt2                                                                                    |  59.983s |20.916MiB|
|167.smt2                                                                                   |  59.983s |68.376MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |22.464MiB|22.464MiB|0B| 0.0%|
|02.smt2                                                                                     |22.252MiB|22.252MiB|0B| 0.0%|
|03.smt2                                                                                     |22.176MiB|22.176MiB|0B| 0.0%|
|04.smt2                                                                                     |21.324MiB|21.324MiB|0B| 0.0%|
|05.smt2                                                                                     |22.508MiB|22.508MiB|0B| 0.0%|
|06.smt2                                                                                     |20.044MiB|20.044MiB|0B| 0.0%|
|07.smt2                                                                                     |21.612MiB|21.612MiB|0B| 0.0%|
|08.smt2                                                                                     |21.004MiB|21.004MiB|0B| 0.0%|
|09.smt2                                                                                     |21.364MiB|21.364MiB|0B| 0.0%|
|10.smt2                                                                                     |21.876MiB|21.876MiB|0B| 0.0%|
|100.smt2                                                                                    |23.464MiB|23.464MiB|0B| 0.0%|
|101.smt2                                                                                    |22.48MiB|22.48MiB|0B| 0.0%|
|102.smt2                                                                                    |24.548MiB|24.548MiB|0B| 0.0%|
|103.smt2                                                                                    |23.476MiB|23.476MiB|0B| 0.0%|
|104.smt2                                                                                    |24.304MiB|24.304MiB|0B| 0.0%|
|105.smt2                                                                                    |33.492MiB|33.492MiB|0B| 0.0%|
|106.smt2                                                                                    |36.932MiB|36.932MiB|0B| 0.0%|
|107.smt2                                                                                    |22.16MiB|22.16MiB|0B| 0.0%|
|108.smt2                                                                                    |33.832MiB|33.832MiB|0B| 0.0%|
|109.smt2                                                                                    |22.936MiB|22.936MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |22.464MiB|22.464MiB|0B| 0.0%|
|02.smt2                                                                                     |22.252MiB|22.252MiB|0B| 0.0%|
|03.smt2                                                                                     |22.176MiB|22.176MiB|0B| 0.0%|
|04.smt2                                                                                     |21.324MiB|21.324MiB|0B| 0.0%|
|05.smt2                                                                                     |22.508MiB|22.508MiB|0B| 0.0%|
|06.smt2                                                                                     |20.044MiB|20.044MiB|0B| 0.0%|
|07.smt2                                                                                     |21.612MiB|21.612MiB|0B| 0.0%|
|08.smt2                                                                                     |21.004MiB|21.004MiB|0B| 0.0%|
|09.smt2                                                                                     |21.364MiB|21.364MiB|0B| 0.0%|
|10.smt2                                                                                     |21.876MiB|21.876MiB|0B| 0.0%|
|100.smt2                                                                                    |23.464MiB|23.464MiB|0B| 0.0%|
|101.smt2                                                                                    |22.48MiB|22.48MiB|0B| 0.0%|
|102.smt2                                                                                    |24.548MiB|24.548MiB|0B| 0.0%|
|103.smt2                                                                                    |23.476MiB|23.476MiB|0B| 0.0%|
|104.smt2                                                                                    |24.304MiB|24.304MiB|0B| 0.0%|
|105.smt2                                                                                    |33.492MiB|33.492MiB|0B| 0.0%|
|106.smt2                                                                                    |36.932MiB|36.932MiB|0B| 0.0%|
|107.smt2                                                                                    |22.16MiB|22.16MiB|0B| 0.0%|
|108.smt2                                                                                    |33.832MiB|33.832MiB|0B| 0.0%|
|109.smt2                                                                                    |22.936MiB|22.936MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |22.464MiB|22.464MiB|0B| 0.0%|
|02.smt2                                                                                     |22.252MiB|22.252MiB|0B| 0.0%|
|03.smt2                                                                                     |22.176MiB|22.176MiB|0B| 0.0%|
|04.smt2                                                                                     |21.324MiB|21.324MiB|0B| 0.0%|
|05.smt2                                                                                     |22.508MiB|22.508MiB|0B| 0.0%|
|06.smt2                                                                                     |20.044MiB|20.044MiB|0B| 0.0%|
|07.smt2                                                                                     |21.612MiB|21.612MiB|0B| 0.0%|
|08.smt2                                                                                     |21.004MiB|21.004MiB|0B| 0.0%|
|09.smt2                                                                                     |21.364MiB|21.364MiB|0B| 0.0%|
|10.smt2                                                                                     |21.876MiB|21.876MiB|0B| 0.0%|
|100.smt2                                                                                    |23.464MiB|23.464MiB|0B| 0.0%|
|101.smt2                                                                                    |22.48MiB|22.48MiB|0B| 0.0%|
|102.smt2                                                                                    |24.548MiB|24.548MiB|0B| 0.0%|
|103.smt2                                                                                    |23.476MiB|23.476MiB|0B| 0.0%|
|104.smt2                                                                                    |24.304MiB|24.304MiB|0B| 0.0%|
|105.smt2                                                                                    |33.492MiB|33.492MiB|0B| 0.0%|
|106.smt2                                                                                    |36.932MiB|36.932MiB|0B| 0.0%|
|107.smt2                                                                                    |22.16MiB|22.16MiB|0B| 0.0%|
|108.smt2                                                                                    |33.832MiB|33.832MiB|0B| 0.0%|
|109.smt2                                                                                    |22.936MiB|22.936MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |22.464MiB|22.464MiB|0B| 0.0%|
|02.smt2                                                                                     |22.252MiB|22.252MiB|0B| 0.0%|
|03.smt2                                                                                     |22.176MiB|22.176MiB|0B| 0.0%|
|04.smt2                                                                                     |21.324MiB|21.324MiB|0B| 0.0%|
|05.smt2                                                                                     |22.508MiB|22.508MiB|0B| 0.0%|
|06.smt2                                                                                     |20.044MiB|20.044MiB|0B| 0.0%|
|07.smt2                                                                                     |21.612MiB|21.612MiB|0B| 0.0%|
|08.smt2                                                                                     |21.004MiB|21.004MiB|0B| 0.0%|
|09.smt2                                                                                     |21.364MiB|21.364MiB|0B| 0.0%|
|10.smt2                                                                                     |21.876MiB|21.876MiB|0B| 0.0%|
|100.smt2                                                                                    |23.464MiB|23.464MiB|0B| 0.0%|
|101.smt2                                                                                    |22.48MiB|22.48MiB|0B| 0.0%|
|102.smt2                                                                                    |24.548MiB|24.548MiB|0B| 0.0%|
|103.smt2                                                                                    |23.476MiB|23.476MiB|0B| 0.0%|
|104.smt2                                                                                    |24.304MiB|24.304MiB|0B| 0.0%|
|105.smt2                                                                                    |33.492MiB|33.492MiB|0B| 0.0%|
|106.smt2                                                                                    |36.932MiB|36.932MiB|0B| 0.0%|
|107.smt2                                                                                    |22.16MiB|22.16MiB|0B| 0.0%|
|108.smt2                                                                                    |33.832MiB|33.832MiB|0B| 0.0%|
|109.smt2                                                                                    |22.936MiB|22.936MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|186.smt2                                                                                   |  59.776s |711.0MiB|
|185.smt2                                                                                   |  59.842s |690.0MiB|
|184.smt2                                                                                   |  59.909s |473.0MiB|
|183.smt2                                                                                   |  59.928s |320.0MiB|
|182.smt2                                                                                   |  59.927s |319.0MiB|
|178.smt2                                                                                   |  59.991s |189.0MiB|
|181.smt2                                                                                   |  59.845s |185.0MiB|
|179.smt2                                                                                   |  59.775s |179.0MiB|
|180.smt2                                                                                   |  59.502s |179.0MiB|
|176.smt2                                                                                   |  59.951s |176.0MiB|
|172.smt2                                                                                   |  59.722s |176.0MiB|
|173.smt2                                                                                   |  59.658s |159.0MiB|
|175.smt2                                                                                   |  59.964s |152.0MiB|
|174.smt2                                                                                   |  59.777s |152.0MiB|
|165.smt2                                                                                   |  59.918s |93.064MiB|
|169.smt2                                                                                   |  59.852s |93.032MiB|
|161.smt2                                                                                   |  59.767s |89.052MiB|
|163.smt2                                                                                   |  59.578s |85.916MiB|
|168.smt2                                                                                   |  59.839s |76.724MiB|
|167.smt2                                                                                   |  59.983s |68.376MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|186.smt2                                                                                   |  59.776s |711.0MiB|
|185.smt2                                                                                   |  59.842s |690.0MiB|
|184.smt2                                                                                   |  59.909s |473.0MiB|
|183.smt2                                                                                   |  59.928s |320.0MiB|
|182.smt2                                                                                   |  59.927s |319.0MiB|
|178.smt2                                                                                   |  59.991s |189.0MiB|
|181.smt2                                                                                   |  59.845s |185.0MiB|
|179.smt2                                                                                   |  59.775s |179.0MiB|
|180.smt2                                                                                   |  59.502s |179.0MiB|
|176.smt2                                                                                   |  59.951s |176.0MiB|
|172.smt2                                                                                   |  59.722s |176.0MiB|
|173.smt2                                                                                   |  59.658s |159.0MiB|
|175.smt2                                                                                   |  59.964s |152.0MiB|
|174.smt2                                                                                   |  59.777s |152.0MiB|
|165.smt2                                                                                   |  59.918s |93.064MiB|
|169.smt2                                                                                   |  59.852s |93.032MiB|
|161.smt2                                                                                   |  59.767s |89.052MiB|
|163.smt2                                                                                   |  59.578s |85.916MiB|
|168.smt2                                                                                   |  59.839s |76.724MiB|
|167.smt2                                                                                   |  59.983s |68.376MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  29.683s  |  29.683s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  59.777s  |  59.777s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   3.461s  |   3.461s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  59.686s  |  59.686s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   5.981s  |   5.981s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  59.873s  |  59.873s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  58.952s  |  58.952s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  59.844s  |  59.844s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   3.337s  |   3.337s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  59.667s  |  59.667s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  59.559s  |  59.559s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  59.751s  |  59.751s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  59.891s  |  59.891s  |   0.000s  | 0.0%|
|110.smt2                                                                                    |  59.846s  |  59.846s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|112.smt2                                                                                    |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|114.smt2                                                                                    |  59.866s  |  59.866s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   1.749s  |   1.749s  |   0.000s  | 0.0%|
|116.smt2                                                                                    |  59.872s  |  59.872s  |   0.000s  | 0.0%|
|117.smt2                                                                                    |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|118.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|119.smt2                                                                                    |  59.785s  |  59.785s  |   0.000s  | 0.0%|
|12.smt2                                                                                     |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|120.smt2                                                                                    |  59.478s  |  59.478s  |   0.000s  | 0.0%|
|121.smt2                                                                                    |  59.554s  |  59.554s  |   0.000s  | 0.0%|
|122.smt2                                                                                    |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|123.smt2                                                                                    |  35.297s  |  35.297s  |   0.000s  | 0.0%|
|124.smt2                                                                                    |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|125.smt2                                                                                    |  59.774s  |  59.774s  |   0.000s  | 0.0%|
|126.smt2                                                                                    |  59.485s  |  59.485s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |  59.512s  |  59.512s  |   0.000s  | 0.0%|
|128.smt2                                                                                    |  59.862s  |  59.862s  |   0.000s  | 0.0%|
|129.smt2                                                                                    |  59.826s  |  59.826s  |   0.000s  | 0.0%|
|13.smt2                                                                                     |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|130.smt2                                                                                    |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|131.smt2                                                                                    |  59.808s  |  59.808s  |   0.000s  | 0.0%|
|132.smt2                                                                                    |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|133.smt2                                                                                    |  59.932s  |  59.932s  |   0.000s  | 0.0%|
|134.smt2                                                                                    |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|135.smt2                                                                                    |  59.792s  |  59.792s  |   0.000s  | 0.0%|
|136.smt2                                                                                    |  59.542s  |  59.542s  |   0.000s  | 0.0%|
|137.smt2                                                                                    |  59.623s  |  59.623s  |   0.000s  | 0.0%|
|138.smt2                                                                                    |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|139.smt2                                                                                    |  20.115s  |  20.115s  |   0.000s  | 0.0%|
|14.smt2                                                                                     |   9.580s  |   9.580s  |   0.000s  | 0.0%|
|140.smt2                                                                                    |  59.811s  |  59.811s  |   0.000s  | 0.0%|
|141.smt2                                                                                    |  57.588s  |  57.588s  |   0.000s  | 0.0%|
|142.smt2                                                                                    |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|143.smt2                                                                                    |  59.713s  |  59.713s  |   0.000s  | 0.0%|
|144.smt2                                                                                    |  59.651s  |  59.651s  |   0.000s  | 0.0%|
|145.smt2                                                                                    |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|146.smt2                                                                                    |  59.225s  |  59.225s  |   0.000s  | 0.0%|
|147.smt2                                                                                    |  59.730s  |  59.730s  |   0.000s  | 0.0%|
|148.smt2                                                                                    |  58.845s  |  58.845s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |  59.837s  |  59.837s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  54.191s  |  54.191s  |   0.000s  | 0.0%|
|150.smt2                                                                                    |  59.677s  |  59.677s  |   0.000s  | 0.0%|
|151.smt2                                                                                    |  59.925s  |  59.925s  |   0.000s  | 0.0%|
|152.smt2                                                                                    |   5.355s  |   5.355s  |   0.000s  | 0.0%|
|153.smt2                                                                                    |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|154.smt2                                                                                    |  59.376s  |  59.376s  |   0.000s  | 0.0%|
|155.smt2                                                                                    |  59.836s  |  59.836s  |   0.000s  | 0.0%|
|156.smt2                                                                                    |  59.849s  |  59.849s  |   0.000s  | 0.0%|
|157.smt2                                                                                    |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|158.smt2                                                                                    |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|159.smt2                                                                                    |  59.555s  |  59.555s  |   0.000s  | 0.0%|
|16.smt2                                                                                     |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|160.smt2                                                                                    |  59.562s  |  59.562s  |   0.000s  | 0.0%|
|161.smt2                                                                                    |  59.767s  |  59.767s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|163.smt2                                                                                    |  59.578s  |  59.578s  |   0.000s  | 0.0%|
|164.smt2                                                                                    |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|165.smt2                                                                                    |  59.918s  |  59.918s  |   0.000s  | 0.0%|
|166.smt2                                                                                    |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|168.smt2                                                                                    |  59.839s  |  59.839s  |   0.000s  | 0.0%|
|169.smt2                                                                                    |  59.852s  |  59.852s  |   0.000s  | 0.0%|
|17.smt2                                                                                     |  59.741s  |  59.741s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|171.smt2                                                                                    |  59.497s  |  59.497s  |   0.000s  | 0.0%|
|172.smt2                                                                                    |  59.722s  |  59.722s  |   0.000s  | 0.0%|
|173.smt2                                                                                    |  59.658s  |  59.658s  |   0.000s  | 0.0%|
|174.smt2                                                                                    |  59.777s  |  59.777s  |   0.000s  | 0.0%|
|175.smt2                                                                                    |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|176.smt2                                                                                    |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |   1.528s  |   1.528s  |   0.000s  | 0.0%|
|178.smt2                                                                                    |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |  59.775s  |  59.775s  |   0.000s  | 0.0%|
|18.smt2                                                                                     |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|180.smt2                                                                                    |  59.502s  |  59.502s  |   0.000s  | 0.0%|
|181.smt2                                                                                    |  59.845s  |  59.845s  |   0.000s  | 0.0%|
|182.smt2                                                                                    |  59.927s  |  59.927s  |   0.000s  | 0.0%|
|183.smt2                                                                                    |  59.928s  |  59.928s  |   0.000s  | 0.0%|
|184.smt2                                                                                    |  59.909s  |  59.909s  |   0.000s  | 0.0%|
|185.smt2                                                                                    |  59.842s  |  59.842s  |   0.000s  | 0.0%|
|186.smt2                                                                                    |  59.776s  |  59.776s  |   0.000s  | 0.0%|
|19.smt2                                                                                     |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  59.915s  |  59.915s  |   0.000s  | 0.0%|
|21.smt2                                                                                     |  59.773s  |  59.773s  |   0.000s  | 0.0%|
|22.smt2                                                                                     |  59.850s  |  59.850s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |  59.853s  |  59.853s  |   0.000s  | 0.0%|
|24.smt2                                                                                     |  59.552s  |  59.552s  |   0.000s  | 0.0%|
|25.smt2                                                                                     |  59.799s  |  59.799s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  59.917s  |  59.917s  |   0.000s  | 0.0%|
|27.smt2                                                                                     |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|28.smt2                                                                                     |  59.919s  |  59.919s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  59.800s  |  59.800s  |   0.000s  | 0.0%|
|30.smt2                                                                                     |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|31.smt2                                                                                     |  59.634s  |  59.634s  |   0.000s  | 0.0%|
|32.smt2                                                                                     |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  33.962s  |  33.962s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |  59.671s  |  59.671s  |   0.000s  | 0.0%|
|35.smt2                                                                                     |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|36.smt2                                                                                     |  59.762s  |  59.762s  |   0.000s  | 0.0%|
|37.smt2                                                                                     |  59.161s  |  59.161s  |   0.000s  | 0.0%|
|38.smt2                                                                                     |  59.958s  |  59.958s  |   0.000s  | 0.0%|
|39.smt2                                                                                     |  59.839s  |  59.839s  |   0.000s  | 0.0%|
|40.smt2                                                                                     |  59.908s  |  59.908s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|42.smt2                                                                                     |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|43.smt2                                                                                     |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|44.smt2                                                                                     |  59.912s  |  59.912s  |   0.000s  | 0.0%|
|45.smt2                                                                                     |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|46.smt2                                                                                     |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|47.smt2                                                                                     |  59.856s  |  59.856s  |   0.000s  | 0.0%|
|48.smt2                                                                                     |  59.599s  |  59.599s  |   0.000s  | 0.0%|
|49.smt2                                                                                     |  60.024s  |  60.024s  |   0.000s  | 0.0%|
|50.smt2                                                                                     |  59.778s  |  59.778s  |   0.000s  | 0.0%|
|51.smt2                                                                                     |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|52.smt2                                                                                     |  59.816s  |  59.816s  |   0.000s  | 0.0%|
|53.smt2                                                                                     |  59.899s  |  59.899s  |   0.000s  | 0.0%|
|54.smt2                                                                                     |  59.697s  |  59.697s  |   0.000s  | 0.0%|
|55.smt2                                                                                     |  59.924s  |  59.924s  |   0.000s  | 0.0%|
|56.smt2                                                                                     |  59.892s  |  59.892s  |   0.000s  | 0.0%|
|57.smt2                                                                                     |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|58.smt2                                                                                     |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|59.smt2                                                                                     |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|60.smt2                                                                                     |  59.740s  |  59.740s  |   0.000s  | 0.0%|
|61.smt2                                                                                     |  59.689s  |  59.689s  |   0.000s  | 0.0%|
|62.smt2                                                                                     |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|63.smt2                                                                                     |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  59.852s  |  59.852s  |   0.000s  | 0.0%|
|65.smt2                                                                                     |  59.912s  |  59.912s  |   0.000s  | 0.0%|
|66.smt2                                                                                     |  59.751s  |  59.751s  |   0.000s  | 0.0%|
|67.smt2                                                                                     |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|68.smt2                                                                                     |  59.871s  |  59.871s  |   0.000s  | 0.0%|
|69.smt2                                                                                     |  59.712s  |  59.712s  |   0.000s  | 0.0%|
|70.smt2                                                                                     |  59.803s  |  59.803s  |   0.000s  | 0.0%|
|71.smt2                                                                                     |  59.703s  |  59.703s  |   0.000s  | 0.0%|
|72.smt2                                                                                     |  59.557s  |  59.557s  |   0.000s  | 0.0%|
|73.smt2                                                                                     |  59.673s  |  59.673s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |  59.484s  |  59.484s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |  59.820s  |  59.820s  |   0.000s  | 0.0%|
|76.smt2                                                                                     |  59.628s  |  59.628s  |   0.000s  | 0.0%|
|77.smt2                                                                                     |  59.820s  |  59.820s  |   0.000s  | 0.0%|
|78.smt2                                                                                     |  59.918s  |  59.918s  |   0.000s  | 0.0%|
|79.smt2                                                                                     |  59.759s  |  59.759s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  59.571s  |  59.571s  |   0.000s  | 0.0%|
|81.smt2                                                                                     |  59.904s  |  59.904s  |   0.000s  | 0.0%|
|82.smt2                                                                                     |  58.740s  |  58.740s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |  59.625s  |  59.625s  |   0.000s  | 0.0%|
|84.smt2                                                                                     |  59.689s  |  59.689s  |   0.000s  | 0.0%|
|85.smt2                                                                                     |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|86.smt2                                                                                     |  59.771s  |  59.771s  |   0.000s  | 0.0%|
|87.smt2                                                                                     |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|88.smt2                                                                                     |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|89.smt2                                                                                     |  59.449s  |  59.449s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  59.618s  |  59.618s  |   0.000s  | 0.0%|
|91.smt2                                                                                     |  59.696s  |  59.696s  |   0.000s  | 0.0%|
|92.smt2                                                                                     |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |  59.132s  |  59.132s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  59.701s  |  59.701s  |   0.000s  | 0.0%|
|95.smt2                                                                                     |  59.518s  |  59.518s  |   0.000s  | 0.0%|
|96.smt2                                                                                     |  59.864s  |  59.864s  |   0.000s  | 0.0%|
|97.smt2                                                                                     |  59.874s  |  59.874s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  60.000s  |  60.000s  |   0.000s  | 0.0%|
</details>
