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
Job tag: Z3-threads-8-smtcomp2025-QF_IDL-timeout20min-bb2-no_default_tactic
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=false smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_IDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_IDL-timeout20min-bb2-no_default_tactic
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=false smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_IDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.133s  |1200.133s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.238s  |1200.238s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 792.602s  | 792.602s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.230s  |1201.230s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.111s  |1200.111s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.133s  |1200.133s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.238s  |1200.238s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 792.602s  | 792.602s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.230s  |1201.230s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.111s  |1200.111s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.133s  |1200.133s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.238s  |1200.238s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 792.602s  | 792.602s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.230s  |1201.230s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.111s  |1200.111s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.133s  |1200.133s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.238s  |1200.238s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 792.602s  | 792.602s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.230s  |1201.230s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.111s  |1200.111s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.230s |13.872GiB|
|scrambled124624.smt2                                                                       |1200.238s |1468.0MiB|
|scrambled82743.smt2                                                                        |1200.185s |830.0MiB|
|scrambled62810.smt2                                                                        |1200.183s |1341.0MiB|
|scrambled92133.smt2                                                                        |1200.175s |1839.0MiB|
|scrambled27577.smt2                                                                        |1200.174s |1167.0MiB|
|scrambled41801.smt2                                                                        |1200.173s |922.0MiB|
|scrambled97138.smt2                                                                        |1200.164s |1439.0MiB|
|scrambled38610.smt2                                                                        |1200.160s |1447.0MiB|
|scrambled62859.smt2                                                                        |1200.159s |1488.0MiB|
|scrambled15552.smt2                                                                        |1200.157s |1167.0MiB|
|scrambled103851.smt2                                                                       |1200.157s |1465.0MiB|
|scrambled42287.smt2                                                                        |1200.156s |1428.0MiB|
|scrambled128361.smt2                                                                       |1200.152s |780.0MiB|
|scrambled58720.smt2                                                                        |1200.152s |654.0MiB|
|scrambled21544.smt2                                                                        |1200.151s |733.0MiB|
|scrambled117178.smt2                                                                       |1200.140s |530.0MiB|
|scrambled54073.smt2                                                                        |1200.139s |663.0MiB|
|scrambled9927.smt2                                                                         |1200.136s |731.0MiB|
|scrambled122058.smt2                                                                       |1200.133s |891.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.230s |13.872GiB|
|scrambled124624.smt2                                                                       |1200.238s |1468.0MiB|
|scrambled82743.smt2                                                                        |1200.185s |830.0MiB|
|scrambled62810.smt2                                                                        |1200.183s |1341.0MiB|
|scrambled92133.smt2                                                                        |1200.175s |1839.0MiB|
|scrambled27577.smt2                                                                        |1200.174s |1167.0MiB|
|scrambled41801.smt2                                                                        |1200.173s |922.0MiB|
|scrambled97138.smt2                                                                        |1200.164s |1439.0MiB|
|scrambled38610.smt2                                                                        |1200.160s |1447.0MiB|
|scrambled62859.smt2                                                                        |1200.159s |1488.0MiB|
|scrambled15552.smt2                                                                        |1200.157s |1167.0MiB|
|scrambled103851.smt2                                                                       |1200.157s |1465.0MiB|
|scrambled42287.smt2                                                                        |1200.156s |1428.0MiB|
|scrambled128361.smt2                                                                       |1200.152s |780.0MiB|
|scrambled58720.smt2                                                                        |1200.152s |654.0MiB|
|scrambled21544.smt2                                                                        |1200.151s |733.0MiB|
|scrambled117178.smt2                                                                       |1200.140s |530.0MiB|
|scrambled54073.smt2                                                                        |1200.139s |663.0MiB|
|scrambled9927.smt2                                                                         |1200.136s |731.0MiB|
|scrambled122058.smt2                                                                       |1200.133s |891.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |669.0MiB|669.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1465.0MiB|1465.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |877.0MiB|877.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |548.0MiB|548.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |530.0MiB|530.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |472.0MiB|472.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |891.0MiB|891.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |580.0MiB|580.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1468.0MiB|1468.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |780.0MiB|780.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |466.0MiB|466.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |632.0MiB|632.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |662.0MiB|662.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |431.0MiB|431.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |1167.0MiB|1167.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |733.0MiB|733.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |462.0MiB|462.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |13.872GiB|13.872GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |1167.0MiB|1167.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |529.0MiB|529.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |669.0MiB|669.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1465.0MiB|1465.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |877.0MiB|877.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |548.0MiB|548.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |530.0MiB|530.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |472.0MiB|472.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |891.0MiB|891.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |580.0MiB|580.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1468.0MiB|1468.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |780.0MiB|780.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |466.0MiB|466.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |632.0MiB|632.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |662.0MiB|662.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |431.0MiB|431.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |1167.0MiB|1167.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |733.0MiB|733.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |462.0MiB|462.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |13.872GiB|13.872GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |1167.0MiB|1167.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |529.0MiB|529.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |669.0MiB|669.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1465.0MiB|1465.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |877.0MiB|877.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |548.0MiB|548.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |530.0MiB|530.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |472.0MiB|472.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |891.0MiB|891.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |580.0MiB|580.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1468.0MiB|1468.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |780.0MiB|780.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |466.0MiB|466.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |632.0MiB|632.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |662.0MiB|662.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |431.0MiB|431.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |1167.0MiB|1167.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |733.0MiB|733.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |462.0MiB|462.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |13.872GiB|13.872GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |1167.0MiB|1167.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |529.0MiB|529.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |669.0MiB|669.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |1465.0MiB|1465.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |877.0MiB|877.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |548.0MiB|548.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |530.0MiB|530.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |472.0MiB|472.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |891.0MiB|891.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |580.0MiB|580.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1468.0MiB|1468.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |780.0MiB|780.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |466.0MiB|466.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |632.0MiB|632.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |662.0MiB|662.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |431.0MiB|431.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |1167.0MiB|1167.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |733.0MiB|733.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |462.0MiB|462.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |13.872GiB|13.872GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |1167.0MiB|1167.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |529.0MiB|529.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.230s |13.872GiB|
|scrambled92133.smt2                                                                        |1200.175s |1839.0MiB|
|scrambled62859.smt2                                                                        |1200.159s |1488.0MiB|
|scrambled124624.smt2                                                                       |1200.238s |1468.0MiB|
|scrambled103851.smt2                                                                       |1200.157s |1465.0MiB|
|scrambled38610.smt2                                                                        |1200.160s |1447.0MiB|
|scrambled97138.smt2                                                                        |1200.164s |1439.0MiB|
|scrambled42287.smt2                                                                        |1200.156s |1428.0MiB|
|scrambled62810.smt2                                                                        |1200.183s |1341.0MiB|
|scrambled27577.smt2                                                                        |1200.174s |1167.0MiB|
|scrambled15552.smt2                                                                        |1200.157s |1167.0MiB|
|scrambled41801.smt2                                                                        |1200.173s |922.0MiB|
|scrambled122058.smt2                                                                       |1200.133s |891.0MiB|
|scrambled109208.smt2                                                                       |1200.121s |877.0MiB|
|scrambled82743.smt2                                                                        |1200.185s |830.0MiB|
|scrambled4441.smt2                                                                         |1200.118s |801.0MiB|
|scrambled90733.smt2                                                                        |1200.106s |795.0MiB|
|scrambled128361.smt2                                                                       |1200.152s |780.0MiB|
|scrambled96733.smt2                                                                        |1200.118s |777.0MiB|
|scrambled21544.smt2                                                                        |1200.151s |733.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.230s |13.872GiB|
|scrambled92133.smt2                                                                        |1200.175s |1839.0MiB|
|scrambled62859.smt2                                                                        |1200.159s |1488.0MiB|
|scrambled124624.smt2                                                                       |1200.238s |1468.0MiB|
|scrambled103851.smt2                                                                       |1200.157s |1465.0MiB|
|scrambled38610.smt2                                                                        |1200.160s |1447.0MiB|
|scrambled97138.smt2                                                                        |1200.164s |1439.0MiB|
|scrambled42287.smt2                                                                        |1200.156s |1428.0MiB|
|scrambled62810.smt2                                                                        |1200.183s |1341.0MiB|
|scrambled27577.smt2                                                                        |1200.174s |1167.0MiB|
|scrambled15552.smt2                                                                        |1200.157s |1167.0MiB|
|scrambled41801.smt2                                                                        |1200.173s |922.0MiB|
|scrambled122058.smt2                                                                       |1200.133s |891.0MiB|
|scrambled109208.smt2                                                                       |1200.121s |877.0MiB|
|scrambled82743.smt2                                                                        |1200.185s |830.0MiB|
|scrambled4441.smt2                                                                         |1200.118s |801.0MiB|
|scrambled90733.smt2                                                                        |1200.106s |795.0MiB|
|scrambled128361.smt2                                                                       |1200.152s |780.0MiB|
|scrambled96733.smt2                                                                        |1200.118s |777.0MiB|
|scrambled21544.smt2                                                                        |1200.151s |733.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.133s  |1200.133s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.238s  |1200.238s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 792.602s  | 792.602s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.230s  |1201.230s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.111s  |1200.111s  |   0.000s  | 0.0%|
|scrambled38610.smt2                                                                         |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled41312.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled41773.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled41801.smt2                                                                         |1200.173s  |1200.173s  |   0.000s  | 0.0%|
|scrambled42287.smt2                                                                         |1200.156s  |1200.156s  |   0.000s  | 0.0%|
|scrambled4441.smt2                                                                          |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled54073.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled58720.smt2                                                                         |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled62536.smt2                                                                         | 722.451s  | 722.451s  |   0.000s  | 0.0%|
|scrambled62810.smt2                                                                         |1200.183s  |1200.183s  |   0.000s  | 0.0%|
|scrambled62859.smt2                                                                         |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled6373.smt2                                                                          |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled75206.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled78432.smt2                                                                         |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled78606.smt2                                                                         |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled79181.smt2                                                                         | 421.719s  | 421.719s  |   0.000s  | 0.0%|
|scrambled82743.smt2                                                                         |1200.185s  |1200.185s  |   0.000s  | 0.0%|
|scrambled89071.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled90733.smt2                                                                         |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled92133.smt2                                                                         |1200.175s  |1200.175s  |   0.000s  | 0.0%|
|scrambled96514.smt2                                                                         | 286.984s  | 286.984s  |   0.000s  | 0.0%|
|scrambled96733.smt2                                                                         |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled97138.smt2                                                                         |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled98799.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
</details>
