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
Z3 commit: 4e9e3413ec6d3ed78d31f91f5c563e3531e9b393
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.failed_literal_backbones=false smt_parallel.num_global_bb_chunking_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore old changes

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 4e9e3413ec6d3ed78d31f91f5c563e3531e9b393
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.failed_literal_backbones=false smt_parallel.num_global_bb_chunking_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore old changes

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.168s  |1200.168s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  38.717s  |  38.717s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.334s  |1200.334s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.346s  |1200.346s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.289s  |1200.289s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.439s  |1200.439s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.641s  |  11.641s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  18.552s  |  18.552s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.325s  |1200.325s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 489.761s  | 489.761s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.735s  |  13.735s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  36.013s  |  36.013s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  24.911s  |  24.911s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.588s  |   4.588s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 227.399s  | 227.399s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1123.635s  |1123.635s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.168s  |1200.168s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  38.717s  |  38.717s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.334s  |1200.334s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.346s  |1200.346s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.289s  |1200.289s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.439s  |1200.439s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.641s  |  11.641s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  18.552s  |  18.552s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.325s  |1200.325s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 489.761s  | 489.761s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.735s  |  13.735s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  36.013s  |  36.013s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  24.911s  |  24.911s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.588s  |   4.588s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 227.399s  | 227.399s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1123.635s  |1123.635s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.168s  |1200.168s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  38.717s  |  38.717s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.334s  |1200.334s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.346s  |1200.346s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.289s  |1200.289s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.439s  |1200.439s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.641s  |  11.641s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  18.552s  |  18.552s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.325s  |1200.325s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 489.761s  | 489.761s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.735s  |  13.735s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  36.013s  |  36.013s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  24.911s  |  24.911s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.588s  |   4.588s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 227.399s  | 227.399s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1123.635s  |1123.635s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.168s  |1200.168s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  38.717s  |  38.717s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.334s  |1200.334s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.346s  |1200.346s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.289s  |1200.289s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.439s  |1200.439s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.641s  |  11.641s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  18.552s  |  18.552s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.325s  |1200.325s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 489.761s  | 489.761s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.735s  |  13.735s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  36.013s  |  36.013s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  24.911s  |  24.911s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.588s  |   4.588s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 227.399s  | 227.399s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1123.635s  |1123.635s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.165s |29.899GiB|
|scrambled87588.smt2                                                                        |1200.643s |6516.0MiB|
|scrambled73755.smt2                                                                        |1200.635s |5155.0MiB|
|scrambled82760.smt2                                                                        |1200.538s |5021.0MiB|
|scrambled39467.smt2                                                                        |1200.461s |2771.0MiB|
|scrambled122926.smt2                                                                       |1200.439s |3841.0MiB|
|scrambled91750.smt2                                                                        |1200.415s |2629.0MiB|
|scrambled47700.smt2                                                                        |1200.375s |3186.0MiB|
|scrambled62032.smt2                                                                        |1200.363s |2776.0MiB|
|scrambled58311.smt2                                                                        |1200.359s |3440.0MiB|
|scrambled108663.smt2                                                                       |1200.346s |3153.0MiB|
|scrambled108406.smt2                                                                       |1200.334s |2681.0MiB|
|scrambled130111.smt2                                                                       |1200.325s |1808.0MiB|
|scrambled12033.smt2                                                                        |1200.289s |2934.0MiB|
|scrambled97386.smt2                                                                        |1200.273s |1804.0MiB|
|scrambled38587.smt2                                                                        |1200.248s |2002.0MiB|
|scrambled73281.smt2                                                                        |1200.246s |1883.0MiB|
|scrambled98111.smt2                                                                        |1200.227s |1301.0MiB|
|scrambled41135.smt2                                                                        |1200.224s |1768.0MiB|
|scrambled9883.smt2                                                                         |1200.221s |1362.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.165s |29.899GiB|
|scrambled87588.smt2                                                                        |1200.643s |6516.0MiB|
|scrambled73755.smt2                                                                        |1200.635s |5155.0MiB|
|scrambled82760.smt2                                                                        |1200.538s |5021.0MiB|
|scrambled39467.smt2                                                                        |1200.461s |2771.0MiB|
|scrambled122926.smt2                                                                       |1200.439s |3841.0MiB|
|scrambled91750.smt2                                                                        |1200.415s |2629.0MiB|
|scrambled47700.smt2                                                                        |1200.375s |3186.0MiB|
|scrambled62032.smt2                                                                        |1200.363s |2776.0MiB|
|scrambled58311.smt2                                                                        |1200.359s |3440.0MiB|
|scrambled108663.smt2                                                                       |1200.346s |3153.0MiB|
|scrambled108406.smt2                                                                       |1200.334s |2681.0MiB|
|scrambled130111.smt2                                                                       |1200.325s |1808.0MiB|
|scrambled12033.smt2                                                                        |1200.289s |2934.0MiB|
|scrambled97386.smt2                                                                        |1200.273s |1804.0MiB|
|scrambled38587.smt2                                                                        |1200.248s |2002.0MiB|
|scrambled73281.smt2                                                                        |1200.246s |1883.0MiB|
|scrambled98111.smt2                                                                        |1200.227s |1301.0MiB|
|scrambled41135.smt2                                                                        |1200.224s |1768.0MiB|
|scrambled9883.smt2                                                                         |1200.221s |1362.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1253.0MiB|1253.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1456.0MiB|1456.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |381.0MiB|381.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2681.0MiB|2681.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3153.0MiB|3153.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1415.0MiB|1415.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2934.0MiB|2934.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3841.0MiB|3841.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |441.0MiB|441.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |401.0MiB|401.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1808.0MiB|1808.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6629.0MiB|6629.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1068.0MiB|1068.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |825.0MiB|825.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |877.0MiB|877.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1271.0MiB|1271.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1690.0MiB|1690.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1253.0MiB|1253.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1456.0MiB|1456.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |381.0MiB|381.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2681.0MiB|2681.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3153.0MiB|3153.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1415.0MiB|1415.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2934.0MiB|2934.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3841.0MiB|3841.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |441.0MiB|441.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |401.0MiB|401.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1808.0MiB|1808.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6629.0MiB|6629.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1068.0MiB|1068.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |825.0MiB|825.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |877.0MiB|877.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1271.0MiB|1271.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1690.0MiB|1690.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1253.0MiB|1253.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1456.0MiB|1456.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |381.0MiB|381.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2681.0MiB|2681.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3153.0MiB|3153.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1415.0MiB|1415.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2934.0MiB|2934.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3841.0MiB|3841.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |441.0MiB|441.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |401.0MiB|401.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1808.0MiB|1808.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6629.0MiB|6629.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1068.0MiB|1068.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |825.0MiB|825.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |877.0MiB|877.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1271.0MiB|1271.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1690.0MiB|1690.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1253.0MiB|1253.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1456.0MiB|1456.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |381.0MiB|381.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2681.0MiB|2681.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3153.0MiB|3153.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1415.0MiB|1415.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2934.0MiB|2934.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3841.0MiB|3841.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |441.0MiB|441.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |401.0MiB|401.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1808.0MiB|1808.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6629.0MiB|6629.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1068.0MiB|1068.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |825.0MiB|825.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |877.0MiB|877.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1271.0MiB|1271.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1690.0MiB|1690.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.165s |29.899GiB|
|scrambled14845.smt2                                                                        | 489.761s |6629.0MiB|
|scrambled87588.smt2                                                                        |1200.643s |6516.0MiB|
|scrambled73755.smt2                                                                        |1200.635s |5155.0MiB|
|scrambled82760.smt2                                                                        |1200.538s |5021.0MiB|
|scrambled122926.smt2                                                                       |1200.439s |3841.0MiB|
|scrambled58311.smt2                                                                        |1200.359s |3440.0MiB|
|scrambled47700.smt2                                                                        |1200.375s |3186.0MiB|
|scrambled108663.smt2                                                                       |1200.346s |3153.0MiB|
|scrambled12033.smt2                                                                        |1200.289s |2934.0MiB|
|scrambled62032.smt2                                                                        |1200.363s |2776.0MiB|
|scrambled39467.smt2                                                                        |1200.461s |2771.0MiB|
|scrambled108406.smt2                                                                       |1200.334s |2681.0MiB|
|scrambled91750.smt2                                                                        |1200.415s |2629.0MiB|
|scrambled38587.smt2                                                                        |1200.248s |2002.0MiB|
|scrambled73281.smt2                                                                        |1200.246s |1883.0MiB|
|scrambled130111.smt2                                                                       |1200.325s |1808.0MiB|
|scrambled97386.smt2                                                                        |1200.273s |1804.0MiB|
|scrambled41135.smt2                                                                        |1200.224s |1768.0MiB|
|scrambled61060.smt2                                                                        | 215.074s |1761.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.165s |29.899GiB|
|scrambled14845.smt2                                                                        | 489.761s |6629.0MiB|
|scrambled87588.smt2                                                                        |1200.643s |6516.0MiB|
|scrambled73755.smt2                                                                        |1200.635s |5155.0MiB|
|scrambled82760.smt2                                                                        |1200.538s |5021.0MiB|
|scrambled122926.smt2                                                                       |1200.439s |3841.0MiB|
|scrambled58311.smt2                                                                        |1200.359s |3440.0MiB|
|scrambled47700.smt2                                                                        |1200.375s |3186.0MiB|
|scrambled108663.smt2                                                                       |1200.346s |3153.0MiB|
|scrambled12033.smt2                                                                        |1200.289s |2934.0MiB|
|scrambled62032.smt2                                                                        |1200.363s |2776.0MiB|
|scrambled39467.smt2                                                                        |1200.461s |2771.0MiB|
|scrambled108406.smt2                                                                       |1200.334s |2681.0MiB|
|scrambled91750.smt2                                                                        |1200.415s |2629.0MiB|
|scrambled38587.smt2                                                                        |1200.248s |2002.0MiB|
|scrambled73281.smt2                                                                        |1200.246s |1883.0MiB|
|scrambled130111.smt2                                                                       |1200.325s |1808.0MiB|
|scrambled97386.smt2                                                                        |1200.273s |1804.0MiB|
|scrambled41135.smt2                                                                        |1200.224s |1768.0MiB|
|scrambled61060.smt2                                                                        | 215.074s |1761.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.168s  |1200.168s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  38.717s  |  38.717s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.334s  |1200.334s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.346s  |1200.346s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.289s  |1200.289s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.439s  |1200.439s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.641s  |  11.641s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  18.552s  |  18.552s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.325s  |1200.325s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 489.761s  | 489.761s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.735s  |  13.735s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  36.013s  |  36.013s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  24.911s  |  24.911s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.588s  |   4.588s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 227.399s  | 227.399s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1123.635s  |1123.635s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.248s  |1200.248s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.461s  |1200.461s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.224s  |1200.224s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.375s  |1200.375s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   5.894s  |   5.894s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   1.008s  |   1.008s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.359s  |1200.359s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 215.074s  | 215.074s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.363s  |1200.363s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.246s  |1200.246s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.635s  |1200.635s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 585.050s  | 585.050s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   6.132s  |   6.132s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.538s  |1200.538s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1203.165s  |1203.165s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.643s  |1200.643s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.156s  |1200.156s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.415s  |1200.415s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   5.036s  |   5.036s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         | 428.902s  | 428.902s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.273s  |1200.273s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.227s  |1200.227s  |   0.000s  | 0.0%|
</details>
