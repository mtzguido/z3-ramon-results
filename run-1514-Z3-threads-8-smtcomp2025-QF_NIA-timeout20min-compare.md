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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: a7fe211a307cd9ba9def6c904593b8e4d830835a
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: add bb detection via workers' units. also rename some variables

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: a7fe211a307cd9ba9def6c904593b8e4d830835a
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: add bb detection via workers' units. also rename some variables

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  24.723s  |  24.723s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.204s  |1200.204s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.247s  |1200.247s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.297s  |1200.297s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.301s  |1200.301s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.151s  |   9.151s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  11.898s  |  11.898s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.267s  |1200.267s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 604.371s  | 604.371s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.481s  |  13.481s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  31.604s  |  31.604s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  20.123s  |  20.123s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.912s  |   4.912s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 636.646s  | 636.646s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.133s  |1200.133s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 694.632s  | 694.632s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  24.723s  |  24.723s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.204s  |1200.204s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.247s  |1200.247s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.297s  |1200.297s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.301s  |1200.301s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.151s  |   9.151s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  11.898s  |  11.898s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.267s  |1200.267s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 604.371s  | 604.371s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.481s  |  13.481s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  31.604s  |  31.604s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  20.123s  |  20.123s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.912s  |   4.912s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 636.646s  | 636.646s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.133s  |1200.133s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 694.632s  | 694.632s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  24.723s  |  24.723s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.204s  |1200.204s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.247s  |1200.247s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.297s  |1200.297s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.301s  |1200.301s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.151s  |   9.151s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  11.898s  |  11.898s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.267s  |1200.267s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 604.371s  | 604.371s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.481s  |  13.481s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  31.604s  |  31.604s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  20.123s  |  20.123s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.912s  |   4.912s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 636.646s  | 636.646s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.133s  |1200.133s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 694.632s  | 694.632s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  24.723s  |  24.723s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.204s  |1200.204s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.247s  |1200.247s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.297s  |1200.297s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.301s  |1200.301s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.151s  |   9.151s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  11.898s  |  11.898s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.267s  |1200.267s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 604.371s  | 604.371s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.481s  |  13.481s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  31.604s  |  31.604s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  20.123s  |  20.123s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.912s  |   4.912s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 636.646s  | 636.646s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.133s  |1200.133s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 694.632s  | 694.632s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.337s |25.784GiB|
|scrambled73755.smt2                                                                        |1200.551s |4335.0MiB|
|scrambled47700.smt2                                                                        |1200.517s |4026.0MiB|
|scrambled87588.smt2                                                                        |1200.363s |2628.0MiB|
|scrambled122926.smt2                                                                       |1200.301s |2996.0MiB|
|scrambled12033.smt2                                                                        |1200.297s |2333.0MiB|
|scrambled82760.smt2                                                                        |1200.296s |2212.0MiB|
|scrambled130111.smt2                                                                       |1200.267s |2149.0MiB|
|scrambled91750.smt2                                                                        |1200.256s |1966.0MiB|
|scrambled108663.smt2                                                                       |1200.247s |2449.0MiB|
|scrambled41135.smt2                                                                        |1200.246s |1316.0MiB|
|scrambled97386.smt2                                                                        |1200.216s |1376.0MiB|
|scrambled96401.smt2                                                                        |1200.212s |1371.0MiB|
|scrambled108406.smt2                                                                       |1200.204s |1610.0MiB|
|scrambled62032.smt2                                                                        |1200.197s |1507.0MiB|
|scrambled39467.smt2                                                                        |1200.195s |1612.0MiB|
|scrambled73281.smt2                                                                        |1200.191s |1736.0MiB|
|scrambled38587.smt2                                                                        |1200.176s |1177.0MiB|
|scrambled79354.smt2                                                                        |1200.167s |1349.0MiB|
|scrambled119582.smt2                                                                       |1200.160s |1321.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.337s |25.784GiB|
|scrambled73755.smt2                                                                        |1200.551s |4335.0MiB|
|scrambled47700.smt2                                                                        |1200.517s |4026.0MiB|
|scrambled87588.smt2                                                                        |1200.363s |2628.0MiB|
|scrambled122926.smt2                                                                       |1200.301s |2996.0MiB|
|scrambled12033.smt2                                                                        |1200.297s |2333.0MiB|
|scrambled82760.smt2                                                                        |1200.296s |2212.0MiB|
|scrambled130111.smt2                                                                       |1200.267s |2149.0MiB|
|scrambled91750.smt2                                                                        |1200.256s |1966.0MiB|
|scrambled108663.smt2                                                                       |1200.247s |2449.0MiB|
|scrambled41135.smt2                                                                        |1200.246s |1316.0MiB|
|scrambled97386.smt2                                                                        |1200.216s |1376.0MiB|
|scrambled96401.smt2                                                                        |1200.212s |1371.0MiB|
|scrambled108406.smt2                                                                       |1200.204s |1610.0MiB|
|scrambled62032.smt2                                                                        |1200.197s |1507.0MiB|
|scrambled39467.smt2                                                                        |1200.195s |1612.0MiB|
|scrambled73281.smt2                                                                        |1200.191s |1736.0MiB|
|scrambled38587.smt2                                                                        |1200.176s |1177.0MiB|
|scrambled79354.smt2                                                                        |1200.167s |1349.0MiB|
|scrambled119582.smt2                                                                       |1200.160s |1321.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1097.0MiB|1097.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1216.0MiB|1216.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |317.0MiB|317.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1610.0MiB|1610.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2449.0MiB|2449.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1321.0MiB|1321.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2333.0MiB|2333.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |2996.0MiB|2996.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |364.0MiB|364.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |275.0MiB|275.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2149.0MiB|2149.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5850.0MiB|5850.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |855.0MiB|855.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |220.0MiB|220.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |1229.0MiB|1229.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |550.0MiB|550.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |938.0MiB|938.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1093.0MiB|1093.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1097.0MiB|1097.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1216.0MiB|1216.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |317.0MiB|317.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1610.0MiB|1610.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2449.0MiB|2449.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1321.0MiB|1321.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2333.0MiB|2333.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |2996.0MiB|2996.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |364.0MiB|364.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |275.0MiB|275.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2149.0MiB|2149.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5850.0MiB|5850.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |855.0MiB|855.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |220.0MiB|220.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |1229.0MiB|1229.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |550.0MiB|550.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |938.0MiB|938.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1093.0MiB|1093.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1097.0MiB|1097.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1216.0MiB|1216.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |317.0MiB|317.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1610.0MiB|1610.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2449.0MiB|2449.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1321.0MiB|1321.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2333.0MiB|2333.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |2996.0MiB|2996.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |364.0MiB|364.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |275.0MiB|275.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2149.0MiB|2149.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5850.0MiB|5850.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |855.0MiB|855.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |220.0MiB|220.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |1229.0MiB|1229.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |550.0MiB|550.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |938.0MiB|938.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1093.0MiB|1093.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1097.0MiB|1097.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1216.0MiB|1216.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |317.0MiB|317.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1610.0MiB|1610.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2449.0MiB|2449.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1321.0MiB|1321.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2333.0MiB|2333.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |2996.0MiB|2996.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |364.0MiB|364.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |275.0MiB|275.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2149.0MiB|2149.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5850.0MiB|5850.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |855.0MiB|855.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |220.0MiB|220.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |1229.0MiB|1229.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |550.0MiB|550.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |938.0MiB|938.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1093.0MiB|1093.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.337s |25.784GiB|
|scrambled14845.smt2                                                                        | 604.371s |5850.0MiB|
|scrambled73755.smt2                                                                        |1200.551s |4335.0MiB|
|scrambled47700.smt2                                                                        |1200.517s |4026.0MiB|
|scrambled122926.smt2                                                                       |1200.301s |2996.0MiB|
|scrambled87588.smt2                                                                        |1200.363s |2628.0MiB|
|scrambled108663.smt2                                                                       |1200.247s |2449.0MiB|
|scrambled12033.smt2                                                                        |1200.297s |2333.0MiB|
|scrambled82760.smt2                                                                        |1200.296s |2212.0MiB|
|scrambled130111.smt2                                                                       |1200.267s |2149.0MiB|
|scrambled91750.smt2                                                                        |1200.256s |1966.0MiB|
|scrambled73281.smt2                                                                        |1200.191s |1736.0MiB|
|scrambled39467.smt2                                                                        |1200.195s |1612.0MiB|
|scrambled108406.smt2                                                                       |1200.204s |1610.0MiB|
|scrambled62032.smt2                                                                        |1200.197s |1507.0MiB|
|scrambled61060.smt2                                                                        | 222.747s |1406.0MiB|
|scrambled97386.smt2                                                                        |1200.216s |1376.0MiB|
|scrambled96401.smt2                                                                        |1200.212s |1371.0MiB|
|scrambled79354.smt2                                                                        |1200.167s |1349.0MiB|
|scrambled119582.smt2                                                                       |1200.160s |1321.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.337s |25.784GiB|
|scrambled14845.smt2                                                                        | 604.371s |5850.0MiB|
|scrambled73755.smt2                                                                        |1200.551s |4335.0MiB|
|scrambled47700.smt2                                                                        |1200.517s |4026.0MiB|
|scrambled122926.smt2                                                                       |1200.301s |2996.0MiB|
|scrambled87588.smt2                                                                        |1200.363s |2628.0MiB|
|scrambled108663.smt2                                                                       |1200.247s |2449.0MiB|
|scrambled12033.smt2                                                                        |1200.297s |2333.0MiB|
|scrambled82760.smt2                                                                        |1200.296s |2212.0MiB|
|scrambled130111.smt2                                                                       |1200.267s |2149.0MiB|
|scrambled91750.smt2                                                                        |1200.256s |1966.0MiB|
|scrambled73281.smt2                                                                        |1200.191s |1736.0MiB|
|scrambled39467.smt2                                                                        |1200.195s |1612.0MiB|
|scrambled108406.smt2                                                                       |1200.204s |1610.0MiB|
|scrambled62032.smt2                                                                        |1200.197s |1507.0MiB|
|scrambled61060.smt2                                                                        | 222.747s |1406.0MiB|
|scrambled97386.smt2                                                                        |1200.216s |1376.0MiB|
|scrambled96401.smt2                                                                        |1200.212s |1371.0MiB|
|scrambled79354.smt2                                                                        |1200.167s |1349.0MiB|
|scrambled119582.smt2                                                                       |1200.160s |1321.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  24.723s  |  24.723s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.204s  |1200.204s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.247s  |1200.247s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.297s  |1200.297s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.301s  |1200.301s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.151s  |   9.151s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  11.898s  |  11.898s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.267s  |1200.267s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 604.371s  | 604.371s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.481s  |  13.481s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  31.604s  |  31.604s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  20.123s  |  20.123s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.912s  |   4.912s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 636.646s  | 636.646s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.133s  |1200.133s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         | 694.632s  | 694.632s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.176s  |1200.176s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.246s  |1200.246s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.517s  |1200.517s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   4.774s  |   4.774s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 222.747s  | 222.747s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.551s  |1200.551s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.167s  |1200.167s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 288.396s  | 288.396s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   5.827s  |   5.827s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.296s  |1200.296s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1202.337s  |1202.337s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.363s  |1200.363s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.256s  |1200.256s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   5.029s  |   5.029s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.216s  |1200.216s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.117s  |1200.117s  |   0.000s  | 0.0%|
</details>
