Comparing data and data


# SUMMARY
- LHS tests = 45
- RHS tests = 45
- LHS success = 45  (100.0%)
- RHS success = 45  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_IDL-timeout20min-bb1
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: c383004968f5bf66a9668a7ae254c83d45ac3afe
Z3 branch: fmcad26_artifact
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=true smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=1"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_IDL
Z3 commit message: add ablate_backtracking experiment

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_IDL-timeout20min-bb1
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: c383004968f5bf66a9668a7ae254c83d45ac3afe
Z3 branch: fmcad26_artifact
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=true smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=1"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_IDL
Z3 commit message: add ablate_backtracking experiment

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1156.850s  |1156.850s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.365s  |1200.365s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.209s  |1200.209s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 381.623s  | 381.623s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.418s  |1200.418s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 441.217s  | 441.217s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.192s  |1200.192s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.176s  |1201.176s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.645s  |1200.645s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1156.850s  |1156.850s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.365s  |1200.365s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.209s  |1200.209s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 381.623s  | 381.623s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.418s  |1200.418s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 441.217s  | 441.217s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.192s  |1200.192s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.176s  |1201.176s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.645s  |1200.645s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1156.850s  |1156.850s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.365s  |1200.365s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.209s  |1200.209s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 381.623s  | 381.623s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.418s  |1200.418s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 441.217s  | 441.217s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.192s  |1200.192s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.176s  |1201.176s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.645s  |1200.645s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1156.850s  |1156.850s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.365s  |1200.365s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.209s  |1200.209s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 381.623s  | 381.623s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.418s  |1200.418s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 441.217s  | 441.217s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.192s  |1200.192s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.176s  |1201.176s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.645s  |1200.645s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.176s |12.74GiB|
|scrambled35345.smt2                                                                        |1200.645s |3400.0MiB|
|scrambled75206.smt2                                                                        |1200.477s |2411.0MiB|
|scrambled41773.smt2                                                                        |1200.452s |2062.0MiB|
|scrambled1379.smt2                                                                         |1200.418s |1839.0MiB|
|scrambled119992.smt2                                                                       |1200.365s |1870.0MiB|
|scrambled23483.smt2                                                                        |1200.276s |2111.0MiB|
|scrambled103851.smt2                                                                       |1200.214s |1192.0MiB|
|scrambled92133.smt2                                                                        |1200.212s |1680.0MiB|
|scrambled124624.smt2                                                                       |1200.209s |1296.0MiB|
|scrambled15552.smt2                                                                        |1200.192s |904.0MiB|
|scrambled62810.smt2                                                                        |1200.184s |1094.0MiB|
|scrambled62859.smt2                                                                        |1200.169s |1250.0MiB|
|scrambled38610.smt2                                                                        |1200.169s |1183.0MiB|
|scrambled109208.smt2                                                                       |1200.163s |1108.0MiB|
|scrambled82743.smt2                                                                        |1200.160s |861.0MiB|
|scrambled122058.smt2                                                                       |1200.157s |843.0MiB|
|scrambled97138.smt2                                                                        |1200.154s |1168.0MiB|
|scrambled42287.smt2                                                                        |1200.153s |1125.0MiB|
|scrambled41312.smt2                                                                        |1200.138s |454.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.176s |12.74GiB|
|scrambled35345.smt2                                                                        |1200.645s |3400.0MiB|
|scrambled75206.smt2                                                                        |1200.477s |2411.0MiB|
|scrambled41773.smt2                                                                        |1200.452s |2062.0MiB|
|scrambled1379.smt2                                                                         |1200.418s |1839.0MiB|
|scrambled119992.smt2                                                                       |1200.365s |1870.0MiB|
|scrambled23483.smt2                                                                        |1200.276s |2111.0MiB|
|scrambled103851.smt2                                                                       |1200.214s |1192.0MiB|
|scrambled92133.smt2                                                                        |1200.212s |1680.0MiB|
|scrambled124624.smt2                                                                       |1200.209s |1296.0MiB|
|scrambled15552.smt2                                                                        |1200.192s |904.0MiB|
|scrambled62810.smt2                                                                        |1200.184s |1094.0MiB|
|scrambled62859.smt2                                                                        |1200.169s |1250.0MiB|
|scrambled38610.smt2                                                                        |1200.169s |1183.0MiB|
|scrambled109208.smt2                                                                       |1200.163s |1108.0MiB|
|scrambled82743.smt2                                                                        |1200.160s |861.0MiB|
|scrambled122058.smt2                                                                       |1200.157s |843.0MiB|
|scrambled97138.smt2                                                                        |1200.154s |1168.0MiB|
|scrambled42287.smt2                                                                        |1200.153s |1125.0MiB|
|scrambled41312.smt2                                                                        |1200.138s |454.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |558.0MiB|558.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1192.0MiB|1192.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1108.0MiB|1108.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |3723.0MiB|3723.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |401.0MiB|401.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |1870.0MiB|1870.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |843.0MiB|843.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |476.0MiB|476.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1296.0MiB|1296.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |718.0MiB|718.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |1839.0MiB|1839.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |510.0MiB|510.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |529.0MiB|529.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1184.0MiB|1184.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |904.0MiB|904.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |543.0MiB|543.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |2111.0MiB|2111.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |12.74GiB|12.74GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |658.0MiB|658.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |3400.0MiB|3400.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |558.0MiB|558.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1192.0MiB|1192.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1108.0MiB|1108.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |3723.0MiB|3723.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |401.0MiB|401.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |1870.0MiB|1870.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |843.0MiB|843.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |476.0MiB|476.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1296.0MiB|1296.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |718.0MiB|718.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |1839.0MiB|1839.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |510.0MiB|510.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |529.0MiB|529.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1184.0MiB|1184.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |904.0MiB|904.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |543.0MiB|543.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |2111.0MiB|2111.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |12.74GiB|12.74GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |658.0MiB|658.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |3400.0MiB|3400.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |558.0MiB|558.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1192.0MiB|1192.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1108.0MiB|1108.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |3723.0MiB|3723.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |401.0MiB|401.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |1870.0MiB|1870.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |843.0MiB|843.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |476.0MiB|476.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1296.0MiB|1296.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |718.0MiB|718.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |1839.0MiB|1839.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |510.0MiB|510.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |529.0MiB|529.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1184.0MiB|1184.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |904.0MiB|904.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |543.0MiB|543.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |2111.0MiB|2111.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |12.74GiB|12.74GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |658.0MiB|658.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |3400.0MiB|3400.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |558.0MiB|558.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1192.0MiB|1192.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1108.0MiB|1108.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |3723.0MiB|3723.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |401.0MiB|401.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |1870.0MiB|1870.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |843.0MiB|843.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |476.0MiB|476.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1296.0MiB|1296.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |718.0MiB|718.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |1839.0MiB|1839.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |510.0MiB|510.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |529.0MiB|529.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1184.0MiB|1184.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |904.0MiB|904.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |543.0MiB|543.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |2111.0MiB|2111.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |12.74GiB|12.74GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |658.0MiB|658.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |3400.0MiB|3400.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.176s |12.74GiB|
|scrambled116992.smt2                                                                       |1156.850s |3723.0MiB|
|scrambled35345.smt2                                                                        |1200.645s |3400.0MiB|
|scrambled75206.smt2                                                                        |1200.477s |2411.0MiB|
|scrambled23483.smt2                                                                        |1200.276s |2111.0MiB|
|scrambled41773.smt2                                                                        |1200.452s |2062.0MiB|
|scrambled119992.smt2                                                                       |1200.365s |1870.0MiB|
|scrambled1379.smt2                                                                         |1200.418s |1839.0MiB|
|scrambled92133.smt2                                                                        |1200.212s |1680.0MiB|
|scrambled124624.smt2                                                                       |1200.209s |1296.0MiB|
|scrambled62859.smt2                                                                        |1200.169s |1250.0MiB|
|scrambled103851.smt2                                                                       |1200.214s |1192.0MiB|
|scrambled15284.smt2                                                                        | 441.217s |1184.0MiB|
|scrambled38610.smt2                                                                        |1200.169s |1183.0MiB|
|scrambled97138.smt2                                                                        |1200.154s |1168.0MiB|
|scrambled42287.smt2                                                                        |1200.153s |1125.0MiB|
|scrambled109208.smt2                                                                       |1200.163s |1108.0MiB|
|scrambled62810.smt2                                                                        |1200.184s |1094.0MiB|
|scrambled15552.smt2                                                                        |1200.192s |904.0MiB|
|scrambled82743.smt2                                                                        |1200.160s |861.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.176s |12.74GiB|
|scrambled116992.smt2                                                                       |1156.850s |3723.0MiB|
|scrambled35345.smt2                                                                        |1200.645s |3400.0MiB|
|scrambled75206.smt2                                                                        |1200.477s |2411.0MiB|
|scrambled23483.smt2                                                                        |1200.276s |2111.0MiB|
|scrambled41773.smt2                                                                        |1200.452s |2062.0MiB|
|scrambled119992.smt2                                                                       |1200.365s |1870.0MiB|
|scrambled1379.smt2                                                                         |1200.418s |1839.0MiB|
|scrambled92133.smt2                                                                        |1200.212s |1680.0MiB|
|scrambled124624.smt2                                                                       |1200.209s |1296.0MiB|
|scrambled62859.smt2                                                                        |1200.169s |1250.0MiB|
|scrambled103851.smt2                                                                       |1200.214s |1192.0MiB|
|scrambled15284.smt2                                                                        | 441.217s |1184.0MiB|
|scrambled38610.smt2                                                                        |1200.169s |1183.0MiB|
|scrambled97138.smt2                                                                        |1200.154s |1168.0MiB|
|scrambled42287.smt2                                                                        |1200.153s |1125.0MiB|
|scrambled109208.smt2                                                                       |1200.163s |1108.0MiB|
|scrambled62810.smt2                                                                        |1200.184s |1094.0MiB|
|scrambled15552.smt2                                                                        |1200.192s |904.0MiB|
|scrambled82743.smt2                                                                        |1200.160s |861.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1156.850s  |1156.850s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.365s  |1200.365s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.209s  |1200.209s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 381.623s  | 381.623s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.418s  |1200.418s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 441.217s  | 441.217s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.192s  |1200.192s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.176s  |1201.176s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.645s  |1200.645s  |   0.000s  | 0.0%|
|scrambled38610.smt2                                                                         |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled41312.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled41773.smt2                                                                         |1200.452s  |1200.452s  |   0.000s  | 0.0%|
|scrambled41801.smt2                                                                         |1200.130s  |1200.130s  |   0.000s  | 0.0%|
|scrambled42287.smt2                                                                         |1200.153s  |1200.153s  |   0.000s  | 0.0%|
|scrambled4441.smt2                                                                          | 866.726s  | 866.726s  |   0.000s  | 0.0%|
|scrambled54073.smt2                                                                         | 255.767s  | 255.767s  |   0.000s  | 0.0%|
|scrambled58720.smt2                                                                         |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled62536.smt2                                                                         | 382.201s  | 382.201s  |   0.000s  | 0.0%|
|scrambled62810.smt2                                                                         |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled62859.smt2                                                                         |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled6373.smt2                                                                          |1060.641s  |1060.641s  |   0.000s  | 0.0%|
|scrambled75206.smt2                                                                         |1200.477s  |1200.477s  |   0.000s  | 0.0%|
|scrambled78432.smt2                                                                         | 228.687s  | 228.687s  |   0.000s  | 0.0%|
|scrambled78606.smt2                                                                         | 214.050s  | 214.050s  |   0.000s  | 0.0%|
|scrambled79181.smt2                                                                         | 414.903s  | 414.903s  |   0.000s  | 0.0%|
|scrambled82743.smt2                                                                         |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled89071.smt2                                                                         | 199.953s  | 199.953s  |   0.000s  | 0.0%|
|scrambled90733.smt2                                                                         | 852.907s  | 852.907s  |   0.000s  | 0.0%|
|scrambled92133.smt2                                                                         |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled96514.smt2                                                                         | 126.512s  | 126.512s  |   0.000s  | 0.0%|
|scrambled96733.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled97138.smt2                                                                         |1200.154s  |1200.154s  |   0.000s  | 0.0%|
|scrambled98799.smt2                                                                         | 496.414s  | 496.414s  |   0.000s  | 0.0%|
</details>
