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
Job tag: Z3-threads-8-QF_LIA_hard-timeout10min-no_core_min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: f880fdccee614547c38c19beb7af5a027961646b
Z3 branch: core_min
Z3 options: "-T:600 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.core_minimize=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_LIA.tar.zst?download=1
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-QF_LIA_hard-timeout10min-no_core_min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: f880fdccee614547c38c19beb7af5a027961646b
Z3 branch: core_min
Z3 options: "-T:600 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.core_minimize=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_LIA.tar.zst?download=1
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |   3.945s  |   3.945s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |  57.017s  |  57.017s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |   4.433s  |   4.433s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |   5.385s  |   5.385s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   3.396s  |   3.396s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   4.558s  |   4.558s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |   4.649s  |   4.649s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   4.902s  |   4.902s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |   4.285s  |   4.285s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |   3.577s  |   3.577s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |   4.439s  |   4.439s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   4.305s  |   4.305s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   3.352s  |   3.352s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   4.414s  |   4.414s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   4.998s  |   4.998s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   3.791s  |   3.791s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   3.849s  |   3.849s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   5.193s  |   5.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   4.260s  |   4.260s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |   3.945s  |   3.945s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |  57.017s  |  57.017s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |   4.433s  |   4.433s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |   5.385s  |   5.385s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   3.396s  |   3.396s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   4.558s  |   4.558s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |   4.649s  |   4.649s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   4.902s  |   4.902s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |   4.285s  |   4.285s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |   3.577s  |   3.577s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |   4.439s  |   4.439s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   4.305s  |   4.305s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   3.352s  |   3.352s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   4.414s  |   4.414s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   4.998s  |   4.998s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   3.791s  |   3.791s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   3.849s  |   3.849s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   5.193s  |   5.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   4.260s  |   4.260s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |   3.945s  |   3.945s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |  57.017s  |  57.017s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |   4.433s  |   4.433s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |   5.385s  |   5.385s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   3.396s  |   3.396s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   4.558s  |   4.558s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |   4.649s  |   4.649s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   4.902s  |   4.902s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |   4.285s  |   4.285s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |   3.577s  |   3.577s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |   4.439s  |   4.439s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   4.305s  |   4.305s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   3.352s  |   3.352s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   4.414s  |   4.414s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   4.998s  |   4.998s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   3.791s  |   3.791s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   3.849s  |   3.849s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   5.193s  |   5.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   4.260s  |   4.260s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |   3.945s  |   3.945s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |  57.017s  |  57.017s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |   4.433s  |   4.433s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |   5.385s  |   5.385s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   3.396s  |   3.396s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   4.558s  |   4.558s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |   4.649s  |   4.649s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   4.902s  |   4.902s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |   4.285s  |   4.285s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |   3.577s  |   3.577s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |   4.439s  |   4.439s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   4.305s  |   4.305s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   3.352s  |   3.352s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   4.414s  |   4.414s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   4.998s  |   4.998s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   3.791s  |   3.791s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   3.849s  |   3.849s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   5.193s  |   5.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   4.260s  |   4.260s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-1065256.smt2                               | 601.682s |7693.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               | 601.065s |7405.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-993227.smt2                                | 601.038s |6587.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                | 600.962s |6416.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-735583.smt2                              | 600.960s |4699.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                | 600.935s |5563.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                | 600.904s |5692.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                | 600.892s |7015.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                | 600.850s |6157.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-644402.smt2                                | 600.813s |4068.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                | 600.812s |5565.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-989891.smt2                              | 600.805s |5480.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                | 600.798s |5709.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-715402.smt2                              | 600.794s |4503.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-987361.smt2                                | 600.792s |5568.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985918.smt2                                | 600.771s |6338.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                              | 600.744s |5708.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-740637.smt2                              | 600.733s |3929.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-655888.smt2                                | 600.676s |4360.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                              | 600.674s |5613.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-1065256.smt2                               | 601.682s |7693.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               | 601.065s |7405.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-993227.smt2                                | 601.038s |6587.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                | 600.962s |6416.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-735583.smt2                              | 600.960s |4699.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                | 600.935s |5563.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                | 600.904s |5692.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                | 600.892s |7015.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                | 600.850s |6157.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-644402.smt2                                | 600.813s |4068.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                | 600.812s |5565.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-989891.smt2                              | 600.805s |5480.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                | 600.798s |5709.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-715402.smt2                              | 600.794s |4503.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-987361.smt2                                | 600.792s |5568.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985918.smt2                                | 600.771s |6338.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                              | 600.744s |5708.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-740637.smt2                              | 600.733s |3929.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-655888.smt2                                | 600.676s |4360.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                              | 600.674s |5613.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |275.0MiB|275.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |284.0MiB|284.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  |324.0MiB|324.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |2126.0MiB|2126.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |2130.0MiB|2130.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |1363.0MiB|1363.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |2132.0MiB|2132.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |2128.0MiB|2128.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |2135.0MiB|2135.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |2132.0MiB|2132.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |1752.0MiB|1752.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |2129.0MiB|2129.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |2134.0MiB|2134.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |766.0MiB|766.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |2127.0MiB|2127.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |2137.0MiB|2137.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |2206.0MiB|2206.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |2207.0MiB|2207.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |4204.0MiB|4204.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |2142.0MiB|2142.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |275.0MiB|275.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |284.0MiB|284.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  |324.0MiB|324.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |2126.0MiB|2126.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |2130.0MiB|2130.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |1363.0MiB|1363.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |2132.0MiB|2132.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |2128.0MiB|2128.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |2135.0MiB|2135.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |2132.0MiB|2132.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |1752.0MiB|1752.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |2129.0MiB|2129.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |2134.0MiB|2134.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |766.0MiB|766.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |2127.0MiB|2127.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |2137.0MiB|2137.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |2206.0MiB|2206.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |2207.0MiB|2207.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |4204.0MiB|4204.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |2142.0MiB|2142.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |275.0MiB|275.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |284.0MiB|284.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  |324.0MiB|324.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |2126.0MiB|2126.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |2130.0MiB|2130.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |1363.0MiB|1363.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |2132.0MiB|2132.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |2128.0MiB|2128.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |2135.0MiB|2135.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |2132.0MiB|2132.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |1752.0MiB|1752.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |2129.0MiB|2129.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |2134.0MiB|2134.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |766.0MiB|766.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |2127.0MiB|2127.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |2137.0MiB|2137.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |2206.0MiB|2206.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |2207.0MiB|2207.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |4204.0MiB|4204.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |2142.0MiB|2142.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |275.0MiB|275.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |284.0MiB|284.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  |324.0MiB|324.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |2126.0MiB|2126.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |2130.0MiB|2130.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |1363.0MiB|1363.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |2132.0MiB|2132.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |2128.0MiB|2128.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |2135.0MiB|2135.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |2132.0MiB|2132.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |1752.0MiB|1752.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |2129.0MiB|2129.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |2134.0MiB|2134.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |766.0MiB|766.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |2127.0MiB|2127.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |2137.0MiB|2137.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |2206.0MiB|2206.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |2207.0MiB|2207.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |4204.0MiB|4204.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |2142.0MiB|2142.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-1065256.smt2                               | 601.682s |7693.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               | 601.065s |7405.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                | 600.892s |7015.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-993227.smt2                                | 601.038s |6587.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                | 600.962s |6416.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985918.smt2                                | 600.771s |6338.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-983194.smt2                              | 507.300s |6259.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                | 600.850s |6157.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1072007.smt2                             | 172.669s |5839.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                | 600.798s |5709.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                              | 600.744s |5708.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                | 600.904s |5692.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-50.smt2                         | 600.591s |5691.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-50.smt2                         | 600.638s |5646.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                              | 600.674s |5613.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-987361.smt2                                | 600.792s |5568.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                | 600.812s |5565.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                | 600.935s |5563.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-989891.smt2                              | 600.805s |5480.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-48.smt2                         | 600.553s |5097.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-1065256.smt2                               | 601.682s |7693.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               | 601.065s |7405.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                | 600.892s |7015.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-993227.smt2                                | 601.038s |6587.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                | 600.962s |6416.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985918.smt2                                | 600.771s |6338.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-983194.smt2                              | 507.300s |6259.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                | 600.850s |6157.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1072007.smt2                             | 172.669s |5839.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                | 600.798s |5709.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                              | 600.744s |5708.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                | 600.904s |5692.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-50.smt2                         | 600.591s |5691.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-50.smt2                         | 600.638s |5646.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                              | 600.674s |5613.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-987361.smt2                                | 600.792s |5568.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                | 600.812s |5565.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                | 600.935s |5563.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-989891.smt2                              | 600.805s |5480.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-48.smt2                         | 600.553s |5097.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |   3.945s  |   3.945s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |  57.017s  |  57.017s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |   4.433s  |   4.433s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |   5.385s  |   5.385s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   3.396s  |   3.396s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   4.558s  |   4.558s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |   4.649s  |   4.649s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   4.902s  |   4.902s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |   4.285s  |   4.285s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |   3.577s  |   3.577s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |   4.439s  |   4.439s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   4.305s  |   4.305s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   3.352s  |   3.352s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   4.414s  |   4.414s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   4.998s  |   4.998s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   3.791s  |   3.791s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   3.849s  |   3.849s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   5.193s  |   5.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   4.260s  |   4.260s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |   4.279s  |   4.279s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |   4.361s  |   4.361s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |   4.761s  |   4.761s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |   4.371s  |   4.371s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |   3.632s  |   3.632s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |   3.625s  |   3.625s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |   4.929s  |   4.929s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-12.smt2                       |   4.620s  |   4.620s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |   4.718s  |   4.718s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |   4.350s  |   4.350s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-15.smt2                       |   3.674s  |   3.674s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-00.smt2                      |   6.127s  |   6.127s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-01.smt2                      |   6.379s  |   6.379s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-02.smt2                      |   6.575s  |   6.575s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-03.smt2                      |   6.079s  |   6.079s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-07.smt2                      |   6.047s  |   6.047s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-08.smt2                      |   4.371s  |   4.371s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-09.smt2                      |   6.586s  |   6.586s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-10.smt2                      |   5.539s  |   5.539s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-11.smt2                      |   7.137s  |   7.137s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-12.smt2                      |   5.162s  |   5.162s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-13.smt2                      |   6.286s  |   6.286s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-14.smt2                      |   4.426s  |   4.426s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-15.smt2                      |   4.923s  |   4.923s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-00.smt2                      |   6.422s  |   6.422s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-08.smt2                      |   4.565s  |   4.565s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-09.smt2                      |   6.185s  |   6.185s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-10.smt2                      |   5.877s  |   5.877s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-11.smt2                      |   5.029s  |   5.029s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-12.smt2                      |   5.907s  |   5.907s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-13.smt2                      |   6.478s  |   6.478s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-14.smt2                      |   6.734s  |   6.734s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-15.smt2                      |   6.568s  |   6.568s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20231117-c_inference/80_80_71_17_unsat.smt2                          | 600.456s  | 600.456s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/RWS/Example_15.txt.smt2                                              | 600.137s  | 600.137s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/RWS/Example_18.txt.smt2                                              | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/RWS/Example_9.txt.smt2                                               | 132.017s  | 132.017s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1000539.smt2                                |   9.989s  |   9.989s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1007795.smt2                                |   7.707s  |   7.707s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                                | 601.065s  | 601.065s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1065256.smt2                                | 601.682s  | 601.682s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1096871.smt2                                |  90.642s  |  90.642s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1107622.smt2                                |  24.609s  |  24.609s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1121941.smt2                                |  34.994s  |  34.994s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1145584.smt2                                |  56.694s  |  56.694s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1148089.smt2                                |  12.676s  |  12.676s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1185949.smt2                                |  27.431s  |  27.431s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-391798.smt2                                 | 566.126s  | 566.126s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-392137.smt2                                 |   8.718s  |   8.718s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-408585.smt2                                 |  31.560s  |  31.560s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-415996.smt2                                 |  10.599s  |  10.599s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-478122.smt2                                 | 426.576s  | 426.576s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-481231.smt2                                 |  24.183s  |  24.183s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-487307.smt2                                 | 600.435s  | 600.435s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-506600.smt2                                 | 600.383s  | 600.383s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-518109.smt2                                 | 158.332s  | 158.332s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-526410.smt2                                 |   3.883s  |   3.883s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-533042.smt2                                 | 600.485s  | 600.485s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-551279.smt2                                 | 600.481s  | 600.481s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-569261.smt2                                 | 600.497s  | 600.497s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-618384.smt2                                 |  19.294s  |  19.294s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-644402.smt2                                 | 600.813s  | 600.813s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-654327.smt2                                 | 233.274s  | 233.274s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-655888.smt2                                 | 600.676s  | 600.676s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-687518.smt2                                 | 600.563s  | 600.563s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-689472.smt2                                 |  12.303s  |  12.303s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-765743.smt2                                 | 600.613s  | 600.613s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                 | 600.904s  | 600.904s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-804609.smt2                                 | 281.153s  | 281.153s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                 | 600.798s  | 600.798s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-864173.smt2                                 |  19.649s  |  19.649s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                 | 600.935s  | 600.935s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-901628.smt2                                 |  17.157s  |  17.157s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                 | 600.812s  | 600.812s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                 | 600.962s  | 600.962s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-906218.smt2                                 |   8.057s  |   8.057s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-916576.smt2                                 |   7.579s  |   7.579s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-928134.smt2                                 |  10.468s  |  10.468s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-928960.smt2                                 | 558.747s  | 558.747s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-943653.smt2                                 | 171.453s  | 171.453s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                 | 600.850s  | 600.850s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                 | 600.892s  | 600.892s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-985918.smt2                                 | 600.771s  | 600.771s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-987361.smt2                                 | 600.792s  | 600.792s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-993227.smt2                                 | 601.038s  | 601.038s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER10-13-fair.smt2                                       |  19.303s  |  19.303s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER10-14-fair.smt2                                       |  58.715s  |  58.715s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER11-14-fair.smt2                                       |  69.961s  |  69.961s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER11-15-fair.smt2                                       | 248.485s  | 248.485s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-13-48.smt2                           |  22.404s  |  22.404s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-13-50.smt2                           |  47.205s  |  47.205s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-14-49.smt2                           |  34.362s  |  34.362s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-14-50.smt2                           |  43.256s  |  43.256s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-16-48.smt2                           |  52.086s  |  52.086s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-16-49.smt2                           |  43.786s  |  43.786s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-16-50.smt2                           |  28.424s  |  28.424s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-17-47.smt2                           |  28.098s  |  28.098s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-17-50.smt2                           |  35.963s  |  35.963s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-18-46.smt2                           |  13.785s  |  13.785s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-18-48.smt2                           |  35.473s  |  35.473s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-18-50.smt2                           |  39.754s  |  39.754s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-19-49.smt2                           |  21.954s  |  21.954s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-19-50.smt2                           |  34.229s  |  34.229s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-20-45.smt2                           |  14.481s  |  14.481s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-22-48.smt2                           |  42.105s  |  42.105s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-22-49.smt2                           |  23.126s  |  23.126s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-22-50.smt2                           |  26.670s  |  26.670s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-24-49.smt2                           |  45.340s  |  45.340s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-25-50.smt2                           |  95.328s  |  95.328s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-27-47.smt2                           |  21.407s  |  21.407s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-27-49.smt2                           |  27.779s  |  27.779s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-27-50.smt2                           |  57.659s  |  57.659s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-28-48.smt2                           |  31.846s  |  31.846s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-28-49.smt2                           |  25.598s  |  25.598s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-28-50.smt2                           |  31.205s  |  31.205s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-29-48.smt2                           |  26.805s  |  26.805s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-29-50.smt2                           |  39.345s  |  39.345s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-30-48.smt2                           |  22.611s  |  22.611s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-32-47.smt2                           |  35.247s  |  35.247s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-32-49.smt2                           |  47.455s  |  47.455s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-32-50.smt2                           |  34.822s  |  34.822s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-33-50.smt2                           |  35.716s  |  35.716s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-34-45.smt2                           |  20.767s  |  20.767s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-34-48.smt2                           |  29.961s  |  29.961s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-45.smt2                           |  18.733s  |  18.733s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-46.smt2                           | 143.139s  | 143.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-47.smt2                           |  27.386s  |  27.386s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-45.smt2                           |  33.724s  |  33.724s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-46.smt2                           |  45.812s  |  45.812s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-47.smt2                           |  42.212s  |  42.212s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-48.smt2                           |  35.299s  |  35.299s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-49.smt2                           |  34.913s  |  34.913s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-50.smt2                           |  44.775s  |  44.775s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-45.smt2                           | 165.233s  | 165.233s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-46.smt2                           |  28.843s  |  28.843s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-47.smt2                           | 180.914s  | 180.914s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-48.smt2                           |  27.842s  |  27.842s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-45.smt2                           |  26.295s  |  26.295s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-46.smt2                           |  39.922s  |  39.922s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-47.smt2                           |  43.917s  |  43.917s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-48.smt2                           |  46.499s  |  46.499s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-49.smt2                           |  53.714s  |  53.714s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-50.smt2                           |  49.539s  |  49.539s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-45.smt2                           |  41.811s  |  41.811s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-46.smt2                           |  68.662s  |  68.662s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-47.smt2                           |  74.463s  |  74.463s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-48.smt2                           |  59.007s  |  59.007s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-49.smt2                           |  57.954s  |  57.954s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-50.smt2                           |  59.687s  |  59.687s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-4-45.smt2                            |  26.637s  |  26.637s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-4-48.smt2                            | 106.727s  | 106.727s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-4-49.smt2                            |  67.623s  |  67.623s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-4-50.smt2                            |  41.335s  |  41.335s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-45.smt2                           |  31.340s  |  31.340s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-46.smt2                           |  54.967s  |  54.967s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-47.smt2                           |  48.223s  |  48.223s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-48.smt2                           |  46.290s  |  46.290s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-49.smt2                           |  43.935s  |  43.935s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-50.smt2                           |  67.571s  |  67.571s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-45.smt2                           |  40.598s  |  40.598s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-46.smt2                           |  69.589s  |  69.589s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-47.smt2                           |  54.263s  |  54.263s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-48.smt2                           |  79.008s  |  79.008s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-49.smt2                           |  76.526s  |  76.526s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-50.smt2                           | 113.382s  | 113.382s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-45.smt2                           |  44.484s  |  44.484s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-46.smt2                           |  89.248s  |  89.248s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-47.smt2                           |  59.279s  |  59.279s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-48.smt2                           |  76.330s  |  76.330s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-49.smt2                           |  68.550s  |  68.550s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-50.smt2                           | 105.142s  | 105.142s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-45.smt2                           |  37.032s  |  37.032s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-46.smt2                           |  40.418s  |  40.418s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-47.smt2                           |  45.500s  |  45.500s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-48.smt2                           |  50.563s  |  50.563s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-49.smt2                           |  63.427s  |  63.427s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-50.smt2                           |  64.058s  |  64.058s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-45.smt2                           |  48.084s  |  48.084s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-46.smt2                           |  92.614s  |  92.614s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-47.smt2                           |  79.657s  |  79.657s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-48.smt2                           |  63.245s  |  63.245s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-49.smt2                           |  80.373s  |  80.373s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-50.smt2                           | 130.406s  | 130.406s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-45.smt2                           |  38.172s  |  38.172s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-46.smt2                           |  49.766s  |  49.766s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-47.smt2                           |  49.352s  |  49.352s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-48.smt2                           |  50.564s  |  50.564s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-49.smt2                           |  79.970s  |  79.970s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-50.smt2                           |  92.814s  |  92.814s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-45.smt2                           |  45.326s  |  45.326s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-46.smt2                           |  43.209s  |  43.209s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-47.smt2                           |  46.256s  |  46.256s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-48.smt2                           |  56.075s  |  56.075s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-49.smt2                           |  51.317s  |  51.317s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-50.smt2                           |  60.840s  |  60.840s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-45.smt2                           |  46.282s  |  46.282s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-46.smt2                           |  67.540s  |  67.540s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-47.smt2                           |  59.012s  |  59.012s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-48.smt2                           |  82.493s  |  82.493s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-49.smt2                           |  79.157s  |  79.157s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-50.smt2                           | 141.775s  | 141.775s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-45.smt2                           |  52.018s  |  52.018s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-46.smt2                           |  75.198s  |  75.198s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-47.smt2                           |  75.870s  |  75.870s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-48.smt2                           |  75.423s  |  75.423s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-49.smt2                           |  70.601s  |  70.601s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-50.smt2                           |  83.793s  |  83.793s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-45.smt2                           |  35.236s  |  35.236s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-46.smt2                           |  54.059s  |  54.059s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-47.smt2                           |  68.321s  |  68.321s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-48.smt2                           | 100.913s  | 100.913s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-49.smt2                           |  92.050s  |  92.050s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-50.smt2                           |  94.957s  |  94.957s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-5-47.smt2                            |  28.050s  |  28.050s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-5-48.smt2                            |  21.553s  |  21.553s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-5-49.smt2                            |  28.729s  |  28.729s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-5-50.smt2                            |  57.297s  |  57.297s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-45.smt2                           |  39.276s  |  39.276s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-46.smt2                           |  49.550s  |  49.550s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-47.smt2                           |  61.894s  |  61.894s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-48.smt2                           |  66.291s  |  66.291s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-49.smt2                           |  80.836s  |  80.836s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-50.smt2                           | 108.928s  | 108.928s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-45.smt2                           |  43.581s  |  43.581s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-46.smt2                           |  75.833s  |  75.833s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-47.smt2                           |  48.544s  |  48.544s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-48.smt2                           |  64.088s  |  64.088s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-49.smt2                           |  79.213s  |  79.213s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-50.smt2                           | 110.640s  | 110.640s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-45.smt2                           |  36.441s  |  36.441s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-46.smt2                           |  54.437s  |  54.437s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-47.smt2                           |  74.624s  |  74.624s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-48.smt2                           |  61.632s  |  61.632s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-49.smt2                           |  68.337s  |  68.337s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-50.smt2                           | 118.961s  | 118.961s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-45.smt2                           |  42.044s  |  42.044s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-46.smt2                           |  51.745s  |  51.745s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-47.smt2                           |  54.263s  |  54.263s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-48.smt2                           |  57.893s  |  57.893s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-49.smt2                           |  83.634s  |  83.634s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-50.smt2                           |  68.765s  |  68.765s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-45.smt2                           |  41.763s  |  41.763s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-46.smt2                           |  51.260s  |  51.260s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-47.smt2                           |  53.415s  |  53.415s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-48.smt2                           |  62.666s  |  62.666s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-49.smt2                           |  78.961s  |  78.961s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-50.smt2                           |  94.092s  |  94.092s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-46.smt2                           |  37.903s  |  37.903s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-47.smt2                           |  50.759s  |  50.759s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-48.smt2                           |  56.632s  |  56.632s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-49.smt2                           |  65.332s  |  65.332s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-50.smt2                           |  81.747s  |  81.747s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-46.smt2                           |  50.282s  |  50.282s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-47.smt2                           |  53.924s  |  53.924s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-48.smt2                           |  66.660s  |  66.660s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-49.smt2                           |  57.988s  |  57.988s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-50.smt2                           |  83.627s  |  83.627s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-48.smt2                           |  56.584s  |  56.584s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-49.smt2                           |  68.227s  |  68.227s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-50.smt2                           |  62.047s  |  62.047s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-47.smt2                           |  64.343s  |  64.343s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-48.smt2                           |  53.510s  |  53.510s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-49.smt2                           |  52.914s  |  52.914s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-50.smt2                           |  90.436s  |  90.436s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-59-48.smt2                           |  61.963s  |  61.963s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-59-49.smt2                           |  65.117s  |  65.117s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-59-50.smt2                           | 101.737s  | 101.737s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-60-48.smt2                           |  60.871s  |  60.871s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-60-49.smt2                           |  69.307s  |  69.307s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-60-50.smt2                           | 116.482s  | 116.482s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-61-49.smt2                           |  71.154s  |  71.154s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-61-50.smt2                           |  88.513s  |  88.513s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-62-49.smt2                           |  92.505s  |  92.505s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-62-50.smt2                           |  86.045s  |  86.045s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-63-50.smt2                           | 116.237s  | 116.237s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-46.smt2                            |  29.058s  |  29.058s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-47.smt2                            |  43.888s  |  43.888s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-48.smt2                            |  43.793s  |  43.793s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-49.smt2                            |  80.696s  |  80.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-50.smt2                            |  52.875s  |  52.875s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-46.smt2                            |  47.553s  |  47.553s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-47.smt2                            |  22.797s  |  22.797s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-48.smt2                            |  29.935s  |  29.935s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-49.smt2                            |  86.574s  |  86.574s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-50.smt2                            |  51.318s  |  51.318s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-46.smt2                   | 260.316s  | 260.316s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-47.smt2                   | 346.758s  | 346.758s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-48.smt2                   | 442.846s  | 442.846s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-49.smt2                   | 600.271s  | 600.271s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-50.smt2                   | 600.351s  | 600.351s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-46.smt2                   | 252.071s  | 252.071s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-47.smt2                   | 385.227s  | 385.227s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-48.smt2                   | 394.467s  | 394.467s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-49.smt2                   | 478.749s  | 478.749s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-50.smt2                   | 600.402s  | 600.402s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-46.smt2                   | 160.346s  | 160.346s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-47.smt2                   | 208.615s  | 208.615s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-48.smt2                   | 232.640s  | 232.640s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-49.smt2                   | 363.843s  | 363.843s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-50.smt2                   | 305.597s  | 305.597s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-46.smt2                   |  82.262s  |  82.262s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-47.smt2                   |  69.464s  |  69.464s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-48.smt2                   | 113.080s  | 113.080s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-49.smt2                   | 164.066s  | 164.066s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-50.smt2                   | 245.960s  | 245.960s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-47.smt2                    |  38.224s  |  38.224s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-48.smt2                    |  46.440s  |  46.440s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-49.smt2                    |  61.803s  |  61.803s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-50.smt2                    |  74.898s  |  74.898s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-46.smt2                    | 146.287s  | 146.287s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-47.smt2                    | 123.468s  | 123.468s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-48.smt2                    | 179.837s  | 179.837s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-49.smt2                    | 266.015s  | 266.015s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-50.smt2                    | 292.726s  | 292.726s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-46.smt2                    | 116.210s  | 116.210s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-47.smt2                    | 144.127s  | 144.127s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-48.smt2                    | 200.602s  | 200.602s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-49.smt2                    | 246.131s  | 246.131s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-50.smt2                    | 307.369s  | 307.369s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-8-47.smt2                    |  11.739s  |  11.739s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-8-49.smt2                    |  15.166s  |  15.166s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-8-50.smt2                    |  22.801s  |  22.801s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-13-50.smt2                         |  21.881s  |  21.881s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-14-50.smt2                         |  21.243s  |  21.243s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-16-50.smt2                         |  26.867s  |  26.867s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-17-50.smt2                         |  23.737s  |  23.737s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-19-50.smt2                         |  23.207s  |  23.207s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-2-50.smt2                          |  21.098s  |  21.098s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-21-50.smt2                         |  21.774s  |  21.774s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-22-50.smt2                         |  22.458s  |  22.458s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-23-50.smt2                         |  22.100s  |  22.100s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-25-50.smt2                         |  89.750s  |  89.750s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-26-50.smt2                         |  40.332s  |  40.332s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-27-50.smt2                         |  54.934s  |  54.934s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-28-50.smt2                         | 118.589s  | 118.589s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-29-50.smt2                         |  84.272s  |  84.272s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-30-50.smt2                         |  19.239s  |  19.239s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-31-50.smt2                         |  29.589s  |  29.589s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-32-50.smt2                         |  24.382s  |  24.382s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-33-50.smt2                         |  20.140s  |  20.140s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-35-50.smt2                         |  25.267s  |  25.267s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-37-50.smt2                         |  23.368s  |  23.368s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-38-50.smt2                         |  25.765s  |  25.765s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-39-50.smt2                         |  39.044s  |  39.044s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-40-50.smt2                         |  24.890s  |  24.890s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-41-50.smt2                         |  55.372s  |  55.372s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-42-50.smt2                         |  21.429s  |  21.429s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-43-50.smt2                         |  47.252s  |  47.252s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-44-50.smt2                         |  43.983s  |  43.983s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-45-50.smt2                         |  24.783s  |  24.783s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-46-50.smt2                         |  25.001s  |  25.001s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-47-50.smt2                         |  23.048s  |  23.048s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-48-50.smt2                         |  23.151s  |  23.151s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-49-50.smt2                         |  26.038s  |  26.038s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-5-50.smt2                          |  21.164s  |  21.164s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-50-50.smt2                         |  40.839s  |  40.839s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-51-50.smt2                         |  42.173s  |  42.173s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-52-50.smt2                         |  37.900s  |  37.900s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-53-50.smt2                         |  36.731s  |  36.731s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-54-50.smt2                         |  34.754s  |  34.754s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-55-50.smt2                         |  30.408s  |  30.408s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-58-50.smt2                         |  35.688s  |  35.688s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-59-50.smt2                         |  26.157s  |  26.157s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-60-50.smt2                         |  28.626s  |  28.626s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-61-50.smt2                         |  27.503s  |  27.503s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-63-50.smt2                         |  38.700s  |  38.700s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-64-50.smt2                         |  26.955s  |  26.955s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-65-50.smt2                         |  29.875s  |  29.875s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-67-50.smt2                         |  28.534s  |  28.534s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-68-50.smt2                         |  30.337s  |  30.337s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-69-50.smt2                         |  27.485s  |  27.485s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-70-50.smt2                         |  30.469s  |  30.469s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-9-50.smt2                          |  20.607s  |  20.607s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-46.smt2                           |  30.713s  |  30.713s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-47.smt2                           |  32.827s  |  32.827s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-48.smt2                           |  36.423s  |  36.423s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-49.smt2                           |  48.921s  |  48.921s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-50.smt2                           |  56.731s  |  56.731s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-46.smt2                           |  35.160s  |  35.160s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-47.smt2                           |  60.933s  |  60.933s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-48.smt2                           |  40.753s  |  40.753s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-50.smt2                           |  63.161s  |  63.161s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-46.smt2                          | 387.225s  | 387.225s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-47.smt2                          | 378.579s  | 378.579s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-48.smt2                          |  78.543s  |  78.543s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-49.smt2                          | 172.302s  | 172.302s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-50.smt2                          | 600.371s  | 600.371s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-46.smt2                          | 266.990s  | 266.990s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-47.smt2                          | 175.359s  | 175.359s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-48.smt2                          |  77.962s  |  77.962s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-49.smt2                          | 600.261s  | 600.261s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-50.smt2                          | 305.539s  | 305.539s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-46.smt2                          |  32.985s  |  32.985s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-47.smt2                          |  43.502s  |  43.502s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-48.smt2                          |  43.185s  |  43.185s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-49.smt2                          |  56.096s  |  56.096s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-50.smt2                          |  56.311s  |  56.311s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-46.smt2                          | 204.834s  | 204.834s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-47.smt2                          | 279.693s  | 279.693s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-48.smt2                          |  66.677s  |  66.677s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-49.smt2                          | 291.804s  | 291.804s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-50.smt2                          | 600.225s  | 600.225s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-46.smt2                          |  30.854s  |  30.854s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-47.smt2                          |  42.114s  |  42.114s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-49.smt2                          |  47.500s  |  47.500s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-50.smt2                          |  52.474s  |  52.474s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-46.smt2                          |  29.846s  |  29.846s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-47.smt2                          |  32.226s  |  32.226s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-48.smt2                          |  37.571s  |  37.571s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-49.smt2                          |  51.042s  |  51.042s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-50.smt2                          |  50.354s  |  50.354s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-46.smt2                          | 222.741s  | 222.741s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-47.smt2                          | 269.981s  | 269.981s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-48.smt2                          |  65.524s  |  65.524s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-49.smt2                          | 274.411s  | 274.411s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-50.smt2                          | 432.407s  | 432.407s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-46.smt2                          |  88.866s  |  88.866s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-47.smt2                          | 129.126s  | 129.126s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-48.smt2                          |  65.301s  |  65.301s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-49.smt2                          | 404.435s  | 404.435s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-50.smt2                          | 545.756s  | 545.756s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-46.smt2                          |  36.356s  |  36.356s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-47.smt2                          |  32.894s  |  32.894s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-48.smt2                          |  54.926s  |  54.926s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-49.smt2                          |  47.017s  |  47.017s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-50.smt2                          |  63.773s  |  63.773s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-46.smt2                          | 224.610s  | 224.610s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-47.smt2                          | 105.491s  | 105.491s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-48.smt2                          |  71.118s  |  71.118s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-49.smt2                          | 388.189s  | 388.189s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-50.smt2                          | 503.398s  | 503.398s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-46.smt2                           | 202.027s  | 202.027s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-47.smt2                           | 224.823s  | 224.823s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-48.smt2                           |  80.862s  |  80.862s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-49.smt2                           | 479.389s  | 479.389s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-50.smt2                           | 311.889s  | 311.889s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-46.smt2                          |  39.436s  |  39.436s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-47.smt2                          |  41.007s  |  41.007s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-48.smt2                          |  45.943s  |  45.943s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-49.smt2                          |  52.854s  |  52.854s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-50.smt2                          |  60.988s  |  60.988s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-46.smt2                          |  41.816s  |  41.816s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-47.smt2                          |  61.356s  |  61.356s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-48.smt2                          |  56.396s  |  56.396s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-49.smt2                          |  62.098s  |  62.098s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-50.smt2                          |  56.811s  |  56.811s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-46.smt2                          | 222.056s  | 222.056s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-47.smt2                          | 253.722s  | 253.722s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-48.smt2                          |  56.118s  |  56.118s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-49.smt2                          | 281.589s  | 281.589s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-46.smt2                          | 189.406s  | 189.406s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-47.smt2                          | 170.090s  | 170.090s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-48.smt2                          |  57.256s  |  57.256s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-49.smt2                          | 146.350s  | 146.350s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-50.smt2                          | 523.008s  | 523.008s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-46.smt2                          |  37.108s  |  37.108s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-47.smt2                          |  44.305s  |  44.305s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-48.smt2                          |  49.091s  |  49.091s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-49.smt2                          |  63.125s  |  63.125s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-50.smt2                          |  82.390s  |  82.390s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-46.smt2                          | 175.619s  | 175.619s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-47.smt2                          | 139.734s  | 139.734s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-48.smt2                          |  62.976s  |  62.976s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-49.smt2                          | 589.538s  | 589.538s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-50.smt2                          | 532.505s  | 532.505s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-46.smt2                          |  36.711s  |  36.711s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-47.smt2                          |  47.212s  |  47.212s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-48.smt2                          |  58.849s  |  58.849s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-49.smt2                          |  73.696s  |  73.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-50.smt2                          |  88.621s  |  88.621s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-46.smt2                          |  59.429s  |  59.429s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-47.smt2                          |  61.509s  |  61.509s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-48.smt2                          |  51.778s  |  51.778s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-49.smt2                          |  89.637s  |  89.637s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-50.smt2                          |  80.152s  |  80.152s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-47.smt2                          | 570.596s  | 570.596s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-48.smt2                          | 600.553s  | 600.553s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-49.smt2                          | 600.184s  | 600.184s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-50.smt2                          | 600.423s  | 600.423s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-46.smt2                          | 329.190s  | 329.190s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-47.smt2                          |  56.604s  |  56.604s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-48.smt2                          | 316.909s  | 316.909s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-49.smt2                          | 600.360s  | 600.360s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-50.smt2                          | 600.298s  | 600.298s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-46.smt2                           | 233.028s  | 233.028s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-47.smt2                           | 288.178s  | 288.178s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-48.smt2                           |  79.819s  |  79.819s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-49.smt2                           | 531.807s  | 531.807s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-50.smt2                           | 455.321s  | 455.321s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-46.smt2                          | 390.063s  | 390.063s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-47.smt2                          | 539.985s  | 539.985s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-48.smt2                          | 600.260s  | 600.260s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-49.smt2                          | 600.392s  | 600.392s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-50.smt2                          | 600.441s  | 600.441s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-46.smt2                          |  64.413s  |  64.413s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-47.smt2                          |  60.343s  |  60.343s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-48.smt2                          |  53.298s  |  53.298s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-49.smt2                          |  84.033s  |  84.033s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-50.smt2                          | 100.697s  | 100.697s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-46.smt2                          | 198.874s  | 198.874s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-47.smt2                          | 166.561s  | 166.561s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-48.smt2                          |  59.574s  |  59.574s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-49.smt2                          | 361.509s  | 361.509s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-50.smt2                          | 600.389s  | 600.389s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-46.smt2                          | 197.592s  | 197.592s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-47.smt2                          | 168.471s  | 168.471s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-48.smt2                          | 262.481s  | 262.481s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-49.smt2                          | 600.219s  | 600.219s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-50.smt2                          | 568.523s  | 568.523s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-46.smt2                          |  70.069s  |  70.069s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-47.smt2                          | 255.800s  | 255.800s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-48.smt2                          | 310.012s  | 310.012s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-49.smt2                          |  97.370s  |  97.370s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-50.smt2                          | 600.334s  | 600.334s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-46.smt2                          |  68.362s  |  68.362s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-47.smt2                          | 109.665s  | 109.665s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-48.smt2                          |  93.250s  |  93.250s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-49.smt2                          | 106.585s  | 106.585s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-50.smt2                          | 129.998s  | 129.998s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-46.smt2                          |  68.940s  |  68.940s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-47.smt2                          |  61.533s  |  61.533s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-48.smt2                          | 124.252s  | 124.252s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-49.smt2                          | 139.139s  | 139.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-50.smt2                          |  88.084s  |  88.084s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-47.smt2                          |  14.758s  |  14.758s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-48.smt2                          | 548.398s  | 548.398s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-49.smt2                          | 391.830s  | 391.830s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-50.smt2                          | 600.212s  | 600.212s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-46.smt2                          | 166.203s  | 166.203s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-47.smt2                          | 186.860s  | 186.860s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-48.smt2                          |  59.509s  |  59.509s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-49.smt2                          | 343.059s  | 343.059s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-50.smt2                          | 405.463s  | 405.463s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-46.smt2                          | 169.753s  | 169.753s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-47.smt2                          |  78.930s  |  78.930s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-48.smt2                          | 236.984s  | 236.984s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-49.smt2                          | 579.285s  | 579.285s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-50.smt2                          |  81.285s  |  81.285s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-46.smt2                           |  30.521s  |  30.521s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-47.smt2                           |  33.831s  |  33.831s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-48.smt2                           |  46.942s  |  46.942s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-49.smt2                           |  50.191s  |  50.191s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-50.smt2                           |  63.391s  |  63.391s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-46.smt2                          | 202.206s  | 202.206s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-47.smt2                          | 249.296s  | 249.296s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-48.smt2                          | 435.025s  | 435.025s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-49.smt2                          | 600.432s  | 600.432s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-50.smt2                          | 600.545s  | 600.545s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-46.smt2                          | 245.687s  | 245.687s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-47.smt2                          | 302.510s  | 302.510s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-48.smt2                          | 435.592s  | 435.592s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-49.smt2                          | 600.319s  | 600.319s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-50.smt2                          | 600.638s  | 600.638s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-47.smt2                          |  14.606s  |  14.606s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-48.smt2                          |  17.181s  |  17.181s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-49.smt2                          | 522.789s  | 522.789s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-50.smt2                          | 600.591s  | 600.591s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-46.smt2                          | 184.551s  | 184.551s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-47.smt2                          | 239.240s  | 239.240s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-48.smt2                          |  56.472s  |  56.472s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-49.smt2                          | 370.448s  | 370.448s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-50.smt2                          | 263.450s  | 263.450s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-46.smt2                          | 145.129s  | 145.129s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-47.smt2                          | 195.474s  | 195.474s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-48.smt2                          | 183.883s  | 183.883s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-49.smt2                          | 247.869s  | 247.869s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-50.smt2                          | 479.247s  | 479.247s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-46.smt2                          | 107.940s  | 107.940s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-47.smt2                          | 124.989s  | 124.989s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-48.smt2                          |  54.770s  |  54.770s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-49.smt2                          | 343.597s  | 343.597s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-50.smt2                          | 359.696s  | 359.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-46.smt2                          |  45.233s  |  45.233s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-47.smt2                          | 156.539s  | 156.539s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-48.smt2                          | 182.009s  | 182.009s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-49.smt2                          | 249.723s  | 249.723s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-50.smt2                          | 422.755s  | 422.755s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-46.smt2                          | 120.545s  | 120.545s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-47.smt2                          | 164.603s  | 164.603s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-48.smt2                          |  87.408s  |  87.408s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-49.smt2                          | 311.555s  | 311.555s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-50.smt2                          | 407.332s  | 407.332s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-46.smt2                          |  87.416s  |  87.416s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-47.smt2                          |  77.637s  |  77.637s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-48.smt2                          | 211.634s  | 211.634s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-49.smt2                          | 295.001s  | 295.001s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-50.smt2                          | 330.656s  | 330.656s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-46.smt2                          | 200.171s  | 200.171s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-47.smt2                          | 104.409s  | 104.409s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-48.smt2                          |  62.391s  |  62.391s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-49.smt2                          | 214.687s  | 214.687s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-50.smt2                          | 215.190s  | 215.190s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-46.smt2                           |  30.902s  |  30.902s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-47.smt2                           |  36.293s  |  36.293s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-48.smt2                           |  40.123s  |  40.123s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-49.smt2                           |  53.669s  |  53.669s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-50.smt2                           |  67.096s  |  67.096s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-46.smt2                          | 144.435s  | 144.435s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-47.smt2                          | 153.678s  | 153.678s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-48.smt2                          | 179.580s  | 179.580s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-49.smt2                          | 401.191s  | 401.191s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-50.smt2                          | 322.250s  | 322.250s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-47.smt2                          | 137.055s  | 137.055s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-48.smt2                          |  70.696s  |  70.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-49.smt2                          | 244.468s  | 244.468s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-50.smt2                          | 335.278s  | 335.278s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-46.smt2                           |  29.055s  |  29.055s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-47.smt2                           |  32.915s  |  32.915s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-48.smt2                           |  35.118s  |  35.118s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-49.smt2                           |  46.603s  |  46.603s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-50.smt2                           |  51.850s  |  51.850s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-46.smt2                           |  29.627s  |  29.627s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-47.smt2                           |  38.395s  |  38.395s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-48.smt2                           |  40.478s  |  40.478s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-49.smt2                           |  43.804s  |  43.804s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-50.smt2                           |  55.192s  |  55.192s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-46.smt2                           | 224.804s  | 224.804s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-47.smt2                           | 341.673s  | 341.673s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-48.smt2                           |  97.949s  |  97.949s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-50.smt2                           | 600.282s  | 600.282s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-46.smt2                           | 289.954s  | 289.954s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-47.smt2                           | 231.473s  | 231.473s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-48.smt2                           |  70.021s  |  70.021s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-49.smt2                           | 600.343s  | 600.343s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-50.smt2                           | 418.795s  | 418.795s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-46.smt2                         |  49.245s  |  49.245s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-47.smt2                         |  46.226s  |  46.226s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-48.smt2                         | 159.238s  | 159.238s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-49.smt2                         | 172.664s  | 172.664s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-50.smt2                         |  63.435s  |  63.435s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-46.smt2                         | 164.007s  | 164.007s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-47.smt2                         | 195.575s  | 195.575s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-48.smt2                         | 204.765s  | 204.765s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-49.smt2                         | 101.734s  | 101.734s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-50.smt2                         | 306.061s  | 306.061s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-46.smt2                        | 175.215s  | 175.215s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-47.smt2                        | 600.387s  | 600.387s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-48.smt2                        | 293.094s  | 293.094s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-49.smt2                        | 600.349s  | 600.349s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-50.smt2                        | 600.212s  | 600.212s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-46.smt2                        | 187.038s  | 187.038s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-47.smt2                        | 218.207s  | 218.207s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-48.smt2                        | 425.373s  | 425.373s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-49.smt2                        |  67.657s  |  67.657s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-50.smt2                        | 600.233s  | 600.233s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-46.smt2                        |  66.766s  |  66.766s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-47.smt2                        | 323.634s  | 323.634s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-48.smt2                        | 430.231s  | 430.231s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-49.smt2                        | 418.021s  | 418.021s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-50.smt2                        | 590.443s  | 590.443s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-46.smt2                        |  46.935s  |  46.935s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-47.smt2                        |  54.592s  |  54.592s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-48.smt2                        | 291.584s  | 291.584s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-49.smt2                        | 354.481s  | 354.481s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-50.smt2                        | 450.308s  | 450.308s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-46.smt2                        | 186.129s  | 186.129s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-47.smt2                        | 232.552s  | 232.552s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-48.smt2                        | 226.398s  | 226.398s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-49.smt2                        | 378.108s  | 378.108s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-50.smt2                        | 483.004s  | 483.004s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-46.smt2                        |  32.637s  |  32.637s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-47.smt2                        | 222.436s  | 222.436s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-48.smt2                        | 167.464s  | 167.464s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-49.smt2                        |  74.009s  |  74.009s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-50.smt2                        | 563.323s  | 563.323s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-46.smt2                        |  91.673s  |  91.673s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-47.smt2                        |  76.282s  |  76.282s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-48.smt2                        | 213.363s  | 213.363s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-49.smt2                        |  72.713s  |  72.713s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-50.smt2                        | 412.612s  | 412.612s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-46.smt2                        |  33.010s  |  33.010s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-47.smt2                        | 112.914s  | 112.914s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-48.smt2                        | 128.694s  | 128.694s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-49.smt2                        |  79.116s  |  79.116s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-50.smt2                        | 240.812s  | 240.812s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-46.smt2                        |  48.849s  |  48.849s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-47.smt2                        |  68.929s  |  68.929s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-48.smt2                        |  34.033s  |  34.033s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-49.smt2                        | 106.883s  | 106.883s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-50.smt2                        | 308.488s  | 308.488s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-47.smt2                        |  30.644s  |  30.644s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-48.smt2                        |  48.437s  |  48.437s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-49.smt2                        | 194.352s  | 194.352s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-50.smt2                        | 233.779s  | 233.779s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-46.smt2                         |  60.753s  |  60.753s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-47.smt2                         | 234.221s  | 234.221s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-48.smt2                         | 109.372s  | 109.372s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-49.smt2                         | 492.147s  | 492.147s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-50.smt2                         | 442.105s  | 442.105s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-46.smt2                        |  71.236s  |  71.236s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-47.smt2                        | 111.000s  | 111.000s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-48.smt2                        |  66.073s  |  66.073s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-49.smt2                        |  85.590s  |  85.590s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-50.smt2                        | 178.716s  | 178.716s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-46.smt2                        |  64.658s  |  64.658s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-47.smt2                        | 113.764s  | 113.764s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-48.smt2                        | 171.458s  | 171.458s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-49.smt2                        | 211.766s  | 211.766s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-50.smt2                        | 227.184s  | 227.184s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-46.smt2                        |  82.575s  |  82.575s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-47.smt2                        |  89.085s  |  89.085s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-48.smt2                        | 240.250s  | 240.250s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-49.smt2                        | 110.889s  | 110.889s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-50.smt2                        | 143.939s  | 143.939s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-46.smt2                        |  58.751s  |  58.751s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-47.smt2                        |  39.413s  |  39.413s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-48.smt2                        |  91.097s  |  91.097s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-49.smt2                        | 202.980s  | 202.980s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-50.smt2                        | 133.753s  | 133.753s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-46.smt2                        |  64.525s  |  64.525s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-47.smt2                        |  51.569s  |  51.569s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-48.smt2                        | 158.236s  | 158.236s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-49.smt2                        |  41.213s  |  41.213s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-50.smt2                        |  65.698s  |  65.698s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-46.smt2                         | 123.545s  | 123.545s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-47.smt2                         | 135.907s  | 135.907s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-48.smt2                         |  64.958s  |  64.958s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-49.smt2                         | 245.904s  | 245.904s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-50.smt2                         | 141.834s  | 141.834s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-46.smt2                         |  56.867s  |  56.867s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-47.smt2                         | 424.832s  | 424.832s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-48.smt2                         | 445.417s  | 445.417s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-49.smt2                         | 444.778s  | 444.778s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-50.smt2                         | 558.474s  | 558.474s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-46.smt2                         | 376.761s  | 376.761s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-47.smt2                         | 241.497s  | 241.497s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-48.smt2                         | 284.926s  | 284.926s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-49.smt2                         | 335.190s  | 335.190s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-50.smt2                         | 483.104s  | 483.104s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-46.smt2                         |  84.242s  |  84.242s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-47.smt2                         |  86.532s  |  86.532s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-48.smt2                         |  77.461s  |  77.461s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-49.smt2                         | 408.171s  | 408.171s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-46.smt2                         | 228.684s  | 228.684s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-47.smt2                         | 414.370s  | 414.370s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-48.smt2                         | 392.488s  | 392.488s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-49.smt2                         | 166.694s  | 166.694s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-50.smt2                         |  93.930s  |  93.930s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-46.smt2                         | 204.020s  | 204.020s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-47.smt2                         | 171.218s  | 171.218s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-48.smt2                         | 274.168s  | 274.168s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-49.smt2                         | 425.574s  | 425.574s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-50.smt2                         | 228.530s  | 228.530s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-46.smt2                         |  59.509s  |  59.509s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-47.smt2                         | 140.252s  | 140.252s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-48.smt2                         | 103.953s  | 103.953s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-49.smt2                         | 205.576s  | 205.576s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-50.smt2                         | 145.544s  | 145.544s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1015084.smt2                              |  10.308s  |  10.308s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1072007.smt2                              | 172.669s  | 172.669s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1192684.smt2                              |  23.876s  |  23.876s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-373262.smt2                               | 600.244s  | 600.244s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-394532.smt2                               | 600.225s  | 600.225s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-413904.smt2                               |   6.457s  |   6.457s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-416752.smt2                               | 156.302s  | 156.302s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-479884.smt2                               | 209.874s  | 209.874s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-495717.smt2                               | 158.627s  | 158.627s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-496324.smt2                               |  52.186s  |  52.186s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-527358.smt2                               |   4.903s  |   4.903s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-556171.smt2                               | 600.301s  | 600.301s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-579281.smt2                               | 600.343s  | 600.343s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-603294.smt2                               | 600.395s  | 600.395s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-614657.smt2                               |  86.110s  |  86.110s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-645855.smt2                               | 486.685s  | 486.685s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-649834.smt2                               |   7.381s  |   7.381s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-658040.smt2                               | 288.940s  | 288.940s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-687179.smt2                               |  91.189s  |  91.189s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-696340.smt2                               | 600.449s  | 600.449s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-705295.smt2                               |  13.282s  |  13.282s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-715402.smt2                               | 600.794s  | 600.794s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-729964.smt2                               | 198.016s  | 198.016s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-735583.smt2                               | 600.960s  | 600.960s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-737829.smt2                               | 600.632s  | 600.632s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-740637.smt2                               | 600.733s  | 600.733s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-758897.smt2                               |  14.098s  |  14.098s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-762853.smt2                               |  72.882s  |  72.882s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-794687.smt2                               |  12.473s  |  12.473s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-797738.smt2                               | 600.605s  | 600.605s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                               | 600.674s  | 600.674s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                               | 600.744s  | 600.744s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-901996.smt2                               |  14.390s  |  14.390s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-906586.smt2                               |  41.777s  |  41.777s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-916807.smt2                               |  11.244s  |  11.244s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-917322.smt2                               |  16.257s  |  16.257s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-983194.smt2                               | 507.300s  | 507.300s  |   0.000s  | 0.0%|
</details>
