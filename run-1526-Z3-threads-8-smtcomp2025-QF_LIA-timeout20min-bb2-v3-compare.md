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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-v3
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 214817d96aa5e7e5ee8209965723f1d886d0f3db
Z3 branch: 214817d96aa5e7e5ee8209965723f1d886d0f3db
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: modify the fallback policies for bb detection in batch mode but also in FL mode

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-v3
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 214817d96aa5e7e5ee8209965723f1d886d0f3db
Z3 branch: 214817d96aa5e7e5ee8209965723f1d886d0f3db
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: modify the fallback policies for bb detection in batch mode but also in FL mode

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.194s  |1200.194s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  36.662s  |  36.662s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.583s  |1200.583s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.264s  |1200.264s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.320s  |1200.320s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.422s  |1200.422s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.954s  |  12.954s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  16.573s  |  16.573s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.362s  |1200.362s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 650.100s  | 650.100s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.665s  |  14.665s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 230.035s  | 230.035s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  32.178s  |  32.178s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.728s  |   4.728s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 581.792s  | 581.792s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.167s  |1200.167s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.211s  |1200.211s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.194s  |1200.194s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  36.662s  |  36.662s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.583s  |1200.583s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.264s  |1200.264s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.320s  |1200.320s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.422s  |1200.422s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.954s  |  12.954s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  16.573s  |  16.573s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.362s  |1200.362s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 650.100s  | 650.100s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.665s  |  14.665s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 230.035s  | 230.035s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  32.178s  |  32.178s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.728s  |   4.728s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 581.792s  | 581.792s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.167s  |1200.167s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.211s  |1200.211s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.194s  |1200.194s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  36.662s  |  36.662s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.583s  |1200.583s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.264s  |1200.264s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.320s  |1200.320s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.422s  |1200.422s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.954s  |  12.954s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  16.573s  |  16.573s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.362s  |1200.362s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 650.100s  | 650.100s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.665s  |  14.665s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 230.035s  | 230.035s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  32.178s  |  32.178s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.728s  |   4.728s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 581.792s  | 581.792s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.167s  |1200.167s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.211s  |1200.211s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.194s  |1200.194s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  36.662s  |  36.662s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.583s  |1200.583s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.264s  |1200.264s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.320s  |1200.320s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.422s  |1200.422s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.954s  |  12.954s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  16.573s  |  16.573s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.362s  |1200.362s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 650.100s  | 650.100s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.665s  |  14.665s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 230.035s  | 230.035s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  32.178s  |  32.178s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.728s  |   4.728s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 581.792s  | 581.792s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.167s  |1200.167s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.211s  |1200.211s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.497s |26.31GiB|
|scrambled62032.smt2                                                                        |1200.666s |6437.0MiB|
|scrambled73755.smt2                                                                        |1200.662s |5267.0MiB|
|scrambled87588.smt2                                                                        |1200.601s |4075.0MiB|
|scrambled108663.smt2                                                                       |1200.583s |3520.0MiB|
|scrambled41135.smt2                                                                        |1200.499s |6256.0MiB|
|scrambled39467.smt2                                                                        |1200.457s |2769.0MiB|
|scrambled122926.smt2                                                                       |1200.422s |3848.0MiB|
|scrambled91750.smt2                                                                        |1200.417s |2587.0MiB|
|scrambled47700.smt2                                                                        |1200.413s |3057.0MiB|
|scrambled130111.smt2                                                                       |1200.362s |2237.0MiB|
|scrambled73281.smt2                                                                        |1200.350s |3283.0MiB|
|scrambled97386.smt2                                                                        |1200.329s |1711.0MiB|
|scrambled108406.smt2                                                                       |1200.323s |2863.0MiB|
|scrambled12033.smt2                                                                        |1200.320s |2929.0MiB|
|scrambled82760.smt2                                                                        |1200.282s |1505.0MiB|
|scrambled119582.smt2                                                                       |1200.264s |1493.0MiB|
|scrambled38587.smt2                                                                        |1200.254s |1499.0MiB|
|scrambled79354.smt2                                                                        |1200.227s |1638.0MiB|
|scrambled9883.smt2                                                                         |1200.226s |1617.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.497s |26.31GiB|
|scrambled62032.smt2                                                                        |1200.666s |6437.0MiB|
|scrambled73755.smt2                                                                        |1200.662s |5267.0MiB|
|scrambled87588.smt2                                                                        |1200.601s |4075.0MiB|
|scrambled108663.smt2                                                                       |1200.583s |3520.0MiB|
|scrambled41135.smt2                                                                        |1200.499s |6256.0MiB|
|scrambled39467.smt2                                                                        |1200.457s |2769.0MiB|
|scrambled122926.smt2                                                                       |1200.422s |3848.0MiB|
|scrambled91750.smt2                                                                        |1200.417s |2587.0MiB|
|scrambled47700.smt2                                                                        |1200.413s |3057.0MiB|
|scrambled130111.smt2                                                                       |1200.362s |2237.0MiB|
|scrambled73281.smt2                                                                        |1200.350s |3283.0MiB|
|scrambled97386.smt2                                                                        |1200.329s |1711.0MiB|
|scrambled108406.smt2                                                                       |1200.323s |2863.0MiB|
|scrambled12033.smt2                                                                        |1200.320s |2929.0MiB|
|scrambled82760.smt2                                                                        |1200.282s |1505.0MiB|
|scrambled119582.smt2                                                                       |1200.264s |1493.0MiB|
|scrambled38587.smt2                                                                        |1200.254s |1499.0MiB|
|scrambled79354.smt2                                                                        |1200.227s |1638.0MiB|
|scrambled9883.smt2                                                                         |1200.226s |1617.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1227.0MiB|1227.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1601.0MiB|1601.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2863.0MiB|2863.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3520.0MiB|3520.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1493.0MiB|1493.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2929.0MiB|2929.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3848.0MiB|3848.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |444.0MiB|444.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |363.0MiB|363.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2237.0MiB|2237.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6854.0MiB|6854.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1069.0MiB|1069.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1177.0MiB|1177.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |315.0MiB|315.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |1325.0MiB|1325.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1192.0MiB|1192.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1776.0MiB|1776.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1227.0MiB|1227.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1601.0MiB|1601.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2863.0MiB|2863.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3520.0MiB|3520.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1493.0MiB|1493.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2929.0MiB|2929.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3848.0MiB|3848.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |444.0MiB|444.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |363.0MiB|363.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2237.0MiB|2237.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6854.0MiB|6854.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1069.0MiB|1069.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1177.0MiB|1177.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |315.0MiB|315.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |1325.0MiB|1325.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1192.0MiB|1192.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1776.0MiB|1776.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1227.0MiB|1227.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1601.0MiB|1601.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2863.0MiB|2863.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3520.0MiB|3520.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1493.0MiB|1493.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2929.0MiB|2929.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3848.0MiB|3848.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |444.0MiB|444.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |363.0MiB|363.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2237.0MiB|2237.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6854.0MiB|6854.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1069.0MiB|1069.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1177.0MiB|1177.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |315.0MiB|315.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |1325.0MiB|1325.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1192.0MiB|1192.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1776.0MiB|1776.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1227.0MiB|1227.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1601.0MiB|1601.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2863.0MiB|2863.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3520.0MiB|3520.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1493.0MiB|1493.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2929.0MiB|2929.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3848.0MiB|3848.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |444.0MiB|444.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |363.0MiB|363.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2237.0MiB|2237.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6854.0MiB|6854.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1069.0MiB|1069.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1177.0MiB|1177.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |315.0MiB|315.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |1325.0MiB|1325.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1192.0MiB|1192.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1776.0MiB|1776.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.497s |26.31GiB|
|scrambled14845.smt2                                                                        | 650.100s |6854.0MiB|
|scrambled62032.smt2                                                                        |1200.666s |6437.0MiB|
|scrambled41135.smt2                                                                        |1200.499s |6256.0MiB|
|scrambled73755.smt2                                                                        |1200.662s |5267.0MiB|
|scrambled87588.smt2                                                                        |1200.601s |4075.0MiB|
|scrambled122926.smt2                                                                       |1200.422s |3848.0MiB|
|scrambled108663.smt2                                                                       |1200.583s |3520.0MiB|
|scrambled73281.smt2                                                                        |1200.350s |3283.0MiB|
|scrambled47700.smt2                                                                        |1200.413s |3057.0MiB|
|scrambled12033.smt2                                                                        |1200.320s |2929.0MiB|
|scrambled108406.smt2                                                                       |1200.323s |2863.0MiB|
|scrambled39467.smt2                                                                        |1200.457s |2769.0MiB|
|scrambled91750.smt2                                                                        |1200.417s |2587.0MiB|
|scrambled130111.smt2                                                                       |1200.362s |2237.0MiB|
|scrambled36790.smt2                                                                        |1200.211s |1776.0MiB|
|scrambled97386.smt2                                                                        |1200.329s |1711.0MiB|
|scrambled96401.smt2                                                                        |1200.210s |1697.0MiB|
|scrambled61060.smt2                                                                        | 194.579s |1673.0MiB|
|scrambled79354.smt2                                                                        |1200.227s |1638.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.497s |26.31GiB|
|scrambled14845.smt2                                                                        | 650.100s |6854.0MiB|
|scrambled62032.smt2                                                                        |1200.666s |6437.0MiB|
|scrambled41135.smt2                                                                        |1200.499s |6256.0MiB|
|scrambled73755.smt2                                                                        |1200.662s |5267.0MiB|
|scrambled87588.smt2                                                                        |1200.601s |4075.0MiB|
|scrambled122926.smt2                                                                       |1200.422s |3848.0MiB|
|scrambled108663.smt2                                                                       |1200.583s |3520.0MiB|
|scrambled73281.smt2                                                                        |1200.350s |3283.0MiB|
|scrambled47700.smt2                                                                        |1200.413s |3057.0MiB|
|scrambled12033.smt2                                                                        |1200.320s |2929.0MiB|
|scrambled108406.smt2                                                                       |1200.323s |2863.0MiB|
|scrambled39467.smt2                                                                        |1200.457s |2769.0MiB|
|scrambled91750.smt2                                                                        |1200.417s |2587.0MiB|
|scrambled130111.smt2                                                                       |1200.362s |2237.0MiB|
|scrambled36790.smt2                                                                        |1200.211s |1776.0MiB|
|scrambled97386.smt2                                                                        |1200.329s |1711.0MiB|
|scrambled96401.smt2                                                                        |1200.210s |1697.0MiB|
|scrambled61060.smt2                                                                        | 194.579s |1673.0MiB|
|scrambled79354.smt2                                                                        |1200.227s |1638.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.194s  |1200.194s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  36.662s  |  36.662s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.583s  |1200.583s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.264s  |1200.264s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.320s  |1200.320s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.422s  |1200.422s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.954s  |  12.954s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  16.573s  |  16.573s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.362s  |1200.362s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 650.100s  | 650.100s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.665s  |  14.665s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 230.035s  | 230.035s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  32.178s  |  32.178s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.728s  |   4.728s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 581.792s  | 581.792s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.167s  |1200.167s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.211s  |1200.211s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.254s  |1200.254s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.457s  |1200.457s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.499s  |1200.499s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.413s  |1200.413s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   5.690s  |   5.690s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.912s  |   0.912s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.198s  |1200.198s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 194.579s  | 194.579s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.666s  |1200.666s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.350s  |1200.350s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.662s  |1200.662s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.227s  |1200.227s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 279.406s  | 279.406s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   5.745s  |   5.745s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.282s  |1200.282s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1202.497s  |1202.497s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.601s  |1200.601s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.161s  |1200.161s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.417s  |1200.417s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   4.145s  |   4.145s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1200.210s  |1200.210s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.329s  |1200.329s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.174s  |1200.174s  |   0.000s  | 0.0%|
</details>
