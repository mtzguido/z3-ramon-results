Comparing data and data


# SUMMARY
- LHS tests = 38
- RHS tests = 38
- LHS success = 38  (100.0%)
- RHS success = 38  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-1-mode-sequential-smtcomp2025-QF_LRA-timeout20min
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_LRA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-1-mode-sequential-smtcomp2025-QF_LRA-timeout20min
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_LRA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.162s  |1200.162s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.193s  |1200.193s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.156s  |1200.156s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.235s  |1200.235s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.208s  |1200.208s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 649.732s  | 649.732s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.207s  |1200.207s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.208s  |1200.208s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.116s  |1200.116s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.162s  |1200.162s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.193s  |1200.193s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.156s  |1200.156s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.235s  |1200.235s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.208s  |1200.208s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 649.732s  | 649.732s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.207s  |1200.207s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.208s  |1200.208s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.116s  |1200.116s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.162s  |1200.162s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.193s  |1200.193s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.156s  |1200.156s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.235s  |1200.235s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.208s  |1200.208s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 649.732s  | 649.732s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.207s  |1200.207s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.208s  |1200.208s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.116s  |1200.116s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.162s  |1200.162s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.193s  |1200.193s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.156s  |1200.156s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.235s  |1200.235s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.208s  |1200.208s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 649.732s  | 649.732s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.207s  |1200.207s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.208s  |1200.208s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.116s  |1200.116s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled8163.smt2                                                                         |1200.252s |1585.0MiB|
|scrambled104811.smt2                                                                       |1200.235s |1678.0MiB|
|scrambled13169.smt2                                                                        |1200.219s |1529.0MiB|
|scrambled77308.smt2                                                                        |1200.210s |1661.0MiB|
|scrambled25695.smt2                                                                        |1200.208s |1402.0MiB|
|scrambled111949.smt2                                                                       |1200.208s |1239.0MiB|
|scrambled13209.smt2                                                                        |1200.207s |1386.0MiB|
|scrambled102621.smt2                                                                       |1200.193s |1267.0MiB|
|scrambled55850.smt2                                                                        |1200.181s |1139.0MiB|
|scrambled65517.smt2                                                                        |1200.179s |902.0MiB|
|scrambled98986.smt2                                                                        |1200.178s |1145.0MiB|
|scrambled77008.smt2                                                                        |1200.165s |695.0MiB|
|scrambled101728.smt2                                                                       |1200.162s |687.0MiB|
|scrambled102680.smt2                                                                       |1200.156s |899.0MiB|
|scrambled17583.smt2                                                                        |1200.128s |398.0MiB|
|scrambled101086.smt2                                                                       |1200.123s |389.0MiB|
|scrambled37260.smt2                                                                        |1200.116s |379.0MiB|
|scrambled31085.smt2                                                                        |1200.114s |293.0MiB|
|scrambled124455.smt2                                                                       |1200.105s |327.0MiB|
|scrambled109307.smt2                                                                       |1200.104s |513.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled8163.smt2                                                                         |1200.252s |1585.0MiB|
|scrambled104811.smt2                                                                       |1200.235s |1678.0MiB|
|scrambled13169.smt2                                                                        |1200.219s |1529.0MiB|
|scrambled77308.smt2                                                                        |1200.210s |1661.0MiB|
|scrambled25695.smt2                                                                        |1200.208s |1402.0MiB|
|scrambled111949.smt2                                                                       |1200.208s |1239.0MiB|
|scrambled13209.smt2                                                                        |1200.207s |1386.0MiB|
|scrambled102621.smt2                                                                       |1200.193s |1267.0MiB|
|scrambled55850.smt2                                                                        |1200.181s |1139.0MiB|
|scrambled65517.smt2                                                                        |1200.179s |902.0MiB|
|scrambled98986.smt2                                                                        |1200.178s |1145.0MiB|
|scrambled77008.smt2                                                                        |1200.165s |695.0MiB|
|scrambled101728.smt2                                                                       |1200.162s |687.0MiB|
|scrambled102680.smt2                                                                       |1200.156s |899.0MiB|
|scrambled17583.smt2                                                                        |1200.128s |398.0MiB|
|scrambled101086.smt2                                                                       |1200.123s |389.0MiB|
|scrambled37260.smt2                                                                        |1200.116s |379.0MiB|
|scrambled31085.smt2                                                                        |1200.114s |293.0MiB|
|scrambled124455.smt2                                                                       |1200.105s |327.0MiB|
|scrambled109307.smt2                                                                       |1200.104s |513.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |389.0MiB|389.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |687.0MiB|687.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1267.0MiB|1267.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |899.0MiB|899.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |190.0MiB|190.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |1678.0MiB|1678.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |513.0MiB|513.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |1239.0MiB|1239.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |167.0MiB|167.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |396.0MiB|396.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |165.0MiB|165.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |327.0MiB|327.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |317.0MiB|317.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1529.0MiB|1529.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |1386.0MiB|1386.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |398.0MiB|398.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1402.0MiB|1402.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |57.904MiB|57.904MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |379.0MiB|379.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |389.0MiB|389.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |687.0MiB|687.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1267.0MiB|1267.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |899.0MiB|899.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |190.0MiB|190.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |1678.0MiB|1678.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |513.0MiB|513.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |1239.0MiB|1239.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |167.0MiB|167.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |396.0MiB|396.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |165.0MiB|165.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |327.0MiB|327.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |317.0MiB|317.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1529.0MiB|1529.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |1386.0MiB|1386.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |398.0MiB|398.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1402.0MiB|1402.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |57.904MiB|57.904MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |379.0MiB|379.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |389.0MiB|389.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |687.0MiB|687.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1267.0MiB|1267.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |899.0MiB|899.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |190.0MiB|190.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |1678.0MiB|1678.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |513.0MiB|513.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |1239.0MiB|1239.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |167.0MiB|167.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |396.0MiB|396.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |165.0MiB|165.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |327.0MiB|327.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |317.0MiB|317.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1529.0MiB|1529.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |1386.0MiB|1386.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |398.0MiB|398.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1402.0MiB|1402.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |57.904MiB|57.904MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |379.0MiB|379.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |389.0MiB|389.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |687.0MiB|687.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1267.0MiB|1267.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |899.0MiB|899.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |190.0MiB|190.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |1678.0MiB|1678.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |513.0MiB|513.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |1239.0MiB|1239.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |167.0MiB|167.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |396.0MiB|396.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |165.0MiB|165.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |327.0MiB|327.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |317.0MiB|317.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1529.0MiB|1529.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |1386.0MiB|1386.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |398.0MiB|398.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1402.0MiB|1402.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |57.904MiB|57.904MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |379.0MiB|379.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled44527.smt2                                                                        | 650.848s |2553.0MiB|
|scrambled104811.smt2                                                                       |1200.235s |1678.0MiB|
|scrambled77308.smt2                                                                        |1200.210s |1661.0MiB|
|scrambled8163.smt2                                                                         |1200.252s |1585.0MiB|
|scrambled13169.smt2                                                                        |1200.219s |1529.0MiB|
|scrambled25695.smt2                                                                        |1200.208s |1402.0MiB|
|scrambled13209.smt2                                                                        |1200.207s |1386.0MiB|
|scrambled102621.smt2                                                                       |1200.193s |1267.0MiB|
|scrambled111949.smt2                                                                       |1200.208s |1239.0MiB|
|scrambled98986.smt2                                                                        |1200.178s |1145.0MiB|
|scrambled55850.smt2                                                                        |1200.181s |1139.0MiB|
|scrambled65517.smt2                                                                        |1200.179s |902.0MiB|
|scrambled102680.smt2                                                                       |1200.156s |899.0MiB|
|scrambled77008.smt2                                                                        |1200.165s |695.0MiB|
|scrambled101728.smt2                                                                       |1200.162s |687.0MiB|
|scrambled109307.smt2                                                                       |1200.104s |513.0MiB|
|scrambled95284.smt2                                                                        |1200.102s |405.0MiB|
|scrambled49820.smt2                                                                        |1200.056s |404.0MiB|
|scrambled17583.smt2                                                                        |1200.128s |398.0MiB|
|scrambled117897.smt2                                                                       |1200.049s |396.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled44527.smt2                                                                        | 650.848s |2553.0MiB|
|scrambled104811.smt2                                                                       |1200.235s |1678.0MiB|
|scrambled77308.smt2                                                                        |1200.210s |1661.0MiB|
|scrambled8163.smt2                                                                         |1200.252s |1585.0MiB|
|scrambled13169.smt2                                                                        |1200.219s |1529.0MiB|
|scrambled25695.smt2                                                                        |1200.208s |1402.0MiB|
|scrambled13209.smt2                                                                        |1200.207s |1386.0MiB|
|scrambled102621.smt2                                                                       |1200.193s |1267.0MiB|
|scrambled111949.smt2                                                                       |1200.208s |1239.0MiB|
|scrambled98986.smt2                                                                        |1200.178s |1145.0MiB|
|scrambled55850.smt2                                                                        |1200.181s |1139.0MiB|
|scrambled65517.smt2                                                                        |1200.179s |902.0MiB|
|scrambled102680.smt2                                                                       |1200.156s |899.0MiB|
|scrambled77008.smt2                                                                        |1200.165s |695.0MiB|
|scrambled101728.smt2                                                                       |1200.162s |687.0MiB|
|scrambled109307.smt2                                                                       |1200.104s |513.0MiB|
|scrambled95284.smt2                                                                        |1200.102s |405.0MiB|
|scrambled49820.smt2                                                                        |1200.056s |404.0MiB|
|scrambled17583.smt2                                                                        |1200.128s |398.0MiB|
|scrambled117897.smt2                                                                       |1200.049s |396.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.162s  |1200.162s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.193s  |1200.193s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.156s  |1200.156s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.235s  |1200.235s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.208s  |1200.208s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 649.732s  | 649.732s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.207s  |1200.207s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.208s  |1200.208s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled44527.smt2                                                                         | 650.848s  | 650.848s  |   0.000s  | 0.0%|
|scrambled46192.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled47581.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled49820.smt2                                                                         |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled55845.smt2                                                                         |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled55850.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled59368.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled65517.smt2                                                                         |1200.179s  |1200.179s  |   0.000s  | 0.0%|
|scrambled71015.smt2                                                                         | 503.268s  | 503.268s  |   0.000s  | 0.0%|
|scrambled76525.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled76532.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled77008.smt2                                                                         |1200.165s  |1200.165s  |   0.000s  | 0.0%|
|scrambled77308.smt2                                                                         |1200.210s  |1200.210s  |   0.000s  | 0.0%|
|scrambled8163.smt2                                                                          |1200.252s  |1200.252s  |   0.000s  | 0.0%|
|scrambled88927.smt2                                                                         |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled92964.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled95284.smt2                                                                         |1200.102s  |1200.102s  |   0.000s  | 0.0%|
</details>
