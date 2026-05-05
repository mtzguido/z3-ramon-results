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
Job tag: Z3-threads-8-smtcomp2025-QF_LRA-timeout20min-bb2-no_default_tactic-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=true smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LRA-timeout20min-bb2-no_default_tactic-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=true smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.112s  |1201.112s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.310s  |1201.310s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 795.836s  | 795.836s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.990s  |1200.990s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.579s  |1201.579s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.761s  |1200.761s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 441.330s  | 441.330s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.443s  |1200.443s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.142s  |1201.142s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.460s  |1202.460s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.463s  |1200.463s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.848s  |1201.848s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.685s  |1200.685s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.112s  |1201.112s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.310s  |1201.310s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 795.836s  | 795.836s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.990s  |1200.990s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.579s  |1201.579s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.761s  |1200.761s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 441.330s  | 441.330s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.443s  |1200.443s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.142s  |1201.142s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.460s  |1202.460s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.463s  |1200.463s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.848s  |1201.848s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.685s  |1200.685s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.112s  |1201.112s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.310s  |1201.310s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 795.836s  | 795.836s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.990s  |1200.990s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.579s  |1201.579s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.761s  |1200.761s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 441.330s  | 441.330s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.443s  |1200.443s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.142s  |1201.142s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.460s  |1202.460s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.463s  |1200.463s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.848s  |1201.848s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.685s  |1200.685s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.112s  |1201.112s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.310s  |1201.310s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 795.836s  | 795.836s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.990s  |1200.990s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.579s  |1201.579s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.761s  |1200.761s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 441.330s  | 441.330s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.443s  |1200.443s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.142s  |1201.142s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.460s  |1202.460s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.463s  |1200.463s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.848s  |1201.848s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.685s  |1200.685s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1202.460s |21.463GiB|
|scrambled25695.smt2                                                                        |1201.848s |13.282GiB|
|scrambled111949.smt2                                                                       |1201.579s |15.821GiB|
|scrambled98986.smt2                                                                        |1201.383s |12.488GiB|
|scrambled102621.smt2                                                                       |1201.310s |12.884GiB|
|scrambled55850.smt2                                                                        |1201.251s |12.277GiB|
|scrambled13169.smt2                                                                        |1201.142s |10.667GiB|
|scrambled101728.smt2                                                                       |1201.112s |10.615GiB|
|scrambled8163.smt2                                                                         |1201.020s |10.965GiB|
|scrambled109307.smt2                                                                       |1200.990s |8324.0MiB|
|scrambled77008.smt2                                                                        |1200.914s |7636.0MiB|
|scrambled117897.smt2                                                                       |1200.761s |5729.0MiB|
|scrambled37260.smt2                                                                        |1200.685s |5018.0MiB|
|scrambled47581.smt2                                                                        |1200.541s |3327.0MiB|
|scrambled95284.smt2                                                                        |1200.522s |4782.0MiB|
|scrambled17583.smt2                                                                        |1200.463s |3407.0MiB|
|scrambled124455.smt2                                                                       |1200.443s |3731.0MiB|
|scrambled76525.smt2                                                                        |1200.396s |2955.0MiB|
|scrambled59368.smt2                                                                        |1200.377s |2896.0MiB|
|scrambled55845.smt2                                                                        |1200.264s |1565.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1202.460s |21.463GiB|
|scrambled25695.smt2                                                                        |1201.848s |13.282GiB|
|scrambled111949.smt2                                                                       |1201.579s |15.821GiB|
|scrambled98986.smt2                                                                        |1201.383s |12.488GiB|
|scrambled102621.smt2                                                                       |1201.310s |12.884GiB|
|scrambled55850.smt2                                                                        |1201.251s |12.277GiB|
|scrambled13169.smt2                                                                        |1201.142s |10.667GiB|
|scrambled101728.smt2                                                                       |1201.112s |10.615GiB|
|scrambled8163.smt2                                                                         |1201.020s |10.965GiB|
|scrambled109307.smt2                                                                       |1200.990s |8324.0MiB|
|scrambled77008.smt2                                                                        |1200.914s |7636.0MiB|
|scrambled117897.smt2                                                                       |1200.761s |5729.0MiB|
|scrambled37260.smt2                                                                        |1200.685s |5018.0MiB|
|scrambled47581.smt2                                                                        |1200.541s |3327.0MiB|
|scrambled95284.smt2                                                                        |1200.522s |4782.0MiB|
|scrambled17583.smt2                                                                        |1200.463s |3407.0MiB|
|scrambled124455.smt2                                                                       |1200.443s |3731.0MiB|
|scrambled76525.smt2                                                                        |1200.396s |2955.0MiB|
|scrambled59368.smt2                                                                        |1200.377s |2896.0MiB|
|scrambled55845.smt2                                                                        |1200.264s |1565.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |563.0MiB|563.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |10.615GiB|10.615GiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |12.884GiB|12.884GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |12.397GiB|12.397GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |312.0MiB|312.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |409.0MiB|409.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |8324.0MiB|8324.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |15.821GiB|15.821GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |5729.0MiB|5729.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |527.0MiB|527.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |3731.0MiB|3731.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |299.0MiB|299.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |10.667GiB|10.667GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |21.463GiB|21.463GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |3407.0MiB|3407.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |13.282GiB|13.282GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |454.0MiB|454.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |583.0MiB|583.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |5018.0MiB|5018.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |563.0MiB|563.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |10.615GiB|10.615GiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |12.884GiB|12.884GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |12.397GiB|12.397GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |312.0MiB|312.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |409.0MiB|409.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |8324.0MiB|8324.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |15.821GiB|15.821GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |5729.0MiB|5729.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |527.0MiB|527.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |3731.0MiB|3731.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |299.0MiB|299.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |10.667GiB|10.667GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |21.463GiB|21.463GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |3407.0MiB|3407.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |13.282GiB|13.282GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |454.0MiB|454.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |583.0MiB|583.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |5018.0MiB|5018.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |563.0MiB|563.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |10.615GiB|10.615GiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |12.884GiB|12.884GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |12.397GiB|12.397GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |312.0MiB|312.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |409.0MiB|409.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |8324.0MiB|8324.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |15.821GiB|15.821GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |5729.0MiB|5729.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |527.0MiB|527.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |3731.0MiB|3731.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |299.0MiB|299.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |10.667GiB|10.667GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |21.463GiB|21.463GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |3407.0MiB|3407.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |13.282GiB|13.282GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |454.0MiB|454.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |583.0MiB|583.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |5018.0MiB|5018.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |563.0MiB|563.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |10.615GiB|10.615GiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |12.884GiB|12.884GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |12.397GiB|12.397GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |312.0MiB|312.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |409.0MiB|409.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |8324.0MiB|8324.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |15.821GiB|15.821GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |5729.0MiB|5729.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |527.0MiB|527.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |3731.0MiB|3731.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |299.0MiB|299.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |10.667GiB|10.667GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |21.463GiB|21.463GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |3407.0MiB|3407.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |13.282GiB|13.282GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |454.0MiB|454.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |583.0MiB|583.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |5018.0MiB|5018.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1202.460s |21.463GiB|
|scrambled111949.smt2                                                                       |1201.579s |15.821GiB|
|scrambled25695.smt2                                                                        |1201.848s |13.282GiB|
|scrambled102621.smt2                                                                       |1201.310s |12.884GiB|
|scrambled98986.smt2                                                                        |1201.383s |12.488GiB|
|scrambled102680.smt2                                                                       | 795.836s |12.397GiB|
|scrambled55850.smt2                                                                        |1201.251s |12.277GiB|
|scrambled8163.smt2                                                                         |1201.020s |10.965GiB|
|scrambled44527.smt2                                                                        | 388.855s |10.907GiB|
|scrambled13169.smt2                                                                        |1201.142s |10.667GiB|
|scrambled101728.smt2                                                                       |1201.112s |10.615GiB|
|scrambled109307.smt2                                                                       |1200.990s |8324.0MiB|
|scrambled77008.smt2                                                                        |1200.914s |7636.0MiB|
|scrambled117897.smt2                                                                       |1200.761s |5729.0MiB|
|scrambled37260.smt2                                                                        |1200.685s |5018.0MiB|
|scrambled95284.smt2                                                                        |1200.522s |4782.0MiB|
|scrambled124455.smt2                                                                       |1200.443s |3731.0MiB|
|scrambled17583.smt2                                                                        |1200.463s |3407.0MiB|
|scrambled47581.smt2                                                                        |1200.541s |3327.0MiB|
|scrambled76525.smt2                                                                        |1200.396s |2955.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1202.460s |21.463GiB|
|scrambled111949.smt2                                                                       |1201.579s |15.821GiB|
|scrambled25695.smt2                                                                        |1201.848s |13.282GiB|
|scrambled102621.smt2                                                                       |1201.310s |12.884GiB|
|scrambled98986.smt2                                                                        |1201.383s |12.488GiB|
|scrambled102680.smt2                                                                       | 795.836s |12.397GiB|
|scrambled55850.smt2                                                                        |1201.251s |12.277GiB|
|scrambled8163.smt2                                                                         |1201.020s |10.965GiB|
|scrambled44527.smt2                                                                        | 388.855s |10.907GiB|
|scrambled13169.smt2                                                                        |1201.142s |10.667GiB|
|scrambled101728.smt2                                                                       |1201.112s |10.615GiB|
|scrambled109307.smt2                                                                       |1200.990s |8324.0MiB|
|scrambled77008.smt2                                                                        |1200.914s |7636.0MiB|
|scrambled117897.smt2                                                                       |1200.761s |5729.0MiB|
|scrambled37260.smt2                                                                        |1200.685s |5018.0MiB|
|scrambled95284.smt2                                                                        |1200.522s |4782.0MiB|
|scrambled124455.smt2                                                                       |1200.443s |3731.0MiB|
|scrambled17583.smt2                                                                        |1200.463s |3407.0MiB|
|scrambled47581.smt2                                                                        |1200.541s |3327.0MiB|
|scrambled76525.smt2                                                                        |1200.396s |2955.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.112s  |1201.112s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.310s  |1201.310s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 795.836s  | 795.836s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.990s  |1200.990s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.579s  |1201.579s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.761s  |1200.761s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 441.330s  | 441.330s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.443s  |1200.443s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.142s  |1201.142s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.460s  |1202.460s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.463s  |1200.463s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.848s  |1201.848s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.685s  |1200.685s  |   0.000s  | 0.0%|
|scrambled44527.smt2                                                                         | 388.855s  | 388.855s  |   0.000s  | 0.0%|
|scrambled46192.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled47581.smt2                                                                         |1200.541s  |1200.541s  |   0.000s  | 0.0%|
|scrambled49820.smt2                                                                         |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled55845.smt2                                                                         |1200.264s  |1200.264s  |   0.000s  | 0.0%|
|scrambled55850.smt2                                                                         |1201.251s  |1201.251s  |   0.000s  | 0.0%|
|scrambled59368.smt2                                                                         |1200.377s  |1200.377s  |   0.000s  | 0.0%|
|scrambled65517.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled71015.smt2                                                                         |1200.190s  |1200.190s  |   0.000s  | 0.0%|
|scrambled76525.smt2                                                                         |1200.396s  |1200.396s  |   0.000s  | 0.0%|
|scrambled76532.smt2                                                                         |1200.166s  |1200.166s  |   0.000s  | 0.0%|
|scrambled77008.smt2                                                                         |1200.914s  |1200.914s  |   0.000s  | 0.0%|
|scrambled77308.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled8163.smt2                                                                          |1201.020s  |1201.020s  |   0.000s  | 0.0%|
|scrambled88927.smt2                                                                         | 602.302s  | 602.302s  |   0.000s  | 0.0%|
|scrambled92964.smt2                                                                         |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled95284.smt2                                                                         |1200.522s  |1200.522s  |   0.000s  | 0.0%|
</details>
