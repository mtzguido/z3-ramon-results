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
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_RDL-timeout20min}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false smt.arith.solver=4"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_RDL
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_RDL-timeout20min}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false smt.arith.solver=4"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_RDL
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 170.862s  | 170.862s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.021s  |1200.021s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 723.104s  | 723.104s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 170.862s  | 170.862s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.021s  |1200.021s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 723.104s  | 723.104s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 170.862s  | 170.862s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.021s  |1200.021s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 723.104s  | 723.104s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 170.862s  | 170.862s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.021s  |1200.021s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 723.104s  | 723.104s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled120626.smt2                                                                       |1200.046s |87.048MiB|
|scrambled57711.smt2                                                                        |1200.035s |84.944MiB|
|scrambled103636.smt2                                                                       |1200.035s |62.66MiB|
|scrambled106386.smt2                                                                       |1200.035s |85.744MiB|
|scrambled36439.smt2                                                                        |1200.035s |88.304MiB|
|scrambled43005.smt2                                                                        |1200.035s |87.268MiB|
|scrambled19322.smt2                                                                        |1200.035s |87.068MiB|
|scrambled118796.smt2                                                                       |1200.035s |63.576MiB|
|scrambled114492.smt2                                                                       |1200.035s |86.352MiB|
|scrambled103130.smt2                                                                       |1200.035s |59.136MiB|
|scrambled55916.smt2                                                                        |1200.035s |64.172MiB|
|scrambled64619.smt2                                                                        |1200.034s |85.952MiB|
|scrambled111948.smt2                                                                       |1200.034s |58.224MiB|
|scrambled7069.smt2                                                                         |1200.032s |61.792MiB|
|scrambled5175.smt2                                                                         |1200.032s |60.148MiB|
|scrambled69775.smt2                                                                        |1200.031s |60.484MiB|
|scrambled73226.smt2                                                                        |1200.031s |62.7MiB|
|scrambled36692.smt2                                                                        |1200.021s |84.516MiB|
|scrambled116502.smt2                                                                       |1200.020s |87.292MiB|
|scrambled68857.smt2                                                                        |1200.019s |87.592MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled120626.smt2                                                                       |1200.046s |87.048MiB|
|scrambled57711.smt2                                                                        |1200.035s |84.944MiB|
|scrambled103636.smt2                                                                       |1200.035s |62.66MiB|
|scrambled106386.smt2                                                                       |1200.035s |85.744MiB|
|scrambled36439.smt2                                                                        |1200.035s |88.304MiB|
|scrambled43005.smt2                                                                        |1200.035s |87.268MiB|
|scrambled19322.smt2                                                                        |1200.035s |87.068MiB|
|scrambled118796.smt2                                                                       |1200.035s |63.576MiB|
|scrambled114492.smt2                                                                       |1200.035s |86.352MiB|
|scrambled103130.smt2                                                                       |1200.035s |59.136MiB|
|scrambled55916.smt2                                                                        |1200.035s |64.172MiB|
|scrambled64619.smt2                                                                        |1200.034s |85.952MiB|
|scrambled111948.smt2                                                                       |1200.034s |58.224MiB|
|scrambled7069.smt2                                                                         |1200.032s |61.792MiB|
|scrambled5175.smt2                                                                         |1200.032s |60.148MiB|
|scrambled69775.smt2                                                                        |1200.031s |60.484MiB|
|scrambled73226.smt2                                                                        |1200.031s |62.7MiB|
|scrambled36692.smt2                                                                        |1200.021s |84.516MiB|
|scrambled116502.smt2                                                                       |1200.020s |87.292MiB|
|scrambled68857.smt2                                                                        |1200.019s |87.592MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |59.136MiB|59.136MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |62.66MiB|62.66MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |85.744MiB|85.744MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |58.224MiB|58.224MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |86.352MiB|86.352MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |87.292MiB|87.292MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |63.576MiB|63.576MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |87.048MiB|87.048MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |53.896MiB|53.896MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |87.068MiB|87.068MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |43.764MiB|43.764MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |88.304MiB|88.304MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |84.516MiB|84.516MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |87.268MiB|87.268MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |54.0MiB|54.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |60.148MiB|60.148MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |64.172MiB|64.172MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |84.944MiB|84.944MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |85.952MiB|85.952MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |87.592MiB|87.592MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |59.136MiB|59.136MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |62.66MiB|62.66MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |85.744MiB|85.744MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |58.224MiB|58.224MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |86.352MiB|86.352MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |87.292MiB|87.292MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |63.576MiB|63.576MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |87.048MiB|87.048MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |53.896MiB|53.896MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |87.068MiB|87.068MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |43.764MiB|43.764MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |88.304MiB|88.304MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |84.516MiB|84.516MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |87.268MiB|87.268MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |54.0MiB|54.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |60.148MiB|60.148MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |64.172MiB|64.172MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |84.944MiB|84.944MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |85.952MiB|85.952MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |87.592MiB|87.592MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |59.136MiB|59.136MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |62.66MiB|62.66MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |85.744MiB|85.744MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |58.224MiB|58.224MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |86.352MiB|86.352MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |87.292MiB|87.292MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |63.576MiB|63.576MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |87.048MiB|87.048MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |53.896MiB|53.896MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |87.068MiB|87.068MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |43.764MiB|43.764MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |88.304MiB|88.304MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |84.516MiB|84.516MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |87.268MiB|87.268MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |54.0MiB|54.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |60.148MiB|60.148MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |64.172MiB|64.172MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |84.944MiB|84.944MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |85.952MiB|85.952MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |87.592MiB|87.592MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |59.136MiB|59.136MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |62.66MiB|62.66MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |85.744MiB|85.744MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |58.224MiB|58.224MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |86.352MiB|86.352MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |87.292MiB|87.292MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |63.576MiB|63.576MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |87.048MiB|87.048MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |53.896MiB|53.896MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |87.068MiB|87.068MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |43.764MiB|43.764MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |88.304MiB|88.304MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |84.516MiB|84.516MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |87.268MiB|87.268MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |54.0MiB|54.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |60.148MiB|60.148MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |64.172MiB|64.172MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |84.944MiB|84.944MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |85.952MiB|85.952MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |87.592MiB|87.592MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled36439.smt2                                                                        |1200.035s |88.304MiB|
|scrambled68857.smt2                                                                        |1200.019s |87.592MiB|
|scrambled116502.smt2                                                                       |1200.020s |87.292MiB|
|scrambled43005.smt2                                                                        |1200.035s |87.268MiB|
|scrambled19322.smt2                                                                        |1200.035s |87.068MiB|
|scrambled120626.smt2                                                                       |1200.046s |87.048MiB|
|scrambled114492.smt2                                                                       |1200.035s |86.352MiB|
|scrambled64619.smt2                                                                        |1200.034s |85.952MiB|
|scrambled106386.smt2                                                                       |1200.035s |85.744MiB|
|scrambled57711.smt2                                                                        |1200.035s |84.944MiB|
|scrambled36692.smt2                                                                        |1200.021s |84.516MiB|
|scrambled55916.smt2                                                                        |1200.035s |64.172MiB|
|scrambled118796.smt2                                                                       |1200.035s |63.576MiB|
|scrambled73226.smt2                                                                        |1200.031s |62.7MiB|
|scrambled103636.smt2                                                                       |1200.035s |62.66MiB|
|scrambled7069.smt2                                                                         |1200.032s |61.792MiB|
|scrambled69775.smt2                                                                        |1200.031s |60.484MiB|
|scrambled5175.smt2                                                                         |1200.032s |60.148MiB|
|scrambled103130.smt2                                                                       |1200.035s |59.136MiB|
|scrambled111948.smt2                                                                       |1200.034s |58.224MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled36439.smt2                                                                        |1200.035s |88.304MiB|
|scrambled68857.smt2                                                                        |1200.019s |87.592MiB|
|scrambled116502.smt2                                                                       |1200.020s |87.292MiB|
|scrambled43005.smt2                                                                        |1200.035s |87.268MiB|
|scrambled19322.smt2                                                                        |1200.035s |87.068MiB|
|scrambled120626.smt2                                                                       |1200.046s |87.048MiB|
|scrambled114492.smt2                                                                       |1200.035s |86.352MiB|
|scrambled64619.smt2                                                                        |1200.034s |85.952MiB|
|scrambled106386.smt2                                                                       |1200.035s |85.744MiB|
|scrambled57711.smt2                                                                        |1200.035s |84.944MiB|
|scrambled36692.smt2                                                                        |1200.021s |84.516MiB|
|scrambled55916.smt2                                                                        |1200.035s |64.172MiB|
|scrambled118796.smt2                                                                       |1200.035s |63.576MiB|
|scrambled73226.smt2                                                                        |1200.031s |62.7MiB|
|scrambled103636.smt2                                                                       |1200.035s |62.66MiB|
|scrambled7069.smt2                                                                         |1200.032s |61.792MiB|
|scrambled69775.smt2                                                                        |1200.031s |60.484MiB|
|scrambled5175.smt2                                                                         |1200.032s |60.148MiB|
|scrambled103130.smt2                                                                       |1200.035s |59.136MiB|
|scrambled111948.smt2                                                                       |1200.034s |58.224MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 170.862s  | 170.862s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.021s  |1200.021s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 723.104s  | 723.104s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled69775.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled7069.smt2                                                                          |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled73226.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
</details>
