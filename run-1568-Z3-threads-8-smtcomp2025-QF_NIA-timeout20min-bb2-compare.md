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
Z3 commit: bca74f00c9880bf41a61b573a3854e32fbc01120
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: ablate sharing non-worker units

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bca74f00c9880bf41a61b573a3854e32fbc01120
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: ablate sharing non-worker units

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.173s  |1200.173s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  44.035s  |  44.035s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.608s  |1200.608s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.470s  |1200.470s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.322s  |1200.322s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.543s  |1200.543s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.258s  |  12.258s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  15.443s  |  15.443s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 491.272s  | 491.272s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.603s  |  14.603s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  27.871s  |  27.871s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  31.866s  |  31.866s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.096s  |   4.096s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  85.885s  |  85.885s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.197s  |1200.197s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.173s  |1200.173s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  44.035s  |  44.035s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.608s  |1200.608s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.470s  |1200.470s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.322s  |1200.322s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.543s  |1200.543s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.258s  |  12.258s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  15.443s  |  15.443s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 491.272s  | 491.272s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.603s  |  14.603s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  27.871s  |  27.871s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  31.866s  |  31.866s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.096s  |   4.096s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  85.885s  |  85.885s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.197s  |1200.197s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.173s  |1200.173s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  44.035s  |  44.035s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.608s  |1200.608s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.470s  |1200.470s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.322s  |1200.322s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.543s  |1200.543s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.258s  |  12.258s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  15.443s  |  15.443s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 491.272s  | 491.272s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.603s  |  14.603s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  27.871s  |  27.871s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  31.866s  |  31.866s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.096s  |   4.096s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  85.885s  |  85.885s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.197s  |1200.197s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.173s  |1200.173s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  44.035s  |  44.035s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.608s  |1200.608s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.470s  |1200.470s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.322s  |1200.322s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.543s  |1200.543s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.258s  |  12.258s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  15.443s  |  15.443s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 491.272s  | 491.272s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.603s  |  14.603s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  27.871s  |  27.871s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  31.866s  |  31.866s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.096s  |   4.096s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  85.885s  |  85.885s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.197s  |1200.197s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.325s |26.766GiB|
|scrambled108406.smt2                                                                       |1200.608s |5977.0MiB|
|scrambled73755.smt2                                                                        |1200.545s |5171.0MiB|
|scrambled122926.smt2                                                                       |1200.543s |3617.0MiB|
|scrambled108663.smt2                                                                       |1200.470s |3835.0MiB|
|scrambled39467.smt2                                                                        |1200.417s |2766.0MiB|
|scrambled91750.smt2                                                                        |1200.385s |2574.0MiB|
|scrambled62032.smt2                                                                        |1200.378s |3880.0MiB|
|scrambled47700.smt2                                                                        |1200.330s |2474.0MiB|
|scrambled12033.smt2                                                                        |1200.322s |2944.0MiB|
|scrambled87588.smt2                                                                        |1200.308s |2539.0MiB|
|scrambled130111.smt2                                                                       |1200.284s |1861.0MiB|
|scrambled73281.smt2                                                                        |1200.265s |2469.0MiB|
|scrambled98111.smt2                                                                        |1200.239s |1584.0MiB|
|scrambled79354.smt2                                                                        |1200.222s |1723.0MiB|
|scrambled38587.smt2                                                                        |1200.210s |1882.0MiB|
|scrambled36790.smt2                                                                        |1200.197s |1763.0MiB|
|scrambled97386.smt2                                                                        |1200.195s |1718.0MiB|
|scrambled82760.smt2                                                                        |1200.192s |1492.0MiB|
|scrambled96401.smt2                                                                        |1200.187s |1523.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.325s |26.766GiB|
|scrambled108406.smt2                                                                       |1200.608s |5977.0MiB|
|scrambled73755.smt2                                                                        |1200.545s |5171.0MiB|
|scrambled122926.smt2                                                                       |1200.543s |3617.0MiB|
|scrambled108663.smt2                                                                       |1200.470s |3835.0MiB|
|scrambled39467.smt2                                                                        |1200.417s |2766.0MiB|
|scrambled91750.smt2                                                                        |1200.385s |2574.0MiB|
|scrambled62032.smt2                                                                        |1200.378s |3880.0MiB|
|scrambled47700.smt2                                                                        |1200.330s |2474.0MiB|
|scrambled12033.smt2                                                                        |1200.322s |2944.0MiB|
|scrambled87588.smt2                                                                        |1200.308s |2539.0MiB|
|scrambled130111.smt2                                                                       |1200.284s |1861.0MiB|
|scrambled73281.smt2                                                                        |1200.265s |2469.0MiB|
|scrambled98111.smt2                                                                        |1200.239s |1584.0MiB|
|scrambled79354.smt2                                                                        |1200.222s |1723.0MiB|
|scrambled38587.smt2                                                                        |1200.210s |1882.0MiB|
|scrambled36790.smt2                                                                        |1200.197s |1763.0MiB|
|scrambled97386.smt2                                                                        |1200.195s |1718.0MiB|
|scrambled82760.smt2                                                                        |1200.192s |1492.0MiB|
|scrambled96401.smt2                                                                        |1200.187s |1523.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1246.0MiB|1246.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1403.0MiB|1403.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |392.0MiB|392.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |5977.0MiB|5977.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3835.0MiB|3835.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1390.0MiB|1390.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2944.0MiB|2944.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3617.0MiB|3617.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |443.0MiB|443.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |398.0MiB|398.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1861.0MiB|1861.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6591.0MiB|6591.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1063.0MiB|1063.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |744.0MiB|744.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |299.0MiB|299.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |251.0MiB|251.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |635.0MiB|635.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |932.0MiB|932.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1763.0MiB|1763.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1246.0MiB|1246.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1403.0MiB|1403.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |392.0MiB|392.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |5977.0MiB|5977.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3835.0MiB|3835.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1390.0MiB|1390.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2944.0MiB|2944.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3617.0MiB|3617.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |443.0MiB|443.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |398.0MiB|398.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1861.0MiB|1861.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6591.0MiB|6591.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1063.0MiB|1063.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |744.0MiB|744.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |299.0MiB|299.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |251.0MiB|251.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |635.0MiB|635.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |932.0MiB|932.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1763.0MiB|1763.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1246.0MiB|1246.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1403.0MiB|1403.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |392.0MiB|392.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |5977.0MiB|5977.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3835.0MiB|3835.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1390.0MiB|1390.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2944.0MiB|2944.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3617.0MiB|3617.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |443.0MiB|443.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |398.0MiB|398.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1861.0MiB|1861.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6591.0MiB|6591.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1063.0MiB|1063.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |744.0MiB|744.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |299.0MiB|299.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |251.0MiB|251.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |635.0MiB|635.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |932.0MiB|932.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1763.0MiB|1763.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1246.0MiB|1246.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1403.0MiB|1403.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |392.0MiB|392.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |5977.0MiB|5977.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3835.0MiB|3835.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1390.0MiB|1390.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2944.0MiB|2944.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3617.0MiB|3617.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |443.0MiB|443.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |398.0MiB|398.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1861.0MiB|1861.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6591.0MiB|6591.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1063.0MiB|1063.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |744.0MiB|744.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |299.0MiB|299.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |251.0MiB|251.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |635.0MiB|635.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |932.0MiB|932.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1763.0MiB|1763.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.325s |26.766GiB|
|scrambled14845.smt2                                                                        | 491.272s |6591.0MiB|
|scrambled108406.smt2                                                                       |1200.608s |5977.0MiB|
|scrambled73755.smt2                                                                        |1200.545s |5171.0MiB|
|scrambled62032.smt2                                                                        |1200.378s |3880.0MiB|
|scrambled108663.smt2                                                                       |1200.470s |3835.0MiB|
|scrambled122926.smt2                                                                       |1200.543s |3617.0MiB|
|scrambled12033.smt2                                                                        |1200.322s |2944.0MiB|
|scrambled39467.smt2                                                                        |1200.417s |2766.0MiB|
|scrambled91750.smt2                                                                        |1200.385s |2574.0MiB|
|scrambled87588.smt2                                                                        |1200.308s |2539.0MiB|
|scrambled47700.smt2                                                                        |1200.330s |2474.0MiB|
|scrambled73281.smt2                                                                        |1200.265s |2469.0MiB|
|scrambled38587.smt2                                                                        |1200.210s |1882.0MiB|
|scrambled130111.smt2                                                                       |1200.284s |1861.0MiB|
|scrambled36790.smt2                                                                        |1200.197s |1763.0MiB|
|scrambled79354.smt2                                                                        |1200.222s |1723.0MiB|
|scrambled97386.smt2                                                                        |1200.195s |1718.0MiB|
|scrambled61060.smt2                                                                        | 200.361s |1657.0MiB|
|scrambled98111.smt2                                                                        |1200.239s |1584.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.325s |26.766GiB|
|scrambled14845.smt2                                                                        | 491.272s |6591.0MiB|
|scrambled108406.smt2                                                                       |1200.608s |5977.0MiB|
|scrambled73755.smt2                                                                        |1200.545s |5171.0MiB|
|scrambled62032.smt2                                                                        |1200.378s |3880.0MiB|
|scrambled108663.smt2                                                                       |1200.470s |3835.0MiB|
|scrambled122926.smt2                                                                       |1200.543s |3617.0MiB|
|scrambled12033.smt2                                                                        |1200.322s |2944.0MiB|
|scrambled39467.smt2                                                                        |1200.417s |2766.0MiB|
|scrambled91750.smt2                                                                        |1200.385s |2574.0MiB|
|scrambled87588.smt2                                                                        |1200.308s |2539.0MiB|
|scrambled47700.smt2                                                                        |1200.330s |2474.0MiB|
|scrambled73281.smt2                                                                        |1200.265s |2469.0MiB|
|scrambled38587.smt2                                                                        |1200.210s |1882.0MiB|
|scrambled130111.smt2                                                                       |1200.284s |1861.0MiB|
|scrambled36790.smt2                                                                        |1200.197s |1763.0MiB|
|scrambled79354.smt2                                                                        |1200.222s |1723.0MiB|
|scrambled97386.smt2                                                                        |1200.195s |1718.0MiB|
|scrambled61060.smt2                                                                        | 200.361s |1657.0MiB|
|scrambled98111.smt2                                                                        |1200.239s |1584.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.173s  |1200.173s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  44.035s  |  44.035s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.608s  |1200.608s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.470s  |1200.470s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.322s  |1200.322s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.543s  |1200.543s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.258s  |  12.258s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  15.443s  |  15.443s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 491.272s  | 491.272s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.603s  |  14.603s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  27.871s  |  27.871s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  31.866s  |  31.866s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.096s  |   4.096s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  85.885s  |  85.885s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.210s  |1200.210s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.417s  |1200.417s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.173s  |1200.173s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.330s  |1200.330s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   5.233s  |   5.233s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.925s  |   0.925s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 200.361s  | 200.361s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.378s  |1200.378s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.265s  |1200.265s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.545s  |1200.545s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.222s  |1200.222s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 359.137s  | 359.137s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   5.772s  |   5.772s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.192s  |1200.192s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1202.325s  |1202.325s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.173s  |1200.173s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.385s  |1200.385s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   5.180s  |   5.180s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.239s  |1200.239s  |   0.000s  | 0.0%|
</details>
