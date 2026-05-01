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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-ablate
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: ae632291327d6cc0ccd360d0d267ddd7b28f703e
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: ablate

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-ablate
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: ae632291327d6cc0ccd360d0d267ddd7b28f703e
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: ablate

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  39.433s  |  39.433s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.345s  |1200.345s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.537s  |1200.537s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.154s  |1200.154s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.283s  |1200.283s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.383s  |1200.383s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.007s  |  11.007s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  17.090s  |  17.090s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.293s  |1200.293s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 709.270s  | 709.270s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  17.636s  |  17.636s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   3.493s  |   3.493s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  19.014s  |  19.014s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.302s  |   4.302s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1051.165s  |1051.165s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.233s  |1200.233s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  39.433s  |  39.433s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.345s  |1200.345s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.537s  |1200.537s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.154s  |1200.154s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.283s  |1200.283s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.383s  |1200.383s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.007s  |  11.007s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  17.090s  |  17.090s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.293s  |1200.293s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 709.270s  | 709.270s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  17.636s  |  17.636s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   3.493s  |   3.493s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  19.014s  |  19.014s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.302s  |   4.302s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1051.165s  |1051.165s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.233s  |1200.233s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  39.433s  |  39.433s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.345s  |1200.345s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.537s  |1200.537s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.154s  |1200.154s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.283s  |1200.283s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.383s  |1200.383s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.007s  |  11.007s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  17.090s  |  17.090s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.293s  |1200.293s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 709.270s  | 709.270s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  17.636s  |  17.636s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   3.493s  |   3.493s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  19.014s  |  19.014s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.302s  |   4.302s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1051.165s  |1051.165s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.233s  |1200.233s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  39.433s  |  39.433s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.345s  |1200.345s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.537s  |1200.537s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.154s  |1200.154s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.283s  |1200.283s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.383s  |1200.383s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.007s  |  11.007s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  17.090s  |  17.090s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.293s  |1200.293s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 709.270s  | 709.270s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  17.636s  |  17.636s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   3.493s  |   3.493s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  19.014s  |  19.014s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.302s  |   4.302s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1051.165s  |1051.165s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.233s  |1200.233s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.458s |27.862GiB|
|scrambled87588.smt2                                                                        |1201.666s |19.451GiB|
|scrambled41135.smt2                                                                        |1200.871s |10.194GiB|
|scrambled73755.smt2                                                                        |1200.541s |5276.0MiB|
|scrambled108663.smt2                                                                       |1200.537s |5199.0MiB|
|scrambled39467.smt2                                                                        |1200.442s |2768.0MiB|
|scrambled122926.smt2                                                                       |1200.383s |3640.0MiB|
|scrambled47700.smt2                                                                        |1200.359s |2775.0MiB|
|scrambled108406.smt2                                                                       |1200.345s |3234.0MiB|
|scrambled91750.smt2                                                                        |1200.340s |2541.0MiB|
|scrambled58311.smt2                                                                        |1200.332s |3069.0MiB|
|scrambled130111.smt2                                                                       |1200.293s |1916.0MiB|
|scrambled79354.smt2                                                                        |1200.284s |1779.0MiB|
|scrambled12033.smt2                                                                        |1200.283s |2922.0MiB|
|scrambled62032.smt2                                                                        |1200.266s |1844.0MiB|
|scrambled73281.smt2                                                                        |1200.248s |1629.0MiB|
|scrambled82760.smt2                                                                        |1200.242s |1851.0MiB|
|scrambled36790.smt2                                                                        |1200.233s |1819.0MiB|
|scrambled9883.smt2                                                                         |1200.226s |1364.0MiB|
|scrambled38587.smt2                                                                        |1200.172s |1449.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.458s |27.862GiB|
|scrambled87588.smt2                                                                        |1201.666s |19.451GiB|
|scrambled41135.smt2                                                                        |1200.871s |10.194GiB|
|scrambled73755.smt2                                                                        |1200.541s |5276.0MiB|
|scrambled108663.smt2                                                                       |1200.537s |5199.0MiB|
|scrambled39467.smt2                                                                        |1200.442s |2768.0MiB|
|scrambled122926.smt2                                                                       |1200.383s |3640.0MiB|
|scrambled47700.smt2                                                                        |1200.359s |2775.0MiB|
|scrambled108406.smt2                                                                       |1200.345s |3234.0MiB|
|scrambled91750.smt2                                                                        |1200.340s |2541.0MiB|
|scrambled58311.smt2                                                                        |1200.332s |3069.0MiB|
|scrambled130111.smt2                                                                       |1200.293s |1916.0MiB|
|scrambled79354.smt2                                                                        |1200.284s |1779.0MiB|
|scrambled12033.smt2                                                                        |1200.283s |2922.0MiB|
|scrambled62032.smt2                                                                        |1200.266s |1844.0MiB|
|scrambled73281.smt2                                                                        |1200.248s |1629.0MiB|
|scrambled82760.smt2                                                                        |1200.242s |1851.0MiB|
|scrambled36790.smt2                                                                        |1200.233s |1819.0MiB|
|scrambled9883.smt2                                                                         |1200.226s |1364.0MiB|
|scrambled38587.smt2                                                                        |1200.172s |1449.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1253.0MiB|1253.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1371.0MiB|1371.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |366.0MiB|366.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |3234.0MiB|3234.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |5199.0MiB|5199.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1471.0MiB|1471.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2922.0MiB|2922.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3640.0MiB|3640.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |443.0MiB|443.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |405.0MiB|405.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1916.0MiB|1916.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6691.0MiB|6691.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1090.0MiB|1090.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |299.0MiB|299.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |250.0MiB|250.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |2058.0MiB|2058.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |777.0MiB|777.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1819.0MiB|1819.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1253.0MiB|1253.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1371.0MiB|1371.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |366.0MiB|366.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |3234.0MiB|3234.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |5199.0MiB|5199.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1471.0MiB|1471.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2922.0MiB|2922.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3640.0MiB|3640.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |443.0MiB|443.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |405.0MiB|405.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1916.0MiB|1916.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6691.0MiB|6691.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1090.0MiB|1090.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |299.0MiB|299.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |250.0MiB|250.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |2058.0MiB|2058.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |777.0MiB|777.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1819.0MiB|1819.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1253.0MiB|1253.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1371.0MiB|1371.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |366.0MiB|366.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |3234.0MiB|3234.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |5199.0MiB|5199.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1471.0MiB|1471.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2922.0MiB|2922.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3640.0MiB|3640.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |443.0MiB|443.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |405.0MiB|405.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1916.0MiB|1916.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6691.0MiB|6691.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1090.0MiB|1090.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |299.0MiB|299.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |250.0MiB|250.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |2058.0MiB|2058.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |777.0MiB|777.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1819.0MiB|1819.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1253.0MiB|1253.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1371.0MiB|1371.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |366.0MiB|366.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |3234.0MiB|3234.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |5199.0MiB|5199.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1471.0MiB|1471.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2922.0MiB|2922.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3640.0MiB|3640.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |443.0MiB|443.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |405.0MiB|405.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1916.0MiB|1916.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6691.0MiB|6691.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1090.0MiB|1090.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |299.0MiB|299.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |250.0MiB|250.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |2058.0MiB|2058.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |777.0MiB|777.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1819.0MiB|1819.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.458s |27.862GiB|
|scrambled87588.smt2                                                                        |1201.666s |19.451GiB|
|scrambled41135.smt2                                                                        |1200.871s |10.194GiB|
|scrambled14845.smt2                                                                        | 709.270s |6691.0MiB|
|scrambled73755.smt2                                                                        |1200.541s |5276.0MiB|
|scrambled108663.smt2                                                                       |1200.537s |5199.0MiB|
|scrambled122926.smt2                                                                       |1200.383s |3640.0MiB|
|scrambled108406.smt2                                                                       |1200.345s |3234.0MiB|
|scrambled58311.smt2                                                                        |1200.332s |3069.0MiB|
|scrambled12033.smt2                                                                        |1200.283s |2922.0MiB|
|scrambled47700.smt2                                                                        |1200.359s |2775.0MiB|
|scrambled39467.smt2                                                                        |1200.442s |2768.0MiB|
|scrambled91750.smt2                                                                        |1200.340s |2541.0MiB|
|scrambled31071.smt2                                                                        |1051.165s |2058.0MiB|
|scrambled130111.smt2                                                                       |1200.293s |1916.0MiB|
|scrambled82760.smt2                                                                        |1200.242s |1851.0MiB|
|scrambled62032.smt2                                                                        |1200.266s |1844.0MiB|
|scrambled36790.smt2                                                                        |1200.233s |1819.0MiB|
|scrambled79354.smt2                                                                        |1200.284s |1779.0MiB|
|scrambled97386.smt2                                                                        |1200.165s |1728.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.458s |27.862GiB|
|scrambled87588.smt2                                                                        |1201.666s |19.451GiB|
|scrambled41135.smt2                                                                        |1200.871s |10.194GiB|
|scrambled14845.smt2                                                                        | 709.270s |6691.0MiB|
|scrambled73755.smt2                                                                        |1200.541s |5276.0MiB|
|scrambled108663.smt2                                                                       |1200.537s |5199.0MiB|
|scrambled122926.smt2                                                                       |1200.383s |3640.0MiB|
|scrambled108406.smt2                                                                       |1200.345s |3234.0MiB|
|scrambled58311.smt2                                                                        |1200.332s |3069.0MiB|
|scrambled12033.smt2                                                                        |1200.283s |2922.0MiB|
|scrambled47700.smt2                                                                        |1200.359s |2775.0MiB|
|scrambled39467.smt2                                                                        |1200.442s |2768.0MiB|
|scrambled91750.smt2                                                                        |1200.340s |2541.0MiB|
|scrambled31071.smt2                                                                        |1051.165s |2058.0MiB|
|scrambled130111.smt2                                                                       |1200.293s |1916.0MiB|
|scrambled82760.smt2                                                                        |1200.242s |1851.0MiB|
|scrambled62032.smt2                                                                        |1200.266s |1844.0MiB|
|scrambled36790.smt2                                                                        |1200.233s |1819.0MiB|
|scrambled79354.smt2                                                                        |1200.284s |1779.0MiB|
|scrambled97386.smt2                                                                        |1200.165s |1728.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  39.433s  |  39.433s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.345s  |1200.345s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.537s  |1200.537s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.154s  |1200.154s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.283s  |1200.283s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.383s  |1200.383s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.007s  |  11.007s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  17.090s  |  17.090s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.293s  |1200.293s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 709.270s  | 709.270s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  17.636s  |  17.636s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   3.493s  |   3.493s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  19.014s  |  19.014s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.302s  |   4.302s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1051.165s  |1051.165s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.233s  |1200.233s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.442s  |1200.442s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.871s  |1200.871s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.359s  |1200.359s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   5.534s  |   5.534s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.887s  |   0.887s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.332s  |1200.332s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 213.577s  | 213.577s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.266s  |1200.266s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.248s  |1200.248s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.541s  |1200.541s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 677.735s  | 677.735s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   5.985s  |   5.985s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.242s  |1200.242s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1202.458s  |1202.458s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1201.666s  |1201.666s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.149s  |1200.149s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.340s  |1200.340s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   4.351s  |   4.351s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         | 199.866s  | 199.866s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.165s  |1200.165s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.171s  |1200.171s  |   0.000s  | 0.0%|
</details>
