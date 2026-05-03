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
Z3 commit: dd30b9eaf3624ea8d87e9e84ece5b50b171e5eda
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore incomplete-theory give-up paths

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: dd30b9eaf3624ea8d87e9e84ece5b50b171e5eda
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore incomplete-theory give-up paths

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.196s  |1205.196s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.818s  |1201.818s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.529s  |1202.529s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.999s  |1203.999s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.643s  |1203.643s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 150.254s  | 150.254s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.903s  |1200.903s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1205.335s  |1205.335s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 138.956s  | 138.956s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 145.287s  | 145.287s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.741s  |1200.741s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.504s  |1200.504s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.707s  |1200.707s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.776s  |1200.776s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.193s  |1203.193s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 125.361s  | 125.361s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 205.382s  | 205.382s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.248s  |1202.248s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.196s  |1205.196s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.818s  |1201.818s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.529s  |1202.529s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.999s  |1203.999s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.643s  |1203.643s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 150.254s  | 150.254s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.903s  |1200.903s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1205.335s  |1205.335s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 138.956s  | 138.956s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 145.287s  | 145.287s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.741s  |1200.741s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.504s  |1200.504s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.707s  |1200.707s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.776s  |1200.776s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.193s  |1203.193s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 125.361s  | 125.361s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 205.382s  | 205.382s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.248s  |1202.248s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.196s  |1205.196s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.818s  |1201.818s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.529s  |1202.529s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.999s  |1203.999s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.643s  |1203.643s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 150.254s  | 150.254s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.903s  |1200.903s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1205.335s  |1205.335s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 138.956s  | 138.956s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 145.287s  | 145.287s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.741s  |1200.741s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.504s  |1200.504s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.707s  |1200.707s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.776s  |1200.776s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.193s  |1203.193s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 125.361s  | 125.361s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 205.382s  | 205.382s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.248s  |1202.248s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.196s  |1205.196s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.818s  |1201.818s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.529s  |1202.529s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.999s  |1203.999s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.643s  |1203.643s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 150.254s  | 150.254s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.903s  |1200.903s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1205.335s  |1205.335s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 138.956s  | 138.956s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 145.287s  | 145.287s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.741s  |1200.741s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.504s  |1200.504s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.707s  |1200.707s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.776s  |1200.776s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.193s  |1203.193s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 125.361s  | 125.361s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 205.382s  | 205.382s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.248s  |1202.248s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.987s |63.168GiB|
|scrambled55680.smt2                                                                        |1205.686s |50.628GiB|
|scrambled4198.smt2                                                                         |1205.458s |49.17GiB|
|scrambled12042.smt2                                                                        |1205.335s |54.49GiB|
|scrambled4299.smt2                                                                         |1205.279s |56.815GiB|
|scrambled102166.smt2                                                                       |1205.196s |48.042GiB|
|scrambled79760.smt2                                                                        |1204.386s |44.258GiB|
|scrambled68944.smt2                                                                        |1204.356s |46.867GiB|
|scrambled75189.smt2                                                                        |1204.030s |31.663GiB|
|scrambled108840.smt2                                                                       |1203.999s |43.088GiB|
|scrambled111627.smt2                                                                       |1203.643s |37.772GiB|
|scrambled43577.smt2                                                                        |1203.490s |34.291GiB|
|scrambled19335.smt2                                                                        |1203.193s |31.987GiB|
|scrambled107826.smt2                                                                       |1202.529s |27.847GiB|
|scrambled27843.smt2                                                                        |1202.248s |21.034GiB|
|scrambled107115.smt2                                                                       |1201.818s |17.756GiB|
|scrambled61922.smt2                                                                        |1201.246s |10.83GiB|
|scrambled40621.smt2                                                                        |1201.155s |10.951GiB|
|scrambled119331.smt2                                                                       |1200.903s |9348.0MiB|
|scrambled55777.smt2                                                                        |1200.838s |4561.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.987s |63.168GiB|
|scrambled55680.smt2                                                                        |1205.686s |50.628GiB|
|scrambled4198.smt2                                                                         |1205.458s |49.17GiB|
|scrambled12042.smt2                                                                        |1205.335s |54.49GiB|
|scrambled4299.smt2                                                                         |1205.279s |56.815GiB|
|scrambled102166.smt2                                                                       |1205.196s |48.042GiB|
|scrambled79760.smt2                                                                        |1204.386s |44.258GiB|
|scrambled68944.smt2                                                                        |1204.356s |46.867GiB|
|scrambled75189.smt2                                                                        |1204.030s |31.663GiB|
|scrambled108840.smt2                                                                       |1203.999s |43.088GiB|
|scrambled111627.smt2                                                                       |1203.643s |37.772GiB|
|scrambled43577.smt2                                                                        |1203.490s |34.291GiB|
|scrambled19335.smt2                                                                        |1203.193s |31.987GiB|
|scrambled107826.smt2                                                                       |1202.529s |27.847GiB|
|scrambled27843.smt2                                                                        |1202.248s |21.034GiB|
|scrambled107115.smt2                                                                       |1201.818s |17.756GiB|
|scrambled61922.smt2                                                                        |1201.246s |10.83GiB|
|scrambled40621.smt2                                                                        |1201.155s |10.951GiB|
|scrambled119331.smt2                                                                       |1200.903s |9348.0MiB|
|scrambled55777.smt2                                                                        |1200.838s |4561.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.042GiB|48.042GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.564MiB|42.564MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.756GiB|17.756GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.847GiB|27.847GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.088GiB|43.088GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.772GiB|37.772GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |962.0MiB|962.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9348.0MiB|9348.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.49GiB|54.49GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1012.0MiB|1012.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1604.0MiB|1604.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6487.0MiB|6487.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5142.0MiB|5142.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5176.0MiB|5176.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6457.0MiB|6457.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |31.987GiB|31.987GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1631.0MiB|1631.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5921.0MiB|5921.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.034GiB|21.034GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.042GiB|48.042GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.564MiB|42.564MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.756GiB|17.756GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.847GiB|27.847GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.088GiB|43.088GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.772GiB|37.772GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |962.0MiB|962.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9348.0MiB|9348.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.49GiB|54.49GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1012.0MiB|1012.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1604.0MiB|1604.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6487.0MiB|6487.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5142.0MiB|5142.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5176.0MiB|5176.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6457.0MiB|6457.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |31.987GiB|31.987GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1631.0MiB|1631.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5921.0MiB|5921.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.034GiB|21.034GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.042GiB|48.042GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.564MiB|42.564MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.756GiB|17.756GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.847GiB|27.847GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.088GiB|43.088GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.772GiB|37.772GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |962.0MiB|962.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9348.0MiB|9348.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.49GiB|54.49GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1012.0MiB|1012.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1604.0MiB|1604.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6487.0MiB|6487.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5142.0MiB|5142.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5176.0MiB|5176.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6457.0MiB|6457.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |31.987GiB|31.987GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1631.0MiB|1631.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5921.0MiB|5921.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.034GiB|21.034GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.042GiB|48.042GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.564MiB|42.564MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.756GiB|17.756GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.847GiB|27.847GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.088GiB|43.088GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.772GiB|37.772GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |962.0MiB|962.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9348.0MiB|9348.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.49GiB|54.49GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1012.0MiB|1012.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1604.0MiB|1604.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6487.0MiB|6487.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5142.0MiB|5142.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5176.0MiB|5176.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6457.0MiB|6457.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |31.987GiB|31.987GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1631.0MiB|1631.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5921.0MiB|5921.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.034GiB|21.034GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.987s |63.168GiB|
|scrambled4299.smt2                                                                         |1205.279s |56.815GiB|
|scrambled12042.smt2                                                                        |1205.335s |54.49GiB|
|scrambled55680.smt2                                                                        |1205.686s |50.628GiB|
|scrambled4198.smt2                                                                         |1205.458s |49.17GiB|
|scrambled102166.smt2                                                                       |1205.196s |48.042GiB|
|scrambled68944.smt2                                                                        |1204.356s |46.867GiB|
|scrambled79760.smt2                                                                        |1204.386s |44.258GiB|
|scrambled108840.smt2                                                                       |1203.999s |43.088GiB|
|scrambled111627.smt2                                                                       |1203.643s |37.772GiB|
|scrambled43577.smt2                                                                        |1203.490s |34.291GiB|
|scrambled19335.smt2                                                                        |1203.193s |31.987GiB|
|scrambled75189.smt2                                                                        |1204.030s |31.663GiB|
|scrambled107826.smt2                                                                       |1202.529s |27.847GiB|
|scrambled27843.smt2                                                                        |1202.248s |21.034GiB|
|scrambled107115.smt2                                                                       |1201.818s |17.756GiB|
|scrambled40621.smt2                                                                        |1201.155s |10.951GiB|
|scrambled61922.smt2                                                                        |1201.246s |10.83GiB|
|scrambled119331.smt2                                                                       |1200.903s |9348.0MiB|
|scrambled7741.smt2                                                                         |1200.770s |6776.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.987s |63.168GiB|
|scrambled4299.smt2                                                                         |1205.279s |56.815GiB|
|scrambled12042.smt2                                                                        |1205.335s |54.49GiB|
|scrambled55680.smt2                                                                        |1205.686s |50.628GiB|
|scrambled4198.smt2                                                                         |1205.458s |49.17GiB|
|scrambled102166.smt2                                                                       |1205.196s |48.042GiB|
|scrambled68944.smt2                                                                        |1204.356s |46.867GiB|
|scrambled79760.smt2                                                                        |1204.386s |44.258GiB|
|scrambled108840.smt2                                                                       |1203.999s |43.088GiB|
|scrambled111627.smt2                                                                       |1203.643s |37.772GiB|
|scrambled43577.smt2                                                                        |1203.490s |34.291GiB|
|scrambled19335.smt2                                                                        |1203.193s |31.987GiB|
|scrambled75189.smt2                                                                        |1204.030s |31.663GiB|
|scrambled107826.smt2                                                                       |1202.529s |27.847GiB|
|scrambled27843.smt2                                                                        |1202.248s |21.034GiB|
|scrambled107115.smt2                                                                       |1201.818s |17.756GiB|
|scrambled40621.smt2                                                                        |1201.155s |10.951GiB|
|scrambled61922.smt2                                                                        |1201.246s |10.83GiB|
|scrambled119331.smt2                                                                       |1200.903s |9348.0MiB|
|scrambled7741.smt2                                                                         |1200.770s |6776.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.196s  |1205.196s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.818s  |1201.818s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.529s  |1202.529s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.999s  |1203.999s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.643s  |1203.643s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 150.254s  | 150.254s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.903s  |1200.903s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1205.335s  |1205.335s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 138.956s  | 138.956s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 145.287s  | 145.287s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.741s  |1200.741s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.504s  |1200.504s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.707s  |1200.707s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.776s  |1200.776s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.193s  |1203.193s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 125.361s  | 125.361s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 205.382s  | 205.382s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.248s  |1202.248s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1012.554s  |1012.554s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1201.155s  |1201.155s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1205.458s  |1205.458s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1205.279s  |1205.279s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1203.490s  |1203.490s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.655s  |1200.655s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.638s  |1200.638s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1205.686s  |1205.686s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.838s  |1200.838s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1201.246s  |1201.246s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1204.356s  |1204.356s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         | 669.769s  | 669.769s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1204.030s  |1204.030s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.770s  |1200.770s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1204.386s  |1204.386s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1205.987s  |1205.987s  |   0.000s  | 0.0%|
</details>
