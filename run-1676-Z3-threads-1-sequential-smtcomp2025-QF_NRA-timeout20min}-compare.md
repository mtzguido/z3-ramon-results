Comparing data and data


# SUMMARY
- LHS tests = 44
- RHS tests = 44
- LHS success = 44  (100.0%)
- RHS success = 44  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_NRA-timeout20min}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NRA
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_NRA-timeout20min}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NRA
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1200.496s  |1200.496s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   9.803s  |   9.803s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.021s  |1200.021s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1200.496s  |1200.496s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   9.803s  |   9.803s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.021s  |1200.021s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1200.496s  |1200.496s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   9.803s  |   9.803s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.021s  |1200.021s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1200.496s  |1200.496s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   9.803s  |   9.803s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.021s  |1200.021s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled114923.smt2                                                                       |1200.496s |2703.0MiB|
|scrambled5797.smt2                                                                         |1200.316s |1787.0MiB|
|scrambled14016.smt2                                                                        |1200.180s |874.0MiB|
|scrambled61896.smt2                                                                        |1200.164s |710.0MiB|
|scrambled36539.smt2                                                                        |1200.151s |681.0MiB|
|scrambled60239.smt2                                                                        |1200.129s |548.0MiB|
|scrambled121780.smt2                                                                       |1200.120s |974.0MiB|
|scrambled78428.smt2                                                                        |1200.110s |711.0MiB|
|scrambled65757.smt2                                                                        |1200.103s |707.0MiB|
|scrambled6476.smt2                                                                         |1200.098s |969.0MiB|
|scrambled70990.smt2                                                                        |1200.097s |494.0MiB|
|scrambled85895.smt2                                                                        |1200.091s |410.0MiB|
|scrambled91241.smt2                                                                        |1200.091s |742.0MiB|
|scrambled41575.smt2                                                                        |1200.087s |495.0MiB|
|scrambled27426.smt2                                                                        |1200.056s |753.0MiB|
|scrambled94768.smt2                                                                        |1200.052s |365.0MiB|
|scrambled32701.smt2                                                                        |1200.043s |128.0MiB|
|scrambled118224.smt2                                                                       |1200.041s |57.928MiB|
|scrambled21647.smt2                                                                        |1200.040s |56.296MiB|
|scrambled22492.smt2                                                                        |1200.038s |49.788MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled114923.smt2                                                                       |1200.496s |2703.0MiB|
|scrambled5797.smt2                                                                         |1200.316s |1787.0MiB|
|scrambled14016.smt2                                                                        |1200.180s |874.0MiB|
|scrambled61896.smt2                                                                        |1200.164s |710.0MiB|
|scrambled36539.smt2                                                                        |1200.151s |681.0MiB|
|scrambled60239.smt2                                                                        |1200.129s |548.0MiB|
|scrambled121780.smt2                                                                       |1200.120s |974.0MiB|
|scrambled78428.smt2                                                                        |1200.110s |711.0MiB|
|scrambled65757.smt2                                                                        |1200.103s |707.0MiB|
|scrambled6476.smt2                                                                         |1200.098s |969.0MiB|
|scrambled70990.smt2                                                                        |1200.097s |494.0MiB|
|scrambled85895.smt2                                                                        |1200.091s |410.0MiB|
|scrambled91241.smt2                                                                        |1200.091s |742.0MiB|
|scrambled41575.smt2                                                                        |1200.087s |495.0MiB|
|scrambled27426.smt2                                                                        |1200.056s |753.0MiB|
|scrambled94768.smt2                                                                        |1200.052s |365.0MiB|
|scrambled32701.smt2                                                                        |1200.043s |128.0MiB|
|scrambled118224.smt2                                                                       |1200.041s |57.928MiB|
|scrambled21647.smt2                                                                        |1200.040s |56.296MiB|
|scrambled22492.smt2                                                                        |1200.038s |49.788MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |30.808MiB|30.808MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |28.34MiB|28.34MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |36.66MiB|36.66MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |2703.0MiB|2703.0MiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |57.172MiB|57.172MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |29.012MiB|29.012MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |57.928MiB|57.928MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |974.0MiB|974.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |43.828MiB|43.828MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |874.0MiB|874.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |26.768MiB|26.768MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |30.436MiB|30.436MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |31.436MiB|31.436MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |56.296MiB|56.296MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |49.788MiB|49.788MiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |753.0MiB|753.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |31.32MiB|31.32MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |30.5MiB|30.5MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |27.148MiB|27.148MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |128.0MiB|128.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |30.808MiB|30.808MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |28.34MiB|28.34MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |36.66MiB|36.66MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |2703.0MiB|2703.0MiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |57.172MiB|57.172MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |29.012MiB|29.012MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |57.928MiB|57.928MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |974.0MiB|974.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |43.828MiB|43.828MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |874.0MiB|874.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |26.768MiB|26.768MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |30.436MiB|30.436MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |31.436MiB|31.436MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |56.296MiB|56.296MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |49.788MiB|49.788MiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |753.0MiB|753.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |31.32MiB|31.32MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |30.5MiB|30.5MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |27.148MiB|27.148MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |128.0MiB|128.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |30.808MiB|30.808MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |28.34MiB|28.34MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |36.66MiB|36.66MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |2703.0MiB|2703.0MiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |57.172MiB|57.172MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |29.012MiB|29.012MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |57.928MiB|57.928MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |974.0MiB|974.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |43.828MiB|43.828MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |874.0MiB|874.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |26.768MiB|26.768MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |30.436MiB|30.436MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |31.436MiB|31.436MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |56.296MiB|56.296MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |49.788MiB|49.788MiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |753.0MiB|753.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |31.32MiB|31.32MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |30.5MiB|30.5MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |27.148MiB|27.148MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |128.0MiB|128.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |30.808MiB|30.808MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |28.34MiB|28.34MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |36.66MiB|36.66MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |2703.0MiB|2703.0MiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |57.172MiB|57.172MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |29.012MiB|29.012MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |57.928MiB|57.928MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |974.0MiB|974.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |43.828MiB|43.828MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |874.0MiB|874.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |26.768MiB|26.768MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |30.436MiB|30.436MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |31.436MiB|31.436MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |56.296MiB|56.296MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |49.788MiB|49.788MiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |753.0MiB|753.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |31.32MiB|31.32MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |30.5MiB|30.5MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |27.148MiB|27.148MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |128.0MiB|128.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled114923.smt2                                                                       |1200.496s |2703.0MiB|
|scrambled5797.smt2                                                                         |1200.316s |1787.0MiB|
|scrambled121780.smt2                                                                       |1200.120s |974.0MiB|
|scrambled6476.smt2                                                                         |1200.098s |969.0MiB|
|scrambled14016.smt2                                                                        |1200.180s |874.0MiB|
|scrambled27426.smt2                                                                        |1200.056s |753.0MiB|
|scrambled91241.smt2                                                                        |1200.091s |742.0MiB|
|scrambled78428.smt2                                                                        |1200.110s |711.0MiB|
|scrambled61896.smt2                                                                        |1200.164s |710.0MiB|
|scrambled65757.smt2                                                                        |1200.103s |707.0MiB|
|scrambled36539.smt2                                                                        |1200.151s |681.0MiB|
|scrambled60239.smt2                                                                        |1200.129s |548.0MiB|
|scrambled41575.smt2                                                                        |1200.087s |495.0MiB|
|scrambled70990.smt2                                                                        |1200.097s |494.0MiB|
|scrambled85895.smt2                                                                        |1200.091s |410.0MiB|
|scrambled94768.smt2                                                                        |1200.052s |365.0MiB|
|scrambled32701.smt2                                                                        |1200.043s |128.0MiB|
|scrambled118224.smt2                                                                       |1200.041s |57.928MiB|
|scrambled117334.smt2                                                                       |1200.034s |57.172MiB|
|scrambled21647.smt2                                                                        |1200.040s |56.296MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled114923.smt2                                                                       |1200.496s |2703.0MiB|
|scrambled5797.smt2                                                                         |1200.316s |1787.0MiB|
|scrambled121780.smt2                                                                       |1200.120s |974.0MiB|
|scrambled6476.smt2                                                                         |1200.098s |969.0MiB|
|scrambled14016.smt2                                                                        |1200.180s |874.0MiB|
|scrambled27426.smt2                                                                        |1200.056s |753.0MiB|
|scrambled91241.smt2                                                                        |1200.091s |742.0MiB|
|scrambled78428.smt2                                                                        |1200.110s |711.0MiB|
|scrambled61896.smt2                                                                        |1200.164s |710.0MiB|
|scrambled65757.smt2                                                                        |1200.103s |707.0MiB|
|scrambled36539.smt2                                                                        |1200.151s |681.0MiB|
|scrambled60239.smt2                                                                        |1200.129s |548.0MiB|
|scrambled41575.smt2                                                                        |1200.087s |495.0MiB|
|scrambled70990.smt2                                                                        |1200.097s |494.0MiB|
|scrambled85895.smt2                                                                        |1200.091s |410.0MiB|
|scrambled94768.smt2                                                                        |1200.052s |365.0MiB|
|scrambled32701.smt2                                                                        |1200.043s |128.0MiB|
|scrambled118224.smt2                                                                       |1200.041s |57.928MiB|
|scrambled117334.smt2                                                                       |1200.034s |57.172MiB|
|scrambled21647.smt2                                                                        |1200.040s |56.296MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1200.496s  |1200.496s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   9.803s  |   9.803s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.021s  |1200.021s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled34121.smt2                                                                         |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled36539.smt2                                                                         |1200.151s  |1200.151s  |   0.000s  | 0.0%|
|scrambled41575.smt2                                                                         |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled42946.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled54263.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled5797.smt2                                                                          |1200.316s  |1200.316s  |   0.000s  | 0.0%|
|scrambled58292.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled60239.smt2                                                                         |1200.129s  |1200.129s  |   0.000s  | 0.0%|
|scrambled61896.smt2                                                                         |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled6476.smt2                                                                          |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled65757.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled70990.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled73220.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled74869.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled7586.smt2                                                                          |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled78428.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled7923.smt2                                                                          |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled80728.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled82241.smt2                                                                         |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled85895.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled91241.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled94319.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled94768.smt2                                                                         |1200.052s  |1200.052s  |   0.000s  | 0.0%|
</details>
