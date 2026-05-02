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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: dd30b9eaf3624ea8d87e9e84ece5b50b171e5eda
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore incomplete-theory give-up paths

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: dd30b9eaf3624ea8d87e9e84ece5b50b171e5eda
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore incomplete-theory give-up paths

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  21.649s  |  21.649s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.501s  |1200.501s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.483s  |1200.483s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.234s  |1200.234s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.399s  |1200.399s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.831s  |   9.831s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  24.793s  |  24.793s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.263s  |1200.263s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 288.208s  | 288.208s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  33.030s  |  33.030s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  13.715s  |  13.715s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  32.604s  |  32.604s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.901s  |   3.901s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 139.768s  | 139.768s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.198s  |1200.198s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  21.649s  |  21.649s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.501s  |1200.501s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.483s  |1200.483s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.234s  |1200.234s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.399s  |1200.399s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.831s  |   9.831s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  24.793s  |  24.793s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.263s  |1200.263s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 288.208s  | 288.208s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  33.030s  |  33.030s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  13.715s  |  13.715s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  32.604s  |  32.604s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.901s  |   3.901s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 139.768s  | 139.768s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.198s  |1200.198s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  21.649s  |  21.649s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.501s  |1200.501s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.483s  |1200.483s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.234s  |1200.234s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.399s  |1200.399s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.831s  |   9.831s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  24.793s  |  24.793s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.263s  |1200.263s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 288.208s  | 288.208s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  33.030s  |  33.030s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  13.715s  |  13.715s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  32.604s  |  32.604s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.901s  |   3.901s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 139.768s  | 139.768s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.198s  |1200.198s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  21.649s  |  21.649s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.501s  |1200.501s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.483s  |1200.483s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.234s  |1200.234s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.399s  |1200.399s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.831s  |   9.831s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  24.793s  |  24.793s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.263s  |1200.263s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 288.208s  | 288.208s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  33.030s  |  33.030s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  13.715s  |  13.715s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  32.604s  |  32.604s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.901s  |   3.901s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 139.768s  | 139.768s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.198s  |1200.198s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.286s |26.545GiB|
|scrambled62032.smt2                                                                        |1201.344s |16.096GiB|
|scrambled47700.smt2                                                                        |1200.680s |5742.0MiB|
|scrambled73755.smt2                                                                        |1200.547s |5421.0MiB|
|scrambled108406.smt2                                                                       |1200.501s |2682.0MiB|
|scrambled108663.smt2                                                                       |1200.483s |2458.0MiB|
|scrambled122926.smt2                                                                       |1200.399s |3797.0MiB|
|scrambled91750.smt2                                                                        |1200.396s |2487.0MiB|
|scrambled12033.smt2                                                                        |1200.319s |2959.0MiB|
|scrambled87588.smt2                                                                        |1200.301s |2621.0MiB|
|scrambled82760.smt2                                                                        |1200.297s |2017.0MiB|
|scrambled97386.smt2                                                                        |1200.277s |1641.0MiB|
|scrambled130111.smt2                                                                       |1200.263s |1912.0MiB|
|scrambled119582.smt2                                                                       |1200.234s |1417.0MiB|
|scrambled41135.smt2                                                                        |1200.221s |2044.0MiB|
|scrambled79354.smt2                                                                        |1200.221s |1754.0MiB|
|scrambled36790.smt2                                                                        |1200.198s |1786.0MiB|
|scrambled38587.smt2                                                                        |1200.188s |1933.0MiB|
|scrambled73281.smt2                                                                        |1200.181s |1341.0MiB|
|scrambled98111.smt2                                                                        |1200.180s |1431.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.286s |26.545GiB|
|scrambled62032.smt2                                                                        |1201.344s |16.096GiB|
|scrambled47700.smt2                                                                        |1200.680s |5742.0MiB|
|scrambled73755.smt2                                                                        |1200.547s |5421.0MiB|
|scrambled108406.smt2                                                                       |1200.501s |2682.0MiB|
|scrambled108663.smt2                                                                       |1200.483s |2458.0MiB|
|scrambled122926.smt2                                                                       |1200.399s |3797.0MiB|
|scrambled91750.smt2                                                                        |1200.396s |2487.0MiB|
|scrambled12033.smt2                                                                        |1200.319s |2959.0MiB|
|scrambled87588.smt2                                                                        |1200.301s |2621.0MiB|
|scrambled82760.smt2                                                                        |1200.297s |2017.0MiB|
|scrambled97386.smt2                                                                        |1200.277s |1641.0MiB|
|scrambled130111.smt2                                                                       |1200.263s |1912.0MiB|
|scrambled119582.smt2                                                                       |1200.234s |1417.0MiB|
|scrambled41135.smt2                                                                        |1200.221s |2044.0MiB|
|scrambled79354.smt2                                                                        |1200.221s |1754.0MiB|
|scrambled36790.smt2                                                                        |1200.198s |1786.0MiB|
|scrambled38587.smt2                                                                        |1200.188s |1933.0MiB|
|scrambled73281.smt2                                                                        |1200.181s |1341.0MiB|
|scrambled98111.smt2                                                                        |1200.180s |1431.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |621.0MiB|621.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1396.0MiB|1396.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |356.0MiB|356.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2682.0MiB|2682.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2458.0MiB|2458.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1417.0MiB|1417.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2959.0MiB|2959.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3797.0MiB|3797.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |430.0MiB|430.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |456.0MiB|456.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1912.0MiB|1912.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6281.0MiB|6281.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1142.0MiB|1142.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |498.0MiB|498.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |314.0MiB|314.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |245.0MiB|245.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |698.0MiB|698.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |1210.0MiB|1210.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |916.0MiB|916.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1786.0MiB|1786.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |621.0MiB|621.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1396.0MiB|1396.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |356.0MiB|356.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2682.0MiB|2682.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2458.0MiB|2458.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1417.0MiB|1417.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2959.0MiB|2959.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3797.0MiB|3797.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |430.0MiB|430.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |456.0MiB|456.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1912.0MiB|1912.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6281.0MiB|6281.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1142.0MiB|1142.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |498.0MiB|498.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |314.0MiB|314.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |245.0MiB|245.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |698.0MiB|698.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |1210.0MiB|1210.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |916.0MiB|916.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1786.0MiB|1786.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |621.0MiB|621.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1396.0MiB|1396.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |356.0MiB|356.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2682.0MiB|2682.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2458.0MiB|2458.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1417.0MiB|1417.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2959.0MiB|2959.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3797.0MiB|3797.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |430.0MiB|430.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |456.0MiB|456.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1912.0MiB|1912.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6281.0MiB|6281.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1142.0MiB|1142.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |498.0MiB|498.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |314.0MiB|314.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |245.0MiB|245.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |698.0MiB|698.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |1210.0MiB|1210.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |916.0MiB|916.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1786.0MiB|1786.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |621.0MiB|621.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1396.0MiB|1396.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |356.0MiB|356.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2682.0MiB|2682.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2458.0MiB|2458.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1417.0MiB|1417.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2959.0MiB|2959.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3797.0MiB|3797.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |430.0MiB|430.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |456.0MiB|456.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1912.0MiB|1912.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6281.0MiB|6281.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1142.0MiB|1142.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |498.0MiB|498.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |314.0MiB|314.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |245.0MiB|245.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |698.0MiB|698.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |1210.0MiB|1210.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |916.0MiB|916.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1786.0MiB|1786.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.286s |26.545GiB|
|scrambled62032.smt2                                                                        |1201.344s |16.096GiB|
|scrambled14845.smt2                                                                        | 288.208s |6281.0MiB|
|scrambled47700.smt2                                                                        |1200.680s |5742.0MiB|
|scrambled73755.smt2                                                                        |1200.547s |5421.0MiB|
|scrambled122926.smt2                                                                       |1200.399s |3797.0MiB|
|scrambled12033.smt2                                                                        |1200.319s |2959.0MiB|
|scrambled108406.smt2                                                                       |1200.501s |2682.0MiB|
|scrambled87588.smt2                                                                        |1200.301s |2621.0MiB|
|scrambled91750.smt2                                                                        |1200.396s |2487.0MiB|
|scrambled108663.smt2                                                                       |1200.483s |2458.0MiB|
|scrambled41135.smt2                                                                        |1200.221s |2044.0MiB|
|scrambled82760.smt2                                                                        |1200.297s |2017.0MiB|
|scrambled38587.smt2                                                                        |1200.188s |1933.0MiB|
|scrambled130111.smt2                                                                       |1200.263s |1912.0MiB|
|scrambled36790.smt2                                                                        |1200.198s |1786.0MiB|
|scrambled79354.smt2                                                                        |1200.221s |1754.0MiB|
|scrambled8852.smt2                                                                         |1200.152s |1738.0MiB|
|scrambled80288.smt2                                                                        | 236.296s |1710.0MiB|
|scrambled97386.smt2                                                                        |1200.277s |1641.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.286s |26.545GiB|
|scrambled62032.smt2                                                                        |1201.344s |16.096GiB|
|scrambled14845.smt2                                                                        | 288.208s |6281.0MiB|
|scrambled47700.smt2                                                                        |1200.680s |5742.0MiB|
|scrambled73755.smt2                                                                        |1200.547s |5421.0MiB|
|scrambled122926.smt2                                                                       |1200.399s |3797.0MiB|
|scrambled12033.smt2                                                                        |1200.319s |2959.0MiB|
|scrambled108406.smt2                                                                       |1200.501s |2682.0MiB|
|scrambled87588.smt2                                                                        |1200.301s |2621.0MiB|
|scrambled91750.smt2                                                                        |1200.396s |2487.0MiB|
|scrambled108663.smt2                                                                       |1200.483s |2458.0MiB|
|scrambled41135.smt2                                                                        |1200.221s |2044.0MiB|
|scrambled82760.smt2                                                                        |1200.297s |2017.0MiB|
|scrambled38587.smt2                                                                        |1200.188s |1933.0MiB|
|scrambled130111.smt2                                                                       |1200.263s |1912.0MiB|
|scrambled36790.smt2                                                                        |1200.198s |1786.0MiB|
|scrambled79354.smt2                                                                        |1200.221s |1754.0MiB|
|scrambled8852.smt2                                                                         |1200.152s |1738.0MiB|
|scrambled80288.smt2                                                                        | 236.296s |1710.0MiB|
|scrambled97386.smt2                                                                        |1200.277s |1641.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  21.649s  |  21.649s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.501s  |1200.501s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.483s  |1200.483s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.234s  |1200.234s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.399s  |1200.399s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.831s  |   9.831s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  24.793s  |  24.793s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.263s  |1200.263s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 288.208s  | 288.208s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  33.030s  |  33.030s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  13.715s  |  13.715s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  32.604s  |  32.604s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.901s  |   3.901s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 139.768s  | 139.768s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.198s  |1200.198s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.188s  |1200.188s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.221s  |1200.221s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.680s  |1200.680s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   8.061s  |   8.061s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.149s  |1200.149s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 145.785s  | 145.785s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1201.344s  |1201.344s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.547s  |1200.547s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.221s  |1200.221s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 236.296s  | 236.296s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   5.407s  |   5.407s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.297s  |1200.297s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1202.286s  |1202.286s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.301s  |1200.301s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.396s  |1200.396s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   4.252s  |   4.252s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         | 229.376s  | 229.376s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.277s  |1200.277s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
</details>
