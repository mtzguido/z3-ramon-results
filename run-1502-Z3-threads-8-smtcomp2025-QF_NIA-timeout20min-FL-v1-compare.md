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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-FL-v1
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 9802bb4838b72199dab085698cfcfdc169ab06e5
Z3 branch: 9802bb4838b72199dab085698cfcfdc169ab06e5
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.failed_literal_backbones=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: ablate continuous FL checking

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-FL-v1
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 9802bb4838b72199dab085698cfcfdc169ab06e5
Z3 branch: 9802bb4838b72199dab085698cfcfdc169ab06e5
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.failed_literal_backbones=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: ablate continuous FL checking

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  49.913s  |  49.913s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.177s  |1200.177s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.310s  |1200.310s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.413s  |1200.413s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.969s  |   9.969s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  16.327s  |  16.327s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.327s  |1200.327s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 585.197s  | 585.197s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.664s  |  13.664s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   3.646s  |   3.646s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  23.673s  |  23.673s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.592s  |   3.592s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  13.153s  |  13.153s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.235s  |1200.235s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  49.913s  |  49.913s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.177s  |1200.177s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.310s  |1200.310s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.413s  |1200.413s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.969s  |   9.969s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  16.327s  |  16.327s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.327s  |1200.327s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 585.197s  | 585.197s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.664s  |  13.664s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   3.646s  |   3.646s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  23.673s  |  23.673s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.592s  |   3.592s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  13.153s  |  13.153s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.235s  |1200.235s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  49.913s  |  49.913s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.177s  |1200.177s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.310s  |1200.310s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.413s  |1200.413s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.969s  |   9.969s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  16.327s  |  16.327s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.327s  |1200.327s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 585.197s  | 585.197s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.664s  |  13.664s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   3.646s  |   3.646s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  23.673s  |  23.673s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.592s  |   3.592s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  13.153s  |  13.153s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.235s  |1200.235s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  49.913s  |  49.913s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.177s  |1200.177s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.310s  |1200.310s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.413s  |1200.413s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.969s  |   9.969s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  16.327s  |  16.327s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.327s  |1200.327s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 585.197s  | 585.197s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.664s  |  13.664s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   3.646s  |   3.646s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  23.673s  |  23.673s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.592s  |   3.592s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  13.153s  |  13.153s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.235s  |1200.235s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.426s |25.497GiB|
|scrambled73755.smt2                                                                        |1200.533s |3725.0MiB|
|scrambled122926.smt2                                                                       |1200.413s |3334.0MiB|
|scrambled91750.smt2                                                                        |1200.409s |2329.0MiB|
|scrambled82760.smt2                                                                        |1200.376s |2168.0MiB|
|scrambled130111.smt2                                                                       |1200.327s |2174.0MiB|
|scrambled108406.smt2                                                                       |1200.319s |2510.0MiB|
|scrambled73281.smt2                                                                        |1200.314s |2500.0MiB|
|scrambled12033.smt2                                                                        |1200.310s |2636.0MiB|
|scrambled87588.smt2                                                                        |1200.295s |2315.0MiB|
|scrambled108663.smt2                                                                       |1200.284s |2629.0MiB|
|scrambled47700.smt2                                                                        |1200.278s |2047.0MiB|
|scrambled9883.smt2                                                                         |1200.258s |1493.0MiB|
|scrambled79354.smt2                                                                        |1200.253s |1607.0MiB|
|scrambled8852.smt2                                                                         |1200.245s |1532.0MiB|
|scrambled39467.smt2                                                                        |1200.240s |1751.0MiB|
|scrambled36790.smt2                                                                        |1200.235s |1542.0MiB|
|scrambled62032.smt2                                                                        |1200.220s |1503.0MiB|
|scrambled101716.smt2                                                                       |1200.214s |1387.0MiB|
|scrambled96401.smt2                                                                        |1200.212s |1355.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.426s |25.497GiB|
|scrambled73755.smt2                                                                        |1200.533s |3725.0MiB|
|scrambled122926.smt2                                                                       |1200.413s |3334.0MiB|
|scrambled91750.smt2                                                                        |1200.409s |2329.0MiB|
|scrambled82760.smt2                                                                        |1200.376s |2168.0MiB|
|scrambled130111.smt2                                                                       |1200.327s |2174.0MiB|
|scrambled108406.smt2                                                                       |1200.319s |2510.0MiB|
|scrambled73281.smt2                                                                        |1200.314s |2500.0MiB|
|scrambled12033.smt2                                                                        |1200.310s |2636.0MiB|
|scrambled87588.smt2                                                                        |1200.295s |2315.0MiB|
|scrambled108663.smt2                                                                       |1200.284s |2629.0MiB|
|scrambled47700.smt2                                                                        |1200.278s |2047.0MiB|
|scrambled9883.smt2                                                                         |1200.258s |1493.0MiB|
|scrambled79354.smt2                                                                        |1200.253s |1607.0MiB|
|scrambled8852.smt2                                                                         |1200.245s |1532.0MiB|
|scrambled39467.smt2                                                                        |1200.240s |1751.0MiB|
|scrambled36790.smt2                                                                        |1200.235s |1542.0MiB|
|scrambled62032.smt2                                                                        |1200.220s |1503.0MiB|
|scrambled101716.smt2                                                                       |1200.214s |1387.0MiB|
|scrambled96401.smt2                                                                        |1200.212s |1355.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1191.0MiB|1191.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1387.0MiB|1387.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |347.0MiB|347.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2510.0MiB|2510.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2629.0MiB|2629.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1373.0MiB|1373.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2636.0MiB|2636.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3334.0MiB|3334.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |410.0MiB|410.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |365.0MiB|365.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2174.0MiB|2174.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5957.0MiB|5957.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |968.0MiB|968.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |364.0MiB|364.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |228.0MiB|228.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |567.0MiB|567.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1388.0MiB|1388.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1542.0MiB|1542.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1191.0MiB|1191.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1387.0MiB|1387.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |347.0MiB|347.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2510.0MiB|2510.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2629.0MiB|2629.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1373.0MiB|1373.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2636.0MiB|2636.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3334.0MiB|3334.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |410.0MiB|410.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |365.0MiB|365.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2174.0MiB|2174.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5957.0MiB|5957.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |968.0MiB|968.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |364.0MiB|364.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |228.0MiB|228.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |567.0MiB|567.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1388.0MiB|1388.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1542.0MiB|1542.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1191.0MiB|1191.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1387.0MiB|1387.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |347.0MiB|347.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2510.0MiB|2510.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2629.0MiB|2629.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1373.0MiB|1373.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2636.0MiB|2636.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3334.0MiB|3334.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |410.0MiB|410.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |365.0MiB|365.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2174.0MiB|2174.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5957.0MiB|5957.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |968.0MiB|968.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |364.0MiB|364.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |228.0MiB|228.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |567.0MiB|567.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1388.0MiB|1388.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1542.0MiB|1542.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1191.0MiB|1191.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1387.0MiB|1387.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |347.0MiB|347.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2510.0MiB|2510.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2629.0MiB|2629.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1373.0MiB|1373.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2636.0MiB|2636.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3334.0MiB|3334.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |410.0MiB|410.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |365.0MiB|365.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2174.0MiB|2174.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5957.0MiB|5957.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |968.0MiB|968.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |364.0MiB|364.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |228.0MiB|228.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |567.0MiB|567.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1388.0MiB|1388.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1542.0MiB|1542.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.426s |25.497GiB|
|scrambled14845.smt2                                                                        | 585.197s |5957.0MiB|
|scrambled73755.smt2                                                                        |1200.533s |3725.0MiB|
|scrambled122926.smt2                                                                       |1200.413s |3334.0MiB|
|scrambled12033.smt2                                                                        |1200.310s |2636.0MiB|
|scrambled108663.smt2                                                                       |1200.284s |2629.0MiB|
|scrambled108406.smt2                                                                       |1200.319s |2510.0MiB|
|scrambled73281.smt2                                                                        |1200.314s |2500.0MiB|
|scrambled91750.smt2                                                                        |1200.409s |2329.0MiB|
|scrambled87588.smt2                                                                        |1200.295s |2315.0MiB|
|scrambled130111.smt2                                                                       |1200.327s |2174.0MiB|
|scrambled82760.smt2                                                                        |1200.376s |2168.0MiB|
|scrambled47700.smt2                                                                        |1200.278s |2047.0MiB|
|scrambled58311.smt2                                                                        |1200.198s |1830.0MiB|
|scrambled39467.smt2                                                                        |1200.240s |1751.0MiB|
|scrambled79354.smt2                                                                        |1200.253s |1607.0MiB|
|scrambled41135.smt2                                                                        |1200.193s |1570.0MiB|
|scrambled36790.smt2                                                                        |1200.235s |1542.0MiB|
|scrambled8852.smt2                                                                         |1200.245s |1532.0MiB|
|scrambled61060.smt2                                                                        | 157.923s |1524.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.426s |25.497GiB|
|scrambled14845.smt2                                                                        | 585.197s |5957.0MiB|
|scrambled73755.smt2                                                                        |1200.533s |3725.0MiB|
|scrambled122926.smt2                                                                       |1200.413s |3334.0MiB|
|scrambled12033.smt2                                                                        |1200.310s |2636.0MiB|
|scrambled108663.smt2                                                                       |1200.284s |2629.0MiB|
|scrambled108406.smt2                                                                       |1200.319s |2510.0MiB|
|scrambled73281.smt2                                                                        |1200.314s |2500.0MiB|
|scrambled91750.smt2                                                                        |1200.409s |2329.0MiB|
|scrambled87588.smt2                                                                        |1200.295s |2315.0MiB|
|scrambled130111.smt2                                                                       |1200.327s |2174.0MiB|
|scrambled82760.smt2                                                                        |1200.376s |2168.0MiB|
|scrambled47700.smt2                                                                        |1200.278s |2047.0MiB|
|scrambled58311.smt2                                                                        |1200.198s |1830.0MiB|
|scrambled39467.smt2                                                                        |1200.240s |1751.0MiB|
|scrambled79354.smt2                                                                        |1200.253s |1607.0MiB|
|scrambled41135.smt2                                                                        |1200.193s |1570.0MiB|
|scrambled36790.smt2                                                                        |1200.235s |1542.0MiB|
|scrambled8852.smt2                                                                         |1200.245s |1532.0MiB|
|scrambled61060.smt2                                                                        | 157.923s |1524.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  49.913s  |  49.913s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.177s  |1200.177s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.310s  |1200.310s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.413s  |1200.413s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.969s  |   9.969s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  16.327s  |  16.327s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.327s  |1200.327s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 585.197s  | 585.197s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  13.664s  |  13.664s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   3.646s  |   3.646s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  23.673s  |  23.673s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.592s  |   3.592s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  13.153s  |  13.153s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.235s  |1200.235s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.198s  |1200.198s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.240s  |1200.240s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.193s  |1200.193s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.278s  |1200.278s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   5.492s  |   5.492s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.934s  |   0.934s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.198s  |1200.198s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 157.923s  | 157.923s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.220s  |1200.220s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.314s  |1200.314s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.533s  |1200.533s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.253s  |1200.253s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 213.560s  | 213.560s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   5.356s  |   5.356s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.376s  |1200.376s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1202.426s  |1202.426s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.295s  |1200.295s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.245s  |1200.245s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.409s  |1200.409s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   5.672s  |   5.672s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.175s  |1200.175s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
</details>
