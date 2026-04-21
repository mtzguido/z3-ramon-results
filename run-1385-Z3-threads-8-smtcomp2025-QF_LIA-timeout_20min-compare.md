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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout_20min
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 8e294820a0bcdbe59f6282f7a0a3f73f594bd601
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: backtrack more aggressively in search tree: close matching external targets (i.e. repeat literals on other branches)

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout_20min
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 8e294820a0bcdbe59f6282f7a0a3f73f594bd601
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: backtrack more aggressively in search tree: close matching external targets (i.e. repeat literals on other branches)

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1264.196s  |1264.196s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.045s  |1260.045s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.813s  |1261.813s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1262.626s  |1262.626s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1263.958s  |1263.958s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1264.018s  |1264.018s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 116.779s  | 116.779s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.963s  |1260.963s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1264.862s  |1264.862s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 203.106s  | 203.106s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 158.212s  | 158.212s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.672s  |1260.672s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.543s  |1260.543s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  90.501s  |  90.501s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1261.107s  |1261.107s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.062s  |1260.062s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1264.351s  |1264.351s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 107.817s  | 107.817s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 197.532s  | 197.532s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1262.049s  |1262.049s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1264.196s  |1264.196s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.045s  |1260.045s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.813s  |1261.813s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1262.626s  |1262.626s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1263.958s  |1263.958s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1264.018s  |1264.018s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 116.779s  | 116.779s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.963s  |1260.963s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1264.862s  |1264.862s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 203.106s  | 203.106s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 158.212s  | 158.212s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.672s  |1260.672s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.543s  |1260.543s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  90.501s  |  90.501s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1261.107s  |1261.107s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.062s  |1260.062s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1264.351s  |1264.351s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 107.817s  | 107.817s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 197.532s  | 197.532s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1262.049s  |1262.049s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1264.196s  |1264.196s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.045s  |1260.045s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.813s  |1261.813s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1262.626s  |1262.626s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1263.958s  |1263.958s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1264.018s  |1264.018s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 116.779s  | 116.779s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.963s  |1260.963s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1264.862s  |1264.862s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 203.106s  | 203.106s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 158.212s  | 158.212s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.672s  |1260.672s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.543s  |1260.543s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  90.501s  |  90.501s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1261.107s  |1261.107s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.062s  |1260.062s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1264.351s  |1264.351s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 107.817s  | 107.817s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 197.532s  | 197.532s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1262.049s  |1262.049s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1264.196s  |1264.196s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.045s  |1260.045s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.813s  |1261.813s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1262.626s  |1262.626s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1263.958s  |1263.958s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1264.018s  |1264.018s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 116.779s  | 116.779s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.963s  |1260.963s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1264.862s  |1264.862s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 203.106s  | 203.106s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 158.212s  | 158.212s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.672s  |1260.672s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.543s  |1260.543s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  90.501s  |  90.501s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1261.107s  |1261.107s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.062s  |1260.062s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1264.351s  |1264.351s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 107.817s  | 107.817s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 197.532s  | 197.532s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1262.049s  |1262.049s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1265.240s |62.314GiB|
|scrambled4299.smt2                                                                         |1265.179s |56.495GiB|
|scrambled12042.smt2                                                                        |1264.862s |54.332GiB|
|scrambled19335.smt2                                                                        |1264.351s |32.078GiB|
|scrambled55680.smt2                                                                        |1264.322s |50.218GiB|
|scrambled68944.smt2                                                                        |1264.223s |48.09GiB|
|scrambled102166.smt2                                                                       |1264.196s |47.697GiB|
|scrambled4198.smt2                                                                         |1264.119s |48.57GiB|
|scrambled79760.smt2                                                                        |1264.083s |44.325GiB|
|scrambled111627.smt2                                                                       |1264.018s |37.565GiB|
|scrambled108840.smt2                                                                       |1263.958s |42.678GiB|
|scrambled43577.smt2                                                                        |1263.210s |34.115GiB|
|scrambled75189.smt2                                                                        |1262.982s |31.543GiB|
|scrambled107826.smt2                                                                       |1262.626s |27.716GiB|
|scrambled27843.smt2                                                                        |1262.049s |20.739GiB|
|scrambled107115.smt2                                                                       |1261.813s |17.634GiB|
|scrambled40621.smt2                                                                        |1261.548s |11.326GiB|
|scrambled7741.smt2                                                                         |1261.150s |6756.0MiB|
|scrambled131241.smt2                                                                       |1261.107s |6367.0MiB|
|scrambled61922.smt2                                                                        |1261.105s |10.71GiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1265.240s |62.314GiB|
|scrambled4299.smt2                                                                         |1265.179s |56.495GiB|
|scrambled12042.smt2                                                                        |1264.862s |54.332GiB|
|scrambled19335.smt2                                                                        |1264.351s |32.078GiB|
|scrambled55680.smt2                                                                        |1264.322s |50.218GiB|
|scrambled68944.smt2                                                                        |1264.223s |48.09GiB|
|scrambled102166.smt2                                                                       |1264.196s |47.697GiB|
|scrambled4198.smt2                                                                         |1264.119s |48.57GiB|
|scrambled79760.smt2                                                                        |1264.083s |44.325GiB|
|scrambled111627.smt2                                                                       |1264.018s |37.565GiB|
|scrambled108840.smt2                                                                       |1263.958s |42.678GiB|
|scrambled43577.smt2                                                                        |1263.210s |34.115GiB|
|scrambled75189.smt2                                                                        |1262.982s |31.543GiB|
|scrambled107826.smt2                                                                       |1262.626s |27.716GiB|
|scrambled27843.smt2                                                                        |1262.049s |20.739GiB|
|scrambled107115.smt2                                                                       |1261.813s |17.634GiB|
|scrambled40621.smt2                                                                        |1261.548s |11.326GiB|
|scrambled7741.smt2                                                                         |1261.150s |6756.0MiB|
|scrambled131241.smt2                                                                       |1261.107s |6367.0MiB|
|scrambled61922.smt2                                                                        |1261.105s |10.71GiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.697GiB|47.697GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.6MiB|42.6MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.634GiB|17.634GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.716GiB|27.716GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.678GiB|42.678GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.565GiB|37.565GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |915.0MiB|915.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9517.0MiB|9517.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.332GiB|54.332GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |987.0MiB|987.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1581.0MiB|1581.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6481.0MiB|6481.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5087.0MiB|5087.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3869.0MiB|3869.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6367.0MiB|6367.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |362.0MiB|362.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.078GiB|32.078GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1579.0MiB|1579.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5762.0MiB|5762.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.739GiB|20.739GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.697GiB|47.697GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.6MiB|42.6MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.634GiB|17.634GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.716GiB|27.716GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.678GiB|42.678GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.565GiB|37.565GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |915.0MiB|915.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9517.0MiB|9517.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.332GiB|54.332GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |987.0MiB|987.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1581.0MiB|1581.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6481.0MiB|6481.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5087.0MiB|5087.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3869.0MiB|3869.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6367.0MiB|6367.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |362.0MiB|362.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.078GiB|32.078GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1579.0MiB|1579.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5762.0MiB|5762.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.739GiB|20.739GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.697GiB|47.697GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.6MiB|42.6MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.634GiB|17.634GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.716GiB|27.716GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.678GiB|42.678GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.565GiB|37.565GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |915.0MiB|915.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9517.0MiB|9517.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.332GiB|54.332GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |987.0MiB|987.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1581.0MiB|1581.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6481.0MiB|6481.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5087.0MiB|5087.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3869.0MiB|3869.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6367.0MiB|6367.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |362.0MiB|362.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.078GiB|32.078GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1579.0MiB|1579.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5762.0MiB|5762.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.739GiB|20.739GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.697GiB|47.697GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.6MiB|42.6MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.634GiB|17.634GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.716GiB|27.716GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.678GiB|42.678GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.565GiB|37.565GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |915.0MiB|915.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9517.0MiB|9517.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.332GiB|54.332GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |987.0MiB|987.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1581.0MiB|1581.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6481.0MiB|6481.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5087.0MiB|5087.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3869.0MiB|3869.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6367.0MiB|6367.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |362.0MiB|362.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.078GiB|32.078GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1579.0MiB|1579.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5762.0MiB|5762.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.739GiB|20.739GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1265.240s |62.314GiB|
|scrambled4299.smt2                                                                         |1265.179s |56.495GiB|
|scrambled12042.smt2                                                                        |1264.862s |54.332GiB|
|scrambled55680.smt2                                                                        |1264.322s |50.218GiB|
|scrambled4198.smt2                                                                         |1264.119s |48.57GiB|
|scrambled68944.smt2                                                                        |1264.223s |48.09GiB|
|scrambled102166.smt2                                                                       |1264.196s |47.697GiB|
|scrambled79760.smt2                                                                        |1264.083s |44.325GiB|
|scrambled108840.smt2                                                                       |1263.958s |42.678GiB|
|scrambled111627.smt2                                                                       |1264.018s |37.565GiB|
|scrambled43577.smt2                                                                        |1263.210s |34.115GiB|
|scrambled19335.smt2                                                                        |1264.351s |32.078GiB|
|scrambled75189.smt2                                                                        |1262.982s |31.543GiB|
|scrambled107826.smt2                                                                       |1262.626s |27.716GiB|
|scrambled27843.smt2                                                                        |1262.049s |20.739GiB|
|scrambled107115.smt2                                                                       |1261.813s |17.634GiB|
|scrambled40621.smt2                                                                        |1261.548s |11.326GiB|
|scrambled61922.smt2                                                                        |1261.105s |10.71GiB|
|scrambled119331.smt2                                                                       |1260.963s |9517.0MiB|
|scrambled7741.smt2                                                                         |1261.150s |6756.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1265.240s |62.314GiB|
|scrambled4299.smt2                                                                         |1265.179s |56.495GiB|
|scrambled12042.smt2                                                                        |1264.862s |54.332GiB|
|scrambled55680.smt2                                                                        |1264.322s |50.218GiB|
|scrambled4198.smt2                                                                         |1264.119s |48.57GiB|
|scrambled68944.smt2                                                                        |1264.223s |48.09GiB|
|scrambled102166.smt2                                                                       |1264.196s |47.697GiB|
|scrambled79760.smt2                                                                        |1264.083s |44.325GiB|
|scrambled108840.smt2                                                                       |1263.958s |42.678GiB|
|scrambled111627.smt2                                                                       |1264.018s |37.565GiB|
|scrambled43577.smt2                                                                        |1263.210s |34.115GiB|
|scrambled19335.smt2                                                                        |1264.351s |32.078GiB|
|scrambled75189.smt2                                                                        |1262.982s |31.543GiB|
|scrambled107826.smt2                                                                       |1262.626s |27.716GiB|
|scrambled27843.smt2                                                                        |1262.049s |20.739GiB|
|scrambled107115.smt2                                                                       |1261.813s |17.634GiB|
|scrambled40621.smt2                                                                        |1261.548s |11.326GiB|
|scrambled61922.smt2                                                                        |1261.105s |10.71GiB|
|scrambled119331.smt2                                                                       |1260.963s |9517.0MiB|
|scrambled7741.smt2                                                                         |1261.150s |6756.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1264.196s  |1264.196s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.045s  |1260.045s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.813s  |1261.813s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1262.626s  |1262.626s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1263.958s  |1263.958s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1264.018s  |1264.018s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 116.779s  | 116.779s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.963s  |1260.963s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1264.862s  |1264.862s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 203.106s  | 203.106s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 158.212s  | 158.212s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.672s  |1260.672s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.543s  |1260.543s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  90.501s  |  90.501s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1261.107s  |1261.107s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.062s  |1260.062s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1264.351s  |1264.351s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 107.817s  | 107.817s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 197.532s  | 197.532s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1262.049s  |1262.049s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1260.547s  |1260.547s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1260.014s  |1260.014s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1260.037s  |1260.037s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1261.548s  |1261.548s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1264.119s  |1264.119s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1265.179s  |1265.179s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1263.210s  |1263.210s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1260.818s  |1260.818s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1260.023s  |1260.023s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1260.347s  |1260.347s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1264.322s  |1264.322s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1260.537s  |1260.537s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1260.023s  |1260.023s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1261.105s  |1261.105s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1260.023s  |1260.023s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1264.223s  |1264.223s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         | 176.000s  | 176.000s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1262.982s  |1262.982s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1261.150s  |1261.150s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1264.083s  |1264.083s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1260.014s  |1260.014s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1265.240s  |1265.240s  |   0.000s  | 0.0%|
</details>
