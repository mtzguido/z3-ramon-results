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
Z3 commit: 4e0f9c891a995745172a1fc312ffb9b4544561e3
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: ablate continuous checking for batch bb mode

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 4e0f9c891a995745172a1fc312ffb9b4544561e3
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: ablate continuous checking for batch bb mode

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.156s  |1204.156s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.693s  |1201.693s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.515s  |1202.515s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.653s  |1203.653s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.495s  |1203.495s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 115.989s  | 115.989s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.356s  |1201.356s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.718s  |1204.718s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 671.984s  | 671.984s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 178.686s  | 178.686s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.721s  |1200.721s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        | 978.712s  | 978.712s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.518s  |1200.518s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.845s  |1200.845s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.062s  |1203.062s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 100.430s  | 100.430s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 204.429s  | 204.429s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.838s  |1202.838s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.156s  |1204.156s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.693s  |1201.693s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.515s  |1202.515s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.653s  |1203.653s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.495s  |1203.495s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 115.989s  | 115.989s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.356s  |1201.356s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.718s  |1204.718s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 671.984s  | 671.984s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 178.686s  | 178.686s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.721s  |1200.721s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        | 978.712s  | 978.712s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.518s  |1200.518s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.845s  |1200.845s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.062s  |1203.062s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 100.430s  | 100.430s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 204.429s  | 204.429s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.838s  |1202.838s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.156s  |1204.156s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.693s  |1201.693s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.515s  |1202.515s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.653s  |1203.653s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.495s  |1203.495s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 115.989s  | 115.989s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.356s  |1201.356s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.718s  |1204.718s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 671.984s  | 671.984s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 178.686s  | 178.686s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.721s  |1200.721s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        | 978.712s  | 978.712s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.518s  |1200.518s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.845s  |1200.845s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.062s  |1203.062s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 100.430s  | 100.430s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 204.429s  | 204.429s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.838s  |1202.838s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.156s  |1204.156s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.693s  |1201.693s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.515s  |1202.515s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.653s  |1203.653s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.495s  |1203.495s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 115.989s  | 115.989s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.356s  |1201.356s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.718s  |1204.718s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 671.984s  | 671.984s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 178.686s  | 178.686s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.721s  |1200.721s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        | 978.712s  | 978.712s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.518s  |1200.518s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.845s  |1200.845s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.062s  |1203.062s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 100.430s  | 100.430s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 204.429s  | 204.429s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.838s  |1202.838s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.200s |63.521GiB|
|scrambled4198.smt2                                                                         |1205.277s |49.234GiB|
|scrambled4299.smt2                                                                         |1204.822s |56.792GiB|
|scrambled12042.smt2                                                                        |1204.718s |54.76GiB|
|scrambled55680.smt2                                                                        |1204.677s |50.643GiB|
|scrambled102166.smt2                                                                       |1204.156s |48.147GiB|
|scrambled68944.smt2                                                                        |1204.111s |47.103GiB|
|scrambled79760.smt2                                                                        |1203.796s |44.285GiB|
|scrambled108840.smt2                                                                       |1203.653s |43.137GiB|
|scrambled111627.smt2                                                                       |1203.495s |37.772GiB|
|scrambled19335.smt2                                                                        |1203.062s |32.339GiB|
|scrambled43577.smt2                                                                        |1203.048s |34.33GiB|
|scrambled27843.smt2                                                                        |1202.838s |21.043GiB|
|scrambled75189.smt2                                                                        |1202.713s |31.7GiB|
|scrambled107826.smt2                                                                       |1202.515s |27.977GiB|
|scrambled107115.smt2                                                                       |1201.693s |17.782GiB|
|scrambled61922.smt2                                                                        |1201.640s |10.83GiB|
|scrambled119331.smt2                                                                       |1201.356s |9415.0MiB|
|scrambled40621.smt2                                                                        |1201.041s |11.217GiB|
|scrambled131241.smt2                                                                       |1200.845s |6379.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.200s |63.521GiB|
|scrambled4198.smt2                                                                         |1205.277s |49.234GiB|
|scrambled4299.smt2                                                                         |1204.822s |56.792GiB|
|scrambled12042.smt2                                                                        |1204.718s |54.76GiB|
|scrambled55680.smt2                                                                        |1204.677s |50.643GiB|
|scrambled102166.smt2                                                                       |1204.156s |48.147GiB|
|scrambled68944.smt2                                                                        |1204.111s |47.103GiB|
|scrambled79760.smt2                                                                        |1203.796s |44.285GiB|
|scrambled108840.smt2                                                                       |1203.653s |43.137GiB|
|scrambled111627.smt2                                                                       |1203.495s |37.772GiB|
|scrambled19335.smt2                                                                        |1203.062s |32.339GiB|
|scrambled43577.smt2                                                                        |1203.048s |34.33GiB|
|scrambled27843.smt2                                                                        |1202.838s |21.043GiB|
|scrambled75189.smt2                                                                        |1202.713s |31.7GiB|
|scrambled107826.smt2                                                                       |1202.515s |27.977GiB|
|scrambled107115.smt2                                                                       |1201.693s |17.782GiB|
|scrambled61922.smt2                                                                        |1201.640s |10.83GiB|
|scrambled119331.smt2                                                                       |1201.356s |9415.0MiB|
|scrambled40621.smt2                                                                        |1201.041s |11.217GiB|
|scrambled131241.smt2                                                                       |1200.845s |6379.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.147GiB|48.147GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.348MiB|42.348MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.782GiB|17.782GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.977GiB|27.977GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.137GiB|43.137GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.772GiB|37.772GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |947.0MiB|947.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9415.0MiB|9415.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.76GiB|54.76GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1030.0MiB|1030.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1625.0MiB|1625.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6517.0MiB|6517.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5143.0MiB|5143.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5170.0MiB|5170.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6379.0MiB|6379.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |377.0MiB|377.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.339GiB|32.339GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1610.0MiB|1610.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5975.0MiB|5975.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.043GiB|21.043GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.147GiB|48.147GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.348MiB|42.348MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.782GiB|17.782GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.977GiB|27.977GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.137GiB|43.137GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.772GiB|37.772GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |947.0MiB|947.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9415.0MiB|9415.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.76GiB|54.76GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1030.0MiB|1030.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1625.0MiB|1625.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6517.0MiB|6517.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5143.0MiB|5143.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5170.0MiB|5170.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6379.0MiB|6379.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |377.0MiB|377.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.339GiB|32.339GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1610.0MiB|1610.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5975.0MiB|5975.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.043GiB|21.043GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.147GiB|48.147GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.348MiB|42.348MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.782GiB|17.782GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.977GiB|27.977GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.137GiB|43.137GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.772GiB|37.772GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |947.0MiB|947.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9415.0MiB|9415.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.76GiB|54.76GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1030.0MiB|1030.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1625.0MiB|1625.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6517.0MiB|6517.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5143.0MiB|5143.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5170.0MiB|5170.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6379.0MiB|6379.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |377.0MiB|377.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.339GiB|32.339GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1610.0MiB|1610.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5975.0MiB|5975.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.043GiB|21.043GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.147GiB|48.147GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.348MiB|42.348MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.782GiB|17.782GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.977GiB|27.977GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.137GiB|43.137GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.772GiB|37.772GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |947.0MiB|947.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9415.0MiB|9415.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.76GiB|54.76GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1030.0MiB|1030.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1625.0MiB|1625.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6517.0MiB|6517.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5143.0MiB|5143.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5170.0MiB|5170.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6379.0MiB|6379.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |377.0MiB|377.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.339GiB|32.339GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1610.0MiB|1610.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5975.0MiB|5975.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.043GiB|21.043GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.200s |63.521GiB|
|scrambled4299.smt2                                                                         |1204.822s |56.792GiB|
|scrambled12042.smt2                                                                        |1204.718s |54.76GiB|
|scrambled55680.smt2                                                                        |1204.677s |50.643GiB|
|scrambled4198.smt2                                                                         |1205.277s |49.234GiB|
|scrambled102166.smt2                                                                       |1204.156s |48.147GiB|
|scrambled68944.smt2                                                                        |1204.111s |47.103GiB|
|scrambled79760.smt2                                                                        |1203.796s |44.285GiB|
|scrambled108840.smt2                                                                       |1203.653s |43.137GiB|
|scrambled111627.smt2                                                                       |1203.495s |37.772GiB|
|scrambled43577.smt2                                                                        |1203.048s |34.33GiB|
|scrambled19335.smt2                                                                        |1203.062s |32.339GiB|
|scrambled75189.smt2                                                                        |1202.713s |31.7GiB|
|scrambled107826.smt2                                                                       |1202.515s |27.977GiB|
|scrambled27843.smt2                                                                        |1202.838s |21.043GiB|
|scrambled107115.smt2                                                                       |1201.693s |17.782GiB|
|scrambled40621.smt2                                                                        |1201.041s |11.217GiB|
|scrambled61922.smt2                                                                        |1201.640s |10.83GiB|
|scrambled119331.smt2                                                                       |1201.356s |9415.0MiB|
|scrambled7741.smt2                                                                         |1200.749s |6735.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.200s |63.521GiB|
|scrambled4299.smt2                                                                         |1204.822s |56.792GiB|
|scrambled12042.smt2                                                                        |1204.718s |54.76GiB|
|scrambled55680.smt2                                                                        |1204.677s |50.643GiB|
|scrambled4198.smt2                                                                         |1205.277s |49.234GiB|
|scrambled102166.smt2                                                                       |1204.156s |48.147GiB|
|scrambled68944.smt2                                                                        |1204.111s |47.103GiB|
|scrambled79760.smt2                                                                        |1203.796s |44.285GiB|
|scrambled108840.smt2                                                                       |1203.653s |43.137GiB|
|scrambled111627.smt2                                                                       |1203.495s |37.772GiB|
|scrambled43577.smt2                                                                        |1203.048s |34.33GiB|
|scrambled19335.smt2                                                                        |1203.062s |32.339GiB|
|scrambled75189.smt2                                                                        |1202.713s |31.7GiB|
|scrambled107826.smt2                                                                       |1202.515s |27.977GiB|
|scrambled27843.smt2                                                                        |1202.838s |21.043GiB|
|scrambled107115.smt2                                                                       |1201.693s |17.782GiB|
|scrambled40621.smt2                                                                        |1201.041s |11.217GiB|
|scrambled61922.smt2                                                                        |1201.640s |10.83GiB|
|scrambled119331.smt2                                                                       |1201.356s |9415.0MiB|
|scrambled7741.smt2                                                                         |1200.749s |6735.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.156s  |1204.156s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.693s  |1201.693s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.515s  |1202.515s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.653s  |1203.653s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.495s  |1203.495s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 115.989s  | 115.989s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.356s  |1201.356s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.718s  |1204.718s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 671.984s  | 671.984s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 178.686s  | 178.686s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.721s  |1200.721s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        | 978.712s  | 978.712s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.518s  |1200.518s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.845s  |1200.845s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.062s  |1203.062s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 100.430s  | 100.430s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 204.429s  | 204.429s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.838s  |1202.838s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.285s  |1200.285s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1201.041s  |1201.041s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1205.277s  |1205.277s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1204.822s  |1204.822s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1203.048s  |1203.048s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.842s  |1200.842s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.439s  |1200.439s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1204.677s  |1204.677s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.516s  |1200.516s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1201.640s  |1201.640s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1204.111s  |1204.111s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         | 337.892s  | 337.892s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1202.713s  |1202.713s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.749s  |1200.749s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1203.796s  |1203.796s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1206.200s  |1206.200s  |   0.000s  | 0.0%|
</details>
