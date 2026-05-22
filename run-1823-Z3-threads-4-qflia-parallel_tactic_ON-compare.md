Comparing data and data


# SUMMARY
- LHS tests = 5000
- RHS tests = 5000
- LHS success = 2002  (40.04%)
- RHS success = 2002  (40.04%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-qflia-parallel_tactic_ON
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 991b5e5f9c18b57a615c731d08dcc2409ce49dad
Z3 branch: parallel_tactic
Z3 options: "-T:30 -v:0 parallel.enable=true parallel.threads=4 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/QF_LIA
Z3 commit message: fix random seed

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-qflia-parallel_tactic_ON
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 991b5e5f9c18b57a615c731d08dcc2409ce49dad
Z3 branch: parallel_tactic
Z3 options: "-T:30 -v:0 parallel.enable=true parallel.threads=4 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/QF_LIA
Z3 commit message: fix random seed

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02-treeWeight-570-8leaves.smt2                                                              |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|064-incremental_scheduling-15092-0.smt2                                                     |  11.713s  |  11.713s  |   0.000s  | 0.0%|
|07-treeWeight-569-8leaves.smt2                                                              |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|10-30.slack.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|14-treeWeight-537-8leaves.smt2                                                              |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|140-incremental_scheduling-18576-0.smt2                                                     |   1.990s  |   1.990s  |   0.000s  | 0.0%|
|15-20.smt2                                                                                  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|15-5.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|16.lp.smt2                                                                                  |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|18.lp.smt2                                                                                  |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|182-incremental_scheduling-17280-0.smt2                                                     |   1.157s  |   1.157s  |   0.000s  | 0.0%|
|19-treeWeight-772-8leaves.smt2                                                              |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|20-10.smt2                                                                                  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|20-11.slack.smt2                                                                            |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|20-12.slack.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|20-12.smt2                                                                                  |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|20-14.smt2                                                                                  |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|20-17.smt2                                                                                  |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|20-4.slack.smt2                                                                             |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|20-7.slack.smt2                                                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02-treeWeight-570-8leaves.smt2                                                              |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|064-incremental_scheduling-15092-0.smt2                                                     |  11.713s  |  11.713s  |   0.000s  | 0.0%|
|07-treeWeight-569-8leaves.smt2                                                              |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|10-30.slack.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|14-treeWeight-537-8leaves.smt2                                                              |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|140-incremental_scheduling-18576-0.smt2                                                     |   1.990s  |   1.990s  |   0.000s  | 0.0%|
|15-20.smt2                                                                                  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|15-5.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|16.lp.smt2                                                                                  |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|18.lp.smt2                                                                                  |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|182-incremental_scheduling-17280-0.smt2                                                     |   1.157s  |   1.157s  |   0.000s  | 0.0%|
|19-treeWeight-772-8leaves.smt2                                                              |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|20-10.smt2                                                                                  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|20-11.slack.smt2                                                                            |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|20-12.slack.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|20-12.smt2                                                                                  |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|20-14.smt2                                                                                  |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|20-17.smt2                                                                                  |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|20-4.slack.smt2                                                                             |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|20-7.slack.smt2                                                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02-treeWeight-570-8leaves.smt2                                                              |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|064-incremental_scheduling-15092-0.smt2                                                     |  11.713s  |  11.713s  |   0.000s  | 0.0%|
|07-treeWeight-569-8leaves.smt2                                                              |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|10-30.slack.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|14-treeWeight-537-8leaves.smt2                                                              |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|140-incremental_scheduling-18576-0.smt2                                                     |   1.990s  |   1.990s  |   0.000s  | 0.0%|
|15-20.smt2                                                                                  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|15-5.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|16.lp.smt2                                                                                  |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|18.lp.smt2                                                                                  |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|182-incremental_scheduling-17280-0.smt2                                                     |   1.157s  |   1.157s  |   0.000s  | 0.0%|
|19-treeWeight-772-8leaves.smt2                                                              |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|20-10.smt2                                                                                  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|20-11.slack.smt2                                                                            |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|20-12.slack.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|20-12.smt2                                                                                  |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|20-14.smt2                                                                                  |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|20-17.smt2                                                                                  |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|20-4.slack.smt2                                                                             |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|20-7.slack.smt2                                                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02-treeWeight-570-8leaves.smt2                                                              |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|064-incremental_scheduling-15092-0.smt2                                                     |  11.713s  |  11.713s  |   0.000s  | 0.0%|
|07-treeWeight-569-8leaves.smt2                                                              |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|10-30.slack.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|14-treeWeight-537-8leaves.smt2                                                              |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|140-incremental_scheduling-18576-0.smt2                                                     |   1.990s  |   1.990s  |   0.000s  | 0.0%|
|15-20.smt2                                                                                  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|15-5.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|16.lp.smt2                                                                                  |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|18.lp.smt2                                                                                  |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|182-incremental_scheduling-17280-0.smt2                                                     |   1.157s  |   1.157s  |   0.000s  | 0.0%|
|19-treeWeight-772-8leaves.smt2                                                              |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|20-10.smt2                                                                                  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|20-11.slack.smt2                                                                            |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|20-12.slack.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|20-12.smt2                                                                                  |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|20-14.smt2                                                                                  |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|20-17.smt2                                                                                  |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|20-4.slack.smt2                                                                             |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|20-7.slack.smt2                                                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n6757-prp-14-50.smt2                                                                       |  30.241s |1056.0MiB|
|n7399-prp-10-48.smt2                                                                       |  30.234s |1398.0MiB|
|n6981-prp-62-50.smt2                                                                       |  30.208s |921.0MiB|
|n7559-prp-4-48.smt2                                                                        |  30.207s |1517.0MiB|
|n7392-prp-1-46.smt2                                                                        |  30.205s |1460.0MiB|
|n6833-prp-34-47.smt2                                                                       |  30.203s |1085.0MiB|
|n6931-prp-5-50.smt2                                                                        |  30.192s |1037.0MiB|
|n7618-prp-50-47.smt2                                                                       |  30.191s |1467.0MiB|
|n6843-prp-36-49.smt2                                                                       |  30.190s |977.0MiB|
|n7525-prp-33-49.smt2                                                                       |  30.188s |1033.0MiB|
|n6971-prp-58-50.smt2                                                                       |  30.187s |791.0MiB|
|n8026-prp-21-46.smt2                                                                       |  30.186s |845.0MiB|
|n7994-prp-15-49.smt2                                                                       |  30.184s |1059.0MiB|
|n7498-prp-29-47.smt2                                                                       |  30.182s |1352.0MiB|
|n7502-prp-3-46.smt2                                                                        |  30.182s |1215.0MiB|
|n8000-prp-16-50.smt2                                                                       |  30.181s |1068.0MiB|
|n7020-prp-6-48.smt2                                                                        |  30.179s |1312.0MiB|
|n7412-prp-13-46.smt2                                                                       |  30.179s |1285.0MiB|
|n8042-prp-24-47.smt2                                                                       |  30.178s |888.0MiB|
|n7499-prp-29-48.smt2                                                                       |  30.177s |1301.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n6757-prp-14-50.smt2                                                                       |  30.241s |1056.0MiB|
|n7399-prp-10-48.smt2                                                                       |  30.234s |1398.0MiB|
|n6981-prp-62-50.smt2                                                                       |  30.208s |921.0MiB|
|n7559-prp-4-48.smt2                                                                        |  30.207s |1517.0MiB|
|n7392-prp-1-46.smt2                                                                        |  30.205s |1460.0MiB|
|n6833-prp-34-47.smt2                                                                       |  30.203s |1085.0MiB|
|n6931-prp-5-50.smt2                                                                        |  30.192s |1037.0MiB|
|n7618-prp-50-47.smt2                                                                       |  30.191s |1467.0MiB|
|n6843-prp-36-49.smt2                                                                       |  30.190s |977.0MiB|
|n7525-prp-33-49.smt2                                                                       |  30.188s |1033.0MiB|
|n6971-prp-58-50.smt2                                                                       |  30.187s |791.0MiB|
|n8026-prp-21-46.smt2                                                                       |  30.186s |845.0MiB|
|n7994-prp-15-49.smt2                                                                       |  30.184s |1059.0MiB|
|n7498-prp-29-47.smt2                                                                       |  30.182s |1352.0MiB|
|n7502-prp-3-46.smt2                                                                        |  30.182s |1215.0MiB|
|n8000-prp-16-50.smt2                                                                       |  30.181s |1068.0MiB|
|n7020-prp-6-48.smt2                                                                        |  30.179s |1312.0MiB|
|n7412-prp-13-46.smt2                                                                       |  30.179s |1285.0MiB|
|n8042-prp-24-47.smt2                                                                       |  30.178s |888.0MiB|
|n7499-prp-29-48.smt2                                                                       |  30.177s |1301.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02-treeWeight-570-8leaves.smt2                                                              |155.0MiB|155.0MiB|0B| 0.0%|
|064-incremental_scheduling-15092-0.smt2                                                     |164.0MiB|164.0MiB|0B| 0.0%|
|07-treeWeight-569-8leaves.smt2                                                              |155.0MiB|155.0MiB|0B| 0.0%|
|10-30.slack.smt2                                                                            |140.0MiB|140.0MiB|0B| 0.0%|
|14-treeWeight-537-8leaves.smt2                                                              |154.0MiB|154.0MiB|0B| 0.0%|
|140-incremental_scheduling-18576-0.smt2                                                     |164.0MiB|164.0MiB|0B| 0.0%|
|15-20.smt2                                                                                  |140.0MiB|140.0MiB|0B| 0.0%|
|15-5.smt2                                                                                   |140.0MiB|140.0MiB|0B| 0.0%|
|16.lp.smt2                                                                                  |158.0MiB|158.0MiB|0B| 0.0%|
|18.lp.smt2                                                                                  |157.0MiB|157.0MiB|0B| 0.0%|
|182-incremental_scheduling-17280-0.smt2                                                     |171.0MiB|171.0MiB|0B| 0.0%|
|19-treeWeight-772-8leaves.smt2                                                              |154.0MiB|154.0MiB|0B| 0.0%|
|20-10.smt2                                                                                  |141.0MiB|141.0MiB|0B| 0.0%|
|20-11.slack.smt2                                                                            |141.0MiB|141.0MiB|0B| 0.0%|
|20-12.slack.smt2                                                                            |141.0MiB|141.0MiB|0B| 0.0%|
|20-12.smt2                                                                                  |140.0MiB|140.0MiB|0B| 0.0%|
|20-14.smt2                                                                                  |144.0MiB|144.0MiB|0B| 0.0%|
|20-17.smt2                                                                                  |140.0MiB|140.0MiB|0B| 0.0%|
|20-4.slack.smt2                                                                             |140.0MiB|140.0MiB|0B| 0.0%|
|20-7.slack.smt2                                                                             |141.0MiB|141.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02-treeWeight-570-8leaves.smt2                                                              |155.0MiB|155.0MiB|0B| 0.0%|
|064-incremental_scheduling-15092-0.smt2                                                     |164.0MiB|164.0MiB|0B| 0.0%|
|07-treeWeight-569-8leaves.smt2                                                              |155.0MiB|155.0MiB|0B| 0.0%|
|10-30.slack.smt2                                                                            |140.0MiB|140.0MiB|0B| 0.0%|
|14-treeWeight-537-8leaves.smt2                                                              |154.0MiB|154.0MiB|0B| 0.0%|
|140-incremental_scheduling-18576-0.smt2                                                     |164.0MiB|164.0MiB|0B| 0.0%|
|15-20.smt2                                                                                  |140.0MiB|140.0MiB|0B| 0.0%|
|15-5.smt2                                                                                   |140.0MiB|140.0MiB|0B| 0.0%|
|16.lp.smt2                                                                                  |158.0MiB|158.0MiB|0B| 0.0%|
|18.lp.smt2                                                                                  |157.0MiB|157.0MiB|0B| 0.0%|
|182-incremental_scheduling-17280-0.smt2                                                     |171.0MiB|171.0MiB|0B| 0.0%|
|19-treeWeight-772-8leaves.smt2                                                              |154.0MiB|154.0MiB|0B| 0.0%|
|20-10.smt2                                                                                  |141.0MiB|141.0MiB|0B| 0.0%|
|20-11.slack.smt2                                                                            |141.0MiB|141.0MiB|0B| 0.0%|
|20-12.slack.smt2                                                                            |141.0MiB|141.0MiB|0B| 0.0%|
|20-12.smt2                                                                                  |140.0MiB|140.0MiB|0B| 0.0%|
|20-14.smt2                                                                                  |144.0MiB|144.0MiB|0B| 0.0%|
|20-17.smt2                                                                                  |140.0MiB|140.0MiB|0B| 0.0%|
|20-4.slack.smt2                                                                             |140.0MiB|140.0MiB|0B| 0.0%|
|20-7.slack.smt2                                                                             |141.0MiB|141.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02-treeWeight-570-8leaves.smt2                                                              |155.0MiB|155.0MiB|0B| 0.0%|
|064-incremental_scheduling-15092-0.smt2                                                     |164.0MiB|164.0MiB|0B| 0.0%|
|07-treeWeight-569-8leaves.smt2                                                              |155.0MiB|155.0MiB|0B| 0.0%|
|10-30.slack.smt2                                                                            |140.0MiB|140.0MiB|0B| 0.0%|
|14-treeWeight-537-8leaves.smt2                                                              |154.0MiB|154.0MiB|0B| 0.0%|
|140-incremental_scheduling-18576-0.smt2                                                     |164.0MiB|164.0MiB|0B| 0.0%|
|15-20.smt2                                                                                  |140.0MiB|140.0MiB|0B| 0.0%|
|15-5.smt2                                                                                   |140.0MiB|140.0MiB|0B| 0.0%|
|16.lp.smt2                                                                                  |158.0MiB|158.0MiB|0B| 0.0%|
|18.lp.smt2                                                                                  |157.0MiB|157.0MiB|0B| 0.0%|
|182-incremental_scheduling-17280-0.smt2                                                     |171.0MiB|171.0MiB|0B| 0.0%|
|19-treeWeight-772-8leaves.smt2                                                              |154.0MiB|154.0MiB|0B| 0.0%|
|20-10.smt2                                                                                  |141.0MiB|141.0MiB|0B| 0.0%|
|20-11.slack.smt2                                                                            |141.0MiB|141.0MiB|0B| 0.0%|
|20-12.slack.smt2                                                                            |141.0MiB|141.0MiB|0B| 0.0%|
|20-12.smt2                                                                                  |140.0MiB|140.0MiB|0B| 0.0%|
|20-14.smt2                                                                                  |144.0MiB|144.0MiB|0B| 0.0%|
|20-17.smt2                                                                                  |140.0MiB|140.0MiB|0B| 0.0%|
|20-4.slack.smt2                                                                             |140.0MiB|140.0MiB|0B| 0.0%|
|20-7.slack.smt2                                                                             |141.0MiB|141.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02-treeWeight-570-8leaves.smt2                                                              |155.0MiB|155.0MiB|0B| 0.0%|
|064-incremental_scheduling-15092-0.smt2                                                     |164.0MiB|164.0MiB|0B| 0.0%|
|07-treeWeight-569-8leaves.smt2                                                              |155.0MiB|155.0MiB|0B| 0.0%|
|10-30.slack.smt2                                                                            |140.0MiB|140.0MiB|0B| 0.0%|
|14-treeWeight-537-8leaves.smt2                                                              |154.0MiB|154.0MiB|0B| 0.0%|
|140-incremental_scheduling-18576-0.smt2                                                     |164.0MiB|164.0MiB|0B| 0.0%|
|15-20.smt2                                                                                  |140.0MiB|140.0MiB|0B| 0.0%|
|15-5.smt2                                                                                   |140.0MiB|140.0MiB|0B| 0.0%|
|16.lp.smt2                                                                                  |158.0MiB|158.0MiB|0B| 0.0%|
|18.lp.smt2                                                                                  |157.0MiB|157.0MiB|0B| 0.0%|
|182-incremental_scheduling-17280-0.smt2                                                     |171.0MiB|171.0MiB|0B| 0.0%|
|19-treeWeight-772-8leaves.smt2                                                              |154.0MiB|154.0MiB|0B| 0.0%|
|20-10.smt2                                                                                  |141.0MiB|141.0MiB|0B| 0.0%|
|20-11.slack.smt2                                                                            |141.0MiB|141.0MiB|0B| 0.0%|
|20-12.slack.smt2                                                                            |141.0MiB|141.0MiB|0B| 0.0%|
|20-12.smt2                                                                                  |140.0MiB|140.0MiB|0B| 0.0%|
|20-14.smt2                                                                                  |144.0MiB|144.0MiB|0B| 0.0%|
|20-17.smt2                                                                                  |140.0MiB|140.0MiB|0B| 0.0%|
|20-4.slack.smt2                                                                             |140.0MiB|140.0MiB|0B| 0.0%|
|20-7.slack.smt2                                                                             |141.0MiB|141.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n4085-RC-02.smt2                                                                           |   3.570s |1982.0MiB|
|n4086-RC-03.smt2                                                                           |   2.971s |1917.0MiB|
|n7559-prp-4-48.smt2                                                                        |  30.207s |1517.0MiB|
|n7618-prp-50-47.smt2                                                                       |  30.191s |1467.0MiB|
|n7392-prp-1-46.smt2                                                                        |  30.205s |1460.0MiB|
|n7633-prp-7-48.smt2                                                                        |  30.164s |1427.0MiB|
|n7399-prp-10-48.smt2                                                                       |  30.234s |1398.0MiB|
|n7637-prp-8-47.smt2                                                                        |  30.166s |1392.0MiB|
|n4083-RC-00.smt2                                                                           |   1.896s |1358.0MiB|
|n7387-prp-0-46.smt2                                                                        |  21.708s |1353.0MiB|
|n7498-prp-29-47.smt2                                                                       |  30.182s |1352.0MiB|
|n7642-prp-9-47.smt2                                                                        |  30.171s |1340.0MiB|
|n7388-prp-0-47.smt2                                                                        |  29.756s |1320.0MiB|
|n7020-prp-6-48.smt2                                                                        |  30.179s |1312.0MiB|
|n7268-prp-50-49.smt2                                                                       |  28.978s |1309.0MiB|
|n7499-prp-29-48.smt2                                                                       |  30.177s |1301.0MiB|
|n7139-prp-27-50.smt2                                                                       |  30.172s |1298.0MiB|
|n7424-prp-15-48.smt2                                                                       |  30.154s |1296.0MiB|
|n7402-prp-11-46.smt2                                                                       |  30.169s |1287.0MiB|
|n7412-prp-13-46.smt2                                                                       |  30.179s |1285.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n4085-RC-02.smt2                                                                           |   3.570s |1982.0MiB|
|n4086-RC-03.smt2                                                                           |   2.971s |1917.0MiB|
|n7559-prp-4-48.smt2                                                                        |  30.207s |1517.0MiB|
|n7618-prp-50-47.smt2                                                                       |  30.191s |1467.0MiB|
|n7392-prp-1-46.smt2                                                                        |  30.205s |1460.0MiB|
|n7633-prp-7-48.smt2                                                                        |  30.164s |1427.0MiB|
|n7399-prp-10-48.smt2                                                                       |  30.234s |1398.0MiB|
|n7637-prp-8-47.smt2                                                                        |  30.166s |1392.0MiB|
|n4083-RC-00.smt2                                                                           |   1.896s |1358.0MiB|
|n7387-prp-0-46.smt2                                                                        |  21.708s |1353.0MiB|
|n7498-prp-29-47.smt2                                                                       |  30.182s |1352.0MiB|
|n7642-prp-9-47.smt2                                                                        |  30.171s |1340.0MiB|
|n7388-prp-0-47.smt2                                                                        |  29.756s |1320.0MiB|
|n7020-prp-6-48.smt2                                                                        |  30.179s |1312.0MiB|
|n7268-prp-50-49.smt2                                                                       |  28.978s |1309.0MiB|
|n7499-prp-29-48.smt2                                                                       |  30.177s |1301.0MiB|
|n7139-prp-27-50.smt2                                                                       |  30.172s |1298.0MiB|
|n7424-prp-15-48.smt2                                                                       |  30.154s |1296.0MiB|
|n7402-prp-11-46.smt2                                                                       |  30.169s |1287.0MiB|
|n7412-prp-13-46.smt2                                                                       |  30.179s |1285.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02-treeWeight-570-8leaves.smt2                                                              |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|064-incremental_scheduling-15092-0.smt2                                                     |  11.713s  |  11.713s  |   0.000s  | 0.0%|
|07-treeWeight-569-8leaves.smt2                                                              |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|10-30.slack.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|14-treeWeight-537-8leaves.smt2                                                              |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|140-incremental_scheduling-18576-0.smt2                                                     |   1.990s  |   1.990s  |   0.000s  | 0.0%|
|15-20.smt2                                                                                  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|15-5.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|16.lp.smt2                                                                                  |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|18.lp.smt2                                                                                  |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|182-incremental_scheduling-17280-0.smt2                                                     |   1.157s  |   1.157s  |   0.000s  | 0.0%|
|19-treeWeight-772-8leaves.smt2                                                              |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|20-10.smt2                                                                                  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|20-11.slack.smt2                                                                            |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|20-12.slack.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|20-12.smt2                                                                                  |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|20-14.smt2                                                                                  |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|20-17.smt2                                                                                  |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|20-4.slack.smt2                                                                             |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|20-7.slack.smt2                                                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|20-9.slack.smt2                                                                             |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|21.lp.smt2                                                                                  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|22-treeWeight-641-8leaves.smt2                                                              |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|22.lp.smt2                                                                                  |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|23-treeWeight-542-8leaves.smt2                                                              |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|24.lp.smt2                                                                                  |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|25-11.smt2                                                                                  |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|25-14.slack.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|25-15.slack.smt2                                                                            |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|25-15.smt2                                                                                  |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|25-17.smt2                                                                                  |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|25-19.slack.smt2                                                                            |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|25-2.smt2                                                                                   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|25-23.slack.smt2                                                                            |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|25-24.slack.smt2                                                                            |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|25-25.smt2                                                                                  |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|25-27.smt2                                                                                  |   1.587s  |   1.587s  |   0.000s  | 0.0%|
|25-29.slack.smt2                                                                            |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|25-7.slack.smt2                                                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|25-treeWeight-539-8leaves.smt2                                                              |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|25.lp.smt2                                                                                  |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|26-treeWeight-528-8leaves.smt2                                                              |   0.559s  |   0.559s  |   0.000s  | 0.0%|
|26.lp.smt2                                                                                  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|30-11.slack.smt2                                                                            |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|30-16.slack.smt2                                                                            |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|30-25.slack.smt2                                                                            |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|30-35.slack.smt2                                                                            |   1.064s  |   1.064s  |   0.000s  | 0.0%|
|30_30_18_15_sat.smt2                                                                        |   1.954s  |   1.954s  |   0.000s  | 0.0%|
|30_30_18_8_sat.smt2                                                                         |   1.113s  |   1.113s  |   0.000s  | 0.0%|
|35-10.slack.smt2                                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|35-18.slack.smt2                                                                            |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|35-19.smt2                                                                                  |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|35-20.smt2                                                                                  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|35-22.smt2                                                                                  |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|35-25.smt2                                                                                  |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|35-32.slack.smt2                                                                            |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|40-13.slack.smt2                                                                            |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|40-14.smt2                                                                                  |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|40-18.slack.smt2                                                                            |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|40-20.slack.smt2                                                                            |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|40-22.slack.smt2                                                                            |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|40-25.slack.smt2                                                                            |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|40-4.slack.smt2                                                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|40-5.slack.smt2                                                                             |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|40_40_78_12_sat.smt2                                                                        |   1.000s  |   1.000s  |   0.000s  | 0.0%|
|45-1.slack.smt2                                                                             |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|45-19.slack.smt2                                                                            |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|45-19.smt2                                                                                  |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|45-29.slack.smt2                                                                            |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|45-3.slack.smt2                                                                             |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|45-30.smt2                                                                                  |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|45-32.slack.smt2                                                                            |   0.789s  |   0.789s  |   0.000s  | 0.0%|
|45-5.slack.smt2                                                                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|45-8.slack.smt2                                                                             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|Example_13.txt.smt2                                                                         |   3.110s  |   3.110s  |   0.000s  | 0.0%|
|Example_7.txt.smt2                                                                          |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|Example_9.txt.smt2                                                                          |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|FISCHER1-1-fair.smt2                                                                        |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|FISCHER10-11-fair.smt2                                                                      |   1.982s  |   1.982s  |   0.000s  | 0.0%|
|FISCHER11-9-fair.smt2                                                                       |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|FISCHER2-5-fair.smt2                                                                        |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|FISCHER3-1-fair.smt2                                                                        |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|FISCHER4-6-fair.smt2                                                                        |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|FISCHER4-8-fair.smt2                                                                        |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|FISCHER4-9-fair.smt2                                                                        |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|FISCHER5-8-fair.smt2                                                                        |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|FISCHER8-5-fair.smt2                                                                        |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|FISCHER9-4-fair.smt2                                                                        |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|FISCHER9-5-fair.smt2                                                                        |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|MULTIPLIER_11.msat.smt2                                                                     |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|MULTIPLIER_32.msat.smt2                                                                     |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|MULTIPLIER_9.msat.smt2                                                                      |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|MULTIPLIER_PRIME_11.msat.smt2                                                               |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|MULTIPLIER_PRIME_13.msat.smt2                                                               |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|MULTIPLIER_PRIME_64.msat.smt2                                                               |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|MULTIPLIER_PRIME_8.msat.smt2                                                                |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_10.msat.smt2                                                         |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_13.msat.smt2                                                         |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_14.msat.smt2                                                         |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_3.msat.smt2                                                          |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_4.msat.smt2                                                          |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|Sz128_2823.smt2                                                                             |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|Sz256_6616.smt2                                                                             |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|Sz32_456.smt2                                                                               |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|benchmark04_conjunctive-O0.smt2                                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|bignum_lia1.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|c100_problem__002.smt2.slack.smt2                                                           |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|c10_problem__003.smt2.slack.smt2                                                            |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|c10_problem__005.smt2.slack.smt2                                                            |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|c10_problem__006.smt2.slack.smt2                                                            |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|c30_problem__002.smt2.slack.smt2                                                            |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|c30_problem__005.smt2.slack.smt2                                                            |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|c70_problem__003.smt2.slack.smt2                                                            |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|c80_problem__003.smt2.slack.smt2                                                            |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|c80_problem__004.smt2.slack.smt2                                                            |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|constraint-221609.smt2                                                                      |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|constraint-285271.smt2                                                                      |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|constraint-319990.smt2                                                                      |  30.103s  |  30.103s  |   0.000s  | 0.0%|
|constraint-321761.smt2                                                                      |  30.072s  |  30.072s  |   0.000s  | 0.0%|
|constraint-357303.smt2                                                                      |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|constraint-373262.smt2                                                                      |  30.100s  |  30.100s  |   0.000s  | 0.0%|
|constraint-394532.smt2                                                                      |  30.127s  |  30.127s  |   0.000s  | 0.0%|
|constraint-478122.smt2                                                                      |  30.174s  |  30.174s  |   0.000s  | 0.0%|
|constraint-479884.smt2                                                                      |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|constraint-495717.smt2                                                                      |  30.171s  |  30.171s  |   0.000s  | 0.0%|
|constraint-496324.smt2                                                                      |  30.143s  |  30.143s  |   0.000s  | 0.0%|
|constraint-496502.smt2                                                                      |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|constraint-506600.smt2                                                                      |  30.139s  |  30.139s  |   0.000s  | 0.0%|
|constraint-515686.smt2                                                                      |   1.969s  |   1.969s  |   0.000s  | 0.0%|
|constraint-551279.smt2                                                                      |  30.167s  |  30.167s  |   0.000s  | 0.0%|
|constraint-579281.smt2                                                                      |  30.132s  |  30.132s  |   0.000s  | 0.0%|
|constraint-603294.smt2                                                                      |  30.142s  |  30.142s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1182.smt2                                                             |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1206.smt2                                                             |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1408.smt2                                                             |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1410.smt2                                                             |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1412.smt2                                                             |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1413.smt2                                                             |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1421.smt2                                                             |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1422.smt2                                                             |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1423.smt2                                                             |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1426.smt2                                                             |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1432.smt2                                                             |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1439.smt2                                                             |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1441.smt2                                                             |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1442.smt2                                                             |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1444.smt2                                                             |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1446.smt2                                                             |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1447.smt2                                                             |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1451.smt2                                                             |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1454.smt2                                                             |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1460.smt2                                                             |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1463.smt2                                                             |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1472.smt2                                                             |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1476.smt2                                                             |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1486.smt2                                                             |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1491.smt2                                                             |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1498.smt2                                                             |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1503.smt2                                                             |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1516.smt2                                                             |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1518.smt2                                                             |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1524.smt2                                                             |   0.494s  |   0.494s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1526.smt2                                                             |   0.524s  |   0.524s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1532.smt2                                                             |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1540.smt2                                                             |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1546.smt2                                                             |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1547.smt2                                                             |   1.822s  |   1.822s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1556.smt2                                                             |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1557.smt2                                                             |   1.324s  |   1.324s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1559.smt2                                                             |   0.562s  |   0.562s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1560.smt2                                                             |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1562.smt2                                                             |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1565.smt2                                                             |   0.739s  |   0.739s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1572.smt2                                                             |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1580.smt2                                                             |   0.593s  |   0.593s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1581.smt2                                                             |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1582.smt2                                                             |   0.568s  |   0.568s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1583.smt2                                                             |   0.530s  |   0.530s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1589.smt2                                                             |   0.676s  |   0.676s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1591.smt2                                                             |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1592.smt2                                                             |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1593.smt2                                                             |   0.582s  |   0.582s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1596.smt2                                                             |   0.620s  |   0.620s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1598.smt2                                                             |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1600.smt2                                                             |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1605.smt2                                                             |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1606.smt2                                                             |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1608.smt2                                                             |   0.671s  |   0.671s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1609.smt2                                                             |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1614.smt2                                                             |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|cut_lemma_02_007.smt2.slack.smt2                                                            |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|cut_lemma_02_015.smt2.slack.smt2                                                            |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|cut_lemma_02_016.smt2.slack.smt2                                                            |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|cut_lemma_03_009.smt2                                                                       |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|cut_lemma_03_018.smt2                                                                       |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|ex10000_2400_100.smt2                                                                       |   0.939s  |   0.939s  |   0.000s  | 0.0%|
|ex10000_2600_100.smt2                                                                       |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|ex10400_2600_100.smt2                                                                       |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|ex10500_2600_100.smt2                                                                       |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|ex10700_2600_100.smt2                                                                       |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|ex10800_2600_100.smt2                                                                       |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|ex11300_2600_100.smt2                                                                       |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|ex11500_2600_100.smt2                                                                       |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|ex12200_2600_100.smt2                                                                       |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|ex12300_2600_100.smt2                                                                       |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|ex12600_2600_100.smt2                                                                       |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|ex13200_2600_100.smt2                                                                       |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|ex13500_2600_100.smt2                                                                       |  21.136s  |  21.136s  |   0.000s  | 0.0%|
|ex13800_2600_100.smt2                                                                       |  25.257s  |  25.257s  |   0.000s  | 0.0%|
|ex13900_2600_100.smt2                                                                       |   6.250s  |   6.250s  |   0.000s  | 0.0%|
|ex14400_2600_100.smt2                                                                       |   4.292s  |   4.292s  |   0.000s  | 0.0%|
|ex14600_2600_100.smt2                                                                       |   8.288s  |   8.288s  |   0.000s  | 0.0%|
|ex14700_2600_100.smt2                                                                       |  10.682s  |  10.682s  |   0.000s  | 0.0%|
|ex15200_2600_100.smt2                                                                       |   4.776s  |   4.776s  |   0.000s  | 0.0%|
|ex15400_2600_100.smt2                                                                       |   3.970s  |   3.970s  |   0.000s  | 0.0%|
|ex15800_2600_100.smt2                                                                       |   3.327s  |   3.327s  |   0.000s  | 0.0%|
|ex16000_2600_100.smt2                                                                       |   4.125s  |   4.125s  |   0.000s  | 0.0%|
|ex16100_2600_100.smt2                                                                       |   3.609s  |   3.609s  |   0.000s  | 0.0%|
|ex16300_2600_100.smt2                                                                       |   4.166s  |   4.166s  |   0.000s  | 0.0%|
|ex16400_2600_100.smt2                                                                       |   2.549s  |   2.549s  |   0.000s  | 0.0%|
|ex16600_2600_100.smt2                                                                       |   2.384s  |   2.384s  |   0.000s  | 0.0%|
|ex16700_2600_100.smt2                                                                       |   3.152s  |   3.152s  |   0.000s  | 0.0%|
|ex16900_2600_100.smt2                                                                       |   2.812s  |   2.812s  |   0.000s  | 0.0%|
|ex17000_2600_100.smt2                                                                       |   3.119s  |   3.119s  |   0.000s  | 0.0%|
|ex17100_2600_100.smt2                                                                       |   2.569s  |   2.569s  |   0.000s  | 0.0%|
|ex17200_2600_100.smt2                                                                       |   3.901s  |   3.901s  |   0.000s  | 0.0%|
|ex17400_2600_100.smt2                                                                       |   3.209s  |   3.209s  |   0.000s  | 0.0%|
|ex17800_2600_100.smt2                                                                       |   2.660s  |   2.660s  |   0.000s  | 0.0%|
|ex18100_2600_100.smt2                                                                       |   2.574s  |   2.574s  |   0.000s  | 0.0%|
|ex18200_2600_100.smt2                                                                       |   3.019s  |   3.019s  |   0.000s  | 0.0%|
|ex18300_2600_100.smt2                                                                       |   2.835s  |   2.835s  |   0.000s  | 0.0%|
|ex18400_2600_100.smt2                                                                       |   2.127s  |   2.127s  |   0.000s  | 0.0%|
|ex18500_2600_100.smt2                                                                       |   3.324s  |   3.324s  |   0.000s  | 0.0%|
|ex18600_2600_100.smt2                                                                       |   2.671s  |   2.671s  |   0.000s  | 0.0%|
|ex18700_2600_100.smt2                                                                       |   3.411s  |   3.411s  |   0.000s  | 0.0%|
|ex19500_2600_100.smt2                                                                       |   3.543s  |   3.543s  |   0.000s  | 0.0%|
|ex19600_2600_100.smt2                                                                       |   2.441s  |   2.441s  |   0.000s  | 0.0%|
|ex20200_2600_100.smt2                                                                       |   3.312s  |   3.312s  |   0.000s  | 0.0%|
|ex20300_2600_100.smt2                                                                       |   2.624s  |   2.624s  |   0.000s  | 0.0%|
|ex20400_2600_100.smt2                                                                       |   2.708s  |   2.708s  |   0.000s  | 0.0%|
|ex20900_2600_100.smt2                                                                       |   3.456s  |   3.456s  |   0.000s  | 0.0%|
|ex21200_2600_100.smt2                                                                       |   2.207s  |   2.207s  |   0.000s  | 0.0%|
|ex22100_2600_100.smt2                                                                       |   2.939s  |   2.939s  |   0.000s  | 0.0%|
|ex22300_2600_100.smt2                                                                       |   1.855s  |   1.855s  |   0.000s  | 0.0%|
|ex22600_2600_100.smt2                                                                       |   2.557s  |   2.557s  |   0.000s  | 0.0%|
|ex22700_2600_100.smt2                                                                       |   3.379s  |   3.379s  |   0.000s  | 0.0%|
|ex23700_2600_100.smt2                                                                       |   2.943s  |   2.943s  |   0.000s  | 0.0%|
|ex24000_2600_100.smt2                                                                       |   1.912s  |   1.912s  |   0.000s  | 0.0%|
|ex24200_2600_100.smt2                                                                       |   3.439s  |   3.439s  |   0.000s  | 0.0%|
|ex24400_2600_100.smt2                                                                       |   2.897s  |   2.897s  |   0.000s  | 0.0%|
|ex24500_2600_100.smt2                                                                       |   2.890s  |   2.890s  |   0.000s  | 0.0%|
|ex24800_2600_100.smt2                                                                       |   2.697s  |   2.697s  |   0.000s  | 0.0%|
|ex25000_2600_100.smt2                                                                       |   1.935s  |   1.935s  |   0.000s  | 0.0%|
|ex25300_2600_100.smt2                                                                       |   3.217s  |   3.217s  |   0.000s  | 0.0%|
|ex26000_2600_100.smt2                                                                       |   2.774s  |   2.774s  |   0.000s  | 0.0%|
|ex26200_2600_100.smt2                                                                       |   2.797s  |   2.797s  |   0.000s  | 0.0%|
|ex26300_2600_100.smt2                                                                       |   2.909s  |   2.909s  |   0.000s  | 0.0%|
|ex26400_2600_100.smt2                                                                       |   3.023s  |   3.023s  |   0.000s  | 0.0%|
|ex26500_2600_100.smt2                                                                       |   2.341s  |   2.341s  |   0.000s  | 0.0%|
|ex27000_2600_100.smt2                                                                       |   3.608s  |   3.608s  |   0.000s  | 0.0%|
|ex28300_2600_100.smt2                                                                       |   3.670s  |   3.670s  |   0.000s  | 0.0%|
|ex28600_2600_100.smt2                                                                       |   2.539s  |   2.539s  |   0.000s  | 0.0%|
|ex29200_2600_100.smt2                                                                       |   2.287s  |   2.287s  |   0.000s  | 0.0%|
|ex29600_2600_100.smt2                                                                       |   2.332s  |   2.332s  |   0.000s  | 0.0%|
|ex29700_2600_100.smt2                                                                       |   2.367s  |   2.367s  |   0.000s  | 0.0%|
|ex29900_2600_100.smt2                                                                       |   3.149s  |   3.149s  |   0.000s  | 0.0%|
|ex4920_2400_100.smt2                                                                        |   2.284s  |   2.284s  |   0.000s  | 0.0%|
|ex4960_2400_100.smt2                                                                        |   7.435s  |   7.435s  |   0.000s  | 0.0%|
|ex5000_2400_100.smt2                                                                        |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|ex5000_2600_100.smt2                                                                        |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|ex5020_2400_100.smt2                                                                        |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|ex5040_2400_100.smt2                                                                        |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|ex5060_2400_100.smt2                                                                        |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|ex5080_2400_100.smt2                                                                        |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|ex5100_2600_100.smt2                                                                        |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|ex5120_2400_100.smt2                                                                        |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|ex5180_2400_100.smt2                                                                        |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|ex5200_2400_100.smt2                                                                        |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|ex5240_2400_100.smt2                                                                        |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|ex5360_2400_100.smt2                                                                        |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|ex5540_2400_100.smt2                                                                        |  10.382s  |  10.382s  |   0.000s  | 0.0%|
|ex5580_2400_100.smt2                                                                        |  17.969s  |  17.969s  |   0.000s  | 0.0%|
|ex5600_2400_100.smt2                                                                        |  11.984s  |  11.984s  |   0.000s  | 0.0%|
|ex5600_2600_100.smt2                                                                        |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|ex5620_2400_100.smt2                                                                        |  27.202s  |  27.202s  |   0.000s  | 0.0%|
|ex5640_2400_100.smt2                                                                        |  19.875s  |  19.875s  |   0.000s  | 0.0%|
|ex5660_2400_100.smt2                                                                        |  17.791s  |  17.791s  |   0.000s  | 0.0%|
|ex5700_2400_100.smt2                                                                        |  14.437s  |  14.437s  |   0.000s  | 0.0%|
|ex5700_2600_100.smt2                                                                        |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|ex5720_2400_100.smt2                                                                        |   9.387s  |   9.387s  |   0.000s  | 0.0%|
|ex5780_2400_100.smt2                                                                        |   9.964s  |   9.964s  |   0.000s  | 0.0%|
|ex5800_2400_100.smt2                                                                        |   4.048s  |   4.048s  |   0.000s  | 0.0%|
|ex5800_2600_100.smt2                                                                        |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|ex5840_2400_100.smt2                                                                        |   4.824s  |   4.824s  |   0.000s  | 0.0%|
|ex5860_2400_100.smt2                                                                        |   4.634s  |   4.634s  |   0.000s  | 0.0%|
|ex5900_2600_100.smt2                                                                        |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|ex5920_2400_100.smt2                                                                        |   8.537s  |   8.537s  |   0.000s  | 0.0%|
|ex5960_2400_100.smt2                                                                        |   5.395s  |   5.395s  |   0.000s  | 0.0%|
|ex6000_2600_100.smt2                                                                        |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|ex6040_2400_100.smt2                                                                        |   3.258s  |   3.258s  |   0.000s  | 0.0%|
|ex6060_2400_100.smt2                                                                        |   4.998s  |   4.998s  |   0.000s  | 0.0%|
|ex6100_2600_100.smt2                                                                        |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|ex6120_2400_100.smt2                                                                        |   3.201s  |   3.201s  |   0.000s  | 0.0%|
|ex6160_2400_100.smt2                                                                        |   2.701s  |   2.701s  |   0.000s  | 0.0%|
|ex6180_2400_100.smt2                                                                        |   3.466s  |   3.466s  |   0.000s  | 0.0%|
|ex6260_2400_100.smt2                                                                        |   4.539s  |   4.539s  |   0.000s  | 0.0%|
|ex6300_2600_100.smt2                                                                        |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|ex6440_2400_100.smt2                                                                        |   4.178s  |   4.178s  |   0.000s  | 0.0%|
|ex6460_2400_100.smt2                                                                        |   2.771s  |   2.771s  |   0.000s  | 0.0%|
|ex6520_2400_100.smt2                                                                        |   1.607s  |   1.607s  |   0.000s  | 0.0%|
|ex6560_2400_100.smt2                                                                        |   3.660s  |   3.660s  |   0.000s  | 0.0%|
|ex6600_2400_100.smt2                                                                        |   3.022s  |   3.022s  |   0.000s  | 0.0%|
|ex6640_2400_100.smt2                                                                        |   1.784s  |   1.784s  |   0.000s  | 0.0%|
|ex6680_2400_100.smt2                                                                        |   3.863s  |   3.863s  |   0.000s  | 0.0%|
|ex6720_2400_100.smt2                                                                        |   2.860s  |   2.860s  |   0.000s  | 0.0%|
|ex6760_2400_100.smt2                                                                        |   1.878s  |   1.878s  |   0.000s  | 0.0%|
|ex6780_2400_100.smt2                                                                        |   1.860s  |   1.860s  |   0.000s  | 0.0%|
|ex6800_2400_100.smt2                                                                        |   3.306s  |   3.306s  |   0.000s  | 0.0%|
|ex6820_2400_100.smt2                                                                        |   3.602s  |   3.602s  |   0.000s  | 0.0%|
|ex6840_2400_100.smt2                                                                        |   2.777s  |   2.777s  |   0.000s  | 0.0%|
|ex6860_2400_100.smt2                                                                        |   2.400s  |   2.400s  |   0.000s  | 0.0%|
|ex6900_2600_100.smt2                                                                        |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|ex6940_2400_100.smt2                                                                        |   1.582s  |   1.582s  |   0.000s  | 0.0%|
|ex7000_2400_100.smt2                                                                        |   1.483s  |   1.483s  |   0.000s  | 0.0%|
|ex7020_2400_100.smt2                                                                        |   1.530s  |   1.530s  |   0.000s  | 0.0%|
|ex7080_2400_100.smt2                                                                        |   1.391s  |   1.391s  |   0.000s  | 0.0%|
|ex7140_2400_100.smt2                                                                        |   2.569s  |   2.569s  |   0.000s  | 0.0%|
|ex7200_2600_100.smt2                                                                        |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|ex7220_2400_100.smt2                                                                        |   1.389s  |   1.389s  |   0.000s  | 0.0%|
|ex7240_2400_100.smt2                                                                        |   2.138s  |   2.138s  |   0.000s  | 0.0%|
|ex7280_2400_100.smt2                                                                        |   2.860s  |   2.860s  |   0.000s  | 0.0%|
|ex7360_2400_100.smt2                                                                        |   1.446s  |   1.446s  |   0.000s  | 0.0%|
|ex7500_2600_100.smt2                                                                        |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|ex7580_2400_100.smt2                                                                        |   1.181s  |   1.181s  |   0.000s  | 0.0%|
|ex7600_2400_100.smt2                                                                        |   1.545s  |   1.545s  |   0.000s  | 0.0%|
|ex7600_2600_100.smt2                                                                        |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|ex7620_2400_100.smt2                                                                        |   1.177s  |   1.177s  |   0.000s  | 0.0%|
|ex7640_2400_100.smt2                                                                        |   1.194s  |   1.194s  |   0.000s  | 0.0%|
|ex7660_2400_100.smt2                                                                        |   1.340s  |   1.340s  |   0.000s  | 0.0%|
|ex7680_2400_100.smt2                                                                        |   1.493s  |   1.493s  |   0.000s  | 0.0%|
|ex7700_2400_100.smt2                                                                        |   1.125s  |   1.125s  |   0.000s  | 0.0%|
|ex7700_2600_100.smt2                                                                        |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|ex7780_2400_100.smt2                                                                        |   1.500s  |   1.500s  |   0.000s  | 0.0%|
|ex7800_2400_100.smt2                                                                        |   1.356s  |   1.356s  |   0.000s  | 0.0%|
|ex7840_2400_100.smt2                                                                        |   1.274s  |   1.274s  |   0.000s  | 0.0%|
|ex7860_2400_100.smt2                                                                        |   1.358s  |   1.358s  |   0.000s  | 0.0%|
|ex7880_2400_100.smt2                                                                        |   1.326s  |   1.326s  |   0.000s  | 0.0%|
|ex7900_2400_100.smt2                                                                        |   1.409s  |   1.409s  |   0.000s  | 0.0%|
|ex7920_2400_100.smt2                                                                        |   1.378s  |   1.378s  |   0.000s  | 0.0%|
|ex7940_2400_100.smt2                                                                        |   1.161s  |   1.161s  |   0.000s  | 0.0%|
|ex8000_2400_100.smt2                                                                        |   1.032s  |   1.032s  |   0.000s  | 0.0%|
|ex8020_2400_100.smt2                                                                        |   1.511s  |   1.511s  |   0.000s  | 0.0%|
|ex8040_2400_100.smt2                                                                        |   1.490s  |   1.490s  |   0.000s  | 0.0%|
|ex8060_2400_100.smt2                                                                        |   1.509s  |   1.509s  |   0.000s  | 0.0%|
|ex8080_2400_100.smt2                                                                        |   1.111s  |   1.111s  |   0.000s  | 0.0%|
|ex8120_2400_100.smt2                                                                        |   1.262s  |   1.262s  |   0.000s  | 0.0%|
|ex8140_2400_100.smt2                                                                        |   1.342s  |   1.342s  |   0.000s  | 0.0%|
|ex8180_2400_100.smt2                                                                        |   1.467s  |   1.467s  |   0.000s  | 0.0%|
|ex8260_2400_100.smt2                                                                        |   1.466s  |   1.466s  |   0.000s  | 0.0%|
|ex8300_2400_100.smt2                                                                        |   1.270s  |   1.270s  |   0.000s  | 0.0%|
|ex8300_2600_100.smt2                                                                        |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|ex8320_2400_100.smt2                                                                        |   1.306s  |   1.306s  |   0.000s  | 0.0%|
|ex8360_2400_100.smt2                                                                        |   1.323s  |   1.323s  |   0.000s  | 0.0%|
|ex8440_2400_100.smt2                                                                        |   1.058s  |   1.058s  |   0.000s  | 0.0%|
|ex8460_2400_100.smt2                                                                        |   1.675s  |   1.675s  |   0.000s  | 0.0%|
|ex8480_2400_100.smt2                                                                        |   1.302s  |   1.302s  |   0.000s  | 0.0%|
|ex8520_2400_100.smt2                                                                        |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|ex8580_2400_100.smt2                                                                        |   1.689s  |   1.689s  |   0.000s  | 0.0%|
|ex8600_2600_100.smt2                                                                        |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|ex8700_2400_100.smt2                                                                        |   0.942s  |   0.942s  |   0.000s  | 0.0%|
|ex8700_2600_100.smt2                                                                        |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|ex8720_2400_100.smt2                                                                        |   1.014s  |   1.014s  |   0.000s  | 0.0%|
|ex8740_2400_100.smt2                                                                        |   1.021s  |   1.021s  |   0.000s  | 0.0%|
|ex8800_2600_100.smt2                                                                        |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|ex8860_2400_100.smt2                                                                        |   1.194s  |   1.194s  |   0.000s  | 0.0%|
|ex8900_2600_100.smt2                                                                        |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|ex8940_2400_100.smt2                                                                        |   1.630s  |   1.630s  |   0.000s  | 0.0%|
|ex8960_2400_100.smt2                                                                        |   1.988s  |   1.988s  |   0.000s  | 0.0%|
|ex9000_2600_100.smt2                                                                        |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|ex9020_2400_100.smt2                                                                        |   1.280s  |   1.280s  |   0.000s  | 0.0%|
|ex9080_2400_100.smt2                                                                        |   1.269s  |   1.269s  |   0.000s  | 0.0%|
|ex9100_2600_100.smt2                                                                        |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|ex9120_2400_100.smt2                                                                        |   1.295s  |   1.295s  |   0.000s  | 0.0%|
|ex9140_2400_100.smt2                                                                        |   1.237s  |   1.237s  |   0.000s  | 0.0%|
|ex9200_2400_100.smt2                                                                        |   1.087s  |   1.087s  |   0.000s  | 0.0%|
|ex9200_2600_100.smt2                                                                        |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|ex9240_2400_100.smt2                                                                        |   1.110s  |   1.110s  |   0.000s  | 0.0%|
|ex9300_2400_100.smt2                                                                        |   1.063s  |   1.063s  |   0.000s  | 0.0%|
|ex9300_2600_100.smt2                                                                        |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|ex9340_2400_100.smt2                                                                        |   1.267s  |   1.267s  |   0.000s  | 0.0%|
|ex9360_2400_100.smt2                                                                        |   1.079s  |   1.079s  |   0.000s  | 0.0%|
|ex9440_2400_100.smt2                                                                        |   0.848s  |   0.848s  |   0.000s  | 0.0%|
|ex9460_2400_100.smt2                                                                        |   1.132s  |   1.132s  |   0.000s  | 0.0%|
|ex9500_2600_100.smt2                                                                        |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|ex9540_2400_100.smt2                                                                        |   1.010s  |   1.010s  |   0.000s  | 0.0%|
|ex9560_2400_100.smt2                                                                        |   0.964s  |   0.964s  |   0.000s  | 0.0%|
|ex9580_2400_100.smt2                                                                        |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|ex9600_2600_100.smt2                                                                        |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|ex9660_2400_100.smt2                                                                        |   0.885s  |   0.885s  |   0.000s  | 0.0%|
|ex9680_2400_100.smt2                                                                        |   0.880s  |   0.880s  |   0.000s  | 0.0%|
|ex9700_2400_100.smt2                                                                        |   0.887s  |   0.887s  |   0.000s  | 0.0%|
|ex9700_2600_100.smt2                                                                        |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|ex9720_2400_100.smt2                                                                        |   0.887s  |   0.887s  |   0.000s  | 0.0%|
|ex9740_2400_100.smt2                                                                        |   0.850s  |   0.850s  |   0.000s  | 0.0%|
|ex9780_2400_100.smt2                                                                        |   0.778s  |   0.778s  |   0.000s  | 0.0%|
|ex9800_2400_100.smt2                                                                        |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|ex9820_2400_100.smt2                                                                        |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|ex9840_2400_100.smt2                                                                        |   0.783s  |   0.783s  |   0.000s  | 0.0%|
|ex9860_2400_100.smt2                                                                        |   0.773s  |   0.773s  |   0.000s  | 0.0%|
|ex9900_2400_100.smt2                                                                        |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|ex9920_2400_100.smt2                                                                        |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|ex9960_2400_100.smt2                                                                        |   0.986s  |   0.986s  |   0.000s  | 0.0%|
|int_incompleteness1.smt2                                                                    |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n10-cut_lemma_01_005.smt2.slack.smt2                                                        |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|n100-unbd-sage16.smt2                                                                       |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|n103-unbd-sage19.smt2                                                                       |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|n104-unbd-sage2.smt2                                                                        |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|n106-unbd-sage21.smt2                                                                       |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|n107-unbd-sage22.smt2                                                                       |  30.029s  |  30.029s  |   0.000s  | 0.0%|
|n108-unbd-sage23.smt2                                                                       |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|n111-unbd-sage4.smt2                                                                        |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|n113-unbd-sage6.smt2                                                                        |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|n115-unbd-sage8.smt2                                                                        |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|n116-unbd-sage9.smt2                                                                        |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|n118-unbd-sage1.smt2                                                                        |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|n123-unbd-sage14.smt2                                                                       |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|n125-unbd-sage16.smt2                                                                       |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|n128-unbd-sage19.smt2                                                                       |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|n129-unbd-sage2.smt2                                                                        |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|n1297-RC-02.smt2                                                                            |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|n1299-RC-04.smt2                                                                            |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|n1300-RC-05.smt2                                                                            |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|n1303-RC-08.smt2                                                                            |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|n1312-RF-01.smt2                                                                            |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|n1319-RF-08.smt2                                                                            |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|n133-unbd-sage23.smt2                                                                       |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|n1342-RC-15.smt2                                                                            |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|n1344-RF-01.smt2                                                                            |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|n135-unbd-sage3.smt2                                                                        |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|n1358-RF-15.smt2                                                                            |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|n136-unbd-sage4.smt2                                                                        |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|n1366-RC-07.smt2                                                                            |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|n1376-RF-01.smt2                                                                            |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|n138-unbd-sage6.smt2                                                                        |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|n1380-RF-05.smt2                                                                            |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|n1389-RF-14.smt2                                                                            |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|n1391-RC-00.smt2                                                                            |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|n1394-RC-03.smt2                                                                            |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|n1396-RC-05.smt2                                                                            |   0.495s  |   0.495s  |   0.000s  | 0.0%|
|n1399-RC-08.smt2                                                                            |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|n14-cut_lemma_01_009.smt2.slack.smt2                                                        |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|n1405-RC-14.smt2                                                                            |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|n1425-RC-02.smt2                                                                            |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|n1441-RF-02.smt2                                                                            |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|n1454-RF-15.smt2                                                                            |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|n1456-RC-01.smt2                                                                            |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|n1458-RC-03.smt2                                                                            |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|n1463-RC-08.smt2                                                                            |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|n1467-RC-12.smt2                                                                            |   0.532s  |   0.532s  |   0.000s  | 0.0%|
|n1491-RC-04.smt2                                                                            |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|n1495-RC-08.smt2                                                                            |   0.520s  |   0.520s  |   0.000s  | 0.0%|
|n1502-RC-15.smt2                                                                            |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|n1513-RF-10.smt2                                                                            |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|n1517-RF-14.smt2                                                                            |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|n1519-RC-00.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n1522-RC-03.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n1523-RC-04.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n1527-RC-08.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n1528-RC-09.smt2                                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|n1531-RC-12.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n1533-RC-14.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n1537-RF-02.smt2                                                                            |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|n1541-RF-06.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n1542-RF-07.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n1543-RF-08.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n1544-RF-09.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n1546-RF-11.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n1550-RF-15.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n1552-RC-01.smt2                                                                            |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|n1560-RC-09.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n1561-RC-10.smt2                                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|n1565-RC-14.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n1568-RF-01.smt2                                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|n1569-RF-02.smt2                                                                            |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|n1570-RF-03.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n1575-RF-08.smt2                                                                            |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|n1580-RF-13.smt2                                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|n1594-RC-11.smt2                                                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|n1599-RF-00.smt2                                                                            |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|n16-cut_lemma_01_011.smt2.slack.smt2                                                        |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|n1605-RF-06.smt2                                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|n1642-RF-11.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n1671-RF-08.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n17-cut_lemma_01_012.smt2.slack.smt2                                                        |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|n1714-RC-03.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n1715-RC-04.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n1719-RC-08.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n1724-RC-13.smt2                                                                            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|n1726-RC-15.smt2                                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|n1727-RF-00.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n1736-RF-11.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n1740-RC-00.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n1741-RC-01.smt2                                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|n1742-RC-02.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n1746-RC-06.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n1751-RC-11.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n1753-RC-14.smt2                                                                            |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|n1756-RF-01.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n1763-RF-08.smt2                                                                            |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|n1764-RF-09.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n1765-RF-10.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n1766-RF-11.smt2                                                                            |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|n1767-RF-12.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n1773-RC-02.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n1775-RC-04.smt2                                                                            |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|n1780-RC-09.smt2                                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|n1782-RC-11.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n1787-RF-00.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n1788-RF-01.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n1789-RF-02.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n1793-RF-06.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n1794-RF-07.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n1798-RF-11.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n1801-RF-15.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n1806-RC-04.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n1810-RC-08.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n1813-RC-11.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n1815-RC-13.smt2                                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|n1816-RC-14.smt2                                                                            |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|n1818-RF-00.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n1820-RF-02.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n1825-RF-07.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n1836-RC-03.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n1838-RC-05.smt2                                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|n1839-RC-06.smt2                                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|n1840-RC-07.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n1841-RC-08.smt2                                                                            |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|n1842-RC-09.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n1843-RC-10.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n1845-RC-12.smt2                                                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|n1848-RC-15.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n1849-RF-00.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n1852-RF-03.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n1854-RF-07.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n1856-RF-10.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n1857-RF-11.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n1858-RF-12.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n1862-RC-02.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n1863-RC-03.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n1864-RC-04.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n1865-RC-05.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n1869-RC-09.smt2                                                                            |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|n1875-RC-15.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n1882-RF-07.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n2030-RC-14.smt2                                                                            |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|n2039-RF-07.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n2066-RF-02.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n2098-RF-03.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n21-cut_lemma_02_002.smt2.slack.smt2                                                        |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|n2129-RF-03.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n2179-RC-10.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n2187-RF-02.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n22-cut_lemma_02_003.smt2.slack.smt2                                                        |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|n2201-RC-00.smt2                                                                            |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|n2213-RC-12.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n2216-RC-15.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n2252-RF-03.smt2                                                                            |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|n2284-RF-04.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n23-cut_lemma_02_004.smt2.slack.smt2                                                        |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|n2311-RF-00.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n2352-RF-09.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n24-cut_lemma_02_005.smt2.slack.smt2                                                        |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|n2454-RC-01.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n2465-RC-12.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n25-cut_lemma_02_006.smt2.slack.smt2                                                        |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|n2520-RC-12.smt2                                                                            |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|n2526-RF-02.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n2602-RC-02.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n264-RC-06.smt2                                                                             |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|n265-RC-07.smt2                                                                             |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|n27-cut_lemma_02_009.smt2.slack.smt2                                                        |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|n2701-RC-06.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n2706-RC-11.smt2                                                                            |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|n2733-RC-08.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n2734-RC-09.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n277-RF-03.smt2                                                                             |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|n2795-RC-06.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n28-cut_lemma_02_010.smt2.slack.smt2                                                        |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|n2808-RF-03.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n2811-RF-06.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n283-RF-09.smt2                                                                             |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|n2907-RF-06.smt2                                                                            |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|n2951-RC-02.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n2960-RC-11.smt2                                                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|n2963-RC-14.smt2                                                                            |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|n2964-RC-15.smt2                                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|n2965-RF-00.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n2973-RF-08.smt2                                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|n2983-RC-02.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n2987-RC-06.smt2                                                                            |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|n2988-RC-07.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n2990-RC-09.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n2997-RF-00.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n3000-RF-03.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n3009-RF-12.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n3017-RC-04.smt2                                                                            |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|n3021-RC-08.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n3022-RC-09.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n3027-RC-14.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n3044-RF-15.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n3055-RC-10.smt2                                                                            |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|n3069-RF-08.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n3070-RF-09.smt2                                                                            |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|n3080-RC-03.smt2                                                                            |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|n3084-RC-07.smt2                                                                            |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|n3090-RC-13.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n3091-RC-14.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n3099-RF-06.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n3100-RF-07.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n3102-RF-09.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n3118-RC-10.smt2                                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|n3122-RC-14.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n3128-RF-05.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n3136-RF-13.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n3145-RC-06.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n3151-RC-12.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n3154-RC-15.smt2                                                                            |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|n3155-RF-00.smt2                                                                            |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|n3159-RF-04.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n3164-RF-09.smt2                                                                            |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|n3165-RF-10.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n3170-RF-15.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n3171-RC-00.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n3176-RC-05.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n3195-RF-08.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n3197-RF-10.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n3205-RC-02.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n3207-RC-04.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n3212-RC-09.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n3218-RC-15.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n3235-RC-03.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n3259-RF-13.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n3262-RC-00.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n3265-RC-03.smt2                                                                            |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|n3277-RF-00.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n3286-RF-09.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n3288-RF-11.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n3289-RF-12.smt2                                                                            |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|n3292-RF-15.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n3293-RC-00.smt2                                                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|n3304-RC-11.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n3309-RF-00.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n3315-RF-06.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n3316-RF-07.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n3317-RF-08.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n3332-RC-08.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n3338-RC-14.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n3343-RF-03.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n3350-RF-10.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n3375-RF-04.smt2                                                                            |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|n3393-RC-06.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n34-cut_lemma_03_006.smt2.slack.smt2                                                        |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|n3404-RF-01.smt2                                                                            |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|n3409-RF-06.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n3419-RC-00.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n3424-RC-05.smt2                                                                            |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|n3425-RC-06.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n3428-RC-09.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n3430-RC-11.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n3432-RC-13.smt2                                                                            |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|n3437-RF-02.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n3457-RC-06.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n3459-RC-08.smt2                                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|n3463-RC-12.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n3465-RC-14.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n3476-RF-09.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n3483-RC-00.smt2                                                                            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|n3489-RC-06.smt2                                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|n3492-RC-09.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n3495-RC-12.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n3496-RC-13.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n3497-RC-14.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n3502-RF-03.smt2                                                                            |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|n3504-RF-05.smt2                                                                            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|n3509-RF-10.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n3512-RF-13.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n3516-RC-01.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n3520-RC-05.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n3534-RF-04.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n3545-RF-15.smt2                                                                            |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|n3547-RC-01.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n3551-RC-05.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n3557-RC-11.smt2                                                                            |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|n3559-RC-13.smt2                                                                            |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|n3560-RC-14.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n3575-RF-14.smt2                                                                            |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|n3583-RC-06.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n3584-RC-07.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n3593-RF-00.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n3603-RF-11.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n3605-RF-13.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n3612-RC-05.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n3626-RF-03.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n3635-RF-12.smt2                                                                            |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|n3639-RC-00.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n3644-RC-05.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n3649-RC-10.smt2                                                                            |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|n3650-RC-11.smt2                                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|n3651-RC-12.smt2                                                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|n3653-RC-14.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n3654-RC-15.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n3664-RF-10.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n3676-RC-07.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n3677-RC-08.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n3679-RC-10.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n3681-RC-12.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n3683-RC-14.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n3684-RC-15.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n3695-RF-10.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n3705-RC-04.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n3709-RC-08.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n3712-RC-11.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n3713-RC-12.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n3717-RF-01.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n3719-RF-03.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n3720-RF-04.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n3722-RF-06.smt2                                                                            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|n3723-RF-07.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n3724-RF-08.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n3725-RF-09.smt2                                                                            |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|n3732-RC-00.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n3733-RC-01.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n3734-RC-02.smt2                                                                            |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|n3738-RC-06.smt2                                                                            |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|n3739-RC-07.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n3744-RC-12.smt2                                                                            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|n3746-RC-14.smt2                                                                            |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|n3747-RC-15.smt2                                                                            |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|n3752-RF-04.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n3753-RF-05.smt2                                                                            |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|n3755-RF-07.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n3757-RF-09.smt2                                                                            |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|n3758-RF-10.smt2                                                                            |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|n3760-RF-12.smt2                                                                            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|n3775-RC-11.smt2                                                                            |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|n3783-RF-03.smt2                                                                            |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|n3789-RF-09.smt2                                                                            |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|n3792-RF-12.smt2                                                                            |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|n3863-RC-04.smt2                                                                            |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|n3918-RF-11.smt2                                                                            |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|n3919-RF-12.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n3922-RF-15.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n3927-RC-04.smt2                                                                            |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|n3929-RC-06.smt2                                                                            |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|n3946-RF-07.smt2                                                                            |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|n3959-RC-04.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n3976-RF-05.smt2                                                                            |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|n40-sat-b20.lp.smt2                                                                         |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|n40-sat-b5.lp.smt2                                                                          |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|n4021-RC-02.smt2                                                                            |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|n4039-RF-04.smt2                                                                            |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|n4065-RC-14.smt2                                                                            |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|n4081-RF-14.smt2                                                                            |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|n4083-RC-00.smt2                                                                            |   1.896s  |   1.896s  |   0.000s  | 0.0%|
|n4095-RC-12.smt2                                                                            |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|n4106-RF-07.smt2                                                                            |   1.598s  |   1.598s  |   0.000s  | 0.0%|
|n4108-RF-09.smt2                                                                            |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|n4123-RC-08.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n4127-RC-12.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n4128-RC-13.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n4130-RC-15.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n4135-RF-04.smt2                                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|n4137-RF-06.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n4138-RF-07.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n4139-RF-08.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n4140-RF-09.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n4141-RF-10.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n4148-RC-01.smt2                                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|n4151-RC-04.smt2                                                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|n4155-RC-08.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n4166-RF-03.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n4175-RF-13.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n4182-RC-04.smt2                                                                            |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|n4184-RC-06.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n4192-RC-15.smt2                                                                            |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|n4196-RF-03.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n42-unbd-sage0.smt2                                                                         |   7.980s  |   7.980s  |   0.000s  | 0.0%|
|n420-RC-02.smt2                                                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|n4202-RF-09.smt2                                                                            |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|n4209-RC-00.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n421-RC-03.smt2                                                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|n4215-RC-06.smt2                                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|n4216-RC-07.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n4218-RC-09.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n4227-RF-03.smt2                                                                            |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|n4230-RF-06.smt2                                                                            |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|n4235-RF-12.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n4253-RC-15.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n4261-RF-07.smt2                                                                            |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|n4262-RF-08.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n4265-RF-11.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n4275-RC-05.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n4285-RC-15.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n4290-RF-04.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n4301-RC-00.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n4311-RC-10.smt2                                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|n4313-RC-12.smt2                                                                            |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|n4314-RC-13.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n4320-RF-03.smt2                                                                            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|n4328-RF-11.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n4334-RC-01.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n4335-RC-02.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n4336-RC-03.smt2                                                                            |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|n4355-RF-10.smt2                                                                            |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|n4362-RC-02.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n4377-RF-01.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n4395-RC-05.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n4396-RC-06.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n4399-RC-10.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n4413-RF-09.smt2                                                                            |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|n4422-RC-02.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n4435-RF-00.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n4440-RF-05.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n4449-RC-01.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n4450-RC-02.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n4457-RC-09.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n4459-RC-11.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n4461-RC-13.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n4474-RF-10.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n4476-RF-14.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n4480-RC-02.smt2                                                                            |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|n4482-RC-04.smt2                                                                            |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|n4485-RC-07.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n4487-RC-09.smt2                                                                            |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|n4492-RC-15.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n4502-RF-10.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n4506-RF-14.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n4507-RF-15.smt2                                                                            |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|n468-RF-02.smt2                                                                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n473-RF-07.smt2                                                                             |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|n480-RF-14.smt2                                                                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|n49-unbd-sage15.smt2                                                                        |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|n4912-RF-06.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n502-RF-04.smt2                                                                             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|n5079-RC-01.smt2                                                                            |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|n5081-RC-03.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n5082-RC-04.smt2                                                                            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|n5083-RC-05.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n5084-RC-06.smt2                                                                            |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|n5086-RC-08.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n5089-RC-11.smt2                                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|n5090-RC-12.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n5091-RC-13.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5092-RC-14.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5093-RC-15.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5100-RF-06.smt2                                                                            |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|n5101-RF-07.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5104-RF-10.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n5105-RF-11.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5108-RF-14.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n511-RF-14.smt2                                                                             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n5112-RC-02.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5113-RC-03.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5118-RC-08.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n5120-RC-10.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5121-RC-11.smt2                                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|n5123-RC-13.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5131-RF-05.smt2                                                                            |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|n5132-RF-06.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n5134-RF-08.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5137-RF-11.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n5142-RC-00.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5143-RC-01.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n5145-RC-03.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n5148-RC-06.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5149-RC-07.smt2                                                                            |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|n5153-RC-11.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5156-RC-14.smt2                                                                            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|n5161-RF-03.smt2                                                                            |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|n5166-RF-08.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n5167-RF-09.smt2                                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|n5168-RF-10.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5170-RF-12.smt2                                                                            |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|n5171-RF-13.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n5172-RF-14.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5173-RF-15.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n5178-RC-04.smt2                                                                            |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|n5185-RC-11.smt2                                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|n5193-RF-03.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n5197-RF-07.smt2                                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|n52-unbd-sage18.smt2                                                                        |   9.598s  |   9.598s  |   0.000s  | 0.0%|
|n5201-RF-11.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n5202-RF-12.smt2                                                                            |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|n5204-RF-14.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n5206-RC-00.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5209-RC-03.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5212-RC-06.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n5214-RC-08.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5215-RC-09.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5217-RC-11.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n5218-RC-12.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n5219-RC-13.smt2                                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|n5222-RF-00.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n5230-RF-10.smt2                                                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|n5231-RF-12.smt2                                                                            |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|n5234-RC-00.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5235-RC-01.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n5242-RC-10.smt2                                                                            |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|n5249-RF-01.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n5250-RF-03.smt2                                                                            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|n5256-RF-12.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5257-RF-13.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5258-RF-15.smt2                                                                            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|n5263-RC-04.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5266-RC-07.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5268-RC-09.smt2                                                                            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|n5272-RC-13.smt2                                                                            |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|n5273-RC-14.smt2                                                                            |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|n5276-RF-01.smt2                                                                            |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|n5283-RF-08.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5284-RF-09.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5286-RF-11.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5290-RC-00.smt2                                                                            |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|n5291-RC-01.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n5297-RC-07.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5299-RC-09.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n53-unbd-sage19.smt2                                                                        |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|n5300-RC-10.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n5302-RC-12.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n5305-RC-15.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5308-RF-02.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n5310-RF-04.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5315-RF-14.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n5316-RF-15.smt2                                                                            |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|n5317-RC-00.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n5318-RC-01.smt2                                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|n5319-RC-02.smt2                                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|n5320-RC-03.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5321-RC-04.smt2                                                                            |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|n5326-RC-09.smt2                                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|n5328-RC-11.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5330-RC-13.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n5332-RF-00.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5334-RF-02.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5336-RF-04.smt2                                                                            |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|n5338-RF-06.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n5342-RF-13.smt2                                                                            |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|n5343-RF-15.smt2                                                                            |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|n5346-RC-02.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5347-RC-03.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5351-RC-07.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5352-RC-08.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n5356-RC-12.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5363-RF-03.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n5364-RF-04.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n5366-RF-07.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5367-RF-08.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5368-RF-09.smt2                                                                            |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|n5373-RC-00.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n5374-RC-01.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n5375-RC-02.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5377-RC-04.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n5379-RC-06.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n5380-RC-08.smt2                                                                            |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|n5381-RC-09.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n5382-RC-10.smt2                                                                            |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|n5384-RC-12.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5385-RC-13.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5386-RC-14.smt2                                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|n5390-RF-02.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5391-RF-03.smt2                                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|n5392-RF-04.smt2                                                                            |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|n5394-RF-06.smt2                                                                            |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|n5395-RF-07.smt2                                                                            |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|n54-unbd-sage2.smt2                                                                         |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|n5403-RF-15.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5405-RC-01.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n5411-RC-07.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n5412-RC-08.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5413-RC-09.smt2                                                                            |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|n5415-RC-11.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n5416-RC-12.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n5418-RC-14.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n5419-RC-15.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5422-RF-02.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n5425-RF-07.smt2                                                                            |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|n5427-RF-10.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5431-RF-14.smt2                                                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|n5432-RF-15.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5437-RC-04.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5438-RC-05.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n5440-RC-07.smt2                                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|n5442-RC-09.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n5443-RC-10.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5445-RC-12.smt2                                                                            |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|n5452-RF-03.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5453-RF-04.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n5456-RF-07.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n5458-RF-11.smt2                                                                            |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|n5461-RF-15.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n5467-RC-05.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n5470-RC-08.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5474-RC-12.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5475-RC-13.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5476-RC-14.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5481-RF-04.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n5482-RF-05.smt2                                                                            |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|n5483-RF-06.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5488-RF-12.smt2                                                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|n5489-RF-13.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5495-RC-03.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n5498-RC-06.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n5499-RC-07.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n5501-RC-09.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5502-RC-10.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n5504-RC-12.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n5505-RC-13.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n5509-RF-01.smt2                                                                            |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|n5511-RF-03.smt2                                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|n5516-RF-09.smt2                                                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|n5520-RF-15.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5521-RC-00.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5522-RC-01.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n5525-RC-04.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5529-RC-08.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5530-RC-09.smt2                                                                            |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|n5533-RC-12.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n5534-RC-13.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n5535-RC-14.smt2                                                                            |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|n5536-RC-15.smt2                                                                            |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|n5538-RF-01.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5541-RF-04.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5542-RF-05.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5544-RF-08.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n5545-RF-09.smt2                                                                            |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|n5551-RC-01.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n5553-RC-03.smt2                                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|n5555-RC-05.smt2                                                                            |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|n5556-RC-06.smt2                                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|n5558-RC-08.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5563-RC-13.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5564-RC-14.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5569-RF-05.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5570-RF-06.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n5571-RF-07.smt2                                                                            |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|n5573-RF-10.smt2                                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|n5578-RC-01.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5582-RC-05.smt2                                                                            |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|n5586-RC-09.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n5590-RC-13.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5592-RC-15.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5593-RF-00.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n5595-RF-02.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5597-RF-04.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n5599-RF-06.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n56-unbd-sage21.smt2                                                                        |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|n5603-RF-12.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5604-RF-13.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5606-RF-15.smt2                                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|n5607-RC-00.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n5608-RC-01.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n5610-RC-03.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n5616-RC-09.smt2                                                                            |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|n5617-RC-10.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5620-RC-13.smt2                                                                            |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|n5623-RF-00.smt2                                                                            |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|n5624-RF-01.smt2                                                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|n5625-RF-02.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n5627-RF-04.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n5628-RF-05.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n5629-RF-06.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n5630-RF-07.smt2                                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|n5631-RF-08.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n5636-RF-13.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n5637-RF-14.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5667-RC-04.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5681-RF-02.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n5684-RF-05.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n5685-RF-06.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n5694-RF-15.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5695-RC-00.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5698-RC-03.smt2                                                                            |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|n5700-RC-05.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5701-RC-06.smt2                                                                            |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|n5703-RC-08.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5706-RC-11.smt2                                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|n5707-RC-12.smt2                                                                            |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|n5708-RC-13.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5709-RC-14.smt2                                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|n5710-RC-15.smt2                                                                            |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|n5711-RF-00.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5712-RF-01.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5713-RF-02.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5718-RF-07.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5723-RF-12.smt2                                                                            |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|n5724-RF-13.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5725-RF-14.smt2                                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|n5726-RF-15.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n5728-RC-01.smt2                                                                            |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|n5731-RC-04.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5732-RC-05.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n5733-RC-06.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n5736-RC-09.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5737-RC-10.smt2                                                                            |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|n574-RF-14.smt2                                                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|n5745-RF-02.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n5746-RF-03.smt2                                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|n5750-RF-07.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5759-RC-06.smt2                                                                            |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|n5761-RC-08.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n5763-RC-10.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5766-RC-13.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n5767-RC-14.smt2                                                                            |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|n5770-RF-01.smt2                                                                            |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|n5772-RF-03.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5776-RF-10.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5779-RF-13.smt2                                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|n5781-RC-00.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5782-RC-01.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5783-RC-02.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n5785-RC-04.smt2                                                                            |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|n5789-RC-08.smt2                                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|n5791-RC-10.smt2                                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|n5794-RC-13.smt2                                                                            |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|n5796-RC-15.smt2                                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|n5797-RF-00.smt2                                                                            |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|n5801-RF-04.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5802-RF-05.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n5806-RF-11.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5808-RF-14.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n581-RC-06.smt2                                                                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|n5813-RC-03.smt2                                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|n5815-RC-05.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5817-RC-07.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5818-RC-08.smt2                                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|n5819-RC-09.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n5821-RC-11.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5823-RC-13.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5824-RC-14.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n5826-RF-00.smt2                                                                            |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|n5828-RF-02.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n5829-RF-03.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n5832-RF-06.smt2                                                                            |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|n5833-RF-07.smt2                                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|n5834-RF-09.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5836-RF-12.smt2                                                                            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|n5840-RC-00.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n5842-RC-02.smt2                                                                            |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|n5844-RC-04.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5845-RC-05.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n5846-RC-06.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5847-RC-07.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n5848-RC-08.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5849-RC-09.smt2                                                                            |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|n5850-RC-10.smt2                                                                            |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|n5851-RC-11.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5852-RC-12.smt2                                                                            |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|n5855-RC-15.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5857-RF-01.smt2                                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n5858-RF-02.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5860-RF-05.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5862-RF-08.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n5866-RF-13.smt2                                                                            |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|n5869-RC-01.smt2                                                                            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n5872-RC-04.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n5874-RC-06.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n5877-RC-09.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n5881-RC-13.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n5885-RF-01.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5886-RF-02.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5889-RF-06.smt2                                                                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n5890-RF-09.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5891-RF-10.smt2                                                                            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n5892-RF-12.smt2                                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|n5893-RF-14.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n5897-RC-02.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5898-RC-03.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5900-RC-05.smt2                                                                            |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|n5901-RC-06.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n5908-RC-13.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n5909-RC-14.smt2                                                                            |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|n5910-RC-15.smt2                                                                            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n5911-RF-00.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5914-RF-03.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n5915-RF-04.smt2                                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|n5917-RF-06.smt2                                                                            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n5918-RF-08.smt2                                                                            |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|n5919-RF-11.smt2                                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|n5920-RF-12.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n5922-RF-15.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5923-RC-00.smt2                                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|n5925-RC-02.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n593-RF-02.smt2                                                                             |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|n5931-RC-08.smt2                                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n5933-RC-10.smt2                                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|n5937-RC-14.smt2                                                                            |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n5938-RC-15.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n5939-RF-00.smt2                                                                            |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|n5941-RF-02.smt2                                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|n5942-RF-03.smt2                                                                            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n5945-RF-07.smt2                                                                            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n5947-RF-11.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5957-RC-05.smt2                                                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|n5958-RC-06.smt2                                                                            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|n596-RF-05.smt2                                                                             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|n5961-RC-09.smt2                                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n5962-RC-10.smt2                                                                            |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|n5963-RC-11.smt2                                                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|n5964-RC-12.smt2                                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|n5968-RF-00.smt2                                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n5970-RF-02.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5971-RF-03.smt2                                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n5977-RF-09.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n598-RF-07.smt2                                                                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|n5983-RF-15.smt2                                                                            |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|n6-cut_lemma_01_001.smt2.slack.smt2                                                         |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|n6002-problem__005.smt2                                                                     |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|n6010-problem__003.smt2                                                                     |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|n6014-problem__002.smt2                                                                     |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|n602-RF-11.smt2                                                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|n6020-problem__003.smt2                                                                     |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|n603-RF-12.smt2                                                                             |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n6032-problem__004.smt2                                                                     |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|n604-RF-13.smt2                                                                             |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n6043-problem_2__009.smt2                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n6048-problem_2__014.smt2                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|n6057-problem_2__023.smt2                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n6063-problem__004.smt2                                                                     |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n6071-problem__012.smt2                                                                     |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n6089-problem_2__005.smt2                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n609-RC-02.smt2                                                                             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n6090-problem_2__006.smt2                                                                   |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n6093-problem_2__009.smt2                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|n6101-problem_2__017.smt2                                                                   |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|n6103-problem_2__019.smt2                                                                   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|n6104-problem_2__020.smt2                                                                   |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|n612-RC-05.smt2                                                                             |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n6125-problem__006.smt2                                                                     |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n6133-problem__014.smt2                                                                     |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|n6142-problem__023.smt2                                                                     |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|n6152-problem__033.smt2                                                                     |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|n6156-problem_2__002.smt2                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n6159-problem_2__005.smt2                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n6163-problem_2__009.smt2                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n6168-problem_2__014.smt2                                                                   |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n618-RC-11.smt2                                                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n619-RC-12.smt2                                                                             |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n6191-problem__002.smt2                                                                     |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n6198-problem__009.smt2                                                                     |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|n6206-problem__017.smt2                                                                     |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|n6208-problem__019.smt2                                                                     |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|n6211-problem__022.smt2                                                                     |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|n6227-problem_2__003.smt2                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n6228-problem_2__004.smt2                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|n6232-problem_2__008.smt2                                                                   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n6237-problem_2__013.smt2                                                                   |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|n6247-problem_2__023.smt2                                                                   |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|n6275-problem__016.smt2                                                                     |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|n6293-problem__034.smt2                                                                     |   3.114s  |   3.114s  |   0.000s  | 0.0%|
|n6308-problem_2__014.smt2                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n6329-problem_2__035.smt2                                                                   |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|n6330-problem__001.smt2                                                                     |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|n6343-problem__014.smt2                                                                     |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|n636-RC-00.smt2                                                                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n6389-problem_2__025.smt2                                                                   |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|n639-RC-03.smt2                                                                             |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n641-RC-05.smt2                                                                             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|n642-RC-06.smt2                                                                             |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n6423-problem__024.smt2                                                                     |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|n643-RC-07.smt2                                                                             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n6432-problem__033.smt2                                                                     |   0.702s  |   0.702s  |   0.000s  | 0.0%|
|n6475-problem__006.smt2                                                                     |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|n6499-problem__030.smt2                                                                     |   0.599s  |   0.599s  |   0.000s  | 0.0%|
|n6502-problem__033.smt2                                                                     |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|n651-RC-15.smt2                                                                             |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n6537-cut_lemma_03_004.smt2                                                                 |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|n6545-cut_lemma_03_013.smt2                                                                 |   1.889s  |   1.889s  |   0.000s  | 0.0%|
|n6552-prp-11-46.smt2                                                                        |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|n6563-prp-13-47.smt2                                                                        |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|n657-RF-06.smt2                                                                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n6573-prp-15-47.smt2                                                                        |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|n658-RF-07.smt2                                                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n6580-prp-16-49.smt2                                                                        |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|n6583-prp-17-47.smt2                                                                        |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|n659-RF-08.smt2                                                                             |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n6595-prp-19-49.smt2                                                                        |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|n6605-prp-20-49.smt2                                                                        |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|n6609-prp-21-48.smt2                                                                        |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|n6612-prp-22-46.smt2                                                                        |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|n6613-prp-22-47.smt2                                                                        |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|n663-RF-12.smt2                                                                             |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n6635-prp-27-47.smt2                                                                        |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|n6637-prp-27-49.smt2                                                                        |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|n664-RF-13.smt2                                                                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|n6653-prp-30-47.smt2                                                                        |   0.971s  |   0.971s  |   0.000s  | 0.0%|
|n6657-prp-31-46.smt2                                                                        |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|n6658-prp-31-47.smt2                                                                        |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|n6664-prp-32-48.smt2                                                                        |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|n6665-prp-32-49.smt2                                                                        |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|n6667-prp-33-46.smt2                                                                        |   0.851s  |   0.851s  |   0.000s  | 0.0%|
|n6668-prp-33-47.smt2                                                                        |   1.061s  |   1.061s  |   0.000s  | 0.0%|
|n6683-prp-39-49.smt2                                                                        |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|n669-RC-02.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|n6695-prp-42-48.smt2                                                                        |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|n67-unbd-sage0.smt2                                                                         |   2.191s  |   2.191s  |   0.000s  | 0.0%|
|n6702-prp-44-49.smt2                                                                        |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|n6708-prp-47-49.smt2                                                                        |   1.683s  |   1.683s  |   0.000s  | 0.0%|
|n6729-prp-6-47.smt2                                                                         |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|n6733-prp-7-46.smt2                                                                         |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|n6741-prp-8-49.smt2                                                                         |   1.871s  |   1.871s  |   0.000s  | 0.0%|
|n6746-prp-9-49.smt2                                                                         |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|n6748-prp-13-46.smt2                                                                        |  30.116s  |  30.116s  |   0.000s  | 0.0%|
|n6752-prp-13-50.smt2                                                                        |  30.143s  |  30.143s  |   0.000s  | 0.0%|
|n6754-prp-14-47.smt2                                                                        |  27.001s  |  27.001s  |   0.000s  | 0.0%|
|n6756-prp-14-49.smt2                                                                        |  30.165s  |  30.165s  |   0.000s  | 0.0%|
|n6757-prp-14-50.smt2                                                                        |  30.241s  |  30.241s  |   0.000s  | 0.0%|
|n6758-prp-16-46.smt2                                                                        |  30.136s  |  30.136s  |   0.000s  | 0.0%|
|n6759-prp-16-47.smt2                                                                        |  30.154s  |  30.154s  |   0.000s  | 0.0%|
|n6763-prp-17-46.smt2                                                                        |  30.084s  |  30.084s  |   0.000s  | 0.0%|
|n6765-prp-17-48.smt2                                                                        |  30.152s  |  30.152s  |   0.000s  | 0.0%|
|n6768-prp-18-46.smt2                                                                        |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|n6771-prp-18-49.smt2                                                                        |  30.168s  |  30.168s  |   0.000s  | 0.0%|
|n6772-prp-18-50.smt2                                                                        |  30.170s  |  30.170s  |   0.000s  | 0.0%|
|n6773-prp-19-46.smt2                                                                        |  30.136s  |  30.136s  |   0.000s  | 0.0%|
|n6775-prp-19-48.smt2                                                                        |  30.139s  |  30.139s  |   0.000s  | 0.0%|
|n6777-prp-19-50.smt2                                                                        |  30.146s  |  30.146s  |   0.000s  | 0.0%|
|n6778-prp-20-46.smt2                                                                        |  30.134s  |  30.134s  |   0.000s  | 0.0%|
|n6782-prp-20-50.smt2                                                                        |  30.164s  |  30.164s  |   0.000s  | 0.0%|
|n6785-prp-22-48.smt2                                                                        |  30.141s  |  30.141s  |   0.000s  | 0.0%|
|n6806-prp-28-46.smt2                                                                        |  30.130s  |  30.130s  |   0.000s  | 0.0%|
|n6809-prp-28-49.smt2                                                                        |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|n6810-prp-28-50.smt2                                                                        |  30.132s  |  30.132s  |   0.000s  | 0.0%|
|n6812-prp-29-47.smt2                                                                        |  30.147s  |  30.147s  |   0.000s  | 0.0%|
|n6821-prp-32-46.smt2                                                                        |  30.158s  |  30.158s  |   0.000s  | 0.0%|
|n6823-prp-32-48.smt2                                                                        |  30.174s  |  30.174s  |   0.000s  | 0.0%|
|n6825-prp-32-50.smt2                                                                        |  30.139s  |  30.139s  |   0.000s  | 0.0%|
|n6826-prp-33-45.smt2                                                                        |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|n6830-prp-33-49.smt2                                                                        |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|n6832-prp-34-46.smt2                                                                        |  30.141s  |  30.141s  |   0.000s  | 0.0%|
|n6833-prp-34-47.smt2                                                                        |  30.203s  |  30.203s  |   0.000s  | 0.0%|
|n6834-prp-34-48.smt2                                                                        |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|n6836-prp-34-50.smt2                                                                        |  30.173s  |  30.173s  |   0.000s  | 0.0%|
|n6838-prp-35-47.smt2                                                                        |  30.152s  |  30.152s  |   0.000s  | 0.0%|
|n6839-prp-36-45.smt2                                                                        |  30.135s  |  30.135s  |   0.000s  | 0.0%|
|n6842-prp-36-48.smt2                                                                        |  30.143s  |  30.143s  |   0.000s  | 0.0%|
|n6843-prp-36-49.smt2                                                                        |  30.190s  |  30.190s  |   0.000s  | 0.0%|
|n6844-prp-36-50.smt2                                                                        |  30.141s  |  30.141s  |   0.000s  | 0.0%|
|n6849-prp-38-42.smt2                                                                        |  30.106s  |  30.106s  |   0.000s  | 0.0%|
|n6854-prp-38-48.smt2                                                                        |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|n6857-prp-39-41.smt2                                                                        |  30.139s  |  30.139s  |   0.000s  | 0.0%|
|n6864-prp-4-46.smt2                                                                         |  28.888s  |  28.888s  |   0.000s  | 0.0%|
|n6868-prp-4-50.smt2                                                                         |  30.157s  |  30.157s  |   0.000s  | 0.0%|
|n6870-prp-40-46.smt2                                                                        |  30.132s  |  30.132s  |   0.000s  | 0.0%|
|n6873-prp-40-49.smt2                                                                        |  30.121s  |  30.121s  |   0.000s  | 0.0%|
|n6874-prp-40-50.smt2                                                                        |  30.119s  |  30.119s  |   0.000s  | 0.0%|
|n6875-prp-41-42.smt2                                                                        |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|n6878-prp-41-45.smt2                                                                        |  30.116s  |  30.116s  |   0.000s  | 0.0%|
|n6879-prp-41-46.smt2                                                                        |  30.100s  |  30.100s  |   0.000s  | 0.0%|
|n688-RF-05.smt2                                                                             |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n6886-prp-42-48.smt2                                                                        |  30.127s  |  30.127s  |   0.000s  | 0.0%|
|n6891-prp-43-46.smt2                                                                        |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|n6893-prp-43-48.smt2                                                                        |  30.153s  |  30.153s  |   0.000s  | 0.0%|
|n6894-prp-43-49.smt2                                                                        |  30.119s  |  30.119s  |   0.000s  | 0.0%|
|n6895-prp-43-50.smt2                                                                        |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|n6897-prp-44-47.smt2                                                                        |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|n6898-prp-44-48.smt2                                                                        |  30.143s  |  30.143s  |   0.000s  | 0.0%|
|n6902-prp-45-45.smt2                                                                        |  30.139s  |  30.139s  |   0.000s  | 0.0%|
|n6904-prp-45-47.smt2                                                                        |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|n6906-prp-45-49.smt2                                                                        |  30.116s  |  30.116s  |   0.000s  | 0.0%|
|n6908-prp-46-46.smt2                                                                        |  30.146s  |  30.146s  |   0.000s  | 0.0%|
|n6909-prp-46-48.smt2                                                                        |  30.144s  |  30.144s  |   0.000s  | 0.0%|
|n6910-prp-46-49.smt2                                                                        |  30.144s  |  30.144s  |   0.000s  | 0.0%|
|n6911-prp-46-50.smt2                                                                        |  30.159s  |  30.159s  |   0.000s  | 0.0%|
|n6912-prp-47-46.smt2                                                                        |  30.097s  |  30.097s  |   0.000s  | 0.0%|
|n6917-prp-48-46.smt2                                                                        |  30.119s  |  30.119s  |   0.000s  | 0.0%|
|n6918-prp-48-47.smt2                                                                        |  30.150s  |  30.150s  |   0.000s  | 0.0%|
|n6919-prp-48-48.smt2                                                                        |  30.158s  |  30.158s  |   0.000s  | 0.0%|
|n6923-prp-49-47.smt2                                                                        |  30.121s  |  30.121s  |   0.000s  | 0.0%|
|n6928-prp-5-47.smt2                                                                         |  30.145s  |  30.145s  |   0.000s  | 0.0%|
|n6930-prp-5-49.smt2                                                                         |  30.135s  |  30.135s  |   0.000s  | 0.0%|
|n6931-prp-5-50.smt2                                                                         |  30.192s  |  30.192s  |   0.000s  | 0.0%|
|n6933-prp-50-47.smt2                                                                        |  30.175s  |  30.175s  |   0.000s  | 0.0%|
|n6934-prp-50-48.smt2                                                                        |  30.128s  |  30.128s  |   0.000s  | 0.0%|
|n6936-prp-50-50.smt2                                                                        |  30.138s  |  30.138s  |   0.000s  | 0.0%|
|n6938-prp-51-47.smt2                                                                        |  30.146s  |  30.146s  |   0.000s  | 0.0%|
|n6939-prp-51-48.smt2                                                                        |  30.114s  |  30.114s  |   0.000s  | 0.0%|
|n694-RF-11.smt2                                                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|n6940-prp-51-49.smt2                                                                        |  30.147s  |  30.147s  |   0.000s  | 0.0%|
|n6941-prp-51-50.smt2                                                                        |  30.133s  |  30.133s  |   0.000s  | 0.0%|
|n6945-prp-52-50.smt2                                                                        |  30.122s  |  30.122s  |   0.000s  | 0.0%|
|n6947-prp-53-47.smt2                                                                        |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|n6949-prp-53-49.smt2                                                                        |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|n695-RF-12.smt2                                                                             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n6952-prp-54-47.smt2                                                                        |  30.176s  |  30.176s  |   0.000s  | 0.0%|
|n6953-prp-54-48.smt2                                                                        |  30.122s  |  30.122s  |   0.000s  | 0.0%|
|n6956-prp-55-46.smt2                                                                        |  30.118s  |  30.118s  |   0.000s  | 0.0%|
|n6957-prp-55-47.smt2                                                                        |  30.171s  |  30.171s  |   0.000s  | 0.0%|
|n696-RF-13.smt2                                                                             |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n6965-prp-57-48.smt2                                                                        |  30.140s  |  30.140s  |   0.000s  | 0.0%|
|n6968-prp-58-47.smt2                                                                        |  30.134s  |  30.134s  |   0.000s  | 0.0%|
|n6970-prp-58-49.smt2                                                                        |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|n6971-prp-58-50.smt2                                                                        |  30.187s  |  30.187s  |   0.000s  | 0.0%|
|n6972-prp-59-48.smt2                                                                        |  30.114s  |  30.114s  |   0.000s  | 0.0%|
|n6975-prp-60-48.smt2                                                                        |  30.116s  |  30.116s  |   0.000s  | 0.0%|
|n698-RF-15.smt2                                                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|n6981-prp-62-50.smt2                                                                        |  30.208s  |  30.208s  |   0.000s  | 0.0%|
|n6982-prp-63-50.smt2                                                                        |  30.120s  |  30.120s  |   0.000s  | 0.0%|
|n6983-prp-7-46.smt2                                                                         |  30.161s  |  30.161s  |   0.000s  | 0.0%|
|n6984-prp-7-47.smt2                                                                         |  30.135s  |  30.135s  |   0.000s  | 0.0%|
|n6985-prp-7-48.smt2                                                                         |  30.149s  |  30.149s  |   0.000s  | 0.0%|
|n6986-prp-7-49.smt2                                                                         |  30.139s  |  30.139s  |   0.000s  | 0.0%|
|n6987-prp-7-50.smt2                                                                         |  30.121s  |  30.121s  |   0.000s  | 0.0%|
|n6990-prp-8-48.smt2                                                                         |  30.144s  |  30.144s  |   0.000s  | 0.0%|
|n6991-prp-8-49.smt2                                                                         |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|n6995-prp-10-48.smt2                                                                        |  30.127s  |  30.127s  |   0.000s  | 0.0%|
|n6996-prp-10-49.smt2                                                                        |  30.089s  |  30.089s  |   0.000s  | 0.0%|
|n6999-prp-11-47.smt2                                                                        |  30.166s  |  30.166s  |   0.000s  | 0.0%|
|n7000-prp-11-48.smt2                                                                        |  30.146s  |  30.146s  |   0.000s  | 0.0%|
|n7001-prp-11-49.smt2                                                                        |  30.091s  |  30.091s  |   0.000s  | 0.0%|
|n7003-prp-12-46.smt2                                                                        |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|n7006-prp-12-49.smt2                                                                        |  30.152s  |  30.152s  |   0.000s  | 0.0%|
|n7011-prp-13-49.smt2                                                                        |  30.119s  |  30.119s  |   0.000s  | 0.0%|
|n7012-prp-13-50.smt2                                                                        |  30.132s  |  30.132s  |   0.000s  | 0.0%|
|n7014-prp-5-47.smt2                                                                         |  30.136s  |  30.136s  |   0.000s  | 0.0%|
|n7016-prp-5-49.smt2                                                                         |  30.132s  |  30.132s  |   0.000s  | 0.0%|
|n7018-prp-6-46.smt2                                                                         |  30.154s  |  30.154s  |   0.000s  | 0.0%|
|n702-RC-03.smt2                                                                             |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n7020-prp-6-48.smt2                                                                         |  30.179s  |  30.179s  |   0.000s  | 0.0%|
|n7025-prp-7-48.smt2                                                                         |  30.120s  |  30.120s  |   0.000s  | 0.0%|
|n7026-prp-7-49.smt2                                                                         |  30.106s  |  30.106s  |   0.000s  | 0.0%|
|n7028-prp-8-46.smt2                                                                         |   5.578s  |   5.578s  |   0.000s  | 0.0%|
|n7038-prp-0-47.smt2                                                                         |   7.654s  |   7.654s  |   0.000s  | 0.0%|
|n7044-prp-1-48.smt2                                                                         |  30.106s  |  30.106s  |   0.000s  | 0.0%|
|n7045-prp-1-49.smt2                                                                         |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|n7048-prp-10-47.smt2                                                                        |   9.973s  |   9.973s  |   0.000s  | 0.0%|
|n7049-prp-10-48.smt2                                                                        |  11.079s  |  11.079s  |   0.000s  | 0.0%|
|n7050-prp-10-49.smt2                                                                        |  13.184s  |  13.184s  |   0.000s  | 0.0%|
|n7051-prp-10-50.smt2                                                                        |  30.107s  |  30.107s  |   0.000s  | 0.0%|
|n7061-prp-12-50.smt2                                                                        |  12.406s  |  12.406s  |   0.000s  | 0.0%|
|n7070-prp-14-49.smt2                                                                        |  11.474s  |  11.474s  |   0.000s  | 0.0%|
|n7076-prp-15-50.smt2                                                                        |  13.801s  |  13.801s  |   0.000s  | 0.0%|
|n708-RC-09.smt2                                                                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n7083-prp-17-47.smt2                                                                        |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|n7085-prp-17-49.smt2                                                                        |  16.715s  |  16.715s  |   0.000s  | 0.0%|
|n7087-prp-18-46.smt2                                                                        |   5.486s  |   5.486s  |   0.000s  | 0.0%|
|n7088-prp-18-47.smt2                                                                        |   7.190s  |   7.190s  |   0.000s  | 0.0%|
|n7099-prp-2-48.smt2                                                                         |   7.941s  |   7.941s  |   0.000s  | 0.0%|
|n710-RC-11.smt2                                                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|n711-RC-12.smt2                                                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n7115-prp-22-49.smt2                                                                        |  17.946s  |  17.946s  |   0.000s  | 0.0%|
|n7116-prp-22-50.smt2                                                                        |  17.525s  |  17.525s  |   0.000s  | 0.0%|
|n712-RC-13.smt2                                                                             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n7125-prp-24-49.smt2                                                                        |  30.114s  |  30.114s  |   0.000s  | 0.0%|
|n7127-prp-25-47.smt2                                                                        |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|n7128-prp-25-48.smt2                                                                        |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|n7129-prp-25-49.smt2                                                                        |  30.105s  |  30.105s  |   0.000s  | 0.0%|
|n7130-prp-25-50.smt2                                                                        |  30.107s  |  30.107s  |   0.000s  | 0.0%|
|n7131-prp-26-47.smt2                                                                        |  11.808s  |  11.808s  |   0.000s  | 0.0%|
|n7134-prp-26-50.smt2                                                                        |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|n7136-prp-27-47.smt2                                                                        |  21.139s  |  21.139s  |   0.000s  | 0.0%|
|n7138-prp-27-49.smt2                                                                        |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|n7139-prp-27-50.smt2                                                                        |  30.172s  |  30.172s  |   0.000s  | 0.0%|
|n7142-prp-28-48.smt2                                                                        |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|n7148-prp-29-49.smt2                                                                        |  30.097s  |  30.097s  |   0.000s  | 0.0%|
|n715-RF-00.smt2                                                                             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n7153-prp-3-49.smt2                                                                         |  30.103s  |  30.103s  |   0.000s  | 0.0%|
|n7154-prp-3-50.smt2                                                                         |  11.989s  |  11.989s  |   0.000s  | 0.0%|
|n7163-prp-31-49.smt2                                                                        |  14.608s  |  14.608s  |   0.000s  | 0.0%|
|n717-RF-02.smt2                                                                             |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|n7174-prp-33-50.smt2                                                                        |  13.872s  |  13.872s  |   0.000s  | 0.0%|
|n7178-prp-34-48.smt2                                                                        |   8.027s  |   8.027s  |   0.000s  | 0.0%|
|n7180-prp-35-46.smt2                                                                        |  11.958s  |  11.958s  |   0.000s  | 0.0%|
|n7181-prp-35-47.smt2                                                                        |  10.254s  |  10.254s  |   0.000s  | 0.0%|
|n7193-prp-37-49.smt2                                                                        |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|n72-unbd-sage13.smt2                                                                        |   2.937s  |   2.937s  |   0.000s  | 0.0%|
|n7206-prp-4-47.smt2                                                                         |   6.499s  |   6.499s  |   0.000s  | 0.0%|
|n7207-prp-4-48.smt2                                                                         |   8.380s  |   8.380s  |   0.000s  | 0.0%|
|n7217-prp-41-48.smt2                                                                        |  30.081s  |  30.081s  |   0.000s  | 0.0%|
|n7219-prp-41-50.smt2                                                                        |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|n7227-prp-43-48.smt2                                                                        |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|n7230-prp-44-46.smt2                                                                        |   7.390s  |   7.390s  |   0.000s  | 0.0%|
|n7232-prp-44-48.smt2                                                                        |  13.987s  |  13.987s  |   0.000s  | 0.0%|
|n7237-prp-45-48.smt2                                                                        |  10.637s  |  10.637s  |   0.000s  | 0.0%|
|n7238-prp-45-49.smt2                                                                        |  12.612s  |  12.612s  |   0.000s  | 0.0%|
|n724-RF-11.smt2                                                                             |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n7247-prp-47-48.smt2                                                                        |  13.198s  |  13.198s  |   0.000s  | 0.0%|
|n7252-prp-48-48.smt2                                                                        |  30.091s  |  30.091s  |   0.000s  | 0.0%|
|n7259-prp-49-50.smt2                                                                        |  30.109s  |  30.109s  |   0.000s  | 0.0%|
|n7268-prp-50-49.smt2                                                                        |  28.978s  |  28.978s  |   0.000s  | 0.0%|
|n7269-prp-50-50.smt2                                                                        |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|n7274-prp-51-50.smt2                                                                        |  30.115s  |  30.115s  |   0.000s  | 0.0%|
|n7279-prp-52-50.smt2                                                                        |  30.173s  |  30.173s  |   0.000s  | 0.0%|
|n7287-prp-54-48.smt2                                                                        |  13.490s  |  13.490s  |   0.000s  | 0.0%|
|n7293-prp-55-49.smt2                                                                        |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|n7301-prp-57-47.smt2                                                                        |   9.112s  |   9.112s  |   0.000s  | 0.0%|
|n7306-prp-58-47.smt2                                                                        |   9.740s  |   9.740s  |   0.000s  | 0.0%|
|n7316-prp-6-47.smt2                                                                         |   6.457s  |   6.457s  |   0.000s  | 0.0%|
|n7318-prp-6-49.smt2                                                                         |  30.127s  |  30.127s  |   0.000s  | 0.0%|
|n732-RC-04.smt2                                                                             |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n7327-prp-61-49.smt2                                                                        |  14.149s  |  14.149s  |   0.000s  | 0.0%|
|n7331-prp-62-49.smt2                                                                        |  12.107s  |  12.107s  |   0.000s  | 0.0%|
|n7337-prp-64-47.smt2                                                                        |   9.819s  |   9.819s  |   0.000s  | 0.0%|
|n7341-prp-65-48.smt2                                                                        |  11.056s  |  11.056s  |   0.000s  | 0.0%|
|n7349-prp-67-50.smt2                                                                        |  20.823s  |  20.823s  |   0.000s  | 0.0%|
|n7350-prp-68-49.smt2                                                                        |  14.053s  |  14.053s  |   0.000s  | 0.0%|
|n7354-prp-7-46.smt2                                                                         |   5.646s  |   5.646s  |   0.000s  | 0.0%|
|n7359-prp-70-49.smt2                                                                        |  30.114s  |  30.114s  |   0.000s  | 0.0%|
|n7366-prp-74-48.smt2                                                                        |  10.528s  |  10.528s  |   0.000s  | 0.0%|
|n737-RC-09.smt2                                                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n7376-prp-8-47.smt2                                                                         |  11.041s  |  11.041s  |   0.000s  | 0.0%|
|n738-RC-10.smt2                                                                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|n7385-prp-9-49.smt2                                                                         |  10.016s  |  10.016s  |   0.000s  | 0.0%|
|n7389-prp-0-48.smt2                                                                         |  30.157s  |  30.157s  |   0.000s  | 0.0%|
|n739-RC-11.smt2                                                                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n7390-prp-0-49.smt2                                                                         |  30.129s  |  30.129s  |   0.000s  | 0.0%|
|n7392-prp-1-46.smt2                                                                         |  30.205s  |  30.205s  |   0.000s  | 0.0%|
|n7394-prp-1-48.smt2                                                                         |  29.334s  |  29.334s  |   0.000s  | 0.0%|
|n7399-prp-10-48.smt2                                                                        |  30.234s  |  30.234s  |   0.000s  | 0.0%|
|n7402-prp-11-46.smt2                                                                        |  30.169s  |  30.169s  |   0.000s  | 0.0%|
|n7403-prp-11-47.smt2                                                                        |  30.151s  |  30.151s  |   0.000s  | 0.0%|
|n7405-prp-11-49.smt2                                                                        |  30.151s  |  30.151s  |   0.000s  | 0.0%|
|n7407-prp-12-46.smt2                                                                        |  19.930s  |  19.930s  |   0.000s  | 0.0%|
|n741-RC-13.smt2                                                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|n7412-prp-13-46.smt2                                                                        |  30.179s  |  30.179s  |   0.000s  | 0.0%|
|n7420-prp-14-49.smt2                                                                        |  30.133s  |  30.133s  |   0.000s  | 0.0%|
|n7422-prp-15-46.smt2                                                                        |  16.749s  |  16.749s  |   0.000s  | 0.0%|
|n7424-prp-15-48.smt2                                                                        |  30.154s  |  30.154s  |   0.000s  | 0.0%|
|n7427-prp-16-46.smt2                                                                        |  30.151s  |  30.151s  |   0.000s  | 0.0%|
|n7429-prp-16-48.smt2                                                                        |  30.159s  |  30.159s  |   0.000s  | 0.0%|
|n7430-prp-16-49.smt2                                                                        |  30.159s  |  30.159s  |   0.000s  | 0.0%|
|n7443-prp-19-47.smt2                                                                        |  30.166s  |  30.166s  |   0.000s  | 0.0%|
|n7444-prp-19-48.smt2                                                                        |  30.135s  |  30.135s  |   0.000s  | 0.0%|
|n7448-prp-2-47.smt2                                                                         |  30.127s  |  30.127s  |   0.000s  | 0.0%|
|n7450-prp-2-49.smt2                                                                         |  30.148s  |  30.148s  |   0.000s  | 0.0%|
|n7452-prp-20-46.smt2                                                                        |  24.774s  |  24.774s  |   0.000s  | 0.0%|
|n7459-prp-21-48.smt2                                                                        |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|n7463-prp-22-47.smt2                                                                        |  30.132s  |  30.132s  |   0.000s  | 0.0%|
|n7464-prp-22-48.smt2                                                                        |  30.155s  |  30.155s  |   0.000s  | 0.0%|
|n7472-prp-24-46.smt2                                                                        |  23.055s  |  23.055s  |   0.000s  | 0.0%|
|n7489-prp-27-48.smt2                                                                        |  30.141s  |  30.141s  |   0.000s  | 0.0%|
|n7492-prp-28-46.smt2                                                                        |  30.129s  |  30.129s  |   0.000s  | 0.0%|
|n7498-prp-29-47.smt2                                                                        |  30.182s  |  30.182s  |   0.000s  | 0.0%|
|n7499-prp-29-48.smt2                                                                        |  30.177s  |  30.177s  |   0.000s  | 0.0%|
|n75-unbd-sage16.smt2                                                                        |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|n7502-prp-3-46.smt2                                                                         |  30.182s  |  30.182s  |   0.000s  | 0.0%|
|n7503-prp-3-47.smt2                                                                         |  30.156s  |  30.156s  |   0.000s  | 0.0%|
|n7507-prp-30-46.smt2                                                                        |  30.135s  |  30.135s  |   0.000s  | 0.0%|
|n7508-prp-30-47.smt2                                                                        |  30.127s  |  30.127s  |   0.000s  | 0.0%|
|n7510-prp-30-49.smt2                                                                        |  30.134s  |  30.134s  |   0.000s  | 0.0%|
|n7514-prp-31-48.smt2                                                                        |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|n7517-prp-32-46.smt2                                                                        |  30.176s  |  30.176s  |   0.000s  | 0.0%|
|n752-RF-10.smt2                                                                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|n7522-prp-33-46.smt2                                                                        |  30.125s  |  30.125s  |   0.000s  | 0.0%|
|n7523-prp-33-47.smt2                                                                        |  30.170s  |  30.170s  |   0.000s  | 0.0%|
|n7525-prp-33-49.smt2                                                                        |  30.188s  |  30.188s  |   0.000s  | 0.0%|
|n7527-prp-34-46.smt2                                                                        |  30.146s  |  30.146s  |   0.000s  | 0.0%|
|n7528-prp-34-47.smt2                                                                        |  30.139s  |  30.139s  |   0.000s  | 0.0%|
|n7529-prp-34-48.smt2                                                                        |  30.125s  |  30.125s  |   0.000s  | 0.0%|
|n7533-prp-35-47.smt2                                                                        |  30.118s  |  30.118s  |   0.000s  | 0.0%|
|n7534-prp-35-48.smt2                                                                        |  30.147s  |  30.147s  |   0.000s  | 0.0%|
|n7540-prp-36-49.smt2                                                                        |  30.146s  |  30.146s  |   0.000s  | 0.0%|
|n7544-prp-37-48.smt2                                                                        |  30.115s  |  30.115s  |   0.000s  | 0.0%|
|n7545-prp-37-49.smt2                                                                        |  30.136s  |  30.136s  |   0.000s  | 0.0%|
|n7550-prp-38-49.smt2                                                                        |  30.127s  |  30.127s  |   0.000s  | 0.0%|
|n7555-prp-39-49.smt2                                                                        |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|n7559-prp-4-48.smt2                                                                         |  30.207s  |  30.207s  |   0.000s  | 0.0%|
|n756-RC-00.smt2                                                                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n7562-prp-40-46.smt2                                                                        |  30.152s  |  30.152s  |   0.000s  | 0.0%|
|n7563-prp-40-47.smt2                                                                        |  30.139s  |  30.139s  |   0.000s  | 0.0%|
|n7579-prp-43-48.smt2                                                                        |  30.107s  |  30.107s  |   0.000s  | 0.0%|
|n7580-prp-43-49.smt2                                                                        |  30.121s  |  30.121s  |   0.000s  | 0.0%|
|n7583-prp-44-47.smt2                                                                        |  30.138s  |  30.138s  |   0.000s  | 0.0%|
|n7584-prp-44-48.smt2                                                                        |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|n7585-prp-44-49.smt2                                                                        |  30.161s  |  30.161s  |   0.000s  | 0.0%|
|n7587-prp-45-46.smt2                                                                        |  30.142s  |  30.142s  |   0.000s  | 0.0%|
|n7588-prp-45-47.smt2                                                                        |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|n7592-prp-46-46.smt2                                                                        |  30.121s  |  30.121s  |   0.000s  | 0.0%|
|n7594-prp-46-48.smt2                                                                        |  30.114s  |  30.114s  |   0.000s  | 0.0%|
|n76-unbd-sage17.smt2                                                                        |  30.023s  |  30.023s  |   0.000s  | 0.0%|
|n760-RC-04.smt2                                                                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|n7603-prp-48-47.smt2                                                                        |  30.125s  |  30.125s  |   0.000s  | 0.0%|
|n7605-prp-48-49.smt2                                                                        |  30.136s  |  30.136s  |   0.000s  | 0.0%|
|n7609-prp-49-48.smt2                                                                        |  30.146s  |  30.146s  |   0.000s  | 0.0%|
|n7618-prp-50-47.smt2                                                                        |  30.191s  |  30.191s  |   0.000s  | 0.0%|
|n7619-prp-50-48.smt2                                                                        |  30.165s  |  30.165s  |   0.000s  | 0.0%|
|n7633-prp-7-48.smt2                                                                         |  30.164s  |  30.164s  |   0.000s  | 0.0%|
|n7637-prp-8-47.smt2                                                                         |  30.166s  |  30.166s  |   0.000s  | 0.0%|
|n764-RC-08.smt2                                                                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|n7641-prp-9-46.smt2                                                                         |  30.115s  |  30.115s  |   0.000s  | 0.0%|
|n7642-prp-9-47.smt2                                                                         |  30.171s  |  30.171s  |   0.000s  | 0.0%|
|n7643-prp-9-48.smt2                                                                         |  30.148s  |  30.148s  |   0.000s  | 0.0%|
|n766-RC-10.smt2                                                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n7686-prp-16-46.smt2                                                                        |   1.527s  |   1.527s  |   0.000s  | 0.0%|
|n771-RC-15.smt2                                                                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n772-RF-00.smt2                                                                             |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|n773-RF-01.smt2                                                                             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n7736-prp-25-46.smt2                                                                        |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|n7739-prp-25-49.smt2                                                                        |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|n7776-prp-0-46.smt2                                                                         |  30.132s  |  30.132s  |   0.000s  | 0.0%|
|n7778-prp-0-48.smt2                                                                         |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|n778-RF-08.smt2                                                                             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|n7782-prp-1-47.smt2                                                                         |  30.097s  |  30.097s  |   0.000s  | 0.0%|
|n7783-prp-1-48.smt2                                                                         |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|n7785-prp-1-50.smt2                                                                         |  30.107s  |  30.107s  |   0.000s  | 0.0%|
|n7788-prp-11-48.smt2                                                                        |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|n7792-prp-12-47.smt2                                                                        |   3.968s  |   3.968s  |   0.000s  | 0.0%|
|n7793-prp-12-48.smt2                                                                        |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|n7799-prp-17-49.smt2                                                                        |   8.332s  |   8.332s  |   0.000s  | 0.0%|
|n78-unbd-sage19.smt2                                                                        |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|n7804-prp-20-49.smt2                                                                        |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|n7807-prp-24-41.smt2                                                                        |   2.032s  |   2.032s  |   0.000s  | 0.0%|
|n7809-prp-24-43.smt2                                                                        |   3.653s  |   3.653s  |   0.000s  | 0.0%|
|n7813-prp-34-41.smt2                                                                        |   3.131s  |   3.131s  |   0.000s  | 0.0%|
|n7815-prp-34-43.smt2                                                                        |   4.343s  |   4.343s  |   0.000s  | 0.0%|
|n7818-prp-35-44.smt2                                                                        |   3.498s  |   3.498s  |   0.000s  | 0.0%|
|n7823-prp-37-48.smt2                                                                        |  22.561s  |  22.561s  |   0.000s  | 0.0%|
|n7824-prp-37-49.smt2                                                                        |   7.659s  |   7.659s  |   0.000s  | 0.0%|
|n7829-prp-40-49.smt2                                                                        |  30.105s  |  30.105s  |   0.000s  | 0.0%|
|n784-RF-15.smt2                                                                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|n7847-prp-45-47.smt2                                                                        |  26.293s  |  26.293s  |   0.000s  | 0.0%|
|n7854-prp-47-46.smt2                                                                        |   5.938s  |   5.938s  |   0.000s  | 0.0%|
|n786-RC-01.smt2                                                                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|n7861-prp-48-48.smt2                                                                        |   9.488s  |   9.488s  |   0.000s  | 0.0%|
|n7869-prp-50-46.smt2                                                                        |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|n7872-prp-50-49.smt2                                                                        |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|n7873-prp-50-50.smt2                                                                        |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|n7877-prp-51-49.smt2                                                                        |   7.101s  |   7.101s  |   0.000s  | 0.0%|
|n788-RC-03.smt2                                                                             |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n7880-prp-52-47.smt2                                                                        |   4.377s  |   4.377s  |   0.000s  | 0.0%|
|n7882-prp-52-49.smt2                                                                        |   5.492s  |   5.492s  |   0.000s  | 0.0%|
|n7883-prp-52-50.smt2                                                                        |  14.752s  |  14.752s  |   0.000s  | 0.0%|
|n7888-prp-53-50.smt2                                                                        |  21.294s  |  21.294s  |   0.000s  | 0.0%|
|n7891-prp-54-48.smt2                                                                        |   0.519s  |   0.519s  |   0.000s  | 0.0%|
|n7892-prp-54-49.smt2                                                                        |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|n7894-prp-55-46.smt2                                                                        |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|n7898-prp-55-50.smt2                                                                        |   0.543s  |   0.543s  |   0.000s  | 0.0%|
|n7899-prp-56-46.smt2                                                                        |   5.605s  |   5.605s  |   0.000s  | 0.0%|
|n79-unbd-sage2.smt2                                                                         |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|n790-RC-05.smt2                                                                             |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n7903-prp-56-50.smt2                                                                        |   3.784s  |   3.784s  |   0.000s  | 0.0%|
|n7910-prp-58-47.smt2                                                                        |   4.713s  |   4.713s  |   0.000s  | 0.0%|
|n7915-prp-59-47.smt2                                                                        |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|n7916-prp-59-48.smt2                                                                        |   0.494s  |   0.494s  |   0.000s  | 0.0%|
|n7920-prp-60-47.smt2                                                                        |   4.195s  |   4.195s  |   0.000s  | 0.0%|
|n7922-prp-60-49.smt2                                                                        |  10.721s  |  10.721s  |   0.000s  | 0.0%|
|n7923-prp-60-50.smt2                                                                        |   6.337s  |   6.337s  |   0.000s  | 0.0%|
|n7924-prp-61-46.smt2                                                                        |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|n7925-prp-61-47.smt2                                                                        |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|n7929-prp-62-46.smt2                                                                        |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|n793-RC-08.smt2                                                                             |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|n7932-prp-62-49.smt2                                                                        |   6.583s  |   6.583s  |   0.000s  | 0.0%|
|n7934-prp-63-47.smt2                                                                        |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|n7936-prp-63-49.smt2                                                                        |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|n7940-prp-7-48.smt2                                                                         |  30.105s  |  30.105s  |   0.000s  | 0.0%|
|n7943-prp-8-46.smt2                                                                         |   4.288s  |   4.288s  |   0.000s  | 0.0%|
|n7944-prp-8-47.smt2                                                                         |   6.283s  |   6.283s  |   0.000s  | 0.0%|
|n7946-prp-8-49.smt2                                                                         |   9.482s  |   9.482s  |   0.000s  | 0.0%|
|n7949-prp-0-48.smt2                                                                         |   2.278s  |   2.278s  |   0.000s  | 0.0%|
|n795-RC-10.smt2                                                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|n7956-prp-0-46.smt2                                                                         |  30.122s  |  30.122s  |   0.000s  | 0.0%|
|n7958-prp-0-48.smt2                                                                         |  30.141s  |  30.141s  |   0.000s  | 0.0%|
|n7959-prp-0-49.smt2                                                                         |  30.158s  |  30.158s  |   0.000s  | 0.0%|
|n7961-prp-1-46.smt2                                                                         |  30.089s  |  30.089s  |   0.000s  | 0.0%|
|n7970-prp-10-50.smt2                                                                        |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|n7971-prp-11-46.smt2                                                                        |  30.144s  |  30.144s  |   0.000s  | 0.0%|
|n7977-prp-12-47.smt2                                                                        |  30.129s  |  30.129s  |   0.000s  | 0.0%|
|n7979-prp-12-49.smt2                                                                        |  30.110s  |  30.110s  |   0.000s  | 0.0%|
|n7982-prp-13-47.smt2                                                                        |  30.111s  |  30.111s  |   0.000s  | 0.0%|
|n7983-prp-13-48.smt2                                                                        |  30.107s  |  30.107s  |   0.000s  | 0.0%|
|n7984-prp-13-49.smt2                                                                        |  30.173s  |  30.173s  |   0.000s  | 0.0%|
|n7986-prp-14-46.smt2                                                                        |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|n7987-prp-14-47.smt2                                                                        |  30.111s  |  30.111s  |   0.000s  | 0.0%|
|n7990-prp-14-50.smt2                                                                        |  30.130s  |  30.130s  |   0.000s  | 0.0%|
|n7991-prp-15-46.smt2                                                                        |  30.142s  |  30.142s  |   0.000s  | 0.0%|
|n7993-prp-15-48.smt2                                                                        |  30.156s  |  30.156s  |   0.000s  | 0.0%|
|n7994-prp-15-49.smt2                                                                        |  30.184s  |  30.184s  |   0.000s  | 0.0%|
|n8000-prp-16-50.smt2                                                                        |  30.181s  |  30.181s  |   0.000s  | 0.0%|
|n8001-prp-17-46.smt2                                                                        |  30.165s  |  30.165s  |   0.000s  | 0.0%|
|n8002-prp-17-47.smt2                                                                        |  30.104s  |  30.104s  |   0.000s  | 0.0%|
|n8003-prp-17-48.smt2                                                                        |  30.112s  |  30.112s  |   0.000s  | 0.0%|
|n8005-prp-17-50.smt2                                                                        |  30.145s  |  30.145s  |   0.000s  | 0.0%|
|n8006-prp-18-46.smt2                                                                        |  30.111s  |  30.111s  |   0.000s  | 0.0%|
|n8007-prp-18-47.smt2                                                                        |  30.135s  |  30.135s  |   0.000s  | 0.0%|
|n8010-prp-18-50.smt2                                                                        |  30.156s  |  30.156s  |   0.000s  | 0.0%|
|n8015-prp-19-50.smt2                                                                        |  30.141s  |  30.141s  |   0.000s  | 0.0%|
|n8017-prp-2-47.smt2                                                                         |  30.112s  |  30.112s  |   0.000s  | 0.0%|
|n8019-prp-2-49.smt2                                                                         |  30.119s  |  30.119s  |   0.000s  | 0.0%|
|n802-RF-01.smt2                                                                             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n8023-prp-20-48.smt2                                                                        |  30.171s  |  30.171s  |   0.000s  | 0.0%|
|n8025-prp-20-50.smt2                                                                        |  30.154s  |  30.154s  |   0.000s  | 0.0%|
|n8026-prp-21-46.smt2                                                                        |  30.186s  |  30.186s  |   0.000s  | 0.0%|
|n8028-prp-21-48.smt2                                                                        |  30.163s  |  30.163s  |   0.000s  | 0.0%|
|n8029-prp-21-49.smt2                                                                        |  30.171s  |  30.171s  |   0.000s  | 0.0%|
|n8030-prp-21-50.smt2                                                                        |  30.142s  |  30.142s  |   0.000s  | 0.0%|
|n8033-prp-22-48.smt2                                                                        |  30.129s  |  30.129s  |   0.000s  | 0.0%|
|n8037-prp-23-47.smt2                                                                        |  30.107s  |  30.107s  |   0.000s  | 0.0%|
|n8040-prp-23-50.smt2                                                                        |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|n8041-prp-24-46.smt2                                                                        |  30.133s  |  30.133s  |   0.000s  | 0.0%|
|n8042-prp-24-47.smt2                                                                        |  30.178s  |  30.178s  |   0.000s  | 0.0%|
|n8047-prp-3-47.smt2                                                                         |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|n8049-prp-3-49.smt2                                                                         |  30.167s  |  30.167s  |   0.000s  | 0.0%|
|n8050-prp-3-50.smt2                                                                         |  30.151s  |  30.151s  |   0.000s  | 0.0%|
|n8054-prp-4-49.smt2                                                                         |  30.155s  |  30.155s  |   0.000s  | 0.0%|
|n8055-prp-4-50.smt2                                                                         |  30.154s  |  30.154s  |   0.000s  | 0.0%|
|n8056-prp-5-46.smt2                                                                         |  30.122s  |  30.122s  |   0.000s  | 0.0%|
|n8059-prp-5-49.smt2                                                                         |  30.139s  |  30.139s  |   0.000s  | 0.0%|
|n8064-prp-6-49.smt2                                                                         |  30.128s  |  30.128s  |   0.000s  | 0.0%|
|n8070-prp-7-50.smt2                                                                         |  30.167s  |  30.167s  |   0.000s  | 0.0%|
|n8072-prp-8-47.smt2                                                                         |  30.112s  |  30.112s  |   0.000s  | 0.0%|
|n8077-prp-9-47.smt2                                                                         |  30.083s  |  30.083s  |   0.000s  | 0.0%|
|n8079-prp-9-49.smt2                                                                         |  30.120s  |  30.120s  |   0.000s  | 0.0%|
|n8080-prp-9-50.smt2                                                                         |  30.157s  |  30.157s  |   0.000s  | 0.0%|
|n8111-prp-13-31.smt2                                                                        |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|n8112-prp-13-32.smt2                                                                        |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|n8115-prp-14-33.smt2                                                                        |   1.002s  |   1.002s  |   0.000s  | 0.0%|
|n8127-prp-21-38.smt2                                                                        |   4.185s  |   4.185s  |   0.000s  | 0.0%|
|n8134-prp-22-32.smt2                                                                        |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|n8146-prp-27-38.smt2                                                                        |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|n815-RF-14.smt2                                                                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|n8158-prp-32-37.smt2                                                                        |   1.715s  |   1.715s  |   0.000s  | 0.0%|
|n8159-prp-32-38.smt2                                                                        |   2.306s  |   2.306s  |   0.000s  | 0.0%|
|n8165-prp-34-40.smt2                                                                        |   2.722s  |   2.722s  |   0.000s  | 0.0%|
|n8171-prp-41-39.smt2                                                                        |   0.849s  |   0.849s  |   0.000s  | 0.0%|
|n8173-prp-42-39.smt2                                                                        |   1.765s  |   1.765s  |   0.000s  | 0.0%|
|n8180-prp-0-50.smt2                                                                         |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|n8185-prp-3-21.smt2                                                                         |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|n8188-prp-5-20.smt2                                                                         |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n8190-prp-5-22.smt2                                                                         |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|n8191-prp-5-23.smt2                                                                         |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|n82-unbd-sage22.smt2                                                                        |   2.667s  |   2.667s  |   0.000s  | 0.0%|
|n8211-ring_2exp10_6vars_2ite_unsat.smt2                                                     |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|n8214-ring_2exp10_6vars_5ite_unsat.smt2                                                     |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|n8219-ring_2exp10_7vars_4ite_unsat.smt2                                                     |   8.770s  |   8.770s  |   0.000s  | 0.0%|
|n8220-ring_2exp10_7vars_5ite_unsat.smt2                                                     |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|n8225-ring_2exp10_8vars_3ite_unsat.smt2                                                     |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|n8226-ring_2exp10_8vars_4ite_unsat.smt2                                                     |  23.244s  |  23.244s  |   0.000s  | 0.0%|
|n8227-ring_2exp10_8vars_5ite_unsat.smt2                                                     |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|n8228-ring_2exp10_8vars_6ite_unsat.smt2                                                     |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|n8235-ring_2exp10_9vars_5ite_unsat.smt2                                                     |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|n8237-ring_2exp10_9vars_7ite_unsat.smt2                                                     |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|n8246-ring_2exp12_5vars_0ite_unsat.smt2                                                     |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n8249-ring_2exp12_5vars_3ite_unsat.smt2                                                     |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|n825-RC-08.smt2                                                                             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|n8252-ring_2exp12_6vars_1ite_unsat.smt2                                                     |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|n8254-ring_2exp12_6vars_3ite_unsat.smt2                                                     |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|n8261-ring_2exp12_7vars_4ite_unsat.smt2                                                     |  13.023s  |  13.023s  |   0.000s  | 0.0%|
|n8262-ring_2exp12_7vars_5ite_unsat.smt2                                                     |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|n8265-ring_2exp12_8vars_1ite_unsat.smt2                                                     |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|n8266-ring_2exp12_8vars_2ite_unsat.smt2                                                     |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|n827-RC-10.smt2                                                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|n8270-ring_2exp12_8vars_6ite_unsat.smt2                                                     |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|n8271-ring_2exp12_8vars_7ite_unsat.smt2                                                     |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|n8273-ring_2exp12_9vars_1ite_unsat.smt2                                                     |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|n8274-ring_2exp12_9vars_2ite_unsat.smt2                                                     |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|n8284-ring_2exp14_4vars_0ite_unsat.smt2                                                     |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|n8285-ring_2exp14_4vars_1ite_unsat.smt2                                                     |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|n8288-ring_2exp14_5vars_0ite_unsat.smt2                                                     |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|n8291-ring_2exp14_5vars_3ite_unsat.smt2                                                     |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|n8292-ring_2exp14_5vars_4ite_unsat.smt2                                                     |   0.635s  |   0.635s  |   0.000s  | 0.0%|
|n8294-ring_2exp14_6vars_1ite_unsat.smt2                                                     |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|n831-RC-14.smt2                                                                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|n8310-ring_2exp14_8vars_4ite_unsat.smt2                                                     |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|n8311-ring_2exp14_8vars_5ite_unsat.smt2                                                     |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|n8312-ring_2exp14_8vars_6ite_unsat.smt2                                                     |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|n8314-ring_2exp14_9vars_0ite_unsat.smt2                                                     |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|n8318-ring_2exp14_9vars_4ite_unsat.smt2                                                     |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|n8319-ring_2exp14_9vars_5ite_unsat.smt2                                                     |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|n832-RC-15.smt2                                                                             |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|n8322-ring_2exp14_9vars_8ite_unsat.smt2                                                     |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|n8324-ring_2exp16_3vars_1ite_unsat.smt2                                                     |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|n8332-ring_2exp16_5vars_2ite_unsat.smt2                                                     |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|n8336-ring_2exp16_6vars_1ite_unsat.smt2                                                     |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|n8350-ring_2exp16_8vars_2ite_unsat.smt2                                                     |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|n8351-ring_2exp16_8vars_3ite_unsat.smt2                                                     |   0.954s  |   0.954s  |   0.000s  | 0.0%|
|n8352-ring_2exp16_8vars_4ite_unsat.smt2                                                     |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|n8354-ring_2exp16_8vars_6ite_unsat.smt2                                                     |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|n8355-ring_2exp16_8vars_7ite_unsat.smt2                                                     |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|n8358-ring_2exp16_9vars_2ite_unsat.smt2                                                     |   0.594s  |   0.594s  |   0.000s  | 0.0%|
|n8360-ring_2exp16_9vars_4ite_unsat.smt2                                                     |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|n8361-ring_2exp16_9vars_5ite_unsat.smt2                                                     |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|n8364-ring_2exp16_9vars_8ite_unsat.smt2                                                     |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|n8366-ring_2exp4_3vars_1ite_unsat.smt2                                                      |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|n8369-ring_2exp4_4vars_1ite_unsat.smt2                                                      |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|n8378-ring_2exp4_6vars_1ite_unsat.smt2                                                      |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|n8396-ring_2exp4_8vars_6ite_unsat.smt2                                                      |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|n8400-ring_2exp4_9vars_2ite_unsat.smt2                                                      |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|n8408-ring_2exp6_3vars_1ite_unsat.smt2                                                      |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|n8411-ring_2exp6_4vars_1ite_unsat.smt2                                                      |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|n8424-ring_2exp6_6vars_5ite_unsat.smt2                                                      |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|n8431-ring_2exp6_7vars_6ite_unsat.smt2                                                      |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|n8438-ring_2exp6_8vars_6ite_unsat.smt2                                                      |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|n8439-ring_2exp6_8vars_7ite_unsat.smt2                                                      |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|n8441-ring_2exp6_9vars_1ite_unsat.smt2                                                      |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|n8446-ring_2exp6_9vars_6ite_unsat.smt2                                                      |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|n8447-ring_2exp6_9vars_7ite_unsat.smt2                                                      |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|n8459-ring_2exp8_5vars_3ite_unsat.smt2                                                      |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|n8462-ring_2exp8_6vars_1ite_unsat.smt2                                                      |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|n8469-ring_2exp8_7vars_2ite_unsat.smt2                                                      |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|n8472-ring_2exp8_7vars_5ite_unsat.smt2                                                      |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|n8473-ring_2exp8_7vars_6ite_unsat.smt2                                                      |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|n8474-ring_2exp8_8vars_0ite_unsat.smt2                                                      |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|n8476-ring_2exp8_8vars_2ite_unsat.smt2                                                      |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|n8484-ring_2exp8_9vars_2ite_unsat.smt2                                                      |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|n8486-ring_2exp8_9vars_4ite_unsat.smt2                                                      |  30.029s  |  30.029s  |   0.000s  | 0.0%|
|n8488-ring_2exp8_9vars_6ite_unsat.smt2                                                      |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|n8489-ring_2exp8_9vars_7ite_unsat.smt2                                                      |  30.028s  |  30.028s  |   0.000s  | 0.0%|
|n87-unbd-sage5.smt2                                                                         |   2.525s  |   2.525s  |   0.000s  | 0.0%|
|n89-unbd-sage7.smt2                                                                         |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|n9-cut_lemma_01_004.smt2.slack.smt2                                                         |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|n92-unbd-sage0.smt2                                                                         |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|n93-unbd-sage1.smt2                                                                         |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|n95-unbd-sage11.smt2                                                                        |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|normalized-1096.cudf.paranoid.smt2                                                          |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|p2756.sat.smt2                                                                              |   0.739s  |   0.739s  |   0.000s  | 0.0%|
|pigeon-hole-3.smt2                                                                          |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|pigeon-hole-5.smt2                                                                          |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|prime_cone_unsat_14.smt2                                                                    |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|prime_cone_unsat_15.smt2                                                                    |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|problem-004282.cvc.1.smt2                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|problem-004284.cvc.1.smt2                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|problem-004285.cvc.1.smt2                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|problem-004296.cvc.1.smt2                                                                   |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|problem-004316.cvc.1.smt2                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|problem-004317.cvc.1.smt2                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|problem-004327.cvc.1.smt2                                                                   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|problem-004335.cvc.1.smt2                                                                   |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|problem-005675.cvc.2.smt2                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|prp-0-196.smt2                                                                              |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|prp-0-197.smt2                                                                              |  30.103s  |  30.103s  |   0.000s  | 0.0%|
|prp-0-198.smt2                                                                              |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|prp-0-199.smt2                                                                              |  30.110s  |  30.110s  |   0.000s  | 0.0%|
|prp-0-200.smt2                                                                              |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|prp-1-196.smt2                                                                              |   2.402s  |   2.402s  |   0.000s  | 0.0%|
|prp-1-199.smt2                                                                              |   2.426s  |   2.426s  |   0.000s  | 0.0%|
|prp-11-25.smt2                                                                              |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|prp-12-31.smt2                                                                              |   1.233s  |   1.233s  |   0.000s  | 0.0%|
|prp-13-40.smt2                                                                              |   6.544s  |   6.544s  |   0.000s  | 0.0%|
|prp-13-45.smt2                                                                              |  30.154s  |  30.154s  |   0.000s  | 0.0%|
|prp-14-45.smt2                                                                              |  30.141s  |  30.141s  |   0.000s  | 0.0%|
|prp-15-33.smt2                                                                              |   2.245s  |   2.245s  |   0.000s  | 0.0%|
|prp-15-34.smt2                                                                              |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|prp-16-34.smt2                                                                              |   2.463s  |   2.463s  |   0.000s  | 0.0%|
|prp-17-33.smt2                                                                              |   3.378s  |   3.378s  |   0.000s  | 0.0%|
|prp-17-34.smt2                                                                              |   2.470s  |   2.470s  |   0.000s  | 0.0%|
|prp-17-36.smt2                                                                              |   8.425s  |   8.425s  |   0.000s  | 0.0%|
|prp-18-33.smt2                                                                              |   3.542s  |   3.542s  |   0.000s  | 0.0%|
|prp-19-32.smt2                                                                              |   4.100s  |   4.100s  |   0.000s  | 0.0%|
|prp-19-41.smt2                                                                              |  11.946s  |  11.946s  |   0.000s  | 0.0%|
|prp-2-16.smt2                                                                               |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|prp-2-17.smt2                                                                               |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|prp-2-197.smt2                                                                              |  30.154s  |  30.154s  |   0.000s  | 0.0%|
|prp-2-199.smt2                                                                              |  30.120s  |  30.120s  |   0.000s  | 0.0%|
|prp-2-200.smt2                                                                              |  30.174s  |  30.174s  |   0.000s  | 0.0%|
|prp-20-29.smt2                                                                              |   1.895s  |   1.895s  |   0.000s  | 0.0%|
|prp-20-32.smt2                                                                              |   3.124s  |   3.124s  |   0.000s  | 0.0%|
|prp-20-33.smt2                                                                              |   3.307s  |   3.307s  |   0.000s  | 0.0%|
|prp-20-35.smt2                                                                              |   5.547s  |   5.547s  |   0.000s  | 0.0%|
|prp-20-42.smt2                                                                              |   9.433s  |   9.433s  |   0.000s  | 0.0%|
|prp-20-43.smt2                                                                              |  30.128s  |  30.128s  |   0.000s  | 0.0%|
|prp-20-45.smt2                                                                              |  30.125s  |  30.125s  |   0.000s  | 0.0%|
|prp-21-32.smt2                                                                              |   2.581s  |   2.581s  |   0.000s  | 0.0%|
|prp-22-33.smt2                                                                              |   4.675s  |   4.675s  |   0.000s  | 0.0%|
|prp-22-35.smt2                                                                              |   7.489s  |   7.489s  |   0.000s  | 0.0%|
|prp-23-39.smt2                                                                              |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|prp-23-41.smt2                                                                              |  30.103s  |  30.103s  |   0.000s  | 0.0%|
|prp-24-32.smt2                                                                              |   3.952s  |   3.952s  |   0.000s  | 0.0%|
|prp-24-33.smt2                                                                              |   6.712s  |   6.712s  |   0.000s  | 0.0%|
|prp-24-35.smt2                                                                              |   5.968s  |   5.968s  |   0.000s  | 0.0%|
|prp-24-45.smt2                                                                              |  30.146s  |  30.146s  |   0.000s  | 0.0%|
|prp-25-45.smt2                                                                              |  30.150s  |  30.150s  |   0.000s  | 0.0%|
|prp-26-33.smt2                                                                              |   3.868s  |   3.868s  |   0.000s  | 0.0%|
|prp-27-33.smt2                                                                              |  14.283s  |  14.283s  |   0.000s  | 0.0%|
|prp-27-44.smt2                                                                              |  30.104s  |  30.104s  |   0.000s  | 0.0%|
|prp-27-45.smt2                                                                              |  30.109s  |  30.109s  |   0.000s  | 0.0%|
|prp-28-33.smt2                                                                              |   6.289s  |   6.289s  |   0.000s  | 0.0%|
|prp-28-39.smt2                                                                              |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|prp-29-36.smt2                                                                              |   7.636s  |   7.636s  |   0.000s  | 0.0%|
|prp-29-44.smt2                                                                              |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|prp-29-45.smt2                                                                              |  30.156s  |  30.156s  |   0.000s  | 0.0%|
|prp-3-28.smt2                                                                               |   1.064s  |   1.064s  |   0.000s  | 0.0%|
|prp-3-45.smt2                                                                               |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|prp-30-36.smt2                                                                              |  13.447s  |  13.447s  |   0.000s  | 0.0%|
|prp-30-43.smt2                                                                              |  15.314s  |  15.314s  |   0.000s  | 0.0%|
|prp-30-44.smt2                                                                              |  30.120s  |  30.120s  |   0.000s  | 0.0%|
|prp-31-35.smt2                                                                              |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|prp-31-43.smt2                                                                              |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|prp-32-32.smt2                                                                              |   4.826s  |   4.826s  |   0.000s  | 0.0%|
|prp-32-44.smt2                                                                              |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|prp-33-32.smt2                                                                              |   4.316s  |   4.316s  |   0.000s  | 0.0%|
|prp-33-34.smt2                                                                              |   7.777s  |   7.777s  |   0.000s  | 0.0%|
|prp-33-35.smt2                                                                              |   7.624s  |   7.624s  |   0.000s  | 0.0%|
|prp-34-33.smt2                                                                              |   4.526s  |   4.526s  |   0.000s  | 0.0%|
|prp-35-36.smt2                                                                              |  30.117s  |  30.117s  |   0.000s  | 0.0%|
|prp-35-39.smt2                                                                              |   0.692s  |   0.692s  |   0.000s  | 0.0%|
|prp-35-40.smt2                                                                              |   0.883s  |   0.883s  |   0.000s  | 0.0%|
|prp-35-41.smt2                                                                              |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|prp-36-34.smt2                                                                              |   6.300s  |   6.300s  |   0.000s  | 0.0%|
|prp-36-42.smt2                                                                              |  30.112s  |  30.112s  |   0.000s  | 0.0%|
|prp-37-44.smt2                                                                              |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|prp-39-40.smt2                                                                              |  30.107s  |  30.107s  |   0.000s  | 0.0%|
|prp-39-44.smt2                                                                              |  30.111s  |  30.111s  |   0.000s  | 0.0%|
|prp-39-45.smt2                                                                              |  30.134s  |  30.134s  |   0.000s  | 0.0%|
|prp-4-32.smt2                                                                               |   3.167s  |   3.167s  |   0.000s  | 0.0%|
|prp-4-39.smt2                                                                               |  29.886s  |  29.886s  |   0.000s  | 0.0%|
|prp-4-41.smt2                                                                               |  14.126s  |  14.126s  |   0.000s  | 0.0%|
|prp-4-42.smt2                                                                               |  30.125s  |  30.125s  |   0.000s  | 0.0%|
|prp-4-43.smt2                                                                               |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|prp-40-40.smt2                                                                              |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|prp-40-42.smt2                                                                              |  30.112s  |  30.112s  |   0.000s  | 0.0%|
|prp-40-43.smt2                                                                              |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|prp-42-44.smt2                                                                              |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|prp-43-39.smt2                                                                              |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|prp-43-40.smt2                                                                              |  30.106s  |  30.106s  |   0.000s  | 0.0%|
|prp-43-45.smt2                                                                              |  30.147s  |  30.147s  |   0.000s  | 0.0%|
|prp-45-41.smt2                                                                              |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|prp-46-40.smt2                                                                              |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|prp-46-45.smt2                                                                              |  30.138s  |  30.138s  |   0.000s  | 0.0%|
|prp-47-42.smt2                                                                              |  30.163s  |  30.163s  |   0.000s  | 0.0%|
|prp-47-44.smt2                                                                              |  30.119s  |  30.119s  |   0.000s  | 0.0%|
|prp-49-43.smt2                                                                              |  30.114s  |  30.114s  |   0.000s  | 0.0%|
|prp-49-44.smt2                                                                              |  30.084s  |  30.084s  |   0.000s  | 0.0%|
|prp-5-25.smt2                                                                               |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|prp-5-32.smt2                                                                               |   1.163s  |   1.163s  |   0.000s  | 0.0%|
|prp-5-33.smt2                                                                               |   1.833s  |   1.833s  |   0.000s  | 0.0%|
|prp-5-34.smt2                                                                               |  10.159s  |  10.159s  |   0.000s  | 0.0%|
|prp-5-36.smt2                                                                               |   4.924s  |   4.924s  |   0.000s  | 0.0%|
|prp-5-37.smt2                                                                               |   4.730s  |   4.730s  |   0.000s  | 0.0%|
|prp-5-38.smt2                                                                               |   5.355s  |   5.355s  |   0.000s  | 0.0%|
|prp-5-41.smt2                                                                               |  17.495s  |  17.495s  |   0.000s  | 0.0%|
|prp-5-42.smt2                                                                               |  30.114s  |  30.114s  |   0.000s  | 0.0%|
|prp-5-44.smt2                                                                               |  30.133s  |  30.133s  |   0.000s  | 0.0%|
|prp-50-43.smt2                                                                              |  30.110s  |  30.110s  |   0.000s  | 0.0%|
|prp-50-44.smt2                                                                              |  30.109s  |  30.109s  |   0.000s  | 0.0%|
|prp-6-29.smt2                                                                               |   0.981s  |   0.981s  |   0.000s  | 0.0%|
|prp-7-32.smt2                                                                               |   0.853s  |   0.853s  |   0.000s  | 0.0%|
|prp-7-38.smt2                                                                               |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|prp-7-40.smt2                                                                               |  12.562s  |  12.562s  |   0.000s  | 0.0%|
|prp-7-43.smt2                                                                               |  20.509s  |  20.509s  |   0.000s  | 0.0%|
|prp-75-48.smt2                                                                              |  11.054s  |  11.054s  |   0.000s  | 0.0%|
|prp-8-21.smt2                                                                               |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|prp-8-25.smt2                                                                               |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|prp-8-27.smt2                                                                               |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|prp-8-33.smt2                                                                               |   2.512s  |   2.512s  |   0.000s  | 0.0%|
|prp-8-34.smt2                                                                               |   3.186s  |   3.186s  |   0.000s  | 0.0%|
|prp-8-36.smt2                                                                               |   9.472s  |   9.472s  |   0.000s  | 0.0%|
|prp-8-39.smt2                                                                               |   8.808s  |   8.808s  |   0.000s  | 0.0%|
|prp-8-42.smt2                                                                               |   9.383s  |   9.383s  |   0.000s  | 0.0%|
|prp-8-43.smt2                                                                               |  30.143s  |  30.143s  |   0.000s  | 0.0%|
|prp-8-44.smt2                                                                               |  30.142s  |  30.142s  |   0.000s  | 0.0%|
|v10_problem_2__001.smt2.slack.smt2                                                          |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|v10_problem__003.smt2.slack.smt2                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|v15_problem_2__011.smt2.slack.smt2                                                          |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|v15_problem_2__017.smt2.slack.smt2                                                          |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|v15_problem__013.smt2.slack.smt2                                                            |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|v15_problem__022.smt2.slack.smt2                                                            |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|v15_problem__023.smt2.slack.smt2                                                            |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|v20_problem_2__004.smt2.slack.smt2                                                          |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|v20_problem_2__014.smt2.slack.smt2                                                          |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|v20_problem_2__017.smt2.slack.smt2                                                          |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|v20_problem_2__028.smt2.slack.smt2                                                          |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|v20_problem__006.smt2.slack.smt2                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|v20_problem__008.smt2.slack.smt2                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|v20_problem__011.smt2.slack.smt2                                                            |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|v20_problem__014.smt2.slack.smt2                                                            |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|v25_problem_2__018.smt2.slack.smt2                                                          |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|v25_problem_2__026.smt2.slack.smt2                                                          |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|v25_problem_2__028.smt2.slack.smt2                                                          |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|v25_problem__021.smt2.slack.smt2                                                            |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|v25_problem__031.smt2.slack.smt2                                                            |   3.470s  |   3.470s  |   0.000s  | 0.0%|
|v30_problem_2__016.smt2.slack.smt2                                                          |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|v30_problem_2__017.smt2.slack.smt2                                                          |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|v30_problem_2__018.smt2.slack.smt2                                                          |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|v30_problem_2__029.smt2.slack.smt2                                                          |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|v30_problem_2__033.smt2.slack.smt2                                                          |   1.357s  |   1.357s  |   0.000s  | 0.0%|
|v30_problem__003.smt2.slack.smt2                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|v30_problem__010.smt2.slack.smt2                                                            |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|v30_problem__013.smt2.slack.smt2                                                            |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|v30_problem__024.smt2.slack.smt2                                                            |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|v35_problem_2__011.smt2.slack.smt2                                                          |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|v35_problem_2__018.smt2.slack.smt2                                                          |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|v35_problem_2__019.smt2.slack.smt2                                                          |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|v35_problem_2__021.smt2.slack.smt2                                                          |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|v35_problem_2__027.smt2.slack.smt2                                                          |   0.520s  |   0.520s  |   0.000s  | 0.0%|
|v35_problem__011.smt2.slack.smt2                                                            |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|v35_problem__033.smt2.slack.smt2                                                            |   0.798s  |   0.798s  |   0.000s  | 0.0%|
|v40_problem_2__006.smt2.slack.smt2                                                          |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|v40_problem_2__007.smt2.slack.smt2                                                          |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|v40_problem_2__018.smt2.slack.smt2                                                          |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|v40_problem_2__021.smt2.slack.smt2                                                          |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|v40_problem_2__027.smt2.slack.smt2                                                          |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|v40_problem_2__031.smt2.slack.smt2                                                          |   1.422s  |   1.422s  |   0.000s  | 0.0%|
|v40_problem__002.smt2.slack.smt2                                                            |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|v40_problem__015.smt2.slack.smt2                                                            |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|v40_problem__018.smt2.slack.smt2                                                            |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|v40_problem__019.smt2.slack.smt2                                                            |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|v45_problem_2__006.smt2.slack.smt2                                                          |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|v45_problem_2__014.smt2.slack.smt2                                                          |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|v45_problem_2__020.smt2.slack.smt2                                                          |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|v45_problem_2__027.smt2.slack.smt2                                                          |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|v45_problem__011.smt2.slack.smt2                                                            |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|v45_problem__024.smt2.slack.smt2                                                            |   0.232s  |   0.232s  |   0.000s  | 0.0%|
</details>
