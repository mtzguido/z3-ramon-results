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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: dd30b9eaf3624ea8d87e9e84ece5b50b171e5eda
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore incomplete-theory give-up paths

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: dd30b9eaf3624ea8d87e9e84ece5b50b171e5eda
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore incomplete-theory give-up paths

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  46.316s  |  46.316s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.719s  |1200.719s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.496s  |1200.496s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.179s  |1200.179s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.405s  |1200.405s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.545s  |  10.545s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  13.345s  |  13.345s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 396.891s  | 396.891s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.976s  |  13.976s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  50.528s  |  50.528s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  22.145s  |  22.145s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.380s  |   4.380s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 288.295s  | 288.295s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 508.795s  | 508.795s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  46.316s  |  46.316s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.719s  |1200.719s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.496s  |1200.496s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.179s  |1200.179s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.405s  |1200.405s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.545s  |  10.545s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  13.345s  |  13.345s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 396.891s  | 396.891s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.976s  |  13.976s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  50.528s  |  50.528s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  22.145s  |  22.145s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.380s  |   4.380s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 288.295s  | 288.295s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 508.795s  | 508.795s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  46.316s  |  46.316s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.719s  |1200.719s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.496s  |1200.496s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.179s  |1200.179s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.405s  |1200.405s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.545s  |  10.545s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  13.345s  |  13.345s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 396.891s  | 396.891s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.976s  |  13.976s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  50.528s  |  50.528s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  22.145s  |  22.145s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.380s  |   4.380s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 288.295s  | 288.295s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 508.795s  | 508.795s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  46.316s  |  46.316s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.719s  |1200.719s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.496s  |1200.496s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.179s  |1200.179s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.405s  |1200.405s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.545s  |  10.545s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  13.345s  |  13.345s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 396.891s  | 396.891s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.976s  |  13.976s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  50.528s  |  50.528s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  22.145s  |  22.145s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.380s  |   4.380s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 288.295s  | 288.295s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 508.795s  | 508.795s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.871s |32.054GiB|
|scrambled108406.smt2                                                                       |1200.719s |6491.0MiB|
|scrambled73755.smt2                                                                        |1200.642s |5151.0MiB|
|scrambled47700.smt2                                                                        |1200.508s |3590.0MiB|
|scrambled108663.smt2                                                                       |1200.496s |4334.0MiB|
|scrambled87588.smt2                                                                        |1200.422s |3522.0MiB|
|scrambled62032.smt2                                                                        |1200.415s |3363.0MiB|
|scrambled91750.smt2                                                                        |1200.412s |2924.0MiB|
|scrambled122926.smt2                                                                       |1200.405s |3608.0MiB|
|scrambled82760.smt2                                                                        |1200.334s |2547.0MiB|
|scrambled12033.smt2                                                                        |1200.323s |2933.0MiB|
|scrambled130111.smt2                                                                       |1200.276s |2031.0MiB|
|scrambled97386.smt2                                                                        |1200.271s |1758.0MiB|
|scrambled9883.smt2                                                                         |1200.244s |1614.0MiB|
|scrambled73281.smt2                                                                        |1200.231s |1737.0MiB|
|scrambled96401.smt2                                                                        |1200.225s |1386.0MiB|
|scrambled39467.smt2                                                                        |1200.222s |2273.0MiB|
|scrambled41135.smt2                                                                        |1200.213s |2543.0MiB|
|scrambled98111.smt2                                                                        |1200.210s |1566.0MiB|
|scrambled38587.smt2                                                                        |1200.209s |1405.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.871s |32.054GiB|
|scrambled108406.smt2                                                                       |1200.719s |6491.0MiB|
|scrambled73755.smt2                                                                        |1200.642s |5151.0MiB|
|scrambled47700.smt2                                                                        |1200.508s |3590.0MiB|
|scrambled108663.smt2                                                                       |1200.496s |4334.0MiB|
|scrambled87588.smt2                                                                        |1200.422s |3522.0MiB|
|scrambled62032.smt2                                                                        |1200.415s |3363.0MiB|
|scrambled91750.smt2                                                                        |1200.412s |2924.0MiB|
|scrambled122926.smt2                                                                       |1200.405s |3608.0MiB|
|scrambled82760.smt2                                                                        |1200.334s |2547.0MiB|
|scrambled12033.smt2                                                                        |1200.323s |2933.0MiB|
|scrambled130111.smt2                                                                       |1200.276s |2031.0MiB|
|scrambled97386.smt2                                                                        |1200.271s |1758.0MiB|
|scrambled9883.smt2                                                                         |1200.244s |1614.0MiB|
|scrambled73281.smt2                                                                        |1200.231s |1737.0MiB|
|scrambled96401.smt2                                                                        |1200.225s |1386.0MiB|
|scrambled39467.smt2                                                                        |1200.222s |2273.0MiB|
|scrambled41135.smt2                                                                        |1200.213s |2543.0MiB|
|scrambled98111.smt2                                                                        |1200.210s |1566.0MiB|
|scrambled38587.smt2                                                                        |1200.209s |1405.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1267.0MiB|1267.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1506.0MiB|1506.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |414.0MiB|414.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |6491.0MiB|6491.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |4334.0MiB|4334.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1275.0MiB|1275.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2933.0MiB|2933.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3608.0MiB|3608.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |450.0MiB|450.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2031.0MiB|2031.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6543.0MiB|6543.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1063.0MiB|1063.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |762.0MiB|762.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |286.0MiB|286.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |262.0MiB|262.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |924.0MiB|924.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |886.0MiB|886.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1125.0MiB|1125.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1267.0MiB|1267.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1506.0MiB|1506.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |414.0MiB|414.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |6491.0MiB|6491.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |4334.0MiB|4334.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1275.0MiB|1275.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2933.0MiB|2933.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3608.0MiB|3608.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |450.0MiB|450.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2031.0MiB|2031.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6543.0MiB|6543.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1063.0MiB|1063.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |762.0MiB|762.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |286.0MiB|286.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |262.0MiB|262.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |924.0MiB|924.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |886.0MiB|886.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1125.0MiB|1125.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1267.0MiB|1267.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1506.0MiB|1506.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |414.0MiB|414.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |6491.0MiB|6491.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |4334.0MiB|4334.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1275.0MiB|1275.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2933.0MiB|2933.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3608.0MiB|3608.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |450.0MiB|450.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2031.0MiB|2031.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6543.0MiB|6543.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1063.0MiB|1063.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |762.0MiB|762.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |286.0MiB|286.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |262.0MiB|262.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |924.0MiB|924.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |886.0MiB|886.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1125.0MiB|1125.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1267.0MiB|1267.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1506.0MiB|1506.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |414.0MiB|414.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |6491.0MiB|6491.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |4334.0MiB|4334.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1275.0MiB|1275.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2933.0MiB|2933.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3608.0MiB|3608.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |450.0MiB|450.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2031.0MiB|2031.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6543.0MiB|6543.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1063.0MiB|1063.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |762.0MiB|762.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |286.0MiB|286.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |262.0MiB|262.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |924.0MiB|924.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |886.0MiB|886.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1125.0MiB|1125.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.871s |32.054GiB|
|scrambled14845.smt2                                                                        | 396.891s |6543.0MiB|
|scrambled108406.smt2                                                                       |1200.719s |6491.0MiB|
|scrambled73755.smt2                                                                        |1200.642s |5151.0MiB|
|scrambled108663.smt2                                                                       |1200.496s |4334.0MiB|
|scrambled122926.smt2                                                                       |1200.405s |3608.0MiB|
|scrambled47700.smt2                                                                        |1200.508s |3590.0MiB|
|scrambled87588.smt2                                                                        |1200.422s |3522.0MiB|
|scrambled62032.smt2                                                                        |1200.415s |3363.0MiB|
|scrambled12033.smt2                                                                        |1200.323s |2933.0MiB|
|scrambled91750.smt2                                                                        |1200.412s |2924.0MiB|
|scrambled8852.smt2                                                                         |1200.206s |2596.0MiB|
|scrambled82760.smt2                                                                        |1200.334s |2547.0MiB|
|scrambled41135.smt2                                                                        |1200.213s |2543.0MiB|
|scrambled39467.smt2                                                                        |1200.222s |2273.0MiB|
|scrambled130111.smt2                                                                       |1200.276s |2031.0MiB|
|scrambled97386.smt2                                                                        |1200.271s |1758.0MiB|
|scrambled61060.smt2                                                                        | 248.778s |1756.0MiB|
|scrambled73281.smt2                                                                        |1200.231s |1737.0MiB|
|scrambled9883.smt2                                                                         |1200.244s |1614.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.871s |32.054GiB|
|scrambled14845.smt2                                                                        | 396.891s |6543.0MiB|
|scrambled108406.smt2                                                                       |1200.719s |6491.0MiB|
|scrambled73755.smt2                                                                        |1200.642s |5151.0MiB|
|scrambled108663.smt2                                                                       |1200.496s |4334.0MiB|
|scrambled122926.smt2                                                                       |1200.405s |3608.0MiB|
|scrambled47700.smt2                                                                        |1200.508s |3590.0MiB|
|scrambled87588.smt2                                                                        |1200.422s |3522.0MiB|
|scrambled62032.smt2                                                                        |1200.415s |3363.0MiB|
|scrambled12033.smt2                                                                        |1200.323s |2933.0MiB|
|scrambled91750.smt2                                                                        |1200.412s |2924.0MiB|
|scrambled8852.smt2                                                                         |1200.206s |2596.0MiB|
|scrambled82760.smt2                                                                        |1200.334s |2547.0MiB|
|scrambled41135.smt2                                                                        |1200.213s |2543.0MiB|
|scrambled39467.smt2                                                                        |1200.222s |2273.0MiB|
|scrambled130111.smt2                                                                       |1200.276s |2031.0MiB|
|scrambled97386.smt2                                                                        |1200.271s |1758.0MiB|
|scrambled61060.smt2                                                                        | 248.778s |1756.0MiB|
|scrambled73281.smt2                                                                        |1200.231s |1737.0MiB|
|scrambled9883.smt2                                                                         |1200.244s |1614.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  46.316s  |  46.316s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.719s  |1200.719s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.496s  |1200.496s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.179s  |1200.179s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.405s  |1200.405s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.545s  |  10.545s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  13.345s  |  13.345s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 396.891s  | 396.891s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.976s  |  13.976s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  50.528s  |  50.528s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  22.145s  |  22.145s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.380s  |   4.380s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 288.295s  | 288.295s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 508.795s  | 508.795s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.209s  |1200.209s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.222s  |1200.222s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.213s  |1200.213s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.508s  |1200.508s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   5.524s  |   5.524s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.883s  |   0.883s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.130s  |1200.130s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 248.778s  | 248.778s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.415s  |1200.415s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.231s  |1200.231s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.642s  |1200.642s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.208s  |1200.208s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 300.403s  | 300.403s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   6.206s  |   6.206s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.334s  |1200.334s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1202.871s  |1202.871s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.422s  |1200.422s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.206s  |1200.206s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.412s  |1200.412s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   6.438s  |   6.438s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1200.225s  |1200.225s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.271s  |1200.271s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.210s  |1200.210s  |   0.000s  | 0.0%|
</details>
