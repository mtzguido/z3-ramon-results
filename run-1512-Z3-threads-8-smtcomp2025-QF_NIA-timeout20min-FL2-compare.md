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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-FL2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: d6f9357ea8c4d16c8b57d23d268d2276ecf7c7a3
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_fl_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: separate FL probe into 2 threads for pos and neg mode

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-FL2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: d6f9357ea8c4d16c8b57d23d268d2276ecf7c7a3
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_fl_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: separate FL probe into 2 threads for pos and neg mode

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.162s  |1200.162s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  26.230s  |  26.230s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.342s  |1200.342s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.239s  |1200.239s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.304s  |1200.304s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.658s  |1200.658s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.000s  |  12.000s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  19.863s  |  19.863s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.344s  |1200.344s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 631.692s  | 631.692s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.308s  |  14.308s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 306.704s  | 306.704s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  29.959s  |  29.959s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.922s  |   3.922s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 200.628s  | 200.628s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.150s  |1200.150s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 758.930s  | 758.930s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.162s  |1200.162s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  26.230s  |  26.230s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.342s  |1200.342s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.239s  |1200.239s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.304s  |1200.304s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.658s  |1200.658s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.000s  |  12.000s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  19.863s  |  19.863s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.344s  |1200.344s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 631.692s  | 631.692s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.308s  |  14.308s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 306.704s  | 306.704s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  29.959s  |  29.959s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.922s  |   3.922s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 200.628s  | 200.628s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.150s  |1200.150s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 758.930s  | 758.930s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.162s  |1200.162s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  26.230s  |  26.230s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.342s  |1200.342s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.239s  |1200.239s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.304s  |1200.304s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.658s  |1200.658s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.000s  |  12.000s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  19.863s  |  19.863s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.344s  |1200.344s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 631.692s  | 631.692s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.308s  |  14.308s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 306.704s  | 306.704s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  29.959s  |  29.959s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.922s  |   3.922s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 200.628s  | 200.628s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.150s  |1200.150s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 758.930s  | 758.930s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.162s  |1200.162s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  26.230s  |  26.230s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.342s  |1200.342s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.239s  |1200.239s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.304s  |1200.304s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.658s  |1200.658s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.000s  |  12.000s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  19.863s  |  19.863s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.344s  |1200.344s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 631.692s  | 631.692s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.308s  |  14.308s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 306.704s  | 306.704s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  29.959s  |  29.959s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.922s  |   3.922s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 200.628s  | 200.628s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.150s  |1200.150s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 758.930s  | 758.930s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.423s |23.307GiB|
|scrambled122926.smt2                                                                       |1200.658s |3964.0MiB|
|scrambled73755.smt2                                                                        |1200.635s |5065.0MiB|
|scrambled87588.smt2                                                                        |1200.466s |4039.0MiB|
|scrambled47700.smt2                                                                        |1200.375s |3390.0MiB|
|scrambled8852.smt2                                                                         |1200.371s |3231.0MiB|
|scrambled130111.smt2                                                                       |1200.344s |1969.0MiB|
|scrambled108406.smt2                                                                       |1200.342s |2253.0MiB|
|scrambled97386.smt2                                                                        |1200.314s |1840.0MiB|
|scrambled73281.smt2                                                                        |1200.312s |2790.0MiB|
|scrambled108663.smt2                                                                       |1200.308s |2884.0MiB|
|scrambled91750.smt2                                                                        |1200.306s |2644.0MiB|
|scrambled12033.smt2                                                                        |1200.304s |2847.0MiB|
|scrambled82760.smt2                                                                        |1200.283s |1690.0MiB|
|scrambled62032.smt2                                                                        |1200.269s |1817.0MiB|
|scrambled79354.smt2                                                                        |1200.250s |1657.0MiB|
|scrambled119582.smt2                                                                       |1200.239s |1379.0MiB|
|scrambled38587.smt2                                                                        |1200.232s |1888.0MiB|
|scrambled96401.smt2                                                                        |1200.226s |1593.0MiB|
|scrambled9883.smt2                                                                         |1200.213s |1369.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.423s |23.307GiB|
|scrambled122926.smt2                                                                       |1200.658s |3964.0MiB|
|scrambled73755.smt2                                                                        |1200.635s |5065.0MiB|
|scrambled87588.smt2                                                                        |1200.466s |4039.0MiB|
|scrambled47700.smt2                                                                        |1200.375s |3390.0MiB|
|scrambled8852.smt2                                                                         |1200.371s |3231.0MiB|
|scrambled130111.smt2                                                                       |1200.344s |1969.0MiB|
|scrambled108406.smt2                                                                       |1200.342s |2253.0MiB|
|scrambled97386.smt2                                                                        |1200.314s |1840.0MiB|
|scrambled73281.smt2                                                                        |1200.312s |2790.0MiB|
|scrambled108663.smt2                                                                       |1200.308s |2884.0MiB|
|scrambled91750.smt2                                                                        |1200.306s |2644.0MiB|
|scrambled12033.smt2                                                                        |1200.304s |2847.0MiB|
|scrambled82760.smt2                                                                        |1200.283s |1690.0MiB|
|scrambled62032.smt2                                                                        |1200.269s |1817.0MiB|
|scrambled79354.smt2                                                                        |1200.250s |1657.0MiB|
|scrambled119582.smt2                                                                       |1200.239s |1379.0MiB|
|scrambled38587.smt2                                                                        |1200.232s |1888.0MiB|
|scrambled96401.smt2                                                                        |1200.226s |1593.0MiB|
|scrambled9883.smt2                                                                         |1200.213s |1369.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1221.0MiB|1221.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1428.0MiB|1428.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |369.0MiB|369.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2253.0MiB|2253.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2884.0MiB|2884.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1379.0MiB|1379.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2847.0MiB|2847.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3964.0MiB|3964.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |444.0MiB|444.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |403.0MiB|403.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1969.0MiB|1969.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6672.0MiB|6672.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1061.0MiB|1061.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1811.0MiB|1811.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |297.0MiB|297.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |261.0MiB|261.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |765.0MiB|765.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1003.0MiB|1003.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1368.0MiB|1368.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1221.0MiB|1221.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1428.0MiB|1428.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |369.0MiB|369.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2253.0MiB|2253.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2884.0MiB|2884.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1379.0MiB|1379.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2847.0MiB|2847.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3964.0MiB|3964.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |444.0MiB|444.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |403.0MiB|403.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1969.0MiB|1969.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6672.0MiB|6672.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1061.0MiB|1061.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1811.0MiB|1811.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |297.0MiB|297.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |261.0MiB|261.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |765.0MiB|765.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1003.0MiB|1003.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1368.0MiB|1368.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1221.0MiB|1221.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1428.0MiB|1428.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |369.0MiB|369.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2253.0MiB|2253.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2884.0MiB|2884.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1379.0MiB|1379.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2847.0MiB|2847.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3964.0MiB|3964.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |444.0MiB|444.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |403.0MiB|403.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1969.0MiB|1969.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6672.0MiB|6672.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1061.0MiB|1061.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1811.0MiB|1811.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |297.0MiB|297.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |261.0MiB|261.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |765.0MiB|765.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1003.0MiB|1003.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1368.0MiB|1368.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1221.0MiB|1221.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1428.0MiB|1428.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |369.0MiB|369.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2253.0MiB|2253.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2884.0MiB|2884.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1379.0MiB|1379.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2847.0MiB|2847.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3964.0MiB|3964.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |444.0MiB|444.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |403.0MiB|403.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1969.0MiB|1969.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6672.0MiB|6672.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1061.0MiB|1061.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1811.0MiB|1811.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |297.0MiB|297.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |261.0MiB|261.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |765.0MiB|765.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1003.0MiB|1003.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1368.0MiB|1368.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.423s |23.307GiB|
|scrambled14845.smt2                                                                        | 631.692s |6672.0MiB|
|scrambled73755.smt2                                                                        |1200.635s |5065.0MiB|
|scrambled87588.smt2                                                                        |1200.466s |4039.0MiB|
|scrambled122926.smt2                                                                       |1200.658s |3964.0MiB|
|scrambled47700.smt2                                                                        |1200.375s |3390.0MiB|
|scrambled8852.smt2                                                                         |1200.371s |3231.0MiB|
|scrambled108663.smt2                                                                       |1200.308s |2884.0MiB|
|scrambled12033.smt2                                                                        |1200.304s |2847.0MiB|
|scrambled73281.smt2                                                                        |1200.312s |2790.0MiB|
|scrambled91750.smt2                                                                        |1200.306s |2644.0MiB|
|scrambled108406.smt2                                                                       |1200.342s |2253.0MiB|
|scrambled41135.smt2                                                                        |1200.192s |2033.0MiB|
|scrambled130111.smt2                                                                       |1200.344s |1969.0MiB|
|scrambled38587.smt2                                                                        |1200.232s |1888.0MiB|
|scrambled97386.smt2                                                                        |1200.314s |1840.0MiB|
|scrambled62032.smt2                                                                        |1200.269s |1817.0MiB|
|scrambled28176.smt2                                                                        | 306.704s |1811.0MiB|
|scrambled39467.smt2                                                                        |1200.188s |1770.0MiB|
|scrambled82760.smt2                                                                        |1200.283s |1690.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.423s |23.307GiB|
|scrambled14845.smt2                                                                        | 631.692s |6672.0MiB|
|scrambled73755.smt2                                                                        |1200.635s |5065.0MiB|
|scrambled87588.smt2                                                                        |1200.466s |4039.0MiB|
|scrambled122926.smt2                                                                       |1200.658s |3964.0MiB|
|scrambled47700.smt2                                                                        |1200.375s |3390.0MiB|
|scrambled8852.smt2                                                                         |1200.371s |3231.0MiB|
|scrambled108663.smt2                                                                       |1200.308s |2884.0MiB|
|scrambled12033.smt2                                                                        |1200.304s |2847.0MiB|
|scrambled73281.smt2                                                                        |1200.312s |2790.0MiB|
|scrambled91750.smt2                                                                        |1200.306s |2644.0MiB|
|scrambled108406.smt2                                                                       |1200.342s |2253.0MiB|
|scrambled41135.smt2                                                                        |1200.192s |2033.0MiB|
|scrambled130111.smt2                                                                       |1200.344s |1969.0MiB|
|scrambled38587.smt2                                                                        |1200.232s |1888.0MiB|
|scrambled97386.smt2                                                                        |1200.314s |1840.0MiB|
|scrambled62032.smt2                                                                        |1200.269s |1817.0MiB|
|scrambled28176.smt2                                                                        | 306.704s |1811.0MiB|
|scrambled39467.smt2                                                                        |1200.188s |1770.0MiB|
|scrambled82760.smt2                                                                        |1200.283s |1690.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.162s  |1200.162s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  26.230s  |  26.230s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.342s  |1200.342s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.239s  |1200.239s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.304s  |1200.304s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.658s  |1200.658s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.000s  |  12.000s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  19.863s  |  19.863s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.344s  |1200.344s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 631.692s  | 631.692s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.308s  |  14.308s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 306.704s  | 306.704s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  29.959s  |  29.959s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.922s  |   3.922s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 200.628s  | 200.628s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.150s  |1200.150s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 758.930s  | 758.930s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.232s  |1200.232s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.188s  |1200.188s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.192s  |1200.192s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.375s  |1200.375s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   5.167s  |   5.167s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.992s  |   0.992s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.143s  |1200.143s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 189.614s  | 189.614s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.269s  |1200.269s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.312s  |1200.312s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.635s  |1200.635s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.250s  |1200.250s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         |  37.029s  |  37.029s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   5.949s  |   5.949s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.283s  |1200.283s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1202.423s  |1202.423s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.466s  |1200.466s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.371s  |1200.371s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.306s  |1200.306s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   3.967s  |   3.967s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1200.226s  |1200.226s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.314s  |1200.314s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.153s  |1200.153s  |   0.000s  | 0.0%|
</details>
