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
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_LRA-timeout20min-no_default_tactic-auto_config}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_LRA-timeout20min-no_default_tactic-auto_config}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.149s  |1200.149s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 620.569s  | 620.569s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1043.753s  |1043.753s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.217s  |1200.217s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 791.861s  | 791.861s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.185s  |1200.185s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.029s  |1200.029s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.149s  |1200.149s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 620.569s  | 620.569s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1043.753s  |1043.753s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.217s  |1200.217s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 791.861s  | 791.861s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.185s  |1200.185s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.029s  |1200.029s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.149s  |1200.149s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 620.569s  | 620.569s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1043.753s  |1043.753s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.217s  |1200.217s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 791.861s  | 791.861s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.185s  |1200.185s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.029s  |1200.029s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.149s  |1200.149s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 620.569s  | 620.569s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1043.753s  |1043.753s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.217s  |1200.217s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 791.861s  | 791.861s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.185s  |1200.185s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.029s  |1200.029s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1200.276s |2544.0MiB|
|scrambled111949.smt2                                                                       |1200.217s |2040.0MiB|
|scrambled25695.smt2                                                                        |1200.185s |1684.0MiB|
|scrambled98986.smt2                                                                        |1200.173s |1357.0MiB|
|scrambled102621.smt2                                                                       |1200.159s |1545.0MiB|
|scrambled13169.smt2                                                                        |1200.155s |1239.0MiB|
|scrambled55850.smt2                                                                        |1200.153s |1334.0MiB|
|scrambled44527.smt2                                                                        |1200.150s |1130.0MiB|
|scrambled101728.smt2                                                                       |1200.149s |1271.0MiB|
|scrambled8163.smt2                                                                         |1200.148s |1252.0MiB|
|scrambled77008.smt2                                                                        |1200.132s |982.0MiB|
|scrambled37260.smt2                                                                        |1200.122s |1006.0MiB|
|scrambled124455.smt2                                                                       |1200.079s |476.0MiB|
|scrambled95284.smt2                                                                        |1200.077s |539.0MiB|
|scrambled47581.smt2                                                                        |1200.064s |319.0MiB|
|scrambled59368.smt2                                                                        |1200.055s |294.0MiB|
|scrambled117897.smt2                                                                       |1200.053s |399.0MiB|
|scrambled17583.smt2                                                                        |1200.051s |330.0MiB|
|scrambled76525.smt2                                                                        |1200.046s |298.0MiB|
|scrambled65517.smt2                                                                        |1200.040s |78.088MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1200.276s |2544.0MiB|
|scrambled111949.smt2                                                                       |1200.217s |2040.0MiB|
|scrambled25695.smt2                                                                        |1200.185s |1684.0MiB|
|scrambled98986.smt2                                                                        |1200.173s |1357.0MiB|
|scrambled102621.smt2                                                                       |1200.159s |1545.0MiB|
|scrambled13169.smt2                                                                        |1200.155s |1239.0MiB|
|scrambled55850.smt2                                                                        |1200.153s |1334.0MiB|
|scrambled44527.smt2                                                                        |1200.150s |1130.0MiB|
|scrambled101728.smt2                                                                       |1200.149s |1271.0MiB|
|scrambled8163.smt2                                                                         |1200.148s |1252.0MiB|
|scrambled77008.smt2                                                                        |1200.132s |982.0MiB|
|scrambled37260.smt2                                                                        |1200.122s |1006.0MiB|
|scrambled124455.smt2                                                                       |1200.079s |476.0MiB|
|scrambled95284.smt2                                                                        |1200.077s |539.0MiB|
|scrambled47581.smt2                                                                        |1200.064s |319.0MiB|
|scrambled59368.smt2                                                                        |1200.055s |294.0MiB|
|scrambled117897.smt2                                                                       |1200.053s |399.0MiB|
|scrambled17583.smt2                                                                        |1200.051s |330.0MiB|
|scrambled76525.smt2                                                                        |1200.046s |298.0MiB|
|scrambled65517.smt2                                                                        |1200.040s |78.088MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |58.964MiB|58.964MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |1271.0MiB|1271.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1545.0MiB|1545.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |1584.0MiB|1584.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |34.796MiB|34.796MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |47.336MiB|47.336MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |828.0MiB|828.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |2040.0MiB|2040.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |49.184MiB|49.184MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |399.0MiB|399.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |53.952MiB|53.952MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |476.0MiB|476.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |29.836MiB|29.836MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1239.0MiB|1239.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |2544.0MiB|2544.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |330.0MiB|330.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1684.0MiB|1684.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |46.8MiB|46.8MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |59.028MiB|59.028MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |1006.0MiB|1006.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |58.964MiB|58.964MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |1271.0MiB|1271.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1545.0MiB|1545.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |1584.0MiB|1584.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |34.796MiB|34.796MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |47.336MiB|47.336MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |828.0MiB|828.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |2040.0MiB|2040.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |49.184MiB|49.184MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |399.0MiB|399.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |53.952MiB|53.952MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |476.0MiB|476.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |29.836MiB|29.836MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1239.0MiB|1239.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |2544.0MiB|2544.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |330.0MiB|330.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1684.0MiB|1684.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |46.8MiB|46.8MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |59.028MiB|59.028MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |1006.0MiB|1006.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |58.964MiB|58.964MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |1271.0MiB|1271.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1545.0MiB|1545.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |1584.0MiB|1584.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |34.796MiB|34.796MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |47.336MiB|47.336MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |828.0MiB|828.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |2040.0MiB|2040.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |49.184MiB|49.184MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |399.0MiB|399.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |53.952MiB|53.952MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |476.0MiB|476.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |29.836MiB|29.836MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1239.0MiB|1239.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |2544.0MiB|2544.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |330.0MiB|330.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1684.0MiB|1684.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |46.8MiB|46.8MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |59.028MiB|59.028MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |1006.0MiB|1006.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |58.964MiB|58.964MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |1271.0MiB|1271.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1545.0MiB|1545.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |1584.0MiB|1584.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |34.796MiB|34.796MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |47.336MiB|47.336MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |828.0MiB|828.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |2040.0MiB|2040.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |49.184MiB|49.184MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |399.0MiB|399.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |53.952MiB|53.952MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |476.0MiB|476.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |29.836MiB|29.836MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1239.0MiB|1239.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |2544.0MiB|2544.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |330.0MiB|330.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1684.0MiB|1684.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |46.8MiB|46.8MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |59.028MiB|59.028MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |1006.0MiB|1006.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1200.276s |2544.0MiB|
|scrambled111949.smt2                                                                       |1200.217s |2040.0MiB|
|scrambled25695.smt2                                                                        |1200.185s |1684.0MiB|
|scrambled102680.smt2                                                                       | 620.569s |1584.0MiB|
|scrambled102621.smt2                                                                       |1200.159s |1545.0MiB|
|scrambled98986.smt2                                                                        |1200.173s |1357.0MiB|
|scrambled55850.smt2                                                                        |1200.153s |1334.0MiB|
|scrambled101728.smt2                                                                       |1200.149s |1271.0MiB|
|scrambled8163.smt2                                                                         |1200.148s |1252.0MiB|
|scrambled13169.smt2                                                                        |1200.155s |1239.0MiB|
|scrambled44527.smt2                                                                        |1200.150s |1130.0MiB|
|scrambled37260.smt2                                                                        |1200.122s |1006.0MiB|
|scrambled77008.smt2                                                                        |1200.132s |982.0MiB|
|scrambled109307.smt2                                                                       |1043.753s |828.0MiB|
|scrambled95284.smt2                                                                        |1200.077s |539.0MiB|
|scrambled124455.smt2                                                                       |1200.079s |476.0MiB|
|scrambled117897.smt2                                                                       |1200.053s |399.0MiB|
|scrambled17583.smt2                                                                        |1200.051s |330.0MiB|
|scrambled47581.smt2                                                                        |1200.064s |319.0MiB|
|scrambled76525.smt2                                                                        |1200.046s |298.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1200.276s |2544.0MiB|
|scrambled111949.smt2                                                                       |1200.217s |2040.0MiB|
|scrambled25695.smt2                                                                        |1200.185s |1684.0MiB|
|scrambled102680.smt2                                                                       | 620.569s |1584.0MiB|
|scrambled102621.smt2                                                                       |1200.159s |1545.0MiB|
|scrambled98986.smt2                                                                        |1200.173s |1357.0MiB|
|scrambled55850.smt2                                                                        |1200.153s |1334.0MiB|
|scrambled101728.smt2                                                                       |1200.149s |1271.0MiB|
|scrambled8163.smt2                                                                         |1200.148s |1252.0MiB|
|scrambled13169.smt2                                                                        |1200.155s |1239.0MiB|
|scrambled44527.smt2                                                                        |1200.150s |1130.0MiB|
|scrambled37260.smt2                                                                        |1200.122s |1006.0MiB|
|scrambled77008.smt2                                                                        |1200.132s |982.0MiB|
|scrambled109307.smt2                                                                       |1043.753s |828.0MiB|
|scrambled95284.smt2                                                                        |1200.077s |539.0MiB|
|scrambled124455.smt2                                                                       |1200.079s |476.0MiB|
|scrambled117897.smt2                                                                       |1200.053s |399.0MiB|
|scrambled17583.smt2                                                                        |1200.051s |330.0MiB|
|scrambled47581.smt2                                                                        |1200.064s |319.0MiB|
|scrambled76525.smt2                                                                        |1200.046s |298.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.149s  |1200.149s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 620.569s  | 620.569s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1043.753s  |1043.753s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.217s  |1200.217s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 791.861s  | 791.861s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.185s  |1200.185s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.029s  |1200.029s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled44527.smt2                                                                         |1200.150s  |1200.150s  |   0.000s  | 0.0%|
|scrambled46192.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled47581.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled49820.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled55845.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled55850.smt2                                                                         |1200.153s  |1200.153s  |   0.000s  | 0.0%|
|scrambled59368.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled65517.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled71015.smt2                                                                         |1200.023s  |1200.023s  |   0.000s  | 0.0%|
|scrambled76525.smt2                                                                         |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled76532.smt2                                                                         |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled77008.smt2                                                                         |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled77308.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled8163.smt2                                                                          |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled88927.smt2                                                                         |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled92964.smt2                                                                         |1200.026s  |1200.026s  |   0.000s  | 0.0%|
|scrambled95284.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
</details>
