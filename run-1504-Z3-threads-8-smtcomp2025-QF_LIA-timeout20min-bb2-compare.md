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
Z3 commit: 4e9e3413ec6d3ed78d31f91f5c563e3531e9b393
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.failed_literal_backbones=false smt_parallel.num_global_bb_chunking_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore old changes

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 4e9e3413ec6d3ed78d31f91f5c563e3531e9b393
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.failed_literal_backbones=false smt_parallel.num_global_bb_chunking_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore old changes

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.145s  |1205.145s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.796s  |1201.796s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.503s  |1202.503s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.985s  |1203.985s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.780s  |1203.780s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 190.367s  | 190.367s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.107s  |1201.107s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.849s  |1204.849s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 266.425s  | 266.425s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 145.875s  | 145.875s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.643s  |1200.643s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.556s  |1200.556s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  82.313s  |  82.313s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.725s  |1200.725s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.308s  |1203.308s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  74.747s  |  74.747s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 212.073s  | 212.073s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.755s  |1202.755s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.145s  |1205.145s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.796s  |1201.796s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.503s  |1202.503s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.985s  |1203.985s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.780s  |1203.780s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 190.367s  | 190.367s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.107s  |1201.107s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.849s  |1204.849s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 266.425s  | 266.425s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 145.875s  | 145.875s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.643s  |1200.643s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.556s  |1200.556s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  82.313s  |  82.313s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.725s  |1200.725s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.308s  |1203.308s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  74.747s  |  74.747s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 212.073s  | 212.073s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.755s  |1202.755s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.145s  |1205.145s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.796s  |1201.796s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.503s  |1202.503s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.985s  |1203.985s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.780s  |1203.780s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 190.367s  | 190.367s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.107s  |1201.107s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.849s  |1204.849s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 266.425s  | 266.425s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 145.875s  | 145.875s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.643s  |1200.643s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.556s  |1200.556s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  82.313s  |  82.313s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.725s  |1200.725s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.308s  |1203.308s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  74.747s  |  74.747s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 212.073s  | 212.073s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.755s  |1202.755s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.145s  |1205.145s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.796s  |1201.796s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.503s  |1202.503s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.985s  |1203.985s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.780s  |1203.780s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 190.367s  | 190.367s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.107s  |1201.107s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.849s  |1204.849s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 266.425s  | 266.425s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 145.875s  | 145.875s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.643s  |1200.643s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.556s  |1200.556s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  82.313s  |  82.313s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.725s  |1200.725s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.308s  |1203.308s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  74.747s  |  74.747s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 212.073s  | 212.073s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.755s  |1202.755s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1207.335s |63.342GiB|
|scrambled4299.smt2                                                                         |1205.796s |56.866GiB|
|scrambled55680.smt2                                                                        |1205.336s |50.73GiB|
|scrambled102166.smt2                                                                       |1205.145s |48.149GiB|
|scrambled12042.smt2                                                                        |1204.849s |54.78GiB|
|scrambled4198.smt2                                                                         |1204.677s |49.351GiB|
|scrambled68944.smt2                                                                        |1204.318s |47.643GiB|
|scrambled79760.smt2                                                                        |1204.069s |44.268GiB|
|scrambled108840.smt2                                                                       |1203.985s |43.086GiB|
|scrambled111627.smt2                                                                       |1203.780s |37.783GiB|
|scrambled75189.smt2                                                                        |1203.309s |31.686GiB|
|scrambled19335.smt2                                                                        |1203.308s |32.431GiB|
|scrambled43577.smt2                                                                        |1203.230s |34.29GiB|
|scrambled27843.smt2                                                                        |1202.755s |21.066GiB|
|scrambled107826.smt2                                                                       |1202.503s |28.003GiB|
|scrambled61922.smt2                                                                        |1202.028s |10.841GiB|
|scrambled107115.smt2                                                                       |1201.796s |17.782GiB|
|scrambled40621.smt2                                                                        |1201.169s |11.532GiB|
|scrambled119331.smt2                                                                       |1201.107s |9496.0MiB|
|scrambled44911.smt2                                                                        |1200.943s |5019.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1207.335s |63.342GiB|
|scrambled4299.smt2                                                                         |1205.796s |56.866GiB|
|scrambled55680.smt2                                                                        |1205.336s |50.73GiB|
|scrambled102166.smt2                                                                       |1205.145s |48.149GiB|
|scrambled12042.smt2                                                                        |1204.849s |54.78GiB|
|scrambled4198.smt2                                                                         |1204.677s |49.351GiB|
|scrambled68944.smt2                                                                        |1204.318s |47.643GiB|
|scrambled79760.smt2                                                                        |1204.069s |44.268GiB|
|scrambled108840.smt2                                                                       |1203.985s |43.086GiB|
|scrambled111627.smt2                                                                       |1203.780s |37.783GiB|
|scrambled75189.smt2                                                                        |1203.309s |31.686GiB|
|scrambled19335.smt2                                                                        |1203.308s |32.431GiB|
|scrambled43577.smt2                                                                        |1203.230s |34.29GiB|
|scrambled27843.smt2                                                                        |1202.755s |21.066GiB|
|scrambled107826.smt2                                                                       |1202.503s |28.003GiB|
|scrambled61922.smt2                                                                        |1202.028s |10.841GiB|
|scrambled107115.smt2                                                                       |1201.796s |17.782GiB|
|scrambled40621.smt2                                                                        |1201.169s |11.532GiB|
|scrambled119331.smt2                                                                       |1201.107s |9496.0MiB|
|scrambled44911.smt2                                                                        |1200.943s |5019.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.149GiB|48.149GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.312MiB|42.312MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.782GiB|17.782GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |28.003GiB|28.003GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.086GiB|43.086GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.783GiB|37.783GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |973.0MiB|973.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9496.0MiB|9496.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.78GiB|54.78GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1019.0MiB|1019.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1608.0MiB|1608.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6520.0MiB|6520.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5190.0MiB|5190.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3896.0MiB|3896.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6389.0MiB|6389.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |377.0MiB|377.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.431GiB|32.431GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1568.0MiB|1568.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5959.0MiB|5959.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.066GiB|21.066GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.149GiB|48.149GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.312MiB|42.312MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.782GiB|17.782GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |28.003GiB|28.003GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.086GiB|43.086GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.783GiB|37.783GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |973.0MiB|973.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9496.0MiB|9496.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.78GiB|54.78GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1019.0MiB|1019.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1608.0MiB|1608.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6520.0MiB|6520.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5190.0MiB|5190.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3896.0MiB|3896.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6389.0MiB|6389.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |377.0MiB|377.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.431GiB|32.431GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1568.0MiB|1568.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5959.0MiB|5959.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.066GiB|21.066GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.149GiB|48.149GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.312MiB|42.312MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.782GiB|17.782GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |28.003GiB|28.003GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.086GiB|43.086GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.783GiB|37.783GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |973.0MiB|973.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9496.0MiB|9496.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.78GiB|54.78GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1019.0MiB|1019.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1608.0MiB|1608.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6520.0MiB|6520.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5190.0MiB|5190.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3896.0MiB|3896.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6389.0MiB|6389.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |377.0MiB|377.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.431GiB|32.431GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1568.0MiB|1568.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5959.0MiB|5959.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.066GiB|21.066GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.149GiB|48.149GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.312MiB|42.312MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.782GiB|17.782GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |28.003GiB|28.003GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.086GiB|43.086GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.783GiB|37.783GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |973.0MiB|973.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9496.0MiB|9496.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.78GiB|54.78GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1019.0MiB|1019.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1608.0MiB|1608.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6520.0MiB|6520.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5190.0MiB|5190.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3896.0MiB|3896.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6389.0MiB|6389.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |377.0MiB|377.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.431GiB|32.431GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1568.0MiB|1568.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5959.0MiB|5959.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.066GiB|21.066GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1207.335s |63.342GiB|
|scrambled4299.smt2                                                                         |1205.796s |56.866GiB|
|scrambled12042.smt2                                                                        |1204.849s |54.78GiB|
|scrambled55680.smt2                                                                        |1205.336s |50.73GiB|
|scrambled4198.smt2                                                                         |1204.677s |49.351GiB|
|scrambled102166.smt2                                                                       |1205.145s |48.149GiB|
|scrambled68944.smt2                                                                        |1204.318s |47.643GiB|
|scrambled79760.smt2                                                                        |1204.069s |44.268GiB|
|scrambled108840.smt2                                                                       |1203.985s |43.086GiB|
|scrambled111627.smt2                                                                       |1203.780s |37.783GiB|
|scrambled43577.smt2                                                                        |1203.230s |34.29GiB|
|scrambled19335.smt2                                                                        |1203.308s |32.431GiB|
|scrambled75189.smt2                                                                        |1203.309s |31.686GiB|
|scrambled107826.smt2                                                                       |1202.503s |28.003GiB|
|scrambled27843.smt2                                                                        |1202.755s |21.066GiB|
|scrambled107115.smt2                                                                       |1201.796s |17.782GiB|
|scrambled40621.smt2                                                                        |1201.169s |11.532GiB|
|scrambled61922.smt2                                                                        |1202.028s |10.841GiB|
|scrambled119331.smt2                                                                       |1201.107s |9496.0MiB|
|scrambled7741.smt2                                                                         |1200.759s |6853.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1207.335s |63.342GiB|
|scrambled4299.smt2                                                                         |1205.796s |56.866GiB|
|scrambled12042.smt2                                                                        |1204.849s |54.78GiB|
|scrambled55680.smt2                                                                        |1205.336s |50.73GiB|
|scrambled4198.smt2                                                                         |1204.677s |49.351GiB|
|scrambled102166.smt2                                                                       |1205.145s |48.149GiB|
|scrambled68944.smt2                                                                        |1204.318s |47.643GiB|
|scrambled79760.smt2                                                                        |1204.069s |44.268GiB|
|scrambled108840.smt2                                                                       |1203.985s |43.086GiB|
|scrambled111627.smt2                                                                       |1203.780s |37.783GiB|
|scrambled43577.smt2                                                                        |1203.230s |34.29GiB|
|scrambled19335.smt2                                                                        |1203.308s |32.431GiB|
|scrambled75189.smt2                                                                        |1203.309s |31.686GiB|
|scrambled107826.smt2                                                                       |1202.503s |28.003GiB|
|scrambled27843.smt2                                                                        |1202.755s |21.066GiB|
|scrambled107115.smt2                                                                       |1201.796s |17.782GiB|
|scrambled40621.smt2                                                                        |1201.169s |11.532GiB|
|scrambled61922.smt2                                                                        |1202.028s |10.841GiB|
|scrambled119331.smt2                                                                       |1201.107s |9496.0MiB|
|scrambled7741.smt2                                                                         |1200.759s |6853.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.145s  |1205.145s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.796s  |1201.796s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.503s  |1202.503s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.985s  |1203.985s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.780s  |1203.780s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 190.367s  | 190.367s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.107s  |1201.107s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.849s  |1204.849s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 266.425s  | 266.425s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 145.875s  | 145.875s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.643s  |1200.643s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.556s  |1200.556s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  82.313s  |  82.313s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.725s  |1200.725s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.308s  |1203.308s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  74.747s  |  74.747s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 212.073s  | 212.073s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.755s  |1202.755s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 488.284s  | 488.284s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1201.169s  |1201.169s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1204.677s  |1204.677s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1205.796s  |1205.796s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1203.230s  |1203.230s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.943s  |1200.943s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.480s  |1200.480s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1205.336s  |1205.336s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.584s  |1200.584s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1202.028s  |1202.028s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1204.318s  |1204.318s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         | 748.823s  | 748.823s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1203.309s  |1203.309s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.759s  |1200.759s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1204.069s  |1204.069s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1207.335s  |1207.335s  |   0.000s  | 0.0%|
</details>
