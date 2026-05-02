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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: dd30b9eaf3624ea8d87e9e84ece5b50b171e5eda
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore incomplete-theory give-up paths

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: dd30b9eaf3624ea8d87e9e84ece5b50b171e5eda
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore incomplete-theory give-up paths

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.228s  |1204.228s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.800s  |1201.800s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.469s  |1202.469s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.902s  |1203.902s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.410s  |1203.410s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 493.652s  | 493.652s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.884s  |1200.884s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.858s  |1204.858s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  39.171s  |  39.171s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 247.837s  | 247.837s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 336.670s  | 336.670s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.496s  |1200.496s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.546s  |1200.546s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.598s  |1200.598s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.188s  |1203.188s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 454.953s  | 454.953s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  93.847s  |  93.847s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.274s  |1202.274s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.228s  |1204.228s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.800s  |1201.800s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.469s  |1202.469s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.902s  |1203.902s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.410s  |1203.410s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 493.652s  | 493.652s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.884s  |1200.884s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.858s  |1204.858s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  39.171s  |  39.171s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 247.837s  | 247.837s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 336.670s  | 336.670s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.496s  |1200.496s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.546s  |1200.546s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.598s  |1200.598s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.188s  |1203.188s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 454.953s  | 454.953s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  93.847s  |  93.847s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.274s  |1202.274s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.228s  |1204.228s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.800s  |1201.800s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.469s  |1202.469s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.902s  |1203.902s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.410s  |1203.410s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 493.652s  | 493.652s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.884s  |1200.884s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.858s  |1204.858s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  39.171s  |  39.171s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 247.837s  | 247.837s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 336.670s  | 336.670s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.496s  |1200.496s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.546s  |1200.546s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.598s  |1200.598s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.188s  |1203.188s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 454.953s  | 454.953s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  93.847s  |  93.847s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.274s  |1202.274s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.228s  |1204.228s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.800s  |1201.800s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.469s  |1202.469s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.902s  |1203.902s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.410s  |1203.410s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 493.652s  | 493.652s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.884s  |1200.884s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.858s  |1204.858s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  39.171s  |  39.171s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 247.837s  | 247.837s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 336.670s  | 336.670s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.496s  |1200.496s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.546s  |1200.546s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.598s  |1200.598s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.188s  |1203.188s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 454.953s  | 454.953s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  93.847s  |  93.847s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.274s  |1202.274s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1209.468s |62.561GiB|
|scrambled4299.smt2                                                                         |1205.241s |56.456GiB|
|scrambled12042.smt2                                                                        |1204.858s |53.967GiB|
|scrambled4198.smt2                                                                         |1204.539s |48.815GiB|
|scrambled55680.smt2                                                                        |1204.534s |50.221GiB|
|scrambled68944.smt2                                                                        |1204.231s |46.641GiB|
|scrambled102166.smt2                                                                       |1204.228s |47.8GiB|
|scrambled79760.smt2                                                                        |1203.941s |43.986GiB|
|scrambled108840.smt2                                                                       |1203.902s |42.748GiB|
|scrambled111627.smt2                                                                       |1203.410s |37.48GiB|
|scrambled19335.smt2                                                                        |1203.188s |32.115GiB|
|scrambled43577.smt2                                                                        |1203.083s |33.979GiB|
|scrambled75189.smt2                                                                        |1202.980s |31.467GiB|
|scrambled107826.smt2                                                                       |1202.469s |27.661GiB|
|scrambled27843.smt2                                                                        |1202.274s |20.851GiB|
|scrambled107115.smt2                                                                       |1201.800s |17.671GiB|
|scrambled61922.smt2                                                                        |1201.074s |10.758GiB|
|scrambled72668.smt2                                                                        |1201.055s |5146.0MiB|
|scrambled119331.smt2                                                                       |1200.884s |6963.0MiB|
|scrambled7741.smt2                                                                         |1200.818s |5918.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1209.468s |62.561GiB|
|scrambled4299.smt2                                                                         |1205.241s |56.456GiB|
|scrambled12042.smt2                                                                        |1204.858s |53.967GiB|
|scrambled4198.smt2                                                                         |1204.539s |48.815GiB|
|scrambled55680.smt2                                                                        |1204.534s |50.221GiB|
|scrambled68944.smt2                                                                        |1204.231s |46.641GiB|
|scrambled102166.smt2                                                                       |1204.228s |47.8GiB|
|scrambled79760.smt2                                                                        |1203.941s |43.986GiB|
|scrambled108840.smt2                                                                       |1203.902s |42.748GiB|
|scrambled111627.smt2                                                                       |1203.410s |37.48GiB|
|scrambled19335.smt2                                                                        |1203.188s |32.115GiB|
|scrambled43577.smt2                                                                        |1203.083s |33.979GiB|
|scrambled75189.smt2                                                                        |1202.980s |31.467GiB|
|scrambled107826.smt2                                                                       |1202.469s |27.661GiB|
|scrambled27843.smt2                                                                        |1202.274s |20.851GiB|
|scrambled107115.smt2                                                                       |1201.800s |17.671GiB|
|scrambled61922.smt2                                                                        |1201.074s |10.758GiB|
|scrambled72668.smt2                                                                        |1201.055s |5146.0MiB|
|scrambled119331.smt2                                                                       |1200.884s |6963.0MiB|
|scrambled7741.smt2                                                                         |1200.818s |5918.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.8GiB|47.8GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.564MiB|42.564MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.671GiB|17.671GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.661GiB|27.661GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.748GiB|42.748GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.48GiB|37.48GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |976.0MiB|976.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |6963.0MiB|6963.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |53.967GiB|53.967GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |935.0MiB|935.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1555.0MiB|1555.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |4856.0MiB|4856.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4639.0MiB|4639.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4657.0MiB|4657.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5078.0MiB|5078.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |371.0MiB|371.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.115GiB|32.115GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1654.0MiB|1654.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3630.0MiB|3630.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.851GiB|20.851GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.8GiB|47.8GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.564MiB|42.564MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.671GiB|17.671GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.661GiB|27.661GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.748GiB|42.748GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.48GiB|37.48GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |976.0MiB|976.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |6963.0MiB|6963.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |53.967GiB|53.967GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |935.0MiB|935.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1555.0MiB|1555.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |4856.0MiB|4856.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4639.0MiB|4639.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4657.0MiB|4657.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5078.0MiB|5078.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |371.0MiB|371.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.115GiB|32.115GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1654.0MiB|1654.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3630.0MiB|3630.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.851GiB|20.851GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.8GiB|47.8GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.564MiB|42.564MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.671GiB|17.671GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.661GiB|27.661GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.748GiB|42.748GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.48GiB|37.48GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |976.0MiB|976.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |6963.0MiB|6963.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |53.967GiB|53.967GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |935.0MiB|935.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1555.0MiB|1555.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |4856.0MiB|4856.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4639.0MiB|4639.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4657.0MiB|4657.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5078.0MiB|5078.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |371.0MiB|371.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.115GiB|32.115GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1654.0MiB|1654.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3630.0MiB|3630.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.851GiB|20.851GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.8GiB|47.8GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.564MiB|42.564MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.671GiB|17.671GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.661GiB|27.661GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.748GiB|42.748GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.48GiB|37.48GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |976.0MiB|976.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |6963.0MiB|6963.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |53.967GiB|53.967GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |935.0MiB|935.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1555.0MiB|1555.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |4856.0MiB|4856.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4639.0MiB|4639.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4657.0MiB|4657.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5078.0MiB|5078.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |371.0MiB|371.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.115GiB|32.115GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1654.0MiB|1654.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3630.0MiB|3630.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.851GiB|20.851GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1209.468s |62.561GiB|
|scrambled4299.smt2                                                                         |1205.241s |56.456GiB|
|scrambled12042.smt2                                                                        |1204.858s |53.967GiB|
|scrambled55680.smt2                                                                        |1204.534s |50.221GiB|
|scrambled4198.smt2                                                                         |1204.539s |48.815GiB|
|scrambled102166.smt2                                                                       |1204.228s |47.8GiB|
|scrambled68944.smt2                                                                        |1204.231s |46.641GiB|
|scrambled79760.smt2                                                                        |1203.941s |43.986GiB|
|scrambled108840.smt2                                                                       |1203.902s |42.748GiB|
|scrambled111627.smt2                                                                       |1203.410s |37.48GiB|
|scrambled43577.smt2                                                                        |1203.083s |33.979GiB|
|scrambled19335.smt2                                                                        |1203.188s |32.115GiB|
|scrambled75189.smt2                                                                        |1202.980s |31.467GiB|
|scrambled107826.smt2                                                                       |1202.469s |27.661GiB|
|scrambled27843.smt2                                                                        |1202.274s |20.851GiB|
|scrambled107115.smt2                                                                       |1201.800s |17.671GiB|
|scrambled61922.smt2                                                                        |1201.074s |10.758GiB|
|scrambled119331.smt2                                                                       |1200.884s |6963.0MiB|
|scrambled40621.smt2                                                                        |1200.804s |6337.0MiB|
|scrambled7741.smt2                                                                         |1200.818s |5918.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1209.468s |62.561GiB|
|scrambled4299.smt2                                                                         |1205.241s |56.456GiB|
|scrambled12042.smt2                                                                        |1204.858s |53.967GiB|
|scrambled55680.smt2                                                                        |1204.534s |50.221GiB|
|scrambled4198.smt2                                                                         |1204.539s |48.815GiB|
|scrambled102166.smt2                                                                       |1204.228s |47.8GiB|
|scrambled68944.smt2                                                                        |1204.231s |46.641GiB|
|scrambled79760.smt2                                                                        |1203.941s |43.986GiB|
|scrambled108840.smt2                                                                       |1203.902s |42.748GiB|
|scrambled111627.smt2                                                                       |1203.410s |37.48GiB|
|scrambled43577.smt2                                                                        |1203.083s |33.979GiB|
|scrambled19335.smt2                                                                        |1203.188s |32.115GiB|
|scrambled75189.smt2                                                                        |1202.980s |31.467GiB|
|scrambled107826.smt2                                                                       |1202.469s |27.661GiB|
|scrambled27843.smt2                                                                        |1202.274s |20.851GiB|
|scrambled107115.smt2                                                                       |1201.800s |17.671GiB|
|scrambled61922.smt2                                                                        |1201.074s |10.758GiB|
|scrambled119331.smt2                                                                       |1200.884s |6963.0MiB|
|scrambled40621.smt2                                                                        |1200.804s |6337.0MiB|
|scrambled7741.smt2                                                                         |1200.818s |5918.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.228s  |1204.228s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.800s  |1201.800s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.469s  |1202.469s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.902s  |1203.902s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.410s  |1203.410s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 493.652s  | 493.652s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.884s  |1200.884s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.858s  |1204.858s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  39.171s  |  39.171s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 247.837s  | 247.837s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 336.670s  | 336.670s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.496s  |1200.496s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.546s  |1200.546s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.598s  |1200.598s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.188s  |1203.188s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 454.953s  | 454.953s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  93.847s  |  93.847s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.274s  |1202.274s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.325s  |1200.325s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1200.804s  |1200.804s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1204.539s  |1204.539s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1205.241s  |1205.241s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1203.083s  |1203.083s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         | 360.560s  | 360.560s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.392s  |1200.392s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1204.534s  |1204.534s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1201.074s  |1201.074s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1204.231s  |1204.231s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1201.055s  |1201.055s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1202.980s  |1202.980s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.818s  |1200.818s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1203.941s  |1203.941s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1209.468s  |1209.468s  |   0.000s  | 0.0%|
</details>
