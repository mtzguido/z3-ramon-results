Comparing data and data


# SUMMARY
- LHS tests = 29
- RHS tests = 29
- LHS success = 27  (93.10344827586206%)
- RHS success = 27  (93.10344827586206%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: qfbv-master-perf-pr
Runner: lev-ripper
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
Runner: lev-ripper
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
|1hSVT2qncdEm.smt2                                                                           |   1.378s  |   1.378s  |   0.000s  | 0.0%|
|bench0.smt2                                                                                 |  30.833s  |  30.833s  |   0.000s  | 0.0%|
|bench0_check.smt2                                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench0_simplified.smt2                                                                      |  30.189s  |  30.189s  |   0.000s  | 0.0%|
|bench1.smt2                                                                                 |  30.725s  |  30.725s  |   0.000s  | 0.0%|
|bench11.smt2                                                                                |   5.602s  |   5.602s  |   0.000s  | 0.0%|
|bench13.smt2                                                                                |  30.645s  |  30.645s  |   0.000s  | 0.0%|
|bench15.smt2                                                                                |  30.815s  |  30.815s  |   0.000s  | 0.0%|
|bench1_bw1024.smt2                                                                          |  30.668s  |  30.668s  |   0.000s  | 0.0%|
|bench1_bw256.smt2                                                                           |  30.650s  |  30.650s  |   0.000s  | 0.0%|
|bench1_bw300.smt2                                                                           |  30.429s  |  30.429s  |   0.000s  | 0.0%|
|bench1_bw64.smt2                                                                            |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|bench1_bw8192.smt2                                                                          |  30.761s  |  30.761s  |   0.000s  | 0.0%|
|bench1_check.smt2                                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench2.smt2                                                                                 |  30.453s  |  30.453s  |   0.000s  | 0.0%|
|bench23.smt2                                                                                |  30.626s  |  30.626s  |   0.000s  | 0.0%|
|bench25_core.smt2                                                                           |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|bench27.smt2                                                                                |  30.621s  |  30.621s  |   0.000s  | 0.0%|
|bench3.smt2                                                                                 |  30.600s  |  30.600s  |   0.000s  | 0.0%|
|bench31.smt2                                                                                |  30.594s  |  30.594s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |   1.378s  |   1.378s  |   0.000s  | 0.0%|
|bench0.smt2                                                                                 |  30.833s  |  30.833s  |   0.000s  | 0.0%|
|bench0_check.smt2                                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench0_simplified.smt2                                                                      |  30.189s  |  30.189s  |   0.000s  | 0.0%|
|bench1.smt2                                                                                 |  30.725s  |  30.725s  |   0.000s  | 0.0%|
|bench11.smt2                                                                                |   5.602s  |   5.602s  |   0.000s  | 0.0%|
|bench13.smt2                                                                                |  30.645s  |  30.645s  |   0.000s  | 0.0%|
|bench15.smt2                                                                                |  30.815s  |  30.815s  |   0.000s  | 0.0%|
|bench1_bw1024.smt2                                                                          |  30.668s  |  30.668s  |   0.000s  | 0.0%|
|bench1_bw256.smt2                                                                           |  30.650s  |  30.650s  |   0.000s  | 0.0%|
|bench1_bw300.smt2                                                                           |  30.429s  |  30.429s  |   0.000s  | 0.0%|
|bench1_bw64.smt2                                                                            |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|bench1_bw8192.smt2                                                                          |  30.761s  |  30.761s  |   0.000s  | 0.0%|
|bench1_check.smt2                                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench2.smt2                                                                                 |  30.453s  |  30.453s  |   0.000s  | 0.0%|
|bench23.smt2                                                                                |  30.626s  |  30.626s  |   0.000s  | 0.0%|
|bench25_core.smt2                                                                           |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|bench27.smt2                                                                                |  30.621s  |  30.621s  |   0.000s  | 0.0%|
|bench3.smt2                                                                                 |  30.600s  |  30.600s  |   0.000s  | 0.0%|
|bench31.smt2                                                                                |  30.594s  |  30.594s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |   1.378s  |   1.378s  |   0.000s  | 0.0%|
|bench0.smt2                                                                                 |  30.833s  |  30.833s  |   0.000s  | 0.0%|
|bench0_check.smt2                                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench0_simplified.smt2                                                                      |  30.189s  |  30.189s  |   0.000s  | 0.0%|
|bench1.smt2                                                                                 |  30.725s  |  30.725s  |   0.000s  | 0.0%|
|bench11.smt2                                                                                |   5.602s  |   5.602s  |   0.000s  | 0.0%|
|bench13.smt2                                                                                |  30.645s  |  30.645s  |   0.000s  | 0.0%|
|bench15.smt2                                                                                |  30.815s  |  30.815s  |   0.000s  | 0.0%|
|bench1_bw1024.smt2                                                                          |  30.668s  |  30.668s  |   0.000s  | 0.0%|
|bench1_bw256.smt2                                                                           |  30.650s  |  30.650s  |   0.000s  | 0.0%|
|bench1_bw300.smt2                                                                           |  30.429s  |  30.429s  |   0.000s  | 0.0%|
|bench1_bw64.smt2                                                                            |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|bench1_bw8192.smt2                                                                          |  30.761s  |  30.761s  |   0.000s  | 0.0%|
|bench1_check.smt2                                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench2.smt2                                                                                 |  30.453s  |  30.453s  |   0.000s  | 0.0%|
|bench23.smt2                                                                                |  30.626s  |  30.626s  |   0.000s  | 0.0%|
|bench25_core.smt2                                                                           |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|bench27.smt2                                                                                |  30.621s  |  30.621s  |   0.000s  | 0.0%|
|bench3.smt2                                                                                 |  30.600s  |  30.600s  |   0.000s  | 0.0%|
|bench31.smt2                                                                                |  30.594s  |  30.594s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |   1.378s  |   1.378s  |   0.000s  | 0.0%|
|bench0.smt2                                                                                 |  30.833s  |  30.833s  |   0.000s  | 0.0%|
|bench0_check.smt2                                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench0_simplified.smt2                                                                      |  30.189s  |  30.189s  |   0.000s  | 0.0%|
|bench1.smt2                                                                                 |  30.725s  |  30.725s  |   0.000s  | 0.0%|
|bench11.smt2                                                                                |   5.602s  |   5.602s  |   0.000s  | 0.0%|
|bench13.smt2                                                                                |  30.645s  |  30.645s  |   0.000s  | 0.0%|
|bench15.smt2                                                                                |  30.815s  |  30.815s  |   0.000s  | 0.0%|
|bench1_bw1024.smt2                                                                          |  30.668s  |  30.668s  |   0.000s  | 0.0%|
|bench1_bw256.smt2                                                                           |  30.650s  |  30.650s  |   0.000s  | 0.0%|
|bench1_bw300.smt2                                                                           |  30.429s  |  30.429s  |   0.000s  | 0.0%|
|bench1_bw64.smt2                                                                            |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|bench1_bw8192.smt2                                                                          |  30.761s  |  30.761s  |   0.000s  | 0.0%|
|bench1_check.smt2                                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench2.smt2                                                                                 |  30.453s  |  30.453s  |   0.000s  | 0.0%|
|bench23.smt2                                                                                |  30.626s  |  30.626s  |   0.000s  | 0.0%|
|bench25_core.smt2                                                                           |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|bench27.smt2                                                                                |  30.621s  |  30.621s  |   0.000s  | 0.0%|
|bench3.smt2                                                                                 |  30.600s  |  30.600s  |   0.000s  | 0.0%|
|bench31.smt2                                                                                |  30.594s  |  30.594s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench0.smt2                                                                                |  30.833s |6401.0MiB|
|bench15.smt2                                                                               |  30.815s |6460.0MiB|
|bench1_bw8192.smt2                                                                         |  30.761s |7258.0MiB|
|bench1.smt2                                                                                |  30.725s |6401.0MiB|
|bench1_bw1024.smt2                                                                         |  30.668s |6620.0MiB|
|bench1_bw256.smt2                                                                          |  30.650s |6401.0MiB|
|bench13.smt2                                                                               |  30.645s |6376.0MiB|
|bench6.smt2                                                                                |  30.629s |6232.0MiB|
|bench23.smt2                                                                               |  30.626s |3623.0MiB|
|bench27.smt2                                                                               |  30.621s |3633.0MiB|
|bench3.smt2                                                                                |  30.600s |3293.0MiB|
|bench31.smt2                                                                               |  30.594s |6376.0MiB|
|bench2.smt2                                                                                |  30.453s |3193.0MiB|
|bench1_bw300.smt2                                                                          |  30.429s |3231.0MiB|
|bench0_simplified.smt2                                                                     |  30.189s |767.0MiB|
|bench_4153.smt2                                                                            |  30.095s |137.0MiB|
|bench1_bw64.smt2                                                                           |  30.086s |849.0MiB|
|bench25_core.smt2                                                                          |  30.026s |42.168MiB|
|bench1_bw512.smt2                                                                          |  28.242s |6387.0MiB|
|bench25.smt2                                                                               |  26.535s |12.798GiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench0.smt2                                                                                |  30.833s |6401.0MiB|
|bench15.smt2                                                                               |  30.815s |6460.0MiB|
|bench1_bw8192.smt2                                                                         |  30.761s |7258.0MiB|
|bench1.smt2                                                                                |  30.725s |6401.0MiB|
|bench1_bw1024.smt2                                                                         |  30.668s |6620.0MiB|
|bench1_bw256.smt2                                                                          |  30.650s |6401.0MiB|
|bench13.smt2                                                                               |  30.645s |6376.0MiB|
|bench6.smt2                                                                                |  30.629s |6232.0MiB|
|bench23.smt2                                                                               |  30.626s |3623.0MiB|
|bench27.smt2                                                                               |  30.621s |3633.0MiB|
|bench3.smt2                                                                                |  30.600s |3293.0MiB|
|bench31.smt2                                                                               |  30.594s |6376.0MiB|
|bench2.smt2                                                                                |  30.453s |3193.0MiB|
|bench1_bw300.smt2                                                                          |  30.429s |3231.0MiB|
|bench0_simplified.smt2                                                                     |  30.189s |767.0MiB|
|bench_4153.smt2                                                                            |  30.095s |137.0MiB|
|bench1_bw64.smt2                                                                           |  30.086s |849.0MiB|
|bench25_core.smt2                                                                          |  30.026s |42.168MiB|
|bench1_bw512.smt2                                                                          |  28.242s |6387.0MiB|
|bench25.smt2                                                                               |  26.535s |12.798GiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |31.364MiB|31.364MiB|0B| 0.0%|
|bench0.smt2                                                                                 |6401.0MiB|6401.0MiB|0B| 0.0%|
|bench0_check.smt2                                                                           |19.18MiB|19.18MiB|0B| 0.0%|
|bench0_simplified.smt2                                                                      |767.0MiB|767.0MiB|0B| 0.0%|
|bench1.smt2                                                                                 |6401.0MiB|6401.0MiB|0B| 0.0%|
|bench11.smt2                                                                                |1705.0MiB|1705.0MiB|0B| 0.0%|
|bench13.smt2                                                                                |6376.0MiB|6376.0MiB|0B| 0.0%|
|bench15.smt2                                                                                |6460.0MiB|6460.0MiB|0B| 0.0%|
|bench1_bw1024.smt2                                                                          |6620.0MiB|6620.0MiB|0B| 0.0%|
|bench1_bw256.smt2                                                                           |6401.0MiB|6401.0MiB|0B| 0.0%|
|bench1_bw300.smt2                                                                           |3231.0MiB|3231.0MiB|0B| 0.0%|
|bench1_bw64.smt2                                                                            |849.0MiB|849.0MiB|0B| 0.0%|
|bench1_bw8192.smt2                                                                          |7258.0MiB|7258.0MiB|0B| 0.0%|
|bench1_check.smt2                                                                           |19.328MiB|19.328MiB|0B| 0.0%|
|bench2.smt2                                                                                 |3193.0MiB|3193.0MiB|0B| 0.0%|
|bench23.smt2                                                                                |3623.0MiB|3623.0MiB|0B| 0.0%|
|bench25_core.smt2                                                                           |42.168MiB|42.168MiB|0B| 0.0%|
|bench27.smt2                                                                                |3633.0MiB|3633.0MiB|0B| 0.0%|
|bench3.smt2                                                                                 |3293.0MiB|3293.0MiB|0B| 0.0%|
|bench31.smt2                                                                                |6376.0MiB|6376.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |31.364MiB|31.364MiB|0B| 0.0%|
|bench0.smt2                                                                                 |6401.0MiB|6401.0MiB|0B| 0.0%|
|bench0_check.smt2                                                                           |19.18MiB|19.18MiB|0B| 0.0%|
|bench0_simplified.smt2                                                                      |767.0MiB|767.0MiB|0B| 0.0%|
|bench1.smt2                                                                                 |6401.0MiB|6401.0MiB|0B| 0.0%|
|bench11.smt2                                                                                |1705.0MiB|1705.0MiB|0B| 0.0%|
|bench13.smt2                                                                                |6376.0MiB|6376.0MiB|0B| 0.0%|
|bench15.smt2                                                                                |6460.0MiB|6460.0MiB|0B| 0.0%|
|bench1_bw1024.smt2                                                                          |6620.0MiB|6620.0MiB|0B| 0.0%|
|bench1_bw256.smt2                                                                           |6401.0MiB|6401.0MiB|0B| 0.0%|
|bench1_bw300.smt2                                                                           |3231.0MiB|3231.0MiB|0B| 0.0%|
|bench1_bw64.smt2                                                                            |849.0MiB|849.0MiB|0B| 0.0%|
|bench1_bw8192.smt2                                                                          |7258.0MiB|7258.0MiB|0B| 0.0%|
|bench1_check.smt2                                                                           |19.328MiB|19.328MiB|0B| 0.0%|
|bench2.smt2                                                                                 |3193.0MiB|3193.0MiB|0B| 0.0%|
|bench23.smt2                                                                                |3623.0MiB|3623.0MiB|0B| 0.0%|
|bench25_core.smt2                                                                           |42.168MiB|42.168MiB|0B| 0.0%|
|bench27.smt2                                                                                |3633.0MiB|3633.0MiB|0B| 0.0%|
|bench3.smt2                                                                                 |3293.0MiB|3293.0MiB|0B| 0.0%|
|bench31.smt2                                                                                |6376.0MiB|6376.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |31.364MiB|31.364MiB|0B| 0.0%|
|bench0.smt2                                                                                 |6401.0MiB|6401.0MiB|0B| 0.0%|
|bench0_check.smt2                                                                           |19.18MiB|19.18MiB|0B| 0.0%|
|bench0_simplified.smt2                                                                      |767.0MiB|767.0MiB|0B| 0.0%|
|bench1.smt2                                                                                 |6401.0MiB|6401.0MiB|0B| 0.0%|
|bench11.smt2                                                                                |1705.0MiB|1705.0MiB|0B| 0.0%|
|bench13.smt2                                                                                |6376.0MiB|6376.0MiB|0B| 0.0%|
|bench15.smt2                                                                                |6460.0MiB|6460.0MiB|0B| 0.0%|
|bench1_bw1024.smt2                                                                          |6620.0MiB|6620.0MiB|0B| 0.0%|
|bench1_bw256.smt2                                                                           |6401.0MiB|6401.0MiB|0B| 0.0%|
|bench1_bw300.smt2                                                                           |3231.0MiB|3231.0MiB|0B| 0.0%|
|bench1_bw64.smt2                                                                            |849.0MiB|849.0MiB|0B| 0.0%|
|bench1_bw8192.smt2                                                                          |7258.0MiB|7258.0MiB|0B| 0.0%|
|bench1_check.smt2                                                                           |19.328MiB|19.328MiB|0B| 0.0%|
|bench2.smt2                                                                                 |3193.0MiB|3193.0MiB|0B| 0.0%|
|bench23.smt2                                                                                |3623.0MiB|3623.0MiB|0B| 0.0%|
|bench25_core.smt2                                                                           |42.168MiB|42.168MiB|0B| 0.0%|
|bench27.smt2                                                                                |3633.0MiB|3633.0MiB|0B| 0.0%|
|bench3.smt2                                                                                 |3293.0MiB|3293.0MiB|0B| 0.0%|
|bench31.smt2                                                                                |6376.0MiB|6376.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |31.364MiB|31.364MiB|0B| 0.0%|
|bench0.smt2                                                                                 |6401.0MiB|6401.0MiB|0B| 0.0%|
|bench0_check.smt2                                                                           |19.18MiB|19.18MiB|0B| 0.0%|
|bench0_simplified.smt2                                                                      |767.0MiB|767.0MiB|0B| 0.0%|
|bench1.smt2                                                                                 |6401.0MiB|6401.0MiB|0B| 0.0%|
|bench11.smt2                                                                                |1705.0MiB|1705.0MiB|0B| 0.0%|
|bench13.smt2                                                                                |6376.0MiB|6376.0MiB|0B| 0.0%|
|bench15.smt2                                                                                |6460.0MiB|6460.0MiB|0B| 0.0%|
|bench1_bw1024.smt2                                                                          |6620.0MiB|6620.0MiB|0B| 0.0%|
|bench1_bw256.smt2                                                                           |6401.0MiB|6401.0MiB|0B| 0.0%|
|bench1_bw300.smt2                                                                           |3231.0MiB|3231.0MiB|0B| 0.0%|
|bench1_bw64.smt2                                                                            |849.0MiB|849.0MiB|0B| 0.0%|
|bench1_bw8192.smt2                                                                          |7258.0MiB|7258.0MiB|0B| 0.0%|
|bench1_check.smt2                                                                           |19.328MiB|19.328MiB|0B| 0.0%|
|bench2.smt2                                                                                 |3193.0MiB|3193.0MiB|0B| 0.0%|
|bench23.smt2                                                                                |3623.0MiB|3623.0MiB|0B| 0.0%|
|bench25_core.smt2                                                                           |42.168MiB|42.168MiB|0B| 0.0%|
|bench27.smt2                                                                                |3633.0MiB|3633.0MiB|0B| 0.0%|
|bench3.smt2                                                                                 |3293.0MiB|3293.0MiB|0B| 0.0%|
|bench31.smt2                                                                                |6376.0MiB|6376.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench25.smt2                                                                               |  26.535s |12.798GiB|
|bench1_bw8192.smt2                                                                         |  30.761s |7258.0MiB|
|bench1_bw1024.smt2                                                                         |  30.668s |6620.0MiB|
|bench15.smt2                                                                               |  30.815s |6460.0MiB|
|bench0.smt2                                                                                |  30.833s |6401.0MiB|
|bench1.smt2                                                                                |  30.725s |6401.0MiB|
|bench1_bw256.smt2                                                                          |  30.650s |6401.0MiB|
|bench1_bw512.smt2                                                                          |  28.242s |6387.0MiB|
|bench13.smt2                                                                               |  30.645s |6376.0MiB|
|bench31.smt2                                                                               |  30.594s |6376.0MiB|
|bench6.smt2                                                                                |  30.629s |6232.0MiB|
|bench27.smt2                                                                               |  30.621s |3633.0MiB|
|bench23.smt2                                                                               |  30.626s |3623.0MiB|
|bench3.smt2                                                                                |  30.600s |3293.0MiB|
|bench1_bw300.smt2                                                                          |  30.429s |3231.0MiB|
|bench2.smt2                                                                                |  30.453s |3193.0MiB|
|bench7.smt2                                                                                |   7.759s |1780.0MiB|
|bench11.smt2                                                                               |   5.602s |1705.0MiB|
|bench5.smt2                                                                                |   5.448s |1700.0MiB|
|bench1_bw64.smt2                                                                           |  30.086s |849.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench25.smt2                                                                               |  26.535s |12.798GiB|
|bench1_bw8192.smt2                                                                         |  30.761s |7258.0MiB|
|bench1_bw1024.smt2                                                                         |  30.668s |6620.0MiB|
|bench15.smt2                                                                               |  30.815s |6460.0MiB|
|bench0.smt2                                                                                |  30.833s |6401.0MiB|
|bench1.smt2                                                                                |  30.725s |6401.0MiB|
|bench1_bw256.smt2                                                                          |  30.650s |6401.0MiB|
|bench1_bw512.smt2                                                                          |  28.242s |6387.0MiB|
|bench13.smt2                                                                               |  30.645s |6376.0MiB|
|bench31.smt2                                                                               |  30.594s |6376.0MiB|
|bench6.smt2                                                                                |  30.629s |6232.0MiB|
|bench27.smt2                                                                               |  30.621s |3633.0MiB|
|bench23.smt2                                                                               |  30.626s |3623.0MiB|
|bench3.smt2                                                                                |  30.600s |3293.0MiB|
|bench1_bw300.smt2                                                                          |  30.429s |3231.0MiB|
|bench2.smt2                                                                                |  30.453s |3193.0MiB|
|bench7.smt2                                                                                |   7.759s |1780.0MiB|
|bench11.smt2                                                                               |   5.602s |1705.0MiB|
|bench5.smt2                                                                                |   5.448s |1700.0MiB|
|bench1_bw64.smt2                                                                           |  30.086s |849.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|1hSVT2qncdEm.smt2                                                                           |   1.378s  |   1.378s  |   0.000s  | 0.0%|
|bench0.smt2                                                                                 |  30.833s  |  30.833s  |   0.000s  | 0.0%|
|bench0_check.smt2                                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench0_simplified.smt2                                                                      |  30.189s  |  30.189s  |   0.000s  | 0.0%|
|bench1.smt2                                                                                 |  30.725s  |  30.725s  |   0.000s  | 0.0%|
|bench11.smt2                                                                                |   5.602s  |   5.602s  |   0.000s  | 0.0%|
|bench13.smt2                                                                                |  30.645s  |  30.645s  |   0.000s  | 0.0%|
|bench15.smt2                                                                                |  30.815s  |  30.815s  |   0.000s  | 0.0%|
|bench1_bw1024.smt2                                                                          |  30.668s  |  30.668s  |   0.000s  | 0.0%|
|bench1_bw256.smt2                                                                           |  30.650s  |  30.650s  |   0.000s  | 0.0%|
|bench1_bw300.smt2                                                                           |  30.429s  |  30.429s  |   0.000s  | 0.0%|
|bench1_bw64.smt2                                                                            |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|bench1_bw8192.smt2                                                                          |  30.761s  |  30.761s  |   0.000s  | 0.0%|
|bench1_check.smt2                                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench2.smt2                                                                                 |  30.453s  |  30.453s  |   0.000s  | 0.0%|
|bench23.smt2                                                                                |  30.626s  |  30.626s  |   0.000s  | 0.0%|
|bench25_core.smt2                                                                           |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|bench27.smt2                                                                                |  30.621s  |  30.621s  |   0.000s  | 0.0%|
|bench3.smt2                                                                                 |  30.600s  |  30.600s  |   0.000s  | 0.0%|
|bench31.smt2                                                                                |  30.594s  |  30.594s  |   0.000s  | 0.0%|
|bench5.smt2                                                                                 |   5.448s  |   5.448s  |   0.000s  | 0.0%|
|bench6.smt2                                                                                 |  30.629s  |  30.629s  |   0.000s  | 0.0%|
|bench7.smt2                                                                                 |   7.759s  |   7.759s  |   0.000s  | 0.0%|
|bench_2155.smt2                                                                             |   4.083s  |   4.083s  |   0.000s  | 0.0%|
|bench_4153.smt2                                                                             |  30.095s  |  30.095s  |   0.000s  | 0.0%|
|bench_6159.smt2                                                                             |   3.775s  |   3.775s  |   0.000s  | 0.0%|
</details>
