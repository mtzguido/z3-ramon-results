Comparing data and data


# SUMMARY
- LHS tests = 806
- RHS tests = 806
- LHS success = 806  (100.0%)
- RHS success = 806  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-QF_LIA_hard-timeout10min-bb0
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: f880fdccee614547c38c19beb7af5a027961646b
Z3 branch: core_min
Z3 options: "-T:600 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=0"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_LIA.tar.zst?download=1
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-QF_LIA_hard-timeout10min-bb0
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: f880fdccee614547c38c19beb7af5a027961646b
Z3 branch: core_min
Z3 options: "-T:600 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=0"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_LIA.tar.zst?download=1
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |   3.811s  |   3.811s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |  74.261s  |  74.261s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |   3.754s  |   3.754s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |   3.851s  |   3.851s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   2.717s  |   2.717s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   3.823s  |   3.823s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |   3.679s  |   3.679s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   4.531s  |   4.531s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |   3.770s  |   3.770s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |   2.914s  |   2.914s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |   3.736s  |   3.736s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   4.105s  |   4.105s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   2.468s  |   2.468s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   3.696s  |   3.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   4.789s  |   4.789s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   3.139s  |   3.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   3.149s  |   3.149s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   4.421s  |   4.421s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   3.745s  |   3.745s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |   3.811s  |   3.811s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |  74.261s  |  74.261s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |   3.754s  |   3.754s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |   3.851s  |   3.851s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   2.717s  |   2.717s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   3.823s  |   3.823s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |   3.679s  |   3.679s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   4.531s  |   4.531s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |   3.770s  |   3.770s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |   2.914s  |   2.914s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |   3.736s  |   3.736s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   4.105s  |   4.105s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   2.468s  |   2.468s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   3.696s  |   3.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   4.789s  |   4.789s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   3.139s  |   3.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   3.149s  |   3.149s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   4.421s  |   4.421s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   3.745s  |   3.745s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |   3.811s  |   3.811s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |  74.261s  |  74.261s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |   3.754s  |   3.754s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |   3.851s  |   3.851s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   2.717s  |   2.717s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   3.823s  |   3.823s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |   3.679s  |   3.679s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   4.531s  |   4.531s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |   3.770s  |   3.770s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |   2.914s  |   2.914s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |   3.736s  |   3.736s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   4.105s  |   4.105s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   2.468s  |   2.468s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   3.696s  |   3.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   4.789s  |   4.789s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   3.139s  |   3.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   3.149s  |   3.149s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   4.421s  |   4.421s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   3.745s  |   3.745s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |   3.811s  |   3.811s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |  74.261s  |  74.261s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |   3.754s  |   3.754s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |   3.851s  |   3.851s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   2.717s  |   2.717s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   3.823s  |   3.823s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |   3.679s  |   3.679s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   4.531s  |   4.531s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |   3.770s  |   3.770s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |   2.914s  |   2.914s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |   3.736s  |   3.736s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   4.105s  |   4.105s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   2.468s  |   2.468s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   3.696s  |   3.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   4.789s  |   4.789s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   3.139s  |   3.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   3.149s  |   3.149s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   4.421s  |   4.421s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   3.745s  |   3.745s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-987361.smt2                                | 600.940s |4531.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               | 600.855s |5902.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1065256.smt2                               | 600.851s |6309.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                | 600.812s |5839.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                | 600.807s |5231.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                | 600.788s |4583.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                | 600.730s |4553.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-993227.smt2                                | 600.725s |5465.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-797738.smt2                              | 600.722s |4000.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-715402.smt2                              | 600.701s |3632.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                | 600.689s |4599.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                              | 600.681s |4633.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                              | 600.668s |4560.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                | 600.661s |5049.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-989891.smt2                              | 600.661s |4460.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                | 600.653s |4654.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985918.smt2                                | 600.626s |5243.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-804609.smt2                                | 600.592s |4329.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-740637.smt2                              | 600.573s |3335.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-928960.smt2                                | 600.566s |4223.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-987361.smt2                                | 600.940s |4531.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               | 600.855s |5902.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1065256.smt2                               | 600.851s |6309.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                | 600.812s |5839.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                | 600.807s |5231.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                | 600.788s |4583.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                | 600.730s |4553.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-993227.smt2                                | 600.725s |5465.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-797738.smt2                              | 600.722s |4000.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-715402.smt2                              | 600.701s |3632.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                | 600.689s |4599.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                              | 600.681s |4633.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                              | 600.668s |4560.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                | 600.661s |5049.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-989891.smt2                              | 600.661s |4460.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                | 600.653s |4654.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985918.smt2                                | 600.626s |5243.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-804609.smt2                                | 600.592s |4329.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-740637.smt2                              | 600.573s |3335.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-928960.smt2                                | 600.566s |4223.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |245.0MiB|245.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |258.0MiB|258.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  |291.0MiB|291.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |1774.0MiB|1774.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |1766.0MiB|1766.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |1159.0MiB|1159.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |1764.0MiB|1764.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |1771.0MiB|1771.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |1768.0MiB|1768.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |1767.0MiB|1767.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |1468.0MiB|1468.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |1775.0MiB|1775.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |1764.0MiB|1764.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |793.0MiB|793.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |1767.0MiB|1767.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |1760.0MiB|1760.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |1837.0MiB|1837.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |1828.0MiB|1828.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |3445.0MiB|3445.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |1772.0MiB|1772.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |245.0MiB|245.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |258.0MiB|258.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  |291.0MiB|291.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |1774.0MiB|1774.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |1766.0MiB|1766.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |1159.0MiB|1159.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |1764.0MiB|1764.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |1771.0MiB|1771.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |1768.0MiB|1768.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |1767.0MiB|1767.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |1468.0MiB|1468.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |1775.0MiB|1775.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |1764.0MiB|1764.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |793.0MiB|793.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |1767.0MiB|1767.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |1760.0MiB|1760.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |1837.0MiB|1837.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |1828.0MiB|1828.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |3445.0MiB|3445.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |1772.0MiB|1772.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |245.0MiB|245.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |258.0MiB|258.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  |291.0MiB|291.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |1774.0MiB|1774.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |1766.0MiB|1766.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |1159.0MiB|1159.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |1764.0MiB|1764.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |1771.0MiB|1771.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |1768.0MiB|1768.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |1767.0MiB|1767.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |1468.0MiB|1468.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |1775.0MiB|1775.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |1764.0MiB|1764.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |793.0MiB|793.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |1767.0MiB|1767.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |1760.0MiB|1760.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |1837.0MiB|1837.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |1828.0MiB|1828.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |3445.0MiB|3445.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |1772.0MiB|1772.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |245.0MiB|245.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |258.0MiB|258.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  |291.0MiB|291.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |1774.0MiB|1774.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |1766.0MiB|1766.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |1159.0MiB|1159.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |1764.0MiB|1764.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |1771.0MiB|1771.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |1768.0MiB|1768.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |1767.0MiB|1767.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |1468.0MiB|1468.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |1775.0MiB|1775.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |1764.0MiB|1764.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |793.0MiB|793.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |1767.0MiB|1767.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |1760.0MiB|1760.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |1837.0MiB|1837.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |1828.0MiB|1828.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |3445.0MiB|3445.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |1772.0MiB|1772.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-1065256.smt2                               | 600.851s |6309.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               | 600.855s |5902.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                | 600.812s |5839.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-993227.smt2                                | 600.725s |5465.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985918.smt2                                | 600.626s |5243.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                | 600.807s |5231.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-983194.smt2                              | 599.907s |5167.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                | 600.661s |5049.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                | 600.653s |4654.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                              | 600.681s |4633.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1072007.smt2                             | 153.788s |4613.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                | 600.689s |4599.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                | 600.788s |4583.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                              | 600.668s |4560.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                | 600.730s |4553.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-987361.smt2                                | 600.940s |4531.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-989891.smt2                              | 600.661s |4460.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-804609.smt2                                | 600.592s |4329.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1000539.smt2                               | 368.466s |4317.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-928960.smt2                                | 600.566s |4223.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-1065256.smt2                               | 600.851s |6309.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               | 600.855s |5902.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                | 600.812s |5839.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-993227.smt2                                | 600.725s |5465.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985918.smt2                                | 600.626s |5243.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                | 600.807s |5231.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-983194.smt2                              | 599.907s |5167.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                | 600.661s |5049.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                | 600.653s |4654.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                              | 600.681s |4633.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1072007.smt2                             | 153.788s |4613.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                | 600.689s |4599.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                | 600.788s |4583.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                              | 600.668s |4560.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                | 600.730s |4553.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-987361.smt2                                | 600.940s |4531.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-989891.smt2                              | 600.661s |4460.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-804609.smt2                                | 600.592s |4329.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1000539.smt2                               | 368.466s |4317.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-928960.smt2                                | 600.566s |4223.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |   3.811s  |   3.811s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |  74.261s  |  74.261s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |   3.754s  |   3.754s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |   3.851s  |   3.851s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   2.717s  |   2.717s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   3.823s  |   3.823s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |   3.679s  |   3.679s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   4.531s  |   4.531s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |   3.770s  |   3.770s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |   2.914s  |   2.914s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |   3.736s  |   3.736s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   4.105s  |   4.105s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   2.468s  |   2.468s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   3.696s  |   3.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   4.789s  |   4.789s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   3.139s  |   3.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   3.149s  |   3.149s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   4.421s  |   4.421s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   3.745s  |   3.745s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |   3.672s  |   3.672s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |   3.788s  |   3.788s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |   4.279s  |   4.279s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |   3.816s  |   3.816s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |   3.048s  |   3.048s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |   2.833s  |   2.833s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |   4.247s  |   4.247s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-12.smt2                       |   3.639s  |   3.639s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |   3.795s  |   3.795s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |   3.652s  |   3.652s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-15.smt2                       |   3.282s  |   3.282s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-00.smt2                      |   5.338s  |   5.338s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-01.smt2                      |   5.274s  |   5.274s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-02.smt2                      |   5.850s  |   5.850s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-03.smt2                      |   5.427s  |   5.427s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-07.smt2                      |   5.278s  |   5.278s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-08.smt2                      |   3.789s  |   3.789s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-09.smt2                      |   5.462s  |   5.462s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-10.smt2                      |   4.629s  |   4.629s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-11.smt2                      |   6.274s  |   6.274s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-12.smt2                      |   4.305s  |   4.305s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-13.smt2                      |   5.660s  |   5.660s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-14.smt2                      |   3.861s  |   3.861s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-15.smt2                      |   4.443s  |   4.443s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-00.smt2                      |   5.602s  |   5.602s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-08.smt2                      |   3.872s  |   3.872s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-09.smt2                      |   5.579s  |   5.579s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-10.smt2                      |   5.286s  |   5.286s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-11.smt2                      |   4.263s  |   4.263s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-12.smt2                      |   5.281s  |   5.281s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-13.smt2                      |   5.706s  |   5.706s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-14.smt2                      |   6.035s  |   6.035s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-15.smt2                      |   5.687s  |   5.687s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20231117-c_inference/80_80_71_17_unsat.smt2                          | 600.408s  | 600.408s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/RWS/Example_15.txt.smt2                                              | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/RWS/Example_18.txt.smt2                                              | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/RWS/Example_9.txt.smt2                                               | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1000539.smt2                                | 368.466s  | 368.466s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1007795.smt2                                |   5.850s  |   5.850s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                                | 600.855s  | 600.855s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1065256.smt2                                | 600.851s  | 600.851s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1096871.smt2                                |  84.016s  |  84.016s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1107622.smt2                                |  20.418s  |  20.418s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1121941.smt2                                |  28.795s  |  28.795s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1145584.smt2                                |  51.725s  |  51.725s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1148089.smt2                                |  60.089s  |  60.089s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1185949.smt2                                |  22.139s  |  22.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-391798.smt2                                 | 502.648s  | 502.648s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-392137.smt2                                 |   8.391s  |   8.391s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-408585.smt2                                 |  84.294s  |  84.294s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-415996.smt2                                 |  10.272s  |  10.272s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-478122.smt2                                 | 388.492s  | 388.492s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-481231.smt2                                 |  21.634s  |  21.634s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-487307.smt2                                 | 600.399s  | 600.399s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-506600.smt2                                 | 600.437s  | 600.437s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-518109.smt2                                 | 141.711s  | 141.711s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-526410.smt2                                 |   2.844s  |   2.844s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-533042.smt2                                 | 600.390s  | 600.390s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-551279.smt2                                 | 327.670s  | 327.670s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-569261.smt2                                 | 146.801s  | 146.801s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-618384.smt2                                 |  17.373s  |  17.373s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-644402.smt2                                 | 600.475s  | 600.475s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-654327.smt2                                 | 235.934s  | 235.934s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-655888.smt2                                 | 600.557s  | 600.557s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-687518.smt2                                 | 600.481s  | 600.481s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-689472.smt2                                 |   9.504s  |   9.504s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-765743.smt2                                 | 600.530s  | 600.530s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                 | 600.689s  | 600.689s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-804609.smt2                                 | 600.592s  | 600.592s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                 | 600.653s  | 600.653s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-864173.smt2                                 |  24.343s  |  24.343s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                 | 600.788s  | 600.788s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-901628.smt2                                 |  16.761s  |  16.761s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                 | 600.730s  | 600.730s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                 | 600.807s  | 600.807s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-906218.smt2                                 |  13.197s  |  13.197s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-916576.smt2                                 |   6.648s  |   6.648s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-928134.smt2                                 |   8.429s  |   8.429s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-928960.smt2                                 | 600.566s  | 600.566s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-943653.smt2                                 | 153.193s  | 153.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                 | 600.661s  | 600.661s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                 | 600.812s  | 600.812s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-985918.smt2                                 | 600.626s  | 600.626s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-987361.smt2                                 | 600.940s  | 600.940s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-993227.smt2                                 | 600.725s  | 600.725s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER10-13-fair.smt2                                       |  28.367s  |  28.367s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER10-14-fair.smt2                                       |  72.892s  |  72.892s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER11-14-fair.smt2                                       |  65.517s  |  65.517s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER11-15-fair.smt2                                       | 335.443s  | 335.443s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-13-48.smt2                           |  39.249s  |  39.249s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-13-50.smt2                           |  48.485s  |  48.485s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-14-49.smt2                           |  40.899s  |  40.899s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-14-50.smt2                           |  47.755s  |  47.755s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-16-48.smt2                           |  16.061s  |  16.061s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-16-49.smt2                           |  25.146s  |  25.146s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-16-50.smt2                           |  29.369s  |  29.369s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-17-47.smt2                           |  35.839s  |  35.839s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-17-50.smt2                           |  19.621s  |  19.621s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-18-46.smt2                           |  15.013s  |  15.013s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-18-48.smt2                           |  41.077s  |  41.077s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-18-50.smt2                           |  24.565s  |  24.565s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-19-49.smt2                           |  23.363s  |  23.363s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-19-50.smt2                           |  27.438s  |  27.438s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-20-45.smt2                           |  15.691s  |  15.691s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-22-48.smt2                           |  59.253s  |  59.253s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-22-49.smt2                           |  22.399s  |  22.399s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-22-50.smt2                           |  42.677s  |  42.677s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-24-49.smt2                           |  38.751s  |  38.751s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-25-50.smt2                           |  46.160s  |  46.160s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-27-47.smt2                           |  42.707s  |  42.707s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-27-49.smt2                           |  26.827s  |  26.827s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-27-50.smt2                           |  50.381s  |  50.381s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-28-48.smt2                           |  34.473s  |  34.473s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-28-49.smt2                           |  25.704s  |  25.704s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-28-50.smt2                           |  63.058s  |  63.058s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-29-48.smt2                           |  28.978s  |  28.978s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-29-50.smt2                           |  37.211s  |  37.211s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-30-48.smt2                           |  23.486s  |  23.486s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-32-47.smt2                           |  23.576s  |  23.576s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-32-49.smt2                           |  25.262s  |  25.262s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-32-50.smt2                           |  30.191s  |  30.191s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-33-50.smt2                           |  25.398s  |  25.398s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-34-45.smt2                           |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-34-48.smt2                           |  21.970s  |  21.970s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-45.smt2                           |  18.814s  |  18.814s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-46.smt2                           | 181.152s  | 181.152s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-47.smt2                           |  23.340s  |  23.340s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-45.smt2                           |  31.398s  |  31.398s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-46.smt2                           |  35.886s  |  35.886s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-47.smt2                           |  43.353s  |  43.353s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-48.smt2                           |  36.424s  |  36.424s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-49.smt2                           |  38.486s  |  38.486s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-50.smt2                           |  36.013s  |  36.013s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-45.smt2                           | 109.479s  | 109.479s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-46.smt2                           |  24.866s  |  24.866s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-47.smt2                           | 145.315s  | 145.315s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-48.smt2                           |  25.679s  |  25.679s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-45.smt2                           |  30.606s  |  30.606s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-46.smt2                           |  44.336s  |  44.336s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-47.smt2                           |  39.610s  |  39.610s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-48.smt2                           |  39.845s  |  39.845s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-49.smt2                           |  38.618s  |  38.618s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-50.smt2                           |  46.071s  |  46.071s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-45.smt2                           |  35.983s  |  35.983s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-46.smt2                           |  71.166s  |  71.166s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-47.smt2                           |  49.734s  |  49.734s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-48.smt2                           |  46.156s  |  46.156s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-49.smt2                           |  66.955s  |  66.955s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-50.smt2                           |  44.335s  |  44.335s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-4-45.smt2                            |  31.553s  |  31.553s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-4-48.smt2                            |  36.464s  |  36.464s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-4-49.smt2                            |  81.249s  |  81.249s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-4-50.smt2                            |  90.132s  |  90.132s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-45.smt2                           |  26.093s  |  26.093s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-46.smt2                           |  45.634s  |  45.634s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-47.smt2                           |  37.470s  |  37.470s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-48.smt2                           |  39.482s  |  39.482s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-49.smt2                           |  48.286s  |  48.286s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-50.smt2                           |  36.952s  |  36.952s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-45.smt2                           |  41.691s  |  41.691s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-46.smt2                           |  51.953s  |  51.953s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-47.smt2                           |  57.342s  |  57.342s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-48.smt2                           |  50.829s  |  50.829s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-49.smt2                           |  66.272s  |  66.272s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-50.smt2                           |  93.623s  |  93.623s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-45.smt2                           |  40.388s  |  40.388s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-46.smt2                           |  57.508s  |  57.508s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-47.smt2                           |  60.951s  |  60.951s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-48.smt2                           |  41.875s  |  41.875s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-49.smt2                           |  68.799s  |  68.799s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-50.smt2                           |  54.418s  |  54.418s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-45.smt2                           |  28.970s  |  28.970s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-46.smt2                           |  42.566s  |  42.566s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-47.smt2                           |  41.017s  |  41.017s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-48.smt2                           |  56.927s  |  56.927s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-49.smt2                           |  53.077s  |  53.077s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-50.smt2                           |  53.997s  |  53.997s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-45.smt2                           |  39.578s  |  39.578s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-46.smt2                           |  73.844s  |  73.844s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-47.smt2                           |  67.420s  |  67.420s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-48.smt2                           |  87.419s  |  87.419s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-49.smt2                           |  78.540s  |  78.540s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-50.smt2                           | 157.849s  | 157.849s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-45.smt2                           |  40.124s  |  40.124s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-46.smt2                           |  58.882s  |  58.882s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-47.smt2                           |  49.318s  |  49.318s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-48.smt2                           |  69.169s  |  69.169s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-49.smt2                           |  60.391s  |  60.391s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-50.smt2                           |  69.588s  |  69.588s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-45.smt2                           |  34.874s  |  34.874s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-46.smt2                           |  48.011s  |  48.011s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-47.smt2                           |  46.362s  |  46.362s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-48.smt2                           |  51.383s  |  51.383s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-49.smt2                           |  57.771s  |  57.771s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-50.smt2                           |  60.618s  |  60.618s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-45.smt2                           |  39.090s  |  39.090s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-46.smt2                           |  74.020s  |  74.020s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-47.smt2                           |  70.678s  |  70.678s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-48.smt2                           |  85.234s  |  85.234s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-49.smt2                           |  87.439s  |  87.439s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-50.smt2                           | 120.636s  | 120.636s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-45.smt2                           |  40.089s  |  40.089s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-46.smt2                           |  54.461s  |  54.461s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-47.smt2                           |  57.860s  |  57.860s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-48.smt2                           |  72.358s  |  72.358s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-49.smt2                           |  76.565s  |  76.565s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-50.smt2                           | 113.587s  | 113.587s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-45.smt2                           |  39.734s  |  39.734s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-46.smt2                           |  59.277s  |  59.277s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-47.smt2                           |  55.613s  |  55.613s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-48.smt2                           |  79.047s  |  79.047s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-49.smt2                           |  74.545s  |  74.545s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-50.smt2                           |  98.692s  |  98.692s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-5-47.smt2                            |  37.820s  |  37.820s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-5-48.smt2                            |  18.103s  |  18.103s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-5-49.smt2                            |  52.965s  |  52.965s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-5-50.smt2                            |  39.373s  |  39.373s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-45.smt2                           |  44.299s  |  44.299s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-46.smt2                           |  60.600s  |  60.600s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-47.smt2                           |  71.952s  |  71.952s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-48.smt2                           |  82.878s  |  82.878s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-49.smt2                           |  88.352s  |  88.352s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-50.smt2                           | 104.418s  | 104.418s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-45.smt2                           |  35.334s  |  35.334s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-46.smt2                           |  58.301s  |  58.301s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-47.smt2                           |  50.975s  |  50.975s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-48.smt2                           |  64.351s  |  64.351s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-49.smt2                           |  64.921s  |  64.921s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-50.smt2                           | 143.187s  | 143.187s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-45.smt2                           |  40.684s  |  40.684s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-46.smt2                           |  44.159s  |  44.159s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-47.smt2                           |  80.891s  |  80.891s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-48.smt2                           |  63.226s  |  63.226s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-49.smt2                           |  69.254s  |  69.254s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-50.smt2                           |  72.107s  |  72.107s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-45.smt2                           |  38.611s  |  38.611s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-46.smt2                           |  45.113s  |  45.113s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-47.smt2                           |  48.136s  |  48.136s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-48.smt2                           |  59.211s  |  59.211s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-49.smt2                           |  72.891s  |  72.891s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-50.smt2                           |  67.214s  |  67.214s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-45.smt2                           |  44.856s  |  44.856s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-46.smt2                           |  43.928s  |  43.928s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-47.smt2                           |  48.756s  |  48.756s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-48.smt2                           |  59.712s  |  59.712s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-49.smt2                           |  82.290s  |  82.290s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-50.smt2                           |  81.107s  |  81.107s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-46.smt2                           |  49.656s  |  49.656s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-47.smt2                           |  52.793s  |  52.793s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-48.smt2                           |  60.236s  |  60.236s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-49.smt2                           |  82.344s  |  82.344s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-50.smt2                           |  80.070s  |  80.070s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-46.smt2                           |  57.931s  |  57.931s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-47.smt2                           |  66.105s  |  66.105s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-48.smt2                           |  66.504s  |  66.504s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-49.smt2                           |  70.605s  |  70.605s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-50.smt2                           |  83.705s  |  83.705s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-48.smt2                           |  60.151s  |  60.151s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-49.smt2                           |  59.183s  |  59.183s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-50.smt2                           |  64.802s  |  64.802s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-47.smt2                           |  55.539s  |  55.539s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-48.smt2                           |  53.695s  |  53.695s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-49.smt2                           |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-50.smt2                           |  76.064s  |  76.064s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-59-48.smt2                           |  62.002s  |  62.002s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-59-49.smt2                           |  73.659s  |  73.659s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-59-50.smt2                           |  94.778s  |  94.778s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-60-48.smt2                           |  66.839s  |  66.839s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-60-49.smt2                           |  63.782s  |  63.782s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-60-50.smt2                           | 101.637s  | 101.637s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-61-49.smt2                           |  68.222s  |  68.222s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-61-50.smt2                           |  75.941s  |  75.941s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-62-49.smt2                           |  77.715s  |  77.715s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-62-50.smt2                           |  92.528s  |  92.528s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-63-50.smt2                           |  84.121s  |  84.121s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-46.smt2                            |  38.536s  |  38.536s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-47.smt2                            |  71.059s  |  71.059s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-48.smt2                            |  15.557s  |  15.557s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-49.smt2                            |  17.159s  |  17.159s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-50.smt2                            |  67.503s  |  67.503s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-46.smt2                            |  41.064s  |  41.064s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-47.smt2                            |  19.055s  |  19.055s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-48.smt2                            |  35.556s  |  35.556s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-49.smt2                            |  18.695s  |  18.695s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-50.smt2                            |  57.773s  |  57.773s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-46.smt2                   | 265.664s  | 265.664s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-47.smt2                   | 354.251s  | 354.251s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-48.smt2                   | 414.097s  | 414.097s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-49.smt2                   | 543.838s  | 543.838s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-50.smt2                   | 600.282s  | 600.282s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-46.smt2                   | 309.174s  | 309.174s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-47.smt2                   | 410.397s  | 410.397s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-48.smt2                   | 374.242s  | 374.242s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-49.smt2                   | 600.179s  | 600.179s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-50.smt2                   | 531.186s  | 531.186s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-46.smt2                   | 128.214s  | 128.214s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-47.smt2                   | 249.249s  | 249.249s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-48.smt2                   | 271.011s  | 271.011s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-49.smt2                   | 242.107s  | 242.107s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-50.smt2                   | 244.587s  | 244.587s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-46.smt2                   |  75.553s  |  75.553s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-47.smt2                   |  97.719s  |  97.719s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-48.smt2                   | 144.415s  | 144.415s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-49.smt2                   | 149.519s  | 149.519s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-50.smt2                   | 201.733s  | 201.733s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-47.smt2                    |  39.471s  |  39.471s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-48.smt2                    |  48.761s  |  48.761s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-49.smt2                    |  67.173s  |  67.173s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-50.smt2                    |  81.528s  |  81.528s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-46.smt2                    | 124.281s  | 124.281s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-47.smt2                    | 126.956s  | 126.956s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-48.smt2                    | 212.040s  | 212.040s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-49.smt2                    | 266.850s  | 266.850s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-50.smt2                    | 274.631s  | 274.631s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-46.smt2                    | 143.190s  | 143.190s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-47.smt2                    | 177.470s  | 177.470s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-48.smt2                    | 199.172s  | 199.172s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-49.smt2                    | 242.929s  | 242.929s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-50.smt2                    | 300.902s  | 300.902s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-8-47.smt2                    |  10.805s  |  10.805s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-8-49.smt2                    |  13.556s  |  13.556s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-8-50.smt2                    |  15.835s  |  15.835s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-13-50.smt2                         |  19.428s  |  19.428s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-14-50.smt2                         |  19.774s  |  19.774s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-16-50.smt2                         |  20.414s  |  20.414s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-17-50.smt2                         |  23.851s  |  23.851s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-19-50.smt2                         |  19.559s  |  19.559s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-2-50.smt2                          |  18.732s  |  18.732s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-21-50.smt2                         |  19.470s  |  19.470s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-22-50.smt2                         |  21.700s  |  21.700s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-23-50.smt2                         |  20.652s  |  20.652s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-25-50.smt2                         |  76.080s  |  76.080s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-26-50.smt2                         |  69.997s  |  69.997s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-27-50.smt2                         |  65.285s  |  65.285s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-28-50.smt2                         | 105.688s  | 105.688s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-29-50.smt2                         |  68.904s  |  68.904s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-30-50.smt2                         |  20.400s  |  20.400s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-31-50.smt2                         |  21.841s  |  21.841s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-32-50.smt2                         |  21.561s  |  21.561s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-33-50.smt2                         |  19.785s  |  19.785s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-35-50.smt2                         |  22.440s  |  22.440s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-37-50.smt2                         |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-38-50.smt2                         |  22.919s  |  22.919s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-39-50.smt2                         |  34.180s  |  34.180s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-40-50.smt2                         |  35.332s  |  35.332s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-41-50.smt2                         |  53.564s  |  53.564s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-42-50.smt2                         |  22.521s  |  22.521s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-43-50.smt2                         |  43.741s  |  43.741s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-44-50.smt2                         |  44.194s  |  44.194s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-45-50.smt2                         |  23.756s  |  23.756s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-46-50.smt2                         |  22.749s  |  22.749s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-47-50.smt2                         |  24.866s  |  24.866s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-48-50.smt2                         |  22.440s  |  22.440s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-49-50.smt2                         |  26.509s  |  26.509s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-5-50.smt2                          |  18.761s  |  18.761s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-50-50.smt2                         |  42.139s  |  42.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-51-50.smt2                         |  35.814s  |  35.814s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-52-50.smt2                         |  32.595s  |  32.595s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-53-50.smt2                         |  36.572s  |  36.572s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-54-50.smt2                         |  35.687s  |  35.687s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-55-50.smt2                         |  32.682s  |  32.682s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-58-50.smt2                         |  33.448s  |  33.448s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-59-50.smt2                         |  24.007s  |  24.007s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-60-50.smt2                         |  24.115s  |  24.115s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-61-50.smt2                         |  24.343s  |  24.343s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-63-50.smt2                         |  32.905s  |  32.905s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-64-50.smt2                         |  25.784s  |  25.784s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-65-50.smt2                         |  29.158s  |  29.158s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-67-50.smt2                         |  28.860s  |  28.860s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-68-50.smt2                         |  29.045s  |  29.045s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-69-50.smt2                         |  28.003s  |  28.003s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-70-50.smt2                         |  26.667s  |  26.667s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-9-50.smt2                          |  19.738s  |  19.738s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-46.smt2                           |  28.541s  |  28.541s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-47.smt2                           |  30.314s  |  30.314s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-48.smt2                           |  36.240s  |  36.240s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-49.smt2                           |  37.358s  |  37.358s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-50.smt2                           |  46.678s  |  46.678s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-46.smt2                           |  34.340s  |  34.340s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-47.smt2                           |  34.318s  |  34.318s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-48.smt2                           |  35.207s  |  35.207s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-50.smt2                           |  49.202s  |  49.202s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-46.smt2                          | 120.106s  | 120.106s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-47.smt2                          | 336.510s  | 336.510s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-48.smt2                          |  70.862s  |  70.862s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-49.smt2                          | 339.308s  | 339.308s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-50.smt2                          | 600.186s  | 600.186s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-46.smt2                          | 180.289s  | 180.289s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-47.smt2                          | 409.097s  | 409.097s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-48.smt2                          |  82.952s  |  82.952s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-49.smt2                          | 511.719s  | 511.719s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-50.smt2                          | 312.518s  | 312.518s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-46.smt2                          |  30.766s  |  30.766s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-47.smt2                          |  33.018s  |  33.018s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-48.smt2                          |  33.432s  |  33.432s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-49.smt2                          |  45.333s  |  45.333s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-50.smt2                          |  44.502s  |  44.502s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-46.smt2                          | 184.337s  | 184.337s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-47.smt2                          | 304.307s  | 304.307s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-48.smt2                          |  67.486s  |  67.486s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-49.smt2                          | 394.884s  | 394.884s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-50.smt2                          | 409.718s  | 409.718s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-46.smt2                          |  26.924s  |  26.924s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-47.smt2                          |  30.366s  |  30.366s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-49.smt2                          |  46.717s  |  46.717s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-50.smt2                          |  47.417s  |  47.417s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-46.smt2                          |  26.470s  |  26.470s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-47.smt2                          |  31.020s  |  31.020s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-48.smt2                          |  31.589s  |  31.589s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-49.smt2                          |  43.687s  |  43.687s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-50.smt2                          |  47.094s  |  47.094s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-46.smt2                          | 170.359s  | 170.359s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-47.smt2                          | 225.179s  | 225.179s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-48.smt2                          |  70.965s  |  70.965s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-49.smt2                          | 480.035s  | 480.035s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-50.smt2                          | 347.382s  | 347.382s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-46.smt2                          | 232.857s  | 232.857s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-47.smt2                          | 205.364s  | 205.364s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-48.smt2                          |  52.917s  |  52.917s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-49.smt2                          | 358.601s  | 358.601s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-50.smt2                          | 332.555s  | 332.555s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-46.smt2                          |  31.545s  |  31.545s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-47.smt2                          |  32.221s  |  32.221s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-48.smt2                          |  39.867s  |  39.867s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-49.smt2                          |  36.522s  |  36.522s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-50.smt2                          |  47.636s  |  47.636s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-46.smt2                          | 158.509s  | 158.509s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-47.smt2                          | 192.748s  | 192.748s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-48.smt2                          |  53.410s  |  53.410s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-49.smt2                          | 506.382s  | 506.382s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-50.smt2                          | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-46.smt2                           | 110.411s  | 110.411s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-47.smt2                           | 294.578s  | 294.578s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-48.smt2                           |  70.684s  |  70.684s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-49.smt2                           | 331.922s  | 331.922s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-50.smt2                           | 358.027s  | 358.027s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-46.smt2                          |  34.719s  |  34.719s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-47.smt2                          |  31.627s  |  31.627s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-48.smt2                          |  38.731s  |  38.731s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-49.smt2                          |  40.848s  |  40.848s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-50.smt2                          |  57.474s  |  57.474s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-46.smt2                          |  33.446s  |  33.446s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-47.smt2                          |  70.628s  |  70.628s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-48.smt2                          |  47.208s  |  47.208s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-49.smt2                          |  54.488s  |  54.488s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-50.smt2                          |  67.660s  |  67.660s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-46.smt2                          | 284.061s  | 284.061s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-47.smt2                          | 253.231s  | 253.231s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-48.smt2                          |  54.664s  |  54.664s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-49.smt2                          | 173.931s  | 173.931s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-46.smt2                          | 107.629s  | 107.629s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-47.smt2                          | 133.073s  | 133.073s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-48.smt2                          |  49.922s  |  49.922s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-49.smt2                          | 496.856s  | 496.856s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-50.smt2                          | 294.482s  | 294.482s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-46.smt2                          |  39.609s  |  39.609s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-47.smt2                          |  36.233s  |  36.233s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-48.smt2                          |  37.854s  |  37.854s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-49.smt2                          |  45.993s  |  45.993s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-50.smt2                          |  56.399s  |  56.399s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-46.smt2                          | 207.842s  | 207.842s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-47.smt2                          | 156.195s  | 156.195s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-48.smt2                          |  55.650s  |  55.650s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-49.smt2                          | 537.477s  | 537.477s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-50.smt2                          | 600.185s  | 600.185s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-46.smt2                          |  39.756s  |  39.756s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-47.smt2                          |  44.651s  |  44.651s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-48.smt2                          |  61.025s  |  61.025s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-49.smt2                          |  66.302s  |  66.302s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-50.smt2                          |  63.062s  |  63.062s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-46.smt2                          |  44.510s  |  44.510s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-47.smt2                          |  47.572s  |  47.572s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-48.smt2                          |  77.359s  |  77.359s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-49.smt2                          |  76.991s  |  76.991s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-50.smt2                          |  85.895s  |  85.895s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-47.smt2                          | 513.035s  | 513.035s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-48.smt2                          | 600.167s  | 600.167s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-49.smt2                          | 600.180s  | 600.180s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-50.smt2                          | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-46.smt2                          | 348.528s  | 348.528s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-47.smt2                          |  39.859s  |  39.859s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-48.smt2                          | 352.646s  | 352.646s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-49.smt2                          | 600.194s  | 600.194s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-50.smt2                          | 600.188s  | 600.188s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-46.smt2                           | 300.892s  | 300.892s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-47.smt2                           | 212.295s  | 212.295s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-48.smt2                           |  68.469s  |  68.469s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-49.smt2                           | 560.730s  | 560.730s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-50.smt2                           | 600.156s  | 600.156s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-46.smt2                          | 369.937s  | 369.937s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-47.smt2                          | 475.806s  | 475.806s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-48.smt2                          | 600.158s  | 600.158s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-49.smt2                          | 600.155s  | 600.155s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-50.smt2                          | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-46.smt2                          |  60.090s  |  60.090s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-47.smt2                          |  52.317s  |  52.317s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-48.smt2                          |  42.020s  |  42.020s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-49.smt2                          |  62.510s  |  62.510s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-50.smt2                          |  91.135s  |  91.135s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-46.smt2                          | 161.366s  | 161.366s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-47.smt2                          | 163.055s  | 163.055s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-48.smt2                          |  53.498s  |  53.498s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-49.smt2                          | 493.860s  | 493.860s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-50.smt2                          | 459.190s  | 459.190s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-46.smt2                          | 283.786s  | 283.786s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-47.smt2                          | 368.870s  | 368.870s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-48.smt2                          | 238.464s  | 238.464s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-49.smt2                          | 600.229s  | 600.229s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-50.smt2                          | 600.165s  | 600.165s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-46.smt2                          |  53.618s  |  53.618s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-47.smt2                          | 331.277s  | 331.277s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-48.smt2                          | 325.156s  | 325.156s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-49.smt2                          |  95.922s  |  95.922s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-50.smt2                          | 600.165s  | 600.165s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-46.smt2                          |  64.513s  |  64.513s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-47.smt2                          |  87.315s  |  87.315s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-48.smt2                          |  96.590s  |  96.590s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-49.smt2                          |  99.962s  |  99.962s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-50.smt2                          | 107.243s  | 107.243s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-46.smt2                          |  59.165s  |  59.165s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-47.smt2                          |  56.837s  |  56.837s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-48.smt2                          |  86.500s  |  86.500s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-49.smt2                          | 112.979s  | 112.979s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-50.smt2                          | 179.741s  | 179.741s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-47.smt2                          |  14.803s  |  14.803s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-48.smt2                          | 359.741s  | 359.741s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-49.smt2                          | 600.178s  | 600.178s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-50.smt2                          | 600.156s  | 600.156s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-46.smt2                          | 110.042s  | 110.042s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-47.smt2                          | 178.954s  | 178.954s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-48.smt2                          |  46.767s  |  46.767s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-49.smt2                          | 258.677s  | 258.677s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-50.smt2                          | 436.674s  | 436.674s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-46.smt2                          | 150.186s  | 150.186s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-47.smt2                          |  80.950s  |  80.950s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-48.smt2                          | 277.075s  | 277.075s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-49.smt2                          | 567.369s  | 567.369s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-50.smt2                          | 149.214s  | 149.214s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-46.smt2                           |  29.418s  |  29.418s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-47.smt2                           |  40.895s  |  40.895s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-48.smt2                           |  37.670s  |  37.670s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-49.smt2                           |  45.415s  |  45.415s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-50.smt2                           |  57.737s  |  57.737s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-46.smt2                          | 214.701s  | 214.701s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-47.smt2                          | 245.655s  | 245.655s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-48.smt2                          | 418.320s  | 418.320s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-49.smt2                          | 600.168s  | 600.168s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-50.smt2                          | 600.177s  | 600.177s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-46.smt2                          | 254.100s  | 254.100s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-47.smt2                          | 249.245s  | 249.245s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-48.smt2                          | 435.733s  | 435.733s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-49.smt2                          | 503.497s  | 503.497s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-50.smt2                          | 600.149s  | 600.149s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-47.smt2                          |  15.549s  |  15.549s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-48.smt2                          |  17.454s  |  17.454s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-49.smt2                          | 510.177s  | 510.177s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-50.smt2                          | 600.248s  | 600.248s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-46.smt2                          |  93.998s  |  93.998s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-47.smt2                          | 187.401s  | 187.401s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-48.smt2                          |  52.042s  |  52.042s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-49.smt2                          | 362.740s  | 362.740s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-50.smt2                          | 466.800s  | 466.800s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-46.smt2                          | 148.639s  | 148.639s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-47.smt2                          | 208.445s  | 208.445s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-48.smt2                          | 212.023s  | 212.023s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-49.smt2                          | 211.373s  | 211.373s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-50.smt2                          | 600.158s  | 600.158s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-46.smt2                          | 123.441s  | 123.441s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-47.smt2                          | 152.929s  | 152.929s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-48.smt2                          |  46.239s  |  46.239s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-49.smt2                          | 389.965s  | 389.965s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-50.smt2                          | 347.069s  | 347.069s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-46.smt2                          | 125.146s  | 125.146s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-47.smt2                          | 113.796s  | 113.796s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-48.smt2                          | 310.386s  | 310.386s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-49.smt2                          | 405.583s  | 405.583s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-50.smt2                          | 433.857s  | 433.857s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-46.smt2                          | 108.870s  | 108.870s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-47.smt2                          | 125.495s  | 125.495s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-48.smt2                          | 111.672s  | 111.672s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-49.smt2                          | 399.661s  | 399.661s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-50.smt2                          | 581.618s  | 581.618s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-46.smt2                          | 116.096s  | 116.096s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-47.smt2                          | 115.800s  | 115.800s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-48.smt2                          | 162.390s  | 162.390s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-49.smt2                          | 298.093s  | 298.093s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-50.smt2                          | 255.228s  | 255.228s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-46.smt2                          |  74.929s  |  74.929s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-47.smt2                          | 141.347s  | 141.347s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-48.smt2                          |  49.775s  |  49.775s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-49.smt2                          | 282.576s  | 282.576s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-50.smt2                          | 254.980s  | 254.980s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-46.smt2                           |  28.208s  |  28.208s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-47.smt2                           |  32.387s  |  32.387s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-48.smt2                           |  37.947s  |  37.947s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-49.smt2                           |  45.321s  |  45.321s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-50.smt2                           |  48.305s  |  48.305s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-46.smt2                          | 116.884s  | 116.884s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-47.smt2                          | 123.167s  | 123.167s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-48.smt2                          | 154.931s  | 154.931s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-49.smt2                          | 263.951s  | 263.951s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-50.smt2                          | 181.204s  | 181.204s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-47.smt2                          | 129.071s  | 129.071s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-48.smt2                          |  47.533s  |  47.533s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-49.smt2                          | 293.868s  | 293.868s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-50.smt2                          | 350.689s  | 350.689s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-46.smt2                           |  24.778s  |  24.778s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-47.smt2                           |  30.353s  |  30.353s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-48.smt2                           |  34.146s  |  34.146s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-49.smt2                           |  41.601s  |  41.601s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-50.smt2                           |  44.735s  |  44.735s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-46.smt2                           |  28.472s  |  28.472s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-47.smt2                           |  33.598s  |  33.598s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-48.smt2                           |  35.517s  |  35.517s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-49.smt2                           |  42.128s  |  42.128s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-50.smt2                           |  49.109s  |  49.109s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-46.smt2                           | 320.683s  | 320.683s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-47.smt2                           |  89.711s  |  89.711s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-48.smt2                           |  72.891s  |  72.891s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-50.smt2                           | 600.260s  | 600.260s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-46.smt2                           | 170.041s  | 170.041s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-47.smt2                           | 269.506s  | 269.506s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-48.smt2                           |  65.941s  |  65.941s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-49.smt2                           | 486.830s  | 486.830s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-50.smt2                           | 500.049s  | 500.049s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-46.smt2                         |  93.908s  |  93.908s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-47.smt2                         |  73.294s  |  73.294s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-48.smt2                         |  54.536s  |  54.536s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-49.smt2                         | 137.090s  | 137.090s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-50.smt2                         |  99.770s  |  99.770s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-46.smt2                         |  83.582s  |  83.582s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-47.smt2                         |  77.085s  |  77.085s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-48.smt2                         | 272.770s  | 272.770s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-49.smt2                         | 193.797s  | 193.797s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-50.smt2                         | 201.755s  | 201.755s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-46.smt2                        | 432.889s  | 432.889s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-47.smt2                        | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-48.smt2                        | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-49.smt2                        | 303.024s  | 303.024s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-50.smt2                        | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-46.smt2                        |  56.242s  |  56.242s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-47.smt2                        | 269.757s  | 269.757s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-48.smt2                        | 277.843s  | 277.843s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-49.smt2                        | 330.684s  | 330.684s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-50.smt2                        |  79.503s  |  79.503s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-46.smt2                        | 104.962s  | 104.962s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-47.smt2                        | 348.056s  | 348.056s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-48.smt2                        | 131.091s  | 131.091s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-49.smt2                        | 450.975s  | 450.975s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-50.smt2                        | 200.536s  | 200.536s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-46.smt2                        | 158.596s  | 158.596s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-47.smt2                        | 263.569s  | 263.569s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-48.smt2                        | 210.258s  | 210.258s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-49.smt2                        | 325.073s  | 325.073s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-50.smt2                        | 403.510s  | 403.510s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-46.smt2                        |  54.864s  |  54.864s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-47.smt2                        | 144.986s  | 144.986s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-48.smt2                        |  34.652s  |  34.652s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-49.smt2                        | 324.038s  | 324.038s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-50.smt2                        | 405.693s  | 405.693s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-46.smt2                        |  27.900s  |  27.900s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-47.smt2                        | 192.218s  | 192.218s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-48.smt2                        | 156.437s  | 156.437s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-49.smt2                        | 259.070s  | 259.070s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-50.smt2                        | 600.161s  | 600.161s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-46.smt2                        | 137.960s  | 137.960s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-47.smt2                        |  87.471s  |  87.471s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-48.smt2                        | 116.964s  | 116.964s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-49.smt2                        | 153.862s  | 153.862s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-50.smt2                        |  96.816s  |  96.816s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-46.smt2                        | 146.557s  | 146.557s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-47.smt2                        |  58.584s  |  58.584s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-48.smt2                        |  41.001s  |  41.001s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-49.smt2                        |  50.995s  |  50.995s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-50.smt2                        | 139.146s  | 139.146s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-46.smt2                        |  55.966s  |  55.966s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-47.smt2                        | 106.867s  | 106.867s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-48.smt2                        |  74.807s  |  74.807s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-49.smt2                        |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-50.smt2                        | 101.120s  | 101.120s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-47.smt2                        |  86.117s  |  86.117s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-48.smt2                        |  84.985s  |  84.985s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-49.smt2                        | 239.100s  | 239.100s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-50.smt2                        | 225.468s  | 225.468s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-46.smt2                         |  65.778s  |  65.778s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-47.smt2                         | 270.984s  | 270.984s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-48.smt2                         |  81.975s  |  81.975s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-49.smt2                         | 337.844s  | 337.844s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-50.smt2                         | 190.524s  | 190.524s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-46.smt2                        |  55.010s  |  55.010s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-47.smt2                        |  24.879s  |  24.879s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-48.smt2                        |  34.792s  |  34.792s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-49.smt2                        |  85.463s  |  85.463s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-50.smt2                        | 282.144s  | 282.144s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-46.smt2                        |  43.991s  |  43.991s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-47.smt2                        |  98.323s  |  98.323s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-48.smt2                        |  35.128s  |  35.128s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-49.smt2                        |  38.472s  |  38.472s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-50.smt2                        | 184.840s  | 184.840s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-46.smt2                        |  35.915s  |  35.915s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-47.smt2                        |  65.773s  |  65.773s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-48.smt2                        |  74.304s  |  74.304s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-49.smt2                        |  91.236s  |  91.236s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-50.smt2                        | 168.605s  | 168.605s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-46.smt2                        |  40.983s  |  40.983s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-47.smt2                        |  33.782s  |  33.782s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-48.smt2                        |  50.839s  |  50.839s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-49.smt2                        | 175.259s  | 175.259s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-50.smt2                        |  88.469s  |  88.469s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-46.smt2                        |  47.061s  |  47.061s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-47.smt2                        |  70.533s  |  70.533s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-48.smt2                        | 115.932s  | 115.932s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-49.smt2                        | 152.740s  | 152.740s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-50.smt2                        | 261.360s  | 261.360s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-46.smt2                         | 159.811s  | 159.811s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-47.smt2                         |  95.148s  |  95.148s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-48.smt2                         | 384.280s  | 384.280s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-49.smt2                         | 130.814s  | 130.814s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-50.smt2                         | 224.892s  | 224.892s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-46.smt2                         |  45.409s  |  45.409s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-47.smt2                         |  47.488s  |  47.488s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-48.smt2                         | 434.245s  | 434.245s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-49.smt2                         | 521.217s  | 521.217s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-50.smt2                         | 504.008s  | 504.008s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-46.smt2                         | 187.759s  | 187.759s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-47.smt2                         | 261.609s  | 261.609s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-48.smt2                         | 275.840s  | 275.840s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-49.smt2                         | 175.015s  | 175.015s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-50.smt2                         | 419.292s  | 419.292s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-46.smt2                         |  64.056s  |  64.056s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-47.smt2                         |  83.360s  |  83.360s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-48.smt2                         | 249.570s  | 249.570s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-49.smt2                         | 391.211s  | 391.211s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-46.smt2                         |  55.759s  |  55.759s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-47.smt2                         | 356.439s  | 356.439s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-48.smt2                         | 221.953s  | 221.953s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-49.smt2                         |  64.656s  |  64.656s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-50.smt2                         | 101.285s  | 101.285s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-46.smt2                         |  77.894s  |  77.894s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-47.smt2                         | 193.340s  | 193.340s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-48.smt2                         | 156.679s  | 156.679s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-49.smt2                         | 173.836s  | 173.836s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-50.smt2                         | 336.963s  | 336.963s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-46.smt2                         |  92.282s  |  92.282s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-47.smt2                         | 196.376s  | 196.376s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-48.smt2                         |  48.942s  |  48.942s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-49.smt2                         | 216.828s  | 216.828s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-50.smt2                         |  86.597s  |  86.597s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1015084.smt2                              |   9.032s  |   9.032s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1072007.smt2                              | 153.788s  | 153.788s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1192684.smt2                              |  21.522s  |  21.522s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-373262.smt2                               | 600.240s  | 600.240s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-394532.smt2                               | 149.276s  | 149.276s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-413904.smt2                               |  16.229s  |  16.229s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-416752.smt2                               | 369.546s  | 369.546s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-479884.smt2                               | 317.607s  | 317.607s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-495717.smt2                               | 155.290s  | 155.290s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-496324.smt2                               |  48.984s  |  48.984s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-527358.smt2                               |   3.774s  |   3.774s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-556171.smt2                               | 600.304s  | 600.304s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-579281.smt2                               | 600.339s  | 600.339s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-603294.smt2                               | 537.477s  | 537.477s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-614657.smt2                               |  80.517s  |  80.517s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-645855.smt2                               | 375.655s  | 375.655s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-649834.smt2                               |   5.606s  |   5.606s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-658040.smt2                               | 292.919s  | 292.919s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-687179.smt2                               | 317.723s  | 317.723s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-696340.smt2                               | 420.563s  | 420.563s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-705295.smt2                               |  11.451s  |  11.451s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-715402.smt2                               | 600.701s  | 600.701s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-729964.smt2                               | 139.799s  | 139.799s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-735583.smt2                               | 600.562s  | 600.562s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-737829.smt2                               | 600.528s  | 600.528s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-740637.smt2                               | 600.573s  | 600.573s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-758897.smt2                               |  12.943s  |  12.943s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-762853.smt2                               | 599.202s  | 599.202s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-794687.smt2                               |  10.618s  |  10.618s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-797738.smt2                               | 600.722s  | 600.722s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                               | 600.668s  | 600.668s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                               | 600.681s  | 600.681s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-901996.smt2                               |  12.852s  |  12.852s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-906586.smt2                               |  37.345s  |  37.345s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-916807.smt2                               |   9.899s  |   9.899s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-917322.smt2                               |  14.313s  |  14.313s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-983194.smt2                               | 599.907s  | 599.907s  |   0.000s  | 0.0%|
</details>
