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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-partial_share
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: fc6e0e2742443c693f569ba295c61781ffcc3916
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: core min and bb threads share units as global bb ONLY and do not actually send them to the worker threads, just use for pruning

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-partial_share
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: fc6e0e2742443c693f569ba295c61781ffcc3916
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: core min and bb threads share units as global bb ONLY and do not actually send them to the worker threads, just use for pruning

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.190s  |1204.190s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.758s  |1201.758s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.401s  |1202.401s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.826s  |1203.826s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1204.441s  |1204.441s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 117.685s  | 117.685s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.922s  |1200.922s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.934s  |1204.934s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 672.401s  | 672.401s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  95.489s  |  95.489s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.683s  |1200.683s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.520s  |1200.520s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.576s  |1200.576s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.735s  |1200.735s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.408s  |1203.408s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 114.381s  | 114.381s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 215.662s  | 215.662s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.541s  |1202.541s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.190s  |1204.190s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.758s  |1201.758s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.401s  |1202.401s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.826s  |1203.826s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1204.441s  |1204.441s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 117.685s  | 117.685s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.922s  |1200.922s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.934s  |1204.934s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 672.401s  | 672.401s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  95.489s  |  95.489s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.683s  |1200.683s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.520s  |1200.520s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.576s  |1200.576s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.735s  |1200.735s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.408s  |1203.408s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 114.381s  | 114.381s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 215.662s  | 215.662s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.541s  |1202.541s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.190s  |1204.190s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.758s  |1201.758s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.401s  |1202.401s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.826s  |1203.826s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1204.441s  |1204.441s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 117.685s  | 117.685s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.922s  |1200.922s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.934s  |1204.934s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 672.401s  | 672.401s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  95.489s  |  95.489s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.683s  |1200.683s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.520s  |1200.520s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.576s  |1200.576s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.735s  |1200.735s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.408s  |1203.408s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 114.381s  | 114.381s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 215.662s  | 215.662s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.541s  |1202.541s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.190s  |1204.190s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.758s  |1201.758s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.401s  |1202.401s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.826s  |1203.826s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1204.441s  |1204.441s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 117.685s  | 117.685s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.922s  |1200.922s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.934s  |1204.934s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 672.401s  | 672.401s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  95.489s  |  95.489s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.683s  |1200.683s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.520s  |1200.520s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.576s  |1200.576s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.735s  |1200.735s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.408s  |1203.408s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 114.381s  | 114.381s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 215.662s  | 215.662s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.541s  |1202.541s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.716s |63.257GiB|
|scrambled12042.smt2                                                                        |1204.934s |54.639GiB|
|scrambled4299.smt2                                                                         |1204.922s |56.789GiB|
|scrambled79760.smt2                                                                        |1204.824s |44.244GiB|
|scrambled68944.smt2                                                                        |1204.716s |46.324GiB|
|scrambled4198.smt2                                                                         |1204.567s |49.22GiB|
|scrambled55680.smt2                                                                        |1204.557s |50.685GiB|
|scrambled111627.smt2                                                                       |1204.441s |37.747GiB|
|scrambled102166.smt2                                                                       |1204.190s |48.152GiB|
|scrambled108840.smt2                                                                       |1203.826s |43.146GiB|
|scrambled43577.smt2                                                                        |1203.568s |34.26GiB|
|scrambled19335.smt2                                                                        |1203.408s |32.372GiB|
|scrambled75189.smt2                                                                        |1202.864s |31.696GiB|
|scrambled27843.smt2                                                                        |1202.541s |21.031GiB|
|scrambled107826.smt2                                                                       |1202.401s |27.972GiB|
|scrambled107115.smt2                                                                       |1201.758s |17.79GiB|
|scrambled72668.smt2                                                                        |1201.244s |5315.0MiB|
|scrambled61922.smt2                                                                        |1201.164s |10.83GiB|
|scrambled40621.smt2                                                                        |1201.125s |10.832GiB|
|scrambled119331.smt2                                                                       |1200.922s |9255.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.716s |63.257GiB|
|scrambled12042.smt2                                                                        |1204.934s |54.639GiB|
|scrambled4299.smt2                                                                         |1204.922s |56.789GiB|
|scrambled79760.smt2                                                                        |1204.824s |44.244GiB|
|scrambled68944.smt2                                                                        |1204.716s |46.324GiB|
|scrambled4198.smt2                                                                         |1204.567s |49.22GiB|
|scrambled55680.smt2                                                                        |1204.557s |50.685GiB|
|scrambled111627.smt2                                                                       |1204.441s |37.747GiB|
|scrambled102166.smt2                                                                       |1204.190s |48.152GiB|
|scrambled108840.smt2                                                                       |1203.826s |43.146GiB|
|scrambled43577.smt2                                                                        |1203.568s |34.26GiB|
|scrambled19335.smt2                                                                        |1203.408s |32.372GiB|
|scrambled75189.smt2                                                                        |1202.864s |31.696GiB|
|scrambled27843.smt2                                                                        |1202.541s |21.031GiB|
|scrambled107826.smt2                                                                       |1202.401s |27.972GiB|
|scrambled107115.smt2                                                                       |1201.758s |17.79GiB|
|scrambled72668.smt2                                                                        |1201.244s |5315.0MiB|
|scrambled61922.smt2                                                                        |1201.164s |10.83GiB|
|scrambled40621.smt2                                                                        |1201.125s |10.832GiB|
|scrambled119331.smt2                                                                       |1200.922s |9255.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.152GiB|48.152GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.312MiB|42.312MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.79GiB|17.79GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.972GiB|27.972GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.146GiB|43.146GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.747GiB|37.747GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |948.0MiB|948.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9255.0MiB|9255.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.639GiB|54.639GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1032.0MiB|1032.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1581.0MiB|1581.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6581.0MiB|6581.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5187.0MiB|5187.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5194.0MiB|5194.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6453.0MiB|6453.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.372GiB|32.372GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1627.0MiB|1627.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5904.0MiB|5904.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.031GiB|21.031GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.152GiB|48.152GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.312MiB|42.312MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.79GiB|17.79GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.972GiB|27.972GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.146GiB|43.146GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.747GiB|37.747GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |948.0MiB|948.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9255.0MiB|9255.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.639GiB|54.639GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1032.0MiB|1032.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1581.0MiB|1581.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6581.0MiB|6581.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5187.0MiB|5187.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5194.0MiB|5194.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6453.0MiB|6453.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.372GiB|32.372GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1627.0MiB|1627.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5904.0MiB|5904.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.031GiB|21.031GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.152GiB|48.152GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.312MiB|42.312MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.79GiB|17.79GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.972GiB|27.972GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.146GiB|43.146GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.747GiB|37.747GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |948.0MiB|948.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9255.0MiB|9255.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.639GiB|54.639GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1032.0MiB|1032.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1581.0MiB|1581.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6581.0MiB|6581.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5187.0MiB|5187.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5194.0MiB|5194.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6453.0MiB|6453.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.372GiB|32.372GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1627.0MiB|1627.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5904.0MiB|5904.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.031GiB|21.031GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.152GiB|48.152GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.312MiB|42.312MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.79GiB|17.79GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.972GiB|27.972GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.146GiB|43.146GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.747GiB|37.747GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |948.0MiB|948.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9255.0MiB|9255.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.639GiB|54.639GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1032.0MiB|1032.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1581.0MiB|1581.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6581.0MiB|6581.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5187.0MiB|5187.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5194.0MiB|5194.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6453.0MiB|6453.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.372GiB|32.372GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1627.0MiB|1627.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5904.0MiB|5904.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.031GiB|21.031GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.716s |63.257GiB|
|scrambled4299.smt2                                                                         |1204.922s |56.789GiB|
|scrambled12042.smt2                                                                        |1204.934s |54.639GiB|
|scrambled55680.smt2                                                                        |1204.557s |50.685GiB|
|scrambled4198.smt2                                                                         |1204.567s |49.22GiB|
|scrambled102166.smt2                                                                       |1204.190s |48.152GiB|
|scrambled68944.smt2                                                                        |1204.716s |46.324GiB|
|scrambled79760.smt2                                                                        |1204.824s |44.244GiB|
|scrambled108840.smt2                                                                       |1203.826s |43.146GiB|
|scrambled111627.smt2                                                                       |1204.441s |37.747GiB|
|scrambled43577.smt2                                                                        |1203.568s |34.26GiB|
|scrambled19335.smt2                                                                        |1203.408s |32.372GiB|
|scrambled75189.smt2                                                                        |1202.864s |31.696GiB|
|scrambled107826.smt2                                                                       |1202.401s |27.972GiB|
|scrambled27843.smt2                                                                        |1202.541s |21.031GiB|
|scrambled107115.smt2                                                                       |1201.758s |17.79GiB|
|scrambled40621.smt2                                                                        |1201.125s |10.832GiB|
|scrambled61922.smt2                                                                        |1201.164s |10.83GiB|
|scrambled119331.smt2                                                                       |1200.922s |9255.0MiB|
|scrambled7741.smt2                                                                         |1200.826s |6721.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.716s |63.257GiB|
|scrambled4299.smt2                                                                         |1204.922s |56.789GiB|
|scrambled12042.smt2                                                                        |1204.934s |54.639GiB|
|scrambled55680.smt2                                                                        |1204.557s |50.685GiB|
|scrambled4198.smt2                                                                         |1204.567s |49.22GiB|
|scrambled102166.smt2                                                                       |1204.190s |48.152GiB|
|scrambled68944.smt2                                                                        |1204.716s |46.324GiB|
|scrambled79760.smt2                                                                        |1204.824s |44.244GiB|
|scrambled108840.smt2                                                                       |1203.826s |43.146GiB|
|scrambled111627.smt2                                                                       |1204.441s |37.747GiB|
|scrambled43577.smt2                                                                        |1203.568s |34.26GiB|
|scrambled19335.smt2                                                                        |1203.408s |32.372GiB|
|scrambled75189.smt2                                                                        |1202.864s |31.696GiB|
|scrambled107826.smt2                                                                       |1202.401s |27.972GiB|
|scrambled27843.smt2                                                                        |1202.541s |21.031GiB|
|scrambled107115.smt2                                                                       |1201.758s |17.79GiB|
|scrambled40621.smt2                                                                        |1201.125s |10.832GiB|
|scrambled61922.smt2                                                                        |1201.164s |10.83GiB|
|scrambled119331.smt2                                                                       |1200.922s |9255.0MiB|
|scrambled7741.smt2                                                                         |1200.826s |6721.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.190s  |1204.190s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.758s  |1201.758s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.401s  |1202.401s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.826s  |1203.826s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1204.441s  |1204.441s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 117.685s  | 117.685s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.922s  |1200.922s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.934s  |1204.934s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 672.401s  | 672.401s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  95.489s  |  95.489s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.683s  |1200.683s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.520s  |1200.520s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.576s  |1200.576s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.735s  |1200.735s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.408s  |1203.408s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 114.381s  | 114.381s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 215.662s  | 215.662s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.541s  |1202.541s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 509.773s  | 509.773s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1201.125s  |1201.125s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1204.567s  |1204.567s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1204.922s  |1204.922s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1203.568s  |1203.568s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.733s  |1200.733s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.401s  |1200.401s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1204.557s  |1204.557s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.505s  |1200.505s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1201.164s  |1201.164s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1204.716s  |1204.716s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1201.244s  |1201.244s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1202.864s  |1202.864s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.826s  |1200.826s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1204.824s  |1204.824s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1206.716s  |1206.716s  |   0.000s  | 0.0%|
</details>
