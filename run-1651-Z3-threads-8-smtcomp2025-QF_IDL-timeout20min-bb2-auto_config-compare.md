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
Job tag: Z3-threads-8-smtcomp2025-QF_IDL-timeout20min-bb2-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=true smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_IDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_IDL-timeout20min-bb2-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=true smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_IDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.124s  |1200.124s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.539s  |1200.539s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.331s  |1200.331s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.233s  |1200.233s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 588.110s  | 588.110s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.346s  |1200.346s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1129.195s  |1129.195s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.413s  |1200.413s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.205s  |1201.205s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.672s  |1200.672s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.124s  |1200.124s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.539s  |1200.539s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.331s  |1200.331s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.233s  |1200.233s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 588.110s  | 588.110s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.346s  |1200.346s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1129.195s  |1129.195s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.413s  |1200.413s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.205s  |1201.205s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.672s  |1200.672s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.124s  |1200.124s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.539s  |1200.539s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.331s  |1200.331s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.233s  |1200.233s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 588.110s  | 588.110s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.346s  |1200.346s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1129.195s  |1129.195s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.413s  |1200.413s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.205s  |1201.205s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.672s  |1200.672s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.124s  |1200.124s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.539s  |1200.539s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.331s  |1200.331s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.233s  |1200.233s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 588.110s  | 588.110s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.346s  |1200.346s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1129.195s  |1129.195s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.413s  |1200.413s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.205s  |1201.205s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.672s  |1200.672s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.205s |13.766GiB|
|scrambled35345.smt2                                                                        |1200.672s |3779.0MiB|
|scrambled116992.smt2                                                                       |1200.539s |3928.0MiB|
|scrambled23483.smt2                                                                        |1200.413s |2288.0MiB|
|scrambled1379.smt2                                                                         |1200.346s |2023.0MiB|
|scrambled119992.smt2                                                                       |1200.331s |2005.0MiB|
|scrambled41773.smt2                                                                        |1200.308s |2382.0MiB|
|scrambled124624.smt2                                                                       |1200.233s |1366.0MiB|
|scrambled62810.smt2                                                                        |1200.216s |1190.0MiB|
|scrambled92133.smt2                                                                        |1200.213s |1807.0MiB|
|scrambled97138.smt2                                                                        |1200.184s |1233.0MiB|
|scrambled62859.smt2                                                                        |1200.172s |1345.0MiB|
|scrambled122058.smt2                                                                       |1200.171s |827.0MiB|
|scrambled27577.smt2                                                                        |1200.164s |697.0MiB|
|scrambled103851.smt2                                                                       |1200.163s |1292.0MiB|
|scrambled42287.smt2                                                                        |1200.159s |1228.0MiB|
|scrambled109208.smt2                                                                       |1200.157s |1079.0MiB|
|scrambled38610.smt2                                                                        |1200.152s |1244.0MiB|
|scrambled15552.smt2                                                                        |1200.148s |980.0MiB|
|scrambled100416.smt2                                                                       |1200.124s |612.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.205s |13.766GiB|
|scrambled35345.smt2                                                                        |1200.672s |3779.0MiB|
|scrambled116992.smt2                                                                       |1200.539s |3928.0MiB|
|scrambled23483.smt2                                                                        |1200.413s |2288.0MiB|
|scrambled1379.smt2                                                                         |1200.346s |2023.0MiB|
|scrambled119992.smt2                                                                       |1200.331s |2005.0MiB|
|scrambled41773.smt2                                                                        |1200.308s |2382.0MiB|
|scrambled124624.smt2                                                                       |1200.233s |1366.0MiB|
|scrambled62810.smt2                                                                        |1200.216s |1190.0MiB|
|scrambled92133.smt2                                                                        |1200.213s |1807.0MiB|
|scrambled97138.smt2                                                                        |1200.184s |1233.0MiB|
|scrambled62859.smt2                                                                        |1200.172s |1345.0MiB|
|scrambled122058.smt2                                                                       |1200.171s |827.0MiB|
|scrambled27577.smt2                                                                        |1200.164s |697.0MiB|
|scrambled103851.smt2                                                                       |1200.163s |1292.0MiB|
|scrambled42287.smt2                                                                        |1200.159s |1228.0MiB|
|scrambled109208.smt2                                                                       |1200.157s |1079.0MiB|
|scrambled38610.smt2                                                                        |1200.152s |1244.0MiB|
|scrambled15552.smt2                                                                        |1200.148s |980.0MiB|
|scrambled100416.smt2                                                                       |1200.124s |612.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |612.0MiB|612.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1292.0MiB|1292.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1079.0MiB|1079.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |3928.0MiB|3928.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |431.0MiB|431.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |2005.0MiB|2005.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |827.0MiB|827.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |498.0MiB|498.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1366.0MiB|1366.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |815.0MiB|815.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |2023.0MiB|2023.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |544.0MiB|544.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1446.0MiB|1446.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |980.0MiB|980.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |559.0MiB|559.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |2288.0MiB|2288.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |13.766GiB|13.766GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |697.0MiB|697.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |3779.0MiB|3779.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |612.0MiB|612.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1292.0MiB|1292.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1079.0MiB|1079.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |3928.0MiB|3928.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |431.0MiB|431.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |2005.0MiB|2005.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |827.0MiB|827.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |498.0MiB|498.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1366.0MiB|1366.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |815.0MiB|815.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |2023.0MiB|2023.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |544.0MiB|544.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1446.0MiB|1446.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |980.0MiB|980.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |559.0MiB|559.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |2288.0MiB|2288.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |13.766GiB|13.766GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |697.0MiB|697.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |3779.0MiB|3779.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |612.0MiB|612.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1292.0MiB|1292.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1079.0MiB|1079.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |3928.0MiB|3928.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |431.0MiB|431.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |2005.0MiB|2005.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |827.0MiB|827.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |498.0MiB|498.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1366.0MiB|1366.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |815.0MiB|815.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |2023.0MiB|2023.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |544.0MiB|544.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1446.0MiB|1446.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |980.0MiB|980.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |559.0MiB|559.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |2288.0MiB|2288.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |13.766GiB|13.766GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |697.0MiB|697.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |3779.0MiB|3779.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |612.0MiB|612.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1292.0MiB|1292.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1079.0MiB|1079.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |3928.0MiB|3928.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |431.0MiB|431.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |2005.0MiB|2005.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |827.0MiB|827.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |498.0MiB|498.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1366.0MiB|1366.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |815.0MiB|815.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |2023.0MiB|2023.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |544.0MiB|544.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |551.0MiB|551.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1446.0MiB|1446.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |980.0MiB|980.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |559.0MiB|559.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |2288.0MiB|2288.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |13.766GiB|13.766GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |697.0MiB|697.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |3779.0MiB|3779.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.205s |13.766GiB|
|scrambled116992.smt2                                                                       |1200.539s |3928.0MiB|
|scrambled35345.smt2                                                                        |1200.672s |3779.0MiB|
|scrambled75206.smt2                                                                        | 904.370s |2602.0MiB|
|scrambled41773.smt2                                                                        |1200.308s |2382.0MiB|
|scrambled23483.smt2                                                                        |1200.413s |2288.0MiB|
|scrambled1379.smt2                                                                         |1200.346s |2023.0MiB|
|scrambled119992.smt2                                                                       |1200.331s |2005.0MiB|
|scrambled92133.smt2                                                                        |1200.213s |1807.0MiB|
|scrambled15284.smt2                                                                        |1129.195s |1446.0MiB|
|scrambled124624.smt2                                                                       |1200.233s |1366.0MiB|
|scrambled62859.smt2                                                                        |1200.172s |1345.0MiB|
|scrambled103851.smt2                                                                       |1200.163s |1292.0MiB|
|scrambled38610.smt2                                                                        |1200.152s |1244.0MiB|
|scrambled97138.smt2                                                                        |1200.184s |1233.0MiB|
|scrambled42287.smt2                                                                        |1200.159s |1228.0MiB|
|scrambled62810.smt2                                                                        |1200.216s |1190.0MiB|
|scrambled109208.smt2                                                                       |1200.157s |1079.0MiB|
|scrambled15552.smt2                                                                        |1200.148s |980.0MiB|
|scrambled4441.smt2                                                                         |1186.791s |914.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.205s |13.766GiB|
|scrambled116992.smt2                                                                       |1200.539s |3928.0MiB|
|scrambled35345.smt2                                                                        |1200.672s |3779.0MiB|
|scrambled75206.smt2                                                                        | 904.370s |2602.0MiB|
|scrambled41773.smt2                                                                        |1200.308s |2382.0MiB|
|scrambled23483.smt2                                                                        |1200.413s |2288.0MiB|
|scrambled1379.smt2                                                                         |1200.346s |2023.0MiB|
|scrambled119992.smt2                                                                       |1200.331s |2005.0MiB|
|scrambled92133.smt2                                                                        |1200.213s |1807.0MiB|
|scrambled15284.smt2                                                                        |1129.195s |1446.0MiB|
|scrambled124624.smt2                                                                       |1200.233s |1366.0MiB|
|scrambled62859.smt2                                                                        |1200.172s |1345.0MiB|
|scrambled103851.smt2                                                                       |1200.163s |1292.0MiB|
|scrambled38610.smt2                                                                        |1200.152s |1244.0MiB|
|scrambled97138.smt2                                                                        |1200.184s |1233.0MiB|
|scrambled42287.smt2                                                                        |1200.159s |1228.0MiB|
|scrambled62810.smt2                                                                        |1200.216s |1190.0MiB|
|scrambled109208.smt2                                                                       |1200.157s |1079.0MiB|
|scrambled15552.smt2                                                                        |1200.148s |980.0MiB|
|scrambled4441.smt2                                                                         |1186.791s |914.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.124s  |1200.124s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.539s  |1200.539s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.331s  |1200.331s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.233s  |1200.233s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 588.110s  | 588.110s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.346s  |1200.346s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1129.195s  |1129.195s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.413s  |1200.413s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.205s  |1201.205s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.672s  |1200.672s  |   0.000s  | 0.0%|
|scrambled38610.smt2                                                                         |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled41312.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled41773.smt2                                                                         |1200.308s  |1200.308s  |   0.000s  | 0.0%|
|scrambled41801.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled42287.smt2                                                                         |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled4441.smt2                                                                          |1186.791s  |1186.791s  |   0.000s  | 0.0%|
|scrambled54073.smt2                                                                         | 230.127s  | 230.127s  |   0.000s  | 0.0%|
|scrambled58720.smt2                                                                         |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled62536.smt2                                                                         | 536.974s  | 536.974s  |   0.000s  | 0.0%|
|scrambled62810.smt2                                                                         |1200.216s  |1200.216s  |   0.000s  | 0.0%|
|scrambled62859.smt2                                                                         |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled6373.smt2                                                                          | 654.613s  | 654.613s  |   0.000s  | 0.0%|
|scrambled75206.smt2                                                                         | 904.370s  | 904.370s  |   0.000s  | 0.0%|
|scrambled78432.smt2                                                                         | 276.525s  | 276.525s  |   0.000s  | 0.0%|
|scrambled78606.smt2                                                                         | 202.811s  | 202.811s  |   0.000s  | 0.0%|
|scrambled79181.smt2                                                                         |1200.102s  |1200.102s  |   0.000s  | 0.0%|
|scrambled82743.smt2                                                                         | 925.849s  | 925.849s  |   0.000s  | 0.0%|
|scrambled89071.smt2                                                                         | 196.053s  | 196.053s  |   0.000s  | 0.0%|
|scrambled90733.smt2                                                                         | 547.840s  | 547.840s  |   0.000s  | 0.0%|
|scrambled92133.smt2                                                                         |1200.213s  |1200.213s  |   0.000s  | 0.0%|
|scrambled96514.smt2                                                                         | 100.191s  | 100.191s  |   0.000s  | 0.0%|
|scrambled96733.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled97138.smt2                                                                         |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled98799.smt2                                                                         | 469.933s  | 469.933s  |   0.000s  | 0.0%|
</details>
