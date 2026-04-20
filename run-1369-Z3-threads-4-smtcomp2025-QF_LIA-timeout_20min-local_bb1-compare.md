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
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-local_bb1
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bdff96fde97215ca1c28b4d30df7a4a20cbfc050
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.local_backbones=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: undo local bb ablation about resetting phase/activities, and reinstate the shared lemmas of length 2 and 3 experiment

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-local_bb1
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bdff96fde97215ca1c28b4d30df7a4a20cbfc050
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.local_backbones=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: undo local bb ablation about resetting phase/activities, and reinstate the shared lemmas of length 2 and 3 experiment

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.211s  |1262.211s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.039s  |1260.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.070s  |1261.070s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.587s  |1261.587s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.118s  |1262.118s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.859s  |1261.859s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 891.427s  | 891.427s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.602s  |1260.602s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.949s  |1262.949s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 121.310s  | 121.310s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 548.859s  | 548.859s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.403s  |1260.403s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.205s  |1260.205s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.419s  |1260.419s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.415s  |1260.415s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.087s  |1260.087s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.718s  |1261.718s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 165.349s  | 165.349s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 456.424s  | 456.424s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.184s  |1261.184s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.211s  |1262.211s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.039s  |1260.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.070s  |1261.070s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.587s  |1261.587s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.118s  |1262.118s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.859s  |1261.859s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 891.427s  | 891.427s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.602s  |1260.602s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.949s  |1262.949s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 121.310s  | 121.310s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 548.859s  | 548.859s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.403s  |1260.403s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.205s  |1260.205s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.419s  |1260.419s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.415s  |1260.415s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.087s  |1260.087s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.718s  |1261.718s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 165.349s  | 165.349s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 456.424s  | 456.424s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.184s  |1261.184s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.211s  |1262.211s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.039s  |1260.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.070s  |1261.070s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.587s  |1261.587s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.118s  |1262.118s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.859s  |1261.859s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 891.427s  | 891.427s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.602s  |1260.602s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.949s  |1262.949s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 121.310s  | 121.310s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 548.859s  | 548.859s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.403s  |1260.403s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.205s  |1260.205s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.419s  |1260.419s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.415s  |1260.415s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.087s  |1260.087s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.718s  |1261.718s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 165.349s  | 165.349s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 456.424s  | 456.424s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.184s  |1261.184s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.211s  |1262.211s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.039s  |1260.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.070s  |1261.070s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.587s  |1261.587s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.118s  |1262.118s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.859s  |1261.859s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 891.427s  | 891.427s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.602s  |1260.602s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.949s  |1262.949s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 121.310s  | 121.310s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 548.859s  | 548.859s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.403s  |1260.403s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.205s  |1260.205s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.419s  |1260.419s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.415s  |1260.415s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.087s  |1260.087s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.718s  |1261.718s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 165.349s  | 165.349s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 456.424s  | 456.424s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.184s  |1261.184s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.109s |31.37GiB|
|scrambled12042.smt2                                                                        |1262.949s |29.835GiB|
|scrambled4299.smt2                                                                         |1262.651s |26.155GiB|
|scrambled68944.smt2                                                                        |1262.413s |23.315GiB|
|scrambled55680.smt2                                                                        |1262.335s |25.02GiB|
|scrambled79760.smt2                                                                        |1262.293s |21.909GiB|
|scrambled102166.smt2                                                                       |1262.211s |23.489GiB|
|scrambled108840.smt2                                                                       |1262.118s |22.301GiB|
|scrambled4198.smt2                                                                         |1262.062s |24.522GiB|
|scrambled75189.smt2                                                                        |1261.904s |17.038GiB|
|scrambled111627.smt2                                                                       |1261.859s |18.981GiB|
|scrambled19335.smt2                                                                        |1261.718s |15.597GiB|
|scrambled107826.smt2                                                                       |1261.587s |14.244GiB|
|scrambled43577.smt2                                                                        |1261.545s |15.338GiB|
|scrambled27843.smt2                                                                        |1261.184s |11.128GiB|
|scrambled107115.smt2                                                                       |1261.070s |8696.0MiB|
|scrambled61922.smt2                                                                        |1260.843s |5565.0MiB|
|scrambled119331.smt2                                                                       |1260.602s |4039.0MiB|
|scrambled40621.smt2                                                                        |1260.583s |4279.0MiB|
|scrambled72668.smt2                                                                        |1260.466s |2163.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.109s |31.37GiB|
|scrambled12042.smt2                                                                        |1262.949s |29.835GiB|
|scrambled4299.smt2                                                                         |1262.651s |26.155GiB|
|scrambled68944.smt2                                                                        |1262.413s |23.315GiB|
|scrambled55680.smt2                                                                        |1262.335s |25.02GiB|
|scrambled79760.smt2                                                                        |1262.293s |21.909GiB|
|scrambled102166.smt2                                                                       |1262.211s |23.489GiB|
|scrambled108840.smt2                                                                       |1262.118s |22.301GiB|
|scrambled4198.smt2                                                                         |1262.062s |24.522GiB|
|scrambled75189.smt2                                                                        |1261.904s |17.038GiB|
|scrambled111627.smt2                                                                       |1261.859s |18.981GiB|
|scrambled19335.smt2                                                                        |1261.718s |15.597GiB|
|scrambled107826.smt2                                                                       |1261.587s |14.244GiB|
|scrambled43577.smt2                                                                        |1261.545s |15.338GiB|
|scrambled27843.smt2                                                                        |1261.184s |11.128GiB|
|scrambled107115.smt2                                                                       |1261.070s |8696.0MiB|
|scrambled61922.smt2                                                                        |1260.843s |5565.0MiB|
|scrambled119331.smt2                                                                       |1260.602s |4039.0MiB|
|scrambled40621.smt2                                                                        |1260.583s |4279.0MiB|
|scrambled72668.smt2                                                                        |1260.466s |2163.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.489GiB|23.489GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.808MiB|42.808MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8696.0MiB|8696.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.244GiB|14.244GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.301GiB|22.301GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.981GiB|18.981GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |413.0MiB|413.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |4039.0MiB|4039.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.835GiB|29.835GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |411.0MiB|411.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |676.0MiB|676.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2490.0MiB|2490.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2062.0MiB|2062.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1996.0MiB|1996.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2575.0MiB|2575.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |157.0MiB|157.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.597GiB|15.597GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |671.0MiB|671.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2714.0MiB|2714.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.128GiB|11.128GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.489GiB|23.489GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.808MiB|42.808MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8696.0MiB|8696.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.244GiB|14.244GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.301GiB|22.301GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.981GiB|18.981GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |413.0MiB|413.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |4039.0MiB|4039.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.835GiB|29.835GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |411.0MiB|411.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |676.0MiB|676.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2490.0MiB|2490.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2062.0MiB|2062.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1996.0MiB|1996.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2575.0MiB|2575.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |157.0MiB|157.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.597GiB|15.597GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |671.0MiB|671.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2714.0MiB|2714.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.128GiB|11.128GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.489GiB|23.489GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.808MiB|42.808MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8696.0MiB|8696.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.244GiB|14.244GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.301GiB|22.301GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.981GiB|18.981GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |413.0MiB|413.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |4039.0MiB|4039.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.835GiB|29.835GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |411.0MiB|411.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |676.0MiB|676.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2490.0MiB|2490.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2062.0MiB|2062.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1996.0MiB|1996.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2575.0MiB|2575.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |157.0MiB|157.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.597GiB|15.597GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |671.0MiB|671.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2714.0MiB|2714.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.128GiB|11.128GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.489GiB|23.489GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.808MiB|42.808MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8696.0MiB|8696.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.244GiB|14.244GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.301GiB|22.301GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.981GiB|18.981GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |413.0MiB|413.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |4039.0MiB|4039.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.835GiB|29.835GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |411.0MiB|411.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |676.0MiB|676.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2490.0MiB|2490.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2062.0MiB|2062.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1996.0MiB|1996.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2575.0MiB|2575.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |157.0MiB|157.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.597GiB|15.597GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |671.0MiB|671.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2714.0MiB|2714.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.128GiB|11.128GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.109s |31.37GiB|
|scrambled12042.smt2                                                                        |1262.949s |29.835GiB|
|scrambled4299.smt2                                                                         |1262.651s |26.155GiB|
|scrambled55680.smt2                                                                        |1262.335s |25.02GiB|
|scrambled4198.smt2                                                                         |1262.062s |24.522GiB|
|scrambled102166.smt2                                                                       |1262.211s |23.489GiB|
|scrambled68944.smt2                                                                        |1262.413s |23.315GiB|
|scrambled108840.smt2                                                                       |1262.118s |22.301GiB|
|scrambled79760.smt2                                                                        |1262.293s |21.909GiB|
|scrambled111627.smt2                                                                       |1261.859s |18.981GiB|
|scrambled75189.smt2                                                                        |1261.904s |17.038GiB|
|scrambled19335.smt2                                                                        |1261.718s |15.597GiB|
|scrambled43577.smt2                                                                        |1261.545s |15.338GiB|
|scrambled107826.smt2                                                                       |1261.587s |14.244GiB|
|scrambled27843.smt2                                                                        |1261.184s |11.128GiB|
|scrambled107115.smt2                                                                       |1261.070s |8696.0MiB|
|scrambled61922.smt2                                                                        |1260.843s |5565.0MiB|
|scrambled40621.smt2                                                                        |1260.583s |4279.0MiB|
|scrambled119331.smt2                                                                       |1260.602s |4039.0MiB|
|scrambled25238.smt2                                                                        | 456.424s |2714.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.109s |31.37GiB|
|scrambled12042.smt2                                                                        |1262.949s |29.835GiB|
|scrambled4299.smt2                                                                         |1262.651s |26.155GiB|
|scrambled55680.smt2                                                                        |1262.335s |25.02GiB|
|scrambled4198.smt2                                                                         |1262.062s |24.522GiB|
|scrambled102166.smt2                                                                       |1262.211s |23.489GiB|
|scrambled68944.smt2                                                                        |1262.413s |23.315GiB|
|scrambled108840.smt2                                                                       |1262.118s |22.301GiB|
|scrambled79760.smt2                                                                        |1262.293s |21.909GiB|
|scrambled111627.smt2                                                                       |1261.859s |18.981GiB|
|scrambled75189.smt2                                                                        |1261.904s |17.038GiB|
|scrambled19335.smt2                                                                        |1261.718s |15.597GiB|
|scrambled43577.smt2                                                                        |1261.545s |15.338GiB|
|scrambled107826.smt2                                                                       |1261.587s |14.244GiB|
|scrambled27843.smt2                                                                        |1261.184s |11.128GiB|
|scrambled107115.smt2                                                                       |1261.070s |8696.0MiB|
|scrambled61922.smt2                                                                        |1260.843s |5565.0MiB|
|scrambled40621.smt2                                                                        |1260.583s |4279.0MiB|
|scrambled119331.smt2                                                                       |1260.602s |4039.0MiB|
|scrambled25238.smt2                                                                        | 456.424s |2714.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.211s  |1262.211s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.039s  |1260.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.070s  |1261.070s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.587s  |1261.587s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.118s  |1262.118s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.859s  |1261.859s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 891.427s  | 891.427s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.602s  |1260.602s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.949s  |1262.949s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 121.310s  | 121.310s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 548.859s  | 548.859s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.403s  |1260.403s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.205s  |1260.205s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.419s  |1260.419s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.415s  |1260.415s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.087s  |1260.087s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.718s  |1261.718s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 165.349s  | 165.349s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 456.424s  | 456.424s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.184s  |1261.184s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 579.329s  | 579.329s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1260.054s  |1260.054s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1260.035s  |1260.035s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1260.583s  |1260.583s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1262.062s  |1262.062s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1262.651s  |1262.651s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1261.545s  |1261.545s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1260.395s  |1260.395s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1260.024s  |1260.024s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1260.305s  |1260.305s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1262.335s  |1262.335s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1260.191s  |1260.191s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1260.053s  |1260.053s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1260.843s  |1260.843s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1260.023s  |1260.023s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1262.413s  |1262.413s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1260.466s  |1260.466s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1261.904s  |1261.904s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1260.423s  |1260.423s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1262.293s  |1262.293s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1260.053s  |1260.053s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1260.051s  |1260.051s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1263.109s  |1263.109s  |   0.000s  | 0.0%|
</details>
