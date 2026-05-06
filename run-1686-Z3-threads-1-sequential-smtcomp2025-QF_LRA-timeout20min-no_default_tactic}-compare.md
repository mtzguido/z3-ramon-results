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
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_LRA-timeout20min-no_default_tactic}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_LRA-timeout20min-no_default_tactic}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.200s  |1200.200s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.230s  |1200.230s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 551.690s  | 551.690s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.286s  |1200.286s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.182s  |1200.182s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.118s  |1200.118s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.200s  |1200.200s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.230s  |1200.230s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 551.690s  | 551.690s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.286s  |1200.286s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.182s  |1200.182s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.118s  |1200.118s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.200s  |1200.200s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.230s  |1200.230s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 551.690s  | 551.690s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.286s  |1200.286s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.182s  |1200.182s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.118s  |1200.118s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.200s  |1200.200s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.230s  |1200.230s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 551.690s  | 551.690s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.286s  |1200.286s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.182s  |1200.182s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.118s  |1200.118s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1200.286s |2540.0MiB|
|scrambled111949.smt2                                                                       |1200.230s |1982.0MiB|
|scrambled102680.smt2                                                                       |1200.200s |1525.0MiB|
|scrambled102621.smt2                                                                       |1200.187s |1259.0MiB|
|scrambled25695.smt2                                                                        |1200.182s |1321.0MiB|
|scrambled44527.smt2                                                                        |1200.169s |1216.0MiB|
|scrambled98986.smt2                                                                        |1200.166s |1105.0MiB|
|scrambled55850.smt2                                                                        |1200.162s |1165.0MiB|
|scrambled13169.smt2                                                                        |1200.155s |1369.0MiB|
|scrambled8163.smt2                                                                         |1200.154s |1389.0MiB|
|scrambled101728.smt2                                                                       |1200.151s |1154.0MiB|
|scrambled37260.smt2                                                                        |1200.118s |642.0MiB|
|scrambled109307.smt2                                                                       |1200.115s |668.0MiB|
|scrambled117897.smt2                                                                       |1200.114s |706.0MiB|
|scrambled77008.smt2                                                                        |1200.109s |693.0MiB|
|scrambled95284.smt2                                                                        |1200.082s |425.0MiB|
|scrambled17583.smt2                                                                        |1200.080s |340.0MiB|
|scrambled47581.smt2                                                                        |1200.079s |311.0MiB|
|scrambled76525.smt2                                                                        |1200.074s |297.0MiB|
|scrambled124455.smt2                                                                       |1200.066s |417.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1200.286s |2540.0MiB|
|scrambled111949.smt2                                                                       |1200.230s |1982.0MiB|
|scrambled102680.smt2                                                                       |1200.200s |1525.0MiB|
|scrambled102621.smt2                                                                       |1200.187s |1259.0MiB|
|scrambled25695.smt2                                                                        |1200.182s |1321.0MiB|
|scrambled44527.smt2                                                                        |1200.169s |1216.0MiB|
|scrambled98986.smt2                                                                        |1200.166s |1105.0MiB|
|scrambled55850.smt2                                                                        |1200.162s |1165.0MiB|
|scrambled13169.smt2                                                                        |1200.155s |1369.0MiB|
|scrambled8163.smt2                                                                         |1200.154s |1389.0MiB|
|scrambled101728.smt2                                                                       |1200.151s |1154.0MiB|
|scrambled37260.smt2                                                                        |1200.118s |642.0MiB|
|scrambled109307.smt2                                                                       |1200.115s |668.0MiB|
|scrambled117897.smt2                                                                       |1200.114s |706.0MiB|
|scrambled77008.smt2                                                                        |1200.109s |693.0MiB|
|scrambled95284.smt2                                                                        |1200.082s |425.0MiB|
|scrambled17583.smt2                                                                        |1200.080s |340.0MiB|
|scrambled47581.smt2                                                                        |1200.079s |311.0MiB|
|scrambled76525.smt2                                                                        |1200.074s |297.0MiB|
|scrambled124455.smt2                                                                       |1200.066s |417.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |54.94MiB|54.94MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |1154.0MiB|1154.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1259.0MiB|1259.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |1525.0MiB|1525.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |31.208MiB|31.208MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |41.576MiB|41.576MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |668.0MiB|668.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |1982.0MiB|1982.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |56.472MiB|56.472MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |706.0MiB|706.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |52.212MiB|52.212MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |30.072MiB|30.072MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1369.0MiB|1369.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |2540.0MiB|2540.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |340.0MiB|340.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1321.0MiB|1321.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |48.048MiB|48.048MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |60.332MiB|60.332MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |642.0MiB|642.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |54.94MiB|54.94MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |1154.0MiB|1154.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1259.0MiB|1259.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |1525.0MiB|1525.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |31.208MiB|31.208MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |41.576MiB|41.576MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |668.0MiB|668.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |1982.0MiB|1982.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |56.472MiB|56.472MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |706.0MiB|706.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |52.212MiB|52.212MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |30.072MiB|30.072MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1369.0MiB|1369.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |2540.0MiB|2540.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |340.0MiB|340.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1321.0MiB|1321.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |48.048MiB|48.048MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |60.332MiB|60.332MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |642.0MiB|642.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |54.94MiB|54.94MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |1154.0MiB|1154.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1259.0MiB|1259.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |1525.0MiB|1525.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |31.208MiB|31.208MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |41.576MiB|41.576MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |668.0MiB|668.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |1982.0MiB|1982.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |56.472MiB|56.472MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |706.0MiB|706.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |52.212MiB|52.212MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |30.072MiB|30.072MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1369.0MiB|1369.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |2540.0MiB|2540.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |340.0MiB|340.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1321.0MiB|1321.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |48.048MiB|48.048MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |60.332MiB|60.332MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |642.0MiB|642.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |54.94MiB|54.94MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |1154.0MiB|1154.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1259.0MiB|1259.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |1525.0MiB|1525.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |31.208MiB|31.208MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |41.576MiB|41.576MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |668.0MiB|668.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |1982.0MiB|1982.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |56.472MiB|56.472MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |706.0MiB|706.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |52.212MiB|52.212MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |30.072MiB|30.072MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1369.0MiB|1369.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |2540.0MiB|2540.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |340.0MiB|340.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1321.0MiB|1321.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |48.048MiB|48.048MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |60.332MiB|60.332MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |642.0MiB|642.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1200.286s |2540.0MiB|
|scrambled111949.smt2                                                                       |1200.230s |1982.0MiB|
|scrambled102680.smt2                                                                       |1200.200s |1525.0MiB|
|scrambled8163.smt2                                                                         |1200.154s |1389.0MiB|
|scrambled13169.smt2                                                                        |1200.155s |1369.0MiB|
|scrambled25695.smt2                                                                        |1200.182s |1321.0MiB|
|scrambled102621.smt2                                                                       |1200.187s |1259.0MiB|
|scrambled44527.smt2                                                                        |1200.169s |1216.0MiB|
|scrambled55850.smt2                                                                        |1200.162s |1165.0MiB|
|scrambled101728.smt2                                                                       |1200.151s |1154.0MiB|
|scrambled98986.smt2                                                                        |1200.166s |1105.0MiB|
|scrambled117897.smt2                                                                       |1200.114s |706.0MiB|
|scrambled77008.smt2                                                                        |1200.109s |693.0MiB|
|scrambled109307.smt2                                                                       |1200.115s |668.0MiB|
|scrambled37260.smt2                                                                        |1200.118s |642.0MiB|
|scrambled95284.smt2                                                                        |1200.082s |425.0MiB|
|scrambled124455.smt2                                                                       |1200.066s |417.0MiB|
|scrambled17583.smt2                                                                        |1200.080s |340.0MiB|
|scrambled47581.smt2                                                                        |1200.079s |311.0MiB|
|scrambled76525.smt2                                                                        |1200.074s |297.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1200.286s |2540.0MiB|
|scrambled111949.smt2                                                                       |1200.230s |1982.0MiB|
|scrambled102680.smt2                                                                       |1200.200s |1525.0MiB|
|scrambled8163.smt2                                                                         |1200.154s |1389.0MiB|
|scrambled13169.smt2                                                                        |1200.155s |1369.0MiB|
|scrambled25695.smt2                                                                        |1200.182s |1321.0MiB|
|scrambled102621.smt2                                                                       |1200.187s |1259.0MiB|
|scrambled44527.smt2                                                                        |1200.169s |1216.0MiB|
|scrambled55850.smt2                                                                        |1200.162s |1165.0MiB|
|scrambled101728.smt2                                                                       |1200.151s |1154.0MiB|
|scrambled98986.smt2                                                                        |1200.166s |1105.0MiB|
|scrambled117897.smt2                                                                       |1200.114s |706.0MiB|
|scrambled77008.smt2                                                                        |1200.109s |693.0MiB|
|scrambled109307.smt2                                                                       |1200.115s |668.0MiB|
|scrambled37260.smt2                                                                        |1200.118s |642.0MiB|
|scrambled95284.smt2                                                                        |1200.082s |425.0MiB|
|scrambled124455.smt2                                                                       |1200.066s |417.0MiB|
|scrambled17583.smt2                                                                        |1200.080s |340.0MiB|
|scrambled47581.smt2                                                                        |1200.079s |311.0MiB|
|scrambled76525.smt2                                                                        |1200.074s |297.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.200s  |1200.200s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.230s  |1200.230s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 551.690s  | 551.690s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.286s  |1200.286s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.182s  |1200.182s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled44527.smt2                                                                         |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled46192.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled47581.smt2                                                                         |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled49820.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled55845.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled55850.smt2                                                                         |1200.162s  |1200.162s  |   0.000s  | 0.0%|
|scrambled59368.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled65517.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled71015.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled76525.smt2                                                                         |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled76532.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled77008.smt2                                                                         |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled77308.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled8163.smt2                                                                          |1200.154s  |1200.154s  |   0.000s  | 0.0%|
|scrambled88927.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled92964.smt2                                                                         |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled95284.smt2                                                                         |1200.082s  |1200.082s  |   0.000s  | 0.0%|
</details>
