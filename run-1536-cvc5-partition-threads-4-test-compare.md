Comparing data and data


# SUMMARY
- LHS tests = 44
- RHS tests = 44
- LHS success = 0  (0.0%)
- RHS success = 0  (0.0%)


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
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled82760.smt2                                                                        |   0.046s |3412.0KiB|
|scrambled98111.smt2                                                                        |   0.046s |3244.0KiB|
|scrambled39467.smt2                                                                        |   0.046s |3508.0KiB|
|scrambled31575.smt2                                                                        |   0.046s |3292.0KiB|
|scrambled36790.smt2                                                                        |   0.045s |3364.0KiB|
|scrambled48569.smt2                                                                        |   0.045s |3680.0KiB|
|scrambled80288.smt2                                                                        |   0.045s |3328.0KiB|
|scrambled73755.smt2                                                                        |   0.045s |3208.0KiB|
|scrambled41135.smt2                                                                        |   0.045s |3440.0KiB|
|scrambled28176.smt2                                                                        |   0.045s |3180.0KiB|
|scrambled87588.smt2                                                                        |   0.045s |3388.0KiB|
|scrambled73281.smt2                                                                        |   0.045s |2708.0KiB|
|scrambled58311.smt2                                                                        |   0.044s |3288.0KiB|
|scrambled9883.smt2                                                                         |   0.044s |3388.0KiB|
|scrambled47700.smt2                                                                        |   0.044s |3472.0KiB|
|scrambled35280.smt2                                                                        |   0.044s |3264.0KiB|
|scrambled103775.smt2                                                                       |   0.042s |3508.0KiB|
|scrambled62032.smt2                                                                        |   0.041s |3332.0KiB|
|scrambled9548.smt2                                                                         |   0.041s |2968.0KiB|
|scrambled17293.smt2                                                                        |   0.040s |3492.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled82760.smt2                                                                        |   0.046s |3412.0KiB|
|scrambled98111.smt2                                                                        |   0.046s |3244.0KiB|
|scrambled39467.smt2                                                                        |   0.046s |3508.0KiB|
|scrambled31575.smt2                                                                        |   0.046s |3292.0KiB|
|scrambled36790.smt2                                                                        |   0.045s |3364.0KiB|
|scrambled48569.smt2                                                                        |   0.045s |3680.0KiB|
|scrambled80288.smt2                                                                        |   0.045s |3328.0KiB|
|scrambled73755.smt2                                                                        |   0.045s |3208.0KiB|
|scrambled41135.smt2                                                                        |   0.045s |3440.0KiB|
|scrambled28176.smt2                                                                        |   0.045s |3180.0KiB|
|scrambled87588.smt2                                                                        |   0.045s |3388.0KiB|
|scrambled73281.smt2                                                                        |   0.045s |2708.0KiB|
|scrambled58311.smt2                                                                        |   0.044s |3288.0KiB|
|scrambled9883.smt2                                                                         |   0.044s |3388.0KiB|
|scrambled47700.smt2                                                                        |   0.044s |3472.0KiB|
|scrambled35280.smt2                                                                        |   0.044s |3264.0KiB|
|scrambled103775.smt2                                                                       |   0.042s |3508.0KiB|
|scrambled62032.smt2                                                                        |   0.041s |3332.0KiB|
|scrambled9548.smt2                                                                         |   0.041s |2968.0KiB|
|scrambled17293.smt2                                                                        |   0.040s |3492.0KiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled100714.smt2                                                                       |   0.024s |4588.0KiB|
|scrambled97386.smt2                                                                        |   0.020s |4292.0KiB|
|scrambled85357.smt2                                                                        |   0.022s |4052.0KiB|
|scrambled31071.smt2                                                                        |   0.021s |4004.0KiB|
|scrambled30073.smt2                                                                        |   0.018s |4000.0KiB|
|scrambled96401.smt2                                                                        |   0.020s |3836.0KiB|
|scrambled38587.smt2                                                                        |   0.019s |3792.0KiB|
|scrambled12959.smt2                                                                        |   0.020s |3760.0KiB|
|scrambled129467.smt2                                                                       |   0.022s |3704.0KiB|
|scrambled108406.smt2                                                                       |   0.022s |3696.0KiB|
|scrambled119582.smt2                                                                       |   0.020s |3692.0KiB|
|scrambled48569.smt2                                                                        |   0.045s |3680.0KiB|
|scrambled130111.smt2                                                                       |   0.018s |3596.0KiB|
|scrambled82407.smt2                                                                        |   0.040s |3568.0KiB|
|scrambled12033.smt2                                                                        |   0.039s |3528.0KiB|
|scrambled39467.smt2                                                                        |   0.046s |3508.0KiB|
|scrambled103775.smt2                                                                       |   0.042s |3508.0KiB|
|scrambled17293.smt2                                                                        |   0.040s |3492.0KiB|
|scrambled79354.smt2                                                                        |   0.022s |3484.0KiB|
|scrambled47700.smt2                                                                        |   0.044s |3472.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled100714.smt2                                                                       |   0.024s |4588.0KiB|
|scrambled97386.smt2                                                                        |   0.020s |4292.0KiB|
|scrambled85357.smt2                                                                        |   0.022s |4052.0KiB|
|scrambled31071.smt2                                                                        |   0.021s |4004.0KiB|
|scrambled30073.smt2                                                                        |   0.018s |4000.0KiB|
|scrambled96401.smt2                                                                        |   0.020s |3836.0KiB|
|scrambled38587.smt2                                                                        |   0.019s |3792.0KiB|
|scrambled12959.smt2                                                                        |   0.020s |3760.0KiB|
|scrambled129467.smt2                                                                       |   0.022s |3704.0KiB|
|scrambled108406.smt2                                                                       |   0.022s |3696.0KiB|
|scrambled119582.smt2                                                                       |   0.020s |3692.0KiB|
|scrambled48569.smt2                                                                        |   0.045s |3680.0KiB|
|scrambled130111.smt2                                                                       |   0.018s |3596.0KiB|
|scrambled82407.smt2                                                                        |   0.040s |3568.0KiB|
|scrambled12033.smt2                                                                        |   0.039s |3528.0KiB|
|scrambled39467.smt2                                                                        |   0.046s |3508.0KiB|
|scrambled103775.smt2                                                                       |   0.042s |3508.0KiB|
|scrambled17293.smt2                                                                        |   0.040s |3492.0KiB|
|scrambled79354.smt2                                                                        |   0.022s |3484.0KiB|
|scrambled47700.smt2                                                                        |   0.044s |3472.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
