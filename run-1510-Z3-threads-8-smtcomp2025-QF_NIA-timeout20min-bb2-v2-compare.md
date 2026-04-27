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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-v2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 8184b34a0dabc65c893123172b120d0a65a3fd28
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.failed_literal_backbones=false smt_parallel.num_global_bb_chunking_threads=0"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: add continuous checking for new batch after first pass + continous loop behavior in the chunking algorithm

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-v2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 8184b34a0dabc65c893123172b120d0a65a3fd28
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.failed_literal_backbones=false smt_parallel.num_global_bb_chunking_threads=0"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: add continuous checking for new batch after first pass + continous loop behavior in the chunking algorithm

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  67.297s  |  67.297s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.574s  |1200.574s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.456s  |1200.456s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.176s  |1200.176s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.331s  |1200.331s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.407s  |1200.407s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.342s  |  10.342s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  15.619s  |  15.619s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 718.822s  | 718.822s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  43.098s  |  43.098s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 168.987s  | 168.987s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  27.163s  |  27.163s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.409s  |   4.409s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 139.861s  | 139.861s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.244s  |1200.244s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  67.297s  |  67.297s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.574s  |1200.574s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.456s  |1200.456s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.176s  |1200.176s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.331s  |1200.331s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.407s  |1200.407s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.342s  |  10.342s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  15.619s  |  15.619s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 718.822s  | 718.822s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  43.098s  |  43.098s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 168.987s  | 168.987s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  27.163s  |  27.163s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.409s  |   4.409s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 139.861s  | 139.861s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.244s  |1200.244s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  67.297s  |  67.297s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.574s  |1200.574s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.456s  |1200.456s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.176s  |1200.176s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.331s  |1200.331s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.407s  |1200.407s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.342s  |  10.342s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  15.619s  |  15.619s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 718.822s  | 718.822s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  43.098s  |  43.098s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 168.987s  | 168.987s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  27.163s  |  27.163s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.409s  |   4.409s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 139.861s  | 139.861s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.244s  |1200.244s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  67.297s  |  67.297s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.574s  |1200.574s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.456s  |1200.456s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.176s  |1200.176s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.331s  |1200.331s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.407s  |1200.407s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.342s  |  10.342s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  15.619s  |  15.619s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 718.822s  | 718.822s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  43.098s  |  43.098s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 168.987s  | 168.987s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  27.163s  |  27.163s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.409s  |   4.409s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 139.861s  | 139.861s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.244s  |1200.244s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.750s |24.429GiB|
|scrambled62032.smt2                                                                        |1202.111s |21.15GiB|
|scrambled73755.smt2                                                                        |1200.671s |4312.0MiB|
|scrambled108406.smt2                                                                       |1200.574s |4415.0MiB|
|scrambled82760.smt2                                                                        |1200.503s |3975.0MiB|
|scrambled108663.smt2                                                                       |1200.456s |4506.0MiB|
|scrambled91750.smt2                                                                        |1200.416s |2054.0MiB|
|scrambled122926.smt2                                                                       |1200.407s |2896.0MiB|
|scrambled12033.smt2                                                                        |1200.331s |2345.0MiB|
|scrambled130111.smt2                                                                       |1200.308s |1833.0MiB|
|scrambled47700.smt2                                                                        |1200.282s |2605.0MiB|
|scrambled97386.smt2                                                                        |1200.270s |1372.0MiB|
|scrambled87588.smt2                                                                        |1200.265s |1833.0MiB|
|scrambled73281.smt2                                                                        |1200.260s |1425.0MiB|
|scrambled96401.smt2                                                                        |1200.256s |1508.0MiB|
|scrambled36790.smt2                                                                        |1200.244s |1456.0MiB|
|scrambled9883.smt2                                                                         |1200.234s |1459.0MiB|
|scrambled38587.smt2                                                                        |1200.209s |1183.0MiB|
|scrambled79354.smt2                                                                        |1200.208s |1309.0MiB|
|scrambled39467.smt2                                                                        |1200.196s |1666.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.750s |24.429GiB|
|scrambled62032.smt2                                                                        |1202.111s |21.15GiB|
|scrambled73755.smt2                                                                        |1200.671s |4312.0MiB|
|scrambled108406.smt2                                                                       |1200.574s |4415.0MiB|
|scrambled82760.smt2                                                                        |1200.503s |3975.0MiB|
|scrambled108663.smt2                                                                       |1200.456s |4506.0MiB|
|scrambled91750.smt2                                                                        |1200.416s |2054.0MiB|
|scrambled122926.smt2                                                                       |1200.407s |2896.0MiB|
|scrambled12033.smt2                                                                        |1200.331s |2345.0MiB|
|scrambled130111.smt2                                                                       |1200.308s |1833.0MiB|
|scrambled47700.smt2                                                                        |1200.282s |2605.0MiB|
|scrambled97386.smt2                                                                        |1200.270s |1372.0MiB|
|scrambled87588.smt2                                                                        |1200.265s |1833.0MiB|
|scrambled73281.smt2                                                                        |1200.260s |1425.0MiB|
|scrambled96401.smt2                                                                        |1200.256s |1508.0MiB|
|scrambled36790.smt2                                                                        |1200.244s |1456.0MiB|
|scrambled9883.smt2                                                                         |1200.234s |1459.0MiB|
|scrambled38587.smt2                                                                        |1200.209s |1183.0MiB|
|scrambled79354.smt2                                                                        |1200.208s |1309.0MiB|
|scrambled39467.smt2                                                                        |1200.196s |1666.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1113.0MiB|1113.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1219.0MiB|1219.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |327.0MiB|327.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |4415.0MiB|4415.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |4506.0MiB|4506.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1266.0MiB|1266.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2345.0MiB|2345.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |2896.0MiB|2896.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |364.0MiB|364.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1833.0MiB|1833.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5514.0MiB|5514.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |972.0MiB|972.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1043.0MiB|1043.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |243.0MiB|243.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |274.0MiB|274.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |564.0MiB|564.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |570.0MiB|570.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |767.0MiB|767.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1456.0MiB|1456.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1113.0MiB|1113.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1219.0MiB|1219.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |327.0MiB|327.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |4415.0MiB|4415.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |4506.0MiB|4506.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1266.0MiB|1266.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2345.0MiB|2345.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |2896.0MiB|2896.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |364.0MiB|364.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1833.0MiB|1833.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5514.0MiB|5514.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |972.0MiB|972.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1043.0MiB|1043.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |243.0MiB|243.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |274.0MiB|274.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |564.0MiB|564.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |570.0MiB|570.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |767.0MiB|767.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1456.0MiB|1456.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1113.0MiB|1113.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1219.0MiB|1219.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |327.0MiB|327.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |4415.0MiB|4415.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |4506.0MiB|4506.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1266.0MiB|1266.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2345.0MiB|2345.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |2896.0MiB|2896.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |364.0MiB|364.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1833.0MiB|1833.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5514.0MiB|5514.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |972.0MiB|972.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1043.0MiB|1043.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |243.0MiB|243.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |274.0MiB|274.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |564.0MiB|564.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |570.0MiB|570.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |767.0MiB|767.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1456.0MiB|1456.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1113.0MiB|1113.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1219.0MiB|1219.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |327.0MiB|327.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |4415.0MiB|4415.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |4506.0MiB|4506.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1266.0MiB|1266.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2345.0MiB|2345.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |2896.0MiB|2896.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |364.0MiB|364.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1833.0MiB|1833.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5514.0MiB|5514.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |972.0MiB|972.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1043.0MiB|1043.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |243.0MiB|243.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |274.0MiB|274.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |564.0MiB|564.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |570.0MiB|570.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |767.0MiB|767.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1456.0MiB|1456.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.750s |24.429GiB|
|scrambled62032.smt2                                                                        |1202.111s |21.15GiB|
|scrambled14845.smt2                                                                        | 718.822s |5514.0MiB|
|scrambled108663.smt2                                                                       |1200.456s |4506.0MiB|
|scrambled108406.smt2                                                                       |1200.574s |4415.0MiB|
|scrambled73755.smt2                                                                        |1200.671s |4312.0MiB|
|scrambled82760.smt2                                                                        |1200.503s |3975.0MiB|
|scrambled122926.smt2                                                                       |1200.407s |2896.0MiB|
|scrambled47700.smt2                                                                        |1200.282s |2605.0MiB|
|scrambled12033.smt2                                                                        |1200.331s |2345.0MiB|
|scrambled91750.smt2                                                                        |1200.416s |2054.0MiB|
|scrambled130111.smt2                                                                       |1200.308s |1833.0MiB|
|scrambled87588.smt2                                                                        |1200.265s |1833.0MiB|
|scrambled58311.smt2                                                                        |1200.179s |1763.0MiB|
|scrambled39467.smt2                                                                        |1200.196s |1666.0MiB|
|scrambled96401.smt2                                                                        |1200.256s |1508.0MiB|
|scrambled9883.smt2                                                                         |1200.234s |1459.0MiB|
|scrambled36790.smt2                                                                        |1200.244s |1456.0MiB|
|scrambled73281.smt2                                                                        |1200.260s |1425.0MiB|
|scrambled97386.smt2                                                                        |1200.270s |1372.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.750s |24.429GiB|
|scrambled62032.smt2                                                                        |1202.111s |21.15GiB|
|scrambled14845.smt2                                                                        | 718.822s |5514.0MiB|
|scrambled108663.smt2                                                                       |1200.456s |4506.0MiB|
|scrambled108406.smt2                                                                       |1200.574s |4415.0MiB|
|scrambled73755.smt2                                                                        |1200.671s |4312.0MiB|
|scrambled82760.smt2                                                                        |1200.503s |3975.0MiB|
|scrambled122926.smt2                                                                       |1200.407s |2896.0MiB|
|scrambled47700.smt2                                                                        |1200.282s |2605.0MiB|
|scrambled12033.smt2                                                                        |1200.331s |2345.0MiB|
|scrambled91750.smt2                                                                        |1200.416s |2054.0MiB|
|scrambled130111.smt2                                                                       |1200.308s |1833.0MiB|
|scrambled87588.smt2                                                                        |1200.265s |1833.0MiB|
|scrambled58311.smt2                                                                        |1200.179s |1763.0MiB|
|scrambled39467.smt2                                                                        |1200.196s |1666.0MiB|
|scrambled96401.smt2                                                                        |1200.256s |1508.0MiB|
|scrambled9883.smt2                                                                         |1200.234s |1459.0MiB|
|scrambled36790.smt2                                                                        |1200.244s |1456.0MiB|
|scrambled73281.smt2                                                                        |1200.260s |1425.0MiB|
|scrambled97386.smt2                                                                        |1200.270s |1372.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  67.297s  |  67.297s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.574s  |1200.574s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.456s  |1200.456s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.176s  |1200.176s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.331s  |1200.331s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.407s  |1200.407s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.342s  |  10.342s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  15.619s  |  15.619s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 718.822s  | 718.822s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  43.098s  |  43.098s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 168.987s  | 168.987s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  27.163s  |  27.163s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.409s  |   4.409s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 139.861s  | 139.861s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.244s  |1200.244s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.209s  |1200.209s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.196s  |1200.196s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.282s  |1200.282s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   4.872s  |   4.872s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.925s  |   0.925s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.179s  |1200.179s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 141.722s  | 141.722s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1202.111s  |1202.111s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.260s  |1200.260s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.671s  |1200.671s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.208s  |1200.208s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 313.209s  | 313.209s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   5.955s  |   5.955s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.503s  |1200.503s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1202.750s  |1202.750s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.265s  |1200.265s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.416s  |1200.416s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   5.376s  |   5.376s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1200.256s  |1200.256s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.270s  |1200.270s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.152s  |1200.152s  |   0.000s  | 0.0%|
</details>
