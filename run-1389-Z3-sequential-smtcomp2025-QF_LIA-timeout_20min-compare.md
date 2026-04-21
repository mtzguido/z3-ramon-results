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
Job tag: Z3-sequential-smtcomp2025-QF_LIA-timeout_20min
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 8e294820a0bcdbe59f6282f7a0a3f73f594bd601
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: backtrack more aggressively in search tree: close matching external targets (i.e. repeat literals on other branches)

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-sequential-smtcomp2025-QF_LIA-timeout_20min
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 8e294820a0bcdbe59f6282f7a0a3f73f594bd601
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: backtrack more aggressively in search tree: close matching external targets (i.e. repeat literals on other branches)

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1260.840s  |1260.840s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.034s  |1260.034s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.309s  |1260.309s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1260.513s  |1260.513s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1260.698s  |1260.698s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1260.725s  |1260.725s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1260.043s  |1260.043s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.181s  |1260.181s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1260.737s  |1260.737s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 819.866s  | 819.866s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1174.911s  |1174.911s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.200s  |1260.200s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.165s  |1260.165s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.070s  |1260.070s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.140s  |1260.140s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.020s  |1260.020s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1260.473s  |1260.473s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1260.037s  |1260.037s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1260.196s  |1260.196s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1260.417s  |1260.417s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1260.840s  |1260.840s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.034s  |1260.034s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.309s  |1260.309s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1260.513s  |1260.513s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1260.698s  |1260.698s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1260.725s  |1260.725s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1260.043s  |1260.043s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.181s  |1260.181s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1260.737s  |1260.737s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 819.866s  | 819.866s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1174.911s  |1174.911s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.200s  |1260.200s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.165s  |1260.165s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.070s  |1260.070s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.140s  |1260.140s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.020s  |1260.020s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1260.473s  |1260.473s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1260.037s  |1260.037s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1260.196s  |1260.196s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1260.417s  |1260.417s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1260.840s  |1260.840s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.034s  |1260.034s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.309s  |1260.309s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1260.513s  |1260.513s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1260.698s  |1260.698s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1260.725s  |1260.725s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1260.043s  |1260.043s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.181s  |1260.181s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1260.737s  |1260.737s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 819.866s  | 819.866s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1174.911s  |1174.911s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.200s  |1260.200s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.165s  |1260.165s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.070s  |1260.070s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.140s  |1260.140s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.020s  |1260.020s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1260.473s  |1260.473s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1260.037s  |1260.037s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1260.196s  |1260.196s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1260.417s  |1260.417s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1260.840s  |1260.840s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.034s  |1260.034s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.309s  |1260.309s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1260.513s  |1260.513s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1260.698s  |1260.698s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1260.725s  |1260.725s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1260.043s  |1260.043s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.181s  |1260.181s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1260.737s  |1260.737s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 819.866s  | 819.866s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1174.911s  |1174.911s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.200s  |1260.200s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.165s  |1260.165s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.070s  |1260.070s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.140s  |1260.140s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.020s  |1260.020s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1260.473s  |1260.473s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1260.037s  |1260.037s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1260.196s  |1260.196s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1260.417s  |1260.417s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled102166.smt2                                                                       |1260.840s |7475.0MiB|
|scrambled4198.smt2                                                                         |1260.835s |7174.0MiB|
|scrambled4299.smt2                                                                         |1260.798s |6870.0MiB|
|scrambled94658.smt2                                                                        |1260.773s |6806.0MiB|
|scrambled79760.smt2                                                                        |1260.765s |5944.0MiB|
|scrambled12042.smt2                                                                        |1260.737s |6179.0MiB|
|scrambled55680.smt2                                                                        |1260.733s |6057.0MiB|
|scrambled111627.smt2                                                                       |1260.725s |5804.0MiB|
|scrambled108840.smt2                                                                       |1260.698s |5686.0MiB|
|scrambled68944.smt2                                                                        |1260.627s |4741.0MiB|
|scrambled75189.smt2                                                                        |1260.613s |4318.0MiB|
|scrambled43577.smt2                                                                        |1260.548s |4194.0MiB|
|scrambled107826.smt2                                                                       |1260.513s |3504.0MiB|
|scrambled19335.smt2                                                                        |1260.473s |3356.0MiB|
|scrambled27843.smt2                                                                        |1260.417s |2334.0MiB|
|scrambled107115.smt2                                                                       |1260.309s |1957.0MiB|
|scrambled61922.smt2                                                                        |1260.292s |1280.0MiB|
|scrambled40621.smt2                                                                        |1260.215s |763.0MiB|
|scrambled128128.smt2                                                                       |1260.200s |682.0MiB|
|scrambled7741.smt2                                                                         |1260.196s |719.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled102166.smt2                                                                       |1260.840s |7475.0MiB|
|scrambled4198.smt2                                                                         |1260.835s |7174.0MiB|
|scrambled4299.smt2                                                                         |1260.798s |6870.0MiB|
|scrambled94658.smt2                                                                        |1260.773s |6806.0MiB|
|scrambled79760.smt2                                                                        |1260.765s |5944.0MiB|
|scrambled12042.smt2                                                                        |1260.737s |6179.0MiB|
|scrambled55680.smt2                                                                        |1260.733s |6057.0MiB|
|scrambled111627.smt2                                                                       |1260.725s |5804.0MiB|
|scrambled108840.smt2                                                                       |1260.698s |5686.0MiB|
|scrambled68944.smt2                                                                        |1260.627s |4741.0MiB|
|scrambled75189.smt2                                                                        |1260.613s |4318.0MiB|
|scrambled43577.smt2                                                                        |1260.548s |4194.0MiB|
|scrambled107826.smt2                                                                       |1260.513s |3504.0MiB|
|scrambled19335.smt2                                                                        |1260.473s |3356.0MiB|
|scrambled27843.smt2                                                                        |1260.417s |2334.0MiB|
|scrambled107115.smt2                                                                       |1260.309s |1957.0MiB|
|scrambled61922.smt2                                                                        |1260.292s |1280.0MiB|
|scrambled40621.smt2                                                                        |1260.215s |763.0MiB|
|scrambled128128.smt2                                                                       |1260.200s |682.0MiB|
|scrambled7741.smt2                                                                         |1260.196s |719.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7475.0MiB|7475.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.372MiB|42.372MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1957.0MiB|1957.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3504.0MiB|3504.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |5686.0MiB|5686.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |5804.0MiB|5804.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |989.0MiB|989.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |6179.0MiB|6179.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |164.0MiB|164.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |682.0MiB|682.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |520.0MiB|520.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |490.0MiB|490.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |570.0MiB|570.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |45.856MiB|45.856MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3356.0MiB|3356.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |174.0MiB|174.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |724.0MiB|724.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2334.0MiB|2334.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7475.0MiB|7475.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.372MiB|42.372MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1957.0MiB|1957.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3504.0MiB|3504.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |5686.0MiB|5686.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |5804.0MiB|5804.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |989.0MiB|989.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |6179.0MiB|6179.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |164.0MiB|164.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |682.0MiB|682.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |520.0MiB|520.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |490.0MiB|490.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |570.0MiB|570.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |45.856MiB|45.856MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3356.0MiB|3356.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |174.0MiB|174.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |724.0MiB|724.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2334.0MiB|2334.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7475.0MiB|7475.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.372MiB|42.372MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1957.0MiB|1957.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3504.0MiB|3504.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |5686.0MiB|5686.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |5804.0MiB|5804.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |989.0MiB|989.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |6179.0MiB|6179.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |164.0MiB|164.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |682.0MiB|682.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |520.0MiB|520.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |490.0MiB|490.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |570.0MiB|570.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |45.856MiB|45.856MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3356.0MiB|3356.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |174.0MiB|174.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |724.0MiB|724.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2334.0MiB|2334.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7475.0MiB|7475.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.372MiB|42.372MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1957.0MiB|1957.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3504.0MiB|3504.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |5686.0MiB|5686.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |5804.0MiB|5804.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |989.0MiB|989.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |6179.0MiB|6179.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |164.0MiB|164.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |682.0MiB|682.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |520.0MiB|520.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |490.0MiB|490.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |570.0MiB|570.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |45.856MiB|45.856MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3356.0MiB|3356.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |174.0MiB|174.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |724.0MiB|724.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2334.0MiB|2334.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled102166.smt2                                                                       |1260.840s |7475.0MiB|
|scrambled4198.smt2                                                                         |1260.835s |7174.0MiB|
|scrambled4299.smt2                                                                         |1260.798s |6870.0MiB|
|scrambled94658.smt2                                                                        |1260.773s |6806.0MiB|
|scrambled12042.smt2                                                                        |1260.737s |6179.0MiB|
|scrambled55680.smt2                                                                        |1260.733s |6057.0MiB|
|scrambled79760.smt2                                                                        |1260.765s |5944.0MiB|
|scrambled111627.smt2                                                                       |1260.725s |5804.0MiB|
|scrambled108840.smt2                                                                       |1260.698s |5686.0MiB|
|scrambled68944.smt2                                                                        |1260.627s |4741.0MiB|
|scrambled75189.smt2                                                                        |1260.613s |4318.0MiB|
|scrambled43577.smt2                                                                        |1260.548s |4194.0MiB|
|scrambled107826.smt2                                                                       |1260.513s |3504.0MiB|
|scrambled19335.smt2                                                                        |1260.473s |3356.0MiB|
|scrambled27843.smt2                                                                        |1260.417s |2334.0MiB|
|scrambled107115.smt2                                                                       |1260.309s |1957.0MiB|
|scrambled61922.smt2                                                                        |1260.292s |1280.0MiB|
|scrambled119331.smt2                                                                       |1260.181s |989.0MiB|
|scrambled40621.smt2                                                                        |1260.215s |763.0MiB|
|scrambled25238.smt2                                                                        |1260.196s |724.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled102166.smt2                                                                       |1260.840s |7475.0MiB|
|scrambled4198.smt2                                                                         |1260.835s |7174.0MiB|
|scrambled4299.smt2                                                                         |1260.798s |6870.0MiB|
|scrambled94658.smt2                                                                        |1260.773s |6806.0MiB|
|scrambled12042.smt2                                                                        |1260.737s |6179.0MiB|
|scrambled55680.smt2                                                                        |1260.733s |6057.0MiB|
|scrambled79760.smt2                                                                        |1260.765s |5944.0MiB|
|scrambled111627.smt2                                                                       |1260.725s |5804.0MiB|
|scrambled108840.smt2                                                                       |1260.698s |5686.0MiB|
|scrambled68944.smt2                                                                        |1260.627s |4741.0MiB|
|scrambled75189.smt2                                                                        |1260.613s |4318.0MiB|
|scrambled43577.smt2                                                                        |1260.548s |4194.0MiB|
|scrambled107826.smt2                                                                       |1260.513s |3504.0MiB|
|scrambled19335.smt2                                                                        |1260.473s |3356.0MiB|
|scrambled27843.smt2                                                                        |1260.417s |2334.0MiB|
|scrambled107115.smt2                                                                       |1260.309s |1957.0MiB|
|scrambled61922.smt2                                                                        |1260.292s |1280.0MiB|
|scrambled119331.smt2                                                                       |1260.181s |989.0MiB|
|scrambled40621.smt2                                                                        |1260.215s |763.0MiB|
|scrambled25238.smt2                                                                        |1260.196s |724.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1260.840s  |1260.840s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.034s  |1260.034s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.309s  |1260.309s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1260.513s  |1260.513s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1260.698s  |1260.698s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1260.725s  |1260.725s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1260.043s  |1260.043s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.181s  |1260.181s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1260.737s  |1260.737s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 819.866s  | 819.866s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1174.911s  |1174.911s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.200s  |1260.200s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.165s  |1260.165s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.070s  |1260.070s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.140s  |1260.140s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.020s  |1260.020s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1260.473s  |1260.473s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1260.037s  |1260.037s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1260.196s  |1260.196s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1260.417s  |1260.417s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1260.054s  |1260.054s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1260.041s  |1260.041s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1260.031s  |1260.031s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1260.215s  |1260.215s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1260.835s  |1260.835s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1260.798s  |1260.798s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1260.548s  |1260.548s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1260.151s  |1260.151s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1260.034s  |1260.034s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1260.099s  |1260.099s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1260.733s  |1260.733s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1260.125s  |1260.125s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1260.034s  |1260.034s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1260.292s  |1260.292s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1260.034s  |1260.034s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1260.627s  |1260.627s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1260.160s  |1260.160s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1260.613s  |1260.613s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1260.196s  |1260.196s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1260.765s  |1260.765s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1260.016s  |1260.016s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1260.029s  |1260.029s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1260.773s  |1260.773s  |   0.000s  | 0.0%|
</details>
