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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bca74f00c9880bf41a61b573a3854e32fbc01120
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: ablate sharing non-worker units

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bca74f00c9880bf41a61b573a3854e32fbc01120
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: ablate sharing non-worker units

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.302s  |1204.302s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.827s  |1201.827s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1203.503s  |1203.503s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.868s  |1203.868s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.708s  |1203.708s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 206.647s  | 206.647s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.073s  |1201.073s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.883s  |1204.883s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 101.345s  | 101.345s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 140.733s  | 140.733s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1201.282s  |1201.282s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.597s  |1200.597s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.612s  |1200.612s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.798s  |1200.798s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.353s  |1203.353s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  71.287s  |  71.287s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 207.077s  | 207.077s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.165s  |1202.165s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.302s  |1204.302s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.827s  |1201.827s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1203.503s  |1203.503s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.868s  |1203.868s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.708s  |1203.708s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 206.647s  | 206.647s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.073s  |1201.073s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.883s  |1204.883s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 101.345s  | 101.345s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 140.733s  | 140.733s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1201.282s  |1201.282s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.597s  |1200.597s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.612s  |1200.612s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.798s  |1200.798s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.353s  |1203.353s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  71.287s  |  71.287s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 207.077s  | 207.077s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.165s  |1202.165s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.302s  |1204.302s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.827s  |1201.827s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1203.503s  |1203.503s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.868s  |1203.868s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.708s  |1203.708s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 206.647s  | 206.647s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.073s  |1201.073s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.883s  |1204.883s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 101.345s  | 101.345s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 140.733s  | 140.733s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1201.282s  |1201.282s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.597s  |1200.597s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.612s  |1200.612s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.798s  |1200.798s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.353s  |1203.353s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  71.287s  |  71.287s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 207.077s  | 207.077s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.165s  |1202.165s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.302s  |1204.302s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.827s  |1201.827s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1203.503s  |1203.503s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.868s  |1203.868s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.708s  |1203.708s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 206.647s  | 206.647s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.073s  |1201.073s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.883s  |1204.883s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 101.345s  | 101.345s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 140.733s  | 140.733s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1201.282s  |1201.282s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.597s  |1200.597s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.612s  |1200.612s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.798s  |1200.798s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.353s  |1203.353s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  71.287s  |  71.287s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 207.077s  | 207.077s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.165s  |1202.165s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled4299.smt2                                                                         |1206.092s |56.781GiB|
|scrambled94658.smt2                                                                        |1205.616s |63.395GiB|
|scrambled12042.smt2                                                                        |1204.883s |54.59GiB|
|scrambled55680.smt2                                                                        |1204.829s |50.58GiB|
|scrambled4198.smt2                                                                         |1204.571s |49.024GiB|
|scrambled102166.smt2                                                                       |1204.302s |48.159GiB|
|scrambled79760.smt2                                                                        |1204.285s |44.256GiB|
|scrambled68944.smt2                                                                        |1204.087s |47.167GiB|
|scrambled108840.smt2                                                                       |1203.868s |43.044GiB|
|scrambled111627.smt2                                                                       |1203.708s |37.776GiB|
|scrambled107826.smt2                                                                       |1203.503s |27.94GiB|
|scrambled19335.smt2                                                                        |1203.353s |32.444GiB|
|scrambled43577.smt2                                                                        |1203.275s |34.27GiB|
|scrambled75189.smt2                                                                        |1203.012s |31.686GiB|
|scrambled27843.smt2                                                                        |1202.165s |21.009GiB|
|scrambled107115.smt2                                                                       |1201.827s |17.78GiB|
|scrambled72668.smt2                                                                        |1201.398s |5333.0MiB|
|scrambled61922.smt2                                                                        |1201.287s |10.831GiB|
|scrambled128128.smt2                                                                       |1201.282s |6491.0MiB|
|scrambled40621.smt2                                                                        |1201.105s |11.117GiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled4299.smt2                                                                         |1206.092s |56.781GiB|
|scrambled94658.smt2                                                                        |1205.616s |63.395GiB|
|scrambled12042.smt2                                                                        |1204.883s |54.59GiB|
|scrambled55680.smt2                                                                        |1204.829s |50.58GiB|
|scrambled4198.smt2                                                                         |1204.571s |49.024GiB|
|scrambled102166.smt2                                                                       |1204.302s |48.159GiB|
|scrambled79760.smt2                                                                        |1204.285s |44.256GiB|
|scrambled68944.smt2                                                                        |1204.087s |47.167GiB|
|scrambled108840.smt2                                                                       |1203.868s |43.044GiB|
|scrambled111627.smt2                                                                       |1203.708s |37.776GiB|
|scrambled107826.smt2                                                                       |1203.503s |27.94GiB|
|scrambled19335.smt2                                                                        |1203.353s |32.444GiB|
|scrambled43577.smt2                                                                        |1203.275s |34.27GiB|
|scrambled75189.smt2                                                                        |1203.012s |31.686GiB|
|scrambled27843.smt2                                                                        |1202.165s |21.009GiB|
|scrambled107115.smt2                                                                       |1201.827s |17.78GiB|
|scrambled72668.smt2                                                                        |1201.398s |5333.0MiB|
|scrambled61922.smt2                                                                        |1201.287s |10.831GiB|
|scrambled128128.smt2                                                                       |1201.282s |6491.0MiB|
|scrambled40621.smt2                                                                        |1201.105s |11.117GiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.159GiB|48.159GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.808MiB|42.808MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.78GiB|17.78GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.94GiB|27.94GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.044GiB|43.044GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.776GiB|37.776GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |982.0MiB|982.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9553.0MiB|9553.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.59GiB|54.59GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1007.0MiB|1007.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1605.0MiB|1605.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6491.0MiB|6491.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5174.0MiB|5174.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5191.0MiB|5191.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6452.0MiB|6452.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |376.0MiB|376.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.444GiB|32.444GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1574.0MiB|1574.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5796.0MiB|5796.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.009GiB|21.009GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.159GiB|48.159GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.808MiB|42.808MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.78GiB|17.78GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.94GiB|27.94GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.044GiB|43.044GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.776GiB|37.776GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |982.0MiB|982.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9553.0MiB|9553.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.59GiB|54.59GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1007.0MiB|1007.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1605.0MiB|1605.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6491.0MiB|6491.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5174.0MiB|5174.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5191.0MiB|5191.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6452.0MiB|6452.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |376.0MiB|376.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.444GiB|32.444GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1574.0MiB|1574.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5796.0MiB|5796.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.009GiB|21.009GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.159GiB|48.159GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.808MiB|42.808MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.78GiB|17.78GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.94GiB|27.94GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.044GiB|43.044GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.776GiB|37.776GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |982.0MiB|982.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9553.0MiB|9553.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.59GiB|54.59GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1007.0MiB|1007.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1605.0MiB|1605.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6491.0MiB|6491.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5174.0MiB|5174.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5191.0MiB|5191.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6452.0MiB|6452.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |376.0MiB|376.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.444GiB|32.444GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1574.0MiB|1574.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5796.0MiB|5796.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.009GiB|21.009GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.159GiB|48.159GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.808MiB|42.808MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.78GiB|17.78GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.94GiB|27.94GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.044GiB|43.044GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.776GiB|37.776GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |982.0MiB|982.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9553.0MiB|9553.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.59GiB|54.59GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1007.0MiB|1007.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1605.0MiB|1605.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6491.0MiB|6491.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5174.0MiB|5174.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5191.0MiB|5191.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6452.0MiB|6452.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |376.0MiB|376.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.444GiB|32.444GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1574.0MiB|1574.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5796.0MiB|5796.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.009GiB|21.009GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.616s |63.395GiB|
|scrambled4299.smt2                                                                         |1206.092s |56.781GiB|
|scrambled12042.smt2                                                                        |1204.883s |54.59GiB|
|scrambled55680.smt2                                                                        |1204.829s |50.58GiB|
|scrambled4198.smt2                                                                         |1204.571s |49.024GiB|
|scrambled102166.smt2                                                                       |1204.302s |48.159GiB|
|scrambled68944.smt2                                                                        |1204.087s |47.167GiB|
|scrambled79760.smt2                                                                        |1204.285s |44.256GiB|
|scrambled108840.smt2                                                                       |1203.868s |43.044GiB|
|scrambled111627.smt2                                                                       |1203.708s |37.776GiB|
|scrambled43577.smt2                                                                        |1203.275s |34.27GiB|
|scrambled19335.smt2                                                                        |1203.353s |32.444GiB|
|scrambled75189.smt2                                                                        |1203.012s |31.686GiB|
|scrambled107826.smt2                                                                       |1203.503s |27.94GiB|
|scrambled27843.smt2                                                                        |1202.165s |21.009GiB|
|scrambled107115.smt2                                                                       |1201.827s |17.78GiB|
|scrambled40621.smt2                                                                        |1201.105s |11.117GiB|
|scrambled61922.smt2                                                                        |1201.287s |10.831GiB|
|scrambled119331.smt2                                                                       |1201.073s |9553.0MiB|
|scrambled7741.smt2                                                                         |1200.740s |6836.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.616s |63.395GiB|
|scrambled4299.smt2                                                                         |1206.092s |56.781GiB|
|scrambled12042.smt2                                                                        |1204.883s |54.59GiB|
|scrambled55680.smt2                                                                        |1204.829s |50.58GiB|
|scrambled4198.smt2                                                                         |1204.571s |49.024GiB|
|scrambled102166.smt2                                                                       |1204.302s |48.159GiB|
|scrambled68944.smt2                                                                        |1204.087s |47.167GiB|
|scrambled79760.smt2                                                                        |1204.285s |44.256GiB|
|scrambled108840.smt2                                                                       |1203.868s |43.044GiB|
|scrambled111627.smt2                                                                       |1203.708s |37.776GiB|
|scrambled43577.smt2                                                                        |1203.275s |34.27GiB|
|scrambled19335.smt2                                                                        |1203.353s |32.444GiB|
|scrambled75189.smt2                                                                        |1203.012s |31.686GiB|
|scrambled107826.smt2                                                                       |1203.503s |27.94GiB|
|scrambled27843.smt2                                                                        |1202.165s |21.009GiB|
|scrambled107115.smt2                                                                       |1201.827s |17.78GiB|
|scrambled40621.smt2                                                                        |1201.105s |11.117GiB|
|scrambled61922.smt2                                                                        |1201.287s |10.831GiB|
|scrambled119331.smt2                                                                       |1201.073s |9553.0MiB|
|scrambled7741.smt2                                                                         |1200.740s |6836.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.302s  |1204.302s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.827s  |1201.827s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1203.503s  |1203.503s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.868s  |1203.868s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.708s  |1203.708s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 206.647s  | 206.647s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.073s  |1201.073s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.883s  |1204.883s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 101.345s  | 101.345s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 140.733s  | 140.733s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1201.282s  |1201.282s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.597s  |1200.597s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.612s  |1200.612s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.798s  |1200.798s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.353s  |1203.353s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  71.287s  |  71.287s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 207.077s  | 207.077s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.165s  |1202.165s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 610.658s  | 610.658s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1201.105s  |1201.105s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1204.571s  |1204.571s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1206.092s  |1206.092s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1203.275s  |1203.275s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.746s  |1200.746s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.509s  |1200.509s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1204.829s  |1204.829s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.529s  |1200.529s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1201.287s  |1201.287s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1204.087s  |1204.087s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1201.398s  |1201.398s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1203.012s  |1203.012s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.740s  |1200.740s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1204.285s  |1204.285s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1205.616s  |1205.616s  |   0.000s  | 0.0%|
</details>
