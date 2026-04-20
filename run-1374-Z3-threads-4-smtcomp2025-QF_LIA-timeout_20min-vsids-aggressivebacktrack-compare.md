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
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-vsids-aggressivebacktrack
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 8e294820a0bcdbe59f6282f7a0a3f73f594bd601
Z3 branch: backbones
Z3 options: "-T:60 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: backtrack more aggressively in search tree: close matching external targets (i.e. repeat literals on other branches)

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-vsids-aggressivebacktrack
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 8e294820a0bcdbe59f6282f7a0a3f73f594bd601
Z3 branch: backbones
Z3 options: "-T:60 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: backtrack more aggressively in search tree: close matching external targets (i.e. repeat literals on other branches)

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  60.410s  |  60.410s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  60.014s  |  60.014s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  60.634s  |  60.634s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  60.674s  |  60.674s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  60.496s  |  60.496s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  60.919s  |  60.919s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  60.098s  |  60.098s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  60.396s  |  60.396s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  60.588s  |  60.588s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  60.124s  |  60.124s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  60.096s  |  60.096s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  60.329s  |  60.329s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  60.203s  |  60.203s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  60.337s  |  60.337s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  60.372s  |  60.372s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  60.049s  |  60.049s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  60.709s  |  60.709s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  60.306s  |  60.306s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  60.703s  |  60.703s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  60.410s  |  60.410s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  60.014s  |  60.014s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  60.634s  |  60.634s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  60.674s  |  60.674s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  60.496s  |  60.496s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  60.919s  |  60.919s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  60.098s  |  60.098s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  60.396s  |  60.396s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  60.588s  |  60.588s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  60.124s  |  60.124s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  60.096s  |  60.096s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  60.329s  |  60.329s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  60.203s  |  60.203s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  60.337s  |  60.337s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  60.372s  |  60.372s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  60.049s  |  60.049s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  60.709s  |  60.709s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  60.306s  |  60.306s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  60.703s  |  60.703s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  60.410s  |  60.410s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  60.014s  |  60.014s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  60.634s  |  60.634s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  60.674s  |  60.674s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  60.496s  |  60.496s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  60.919s  |  60.919s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  60.098s  |  60.098s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  60.396s  |  60.396s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  60.588s  |  60.588s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  60.124s  |  60.124s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  60.096s  |  60.096s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  60.329s  |  60.329s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  60.203s  |  60.203s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  60.337s  |  60.337s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  60.372s  |  60.372s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  60.049s  |  60.049s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  60.709s  |  60.709s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  60.306s  |  60.306s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  60.703s  |  60.703s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  60.410s  |  60.410s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  60.014s  |  60.014s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  60.634s  |  60.634s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  60.674s  |  60.674s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  60.496s  |  60.496s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  60.919s  |  60.919s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  60.098s  |  60.098s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  60.396s  |  60.396s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  60.588s  |  60.588s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  60.124s  |  60.124s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  60.096s  |  60.096s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  60.329s  |  60.329s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  60.203s  |  60.203s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  60.337s  |  60.337s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  60.372s  |  60.372s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  60.049s  |  60.049s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  60.709s  |  60.709s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  60.306s  |  60.306s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  60.703s  |  60.703s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled75189.smt2                                                                        |  61.017s |7170.0MiB|
|scrambled68944.smt2                                                                        |  60.958s |7456.0MiB|
|scrambled111627.smt2                                                                       |  60.919s |6798.0MiB|
|scrambled79760.smt2                                                                        |  60.721s |5756.0MiB|
|scrambled19335.smt2                                                                        |  60.709s |5898.0MiB|
|scrambled27843.smt2                                                                        |  60.703s |5114.0MiB|
|scrambled107826.smt2                                                                       |  60.674s |5239.0MiB|
|scrambled107115.smt2                                                                       |  60.634s |4775.0MiB|
|scrambled43577.smt2                                                                        |  60.630s |4663.0MiB|
|scrambled12042.smt2                                                                        |  60.588s |3357.0MiB|
|scrambled55680.smt2                                                                        |  60.564s |2912.0MiB|
|scrambled108840.smt2                                                                       |  60.496s |2271.0MiB|
|scrambled61922.smt2                                                                        |  60.485s |3016.0MiB|
|scrambled4198.smt2                                                                         |  60.472s |3478.0MiB|
|scrambled4299.smt2                                                                         |  60.467s |2164.0MiB|
|scrambled94658.smt2                                                                        |  60.435s |3305.0MiB|
|scrambled102166.smt2                                                                       |  60.410s |2608.0MiB|
|scrambled119331.smt2                                                                       |  60.396s |1767.0MiB|
|scrambled40621.smt2                                                                        |  60.373s |1941.0MiB|
|scrambled131241.smt2                                                                       |  60.372s |1485.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled75189.smt2                                                                        |  61.017s |7170.0MiB|
|scrambled68944.smt2                                                                        |  60.958s |7456.0MiB|
|scrambled111627.smt2                                                                       |  60.919s |6798.0MiB|
|scrambled79760.smt2                                                                        |  60.721s |5756.0MiB|
|scrambled19335.smt2                                                                        |  60.709s |5898.0MiB|
|scrambled27843.smt2                                                                        |  60.703s |5114.0MiB|
|scrambled107826.smt2                                                                       |  60.674s |5239.0MiB|
|scrambled107115.smt2                                                                       |  60.634s |4775.0MiB|
|scrambled43577.smt2                                                                        |  60.630s |4663.0MiB|
|scrambled12042.smt2                                                                        |  60.588s |3357.0MiB|
|scrambled55680.smt2                                                                        |  60.564s |2912.0MiB|
|scrambled108840.smt2                                                                       |  60.496s |2271.0MiB|
|scrambled61922.smt2                                                                        |  60.485s |3016.0MiB|
|scrambled4198.smt2                                                                         |  60.472s |3478.0MiB|
|scrambled4299.smt2                                                                         |  60.467s |2164.0MiB|
|scrambled94658.smt2                                                                        |  60.435s |3305.0MiB|
|scrambled102166.smt2                                                                       |  60.410s |2608.0MiB|
|scrambled119331.smt2                                                                       |  60.396s |1767.0MiB|
|scrambled40621.smt2                                                                        |  60.373s |1941.0MiB|
|scrambled131241.smt2                                                                       |  60.372s |1485.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2608.0MiB|2608.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.288MiB|42.288MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |4775.0MiB|4775.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |5239.0MiB|5239.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |2271.0MiB|2271.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |6798.0MiB|6798.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |357.0MiB|357.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |1767.0MiB|1767.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |3357.0MiB|3357.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |398.0MiB|398.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |599.0MiB|599.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |1243.0MiB|1243.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1286.0MiB|1286.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1466.0MiB|1466.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |1485.0MiB|1485.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |122.0MiB|122.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |5898.0MiB|5898.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |629.0MiB|629.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1790.0MiB|1790.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |5114.0MiB|5114.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2608.0MiB|2608.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.288MiB|42.288MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |4775.0MiB|4775.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |5239.0MiB|5239.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |2271.0MiB|2271.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |6798.0MiB|6798.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |357.0MiB|357.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |1767.0MiB|1767.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |3357.0MiB|3357.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |398.0MiB|398.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |599.0MiB|599.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |1243.0MiB|1243.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1286.0MiB|1286.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1466.0MiB|1466.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |1485.0MiB|1485.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |122.0MiB|122.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |5898.0MiB|5898.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |629.0MiB|629.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1790.0MiB|1790.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |5114.0MiB|5114.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2608.0MiB|2608.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.288MiB|42.288MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |4775.0MiB|4775.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |5239.0MiB|5239.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |2271.0MiB|2271.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |6798.0MiB|6798.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |357.0MiB|357.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |1767.0MiB|1767.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |3357.0MiB|3357.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |398.0MiB|398.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |599.0MiB|599.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |1243.0MiB|1243.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1286.0MiB|1286.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1466.0MiB|1466.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |1485.0MiB|1485.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |122.0MiB|122.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |5898.0MiB|5898.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |629.0MiB|629.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1790.0MiB|1790.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |5114.0MiB|5114.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2608.0MiB|2608.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.288MiB|42.288MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |4775.0MiB|4775.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |5239.0MiB|5239.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |2271.0MiB|2271.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |6798.0MiB|6798.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |357.0MiB|357.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |1767.0MiB|1767.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |3357.0MiB|3357.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |398.0MiB|398.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |599.0MiB|599.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |1243.0MiB|1243.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1286.0MiB|1286.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1466.0MiB|1466.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |1485.0MiB|1485.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |122.0MiB|122.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |5898.0MiB|5898.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |629.0MiB|629.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1790.0MiB|1790.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |5114.0MiB|5114.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled68944.smt2                                                                        |  60.958s |7456.0MiB|
|scrambled75189.smt2                                                                        |  61.017s |7170.0MiB|
|scrambled111627.smt2                                                                       |  60.919s |6798.0MiB|
|scrambled19335.smt2                                                                        |  60.709s |5898.0MiB|
|scrambled79760.smt2                                                                        |  60.721s |5756.0MiB|
|scrambled107826.smt2                                                                       |  60.674s |5239.0MiB|
|scrambled27843.smt2                                                                        |  60.703s |5114.0MiB|
|scrambled107115.smt2                                                                       |  60.634s |4775.0MiB|
|scrambled43577.smt2                                                                        |  60.630s |4663.0MiB|
|scrambled4198.smt2                                                                         |  60.472s |3478.0MiB|
|scrambled12042.smt2                                                                        |  60.588s |3357.0MiB|
|scrambled94658.smt2                                                                        |  60.435s |3305.0MiB|
|scrambled61922.smt2                                                                        |  60.485s |3016.0MiB|
|scrambled55680.smt2                                                                        |  60.564s |2912.0MiB|
|scrambled102166.smt2                                                                       |  60.410s |2608.0MiB|
|scrambled108840.smt2                                                                       |  60.496s |2271.0MiB|
|scrambled4299.smt2                                                                         |  60.467s |2164.0MiB|
|scrambled40621.smt2                                                                        |  60.373s |1941.0MiB|
|scrambled25238.smt2                                                                        |  60.306s |1790.0MiB|
|scrambled119331.smt2                                                                       |  60.396s |1767.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled68944.smt2                                                                        |  60.958s |7456.0MiB|
|scrambled75189.smt2                                                                        |  61.017s |7170.0MiB|
|scrambled111627.smt2                                                                       |  60.919s |6798.0MiB|
|scrambled19335.smt2                                                                        |  60.709s |5898.0MiB|
|scrambled79760.smt2                                                                        |  60.721s |5756.0MiB|
|scrambled107826.smt2                                                                       |  60.674s |5239.0MiB|
|scrambled27843.smt2                                                                        |  60.703s |5114.0MiB|
|scrambled107115.smt2                                                                       |  60.634s |4775.0MiB|
|scrambled43577.smt2                                                                        |  60.630s |4663.0MiB|
|scrambled4198.smt2                                                                         |  60.472s |3478.0MiB|
|scrambled12042.smt2                                                                        |  60.588s |3357.0MiB|
|scrambled94658.smt2                                                                        |  60.435s |3305.0MiB|
|scrambled61922.smt2                                                                        |  60.485s |3016.0MiB|
|scrambled55680.smt2                                                                        |  60.564s |2912.0MiB|
|scrambled102166.smt2                                                                       |  60.410s |2608.0MiB|
|scrambled108840.smt2                                                                       |  60.496s |2271.0MiB|
|scrambled4299.smt2                                                                         |  60.467s |2164.0MiB|
|scrambled40621.smt2                                                                        |  60.373s |1941.0MiB|
|scrambled25238.smt2                                                                        |  60.306s |1790.0MiB|
|scrambled119331.smt2                                                                       |  60.396s |1767.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  60.410s  |  60.410s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  60.014s  |  60.014s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  60.634s  |  60.634s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  60.674s  |  60.674s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  60.496s  |  60.496s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  60.919s  |  60.919s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  60.098s  |  60.098s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  60.396s  |  60.396s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  60.588s  |  60.588s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  60.124s  |  60.124s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  60.096s  |  60.096s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  60.329s  |  60.329s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  60.203s  |  60.203s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  60.337s  |  60.337s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  60.372s  |  60.372s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  60.049s  |  60.049s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  60.709s  |  60.709s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  60.306s  |  60.306s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  60.703s  |  60.703s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |  60.174s  |  60.174s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |  60.051s  |  60.051s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |  60.025s  |  60.025s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |  60.373s  |  60.373s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |  60.472s  |  60.472s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |  60.467s  |  60.467s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |  60.630s  |  60.630s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |  60.178s  |  60.178s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |  60.036s  |  60.036s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |  60.278s  |  60.278s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |  60.564s  |  60.564s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |  60.145s  |  60.145s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |  60.032s  |  60.032s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |  60.485s  |  60.485s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |  60.023s  |  60.023s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |  60.958s  |  60.958s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |  60.240s  |  60.240s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |  61.017s  |  61.017s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |  60.289s  |  60.289s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |  60.721s  |  60.721s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |  60.052s  |  60.052s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |  60.024s  |  60.024s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |  60.435s  |  60.435s  |   0.000s  | 0.0%|
</details>
