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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-v1
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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-v1
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
|scrambled102166.smt2                                                                        |1205.654s  |1205.654s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.821s  |1201.821s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.629s  |1202.629s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.717s  |1203.717s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1204.368s  |1204.368s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 114.233s  | 114.233s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.902s  |1200.902s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.794s  |1204.794s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 145.555s  | 145.555s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 138.425s  | 138.425s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.587s  |1200.587s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.590s  |1200.590s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.613s  |1200.613s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.980s  |1200.980s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.269s  |1203.269s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  81.152s  |  81.152s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 202.561s  | 202.561s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1203.233s  |1203.233s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.654s  |1205.654s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.821s  |1201.821s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.629s  |1202.629s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.717s  |1203.717s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1204.368s  |1204.368s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 114.233s  | 114.233s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.902s  |1200.902s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.794s  |1204.794s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 145.555s  | 145.555s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 138.425s  | 138.425s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.587s  |1200.587s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.590s  |1200.590s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.613s  |1200.613s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.980s  |1200.980s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.269s  |1203.269s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  81.152s  |  81.152s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 202.561s  | 202.561s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1203.233s  |1203.233s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.654s  |1205.654s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.821s  |1201.821s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.629s  |1202.629s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.717s  |1203.717s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1204.368s  |1204.368s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 114.233s  | 114.233s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.902s  |1200.902s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.794s  |1204.794s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 145.555s  | 145.555s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 138.425s  | 138.425s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.587s  |1200.587s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.590s  |1200.590s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.613s  |1200.613s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.980s  |1200.980s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.269s  |1203.269s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  81.152s  |  81.152s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 202.561s  | 202.561s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1203.233s  |1203.233s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.654s  |1205.654s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.821s  |1201.821s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.629s  |1202.629s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.717s  |1203.717s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1204.368s  |1204.368s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 114.233s  | 114.233s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.902s  |1200.902s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.794s  |1204.794s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 145.555s  | 145.555s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 138.425s  | 138.425s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.587s  |1200.587s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.590s  |1200.590s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.613s  |1200.613s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.980s  |1200.980s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.269s  |1203.269s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  81.152s  |  81.152s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 202.561s  | 202.561s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1203.233s  |1203.233s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.821s |63.431GiB|
|scrambled102166.smt2                                                                       |1205.654s |48.043GiB|
|scrambled4198.smt2                                                                         |1205.009s |49.234GiB|
|scrambled4299.smt2                                                                         |1204.863s |56.787GiB|
|scrambled12042.smt2                                                                        |1204.794s |54.745GiB|
|scrambled55680.smt2                                                                        |1204.591s |50.684GiB|
|scrambled111627.smt2                                                                       |1204.368s |37.725GiB|
|scrambled68944.smt2                                                                        |1204.263s |46.969GiB|
|scrambled79760.smt2                                                                        |1204.128s |44.26GiB|
|scrambled108840.smt2                                                                       |1203.717s |43.105GiB|
|scrambled19335.smt2                                                                        |1203.269s |32.427GiB|
|scrambled43577.smt2                                                                        |1203.253s |34.374GiB|
|scrambled27843.smt2                                                                        |1203.233s |20.737GiB|
|scrambled75189.smt2                                                                        |1202.777s |31.717GiB|
|scrambled107826.smt2                                                                       |1202.629s |27.971GiB|
|scrambled107115.smt2                                                                       |1201.821s |17.78GiB|
|scrambled61922.smt2                                                                        |1201.183s |10.831GiB|
|scrambled72668.smt2                                                                        |1201.077s |5301.0MiB|
|scrambled40621.smt2                                                                        |1201.007s |11.154GiB|
|scrambled131241.smt2                                                                       |1200.980s |6401.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.821s |63.431GiB|
|scrambled102166.smt2                                                                       |1205.654s |48.043GiB|
|scrambled4198.smt2                                                                         |1205.009s |49.234GiB|
|scrambled4299.smt2                                                                         |1204.863s |56.787GiB|
|scrambled12042.smt2                                                                        |1204.794s |54.745GiB|
|scrambled55680.smt2                                                                        |1204.591s |50.684GiB|
|scrambled111627.smt2                                                                       |1204.368s |37.725GiB|
|scrambled68944.smt2                                                                        |1204.263s |46.969GiB|
|scrambled79760.smt2                                                                        |1204.128s |44.26GiB|
|scrambled108840.smt2                                                                       |1203.717s |43.105GiB|
|scrambled19335.smt2                                                                        |1203.269s |32.427GiB|
|scrambled43577.smt2                                                                        |1203.253s |34.374GiB|
|scrambled27843.smt2                                                                        |1203.233s |20.737GiB|
|scrambled75189.smt2                                                                        |1202.777s |31.717GiB|
|scrambled107826.smt2                                                                       |1202.629s |27.971GiB|
|scrambled107115.smt2                                                                       |1201.821s |17.78GiB|
|scrambled61922.smt2                                                                        |1201.183s |10.831GiB|
|scrambled72668.smt2                                                                        |1201.077s |5301.0MiB|
|scrambled40621.smt2                                                                        |1201.007s |11.154GiB|
|scrambled131241.smt2                                                                       |1200.980s |6401.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.043GiB|48.043GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.78GiB|17.78GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.971GiB|27.971GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.105GiB|43.105GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.725GiB|37.725GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |946.0MiB|946.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9554.0MiB|9554.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.745GiB|54.745GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1010.0MiB|1010.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1609.0MiB|1609.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6517.0MiB|6517.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5186.0MiB|5186.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5169.0MiB|5169.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6401.0MiB|6401.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |372.0MiB|372.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.427GiB|32.427GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1578.0MiB|1578.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5940.0MiB|5940.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.737GiB|20.737GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.043GiB|48.043GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.78GiB|17.78GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.971GiB|27.971GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.105GiB|43.105GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.725GiB|37.725GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |946.0MiB|946.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9554.0MiB|9554.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.745GiB|54.745GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1010.0MiB|1010.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1609.0MiB|1609.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6517.0MiB|6517.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5186.0MiB|5186.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5169.0MiB|5169.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6401.0MiB|6401.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |372.0MiB|372.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.427GiB|32.427GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1578.0MiB|1578.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5940.0MiB|5940.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.737GiB|20.737GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.043GiB|48.043GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.78GiB|17.78GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.971GiB|27.971GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.105GiB|43.105GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.725GiB|37.725GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |946.0MiB|946.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9554.0MiB|9554.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.745GiB|54.745GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1010.0MiB|1010.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1609.0MiB|1609.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6517.0MiB|6517.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5186.0MiB|5186.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5169.0MiB|5169.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6401.0MiB|6401.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |372.0MiB|372.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.427GiB|32.427GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1578.0MiB|1578.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5940.0MiB|5940.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.737GiB|20.737GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.043GiB|48.043GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.78GiB|17.78GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.971GiB|27.971GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.105GiB|43.105GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.725GiB|37.725GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |946.0MiB|946.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9554.0MiB|9554.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.745GiB|54.745GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1010.0MiB|1010.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1609.0MiB|1609.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6517.0MiB|6517.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5186.0MiB|5186.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5169.0MiB|5169.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6401.0MiB|6401.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |372.0MiB|372.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.427GiB|32.427GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1578.0MiB|1578.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5940.0MiB|5940.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.737GiB|20.737GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.821s |63.431GiB|
|scrambled4299.smt2                                                                         |1204.863s |56.787GiB|
|scrambled12042.smt2                                                                        |1204.794s |54.745GiB|
|scrambled55680.smt2                                                                        |1204.591s |50.684GiB|
|scrambled4198.smt2                                                                         |1205.009s |49.234GiB|
|scrambled102166.smt2                                                                       |1205.654s |48.043GiB|
|scrambled68944.smt2                                                                        |1204.263s |46.969GiB|
|scrambled79760.smt2                                                                        |1204.128s |44.26GiB|
|scrambled108840.smt2                                                                       |1203.717s |43.105GiB|
|scrambled111627.smt2                                                                       |1204.368s |37.725GiB|
|scrambled43577.smt2                                                                        |1203.253s |34.374GiB|
|scrambled19335.smt2                                                                        |1203.269s |32.427GiB|
|scrambled75189.smt2                                                                        |1202.777s |31.717GiB|
|scrambled107826.smt2                                                                       |1202.629s |27.971GiB|
|scrambled27843.smt2                                                                        |1203.233s |20.737GiB|
|scrambled107115.smt2                                                                       |1201.821s |17.78GiB|
|scrambled40621.smt2                                                                        |1201.007s |11.154GiB|
|scrambled61922.smt2                                                                        |1201.183s |10.831GiB|
|scrambled119331.smt2                                                                       |1200.902s |9554.0MiB|
|scrambled7741.smt2                                                                         |1200.936s |6767.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.821s |63.431GiB|
|scrambled4299.smt2                                                                         |1204.863s |56.787GiB|
|scrambled12042.smt2                                                                        |1204.794s |54.745GiB|
|scrambled55680.smt2                                                                        |1204.591s |50.684GiB|
|scrambled4198.smt2                                                                         |1205.009s |49.234GiB|
|scrambled102166.smt2                                                                       |1205.654s |48.043GiB|
|scrambled68944.smt2                                                                        |1204.263s |46.969GiB|
|scrambled79760.smt2                                                                        |1204.128s |44.26GiB|
|scrambled108840.smt2                                                                       |1203.717s |43.105GiB|
|scrambled111627.smt2                                                                       |1204.368s |37.725GiB|
|scrambled43577.smt2                                                                        |1203.253s |34.374GiB|
|scrambled19335.smt2                                                                        |1203.269s |32.427GiB|
|scrambled75189.smt2                                                                        |1202.777s |31.717GiB|
|scrambled107826.smt2                                                                       |1202.629s |27.971GiB|
|scrambled27843.smt2                                                                        |1203.233s |20.737GiB|
|scrambled107115.smt2                                                                       |1201.821s |17.78GiB|
|scrambled40621.smt2                                                                        |1201.007s |11.154GiB|
|scrambled61922.smt2                                                                        |1201.183s |10.831GiB|
|scrambled119331.smt2                                                                       |1200.902s |9554.0MiB|
|scrambled7741.smt2                                                                         |1200.936s |6767.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.654s  |1205.654s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.821s  |1201.821s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.629s  |1202.629s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.717s  |1203.717s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1204.368s  |1204.368s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 114.233s  | 114.233s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.902s  |1200.902s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.794s  |1204.794s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 145.555s  | 145.555s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 138.425s  | 138.425s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.587s  |1200.587s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.590s  |1200.590s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.613s  |1200.613s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.980s  |1200.980s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.269s  |1203.269s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  81.152s  |  81.152s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 202.561s  | 202.561s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1203.233s  |1203.233s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.374s  |1200.374s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1201.007s  |1201.007s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1205.009s  |1205.009s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1204.863s  |1204.863s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1203.253s  |1203.253s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.631s  |1200.631s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.433s  |1200.433s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1204.591s  |1204.591s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.656s  |1200.656s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1201.183s  |1201.183s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1204.263s  |1204.263s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1201.077s  |1201.077s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1202.777s  |1202.777s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.936s  |1200.936s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1204.128s  |1204.128s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1205.821s  |1205.821s  |   0.000s  | 0.0%|
</details>
