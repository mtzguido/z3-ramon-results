Comparing data and data


# SUMMARY
- LHS tests = 24
- RHS tests = 24
- LHS success = 24  (100.0%)
- RHS success = 24  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_RDL-timeout20min-bb2-no_default_tactic-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=true smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_RDL
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_RDL-timeout20min-bb2-no_default_tactic-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=true smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_RDL
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.648s  |1200.648s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.246s  |1200.246s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.742s  |1200.742s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.787s  |1200.787s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.294s  |1200.294s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.670s  |1200.670s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.192s  |1200.192s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.835s  |1200.835s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 711.926s  | 711.926s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.831s  |1200.831s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.647s  |1200.647s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.789s  |1200.789s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.205s  |1200.205s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.282s  |1200.282s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.699s  |1200.699s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.629s  |1200.629s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.791s  |1200.791s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.648s  |1200.648s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.246s  |1200.246s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.742s  |1200.742s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.787s  |1200.787s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.294s  |1200.294s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.670s  |1200.670s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.192s  |1200.192s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.835s  |1200.835s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 711.926s  | 711.926s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.831s  |1200.831s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.647s  |1200.647s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.789s  |1200.789s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.205s  |1200.205s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.282s  |1200.282s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.699s  |1200.699s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.629s  |1200.629s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.791s  |1200.791s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.648s  |1200.648s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.246s  |1200.246s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.742s  |1200.742s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.787s  |1200.787s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.294s  |1200.294s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.670s  |1200.670s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.192s  |1200.192s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.835s  |1200.835s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 711.926s  | 711.926s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.831s  |1200.831s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.647s  |1200.647s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.789s  |1200.789s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.205s  |1200.205s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.282s  |1200.282s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.699s  |1200.699s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.629s  |1200.629s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.791s  |1200.791s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.648s  |1200.648s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.246s  |1200.246s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.742s  |1200.742s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.787s  |1200.787s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.294s  |1200.294s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.670s  |1200.670s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.192s  |1200.192s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.835s  |1200.835s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 711.926s  | 711.926s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.831s  |1200.831s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.647s  |1200.647s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.789s  |1200.789s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.205s  |1200.205s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.282s  |1200.282s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.699s  |1200.699s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.629s  |1200.629s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.791s  |1200.791s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled19322.smt2                                                                        |1200.835s |5432.0MiB|
|scrambled36439.smt2                                                                        |1200.831s |5199.0MiB|
|scrambled68857.smt2                                                                        |1200.791s |5426.0MiB|
|scrambled43005.smt2                                                                        |1200.789s |5442.0MiB|
|scrambled116502.smt2                                                                       |1200.787s |5393.0MiB|
|scrambled114492.smt2                                                                       |1200.742s |5228.0MiB|
|scrambled57711.smt2                                                                        |1200.699s |5362.0MiB|
|scrambled120626.smt2                                                                       |1200.670s |5445.0MiB|
|scrambled106386.smt2                                                                       |1200.648s |5419.0MiB|
|scrambled36692.smt2                                                                        |1200.647s |5164.0MiB|
|scrambled64619.smt2                                                                        |1200.629s |5297.0MiB|
|scrambled118796.smt2                                                                       |1200.294s |1214.0MiB|
|scrambled55916.smt2                                                                        |1200.282s |1215.0MiB|
|scrambled111948.smt2                                                                       |1200.246s |1274.0MiB|
|scrambled7069.smt2                                                                         |1200.245s |1257.0MiB|
|scrambled69775.smt2                                                                        |1200.241s |1396.0MiB|
|scrambled103130.smt2                                                                       |1200.219s |1292.0MiB|
|scrambled5175.smt2                                                                         |1200.212s |1183.0MiB|
|scrambled73226.smt2                                                                        |1200.208s |1237.0MiB|
|scrambled43798.smt2                                                                        |1200.205s |1119.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled19322.smt2                                                                        |1200.835s |5432.0MiB|
|scrambled36439.smt2                                                                        |1200.831s |5199.0MiB|
|scrambled68857.smt2                                                                        |1200.791s |5426.0MiB|
|scrambled43005.smt2                                                                        |1200.789s |5442.0MiB|
|scrambled116502.smt2                                                                       |1200.787s |5393.0MiB|
|scrambled114492.smt2                                                                       |1200.742s |5228.0MiB|
|scrambled57711.smt2                                                                        |1200.699s |5362.0MiB|
|scrambled120626.smt2                                                                       |1200.670s |5445.0MiB|
|scrambled106386.smt2                                                                       |1200.648s |5419.0MiB|
|scrambled36692.smt2                                                                        |1200.647s |5164.0MiB|
|scrambled64619.smt2                                                                        |1200.629s |5297.0MiB|
|scrambled118796.smt2                                                                       |1200.294s |1214.0MiB|
|scrambled55916.smt2                                                                        |1200.282s |1215.0MiB|
|scrambled111948.smt2                                                                       |1200.246s |1274.0MiB|
|scrambled7069.smt2                                                                         |1200.245s |1257.0MiB|
|scrambled69775.smt2                                                                        |1200.241s |1396.0MiB|
|scrambled103130.smt2                                                                       |1200.219s |1292.0MiB|
|scrambled5175.smt2                                                                         |1200.212s |1183.0MiB|
|scrambled73226.smt2                                                                        |1200.208s |1237.0MiB|
|scrambled43798.smt2                                                                        |1200.205s |1119.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1292.0MiB|1292.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |1165.0MiB|1165.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |5419.0MiB|5419.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |1274.0MiB|1274.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |5228.0MiB|5228.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |5393.0MiB|5393.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |1214.0MiB|1214.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |5445.0MiB|5445.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |1397.0MiB|1397.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |5432.0MiB|5432.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |1033.0MiB|1033.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |5199.0MiB|5199.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |5164.0MiB|5164.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |5442.0MiB|5442.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |1119.0MiB|1119.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |1183.0MiB|1183.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |1215.0MiB|1215.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |5362.0MiB|5362.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |5297.0MiB|5297.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |5426.0MiB|5426.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1292.0MiB|1292.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |1165.0MiB|1165.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |5419.0MiB|5419.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |1274.0MiB|1274.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |5228.0MiB|5228.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |5393.0MiB|5393.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |1214.0MiB|1214.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |5445.0MiB|5445.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |1397.0MiB|1397.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |5432.0MiB|5432.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |1033.0MiB|1033.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |5199.0MiB|5199.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |5164.0MiB|5164.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |5442.0MiB|5442.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |1119.0MiB|1119.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |1183.0MiB|1183.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |1215.0MiB|1215.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |5362.0MiB|5362.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |5297.0MiB|5297.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |5426.0MiB|5426.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1292.0MiB|1292.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |1165.0MiB|1165.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |5419.0MiB|5419.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |1274.0MiB|1274.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |5228.0MiB|5228.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |5393.0MiB|5393.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |1214.0MiB|1214.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |5445.0MiB|5445.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |1397.0MiB|1397.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |5432.0MiB|5432.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |1033.0MiB|1033.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |5199.0MiB|5199.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |5164.0MiB|5164.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |5442.0MiB|5442.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |1119.0MiB|1119.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |1183.0MiB|1183.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |1215.0MiB|1215.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |5362.0MiB|5362.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |5297.0MiB|5297.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |5426.0MiB|5426.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1292.0MiB|1292.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |1165.0MiB|1165.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |5419.0MiB|5419.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |1274.0MiB|1274.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |5228.0MiB|5228.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |5393.0MiB|5393.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |1214.0MiB|1214.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |5445.0MiB|5445.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |1397.0MiB|1397.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |5432.0MiB|5432.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |1033.0MiB|1033.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |5199.0MiB|5199.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |5164.0MiB|5164.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |5442.0MiB|5442.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |1119.0MiB|1119.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |1183.0MiB|1183.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |1215.0MiB|1215.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |5362.0MiB|5362.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |5297.0MiB|5297.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |5426.0MiB|5426.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled120626.smt2                                                                       |1200.670s |5445.0MiB|
|scrambled43005.smt2                                                                        |1200.789s |5442.0MiB|
|scrambled19322.smt2                                                                        |1200.835s |5432.0MiB|
|scrambled68857.smt2                                                                        |1200.791s |5426.0MiB|
|scrambled106386.smt2                                                                       |1200.648s |5419.0MiB|
|scrambled116502.smt2                                                                       |1200.787s |5393.0MiB|
|scrambled57711.smt2                                                                        |1200.699s |5362.0MiB|
|scrambled64619.smt2                                                                        |1200.629s |5297.0MiB|
|scrambled114492.smt2                                                                       |1200.742s |5228.0MiB|
|scrambled36439.smt2                                                                        |1200.831s |5199.0MiB|
|scrambled36692.smt2                                                                        |1200.647s |5164.0MiB|
|scrambled12077.smt2                                                                        |1200.192s |1397.0MiB|
|scrambled69775.smt2                                                                        |1200.241s |1396.0MiB|
|scrambled95269.smt2                                                                        |1200.204s |1336.0MiB|
|scrambled103130.smt2                                                                       |1200.219s |1292.0MiB|
|scrambled111948.smt2                                                                       |1200.246s |1274.0MiB|
|scrambled7069.smt2                                                                         |1200.245s |1257.0MiB|
|scrambled73226.smt2                                                                        |1200.208s |1237.0MiB|
|scrambled55916.smt2                                                                        |1200.282s |1215.0MiB|
|scrambled118796.smt2                                                                       |1200.294s |1214.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled120626.smt2                                                                       |1200.670s |5445.0MiB|
|scrambled43005.smt2                                                                        |1200.789s |5442.0MiB|
|scrambled19322.smt2                                                                        |1200.835s |5432.0MiB|
|scrambled68857.smt2                                                                        |1200.791s |5426.0MiB|
|scrambled106386.smt2                                                                       |1200.648s |5419.0MiB|
|scrambled116502.smt2                                                                       |1200.787s |5393.0MiB|
|scrambled57711.smt2                                                                        |1200.699s |5362.0MiB|
|scrambled64619.smt2                                                                        |1200.629s |5297.0MiB|
|scrambled114492.smt2                                                                       |1200.742s |5228.0MiB|
|scrambled36439.smt2                                                                        |1200.831s |5199.0MiB|
|scrambled36692.smt2                                                                        |1200.647s |5164.0MiB|
|scrambled12077.smt2                                                                        |1200.192s |1397.0MiB|
|scrambled69775.smt2                                                                        |1200.241s |1396.0MiB|
|scrambled95269.smt2                                                                        |1200.204s |1336.0MiB|
|scrambled103130.smt2                                                                       |1200.219s |1292.0MiB|
|scrambled111948.smt2                                                                       |1200.246s |1274.0MiB|
|scrambled7069.smt2                                                                         |1200.245s |1257.0MiB|
|scrambled73226.smt2                                                                        |1200.208s |1237.0MiB|
|scrambled55916.smt2                                                                        |1200.282s |1215.0MiB|
|scrambled118796.smt2                                                                       |1200.294s |1214.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.187s  |1200.187s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.648s  |1200.648s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.246s  |1200.246s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.742s  |1200.742s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.787s  |1200.787s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.294s  |1200.294s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.670s  |1200.670s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.192s  |1200.192s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.835s  |1200.835s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 711.926s  | 711.926s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.831s  |1200.831s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.647s  |1200.647s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.789s  |1200.789s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.205s  |1200.205s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.212s  |1200.212s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.282s  |1200.282s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.699s  |1200.699s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.629s  |1200.629s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.791s  |1200.791s  |   0.000s  | 0.0%|
|scrambled69775.smt2                                                                         |1200.241s  |1200.241s  |   0.000s  | 0.0%|
|scrambled7069.smt2                                                                          |1200.245s  |1200.245s  |   0.000s  | 0.0%|
|scrambled73226.smt2                                                                         |1200.208s  |1200.208s  |   0.000s  | 0.0%|
</details>
