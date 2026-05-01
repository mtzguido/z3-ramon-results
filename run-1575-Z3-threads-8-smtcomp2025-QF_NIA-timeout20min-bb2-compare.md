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
Z3 commit: 16130e3063965c4ae1cb3c04f2feebb678ee84ae
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore unit sharing as bb collection on workers

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 16130e3063965c4ae1cb3c04f2feebb678ee84ae
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore unit sharing as bb collection on workers

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.166s  |1200.166s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  57.808s  |  57.808s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.249s  |1200.249s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.406s  |1200.406s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.266s  |1200.266s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.401s  |1200.401s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.671s  |  10.671s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  16.798s  |  16.798s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.286s  |1200.286s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 509.213s  | 509.213s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.793s  |  14.793s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 182.653s  | 182.653s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.484s  |  21.484s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.684s  |   3.684s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 523.886s  | 523.886s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.215s  |1200.215s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.166s  |1200.166s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  57.808s  |  57.808s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.249s  |1200.249s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.406s  |1200.406s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.266s  |1200.266s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.401s  |1200.401s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.671s  |  10.671s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  16.798s  |  16.798s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.286s  |1200.286s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 509.213s  | 509.213s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.793s  |  14.793s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 182.653s  | 182.653s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.484s  |  21.484s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.684s  |   3.684s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 523.886s  | 523.886s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.215s  |1200.215s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.166s  |1200.166s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  57.808s  |  57.808s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.249s  |1200.249s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.406s  |1200.406s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.266s  |1200.266s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.401s  |1200.401s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.671s  |  10.671s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  16.798s  |  16.798s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.286s  |1200.286s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 509.213s  | 509.213s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.793s  |  14.793s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 182.653s  | 182.653s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.484s  |  21.484s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.684s  |   3.684s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 523.886s  | 523.886s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.215s  |1200.215s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.166s  |1200.166s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  57.808s  |  57.808s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.249s  |1200.249s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.406s  |1200.406s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.266s  |1200.266s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.401s  |1200.401s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.671s  |  10.671s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  16.798s  |  16.798s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.286s  |1200.286s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 509.213s  | 509.213s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.793s  |  14.793s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 182.653s  | 182.653s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.484s  |  21.484s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.684s  |   3.684s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 523.886s  | 523.886s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.215s  |1200.215s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.488s |28.194GiB|
|scrambled73755.smt2                                                                        |1200.526s |5267.0MiB|
|scrambled108663.smt2                                                                       |1200.406s |3135.0MiB|
|scrambled122926.smt2                                                                       |1200.401s |3766.0MiB|
|scrambled58311.smt2                                                                        |1200.364s |2560.0MiB|
|scrambled91750.smt2                                                                        |1200.325s |2467.0MiB|
|scrambled39467.smt2                                                                        |1200.311s |2775.0MiB|
|scrambled47700.smt2                                                                        |1200.298s |3055.0MiB|
|scrambled87588.smt2                                                                        |1200.292s |2831.0MiB|
|scrambled130111.smt2                                                                       |1200.286s |2019.0MiB|
|scrambled12033.smt2                                                                        |1200.266s |2956.0MiB|
|scrambled108406.smt2                                                                       |1200.249s |2319.0MiB|
|scrambled36790.smt2                                                                        |1200.215s |1730.0MiB|
|scrambled73281.smt2                                                                        |1200.214s |2016.0MiB|
|scrambled82760.smt2                                                                        |1200.207s |1563.0MiB|
|scrambled79354.smt2                                                                        |1200.199s |1642.0MiB|
|scrambled38587.smt2                                                                        |1200.193s |1403.0MiB|
|scrambled9883.smt2                                                                         |1200.190s |1308.0MiB|
|scrambled98111.smt2                                                                        |1200.181s |1586.0MiB|
|scrambled41135.smt2                                                                        |1200.180s |1738.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.488s |28.194GiB|
|scrambled73755.smt2                                                                        |1200.526s |5267.0MiB|
|scrambled108663.smt2                                                                       |1200.406s |3135.0MiB|
|scrambled122926.smt2                                                                       |1200.401s |3766.0MiB|
|scrambled58311.smt2                                                                        |1200.364s |2560.0MiB|
|scrambled91750.smt2                                                                        |1200.325s |2467.0MiB|
|scrambled39467.smt2                                                                        |1200.311s |2775.0MiB|
|scrambled47700.smt2                                                                        |1200.298s |3055.0MiB|
|scrambled87588.smt2                                                                        |1200.292s |2831.0MiB|
|scrambled130111.smt2                                                                       |1200.286s |2019.0MiB|
|scrambled12033.smt2                                                                        |1200.266s |2956.0MiB|
|scrambled108406.smt2                                                                       |1200.249s |2319.0MiB|
|scrambled36790.smt2                                                                        |1200.215s |1730.0MiB|
|scrambled73281.smt2                                                                        |1200.214s |2016.0MiB|
|scrambled82760.smt2                                                                        |1200.207s |1563.0MiB|
|scrambled79354.smt2                                                                        |1200.199s |1642.0MiB|
|scrambled38587.smt2                                                                        |1200.193s |1403.0MiB|
|scrambled9883.smt2                                                                         |1200.190s |1308.0MiB|
|scrambled98111.smt2                                                                        |1200.181s |1586.0MiB|
|scrambled41135.smt2                                                                        |1200.180s |1738.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1215.0MiB|1215.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1370.0MiB|1370.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |389.0MiB|389.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2319.0MiB|2319.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3135.0MiB|3135.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1412.0MiB|1412.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2956.0MiB|2956.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3766.0MiB|3766.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |443.0MiB|443.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |418.0MiB|418.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2019.0MiB|2019.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6512.0MiB|6512.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1062.0MiB|1062.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1239.0MiB|1239.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |284.0MiB|284.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |249.0MiB|249.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |1239.0MiB|1239.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |987.0MiB|987.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1730.0MiB|1730.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1215.0MiB|1215.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1370.0MiB|1370.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |389.0MiB|389.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2319.0MiB|2319.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3135.0MiB|3135.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1412.0MiB|1412.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2956.0MiB|2956.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3766.0MiB|3766.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |443.0MiB|443.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |418.0MiB|418.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2019.0MiB|2019.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6512.0MiB|6512.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1062.0MiB|1062.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1239.0MiB|1239.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |284.0MiB|284.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |249.0MiB|249.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |1239.0MiB|1239.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |987.0MiB|987.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1730.0MiB|1730.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1215.0MiB|1215.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1370.0MiB|1370.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |389.0MiB|389.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2319.0MiB|2319.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3135.0MiB|3135.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1412.0MiB|1412.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2956.0MiB|2956.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3766.0MiB|3766.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |443.0MiB|443.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |418.0MiB|418.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2019.0MiB|2019.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6512.0MiB|6512.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1062.0MiB|1062.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1239.0MiB|1239.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |284.0MiB|284.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |249.0MiB|249.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |1239.0MiB|1239.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |987.0MiB|987.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1730.0MiB|1730.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1215.0MiB|1215.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1370.0MiB|1370.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |389.0MiB|389.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2319.0MiB|2319.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3135.0MiB|3135.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1412.0MiB|1412.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2956.0MiB|2956.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3766.0MiB|3766.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |443.0MiB|443.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |418.0MiB|418.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2019.0MiB|2019.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6512.0MiB|6512.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1062.0MiB|1062.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1239.0MiB|1239.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |284.0MiB|284.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |249.0MiB|249.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |1239.0MiB|1239.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |987.0MiB|987.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1730.0MiB|1730.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.488s |28.194GiB|
|scrambled14845.smt2                                                                        | 509.213s |6512.0MiB|
|scrambled73755.smt2                                                                        |1200.526s |5267.0MiB|
|scrambled122926.smt2                                                                       |1200.401s |3766.0MiB|
|scrambled108663.smt2                                                                       |1200.406s |3135.0MiB|
|scrambled47700.smt2                                                                        |1200.298s |3055.0MiB|
|scrambled12033.smt2                                                                        |1200.266s |2956.0MiB|
|scrambled87588.smt2                                                                        |1200.292s |2831.0MiB|
|scrambled39467.smt2                                                                        |1200.311s |2775.0MiB|
|scrambled58311.smt2                                                                        |1200.364s |2560.0MiB|
|scrambled91750.smt2                                                                        |1200.325s |2467.0MiB|
|scrambled108406.smt2                                                                       |1200.249s |2319.0MiB|
|scrambled8852.smt2                                                                         |1200.174s |2028.0MiB|
|scrambled130111.smt2                                                                       |1200.286s |2019.0MiB|
|scrambled73281.smt2                                                                        |1200.214s |2016.0MiB|
|scrambled41135.smt2                                                                        |1200.180s |1738.0MiB|
|scrambled36790.smt2                                                                        |1200.215s |1730.0MiB|
|scrambled97386.smt2                                                                        |1200.159s |1648.0MiB|
|scrambled79354.smt2                                                                        |1200.199s |1642.0MiB|
|scrambled61060.smt2                                                                        | 169.210s |1620.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.488s |28.194GiB|
|scrambled14845.smt2                                                                        | 509.213s |6512.0MiB|
|scrambled73755.smt2                                                                        |1200.526s |5267.0MiB|
|scrambled122926.smt2                                                                       |1200.401s |3766.0MiB|
|scrambled108663.smt2                                                                       |1200.406s |3135.0MiB|
|scrambled47700.smt2                                                                        |1200.298s |3055.0MiB|
|scrambled12033.smt2                                                                        |1200.266s |2956.0MiB|
|scrambled87588.smt2                                                                        |1200.292s |2831.0MiB|
|scrambled39467.smt2                                                                        |1200.311s |2775.0MiB|
|scrambled58311.smt2                                                                        |1200.364s |2560.0MiB|
|scrambled91750.smt2                                                                        |1200.325s |2467.0MiB|
|scrambled108406.smt2                                                                       |1200.249s |2319.0MiB|
|scrambled8852.smt2                                                                         |1200.174s |2028.0MiB|
|scrambled130111.smt2                                                                       |1200.286s |2019.0MiB|
|scrambled73281.smt2                                                                        |1200.214s |2016.0MiB|
|scrambled41135.smt2                                                                        |1200.180s |1738.0MiB|
|scrambled36790.smt2                                                                        |1200.215s |1730.0MiB|
|scrambled97386.smt2                                                                        |1200.159s |1648.0MiB|
|scrambled79354.smt2                                                                        |1200.199s |1642.0MiB|
|scrambled61060.smt2                                                                        | 169.210s |1620.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.166s  |1200.166s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  57.808s  |  57.808s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.249s  |1200.249s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.406s  |1200.406s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.266s  |1200.266s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.401s  |1200.401s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.671s  |  10.671s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  16.798s  |  16.798s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.286s  |1200.286s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 509.213s  | 509.213s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.793s  |  14.793s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 182.653s  | 182.653s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.484s  |  21.484s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.684s  |   3.684s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 523.886s  | 523.886s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.215s  |1200.215s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.193s  |1200.193s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.311s  |1200.311s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.298s  |1200.298s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   5.185s  |   5.185s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.917s  |   0.917s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.364s  |1200.364s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 169.210s  | 169.210s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.175s  |1200.175s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.526s  |1200.526s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 446.893s  | 446.893s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   5.987s  |   5.987s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.207s  |1200.207s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1202.488s  |1202.488s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.292s  |1200.292s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.325s  |1200.325s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   5.707s  |   5.707s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1047.962s  |1047.962s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
</details>
