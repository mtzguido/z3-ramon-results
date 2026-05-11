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
Job tag: Z3-threads-8-smtcomp2025-QF_LRA-timeout20min-bb1
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: c383004968f5bf66a9668a7ae254c83d45ac3afe
Z3 branch: fmcad26_artifact
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=1"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: add ablate_backtracking experiment

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LRA-timeout20min-bb1
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: c383004968f5bf66a9668a7ae254c83d45ac3afe
Z3 branch: fmcad26_artifact
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=1"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: add ablate_backtracking experiment

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.911s  |1200.911s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.283s  |1201.283s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1201.379s  |1201.379s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.654s  |1200.654s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.471s  |1201.471s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.688s  |1200.688s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 219.180s  | 219.180s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.474s  |1200.474s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.090s  |1201.090s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.037s  |1202.037s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.350s  |1200.350s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.981s  |1200.981s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.102s  |1200.102s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.931s  |1200.931s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.911s  |1200.911s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.283s  |1201.283s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1201.379s  |1201.379s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.654s  |1200.654s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.471s  |1201.471s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.688s  |1200.688s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 219.180s  | 219.180s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.474s  |1200.474s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.090s  |1201.090s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.037s  |1202.037s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.350s  |1200.350s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.981s  |1200.981s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.102s  |1200.102s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.931s  |1200.931s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.911s  |1200.911s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.283s  |1201.283s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1201.379s  |1201.379s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.654s  |1200.654s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.471s  |1201.471s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.688s  |1200.688s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 219.180s  | 219.180s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.474s  |1200.474s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.090s  |1201.090s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.037s  |1202.037s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.350s  |1200.350s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.981s  |1200.981s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.102s  |1200.102s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.931s  |1200.931s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.911s  |1200.911s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.283s  |1201.283s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1201.379s  |1201.379s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.654s  |1200.654s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.471s  |1201.471s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.688s  |1200.688s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 219.180s  | 219.180s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.474s  |1200.474s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.090s  |1201.090s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.037s  |1202.037s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.350s  |1200.350s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.981s  |1200.981s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.102s  |1200.102s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.931s  |1200.931s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1202.037s |19.382GiB|
|scrambled111949.smt2                                                                       |1201.471s |14.741GiB|
|scrambled55850.smt2                                                                        |1201.392s |9761.0MiB|
|scrambled102680.smt2                                                                       |1201.379s |12.092GiB|
|scrambled102621.smt2                                                                       |1201.283s |10.912GiB|
|scrambled13169.smt2                                                                        |1201.090s |10.94GiB|
|scrambled44527.smt2                                                                        |1201.078s |11.465GiB|
|scrambled8163.smt2                                                                         |1201.046s |11.049GiB|
|scrambled25695.smt2                                                                        |1200.981s |10.078GiB|
|scrambled37260.smt2                                                                        |1200.931s |5777.0MiB|
|scrambled101728.smt2                                                                       |1200.911s |8729.0MiB|
|scrambled98986.smt2                                                                        |1200.882s |9683.0MiB|
|scrambled117897.smt2                                                                       |1200.688s |6017.0MiB|
|scrambled77008.smt2                                                                        |1200.667s |5703.0MiB|
|scrambled109307.smt2                                                                       |1200.654s |5551.0MiB|
|scrambled47581.smt2                                                                        |1200.501s |2900.0MiB|
|scrambled124455.smt2                                                                       |1200.474s |3724.0MiB|
|scrambled76525.smt2                                                                        |1200.442s |2807.0MiB|
|scrambled95284.smt2                                                                        |1200.401s |3430.0MiB|
|scrambled59368.smt2                                                                        |1200.353s |2603.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1202.037s |19.382GiB|
|scrambled111949.smt2                                                                       |1201.471s |14.741GiB|
|scrambled55850.smt2                                                                        |1201.392s |9761.0MiB|
|scrambled102680.smt2                                                                       |1201.379s |12.092GiB|
|scrambled102621.smt2                                                                       |1201.283s |10.912GiB|
|scrambled13169.smt2                                                                        |1201.090s |10.94GiB|
|scrambled44527.smt2                                                                        |1201.078s |11.465GiB|
|scrambled8163.smt2                                                                         |1201.046s |11.049GiB|
|scrambled25695.smt2                                                                        |1200.981s |10.078GiB|
|scrambled37260.smt2                                                                        |1200.931s |5777.0MiB|
|scrambled101728.smt2                                                                       |1200.911s |8729.0MiB|
|scrambled98986.smt2                                                                        |1200.882s |9683.0MiB|
|scrambled117897.smt2                                                                       |1200.688s |6017.0MiB|
|scrambled77008.smt2                                                                        |1200.667s |5703.0MiB|
|scrambled109307.smt2                                                                       |1200.654s |5551.0MiB|
|scrambled47581.smt2                                                                        |1200.501s |2900.0MiB|
|scrambled124455.smt2                                                                       |1200.474s |3724.0MiB|
|scrambled76525.smt2                                                                        |1200.442s |2807.0MiB|
|scrambled95284.smt2                                                                        |1200.401s |3430.0MiB|
|scrambled59368.smt2                                                                        |1200.353s |2603.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |503.0MiB|503.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |8729.0MiB|8729.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |10.912GiB|10.912GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |12.092GiB|12.092GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |268.0MiB|268.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |344.0MiB|344.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |5551.0MiB|5551.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |14.741GiB|14.741GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |530.0MiB|530.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |6017.0MiB|6017.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |481.0MiB|481.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |3724.0MiB|3724.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |275.0MiB|275.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |10.94GiB|10.94GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |19.382GiB|19.382GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2757.0MiB|2757.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |10.078GiB|10.078GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |440.0MiB|440.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |5777.0MiB|5777.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |503.0MiB|503.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |8729.0MiB|8729.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |10.912GiB|10.912GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |12.092GiB|12.092GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |268.0MiB|268.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |344.0MiB|344.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |5551.0MiB|5551.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |14.741GiB|14.741GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |530.0MiB|530.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |6017.0MiB|6017.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |481.0MiB|481.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |3724.0MiB|3724.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |275.0MiB|275.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |10.94GiB|10.94GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |19.382GiB|19.382GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2757.0MiB|2757.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |10.078GiB|10.078GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |440.0MiB|440.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |5777.0MiB|5777.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |503.0MiB|503.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |8729.0MiB|8729.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |10.912GiB|10.912GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |12.092GiB|12.092GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |268.0MiB|268.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |344.0MiB|344.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |5551.0MiB|5551.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |14.741GiB|14.741GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |530.0MiB|530.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |6017.0MiB|6017.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |481.0MiB|481.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |3724.0MiB|3724.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |275.0MiB|275.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |10.94GiB|10.94GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |19.382GiB|19.382GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2757.0MiB|2757.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |10.078GiB|10.078GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |440.0MiB|440.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |5777.0MiB|5777.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |503.0MiB|503.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |8729.0MiB|8729.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |10.912GiB|10.912GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |12.092GiB|12.092GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |268.0MiB|268.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |344.0MiB|344.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |5551.0MiB|5551.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |14.741GiB|14.741GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |530.0MiB|530.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |6017.0MiB|6017.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |481.0MiB|481.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |3724.0MiB|3724.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |275.0MiB|275.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |10.94GiB|10.94GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |19.382GiB|19.382GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2757.0MiB|2757.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |10.078GiB|10.078GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |440.0MiB|440.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |5777.0MiB|5777.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1202.037s |19.382GiB|
|scrambled111949.smt2                                                                       |1201.471s |14.741GiB|
|scrambled102680.smt2                                                                       |1201.379s |12.092GiB|
|scrambled44527.smt2                                                                        |1201.078s |11.465GiB|
|scrambled8163.smt2                                                                         |1201.046s |11.049GiB|
|scrambled13169.smt2                                                                        |1201.090s |10.94GiB|
|scrambled102621.smt2                                                                       |1201.283s |10.912GiB|
|scrambled25695.smt2                                                                        |1200.981s |10.078GiB|
|scrambled55850.smt2                                                                        |1201.392s |9761.0MiB|
|scrambled98986.smt2                                                                        |1200.882s |9683.0MiB|
|scrambled101728.smt2                                                                       |1200.911s |8729.0MiB|
|scrambled117897.smt2                                                                       |1200.688s |6017.0MiB|
|scrambled37260.smt2                                                                        |1200.931s |5777.0MiB|
|scrambled77008.smt2                                                                        |1200.667s |5703.0MiB|
|scrambled109307.smt2                                                                       |1200.654s |5551.0MiB|
|scrambled124455.smt2                                                                       |1200.474s |3724.0MiB|
|scrambled95284.smt2                                                                        |1200.401s |3430.0MiB|
|scrambled47581.smt2                                                                        |1200.501s |2900.0MiB|
|scrambled76525.smt2                                                                        |1200.442s |2807.0MiB|
|scrambled17583.smt2                                                                        |1200.350s |2757.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1202.037s |19.382GiB|
|scrambled111949.smt2                                                                       |1201.471s |14.741GiB|
|scrambled102680.smt2                                                                       |1201.379s |12.092GiB|
|scrambled44527.smt2                                                                        |1201.078s |11.465GiB|
|scrambled8163.smt2                                                                         |1201.046s |11.049GiB|
|scrambled13169.smt2                                                                        |1201.090s |10.94GiB|
|scrambled102621.smt2                                                                       |1201.283s |10.912GiB|
|scrambled25695.smt2                                                                        |1200.981s |10.078GiB|
|scrambled55850.smt2                                                                        |1201.392s |9761.0MiB|
|scrambled98986.smt2                                                                        |1200.882s |9683.0MiB|
|scrambled101728.smt2                                                                       |1200.911s |8729.0MiB|
|scrambled117897.smt2                                                                       |1200.688s |6017.0MiB|
|scrambled37260.smt2                                                                        |1200.931s |5777.0MiB|
|scrambled77008.smt2                                                                        |1200.667s |5703.0MiB|
|scrambled109307.smt2                                                                       |1200.654s |5551.0MiB|
|scrambled124455.smt2                                                                       |1200.474s |3724.0MiB|
|scrambled95284.smt2                                                                        |1200.401s |3430.0MiB|
|scrambled47581.smt2                                                                        |1200.501s |2900.0MiB|
|scrambled76525.smt2                                                                        |1200.442s |2807.0MiB|
|scrambled17583.smt2                                                                        |1200.350s |2757.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.911s  |1200.911s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.283s  |1201.283s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1201.379s  |1201.379s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.654s  |1200.654s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.471s  |1201.471s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.688s  |1200.688s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 219.180s  | 219.180s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.474s  |1200.474s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.090s  |1201.090s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.037s  |1202.037s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.350s  |1200.350s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.981s  |1200.981s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.102s  |1200.102s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.931s  |1200.931s  |   0.000s  | 0.0%|
|scrambled44527.smt2                                                                         |1201.078s  |1201.078s  |   0.000s  | 0.0%|
|scrambled46192.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled47581.smt2                                                                         |1200.501s  |1200.501s  |   0.000s  | 0.0%|
|scrambled49820.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled55845.smt2                                                                         |1200.248s  |1200.248s  |   0.000s  | 0.0%|
|scrambled55850.smt2                                                                         |1201.392s  |1201.392s  |   0.000s  | 0.0%|
|scrambled59368.smt2                                                                         |1200.353s  |1200.353s  |   0.000s  | 0.0%|
|scrambled65517.smt2                                                                         |1200.084s  |1200.084s  |   0.000s  | 0.0%|
|scrambled71015.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled76525.smt2                                                                         |1200.442s  |1200.442s  |   0.000s  | 0.0%|
|scrambled76532.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled77008.smt2                                                                         |1200.667s  |1200.667s  |   0.000s  | 0.0%|
|scrambled77308.smt2                                                                         |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled8163.smt2                                                                          |1201.046s  |1201.046s  |   0.000s  | 0.0%|
|scrambled88927.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled92964.smt2                                                                         |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled95284.smt2                                                                         |1200.401s  |1200.401s  |   0.000s  | 0.0%|
</details>
