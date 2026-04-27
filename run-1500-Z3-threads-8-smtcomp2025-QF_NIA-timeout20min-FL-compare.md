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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-FL
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 4e9e3413ec6d3ed78d31f91f5c563e3531e9b393
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.failed_literal_backbones=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore old changes

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-FL
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 4e9e3413ec6d3ed78d31f91f5c563e3531e9b393
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.failed_literal_backbones=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore old changes

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.170s  |1200.170s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.224s  |1200.224s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  33.036s  |  33.036s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.485s  |1200.485s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.331s  |1200.331s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.570s  |1200.570s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.241s  |   9.241s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  18.242s  |  18.242s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.245s  |1200.245s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 513.242s  | 513.242s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  61.350s  |  61.350s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 110.019s  | 110.019s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  23.431s  |  23.431s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.371s  |   4.371s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 550.450s  | 550.450s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.216s  |1200.216s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.170s  |1200.170s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.224s  |1200.224s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  33.036s  |  33.036s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.485s  |1200.485s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.331s  |1200.331s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.570s  |1200.570s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.241s  |   9.241s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  18.242s  |  18.242s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.245s  |1200.245s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 513.242s  | 513.242s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  61.350s  |  61.350s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 110.019s  | 110.019s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  23.431s  |  23.431s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.371s  |   4.371s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 550.450s  | 550.450s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.216s  |1200.216s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.170s  |1200.170s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.224s  |1200.224s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  33.036s  |  33.036s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.485s  |1200.485s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.331s  |1200.331s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.570s  |1200.570s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.241s  |   9.241s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  18.242s  |  18.242s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.245s  |1200.245s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 513.242s  | 513.242s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  61.350s  |  61.350s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 110.019s  | 110.019s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  23.431s  |  23.431s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.371s  |   4.371s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 550.450s  | 550.450s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.216s  |1200.216s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.170s  |1200.170s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.224s  |1200.224s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  33.036s  |  33.036s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.485s  |1200.485s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.331s  |1200.331s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.570s  |1200.570s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.241s  |   9.241s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  18.242s  |  18.242s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.245s  |1200.245s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 513.242s  | 513.242s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  61.350s  |  61.350s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 110.019s  | 110.019s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  23.431s  |  23.431s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.371s  |   4.371s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 550.450s  | 550.450s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.216s  |1200.216s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.097s |23.439GiB|
|scrambled73755.smt2                                                                        |1200.705s |4791.0MiB|
|scrambled122926.smt2                                                                       |1200.570s |3348.0MiB|
|scrambled108663.smt2                                                                       |1200.485s |3766.0MiB|
|scrambled91750.smt2                                                                        |1200.437s |2422.0MiB|
|scrambled47700.smt2                                                                        |1200.403s |3006.0MiB|
|scrambled62032.smt2                                                                        |1200.356s |2353.0MiB|
|scrambled82760.smt2                                                                        |1200.353s |1940.0MiB|
|scrambled12033.smt2                                                                        |1200.331s |2627.0MiB|
|scrambled39467.smt2                                                                        |1200.322s |1749.0MiB|
|scrambled108406.smt2                                                                       |1200.308s |2501.0MiB|
|scrambled87588.smt2                                                                        |1200.279s |1948.0MiB|
|scrambled73281.smt2                                                                        |1200.260s |1657.0MiB|
|scrambled130111.smt2                                                                       |1200.245s |1737.0MiB|
|scrambled97386.smt2                                                                        |1200.231s |1565.0MiB|
|scrambled8852.smt2                                                                         |1200.229s |1708.0MiB|
|scrambled79354.smt2                                                                        |1200.227s |1613.0MiB|
|scrambled101716.smt2                                                                       |1200.224s |1294.0MiB|
|scrambled98111.smt2                                                                        |1200.223s |1282.0MiB|
|scrambled36790.smt2                                                                        |1200.216s |1756.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.097s |23.439GiB|
|scrambled73755.smt2                                                                        |1200.705s |4791.0MiB|
|scrambled122926.smt2                                                                       |1200.570s |3348.0MiB|
|scrambled108663.smt2                                                                       |1200.485s |3766.0MiB|
|scrambled91750.smt2                                                                        |1200.437s |2422.0MiB|
|scrambled47700.smt2                                                                        |1200.403s |3006.0MiB|
|scrambled62032.smt2                                                                        |1200.356s |2353.0MiB|
|scrambled82760.smt2                                                                        |1200.353s |1940.0MiB|
|scrambled12033.smt2                                                                        |1200.331s |2627.0MiB|
|scrambled39467.smt2                                                                        |1200.322s |1749.0MiB|
|scrambled108406.smt2                                                                       |1200.308s |2501.0MiB|
|scrambled87588.smt2                                                                        |1200.279s |1948.0MiB|
|scrambled73281.smt2                                                                        |1200.260s |1657.0MiB|
|scrambled130111.smt2                                                                       |1200.245s |1737.0MiB|
|scrambled97386.smt2                                                                        |1200.231s |1565.0MiB|
|scrambled8852.smt2                                                                         |1200.229s |1708.0MiB|
|scrambled79354.smt2                                                                        |1200.227s |1613.0MiB|
|scrambled101716.smt2                                                                       |1200.224s |1294.0MiB|
|scrambled98111.smt2                                                                        |1200.223s |1282.0MiB|
|scrambled36790.smt2                                                                        |1200.216s |1756.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1234.0MiB|1234.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1294.0MiB|1294.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |344.0MiB|344.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2501.0MiB|2501.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3766.0MiB|3766.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1358.0MiB|1358.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2627.0MiB|2627.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3348.0MiB|3348.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |409.0MiB|409.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |391.0MiB|391.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1737.0MiB|1737.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6050.0MiB|6050.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1167.0MiB|1167.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |922.0MiB|922.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |233.0MiB|233.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |1160.0MiB|1160.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |568.0MiB|568.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1023.0MiB|1023.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1756.0MiB|1756.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1234.0MiB|1234.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1294.0MiB|1294.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |344.0MiB|344.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2501.0MiB|2501.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3766.0MiB|3766.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1358.0MiB|1358.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2627.0MiB|2627.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3348.0MiB|3348.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |409.0MiB|409.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |391.0MiB|391.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1737.0MiB|1737.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6050.0MiB|6050.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1167.0MiB|1167.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |922.0MiB|922.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |233.0MiB|233.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |1160.0MiB|1160.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |568.0MiB|568.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1023.0MiB|1023.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1756.0MiB|1756.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1234.0MiB|1234.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1294.0MiB|1294.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |344.0MiB|344.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2501.0MiB|2501.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3766.0MiB|3766.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1358.0MiB|1358.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2627.0MiB|2627.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3348.0MiB|3348.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |409.0MiB|409.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |391.0MiB|391.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1737.0MiB|1737.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6050.0MiB|6050.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1167.0MiB|1167.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |922.0MiB|922.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |233.0MiB|233.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |1160.0MiB|1160.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |568.0MiB|568.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1023.0MiB|1023.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1756.0MiB|1756.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1234.0MiB|1234.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1294.0MiB|1294.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |344.0MiB|344.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2501.0MiB|2501.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3766.0MiB|3766.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1358.0MiB|1358.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2627.0MiB|2627.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3348.0MiB|3348.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |409.0MiB|409.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |391.0MiB|391.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1737.0MiB|1737.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6050.0MiB|6050.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1167.0MiB|1167.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |922.0MiB|922.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |233.0MiB|233.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |1160.0MiB|1160.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |568.0MiB|568.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1023.0MiB|1023.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1756.0MiB|1756.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.097s |23.439GiB|
|scrambled14845.smt2                                                                        | 513.242s |6050.0MiB|
|scrambled73755.smt2                                                                        |1200.705s |4791.0MiB|
|scrambled108663.smt2                                                                       |1200.485s |3766.0MiB|
|scrambled122926.smt2                                                                       |1200.570s |3348.0MiB|
|scrambled47700.smt2                                                                        |1200.403s |3006.0MiB|
|scrambled12033.smt2                                                                        |1200.331s |2627.0MiB|
|scrambled108406.smt2                                                                       |1200.308s |2501.0MiB|
|scrambled91750.smt2                                                                        |1200.437s |2422.0MiB|
|scrambled62032.smt2                                                                        |1200.356s |2353.0MiB|
|scrambled87588.smt2                                                                        |1200.279s |1948.0MiB|
|scrambled82760.smt2                                                                        |1200.353s |1940.0MiB|
|scrambled36790.smt2                                                                        |1200.216s |1756.0MiB|
|scrambled39467.smt2                                                                        |1200.322s |1749.0MiB|
|scrambled130111.smt2                                                                       |1200.245s |1737.0MiB|
|scrambled8852.smt2                                                                         |1200.229s |1708.0MiB|
|scrambled73281.smt2                                                                        |1200.260s |1657.0MiB|
|scrambled79354.smt2                                                                        |1200.227s |1613.0MiB|
|scrambled97386.smt2                                                                        |1200.231s |1565.0MiB|
|scrambled61060.smt2                                                                        | 156.564s |1482.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.097s |23.439GiB|
|scrambled14845.smt2                                                                        | 513.242s |6050.0MiB|
|scrambled73755.smt2                                                                        |1200.705s |4791.0MiB|
|scrambled108663.smt2                                                                       |1200.485s |3766.0MiB|
|scrambled122926.smt2                                                                       |1200.570s |3348.0MiB|
|scrambled47700.smt2                                                                        |1200.403s |3006.0MiB|
|scrambled12033.smt2                                                                        |1200.331s |2627.0MiB|
|scrambled108406.smt2                                                                       |1200.308s |2501.0MiB|
|scrambled91750.smt2                                                                        |1200.437s |2422.0MiB|
|scrambled62032.smt2                                                                        |1200.356s |2353.0MiB|
|scrambled87588.smt2                                                                        |1200.279s |1948.0MiB|
|scrambled82760.smt2                                                                        |1200.353s |1940.0MiB|
|scrambled36790.smt2                                                                        |1200.216s |1756.0MiB|
|scrambled39467.smt2                                                                        |1200.322s |1749.0MiB|
|scrambled130111.smt2                                                                       |1200.245s |1737.0MiB|
|scrambled8852.smt2                                                                         |1200.229s |1708.0MiB|
|scrambled73281.smt2                                                                        |1200.260s |1657.0MiB|
|scrambled79354.smt2                                                                        |1200.227s |1613.0MiB|
|scrambled97386.smt2                                                                        |1200.231s |1565.0MiB|
|scrambled61060.smt2                                                                        | 156.564s |1482.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.170s  |1200.170s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.224s  |1200.224s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  33.036s  |  33.036s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.485s  |1200.485s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.331s  |1200.331s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.570s  |1200.570s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.241s  |   9.241s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  18.242s  |  18.242s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.245s  |1200.245s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 513.242s  | 513.242s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  61.350s  |  61.350s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 110.019s  | 110.019s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  23.431s  |  23.431s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.371s  |   4.371s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 550.450s  | 550.450s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.216s  |1200.216s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.193s  |1200.193s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.322s  |1200.322s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.175s  |1200.175s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.403s  |1200.403s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   4.794s  |   4.794s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.969s  |   0.969s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.149s  |1200.149s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 156.564s  | 156.564s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.356s  |1200.356s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.260s  |1200.260s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.705s  |1200.705s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.227s  |1200.227s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 351.480s  | 351.480s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   5.914s  |   5.914s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.353s  |1200.353s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1203.097s  |1203.097s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.279s  |1200.279s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.229s  |1200.229s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.437s  |1200.437s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   3.452s  |   3.452s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1155.154s  |1155.154s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.231s  |1200.231s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.223s  |1200.223s  |   0.000s  | 0.0%|
</details>
