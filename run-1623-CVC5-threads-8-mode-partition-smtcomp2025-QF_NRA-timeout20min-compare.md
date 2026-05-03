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
Job tag: CVC5-threads-8-mode-partition-smtcomp2025-QF_NRA-timeout20min
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_NRA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-8-mode-partition-smtcomp2025-QF_NRA-timeout20min
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_NRA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.645s  |1200.645s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1199.924s  |1199.924s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1199.878s  |1199.878s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1199.658s  |1199.658s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        | 420.572s  | 420.572s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1199.982s  |1199.982s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1199.972s  |1199.972s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |  35.053s  |  35.053s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1199.929s  |1199.929s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1199.849s  |1199.849s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1199.896s  |1199.896s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.123s  |1200.123s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.645s  |1200.645s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1199.924s  |1199.924s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1199.878s  |1199.878s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1199.658s  |1199.658s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        | 420.572s  | 420.572s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1199.982s  |1199.982s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1199.972s  |1199.972s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |  35.053s  |  35.053s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1199.929s  |1199.929s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1199.849s  |1199.849s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1199.896s  |1199.896s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.123s  |1200.123s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.645s  |1200.645s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1199.924s  |1199.924s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1199.878s  |1199.878s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1199.658s  |1199.658s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        | 420.572s  | 420.572s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1199.982s  |1199.982s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1199.972s  |1199.972s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |  35.053s  |  35.053s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1199.929s  |1199.929s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1199.849s  |1199.849s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1199.896s  |1199.896s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.123s  |1200.123s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.645s  |1200.645s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1199.924s  |1199.924s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1199.878s  |1199.878s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1199.658s  |1199.658s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        | 420.572s  | 420.572s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1199.982s  |1199.982s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1199.972s  |1199.972s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |  35.053s  |  35.053s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1199.929s  |1199.929s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1199.849s  |1199.849s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1199.896s  |1199.896s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.123s  |1200.123s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled100912.smt2                                                                       |1200.645s |627.0MiB|
|scrambled73220.smt2                                                                        |1200.170s |1132.0MiB|
|scrambled58292.smt2                                                                        |1200.147s |725.0MiB|
|scrambled32701.smt2                                                                        |1200.123s |766.0MiB|
|scrambled28630.smt2                                                                        |1200.107s |2396.0MiB|
|scrambled94768.smt2                                                                        |1200.098s |629.0MiB|
|scrambled29556.smt2                                                                        |1200.096s |313.0MiB|
|scrambled36539.smt2                                                                        |1200.093s |234.0MiB|
|scrambled117944.smt2                                                                       |1200.091s |62.384MiB|
|scrambled54263.smt2                                                                        |1200.077s |85.104MiB|
|scrambled74869.smt2                                                                        |1200.070s |5048.0MiB|
|scrambled14368.smt2                                                                        |1200.069s |4913.0MiB|
|scrambled21647.smt2                                                                        |1200.057s |351.0MiB|
|scrambled14880.smt2                                                                        |1200.045s |795.0MiB|
|scrambled114923.smt2                                                                       |1200.040s |5680.0MiB|
|scrambled18831.smt2                                                                        |1200.036s |45.448MiB|
|scrambled65757.smt2                                                                        |1200.034s |78.544MiB|
|scrambled121780.smt2                                                                       |1199.982s |575.0MiB|
|scrambled124828.smt2                                                                       |1199.972s |10.179GiB|
|scrambled82241.smt2                                                                        |1199.956s |1347.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled100912.smt2                                                                       |1200.645s |627.0MiB|
|scrambled73220.smt2                                                                        |1200.170s |1132.0MiB|
|scrambled58292.smt2                                                                        |1200.147s |725.0MiB|
|scrambled32701.smt2                                                                        |1200.123s |766.0MiB|
|scrambled28630.smt2                                                                        |1200.107s |2396.0MiB|
|scrambled94768.smt2                                                                        |1200.098s |629.0MiB|
|scrambled29556.smt2                                                                        |1200.096s |313.0MiB|
|scrambled36539.smt2                                                                        |1200.093s |234.0MiB|
|scrambled117944.smt2                                                                       |1200.091s |62.384MiB|
|scrambled54263.smt2                                                                        |1200.077s |85.104MiB|
|scrambled74869.smt2                                                                        |1200.070s |5048.0MiB|
|scrambled14368.smt2                                                                        |1200.069s |4913.0MiB|
|scrambled21647.smt2                                                                        |1200.057s |351.0MiB|
|scrambled14880.smt2                                                                        |1200.045s |795.0MiB|
|scrambled114923.smt2                                                                       |1200.040s |5680.0MiB|
|scrambled18831.smt2                                                                        |1200.036s |45.448MiB|
|scrambled65757.smt2                                                                        |1200.034s |78.544MiB|
|scrambled121780.smt2                                                                       |1199.982s |575.0MiB|
|scrambled124828.smt2                                                                       |1199.972s |10.179GiB|
|scrambled82241.smt2                                                                        |1199.956s |1347.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |627.0MiB|627.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |1016.0MiB|1016.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |1154.0MiB|1154.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |5680.0MiB|5680.0MiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |400.0MiB|400.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |62.384MiB|62.384MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |1186.0MiB|1186.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |575.0MiB|575.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |10.179GiB|10.179GiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |506.0MiB|506.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |4913.0MiB|4913.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |795.0MiB|795.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |45.448MiB|45.448MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |351.0MiB|351.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |2344.0MiB|2344.0MiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |560.0MiB|560.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |2396.0MiB|2396.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |313.0MiB|313.0MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |5157.0MiB|5157.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |766.0MiB|766.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |627.0MiB|627.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |1016.0MiB|1016.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |1154.0MiB|1154.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |5680.0MiB|5680.0MiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |400.0MiB|400.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |62.384MiB|62.384MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |1186.0MiB|1186.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |575.0MiB|575.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |10.179GiB|10.179GiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |506.0MiB|506.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |4913.0MiB|4913.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |795.0MiB|795.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |45.448MiB|45.448MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |351.0MiB|351.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |2344.0MiB|2344.0MiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |560.0MiB|560.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |2396.0MiB|2396.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |313.0MiB|313.0MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |5157.0MiB|5157.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |766.0MiB|766.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |627.0MiB|627.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |1016.0MiB|1016.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |1154.0MiB|1154.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |5680.0MiB|5680.0MiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |400.0MiB|400.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |62.384MiB|62.384MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |1186.0MiB|1186.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |575.0MiB|575.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |10.179GiB|10.179GiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |506.0MiB|506.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |4913.0MiB|4913.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |795.0MiB|795.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |45.448MiB|45.448MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |351.0MiB|351.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |2344.0MiB|2344.0MiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |560.0MiB|560.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |2396.0MiB|2396.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |313.0MiB|313.0MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |5157.0MiB|5157.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |766.0MiB|766.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |627.0MiB|627.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |1016.0MiB|1016.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |1154.0MiB|1154.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |5680.0MiB|5680.0MiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |400.0MiB|400.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |62.384MiB|62.384MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |1186.0MiB|1186.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |575.0MiB|575.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |10.179GiB|10.179GiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |506.0MiB|506.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |4913.0MiB|4913.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |795.0MiB|795.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |45.448MiB|45.448MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |351.0MiB|351.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |2344.0MiB|2344.0MiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |560.0MiB|560.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |2396.0MiB|2396.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |313.0MiB|313.0MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |5157.0MiB|5157.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |766.0MiB|766.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled124828.smt2                                                                       |1199.972s |10.179GiB|
|scrambled114923.smt2                                                                       |1200.040s |5680.0MiB|
|scrambled32269.smt2                                                                        |1199.896s |5157.0MiB|
|scrambled74869.smt2                                                                        |1200.070s |5048.0MiB|
|scrambled14368.smt2                                                                        |1200.069s |4913.0MiB|
|scrambled5797.smt2                                                                         |1199.914s |3303.0MiB|
|scrambled80728.smt2                                                                        |1199.901s |3063.0MiB|
|scrambled28630.smt2                                                                        |1200.107s |2396.0MiB|
|scrambled22492.smt2                                                                        |1199.929s |2344.0MiB|
|scrambled42946.smt2                                                                        |1199.892s |1937.0MiB|
|scrambled94319.smt2                                                                        |1199.836s |1418.0MiB|
|scrambled82241.smt2                                                                        |1199.956s |1347.0MiB|
|scrambled7586.smt2                                                                         |1199.790s |1288.0MiB|
|scrambled118224.smt2                                                                       | 420.572s |1186.0MiB|
|scrambled112144.smt2                                                                       |1199.878s |1154.0MiB|
|scrambled73220.smt2                                                                        |1200.170s |1132.0MiB|
|scrambled34121.smt2                                                                        |1199.905s |1063.0MiB|
|scrambled112083.smt2                                                                       |1199.924s |1016.0MiB|
|scrambled7923.smt2                                                                         |1199.920s |995.0MiB|
|scrambled70990.smt2                                                                        |1199.627s |955.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled124828.smt2                                                                       |1199.972s |10.179GiB|
|scrambled114923.smt2                                                                       |1200.040s |5680.0MiB|
|scrambled32269.smt2                                                                        |1199.896s |5157.0MiB|
|scrambled74869.smt2                                                                        |1200.070s |5048.0MiB|
|scrambled14368.smt2                                                                        |1200.069s |4913.0MiB|
|scrambled5797.smt2                                                                         |1199.914s |3303.0MiB|
|scrambled80728.smt2                                                                        |1199.901s |3063.0MiB|
|scrambled28630.smt2                                                                        |1200.107s |2396.0MiB|
|scrambled22492.smt2                                                                        |1199.929s |2344.0MiB|
|scrambled42946.smt2                                                                        |1199.892s |1937.0MiB|
|scrambled94319.smt2                                                                        |1199.836s |1418.0MiB|
|scrambled82241.smt2                                                                        |1199.956s |1347.0MiB|
|scrambled7586.smt2                                                                         |1199.790s |1288.0MiB|
|scrambled118224.smt2                                                                       | 420.572s |1186.0MiB|
|scrambled112144.smt2                                                                       |1199.878s |1154.0MiB|
|scrambled73220.smt2                                                                        |1200.170s |1132.0MiB|
|scrambled34121.smt2                                                                        |1199.905s |1063.0MiB|
|scrambled112083.smt2                                                                       |1199.924s |1016.0MiB|
|scrambled7923.smt2                                                                         |1199.920s |995.0MiB|
|scrambled70990.smt2                                                                        |1199.627s |955.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.645s  |1200.645s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1199.924s  |1199.924s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1199.878s  |1199.878s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1199.658s  |1199.658s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        | 420.572s  | 420.572s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1199.982s  |1199.982s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1199.972s  |1199.972s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |  35.053s  |  35.053s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1199.929s  |1199.929s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1199.849s  |1199.849s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1199.896s  |1199.896s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled34121.smt2                                                                         |1199.905s  |1199.905s  |   0.000s  | 0.0%|
|scrambled36539.smt2                                                                         |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled41575.smt2                                                                         |1199.664s  |1199.664s  |   0.000s  | 0.0%|
|scrambled42946.smt2                                                                         |1199.892s  |1199.892s  |   0.000s  | 0.0%|
|scrambled54263.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled5797.smt2                                                                          |1199.914s  |1199.914s  |   0.000s  | 0.0%|
|scrambled58292.smt2                                                                         |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled60239.smt2                                                                         |1199.798s  |1199.798s  |   0.000s  | 0.0%|
|scrambled61896.smt2                                                                         |1199.714s  |1199.714s  |   0.000s  | 0.0%|
|scrambled6476.smt2                                                                          |1199.840s  |1199.840s  |   0.000s  | 0.0%|
|scrambled65757.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled70990.smt2                                                                         |1199.627s  |1199.627s  |   0.000s  | 0.0%|
|scrambled73220.smt2                                                                         |1200.170s  |1200.170s  |   0.000s  | 0.0%|
|scrambled74869.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled7586.smt2                                                                          |1199.790s  |1199.790s  |   0.000s  | 0.0%|
|scrambled78428.smt2                                                                         |1199.854s  |1199.854s  |   0.000s  | 0.0%|
|scrambled7923.smt2                                                                          |1199.920s  |1199.920s  |   0.000s  | 0.0%|
|scrambled80728.smt2                                                                         |1199.901s  |1199.901s  |   0.000s  | 0.0%|
|scrambled82241.smt2                                                                         |1199.956s  |1199.956s  |   0.000s  | 0.0%|
|scrambled85895.smt2                                                                         |1199.893s  |1199.893s  |   0.000s  | 0.0%|
|scrambled91241.smt2                                                                         |1199.880s  |1199.880s  |   0.000s  | 0.0%|
|scrambled94319.smt2                                                                         |1199.836s  |1199.836s  |   0.000s  | 0.0%|
|scrambled94768.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
</details>
