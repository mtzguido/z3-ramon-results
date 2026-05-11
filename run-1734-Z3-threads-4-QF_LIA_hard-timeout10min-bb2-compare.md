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
Z3 options: "-T:600 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
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
Z3 options: "-T:600 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_LIA.tar.zst?download=1
Z3 commit message: add ablate_backtracking experiment

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   2.186s  |   2.186s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   3.139s  |   3.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   3.927s  |   3.927s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   3.114s  |   3.114s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   2.089s  |   2.089s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   3.135s  |   3.135s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   3.735s  |   3.735s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   2.621s  |   2.621s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   2.485s  |   2.485s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   3.806s  |   3.806s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   3.116s  |   3.116s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |   3.060s  |   3.060s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |   3.178s  |   3.178s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |   3.611s  |   3.611s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |   3.140s  |   3.140s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |   2.557s  |   2.557s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |   2.666s  |   2.666s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |   3.538s  |   3.538s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |   3.400s  |   3.400s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |   3.140s  |   3.140s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   2.186s  |   2.186s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   3.139s  |   3.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   3.927s  |   3.927s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   3.114s  |   3.114s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   2.089s  |   2.089s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   3.135s  |   3.135s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   3.735s  |   3.735s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   2.621s  |   2.621s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   2.485s  |   2.485s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   3.806s  |   3.806s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   3.116s  |   3.116s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |   3.060s  |   3.060s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |   3.178s  |   3.178s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |   3.611s  |   3.611s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |   3.140s  |   3.140s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |   2.557s  |   2.557s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |   2.666s  |   2.666s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |   3.538s  |   3.538s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |   3.400s  |   3.400s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |   3.140s  |   3.140s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   2.186s  |   2.186s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   3.139s  |   3.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   3.927s  |   3.927s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   3.114s  |   3.114s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   2.089s  |   2.089s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   3.135s  |   3.135s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   3.735s  |   3.735s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   2.621s  |   2.621s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   2.485s  |   2.485s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   3.806s  |   3.806s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   3.116s  |   3.116s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |   3.060s  |   3.060s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |   3.178s  |   3.178s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |   3.611s  |   3.611s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |   3.140s  |   3.140s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |   2.557s  |   2.557s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |   2.666s  |   2.666s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |   3.538s  |   3.538s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |   3.400s  |   3.400s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |   3.140s  |   3.140s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   2.186s  |   2.186s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   3.139s  |   3.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   3.927s  |   3.927s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   3.114s  |   3.114s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   2.089s  |   2.089s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   3.135s  |   3.135s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   3.735s  |   3.735s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   2.621s  |   2.621s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   2.485s  |   2.485s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   3.806s  |   3.806s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   3.116s  |   3.116s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |   3.060s  |   3.060s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |   3.178s  |   3.178s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |   3.611s  |   3.611s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |   3.140s  |   3.140s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |   2.557s  |   2.557s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |   2.666s  |   2.666s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |   3.538s  |   3.538s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |   3.400s  |   3.400s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |   3.140s  |   3.140s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-1472027.smt2                               | 600.900s |7819.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1400961.smt2                               | 600.874s |7099.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               | 600.753s |4612.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1228327.smt2                               | 600.717s |6077.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-50.smt2                         | 600.520s |3683.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                | 600.492s |4425.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-48.smt2                         | 600.445s |4167.0MiB|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-47.smt2                       | 600.397s |2678.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-50.smt2                         | 600.384s |2723.0MiB|
|non-incremental/QF_LIA/20231117-c_inference/80_80_71_17_unsat.smt2                         | 600.364s |2127.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-50.smt2                         | 600.344s |2844.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-49.smt2                         | 600.333s |3144.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-49.smt2                         | 600.324s |3062.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-50.smt2                          | 600.317s |2609.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-50.smt2                         | 600.296s |2362.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-49.smt2                         | 600.291s |2265.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-50.smt2                         | 600.290s |2587.0MiB|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-46.smt2                       | 600.264s |2149.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-49.smt2                         | 600.263s |2743.0MiB|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-50.smt2                       | 600.263s |2217.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-1472027.smt2                               | 600.900s |7819.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1400961.smt2                               | 600.874s |7099.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               | 600.753s |4612.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1228327.smt2                               | 600.717s |6077.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-50.smt2                         | 600.520s |3683.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                | 600.492s |4425.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-48.smt2                         | 600.445s |4167.0MiB|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-47.smt2                       | 600.397s |2678.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-50.smt2                         | 600.384s |2723.0MiB|
|non-incremental/QF_LIA/20231117-c_inference/80_80_71_17_unsat.smt2                         | 600.364s |2127.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-50.smt2                         | 600.344s |2844.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-49.smt2                         | 600.333s |3144.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-49.smt2                         | 600.324s |3062.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-50.smt2                          | 600.317s |2609.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-50.smt2                         | 600.296s |2362.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-49.smt2                         | 600.291s |2265.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-50.smt2                         | 600.290s |2587.0MiB|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-46.smt2                       | 600.264s |2149.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-49.smt2                         | 600.263s |2743.0MiB|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-50.smt2                       | 600.263s |2217.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |901.0MiB|901.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |1356.0MiB|1356.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |1353.0MiB|1353.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |1359.0MiB|1359.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |620.0MiB|620.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |1347.0MiB|1347.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |1346.0MiB|1346.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |1399.0MiB|1399.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |1406.0MiB|1406.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |2579.0MiB|2579.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |1362.0MiB|1362.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |1361.0MiB|1361.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |1350.0MiB|1350.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |1365.0MiB|1365.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |1368.0MiB|1368.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |1393.0MiB|1393.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |1175.0MiB|1175.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |1350.0MiB|1350.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |1348.0MiB|1348.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |1357.0MiB|1357.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |901.0MiB|901.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |1356.0MiB|1356.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |1353.0MiB|1353.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |1359.0MiB|1359.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |620.0MiB|620.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |1347.0MiB|1347.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |1346.0MiB|1346.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |1399.0MiB|1399.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |1406.0MiB|1406.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |2579.0MiB|2579.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |1362.0MiB|1362.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |1361.0MiB|1361.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |1350.0MiB|1350.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |1365.0MiB|1365.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |1368.0MiB|1368.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |1393.0MiB|1393.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |1175.0MiB|1175.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |1350.0MiB|1350.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |1348.0MiB|1348.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |1357.0MiB|1357.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |901.0MiB|901.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |1356.0MiB|1356.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |1353.0MiB|1353.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |1359.0MiB|1359.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |620.0MiB|620.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |1347.0MiB|1347.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |1346.0MiB|1346.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |1399.0MiB|1399.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |1406.0MiB|1406.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |2579.0MiB|2579.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |1362.0MiB|1362.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |1361.0MiB|1361.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |1350.0MiB|1350.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |1365.0MiB|1365.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |1368.0MiB|1368.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |1393.0MiB|1393.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |1175.0MiB|1175.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |1350.0MiB|1350.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |1348.0MiB|1348.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |1357.0MiB|1357.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |901.0MiB|901.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |1356.0MiB|1356.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |1353.0MiB|1353.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |1359.0MiB|1359.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |620.0MiB|620.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |1347.0MiB|1347.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |1346.0MiB|1346.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |1399.0MiB|1399.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |1406.0MiB|1406.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |2579.0MiB|2579.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |1362.0MiB|1362.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |1361.0MiB|1361.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |1350.0MiB|1350.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |1365.0MiB|1365.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |1368.0MiB|1368.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |1393.0MiB|1393.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |1175.0MiB|1175.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |1350.0MiB|1350.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |1348.0MiB|1348.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |1357.0MiB|1357.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-07.smt2                      |   9.513s |9039.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-12.smt2                      |   9.442s |8574.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1472027.smt2                               | 600.900s |7819.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1400961.smt2                               | 600.874s |7099.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-04.smt2                      |   9.057s |6116.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1228327.smt2                               | 600.717s |6077.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1452366.smt2                             | 238.354s |5147.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               | 600.753s |4612.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1262176.smt2                             | 187.192s |4606.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                | 600.492s |4425.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-02.smt2                      |   6.594s |4424.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-09.smt2                      |   6.998s |4332.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-00.smt2                      |   7.155s |4329.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-13.smt2                      |   7.025s |4329.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-06.smt2                      |   7.166s |4328.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-05.smt2                      |   6.837s |4328.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-01.smt2                      |   7.334s |4326.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-15.smt2                      |   6.688s |4326.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-10.smt2                      |   6.553s |4325.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-11.smt2                      |   6.545s |4325.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-07.smt2                      |   9.513s |9039.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-12.smt2                      |   9.442s |8574.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1472027.smt2                               | 600.900s |7819.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1400961.smt2                               | 600.874s |7099.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-04.smt2                      |   9.057s |6116.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1228327.smt2                               | 600.717s |6077.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1452366.smt2                             | 238.354s |5147.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                               | 600.753s |4612.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-1262176.smt2                             | 187.192s |4606.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                | 600.492s |4425.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-02.smt2                      |   6.594s |4424.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-09.smt2                      |   6.998s |4332.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-00.smt2                      |   7.155s |4329.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-13.smt2                      |   7.025s |4329.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-06.smt2                      |   7.166s |4328.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-05.smt2                      |   6.837s |4328.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-01.smt2                      |   7.334s |4326.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-15.smt2                      |   6.688s |4326.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-10.smt2                      |   6.553s |4325.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-11.smt2                      |   6.545s |4325.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   2.186s  |   2.186s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   3.139s  |   3.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   3.927s  |   3.927s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   3.114s  |   3.114s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   2.089s  |   2.089s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   3.135s  |   3.135s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   3.735s  |   3.735s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   2.621s  |   2.621s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   2.485s  |   2.485s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   3.806s  |   3.806s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   3.116s  |   3.116s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |   3.060s  |   3.060s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |   3.178s  |   3.178s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |   3.611s  |   3.611s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |   3.140s  |   3.140s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |   2.557s  |   2.557s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |   2.666s  |   2.666s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |   3.538s  |   3.538s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |   3.400s  |   3.400s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |   3.140s  |   3.140s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-15.smt2                       |   2.520s  |   2.520s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-00.smt2                       |   4.429s  |   4.429s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-01.smt2                       |   4.558s  |   4.558s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-02.smt2                       |   7.390s  |   7.390s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-03.smt2                       |   6.678s  |   6.678s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-04.smt2                       |   5.913s  |   5.913s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-05.smt2                       |   4.638s  |   4.638s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-06.smt2                       |   4.554s  |   4.554s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-07.smt2                       |   4.916s  |   4.916s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-08.smt2                       |   4.396s  |   4.396s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-09.smt2                       |   7.225s  |   7.225s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-10.smt2                       |   4.517s  |   4.517s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-11.smt2                       |   4.511s  |   4.511s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-12.smt2                       |   4.369s  |   4.369s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-13.smt2                       |   7.150s  |   7.150s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RC-14.smt2                       |   4.930s  |   4.930s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-00.smt2                       |   7.155s  |   7.155s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-01.smt2                       |   7.334s  |   7.334s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-02.smt2                       |   6.594s  |   6.594s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-03.smt2                       |   4.774s  |   4.774s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-04.smt2                       |   9.057s  |   9.057s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-05.smt2                       |   6.837s  |   6.837s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-06.smt2                       |   7.166s  |   7.166s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-07.smt2                       |   9.513s  |   9.513s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-08.smt2                       |   6.447s  |   6.447s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-09.smt2                       |   6.998s  |   6.998s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-10.smt2                       |   6.553s  |   6.553s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-11.smt2                       |   6.545s  |   6.545s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-12.smt2                       |   9.442s  |   9.442s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-13.smt2                       |   7.025s  |   7.025s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-14.smt2                       |   6.357s  |   6.357s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w1000/RF-15.smt2                       |   6.688s  |   6.688s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r1000w0010/RC-08.smt2                       |   5.152s  |   5.152s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-00.smt2                      |   4.475s  |   4.475s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-02.smt2                      |   4.896s  |   4.896s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-03.smt2                      |   4.191s  |   4.191s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-06.smt2                      |   4.662s  |   4.662s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-07.smt2                      |   4.095s  |   4.095s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-08.smt2                      |   3.119s  |   3.119s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-09.smt2                      |   4.479s  |   4.479s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-10.smt2                      |   3.741s  |   3.741s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-13.smt2                      |   4.986s  |   4.986s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-14.smt2                      |   3.179s  |   3.179s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RC-15.smt2                      |   3.722s  |   3.722s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-00.smt2                      |   4.709s  |   4.709s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-01.smt2                      |   9.064s  |   9.064s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-05.smt2                      |   4.765s  |   4.765s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-08.smt2                      |   3.169s  |   3.169s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-09.smt2                      |   4.429s  |   4.429s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-10.smt2                      |   4.485s  |   4.485s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-11.smt2                      |   4.021s  |   4.021s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-12.smt2                      |   4.084s  |   4.084s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-13.smt2                      |   4.852s  |   4.852s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/SharedMemory-PT-000050/RF-14.smt2                      |   5.028s  |   5.028s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20231117-c_inference/80_80_71_17_unsat.smt2                          | 600.364s  | 600.364s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/RWS/Example_15.txt.smt2                                              | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/RWS/Example_7.txt.smt2                                               | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1007795.smt2                                |   5.558s  |   5.558s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1060546.smt2                                | 600.753s  | 600.753s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1121941.smt2                                |  25.638s  |  25.638s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1148089.smt2                                |   9.192s  |   9.192s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1185949.smt2                                |  19.121s  |  19.121s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1205831.smt2                                |  11.935s  |  11.935s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1228327.smt2                                | 600.717s  | 600.717s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1275621.smt2                                |  22.540s  |  22.540s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1317511.smt2                                |  23.613s  |  23.613s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1360077.smt2                                |  20.207s  |  20.207s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1365816.smt2                                |  34.209s  |  34.209s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1400961.smt2                                | 600.874s  | 600.874s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1472027.smt2                                | 600.900s  | 600.900s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-267105.smt2                                 |  94.074s  |  94.074s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-357303.smt2                                 | 245.620s  | 245.620s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-379665.smt2                                 |  11.178s  |  11.178s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-392137.smt2                                 |   6.651s  |   6.651s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-408585.smt2                                 |  76.258s  |  76.258s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-415996.smt2                                 |   8.479s  |   8.479s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-478122.smt2                                 | 147.370s  | 147.370s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-481231.smt2                                 |  17.350s  |  17.350s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-518109.smt2                                 | 141.870s  | 141.870s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-526410.smt2                                 |   2.193s  |   2.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-618384.smt2                                 | 135.661s  | 135.661s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-689472.smt2                                 |  17.063s  |  17.063s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-864173.smt2                                 |  15.559s  |  15.559s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-901628.smt2                                 |  13.063s  |  13.063s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-916576.smt2                                 |   7.085s  |   7.085s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-928134.smt2                                 |   7.425s  |   7.425s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-928960.smt2                                 | 402.162s  | 402.162s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-985518.smt2                                 | 600.492s  | 600.492s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1533.smt2                              |   0.679s  |   0.679s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1550.smt2                              |   0.566s  |   0.566s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1565.smt2                              |   0.790s  |   0.790s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1567.smt2                              |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1575.smt2                              |   0.689s  |   0.689s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1591.smt2                              |   0.776s  |   0.776s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1607.smt2                              |   0.664s  |   0.664s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/convert/convert-jpg2gif-query-1617.smt2                              |   0.876s  |   0.876s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER10-13-fair.smt2                                       |  26.287s  |  26.287s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER10-14-fair.smt2                                       |  90.615s  |  90.615s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER11-14-fair.smt2                                       |  87.849s  |  87.849s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER11-15-fair.smt2                                       | 373.823s  | 373.823s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-13-50.smt2                           |  48.005s  |  48.005s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-14-49.smt2                           |  41.430s  |  41.430s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-16-48.smt2                           |  23.224s  |  23.224s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-16-50.smt2                           |  32.609s  |  32.609s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-17-47.smt2                           |  41.311s  |  41.311s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-18-48.smt2                           |  57.436s  |  57.436s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-19-49.smt2                           |  33.445s  |  33.445s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-21-40.smt2                           |  54.885s  |  54.885s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-22-48.smt2                           |  23.449s  |  23.449s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-22-49.smt2                           |  15.708s  |  15.708s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-22-50.smt2                           |  36.065s  |  36.065s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-23-41.smt2                           | 102.802s  | 102.802s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-26-43.smt2                           | 130.688s  | 130.688s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-27-47.smt2                           |  29.036s  |  29.036s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-28-48.smt2                           |  26.080s  |  26.080s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-31-42.smt2                           |  85.507s  |  85.507s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-32-50.smt2                           |  59.178s  |  59.178s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-38.smt2                           |   8.851s  |   8.851s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-41.smt2                           |  14.843s  |  14.843s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-43.smt2                           |  14.828s  |  14.828s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-44.smt2                           |  85.370s  |  85.370s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-46.smt2                           | 131.328s  | 131.328s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-35-47.smt2                           |  27.925s  |  27.925s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-37.smt2                           |  10.387s  |  10.387s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-38.smt2                           |  15.559s  |  15.559s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-39.smt2                           |  18.989s  |  18.989s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-41.smt2                           |  24.013s  |  24.013s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-43.smt2                           |  30.364s  |  30.364s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-45.smt2                           |  32.344s  |  32.344s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-48.smt2                           |  36.268s  |  36.268s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-49.smt2                           |  31.370s  |  31.370s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-36-50.smt2                           |  28.318s  |  28.318s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-39.smt2                           |   9.229s  |   9.229s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-42.smt2                           |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-45.smt2                           | 106.613s  | 106.613s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-46.smt2                           |  22.989s  |  22.989s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-47.smt2                           | 206.805s  | 206.805s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-37-48.smt2                           |  21.708s  |  21.708s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-38.smt2                           |   9.538s  |   9.538s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-39.smt2                           |  14.832s  |  14.832s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-40.smt2                           |  16.525s  |  16.525s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-42.smt2                           |  33.399s  |  33.399s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-43.smt2                           |  36.570s  |  36.570s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-44.smt2                           |  24.430s  |  24.430s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-45.smt2                           |  17.083s  |  17.083s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-46.smt2                           |  33.350s  |  33.350s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-48.smt2                           |  47.102s  |  47.102s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-49.smt2                           |  43.164s  |  43.164s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-38-50.smt2                           |  53.363s  |  53.363s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-38.smt2                           |  13.778s  |  13.778s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-39.smt2                           |  16.401s  |  16.401s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-40.smt2                           |  20.220s  |  20.220s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-41.smt2                           |  24.426s  |  24.426s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-42.smt2                           |  28.579s  |  28.579s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-43.smt2                           |  41.032s  |  41.032s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-44.smt2                           |  35.129s  |  35.129s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-45.smt2                           |  35.176s  |  35.176s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-46.smt2                           |  58.780s  |  58.780s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-48.smt2                           |  39.819s  |  39.819s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-49.smt2                           |  57.630s  |  57.630s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-39-50.smt2                           |  71.105s  |  71.105s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-4-45.smt2                            |  41.640s  |  41.640s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-4-50.smt2                            | 110.784s  | 110.784s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-39.smt2                           |  16.241s  |  16.241s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-40.smt2                           |  20.415s  |  20.415s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-41.smt2                           |  23.147s  |  23.147s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-42.smt2                           |  31.664s  |  31.664s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-44.smt2                           |  31.151s  |  31.151s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-45.smt2                           |  31.986s  |  31.986s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-46.smt2                           |  43.082s  |  43.082s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-48.smt2                           |  37.124s  |  37.124s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-40-50.smt2                           |  55.285s  |  55.285s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-40.smt2                           |  14.379s  |  14.379s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-41.smt2                           |  25.879s  |  25.879s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-42.smt2                           |  28.046s  |  28.046s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-43.smt2                           |  37.386s  |  37.386s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-44.smt2                           |  30.630s  |  30.630s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-45.smt2                           |  35.248s  |  35.248s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-46.smt2                           |  65.745s  |  65.745s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-47.smt2                           |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-48.smt2                           |  57.288s  |  57.288s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-41-49.smt2                           |  61.320s  |  61.320s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-41.smt2                           |  23.247s  |  23.247s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-42.smt2                           |  30.785s  |  30.785s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-44.smt2                           |  45.193s  |  45.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-45.smt2                           |  39.036s  |  39.036s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-49.smt2                           |  68.425s  |  68.425s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-42-50.smt2                           |  50.942s  |  50.942s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-38.smt2                           |  15.744s  |  15.744s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-43.smt2                           |  36.749s  |  36.749s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-44.smt2                           |  33.746s  |  33.746s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-45.smt2                           |  38.097s  |  38.097s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-46.smt2                           |  41.783s  |  41.783s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-47.smt2                           |  39.392s  |  39.392s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-48.smt2                           |  49.951s  |  49.951s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-43-50.smt2                           |  48.630s  |  48.630s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-41.smt2                           |  24.011s  |  24.011s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-42.smt2                           |  36.944s  |  36.944s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-43.smt2                           |  37.012s  |  37.012s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-44.smt2                           |  51.116s  |  51.116s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-45.smt2                           |  41.984s  |  41.984s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-46.smt2                           |  65.548s  |  65.548s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-47.smt2                           |  84.385s  |  84.385s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-48.smt2                           |  64.173s  |  64.173s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-49.smt2                           | 100.719s  | 100.719s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-44-50.smt2                           | 106.478s  | 106.478s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-42.smt2                           |  36.172s  |  36.172s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-44.smt2                           |  37.159s  |  37.159s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-46.smt2                           |  52.257s  |  52.257s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-47.smt2                           |  34.979s  |  34.979s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-49.smt2                           |  71.042s  |  71.042s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-45-50.smt2                           |  67.496s  |  67.496s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-42.smt2                           |  32.355s  |  32.355s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-45.smt2                           |  33.976s  |  33.976s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-46.smt2                           |  52.289s  |  52.289s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-47.smt2                           |  44.350s  |  44.350s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-46-50.smt2                           |  47.710s  |  47.710s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-42.smt2                           |  28.564s  |  28.564s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-43.smt2                           |  28.212s  |  28.212s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-44.smt2                           |  33.252s  |  33.252s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-45.smt2                           |  42.148s  |  42.148s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-47-46.smt2                           |  80.471s  |  80.471s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-42.smt2                           |  28.548s  |  28.548s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-43.smt2                           |  44.958s  |  44.958s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-44.smt2                           |  34.420s  |  34.420s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-45.smt2                           |  37.241s  |  37.241s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-46.smt2                           |  55.388s  |  55.388s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-47.smt2                           |  59.507s  |  59.507s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-48.smt2                           |  75.657s  |  75.657s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-49.smt2                           |  72.135s  |  72.135s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-48-50.smt2                           |  94.789s  |  94.789s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-41.smt2                           |  26.017s  |  26.017s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-43.smt2                           |  39.683s  |  39.683s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-44.smt2                           |  34.323s  |  34.323s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-45.smt2                           |  34.563s  |  34.563s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-46.smt2                           |  57.512s  |  57.512s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-47.smt2                           |  56.261s  |  56.261s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-48.smt2                           | 108.757s  | 108.757s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-49.smt2                           |  94.245s  |  94.245s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-49-50.smt2                           | 111.971s  | 111.971s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-5-47.smt2                            |  40.083s  |  40.083s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-5-49.smt2                            |  44.236s  |  44.236s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-42.smt2                           |  31.057s  |  31.057s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-43.smt2                           |  34.385s  |  34.385s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-45.smt2                           |  44.458s  |  44.458s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-46.smt2                           |  44.726s  |  44.726s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-47.smt2                           |  73.987s  |  73.987s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-48.smt2                           |  67.063s  |  67.063s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-50-50.smt2                           |  71.940s  |  71.940s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-43.smt2                           |  33.670s  |  33.670s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-44.smt2                           |  40.225s  |  40.225s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-45.smt2                           |  41.818s  |  41.818s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-46.smt2                           |  69.747s  |  69.747s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-47.smt2                           |  49.175s  |  49.175s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-48.smt2                           |  55.707s  |  55.707s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-51-50.smt2                           | 143.333s  | 143.333s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-44.smt2                           |  37.114s  |  37.114s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-45.smt2                           |  44.136s  |  44.136s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-46.smt2                           |  47.945s  |  47.945s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-47.smt2                           |  66.338s  |  66.338s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-48.smt2                           |  55.359s  |  55.359s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-49.smt2                           |  55.537s  |  55.537s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-52-50.smt2                           |  69.195s  |  69.195s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-45.smt2                           |  42.450s  |  42.450s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-46.smt2                           |  45.817s  |  45.817s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-47.smt2                           |  46.021s  |  46.021s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-48.smt2                           |  45.020s  |  45.020s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-49.smt2                           |  77.934s  |  77.934s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-53-50.smt2                           |  85.188s  |  85.188s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-46.smt2                           |  41.310s  |  41.310s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-47.smt2                           |  51.182s  |  51.182s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-49.smt2                           |  77.654s  |  77.654s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-54-50.smt2                           |  88.493s  |  88.493s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-46.smt2                           |  65.398s  |  65.398s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-47.smt2                           |  50.007s  |  50.007s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-48.smt2                           |  52.912s  |  52.912s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-49.smt2                           |  76.980s  |  76.980s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-55-50.smt2                           |  66.640s  |  66.640s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-46.smt2                           |  74.341s  |  74.341s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-47.smt2                           |  49.062s  |  49.062s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-48.smt2                           |  73.584s  |  73.584s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-49.smt2                           |  70.090s  |  70.090s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-56-50.smt2                           |  82.767s  |  82.767s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-47.smt2                           |  75.701s  |  75.701s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-48.smt2                           |  46.692s  |  46.692s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-49.smt2                           |  67.876s  |  67.876s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-57-50.smt2                           |  74.747s  |  74.747s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-47.smt2                           |  58.680s  |  58.680s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-48.smt2                           |  55.091s  |  55.091s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-49.smt2                           |  68.398s  |  68.398s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-58-50.smt2                           |  69.809s  |  69.809s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-59-48.smt2                           |  57.710s  |  57.710s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-59-49.smt2                           |  60.691s  |  60.691s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-59-50.smt2                           |  56.995s  |  56.995s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-60-48.smt2                           |  57.295s  |  57.295s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-60-49.smt2                           |  54.713s  |  54.713s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-60-50.smt2                           |  83.943s  |  83.943s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-61-49.smt2                           |  73.027s  |  73.027s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-61-50.smt2                           |  83.034s  |  83.034s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-62-49.smt2                           | 132.010s  | 132.010s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-62-50.smt2                           |  66.503s  |  66.503s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-63-50.smt2                           |  80.851s  |  80.851s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-44.smt2                            |  18.964s  |  18.964s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-46.smt2                            |  18.749s  |  18.749s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-7-50.smt2                            | 141.841s  | 141.841s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-42.smt2                            |   8.385s  |   8.385s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-49.smt2                            |  34.425s  |  34.425s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass_pwd/prp-8-50.smt2                            |  90.622s  |  90.622s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-0-196.smt2                               |  30.955s  |  30.955s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-0-197.smt2                               |  26.681s  |  26.681s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-0-198.smt2                               |  31.831s  |  31.831s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-0-199.smt2                               |  45.667s  |  45.667s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-0-200.smt2                               |  26.295s  |  26.295s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-2-196.smt2                               |  22.511s  |  22.511s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-2-198.smt2                               |  28.714s  |  28.714s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-2-199.smt2                               |  23.702s  |  23.702s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-2-200.smt2                               |  20.844s  |  20.844s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-3-196.smt2                               |  22.190s  |  22.190s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-3-197.smt2                               |  16.756s  |  16.756s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-3-198.smt2                               |  14.172s  |  14.172s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-3-199.smt2                               |  13.072s  |  13.072s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption/prp-3-200.smt2                               |  19.100s  |  19.100s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-46.smt2                   | 213.410s  | 213.410s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-47.smt2                   | 316.800s  | 316.800s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-48.smt2                   | 374.779s  | 374.779s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-49.smt2                   | 474.585s  | 474.585s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-10-50.smt2                   | 489.000s  | 489.000s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-46.smt2                   | 200.595s  | 200.595s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-47.smt2                   | 324.706s  | 324.706s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-48.smt2                   | 306.165s  | 306.165s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-49.smt2                   | 509.042s  | 509.042s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-11-50.smt2                   | 535.877s  | 535.877s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-46.smt2                   | 144.605s  | 144.605s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-47.smt2                   | 180.190s  | 180.190s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-48.smt2                   | 182.993s  | 182.993s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-49.smt2                   | 238.758s  | 238.758s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-12-50.smt2                   | 277.236s  | 277.236s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-46.smt2                   |  88.464s  |  88.464s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-47.smt2                   |  64.166s  |  64.166s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-48.smt2                   | 145.083s  | 145.083s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-49.smt2                   | 143.110s  | 143.110s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-13-50.smt2                   | 198.906s  | 198.906s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-47.smt2                    |  20.464s  |  20.464s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-48.smt2                    |  35.553s  |  35.553s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-49.smt2                    |  67.780s  |  67.780s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-5-50.smt2                    |  80.766s  |  80.766s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-46.smt2                    | 106.838s  | 106.838s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-47.smt2                    | 125.807s  | 125.807s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-48.smt2                    | 176.268s  | 176.268s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-49.smt2                    | 142.209s  | 142.209s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-6-50.smt2                    | 210.567s  | 210.567s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-46.smt2                    | 110.380s  | 110.380s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-47.smt2                    | 127.375s  | 127.375s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-48.smt2                    | 179.497s  | 179.497s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-49.smt2                    | 203.931s  | 203.931s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-7-50.smt2                    | 289.730s  | 289.730s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_directories/prp-8-50.smt2                    |  14.445s  |  14.445s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-13-50.smt2                         |  18.070s  |  18.070s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-16-49.smt2                         |  14.944s  |  14.944s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-17-47.smt2                         |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-19-50.smt2                         |  22.935s  |  22.935s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-22-47.smt2                         |  30.226s  |  30.226s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-22-48.smt2                         |  41.549s  |  41.549s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-22-50.smt2                         |  20.391s  |  20.391s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-23-50.smt2                         |  21.943s  |  21.943s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-24-49.smt2                         |  17.992s  |  17.992s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-25-48.smt2                         |  29.905s  |  29.905s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-25-49.smt2                         |  77.288s  |  77.288s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-25-50.smt2                         |  97.118s  |  97.118s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-26-48.smt2                         |  25.371s  |  25.371s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-26-49.smt2                         |  36.822s  |  36.822s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-26-50.smt2                         |  42.196s  |  42.196s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-27-48.smt2                         |  24.649s  |  24.649s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-27-49.smt2                         |  33.682s  |  33.682s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-27-50.smt2                         |  55.461s  |  55.461s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-28-48.smt2                         |  31.216s  |  31.216s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-28-49.smt2                         |  56.980s  |  56.980s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-28-50.smt2                         |  94.819s  |  94.819s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-29-49.smt2                         |  35.368s  |  35.368s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-29-50.smt2                         |  65.417s  |  65.417s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-32-50.smt2                         |  20.239s  |  20.239s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-35-49.smt2                         |  16.872s  |  16.872s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-35-50.smt2                         |  22.689s  |  22.689s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-37-50.smt2                         |  19.158s  |  19.158s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-38-48.smt2                         |  25.820s  |  25.820s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-38-50.smt2                         |  17.925s  |  17.925s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-39-50.smt2                         |  41.733s  |  41.733s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-40-50.smt2                         |  25.270s  |  25.270s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-41-50.smt2                         |  52.051s  |  52.051s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-42-50.smt2                         |  19.193s  |  19.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-43-49.smt2                         |  29.535s  |  29.535s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-43-50.smt2                         |  44.305s  |  44.305s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-44-49.smt2                         |  23.308s  |  23.308s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-44-50.smt2                         |  33.931s  |  33.931s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-47-49.smt2                         |  18.073s  |  18.073s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-47-50.smt2                         |  22.753s  |  22.753s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-48-50.smt2                         |  20.086s  |  20.086s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-49-49.smt2                         |  25.817s  |  25.817s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-49-50.smt2                         |  24.682s  |  24.682s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-50-49.smt2                         |  23.987s  |  23.987s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-50-50.smt2                         |  41.211s  |  41.211s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-51-49.smt2                         |  25.931s  |  25.931s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-51-50.smt2                         |  33.276s  |  33.276s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-52-49.smt2                         |  25.511s  |  25.511s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-52-50.smt2                         |  32.436s  |  32.436s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-53-49.smt2                         |  21.676s  |  21.676s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-53-50.smt2                         |  34.214s  |  34.214s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-54-49.smt2                         |  22.532s  |  22.532s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-54-50.smt2                         |  30.135s  |  30.135s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-55-49.smt2                         |  22.576s  |  22.576s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-55-50.smt2                         |  32.411s  |  32.411s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-57-49.smt2                         |  22.072s  |  22.072s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-57-50.smt2                         |  29.052s  |  29.052s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-58-50.smt2                         |  31.067s  |  31.067s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-59-50.smt2                         |  22.728s  |  22.728s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-60-50.smt2                         |  21.633s  |  21.633s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-61-49.smt2                         |  19.016s  |  19.016s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-61-50.smt2                         |  24.297s  |  24.297s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-63-50.smt2                         |  37.077s  |  37.077s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-64-50.smt2                         |  23.943s  |  23.943s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-65-50.smt2                         |  24.342s  |  24.342s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-67-50.smt2                         |  26.626s  |  26.626s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-68-50.smt2                         |  25.404s  |  25.404s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-69-50.smt2                         |  28.154s  |  28.154s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-70-50.smt2                         |  29.280s  |  29.280s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-76-50.smt2                         |  25.554s  |  25.554s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-77-50.smt2                         |  23.945s  |  23.945s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_group/prp-8-49.smt2                          |  16.489s  |  16.489s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-47.smt2                           |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-48.smt2                           |  35.620s  |  35.620s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-50.smt2                           |  45.316s  |  45.316s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-46.smt2                           |  28.113s  |  28.113s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-47.smt2                           |  38.445s  |  38.445s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-48.smt2                           |  36.374s  |  36.374s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-46.smt2                          | 157.236s  | 157.236s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-47.smt2                          | 202.526s  | 202.526s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-48.smt2                          |  72.743s  |  72.743s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-49.smt2                          | 600.190s  | 600.190s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-50.smt2                          | 600.257s  | 600.257s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-46.smt2                          | 263.081s  | 263.081s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-47.smt2                          | 164.270s  | 164.270s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-48.smt2                          |  72.848s  |  72.848s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-49.smt2                          | 406.394s  | 406.394s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-50.smt2                          | 498.760s  | 498.760s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-48.smt2                          |  32.866s  |  32.866s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-49.smt2                          |  45.964s  |  45.964s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-50.smt2                          |  48.657s  |  48.657s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-46.smt2                          | 144.233s  | 144.233s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-47.smt2                          | 265.063s  | 265.063s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-48.smt2                          |  58.807s  |  58.807s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-49.smt2                          | 291.686s  | 291.686s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-50.smt2                          | 539.739s  | 539.739s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-46.smt2                          |  25.660s  |  25.660s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-48.smt2                          |  33.388s  |  33.388s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-50.smt2                          |  48.602s  |  48.602s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-47.smt2                          |  29.570s  |  29.570s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-48.smt2                          |  30.836s  |  30.836s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-49.smt2                          |  45.613s  |  45.613s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-46.smt2                          | 189.122s  | 189.122s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-47.smt2                          | 254.852s  | 254.852s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-48.smt2                          |  50.831s  |  50.831s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-49.smt2                          | 344.973s  | 344.973s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-46.smt2                          | 130.251s  | 130.251s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-47.smt2                          | 304.325s  | 304.325s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-48.smt2                          |  71.771s  |  71.771s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-49.smt2                          | 456.536s  | 456.536s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-50.smt2                          | 243.813s  | 243.813s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-46.smt2                          |  32.017s  |  32.017s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-47.smt2                          |  29.882s  |  29.882s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-48.smt2                          |  36.711s  |  36.711s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-49.smt2                          |  38.932s  |  38.932s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-50.smt2                          |  62.245s  |  62.245s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-46.smt2                          | 194.063s  | 194.063s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-47.smt2                          | 231.603s  | 231.603s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-48.smt2                          |  51.808s  |  51.808s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-49.smt2                          | 318.533s  | 318.533s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-50.smt2                          | 341.148s  | 341.148s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-46.smt2                           | 143.667s  | 143.667s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-47.smt2                           | 145.561s  | 145.561s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-48.smt2                           | 110.618s  | 110.618s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-49.smt2                           | 600.153s  | 600.153s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-50.smt2                           | 600.214s  | 600.214s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-46.smt2                          |  37.571s  |  37.571s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-49.smt2                          |  39.479s  |  39.479s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-50.smt2                          |  54.765s  |  54.765s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-46.smt2                          |  37.511s  |  37.511s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-48.smt2                          |  35.334s  |  35.334s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-49.smt2                          |  47.810s  |  47.810s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-50.smt2                          |  54.326s  |  54.326s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-46.smt2                          | 233.121s  | 233.121s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-47.smt2                          | 295.091s  | 295.091s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-48.smt2                          |  42.897s  |  42.897s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-49.smt2                          | 428.939s  | 428.939s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-50.smt2                          | 600.290s  | 600.290s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-46.smt2                          | 214.152s  | 214.152s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-47.smt2                          | 189.766s  | 189.766s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-48.smt2                          |  47.765s  |  47.765s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-49.smt2                          | 366.531s  | 366.531s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-50.smt2                          | 243.638s  | 243.638s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-46.smt2                          |  36.877s  |  36.877s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-48.smt2                          |  38.804s  |  38.804s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-49.smt2                          |  44.419s  |  44.419s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-46.smt2                          | 225.362s  | 225.362s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-47.smt2                          |  91.581s  |  91.581s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-48.smt2                          |  44.731s  |  44.731s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-49.smt2                          | 387.413s  | 387.413s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-50.smt2                          | 329.382s  | 329.382s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-47.smt2                          |  44.509s  |  44.509s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-48.smt2                          |  54.854s  |  54.854s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-46.smt2                          |  39.188s  |  39.188s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-48.smt2                          |  73.476s  |  73.476s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-49.smt2                          |  90.299s  |  90.299s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-50.smt2                          |  99.806s  |  99.806s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-46.smt2                          | 332.524s  | 332.524s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-47.smt2                          | 524.080s  | 524.080s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-48.smt2                          | 600.445s  | 600.445s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-49.smt2                          | 600.215s  | 600.215s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-50.smt2                          | 600.296s  | 600.296s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-46.smt2                          | 279.123s  | 279.123s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-47.smt2                          |  42.326s  |  42.326s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-48.smt2                          | 304.609s  | 304.609s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-49.smt2                          | 600.291s  | 600.291s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-50.smt2                          | 600.247s  | 600.247s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-46.smt2                           | 206.746s  | 206.746s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-47.smt2                           | 217.321s  | 217.321s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-48.smt2                           |  75.553s  |  75.553s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-49.smt2                           | 369.561s  | 369.561s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-50.smt2                           | 600.317s  | 600.317s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-46.smt2                          | 352.645s  | 352.645s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-47.smt2                          | 392.979s  | 392.979s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-48.smt2                          | 600.256s  | 600.256s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-49.smt2                          | 600.324s  | 600.324s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-50.smt2                          | 600.344s  | 600.344s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-46.smt2                          |  55.382s  |  55.382s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-47.smt2                          |  78.698s  |  78.698s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-48.smt2                          |  52.079s  |  52.079s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-50.smt2                          |  86.006s  |  86.006s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-46.smt2                          |  92.255s  |  92.255s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-47.smt2                          | 144.131s  | 144.131s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-48.smt2                          |  44.833s  |  44.833s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-49.smt2                          | 175.014s  | 175.014s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-50.smt2                          | 306.651s  | 306.651s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-46.smt2                          | 255.264s  | 255.264s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-47.smt2                          | 164.222s  | 164.222s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-48.smt2                          | 194.471s  | 194.471s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-49.smt2                          | 600.263s  | 600.263s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-50.smt2                          | 600.181s  | 600.181s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-47.smt2                          | 271.830s  | 271.830s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-48.smt2                          | 268.540s  | 268.540s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-49.smt2                          | 115.167s  | 115.167s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-50.smt2                          | 600.520s  | 600.520s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-46.smt2                          |  94.512s  |  94.512s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-48.smt2                          |  95.251s  |  95.251s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-49.smt2                          | 110.871s  | 110.871s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-50.smt2                          |  91.949s  |  91.949s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-46.smt2                          |  49.917s  |  49.917s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-47.smt2                          |  55.678s  |  55.678s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-48.smt2                          |  87.748s  |  87.748s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-47.smt2                          |  15.008s  |  15.008s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-48.smt2                          | 438.259s  | 438.259s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-49.smt2                          | 600.333s  | 600.333s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-50.smt2                          | 600.258s  | 600.258s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-46.smt2                          |  94.910s  |  94.910s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-47.smt2                          | 163.843s  | 163.843s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-48.smt2                          |  46.149s  |  46.149s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-49.smt2                          | 436.491s  | 436.491s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-50.smt2                          | 357.345s  | 357.345s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-46.smt2                          | 169.994s  | 169.994s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-47.smt2                          |  58.632s  |  58.632s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-48.smt2                          | 198.619s  | 198.619s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-49.smt2                          | 511.318s  | 511.318s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-47.smt2                           |  28.834s  |  28.834s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-49.smt2                           |  35.408s  |  35.408s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-46.smt2                          | 177.307s  | 177.307s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-47.smt2                          | 193.342s  | 193.342s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-48.smt2                          | 412.843s  | 412.843s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-49.smt2                          | 392.591s  | 392.591s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-50.smt2                          | 600.226s  | 600.226s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-46.smt2                          | 200.033s  | 200.033s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-47.smt2                          | 272.031s  | 272.031s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-48.smt2                          | 419.770s  | 419.770s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-49.smt2                          | 364.977s  | 364.977s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-50.smt2                          | 563.720s  | 563.720s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-47.smt2                          |  14.576s  |  14.576s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-48.smt2                          |  16.933s  |  16.933s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-49.smt2                          | 381.324s  | 381.324s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-50.smt2                          | 600.384s  | 600.384s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-46.smt2                          | 112.585s  | 112.585s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-47.smt2                          | 105.703s  | 105.703s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-48.smt2                          |  52.445s  |  52.445s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-49.smt2                          | 202.759s  | 202.759s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-50.smt2                          | 315.159s  | 315.159s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-46.smt2                          | 143.284s  | 143.284s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-47.smt2                          | 159.968s  | 159.968s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-48.smt2                          | 185.193s  | 185.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-49.smt2                          | 298.822s  | 298.822s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-50.smt2                          | 474.926s  | 474.926s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-46.smt2                          |  93.832s  |  93.832s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-47.smt2                          | 133.146s  | 133.146s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-48.smt2                          |  50.966s  |  50.966s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-49.smt2                          | 330.833s  | 330.833s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-50.smt2                          | 310.192s  | 310.192s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-46.smt2                          | 147.169s  | 147.169s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-47.smt2                          | 163.587s  | 163.587s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-48.smt2                          | 216.651s  | 216.651s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-49.smt2                          | 281.727s  | 281.727s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-50.smt2                          | 376.047s  | 376.047s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-46.smt2                          | 122.053s  | 122.053s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-47.smt2                          | 134.964s  | 134.964s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-48.smt2                          |  98.943s  |  98.943s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-49.smt2                          | 396.249s  | 396.249s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-50.smt2                          | 344.490s  | 344.490s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-46.smt2                          | 104.699s  | 104.699s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-47.smt2                          |  46.793s  |  46.793s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-48.smt2                          | 130.650s  | 130.650s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-49.smt2                          | 229.725s  | 229.725s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-50.smt2                          | 335.616s  | 335.616s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-46.smt2                          |  80.402s  |  80.402s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-47.smt2                          | 129.073s  | 129.073s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-48.smt2                          |  63.194s  |  63.194s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-49.smt2                          | 360.067s  | 360.067s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-50.smt2                          | 386.444s  | 386.444s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-46.smt2                           |  24.594s  |  24.594s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-47.smt2                           |  27.374s  |  27.374s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-48.smt2                           |  35.406s  |  35.406s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-49.smt2                           |  38.763s  |  38.763s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-50.smt2                           |  42.061s  |  42.061s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-47.smt2                          |  93.678s  |  93.678s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-49.smt2                          | 208.181s  | 208.181s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-47.smt2                          | 127.764s  | 127.764s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-48.smt2                          |  46.110s  |  46.110s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-49.smt2                          | 271.997s  | 271.997s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-50.smt2                          | 278.042s  | 278.042s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-46.smt2                           |  22.045s  |  22.045s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-47.smt2                           |  29.527s  |  29.527s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-48.smt2                           |  35.305s  |  35.305s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-49.smt2                           |  38.592s  |  38.592s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-50.smt2                           |  44.254s  |  44.254s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-46.smt2                           |  24.244s  |  24.244s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-47.smt2                           |  27.724s  |  27.724s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-48.smt2                           |  35.006s  |  35.006s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-49.smt2                           |  40.846s  |  40.846s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-50.smt2                           |  50.600s  |  50.600s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-46.smt2                           | 270.779s  | 270.779s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-47.smt2                           | 125.736s  | 125.736s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-48.smt2                           |  67.364s  |  67.364s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-49.smt2                           | 499.973s  | 499.973s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-50.smt2                           | 600.231s  | 600.231s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-46.smt2                           |  97.290s  |  97.290s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-47.smt2                           | 296.708s  | 296.708s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-48.smt2                           |  78.567s  |  78.567s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-49.smt2                           | 316.120s  | 316.120s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-50.smt2                           | 600.226s  | 600.226s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/int_from_list/prp-0-48.smt2                            |  45.744s  |  45.744s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/int_from_list/prp-0-49.smt2                            |  35.102s  |  35.102s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/int_from_list/prp-0-50.smt2                            |  60.860s  |  60.860s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/int_from_list/prp-1-48.smt2                            |  35.248s  |  35.248s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/int_from_list/prp-1-49.smt2                            |  51.117s  |  51.117s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/int_from_list/prp-1-50.smt2                            |  46.669s  |  46.669s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/int_from_list/prp-37-47.smt2                           |  21.797s  |  21.797s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-46.smt2                         |  55.555s  |  55.555s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-48.smt2                         |  64.364s  |  64.364s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-49.smt2                         |  45.033s  |  45.033s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-46.smt2                         |  85.432s  |  85.432s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-48.smt2                         | 158.971s  | 158.971s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-50.smt2                         |  97.140s  |  97.140s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-46.smt2                        | 600.264s  | 600.264s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-47.smt2                        | 600.397s  | 600.397s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-49.smt2                        | 600.244s  | 600.244s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-50.smt2                        | 600.263s  | 600.263s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-47.smt2                        | 342.963s  | 342.963s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-49.smt2                        | 403.875s  | 403.875s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-47.smt2                        | 126.473s  | 126.473s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-49.smt2                        | 346.137s  | 346.137s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-50.smt2                        | 421.107s  | 421.107s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-46.smt2                        | 203.120s  | 203.120s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-47.smt2                        | 138.624s  | 138.624s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-48.smt2                        | 258.286s  | 258.286s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-49.smt2                        |  99.943s  |  99.943s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-50.smt2                        | 262.943s  | 262.943s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-46.smt2                        | 128.514s  | 128.514s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-47.smt2                        | 171.105s  | 171.105s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-48.smt2                        | 174.996s  | 174.996s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-49.smt2                        | 533.765s  | 533.765s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-50.smt2                        | 132.356s  | 132.356s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-46.smt2                        | 105.953s  | 105.953s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-48.smt2                        | 163.611s  | 163.611s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-49.smt2                        | 149.961s  | 149.961s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-50.smt2                        |  91.986s  |  91.986s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-46.smt2                        |  51.846s  |  51.846s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-47.smt2                        | 110.344s  | 110.344s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-48.smt2                        | 141.308s  | 141.308s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-49.smt2                        | 199.002s  | 199.002s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-47.smt2                        | 147.895s  | 147.895s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-48.smt2                        |  99.357s  |  99.357s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-49.smt2                        |  48.481s  |  48.481s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-48.smt2                        |  58.413s  |  58.413s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-49.smt2                        |  74.827s  |  74.827s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-50.smt2                        | 187.382s  | 187.382s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-48.smt2                        |  73.714s  |  73.714s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-49.smt2                        | 199.246s  | 199.246s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-50.smt2                        | 233.999s  | 233.999s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-47.smt2                         | 235.390s  | 235.390s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-46.smt2                        |  57.381s  |  57.381s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-47.smt2                        | 103.276s  | 103.276s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-50.smt2                        | 251.951s  | 251.951s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-47.smt2                        |  51.948s  |  51.948s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-48.smt2                        |  79.474s  |  79.474s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-49.smt2                        | 127.215s  | 127.215s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-50.smt2                        | 139.873s  | 139.873s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-46.smt2                        |  48.310s  |  48.310s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-48.smt2                        |  83.208s  |  83.208s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-50.smt2                        | 132.930s  | 132.930s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-46.smt2                        |  40.699s  |  40.699s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-48.smt2                        |  61.202s  |  61.202s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-49.smt2                        | 209.339s  | 209.339s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-50.smt2                        | 253.385s  | 253.385s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-46.smt2                        |  49.381s  |  49.381s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-47.smt2                        | 152.681s  | 152.681s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-48.smt2                        | 100.194s  | 100.194s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-50.smt2                        | 103.530s  | 103.530s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-47.smt2                         | 145.149s  | 145.149s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-48.smt2                         | 236.892s  | 236.892s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-49.smt2                         | 175.669s  | 175.669s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-50.smt2                         | 308.955s  | 308.955s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-46.smt2                         |  70.207s  |  70.207s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-47.smt2                         | 384.634s  | 384.634s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-48.smt2                         |  57.527s  |  57.527s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-49.smt2                         | 433.268s  | 433.268s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-50.smt2                         | 394.880s  | 394.880s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-46.smt2                         | 301.281s  | 301.281s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-47.smt2                         |  74.123s  |  74.123s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-48.smt2                         | 237.702s  | 237.702s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-49.smt2                         | 151.499s  | 151.499s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-50.smt2                         | 141.193s  | 141.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-46.smt2                         |  60.735s  |  60.735s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-47.smt2                         |  58.372s  |  58.372s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-48.smt2                         | 156.236s  | 156.236s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-49.smt2                         | 244.578s  | 244.578s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-50.smt2                         |  94.424s  |  94.424s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-47.smt2                         | 172.054s  | 172.054s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-48.smt2                         | 279.466s  | 279.466s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-49.smt2                         | 360.256s  | 360.256s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-48.smt2                         |  81.314s  |  81.314s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-49.smt2                         | 134.458s  | 134.458s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-46.smt2                         | 145.087s  | 145.087s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-48.smt2                         |  76.325s  |  76.325s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-50.smt2                         | 253.385s  | 253.385s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1015084.smt2                              |  12.462s  |  12.462s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1072007.smt2                              |  77.402s  |  77.402s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1138192.smt2                              | 195.953s  | 195.953s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1192684.smt2                              |  21.442s  |  21.442s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1262176.smt2                              | 187.192s  | 187.192s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1265513.smt2                              |  90.529s  |  90.529s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1268455.smt2                              |  59.092s  |  59.092s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1270163.smt2                              |   5.634s  |   5.634s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1317230.smt2                              |  32.279s  |  32.279s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1361831.smt2                              |  22.849s  |  22.849s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1452366.smt2                              | 238.354s  | 238.354s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-247831.smt2                               |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-269353.smt2                               |  69.578s  |  69.578s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-278378.smt2                               | 202.816s  | 202.816s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-283008.smt2                               | 111.431s  | 111.431s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-285271.smt2                               | 324.171s  | 324.171s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-321761.smt2                               | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-329386.smt2                               |   9.530s  |   9.530s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-343499.smt2                               |   5.563s  |   5.563s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-368069.smt2                               | 600.184s  | 600.184s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-413904.smt2                               |   4.891s  |   4.891s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-495717.smt2                               | 168.822s  | 168.822s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-527358.smt2                               |   3.626s  |   3.626s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-658040.smt2                               | 392.637s  | 392.637s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-705295.smt2                               |  10.424s  |  10.424s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-729964.smt2                               | 195.269s  | 195.269s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-758897.smt2                               |  12.232s  |  12.232s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-762853.smt2                               | 356.454s  | 356.454s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-794687.smt2                               |  16.056s  |  16.056s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-906586.smt2                               |  33.516s  |  33.516s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-916807.smt2                               |   8.506s  |   8.506s  |   0.000s  | 0.0%|
</details>
