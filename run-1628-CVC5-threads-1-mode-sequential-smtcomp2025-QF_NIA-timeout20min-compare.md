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
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-1-mode-sequential-smtcomp2025-QF_NIA-timeout20min
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: sequential
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter decision-cube"
cvc5 partition budget: 1
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 1
cvc5 timeout: 1200
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_NIA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-1-mode-sequential-smtcomp2025-QF_NIA-timeout20min
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: sequential
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter decision-cube"
cvc5 partition budget: 1
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 1
cvc5 timeout: 1200
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_NIA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        | 642.207s  | 642.207s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |1070.596s  |1070.596s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         | 670.292s  | 670.292s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.118s  |1200.118s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        | 642.207s  | 642.207s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |1070.596s  |1070.596s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         | 670.292s  | 670.292s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.118s  |1200.118s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        | 642.207s  | 642.207s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |1070.596s  |1070.596s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         | 670.292s  | 670.292s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.118s  |1200.118s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        | 642.207s  | 642.207s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |1070.596s  |1070.596s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         | 670.292s  | 670.292s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.118s  |1200.118s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.245s |1687.0MiB|
|scrambled73755.smt2                                                                        |1200.150s |694.0MiB|
|scrambled38587.smt2                                                                        |1200.137s |593.0MiB|
|scrambled31071.smt2                                                                        |1200.135s |561.0MiB|
|scrambled62032.smt2                                                                        |1200.134s |684.0MiB|
|scrambled12033.smt2                                                                        |1200.128s |468.0MiB|
|scrambled9548.smt2                                                                         |1200.127s |503.0MiB|
|scrambled36790.smt2                                                                        |1200.118s |391.0MiB|
|scrambled96401.smt2                                                                        |1200.117s |386.0MiB|
|scrambled79354.smt2                                                                        |1200.117s |452.0MiB|
|scrambled100714.smt2                                                                       |1200.114s |387.0MiB|
|scrambled29780.smt2                                                                        |1200.109s |551.0MiB|
|scrambled9883.smt2                                                                         |1200.107s |818.0MiB|
|scrambled28176.smt2                                                                        |1200.107s |317.0MiB|
|scrambled101716.smt2                                                                       |1200.107s |568.0MiB|
|scrambled98111.smt2                                                                        |1200.103s |321.0MiB|
|scrambled58311.smt2                                                                        |1200.099s |450.0MiB|
|scrambled31575.smt2                                                                        |1200.095s |419.0MiB|
|scrambled108663.smt2                                                                       |1200.092s |382.0MiB|
|scrambled61060.smt2                                                                        |1200.090s |323.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.245s |1687.0MiB|
|scrambled73755.smt2                                                                        |1200.150s |694.0MiB|
|scrambled38587.smt2                                                                        |1200.137s |593.0MiB|
|scrambled31071.smt2                                                                        |1200.135s |561.0MiB|
|scrambled62032.smt2                                                                        |1200.134s |684.0MiB|
|scrambled12033.smt2                                                                        |1200.128s |468.0MiB|
|scrambled9548.smt2                                                                         |1200.127s |503.0MiB|
|scrambled36790.smt2                                                                        |1200.118s |391.0MiB|
|scrambled96401.smt2                                                                        |1200.117s |386.0MiB|
|scrambled79354.smt2                                                                        |1200.117s |452.0MiB|
|scrambled100714.smt2                                                                       |1200.114s |387.0MiB|
|scrambled29780.smt2                                                                        |1200.109s |551.0MiB|
|scrambled9883.smt2                                                                         |1200.107s |818.0MiB|
|scrambled28176.smt2                                                                        |1200.107s |317.0MiB|
|scrambled101716.smt2                                                                       |1200.107s |568.0MiB|
|scrambled98111.smt2                                                                        |1200.103s |321.0MiB|
|scrambled58311.smt2                                                                        |1200.099s |450.0MiB|
|scrambled31575.smt2                                                                        |1200.095s |419.0MiB|
|scrambled108663.smt2                                                                       |1200.092s |382.0MiB|
|scrambled61060.smt2                                                                        |1200.090s |323.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |387.0MiB|387.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |568.0MiB|568.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |186.0MiB|186.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |302.0MiB|302.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |382.0MiB|382.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |328.0MiB|328.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |468.0MiB|468.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |304.0MiB|304.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |401.0MiB|401.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |390.0MiB|390.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |255.0MiB|255.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |362.0MiB|362.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |383.0MiB|383.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |317.0MiB|317.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |172.0MiB|172.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |561.0MiB|561.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |419.0MiB|419.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |278.0MiB|278.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |391.0MiB|391.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |387.0MiB|387.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |568.0MiB|568.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |186.0MiB|186.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |302.0MiB|302.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |382.0MiB|382.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |328.0MiB|328.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |468.0MiB|468.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |304.0MiB|304.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |401.0MiB|401.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |390.0MiB|390.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |255.0MiB|255.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |362.0MiB|362.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |383.0MiB|383.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |317.0MiB|317.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |172.0MiB|172.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |561.0MiB|561.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |419.0MiB|419.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |278.0MiB|278.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |391.0MiB|391.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |387.0MiB|387.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |568.0MiB|568.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |186.0MiB|186.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |302.0MiB|302.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |382.0MiB|382.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |328.0MiB|328.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |468.0MiB|468.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |304.0MiB|304.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |401.0MiB|401.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |390.0MiB|390.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |255.0MiB|255.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |362.0MiB|362.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |383.0MiB|383.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |317.0MiB|317.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |172.0MiB|172.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |561.0MiB|561.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |419.0MiB|419.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |278.0MiB|278.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |391.0MiB|391.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |387.0MiB|387.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |568.0MiB|568.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |186.0MiB|186.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |302.0MiB|302.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |382.0MiB|382.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |328.0MiB|328.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |468.0MiB|468.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |304.0MiB|304.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |401.0MiB|401.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |390.0MiB|390.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |255.0MiB|255.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |362.0MiB|362.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |383.0MiB|383.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |317.0MiB|317.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |172.0MiB|172.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |561.0MiB|561.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |419.0MiB|419.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |278.0MiB|278.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |391.0MiB|391.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.245s |1687.0MiB|
|scrambled9883.smt2                                                                         |1200.107s |818.0MiB|
|scrambled73755.smt2                                                                        |1200.150s |694.0MiB|
|scrambled62032.smt2                                                                        |1200.134s |684.0MiB|
|scrambled38587.smt2                                                                        |1200.137s |593.0MiB|
|scrambled101716.smt2                                                                       |1200.107s |568.0MiB|
|scrambled31071.smt2                                                                        |1200.135s |561.0MiB|
|scrambled29780.smt2                                                                        |1200.109s |551.0MiB|
|scrambled9548.smt2                                                                         |1200.127s |503.0MiB|
|scrambled12033.smt2                                                                        |1200.128s |468.0MiB|
|scrambled79354.smt2                                                                        |1200.117s |452.0MiB|
|scrambled58311.smt2                                                                        |1200.099s |450.0MiB|
|scrambled73281.smt2                                                                        |1200.070s |421.0MiB|
|scrambled31575.smt2                                                                        |1200.095s |419.0MiB|
|scrambled129467.smt2                                                                       | 642.207s |401.0MiB|
|scrambled39467.smt2                                                                        |1200.063s |399.0MiB|
|scrambled36790.smt2                                                                        |1200.118s |391.0MiB|
|scrambled12959.smt2                                                                        |1200.059s |390.0MiB|
|scrambled100714.smt2                                                                       |1200.114s |387.0MiB|
|scrambled96401.smt2                                                                        |1200.117s |386.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.245s |1687.0MiB|
|scrambled9883.smt2                                                                         |1200.107s |818.0MiB|
|scrambled73755.smt2                                                                        |1200.150s |694.0MiB|
|scrambled62032.smt2                                                                        |1200.134s |684.0MiB|
|scrambled38587.smt2                                                                        |1200.137s |593.0MiB|
|scrambled101716.smt2                                                                       |1200.107s |568.0MiB|
|scrambled31071.smt2                                                                        |1200.135s |561.0MiB|
|scrambled29780.smt2                                                                        |1200.109s |551.0MiB|
|scrambled9548.smt2                                                                         |1200.127s |503.0MiB|
|scrambled12033.smt2                                                                        |1200.128s |468.0MiB|
|scrambled79354.smt2                                                                        |1200.117s |452.0MiB|
|scrambled58311.smt2                                                                        |1200.099s |450.0MiB|
|scrambled73281.smt2                                                                        |1200.070s |421.0MiB|
|scrambled31575.smt2                                                                        |1200.095s |419.0MiB|
|scrambled129467.smt2                                                                       | 642.207s |401.0MiB|
|scrambled39467.smt2                                                                        |1200.063s |399.0MiB|
|scrambled36790.smt2                                                                        |1200.118s |391.0MiB|
|scrambled12959.smt2                                                                        |1200.059s |390.0MiB|
|scrambled100714.smt2                                                                       |1200.114s |387.0MiB|
|scrambled96401.smt2                                                                        |1200.117s |386.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        | 642.207s  | 642.207s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |1070.596s  |1070.596s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         | 670.292s  | 670.292s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |  77.021s  |  77.021s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.150s  |1200.150s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1200.245s  |1200.245s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
</details>
