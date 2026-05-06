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
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_IDL-timeout20min-no_default_tactic-auto_config}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=true smt.arith.solver=4"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_IDL
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_IDL-timeout20min-no_default_tactic-auto_config}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=true smt.arith.solver=4"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_IDL
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1083.915s  |1083.915s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 462.955s  | 462.955s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          | 891.226s  | 891.226s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.053s  |1200.053s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1083.915s  |1083.915s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 462.955s  | 462.955s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          | 891.226s  | 891.226s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.053s  |1200.053s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1083.915s  |1083.915s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 462.955s  | 462.955s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          | 891.226s  | 891.226s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.053s  |1200.053s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1083.915s  |1083.915s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 462.955s  | 462.955s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          | 891.226s  | 891.226s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.053s  |1200.053s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1200.169s |1861.0MiB|
|scrambled23483.smt2                                                                        |1200.058s |253.0MiB|
|scrambled119992.smt2                                                                       |1200.056s |228.0MiB|
|scrambled41773.smt2                                                                        |1200.055s |240.0MiB|
|scrambled35345.smt2                                                                        |1200.053s |419.0MiB|
|scrambled92133.smt2                                                                        |1200.050s |221.0MiB|
|scrambled62859.smt2                                                                        |1200.049s |224.0MiB|
|scrambled109208.smt2                                                                       |1200.047s |159.0MiB|
|scrambled97138.smt2                                                                        |1200.040s |119.0MiB|
|scrambled82743.smt2                                                                        |1200.040s |101.0MiB|
|scrambled122058.smt2                                                                       |1200.040s |110.0MiB|
|scrambled38610.smt2                                                                        |1200.040s |120.0MiB|
|scrambled41801.smt2                                                                        |1200.040s |117.0MiB|
|scrambled42287.smt2                                                                        |1200.038s |119.0MiB|
|scrambled14967.smt2                                                                        |1200.037s |70.336MiB|
|scrambled100416.smt2                                                                       |1200.037s |82.232MiB|
|scrambled1447.smt2                                                                         |1200.036s |67.22MiB|
|scrambled58720.smt2                                                                        |1200.036s |72.472MiB|
|scrambled21544.smt2                                                                        |1200.035s |79.42MiB|
|scrambled41312.smt2                                                                        |1200.035s |64.628MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1200.169s |1861.0MiB|
|scrambled23483.smt2                                                                        |1200.058s |253.0MiB|
|scrambled119992.smt2                                                                       |1200.056s |228.0MiB|
|scrambled41773.smt2                                                                        |1200.055s |240.0MiB|
|scrambled35345.smt2                                                                        |1200.053s |419.0MiB|
|scrambled92133.smt2                                                                        |1200.050s |221.0MiB|
|scrambled62859.smt2                                                                        |1200.049s |224.0MiB|
|scrambled109208.smt2                                                                       |1200.047s |159.0MiB|
|scrambled97138.smt2                                                                        |1200.040s |119.0MiB|
|scrambled82743.smt2                                                                        |1200.040s |101.0MiB|
|scrambled122058.smt2                                                                       |1200.040s |110.0MiB|
|scrambled38610.smt2                                                                        |1200.040s |120.0MiB|
|scrambled41801.smt2                                                                        |1200.040s |117.0MiB|
|scrambled42287.smt2                                                                        |1200.038s |119.0MiB|
|scrambled14967.smt2                                                                        |1200.037s |70.336MiB|
|scrambled100416.smt2                                                                       |1200.037s |82.232MiB|
|scrambled1447.smt2                                                                         |1200.036s |67.22MiB|
|scrambled58720.smt2                                                                        |1200.036s |72.472MiB|
|scrambled21544.smt2                                                                        |1200.035s |79.42MiB|
|scrambled41312.smt2                                                                        |1200.035s |64.628MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |82.232MiB|82.232MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |223.0MiB|223.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |159.0MiB|159.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |465.0MiB|465.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |57.664MiB|57.664MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |228.0MiB|228.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |110.0MiB|110.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |58.776MiB|58.776MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |177.0MiB|177.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |85.26MiB|85.26MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |225.0MiB|225.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |67.22MiB|67.22MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |70.336MiB|70.336MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |151.0MiB|151.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |129.0MiB|129.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |79.42MiB|79.42MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |1861.0MiB|1861.0MiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |88.02MiB|88.02MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |419.0MiB|419.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |82.232MiB|82.232MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |223.0MiB|223.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |159.0MiB|159.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |465.0MiB|465.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |57.664MiB|57.664MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |228.0MiB|228.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |110.0MiB|110.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |58.776MiB|58.776MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |177.0MiB|177.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |85.26MiB|85.26MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |225.0MiB|225.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |67.22MiB|67.22MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |70.336MiB|70.336MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |151.0MiB|151.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |129.0MiB|129.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |79.42MiB|79.42MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |1861.0MiB|1861.0MiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |88.02MiB|88.02MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |419.0MiB|419.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |82.232MiB|82.232MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |223.0MiB|223.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |159.0MiB|159.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |465.0MiB|465.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |57.664MiB|57.664MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |228.0MiB|228.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |110.0MiB|110.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |58.776MiB|58.776MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |177.0MiB|177.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |85.26MiB|85.26MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |225.0MiB|225.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |67.22MiB|67.22MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |70.336MiB|70.336MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |151.0MiB|151.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |129.0MiB|129.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |79.42MiB|79.42MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |1861.0MiB|1861.0MiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |88.02MiB|88.02MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |419.0MiB|419.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |82.232MiB|82.232MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |223.0MiB|223.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |159.0MiB|159.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |465.0MiB|465.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |57.664MiB|57.664MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |228.0MiB|228.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |110.0MiB|110.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |58.776MiB|58.776MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |177.0MiB|177.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |85.26MiB|85.26MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |225.0MiB|225.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |67.22MiB|67.22MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |70.336MiB|70.336MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |151.0MiB|151.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |129.0MiB|129.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |79.42MiB|79.42MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |1861.0MiB|1861.0MiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |88.02MiB|88.02MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |419.0MiB|419.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1200.169s |1861.0MiB|
|scrambled116992.smt2                                                                       |1083.915s |465.0MiB|
|scrambled35345.smt2                                                                        |1200.053s |419.0MiB|
|scrambled75206.smt2                                                                        | 963.731s |300.0MiB|
|scrambled23483.smt2                                                                        |1200.058s |253.0MiB|
|scrambled41773.smt2                                                                        |1200.055s |240.0MiB|
|scrambled119992.smt2                                                                       |1200.056s |228.0MiB|
|scrambled1379.smt2                                                                         | 891.226s |225.0MiB|
|scrambled62859.smt2                                                                        |1200.049s |224.0MiB|
|scrambled103851.smt2                                                                       |1200.028s |223.0MiB|
|scrambled92133.smt2                                                                        |1200.050s |221.0MiB|
|scrambled124624.smt2                                                                       |1200.035s |177.0MiB|
|scrambled109208.smt2                                                                       |1200.047s |159.0MiB|
|scrambled15284.smt2                                                                        |1200.030s |151.0MiB|
|scrambled15552.smt2                                                                        |1200.031s |129.0MiB|
|scrambled38610.smt2                                                                        |1200.040s |120.0MiB|
|scrambled97138.smt2                                                                        |1200.040s |119.0MiB|
|scrambled42287.smt2                                                                        |1200.038s |119.0MiB|
|scrambled62810.smt2                                                                        |1200.022s |118.0MiB|
|scrambled41801.smt2                                                                        |1200.040s |117.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1200.169s |1861.0MiB|
|scrambled116992.smt2                                                                       |1083.915s |465.0MiB|
|scrambled35345.smt2                                                                        |1200.053s |419.0MiB|
|scrambled75206.smt2                                                                        | 963.731s |300.0MiB|
|scrambled23483.smt2                                                                        |1200.058s |253.0MiB|
|scrambled41773.smt2                                                                        |1200.055s |240.0MiB|
|scrambled119992.smt2                                                                       |1200.056s |228.0MiB|
|scrambled1379.smt2                                                                         | 891.226s |225.0MiB|
|scrambled62859.smt2                                                                        |1200.049s |224.0MiB|
|scrambled103851.smt2                                                                       |1200.028s |223.0MiB|
|scrambled92133.smt2                                                                        |1200.050s |221.0MiB|
|scrambled124624.smt2                                                                       |1200.035s |177.0MiB|
|scrambled109208.smt2                                                                       |1200.047s |159.0MiB|
|scrambled15284.smt2                                                                        |1200.030s |151.0MiB|
|scrambled15552.smt2                                                                        |1200.031s |129.0MiB|
|scrambled38610.smt2                                                                        |1200.040s |120.0MiB|
|scrambled97138.smt2                                                                        |1200.040s |119.0MiB|
|scrambled42287.smt2                                                                        |1200.038s |119.0MiB|
|scrambled62810.smt2                                                                        |1200.022s |118.0MiB|
|scrambled41801.smt2                                                                        |1200.040s |117.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1083.915s  |1083.915s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        | 462.955s  | 462.955s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          | 891.226s  | 891.226s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled38610.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled41312.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled41773.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled41801.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled42287.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled4441.smt2                                                                          | 687.239s  | 687.239s  |   0.000s  | 0.0%|
|scrambled54073.smt2                                                                         | 206.030s  | 206.030s  |   0.000s  | 0.0%|
|scrambled58720.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled62536.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled62810.smt2                                                                         |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled62859.smt2                                                                         |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled6373.smt2                                                                          |1147.422s  |1147.422s  |   0.000s  | 0.0%|
|scrambled75206.smt2                                                                         | 963.731s  | 963.731s  |   0.000s  | 0.0%|
|scrambled78432.smt2                                                                         | 286.496s  | 286.496s  |   0.000s  | 0.0%|
|scrambled78606.smt2                                                                         | 154.361s  | 154.361s  |   0.000s  | 0.0%|
|scrambled79181.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled82743.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled89071.smt2                                                                         | 214.908s  | 214.908s  |   0.000s  | 0.0%|
|scrambled90733.smt2                                                                         | 624.128s  | 624.128s  |   0.000s  | 0.0%|
|scrambled92133.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled96514.smt2                                                                         | 345.078s  | 345.078s  |   0.000s  | 0.0%|
|scrambled96733.smt2                                                                         |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled97138.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled98799.smt2                                                                         | 460.417s  | 460.417s  |   0.000s  | 0.0%|
</details>
