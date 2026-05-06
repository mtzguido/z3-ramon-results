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
Job tag: Z3-threads-8-smtcomp2025-QF_IDL-timeout20min-bb2-no_default_tactic-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=true smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_IDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_IDL-timeout20min-bb2-no_default_tactic-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=true smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_IDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.126s  |1200.126s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.202s  |1200.202s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.451s  |1200.451s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        | 363.482s  | 363.482s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.366s  |1200.366s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.213s  |1200.213s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 393.860s  | 393.860s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.336s  |1200.336s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.124s  |1200.124s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 984.558s  | 984.558s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.303s  |1200.303s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1197.207s  |1197.207s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.439s  |1200.439s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.126s  |1200.126s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.202s  |1200.202s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.451s  |1200.451s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        | 363.482s  | 363.482s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.366s  |1200.366s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.213s  |1200.213s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 393.860s  | 393.860s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.336s  |1200.336s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.124s  |1200.124s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 984.558s  | 984.558s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.303s  |1200.303s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1197.207s  |1197.207s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.439s  |1200.439s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.126s  |1200.126s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.202s  |1200.202s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.451s  |1200.451s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        | 363.482s  | 363.482s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.366s  |1200.366s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.213s  |1200.213s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 393.860s  | 393.860s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.336s  |1200.336s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.124s  |1200.124s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 984.558s  | 984.558s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.303s  |1200.303s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1197.207s  |1197.207s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.439s  |1200.439s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.126s  |1200.126s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.202s  |1200.202s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.451s  |1200.451s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        | 363.482s  | 363.482s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.366s  |1200.366s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.213s  |1200.213s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 393.860s  | 393.860s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.336s  |1200.336s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.124s  |1200.124s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 984.558s  | 984.558s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.303s  |1200.303s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1197.207s  |1197.207s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.439s  |1200.439s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled116992.smt2                                                                       |1200.451s |4078.0MiB|
|scrambled35345.smt2                                                                        |1200.439s |3684.0MiB|
|scrambled119992.smt2                                                                       |1200.366s |2013.0MiB|
|scrambled1379.smt2                                                                         |1200.336s |1991.0MiB|
|scrambled23483.smt2                                                                        |1200.303s |2259.0MiB|
|scrambled41773.smt2                                                                        |1200.297s |2279.0MiB|
|scrambled92133.smt2                                                                        |1200.221s |1815.0MiB|
|scrambled124624.smt2                                                                       |1200.213s |1407.0MiB|
|scrambled103851.smt2                                                                       |1200.202s |1308.0MiB|
|scrambled62859.smt2                                                                        |1200.199s |1352.0MiB|
|scrambled38610.smt2                                                                        |1200.191s |1279.0MiB|
|scrambled41801.smt2                                                                        |1200.189s |787.0MiB|
|scrambled97138.smt2                                                                        |1200.187s |1264.0MiB|
|scrambled15552.smt2                                                                        |1200.172s |926.0MiB|
|scrambled109208.smt2                                                                       |1200.158s |1087.0MiB|
|scrambled42287.smt2                                                                        |1200.154s |1217.0MiB|
|scrambled122058.smt2                                                                       |1200.138s |810.0MiB|
|scrambled27577.smt2                                                                        |1200.137s |708.0MiB|
|scrambled62810.smt2                                                                        |1200.133s |1187.0MiB|
|scrambled58720.smt2                                                                        |1200.128s |553.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled116992.smt2                                                                       |1200.451s |4078.0MiB|
|scrambled35345.smt2                                                                        |1200.439s |3684.0MiB|
|scrambled119992.smt2                                                                       |1200.366s |2013.0MiB|
|scrambled1379.smt2                                                                         |1200.336s |1991.0MiB|
|scrambled23483.smt2                                                                        |1200.303s |2259.0MiB|
|scrambled41773.smt2                                                                        |1200.297s |2279.0MiB|
|scrambled92133.smt2                                                                        |1200.221s |1815.0MiB|
|scrambled124624.smt2                                                                       |1200.213s |1407.0MiB|
|scrambled103851.smt2                                                                       |1200.202s |1308.0MiB|
|scrambled62859.smt2                                                                        |1200.199s |1352.0MiB|
|scrambled38610.smt2                                                                        |1200.191s |1279.0MiB|
|scrambled41801.smt2                                                                        |1200.189s |787.0MiB|
|scrambled97138.smt2                                                                        |1200.187s |1264.0MiB|
|scrambled15552.smt2                                                                        |1200.172s |926.0MiB|
|scrambled109208.smt2                                                                       |1200.158s |1087.0MiB|
|scrambled42287.smt2                                                                        |1200.154s |1217.0MiB|
|scrambled122058.smt2                                                                       |1200.138s |810.0MiB|
|scrambled27577.smt2                                                                        |1200.137s |708.0MiB|
|scrambled62810.smt2                                                                        |1200.133s |1187.0MiB|
|scrambled58720.smt2                                                                        |1200.128s |553.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |603.0MiB|603.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1308.0MiB|1308.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1087.0MiB|1087.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |4078.0MiB|4078.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |357.0MiB|357.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |2013.0MiB|2013.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |810.0MiB|810.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |496.0MiB|496.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1407.0MiB|1407.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |778.0MiB|778.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |1991.0MiB|1991.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |543.0MiB|543.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1412.0MiB|1412.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |926.0MiB|926.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |557.0MiB|557.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |2259.0MiB|2259.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |13.965GiB|13.965GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |708.0MiB|708.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |3684.0MiB|3684.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |603.0MiB|603.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1308.0MiB|1308.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1087.0MiB|1087.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |4078.0MiB|4078.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |357.0MiB|357.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |2013.0MiB|2013.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |810.0MiB|810.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |496.0MiB|496.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1407.0MiB|1407.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |778.0MiB|778.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |1991.0MiB|1991.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |543.0MiB|543.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1412.0MiB|1412.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |926.0MiB|926.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |557.0MiB|557.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |2259.0MiB|2259.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |13.965GiB|13.965GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |708.0MiB|708.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |3684.0MiB|3684.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |603.0MiB|603.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1308.0MiB|1308.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1087.0MiB|1087.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |4078.0MiB|4078.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |357.0MiB|357.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |2013.0MiB|2013.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |810.0MiB|810.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |496.0MiB|496.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1407.0MiB|1407.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |778.0MiB|778.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |1991.0MiB|1991.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |543.0MiB|543.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1412.0MiB|1412.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |926.0MiB|926.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |557.0MiB|557.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |2259.0MiB|2259.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |13.965GiB|13.965GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |708.0MiB|708.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |3684.0MiB|3684.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |603.0MiB|603.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1308.0MiB|1308.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1087.0MiB|1087.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |4078.0MiB|4078.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |357.0MiB|357.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |2013.0MiB|2013.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |810.0MiB|810.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |496.0MiB|496.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1407.0MiB|1407.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |778.0MiB|778.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |1991.0MiB|1991.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |543.0MiB|543.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1412.0MiB|1412.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |926.0MiB|926.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |557.0MiB|557.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |2259.0MiB|2259.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |13.965GiB|13.965GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |708.0MiB|708.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |3684.0MiB|3684.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1197.207s |13.965GiB|
|scrambled116992.smt2                                                                       |1200.451s |4078.0MiB|
|scrambled35345.smt2                                                                        |1200.439s |3684.0MiB|
|scrambled75206.smt2                                                                        |1059.957s |2619.0MiB|
|scrambled41773.smt2                                                                        |1200.297s |2279.0MiB|
|scrambled23483.smt2                                                                        |1200.303s |2259.0MiB|
|scrambled119992.smt2                                                                       |1200.366s |2013.0MiB|
|scrambled1379.smt2                                                                         |1200.336s |1991.0MiB|
|scrambled92133.smt2                                                                        |1200.221s |1815.0MiB|
|scrambled15284.smt2                                                                        | 984.558s |1412.0MiB|
|scrambled124624.smt2                                                                       |1200.213s |1407.0MiB|
|scrambled62859.smt2                                                                        |1200.199s |1352.0MiB|
|scrambled103851.smt2                                                                       |1200.202s |1308.0MiB|
|scrambled38610.smt2                                                                        |1200.191s |1279.0MiB|
|scrambled97138.smt2                                                                        |1200.187s |1264.0MiB|
|scrambled42287.smt2                                                                        |1200.154s |1217.0MiB|
|scrambled62810.smt2                                                                        |1200.133s |1187.0MiB|
|scrambled109208.smt2                                                                       |1200.158s |1087.0MiB|
|scrambled15552.smt2                                                                        |1200.172s |926.0MiB|
|scrambled82743.smt2                                                                        |1159.985s |923.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1197.207s |13.965GiB|
|scrambled116992.smt2                                                                       |1200.451s |4078.0MiB|
|scrambled35345.smt2                                                                        |1200.439s |3684.0MiB|
|scrambled75206.smt2                                                                        |1059.957s |2619.0MiB|
|scrambled41773.smt2                                                                        |1200.297s |2279.0MiB|
|scrambled23483.smt2                                                                        |1200.303s |2259.0MiB|
|scrambled119992.smt2                                                                       |1200.366s |2013.0MiB|
|scrambled1379.smt2                                                                         |1200.336s |1991.0MiB|
|scrambled92133.smt2                                                                        |1200.221s |1815.0MiB|
|scrambled15284.smt2                                                                        | 984.558s |1412.0MiB|
|scrambled124624.smt2                                                                       |1200.213s |1407.0MiB|
|scrambled62859.smt2                                                                        |1200.199s |1352.0MiB|
|scrambled103851.smt2                                                                       |1200.202s |1308.0MiB|
|scrambled38610.smt2                                                                        |1200.191s |1279.0MiB|
|scrambled97138.smt2                                                                        |1200.187s |1264.0MiB|
|scrambled42287.smt2                                                                        |1200.154s |1217.0MiB|
|scrambled62810.smt2                                                                        |1200.133s |1187.0MiB|
|scrambled109208.smt2                                                                       |1200.158s |1087.0MiB|
|scrambled15552.smt2                                                                        |1200.172s |926.0MiB|
|scrambled82743.smt2                                                                        |1159.985s |923.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.126s  |1200.126s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.202s  |1200.202s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.158s  |1200.158s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.451s  |1200.451s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        | 363.482s  | 363.482s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.366s  |1200.366s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.213s  |1200.213s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 393.860s  | 393.860s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.336s  |1200.336s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.124s  |1200.124s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 984.558s  | 984.558s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.303s  |1200.303s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1197.207s  |1197.207s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.439s  |1200.439s  |   0.000s  | 0.0%|
|scrambled38610.smt2                                                                         |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled41312.smt2                                                                         |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled41773.smt2                                                                         |1200.297s  |1200.297s  |   0.000s  | 0.0%|
|scrambled41801.smt2                                                                         |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled42287.smt2                                                                         |1200.154s  |1200.154s  |   0.000s  | 0.0%|
|scrambled4441.smt2                                                                          | 922.039s  | 922.039s  |   0.000s  | 0.0%|
|scrambled54073.smt2                                                                         | 219.255s  | 219.255s  |   0.000s  | 0.0%|
|scrambled58720.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled62536.smt2                                                                         | 465.311s  | 465.311s  |   0.000s  | 0.0%|
|scrambled62810.smt2                                                                         |1200.133s  |1200.133s  |   0.000s  | 0.0%|
|scrambled62859.smt2                                                                         |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled6373.smt2                                                                          | 877.072s  | 877.072s  |   0.000s  | 0.0%|
|scrambled75206.smt2                                                                         |1059.957s  |1059.957s  |   0.000s  | 0.0%|
|scrambled78432.smt2                                                                         | 252.954s  | 252.954s  |   0.000s  | 0.0%|
|scrambled78606.smt2                                                                         | 175.941s  | 175.941s  |   0.000s  | 0.0%|
|scrambled79181.smt2                                                                         | 423.892s  | 423.892s  |   0.000s  | 0.0%|
|scrambled82743.smt2                                                                         |1159.985s  |1159.985s  |   0.000s  | 0.0%|
|scrambled89071.smt2                                                                         | 159.480s  | 159.480s  |   0.000s  | 0.0%|
|scrambled90733.smt2                                                                         | 580.457s  | 580.457s  |   0.000s  | 0.0%|
|scrambled92133.smt2                                                                         |1200.221s  |1200.221s  |   0.000s  | 0.0%|
|scrambled96514.smt2                                                                         |  74.369s  |  74.369s  |   0.000s  | 0.0%|
|scrambled96733.smt2                                                                         |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled97138.smt2                                                                         |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled98799.smt2                                                                         | 644.372s  | 644.372s  |   0.000s  | 0.0%|
</details>
