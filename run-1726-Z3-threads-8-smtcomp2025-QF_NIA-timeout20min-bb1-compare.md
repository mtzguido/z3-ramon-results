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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb1
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: c383004968f5bf66a9668a7ae254c83d45ac3afe
Z3 branch: fmcad26_artifact
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=1"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: add ablate_backtracking experiment

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb1
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: c383004968f5bf66a9668a7ae254c83d45ac3afe
Z3 branch: fmcad26_artifact
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=1"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: add ablate_backtracking experiment

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.168s  |1200.168s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  33.559s  |  33.559s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.297s  |1200.297s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.530s  |1200.530s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.635s  |  11.635s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  11.069s  |  11.069s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 476.363s  | 476.363s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.576s  |  13.576s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 245.944s  | 245.944s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.762s  |  21.762s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.917s  |   3.917s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 115.703s  | 115.703s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 542.796s  | 542.796s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.168s  |1200.168s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  33.559s  |  33.559s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.297s  |1200.297s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.530s  |1200.530s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.635s  |  11.635s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  11.069s  |  11.069s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 476.363s  | 476.363s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.576s  |  13.576s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 245.944s  | 245.944s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.762s  |  21.762s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.917s  |   3.917s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 115.703s  | 115.703s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 542.796s  | 542.796s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.168s  |1200.168s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  33.559s  |  33.559s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.297s  |1200.297s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.530s  |1200.530s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.635s  |  11.635s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  11.069s  |  11.069s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 476.363s  | 476.363s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.576s  |  13.576s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 245.944s  | 245.944s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.762s  |  21.762s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.917s  |   3.917s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 115.703s  | 115.703s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 542.796s  | 542.796s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.168s  |1200.168s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  33.559s  |  33.559s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.297s  |1200.297s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.530s  |1200.530s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.635s  |  11.635s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  11.069s  |  11.069s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 476.363s  | 476.363s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.576s  |  13.576s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 245.944s  | 245.944s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.762s  |  21.762s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.917s  |   3.917s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 115.703s  | 115.703s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 542.796s  | 542.796s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.482s |27.54GiB|
|scrambled122926.smt2                                                                       |1200.530s |3267.0MiB|
|scrambled73755.smt2                                                                        |1200.501s |4789.0MiB|
|scrambled87588.smt2                                                                        |1200.457s |3570.0MiB|
|scrambled41135.smt2                                                                        |1200.435s |4986.0MiB|
|scrambled82760.smt2                                                                        |1200.363s |3429.0MiB|
|scrambled91750.smt2                                                                        |1200.341s |2428.0MiB|
|scrambled108406.smt2                                                                       |1200.323s |1865.0MiB|
|scrambled108663.smt2                                                                       |1200.319s |2773.0MiB|
|scrambled12033.smt2                                                                        |1200.297s |2672.0MiB|
|scrambled130111.smt2                                                                       |1200.284s |2105.0MiB|
|scrambled62032.smt2                                                                        |1200.276s |2361.0MiB|
|scrambled47700.smt2                                                                        |1200.258s |2118.0MiB|
|scrambled73281.smt2                                                                        |1200.242s |1933.0MiB|
|scrambled97386.smt2                                                                        |1200.239s |1651.0MiB|
|scrambled58311.smt2                                                                        |1200.236s |1669.0MiB|
|scrambled39467.smt2                                                                        |1200.234s |1758.0MiB|
|scrambled9883.smt2                                                                         |1200.210s |1321.0MiB|
|scrambled119582.smt2                                                                       |1200.197s |1448.0MiB|
|scrambled8852.smt2                                                                         |1200.181s |1554.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.482s |27.54GiB|
|scrambled122926.smt2                                                                       |1200.530s |3267.0MiB|
|scrambled73755.smt2                                                                        |1200.501s |4789.0MiB|
|scrambled87588.smt2                                                                        |1200.457s |3570.0MiB|
|scrambled41135.smt2                                                                        |1200.435s |4986.0MiB|
|scrambled82760.smt2                                                                        |1200.363s |3429.0MiB|
|scrambled91750.smt2                                                                        |1200.341s |2428.0MiB|
|scrambled108406.smt2                                                                       |1200.323s |1865.0MiB|
|scrambled108663.smt2                                                                       |1200.319s |2773.0MiB|
|scrambled12033.smt2                                                                        |1200.297s |2672.0MiB|
|scrambled130111.smt2                                                                       |1200.284s |2105.0MiB|
|scrambled62032.smt2                                                                        |1200.276s |2361.0MiB|
|scrambled47700.smt2                                                                        |1200.258s |2118.0MiB|
|scrambled73281.smt2                                                                        |1200.242s |1933.0MiB|
|scrambled97386.smt2                                                                        |1200.239s |1651.0MiB|
|scrambled58311.smt2                                                                        |1200.236s |1669.0MiB|
|scrambled39467.smt2                                                                        |1200.234s |1758.0MiB|
|scrambled9883.smt2                                                                         |1200.210s |1321.0MiB|
|scrambled119582.smt2                                                                       |1200.197s |1448.0MiB|
|scrambled8852.smt2                                                                         |1200.181s |1554.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1216.0MiB|1216.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1323.0MiB|1323.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |362.0MiB|362.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1865.0MiB|1865.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2773.0MiB|2773.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1448.0MiB|1448.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2672.0MiB|2672.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3267.0MiB|3267.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |405.0MiB|405.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |290.0MiB|290.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2105.0MiB|2105.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5948.0MiB|5948.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |963.0MiB|963.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1303.0MiB|1303.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |261.0MiB|261.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |301.0MiB|301.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |623.0MiB|623.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |567.0MiB|567.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1084.0MiB|1084.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1036.0MiB|1036.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1216.0MiB|1216.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1323.0MiB|1323.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |362.0MiB|362.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1865.0MiB|1865.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2773.0MiB|2773.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1448.0MiB|1448.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2672.0MiB|2672.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3267.0MiB|3267.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |405.0MiB|405.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |290.0MiB|290.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2105.0MiB|2105.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5948.0MiB|5948.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |963.0MiB|963.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1303.0MiB|1303.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |261.0MiB|261.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |301.0MiB|301.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |623.0MiB|623.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |567.0MiB|567.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1084.0MiB|1084.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1036.0MiB|1036.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1216.0MiB|1216.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1323.0MiB|1323.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |362.0MiB|362.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1865.0MiB|1865.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2773.0MiB|2773.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1448.0MiB|1448.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2672.0MiB|2672.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3267.0MiB|3267.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |405.0MiB|405.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |290.0MiB|290.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2105.0MiB|2105.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5948.0MiB|5948.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |963.0MiB|963.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1303.0MiB|1303.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |261.0MiB|261.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |301.0MiB|301.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |623.0MiB|623.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |567.0MiB|567.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1084.0MiB|1084.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1036.0MiB|1036.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1216.0MiB|1216.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1323.0MiB|1323.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |362.0MiB|362.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1865.0MiB|1865.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2773.0MiB|2773.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1448.0MiB|1448.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2672.0MiB|2672.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3267.0MiB|3267.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |405.0MiB|405.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |290.0MiB|290.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2105.0MiB|2105.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5948.0MiB|5948.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |963.0MiB|963.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1303.0MiB|1303.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |261.0MiB|261.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |301.0MiB|301.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |623.0MiB|623.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |567.0MiB|567.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1084.0MiB|1084.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1036.0MiB|1036.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.482s |27.54GiB|
|scrambled14845.smt2                                                                        | 476.363s |5948.0MiB|
|scrambled41135.smt2                                                                        |1200.435s |4986.0MiB|
|scrambled73755.smt2                                                                        |1200.501s |4789.0MiB|
|scrambled87588.smt2                                                                        |1200.457s |3570.0MiB|
|scrambled82760.smt2                                                                        |1200.363s |3429.0MiB|
|scrambled122926.smt2                                                                       |1200.530s |3267.0MiB|
|scrambled108663.smt2                                                                       |1200.319s |2773.0MiB|
|scrambled12033.smt2                                                                        |1200.297s |2672.0MiB|
|scrambled91750.smt2                                                                        |1200.341s |2428.0MiB|
|scrambled62032.smt2                                                                        |1200.276s |2361.0MiB|
|scrambled47700.smt2                                                                        |1200.258s |2118.0MiB|
|scrambled130111.smt2                                                                       |1200.284s |2105.0MiB|
|scrambled73281.smt2                                                                        |1200.242s |1933.0MiB|
|scrambled108406.smt2                                                                       |1200.323s |1865.0MiB|
|scrambled39467.smt2                                                                        |1200.234s |1758.0MiB|
|scrambled58311.smt2                                                                        |1200.236s |1669.0MiB|
|scrambled97386.smt2                                                                        |1200.239s |1651.0MiB|
|scrambled79354.smt2                                                                        |1200.179s |1597.0MiB|
|scrambled8852.smt2                                                                         |1200.181s |1554.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.482s |27.54GiB|
|scrambled14845.smt2                                                                        | 476.363s |5948.0MiB|
|scrambled41135.smt2                                                                        |1200.435s |4986.0MiB|
|scrambled73755.smt2                                                                        |1200.501s |4789.0MiB|
|scrambled87588.smt2                                                                        |1200.457s |3570.0MiB|
|scrambled82760.smt2                                                                        |1200.363s |3429.0MiB|
|scrambled122926.smt2                                                                       |1200.530s |3267.0MiB|
|scrambled108663.smt2                                                                       |1200.319s |2773.0MiB|
|scrambled12033.smt2                                                                        |1200.297s |2672.0MiB|
|scrambled91750.smt2                                                                        |1200.341s |2428.0MiB|
|scrambled62032.smt2                                                                        |1200.276s |2361.0MiB|
|scrambled47700.smt2                                                                        |1200.258s |2118.0MiB|
|scrambled130111.smt2                                                                       |1200.284s |2105.0MiB|
|scrambled73281.smt2                                                                        |1200.242s |1933.0MiB|
|scrambled108406.smt2                                                                       |1200.323s |1865.0MiB|
|scrambled39467.smt2                                                                        |1200.234s |1758.0MiB|
|scrambled58311.smt2                                                                        |1200.236s |1669.0MiB|
|scrambled97386.smt2                                                                        |1200.239s |1651.0MiB|
|scrambled79354.smt2                                                                        |1200.179s |1597.0MiB|
|scrambled8852.smt2                                                                         |1200.181s |1554.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.168s  |1200.168s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  33.559s  |  33.559s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.297s  |1200.297s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.530s  |1200.530s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.635s  |  11.635s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  11.069s  |  11.069s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 476.363s  | 476.363s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.576s  |  13.576s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 245.944s  | 245.944s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.762s  |  21.762s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.917s  |   3.917s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 115.703s  | 115.703s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 542.796s  | 542.796s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.234s  |1200.234s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.435s  |1200.435s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.258s  |1200.258s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   5.469s  |   5.469s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.877s  |   0.877s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.236s  |1200.236s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 200.625s  | 200.625s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.242s  |1200.242s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.501s  |1200.501s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.179s  |1200.179s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         |  72.523s  |  72.523s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   5.868s  |   5.868s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.363s  |1200.363s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1202.482s  |1202.482s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.457s  |1200.457s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.341s  |1200.341s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   3.606s  |   3.606s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         | 450.188s  | 450.188s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.239s  |1200.239s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
</details>
