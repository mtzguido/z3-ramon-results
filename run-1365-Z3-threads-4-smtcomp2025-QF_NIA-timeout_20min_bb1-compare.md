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
Job tag: Z3-threads-4-smtcomp2025-QF_NIA-timeout_20min_bb1
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6b8cb1099d311aac105cfc6fa658466f4ef6af67
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=1"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore unrelated code to master

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-smtcomp2025-QF_NIA-timeout_20min_bb1
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6b8cb1099d311aac105cfc6fa658466f4ef6af67
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=1"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore unrelated code to master

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1260.138s  |1260.138s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1260.182s  |1260.182s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  75.594s  |  75.594s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1260.150s  |1260.150s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1260.254s  |1260.254s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1260.107s  |1260.107s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1260.203s  |1260.203s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1260.203s  |1260.203s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.123s  |  12.123s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  22.128s  |  22.128s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1260.274s  |1260.274s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 910.267s  | 910.267s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  23.203s  |  23.203s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 320.703s  | 320.703s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  40.699s  |  40.699s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.296s  |   4.296s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 446.317s  | 446.317s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1260.088s  |1260.088s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1260.113s  |1260.113s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1260.138s  |1260.138s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1260.182s  |1260.182s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  75.594s  |  75.594s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1260.150s  |1260.150s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1260.254s  |1260.254s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1260.107s  |1260.107s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1260.203s  |1260.203s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1260.203s  |1260.203s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.123s  |  12.123s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  22.128s  |  22.128s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1260.274s  |1260.274s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 910.267s  | 910.267s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  23.203s  |  23.203s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 320.703s  | 320.703s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  40.699s  |  40.699s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.296s  |   4.296s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 446.317s  | 446.317s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1260.088s  |1260.088s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1260.113s  |1260.113s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1260.138s  |1260.138s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1260.182s  |1260.182s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  75.594s  |  75.594s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1260.150s  |1260.150s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1260.254s  |1260.254s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1260.107s  |1260.107s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1260.203s  |1260.203s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1260.203s  |1260.203s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.123s  |  12.123s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  22.128s  |  22.128s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1260.274s  |1260.274s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 910.267s  | 910.267s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  23.203s  |  23.203s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 320.703s  | 320.703s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  40.699s  |  40.699s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.296s  |   4.296s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 446.317s  | 446.317s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1260.088s  |1260.088s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1260.113s  |1260.113s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1260.138s  |1260.138s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1260.182s  |1260.182s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  75.594s  |  75.594s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1260.150s  |1260.150s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1260.254s  |1260.254s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1260.107s  |1260.107s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1260.203s  |1260.203s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1260.203s  |1260.203s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.123s  |  12.123s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  22.128s  |  22.128s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1260.274s  |1260.274s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 910.267s  | 910.267s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  23.203s  |  23.203s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 320.703s  | 320.703s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  40.699s  |  40.699s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.296s  |   4.296s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 446.317s  | 446.317s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1260.088s  |1260.088s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1260.113s  |1260.113s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1261.367s |14.585GiB|
|scrambled73755.smt2                                                                        |1260.336s |1795.0MiB|
|scrambled47700.smt2                                                                        |1260.327s |2739.0MiB|
|scrambled82760.smt2                                                                        |1260.305s |2045.0MiB|
|scrambled130111.smt2                                                                       |1260.274s |1217.0MiB|
|scrambled108663.smt2                                                                       |1260.254s |2757.0MiB|
|scrambled91750.smt2                                                                        |1260.219s |1314.0MiB|
|scrambled122926.smt2                                                                       |1260.203s |1867.0MiB|
|scrambled12033.smt2                                                                        |1260.203s |1436.0MiB|
|scrambled39467.smt2                                                                        |1260.191s |1252.0MiB|
|scrambled8852.smt2                                                                         |1260.187s |1245.0MiB|
|scrambled101716.smt2                                                                       |1260.182s |726.0MiB|
|scrambled87588.smt2                                                                        |1260.160s |1130.0MiB|
|scrambled108406.smt2                                                                       |1260.150s |1038.0MiB|
|scrambled58311.smt2                                                                        |1260.149s |1335.0MiB|
|scrambled38587.smt2                                                                        |1260.148s |650.0MiB|
|scrambled41135.smt2                                                                        |1260.147s |1391.0MiB|
|scrambled96401.smt2                                                                        |1260.142s |885.0MiB|
|scrambled100714.smt2                                                                       |1260.138s |785.0MiB|
|scrambled73281.smt2                                                                        |1260.133s |1144.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1261.367s |14.585GiB|
|scrambled73755.smt2                                                                        |1260.336s |1795.0MiB|
|scrambled47700.smt2                                                                        |1260.327s |2739.0MiB|
|scrambled82760.smt2                                                                        |1260.305s |2045.0MiB|
|scrambled130111.smt2                                                                       |1260.274s |1217.0MiB|
|scrambled108663.smt2                                                                       |1260.254s |2757.0MiB|
|scrambled91750.smt2                                                                        |1260.219s |1314.0MiB|
|scrambled122926.smt2                                                                       |1260.203s |1867.0MiB|
|scrambled12033.smt2                                                                        |1260.203s |1436.0MiB|
|scrambled39467.smt2                                                                        |1260.191s |1252.0MiB|
|scrambled8852.smt2                                                                         |1260.187s |1245.0MiB|
|scrambled101716.smt2                                                                       |1260.182s |726.0MiB|
|scrambled87588.smt2                                                                        |1260.160s |1130.0MiB|
|scrambled108406.smt2                                                                       |1260.150s |1038.0MiB|
|scrambled58311.smt2                                                                        |1260.149s |1335.0MiB|
|scrambled38587.smt2                                                                        |1260.148s |650.0MiB|
|scrambled41135.smt2                                                                        |1260.147s |1391.0MiB|
|scrambled96401.smt2                                                                        |1260.142s |885.0MiB|
|scrambled100714.smt2                                                                       |1260.138s |785.0MiB|
|scrambled73281.smt2                                                                        |1260.133s |1144.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |785.0MiB|785.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |726.0MiB|726.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |195.0MiB|195.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1038.0MiB|1038.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2757.0MiB|2757.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |724.0MiB|724.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |1436.0MiB|1436.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |1867.0MiB|1867.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |220.0MiB|220.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |226.0MiB|226.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1217.0MiB|1217.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |3675.0MiB|3675.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |2097.0MiB|2097.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |166.0MiB|166.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |119.0MiB|119.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |631.0MiB|631.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |108.0MiB|108.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |573.0MiB|573.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |792.0MiB|792.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |785.0MiB|785.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |726.0MiB|726.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |195.0MiB|195.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1038.0MiB|1038.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2757.0MiB|2757.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |724.0MiB|724.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |1436.0MiB|1436.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |1867.0MiB|1867.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |220.0MiB|220.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |226.0MiB|226.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1217.0MiB|1217.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |3675.0MiB|3675.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |2097.0MiB|2097.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |166.0MiB|166.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |119.0MiB|119.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |631.0MiB|631.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |108.0MiB|108.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |573.0MiB|573.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |792.0MiB|792.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |785.0MiB|785.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |726.0MiB|726.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |195.0MiB|195.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1038.0MiB|1038.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2757.0MiB|2757.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |724.0MiB|724.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |1436.0MiB|1436.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |1867.0MiB|1867.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |220.0MiB|220.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |226.0MiB|226.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1217.0MiB|1217.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |3675.0MiB|3675.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |2097.0MiB|2097.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |166.0MiB|166.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |119.0MiB|119.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |631.0MiB|631.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |108.0MiB|108.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |573.0MiB|573.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |792.0MiB|792.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |785.0MiB|785.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |726.0MiB|726.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |195.0MiB|195.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1038.0MiB|1038.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2757.0MiB|2757.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |724.0MiB|724.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |1436.0MiB|1436.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |1867.0MiB|1867.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |220.0MiB|220.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |226.0MiB|226.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1217.0MiB|1217.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |3675.0MiB|3675.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |2097.0MiB|2097.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |166.0MiB|166.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |119.0MiB|119.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |631.0MiB|631.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |108.0MiB|108.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |573.0MiB|573.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |792.0MiB|792.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1261.367s |14.585GiB|
|scrambled14845.smt2                                                                        | 910.267s |3675.0MiB|
|scrambled108663.smt2                                                                       |1260.254s |2757.0MiB|
|scrambled47700.smt2                                                                        |1260.327s |2739.0MiB|
|scrambled28176.smt2                                                                        | 320.703s |2097.0MiB|
|scrambled82760.smt2                                                                        |1260.305s |2045.0MiB|
|scrambled122926.smt2                                                                       |1260.203s |1867.0MiB|
|scrambled73755.smt2                                                                        |1260.336s |1795.0MiB|
|scrambled12033.smt2                                                                        |1260.203s |1436.0MiB|
|scrambled41135.smt2                                                                        |1260.147s |1391.0MiB|
|scrambled58311.smt2                                                                        |1260.149s |1335.0MiB|
|scrambled91750.smt2                                                                        |1260.219s |1314.0MiB|
|scrambled39467.smt2                                                                        |1260.191s |1252.0MiB|
|scrambled8852.smt2                                                                         |1260.187s |1245.0MiB|
|scrambled130111.smt2                                                                       |1260.274s |1217.0MiB|
|scrambled73281.smt2                                                                        |1260.133s |1144.0MiB|
|scrambled87588.smt2                                                                        |1260.160s |1130.0MiB|
|scrambled108406.smt2                                                                       |1260.150s |1038.0MiB|
|scrambled97386.smt2                                                                        |1260.126s |925.0MiB|
|scrambled96401.smt2                                                                        |1260.142s |885.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1261.367s |14.585GiB|
|scrambled14845.smt2                                                                        | 910.267s |3675.0MiB|
|scrambled108663.smt2                                                                       |1260.254s |2757.0MiB|
|scrambled47700.smt2                                                                        |1260.327s |2739.0MiB|
|scrambled28176.smt2                                                                        | 320.703s |2097.0MiB|
|scrambled82760.smt2                                                                        |1260.305s |2045.0MiB|
|scrambled122926.smt2                                                                       |1260.203s |1867.0MiB|
|scrambled73755.smt2                                                                        |1260.336s |1795.0MiB|
|scrambled12033.smt2                                                                        |1260.203s |1436.0MiB|
|scrambled41135.smt2                                                                        |1260.147s |1391.0MiB|
|scrambled58311.smt2                                                                        |1260.149s |1335.0MiB|
|scrambled91750.smt2                                                                        |1260.219s |1314.0MiB|
|scrambled39467.smt2                                                                        |1260.191s |1252.0MiB|
|scrambled8852.smt2                                                                         |1260.187s |1245.0MiB|
|scrambled130111.smt2                                                                       |1260.274s |1217.0MiB|
|scrambled73281.smt2                                                                        |1260.133s |1144.0MiB|
|scrambled87588.smt2                                                                        |1260.160s |1130.0MiB|
|scrambled108406.smt2                                                                       |1260.150s |1038.0MiB|
|scrambled97386.smt2                                                                        |1260.126s |925.0MiB|
|scrambled96401.smt2                                                                        |1260.142s |885.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1260.138s  |1260.138s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1260.182s  |1260.182s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  75.594s  |  75.594s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1260.150s  |1260.150s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1260.254s  |1260.254s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1260.107s  |1260.107s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1260.203s  |1260.203s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1260.203s  |1260.203s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.123s  |  12.123s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  22.128s  |  22.128s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1260.274s  |1260.274s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 910.267s  | 910.267s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  23.203s  |  23.203s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 320.703s  | 320.703s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  40.699s  |  40.699s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.296s  |   4.296s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 446.317s  | 446.317s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1260.088s  |1260.088s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1260.113s  |1260.113s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1260.148s  |1260.148s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1260.191s  |1260.191s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1260.147s  |1260.147s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1260.327s  |1260.327s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   7.975s  |   7.975s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.899s  |   0.899s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1260.149s  |1260.149s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 162.895s  | 162.895s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1260.125s  |1260.125s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1260.133s  |1260.133s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1260.336s  |1260.336s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1260.111s  |1260.111s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 378.809s  | 378.809s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   7.914s  |   7.914s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1260.305s  |1260.305s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1261.367s  |1261.367s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1260.160s  |1260.160s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1260.187s  |1260.187s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1260.219s  |1260.219s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   6.026s  |   6.026s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1260.142s  |1260.142s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1260.126s  |1260.126s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1260.086s  |1260.086s  |   0.000s  | 0.0%|
</details>
