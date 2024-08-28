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
Job description: MCM with basic SMT solver
Job tag: smt
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 9770c005926e2085d4ede18f03d56cb67d762d84
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: adjust heuristic in random-inc-dec for finite domains

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: MCM with basic SMT solver
Job tag: smt
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 9770c005926e2085d4ede18f03d56cb67d762d84
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: adjust heuristic in random-inc-dec for finite domains

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   2.928s  |   2.928s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  19.897s  |  19.897s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |  19.385s  |  19.385s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  19.917s  |  19.917s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.904s  |  19.904s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   1.048s  |   1.048s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   1.531s  |   1.531s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   2.928s  |   2.928s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  19.897s  |  19.897s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |  19.385s  |  19.385s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  19.917s  |  19.917s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.904s  |  19.904s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   1.048s  |   1.048s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   1.531s  |   1.531s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   2.928s  |   2.928s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  19.897s  |  19.897s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |  19.385s  |  19.385s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  19.917s  |  19.917s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.904s  |  19.904s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   1.048s  |   1.048s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   1.531s  |   1.531s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   2.928s  |   2.928s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  19.897s  |  19.897s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |  19.385s  |  19.385s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  19.917s  |  19.917s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.904s  |  19.904s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   1.048s  |   1.048s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   1.531s  |   1.531s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|158.smt2                                                                                   |  20.036s |167.0MiB|
|54.smt2                                                                                    |  20.034s |142.0MiB|
|49.smt2                                                                                    |  20.034s |117.0MiB|
|119.smt2                                                                                   |  20.033s |118.0MiB|
|143.smt2                                                                                   |  20.033s |138.0MiB|
|47.smt2                                                                                    |  20.032s |123.0MiB|
|138.smt2                                                                                   |  20.032s |144.0MiB|
|122.smt2                                                                                   |  20.031s |151.0MiB|
|45.smt2                                                                                    |  20.030s |72.244MiB|
|60.smt2                                                                                    |  20.030s |137.0MiB|
|151.smt2                                                                                   |  20.027s |203.0MiB|
|51.smt2                                                                                    |  20.027s |137.0MiB|
|135.smt2                                                                                   |  20.026s |144.0MiB|
|82.smt2                                                                                    |  20.026s |123.0MiB|
|24.smt2                                                                                    |  20.025s |113.0MiB|
|52.smt2                                                                                    |  20.025s |144.0MiB|
|93.smt2                                                                                    |  20.025s |89.936MiB|
|105.smt2                                                                                   |  20.025s |177.0MiB|
|144.smt2                                                                                   |  20.025s |140.0MiB|
|75.smt2                                                                                    |  20.025s |126.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|158.smt2                                                                                   |  20.036s |167.0MiB|
|54.smt2                                                                                    |  20.034s |142.0MiB|
|49.smt2                                                                                    |  20.034s |117.0MiB|
|119.smt2                                                                                   |  20.033s |118.0MiB|
|143.smt2                                                                                   |  20.033s |138.0MiB|
|47.smt2                                                                                    |  20.032s |123.0MiB|
|138.smt2                                                                                   |  20.032s |144.0MiB|
|122.smt2                                                                                   |  20.031s |151.0MiB|
|45.smt2                                                                                    |  20.030s |72.244MiB|
|60.smt2                                                                                    |  20.030s |137.0MiB|
|151.smt2                                                                                   |  20.027s |203.0MiB|
|51.smt2                                                                                    |  20.027s |137.0MiB|
|135.smt2                                                                                   |  20.026s |144.0MiB|
|82.smt2                                                                                    |  20.026s |123.0MiB|
|24.smt2                                                                                    |  20.025s |113.0MiB|
|52.smt2                                                                                    |  20.025s |144.0MiB|
|93.smt2                                                                                    |  20.025s |89.936MiB|
|105.smt2                                                                                   |  20.025s |177.0MiB|
|144.smt2                                                                                   |  20.025s |140.0MiB|
|75.smt2                                                                                    |  20.025s |126.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |104.0MiB|104.0MiB|0B| 0.0%|
|02.smt2                                                                                     |114.0MiB|114.0MiB|0B| 0.0%|
|03.smt2                                                                                     |93.62MiB|93.62MiB|0B| 0.0%|
|04.smt2                                                                                     |87.032MiB|87.032MiB|0B| 0.0%|
|05.smt2                                                                                     |123.0MiB|123.0MiB|0B| 0.0%|
|06.smt2                                                                                     |44.996MiB|44.996MiB|0B| 0.0%|
|07.smt2                                                                                     |83.604MiB|83.604MiB|0B| 0.0%|
|08.smt2                                                                                     |75.264MiB|75.264MiB|0B| 0.0%|
|09.smt2                                                                                     |81.792MiB|81.792MiB|0B| 0.0%|
|10.smt2                                                                                     |89.052MiB|89.052MiB|0B| 0.0%|
|100.smt2                                                                                    |110.0MiB|110.0MiB|0B| 0.0%|
|101.smt2                                                                                    |110.0MiB|110.0MiB|0B| 0.0%|
|102.smt2                                                                                    |136.0MiB|136.0MiB|0B| 0.0%|
|103.smt2                                                                                    |111.0MiB|111.0MiB|0B| 0.0%|
|104.smt2                                                                                    |79.424MiB|79.424MiB|0B| 0.0%|
|105.smt2                                                                                    |177.0MiB|177.0MiB|0B| 0.0%|
|106.smt2                                                                                    |135.0MiB|135.0MiB|0B| 0.0%|
|107.smt2                                                                                    |32.432MiB|32.432MiB|0B| 0.0%|
|108.smt2                                                                                    |160.0MiB|160.0MiB|0B| 0.0%|
|109.smt2                                                                                    |49.956MiB|49.956MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |104.0MiB|104.0MiB|0B| 0.0%|
|02.smt2                                                                                     |114.0MiB|114.0MiB|0B| 0.0%|
|03.smt2                                                                                     |93.62MiB|93.62MiB|0B| 0.0%|
|04.smt2                                                                                     |87.032MiB|87.032MiB|0B| 0.0%|
|05.smt2                                                                                     |123.0MiB|123.0MiB|0B| 0.0%|
|06.smt2                                                                                     |44.996MiB|44.996MiB|0B| 0.0%|
|07.smt2                                                                                     |83.604MiB|83.604MiB|0B| 0.0%|
|08.smt2                                                                                     |75.264MiB|75.264MiB|0B| 0.0%|
|09.smt2                                                                                     |81.792MiB|81.792MiB|0B| 0.0%|
|10.smt2                                                                                     |89.052MiB|89.052MiB|0B| 0.0%|
|100.smt2                                                                                    |110.0MiB|110.0MiB|0B| 0.0%|
|101.smt2                                                                                    |110.0MiB|110.0MiB|0B| 0.0%|
|102.smt2                                                                                    |136.0MiB|136.0MiB|0B| 0.0%|
|103.smt2                                                                                    |111.0MiB|111.0MiB|0B| 0.0%|
|104.smt2                                                                                    |79.424MiB|79.424MiB|0B| 0.0%|
|105.smt2                                                                                    |177.0MiB|177.0MiB|0B| 0.0%|
|106.smt2                                                                                    |135.0MiB|135.0MiB|0B| 0.0%|
|107.smt2                                                                                    |32.432MiB|32.432MiB|0B| 0.0%|
|108.smt2                                                                                    |160.0MiB|160.0MiB|0B| 0.0%|
|109.smt2                                                                                    |49.956MiB|49.956MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |104.0MiB|104.0MiB|0B| 0.0%|
|02.smt2                                                                                     |114.0MiB|114.0MiB|0B| 0.0%|
|03.smt2                                                                                     |93.62MiB|93.62MiB|0B| 0.0%|
|04.smt2                                                                                     |87.032MiB|87.032MiB|0B| 0.0%|
|05.smt2                                                                                     |123.0MiB|123.0MiB|0B| 0.0%|
|06.smt2                                                                                     |44.996MiB|44.996MiB|0B| 0.0%|
|07.smt2                                                                                     |83.604MiB|83.604MiB|0B| 0.0%|
|08.smt2                                                                                     |75.264MiB|75.264MiB|0B| 0.0%|
|09.smt2                                                                                     |81.792MiB|81.792MiB|0B| 0.0%|
|10.smt2                                                                                     |89.052MiB|89.052MiB|0B| 0.0%|
|100.smt2                                                                                    |110.0MiB|110.0MiB|0B| 0.0%|
|101.smt2                                                                                    |110.0MiB|110.0MiB|0B| 0.0%|
|102.smt2                                                                                    |136.0MiB|136.0MiB|0B| 0.0%|
|103.smt2                                                                                    |111.0MiB|111.0MiB|0B| 0.0%|
|104.smt2                                                                                    |79.424MiB|79.424MiB|0B| 0.0%|
|105.smt2                                                                                    |177.0MiB|177.0MiB|0B| 0.0%|
|106.smt2                                                                                    |135.0MiB|135.0MiB|0B| 0.0%|
|107.smt2                                                                                    |32.432MiB|32.432MiB|0B| 0.0%|
|108.smt2                                                                                    |160.0MiB|160.0MiB|0B| 0.0%|
|109.smt2                                                                                    |49.956MiB|49.956MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |104.0MiB|104.0MiB|0B| 0.0%|
|02.smt2                                                                                     |114.0MiB|114.0MiB|0B| 0.0%|
|03.smt2                                                                                     |93.62MiB|93.62MiB|0B| 0.0%|
|04.smt2                                                                                     |87.032MiB|87.032MiB|0B| 0.0%|
|05.smt2                                                                                     |123.0MiB|123.0MiB|0B| 0.0%|
|06.smt2                                                                                     |44.996MiB|44.996MiB|0B| 0.0%|
|07.smt2                                                                                     |83.604MiB|83.604MiB|0B| 0.0%|
|08.smt2                                                                                     |75.264MiB|75.264MiB|0B| 0.0%|
|09.smt2                                                                                     |81.792MiB|81.792MiB|0B| 0.0%|
|10.smt2                                                                                     |89.052MiB|89.052MiB|0B| 0.0%|
|100.smt2                                                                                    |110.0MiB|110.0MiB|0B| 0.0%|
|101.smt2                                                                                    |110.0MiB|110.0MiB|0B| 0.0%|
|102.smt2                                                                                    |136.0MiB|136.0MiB|0B| 0.0%|
|103.smt2                                                                                    |111.0MiB|111.0MiB|0B| 0.0%|
|104.smt2                                                                                    |79.424MiB|79.424MiB|0B| 0.0%|
|105.smt2                                                                                    |177.0MiB|177.0MiB|0B| 0.0%|
|106.smt2                                                                                    |135.0MiB|135.0MiB|0B| 0.0%|
|107.smt2                                                                                    |32.432MiB|32.432MiB|0B| 0.0%|
|108.smt2                                                                                    |160.0MiB|160.0MiB|0B| 0.0%|
|109.smt2                                                                                    |49.956MiB|49.956MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|184.smt2                                                                                   |  20.016s |703.0MiB|
|183.smt2                                                                                   |  20.004s |409.0MiB|
|182.smt2                                                                                   |  19.809s |407.0MiB|
|178.smt2                                                                                   |  19.981s |380.0MiB|
|179.smt2                                                                                   |  20.017s |341.0MiB|
|181.smt2                                                                                   |  19.997s |325.0MiB|
|180.smt2                                                                                   |  19.913s |307.0MiB|
|172.smt2                                                                                   |  20.000s |297.0MiB|
|176.smt2                                                                                   |  19.946s |296.0MiB|
|173.smt2                                                                                   |  19.892s |289.0MiB|
|175.smt2                                                                                   |  19.999s |283.0MiB|
|174.smt2                                                                                   |  19.910s |268.0MiB|
|185.smt2                                                                                   |  20.008s |245.0MiB|
|186.smt2                                                                                   |  19.905s |245.0MiB|
|169.smt2                                                                                   |  20.012s |236.0MiB|
|171.smt2                                                                                   |  20.002s |211.0MiB|
|163.smt2                                                                                   |  19.910s |208.0MiB|
|151.smt2                                                                                   |  20.027s |203.0MiB|
|160.smt2                                                                                   |  19.822s |191.0MiB|
|165.smt2                                                                                   |  19.931s |181.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|184.smt2                                                                                   |  20.016s |703.0MiB|
|183.smt2                                                                                   |  20.004s |409.0MiB|
|182.smt2                                                                                   |  19.809s |407.0MiB|
|178.smt2                                                                                   |  19.981s |380.0MiB|
|179.smt2                                                                                   |  20.017s |341.0MiB|
|181.smt2                                                                                   |  19.997s |325.0MiB|
|180.smt2                                                                                   |  19.913s |307.0MiB|
|172.smt2                                                                                   |  20.000s |297.0MiB|
|176.smt2                                                                                   |  19.946s |296.0MiB|
|173.smt2                                                                                   |  19.892s |289.0MiB|
|175.smt2                                                                                   |  19.999s |283.0MiB|
|174.smt2                                                                                   |  19.910s |268.0MiB|
|185.smt2                                                                                   |  20.008s |245.0MiB|
|186.smt2                                                                                   |  19.905s |245.0MiB|
|169.smt2                                                                                   |  20.012s |236.0MiB|
|171.smt2                                                                                   |  20.002s |211.0MiB|
|163.smt2                                                                                   |  19.910s |208.0MiB|
|151.smt2                                                                                   |  20.027s |203.0MiB|
|160.smt2                                                                                   |  19.822s |191.0MiB|
|165.smt2                                                                                   |  19.931s |181.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   2.928s  |   2.928s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  19.897s  |  19.897s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |  19.385s  |  19.385s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  19.917s  |  19.917s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  19.904s  |  19.904s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   1.048s  |   1.048s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   1.531s  |   1.531s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|110.smt2                                                                                    |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  19.853s  |  19.853s  |   0.000s  | 0.0%|
|112.smt2                                                                                    |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|114.smt2                                                                                    |  19.850s  |  19.850s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|116.smt2                                                                                    |  19.805s  |  19.805s  |   0.000s  | 0.0%|
|117.smt2                                                                                    |  10.571s  |  10.571s  |   0.000s  | 0.0%|
|118.smt2                                                                                    |  19.657s  |  19.657s  |   0.000s  | 0.0%|
|119.smt2                                                                                    |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|12.smt2                                                                                     |  19.605s  |  19.605s  |   0.000s  | 0.0%|
|120.smt2                                                                                    |  19.704s  |  19.704s  |   0.000s  | 0.0%|
|121.smt2                                                                                    |  19.541s  |  19.541s  |   0.000s  | 0.0%|
|122.smt2                                                                                    |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|123.smt2                                                                                    |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|124.smt2                                                                                    |  19.839s  |  19.839s  |   0.000s  | 0.0%|
|125.smt2                                                                                    |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|126.smt2                                                                                    |  19.740s  |  19.740s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |  19.500s  |  19.500s  |   0.000s  | 0.0%|
|128.smt2                                                                                    |  19.807s  |  19.807s  |   0.000s  | 0.0%|
|129.smt2                                                                                    |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|13.smt2                                                                                     |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|130.smt2                                                                                    |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|131.smt2                                                                                    |  19.845s  |  19.845s  |   0.000s  | 0.0%|
|132.smt2                                                                                    |  19.832s  |  19.832s  |   0.000s  | 0.0%|
|133.smt2                                                                                    |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|134.smt2                                                                                    |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|135.smt2                                                                                    |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|136.smt2                                                                                    |  19.604s  |  19.604s  |   0.000s  | 0.0%|
|137.smt2                                                                                    |  19.922s  |  19.922s  |   0.000s  | 0.0%|
|138.smt2                                                                                    |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|139.smt2                                                                                    |  19.783s  |  19.783s  |   0.000s  | 0.0%|
|14.smt2                                                                                     |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|140.smt2                                                                                    |  19.818s  |  19.818s  |   0.000s  | 0.0%|
|141.smt2                                                                                    |  19.544s  |  19.544s  |   0.000s  | 0.0%|
|142.smt2                                                                                    |  19.921s  |  19.921s  |   0.000s  | 0.0%|
|143.smt2                                                                                    |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|144.smt2                                                                                    |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|145.smt2                                                                                    |  19.705s  |  19.705s  |   0.000s  | 0.0%|
|146.smt2                                                                                    |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|147.smt2                                                                                    |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|148.smt2                                                                                    |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  19.726s  |  19.726s  |   0.000s  | 0.0%|
|150.smt2                                                                                    |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|151.smt2                                                                                    |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|152.smt2                                                                                    |  19.832s  |  19.832s  |   0.000s  | 0.0%|
|153.smt2                                                                                    |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|154.smt2                                                                                    |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|155.smt2                                                                                    |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|156.smt2                                                                                    |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|157.smt2                                                                                    |  19.879s  |  19.879s  |   0.000s  | 0.0%|
|158.smt2                                                                                    |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|159.smt2                                                                                    |  19.768s  |  19.768s  |   0.000s  | 0.0%|
|16.smt2                                                                                     |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|160.smt2                                                                                    |  19.822s  |  19.822s  |   0.000s  | 0.0%|
|161.smt2                                                                                    |  18.956s  |  18.956s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  19.795s  |  19.795s  |   0.000s  | 0.0%|
|163.smt2                                                                                    |  19.910s  |  19.910s  |   0.000s  | 0.0%|
|164.smt2                                                                                    |  19.187s  |  19.187s  |   0.000s  | 0.0%|
|165.smt2                                                                                    |  19.931s  |  19.931s  |   0.000s  | 0.0%|
|166.smt2                                                                                    |  19.599s  |  19.599s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |  19.889s  |  19.889s  |   0.000s  | 0.0%|
|168.smt2                                                                                    |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|169.smt2                                                                                    |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|17.smt2                                                                                     |  19.903s  |  19.903s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  19.726s  |  19.726s  |   0.000s  | 0.0%|
|171.smt2                                                                                    |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|172.smt2                                                                                    |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|173.smt2                                                                                    |  19.892s  |  19.892s  |   0.000s  | 0.0%|
|174.smt2                                                                                    |  19.910s  |  19.910s  |   0.000s  | 0.0%|
|175.smt2                                                                                    |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|176.smt2                                                                                    |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|178.smt2                                                                                    |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|18.smt2                                                                                     |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|180.smt2                                                                                    |  19.913s  |  19.913s  |   0.000s  | 0.0%|
|181.smt2                                                                                    |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|182.smt2                                                                                    |  19.809s  |  19.809s  |   0.000s  | 0.0%|
|183.smt2                                                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|184.smt2                                                                                    |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|185.smt2                                                                                    |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|186.smt2                                                                                    |  19.905s  |  19.905s  |   0.000s  | 0.0%|
|19.smt2                                                                                     |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|21.smt2                                                                                     |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|22.smt2                                                                                     |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|24.smt2                                                                                     |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|25.smt2                                                                                     |  19.931s  |  19.931s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|27.smt2                                                                                     |  19.862s  |  19.862s  |   0.000s  | 0.0%|
|28.smt2                                                                                     |  19.875s  |  19.875s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|30.smt2                                                                                     |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|31.smt2                                                                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|32.smt2                                                                                     |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.625s  |  19.625s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |  19.823s  |  19.823s  |   0.000s  | 0.0%|
|35.smt2                                                                                     |  19.841s  |  19.841s  |   0.000s  | 0.0%|
|36.smt2                                                                                     |  19.803s  |  19.803s  |   0.000s  | 0.0%|
|37.smt2                                                                                     |  19.825s  |  19.825s  |   0.000s  | 0.0%|
|38.smt2                                                                                     |  19.841s  |  19.841s  |   0.000s  | 0.0%|
|39.smt2                                                                                     |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|40.smt2                                                                                     |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|42.smt2                                                                                     |  19.704s  |  19.704s  |   0.000s  | 0.0%|
|43.smt2                                                                                     |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|44.smt2                                                                                     |  19.895s  |  19.895s  |   0.000s  | 0.0%|
|45.smt2                                                                                     |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|46.smt2                                                                                     |  19.915s  |  19.915s  |   0.000s  | 0.0%|
|47.smt2                                                                                     |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|48.smt2                                                                                     |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|49.smt2                                                                                     |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|50.smt2                                                                                     |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|51.smt2                                                                                     |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|52.smt2                                                                                     |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|53.smt2                                                                                     |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|54.smt2                                                                                     |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|55.smt2                                                                                     |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|56.smt2                                                                                     |  19.925s  |  19.925s  |   0.000s  | 0.0%|
|57.smt2                                                                                     |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|58.smt2                                                                                     |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|59.smt2                                                                                     |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|60.smt2                                                                                     |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|61.smt2                                                                                     |  19.240s  |  19.240s  |   0.000s  | 0.0%|
|62.smt2                                                                                     |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|63.smt2                                                                                     |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  19.725s  |  19.725s  |   0.000s  | 0.0%|
|65.smt2                                                                                     |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|66.smt2                                                                                     |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|67.smt2                                                                                     |  19.871s  |  19.871s  |   0.000s  | 0.0%|
|68.smt2                                                                                     |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|69.smt2                                                                                     |  19.721s  |  19.721s  |   0.000s  | 0.0%|
|70.smt2                                                                                     |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|71.smt2                                                                                     |  19.795s  |  19.795s  |   0.000s  | 0.0%|
|72.smt2                                                                                     |  19.794s  |  19.794s  |   0.000s  | 0.0%|
|73.smt2                                                                                     |  19.900s  |  19.900s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|76.smt2                                                                                     |  19.782s  |  19.782s  |   0.000s  | 0.0%|
|77.smt2                                                                                     |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|78.smt2                                                                                     |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|79.smt2                                                                                     |  19.929s  |  19.929s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|81.smt2                                                                                     |  19.728s  |  19.728s  |   0.000s  | 0.0%|
|82.smt2                                                                                     |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |  19.899s  |  19.899s  |   0.000s  | 0.0%|
|84.smt2                                                                                     |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|85.smt2                                                                                     |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|86.smt2                                                                                     |  19.666s  |  19.666s  |   0.000s  | 0.0%|
|87.smt2                                                                                     |  19.820s  |  19.820s  |   0.000s  | 0.0%|
|88.smt2                                                                                     |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|89.smt2                                                                                     |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|91.smt2                                                                                     |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|92.smt2                                                                                     |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|95.smt2                                                                                     |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|96.smt2                                                                                     |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|97.smt2                                                                                     |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  19.974s  |  19.974s  |   0.000s  | 0.0%|
</details>
