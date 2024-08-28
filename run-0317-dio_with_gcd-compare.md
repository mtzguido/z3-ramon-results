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
Job description: 
Job tag: dio_with_gcd
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 7ee34151501242638597e0af7e4c3e1cd5934046
Z3 branch: 
Z3 options: "-T:600 -st lp.dio=true lp.dio_gcd=true"
Z3 inputs: https://zenodo.org/records/11061097/files/QF_LIA.tar.zst?download=1
Z3 commit message: make gcd call in dio optional

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: dio_with_gcd
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 7ee34151501242638597e0af7e4c3e1cd5934046
Z3 branch: 
Z3 options: "-T:600 -st lp.dio=true lp.dio_gcd=true"
Z3 inputs: https://zenodo.org/records/11061097/files/QF_LIA.tar.zst?download=1
Z3 commit message: make gcd call in dio optional

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
|non-incremental/QF_LIA/20220307-SMPT/FMS-PT-05000/RF-10.smt2                               |   0.031s |1376.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-002/RC-14.smt2                                |   0.027s |1556.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0100/RF-02.smt2                      |   0.024s |1472.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SmallOperatingSystem-PT-MT0128DC0064/RF-05.smt2       |   0.024s |1528.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Diffusion2D-PT-D10N200/RC-12.smt2                     |   0.023s |1412.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Sudoku-PT-AN01/RC-08.smt2                             |   0.023s |1560.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SmallOperatingSystem-PT-MT0128DC0064/RF-03.smt2       |   0.022s |1580.0KiB|
|non-incremental/QF_LIA/cut_lemmas/20-vars/cut_lemma_01_013.smt2                            |   0.021s |1560.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Kanban-PT-00100/RF-04.smt2                            |   0.021s |1560.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Kanban-PT-00100/RF-05.smt2                            |   0.021s |1560.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r2000w0010/RC-14.smt2                      |   0.021s |1560.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/NeighborGrid-PT-d2n3m1c12/RF-06.smt2                  |   0.020s |1560.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/RobotManipulation-PT-00200/RF-05.smt2                 |   0.019s |1560.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SwimmingPool-PT-06/RC-13.smt2                         |   0.019s |1388.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000200/RF-10.smt2                     |   0.019s |1724.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Diffusion2D-PT-D10N200/RC-09.smt2                     |   0.018s |1528.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-002/RC-13.smt2                                |   0.018s |1736.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Sudoku-PT-BN01/RC-09.smt2                             |   0.018s |1356.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/MAPK-PT-00160/RC-05.smt2                              |   0.018s |1564.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/IOTPpurchase-PT-C12M10P15D17/RC-07.smt2               |   0.018s |1428.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/20220307-SMPT/FMS-PT-05000/RF-10.smt2                               |   0.031s |1376.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-002/RC-14.smt2                                |   0.027s |1556.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0100/RF-02.smt2                      |   0.024s |1472.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SmallOperatingSystem-PT-MT0128DC0064/RF-05.smt2       |   0.024s |1528.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Diffusion2D-PT-D10N200/RC-12.smt2                     |   0.023s |1412.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Sudoku-PT-AN01/RC-08.smt2                             |   0.023s |1560.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SmallOperatingSystem-PT-MT0128DC0064/RF-03.smt2       |   0.022s |1580.0KiB|
|non-incremental/QF_LIA/cut_lemmas/20-vars/cut_lemma_01_013.smt2                            |   0.021s |1560.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Kanban-PT-00100/RF-04.smt2                            |   0.021s |1560.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Kanban-PT-00100/RF-05.smt2                            |   0.021s |1560.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r2000w0010/RC-14.smt2                      |   0.021s |1560.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/NeighborGrid-PT-d2n3m1c12/RF-06.smt2                  |   0.020s |1560.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/RobotManipulation-PT-00200/RF-05.smt2                 |   0.019s |1560.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SwimmingPool-PT-06/RC-13.smt2                         |   0.019s |1388.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000200/RF-10.smt2                     |   0.019s |1724.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Diffusion2D-PT-D10N200/RC-09.smt2                     |   0.018s |1528.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-002/RC-13.smt2                                |   0.018s |1736.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Sudoku-PT-BN01/RC-09.smt2                             |   0.018s |1356.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/MAPK-PT-00160/RC-05.smt2                              |   0.018s |1564.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/IOTPpurchase-PT-C12M10P15D17/RC-07.smt2               |   0.018s |1428.0KiB|
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
|non-incremental/QF_LIA/CAV_2009_benchmarks/smt/30-vars/problem_2__030.smt2                 |   0.005s |1836.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/MAPK-PT-01280/RC-13.smt2                              |   0.005s |1836.0KiB|
|non-incremental/QF_LIA/20180326-Bromberger/more_slacked/CAV_2009_benchmarks/smt/30-vars/v30_problem__008.smt2.slack.smt2 |   0.006s |1832.0KiB|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1379.smt2                             |   0.005s |1832.0KiB|
|non-incremental/QF_LIA/rings_preprocessed/ring_2exp14_8vars_2ite_unsat.smt2                |   0.007s |1828.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/RobotManipulation-PT-00005/RF-06.smt2                 |   0.008s |1820.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SmallOperatingSystem-PT-MT8192DC2048/RC-00.smt2       |   0.008s |1820.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/MAPK-PT-10240/RF-01.smt2                              |   0.006s |1820.0KiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-24-46.smt2                        |   0.006s |1820.0KiB|
|non-incremental/QF_LIA/CAV_2009_benchmarks/smt/45-vars/problem__003.smt2                   |   0.005s |1820.0KiB|
|non-incremental/QF_LIA/pidgeons/pigeon-hole-9.smt2                                         |   0.008s |1816.0KiB|
|non-incremental/QF_LIA/mathsat/FISCHER8-10-fair.smt2                                       |   0.006s |1816.0KiB|
|non-incremental/QF_LIA/RWS/Example_4.txt.smt2                                              |   0.005s |1816.0KiB|
|non-incremental/QF_LIA/CAV_2009_benchmarks/smt/35-vars/problem__008.smt2                   |   0.005s |1816.0KiB|
|non-incremental/QF_LIA/bofill-scheduling/SMT_random_LIA/ex17300_2600_100.smt2              |   0.005s |1816.0KiB|
|non-incremental/QF_LIA/20180326-Bromberger/more_slacked/CAV_2009_benchmarks/coef-size/smt/size-10/c10_problem__004.smt2.slack.smt2 |   0.004s |1816.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Diffusion2D-PT-D40N100/RC-04.smt2                     |   0.004s |1816.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Diffusion2D-PT-D05N050/RC-01.smt2                     |   0.004s |1816.0KiB|
|non-incremental/QF_LIA/20180326-Bromberger/more_slacked/cut_lemmas/20-vars/cut_lemma_02_008.smt2.slack.smt2 |   0.003s |1816.0KiB|
|non-incremental/QF_LIA/20180326-Bromberger/more_slacked/CAV_2009_benchmarks/smt/25-vars/v25_problem__018.smt2.slack.smt2 |   0.004s |1812.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/CAV_2009_benchmarks/smt/30-vars/problem_2__030.smt2                 |   0.005s |1836.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/MAPK-PT-01280/RC-13.smt2                              |   0.005s |1836.0KiB|
|non-incremental/QF_LIA/20180326-Bromberger/more_slacked/CAV_2009_benchmarks/smt/30-vars/v30_problem__008.smt2.slack.smt2 |   0.006s |1832.0KiB|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1379.smt2                             |   0.005s |1832.0KiB|
|non-incremental/QF_LIA/rings_preprocessed/ring_2exp14_8vars_2ite_unsat.smt2                |   0.007s |1828.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/RobotManipulation-PT-00005/RF-06.smt2                 |   0.008s |1820.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/SmallOperatingSystem-PT-MT8192DC2048/RC-00.smt2       |   0.008s |1820.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/MAPK-PT-10240/RF-01.smt2                              |   0.006s |1820.0KiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-24-46.smt2                        |   0.006s |1820.0KiB|
|non-incremental/QF_LIA/CAV_2009_benchmarks/smt/45-vars/problem__003.smt2                   |   0.005s |1820.0KiB|
|non-incremental/QF_LIA/pidgeons/pigeon-hole-9.smt2                                         |   0.008s |1816.0KiB|
|non-incremental/QF_LIA/mathsat/FISCHER8-10-fair.smt2                                       |   0.006s |1816.0KiB|
|non-incremental/QF_LIA/RWS/Example_4.txt.smt2                                              |   0.005s |1816.0KiB|
|non-incremental/QF_LIA/CAV_2009_benchmarks/smt/35-vars/problem__008.smt2                   |   0.005s |1816.0KiB|
|non-incremental/QF_LIA/bofill-scheduling/SMT_random_LIA/ex17300_2600_100.smt2              |   0.005s |1816.0KiB|
|non-incremental/QF_LIA/20180326-Bromberger/more_slacked/CAV_2009_benchmarks/coef-size/smt/size-10/c10_problem__004.smt2.slack.smt2 |   0.004s |1816.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Diffusion2D-PT-D40N100/RC-04.smt2                     |   0.004s |1816.0KiB|
|non-incremental/QF_LIA/20220307-SMPT/Diffusion2D-PT-D05N050/RC-01.smt2                     |   0.004s |1816.0KiB|
|non-incremental/QF_LIA/20180326-Bromberger/more_slacked/cut_lemmas/20-vars/cut_lemma_02_008.smt2.slack.smt2 |   0.003s |1816.0KiB|
|non-incremental/QF_LIA/20180326-Bromberger/more_slacked/CAV_2009_benchmarks/smt/25-vars/v25_problem__018.smt2.slack.smt2 |   0.004s |1812.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
