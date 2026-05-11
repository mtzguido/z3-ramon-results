Comparing data and data


# SUMMARY
- LHS tests = 800
- RHS tests = 800
- LHS success = 800  (100.0%)
- RHS success = 800  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-QF_LIA_hard-timeout10min-bb2
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: c383004968f5bf66a9668a7ae254c83d45ac3afe
Z3 branch: fmcad26_artifact
Z3 options: "-T:1200 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_LIA.tar.zst?download=1
Z3 commit message: add ablate_backtracking experiment

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-QF_LIA_hard-timeout10min-bb2
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: c383004968f5bf66a9668a7ae254c83d45ac3afe
Z3 branch: fmcad26_artifact
Z3 options: "-T:1200 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_LIA.tar.zst?download=1
Z3 commit message: add ablate_backtracking experiment

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   2.286s  |   2.286s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   3.215s  |   3.215s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   3.767s  |   3.767s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   3.079s  |   3.079s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   2.116s  |   2.116s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   3.212s  |   3.212s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   3.775s  |   3.775s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   2.442s  |   2.442s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   3.727s  |   3.727s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   3.180s  |   3.180s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |   3.275s  |   3.275s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |   3.115s  |   3.115s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |   3.644s  |   3.644s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |   3.290s  |   3.290s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |   2.458s  |   2.458s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |   2.372s  |   2.372s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |   3.571s  |   3.571s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |   3.160s  |   3.160s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |   3.115s  |   3.115s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   2.286s  |   2.286s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   3.215s  |   3.215s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   3.767s  |   3.767s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   3.079s  |   3.079s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   2.116s  |   2.116s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   3.212s  |   3.212s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   3.775s  |   3.775s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   2.442s  |   2.442s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   3.727s  |   3.727s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   3.180s  |   3.180s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |   3.275s  |   3.275s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |   3.115s  |   3.115s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |   3.644s  |   3.644s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |   3.290s  |   3.290s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |   2.458s  |   2.458s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |   2.372s  |   2.372s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |   3.571s  |   3.571s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |   3.160s  |   3.160s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |   3.115s  |   3.115s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   2.286s  |   2.286s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   3.215s  |   3.215s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   3.767s  |   3.767s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   3.079s  |   3.079s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   2.116s  |   2.116s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   3.212s  |   3.212s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   3.775s  |   3.775s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   2.442s  |   2.442s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   3.727s  |   3.727s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   3.180s  |   3.180s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |   3.275s  |   3.275s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |   3.115s  |   3.115s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |   3.644s  |   3.644s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |   3.290s  |   3.290s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |   2.458s  |   2.458s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |   2.372s  |   2.372s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |   3.571s  |   3.571s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |   3.160s  |   3.160s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |   3.115s  |   3.115s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   2.286s  |   2.286s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   3.215s  |   3.215s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   3.767s  |   3.767s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   3.079s  |   3.079s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   2.116s  |   2.116s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   3.212s  |   3.212s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   3.775s  |   3.775s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   2.442s  |   2.442s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   3.727s  |   3.727s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   3.180s  |   3.180s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |   3.275s  |   3.275s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |   3.115s  |   3.115s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |   3.644s  |   3.644s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |   3.290s  |   3.290s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |   2.458s  |   2.458s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |   2.372s  |   2.372s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |   3.571s  |   3.571s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |   3.160s  |   3.160s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |   3.115s  |   3.115s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-1228327.smt2                               |1200.809s |6818.0MiB|
|non-incremental/QF_LIA/20231117-c_inference/80_80_71_17_unsat.smt2                         |1200.579s |2731.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               |1200.570s |4816.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                |1200.526s |4663.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-50.smt2                         |1200.458s |3752.0MiB|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-49.smt2                       |1200.291s |2868.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-357303.smt2                                |1200.194s |1010.0MiB|
|non-incremental/QF_LIA/RWS/Example_15.txt.smt2                                             |1200.071s |368.0MiB|
|non-incremental/QF_LIA/RWS/Example_7.txt.smt2                                              |1200.063s |308.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-50.smt2                          |1144.778s |1988.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-50.smt2                         |1011.520s |1667.0MiB|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-47.smt2                       |1009.537s |2685.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-49.smt2                         |1000.174s |2980.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-49.smt2                         | 932.317s |1655.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-49.smt2                         | 858.690s |3251.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1138192.smt2                             | 819.834s |5058.0MiB|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-46.smt2                       | 817.383s |2656.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-48.smt2                         | 812.748s |2552.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-48.smt2                         | 803.755s |3588.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-50.smt2                          | 794.712s |2016.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-1228327.smt2                               |1200.809s |6818.0MiB|
|non-incremental/QF_LIA/20231117-c_inference/80_80_71_17_unsat.smt2                         |1200.579s |2731.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               |1200.570s |4816.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                |1200.526s |4663.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-50.smt2                         |1200.458s |3752.0MiB|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-49.smt2                       |1200.291s |2868.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-357303.smt2                                |1200.194s |1010.0MiB|
|non-incremental/QF_LIA/RWS/Example_15.txt.smt2                                             |1200.071s |368.0MiB|
|non-incremental/QF_LIA/RWS/Example_7.txt.smt2                                              |1200.063s |308.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-50.smt2                          |1144.778s |1988.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-50.smt2                         |1011.520s |1667.0MiB|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-47.smt2                       |1009.537s |2685.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-49.smt2                         |1000.174s |2980.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-49.smt2                         | 932.317s |1655.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-49.smt2                         | 858.690s |3251.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1138192.smt2                             | 819.834s |5058.0MiB|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-46.smt2                       | 817.383s |2656.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-48.smt2                         | 812.748s |2552.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-48.smt2                         | 803.755s |3588.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-50.smt2                          | 794.712s |2016.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |888.0MiB|888.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |1353.0MiB|1353.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |1354.0MiB|1354.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |1349.0MiB|1349.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |628.0MiB|628.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |1346.0MiB|1346.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |1359.0MiB|1359.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |1397.0MiB|1397.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |1396.0MiB|1396.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |2578.0MiB|2578.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |1352.0MiB|1352.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |1373.0MiB|1373.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |1360.0MiB|1360.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |1366.0MiB|1366.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |1361.0MiB|1361.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |1391.0MiB|1391.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |1176.0MiB|1176.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |1346.0MiB|1346.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |1355.0MiB|1355.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |1349.0MiB|1349.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |888.0MiB|888.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |1353.0MiB|1353.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |1354.0MiB|1354.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |1349.0MiB|1349.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |628.0MiB|628.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |1346.0MiB|1346.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |1359.0MiB|1359.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |1397.0MiB|1397.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |1396.0MiB|1396.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |2578.0MiB|2578.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |1352.0MiB|1352.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |1373.0MiB|1373.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |1360.0MiB|1360.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |1366.0MiB|1366.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |1361.0MiB|1361.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |1391.0MiB|1391.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |1176.0MiB|1176.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |1346.0MiB|1346.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |1355.0MiB|1355.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |1349.0MiB|1349.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |888.0MiB|888.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |1353.0MiB|1353.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |1354.0MiB|1354.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |1349.0MiB|1349.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |628.0MiB|628.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |1346.0MiB|1346.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |1359.0MiB|1359.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |1397.0MiB|1397.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |1396.0MiB|1396.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |2578.0MiB|2578.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |1352.0MiB|1352.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |1373.0MiB|1373.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |1360.0MiB|1360.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |1366.0MiB|1366.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |1361.0MiB|1361.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |1391.0MiB|1391.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |1176.0MiB|1176.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |1346.0MiB|1346.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |1355.0MiB|1355.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |1349.0MiB|1349.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |888.0MiB|888.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |1353.0MiB|1353.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |1354.0MiB|1354.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |1349.0MiB|1349.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |628.0MiB|628.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |1346.0MiB|1346.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |1359.0MiB|1359.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |1397.0MiB|1397.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |1396.0MiB|1396.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |2578.0MiB|2578.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |1352.0MiB|1352.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |1373.0MiB|1373.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |1360.0MiB|1360.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |1366.0MiB|1366.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |1361.0MiB|1361.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |1391.0MiB|1391.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |1176.0MiB|1176.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |1346.0MiB|1346.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |1355.0MiB|1355.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |1349.0MiB|1349.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-07.smt2                      |   9.049s |9048.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-12.smt2                      |   8.555s |8569.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1228327.smt2                               |1200.809s |6818.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-04.smt2                      |   8.772s |6287.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1472027.smt2                               | 264.617s |6284.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1400961.smt2                               | 279.729s |5876.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-09.smt2                      |  14.734s |5284.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1452366.smt2                             | 224.593s |5089.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1138192.smt2                             | 819.834s |5058.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               |1200.570s |4816.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                |1200.526s |4663.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1262176.smt2                             | 184.455s |4591.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-49.smt2                         | 631.440s |4584.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-02.smt2                      |   6.494s |4441.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-00.smt2                      |   7.005s |4330.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-06.smt2                      |   6.620s |4329.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-13.smt2                      |   6.510s |4329.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-11.smt2                      |   6.992s |4328.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-05.smt2                      |   6.725s |4328.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-15.smt2                      |   6.657s |4328.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-07.smt2                      |   9.049s |9048.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-12.smt2                      |   8.555s |8569.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1228327.smt2                               |1200.809s |6818.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-04.smt2                      |   8.772s |6287.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1472027.smt2                               | 264.617s |6284.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1400961.smt2                               | 279.729s |5876.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-09.smt2                      |  14.734s |5284.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1452366.smt2                             | 224.593s |5089.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1138192.smt2                             | 819.834s |5058.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               |1200.570s |4816.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                |1200.526s |4663.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1262176.smt2                             | 184.455s |4591.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-49.smt2                         | 631.440s |4584.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-02.smt2                      |   6.494s |4441.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-00.smt2                      |   7.005s |4330.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-06.smt2                      |   6.620s |4329.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-13.smt2                      |   6.510s |4329.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-11.smt2                      |   6.992s |4328.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-05.smt2                      |   6.725s |4328.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-15.smt2                      |   6.657s |4328.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   2.286s  |   2.286s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   3.215s  |   3.215s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   3.767s  |   3.767s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   3.079s  |   3.079s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   2.116s  |   2.116s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   3.212s  |   3.212s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   3.775s  |   3.775s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   2.442s  |   2.442s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   3.727s  |   3.727s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   3.180s  |   3.180s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |   3.275s  |   3.275s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |   3.115s  |   3.115s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |   3.644s  |   3.644s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |   3.290s  |   3.290s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |   2.458s  |   2.458s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |   2.372s  |   2.372s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |   3.571s  |   3.571s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |   3.160s  |   3.160s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |   3.115s  |   3.115s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-15.smt2                       |   2.510s  |   2.510s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-00.smt2                       |   4.654s  |   4.654s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-01.smt2                       |   4.419s  |   4.419s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-02.smt2                       |   7.526s  |   7.526s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-03.smt2                       |   6.467s  |   6.467s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-04.smt2                       |   5.968s  |   5.968s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-05.smt2                       |   4.725s  |   4.725s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-06.smt2                       |   4.396s  |   4.396s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-07.smt2                       |   4.559s  |   4.559s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-08.smt2                       |   4.562s  |   4.562s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-09.smt2                       |   7.034s  |   7.034s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-10.smt2                       |   4.551s  |   4.551s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-11.smt2                       |   4.614s  |   4.614s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-12.smt2                       |   4.467s  |   4.467s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-13.smt2                       |   7.045s  |   7.045s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-14.smt2                       |   4.635s  |   4.635s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-00.smt2                       |   7.005s  |   7.005s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-01.smt2                       |   6.628s  |   6.628s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-02.smt2                       |   6.494s  |   6.494s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-03.smt2                       |   4.983s  |   4.983s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-04.smt2                       |   8.772s  |   8.772s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-05.smt2                       |   6.725s  |   6.725s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-06.smt2                       |   6.620s  |   6.620s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-07.smt2                       |   9.049s  |   9.049s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-08.smt2                       |   6.557s  |   6.557s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-09.smt2                       |  14.734s  |  14.734s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-10.smt2                       |   6.585s  |   6.585s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-11.smt2                       |   6.992s  |   6.992s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-12.smt2                       |   8.555s  |   8.555s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-13.smt2                       |   6.510s  |   6.510s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-14.smt2                       |   6.704s  |   6.704s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-15.smt2                       |   6.657s  |   6.657s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r1000w0010/RC-08.smt2                       |   5.232s  |   5.232s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-00.smt2                      |   4.552s  |   4.552s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-02.smt2                      |   4.694s  |   4.694s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-03.smt2                      |   4.241s  |   4.241s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-06.smt2                      |   4.835s  |   4.835s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-07.smt2                      |   4.412s  |   4.412s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-08.smt2                      |   3.043s  |   3.043s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-09.smt2                      |   4.728s  |   4.728s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-10.smt2                      |   4.036s  |   4.036s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-13.smt2                      |   4.672s  |   4.672s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-14.smt2                      |   3.079s  |   3.079s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-15.smt2                      |   3.563s  |   3.563s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-00.smt2                      |   4.774s  |   4.774s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-01.smt2                      |   8.970s  |   8.970s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-05.smt2                      |   4.886s  |   4.886s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-08.smt2                      |   3.044s  |   3.044s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-09.smt2                      |   4.520s  |   4.520s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-10.smt2                      |   4.259s  |   4.259s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-11.smt2                      |   3.678s  |   3.678s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-12.smt2                      |   4.465s  |   4.465s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-13.smt2                      |   4.733s  |   4.733s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-14.smt2                      |   4.945s  |   4.945s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20231117-c_inference/80_80_71_17_unsat.smt2                          |1200.579s  |1200.579s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/RWS/Example_15.txt.smt2                                              |1200.071s  |1200.071s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/RWS/Example_7.txt.smt2                                               |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1007795.smt2                                |   5.146s  |   5.146s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                                |1200.570s  |1200.570s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1121941.smt2                                |  25.770s  |  25.770s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1148089.smt2                                |   8.769s  |   8.769s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1185949.smt2                                |  17.964s  |  17.964s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1205831.smt2                                |  11.052s  |  11.052s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1228327.smt2                                |1200.809s  |1200.809s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1275621.smt2                                |  21.940s  |  21.940s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1317511.smt2                                |  24.780s  |  24.780s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1360077.smt2                                |  19.560s  |  19.560s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1365816.smt2                                |  34.697s  |  34.697s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1400961.smt2                                | 279.729s  | 279.729s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1472027.smt2                                | 264.617s  | 264.617s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-267105.smt2                                 | 134.763s  | 134.763s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-357303.smt2                                 |1200.194s  |1200.194s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-379665.smt2                                 |  11.108s  |  11.108s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-392137.smt2                                 |   7.093s  |   7.093s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-408585.smt2                                 | 112.178s  | 112.178s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-415996.smt2                                 |   9.125s  |   9.125s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-478122.smt2                                 | 142.327s  | 142.327s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-481231.smt2                                 |  17.793s  |  17.793s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-518109.smt2                                 | 152.119s  | 152.119s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-526410.smt2                                 |   2.320s  |   2.320s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-618384.smt2                                 | 147.250s  | 147.250s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-689472.smt2                                 |  16.787s  |  16.787s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-864173.smt2                                 |  14.579s  |  14.579s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-901628.smt2                                 |  13.358s  |  13.358s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-916576.smt2                                 |   6.928s  |   6.928s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-928134.smt2                                 |   7.311s  |   7.311s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-928960.smt2                                 | 400.627s  | 400.627s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                 |1200.526s  |1200.526s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1533.smt2                              |   0.666s  |   0.666s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1550.smt2                              |   0.586s  |   0.586s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1565.smt2                              |   0.768s  |   0.768s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1567.smt2                              |   0.647s  |   0.647s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1575.smt2                              |   0.664s  |   0.664s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1591.smt2                              |   0.785s  |   0.785s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1607.smt2                              |   0.641s  |   0.641s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1617.smt2                              |   0.828s  |   0.828s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER10-13-fair.smt2                                       |  31.196s  |  31.196s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER10-14-fair.smt2                                       |  80.134s  |  80.134s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER11-14-fair.smt2                                       | 129.943s  | 129.943s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER11-15-fair.smt2                                       | 264.052s  | 264.052s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-13-50.smt2                           |  45.389s  |  45.389s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-14-49.smt2                           |  63.907s  |  63.907s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-16-48.smt2                           |  31.703s  |  31.703s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-16-50.smt2                           |  29.216s  |  29.216s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-17-47.smt2                           |  27.712s  |  27.712s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-18-48.smt2                           |  27.457s  |  27.457s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-19-49.smt2                           |  22.907s  |  22.907s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-21-40.smt2                           |  73.911s  |  73.911s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-22-48.smt2                           |  19.442s  |  19.442s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-22-49.smt2                           |  36.330s  |  36.330s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-22-50.smt2                           |  67.843s  |  67.843s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-23-41.smt2                           | 102.049s  | 102.049s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-26-43.smt2                           | 129.803s  | 129.803s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-27-47.smt2                           |  24.406s  |  24.406s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-28-48.smt2                           |  26.433s  |  26.433s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-31-42.smt2                           |  96.042s  |  96.042s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-32-50.smt2                           |  31.489s  |  31.489s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-38.smt2                           |   8.491s  |   8.491s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-41.smt2                           |  21.273s  |  21.273s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-43.smt2                           |  20.826s  |  20.826s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-44.smt2                           | 103.504s  | 103.504s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-46.smt2                           | 162.134s  | 162.134s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-47.smt2                           |  19.099s  |  19.099s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-37.smt2                           |  10.107s  |  10.107s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-38.smt2                           |  14.311s  |  14.311s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-39.smt2                           |  16.729s  |  16.729s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-41.smt2                           |  26.532s  |  26.532s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-43.smt2                           |  28.170s  |  28.170s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-45.smt2                           |  42.681s  |  42.681s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-48.smt2                           |  39.485s  |  39.485s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-49.smt2                           |  37.061s  |  37.061s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-50.smt2                           |  35.986s  |  35.986s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-39.smt2                           |  12.718s  |  12.718s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-42.smt2                           |  17.710s  |  17.710s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-45.smt2                           |  63.351s  |  63.351s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-46.smt2                           |  30.597s  |  30.597s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-47.smt2                           | 277.726s  | 277.726s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-48.smt2                           |  25.154s  |  25.154s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-38.smt2                           |  11.018s  |  11.018s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-39.smt2                           |  18.365s  |  18.365s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-40.smt2                           |  22.925s  |  22.925s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-42.smt2                           |  37.209s  |  37.209s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-43.smt2                           |  35.814s  |  35.814s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-44.smt2                           |  23.186s  |  23.186s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-45.smt2                           |  22.420s  |  22.420s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-46.smt2                           |  32.470s  |  32.470s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-48.smt2                           |  40.949s  |  40.949s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-49.smt2                           |  41.916s  |  41.916s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-50.smt2                           |  55.855s  |  55.855s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-38.smt2                           |  11.439s  |  11.439s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-39.smt2                           |  16.534s  |  16.534s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-40.smt2                           |  22.815s  |  22.815s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-41.smt2                           |  24.962s  |  24.962s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-42.smt2                           |  31.996s  |  31.996s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-43.smt2                           |  35.011s  |  35.011s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-44.smt2                           |  35.725s  |  35.725s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-45.smt2                           |  29.803s  |  29.803s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-46.smt2                           |  45.716s  |  45.716s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-48.smt2                           |  80.187s  |  80.187s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-49.smt2                           |  97.760s  |  97.760s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-50.smt2                           |  72.309s  |  72.309s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-4-45.smt2                            |  38.065s  |  38.065s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-4-50.smt2                            | 118.470s  | 118.470s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-39.smt2                           |  16.242s  |  16.242s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-40.smt2                           |  20.862s  |  20.862s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-41.smt2                           |  26.055s  |  26.055s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-42.smt2                           |  31.298s  |  31.298s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-44.smt2                           |  39.820s  |  39.820s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-45.smt2                           |  28.431s  |  28.431s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-46.smt2                           |  34.792s  |  34.792s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-48.smt2                           |  28.933s  |  28.933s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-50.smt2                           |  43.121s  |  43.121s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-40.smt2                           |  16.565s  |  16.565s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-41.smt2                           |  24.617s  |  24.617s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-42.smt2                           |  31.534s  |  31.534s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-43.smt2                           |  46.484s  |  46.484s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-44.smt2                           |  39.949s  |  39.949s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-45.smt2                           |  33.462s  |  33.462s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-46.smt2                           |  62.531s  |  62.531s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-47.smt2                           |  58.099s  |  58.099s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-48.smt2                           |  75.241s  |  75.241s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-49.smt2                           |  70.126s  |  70.126s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-41.smt2                           |  24.738s  |  24.738s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-42.smt2                           |  31.007s  |  31.007s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-44.smt2                           |  53.184s  |  53.184s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-45.smt2                           |  47.096s  |  47.096s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-49.smt2                           | 103.273s  | 103.273s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-50.smt2                           | 109.735s  | 109.735s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-38.smt2                           |  15.241s  |  15.241s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-43.smt2                           |  35.240s  |  35.240s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-44.smt2                           |  31.436s  |  31.436s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-45.smt2                           |  38.268s  |  38.268s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-46.smt2                           |  50.207s  |  50.207s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-47.smt2                           |  36.916s  |  36.916s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-48.smt2                           |  59.651s  |  59.651s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-50.smt2                           |  62.426s  |  62.426s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-41.smt2                           |  23.435s  |  23.435s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-42.smt2                           |  34.259s  |  34.259s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-43.smt2                           |  33.744s  |  33.744s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-44.smt2                           |  47.733s  |  47.733s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-45.smt2                           |  39.517s  |  39.517s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-46.smt2                           |  76.355s  |  76.355s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-47.smt2                           | 104.268s  | 104.268s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-48.smt2                           |  72.148s  |  72.148s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-49.smt2                           |  70.656s  |  70.656s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-50.smt2                           | 148.768s  | 148.768s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-42.smt2                           |  31.492s  |  31.492s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-44.smt2                           |  42.890s  |  42.890s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-46.smt2                           |  65.688s  |  65.688s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-47.smt2                           |  45.673s  |  45.673s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-49.smt2                           |  70.782s  |  70.782s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-50.smt2                           |  81.579s  |  81.579s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-42.smt2                           |  30.518s  |  30.518s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-45.smt2                           |  37.500s  |  37.500s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-46.smt2                           |  58.508s  |  58.508s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-47.smt2                           |  61.459s  |  61.459s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-50.smt2                           |  62.379s  |  62.379s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-42.smt2                           |  30.808s  |  30.808s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-43.smt2                           |  32.585s  |  32.585s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-44.smt2                           |  36.216s  |  36.216s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-45.smt2                           |  39.194s  |  39.194s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-46.smt2                           |  68.515s  |  68.515s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-42.smt2                           |  21.999s  |  21.999s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-43.smt2                           |  39.542s  |  39.542s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-44.smt2                           |  32.164s  |  32.164s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-45.smt2                           |  31.626s  |  31.626s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-46.smt2                           |  59.014s  |  59.014s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-47.smt2                           |  61.716s  |  61.716s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-48.smt2                           |  87.935s  |  87.935s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-49.smt2                           |  62.843s  |  62.843s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-50.smt2                           |  96.538s  |  96.538s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-41.smt2                           |  27.837s  |  27.837s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-43.smt2                           |  32.687s  |  32.687s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-44.smt2                           |  41.843s  |  41.843s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-45.smt2                           |  34.260s  |  34.260s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-46.smt2                           |  47.585s  |  47.585s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-47.smt2                           |  53.770s  |  53.770s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-48.smt2                           |  93.102s  |  93.102s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-49.smt2                           | 102.765s  | 102.765s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-50.smt2                           | 106.190s  | 106.190s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-5-47.smt2                            |  22.094s  |  22.094s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-5-49.smt2                            |  53.041s  |  53.041s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-42.smt2                           |  33.413s  |  33.413s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-43.smt2                           |  30.985s  |  30.985s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-45.smt2                           |  49.915s  |  49.915s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-46.smt2                           |  48.952s  |  48.952s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-47.smt2                           |  81.303s  |  81.303s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-48.smt2                           |  77.469s  |  77.469s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-50.smt2                           |  87.461s  |  87.461s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-43.smt2                           |  34.674s  |  34.674s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-44.smt2                           |  41.802s  |  41.802s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-45.smt2                           |  41.995s  |  41.995s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-46.smt2                           |  72.337s  |  72.337s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-47.smt2                           |  51.423s  |  51.423s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-48.smt2                           |  58.986s  |  58.986s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-50.smt2                           |  95.475s  |  95.475s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-44.smt2                           |  37.123s  |  37.123s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-45.smt2                           |  39.214s  |  39.214s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-46.smt2                           |  47.989s  |  47.989s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-47.smt2                           |  63.299s  |  63.299s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-48.smt2                           |  67.777s  |  67.777s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-49.smt2                           |  79.113s  |  79.113s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-50.smt2                           |  82.171s  |  82.171s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-45.smt2                           |  37.128s  |  37.128s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-46.smt2                           |  48.849s  |  48.849s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-47.smt2                           |  54.556s  |  54.556s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-48.smt2                           |  51.874s  |  51.874s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-49.smt2                           |  90.743s  |  90.743s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-50.smt2                           |  85.683s  |  85.683s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-46.smt2                           |  41.728s  |  41.728s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-47.smt2                           |  68.635s  |  68.635s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-49.smt2                           |  78.652s  |  78.652s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-50.smt2                           | 103.415s  | 103.415s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-46.smt2                           |  51.727s  |  51.727s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-47.smt2                           |  51.524s  |  51.524s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-48.smt2                           |  56.372s  |  56.372s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-49.smt2                           |  81.343s  |  81.343s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-50.smt2                           |  81.174s  |  81.174s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-46.smt2                           |  48.910s  |  48.910s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-47.smt2                           |  54.469s  |  54.469s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-48.smt2                           |  72.633s  |  72.633s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-49.smt2                           |  73.848s  |  73.848s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-50.smt2                           |  81.893s  |  81.893s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-47.smt2                           |  63.675s  |  63.675s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-48.smt2                           |  50.639s  |  50.639s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-49.smt2                           |  81.129s  |  81.129s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-50.smt2                           |  94.715s  |  94.715s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-47.smt2                           |  59.752s  |  59.752s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-48.smt2                           |  50.546s  |  50.546s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-49.smt2                           |  69.750s  |  69.750s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-50.smt2                           |  66.124s  |  66.124s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-59-48.smt2                           |  56.426s  |  56.426s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-59-49.smt2                           |  63.355s  |  63.355s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-59-50.smt2                           |  66.258s  |  66.258s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-60-48.smt2                           |  61.693s  |  61.693s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-60-49.smt2                           |  80.179s  |  80.179s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-60-50.smt2                           |  74.120s  |  74.120s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-61-49.smt2                           |  74.523s  |  74.523s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-61-50.smt2                           |  87.096s  |  87.096s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-62-49.smt2                           |  80.076s  |  80.076s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-62-50.smt2                           |  89.069s  |  89.069s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-63-50.smt2                           |  78.143s  |  78.143s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-44.smt2                            |  15.610s  |  15.610s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-46.smt2                            |  39.741s  |  39.741s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-50.smt2                            | 164.112s  | 164.112s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-42.smt2                            |   8.536s  |   8.536s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-49.smt2                            |  22.977s  |  22.977s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-50.smt2                            |  37.638s  |  37.638s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-0-196.smt2                               |  27.149s  |  27.149s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-0-197.smt2                               |  41.895s  |  41.895s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-0-198.smt2                               |  43.240s  |  43.240s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-0-199.smt2                               |  48.408s  |  48.408s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-0-200.smt2                               |  39.667s  |  39.667s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-2-196.smt2                               |  27.102s  |  27.102s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-2-198.smt2                               |  24.241s  |  24.241s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-2-199.smt2                               |  23.624s  |  23.624s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-2-200.smt2                               |  31.489s  |  31.489s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-3-196.smt2                               |  18.958s  |  18.958s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-3-197.smt2                               |  19.905s  |  19.905s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-3-198.smt2                               |  16.699s  |  16.699s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-3-199.smt2                               |  15.926s  |  15.926s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-3-200.smt2                               |  27.825s  |  27.825s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-46.smt2                   | 227.310s  | 227.310s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-47.smt2                   | 313.142s  | 313.142s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-48.smt2                   | 344.552s  | 344.552s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-49.smt2                   | 482.944s  | 482.944s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-50.smt2                   | 513.518s  | 513.518s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-46.smt2                   | 198.667s  | 198.667s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-47.smt2                   | 302.009s  | 302.009s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-48.smt2                   | 327.561s  | 327.561s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-49.smt2                   | 519.045s  | 519.045s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-50.smt2                   | 485.967s  | 485.967s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-46.smt2                   | 134.200s  | 134.200s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-47.smt2                   | 144.502s  | 144.502s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-48.smt2                   | 210.348s  | 210.348s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-49.smt2                   | 252.207s  | 252.207s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-50.smt2                   | 244.465s  | 244.465s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-46.smt2                   |  79.550s  |  79.550s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-47.smt2                   |  65.715s  |  65.715s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-48.smt2                   | 108.326s  | 108.326s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-49.smt2                   | 154.080s  | 154.080s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-50.smt2                   | 140.533s  | 140.533s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-47.smt2                    |  28.061s  |  28.061s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-48.smt2                    |  40.411s  |  40.411s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-49.smt2                    |  51.603s  |  51.603s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-50.smt2                    |  71.598s  |  71.598s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-46.smt2                    | 112.765s  | 112.765s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-47.smt2                    | 115.543s  | 115.543s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-48.smt2                    | 177.809s  | 177.809s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-49.smt2                    | 175.491s  | 175.491s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-50.smt2                    | 200.012s  | 200.012s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-46.smt2                    | 112.172s  | 112.172s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-47.smt2                    | 167.423s  | 167.423s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-48.smt2                    | 156.994s  | 156.994s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-49.smt2                    | 209.945s  | 209.945s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-50.smt2                    | 246.497s  | 246.497s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-8-50.smt2                    |  14.254s  |  14.254s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-13-50.smt2                         |  17.283s  |  17.283s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-16-49.smt2                         |  16.202s  |  16.202s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-17-47.smt2                         |  33.156s  |  33.156s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-19-50.smt2                         |  20.629s  |  20.629s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-22-47.smt2                         |  27.931s  |  27.931s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-22-48.smt2                         |  44.314s  |  44.314s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-22-50.smt2                         |  18.768s  |  18.768s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-23-50.smt2                         |  19.537s  |  19.537s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-24-49.smt2                         |  18.839s  |  18.839s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-25-48.smt2                         |  30.275s  |  30.275s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-25-49.smt2                         |  54.189s  |  54.189s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-25-50.smt2                         |  91.525s  |  91.525s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-26-48.smt2                         |  21.010s  |  21.010s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-26-49.smt2                         |  25.285s  |  25.285s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-26-50.smt2                         |  71.147s  |  71.147s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-27-48.smt2                         |  27.092s  |  27.092s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-27-49.smt2                         |  41.306s  |  41.306s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-27-50.smt2                         |  58.943s  |  58.943s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-28-48.smt2                         |  26.256s  |  26.256s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-28-49.smt2                         |  62.128s  |  62.128s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-28-50.smt2                         |  95.460s  |  95.460s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-29-49.smt2                         |  33.298s  |  33.298s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-29-50.smt2                         |  62.871s  |  62.871s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-32-50.smt2                         |  17.559s  |  17.559s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-35-49.smt2                         |  18.637s  |  18.637s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-35-50.smt2                         |  22.774s  |  22.774s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-37-50.smt2                         |  19.730s  |  19.730s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-38-48.smt2                         |  26.273s  |  26.273s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-38-50.smt2                         |  20.961s  |  20.961s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-39-50.smt2                         |  35.043s  |  35.043s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-40-50.smt2                         |  28.181s  |  28.181s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-41-50.smt2                         |  48.830s  |  48.830s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-42-50.smt2                         |  18.855s  |  18.855s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-43-49.smt2                         |  32.221s  |  32.221s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-43-50.smt2                         |  47.978s  |  47.978s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-44-49.smt2                         |  30.271s  |  30.271s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-44-50.smt2                         |  35.086s  |  35.086s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-47-49.smt2                         |  17.760s  |  17.760s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-47-50.smt2                         |  21.572s  |  21.572s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-48-50.smt2                         |  20.505s  |  20.505s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-49-49.smt2                         |  25.670s  |  25.670s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-49-50.smt2                         |  27.765s  |  27.765s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-50-49.smt2                         |  22.797s  |  22.797s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-50-50.smt2                         |  38.220s  |  38.220s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-51-49.smt2                         |  22.664s  |  22.664s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-51-50.smt2                         |  37.540s  |  37.540s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-52-49.smt2                         |  22.996s  |  22.996s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-52-50.smt2                         |  32.671s  |  32.671s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-53-49.smt2                         |  19.910s  |  19.910s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-53-50.smt2                         |  29.604s  |  29.604s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-54-49.smt2                         |  21.940s  |  21.940s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-54-50.smt2                         |  29.588s  |  29.588s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-55-49.smt2                         |  22.000s  |  22.000s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-55-50.smt2                         |  26.361s  |  26.361s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-57-49.smt2                         |  22.697s  |  22.697s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-57-50.smt2                         |  25.917s  |  25.917s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-58-50.smt2                         |  25.166s  |  25.166s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-59-50.smt2                         |  23.903s  |  23.903s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-60-50.smt2                         |  22.285s  |  22.285s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-61-49.smt2                         |  20.714s  |  20.714s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-61-50.smt2                         |  24.392s  |  24.392s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-63-50.smt2                         |  36.049s  |  36.049s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-64-50.smt2                         |  23.792s  |  23.792s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-65-50.smt2                         |  24.697s  |  24.697s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-67-50.smt2                         |  23.312s  |  23.312s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-68-50.smt2                         |  25.874s  |  25.874s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-69-50.smt2                         |  25.148s  |  25.148s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-70-50.smt2                         |  27.593s  |  27.593s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-76-50.smt2                         |  25.307s  |  25.307s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-77-50.smt2                         |  22.905s  |  22.905s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-8-49.smt2                          |  15.238s  |  15.238s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-47.smt2                           |  27.914s  |  27.914s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-48.smt2                           |  33.471s  |  33.471s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-50.smt2                           |  45.102s  |  45.102s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-46.smt2                           |  28.068s  |  28.068s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-47.smt2                           |  49.066s  |  49.066s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-48.smt2                           |  37.703s  |  37.703s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-46.smt2                          | 297.780s  | 297.780s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-47.smt2                          | 260.589s  | 260.589s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-48.smt2                          |  82.094s  |  82.094s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-49.smt2                          | 932.317s  | 932.317s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-50.smt2                          | 549.948s  | 549.948s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-46.smt2                          | 151.018s  | 151.018s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-47.smt2                          | 277.808s  | 277.808s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-48.smt2                          |  79.214s  |  79.214s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-49.smt2                          | 634.924s  | 634.924s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-50.smt2                          | 514.782s  | 514.782s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-48.smt2                          |  33.253s  |  33.253s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-49.smt2                          |  42.917s  |  42.917s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-50.smt2                          |  44.545s  |  44.545s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-46.smt2                          | 133.844s  | 133.844s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-47.smt2                          | 231.757s  | 231.757s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-48.smt2                          |  65.170s  |  65.170s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-49.smt2                          | 268.524s  | 268.524s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-50.smt2                          | 365.432s  | 365.432s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-46.smt2                          |  23.428s  |  23.428s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-48.smt2                          |  36.394s  |  36.394s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-50.smt2                          |  48.212s  |  48.212s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-47.smt2                          |  31.666s  |  31.666s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-48.smt2                          |  33.286s  |  33.286s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-49.smt2                          |  40.749s  |  40.749s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-46.smt2                          | 184.254s  | 184.254s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-47.smt2                          | 229.054s  | 229.054s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-48.smt2                          |  53.499s  |  53.499s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-49.smt2                          | 214.464s  | 214.464s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-46.smt2                          | 236.893s  | 236.893s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-47.smt2                          | 166.629s  | 166.629s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-48.smt2                          |  52.458s  |  52.458s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-49.smt2                          | 370.977s  | 370.977s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-50.smt2                          | 635.010s  | 635.010s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-46.smt2                          |  32.157s  |  32.157s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-47.smt2                          |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-48.smt2                          |  40.106s  |  40.106s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-49.smt2                          |  36.237s  |  36.237s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-50.smt2                          |  74.920s  |  74.920s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-46.smt2                          | 244.843s  | 244.843s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-47.smt2                          | 100.212s  | 100.212s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-48.smt2                          |  49.035s  |  49.035s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-49.smt2                          | 341.595s  | 341.595s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-50.smt2                          | 423.991s  | 423.991s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-46.smt2                           | 199.815s  | 199.815s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-47.smt2                           | 282.064s  | 282.064s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-48.smt2                           |  89.800s  |  89.800s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-49.smt2                           | 605.022s  | 605.022s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-50.smt2                           |1144.778s  |1144.778s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-46.smt2                          |  36.915s  |  36.915s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-49.smt2                          |  38.349s  |  38.349s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-50.smt2                          |  53.511s  |  53.511s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-46.smt2                          |  32.169s  |  32.169s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-48.smt2                          |  39.030s  |  39.030s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-49.smt2                          |  52.587s  |  52.587s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-50.smt2                          |  69.123s  |  69.123s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-46.smt2                          | 294.391s  | 294.391s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-47.smt2                          | 152.364s  | 152.364s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-48.smt2                          |  44.442s  |  44.442s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-49.smt2                          | 149.746s  | 149.746s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-50.smt2                          | 648.890s  | 648.890s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-46.smt2                          | 202.788s  | 202.788s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-47.smt2                          | 156.940s  | 156.940s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-48.smt2                          |  53.787s  |  53.787s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-49.smt2                          | 312.090s  | 312.090s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-50.smt2                          | 663.866s  | 663.866s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-46.smt2                          |  37.767s  |  37.767s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-48.smt2                          |  40.813s  |  40.813s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-49.smt2                          |  50.671s  |  50.671s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-46.smt2                          | 127.537s  | 127.537s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-47.smt2                          | 230.919s  | 230.919s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-48.smt2                          |  55.616s  |  55.616s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-49.smt2                          | 499.435s  | 499.435s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-50.smt2                          | 507.710s  | 507.710s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-47.smt2                          |  54.923s  |  54.923s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-48.smt2                          |  53.379s  |  53.379s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-46.smt2                          |  52.961s  |  52.961s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-48.smt2                          |  58.527s  |  58.527s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-49.smt2                          |  64.472s  |  64.472s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-50.smt2                          |  79.144s  |  79.144s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-46.smt2                          | 296.528s  | 296.528s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-47.smt2                          | 643.614s  | 643.614s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-48.smt2                          | 803.755s  | 803.755s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-49.smt2                          |1000.174s  |1000.174s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-50.smt2                          |1200.458s  |1200.458s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-46.smt2                          | 328.099s  | 328.099s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-47.smt2                          |  58.542s  |  58.542s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-48.smt2                          | 344.930s  | 344.930s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-49.smt2                          | 559.874s  | 559.874s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-50.smt2                          | 774.793s  | 774.793s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-46.smt2                           | 186.296s  | 186.296s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-47.smt2                           | 209.323s  | 209.323s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-48.smt2                           |  64.521s  |  64.521s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-49.smt2                           | 598.884s  | 598.884s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-50.smt2                           | 746.231s  | 746.231s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-46.smt2                          | 363.267s  | 363.267s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-47.smt2                          | 480.195s  | 480.195s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-48.smt2                          | 812.748s  | 812.748s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-49.smt2                          | 858.690s  | 858.690s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-50.smt2                          |1011.520s  |1011.520s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-46.smt2                          |  49.023s  |  49.023s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-47.smt2                          |  58.343s  |  58.343s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-48.smt2                          |  49.569s  |  49.569s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-50.smt2                          |  61.774s  |  61.774s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-46.smt2                          |  47.622s  |  47.622s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-47.smt2                          | 206.294s  | 206.294s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-48.smt2                          |  47.766s  |  47.766s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-49.smt2                          | 387.219s  | 387.219s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-50.smt2                          | 551.065s  | 551.065s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-46.smt2                          | 194.447s  | 194.447s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-47.smt2                          | 230.316s  | 230.316s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-48.smt2                          | 297.485s  | 297.485s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-49.smt2                          | 512.807s  | 512.807s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-50.smt2                          | 738.843s  | 738.843s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-47.smt2                          | 228.625s  | 228.625s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-48.smt2                          | 283.019s  | 283.019s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-49.smt2                          |  87.525s  |  87.525s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-50.smt2                          | 608.113s  | 608.113s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-46.smt2                          |  62.344s  |  62.344s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-48.smt2                          |  94.666s  |  94.666s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-49.smt2                          | 112.631s  | 112.631s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-50.smt2                          |  95.661s  |  95.661s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-46.smt2                          |  65.377s  |  65.377s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-47.smt2                          |  66.886s  |  66.886s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-48.smt2                          |  91.930s  |  91.930s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-47.smt2                          |  14.693s  |  14.693s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-48.smt2                          | 349.669s  | 349.669s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-49.smt2                          | 631.440s  | 631.440s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-50.smt2                          | 709.411s  | 709.411s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-46.smt2                          | 125.369s  | 125.369s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-47.smt2                          | 114.736s  | 114.736s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-48.smt2                          |  55.712s  |  55.712s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-49.smt2                          | 408.746s  | 408.746s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-50.smt2                          | 359.928s  | 359.928s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-46.smt2                          | 172.735s  | 172.735s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-47.smt2                          |  82.582s  |  82.582s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-48.smt2                          | 239.262s  | 239.262s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-49.smt2                          | 497.130s  | 497.130s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-47.smt2                           |  36.325s  |  36.325s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-49.smt2                           |  46.017s  |  46.017s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-46.smt2                          | 201.480s  | 201.480s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-47.smt2                          | 232.263s  | 232.263s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-48.smt2                          | 432.914s  | 432.914s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-49.smt2                          | 377.185s  | 377.185s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-50.smt2                          | 622.642s  | 622.642s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-46.smt2                          | 193.928s  | 193.928s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-47.smt2                          | 184.047s  | 184.047s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-48.smt2                          | 455.066s  | 455.066s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-49.smt2                          | 552.248s  | 552.248s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-50.smt2                          | 381.699s  | 381.699s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-47.smt2                          |  14.696s  |  14.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-48.smt2                          |  17.075s  |  17.075s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-49.smt2                          | 332.521s  | 332.521s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-50.smt2                          | 512.097s  | 512.097s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-46.smt2                          |  88.580s  |  88.580s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-47.smt2                          | 217.391s  | 217.391s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-48.smt2                          |  47.789s  |  47.789s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-49.smt2                          | 245.984s  | 245.984s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-50.smt2                          | 381.177s  | 381.177s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-46.smt2                          | 169.505s  | 169.505s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-47.smt2                          | 183.742s  | 183.742s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-48.smt2                          | 146.235s  | 146.235s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-49.smt2                          | 185.002s  | 185.002s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-50.smt2                          | 372.363s  | 372.363s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-46.smt2                          |  80.491s  |  80.491s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-47.smt2                          | 107.360s  | 107.360s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-48.smt2                          |  46.194s  |  46.194s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-49.smt2                          | 224.083s  | 224.083s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-50.smt2                          | 406.138s  | 406.138s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-46.smt2                          | 100.834s  | 100.834s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-47.smt2                          | 158.948s  | 158.948s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-48.smt2                          | 192.276s  | 192.276s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-49.smt2                          | 255.585s  | 255.585s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-50.smt2                          | 415.690s  | 415.690s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-46.smt2                          |  94.621s  |  94.621s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-47.smt2                          | 174.784s  | 174.784s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-48.smt2                          | 156.822s  | 156.822s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-49.smt2                          | 375.776s  | 375.776s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-50.smt2                          | 417.044s  | 417.044s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-46.smt2                          | 123.655s  | 123.655s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-47.smt2                          |  95.284s  |  95.284s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-48.smt2                          | 168.387s  | 168.387s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-49.smt2                          | 164.542s  | 164.542s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-50.smt2                          | 311.351s  | 311.351s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-46.smt2                          | 153.303s  | 153.303s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-47.smt2                          | 121.205s  | 121.205s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-48.smt2                          |  50.210s  |  50.210s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-49.smt2                          | 225.295s  | 225.295s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-50.smt2                          | 135.246s  | 135.246s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-46.smt2                           |  26.045s  |  26.045s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-47.smt2                           |  30.612s  |  30.612s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-48.smt2                           |  33.767s  |  33.767s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-49.smt2                           |  39.632s  |  39.632s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-50.smt2                           |  42.270s  |  42.270s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-47.smt2                          | 130.873s  | 130.873s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-49.smt2                          | 296.261s  | 296.261s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-47.smt2                          |  81.564s  |  81.564s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-48.smt2                          |  50.984s  |  50.984s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-49.smt2                          | 279.930s  | 279.930s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-50.smt2                          | 144.159s  | 144.159s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-46.smt2                           |  21.921s  |  21.921s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-47.smt2                           |  31.070s  |  31.070s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-48.smt2                           |  34.572s  |  34.572s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-49.smt2                           |  38.356s  |  38.356s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-50.smt2                           |  43.789s  |  43.789s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-46.smt2                           |  24.153s  |  24.153s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-47.smt2                           |  27.689s  |  27.689s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-48.smt2                           |  37.306s  |  37.306s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-49.smt2                           |  39.304s  |  39.304s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-50.smt2                           |  45.750s  |  45.750s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-46.smt2                           | 205.895s  | 205.895s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-47.smt2                           | 209.764s  | 209.764s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-48.smt2                           |  68.058s  |  68.058s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-49.smt2                           | 320.658s  | 320.658s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-50.smt2                           | 557.853s  | 557.853s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-46.smt2                           | 195.043s  | 195.043s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-47.smt2                           | 388.400s  | 388.400s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-48.smt2                           |  74.110s  |  74.110s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-49.smt2                           | 348.775s  | 348.775s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-50.smt2                           | 794.712s  | 794.712s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/int_from_list/prp-0-48.smt2                            |  44.607s  |  44.607s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/int_from_list/prp-0-49.smt2                            |  35.241s  |  35.241s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/int_from_list/prp-0-50.smt2                            |  59.807s  |  59.807s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/int_from_list/prp-1-48.smt2                            |  38.255s  |  38.255s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/int_from_list/prp-1-49.smt2                            |  41.374s  |  41.374s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/int_from_list/prp-1-50.smt2                            |  46.509s  |  46.509s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/int_from_list/prp-37-47.smt2                           |  28.281s  |  28.281s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-46.smt2                         | 131.887s  | 131.887s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-48.smt2                         |  48.166s  |  48.166s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-49.smt2                         |  47.589s  |  47.589s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-46.smt2                         | 130.666s  | 130.666s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-48.smt2                         | 163.893s  | 163.893s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-50.smt2                         | 291.037s  | 291.037s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-46.smt2                        | 817.383s  | 817.383s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-47.smt2                        |1009.537s  |1009.537s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-49.smt2                        |1200.291s  |1200.291s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-50.smt2                        | 388.899s  | 388.899s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-47.smt2                        | 185.925s  | 185.925s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-49.smt2                        | 274.107s  | 274.107s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-47.smt2                        | 175.810s  | 175.810s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-49.smt2                        | 237.007s  | 237.007s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-50.smt2                        | 242.568s  | 242.568s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-46.smt2                        | 159.754s  | 159.754s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-47.smt2                        | 157.607s  | 157.607s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-48.smt2                        | 244.309s  | 244.309s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-49.smt2                        | 209.920s  | 209.920s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-50.smt2                        | 461.107s  | 461.107s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-46.smt2                        | 197.899s  | 197.899s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-47.smt2                        | 216.302s  | 216.302s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-48.smt2                        |  52.871s  |  52.871s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-49.smt2                        | 402.459s  | 402.459s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-50.smt2                        |  77.217s  |  77.217s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-46.smt2                        | 198.490s  | 198.490s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-48.smt2                        | 235.594s  | 235.594s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-49.smt2                        | 322.671s  | 322.671s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-50.smt2                        | 365.748s  | 365.748s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-46.smt2                        |  54.085s  |  54.085s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-47.smt2                        |  60.698s  |  60.698s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-48.smt2                        | 142.407s  | 142.407s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-49.smt2                        | 260.475s  | 260.475s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-47.smt2                        |  26.654s  |  26.654s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-48.smt2                        |  45.541s  |  45.541s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-49.smt2                        |  85.281s  |  85.281s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-48.smt2                        | 141.173s  | 141.173s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-49.smt2                        |  96.159s  |  96.159s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-50.smt2                        | 131.755s  | 131.755s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-48.smt2                        |  68.136s  |  68.136s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-49.smt2                        | 203.749s  | 203.749s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-50.smt2                        | 221.967s  | 221.967s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-47.smt2                         | 270.180s  | 270.180s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-46.smt2                        |  64.827s  |  64.827s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-47.smt2                        |  73.746s  |  73.746s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-50.smt2                        | 187.988s  | 187.988s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-47.smt2                        | 113.103s  | 113.103s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-48.smt2                        |  95.132s  |  95.132s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-49.smt2                        | 181.335s  | 181.335s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-50.smt2                        | 203.481s  | 203.481s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-46.smt2                        |  59.464s  |  59.464s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-48.smt2                        |  81.457s  |  81.457s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-50.smt2                        | 139.390s  | 139.390s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-46.smt2                        |  24.949s  |  24.949s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-48.smt2                        |  87.250s  |  87.250s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-49.smt2                        |  65.147s  |  65.147s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-50.smt2                        |  81.736s  |  81.736s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-46.smt2                        |  39.446s  |  39.446s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-47.smt2                        |  84.689s  |  84.689s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-48.smt2                        | 127.483s  | 127.483s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-50.smt2                        | 173.943s  | 173.943s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-47.smt2                         | 181.959s  | 181.959s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-48.smt2                         | 110.376s  | 110.376s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-49.smt2                         | 407.401s  | 407.401s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-50.smt2                         | 205.914s  | 205.914s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-46.smt2                         |  88.719s  |  88.719s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-47.smt2                         | 328.923s  | 328.923s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-48.smt2                         | 144.928s  | 144.928s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-49.smt2                         | 406.015s  | 406.015s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-50.smt2                         | 458.868s  | 458.868s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-46.smt2                         | 298.515s  | 298.515s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-47.smt2                         | 193.085s  | 193.085s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-48.smt2                         | 205.797s  | 205.797s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-49.smt2                         | 185.363s  | 185.363s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-50.smt2                         | 319.976s  | 319.976s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-46.smt2                         | 228.393s  | 228.393s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-47.smt2                         | 392.224s  | 392.224s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-48.smt2                         | 246.323s  | 246.323s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-49.smt2                         | 266.456s  | 266.456s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-50.smt2                         | 176.066s  | 176.066s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-47.smt2                         | 275.792s  | 275.792s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-48.smt2                         | 373.308s  | 373.308s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-49.smt2                         | 339.977s  | 339.977s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-48.smt2                         | 233.564s  | 233.564s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-49.smt2                         | 280.920s  | 280.920s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-46.smt2                         | 139.500s  | 139.500s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-48.smt2                         | 183.876s  | 183.876s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-50.smt2                         | 154.222s  | 154.222s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1015084.smt2                              |  12.814s  |  12.814s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1072007.smt2                              |  67.954s  |  67.954s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1138192.smt2                              | 819.834s  | 819.834s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1192684.smt2                              |  19.891s  |  19.891s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1262176.smt2                              | 184.455s  | 184.455s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1265513.smt2                              |  92.906s  |  92.906s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1268455.smt2                              |  62.300s  |  62.300s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1270163.smt2                              |   5.707s  |   5.707s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1317230.smt2                              |  32.550s  |  32.550s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1361831.smt2                              |  22.350s  |  22.350s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1452366.smt2                              | 224.593s  | 224.593s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-247831.smt2                               |  28.388s  |  28.388s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-269353.smt2                               |  56.659s  |  56.659s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-278378.smt2                               | 185.823s  | 185.823s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-283008.smt2                               | 272.954s  | 272.954s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-285271.smt2                               | 283.213s  | 283.213s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-321761.smt2                               | 449.132s  | 449.132s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-329386.smt2                               |   8.809s  |   8.809s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-343499.smt2                               |   4.886s  |   4.886s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-368069.smt2                               | 558.570s  | 558.570s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-413904.smt2                               |   4.585s  |   4.585s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-495717.smt2                               | 353.381s  | 353.381s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-527358.smt2                               |   3.764s  |   3.764s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-658040.smt2                               | 392.832s  | 392.832s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-705295.smt2                               |  10.706s  |  10.706s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-729964.smt2                               | 162.552s  | 162.552s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-758897.smt2                               |  12.950s  |  12.950s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-762853.smt2                               | 183.309s  | 183.309s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-794687.smt2                               |  16.367s  |  16.367s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-906586.smt2                               |  30.995s  |  30.995s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-916807.smt2                               |   8.959s  |   8.959s  |   0.000s  | 0.0%|
</details>
