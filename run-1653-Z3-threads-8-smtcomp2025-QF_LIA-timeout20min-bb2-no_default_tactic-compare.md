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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-no_default_tactic
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-no_default_tactic
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.407s  |1200.407s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 166.575s  | 166.575s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.463s  |1201.463s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.419s  |1200.419s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 104.462s  | 104.462s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  98.454s  |  98.454s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.728s  |1200.728s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.670s  |1200.670s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.820s  |1200.820s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        | 166.663s  | 166.663s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1005.549s  |1005.549s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 609.757s  | 609.757s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 455.798s  | 455.798s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.407s  |1200.407s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 166.575s  | 166.575s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.463s  |1201.463s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.419s  |1200.419s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 104.462s  | 104.462s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  98.454s  |  98.454s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.728s  |1200.728s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.670s  |1200.670s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.820s  |1200.820s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        | 166.663s  | 166.663s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1005.549s  |1005.549s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 609.757s  | 609.757s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 455.798s  | 455.798s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.407s  |1200.407s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 166.575s  | 166.575s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.463s  |1201.463s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.419s  |1200.419s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 104.462s  | 104.462s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  98.454s  |  98.454s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.728s  |1200.728s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.670s  |1200.670s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.820s  |1200.820s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        | 166.663s  | 166.663s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1005.549s  |1005.549s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 609.757s  | 609.757s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 455.798s  | 455.798s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.407s  |1200.407s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 166.575s  | 166.575s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.463s  |1201.463s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.419s  |1200.419s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 104.462s  | 104.462s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  98.454s  |  98.454s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.728s  |1200.728s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.670s  |1200.670s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.820s  |1200.820s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        | 166.663s  | 166.663s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1005.549s  |1005.549s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 609.757s  | 609.757s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 455.798s  | 455.798s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled119331.smt2                                                                       |1201.463s |9280.0MiB|
|scrambled40621.smt2                                                                        |1201.307s |9857.0MiB|
|scrambled7741.smt2                                                                         |1200.830s |6905.0MiB|
|scrambled128874.smt2                                                                       |1200.820s |4912.0MiB|
|scrambled44911.smt2                                                                        |1200.762s |4957.0MiB|
|scrambled55777.smt2                                                                        |1200.735s |4477.0MiB|
|scrambled128128.smt2                                                                       |1200.728s |6306.0MiB|
|scrambled128732.smt2                                                                       |1200.670s |5059.0MiB|
|scrambled94658.smt2                                                                        |1200.449s |2881.0MiB|
|scrambled12042.smt2                                                                        |1200.419s |2866.0MiB|
|scrambled102166.smt2                                                                       |1200.407s |2935.0MiB|
|scrambled55680.smt2                                                                        |1200.327s |2772.0MiB|
|scrambled4198.smt2                                                                         |1200.318s |2767.0MiB|
|scrambled4299.smt2                                                                         |1200.267s |2116.0MiB|
|scrambled79760.smt2                                                                        |1200.231s |1749.0MiB|
|scrambled111627.smt2                                                                       |1200.197s |1293.0MiB|
|scrambled108840.smt2                                                                       |1200.189s |1571.0MiB|
|scrambled43577.smt2                                                                        |1200.178s |1183.0MiB|
|scrambled68944.smt2                                                                        |1200.170s |1144.0MiB|
|scrambled107826.smt2                                                                       |1200.160s |1162.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled119331.smt2                                                                       |1201.463s |9280.0MiB|
|scrambled40621.smt2                                                                        |1201.307s |9857.0MiB|
|scrambled7741.smt2                                                                         |1200.830s |6905.0MiB|
|scrambled128874.smt2                                                                       |1200.820s |4912.0MiB|
|scrambled44911.smt2                                                                        |1200.762s |4957.0MiB|
|scrambled55777.smt2                                                                        |1200.735s |4477.0MiB|
|scrambled128128.smt2                                                                       |1200.728s |6306.0MiB|
|scrambled128732.smt2                                                                       |1200.670s |5059.0MiB|
|scrambled94658.smt2                                                                        |1200.449s |2881.0MiB|
|scrambled12042.smt2                                                                        |1200.419s |2866.0MiB|
|scrambled102166.smt2                                                                       |1200.407s |2935.0MiB|
|scrambled55680.smt2                                                                        |1200.327s |2772.0MiB|
|scrambled4198.smt2                                                                         |1200.318s |2767.0MiB|
|scrambled4299.smt2                                                                         |1200.267s |2116.0MiB|
|scrambled79760.smt2                                                                        |1200.231s |1749.0MiB|
|scrambled111627.smt2                                                                       |1200.197s |1293.0MiB|
|scrambled108840.smt2                                                                       |1200.189s |1571.0MiB|
|scrambled43577.smt2                                                                        |1200.178s |1183.0MiB|
|scrambled68944.smt2                                                                        |1200.170s |1144.0MiB|
|scrambled107826.smt2                                                                       |1200.160s |1162.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2935.0MiB|2935.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.34MiB|43.34MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |641.0MiB|641.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1162.0MiB|1162.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1571.0MiB|1571.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1293.0MiB|1293.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |965.0MiB|965.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9280.0MiB|9280.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2866.0MiB|2866.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |990.0MiB|990.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1670.0MiB|1670.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6306.0MiB|6306.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5059.0MiB|5059.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4912.0MiB|4912.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |4700.0MiB|4700.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |284.0MiB|284.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1288.0MiB|1288.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1744.0MiB|1744.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |6908.0MiB|6908.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |680.0MiB|680.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2935.0MiB|2935.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.34MiB|43.34MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |641.0MiB|641.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1162.0MiB|1162.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1571.0MiB|1571.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1293.0MiB|1293.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |965.0MiB|965.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9280.0MiB|9280.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2866.0MiB|2866.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |990.0MiB|990.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1670.0MiB|1670.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6306.0MiB|6306.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5059.0MiB|5059.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4912.0MiB|4912.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |4700.0MiB|4700.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |284.0MiB|284.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1288.0MiB|1288.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1744.0MiB|1744.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |6908.0MiB|6908.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |680.0MiB|680.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2935.0MiB|2935.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.34MiB|43.34MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |641.0MiB|641.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1162.0MiB|1162.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1571.0MiB|1571.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1293.0MiB|1293.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |965.0MiB|965.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9280.0MiB|9280.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2866.0MiB|2866.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |990.0MiB|990.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1670.0MiB|1670.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6306.0MiB|6306.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5059.0MiB|5059.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4912.0MiB|4912.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |4700.0MiB|4700.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |284.0MiB|284.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1288.0MiB|1288.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1744.0MiB|1744.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |6908.0MiB|6908.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |680.0MiB|680.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2935.0MiB|2935.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.34MiB|43.34MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |641.0MiB|641.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1162.0MiB|1162.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1571.0MiB|1571.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1293.0MiB|1293.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |965.0MiB|965.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9280.0MiB|9280.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2866.0MiB|2866.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |990.0MiB|990.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1670.0MiB|1670.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6306.0MiB|6306.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5059.0MiB|5059.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4912.0MiB|4912.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |4700.0MiB|4700.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |284.0MiB|284.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1288.0MiB|1288.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1744.0MiB|1744.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |6908.0MiB|6908.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |680.0MiB|680.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled40621.smt2                                                                        |1201.307s |9857.0MiB|
|scrambled119331.smt2                                                                       |1201.463s |9280.0MiB|
|scrambled25238.smt2                                                                        | 455.798s |6908.0MiB|
|scrambled7741.smt2                                                                         |1200.830s |6905.0MiB|
|scrambled128128.smt2                                                                       |1200.728s |6306.0MiB|
|scrambled72668.smt2                                                                        | 990.076s |5247.0MiB|
|scrambled128732.smt2                                                                       |1200.670s |5059.0MiB|
|scrambled44911.smt2                                                                        |1200.762s |4957.0MiB|
|scrambled128874.smt2                                                                       |1200.820s |4912.0MiB|
|scrambled131241.smt2                                                                       | 166.663s |4700.0MiB|
|scrambled55777.smt2                                                                        |1200.735s |4477.0MiB|
|scrambled102166.smt2                                                                       |1200.407s |2935.0MiB|
|scrambled94658.smt2                                                                        |1200.449s |2881.0MiB|
|scrambled12042.smt2                                                                        |1200.419s |2866.0MiB|
|scrambled55680.smt2                                                                        |1200.327s |2772.0MiB|
|scrambled4198.smt2                                                                         |1200.318s |2767.0MiB|
|scrambled32836.smt2                                                                        | 643.753s |2490.0MiB|
|scrambled95803.smt2                                                                        | 507.662s |2391.0MiB|
|scrambled4299.smt2                                                                         |1200.267s |2116.0MiB|
|scrambled79760.smt2                                                                        |1200.231s |1749.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled40621.smt2                                                                        |1201.307s |9857.0MiB|
|scrambled119331.smt2                                                                       |1201.463s |9280.0MiB|
|scrambled25238.smt2                                                                        | 455.798s |6908.0MiB|
|scrambled7741.smt2                                                                         |1200.830s |6905.0MiB|
|scrambled128128.smt2                                                                       |1200.728s |6306.0MiB|
|scrambled72668.smt2                                                                        | 990.076s |5247.0MiB|
|scrambled128732.smt2                                                                       |1200.670s |5059.0MiB|
|scrambled44911.smt2                                                                        |1200.762s |4957.0MiB|
|scrambled128874.smt2                                                                       |1200.820s |4912.0MiB|
|scrambled131241.smt2                                                                       | 166.663s |4700.0MiB|
|scrambled55777.smt2                                                                        |1200.735s |4477.0MiB|
|scrambled102166.smt2                                                                       |1200.407s |2935.0MiB|
|scrambled94658.smt2                                                                        |1200.449s |2881.0MiB|
|scrambled12042.smt2                                                                        |1200.419s |2866.0MiB|
|scrambled55680.smt2                                                                        |1200.327s |2772.0MiB|
|scrambled4198.smt2                                                                         |1200.318s |2767.0MiB|
|scrambled32836.smt2                                                                        | 643.753s |2490.0MiB|
|scrambled95803.smt2                                                                        | 507.662s |2391.0MiB|
|scrambled4299.smt2                                                                         |1200.267s |2116.0MiB|
|scrambled79760.smt2                                                                        |1200.231s |1749.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.407s  |1200.407s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 166.575s  | 166.575s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1201.463s  |1201.463s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.419s  |1200.419s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 104.462s  | 104.462s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  98.454s  |  98.454s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.728s  |1200.728s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.670s  |1200.670s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.820s  |1200.820s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        | 166.663s  | 166.663s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1005.549s  |1005.549s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 609.757s  | 609.757s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 455.798s  | 455.798s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 643.753s  | 643.753s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1201.307s  |1201.307s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1200.318s  |1200.318s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1200.267s  |1200.267s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1200.178s  |1200.178s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.762s  |1200.762s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         | 204.661s  | 204.661s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1200.327s  |1200.327s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.735s  |1200.735s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |   6.726s  |   6.726s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1200.170s  |1200.170s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         | 990.076s  | 990.076s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.830s  |1200.830s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1200.231s  |1200.231s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1200.449s  |1200.449s  |   0.000s  | 0.0%|
</details>
