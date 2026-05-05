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
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LRA-timeout20min-bb2-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=true smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LRA-timeout20min-bb2-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=true smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.026s  |1201.026s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.164s  |1201.164s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 653.192s  | 653.192s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1201.073s  |1201.073s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.514s  |1201.514s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.861s  |1200.861s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 537.268s  | 537.268s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.443s  |1200.443s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.227s  |1201.227s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1201.886s  |1201.886s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.341s  |1200.341s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.237s  |1201.237s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.583s  |1200.583s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.026s  |1201.026s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.164s  |1201.164s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 653.192s  | 653.192s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1201.073s  |1201.073s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.514s  |1201.514s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.861s  |1200.861s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 537.268s  | 537.268s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.443s  |1200.443s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.227s  |1201.227s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1201.886s  |1201.886s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.341s  |1200.341s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.237s  |1201.237s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.583s  |1200.583s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.026s  |1201.026s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.164s  |1201.164s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 653.192s  | 653.192s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1201.073s  |1201.073s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.514s  |1201.514s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.861s  |1200.861s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 537.268s  | 537.268s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.443s  |1200.443s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.227s  |1201.227s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1201.886s  |1201.886s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.341s  |1200.341s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.237s  |1201.237s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.583s  |1200.583s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.026s  |1201.026s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.164s  |1201.164s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 653.192s  | 653.192s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1201.073s  |1201.073s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.514s  |1201.514s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.861s  |1200.861s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 537.268s  | 537.268s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.443s  |1200.443s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.227s  |1201.227s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1201.886s  |1201.886s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.341s  |1200.341s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.237s  |1201.237s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.583s  |1200.583s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1201.886s |20.963GiB|
|scrambled98986.smt2                                                                        |1201.573s |12.377GiB|
|scrambled111949.smt2                                                                       |1201.514s |16.297GiB|
|scrambled25695.smt2                                                                        |1201.237s |13.412GiB|
|scrambled13169.smt2                                                                        |1201.227s |10.778GiB|
|scrambled55850.smt2                                                                        |1201.194s |12.304GiB|
|scrambled102621.smt2                                                                       |1201.164s |12.903GiB|
|scrambled109307.smt2                                                                       |1201.073s |8390.0MiB|
|scrambled8163.smt2                                                                         |1201.036s |11.047GiB|
|scrambled101728.smt2                                                                       |1201.026s |10.395GiB|
|scrambled117897.smt2                                                                       |1200.861s |5954.0MiB|
|scrambled77008.smt2                                                                        |1200.840s |7601.0MiB|
|scrambled37260.smt2                                                                        |1200.583s |5060.0MiB|
|scrambled95284.smt2                                                                        |1200.573s |4650.0MiB|
|scrambled47581.smt2                                                                        |1200.507s |3346.0MiB|
|scrambled124455.smt2                                                                       |1200.443s |3675.0MiB|
|scrambled59368.smt2                                                                        |1200.418s |2900.0MiB|
|scrambled76525.smt2                                                                        |1200.353s |2894.0MiB|
|scrambled17583.smt2                                                                        |1200.341s |3217.0MiB|
|scrambled55845.smt2                                                                        |1200.332s |1518.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1201.886s |20.963GiB|
|scrambled98986.smt2                                                                        |1201.573s |12.377GiB|
|scrambled111949.smt2                                                                       |1201.514s |16.297GiB|
|scrambled25695.smt2                                                                        |1201.237s |13.412GiB|
|scrambled13169.smt2                                                                        |1201.227s |10.778GiB|
|scrambled55850.smt2                                                                        |1201.194s |12.304GiB|
|scrambled102621.smt2                                                                       |1201.164s |12.903GiB|
|scrambled109307.smt2                                                                       |1201.073s |8390.0MiB|
|scrambled8163.smt2                                                                         |1201.036s |11.047GiB|
|scrambled101728.smt2                                                                       |1201.026s |10.395GiB|
|scrambled117897.smt2                                                                       |1200.861s |5954.0MiB|
|scrambled77008.smt2                                                                        |1200.840s |7601.0MiB|
|scrambled37260.smt2                                                                        |1200.583s |5060.0MiB|
|scrambled95284.smt2                                                                        |1200.573s |4650.0MiB|
|scrambled47581.smt2                                                                        |1200.507s |3346.0MiB|
|scrambled124455.smt2                                                                       |1200.443s |3675.0MiB|
|scrambled59368.smt2                                                                        |1200.418s |2900.0MiB|
|scrambled76525.smt2                                                                        |1200.353s |2894.0MiB|
|scrambled17583.smt2                                                                        |1200.341s |3217.0MiB|
|scrambled55845.smt2                                                                        |1200.332s |1518.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |560.0MiB|560.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |10.395GiB|10.395GiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |12.903GiB|12.903GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |11.632GiB|11.632GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |304.0MiB|304.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |408.0MiB|408.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |8390.0MiB|8390.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |16.297GiB|16.297GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |550.0MiB|550.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |5954.0MiB|5954.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |542.0MiB|542.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |3675.0MiB|3675.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |298.0MiB|298.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |10.778GiB|10.778GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |20.963GiB|20.963GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |3217.0MiB|3217.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |13.412GiB|13.412GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |446.0MiB|446.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |583.0MiB|583.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |5060.0MiB|5060.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |560.0MiB|560.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |10.395GiB|10.395GiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |12.903GiB|12.903GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |11.632GiB|11.632GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |304.0MiB|304.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |408.0MiB|408.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |8390.0MiB|8390.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |16.297GiB|16.297GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |550.0MiB|550.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |5954.0MiB|5954.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |542.0MiB|542.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |3675.0MiB|3675.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |298.0MiB|298.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |10.778GiB|10.778GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |20.963GiB|20.963GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |3217.0MiB|3217.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |13.412GiB|13.412GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |446.0MiB|446.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |583.0MiB|583.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |5060.0MiB|5060.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |560.0MiB|560.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |10.395GiB|10.395GiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |12.903GiB|12.903GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |11.632GiB|11.632GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |304.0MiB|304.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |408.0MiB|408.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |8390.0MiB|8390.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |16.297GiB|16.297GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |550.0MiB|550.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |5954.0MiB|5954.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |542.0MiB|542.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |3675.0MiB|3675.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |298.0MiB|298.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |10.778GiB|10.778GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |20.963GiB|20.963GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |3217.0MiB|3217.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |13.412GiB|13.412GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |446.0MiB|446.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |583.0MiB|583.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |5060.0MiB|5060.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |560.0MiB|560.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |10.395GiB|10.395GiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |12.903GiB|12.903GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |11.632GiB|11.632GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |304.0MiB|304.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |408.0MiB|408.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |8390.0MiB|8390.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |16.297GiB|16.297GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |550.0MiB|550.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |5954.0MiB|5954.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |542.0MiB|542.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |3675.0MiB|3675.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |298.0MiB|298.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |10.778GiB|10.778GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |20.963GiB|20.963GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |3217.0MiB|3217.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |13.412GiB|13.412GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |446.0MiB|446.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |583.0MiB|583.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |5060.0MiB|5060.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1201.886s |20.963GiB|
|scrambled111949.smt2                                                                       |1201.514s |16.297GiB|
|scrambled25695.smt2                                                                        |1201.237s |13.412GiB|
|scrambled102621.smt2                                                                       |1201.164s |12.903GiB|
|scrambled98986.smt2                                                                        |1201.573s |12.377GiB|
|scrambled55850.smt2                                                                        |1201.194s |12.304GiB|
|scrambled102680.smt2                                                                       | 653.192s |11.632GiB|
|scrambled8163.smt2                                                                         |1201.036s |11.047GiB|
|scrambled44527.smt2                                                                        | 399.932s |10.907GiB|
|scrambled13169.smt2                                                                        |1201.227s |10.778GiB|
|scrambled101728.smt2                                                                       |1201.026s |10.395GiB|
|scrambled109307.smt2                                                                       |1201.073s |8390.0MiB|
|scrambled77008.smt2                                                                        |1200.840s |7601.0MiB|
|scrambled117897.smt2                                                                       |1200.861s |5954.0MiB|
|scrambled37260.smt2                                                                        |1200.583s |5060.0MiB|
|scrambled95284.smt2                                                                        |1200.573s |4650.0MiB|
|scrambled124455.smt2                                                                       |1200.443s |3675.0MiB|
|scrambled47581.smt2                                                                        |1200.507s |3346.0MiB|
|scrambled17583.smt2                                                                        |1200.341s |3217.0MiB|
|scrambled59368.smt2                                                                        |1200.418s |2900.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1201.886s |20.963GiB|
|scrambled111949.smt2                                                                       |1201.514s |16.297GiB|
|scrambled25695.smt2                                                                        |1201.237s |13.412GiB|
|scrambled102621.smt2                                                                       |1201.164s |12.903GiB|
|scrambled98986.smt2                                                                        |1201.573s |12.377GiB|
|scrambled55850.smt2                                                                        |1201.194s |12.304GiB|
|scrambled102680.smt2                                                                       | 653.192s |11.632GiB|
|scrambled8163.smt2                                                                         |1201.036s |11.047GiB|
|scrambled44527.smt2                                                                        | 399.932s |10.907GiB|
|scrambled13169.smt2                                                                        |1201.227s |10.778GiB|
|scrambled101728.smt2                                                                       |1201.026s |10.395GiB|
|scrambled109307.smt2                                                                       |1201.073s |8390.0MiB|
|scrambled77008.smt2                                                                        |1200.840s |7601.0MiB|
|scrambled117897.smt2                                                                       |1200.861s |5954.0MiB|
|scrambled37260.smt2                                                                        |1200.583s |5060.0MiB|
|scrambled95284.smt2                                                                        |1200.573s |4650.0MiB|
|scrambled124455.smt2                                                                       |1200.443s |3675.0MiB|
|scrambled47581.smt2                                                                        |1200.507s |3346.0MiB|
|scrambled17583.smt2                                                                        |1200.341s |3217.0MiB|
|scrambled59368.smt2                                                                        |1200.418s |2900.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.026s  |1201.026s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.164s  |1201.164s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 653.192s  | 653.192s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1201.073s  |1201.073s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.514s  |1201.514s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.861s  |1200.861s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 537.268s  | 537.268s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.443s  |1200.443s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.227s  |1201.227s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1201.886s  |1201.886s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.341s  |1200.341s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.237s  |1201.237s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.583s  |1200.583s  |   0.000s  | 0.0%|
|scrambled44527.smt2                                                                         | 399.932s  | 399.932s  |   0.000s  | 0.0%|
|scrambled46192.smt2                                                                         |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled47581.smt2                                                                         |1200.507s  |1200.507s  |   0.000s  | 0.0%|
|scrambled49820.smt2                                                                         |1200.125s  |1200.125s  |   0.000s  | 0.0%|
|scrambled55845.smt2                                                                         |1200.332s  |1200.332s  |   0.000s  | 0.0%|
|scrambled55850.smt2                                                                         |1201.194s  |1201.194s  |   0.000s  | 0.0%|
|scrambled59368.smt2                                                                         |1200.418s  |1200.418s  |   0.000s  | 0.0%|
|scrambled65517.smt2                                                                         |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled71015.smt2                                                                         |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled76525.smt2                                                                         |1200.353s  |1200.353s  |   0.000s  | 0.0%|
|scrambled76532.smt2                                                                         |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled77008.smt2                                                                         |1200.840s  |1200.840s  |   0.000s  | 0.0%|
|scrambled77308.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled8163.smt2                                                                          |1201.036s  |1201.036s  |   0.000s  | 0.0%|
|scrambled88927.smt2                                                                         | 416.404s  | 416.404s  |   0.000s  | 0.0%|
|scrambled92964.smt2                                                                         |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled95284.smt2                                                                         |1200.573s  |1200.573s  |   0.000s  | 0.0%|
</details>
