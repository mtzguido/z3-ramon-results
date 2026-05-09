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
Job tag: Z3-threads-8-QF_LIA_hard-timeout10min-bb1
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: f880fdccee614547c38c19beb7af5a027961646b
Z3 branch: core_min
Z3 options: "-T:600 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=1"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_LIA.tar.zst?download=1
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-QF_LIA_hard-timeout10min-bb1
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: f880fdccee614547c38c19beb7af5a027961646b
Z3 branch: core_min
Z3 options: "-T:600 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=1"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_LIA.tar.zst?download=1
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |   3.705s  |   3.705s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |  62.339s  |  62.339s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |   4.795s  |   4.795s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |   4.193s  |   4.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   3.429s  |   3.429s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   4.179s  |   4.179s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |   4.154s  |   4.154s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   5.075s  |   5.075s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |   4.305s  |   4.305s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |   3.801s  |   3.801s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |   4.757s  |   4.757s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   4.375s  |   4.375s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   3.124s  |   3.124s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   4.287s  |   4.287s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   4.852s  |   4.852s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   3.531s  |   3.531s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   3.595s  |   3.595s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   5.317s  |   5.317s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   4.549s  |   4.549s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |   3.705s  |   3.705s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |  62.339s  |  62.339s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |   4.795s  |   4.795s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |   4.193s  |   4.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   3.429s  |   3.429s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   4.179s  |   4.179s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |   4.154s  |   4.154s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   5.075s  |   5.075s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |   4.305s  |   4.305s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |   3.801s  |   3.801s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |   4.757s  |   4.757s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   4.375s  |   4.375s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   3.124s  |   3.124s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   4.287s  |   4.287s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   4.852s  |   4.852s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   3.531s  |   3.531s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   3.595s  |   3.595s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   5.317s  |   5.317s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   4.549s  |   4.549s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |   3.705s  |   3.705s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |  62.339s  |  62.339s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |   4.795s  |   4.795s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |   4.193s  |   4.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   3.429s  |   3.429s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   4.179s  |   4.179s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |   4.154s  |   4.154s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   5.075s  |   5.075s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |   4.305s  |   4.305s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |   3.801s  |   3.801s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |   4.757s  |   4.757s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   4.375s  |   4.375s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   3.124s  |   3.124s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   4.287s  |   4.287s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   4.852s  |   4.852s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   3.531s  |   3.531s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   3.595s  |   3.595s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   5.317s  |   5.317s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   4.549s  |   4.549s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |   3.705s  |   3.705s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |  62.339s  |  62.339s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |   4.795s  |   4.795s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |   4.193s  |   4.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   3.429s  |   3.429s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   4.179s  |   4.179s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |   4.154s  |   4.154s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   5.075s  |   5.075s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |   4.305s  |   4.305s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |   3.801s  |   3.801s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |   4.757s  |   4.757s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   4.375s  |   4.375s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   3.124s  |   3.124s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   4.287s  |   4.287s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   4.852s  |   4.852s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   3.531s  |   3.531s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   3.595s  |   3.595s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   5.317s  |   5.317s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   4.549s  |   4.549s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                | 601.112s |6476.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1065256.smt2                               | 600.930s |7030.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               | 600.887s |6871.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                              | 600.884s |5240.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                | 600.861s |5889.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-943653.smt2                                | 600.766s |6174.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-993227.smt2                                | 600.757s |6166.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-987361.smt2                                | 600.750s |5073.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-644402.smt2                                | 600.738s |3773.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                | 600.711s |5211.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985918.smt2                                | 600.702s |5888.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                | 600.696s |5087.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                              | 600.664s |5205.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                | 600.655s |5690.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-983194.smt2                              | 600.622s |5822.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-797738.smt2                              | 600.609s |4477.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                | 600.605s |5318.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-735583.smt2                              | 600.599s |4327.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                | 600.593s |5199.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-989891.smt2                              | 600.589s |5055.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                | 601.112s |6476.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1065256.smt2                               | 600.930s |7030.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               | 600.887s |6871.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                              | 600.884s |5240.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                | 600.861s |5889.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-943653.smt2                                | 600.766s |6174.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-993227.smt2                                | 600.757s |6166.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-987361.smt2                                | 600.750s |5073.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-644402.smt2                                | 600.738s |3773.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                | 600.711s |5211.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985918.smt2                                | 600.702s |5888.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                | 600.696s |5087.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                              | 600.664s |5205.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                | 600.655s |5690.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-983194.smt2                              | 600.622s |5822.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-797738.smt2                              | 600.609s |4477.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                | 600.605s |5318.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-735583.smt2                              | 600.599s |4327.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                | 600.593s |5199.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-989891.smt2                              | 600.589s |5055.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |270.0MiB|270.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |286.0MiB|286.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  |320.0MiB|320.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |1977.0MiB|1977.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |2001.0MiB|2001.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |1290.0MiB|1290.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |1976.0MiB|1976.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |1989.0MiB|1989.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |1979.0MiB|1979.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |1977.0MiB|1977.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |1639.0MiB|1639.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |1974.0MiB|1974.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |1975.0MiB|1975.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |868.0MiB|868.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |1993.0MiB|1993.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |1982.0MiB|1982.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |2057.0MiB|2057.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |2062.0MiB|2062.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |3860.0MiB|3860.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |1981.0MiB|1981.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |270.0MiB|270.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |286.0MiB|286.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  |320.0MiB|320.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |1977.0MiB|1977.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |2001.0MiB|2001.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |1290.0MiB|1290.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |1976.0MiB|1976.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |1989.0MiB|1989.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |1979.0MiB|1979.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |1977.0MiB|1977.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |1639.0MiB|1639.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |1974.0MiB|1974.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |1975.0MiB|1975.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |868.0MiB|868.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |1993.0MiB|1993.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |1982.0MiB|1982.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |2057.0MiB|2057.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |2062.0MiB|2062.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |3860.0MiB|3860.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |1981.0MiB|1981.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |270.0MiB|270.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |286.0MiB|286.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  |320.0MiB|320.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |1977.0MiB|1977.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |2001.0MiB|2001.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |1290.0MiB|1290.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |1976.0MiB|1976.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |1989.0MiB|1989.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |1979.0MiB|1979.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |1977.0MiB|1977.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |1639.0MiB|1639.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |1974.0MiB|1974.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |1975.0MiB|1975.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |868.0MiB|868.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |1993.0MiB|1993.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |1982.0MiB|1982.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |2057.0MiB|2057.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |2062.0MiB|2062.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |3860.0MiB|3860.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |1981.0MiB|1981.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |270.0MiB|270.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |286.0MiB|286.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  |320.0MiB|320.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |1977.0MiB|1977.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |2001.0MiB|2001.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |1290.0MiB|1290.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |1976.0MiB|1976.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |1989.0MiB|1989.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |1979.0MiB|1979.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |1977.0MiB|1977.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |1639.0MiB|1639.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |1974.0MiB|1974.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |1975.0MiB|1975.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |868.0MiB|868.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |1993.0MiB|1993.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |1982.0MiB|1982.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |2057.0MiB|2057.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |2062.0MiB|2062.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |3860.0MiB|3860.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |1981.0MiB|1981.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-1065256.smt2                               | 600.930s |7030.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               | 600.887s |6871.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                | 601.112s |6476.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-943653.smt2                                | 600.766s |6174.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-993227.smt2                                | 600.757s |6166.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                | 600.861s |5889.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985918.smt2                                | 600.702s |5888.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-983194.smt2                              | 600.622s |5822.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                | 600.655s |5690.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1072007.smt2                             | 148.490s |5346.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                | 600.605s |5318.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                              | 600.884s |5240.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                | 600.711s |5211.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                              | 600.664s |5205.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                | 600.593s |5199.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                | 600.696s |5087.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-987361.smt2                                | 600.750s |5073.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-989891.smt2                              | 600.589s |5055.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-804609.smt2                                | 571.368s |4796.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1000539.smt2                               | 355.566s |4784.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-1065256.smt2                               | 600.930s |7030.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               | 600.887s |6871.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                | 601.112s |6476.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-943653.smt2                                | 600.766s |6174.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-993227.smt2                                | 600.757s |6166.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                | 600.861s |5889.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985918.smt2                                | 600.702s |5888.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-983194.smt2                              | 600.622s |5822.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                | 600.655s |5690.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1072007.smt2                             | 148.490s |5346.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                | 600.605s |5318.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                              | 600.884s |5240.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                | 600.711s |5211.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                              | 600.664s |5205.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                | 600.593s |5199.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                | 600.696s |5087.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-987361.smt2                                | 600.750s |5073.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-989891.smt2                              | 600.589s |5055.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-804609.smt2                                | 571.368s |4796.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1000539.smt2                               | 355.566s |4784.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |   3.705s  |   3.705s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/258-incremental_scheduling-40698-0.smt2  |  62.339s  |  62.339s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/295-incremental_scheduling-40626-0.smt2  | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |   4.795s  |   4.795s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |   4.193s  |   4.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   3.429s  |   3.429s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   4.179s  |   4.179s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |   4.154s  |   4.154s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   5.075s  |   5.075s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |   4.305s  |   4.305s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |   3.801s  |   3.801s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |   4.757s  |   4.757s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   4.375s  |   4.375s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   3.124s  |   3.124s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   4.287s  |   4.287s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   4.852s  |   4.852s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   3.531s  |   3.531s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   3.595s  |   3.595s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   5.317s  |   5.317s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   4.549s  |   4.549s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |   4.172s  |   4.172s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |   4.233s  |   4.233s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |   5.023s  |   5.023s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |   4.243s  |   4.243s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |   3.559s  |   3.559s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |   3.560s  |   3.560s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |   4.624s  |   4.624s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-12.smt2                       |   4.154s  |   4.154s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |   4.922s  |   4.922s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |   4.241s  |   4.241s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-15.smt2                       |   3.859s  |   3.859s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-00.smt2                      |   5.913s  |   5.913s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-01.smt2                      |   6.059s  |   6.059s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-02.smt2                      |   6.175s  |   6.175s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-03.smt2                      |   6.231s  |   6.231s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-07.smt2                      |   6.065s  |   6.065s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-08.smt2                      |   4.436s  |   4.436s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-09.smt2                      |   6.370s  |   6.370s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-10.smt2                      |   5.469s  |   5.469s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-11.smt2                      |   6.295s  |   6.295s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-12.smt2                      |   5.082s  |   5.082s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-13.smt2                      |   6.466s  |   6.466s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-14.smt2                      |   4.359s  |   4.359s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-15.smt2                      |   4.934s  |   4.934s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-00.smt2                      |   6.593s  |   6.593s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-08.smt2                      |   4.583s  |   4.583s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-09.smt2                      |   6.788s  |   6.788s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-10.smt2                      |   5.754s  |   5.754s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-11.smt2                      |   5.040s  |   5.040s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-12.smt2                      |   5.527s  |   5.527s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-13.smt2                      |   6.196s  |   6.196s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-14.smt2                      |   6.360s  |   6.360s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-15.smt2                      |   6.461s  |   6.461s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20231117-c_inference/80_80_71_17_unsat.smt2                          | 600.409s  | 600.409s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/RWS/Example_15.txt.smt2                                              | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/RWS/Example_18.txt.smt2                                              | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/RWS/Example_9.txt.smt2                                               | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1000539.smt2                                | 355.566s  | 355.566s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1007795.smt2                                |   7.282s  |   7.282s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                                | 600.887s  | 600.887s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1065256.smt2                                | 600.930s  | 600.930s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1096871.smt2                                |  80.061s  |  80.061s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1107622.smt2                                |  23.290s  |  23.290s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1121941.smt2                                |  29.377s  |  29.377s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1145584.smt2                                |  50.281s  |  50.281s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1148089.smt2                                |  58.069s  |  58.069s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1185949.smt2                                |  25.014s  |  25.014s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-391798.smt2                                 | 147.402s  | 147.402s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-392137.smt2                                 |   8.420s  |   8.420s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-408585.smt2                                 |  26.408s  |  26.408s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-415996.smt2                                 |  10.187s  |  10.187s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-478122.smt2                                 | 377.737s  | 377.737s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-481231.smt2                                 |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-487307.smt2                                 | 600.364s  | 600.364s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-506600.smt2                                 | 600.322s  | 600.322s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-518109.smt2                                 |  81.410s  |  81.410s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-526410.smt2                                 |   2.968s  |   2.968s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-533042.smt2                                 | 600.377s  | 600.377s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-551279.smt2                                 | 144.081s  | 144.081s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-569261.smt2                                 | 600.409s  | 600.409s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-618384.smt2                                 |  19.443s  |  19.443s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-644402.smt2                                 | 600.738s  | 600.738s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-654327.smt2                                 | 221.138s  | 221.138s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-655888.smt2                                 | 600.524s  | 600.524s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-687518.smt2                                 | 600.524s  | 600.524s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-689472.smt2                                 |  10.541s  |  10.541s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-765743.smt2                                 | 600.528s  | 600.528s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                 | 600.711s  | 600.711s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-804609.smt2                                 | 571.368s  | 571.368s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                 | 600.605s  | 600.605s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-864173.smt2                                 |  17.188s  |  17.188s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                 | 600.593s  | 600.593s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-901628.smt2                                 |  16.219s  |  16.219s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                 | 600.696s  | 600.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                 | 600.861s  | 600.861s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-906218.smt2                                 |  14.102s  |  14.102s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-916576.smt2                                 |   7.671s  |   7.671s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-928134.smt2                                 |   9.634s  |   9.634s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-928960.smt2                                 | 480.166s  | 480.166s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-943653.smt2                                 | 600.766s  | 600.766s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                 | 600.655s  | 600.655s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                 | 601.112s  | 601.112s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-985918.smt2                                 | 600.702s  | 600.702s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-987361.smt2                                 | 600.750s  | 600.750s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-993227.smt2                                 | 600.757s  | 600.757s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER10-13-fair.smt2                                       |  22.622s  |  22.622s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER10-14-fair.smt2                                       |  67.431s  |  67.431s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER11-14-fair.smt2                                       |  48.520s  |  48.520s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER11-15-fair.smt2                                       | 206.510s  | 206.510s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-13-48.smt2                           |  22.494s  |  22.494s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-13-50.smt2                           |  81.798s  |  81.798s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-14-49.smt2                           |  33.188s  |  33.188s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-14-50.smt2                           |  42.621s  |  42.621s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-16-48.smt2                           |  20.885s  |  20.885s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-16-49.smt2                           |  78.700s  |  78.700s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-16-50.smt2                           |  31.944s  |  31.944s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-17-47.smt2                           |  28.824s  |  28.824s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-17-50.smt2                           |  19.720s  |  19.720s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-18-46.smt2                           |  16.918s  |  16.918s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-18-48.smt2                           |  32.594s  |  32.594s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-18-50.smt2                           |  34.903s  |  34.903s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-19-49.smt2                           |  33.864s  |  33.864s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-19-50.smt2                           |  42.708s  |  42.708s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-20-45.smt2                           |  25.682s  |  25.682s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-22-48.smt2                           |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-22-49.smt2                           |  18.840s  |  18.840s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-22-50.smt2                           |  66.794s  |  66.794s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-24-49.smt2                           |  41.521s  |  41.521s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-25-50.smt2                           |  79.331s  |  79.331s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-27-47.smt2                           |  33.861s  |  33.861s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-27-49.smt2                           |  23.734s  |  23.734s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-27-50.smt2                           |  86.881s  |  86.881s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-28-48.smt2                           |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-28-49.smt2                           |  29.923s  |  29.923s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-28-50.smt2                           |  22.122s  |  22.122s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-29-48.smt2                           |  33.987s  |  33.987s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-29-50.smt2                           |  37.047s  |  37.047s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-30-48.smt2                           |  20.775s  |  20.775s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-32-47.smt2                           |  30.920s  |  30.920s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-32-49.smt2                           |  35.093s  |  35.093s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-32-50.smt2                           |  53.850s  |  53.850s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-33-50.smt2                           |  37.471s  |  37.471s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-34-45.smt2                           |  22.792s  |  22.792s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-34-48.smt2                           |  28.752s  |  28.752s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-45.smt2                           |  21.028s  |  21.028s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-46.smt2                           | 145.674s  | 145.674s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-47.smt2                           |  22.924s  |  22.924s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-45.smt2                           |  30.941s  |  30.941s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-46.smt2                           |  31.465s  |  31.465s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-47.smt2                           |  42.303s  |  42.303s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-48.smt2                           |  33.985s  |  33.985s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-49.smt2                           |  37.520s  |  37.520s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-50.smt2                           |  44.567s  |  44.567s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-45.smt2                           |  98.411s  |  98.411s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-46.smt2                           |  31.083s  |  31.083s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-47.smt2                           | 123.032s  | 123.032s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-48.smt2                           |  22.701s  |  22.701s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-45.smt2                           |  27.041s  |  27.041s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-46.smt2                           |  33.468s  |  33.468s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-47.smt2                           |  38.592s  |  38.592s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-48.smt2                           |  39.716s  |  39.716s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-49.smt2                           |  37.452s  |  37.452s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-50.smt2                           |  51.793s  |  51.793s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-45.smt2                           |  41.053s  |  41.053s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-46.smt2                           |  75.593s  |  75.593s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-47.smt2                           |  57.629s  |  57.629s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-48.smt2                           |  46.074s  |  46.074s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-49.smt2                           |  50.782s  |  50.782s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-50.smt2                           |  40.403s  |  40.403s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-4-45.smt2                            |  26.766s  |  26.766s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-4-48.smt2                            |  32.257s  |  32.257s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-4-49.smt2                            |  29.315s  |  29.315s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-4-50.smt2                            |  41.077s  |  41.077s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-45.smt2                           |  33.425s  |  33.425s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-46.smt2                           |  62.717s  |  62.717s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-47.smt2                           |  45.529s  |  45.529s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-48.smt2                           |  37.113s  |  37.113s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-49.smt2                           |  38.395s  |  38.395s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-50.smt2                           |  44.649s  |  44.649s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-45.smt2                           |  37.088s  |  37.088s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-46.smt2                           |  57.579s  |  57.579s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-47.smt2                           |  56.968s  |  56.968s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-48.smt2                           |  68.201s  |  68.201s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-49.smt2                           |  82.565s  |  82.565s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-50.smt2                           |  72.363s  |  72.363s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-45.smt2                           |  41.539s  |  41.539s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-46.smt2                           |  71.526s  |  71.526s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-47.smt2                           |  66.588s  |  66.588s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-48.smt2                           |  77.914s  |  77.914s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-49.smt2                           |  87.110s  |  87.110s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-50.smt2                           |  44.439s  |  44.439s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-45.smt2                           |  32.867s  |  32.867s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-46.smt2                           |  43.700s  |  43.700s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-47.smt2                           |  36.820s  |  36.820s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-48.smt2                           |  54.297s  |  54.297s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-49.smt2                           |  63.827s  |  63.827s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-50.smt2                           |  47.057s  |  47.057s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-45.smt2                           |  37.763s  |  37.763s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-46.smt2                           |  87.722s  |  87.722s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-47.smt2                           |  94.416s  |  94.416s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-48.smt2                           |  69.677s  |  69.677s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-49.smt2                           |  70.283s  |  70.283s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-50.smt2                           | 122.047s  | 122.047s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-45.smt2                           |  34.708s  |  34.708s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-46.smt2                           |  58.573s  |  58.573s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-47.smt2                           |  49.057s  |  49.057s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-48.smt2                           |  52.561s  |  52.561s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-49.smt2                           |  71.604s  |  71.604s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-50.smt2                           |  68.743s  |  68.743s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-45.smt2                           |  31.216s  |  31.216s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-46.smt2                           |  38.940s  |  38.940s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-47.smt2                           |  49.168s  |  49.168s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-48.smt2                           |  58.019s  |  58.019s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-49.smt2                           |  59.353s  |  59.353s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-50.smt2                           |  62.401s  |  62.401s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-45.smt2                           |  47.932s  |  47.932s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-46.smt2                           |  72.603s  |  72.603s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-47.smt2                           |  69.448s  |  69.448s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-48.smt2                           |  80.653s  |  80.653s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-49.smt2                           |  79.294s  |  79.294s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-50.smt2                           | 109.377s  | 109.377s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-45.smt2                           |  37.722s  |  37.722s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-46.smt2                           |  73.545s  |  73.545s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-47.smt2                           |  75.473s  |  75.473s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-48.smt2                           |  56.439s  |  56.439s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-49.smt2                           |  77.308s  |  77.308s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-50.smt2                           |  88.047s  |  88.047s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-45.smt2                           |  39.531s  |  39.531s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-46.smt2                           |  46.882s  |  46.882s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-47.smt2                           |  57.920s  |  57.920s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-48.smt2                           |  96.328s  |  96.328s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-49.smt2                           |  70.654s  |  70.654s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-50.smt2                           | 107.042s  | 107.042s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-5-47.smt2                            |  60.463s  |  60.463s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-5-48.smt2                            |  24.945s  |  24.945s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-5-49.smt2                            |  42.838s  |  42.838s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-5-50.smt2                            |  40.303s  |  40.303s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-45.smt2                           |  44.957s  |  44.957s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-46.smt2                           |  48.545s  |  48.545s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-47.smt2                           |  57.195s  |  57.195s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-48.smt2                           |  81.697s  |  81.697s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-49.smt2                           |  94.359s  |  94.359s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-50.smt2                           | 115.277s  | 115.277s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-45.smt2                           |  37.326s  |  37.326s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-46.smt2                           |  64.527s  |  64.527s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-47.smt2                           |  45.362s  |  45.362s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-48.smt2                           |  71.223s  |  71.223s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-49.smt2                           |  68.242s  |  68.242s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-50.smt2                           |  99.442s  |  99.442s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-45.smt2                           |  38.234s  |  38.234s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-46.smt2                           |  39.442s  |  39.442s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-47.smt2                           |  62.063s  |  62.063s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-48.smt2                           |  60.615s  |  60.615s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-49.smt2                           |  63.929s  |  63.929s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-50.smt2                           |  97.130s  |  97.130s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-45.smt2                           |  40.368s  |  40.368s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-46.smt2                           |  40.637s  |  40.637s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-47.smt2                           |  51.932s  |  51.932s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-48.smt2                           |  55.843s  |  55.843s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-49.smt2                           |  62.215s  |  62.215s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-50.smt2                           |  76.274s  |  76.274s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-45.smt2                           |  45.044s  |  45.044s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-46.smt2                           |  43.018s  |  43.018s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-47.smt2                           |  57.081s  |  57.081s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-48.smt2                           |  77.701s  |  77.701s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-49.smt2                           |  75.842s  |  75.842s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-50.smt2                           |  96.609s  |  96.609s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-46.smt2                           |  47.710s  |  47.710s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-47.smt2                           |  48.931s  |  48.931s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-48.smt2                           |  63.726s  |  63.726s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-49.smt2                           |  63.156s  |  63.156s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-50.smt2                           |  76.473s  |  76.473s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-46.smt2                           |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-47.smt2                           |  51.917s  |  51.917s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-48.smt2                           |  61.741s  |  61.741s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-49.smt2                           |  74.457s  |  74.457s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-50.smt2                           |  88.970s  |  88.970s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-48.smt2                           |  54.631s  |  54.631s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-49.smt2                           |  63.990s  |  63.990s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-50.smt2                           |  80.381s  |  80.381s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-47.smt2                           |  48.761s  |  48.761s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-48.smt2                           |  49.892s  |  49.892s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-49.smt2                           |  63.829s  |  63.829s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-50.smt2                           |  75.130s  |  75.130s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-59-48.smt2                           |  63.449s  |  63.449s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-59-49.smt2                           |  71.073s  |  71.073s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-59-50.smt2                           |  80.405s  |  80.405s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-60-48.smt2                           |  69.270s  |  69.270s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-60-49.smt2                           |  60.773s  |  60.773s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-60-50.smt2                           | 118.035s  | 118.035s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-61-49.smt2                           |  67.404s  |  67.404s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-61-50.smt2                           |  78.908s  |  78.908s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-62-49.smt2                           |  81.095s  |  81.095s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-62-50.smt2                           | 116.582s  | 116.582s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-63-50.smt2                           |  89.374s  |  89.374s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-46.smt2                            |  16.236s  |  16.236s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-47.smt2                            |  47.879s  |  47.879s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-48.smt2                            |  19.020s  |  19.020s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-49.smt2                            |  20.514s  |  20.514s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-50.smt2                            | 129.227s  | 129.227s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-46.smt2                            |  36.356s  |  36.356s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-47.smt2                            |  35.125s  |  35.125s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-48.smt2                            |  22.093s  |  22.093s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-49.smt2                            |  28.639s  |  28.639s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-50.smt2                            |  51.883s  |  51.883s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-46.smt2                   | 219.135s  | 219.135s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-47.smt2                   | 319.984s  | 319.984s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-48.smt2                   | 493.190s  | 493.190s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-49.smt2                   | 547.093s  | 547.093s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-50.smt2                   | 600.218s  | 600.218s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-46.smt2                   | 238.859s  | 238.859s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-47.smt2                   | 398.225s  | 398.225s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-48.smt2                   | 397.732s  | 397.732s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-49.smt2                   | 483.373s  | 483.373s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-50.smt2                   | 571.958s  | 571.958s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-46.smt2                   | 148.013s  | 148.013s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-47.smt2                   | 213.053s  | 213.053s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-48.smt2                   | 261.529s  | 261.529s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-49.smt2                   | 310.995s  | 310.995s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-50.smt2                   | 235.843s  | 235.843s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-46.smt2                   |  69.059s  |  69.059s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-47.smt2                   |  66.317s  |  66.317s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-48.smt2                   | 143.144s  | 143.144s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-49.smt2                   | 183.786s  | 183.786s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-50.smt2                   | 234.183s  | 234.183s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-47.smt2                    |  36.113s  |  36.113s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-48.smt2                    |  47.426s  |  47.426s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-49.smt2                    |  54.561s  |  54.561s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-50.smt2                    |  98.038s  |  98.038s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-46.smt2                    | 129.293s  | 129.293s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-47.smt2                    | 110.425s  | 110.425s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-48.smt2                    | 174.896s  | 174.896s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-49.smt2                    | 172.996s  | 172.996s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-50.smt2                    | 144.953s  | 144.953s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-46.smt2                    | 106.634s  | 106.634s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-47.smt2                    | 141.961s  | 141.961s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-48.smt2                    | 176.742s  | 176.742s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-49.smt2                    | 239.092s  | 239.092s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-50.smt2                    | 350.047s  | 350.047s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-8-47.smt2                    |  11.967s  |  11.967s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-8-49.smt2                    |  14.899s  |  14.899s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-8-50.smt2                    |  17.316s  |  17.316s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-13-50.smt2                         |  24.265s  |  24.265s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-14-50.smt2                         |  22.607s  |  22.607s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-16-50.smt2                         |  21.289s  |  21.289s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-17-50.smt2                         |  22.704s  |  22.704s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-19-50.smt2                         |  23.327s  |  23.327s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-2-50.smt2                          |  23.133s  |  23.133s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-21-50.smt2                         |  22.207s  |  22.207s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-22-50.smt2                         |  22.477s  |  22.477s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-23-50.smt2                         |  22.087s  |  22.087s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-25-50.smt2                         |  97.061s  |  97.061s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-26-50.smt2                         |  40.606s  |  40.606s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-27-50.smt2                         |  58.570s  |  58.570s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-28-50.smt2                         |  89.625s  |  89.625s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-29-50.smt2                         |  59.697s  |  59.697s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-30-50.smt2                         |  20.152s  |  20.152s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-31-50.smt2                         |  22.337s  |  22.337s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-32-50.smt2                         |  24.844s  |  24.844s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-33-50.smt2                         |  19.704s  |  19.704s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-35-50.smt2                         |  30.208s  |  30.208s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-37-50.smt2                         |  23.043s  |  23.043s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-38-50.smt2                         |  23.087s  |  23.087s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-39-50.smt2                         |  39.584s  |  39.584s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-40-50.smt2                         |  24.644s  |  24.644s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-41-50.smt2                         |  48.894s  |  48.894s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-42-50.smt2                         |  24.062s  |  24.062s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-43-50.smt2                         |  44.625s  |  44.625s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-44-50.smt2                         |  40.792s  |  40.792s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-45-50.smt2                         |  25.565s  |  25.565s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-46-50.smt2                         |  25.179s  |  25.179s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-47-50.smt2                         |  23.762s  |  23.762s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-48-50.smt2                         |  25.907s  |  25.907s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-49-50.smt2                         |  25.645s  |  25.645s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-5-50.smt2                          |  20.372s  |  20.372s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-50-50.smt2                         |  37.648s  |  37.648s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-51-50.smt2                         |  34.465s  |  34.465s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-52-50.smt2                         |  36.932s  |  36.932s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-53-50.smt2                         |  31.660s  |  31.660s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-54-50.smt2                         |  34.449s  |  34.449s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-55-50.smt2                         |  31.293s  |  31.293s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-58-50.smt2                         |  34.879s  |  34.879s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-59-50.smt2                         |  24.083s  |  24.083s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-60-50.smt2                         |  24.643s  |  24.643s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-61-50.smt2                         |  26.346s  |  26.346s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-63-50.smt2                         |  35.254s  |  35.254s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-64-50.smt2                         |  28.395s  |  28.395s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-65-50.smt2                         |  28.416s  |  28.416s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-67-50.smt2                         |  30.178s  |  30.178s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-68-50.smt2                         |  32.192s  |  32.192s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-69-50.smt2                         |  30.913s  |  30.913s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-70-50.smt2                         |  27.128s  |  27.128s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-9-50.smt2                          |  20.382s  |  20.382s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-46.smt2                           |  37.604s  |  37.604s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-47.smt2                           |  35.058s  |  35.058s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-48.smt2                           |  40.335s  |  40.335s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-49.smt2                           |  47.490s  |  47.490s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-50.smt2                           |  51.595s  |  51.595s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-46.smt2                           |  35.565s  |  35.565s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-47.smt2                           |  35.446s  |  35.446s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-48.smt2                           |  48.353s  |  48.353s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-50.smt2                           |  62.705s  |  62.705s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-46.smt2                          | 357.692s  | 357.692s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-47.smt2                          | 245.197s  | 245.197s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-48.smt2                          |  73.241s  |  73.241s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-49.smt2                          | 410.915s  | 410.915s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-50.smt2                          | 518.157s  | 518.157s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-46.smt2                          | 278.851s  | 278.851s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-47.smt2                          | 177.082s  | 177.082s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-48.smt2                          |  75.623s  |  75.623s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-49.smt2                          | 307.494s  | 307.494s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-50.smt2                          | 600.279s  | 600.279s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-46.smt2                          |  31.789s  |  31.789s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-47.smt2                          |  36.617s  |  36.617s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-48.smt2                          |  43.406s  |  43.406s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-49.smt2                          |  43.469s  |  43.469s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-50.smt2                          |  50.280s  |  50.280s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-46.smt2                          | 212.313s  | 212.313s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-47.smt2                          | 243.682s  | 243.682s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-48.smt2                          |  76.562s  |  76.562s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-49.smt2                          | 403.621s  | 403.621s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-50.smt2                          | 299.845s  | 299.845s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-46.smt2                          |  29.992s  |  29.992s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-47.smt2                          |  35.614s  |  35.614s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-49.smt2                          |  43.454s  |  43.454s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-50.smt2                          |  50.799s  |  50.799s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-46.smt2                          |  29.591s  |  29.591s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-47.smt2                          |  35.685s  |  35.685s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-48.smt2                          |  39.994s  |  39.994s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-49.smt2                          |  48.323s  |  48.323s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-50.smt2                          |  51.328s  |  51.328s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-46.smt2                          | 162.681s  | 162.681s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-47.smt2                          | 156.696s  | 156.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-48.smt2                          |  63.573s  |  63.573s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-49.smt2                          | 468.306s  | 468.306s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-50.smt2                          | 340.975s  | 340.975s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-46.smt2                          | 210.058s  | 210.058s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-47.smt2                          | 221.309s  | 221.309s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-48.smt2                          |  63.078s  |  63.078s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-49.smt2                          | 497.752s  | 497.752s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-50.smt2                          | 290.263s  | 290.263s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-46.smt2                          |  33.125s  |  33.125s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-47.smt2                          |  37.481s  |  37.481s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-48.smt2                          |  42.343s  |  42.343s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-49.smt2                          |  50.793s  |  50.793s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-50.smt2                          |  55.235s  |  55.235s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-46.smt2                          | 156.036s  | 156.036s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-47.smt2                          | 130.525s  | 130.525s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-48.smt2                          |  58.415s  |  58.415s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-49.smt2                          | 468.720s  | 468.720s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-50.smt2                          | 423.118s  | 423.118s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-46.smt2                           | 214.004s  | 214.004s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-47.smt2                           | 294.267s  | 294.267s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-48.smt2                           |  66.164s  |  66.164s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-49.smt2                           | 600.209s  | 600.209s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-50.smt2                           | 538.165s  | 538.165s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-46.smt2                          |  39.838s  |  39.838s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-47.smt2                          |  33.097s  |  33.097s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-48.smt2                          |  42.666s  |  42.666s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-49.smt2                          |  53.222s  |  53.222s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-50.smt2                          |  61.387s  |  61.387s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-46.smt2                          |  42.365s  |  42.365s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-47.smt2                          |  41.676s  |  41.676s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-48.smt2                          |  43.956s  |  43.956s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-49.smt2                          |  53.118s  |  53.118s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-50.smt2                          |  59.538s  |  59.538s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-46.smt2                          | 237.660s  | 237.660s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-47.smt2                          | 142.268s  | 142.268s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-48.smt2                          |  51.447s  |  51.447s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-49.smt2                          | 527.382s  | 527.382s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-46.smt2                          | 209.731s  | 209.731s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-47.smt2                          | 243.565s  | 243.565s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-48.smt2                          |  54.497s  |  54.497s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-49.smt2                          | 600.285s  | 600.285s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-50.smt2                          | 294.168s  | 294.168s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-46.smt2                          |  44.345s  |  44.345s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-47.smt2                          |  39.738s  |  39.738s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-48.smt2                          |  51.751s  |  51.751s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-49.smt2                          |  63.035s  |  63.035s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-50.smt2                          |  77.970s  |  77.970s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-46.smt2                          | 123.252s  | 123.252s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-47.smt2                          | 158.339s  | 158.339s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-48.smt2                          |  55.201s  |  55.201s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-49.smt2                          | 263.941s  | 263.941s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-50.smt2                          | 339.987s  | 339.987s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-46.smt2                          |  42.293s  |  42.293s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-47.smt2                          |  50.883s  |  50.883s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-48.smt2                          |  47.776s  |  47.776s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-49.smt2                          |  77.068s  |  77.068s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-50.smt2                          |  80.030s  |  80.030s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-46.smt2                          |  43.685s  |  43.685s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-47.smt2                          |  71.021s  |  71.021s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-48.smt2                          |  46.042s  |  46.042s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-49.smt2                          |  69.473s  |  69.473s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-50.smt2                          |  77.573s  |  77.573s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-47.smt2                          | 495.372s  | 495.372s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-48.smt2                          | 600.184s  | 600.184s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-49.smt2                          | 600.420s  | 600.420s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-50.smt2                          | 600.263s  | 600.263s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-46.smt2                          | 214.122s  | 214.122s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-47.smt2                          |  73.293s  |  73.293s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-48.smt2                          | 419.635s  | 419.635s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-49.smt2                          | 600.254s  | 600.254s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-50.smt2                          | 600.224s  | 600.224s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-46.smt2                           | 300.114s  | 300.114s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-47.smt2                           | 180.098s  | 180.098s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-48.smt2                           |  89.702s  |  89.702s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-49.smt2                           | 468.790s  | 468.790s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-50.smt2                           | 370.330s  | 370.330s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-46.smt2                          | 416.032s  | 416.032s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-47.smt2                          | 358.692s  | 358.692s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-48.smt2                          | 600.153s  | 600.153s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-49.smt2                          | 600.367s  | 600.367s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-50.smt2                          | 600.367s  | 600.367s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-46.smt2                          |  61.161s  |  61.161s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-47.smt2                          |  43.479s  |  43.479s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-48.smt2                          |  53.665s  |  53.665s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-49.smt2                          |  75.867s  |  75.867s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-50.smt2                          |  93.261s  |  93.261s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-46.smt2                          | 175.382s  | 175.382s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-47.smt2                          | 262.032s  | 262.032s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-48.smt2                          |  60.939s  |  60.939s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-49.smt2                          | 367.263s  | 367.263s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-50.smt2                          | 499.409s  | 499.409s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-46.smt2                          | 244.580s  | 244.580s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-47.smt2                          | 156.155s  | 156.155s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-48.smt2                          | 314.902s  | 314.902s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-49.smt2                          | 575.767s  | 575.767s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-50.smt2                          | 600.361s  | 600.361s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-46.smt2                          |  53.999s  |  53.999s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-47.smt2                          | 281.134s  | 281.134s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-48.smt2                          | 332.478s  | 332.478s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-49.smt2                          | 132.081s  | 132.081s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-50.smt2                          | 600.219s  | 600.219s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-46.smt2                          |  54.449s  |  54.449s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-47.smt2                          |  79.084s  |  79.084s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-48.smt2                          |  86.641s  |  86.641s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-49.smt2                          | 131.809s  | 131.809s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-50.smt2                          | 130.770s  | 130.770s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-46.smt2                          |  52.914s  |  52.914s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-47.smt2                          |  85.838s  |  85.838s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-48.smt2                          | 135.978s  | 135.978s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-49.smt2                          | 111.026s  | 111.026s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-50.smt2                          | 170.420s  | 170.420s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-47.smt2                          |  13.467s  |  13.467s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-48.smt2                          | 372.119s  | 372.119s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-49.smt2                          | 600.373s  | 600.373s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-50.smt2                          | 503.278s  | 503.278s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-46.smt2                          | 176.814s  | 176.814s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-47.smt2                          | 122.847s  | 122.847s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-48.smt2                          |  55.024s  |  55.024s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-49.smt2                          | 352.467s  | 352.467s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-50.smt2                          | 413.981s  | 413.981s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-46.smt2                          | 168.688s  | 168.688s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-47.smt2                          |  54.609s  |  54.609s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-48.smt2                          | 262.423s  | 262.423s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-49.smt2                          | 600.327s  | 600.327s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-50.smt2                          | 163.904s  | 163.904s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-46.smt2                           |  30.270s  |  30.270s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-47.smt2                           |  33.941s  |  33.941s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-48.smt2                           |  50.207s  |  50.207s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-49.smt2                           |  49.839s  |  49.839s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-50.smt2                           |  61.247s  |  61.247s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-46.smt2                          | 211.844s  | 211.844s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-47.smt2                          | 286.118s  | 286.118s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-48.smt2                          | 406.730s  | 406.730s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-49.smt2                          | 546.484s  | 546.484s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-50.smt2                          | 600.375s  | 600.375s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-46.smt2                          | 184.070s  | 184.070s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-47.smt2                          | 278.472s  | 278.472s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-48.smt2                          | 479.221s  | 479.221s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-49.smt2                          | 600.338s  | 600.338s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-50.smt2                          | 600.337s  | 600.337s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-47.smt2                          |  14.428s  |  14.428s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-48.smt2                          |  17.130s  |  17.130s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-49.smt2                          | 506.912s  | 506.912s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-50.smt2                          | 600.414s  | 600.414s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-46.smt2                          | 102.179s  | 102.179s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-47.smt2                          | 190.384s  | 190.384s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-48.smt2                          |  61.150s  |  61.150s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-49.smt2                          | 328.718s  | 328.718s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-50.smt2                          | 323.002s  | 323.002s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-46.smt2                          | 161.440s  | 161.440s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-47.smt2                          | 258.419s  | 258.419s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-48.smt2                          | 177.038s  | 177.038s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-49.smt2                          | 215.897s  | 215.897s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-50.smt2                          | 478.642s  | 478.642s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-46.smt2                          | 117.931s  | 117.931s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-47.smt2                          | 133.438s  | 133.438s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-48.smt2                          |  56.258s  |  56.258s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-49.smt2                          | 371.880s  | 371.880s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-50.smt2                          | 379.894s  | 379.894s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-46.smt2                          | 107.893s  | 107.893s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-47.smt2                          | 148.678s  | 148.678s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-48.smt2                          | 213.468s  | 213.468s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-49.smt2                          | 266.075s  | 266.075s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-50.smt2                          | 316.871s  | 316.871s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-46.smt2                          | 136.332s  | 136.332s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-47.smt2                          | 136.166s  | 136.166s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-48.smt2                          | 106.555s  | 106.555s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-49.smt2                          | 384.287s  | 384.287s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-50.smt2                          | 332.637s  | 332.637s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-46.smt2                          | 111.463s  | 111.463s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-47.smt2                          | 112.806s  | 112.806s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-48.smt2                          | 219.685s  | 219.685s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-49.smt2                          | 219.756s  | 219.756s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-50.smt2                          | 204.282s  | 204.282s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-46.smt2                          |  68.916s  |  68.916s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-47.smt2                          | 134.655s  | 134.655s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-48.smt2                          |  55.602s  |  55.602s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-49.smt2                          | 361.340s  | 361.340s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-50.smt2                          | 293.850s  | 293.850s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-46.smt2                           |  30.906s  |  30.906s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-47.smt2                           |  35.644s  |  35.644s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-48.smt2                           |  48.478s  |  48.478s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-49.smt2                           |  48.165s  |  48.165s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-50.smt2                           |  56.146s  |  56.146s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-46.smt2                          | 122.787s  | 122.787s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-47.smt2                          | 167.414s  | 167.414s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-48.smt2                          | 165.488s  | 165.488s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-49.smt2                          | 403.607s  | 403.607s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-50.smt2                          | 269.460s  | 269.460s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-47.smt2                          | 125.290s  | 125.290s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-48.smt2                          |  73.076s  |  73.076s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-49.smt2                          | 383.980s  | 383.980s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-50.smt2                          | 391.893s  | 391.893s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-46.smt2                           |  28.487s  |  28.487s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-47.smt2                           |  33.618s  |  33.618s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-48.smt2                           |  34.907s  |  34.907s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-49.smt2                           |  42.059s  |  42.059s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-50.smt2                           |  52.700s  |  52.700s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-46.smt2                           |  33.488s  |  33.488s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-47.smt2                           |  33.371s  |  33.371s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-48.smt2                           |  42.691s  |  42.691s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-49.smt2                           |  49.771s  |  49.771s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-50.smt2                           |  54.642s  |  54.642s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-46.smt2                           | 196.133s  | 196.133s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-47.smt2                           | 199.293s  | 199.293s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-48.smt2                           |  73.877s  |  73.877s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-50.smt2                           | 328.421s  | 328.421s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-46.smt2                           | 347.169s  | 347.169s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-47.smt2                           | 181.267s  | 181.267s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-48.smt2                           |  95.666s  |  95.666s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-49.smt2                           | 600.279s  | 600.279s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-50.smt2                           | 600.273s  | 600.273s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-46.smt2                         |  61.862s  |  61.862s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-47.smt2                         |  82.811s  |  82.811s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-48.smt2                         | 174.905s  | 174.905s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-49.smt2                         |  51.952s  |  51.952s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-50.smt2                         |  95.286s  |  95.286s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-46.smt2                         |  87.981s  |  87.981s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-47.smt2                         |  95.316s  |  95.316s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-48.smt2                         | 119.023s  | 119.023s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-49.smt2                         | 151.227s  | 151.227s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-50.smt2                         |  94.353s  |  94.353s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-46.smt2                        | 600.192s  | 600.192s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-47.smt2                        | 600.296s  | 600.296s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-48.smt2                        | 495.908s  | 495.908s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-49.smt2                        | 398.887s  | 398.887s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-50.smt2                        | 595.725s  | 595.725s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-46.smt2                        | 162.767s  | 162.767s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-47.smt2                        | 209.941s  | 209.941s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-48.smt2                        | 242.395s  | 242.395s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-49.smt2                        | 281.504s  | 281.504s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-50.smt2                        | 600.169s  | 600.169s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-46.smt2                        |  43.776s  |  43.776s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-47.smt2                        | 321.249s  | 321.249s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-48.smt2                        | 440.217s  | 440.217s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-49.smt2                        | 367.980s  | 367.980s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-50.smt2                        | 556.738s  | 556.738s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-46.smt2                        |  61.049s  |  61.049s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-47.smt2                        | 143.351s  | 143.351s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-48.smt2                        | 112.246s  | 112.246s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-49.smt2                        | 381.503s  | 381.503s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-50.smt2                        | 333.696s  | 333.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-46.smt2                        | 144.091s  | 144.091s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-47.smt2                        | 122.609s  | 122.609s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-48.smt2                        | 106.188s  | 106.188s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-49.smt2                        | 325.898s  | 325.898s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-50.smt2                        | 134.874s  | 134.874s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-46.smt2                        |  39.363s  |  39.363s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-47.smt2                        | 217.963s  | 217.963s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-48.smt2                        |  43.996s  |  43.996s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-49.smt2                        | 106.172s  | 106.172s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-50.smt2                        | 336.426s  | 336.426s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-46.smt2                        |  60.260s  |  60.260s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-47.smt2                        | 126.718s  | 126.718s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-48.smt2                        |  88.971s  |  88.971s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-49.smt2                        |  92.996s  |  92.996s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-50.smt2                        | 430.612s  | 430.612s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-46.smt2                        |  36.507s  |  36.507s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-47.smt2                        |  77.480s  |  77.480s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-48.smt2                        |  45.544s  |  45.544s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-49.smt2                        |  58.660s  |  58.660s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-50.smt2                        | 422.426s  | 422.426s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-46.smt2                        |  31.546s  |  31.546s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-47.smt2                        |  97.552s  |  97.552s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-48.smt2                        |  42.626s  |  42.626s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-49.smt2                        | 213.737s  | 213.737s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-50.smt2                        |  83.503s  |  83.503s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-47.smt2                        | 144.281s  | 144.281s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-48.smt2                        | 133.313s  | 133.313s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-49.smt2                        | 222.738s  | 222.738s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-50.smt2                        | 241.719s  | 241.719s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-46.smt2                         | 205.152s  | 205.152s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-47.smt2                         | 308.313s  | 308.313s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-48.smt2                         | 326.758s  | 326.758s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-49.smt2                         | 204.779s  | 204.779s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-50.smt2                         | 355.221s  | 355.221s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-46.smt2                        |  50.170s  |  50.170s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-47.smt2                        |  37.115s  |  37.115s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-48.smt2                        | 102.992s  | 102.992s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-49.smt2                        | 241.341s  | 241.341s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-50.smt2                        | 150.473s  | 150.473s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-46.smt2                        |  89.818s  |  89.818s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-47.smt2                        |  70.284s  |  70.284s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-48.smt2                        | 112.342s  | 112.342s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-49.smt2                        |  47.223s  |  47.223s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-50.smt2                        | 254.083s  | 254.083s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-46.smt2                        |  61.331s  |  61.331s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-47.smt2                        |  80.052s  |  80.052s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-48.smt2                        |  65.562s  |  65.562s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-49.smt2                        | 324.543s  | 324.543s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-50.smt2                        | 116.283s  | 116.283s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-46.smt2                        | 118.892s  | 118.892s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-47.smt2                        | 154.793s  | 154.793s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-48.smt2                        |  45.893s  |  45.893s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-49.smt2                        |  90.411s  |  90.411s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-50.smt2                        | 132.699s  | 132.699s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-46.smt2                        |  29.893s  |  29.893s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-47.smt2                        |  63.587s  |  63.587s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-48.smt2                        | 106.386s  | 106.386s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-49.smt2                        | 166.472s  | 166.472s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-50.smt2                        | 141.729s  | 141.729s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-46.smt2                         | 106.118s  | 106.118s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-47.smt2                         | 107.382s  | 107.382s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-48.smt2                         | 162.146s  | 162.146s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-49.smt2                         | 160.353s  | 160.353s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-50.smt2                         | 131.869s  | 131.869s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-46.smt2                         | 297.136s  | 297.136s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-47.smt2                         | 156.196s  | 156.196s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-48.smt2                         | 196.482s  | 196.482s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-49.smt2                         | 274.583s  | 274.583s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-50.smt2                         | 376.345s  | 376.345s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-46.smt2                         | 181.107s  | 181.107s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-47.smt2                         | 231.269s  | 231.269s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-48.smt2                         | 266.714s  | 266.714s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-49.smt2                         | 342.362s  | 342.362s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-50.smt2                         | 456.909s  | 456.909s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-46.smt2                         |  90.963s  |  90.963s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-47.smt2                         | 174.201s  | 174.201s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-48.smt2                         |  67.940s  |  67.940s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-49.smt2                         | 446.320s  | 446.320s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-46.smt2                         | 230.296s  | 230.296s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-47.smt2                         | 349.854s  | 349.854s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-48.smt2                         | 103.661s  | 103.661s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-49.smt2                         | 503.522s  | 503.522s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-50.smt2                         |  89.547s  |  89.547s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-46.smt2                         |  54.809s  |  54.809s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-47.smt2                         | 283.501s  | 283.501s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-48.smt2                         | 290.699s  | 290.699s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-49.smt2                         | 371.896s  | 371.896s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-50.smt2                         | 178.486s  | 178.486s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-46.smt2                         |  96.530s  |  96.530s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-47.smt2                         |  78.698s  |  78.698s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-48.smt2                         | 178.835s  | 178.835s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-49.smt2                         | 208.607s  | 208.607s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-50.smt2                         | 120.266s  | 120.266s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1015084.smt2                              |  10.369s  |  10.369s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1072007.smt2                              | 148.490s  | 148.490s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1192684.smt2                              |  23.984s  |  23.984s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-373262.smt2                               | 584.995s  | 584.995s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-394532.smt2                               | 513.606s  | 513.606s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-413904.smt2                               |  17.048s  |  17.048s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-416752.smt2                               | 216.558s  | 216.558s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-479884.smt2                               | 195.092s  | 195.092s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-495717.smt2                               | 158.874s  | 158.874s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-496324.smt2                               |  46.295s  |  46.295s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-527358.smt2                               |   4.693s  |   4.693s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-556171.smt2                               | 600.374s  | 600.374s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-579281.smt2                               | 600.438s  | 600.438s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-603294.smt2                               | 226.734s  | 226.734s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-614657.smt2                               |  78.398s  |  78.398s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-645855.smt2                               | 600.432s  | 600.432s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-649834.smt2                               |   6.638s  |   6.638s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-658040.smt2                               | 281.377s  | 281.377s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-687179.smt2                               | 307.931s  | 307.931s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-696340.smt2                               | 600.454s  | 600.454s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-705295.smt2                               |  11.881s  |  11.881s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-715402.smt2                               | 600.523s  | 600.523s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-729964.smt2                               |  72.167s  |  72.167s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-735583.smt2                               | 600.599s  | 600.599s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-737829.smt2                               | 600.499s  | 600.499s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-740637.smt2                               | 600.436s  | 600.436s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-758897.smt2                               |  14.879s  |  14.879s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-762853.smt2                               | 226.830s  | 226.830s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-794687.smt2                               |  11.836s  |  11.836s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-797738.smt2                               | 600.609s  | 600.609s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                               | 600.884s  | 600.884s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                               | 600.664s  | 600.664s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-901996.smt2                               |  13.477s  |  13.477s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-906586.smt2                               |  37.660s  |  37.660s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-916807.smt2                               |  10.972s  |  10.972s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-917322.smt2                               |  14.264s  |  14.264s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-983194.smt2                               | 600.622s  | 600.622s  |   0.000s  | 0.0%|
</details>
