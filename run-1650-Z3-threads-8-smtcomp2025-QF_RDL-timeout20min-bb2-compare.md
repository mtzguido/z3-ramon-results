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
Job tag: Z3-threads-8-smtcomp2025-QF_RDL-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_RDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_RDL-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_RDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.129s  |1200.129s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 107.003s  | 107.003s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.119s  |1200.119s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.119s  |1200.119s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 721.603s  | 721.603s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.129s  |1200.129s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 107.003s  | 107.003s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.119s  |1200.119s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.119s  |1200.119s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 721.603s  | 721.603s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.129s  |1200.129s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 107.003s  | 107.003s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.119s  |1200.119s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.119s  |1200.119s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 721.603s  | 721.603s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.129s  |1200.129s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 107.003s  | 107.003s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.119s  |1200.119s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.119s  |1200.119s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 721.603s  | 721.603s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled68857.smt2                                                                        |1200.138s |648.0MiB|
|scrambled57711.smt2                                                                        |1200.135s |655.0MiB|
|scrambled120626.smt2                                                                       |1200.134s |646.0MiB|
|scrambled19322.smt2                                                                        |1200.129s |650.0MiB|
|scrambled36439.smt2                                                                        |1200.123s |651.0MiB|
|scrambled64619.smt2                                                                        |1200.122s |654.0MiB|
|scrambled114492.smt2                                                                       |1200.122s |652.0MiB|
|scrambled106386.smt2                                                                       |1200.121s |648.0MiB|
|scrambled116502.smt2                                                                       |1200.120s |656.0MiB|
|scrambled36692.smt2                                                                        |1200.119s |648.0MiB|
|scrambled43005.smt2                                                                        |1200.119s |655.0MiB|
|scrambled103636.smt2                                                                       |1200.117s |544.0MiB|
|scrambled111948.smt2                                                                       |1200.113s |520.0MiB|
|scrambled95269.smt2                                                                        |1200.109s |515.0MiB|
|scrambled103130.smt2                                                                       |1200.108s |504.0MiB|
|scrambled69775.smt2                                                                        |1200.105s |546.0MiB|
|scrambled7069.smt2                                                                         |1200.103s |525.0MiB|
|scrambled73226.smt2                                                                        |1200.099s |521.0MiB|
|scrambled118796.smt2                                                                       |1200.093s |532.0MiB|
|scrambled12077.smt2                                                                        |1200.091s |458.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled68857.smt2                                                                        |1200.138s |648.0MiB|
|scrambled57711.smt2                                                                        |1200.135s |655.0MiB|
|scrambled120626.smt2                                                                       |1200.134s |646.0MiB|
|scrambled19322.smt2                                                                        |1200.129s |650.0MiB|
|scrambled36439.smt2                                                                        |1200.123s |651.0MiB|
|scrambled64619.smt2                                                                        |1200.122s |654.0MiB|
|scrambled114492.smt2                                                                       |1200.122s |652.0MiB|
|scrambled106386.smt2                                                                       |1200.121s |648.0MiB|
|scrambled116502.smt2                                                                       |1200.120s |656.0MiB|
|scrambled36692.smt2                                                                        |1200.119s |648.0MiB|
|scrambled43005.smt2                                                                        |1200.119s |655.0MiB|
|scrambled103636.smt2                                                                       |1200.117s |544.0MiB|
|scrambled111948.smt2                                                                       |1200.113s |520.0MiB|
|scrambled95269.smt2                                                                        |1200.109s |515.0MiB|
|scrambled103130.smt2                                                                       |1200.108s |504.0MiB|
|scrambled69775.smt2                                                                        |1200.105s |546.0MiB|
|scrambled7069.smt2                                                                         |1200.103s |525.0MiB|
|scrambled73226.smt2                                                                        |1200.099s |521.0MiB|
|scrambled118796.smt2                                                                       |1200.093s |532.0MiB|
|scrambled12077.smt2                                                                        |1200.091s |458.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |504.0MiB|504.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |544.0MiB|544.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |648.0MiB|648.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |520.0MiB|520.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |652.0MiB|652.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |656.0MiB|656.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |532.0MiB|532.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |646.0MiB|646.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |458.0MiB|458.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |650.0MiB|650.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |379.0MiB|379.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |651.0MiB|651.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |648.0MiB|648.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |467.0MiB|467.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |533.0MiB|533.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |573.0MiB|573.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |648.0MiB|648.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |504.0MiB|504.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |544.0MiB|544.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |648.0MiB|648.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |520.0MiB|520.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |652.0MiB|652.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |656.0MiB|656.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |532.0MiB|532.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |646.0MiB|646.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |458.0MiB|458.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |650.0MiB|650.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |379.0MiB|379.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |651.0MiB|651.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |648.0MiB|648.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |467.0MiB|467.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |533.0MiB|533.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |573.0MiB|573.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |648.0MiB|648.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |504.0MiB|504.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |544.0MiB|544.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |648.0MiB|648.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |520.0MiB|520.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |652.0MiB|652.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |656.0MiB|656.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |532.0MiB|532.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |646.0MiB|646.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |458.0MiB|458.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |650.0MiB|650.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |379.0MiB|379.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |651.0MiB|651.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |648.0MiB|648.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |467.0MiB|467.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |533.0MiB|533.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |573.0MiB|573.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |648.0MiB|648.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |504.0MiB|504.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |544.0MiB|544.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |648.0MiB|648.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |520.0MiB|520.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |652.0MiB|652.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |656.0MiB|656.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |532.0MiB|532.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |646.0MiB|646.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |458.0MiB|458.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |650.0MiB|650.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |379.0MiB|379.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |651.0MiB|651.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |648.0MiB|648.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |467.0MiB|467.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |533.0MiB|533.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |573.0MiB|573.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |648.0MiB|648.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled116502.smt2                                                                       |1200.120s |656.0MiB|
|scrambled57711.smt2                                                                        |1200.135s |655.0MiB|
|scrambled43005.smt2                                                                        |1200.119s |655.0MiB|
|scrambled64619.smt2                                                                        |1200.122s |654.0MiB|
|scrambled114492.smt2                                                                       |1200.122s |652.0MiB|
|scrambled36439.smt2                                                                        |1200.123s |651.0MiB|
|scrambled19322.smt2                                                                        |1200.129s |650.0MiB|
|scrambled68857.smt2                                                                        |1200.138s |648.0MiB|
|scrambled106386.smt2                                                                       |1200.121s |648.0MiB|
|scrambled36692.smt2                                                                        |1200.119s |648.0MiB|
|scrambled120626.smt2                                                                       |1200.134s |646.0MiB|
|scrambled55916.smt2                                                                        |1200.087s |573.0MiB|
|scrambled69775.smt2                                                                        |1200.105s |546.0MiB|
|scrambled103636.smt2                                                                       |1200.117s |544.0MiB|
|scrambled5175.smt2                                                                         |1200.091s |533.0MiB|
|scrambled118796.smt2                                                                       |1200.093s |532.0MiB|
|scrambled7069.smt2                                                                         |1200.103s |525.0MiB|
|scrambled73226.smt2                                                                        |1200.099s |521.0MiB|
|scrambled111948.smt2                                                                       |1200.113s |520.0MiB|
|scrambled95269.smt2                                                                        |1200.109s |515.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled116502.smt2                                                                       |1200.120s |656.0MiB|
|scrambled57711.smt2                                                                        |1200.135s |655.0MiB|
|scrambled43005.smt2                                                                        |1200.119s |655.0MiB|
|scrambled64619.smt2                                                                        |1200.122s |654.0MiB|
|scrambled114492.smt2                                                                       |1200.122s |652.0MiB|
|scrambled36439.smt2                                                                        |1200.123s |651.0MiB|
|scrambled19322.smt2                                                                        |1200.129s |650.0MiB|
|scrambled68857.smt2                                                                        |1200.138s |648.0MiB|
|scrambled106386.smt2                                                                       |1200.121s |648.0MiB|
|scrambled36692.smt2                                                                        |1200.119s |648.0MiB|
|scrambled120626.smt2                                                                       |1200.134s |646.0MiB|
|scrambled55916.smt2                                                                        |1200.087s |573.0MiB|
|scrambled69775.smt2                                                                        |1200.105s |546.0MiB|
|scrambled103636.smt2                                                                       |1200.117s |544.0MiB|
|scrambled5175.smt2                                                                         |1200.091s |533.0MiB|
|scrambled118796.smt2                                                                       |1200.093s |532.0MiB|
|scrambled7069.smt2                                                                         |1200.103s |525.0MiB|
|scrambled73226.smt2                                                                        |1200.099s |521.0MiB|
|scrambled111948.smt2                                                                       |1200.113s |520.0MiB|
|scrambled95269.smt2                                                                        |1200.109s |515.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.113s  |1200.113s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.129s  |1200.129s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 107.003s  | 107.003s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.119s  |1200.119s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.119s  |1200.119s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 721.603s  | 721.603s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled69775.smt2                                                                         |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled7069.smt2                                                                          |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled73226.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
</details>
