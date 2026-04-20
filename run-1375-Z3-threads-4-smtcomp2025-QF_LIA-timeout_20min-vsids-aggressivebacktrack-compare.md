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
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false"
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
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: backtrack more aggressively in search tree: close matching external targets (i.e. repeat literals on other branches)

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.435s  |1262.435s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.031s  |1260.031s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.910s  |1260.910s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.427s  |1261.427s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.073s  |1262.073s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.077s  |1262.077s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 114.059s  | 114.059s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.591s  |1260.591s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.003s  |1263.003s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1180.114s  |1180.114s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 203.232s  | 203.232s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.489s  |1260.489s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.444s  |1260.444s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.354s  |1260.354s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.464s  |1260.464s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.034s  |1260.034s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.510s  |1261.510s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  68.566s  |  68.566s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 624.633s  | 624.633s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.482s  |1261.482s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.435s  |1262.435s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.031s  |1260.031s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.910s  |1260.910s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.427s  |1261.427s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.073s  |1262.073s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.077s  |1262.077s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 114.059s  | 114.059s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.591s  |1260.591s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.003s  |1263.003s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1180.114s  |1180.114s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 203.232s  | 203.232s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.489s  |1260.489s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.444s  |1260.444s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.354s  |1260.354s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.464s  |1260.464s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.034s  |1260.034s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.510s  |1261.510s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  68.566s  |  68.566s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 624.633s  | 624.633s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.482s  |1261.482s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.435s  |1262.435s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.031s  |1260.031s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.910s  |1260.910s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.427s  |1261.427s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.073s  |1262.073s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.077s  |1262.077s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 114.059s  | 114.059s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.591s  |1260.591s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.003s  |1263.003s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1180.114s  |1180.114s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 203.232s  | 203.232s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.489s  |1260.489s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.444s  |1260.444s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.354s  |1260.354s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.464s  |1260.464s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.034s  |1260.034s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.510s  |1261.510s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  68.566s  |  68.566s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 624.633s  | 624.633s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.482s  |1261.482s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.435s  |1262.435s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.031s  |1260.031s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.910s  |1260.910s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.427s  |1261.427s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.073s  |1262.073s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.077s  |1262.077s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 114.059s  | 114.059s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.591s  |1260.591s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.003s  |1263.003s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1180.114s  |1180.114s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 203.232s  | 203.232s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.489s  |1260.489s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.444s  |1260.444s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.354s  |1260.354s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.464s  |1260.464s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.034s  |1260.034s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.510s  |1261.510s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  68.566s  |  68.566s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 624.633s  | 624.633s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.482s  |1261.482s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.120s |31.336GiB|
|scrambled12042.smt2                                                                        |1263.003s |29.827GiB|
|scrambled4299.smt2                                                                         |1262.706s |25.996GiB|
|scrambled55680.smt2                                                                        |1262.577s |24.975GiB|
|scrambled102166.smt2                                                                       |1262.435s |23.383GiB|
|scrambled79760.smt2                                                                        |1262.318s |21.916GiB|
|scrambled68944.smt2                                                                        |1262.245s |23.207GiB|
|scrambled4198.smt2                                                                         |1262.146s |25.315GiB|
|scrambled111627.smt2                                                                       |1262.077s |18.995GiB|
|scrambled108840.smt2                                                                       |1262.073s |22.294GiB|
|scrambled75189.smt2                                                                        |1261.907s |17.036GiB|
|scrambled19335.smt2                                                                        |1261.510s |15.594GiB|
|scrambled43577.smt2                                                                        |1261.489s |15.292GiB|
|scrambled27843.smt2                                                                        |1261.482s |11.123GiB|
|scrambled107826.smt2                                                                       |1261.427s |14.227GiB|
|scrambled107115.smt2                                                                       |1260.910s |8691.0MiB|
|scrambled61922.smt2                                                                        |1260.806s |5556.0MiB|
|scrambled119331.smt2                                                                       |1260.591s |3775.0MiB|
|scrambled40621.smt2                                                                        |1260.565s |4736.0MiB|
|scrambled128128.smt2                                                                       |1260.489s |2571.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.120s |31.336GiB|
|scrambled12042.smt2                                                                        |1263.003s |29.827GiB|
|scrambled4299.smt2                                                                         |1262.706s |25.996GiB|
|scrambled55680.smt2                                                                        |1262.577s |24.975GiB|
|scrambled102166.smt2                                                                       |1262.435s |23.383GiB|
|scrambled79760.smt2                                                                        |1262.318s |21.916GiB|
|scrambled68944.smt2                                                                        |1262.245s |23.207GiB|
|scrambled4198.smt2                                                                         |1262.146s |25.315GiB|
|scrambled111627.smt2                                                                       |1262.077s |18.995GiB|
|scrambled108840.smt2                                                                       |1262.073s |22.294GiB|
|scrambled75189.smt2                                                                        |1261.907s |17.036GiB|
|scrambled19335.smt2                                                                        |1261.510s |15.594GiB|
|scrambled43577.smt2                                                                        |1261.489s |15.292GiB|
|scrambled27843.smt2                                                                        |1261.482s |11.123GiB|
|scrambled107826.smt2                                                                       |1261.427s |14.227GiB|
|scrambled107115.smt2                                                                       |1260.910s |8691.0MiB|
|scrambled61922.smt2                                                                        |1260.806s |5556.0MiB|
|scrambled119331.smt2                                                                       |1260.591s |3775.0MiB|
|scrambled40621.smt2                                                                        |1260.565s |4736.0MiB|
|scrambled128128.smt2                                                                       |1260.489s |2571.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.383GiB|23.383GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.544MiB|42.544MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8691.0MiB|8691.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.227GiB|14.227GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.294GiB|22.294GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.995GiB|18.995GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3775.0MiB|3775.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.827GiB|29.827GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |415.0MiB|415.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |644.0MiB|644.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2571.0MiB|2571.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2085.0MiB|2085.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2113.0MiB|2113.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2578.0MiB|2578.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.594GiB|15.594GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |623.0MiB|623.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2845.0MiB|2845.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.123GiB|11.123GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.383GiB|23.383GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.544MiB|42.544MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8691.0MiB|8691.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.227GiB|14.227GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.294GiB|22.294GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.995GiB|18.995GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3775.0MiB|3775.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.827GiB|29.827GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |415.0MiB|415.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |644.0MiB|644.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2571.0MiB|2571.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2085.0MiB|2085.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2113.0MiB|2113.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2578.0MiB|2578.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.594GiB|15.594GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |623.0MiB|623.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2845.0MiB|2845.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.123GiB|11.123GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.383GiB|23.383GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.544MiB|42.544MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8691.0MiB|8691.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.227GiB|14.227GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.294GiB|22.294GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.995GiB|18.995GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3775.0MiB|3775.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.827GiB|29.827GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |415.0MiB|415.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |644.0MiB|644.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2571.0MiB|2571.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2085.0MiB|2085.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2113.0MiB|2113.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2578.0MiB|2578.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.594GiB|15.594GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |623.0MiB|623.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2845.0MiB|2845.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.123GiB|11.123GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.383GiB|23.383GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.544MiB|42.544MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8691.0MiB|8691.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.227GiB|14.227GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.294GiB|22.294GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.995GiB|18.995GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3775.0MiB|3775.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.827GiB|29.827GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |415.0MiB|415.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |644.0MiB|644.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2571.0MiB|2571.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2085.0MiB|2085.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2113.0MiB|2113.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2578.0MiB|2578.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.594GiB|15.594GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |623.0MiB|623.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2845.0MiB|2845.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.123GiB|11.123GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.120s |31.336GiB|
|scrambled12042.smt2                                                                        |1263.003s |29.827GiB|
|scrambled4299.smt2                                                                         |1262.706s |25.996GiB|
|scrambled4198.smt2                                                                         |1262.146s |25.315GiB|
|scrambled55680.smt2                                                                        |1262.577s |24.975GiB|
|scrambled102166.smt2                                                                       |1262.435s |23.383GiB|
|scrambled68944.smt2                                                                        |1262.245s |23.207GiB|
|scrambled108840.smt2                                                                       |1262.073s |22.294GiB|
|scrambled79760.smt2                                                                        |1262.318s |21.916GiB|
|scrambled111627.smt2                                                                       |1262.077s |18.995GiB|
|scrambled75189.smt2                                                                        |1261.907s |17.036GiB|
|scrambled19335.smt2                                                                        |1261.510s |15.594GiB|
|scrambled43577.smt2                                                                        |1261.489s |15.292GiB|
|scrambled107826.smt2                                                                       |1261.427s |14.227GiB|
|scrambled27843.smt2                                                                        |1261.482s |11.123GiB|
|scrambled107115.smt2                                                                       |1260.910s |8691.0MiB|
|scrambled61922.smt2                                                                        |1260.806s |5556.0MiB|
|scrambled40621.smt2                                                                        |1260.565s |4736.0MiB|
|scrambled119331.smt2                                                                       |1260.591s |3775.0MiB|
|scrambled25238.smt2                                                                        | 624.633s |2845.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.120s |31.336GiB|
|scrambled12042.smt2                                                                        |1263.003s |29.827GiB|
|scrambled4299.smt2                                                                         |1262.706s |25.996GiB|
|scrambled4198.smt2                                                                         |1262.146s |25.315GiB|
|scrambled55680.smt2                                                                        |1262.577s |24.975GiB|
|scrambled102166.smt2                                                                       |1262.435s |23.383GiB|
|scrambled68944.smt2                                                                        |1262.245s |23.207GiB|
|scrambled108840.smt2                                                                       |1262.073s |22.294GiB|
|scrambled79760.smt2                                                                        |1262.318s |21.916GiB|
|scrambled111627.smt2                                                                       |1262.077s |18.995GiB|
|scrambled75189.smt2                                                                        |1261.907s |17.036GiB|
|scrambled19335.smt2                                                                        |1261.510s |15.594GiB|
|scrambled43577.smt2                                                                        |1261.489s |15.292GiB|
|scrambled107826.smt2                                                                       |1261.427s |14.227GiB|
|scrambled27843.smt2                                                                        |1261.482s |11.123GiB|
|scrambled107115.smt2                                                                       |1260.910s |8691.0MiB|
|scrambled61922.smt2                                                                        |1260.806s |5556.0MiB|
|scrambled40621.smt2                                                                        |1260.565s |4736.0MiB|
|scrambled119331.smt2                                                                       |1260.591s |3775.0MiB|
|scrambled25238.smt2                                                                        | 624.633s |2845.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.435s  |1262.435s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.031s  |1260.031s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.910s  |1260.910s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.427s  |1261.427s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.073s  |1262.073s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.077s  |1262.077s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 114.059s  | 114.059s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.591s  |1260.591s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.003s  |1263.003s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1180.114s  |1180.114s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 203.232s  | 203.232s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.489s  |1260.489s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.444s  |1260.444s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.354s  |1260.354s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.464s  |1260.464s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.034s  |1260.034s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.510s  |1261.510s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  68.566s  |  68.566s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 624.633s  | 624.633s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.482s  |1261.482s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 482.830s  | 482.830s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1260.048s  |1260.048s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1260.038s  |1260.038s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1260.565s  |1260.565s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1262.146s  |1262.146s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1262.706s  |1262.706s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1261.489s  |1261.489s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1260.245s  |1260.245s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1260.025s  |1260.025s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1260.212s  |1260.212s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1262.577s  |1262.577s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1260.196s  |1260.196s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1260.023s  |1260.023s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1260.806s  |1260.806s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1260.023s  |1260.023s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1262.245s  |1262.245s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1058.226s  |1058.226s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1261.907s  |1261.907s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1260.462s  |1260.462s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1262.318s  |1262.318s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1260.017s  |1260.017s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1260.050s  |1260.050s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1263.120s  |1263.120s  |   0.000s  | 0.0%|
</details>
