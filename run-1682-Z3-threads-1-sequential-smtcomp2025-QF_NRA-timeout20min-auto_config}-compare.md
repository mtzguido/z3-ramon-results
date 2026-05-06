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
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_NRA-timeout20min-auto_config}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NRA
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_NRA-timeout20min-auto_config}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NRA
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1200.186s  |1200.186s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   5.838s  |   5.838s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.012s  |1200.012s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   6.158s  |   6.158s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1200.186s  |1200.186s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   5.838s  |   5.838s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.012s  |1200.012s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   6.158s  |   6.158s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1200.186s  |1200.186s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   5.838s  |   5.838s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.012s  |1200.012s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   6.158s  |   6.158s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1200.186s  |1200.186s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   5.838s  |   5.838s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.012s  |1200.012s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   6.158s  |   6.158s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled65757.smt2                                                                        |1201.842s |21.546GiB|
|scrambled94319.smt2                                                                        |1200.267s |2643.0MiB|
|scrambled114923.smt2                                                                       |1200.186s |1907.0MiB|
|scrambled5797.smt2                                                                         |1200.173s |1799.0MiB|
|scrambled78428.smt2                                                                        |1200.110s |711.0MiB|
|scrambled61896.smt2                                                                        |1200.106s |709.0MiB|
|scrambled85895.smt2                                                                        |1200.101s |559.0MiB|
|scrambled6476.smt2                                                                         |1200.088s |969.0MiB|
|scrambled22492.smt2                                                                        |1200.087s |549.0MiB|
|scrambled91241.smt2                                                                        |1200.086s |742.0MiB|
|scrambled124828.smt2                                                                       |1200.082s |725.0MiB|
|scrambled121780.smt2                                                                       |1200.080s |974.0MiB|
|scrambled32701.smt2                                                                        |1200.077s |321.0MiB|
|scrambled70990.smt2                                                                        |1200.076s |494.0MiB|
|scrambled41575.smt2                                                                        |1200.075s |495.0MiB|
|scrambled27426.smt2                                                                        |1200.055s |753.0MiB|
|scrambled60239.smt2                                                                        |1200.051s |548.0MiB|
|scrambled94768.smt2                                                                        |1200.045s |27.292MiB|
|scrambled14016.smt2                                                                        |1200.045s |338.0MiB|
|scrambled21647.smt2                                                                        |1200.037s |33.368MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled65757.smt2                                                                        |1201.842s |21.546GiB|
|scrambled94319.smt2                                                                        |1200.267s |2643.0MiB|
|scrambled114923.smt2                                                                       |1200.186s |1907.0MiB|
|scrambled5797.smt2                                                                         |1200.173s |1799.0MiB|
|scrambled78428.smt2                                                                        |1200.110s |711.0MiB|
|scrambled61896.smt2                                                                        |1200.106s |709.0MiB|
|scrambled85895.smt2                                                                        |1200.101s |559.0MiB|
|scrambled6476.smt2                                                                         |1200.088s |969.0MiB|
|scrambled22492.smt2                                                                        |1200.087s |549.0MiB|
|scrambled91241.smt2                                                                        |1200.086s |742.0MiB|
|scrambled124828.smt2                                                                       |1200.082s |725.0MiB|
|scrambled121780.smt2                                                                       |1200.080s |974.0MiB|
|scrambled32701.smt2                                                                        |1200.077s |321.0MiB|
|scrambled70990.smt2                                                                        |1200.076s |494.0MiB|
|scrambled41575.smt2                                                                        |1200.075s |495.0MiB|
|scrambled27426.smt2                                                                        |1200.055s |753.0MiB|
|scrambled60239.smt2                                                                        |1200.051s |548.0MiB|
|scrambled94768.smt2                                                                        |1200.045s |27.292MiB|
|scrambled14016.smt2                                                                        |1200.045s |338.0MiB|
|scrambled21647.smt2                                                                        |1200.037s |33.368MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |33.128MiB|33.128MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |31.636MiB|31.636MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |33.652MiB|33.652MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |1907.0MiB|1907.0MiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |34.06MiB|34.06MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |31.38MiB|31.38MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |42.504MiB|42.504MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |974.0MiB|974.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |725.0MiB|725.0MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |338.0MiB|338.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |25.904MiB|25.904MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |28.832MiB|28.832MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |33.1MiB|33.1MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |33.368MiB|33.368MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |549.0MiB|549.0MiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |753.0MiB|753.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |29.148MiB|29.148MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |28.352MiB|28.352MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |27.788MiB|27.788MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |321.0MiB|321.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |33.128MiB|33.128MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |31.636MiB|31.636MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |33.652MiB|33.652MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |1907.0MiB|1907.0MiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |34.06MiB|34.06MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |31.38MiB|31.38MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |42.504MiB|42.504MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |974.0MiB|974.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |725.0MiB|725.0MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |338.0MiB|338.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |25.904MiB|25.904MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |28.832MiB|28.832MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |33.1MiB|33.1MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |33.368MiB|33.368MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |549.0MiB|549.0MiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |753.0MiB|753.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |29.148MiB|29.148MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |28.352MiB|28.352MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |27.788MiB|27.788MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |321.0MiB|321.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |33.128MiB|33.128MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |31.636MiB|31.636MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |33.652MiB|33.652MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |1907.0MiB|1907.0MiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |34.06MiB|34.06MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |31.38MiB|31.38MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |42.504MiB|42.504MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |974.0MiB|974.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |725.0MiB|725.0MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |338.0MiB|338.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |25.904MiB|25.904MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |28.832MiB|28.832MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |33.1MiB|33.1MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |33.368MiB|33.368MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |549.0MiB|549.0MiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |753.0MiB|753.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |29.148MiB|29.148MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |28.352MiB|28.352MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |27.788MiB|27.788MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |321.0MiB|321.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |33.128MiB|33.128MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |31.636MiB|31.636MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |33.652MiB|33.652MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |1907.0MiB|1907.0MiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |34.06MiB|34.06MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |31.38MiB|31.38MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |42.504MiB|42.504MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |974.0MiB|974.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |725.0MiB|725.0MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |338.0MiB|338.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |25.904MiB|25.904MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |28.832MiB|28.832MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |33.1MiB|33.1MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |33.368MiB|33.368MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |549.0MiB|549.0MiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |753.0MiB|753.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |29.148MiB|29.148MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |28.352MiB|28.352MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |27.788MiB|27.788MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |321.0MiB|321.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled65757.smt2                                                                        |1201.842s |21.546GiB|
|scrambled94319.smt2                                                                        |1200.267s |2643.0MiB|
|scrambled114923.smt2                                                                       |1200.186s |1907.0MiB|
|scrambled5797.smt2                                                                         |1200.173s |1799.0MiB|
|scrambled121780.smt2                                                                       |1200.080s |974.0MiB|
|scrambled6476.smt2                                                                         |1200.088s |969.0MiB|
|scrambled27426.smt2                                                                        |1200.055s |753.0MiB|
|scrambled91241.smt2                                                                        |1200.086s |742.0MiB|
|scrambled124828.smt2                                                                       |1200.082s |725.0MiB|
|scrambled78428.smt2                                                                        |1200.110s |711.0MiB|
|scrambled61896.smt2                                                                        |1200.106s |709.0MiB|
|scrambled85895.smt2                                                                        |1200.101s |559.0MiB|
|scrambled22492.smt2                                                                        |1200.087s |549.0MiB|
|scrambled60239.smt2                                                                        |1200.051s |548.0MiB|
|scrambled41575.smt2                                                                        |1200.075s |495.0MiB|
|scrambled70990.smt2                                                                        |1200.076s |494.0MiB|
|scrambled14016.smt2                                                                        |1200.045s |338.0MiB|
|scrambled32701.smt2                                                                        |1200.077s |321.0MiB|
|scrambled58292.smt2                                                                        |1200.018s |43.344MiB|
|scrambled118224.smt2                                                                       |1200.015s |42.504MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled65757.smt2                                                                        |1201.842s |21.546GiB|
|scrambled94319.smt2                                                                        |1200.267s |2643.0MiB|
|scrambled114923.smt2                                                                       |1200.186s |1907.0MiB|
|scrambled5797.smt2                                                                         |1200.173s |1799.0MiB|
|scrambled121780.smt2                                                                       |1200.080s |974.0MiB|
|scrambled6476.smt2                                                                         |1200.088s |969.0MiB|
|scrambled27426.smt2                                                                        |1200.055s |753.0MiB|
|scrambled91241.smt2                                                                        |1200.086s |742.0MiB|
|scrambled124828.smt2                                                                       |1200.082s |725.0MiB|
|scrambled78428.smt2                                                                        |1200.110s |711.0MiB|
|scrambled61896.smt2                                                                        |1200.106s |709.0MiB|
|scrambled85895.smt2                                                                        |1200.101s |559.0MiB|
|scrambled22492.smt2                                                                        |1200.087s |549.0MiB|
|scrambled60239.smt2                                                                        |1200.051s |548.0MiB|
|scrambled41575.smt2                                                                        |1200.075s |495.0MiB|
|scrambled70990.smt2                                                                        |1200.076s |494.0MiB|
|scrambled14016.smt2                                                                        |1200.045s |338.0MiB|
|scrambled32701.smt2                                                                        |1200.077s |321.0MiB|
|scrambled58292.smt2                                                                        |1200.018s |43.344MiB|
|scrambled118224.smt2                                                                       |1200.015s |42.504MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1200.186s  |1200.186s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   5.838s  |   5.838s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.012s  |1200.012s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   6.158s  |   6.158s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled34121.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled36539.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled41575.smt2                                                                         |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled42946.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled54263.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled5797.smt2                                                                          |1200.173s  |1200.173s  |   0.000s  | 0.0%|
|scrambled58292.smt2                                                                         |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled60239.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled61896.smt2                                                                         |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled6476.smt2                                                                          |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled65757.smt2                                                                         |1201.842s  |1201.842s  |   0.000s  | 0.0%|
|scrambled70990.smt2                                                                         |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled73220.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled74869.smt2                                                                         |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled7586.smt2                                                                          |1200.012s  |1200.012s  |   0.000s  | 0.0%|
|scrambled78428.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled7923.smt2                                                                          |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled80728.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled82241.smt2                                                                         |1200.012s  |1200.012s  |   0.000s  | 0.0%|
|scrambled85895.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled91241.smt2                                                                         |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled94319.smt2                                                                         |1200.267s  |1200.267s  |   0.000s  | 0.0%|
|scrambled94768.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
</details>
