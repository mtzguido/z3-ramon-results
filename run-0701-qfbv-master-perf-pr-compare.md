Comparing data and data


# SUMMARY
- LHS tests = 29
- RHS tests = 29
- LHS success = 26  (89.65517241379311%)
- RHS success = 26  (89.65517241379311%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: qfbv-master-perf-pr
Runner: guido
Z3 repo: Z3Prover/z3
Z3 commit: 7ec980f6f8a802c8df97715fc8d0edc1deb1d960
Z3 branch: daily-perf-improver-626c8de5af64f883
Z3 options: "-T:30"
Z3 inputs: inputs/QF_BV_small
Z3 commit message: staged files

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: qfbv-master-perf-pr
Runner: guido
Z3 repo: Z3Prover/z3
Z3 commit: 7ec980f6f8a802c8df97715fc8d0edc1deb1d960
Z3 branch: daily-perf-improver-626c8de5af64f883
Z3 options: "-T:30"
Z3 inputs: inputs/QF_BV_small
Z3 commit message: staged files

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |   2.091s  |   2.091s  |   0.000s  | 0.0%|
|bench0.smt2                                                                                 |  30.475s  |  30.475s  |   0.000s  | 0.0%|
|bench0_check.smt2                                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench0_simplified.smt2                                                                      |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|bench1.smt2                                                                                 |  30.463s  |  30.463s  |   0.000s  | 0.0%|
|bench11.smt2                                                                                |   4.237s  |   4.237s  |   0.000s  | 0.0%|
|bench13.smt2                                                                                |  30.436s  |  30.436s  |   0.000s  | 0.0%|
|bench1_bw1024.smt2                                                                          |  30.419s  |  30.419s  |   0.000s  | 0.0%|
|bench1_bw256.smt2                                                                           |  30.443s  |  30.443s  |   0.000s  | 0.0%|
|bench1_bw300.smt2                                                                           |  30.397s  |  30.397s  |   0.000s  | 0.0%|
|bench1_bw512.smt2                                                                           |  30.449s  |  30.449s  |   0.000s  | 0.0%|
|bench1_bw64.smt2                                                                            |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|bench1_check.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench2.smt2                                                                                 |  30.228s  |  30.228s  |   0.000s  | 0.0%|
|bench23.smt2                                                                                |  30.370s  |  30.370s  |   0.000s  | 0.0%|
|bench25_core.smt2                                                                           |  30.008s  |  30.008s  |   0.000s  | 0.0%|
|bench27.smt2                                                                                |  30.385s  |  30.385s  |   0.000s  | 0.0%|
|bench3.smt2                                                                                 |  30.286s  |  30.286s  |   0.000s  | 0.0%|
|bench31.smt2                                                                                |  30.412s  |  30.412s  |   0.000s  | 0.0%|
|bench5.smt2                                                                                 |   3.406s  |   3.406s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |   2.091s  |   2.091s  |   0.000s  | 0.0%|
|bench0.smt2                                                                                 |  30.475s  |  30.475s  |   0.000s  | 0.0%|
|bench0_check.smt2                                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench0_simplified.smt2                                                                      |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|bench1.smt2                                                                                 |  30.463s  |  30.463s  |   0.000s  | 0.0%|
|bench11.smt2                                                                                |   4.237s  |   4.237s  |   0.000s  | 0.0%|
|bench13.smt2                                                                                |  30.436s  |  30.436s  |   0.000s  | 0.0%|
|bench1_bw1024.smt2                                                                          |  30.419s  |  30.419s  |   0.000s  | 0.0%|
|bench1_bw256.smt2                                                                           |  30.443s  |  30.443s  |   0.000s  | 0.0%|
|bench1_bw300.smt2                                                                           |  30.397s  |  30.397s  |   0.000s  | 0.0%|
|bench1_bw512.smt2                                                                           |  30.449s  |  30.449s  |   0.000s  | 0.0%|
|bench1_bw64.smt2                                                                            |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|bench1_check.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench2.smt2                                                                                 |  30.228s  |  30.228s  |   0.000s  | 0.0%|
|bench23.smt2                                                                                |  30.370s  |  30.370s  |   0.000s  | 0.0%|
|bench25_core.smt2                                                                           |  30.008s  |  30.008s  |   0.000s  | 0.0%|
|bench27.smt2                                                                                |  30.385s  |  30.385s  |   0.000s  | 0.0%|
|bench3.smt2                                                                                 |  30.286s  |  30.286s  |   0.000s  | 0.0%|
|bench31.smt2                                                                                |  30.412s  |  30.412s  |   0.000s  | 0.0%|
|bench5.smt2                                                                                 |   3.406s  |   3.406s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |   2.091s  |   2.091s  |   0.000s  | 0.0%|
|bench0.smt2                                                                                 |  30.475s  |  30.475s  |   0.000s  | 0.0%|
|bench0_check.smt2                                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench0_simplified.smt2                                                                      |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|bench1.smt2                                                                                 |  30.463s  |  30.463s  |   0.000s  | 0.0%|
|bench11.smt2                                                                                |   4.237s  |   4.237s  |   0.000s  | 0.0%|
|bench13.smt2                                                                                |  30.436s  |  30.436s  |   0.000s  | 0.0%|
|bench1_bw1024.smt2                                                                          |  30.419s  |  30.419s  |   0.000s  | 0.0%|
|bench1_bw256.smt2                                                                           |  30.443s  |  30.443s  |   0.000s  | 0.0%|
|bench1_bw300.smt2                                                                           |  30.397s  |  30.397s  |   0.000s  | 0.0%|
|bench1_bw512.smt2                                                                           |  30.449s  |  30.449s  |   0.000s  | 0.0%|
|bench1_bw64.smt2                                                                            |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|bench1_check.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench2.smt2                                                                                 |  30.228s  |  30.228s  |   0.000s  | 0.0%|
|bench23.smt2                                                                                |  30.370s  |  30.370s  |   0.000s  | 0.0%|
|bench25_core.smt2                                                                           |  30.008s  |  30.008s  |   0.000s  | 0.0%|
|bench27.smt2                                                                                |  30.385s  |  30.385s  |   0.000s  | 0.0%|
|bench3.smt2                                                                                 |  30.286s  |  30.286s  |   0.000s  | 0.0%|
|bench31.smt2                                                                                |  30.412s  |  30.412s  |   0.000s  | 0.0%|
|bench5.smt2                                                                                 |   3.406s  |   3.406s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |   2.091s  |   2.091s  |   0.000s  | 0.0%|
|bench0.smt2                                                                                 |  30.475s  |  30.475s  |   0.000s  | 0.0%|
|bench0_check.smt2                                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench0_simplified.smt2                                                                      |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|bench1.smt2                                                                                 |  30.463s  |  30.463s  |   0.000s  | 0.0%|
|bench11.smt2                                                                                |   4.237s  |   4.237s  |   0.000s  | 0.0%|
|bench13.smt2                                                                                |  30.436s  |  30.436s  |   0.000s  | 0.0%|
|bench1_bw1024.smt2                                                                          |  30.419s  |  30.419s  |   0.000s  | 0.0%|
|bench1_bw256.smt2                                                                           |  30.443s  |  30.443s  |   0.000s  | 0.0%|
|bench1_bw300.smt2                                                                           |  30.397s  |  30.397s  |   0.000s  | 0.0%|
|bench1_bw512.smt2                                                                           |  30.449s  |  30.449s  |   0.000s  | 0.0%|
|bench1_bw64.smt2                                                                            |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|bench1_check.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench2.smt2                                                                                 |  30.228s  |  30.228s  |   0.000s  | 0.0%|
|bench23.smt2                                                                                |  30.370s  |  30.370s  |   0.000s  | 0.0%|
|bench25_core.smt2                                                                           |  30.008s  |  30.008s  |   0.000s  | 0.0%|
|bench27.smt2                                                                                |  30.385s  |  30.385s  |   0.000s  | 0.0%|
|bench3.smt2                                                                                 |  30.286s  |  30.286s  |   0.000s  | 0.0%|
|bench31.smt2                                                                                |  30.412s  |  30.412s  |   0.000s  | 0.0%|
|bench5.smt2                                                                                 |   3.406s  |   3.406s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench0.smt2                                                                                |  30.475s |6410.0MiB|
|bench1.smt2                                                                                |  30.463s |6411.0MiB|
|bench1_bw512.smt2                                                                          |  30.449s |6426.0MiB|
|bench1_bw256.smt2                                                                          |  30.443s |6410.0MiB|
|bench13.smt2                                                                               |  30.436s |6379.0MiB|
|bench1_bw1024.smt2                                                                         |  30.419s |6622.0MiB|
|bench31.smt2                                                                               |  30.412s |6389.0MiB|
|bench1_bw300.smt2                                                                          |  30.397s |6430.0MiB|
|bench27.smt2                                                                               |  30.385s |3644.0MiB|
|bench23.smt2                                                                               |  30.370s |3630.0MiB|
|bench6.smt2                                                                                |  30.352s |6235.0MiB|
|bench3.smt2                                                                                |  30.286s |5762.0MiB|
|bench2.smt2                                                                                |  30.228s |5885.0MiB|
|bench0_simplified.smt2                                                                     |  30.093s |767.0MiB|
|bench1_bw64.smt2                                                                           |  30.044s |849.0MiB|
|bench_4153.smt2                                                                            |  30.023s |139.0MiB|
|bench25_core.smt2                                                                          |  30.008s |43.776MiB|
|bench15.smt2                                                                               |  26.783s |6460.0MiB|
|bench1_bw8192.smt2                                                                         |  21.456s |7264.0MiB|
|bench25.smt2                                                                               |  17.847s |12.8GiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench0.smt2                                                                                |  30.475s |6410.0MiB|
|bench1.smt2                                                                                |  30.463s |6411.0MiB|
|bench1_bw512.smt2                                                                          |  30.449s |6426.0MiB|
|bench1_bw256.smt2                                                                          |  30.443s |6410.0MiB|
|bench13.smt2                                                                               |  30.436s |6379.0MiB|
|bench1_bw1024.smt2                                                                         |  30.419s |6622.0MiB|
|bench31.smt2                                                                               |  30.412s |6389.0MiB|
|bench1_bw300.smt2                                                                          |  30.397s |6430.0MiB|
|bench27.smt2                                                                               |  30.385s |3644.0MiB|
|bench23.smt2                                                                               |  30.370s |3630.0MiB|
|bench6.smt2                                                                                |  30.352s |6235.0MiB|
|bench3.smt2                                                                                |  30.286s |5762.0MiB|
|bench2.smt2                                                                                |  30.228s |5885.0MiB|
|bench0_simplified.smt2                                                                     |  30.093s |767.0MiB|
|bench1_bw64.smt2                                                                           |  30.044s |849.0MiB|
|bench_4153.smt2                                                                            |  30.023s |139.0MiB|
|bench25_core.smt2                                                                          |  30.008s |43.776MiB|
|bench15.smt2                                                                               |  26.783s |6460.0MiB|
|bench1_bw8192.smt2                                                                         |  21.456s |7264.0MiB|
|bench25.smt2                                                                               |  17.847s |12.8GiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |30.852MiB|30.852MiB|0B| 0.0%|
|bench0.smt2                                                                                 |6410.0MiB|6410.0MiB|0B| 0.0%|
|bench0_check.smt2                                                                           |18.632MiB|18.632MiB|0B| 0.0%|
|bench0_simplified.smt2                                                                      |767.0MiB|767.0MiB|0B| 0.0%|
|bench1.smt2                                                                                 |6411.0MiB|6411.0MiB|0B| 0.0%|
|bench11.smt2                                                                                |1705.0MiB|1705.0MiB|0B| 0.0%|
|bench13.smt2                                                                                |6379.0MiB|6379.0MiB|0B| 0.0%|
|bench1_bw1024.smt2                                                                          |6622.0MiB|6622.0MiB|0B| 0.0%|
|bench1_bw256.smt2                                                                           |6410.0MiB|6410.0MiB|0B| 0.0%|
|bench1_bw300.smt2                                                                           |6430.0MiB|6430.0MiB|0B| 0.0%|
|bench1_bw512.smt2                                                                           |6426.0MiB|6426.0MiB|0B| 0.0%|
|bench1_bw64.smt2                                                                            |849.0MiB|849.0MiB|0B| 0.0%|
|bench1_check.smt2                                                                           |18.996MiB|18.996MiB|0B| 0.0%|
|bench2.smt2                                                                                 |5885.0MiB|5885.0MiB|0B| 0.0%|
|bench23.smt2                                                                                |3630.0MiB|3630.0MiB|0B| 0.0%|
|bench25_core.smt2                                                                           |43.776MiB|43.776MiB|0B| 0.0%|
|bench27.smt2                                                                                |3644.0MiB|3644.0MiB|0B| 0.0%|
|bench3.smt2                                                                                 |5762.0MiB|5762.0MiB|0B| 0.0%|
|bench31.smt2                                                                                |6389.0MiB|6389.0MiB|0B| 0.0%|
|bench5.smt2                                                                                 |1701.0MiB|1701.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |30.852MiB|30.852MiB|0B| 0.0%|
|bench0.smt2                                                                                 |6410.0MiB|6410.0MiB|0B| 0.0%|
|bench0_check.smt2                                                                           |18.632MiB|18.632MiB|0B| 0.0%|
|bench0_simplified.smt2                                                                      |767.0MiB|767.0MiB|0B| 0.0%|
|bench1.smt2                                                                                 |6411.0MiB|6411.0MiB|0B| 0.0%|
|bench11.smt2                                                                                |1705.0MiB|1705.0MiB|0B| 0.0%|
|bench13.smt2                                                                                |6379.0MiB|6379.0MiB|0B| 0.0%|
|bench1_bw1024.smt2                                                                          |6622.0MiB|6622.0MiB|0B| 0.0%|
|bench1_bw256.smt2                                                                           |6410.0MiB|6410.0MiB|0B| 0.0%|
|bench1_bw300.smt2                                                                           |6430.0MiB|6430.0MiB|0B| 0.0%|
|bench1_bw512.smt2                                                                           |6426.0MiB|6426.0MiB|0B| 0.0%|
|bench1_bw64.smt2                                                                            |849.0MiB|849.0MiB|0B| 0.0%|
|bench1_check.smt2                                                                           |18.996MiB|18.996MiB|0B| 0.0%|
|bench2.smt2                                                                                 |5885.0MiB|5885.0MiB|0B| 0.0%|
|bench23.smt2                                                                                |3630.0MiB|3630.0MiB|0B| 0.0%|
|bench25_core.smt2                                                                           |43.776MiB|43.776MiB|0B| 0.0%|
|bench27.smt2                                                                                |3644.0MiB|3644.0MiB|0B| 0.0%|
|bench3.smt2                                                                                 |5762.0MiB|5762.0MiB|0B| 0.0%|
|bench31.smt2                                                                                |6389.0MiB|6389.0MiB|0B| 0.0%|
|bench5.smt2                                                                                 |1701.0MiB|1701.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |30.852MiB|30.852MiB|0B| 0.0%|
|bench0.smt2                                                                                 |6410.0MiB|6410.0MiB|0B| 0.0%|
|bench0_check.smt2                                                                           |18.632MiB|18.632MiB|0B| 0.0%|
|bench0_simplified.smt2                                                                      |767.0MiB|767.0MiB|0B| 0.0%|
|bench1.smt2                                                                                 |6411.0MiB|6411.0MiB|0B| 0.0%|
|bench11.smt2                                                                                |1705.0MiB|1705.0MiB|0B| 0.0%|
|bench13.smt2                                                                                |6379.0MiB|6379.0MiB|0B| 0.0%|
|bench1_bw1024.smt2                                                                          |6622.0MiB|6622.0MiB|0B| 0.0%|
|bench1_bw256.smt2                                                                           |6410.0MiB|6410.0MiB|0B| 0.0%|
|bench1_bw300.smt2                                                                           |6430.0MiB|6430.0MiB|0B| 0.0%|
|bench1_bw512.smt2                                                                           |6426.0MiB|6426.0MiB|0B| 0.0%|
|bench1_bw64.smt2                                                                            |849.0MiB|849.0MiB|0B| 0.0%|
|bench1_check.smt2                                                                           |18.996MiB|18.996MiB|0B| 0.0%|
|bench2.smt2                                                                                 |5885.0MiB|5885.0MiB|0B| 0.0%|
|bench23.smt2                                                                                |3630.0MiB|3630.0MiB|0B| 0.0%|
|bench25_core.smt2                                                                           |43.776MiB|43.776MiB|0B| 0.0%|
|bench27.smt2                                                                                |3644.0MiB|3644.0MiB|0B| 0.0%|
|bench3.smt2                                                                                 |5762.0MiB|5762.0MiB|0B| 0.0%|
|bench31.smt2                                                                                |6389.0MiB|6389.0MiB|0B| 0.0%|
|bench5.smt2                                                                                 |1701.0MiB|1701.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |30.852MiB|30.852MiB|0B| 0.0%|
|bench0.smt2                                                                                 |6410.0MiB|6410.0MiB|0B| 0.0%|
|bench0_check.smt2                                                                           |18.632MiB|18.632MiB|0B| 0.0%|
|bench0_simplified.smt2                                                                      |767.0MiB|767.0MiB|0B| 0.0%|
|bench1.smt2                                                                                 |6411.0MiB|6411.0MiB|0B| 0.0%|
|bench11.smt2                                                                                |1705.0MiB|1705.0MiB|0B| 0.0%|
|bench13.smt2                                                                                |6379.0MiB|6379.0MiB|0B| 0.0%|
|bench1_bw1024.smt2                                                                          |6622.0MiB|6622.0MiB|0B| 0.0%|
|bench1_bw256.smt2                                                                           |6410.0MiB|6410.0MiB|0B| 0.0%|
|bench1_bw300.smt2                                                                           |6430.0MiB|6430.0MiB|0B| 0.0%|
|bench1_bw512.smt2                                                                           |6426.0MiB|6426.0MiB|0B| 0.0%|
|bench1_bw64.smt2                                                                            |849.0MiB|849.0MiB|0B| 0.0%|
|bench1_check.smt2                                                                           |18.996MiB|18.996MiB|0B| 0.0%|
|bench2.smt2                                                                                 |5885.0MiB|5885.0MiB|0B| 0.0%|
|bench23.smt2                                                                                |3630.0MiB|3630.0MiB|0B| 0.0%|
|bench25_core.smt2                                                                           |43.776MiB|43.776MiB|0B| 0.0%|
|bench27.smt2                                                                                |3644.0MiB|3644.0MiB|0B| 0.0%|
|bench3.smt2                                                                                 |5762.0MiB|5762.0MiB|0B| 0.0%|
|bench31.smt2                                                                                |6389.0MiB|6389.0MiB|0B| 0.0%|
|bench5.smt2                                                                                 |1701.0MiB|1701.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench25.smt2                                                                               |  17.847s |12.8GiB|
|bench1_bw8192.smt2                                                                         |  21.456s |7264.0MiB|
|bench1_bw1024.smt2                                                                         |  30.419s |6622.0MiB|
|bench15.smt2                                                                               |  26.783s |6460.0MiB|
|bench1_bw300.smt2                                                                          |  30.397s |6430.0MiB|
|bench1_bw512.smt2                                                                          |  30.449s |6426.0MiB|
|bench1.smt2                                                                                |  30.463s |6411.0MiB|
|bench0.smt2                                                                                |  30.475s |6410.0MiB|
|bench1_bw256.smt2                                                                          |  30.443s |6410.0MiB|
|bench31.smt2                                                                               |  30.412s |6389.0MiB|
|bench13.smt2                                                                               |  30.436s |6379.0MiB|
|bench6.smt2                                                                                |  30.352s |6235.0MiB|
|bench2.smt2                                                                                |  30.228s |5885.0MiB|
|bench3.smt2                                                                                |  30.286s |5762.0MiB|
|bench27.smt2                                                                               |  30.385s |3644.0MiB|
|bench23.smt2                                                                               |  30.370s |3630.0MiB|
|bench7.smt2                                                                                |   7.031s |1781.0MiB|
|bench11.smt2                                                                               |   4.237s |1705.0MiB|
|bench5.smt2                                                                                |   3.406s |1701.0MiB|
|bench1_bw64.smt2                                                                           |  30.044s |849.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench25.smt2                                                                               |  17.847s |12.8GiB|
|bench1_bw8192.smt2                                                                         |  21.456s |7264.0MiB|
|bench1_bw1024.smt2                                                                         |  30.419s |6622.0MiB|
|bench15.smt2                                                                               |  26.783s |6460.0MiB|
|bench1_bw300.smt2                                                                          |  30.397s |6430.0MiB|
|bench1_bw512.smt2                                                                          |  30.449s |6426.0MiB|
|bench1.smt2                                                                                |  30.463s |6411.0MiB|
|bench0.smt2                                                                                |  30.475s |6410.0MiB|
|bench1_bw256.smt2                                                                          |  30.443s |6410.0MiB|
|bench31.smt2                                                                               |  30.412s |6389.0MiB|
|bench13.smt2                                                                               |  30.436s |6379.0MiB|
|bench6.smt2                                                                                |  30.352s |6235.0MiB|
|bench2.smt2                                                                                |  30.228s |5885.0MiB|
|bench3.smt2                                                                                |  30.286s |5762.0MiB|
|bench27.smt2                                                                               |  30.385s |3644.0MiB|
|bench23.smt2                                                                               |  30.370s |3630.0MiB|
|bench7.smt2                                                                                |   7.031s |1781.0MiB|
|bench11.smt2                                                                               |   4.237s |1705.0MiB|
|bench5.smt2                                                                                |   3.406s |1701.0MiB|
|bench1_bw64.smt2                                                                           |  30.044s |849.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |   2.091s  |   2.091s  |   0.000s  | 0.0%|
|bench0.smt2                                                                                 |  30.475s  |  30.475s  |   0.000s  | 0.0%|
|bench0_check.smt2                                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench0_simplified.smt2                                                                      |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|bench1.smt2                                                                                 |  30.463s  |  30.463s  |   0.000s  | 0.0%|
|bench11.smt2                                                                                |   4.237s  |   4.237s  |   0.000s  | 0.0%|
|bench13.smt2                                                                                |  30.436s  |  30.436s  |   0.000s  | 0.0%|
|bench1_bw1024.smt2                                                                          |  30.419s  |  30.419s  |   0.000s  | 0.0%|
|bench1_bw256.smt2                                                                           |  30.443s  |  30.443s  |   0.000s  | 0.0%|
|bench1_bw300.smt2                                                                           |  30.397s  |  30.397s  |   0.000s  | 0.0%|
|bench1_bw512.smt2                                                                           |  30.449s  |  30.449s  |   0.000s  | 0.0%|
|bench1_bw64.smt2                                                                            |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|bench1_check.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench2.smt2                                                                                 |  30.228s  |  30.228s  |   0.000s  | 0.0%|
|bench23.smt2                                                                                |  30.370s  |  30.370s  |   0.000s  | 0.0%|
|bench25_core.smt2                                                                           |  30.008s  |  30.008s  |   0.000s  | 0.0%|
|bench27.smt2                                                                                |  30.385s  |  30.385s  |   0.000s  | 0.0%|
|bench3.smt2                                                                                 |  30.286s  |  30.286s  |   0.000s  | 0.0%|
|bench31.smt2                                                                                |  30.412s  |  30.412s  |   0.000s  | 0.0%|
|bench5.smt2                                                                                 |   3.406s  |   3.406s  |   0.000s  | 0.0%|
|bench6.smt2                                                                                 |  30.352s  |  30.352s  |   0.000s  | 0.0%|
|bench7.smt2                                                                                 |   7.031s  |   7.031s  |   0.000s  | 0.0%|
|bench_2155.smt2                                                                             |   4.930s  |   4.930s  |   0.000s  | 0.0%|
|bench_4153.smt2                                                                             |  30.023s  |  30.023s  |   0.000s  | 0.0%|
|bench_6159.smt2                                                                             |   4.856s  |   4.856s  |   0.000s  | 0.0%|
</details>
