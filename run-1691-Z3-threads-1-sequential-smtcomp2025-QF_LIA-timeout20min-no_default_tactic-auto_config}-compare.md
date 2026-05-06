Comparing data and data


# SUMMARY
- LHS tests = 44
- RHS tests = 44
- LHS success = 44  (100.0%)
- RHS success = 44  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_LIA-timeout20min-no_default_tactic-auto_config}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_LIA-timeout20min-no_default_tactic-auto_config}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.722s  |1200.722s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.285s  |1200.285s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.388s  |1200.388s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.596s  |1200.596s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.580s  |1200.580s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 158.233s  | 158.233s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.654s  |1200.654s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 882.210s  | 882.210s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.420s  |1200.420s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 836.220s  | 836.220s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.323s  |1200.323s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.722s  |1200.722s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.285s  |1200.285s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.388s  |1200.388s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.596s  |1200.596s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.580s  |1200.580s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 158.233s  | 158.233s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.654s  |1200.654s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 882.210s  | 882.210s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.420s  |1200.420s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 836.220s  | 836.220s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.323s  |1200.323s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.722s  |1200.722s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.285s  |1200.285s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.388s  |1200.388s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.596s  |1200.596s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.580s  |1200.580s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 158.233s  | 158.233s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.654s  |1200.654s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 882.210s  | 882.210s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.420s  |1200.420s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 836.220s  | 836.220s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.323s  |1200.323s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.722s  |1200.722s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.285s  |1200.285s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.388s  |1200.388s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.596s  |1200.596s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.580s  |1200.580s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 158.233s  | 158.233s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.654s  |1200.654s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 882.210s  | 882.210s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.420s  |1200.420s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 836.220s  | 836.220s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.323s  |1200.323s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled4198.smt2                                                                         |1200.738s |7116.0MiB|
|scrambled102166.smt2                                                                       |1200.722s |7338.0MiB|
|scrambled94658.smt2                                                                        |1200.705s |6749.0MiB|
|scrambled4299.smt2                                                                         |1200.664s |6773.0MiB|
|scrambled12042.smt2                                                                        |1200.654s |6117.0MiB|
|scrambled55680.smt2                                                                        |1200.641s |6012.0MiB|
|scrambled79760.smt2                                                                        |1200.606s |5912.0MiB|
|scrambled108840.smt2                                                                       |1200.596s |5487.0MiB|
|scrambled111627.smt2                                                                       |1200.580s |5771.0MiB|
|scrambled75189.smt2                                                                        |1200.495s |4292.0MiB|
|scrambled68944.smt2                                                                        |1200.485s |4711.0MiB|
|scrambled43577.smt2                                                                        |1200.475s |4155.0MiB|
|scrambled19335.smt2                                                                        |1200.420s |3326.0MiB|
|scrambled107826.smt2                                                                       |1200.388s |3473.0MiB|
|scrambled27843.smt2                                                                        |1200.323s |2300.0MiB|
|scrambled107115.smt2                                                                       |1200.285s |1924.0MiB|
|scrambled61922.smt2                                                                        |1200.212s |1246.0MiB|
|scrambled119331.smt2                                                                       |1200.134s |595.0MiB|
|scrambled40621.smt2                                                                        |1200.132s |938.0MiB|
|scrambled7741.smt2                                                                         |1200.123s |524.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled4198.smt2                                                                         |1200.738s |7116.0MiB|
|scrambled102166.smt2                                                                       |1200.722s |7338.0MiB|
|scrambled94658.smt2                                                                        |1200.705s |6749.0MiB|
|scrambled4299.smt2                                                                         |1200.664s |6773.0MiB|
|scrambled12042.smt2                                                                        |1200.654s |6117.0MiB|
|scrambled55680.smt2                                                                        |1200.641s |6012.0MiB|
|scrambled79760.smt2                                                                        |1200.606s |5912.0MiB|
|scrambled108840.smt2                                                                       |1200.596s |5487.0MiB|
|scrambled111627.smt2                                                                       |1200.580s |5771.0MiB|
|scrambled75189.smt2                                                                        |1200.495s |4292.0MiB|
|scrambled68944.smt2                                                                        |1200.485s |4711.0MiB|
|scrambled43577.smt2                                                                        |1200.475s |4155.0MiB|
|scrambled19335.smt2                                                                        |1200.420s |3326.0MiB|
|scrambled107826.smt2                                                                       |1200.388s |3473.0MiB|
|scrambled27843.smt2                                                                        |1200.323s |2300.0MiB|
|scrambled107115.smt2                                                                       |1200.285s |1924.0MiB|
|scrambled61922.smt2                                                                        |1200.212s |1246.0MiB|
|scrambled119331.smt2                                                                       |1200.134s |595.0MiB|
|scrambled40621.smt2                                                                        |1200.132s |938.0MiB|
|scrambled7741.smt2                                                                         |1200.123s |524.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7338.0MiB|7338.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.836MiB|42.836MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1924.0MiB|1924.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3473.0MiB|3473.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |5487.0MiB|5487.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |5771.0MiB|5771.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |595.0MiB|595.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |6117.0MiB|6117.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |100.0MiB|100.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |177.0MiB|177.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |426.0MiB|426.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |475.0MiB|475.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |454.0MiB|454.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |511.0MiB|511.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |67.732MiB|67.732MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3326.0MiB|3326.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |171.0MiB|171.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |639.0MiB|639.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2300.0MiB|2300.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7338.0MiB|7338.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.836MiB|42.836MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1924.0MiB|1924.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3473.0MiB|3473.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |5487.0MiB|5487.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |5771.0MiB|5771.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |595.0MiB|595.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |6117.0MiB|6117.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |100.0MiB|100.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |177.0MiB|177.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |426.0MiB|426.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |475.0MiB|475.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |454.0MiB|454.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |511.0MiB|511.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |67.732MiB|67.732MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3326.0MiB|3326.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |171.0MiB|171.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |639.0MiB|639.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2300.0MiB|2300.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7338.0MiB|7338.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.836MiB|42.836MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1924.0MiB|1924.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3473.0MiB|3473.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |5487.0MiB|5487.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |5771.0MiB|5771.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |595.0MiB|595.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |6117.0MiB|6117.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |100.0MiB|100.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |177.0MiB|177.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |426.0MiB|426.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |475.0MiB|475.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |454.0MiB|454.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |511.0MiB|511.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |67.732MiB|67.732MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3326.0MiB|3326.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |171.0MiB|171.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |639.0MiB|639.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2300.0MiB|2300.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7338.0MiB|7338.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.836MiB|42.836MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1924.0MiB|1924.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3473.0MiB|3473.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |5487.0MiB|5487.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |5771.0MiB|5771.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |595.0MiB|595.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |6117.0MiB|6117.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |100.0MiB|100.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |177.0MiB|177.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |426.0MiB|426.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |475.0MiB|475.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |454.0MiB|454.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |511.0MiB|511.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |67.732MiB|67.732MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3326.0MiB|3326.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |171.0MiB|171.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |639.0MiB|639.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2300.0MiB|2300.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled102166.smt2                                                                       |1200.722s |7338.0MiB|
|scrambled4198.smt2                                                                         |1200.738s |7116.0MiB|
|scrambled4299.smt2                                                                         |1200.664s |6773.0MiB|
|scrambled94658.smt2                                                                        |1200.705s |6749.0MiB|
|scrambled12042.smt2                                                                        |1200.654s |6117.0MiB|
|scrambled55680.smt2                                                                        |1200.641s |6012.0MiB|
|scrambled79760.smt2                                                                        |1200.606s |5912.0MiB|
|scrambled111627.smt2                                                                       |1200.580s |5771.0MiB|
|scrambled108840.smt2                                                                       |1200.596s |5487.0MiB|
|scrambled68944.smt2                                                                        |1200.485s |4711.0MiB|
|scrambled75189.smt2                                                                        |1200.495s |4292.0MiB|
|scrambled43577.smt2                                                                        |1200.475s |4155.0MiB|
|scrambled107826.smt2                                                                       |1200.388s |3473.0MiB|
|scrambled19335.smt2                                                                        |1200.420s |3326.0MiB|
|scrambled27843.smt2                                                                        |1200.323s |2300.0MiB|
|scrambled107115.smt2                                                                       |1200.285s |1924.0MiB|
|scrambled61922.smt2                                                                        |1200.212s |1246.0MiB|
|scrambled40621.smt2                                                                        |1200.132s |938.0MiB|
|scrambled25238.smt2                                                                        | 836.220s |639.0MiB|
|scrambled119331.smt2                                                                       |1200.134s |595.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled102166.smt2                                                                       |1200.722s |7338.0MiB|
|scrambled4198.smt2                                                                         |1200.738s |7116.0MiB|
|scrambled4299.smt2                                                                         |1200.664s |6773.0MiB|
|scrambled94658.smt2                                                                        |1200.705s |6749.0MiB|
|scrambled12042.smt2                                                                        |1200.654s |6117.0MiB|
|scrambled55680.smt2                                                                        |1200.641s |6012.0MiB|
|scrambled79760.smt2                                                                        |1200.606s |5912.0MiB|
|scrambled111627.smt2                                                                       |1200.580s |5771.0MiB|
|scrambled108840.smt2                                                                       |1200.596s |5487.0MiB|
|scrambled68944.smt2                                                                        |1200.485s |4711.0MiB|
|scrambled75189.smt2                                                                        |1200.495s |4292.0MiB|
|scrambled43577.smt2                                                                        |1200.475s |4155.0MiB|
|scrambled107826.smt2                                                                       |1200.388s |3473.0MiB|
|scrambled19335.smt2                                                                        |1200.420s |3326.0MiB|
|scrambled27843.smt2                                                                        |1200.323s |2300.0MiB|
|scrambled107115.smt2                                                                       |1200.285s |1924.0MiB|
|scrambled61922.smt2                                                                        |1200.212s |1246.0MiB|
|scrambled40621.smt2                                                                        |1200.132s |938.0MiB|
|scrambled25238.smt2                                                                        | 836.220s |639.0MiB|
|scrambled119331.smt2                                                                       |1200.134s |595.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.722s  |1200.722s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.285s  |1200.285s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.388s  |1200.388s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.596s  |1200.596s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.580s  |1200.580s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 158.233s  | 158.233s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.654s  |1200.654s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 882.210s  | 882.210s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.420s  |1200.420s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 836.220s  | 836.220s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1200.738s  |1200.738s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1200.664s  |1200.664s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1200.475s  |1200.475s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1200.641s  |1200.641s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1200.485s  |1200.485s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1200.495s  |1200.495s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1200.606s  |1200.606s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1200.705s  |1200.705s  |   0.000s  | 0.0%|
</details>
