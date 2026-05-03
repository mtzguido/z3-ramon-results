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
Job tag: CVC5-threads-8-mode-partition-smtcomp2025-QF_NIA-timeout20min
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: partition
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter decision-cube"
cvc5 partition budget: 8
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 8
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
Job tag: CVC5-threads-8-mode-partition-smtcomp2025-QF_NIA-timeout20min
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: partition
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter decision-cube"
cvc5 partition budget: 8
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 8
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
|scrambled100714.smt2                                                                        |1200.243s  |1200.243s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1199.950s  |1199.950s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1199.391s  |1199.391s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1199.904s  |1199.904s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1199.965s  |1199.965s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.226s  |1200.226s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1199.844s  |1199.844s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |1199.946s  |1199.946s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.255s  |1200.255s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1199.914s  |1199.914s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |1199.942s  |1199.942s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  86.539s  |  86.539s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1199.797s  |1199.797s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1199.877s  |1199.877s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |1199.828s  |1199.828s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1199.978s  |1199.978s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1199.797s  |1199.797s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1199.797s  |1199.797s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.243s  |1200.243s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1199.950s  |1199.950s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1199.391s  |1199.391s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1199.904s  |1199.904s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1199.965s  |1199.965s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.226s  |1200.226s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1199.844s  |1199.844s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |1199.946s  |1199.946s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.255s  |1200.255s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1199.914s  |1199.914s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |1199.942s  |1199.942s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  86.539s  |  86.539s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1199.797s  |1199.797s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1199.877s  |1199.877s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |1199.828s  |1199.828s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1199.978s  |1199.978s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1199.797s  |1199.797s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1199.797s  |1199.797s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.243s  |1200.243s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1199.950s  |1199.950s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1199.391s  |1199.391s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1199.904s  |1199.904s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1199.965s  |1199.965s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.226s  |1200.226s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1199.844s  |1199.844s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |1199.946s  |1199.946s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.255s  |1200.255s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1199.914s  |1199.914s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |1199.942s  |1199.942s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  86.539s  |  86.539s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1199.797s  |1199.797s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1199.877s  |1199.877s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |1199.828s  |1199.828s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1199.978s  |1199.978s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1199.797s  |1199.797s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1199.797s  |1199.797s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.243s  |1200.243s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1199.950s  |1199.950s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1199.391s  |1199.391s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1199.904s  |1199.904s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1199.965s  |1199.965s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.226s  |1200.226s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1199.844s  |1199.844s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |1199.946s  |1199.946s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.255s  |1200.255s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1199.914s  |1199.914s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |1199.942s  |1199.942s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  86.539s  |  86.539s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1199.797s  |1199.797s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1199.877s  |1199.877s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |1199.828s  |1199.828s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1199.978s  |1199.978s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1199.797s  |1199.797s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1199.797s  |1199.797s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.448s |13.413GiB|
|scrambled9883.smt2                                                                         |1200.335s |3682.0MiB|
|scrambled73755.smt2                                                                        |1200.311s |5040.0MiB|
|scrambled62032.smt2                                                                        |1200.303s |3198.0MiB|
|scrambled91750.smt2                                                                        |1200.281s |2943.0MiB|
|scrambled82760.smt2                                                                        |1200.257s |2384.0MiB|
|scrambled12959.smt2                                                                        |1200.255s |2045.0MiB|
|scrambled80288.smt2                                                                        |1200.246s |1758.0MiB|
|scrambled100714.smt2                                                                       |1200.243s |2338.0MiB|
|scrambled119582.smt2                                                                       |1200.226s |2399.0MiB|
|scrambled39467.smt2                                                                        |1200.224s |1856.0MiB|
|scrambled96401.smt2                                                                        |1200.219s |2531.0MiB|
|scrambled31575.smt2                                                                        |1200.212s |1944.0MiB|
|scrambled97386.smt2                                                                        |1200.111s |1448.0MiB|
|scrambled79354.smt2                                                                        |1200.015s |3446.0MiB|
|scrambled8852.smt2                                                                         |1200.000s |3394.0MiB|
|scrambled31071.smt2                                                                        |1199.978s |3167.0MiB|
|scrambled108663.smt2                                                                       |1199.965s |2225.0MiB|
|scrambled101716.smt2                                                                       |1199.950s |3248.0MiB|
|scrambled129467.smt2                                                                       |1199.946s |2234.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.448s |13.413GiB|
|scrambled9883.smt2                                                                         |1200.335s |3682.0MiB|
|scrambled73755.smt2                                                                        |1200.311s |5040.0MiB|
|scrambled62032.smt2                                                                        |1200.303s |3198.0MiB|
|scrambled91750.smt2                                                                        |1200.281s |2943.0MiB|
|scrambled82760.smt2                                                                        |1200.257s |2384.0MiB|
|scrambled12959.smt2                                                                        |1200.255s |2045.0MiB|
|scrambled80288.smt2                                                                        |1200.246s |1758.0MiB|
|scrambled100714.smt2                                                                       |1200.243s |2338.0MiB|
|scrambled119582.smt2                                                                       |1200.226s |2399.0MiB|
|scrambled39467.smt2                                                                        |1200.224s |1856.0MiB|
|scrambled96401.smt2                                                                        |1200.219s |2531.0MiB|
|scrambled31575.smt2                                                                        |1200.212s |1944.0MiB|
|scrambled97386.smt2                                                                        |1200.111s |1448.0MiB|
|scrambled79354.smt2                                                                        |1200.015s |3446.0MiB|
|scrambled8852.smt2                                                                         |1200.000s |3394.0MiB|
|scrambled31071.smt2                                                                        |1199.978s |3167.0MiB|
|scrambled108663.smt2                                                                       |1199.965s |2225.0MiB|
|scrambled101716.smt2                                                                       |1199.950s |3248.0MiB|
|scrambled129467.smt2                                                                       |1199.946s |2234.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |2338.0MiB|2338.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |3248.0MiB|3248.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |1764.0MiB|1764.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1618.0MiB|1618.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2225.0MiB|2225.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |2399.0MiB|2399.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |3641.0MiB|3641.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |2337.0MiB|2337.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |2234.0MiB|2234.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |2045.0MiB|2045.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2189.0MiB|2189.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |1889.0MiB|1889.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |889.0MiB|889.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |2661.0MiB|2661.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |3286.0MiB|3286.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |1744.0MiB|1744.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |3167.0MiB|3167.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |1944.0MiB|1944.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |2224.0MiB|2224.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |2537.0MiB|2537.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |2338.0MiB|2338.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |3248.0MiB|3248.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |1764.0MiB|1764.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1618.0MiB|1618.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2225.0MiB|2225.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |2399.0MiB|2399.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |3641.0MiB|3641.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |2337.0MiB|2337.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |2234.0MiB|2234.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |2045.0MiB|2045.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2189.0MiB|2189.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |1889.0MiB|1889.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |889.0MiB|889.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |2661.0MiB|2661.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |3286.0MiB|3286.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |1744.0MiB|1744.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |3167.0MiB|3167.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |1944.0MiB|1944.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |2224.0MiB|2224.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |2537.0MiB|2537.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |2338.0MiB|2338.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |3248.0MiB|3248.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |1764.0MiB|1764.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1618.0MiB|1618.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2225.0MiB|2225.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |2399.0MiB|2399.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |3641.0MiB|3641.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |2337.0MiB|2337.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |2234.0MiB|2234.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |2045.0MiB|2045.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2189.0MiB|2189.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |1889.0MiB|1889.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |889.0MiB|889.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |2661.0MiB|2661.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |3286.0MiB|3286.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |1744.0MiB|1744.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |3167.0MiB|3167.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |1944.0MiB|1944.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |2224.0MiB|2224.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |2537.0MiB|2537.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |2338.0MiB|2338.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |3248.0MiB|3248.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |1764.0MiB|1764.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1618.0MiB|1618.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |2225.0MiB|2225.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |2399.0MiB|2399.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |3641.0MiB|3641.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |2337.0MiB|2337.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |2234.0MiB|2234.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |2045.0MiB|2045.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2189.0MiB|2189.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |1889.0MiB|1889.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |889.0MiB|889.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |2661.0MiB|2661.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |3286.0MiB|3286.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |1744.0MiB|1744.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |3167.0MiB|3167.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |1944.0MiB|1944.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |2224.0MiB|2224.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |2537.0MiB|2537.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.448s |13.413GiB|
|scrambled9548.smt2                                                                         |1199.797s |6176.0MiB|
|scrambled73755.smt2                                                                        |1200.311s |5040.0MiB|
|scrambled9883.smt2                                                                         |1200.335s |3682.0MiB|
|scrambled12033.smt2                                                                        |1199.857s |3641.0MiB|
|scrambled79354.smt2                                                                        |1200.015s |3446.0MiB|
|scrambled8852.smt2                                                                         |1200.000s |3394.0MiB|
|scrambled29780.smt2                                                                        |1199.877s |3286.0MiB|
|scrambled101716.smt2                                                                       |1199.950s |3248.0MiB|
|scrambled62032.smt2                                                                        |1200.303s |3198.0MiB|
|scrambled31071.smt2                                                                        |1199.978s |3167.0MiB|
|scrambled58311.smt2                                                                        |1199.748s |3078.0MiB|
|scrambled87588.smt2                                                                        |1199.797s |3030.0MiB|
|scrambled91750.smt2                                                                        |1200.281s |2943.0MiB|
|scrambled28176.smt2                                                                        |1199.797s |2661.0MiB|
|scrambled73281.smt2                                                                        |1199.758s |2647.0MiB|
|scrambled36790.smt2                                                                        |1199.797s |2537.0MiB|
|scrambled96401.smt2                                                                        |1200.219s |2531.0MiB|
|scrambled41135.smt2                                                                        |1199.807s |2476.0MiB|
|scrambled61060.smt2                                                                        |1199.815s |2403.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.448s |13.413GiB|
|scrambled9548.smt2                                                                         |1199.797s |6176.0MiB|
|scrambled73755.smt2                                                                        |1200.311s |5040.0MiB|
|scrambled9883.smt2                                                                         |1200.335s |3682.0MiB|
|scrambled12033.smt2                                                                        |1199.857s |3641.0MiB|
|scrambled79354.smt2                                                                        |1200.015s |3446.0MiB|
|scrambled8852.smt2                                                                         |1200.000s |3394.0MiB|
|scrambled29780.smt2                                                                        |1199.877s |3286.0MiB|
|scrambled101716.smt2                                                                       |1199.950s |3248.0MiB|
|scrambled62032.smt2                                                                        |1200.303s |3198.0MiB|
|scrambled31071.smt2                                                                        |1199.978s |3167.0MiB|
|scrambled58311.smt2                                                                        |1199.748s |3078.0MiB|
|scrambled87588.smt2                                                                        |1199.797s |3030.0MiB|
|scrambled91750.smt2                                                                        |1200.281s |2943.0MiB|
|scrambled28176.smt2                                                                        |1199.797s |2661.0MiB|
|scrambled73281.smt2                                                                        |1199.758s |2647.0MiB|
|scrambled36790.smt2                                                                        |1199.797s |2537.0MiB|
|scrambled96401.smt2                                                                        |1200.219s |2531.0MiB|
|scrambled41135.smt2                                                                        |1199.807s |2476.0MiB|
|scrambled61060.smt2                                                                        |1199.815s |2403.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.243s  |1200.243s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1199.950s  |1199.950s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1199.391s  |1199.391s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1199.904s  |1199.904s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1199.965s  |1199.965s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.226s  |1200.226s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1199.844s  |1199.844s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |1199.946s  |1199.946s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.255s  |1200.255s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1199.914s  |1199.914s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |1199.942s  |1199.942s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  86.539s  |  86.539s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1199.797s  |1199.797s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1199.877s  |1199.877s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |1199.828s  |1199.828s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1199.978s  |1199.978s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1199.797s  |1199.797s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1199.797s  |1199.797s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1021.082s  |1021.082s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.224s  |1200.224s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1199.807s  |1199.807s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1199.805s  |1199.805s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |  73.889s  |  73.889s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |1199.658s  |1199.658s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1199.748s  |1199.748s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         |1199.815s  |1199.815s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.303s  |1200.303s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1199.758s  |1199.758s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.311s  |1200.311s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         |1200.246s  |1200.246s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |1199.858s  |1199.858s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.257s  |1200.257s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1200.448s  |1200.448s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1199.797s  |1199.797s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.000s  |1200.000s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.281s  |1200.281s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |1199.797s  |1199.797s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.111s  |1200.111s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1199.749s  |1199.749s  |   0.000s  | 0.0%|
</details>
