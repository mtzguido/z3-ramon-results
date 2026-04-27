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
Ramon benchmark for AriParti
-
Job description: 
Job tag: AriParti-threads-8-smtcomp2025-QF_LRA-timeout_20min
Runner: rise-runner-2
AriParti repo: shaowei-cai-group/AriParti
AriParti commit: 8f131f9ccdfff7303fa29d9eb28f5cd893c170d7
AriParti branch: main
AriParti options: "--engine=ariparti --ariparti-dir=. --ariparti-entry=bin/AriParti.py --ariparti-partitioner=bin/partitioner --ariparti-solver=bin/ariparti-solver --ariparti-max-running-tasks=8 --ariparti-time-limit=1200"
AriParti solver backend: z3
AriParti inputs: inputs/smt_comp_2025_parallel/QF_LRA
AriParti commit message: docs: updated 'Cite This Work' section in README with official citation.

</pre>
# RHS
<pre>
Ramon benchmark for AriParti
-
Job description: 
Job tag: AriParti-threads-8-smtcomp2025-QF_LRA-timeout_20min
Runner: rise-runner-2
AriParti repo: shaowei-cai-group/AriParti
AriParti commit: 8f131f9ccdfff7303fa29d9eb28f5cd893c170d7
AriParti branch: main
AriParti options: "--engine=ariparti --ariparti-dir=. --ariparti-entry=bin/AriParti.py --ariparti-partitioner=bin/partitioner --ariparti-solver=bin/ariparti-solver --ariparti-max-running-tasks=8 --ariparti-time-limit=1200"
AriParti solver backend: z3
AriParti inputs: inputs/smt_comp_2025_parallel/QF_LRA
AriParti commit message: docs: updated 'Cite This Work' section in README with official citation.

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.316s  |1200.316s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.386s  |1200.386s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 533.612s  | 533.612s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 430.817s  | 430.817s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.552s  |1200.552s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.177s  |1200.177s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 632.925s  | 632.925s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.438s  |1200.438s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.465s  |1200.465s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.193s  |1200.193s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.443s  |1200.443s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.223s  |1200.223s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.167s  |1200.167s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.163s  |1200.163s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.316s  |1200.316s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.386s  |1200.386s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 533.612s  | 533.612s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 430.817s  | 430.817s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.552s  |1200.552s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.177s  |1200.177s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 632.925s  | 632.925s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.438s  |1200.438s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.465s  |1200.465s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.193s  |1200.193s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.443s  |1200.443s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.223s  |1200.223s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.167s  |1200.167s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.163s  |1200.163s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.316s  |1200.316s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.386s  |1200.386s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 533.612s  | 533.612s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 430.817s  | 430.817s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.552s  |1200.552s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.177s  |1200.177s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 632.925s  | 632.925s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.438s  |1200.438s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.465s  |1200.465s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.193s  |1200.193s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.443s  |1200.443s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.223s  |1200.223s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.167s  |1200.167s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.163s  |1200.163s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.316s  |1200.316s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.386s  |1200.386s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 533.612s  | 533.612s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 430.817s  | 430.817s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.552s  |1200.552s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.177s  |1200.177s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 632.925s  | 632.925s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.438s  |1200.438s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.465s  |1200.465s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.193s  |1200.193s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.443s  |1200.443s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.223s  |1200.223s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.167s  |1200.167s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.163s  |1200.163s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled111949.smt2                                                                       |1200.552s |13.546GiB|
|scrambled8163.smt2                                                                         |1200.492s |11.026GiB|
|scrambled13209.smt2                                                                        |1200.465s |17.493GiB|
|scrambled25695.smt2                                                                        |1200.443s |12.813GiB|
|scrambled55850.smt2                                                                        |1200.440s |11.167GiB|
|scrambled13169.smt2                                                                        |1200.438s |10.813GiB|
|scrambled102621.smt2                                                                       |1200.386s |12.921GiB|
|scrambled77008.smt2                                                                        |1200.323s |7938.0MiB|
|scrambled101728.smt2                                                                       |1200.316s |9380.0MiB|
|scrambled98986.smt2                                                                        |1200.262s |12.421GiB|
|scrambled59368.smt2                                                                        |1200.247s |2638.0MiB|
|scrambled55845.smt2                                                                        |1200.246s |1100.0MiB|
|scrambled31085.smt2                                                                        |1200.223s |420.0MiB|
|scrambled95284.smt2                                                                        |1200.212s |3234.0MiB|
|scrambled103576.smt2                                                                       |1200.197s |305.0MiB|
|scrambled17583.smt2                                                                        |1200.193s |2385.0MiB|
|scrambled76525.smt2                                                                        |1200.192s |2160.0MiB|
|scrambled115671.smt2                                                                       |1200.184s |505.0MiB|
|scrambled117897.smt2                                                                       |1200.177s |4530.0MiB|
|scrambled124455.smt2                                                                       |1200.169s |2733.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled111949.smt2                                                                       |1200.552s |13.546GiB|
|scrambled8163.smt2                                                                         |1200.492s |11.026GiB|
|scrambled13209.smt2                                                                        |1200.465s |17.493GiB|
|scrambled25695.smt2                                                                        |1200.443s |12.813GiB|
|scrambled55850.smt2                                                                        |1200.440s |11.167GiB|
|scrambled13169.smt2                                                                        |1200.438s |10.813GiB|
|scrambled102621.smt2                                                                       |1200.386s |12.921GiB|
|scrambled77008.smt2                                                                        |1200.323s |7938.0MiB|
|scrambled101728.smt2                                                                       |1200.316s |9380.0MiB|
|scrambled98986.smt2                                                                        |1200.262s |12.421GiB|
|scrambled59368.smt2                                                                        |1200.247s |2638.0MiB|
|scrambled55845.smt2                                                                        |1200.246s |1100.0MiB|
|scrambled31085.smt2                                                                        |1200.223s |420.0MiB|
|scrambled95284.smt2                                                                        |1200.212s |3234.0MiB|
|scrambled103576.smt2                                                                       |1200.197s |305.0MiB|
|scrambled17583.smt2                                                                        |1200.193s |2385.0MiB|
|scrambled76525.smt2                                                                        |1200.192s |2160.0MiB|
|scrambled115671.smt2                                                                       |1200.184s |505.0MiB|
|scrambled117897.smt2                                                                       |1200.177s |4530.0MiB|
|scrambled124455.smt2                                                                       |1200.169s |2733.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |468.0MiB|468.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |9380.0MiB|9380.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |12.921GiB|12.921GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |9100.0MiB|9100.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |4660.0MiB|4660.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |4952.0MiB|4952.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |13.546GiB|13.546GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |505.0MiB|505.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |4530.0MiB|4530.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |396.0MiB|396.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |2733.0MiB|2733.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |10.813GiB|10.813GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |17.493GiB|17.493GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2385.0MiB|2385.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |12.813GiB|12.813GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |420.0MiB|420.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |450.0MiB|450.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |4180.0MiB|4180.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |468.0MiB|468.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |9380.0MiB|9380.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |12.921GiB|12.921GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |9100.0MiB|9100.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |4660.0MiB|4660.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |4952.0MiB|4952.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |13.546GiB|13.546GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |505.0MiB|505.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |4530.0MiB|4530.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |396.0MiB|396.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |2733.0MiB|2733.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |10.813GiB|10.813GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |17.493GiB|17.493GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2385.0MiB|2385.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |12.813GiB|12.813GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |420.0MiB|420.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |450.0MiB|450.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |4180.0MiB|4180.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |468.0MiB|468.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |9380.0MiB|9380.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |12.921GiB|12.921GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |9100.0MiB|9100.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |4660.0MiB|4660.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |4952.0MiB|4952.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |13.546GiB|13.546GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |505.0MiB|505.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |4530.0MiB|4530.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |396.0MiB|396.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |2733.0MiB|2733.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |10.813GiB|10.813GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |17.493GiB|17.493GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2385.0MiB|2385.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |12.813GiB|12.813GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |420.0MiB|420.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |450.0MiB|450.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |4180.0MiB|4180.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |468.0MiB|468.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |9380.0MiB|9380.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |12.921GiB|12.921GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |9100.0MiB|9100.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |4660.0MiB|4660.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |4952.0MiB|4952.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |13.546GiB|13.546GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |505.0MiB|505.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |4530.0MiB|4530.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |396.0MiB|396.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |2733.0MiB|2733.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |10.813GiB|10.813GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |17.493GiB|17.493GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2385.0MiB|2385.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |12.813GiB|12.813GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |420.0MiB|420.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |450.0MiB|450.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |4180.0MiB|4180.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1200.465s |17.493GiB|
|scrambled111949.smt2                                                                       |1200.552s |13.546GiB|
|scrambled102621.smt2                                                                       |1200.386s |12.921GiB|
|scrambled25695.smt2                                                                        |1200.443s |12.813GiB|
|scrambled98986.smt2                                                                        |1200.262s |12.421GiB|
|scrambled55850.smt2                                                                        |1200.440s |11.167GiB|
|scrambled8163.smt2                                                                         |1200.492s |11.026GiB|
|scrambled13169.smt2                                                                        |1200.438s |10.813GiB|
|scrambled44527.smt2                                                                        | 382.246s |10.622GiB|
|scrambled101728.smt2                                                                       |1200.316s |9380.0MiB|
|scrambled102680.smt2                                                                       | 533.612s |9100.0MiB|
|scrambled77008.smt2                                                                        |1200.323s |7938.0MiB|
|scrambled109307.smt2                                                                       | 430.817s |4952.0MiB|
|scrambled104811.smt2                                                                       |1200.123s |4660.0MiB|
|scrambled117897.smt2                                                                       |1200.177s |4530.0MiB|
|scrambled37260.smt2                                                                        |1200.163s |4180.0MiB|
|scrambled95284.smt2                                                                        |1200.212s |3234.0MiB|
|scrambled77308.smt2                                                                        |1200.111s |3061.0MiB|
|scrambled124455.smt2                                                                       |1200.169s |2733.0MiB|
|scrambled59368.smt2                                                                        |1200.247s |2638.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1200.465s |17.493GiB|
|scrambled111949.smt2                                                                       |1200.552s |13.546GiB|
|scrambled102621.smt2                                                                       |1200.386s |12.921GiB|
|scrambled25695.smt2                                                                        |1200.443s |12.813GiB|
|scrambled98986.smt2                                                                        |1200.262s |12.421GiB|
|scrambled55850.smt2                                                                        |1200.440s |11.167GiB|
|scrambled8163.smt2                                                                         |1200.492s |11.026GiB|
|scrambled13169.smt2                                                                        |1200.438s |10.813GiB|
|scrambled44527.smt2                                                                        | 382.246s |10.622GiB|
|scrambled101728.smt2                                                                       |1200.316s |9380.0MiB|
|scrambled102680.smt2                                                                       | 533.612s |9100.0MiB|
|scrambled77008.smt2                                                                        |1200.323s |7938.0MiB|
|scrambled109307.smt2                                                                       | 430.817s |4952.0MiB|
|scrambled104811.smt2                                                                       |1200.123s |4660.0MiB|
|scrambled117897.smt2                                                                       |1200.177s |4530.0MiB|
|scrambled37260.smt2                                                                        |1200.163s |4180.0MiB|
|scrambled95284.smt2                                                                        |1200.212s |3234.0MiB|
|scrambled77308.smt2                                                                        |1200.111s |3061.0MiB|
|scrambled124455.smt2                                                                       |1200.169s |2733.0MiB|
|scrambled59368.smt2                                                                        |1200.247s |2638.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.316s  |1200.316s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.386s  |1200.386s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 533.612s  | 533.612s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 430.817s  | 430.817s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.552s  |1200.552s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.177s  |1200.177s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 632.925s  | 632.925s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.438s  |1200.438s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.465s  |1200.465s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.193s  |1200.193s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.443s  |1200.443s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.223s  |1200.223s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.167s  |1200.167s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled44527.smt2                                                                         | 382.246s  | 382.246s  |   0.000s  | 0.0%|
|scrambled46192.smt2                                                                         |1200.144s  |1200.144s  |   0.000s  | 0.0%|
|scrambled47581.smt2                                                                         | 724.137s  | 724.137s  |   0.000s  | 0.0%|
|scrambled49820.smt2                                                                         |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled55845.smt2                                                                         |1200.246s  |1200.246s  |   0.000s  | 0.0%|
|scrambled55850.smt2                                                                         |1200.440s  |1200.440s  |   0.000s  | 0.0%|
|scrambled59368.smt2                                                                         |1200.247s  |1200.247s  |   0.000s  | 0.0%|
|scrambled65517.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled71015.smt2                                                                         | 536.154s  | 536.154s  |   0.000s  | 0.0%|
|scrambled76525.smt2                                                                         |1200.192s  |1200.192s  |   0.000s  | 0.0%|
|scrambled76532.smt2                                                                         |1200.166s  |1200.166s  |   0.000s  | 0.0%|
|scrambled77008.smt2                                                                         |1200.323s  |1200.323s  |   0.000s  | 0.0%|
|scrambled77308.smt2                                                                         |1200.111s  |1200.111s  |   0.000s  | 0.0%|
|scrambled8163.smt2                                                                          |1200.492s  |1200.492s  |   0.000s  | 0.0%|
|scrambled88927.smt2                                                                         | 180.811s  | 180.811s  |   0.000s  | 0.0%|
|scrambled92964.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled95284.smt2                                                                         |1200.212s  |1200.212s  |   0.000s  | 0.0%|
</details>
