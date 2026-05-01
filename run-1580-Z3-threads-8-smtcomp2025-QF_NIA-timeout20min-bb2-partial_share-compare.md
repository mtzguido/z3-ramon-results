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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-partial_share
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6045ce393fc70dffef4ebb7a9ce331b9ce5095c6
Z3 branch: 6045ce393fc70dffef4ebb7a9ce331b9ce5095c6
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: change share units ordering

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-partial_share
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6045ce393fc70dffef4ebb7a9ce331b9ce5095c6
Z3 branch: 6045ce393fc70dffef4ebb7a9ce331b9ce5095c6
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: change share units ordering

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  26.619s  |  26.619s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.327s  |1200.327s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.361s  |1200.361s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.301s  |1200.301s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.387s  |1200.387s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.439s  |  10.439s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  17.588s  |  17.588s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.369s  |1200.369s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 615.201s  | 615.201s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  16.384s  |  16.384s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 259.225s  | 259.225s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  20.712s  |  20.712s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.293s  |   4.293s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  56.776s  |  56.776s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.214s  |1200.214s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  26.619s  |  26.619s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.327s  |1200.327s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.361s  |1200.361s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.301s  |1200.301s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.387s  |1200.387s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.439s  |  10.439s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  17.588s  |  17.588s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.369s  |1200.369s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 615.201s  | 615.201s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  16.384s  |  16.384s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 259.225s  | 259.225s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  20.712s  |  20.712s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.293s  |   4.293s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  56.776s  |  56.776s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.214s  |1200.214s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  26.619s  |  26.619s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.327s  |1200.327s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.361s  |1200.361s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.301s  |1200.301s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.387s  |1200.387s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.439s  |  10.439s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  17.588s  |  17.588s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.369s  |1200.369s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 615.201s  | 615.201s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  16.384s  |  16.384s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 259.225s  | 259.225s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  20.712s  |  20.712s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.293s  |   4.293s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  56.776s  |  56.776s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.214s  |1200.214s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  26.619s  |  26.619s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.327s  |1200.327s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.361s  |1200.361s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.301s  |1200.301s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.387s  |1200.387s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.439s  |  10.439s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  17.588s  |  17.588s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.369s  |1200.369s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 615.201s  | 615.201s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  16.384s  |  16.384s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 259.225s  | 259.225s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  20.712s  |  20.712s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.293s  |   4.293s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  56.776s  |  56.776s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.214s  |1200.214s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.818s |33.043GiB|
|scrambled73755.smt2                                                                        |1200.592s |5096.0MiB|
|scrambled47700.smt2                                                                        |1200.549s |5463.0MiB|
|scrambled87588.smt2                                                                        |1200.449s |3146.0MiB|
|scrambled122926.smt2                                                                       |1200.387s |3668.0MiB|
|scrambled130111.smt2                                                                       |1200.369s |2193.0MiB|
|scrambled108663.smt2                                                                       |1200.361s |3017.0MiB|
|scrambled79354.smt2                                                                        |1200.345s |1807.0MiB|
|scrambled82760.smt2                                                                        |1200.336s |3291.0MiB|
|scrambled108406.smt2                                                                       |1200.327s |2479.0MiB|
|scrambled12033.smt2                                                                        |1200.301s |2952.0MiB|
|scrambled91750.smt2                                                                        |1200.284s |2729.0MiB|
|scrambled62032.smt2                                                                        |1200.275s |2908.0MiB|
|scrambled73281.smt2                                                                        |1200.268s |2212.0MiB|
|scrambled39467.smt2                                                                        |1200.241s |2283.0MiB|
|scrambled97386.smt2                                                                        |1200.240s |1590.0MiB|
|scrambled36790.smt2                                                                        |1200.214s |1758.0MiB|
|scrambled9883.smt2                                                                         |1200.201s |1311.0MiB|
|scrambled41135.smt2                                                                        |1200.180s |1872.0MiB|
|scrambled98111.smt2                                                                        |1200.177s |1582.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.818s |33.043GiB|
|scrambled73755.smt2                                                                        |1200.592s |5096.0MiB|
|scrambled47700.smt2                                                                        |1200.549s |5463.0MiB|
|scrambled87588.smt2                                                                        |1200.449s |3146.0MiB|
|scrambled122926.smt2                                                                       |1200.387s |3668.0MiB|
|scrambled130111.smt2                                                                       |1200.369s |2193.0MiB|
|scrambled108663.smt2                                                                       |1200.361s |3017.0MiB|
|scrambled79354.smt2                                                                        |1200.345s |1807.0MiB|
|scrambled82760.smt2                                                                        |1200.336s |3291.0MiB|
|scrambled108406.smt2                                                                       |1200.327s |2479.0MiB|
|scrambled12033.smt2                                                                        |1200.301s |2952.0MiB|
|scrambled91750.smt2                                                                        |1200.284s |2729.0MiB|
|scrambled62032.smt2                                                                        |1200.275s |2908.0MiB|
|scrambled73281.smt2                                                                        |1200.268s |2212.0MiB|
|scrambled39467.smt2                                                                        |1200.241s |2283.0MiB|
|scrambled97386.smt2                                                                        |1200.240s |1590.0MiB|
|scrambled36790.smt2                                                                        |1200.214s |1758.0MiB|
|scrambled9883.smt2                                                                         |1200.201s |1311.0MiB|
|scrambled41135.smt2                                                                        |1200.180s |1872.0MiB|
|scrambled98111.smt2                                                                        |1200.177s |1582.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1252.0MiB|1252.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1492.0MiB|1492.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |348.0MiB|348.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2479.0MiB|2479.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3017.0MiB|3017.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1439.0MiB|1439.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2952.0MiB|2952.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3668.0MiB|3668.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |438.0MiB|438.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |440.0MiB|440.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2193.0MiB|2193.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6659.0MiB|6659.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1072.0MiB|1072.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1347.0MiB|1347.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |286.0MiB|286.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |244.0MiB|244.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |979.0MiB|979.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1758.0MiB|1758.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1252.0MiB|1252.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1492.0MiB|1492.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |348.0MiB|348.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2479.0MiB|2479.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3017.0MiB|3017.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1439.0MiB|1439.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2952.0MiB|2952.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3668.0MiB|3668.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |438.0MiB|438.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |440.0MiB|440.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2193.0MiB|2193.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6659.0MiB|6659.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1072.0MiB|1072.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1347.0MiB|1347.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |286.0MiB|286.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |244.0MiB|244.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |979.0MiB|979.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1758.0MiB|1758.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1252.0MiB|1252.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1492.0MiB|1492.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |348.0MiB|348.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2479.0MiB|2479.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3017.0MiB|3017.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1439.0MiB|1439.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2952.0MiB|2952.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3668.0MiB|3668.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |438.0MiB|438.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |440.0MiB|440.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2193.0MiB|2193.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6659.0MiB|6659.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1072.0MiB|1072.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1347.0MiB|1347.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |286.0MiB|286.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |244.0MiB|244.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |979.0MiB|979.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1758.0MiB|1758.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1252.0MiB|1252.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1492.0MiB|1492.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |348.0MiB|348.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2479.0MiB|2479.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3017.0MiB|3017.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1439.0MiB|1439.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2952.0MiB|2952.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3668.0MiB|3668.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |438.0MiB|438.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |440.0MiB|440.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2193.0MiB|2193.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6659.0MiB|6659.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1072.0MiB|1072.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1347.0MiB|1347.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |286.0MiB|286.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |244.0MiB|244.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |979.0MiB|979.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1758.0MiB|1758.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.818s |33.043GiB|
|scrambled14845.smt2                                                                        | 615.201s |6659.0MiB|
|scrambled47700.smt2                                                                        |1200.549s |5463.0MiB|
|scrambled73755.smt2                                                                        |1200.592s |5096.0MiB|
|scrambled122926.smt2                                                                       |1200.387s |3668.0MiB|
|scrambled82760.smt2                                                                        |1200.336s |3291.0MiB|
|scrambled87588.smt2                                                                        |1200.449s |3146.0MiB|
|scrambled108663.smt2                                                                       |1200.361s |3017.0MiB|
|scrambled12033.smt2                                                                        |1200.301s |2952.0MiB|
|scrambled62032.smt2                                                                        |1200.275s |2908.0MiB|
|scrambled91750.smt2                                                                        |1200.284s |2729.0MiB|
|scrambled108406.smt2                                                                       |1200.327s |2479.0MiB|
|scrambled96401.smt2                                                                        | 694.701s |2425.0MiB|
|scrambled39467.smt2                                                                        |1200.241s |2283.0MiB|
|scrambled73281.smt2                                                                        |1200.268s |2212.0MiB|
|scrambled130111.smt2                                                                       |1200.369s |2193.0MiB|
|scrambled8852.smt2                                                                         |1200.158s |1977.0MiB|
|scrambled41135.smt2                                                                        |1200.180s |1872.0MiB|
|scrambled79354.smt2                                                                        |1200.345s |1807.0MiB|
|scrambled36790.smt2                                                                        |1200.214s |1758.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.818s |33.043GiB|
|scrambled14845.smt2                                                                        | 615.201s |6659.0MiB|
|scrambled47700.smt2                                                                        |1200.549s |5463.0MiB|
|scrambled73755.smt2                                                                        |1200.592s |5096.0MiB|
|scrambled122926.smt2                                                                       |1200.387s |3668.0MiB|
|scrambled82760.smt2                                                                        |1200.336s |3291.0MiB|
|scrambled87588.smt2                                                                        |1200.449s |3146.0MiB|
|scrambled108663.smt2                                                                       |1200.361s |3017.0MiB|
|scrambled12033.smt2                                                                        |1200.301s |2952.0MiB|
|scrambled62032.smt2                                                                        |1200.275s |2908.0MiB|
|scrambled91750.smt2                                                                        |1200.284s |2729.0MiB|
|scrambled108406.smt2                                                                       |1200.327s |2479.0MiB|
|scrambled96401.smt2                                                                        | 694.701s |2425.0MiB|
|scrambled39467.smt2                                                                        |1200.241s |2283.0MiB|
|scrambled73281.smt2                                                                        |1200.268s |2212.0MiB|
|scrambled130111.smt2                                                                       |1200.369s |2193.0MiB|
|scrambled8852.smt2                                                                         |1200.158s |1977.0MiB|
|scrambled41135.smt2                                                                        |1200.180s |1872.0MiB|
|scrambled79354.smt2                                                                        |1200.345s |1807.0MiB|
|scrambled36790.smt2                                                                        |1200.214s |1758.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  26.619s  |  26.619s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.327s  |1200.327s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.361s  |1200.361s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.301s  |1200.301s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.387s  |1200.387s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.439s  |  10.439s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  17.588s  |  17.588s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.369s  |1200.369s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 615.201s  | 615.201s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  16.384s  |  16.384s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 259.225s  | 259.225s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  20.712s  |  20.712s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.293s  |   4.293s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  56.776s  |  56.776s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.143s  |1200.143s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.241s  |1200.241s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.549s  |1200.549s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   5.730s  |   5.730s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.912s  |   0.912s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.126s  |1200.126s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 204.036s  | 204.036s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.275s  |1200.275s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.268s  |1200.268s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.592s  |1200.592s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.345s  |1200.345s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 220.871s  | 220.871s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   6.129s  |   6.129s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.336s  |1200.336s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1202.818s  |1202.818s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.449s  |1200.449s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   4.962s  |   4.962s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         | 694.701s  | 694.701s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.240s  |1200.240s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.177s  |1200.177s  |   0.000s  | 0.0%|
</details>
