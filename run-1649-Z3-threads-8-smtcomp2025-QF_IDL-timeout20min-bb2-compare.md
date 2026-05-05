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
Job tag: Z3-threads-8-smtcomp2025-QF_IDL-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_IDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_IDL-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_IDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.301s  |1200.301s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.884s  |1201.884s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.242s  |1200.242s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.148s  |1200.148s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.301s  |1200.301s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.884s  |1201.884s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.242s  |1200.242s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.148s  |1200.148s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.301s  |1200.301s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.884s  |1201.884s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.242s  |1200.242s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.148s  |1200.148s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.301s  |1200.301s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.884s  |1201.884s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.242s  |1200.242s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.148s  |1200.148s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.884s |13.868GiB|
|scrambled124624.smt2                                                                       |1200.301s |1438.0MiB|
|scrambled27577.smt2                                                                        |1200.242s |1163.0MiB|
|scrambled41801.smt2                                                                        |1200.229s |966.0MiB|
|scrambled42287.smt2                                                                        |1200.220s |1423.0MiB|
|scrambled62859.smt2                                                                        |1200.205s |1564.0MiB|
|scrambled92133.smt2                                                                        |1200.205s |1830.0MiB|
|scrambled97138.smt2                                                                        |1200.202s |1445.0MiB|
|scrambled15552.smt2                                                                        |1200.199s |902.0MiB|
|scrambled62810.smt2                                                                        |1200.194s |1385.0MiB|
|scrambled103851.smt2                                                                       |1200.189s |1513.0MiB|
|scrambled38610.smt2                                                                        |1200.172s |1475.0MiB|
|scrambled96733.smt2                                                                        |1200.168s |828.0MiB|
|scrambled116992.smt2                                                                       |1200.159s |543.0MiB|
|scrambled98799.smt2                                                                        |1200.157s |802.0MiB|
|scrambled82743.smt2                                                                        |1200.155s |819.0MiB|
|scrambled128361.smt2                                                                       |1200.152s |743.0MiB|
|scrambled54073.smt2                                                                        |1200.151s |661.0MiB|
|scrambled58720.smt2                                                                        |1200.149s |652.0MiB|
|scrambled35345.smt2                                                                        |1200.148s |521.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.884s |13.868GiB|
|scrambled124624.smt2                                                                       |1200.301s |1438.0MiB|
|scrambled27577.smt2                                                                        |1200.242s |1163.0MiB|
|scrambled41801.smt2                                                                        |1200.229s |966.0MiB|
|scrambled42287.smt2                                                                        |1200.220s |1423.0MiB|
|scrambled62859.smt2                                                                        |1200.205s |1564.0MiB|
|scrambled92133.smt2                                                                        |1200.205s |1830.0MiB|
|scrambled97138.smt2                                                                        |1200.202s |1445.0MiB|
|scrambled15552.smt2                                                                        |1200.199s |902.0MiB|
|scrambled62810.smt2                                                                        |1200.194s |1385.0MiB|
|scrambled103851.smt2                                                                       |1200.189s |1513.0MiB|
|scrambled38610.smt2                                                                        |1200.172s |1475.0MiB|
|scrambled96733.smt2                                                                        |1200.168s |828.0MiB|
|scrambled116992.smt2                                                                       |1200.159s |543.0MiB|
|scrambled98799.smt2                                                                        |1200.157s |802.0MiB|
|scrambled82743.smt2                                                                        |1200.155s |819.0MiB|
|scrambled128361.smt2                                                                       |1200.152s |743.0MiB|
|scrambled54073.smt2                                                                        |1200.151s |661.0MiB|
|scrambled58720.smt2                                                                        |1200.149s |652.0MiB|
|scrambled35345.smt2                                                                        |1200.148s |521.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |670.0MiB|670.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1513.0MiB|1513.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |845.0MiB|845.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |543.0MiB|543.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |503.0MiB|503.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |474.0MiB|474.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |898.0MiB|898.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |577.0MiB|577.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1438.0MiB|1438.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |743.0MiB|743.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |465.0MiB|465.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |622.0MiB|622.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |479.0MiB|479.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |902.0MiB|902.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |668.0MiB|668.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |462.0MiB|462.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |13.868GiB|13.868GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |1163.0MiB|1163.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |521.0MiB|521.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |670.0MiB|670.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1513.0MiB|1513.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |845.0MiB|845.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |543.0MiB|543.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |503.0MiB|503.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |474.0MiB|474.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |898.0MiB|898.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |577.0MiB|577.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1438.0MiB|1438.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |743.0MiB|743.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |465.0MiB|465.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |622.0MiB|622.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |479.0MiB|479.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |902.0MiB|902.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |668.0MiB|668.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |462.0MiB|462.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |13.868GiB|13.868GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |1163.0MiB|1163.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |521.0MiB|521.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |670.0MiB|670.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1513.0MiB|1513.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |845.0MiB|845.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |543.0MiB|543.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |503.0MiB|503.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |474.0MiB|474.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |898.0MiB|898.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |577.0MiB|577.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1438.0MiB|1438.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |743.0MiB|743.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |465.0MiB|465.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |622.0MiB|622.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |479.0MiB|479.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |902.0MiB|902.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |668.0MiB|668.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |462.0MiB|462.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |13.868GiB|13.868GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |1163.0MiB|1163.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |521.0MiB|521.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |670.0MiB|670.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1513.0MiB|1513.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |845.0MiB|845.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |543.0MiB|543.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |503.0MiB|503.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |474.0MiB|474.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |898.0MiB|898.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |577.0MiB|577.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1438.0MiB|1438.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |743.0MiB|743.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |465.0MiB|465.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |622.0MiB|622.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |479.0MiB|479.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |902.0MiB|902.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |668.0MiB|668.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |462.0MiB|462.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |13.868GiB|13.868GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |1163.0MiB|1163.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |521.0MiB|521.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.884s |13.868GiB|
|scrambled92133.smt2                                                                        |1200.205s |1830.0MiB|
|scrambled62859.smt2                                                                        |1200.205s |1564.0MiB|
|scrambled103851.smt2                                                                       |1200.189s |1513.0MiB|
|scrambled38610.smt2                                                                        |1200.172s |1475.0MiB|
|scrambled97138.smt2                                                                        |1200.202s |1445.0MiB|
|scrambled124624.smt2                                                                       |1200.301s |1438.0MiB|
|scrambled42287.smt2                                                                        |1200.220s |1423.0MiB|
|scrambled62810.smt2                                                                        |1200.194s |1385.0MiB|
|scrambled27577.smt2                                                                        |1200.242s |1163.0MiB|
|scrambled41801.smt2                                                                        |1200.229s |966.0MiB|
|scrambled15552.smt2                                                                        |1200.199s |902.0MiB|
|scrambled122058.smt2                                                                       |1200.110s |898.0MiB|
|scrambled90733.smt2                                                                        |1200.138s |876.0MiB|
|scrambled109208.smt2                                                                       |1200.146s |845.0MiB|
|scrambled96733.smt2                                                                        |1200.168s |828.0MiB|
|scrambled9927.smt2                                                                         |1200.125s |828.0MiB|
|scrambled82743.smt2                                                                        |1200.155s |819.0MiB|
|scrambled98799.smt2                                                                        |1200.157s |802.0MiB|
|scrambled4441.smt2                                                                         |1200.109s |785.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.884s |13.868GiB|
|scrambled92133.smt2                                                                        |1200.205s |1830.0MiB|
|scrambled62859.smt2                                                                        |1200.205s |1564.0MiB|
|scrambled103851.smt2                                                                       |1200.189s |1513.0MiB|
|scrambled38610.smt2                                                                        |1200.172s |1475.0MiB|
|scrambled97138.smt2                                                                        |1200.202s |1445.0MiB|
|scrambled124624.smt2                                                                       |1200.301s |1438.0MiB|
|scrambled42287.smt2                                                                        |1200.220s |1423.0MiB|
|scrambled62810.smt2                                                                        |1200.194s |1385.0MiB|
|scrambled27577.smt2                                                                        |1200.242s |1163.0MiB|
|scrambled41801.smt2                                                                        |1200.229s |966.0MiB|
|scrambled15552.smt2                                                                        |1200.199s |902.0MiB|
|scrambled122058.smt2                                                                       |1200.110s |898.0MiB|
|scrambled90733.smt2                                                                        |1200.138s |876.0MiB|
|scrambled109208.smt2                                                                       |1200.146s |845.0MiB|
|scrambled96733.smt2                                                                        |1200.168s |828.0MiB|
|scrambled9927.smt2                                                                         |1200.125s |828.0MiB|
|scrambled82743.smt2                                                                        |1200.155s |819.0MiB|
|scrambled98799.smt2                                                                        |1200.157s |802.0MiB|
|scrambled4441.smt2                                                                         |1200.109s |785.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.301s  |1200.301s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.884s  |1201.884s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.242s  |1200.242s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.148s  |1200.148s  |   0.000s  | 0.0%|
|scrambled38610.smt2                                                                         |1200.172s  |1200.172s  |   0.000s  | 0.0%|
|scrambled41312.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled41773.smt2                                                                         |1200.124s  |1200.124s  |   0.000s  | 0.0%|
|scrambled41801.smt2                                                                         |1200.229s  |1200.229s  |   0.000s  | 0.0%|
|scrambled42287.smt2                                                                         |1200.220s  |1200.220s  |   0.000s  | 0.0%|
|scrambled4441.smt2                                                                          |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled54073.smt2                                                                         |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled58720.smt2                                                                         |1200.149s  |1200.149s  |   0.000s  | 0.0%|
|scrambled62536.smt2                                                                         | 920.027s  | 920.027s  |   0.000s  | 0.0%|
|scrambled62810.smt2                                                                         |1200.194s  |1200.194s  |   0.000s  | 0.0%|
|scrambled62859.smt2                                                                         |1200.205s  |1200.205s  |   0.000s  | 0.0%|
|scrambled6373.smt2                                                                          |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled75206.smt2                                                                         |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled78432.smt2                                                                         |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled78606.smt2                                                                         |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled79181.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled82743.smt2                                                                         |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled89071.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled90733.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled92133.smt2                                                                         |1200.205s  |1200.205s  |   0.000s  | 0.0%|
|scrambled96514.smt2                                                                         | 336.512s  | 336.512s  |   0.000s  | 0.0%|
|scrambled96733.smt2                                                                         |1200.168s  |1200.168s  |   0.000s  | 0.0%|
|scrambled97138.smt2                                                                         |1200.202s  |1200.202s  |   0.000s  | 0.0%|
|scrambled98799.smt2                                                                         |1200.157s  |1200.157s  |   0.000s  | 0.0%|
</details>
