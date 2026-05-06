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
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_LRA-timeout20min}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_LRA-timeout20min}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.229s  |1200.229s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.218s  |1200.218s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.400s  |1200.400s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.316s  |1200.316s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 572.477s  | 572.477s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.245s  |1200.245s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.357s  |1200.357s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.347s  |1200.347s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.229s  |1200.229s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.218s  |1200.218s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.400s  |1200.400s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.316s  |1200.316s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 572.477s  | 572.477s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.245s  |1200.245s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.357s  |1200.357s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.347s  |1200.347s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.229s  |1200.229s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.218s  |1200.218s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.400s  |1200.400s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.316s  |1200.316s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 572.477s  | 572.477s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.245s  |1200.245s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.357s  |1200.357s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.347s  |1200.347s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.229s  |1200.229s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.218s  |1200.218s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.400s  |1200.400s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.316s  |1200.316s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 572.477s  | 572.477s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.245s  |1200.245s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.357s  |1200.357s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.347s  |1200.347s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled102680.smt2                                                                       |1200.400s |1548.0MiB|
|scrambled13209.smt2                                                                        |1200.357s |2438.0MiB|
|scrambled25695.smt2                                                                        |1200.347s |1317.0MiB|
|scrambled44527.smt2                                                                        |1200.335s |1216.0MiB|
|scrambled111949.smt2                                                                       |1200.316s |1893.0MiB|
|scrambled55850.smt2                                                                        |1200.283s |1152.0MiB|
|scrambled13169.smt2                                                                        |1200.245s |1365.0MiB|
|scrambled101728.smt2                                                                       |1200.229s |1165.0MiB|
|scrambled8163.smt2                                                                         |1200.225s |1360.0MiB|
|scrambled102621.smt2                                                                       |1200.218s |1306.0MiB|
|scrambled98986.smt2                                                                        |1200.209s |1121.0MiB|
|scrambled117897.smt2                                                                       |1200.195s |709.0MiB|
|scrambled77008.smt2                                                                        |1200.189s |718.0MiB|
|scrambled37260.smt2                                                                        |1200.139s |645.0MiB|
|scrambled109307.smt2                                                                       |1200.113s |669.0MiB|
|scrambled17583.smt2                                                                        |1200.107s |335.0MiB|
|scrambled124455.smt2                                                                       |1200.106s |417.0MiB|
|scrambled76525.smt2                                                                        |1200.088s |295.0MiB|
|scrambled47581.smt2                                                                        |1200.076s |310.0MiB|
|scrambled95284.smt2                                                                        |1200.076s |427.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled102680.smt2                                                                       |1200.400s |1548.0MiB|
|scrambled13209.smt2                                                                        |1200.357s |2438.0MiB|
|scrambled25695.smt2                                                                        |1200.347s |1317.0MiB|
|scrambled44527.smt2                                                                        |1200.335s |1216.0MiB|
|scrambled111949.smt2                                                                       |1200.316s |1893.0MiB|
|scrambled55850.smt2                                                                        |1200.283s |1152.0MiB|
|scrambled13169.smt2                                                                        |1200.245s |1365.0MiB|
|scrambled101728.smt2                                                                       |1200.229s |1165.0MiB|
|scrambled8163.smt2                                                                         |1200.225s |1360.0MiB|
|scrambled102621.smt2                                                                       |1200.218s |1306.0MiB|
|scrambled98986.smt2                                                                        |1200.209s |1121.0MiB|
|scrambled117897.smt2                                                                       |1200.195s |709.0MiB|
|scrambled77008.smt2                                                                        |1200.189s |718.0MiB|
|scrambled37260.smt2                                                                        |1200.139s |645.0MiB|
|scrambled109307.smt2                                                                       |1200.113s |669.0MiB|
|scrambled17583.smt2                                                                        |1200.107s |335.0MiB|
|scrambled124455.smt2                                                                       |1200.106s |417.0MiB|
|scrambled76525.smt2                                                                        |1200.088s |295.0MiB|
|scrambled47581.smt2                                                                        |1200.076s |310.0MiB|
|scrambled95284.smt2                                                                        |1200.076s |427.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |54.76MiB|54.76MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |1165.0MiB|1165.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1306.0MiB|1306.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |1548.0MiB|1548.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |31.304MiB|31.304MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |41.348MiB|41.348MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |669.0MiB|669.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |1893.0MiB|1893.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |56.088MiB|56.088MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |709.0MiB|709.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |52.352MiB|52.352MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |30.12MiB|30.12MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1365.0MiB|1365.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |2438.0MiB|2438.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |335.0MiB|335.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1317.0MiB|1317.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |48.172MiB|48.172MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |60.288MiB|60.288MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |645.0MiB|645.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |54.76MiB|54.76MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |1165.0MiB|1165.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1306.0MiB|1306.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |1548.0MiB|1548.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |31.304MiB|31.304MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |41.348MiB|41.348MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |669.0MiB|669.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |1893.0MiB|1893.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |56.088MiB|56.088MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |709.0MiB|709.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |52.352MiB|52.352MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |30.12MiB|30.12MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1365.0MiB|1365.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |2438.0MiB|2438.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |335.0MiB|335.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1317.0MiB|1317.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |48.172MiB|48.172MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |60.288MiB|60.288MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |645.0MiB|645.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |54.76MiB|54.76MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |1165.0MiB|1165.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1306.0MiB|1306.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |1548.0MiB|1548.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |31.304MiB|31.304MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |41.348MiB|41.348MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |669.0MiB|669.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |1893.0MiB|1893.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |56.088MiB|56.088MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |709.0MiB|709.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |52.352MiB|52.352MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |30.12MiB|30.12MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1365.0MiB|1365.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |2438.0MiB|2438.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |335.0MiB|335.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1317.0MiB|1317.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |48.172MiB|48.172MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |60.288MiB|60.288MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |645.0MiB|645.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |54.76MiB|54.76MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |1165.0MiB|1165.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1306.0MiB|1306.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |1548.0MiB|1548.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |31.304MiB|31.304MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |41.348MiB|41.348MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |669.0MiB|669.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |1893.0MiB|1893.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |56.088MiB|56.088MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |709.0MiB|709.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |52.352MiB|52.352MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |30.12MiB|30.12MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1365.0MiB|1365.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |2438.0MiB|2438.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |335.0MiB|335.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1317.0MiB|1317.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |48.172MiB|48.172MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |60.288MiB|60.288MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |645.0MiB|645.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1200.357s |2438.0MiB|
|scrambled111949.smt2                                                                       |1200.316s |1893.0MiB|
|scrambled102680.smt2                                                                       |1200.400s |1548.0MiB|
|scrambled13169.smt2                                                                        |1200.245s |1365.0MiB|
|scrambled8163.smt2                                                                         |1200.225s |1360.0MiB|
|scrambled25695.smt2                                                                        |1200.347s |1317.0MiB|
|scrambled102621.smt2                                                                       |1200.218s |1306.0MiB|
|scrambled44527.smt2                                                                        |1200.335s |1216.0MiB|
|scrambled101728.smt2                                                                       |1200.229s |1165.0MiB|
|scrambled55850.smt2                                                                        |1200.283s |1152.0MiB|
|scrambled98986.smt2                                                                        |1200.209s |1121.0MiB|
|scrambled77008.smt2                                                                        |1200.189s |718.0MiB|
|scrambled117897.smt2                                                                       |1200.195s |709.0MiB|
|scrambled109307.smt2                                                                       |1200.113s |669.0MiB|
|scrambled37260.smt2                                                                        |1200.139s |645.0MiB|
|scrambled95284.smt2                                                                        |1200.076s |427.0MiB|
|scrambled124455.smt2                                                                       |1200.106s |417.0MiB|
|scrambled17583.smt2                                                                        |1200.107s |335.0MiB|
|scrambled47581.smt2                                                                        |1200.076s |310.0MiB|
|scrambled76525.smt2                                                                        |1200.088s |295.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1200.357s |2438.0MiB|
|scrambled111949.smt2                                                                       |1200.316s |1893.0MiB|
|scrambled102680.smt2                                                                       |1200.400s |1548.0MiB|
|scrambled13169.smt2                                                                        |1200.245s |1365.0MiB|
|scrambled8163.smt2                                                                         |1200.225s |1360.0MiB|
|scrambled25695.smt2                                                                        |1200.347s |1317.0MiB|
|scrambled102621.smt2                                                                       |1200.218s |1306.0MiB|
|scrambled44527.smt2                                                                        |1200.335s |1216.0MiB|
|scrambled101728.smt2                                                                       |1200.229s |1165.0MiB|
|scrambled55850.smt2                                                                        |1200.283s |1152.0MiB|
|scrambled98986.smt2                                                                        |1200.209s |1121.0MiB|
|scrambled77008.smt2                                                                        |1200.189s |718.0MiB|
|scrambled117897.smt2                                                                       |1200.195s |709.0MiB|
|scrambled109307.smt2                                                                       |1200.113s |669.0MiB|
|scrambled37260.smt2                                                                        |1200.139s |645.0MiB|
|scrambled95284.smt2                                                                        |1200.076s |427.0MiB|
|scrambled124455.smt2                                                                       |1200.106s |417.0MiB|
|scrambled17583.smt2                                                                        |1200.107s |335.0MiB|
|scrambled47581.smt2                                                                        |1200.076s |310.0MiB|
|scrambled76525.smt2                                                                        |1200.088s |295.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.229s  |1200.229s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.218s  |1200.218s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.400s  |1200.400s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.316s  |1200.316s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 572.477s  | 572.477s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.245s  |1200.245s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.357s  |1200.357s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.347s  |1200.347s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled44527.smt2                                                                         |1200.335s  |1200.335s  |   0.000s  | 0.0%|
|scrambled46192.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled47581.smt2                                                                         |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled49820.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled55845.smt2                                                                         |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled55850.smt2                                                                         |1200.283s  |1200.283s  |   0.000s  | 0.0%|
|scrambled59368.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled65517.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled71015.smt2                                                                         |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled76525.smt2                                                                         |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled76532.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled77008.smt2                                                                         |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled77308.smt2                                                                         |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled8163.smt2                                                                          |1200.225s  |1200.225s  |   0.000s  | 0.0%|
|scrambled88927.smt2                                                                         |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled92964.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled95284.smt2                                                                         |1200.076s  |1200.076s  |   0.000s  | 0.0%|
</details>
