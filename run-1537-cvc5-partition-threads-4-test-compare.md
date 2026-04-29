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
Job tag: cvc5-partition-threads-4-test
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: 6024d13c001a5e01a37ca74152aabcfe6f2ac0ba
cvc5 branch: main
cvc5 mode: partition
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter decision-cube"
cvc5 partition budget: 4
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 4
cvc5 timeout: 1
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_NIA
cvc5 commit message: bv: Refactor BitVector to use uint32_t for size and indices. (#12629)

</pre>
# RHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: cvc5-partition-threads-4-test
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: 6024d13c001a5e01a37ca74152aabcfe6f2ac0ba
cvc5 branch: main
cvc5 mode: partition
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter decision-cube"
cvc5 partition budget: 4
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 4
cvc5 timeout: 1
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_NIA
cvc5 commit message: bv: Refactor BitVector to use uint32_t for size and indices. (#12629)

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled82760.smt2                                                                        |   0.046s |3976.0KiB|
|scrambled91750.smt2                                                                        |   0.042s |3640.0KiB|
|scrambled73755.smt2                                                                        |   0.042s |3856.0KiB|
|scrambled12959.smt2                                                                        |   0.041s |3740.0KiB|
|scrambled41135.smt2                                                                        |   0.032s |3480.0KiB|
|scrambled28176.smt2                                                                        |   0.032s |3660.0KiB|
|scrambled12033.smt2                                                                        |   0.032s |3316.0KiB|
|scrambled82407.smt2                                                                        |   0.031s |3360.0KiB|
|scrambled100714.smt2                                                                       |   0.031s |3256.0KiB|
|scrambled47700.smt2                                                                        |   0.031s |3596.0KiB|
|scrambled96401.smt2                                                                        |   0.030s |3908.0KiB|
|scrambled98111.smt2                                                                        |   0.030s |3076.0KiB|
|scrambled119582.smt2                                                                       |   0.030s |3884.0KiB|
|scrambled9548.smt2                                                                         |   0.030s |3212.0KiB|
|scrambled17293.smt2                                                                        |   0.029s |4112.0KiB|
|scrambled36790.smt2                                                                        |   0.029s |3300.0KiB|
|scrambled62032.smt2                                                                        |   0.029s |3596.0KiB|
|scrambled80288.smt2                                                                        |   0.029s |3640.0KiB|
|scrambled9883.smt2                                                                         |   0.029s |4000.0KiB|
|scrambled58311.smt2                                                                        |   0.028s |4468.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled82760.smt2                                                                        |   0.046s |3976.0KiB|
|scrambled91750.smt2                                                                        |   0.042s |3640.0KiB|
|scrambled73755.smt2                                                                        |   0.042s |3856.0KiB|
|scrambled12959.smt2                                                                        |   0.041s |3740.0KiB|
|scrambled41135.smt2                                                                        |   0.032s |3480.0KiB|
|scrambled28176.smt2                                                                        |   0.032s |3660.0KiB|
|scrambled12033.smt2                                                                        |   0.032s |3316.0KiB|
|scrambled82407.smt2                                                                        |   0.031s |3360.0KiB|
|scrambled100714.smt2                                                                       |   0.031s |3256.0KiB|
|scrambled47700.smt2                                                                        |   0.031s |3596.0KiB|
|scrambled96401.smt2                                                                        |   0.030s |3908.0KiB|
|scrambled98111.smt2                                                                        |   0.030s |3076.0KiB|
|scrambled119582.smt2                                                                       |   0.030s |3884.0KiB|
|scrambled9548.smt2                                                                         |   0.030s |3212.0KiB|
|scrambled17293.smt2                                                                        |   0.029s |4112.0KiB|
|scrambled36790.smt2                                                                        |   0.029s |3300.0KiB|
|scrambled62032.smt2                                                                        |   0.029s |3596.0KiB|
|scrambled80288.smt2                                                                        |   0.029s |3640.0KiB|
|scrambled9883.smt2                                                                         |   0.029s |4000.0KiB|
|scrambled58311.smt2                                                                        |   0.028s |4468.0KiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |3256.0KiB|3256.0KiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |4172.0KiB|4172.0KiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |3192.0KiB|3192.0KiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |3556.0KiB|3556.0KiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3572.0KiB|3572.0KiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |3884.0KiB|3884.0KiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |3316.0KiB|3316.0KiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3924.0KiB|3924.0KiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |3252.0KiB|3252.0KiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |3740.0KiB|3740.0KiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |3036.0KiB|3036.0KiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |3628.0KiB|3628.0KiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |4112.0KiB|4112.0KiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |3660.0KiB|3660.0KiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |3792.0KiB|3792.0KiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |3652.0KiB|3652.0KiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |3388.0KiB|3388.0KiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |3548.0KiB|3548.0KiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |3384.0KiB|3384.0KiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |3300.0KiB|3300.0KiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |3256.0KiB|3256.0KiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |4172.0KiB|4172.0KiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |3192.0KiB|3192.0KiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |3556.0KiB|3556.0KiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3572.0KiB|3572.0KiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |3884.0KiB|3884.0KiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |3316.0KiB|3316.0KiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3924.0KiB|3924.0KiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |3252.0KiB|3252.0KiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |3740.0KiB|3740.0KiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |3036.0KiB|3036.0KiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |3628.0KiB|3628.0KiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |4112.0KiB|4112.0KiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |3660.0KiB|3660.0KiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |3792.0KiB|3792.0KiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |3652.0KiB|3652.0KiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |3388.0KiB|3388.0KiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |3548.0KiB|3548.0KiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |3384.0KiB|3384.0KiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |3300.0KiB|3300.0KiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |3256.0KiB|3256.0KiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |4172.0KiB|4172.0KiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |3192.0KiB|3192.0KiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |3556.0KiB|3556.0KiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3572.0KiB|3572.0KiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |3884.0KiB|3884.0KiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |3316.0KiB|3316.0KiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3924.0KiB|3924.0KiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |3252.0KiB|3252.0KiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |3740.0KiB|3740.0KiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |3036.0KiB|3036.0KiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |3628.0KiB|3628.0KiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |4112.0KiB|4112.0KiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |3660.0KiB|3660.0KiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |3792.0KiB|3792.0KiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |3652.0KiB|3652.0KiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |3388.0KiB|3388.0KiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |3548.0KiB|3548.0KiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |3384.0KiB|3384.0KiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |3300.0KiB|3300.0KiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |3256.0KiB|3256.0KiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |4172.0KiB|4172.0KiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |3192.0KiB|3192.0KiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |3556.0KiB|3556.0KiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3572.0KiB|3572.0KiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |3884.0KiB|3884.0KiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |3316.0KiB|3316.0KiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3924.0KiB|3924.0KiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |3252.0KiB|3252.0KiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |3740.0KiB|3740.0KiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |3036.0KiB|3036.0KiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |3628.0KiB|3628.0KiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |4112.0KiB|4112.0KiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |3660.0KiB|3660.0KiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |3792.0KiB|3792.0KiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |3652.0KiB|3652.0KiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |3388.0KiB|3388.0KiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |3548.0KiB|3548.0KiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |3384.0KiB|3384.0KiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |3300.0KiB|3300.0KiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled58311.smt2                                                                        |   0.028s |4468.0KiB|
|scrambled101716.smt2                                                                       |   0.024s |4172.0KiB|
|scrambled17293.smt2                                                                        |   0.029s |4112.0KiB|
|scrambled39467.smt2                                                                        |   0.028s |4020.0KiB|
|scrambled9883.smt2                                                                         |   0.029s |4000.0KiB|
|scrambled82760.smt2                                                                        |   0.046s |3976.0KiB|
|scrambled122926.smt2                                                                       |   0.021s |3924.0KiB|
|scrambled96401.smt2                                                                        |   0.030s |3908.0KiB|
|scrambled97386.smt2                                                                        |   0.027s |3908.0KiB|
|scrambled119582.smt2                                                                       |   0.030s |3884.0KiB|
|scrambled8852.smt2                                                                         |   0.024s |3868.0KiB|
|scrambled73755.smt2                                                                        |   0.042s |3856.0KiB|
|scrambled48569.smt2                                                                        |   0.021s |3840.0KiB|
|scrambled29780.smt2                                                                        |   0.020s |3792.0KiB|
|scrambled12959.smt2                                                                        |   0.041s |3740.0KiB|
|scrambled87588.smt2                                                                        |   0.022s |3732.0KiB|
|scrambled28176.smt2                                                                        |   0.032s |3660.0KiB|
|scrambled73281.smt2                                                                        |   0.022s |3660.0KiB|
|scrambled30073.smt2                                                                        |   0.020s |3652.0KiB|
|scrambled91750.smt2                                                                        |   0.042s |3640.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled58311.smt2                                                                        |   0.028s |4468.0KiB|
|scrambled101716.smt2                                                                       |   0.024s |4172.0KiB|
|scrambled17293.smt2                                                                        |   0.029s |4112.0KiB|
|scrambled39467.smt2                                                                        |   0.028s |4020.0KiB|
|scrambled9883.smt2                                                                         |   0.029s |4000.0KiB|
|scrambled82760.smt2                                                                        |   0.046s |3976.0KiB|
|scrambled122926.smt2                                                                       |   0.021s |3924.0KiB|
|scrambled96401.smt2                                                                        |   0.030s |3908.0KiB|
|scrambled97386.smt2                                                                        |   0.027s |3908.0KiB|
|scrambled119582.smt2                                                                       |   0.030s |3884.0KiB|
|scrambled8852.smt2                                                                         |   0.024s |3868.0KiB|
|scrambled73755.smt2                                                                        |   0.042s |3856.0KiB|
|scrambled48569.smt2                                                                        |   0.021s |3840.0KiB|
|scrambled29780.smt2                                                                        |   0.020s |3792.0KiB|
|scrambled12959.smt2                                                                        |   0.041s |3740.0KiB|
|scrambled87588.smt2                                                                        |   0.022s |3732.0KiB|
|scrambled28176.smt2                                                                        |   0.032s |3660.0KiB|
|scrambled73281.smt2                                                                        |   0.022s |3660.0KiB|
|scrambled30073.smt2                                                                        |   0.020s |3652.0KiB|
|scrambled91750.smt2                                                                        |   0.042s |3640.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |   0.030s  |   0.030s  |   0.000s  | 0.0%|
</details>
