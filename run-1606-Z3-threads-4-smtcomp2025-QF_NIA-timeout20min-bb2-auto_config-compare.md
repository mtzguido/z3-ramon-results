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
Job tag: Z3-threads-4-smtcomp2025-QF_NIA-timeout20min-bb2-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: dd30b9eaf3624ea8d87e9e84ece5b50b171e5eda
Z3 branch: core_min
Z3 options: "-T:60 -v:0 smt.threads=4 tactic.default_tactic=smt smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore incomplete-theory give-up paths

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-smtcomp2025-QF_NIA-timeout20min-bb2-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: dd30b9eaf3624ea8d87e9e84ece5b50b171e5eda
Z3 branch: core_min
Z3 options: "-T:60 -v:0 smt.threads=4 tactic.default_tactic=smt smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore incomplete-theory give-up paths

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |  60.039s  |  60.039s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |  60.085s  |  60.085s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  40.866s  |  40.866s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |  60.081s  |  60.081s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |  60.092s  |  60.092s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |  60.261s  |  60.261s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |  60.163s  |  60.163s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   8.448s  |   8.448s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  22.756s  |  22.756s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |  60.110s  |  60.110s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |  60.467s  |  60.467s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.863s  |  14.863s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  41.125s  |  41.125s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  40.083s  |  40.083s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   5.262s  |   5.262s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |  60.041s  |  60.041s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |  60.044s  |  60.044s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |  60.091s  |  60.091s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |  60.039s  |  60.039s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |  60.085s  |  60.085s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  40.866s  |  40.866s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |  60.081s  |  60.081s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |  60.092s  |  60.092s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |  60.261s  |  60.261s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |  60.163s  |  60.163s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   8.448s  |   8.448s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  22.756s  |  22.756s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |  60.110s  |  60.110s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |  60.467s  |  60.467s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.863s  |  14.863s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  41.125s  |  41.125s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  40.083s  |  40.083s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   5.262s  |   5.262s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |  60.041s  |  60.041s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |  60.044s  |  60.044s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |  60.091s  |  60.091s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |  60.039s  |  60.039s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |  60.085s  |  60.085s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  40.866s  |  40.866s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |  60.081s  |  60.081s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |  60.092s  |  60.092s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |  60.261s  |  60.261s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |  60.163s  |  60.163s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   8.448s  |   8.448s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  22.756s  |  22.756s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |  60.110s  |  60.110s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |  60.467s  |  60.467s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.863s  |  14.863s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  41.125s  |  41.125s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  40.083s  |  40.083s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   5.262s  |   5.262s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |  60.041s  |  60.041s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |  60.044s  |  60.044s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |  60.091s  |  60.091s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |  60.039s  |  60.039s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |  60.085s  |  60.085s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  40.866s  |  40.866s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |  60.081s  |  60.081s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |  60.092s  |  60.092s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |  60.261s  |  60.261s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |  60.163s  |  60.163s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   8.448s  |   8.448s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  22.756s  |  22.756s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |  60.110s  |  60.110s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |  60.467s  |  60.467s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.863s  |  14.863s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  41.125s  |  41.125s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  40.083s  |  40.083s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   5.262s  |   5.262s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |  60.041s  |  60.041s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |  60.044s  |  60.044s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |  60.091s  |  60.091s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |  60.835s |6687.0MiB|
|scrambled14845.smt2                                                                        |  60.467s |3732.0MiB|
|scrambled73755.smt2                                                                        |  60.438s |2400.0MiB|
|scrambled12033.smt2                                                                        |  60.261s |1383.0MiB|
|scrambled91750.smt2                                                                        |  60.166s |675.0MiB|
|scrambled62032.smt2                                                                        |  60.163s |666.0MiB|
|scrambled122926.smt2                                                                       |  60.163s |971.0MiB|
|scrambled61060.smt2                                                                        |  60.152s |863.0MiB|
|scrambled41135.smt2                                                                        |  60.148s |638.0MiB|
|scrambled58311.smt2                                                                        |  60.135s |586.0MiB|
|scrambled82760.smt2                                                                        |  60.133s |523.0MiB|
|scrambled80288.smt2                                                                        |  60.133s |525.0MiB|
|scrambled87588.smt2                                                                        |  60.133s |325.0MiB|
|scrambled9883.smt2                                                                         |  60.129s |557.0MiB|
|scrambled97386.smt2                                                                        |  60.129s |602.0MiB|
|scrambled47700.smt2                                                                        |  60.122s |479.0MiB|
|scrambled8852.smt2                                                                         |  60.111s |451.0MiB|
|scrambled130111.smt2                                                                       |  60.110s |560.0MiB|
|scrambled31071.smt2                                                                        |  60.101s |354.0MiB|
|scrambled108663.smt2                                                                       |  60.101s |548.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |  60.835s |6687.0MiB|
|scrambled14845.smt2                                                                        |  60.467s |3732.0MiB|
|scrambled73755.smt2                                                                        |  60.438s |2400.0MiB|
|scrambled12033.smt2                                                                        |  60.261s |1383.0MiB|
|scrambled91750.smt2                                                                        |  60.166s |675.0MiB|
|scrambled62032.smt2                                                                        |  60.163s |666.0MiB|
|scrambled122926.smt2                                                                       |  60.163s |971.0MiB|
|scrambled61060.smt2                                                                        |  60.152s |863.0MiB|
|scrambled41135.smt2                                                                        |  60.148s |638.0MiB|
|scrambled58311.smt2                                                                        |  60.135s |586.0MiB|
|scrambled82760.smt2                                                                        |  60.133s |523.0MiB|
|scrambled80288.smt2                                                                        |  60.133s |525.0MiB|
|scrambled87588.smt2                                                                        |  60.133s |325.0MiB|
|scrambled9883.smt2                                                                         |  60.129s |557.0MiB|
|scrambled97386.smt2                                                                        |  60.129s |602.0MiB|
|scrambled47700.smt2                                                                        |  60.122s |479.0MiB|
|scrambled8852.smt2                                                                         |  60.111s |451.0MiB|
|scrambled130111.smt2                                                                       |  60.110s |560.0MiB|
|scrambled31071.smt2                                                                        |  60.101s |354.0MiB|
|scrambled108663.smt2                                                                       |  60.101s |548.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |169.0MiB|169.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |368.0MiB|368.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |280.0MiB|280.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |351.0MiB|351.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |548.0MiB|548.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |384.0MiB|384.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |1383.0MiB|1383.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |971.0MiB|971.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |288.0MiB|288.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |282.0MiB|282.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |560.0MiB|560.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |3732.0MiB|3732.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |685.0MiB|685.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |472.0MiB|472.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |199.0MiB|199.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |189.0MiB|189.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |225.0MiB|225.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |450.0MiB|450.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |169.0MiB|169.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |368.0MiB|368.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |280.0MiB|280.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |351.0MiB|351.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |548.0MiB|548.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |384.0MiB|384.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |1383.0MiB|1383.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |971.0MiB|971.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |288.0MiB|288.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |282.0MiB|282.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |560.0MiB|560.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |3732.0MiB|3732.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |685.0MiB|685.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |472.0MiB|472.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |199.0MiB|199.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |189.0MiB|189.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |225.0MiB|225.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |450.0MiB|450.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |169.0MiB|169.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |368.0MiB|368.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |280.0MiB|280.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |351.0MiB|351.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |548.0MiB|548.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |384.0MiB|384.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |1383.0MiB|1383.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |971.0MiB|971.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |288.0MiB|288.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |282.0MiB|282.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |560.0MiB|560.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |3732.0MiB|3732.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |685.0MiB|685.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |472.0MiB|472.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |199.0MiB|199.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |189.0MiB|189.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |225.0MiB|225.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |450.0MiB|450.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |169.0MiB|169.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |368.0MiB|368.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |280.0MiB|280.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |351.0MiB|351.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |548.0MiB|548.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |384.0MiB|384.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |1383.0MiB|1383.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |971.0MiB|971.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |288.0MiB|288.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |282.0MiB|282.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |560.0MiB|560.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |3732.0MiB|3732.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |685.0MiB|685.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |472.0MiB|472.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |199.0MiB|199.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |189.0MiB|189.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |225.0MiB|225.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |450.0MiB|450.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |  60.835s |6687.0MiB|
|scrambled14845.smt2                                                                        |  60.467s |3732.0MiB|
|scrambled73755.smt2                                                                        |  60.438s |2400.0MiB|
|scrambled12033.smt2                                                                        |  60.261s |1383.0MiB|
|scrambled122926.smt2                                                                       |  60.163s |971.0MiB|
|scrambled48569.smt2                                                                        |   7.013s |896.0MiB|
|scrambled61060.smt2                                                                        |  60.152s |863.0MiB|
|scrambled17293.smt2                                                                        |  14.863s |685.0MiB|
|scrambled91750.smt2                                                                        |  60.166s |675.0MiB|
|scrambled62032.smt2                                                                        |  60.163s |666.0MiB|
|scrambled41135.smt2                                                                        |  60.148s |638.0MiB|
|scrambled97386.smt2                                                                        |  60.129s |602.0MiB|
|scrambled58311.smt2                                                                        |  60.135s |586.0MiB|
|scrambled130111.smt2                                                                       |  60.110s |560.0MiB|
|scrambled9883.smt2                                                                         |  60.129s |557.0MiB|
|scrambled108663.smt2                                                                       |  60.101s |548.0MiB|
|scrambled80288.smt2                                                                        |  60.133s |525.0MiB|
|scrambled82760.smt2                                                                        |  60.133s |523.0MiB|
|scrambled47700.smt2                                                                        |  60.122s |479.0MiB|
|scrambled28176.smt2                                                                        |  41.125s |472.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |  60.835s |6687.0MiB|
|scrambled14845.smt2                                                                        |  60.467s |3732.0MiB|
|scrambled73755.smt2                                                                        |  60.438s |2400.0MiB|
|scrambled12033.smt2                                                                        |  60.261s |1383.0MiB|
|scrambled122926.smt2                                                                       |  60.163s |971.0MiB|
|scrambled48569.smt2                                                                        |   7.013s |896.0MiB|
|scrambled61060.smt2                                                                        |  60.152s |863.0MiB|
|scrambled17293.smt2                                                                        |  14.863s |685.0MiB|
|scrambled91750.smt2                                                                        |  60.166s |675.0MiB|
|scrambled62032.smt2                                                                        |  60.163s |666.0MiB|
|scrambled41135.smt2                                                                        |  60.148s |638.0MiB|
|scrambled97386.smt2                                                                        |  60.129s |602.0MiB|
|scrambled58311.smt2                                                                        |  60.135s |586.0MiB|
|scrambled130111.smt2                                                                       |  60.110s |560.0MiB|
|scrambled9883.smt2                                                                         |  60.129s |557.0MiB|
|scrambled108663.smt2                                                                       |  60.101s |548.0MiB|
|scrambled80288.smt2                                                                        |  60.133s |525.0MiB|
|scrambled82760.smt2                                                                        |  60.133s |523.0MiB|
|scrambled47700.smt2                                                                        |  60.122s |479.0MiB|
|scrambled28176.smt2                                                                        |  41.125s |472.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |  60.039s  |  60.039s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |  60.085s  |  60.085s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  40.866s  |  40.866s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |  60.081s  |  60.081s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |  60.092s  |  60.092s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |  60.261s  |  60.261s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |  60.163s  |  60.163s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   8.448s  |   8.448s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  22.756s  |  22.756s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |  60.110s  |  60.110s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |  60.467s  |  60.467s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.863s  |  14.863s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  41.125s  |  41.125s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  40.083s  |  40.083s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   5.262s  |   5.262s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |  60.041s  |  60.041s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |  60.044s  |  60.044s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |  60.091s  |  60.091s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |  60.074s  |  60.074s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |  60.035s  |  60.035s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |  60.148s  |  60.148s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |  60.122s  |  60.122s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   7.013s  |   7.013s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.846s  |   0.846s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |  60.135s  |  60.135s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         |  60.152s  |  60.152s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |  60.163s  |  60.163s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |  60.074s  |  60.074s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |  60.438s  |  60.438s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |  60.092s  |  60.092s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         |  60.133s  |  60.133s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   5.387s  |   5.387s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |  60.133s  |  60.133s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |  60.835s  |  60.835s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |  60.133s  |  60.133s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |  60.111s  |  60.111s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |  60.166s  |  60.166s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   6.799s  |   6.799s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |  60.081s  |  60.081s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |  60.129s  |  60.129s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |  60.049s  |  60.049s  |   0.000s  | 0.0%|
</details>
