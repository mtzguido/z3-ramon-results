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
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_NIA-timeout20min-no_default_tactic}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_NIA-timeout20min-no_default_tactic}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.024s  |1200.024s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.029s  |1200.029s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.356s  |   9.356s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |   4.204s  |   4.204s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |  26.535s  |  26.535s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  15.070s  |  15.070s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   1.734s  |   1.734s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  37.640s  |  37.640s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   8.111s  |   8.111s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 172.083s  | 172.083s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.024s  |1200.024s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.029s  |1200.029s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.356s  |   9.356s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |   4.204s  |   4.204s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |  26.535s  |  26.535s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  15.070s  |  15.070s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   1.734s  |   1.734s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  37.640s  |  37.640s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   8.111s  |   8.111s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 172.083s  | 172.083s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.024s  |1200.024s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.029s  |1200.029s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.356s  |   9.356s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |   4.204s  |   4.204s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |  26.535s  |  26.535s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  15.070s  |  15.070s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   1.734s  |   1.734s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  37.640s  |  37.640s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   8.111s  |   8.111s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 172.083s  | 172.083s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.024s  |1200.024s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.029s  |1200.029s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.356s  |   9.356s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |   4.204s  |   4.204s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |  26.535s  |  26.535s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  15.070s  |  15.070s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   1.734s  |   1.734s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  37.640s  |  37.640s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   8.111s  |   8.111s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 172.083s  | 172.083s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.399s |3728.0MiB|
|scrambled87588.smt2                                                                        |1200.118s |913.0MiB|
|scrambled8852.smt2                                                                         |1200.084s |649.0MiB|
|scrambled73755.smt2                                                                        |1200.083s |532.0MiB|
|scrambled91750.smt2                                                                        |1200.059s |334.0MiB|
|scrambled82760.smt2                                                                        |1200.058s |196.0MiB|
|scrambled39467.smt2                                                                        |1200.056s |462.0MiB|
|scrambled47700.smt2                                                                        |1200.054s |425.0MiB|
|scrambled79354.smt2                                                                        |1200.050s |234.0MiB|
|scrambled122926.smt2                                                                       |1200.050s |363.0MiB|
|scrambled73281.smt2                                                                        |1200.048s |209.0MiB|
|scrambled12033.smt2                                                                        |1200.047s |311.0MiB|
|scrambled97386.smt2                                                                        |1200.046s |252.0MiB|
|scrambled130111.smt2                                                                       |1200.045s |200.0MiB|
|scrambled36790.smt2                                                                        |1200.044s |178.0MiB|
|scrambled108663.smt2                                                                       |1200.042s |229.0MiB|
|scrambled108406.smt2                                                                       |1200.041s |298.0MiB|
|scrambled96401.smt2                                                                        |1200.038s |309.0MiB|
|scrambled9883.smt2                                                                         |1200.037s |348.0MiB|
|scrambled98111.smt2                                                                        |1200.034s |89.464MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.399s |3728.0MiB|
|scrambled87588.smt2                                                                        |1200.118s |913.0MiB|
|scrambled8852.smt2                                                                         |1200.084s |649.0MiB|
|scrambled73755.smt2                                                                        |1200.083s |532.0MiB|
|scrambled91750.smt2                                                                        |1200.059s |334.0MiB|
|scrambled82760.smt2                                                                        |1200.058s |196.0MiB|
|scrambled39467.smt2                                                                        |1200.056s |462.0MiB|
|scrambled47700.smt2                                                                        |1200.054s |425.0MiB|
|scrambled79354.smt2                                                                        |1200.050s |234.0MiB|
|scrambled122926.smt2                                                                       |1200.050s |363.0MiB|
|scrambled73281.smt2                                                                        |1200.048s |209.0MiB|
|scrambled12033.smt2                                                                        |1200.047s |311.0MiB|
|scrambled97386.smt2                                                                        |1200.046s |252.0MiB|
|scrambled130111.smt2                                                                       |1200.045s |200.0MiB|
|scrambled36790.smt2                                                                        |1200.044s |178.0MiB|
|scrambled108663.smt2                                                                       |1200.042s |229.0MiB|
|scrambled108406.smt2                                                                       |1200.041s |298.0MiB|
|scrambled96401.smt2                                                                        |1200.038s |309.0MiB|
|scrambled9883.smt2                                                                         |1200.037s |348.0MiB|
|scrambled98111.smt2                                                                        |1200.034s |89.464MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |85.9MiB|85.9MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |191.0MiB|191.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |178.0MiB|178.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |298.0MiB|298.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |229.0MiB|229.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |201.0MiB|201.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |311.0MiB|311.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |363.0MiB|363.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |34.012MiB|34.012MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |29.264MiB|29.264MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |200.0MiB|200.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |178.0MiB|178.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |422.0MiB|422.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |30.648MiB|30.648MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |30.772MiB|30.772MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |80.776MiB|80.776MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |89.276MiB|89.276MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |175.0MiB|175.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |178.0MiB|178.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |85.9MiB|85.9MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |191.0MiB|191.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |178.0MiB|178.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |298.0MiB|298.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |229.0MiB|229.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |201.0MiB|201.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |311.0MiB|311.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |363.0MiB|363.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |34.012MiB|34.012MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |29.264MiB|29.264MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |200.0MiB|200.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |178.0MiB|178.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |422.0MiB|422.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |30.648MiB|30.648MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |30.772MiB|30.772MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |80.776MiB|80.776MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |89.276MiB|89.276MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |175.0MiB|175.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |178.0MiB|178.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |85.9MiB|85.9MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |191.0MiB|191.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |178.0MiB|178.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |298.0MiB|298.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |229.0MiB|229.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |201.0MiB|201.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |311.0MiB|311.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |363.0MiB|363.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |34.012MiB|34.012MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |29.264MiB|29.264MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |200.0MiB|200.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |178.0MiB|178.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |422.0MiB|422.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |30.648MiB|30.648MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |30.772MiB|30.772MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |80.776MiB|80.776MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |89.276MiB|89.276MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |175.0MiB|175.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |178.0MiB|178.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |85.9MiB|85.9MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |191.0MiB|191.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |178.0MiB|178.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |298.0MiB|298.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |229.0MiB|229.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |201.0MiB|201.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |311.0MiB|311.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |363.0MiB|363.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |34.012MiB|34.012MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |29.264MiB|29.264MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |200.0MiB|200.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |178.0MiB|178.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |422.0MiB|422.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |30.648MiB|30.648MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |30.772MiB|30.772MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |80.776MiB|80.776MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |89.276MiB|89.276MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |175.0MiB|175.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |178.0MiB|178.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.399s |3728.0MiB|
|scrambled87588.smt2                                                                        |1200.118s |913.0MiB|
|scrambled8852.smt2                                                                         |1200.084s |649.0MiB|
|scrambled73755.smt2                                                                        |1200.083s |532.0MiB|
|scrambled39467.smt2                                                                        |1200.056s |462.0MiB|
|scrambled47700.smt2                                                                        |1200.054s |425.0MiB|
|scrambled17293.smt2                                                                        |  15.070s |422.0MiB|
|scrambled41135.smt2                                                                        |1200.025s |408.0MiB|
|scrambled122926.smt2                                                                       |1200.050s |363.0MiB|
|scrambled9883.smt2                                                                         |1200.037s |348.0MiB|
|scrambled91750.smt2                                                                        |1200.059s |334.0MiB|
|scrambled38587.smt2                                                                        |1200.032s |334.0MiB|
|scrambled12033.smt2                                                                        |1200.047s |311.0MiB|
|scrambled96401.smt2                                                                        |1200.038s |309.0MiB|
|scrambled31071.smt2                                                                        | 172.083s |305.0MiB|
|scrambled108406.smt2                                                                       |1200.041s |298.0MiB|
|scrambled97386.smt2                                                                        |1200.046s |252.0MiB|
|scrambled79354.smt2                                                                        |1200.050s |234.0MiB|
|scrambled108663.smt2                                                                       |1200.042s |229.0MiB|
|scrambled73281.smt2                                                                        |1200.048s |209.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.399s |3728.0MiB|
|scrambled87588.smt2                                                                        |1200.118s |913.0MiB|
|scrambled8852.smt2                                                                         |1200.084s |649.0MiB|
|scrambled73755.smt2                                                                        |1200.083s |532.0MiB|
|scrambled39467.smt2                                                                        |1200.056s |462.0MiB|
|scrambled47700.smt2                                                                        |1200.054s |425.0MiB|
|scrambled17293.smt2                                                                        |  15.070s |422.0MiB|
|scrambled41135.smt2                                                                        |1200.025s |408.0MiB|
|scrambled122926.smt2                                                                       |1200.050s |363.0MiB|
|scrambled9883.smt2                                                                         |1200.037s |348.0MiB|
|scrambled91750.smt2                                                                        |1200.059s |334.0MiB|
|scrambled38587.smt2                                                                        |1200.032s |334.0MiB|
|scrambled12033.smt2                                                                        |1200.047s |311.0MiB|
|scrambled96401.smt2                                                                        |1200.038s |309.0MiB|
|scrambled31071.smt2                                                                        | 172.083s |305.0MiB|
|scrambled108406.smt2                                                                       |1200.041s |298.0MiB|
|scrambled97386.smt2                                                                        |1200.046s |252.0MiB|
|scrambled79354.smt2                                                                        |1200.050s |234.0MiB|
|scrambled108663.smt2                                                                       |1200.042s |229.0MiB|
|scrambled73281.smt2                                                                        |1200.048s |209.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.024s  |1200.024s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.029s  |1200.029s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.356s  |   9.356s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |   4.204s  |   4.204s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |  26.535s  |  26.535s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  15.070s  |  15.070s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   1.734s  |   1.734s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  37.640s  |  37.640s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   8.111s  |   8.111s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 172.083s  | 172.083s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |  13.744s  |  13.744s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |  12.098s  |  12.098s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.024s  |1200.024s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         |  96.484s  |  96.484s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.024s  |1200.024s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         |  76.194s  |  76.194s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |  10.010s  |  10.010s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1200.399s  |1200.399s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.084s  |1200.084s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   9.599s  |   9.599s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
</details>
