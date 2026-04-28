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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-v3
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 78d6305f18ab1b89acb75ef00b12e1e72ee3e423
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.failed_literal_backbones=false smt_parallel.num_global_bb_chunking_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: bb batch mode is continuous, with checks for new candidates after the first round

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-v3
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 78d6305f18ab1b89acb75ef00b12e1e72ee3e423
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.failed_literal_backbones=false smt_parallel.num_global_bb_chunking_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: bb batch mode is continuous, with checks for new candidates after the first round

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.203s  |1200.203s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.186s  |1200.186s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  25.461s  |  25.461s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.575s  |1200.575s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.475s  |1200.475s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.372s  |1200.372s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.493s  |1200.493s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.629s  |  12.629s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  13.869s  |  13.869s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.275s  |1200.275s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 625.450s  | 625.450s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.614s  |  13.614s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  40.587s  |  40.587s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  26.149s  |  26.149s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.963s  |   3.963s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 111.731s  | 111.731s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.144s  |1200.144s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.203s  |1200.203s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.203s  |1200.203s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.186s  |1200.186s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  25.461s  |  25.461s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.575s  |1200.575s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.475s  |1200.475s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.372s  |1200.372s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.493s  |1200.493s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.629s  |  12.629s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  13.869s  |  13.869s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.275s  |1200.275s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 625.450s  | 625.450s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.614s  |  13.614s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  40.587s  |  40.587s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  26.149s  |  26.149s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.963s  |   3.963s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 111.731s  | 111.731s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.144s  |1200.144s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.203s  |1200.203s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.203s  |1200.203s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.186s  |1200.186s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  25.461s  |  25.461s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.575s  |1200.575s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.475s  |1200.475s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.372s  |1200.372s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.493s  |1200.493s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.629s  |  12.629s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  13.869s  |  13.869s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.275s  |1200.275s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 625.450s  | 625.450s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.614s  |  13.614s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  40.587s  |  40.587s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  26.149s  |  26.149s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.963s  |   3.963s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 111.731s  | 111.731s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.144s  |1200.144s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.203s  |1200.203s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.203s  |1200.203s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.186s  |1200.186s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  25.461s  |  25.461s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.575s  |1200.575s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.475s  |1200.475s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.372s  |1200.372s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.493s  |1200.493s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.629s  |  12.629s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  13.869s  |  13.869s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.275s  |1200.275s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 625.450s  | 625.450s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.614s  |  13.614s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  40.587s  |  40.587s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  26.149s  |  26.149s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.963s  |   3.963s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 111.731s  | 111.731s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.144s  |1200.144s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.203s  |1200.203s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.111s |28.993GiB|
|scrambled73281.smt2                                                                        |1200.828s |8964.0MiB|
|scrambled108406.smt2                                                                       |1200.575s |4707.0MiB|
|scrambled73755.smt2                                                                        |1200.574s |5314.0MiB|
|scrambled58311.smt2                                                                        |1200.562s |2336.0MiB|
|scrambled122926.smt2                                                                       |1200.493s |3832.0MiB|
|scrambled108663.smt2                                                                       |1200.475s |3186.0MiB|
|scrambled12033.smt2                                                                        |1200.372s |2955.0MiB|
|scrambled41135.smt2                                                                        |1200.341s |2746.0MiB|
|scrambled82760.smt2                                                                        |1200.336s |2396.0MiB|
|scrambled91750.smt2                                                                        |1200.335s |2948.0MiB|
|scrambled62032.smt2                                                                        |1200.333s |2628.0MiB|
|scrambled47700.smt2                                                                        |1200.316s |2576.0MiB|
|scrambled79354.smt2                                                                        |1200.304s |1644.0MiB|
|scrambled87588.smt2                                                                        |1200.298s |1996.0MiB|
|scrambled39467.smt2                                                                        |1200.287s |2742.0MiB|
|scrambled130111.smt2                                                                       |1200.275s |2031.0MiB|
|scrambled97386.smt2                                                                        |1200.271s |1688.0MiB|
|scrambled119582.smt2                                                                       |1200.212s |1038.0MiB|
|scrambled38587.smt2                                                                        |1200.211s |1411.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.111s |28.993GiB|
|scrambled73281.smt2                                                                        |1200.828s |8964.0MiB|
|scrambled108406.smt2                                                                       |1200.575s |4707.0MiB|
|scrambled73755.smt2                                                                        |1200.574s |5314.0MiB|
|scrambled58311.smt2                                                                        |1200.562s |2336.0MiB|
|scrambled122926.smt2                                                                       |1200.493s |3832.0MiB|
|scrambled108663.smt2                                                                       |1200.475s |3186.0MiB|
|scrambled12033.smt2                                                                        |1200.372s |2955.0MiB|
|scrambled41135.smt2                                                                        |1200.341s |2746.0MiB|
|scrambled82760.smt2                                                                        |1200.336s |2396.0MiB|
|scrambled91750.smt2                                                                        |1200.335s |2948.0MiB|
|scrambled62032.smt2                                                                        |1200.333s |2628.0MiB|
|scrambled47700.smt2                                                                        |1200.316s |2576.0MiB|
|scrambled79354.smt2                                                                        |1200.304s |1644.0MiB|
|scrambled87588.smt2                                                                        |1200.298s |1996.0MiB|
|scrambled39467.smt2                                                                        |1200.287s |2742.0MiB|
|scrambled130111.smt2                                                                       |1200.275s |2031.0MiB|
|scrambled97386.smt2                                                                        |1200.271s |1688.0MiB|
|scrambled119582.smt2                                                                       |1200.212s |1038.0MiB|
|scrambled38587.smt2                                                                        |1200.211s |1411.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1216.0MiB|1216.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1406.0MiB|1406.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |329.0MiB|329.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |4707.0MiB|4707.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3186.0MiB|3186.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1038.0MiB|1038.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2955.0MiB|2955.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3832.0MiB|3832.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |443.0MiB|443.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |356.0MiB|356.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2031.0MiB|2031.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6791.0MiB|6791.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1071.0MiB|1071.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |665.0MiB|665.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |295.0MiB|295.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |304.0MiB|304.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |668.0MiB|668.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |932.0MiB|932.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1684.0MiB|1684.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1216.0MiB|1216.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1406.0MiB|1406.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |329.0MiB|329.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |4707.0MiB|4707.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3186.0MiB|3186.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1038.0MiB|1038.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2955.0MiB|2955.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3832.0MiB|3832.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |443.0MiB|443.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |356.0MiB|356.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2031.0MiB|2031.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6791.0MiB|6791.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1071.0MiB|1071.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |665.0MiB|665.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |295.0MiB|295.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |304.0MiB|304.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |668.0MiB|668.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |932.0MiB|932.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1684.0MiB|1684.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1216.0MiB|1216.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1406.0MiB|1406.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |329.0MiB|329.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |4707.0MiB|4707.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3186.0MiB|3186.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1038.0MiB|1038.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2955.0MiB|2955.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3832.0MiB|3832.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |443.0MiB|443.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |356.0MiB|356.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2031.0MiB|2031.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6791.0MiB|6791.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1071.0MiB|1071.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |665.0MiB|665.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |295.0MiB|295.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |304.0MiB|304.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |668.0MiB|668.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |932.0MiB|932.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1684.0MiB|1684.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1216.0MiB|1216.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1406.0MiB|1406.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |329.0MiB|329.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |4707.0MiB|4707.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3186.0MiB|3186.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1038.0MiB|1038.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2955.0MiB|2955.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3832.0MiB|3832.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |443.0MiB|443.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |356.0MiB|356.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2031.0MiB|2031.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6791.0MiB|6791.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1071.0MiB|1071.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |665.0MiB|665.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |295.0MiB|295.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |304.0MiB|304.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |668.0MiB|668.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |932.0MiB|932.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1684.0MiB|1684.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.111s |28.993GiB|
|scrambled73281.smt2                                                                        |1200.828s |8964.0MiB|
|scrambled14845.smt2                                                                        | 625.450s |6791.0MiB|
|scrambled73755.smt2                                                                        |1200.574s |5314.0MiB|
|scrambled108406.smt2                                                                       |1200.575s |4707.0MiB|
|scrambled122926.smt2                                                                       |1200.493s |3832.0MiB|
|scrambled108663.smt2                                                                       |1200.475s |3186.0MiB|
|scrambled12033.smt2                                                                        |1200.372s |2955.0MiB|
|scrambled91750.smt2                                                                        |1200.335s |2948.0MiB|
|scrambled41135.smt2                                                                        |1200.341s |2746.0MiB|
|scrambled39467.smt2                                                                        |1200.287s |2742.0MiB|
|scrambled62032.smt2                                                                        |1200.333s |2628.0MiB|
|scrambled47700.smt2                                                                        |1200.316s |2576.0MiB|
|scrambled82760.smt2                                                                        |1200.336s |2396.0MiB|
|scrambled58311.smt2                                                                        |1200.562s |2336.0MiB|
|scrambled130111.smt2                                                                       |1200.275s |2031.0MiB|
|scrambled87588.smt2                                                                        |1200.298s |1996.0MiB|
|scrambled96401.smt2                                                                        |1200.184s |1763.0MiB|
|scrambled61060.smt2                                                                        | 189.317s |1704.0MiB|
|scrambled97386.smt2                                                                        |1200.271s |1688.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.111s |28.993GiB|
|scrambled73281.smt2                                                                        |1200.828s |8964.0MiB|
|scrambled14845.smt2                                                                        | 625.450s |6791.0MiB|
|scrambled73755.smt2                                                                        |1200.574s |5314.0MiB|
|scrambled108406.smt2                                                                       |1200.575s |4707.0MiB|
|scrambled122926.smt2                                                                       |1200.493s |3832.0MiB|
|scrambled108663.smt2                                                                       |1200.475s |3186.0MiB|
|scrambled12033.smt2                                                                        |1200.372s |2955.0MiB|
|scrambled91750.smt2                                                                        |1200.335s |2948.0MiB|
|scrambled41135.smt2                                                                        |1200.341s |2746.0MiB|
|scrambled39467.smt2                                                                        |1200.287s |2742.0MiB|
|scrambled62032.smt2                                                                        |1200.333s |2628.0MiB|
|scrambled47700.smt2                                                                        |1200.316s |2576.0MiB|
|scrambled82760.smt2                                                                        |1200.336s |2396.0MiB|
|scrambled58311.smt2                                                                        |1200.562s |2336.0MiB|
|scrambled130111.smt2                                                                       |1200.275s |2031.0MiB|
|scrambled87588.smt2                                                                        |1200.298s |1996.0MiB|
|scrambled96401.smt2                                                                        |1200.184s |1763.0MiB|
|scrambled61060.smt2                                                                        | 189.317s |1704.0MiB|
|scrambled97386.smt2                                                                        |1200.271s |1688.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.203s  |1200.203s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.186s  |1200.186s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  25.461s  |  25.461s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.575s  |1200.575s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.475s  |1200.475s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.372s  |1200.372s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.493s  |1200.493s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.629s  |  12.629s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  13.869s  |  13.869s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.275s  |1200.275s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 625.450s  | 625.450s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.614s  |  13.614s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  40.587s  |  40.587s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  26.149s  |  26.149s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.963s  |   3.963s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 111.731s  | 111.731s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.144s  |1200.144s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.203s  |1200.203s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.211s  |1200.211s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.287s  |1200.287s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.341s  |1200.341s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.316s  |1200.316s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   5.800s  |   5.800s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.562s  |1200.562s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 189.317s  | 189.317s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.333s  |1200.333s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.828s  |1200.828s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.574s  |1200.574s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.304s  |1200.304s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 192.581s  | 192.581s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   6.605s  |   6.605s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.336s  |1200.336s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1203.111s  |1203.111s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.298s  |1200.298s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.335s  |1200.335s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   5.397s  |   5.397s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.271s  |1200.271s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.150s  |1200.150s  |   0.000s  | 0.0%|
</details>
