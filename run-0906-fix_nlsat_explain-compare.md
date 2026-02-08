Comparing data and data


# SUMMARY
- LHS tests = 13306
- RHS tests = 13306
- LHS success = 0  (0.0%)
- RHS success = 0  (0.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: correct handling of add all coeffs mode
Job tag: fix_nlsat_explain
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 56db8d5e98f0228b8cd8021442764ae9d3cae591
Z3 branch: master
Z3 options: "-T:600 lp.int_patch_period=4 smt.random_seed=12"
Z3 inputs: https://zenodo.org/records/11061097/files/QF_LIA.tar.zst?download=1
Z3 commit message: fix nlsat_explain.cpp that the regression tests would pass with lws=false

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: correct handling of add all coeffs mode
Job tag: fix_nlsat_explain
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 56db8d5e98f0228b8cd8021442764ae9d3cae591
Z3 branch: master
Z3 options: "-T:600 lp.int_patch_period=4 smt.random_seed=12"
Z3 inputs: https://zenodo.org/records/11061097/files/QF_LIA.tar.zst?download=1
Z3 commit message: fix nlsat_explain.cpp that the regression tests would pass with lws=false

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/20220307-SMPT/HouseConstruction-PT-01000/RF-13.smt2                 |   0.264s |1788.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/HouseConstruction-PT-00100/RC-05.smt2                 |   0.246s |2036.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Sudoku-PT-BN01/RC-10.smt2                             |   0.177s |1548.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/HouseConstruction-PT-01000/RF-07.smt2                 |   0.174s |1560.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-0200/RC-06.smt2                         |   0.172s |1536.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SwimmingPool-PT-01/RF-06.smt2                         |   0.139s |1472.0KiB|
|non-incremental/QF_LIA/pb2010/normalized-j12045_10-sat.smt2                                |   0.136s |1552.0KiB|
|non-incremental/QF_LIA/prime-cone/prime_cone_sat_13.smt2                                   |   0.132s |1788.0KiB|
|non-incremental/QF_LIA/prime-cone/prime_cone_unsat_6.smt2                                  |   0.131s |1788.0KiB|
|non-incremental/QF_LIA/prime-cone/prime_cone_unsat_4.smt2                                  |   0.129s |1576.0KiB|
|non-incremental/QF_LIA/prime-cone/prime_cone_sat_5.smt2                                    |   0.128s |1788.0KiB|
|non-incremental/QF_LIA/prime-cone/prime_cone_unsat_18.smt2                                 |   0.127s |1788.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SwimmingPool-PT-01/RF-03.smt2                         |   0.126s |1464.0KiB|
|non-incremental/QF_LIA/prime-cone/prime_cone_sat_12.smt2                                   |   0.125s |1452.0KiB|
|non-incremental/QF_LIA/prime-cone/prime_cone_unsat_7.smt2                                  |   0.125s |1788.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Diffusion2D-PT-D05N300/RC-06.smt2                     |   0.122s |1788.0KiB|
|non-incremental/QF_LIA/slacks/35-16.slack.smt2                                             |   0.119s |1564.0KiB|
|non-incremental/QF_LIA/slacks/35-14.slack.smt2                                             |   0.119s |1768.0KiB|
|non-incremental/QF_LIA/slacks/30-1.slack.smt2                                              |   0.119s |1576.0KiB|
|non-incremental/QF_LIA/slacks/40-23.slack.smt2                                             |   0.118s |1576.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/20220307-SMPT/HouseConstruction-PT-01000/RF-13.smt2                 |   0.264s |1788.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/HouseConstruction-PT-00100/RC-05.smt2                 |   0.246s |2036.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Sudoku-PT-BN01/RC-10.smt2                             |   0.177s |1548.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/HouseConstruction-PT-01000/RF-07.smt2                 |   0.174s |1560.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-0200/RC-06.smt2                         |   0.172s |1536.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SwimmingPool-PT-01/RF-06.smt2                         |   0.139s |1472.0KiB|
|non-incremental/QF_LIA/pb2010/normalized-j12045_10-sat.smt2                                |   0.136s |1552.0KiB|
|non-incremental/QF_LIA/prime-cone/prime_cone_sat_13.smt2                                   |   0.132s |1788.0KiB|
|non-incremental/QF_LIA/prime-cone/prime_cone_unsat_6.smt2                                  |   0.131s |1788.0KiB|
|non-incremental/QF_LIA/prime-cone/prime_cone_unsat_4.smt2                                  |   0.129s |1576.0KiB|
|non-incremental/QF_LIA/prime-cone/prime_cone_sat_5.smt2                                    |   0.128s |1788.0KiB|
|non-incremental/QF_LIA/prime-cone/prime_cone_unsat_18.smt2                                 |   0.127s |1788.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SwimmingPool-PT-01/RF-03.smt2                         |   0.126s |1464.0KiB|
|non-incremental/QF_LIA/prime-cone/prime_cone_sat_12.smt2                                   |   0.125s |1452.0KiB|
|non-incremental/QF_LIA/prime-cone/prime_cone_unsat_7.smt2                                  |   0.125s |1788.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Diffusion2D-PT-D05N300/RC-06.smt2                     |   0.122s |1788.0KiB|
|non-incremental/QF_LIA/slacks/35-16.slack.smt2                                             |   0.119s |1564.0KiB|
|non-incremental/QF_LIA/slacks/35-14.slack.smt2                                             |   0.119s |1768.0KiB|
|non-incremental/QF_LIA/slacks/30-1.slack.smt2                                              |   0.119s |1576.0KiB|
|non-incremental/QF_LIA/slacks/40-23.slack.smt2                                             |   0.118s |1576.0KiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-020/RF-10.smt2                          |   0.025s |2040.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/HouseConstruction-PT-00100/RC-05.smt2                 |   0.246s |2036.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/CircularTrains-PT-048/RC-14.smt2                      |   0.034s |2020.0KiB|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1201.smt2                             |   0.011s |1832.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Sudoku-PT-BN01/RC-14.smt2                             |   0.008s |1832.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SwimmingPool-PT-05/RF-04.smt2                         |   0.026s |1828.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SmallOperatingSystem-PT-MT0016DC0008/RC-14.smt2       |   0.018s |1828.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Kanban-PT-00200/RC-06.smt2                            |   0.004s |1828.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/CircularTrains-PT-024/RF-08.smt2                      |   0.036s |1824.0KiB|
|non-incremental/QF_LIA/20180326-Bromberger/more_slacked/CAV_2009_benchmarks/smt/40-vars/v40_problem_2__016.smt2.slack.smt2 |   0.023s |1824.0KiB|
|non-incremental/QF_LIA/rings/ring_2exp12_4vars_0ite_unsat.smt2                             |   0.016s |1824.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-050/RC-15.smt2                                |   0.027s |1820.0KiB|
|non-incremental/QF_LIA/2019-cmodelsdiff/stillLive/0002-still_live-7-1.smt2                 |   0.022s |1820.0KiB|
|non-incremental/QF_LIA/bofill-scheduling/SMT_real_LIA/ex4380_2400_100.smt2                 |   0.021s |1820.0KiB|
|non-incremental/QF_LIA/nec-smt/large/handler_sigchld/prp-23-48.smt2                        |   0.020s |1820.0KiB|
|non-incremental/QF_LIA/pb2010/normalized-j3029_6-sat.smt2                                  |   0.019s |1820.0KiB|
|non-incremental/QF_LIA/20180326-Bromberger/more_slacked/CAV_2009_benchmarks/smt/40-vars/v40_problem__019.smt2.slack.smt2 |   0.030s |1816.0KiB|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1526.smt2                             |   0.029s |1816.0KiB|
|non-incremental/QF_LIA/20180326-Bromberger/more_slacked/CAV_2009_benchmarks/smt/25-vars/v25_problem_2__025.smt2.slack.smt2 |   0.023s |1816.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/HouseConstruction-PT-04000/RC-11.smt2                 |   0.022s |1816.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-020/RF-10.smt2                          |   0.025s |2040.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/HouseConstruction-PT-00100/RC-05.smt2                 |   0.246s |2036.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/CircularTrains-PT-048/RC-14.smt2                      |   0.034s |2020.0KiB|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1201.smt2                             |   0.011s |1832.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Sudoku-PT-BN01/RC-14.smt2                             |   0.008s |1832.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SwimmingPool-PT-05/RF-04.smt2                         |   0.026s |1828.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SmallOperatingSystem-PT-MT0016DC0008/RC-14.smt2       |   0.018s |1828.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Kanban-PT-00200/RC-06.smt2                            |   0.004s |1828.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/CircularTrains-PT-024/RF-08.smt2                      |   0.036s |1824.0KiB|
|non-incremental/QF_LIA/20180326-Bromberger/more_slacked/CAV_2009_benchmarks/smt/40-vars/v40_problem_2__016.smt2.slack.smt2 |   0.023s |1824.0KiB|
|non-incremental/QF_LIA/rings/ring_2exp12_4vars_0ite_unsat.smt2                             |   0.016s |1824.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-050/RC-15.smt2                                |   0.027s |1820.0KiB|
|non-incremental/QF_LIA/2019-cmodelsdiff/stillLive/0002-still_live-7-1.smt2                 |   0.022s |1820.0KiB|
|non-incremental/QF_LIA/bofill-scheduling/SMT_real_LIA/ex4380_2400_100.smt2                 |   0.021s |1820.0KiB|
|non-incremental/QF_LIA/nec-smt/large/handler_sigchld/prp-23-48.smt2                        |   0.020s |1820.0KiB|
|non-incremental/QF_LIA/pb2010/normalized-j3029_6-sat.smt2                                  |   0.019s |1820.0KiB|
|non-incremental/QF_LIA/20180326-Bromberger/more_slacked/CAV_2009_benchmarks/smt/40-vars/v40_problem__019.smt2.slack.smt2 |   0.030s |1816.0KiB|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1526.smt2                             |   0.029s |1816.0KiB|
|non-incremental/QF_LIA/20180326-Bromberger/more_slacked/CAV_2009_benchmarks/smt/25-vars/v25_problem_2__025.smt2.slack.smt2 |   0.023s |1816.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/HouseConstruction-PT-04000/RC-11.smt2                 |   0.022s |1816.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
