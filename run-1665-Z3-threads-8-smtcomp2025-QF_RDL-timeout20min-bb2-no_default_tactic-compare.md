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
Job tag: Z3-threads-8-smtcomp2025-QF_RDL-timeout20min-bb2-no_default_tactic
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=false smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_RDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_RDL-timeout20min-bb2-no_default_tactic
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=false smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_RDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.162s  |1200.162s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.154s  |1200.154s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.131s  |1200.131s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 129.519s  | 129.519s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.102s  |1200.102s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 762.359s  | 762.359s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.175s  |1200.175s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.162s  |1200.162s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.154s  |1200.154s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.131s  |1200.131s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 129.519s  | 129.519s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.102s  |1200.102s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 762.359s  | 762.359s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.175s  |1200.175s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.162s  |1200.162s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.154s  |1200.154s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.131s  |1200.131s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 129.519s  | 129.519s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.102s  |1200.102s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 762.359s  | 762.359s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.175s  |1200.175s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.162s  |1200.162s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.154s  |1200.154s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.131s  |1200.131s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 129.519s  | 129.519s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.102s  |1200.102s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 762.359s  | 762.359s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.175s  |1200.175s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled68857.smt2                                                                        |1200.180s |655.0MiB|
|scrambled64619.smt2                                                                        |1200.175s |654.0MiB|
|scrambled120626.smt2                                                                       |1200.174s |650.0MiB|
|scrambled103130.smt2                                                                       |1200.162s |505.0MiB|
|scrambled103636.smt2                                                                       |1200.154s |530.0MiB|
|scrambled106386.smt2                                                                       |1200.152s |654.0MiB|
|scrambled116502.smt2                                                                       |1200.131s |647.0MiB|
|scrambled111948.smt2                                                                       |1200.123s |515.0MiB|
|scrambled43005.smt2                                                                        |1200.122s |658.0MiB|
|scrambled12077.smt2                                                                        |1200.121s |456.0MiB|
|scrambled73226.smt2                                                                        |1200.115s |543.0MiB|
|scrambled19322.smt2                                                                        |1200.114s |654.0MiB|
|scrambled69775.smt2                                                                        |1200.106s |548.0MiB|
|scrambled57711.smt2                                                                        |1200.103s |657.0MiB|
|scrambled36439.smt2                                                                        |1200.102s |655.0MiB|
|scrambled36692.smt2                                                                        |1200.099s |651.0MiB|
|scrambled7069.smt2                                                                         |1200.099s |534.0MiB|
|scrambled114492.smt2                                                                       |1200.099s |655.0MiB|
|scrambled118796.smt2                                                                       |1200.093s |545.0MiB|
|scrambled55916.smt2                                                                        |1200.090s |585.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled68857.smt2                                                                        |1200.180s |655.0MiB|
|scrambled64619.smt2                                                                        |1200.175s |654.0MiB|
|scrambled120626.smt2                                                                       |1200.174s |650.0MiB|
|scrambled103130.smt2                                                                       |1200.162s |505.0MiB|
|scrambled103636.smt2                                                                       |1200.154s |530.0MiB|
|scrambled106386.smt2                                                                       |1200.152s |654.0MiB|
|scrambled116502.smt2                                                                       |1200.131s |647.0MiB|
|scrambled111948.smt2                                                                       |1200.123s |515.0MiB|
|scrambled43005.smt2                                                                        |1200.122s |658.0MiB|
|scrambled12077.smt2                                                                        |1200.121s |456.0MiB|
|scrambled73226.smt2                                                                        |1200.115s |543.0MiB|
|scrambled19322.smt2                                                                        |1200.114s |654.0MiB|
|scrambled69775.smt2                                                                        |1200.106s |548.0MiB|
|scrambled57711.smt2                                                                        |1200.103s |657.0MiB|
|scrambled36439.smt2                                                                        |1200.102s |655.0MiB|
|scrambled36692.smt2                                                                        |1200.099s |651.0MiB|
|scrambled7069.smt2                                                                         |1200.099s |534.0MiB|
|scrambled114492.smt2                                                                       |1200.099s |655.0MiB|
|scrambled118796.smt2                                                                       |1200.093s |545.0MiB|
|scrambled55916.smt2                                                                        |1200.090s |585.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |505.0MiB|505.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |530.0MiB|530.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |515.0MiB|515.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |647.0MiB|647.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |545.0MiB|545.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |650.0MiB|650.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |456.0MiB|456.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |393.0MiB|393.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |651.0MiB|651.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |658.0MiB|658.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |467.0MiB|467.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |523.0MiB|523.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |657.0MiB|657.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |505.0MiB|505.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |530.0MiB|530.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |515.0MiB|515.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |647.0MiB|647.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |545.0MiB|545.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |650.0MiB|650.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |456.0MiB|456.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |393.0MiB|393.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |651.0MiB|651.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |658.0MiB|658.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |467.0MiB|467.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |523.0MiB|523.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |657.0MiB|657.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |505.0MiB|505.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |530.0MiB|530.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |515.0MiB|515.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |647.0MiB|647.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |545.0MiB|545.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |650.0MiB|650.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |456.0MiB|456.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |393.0MiB|393.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |651.0MiB|651.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |658.0MiB|658.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |467.0MiB|467.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |523.0MiB|523.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |657.0MiB|657.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |505.0MiB|505.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |530.0MiB|530.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |515.0MiB|515.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |647.0MiB|647.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |545.0MiB|545.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |650.0MiB|650.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |456.0MiB|456.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |393.0MiB|393.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |651.0MiB|651.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |658.0MiB|658.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |467.0MiB|467.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |523.0MiB|523.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |585.0MiB|585.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |657.0MiB|657.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |655.0MiB|655.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled43005.smt2                                                                        |1200.122s |658.0MiB|
|scrambled57711.smt2                                                                        |1200.103s |657.0MiB|
|scrambled68857.smt2                                                                        |1200.180s |655.0MiB|
|scrambled36439.smt2                                                                        |1200.102s |655.0MiB|
|scrambled114492.smt2                                                                       |1200.099s |655.0MiB|
|scrambled64619.smt2                                                                        |1200.175s |654.0MiB|
|scrambled106386.smt2                                                                       |1200.152s |654.0MiB|
|scrambled19322.smt2                                                                        |1200.114s |654.0MiB|
|scrambled36692.smt2                                                                        |1200.099s |651.0MiB|
|scrambled120626.smt2                                                                       |1200.174s |650.0MiB|
|scrambled116502.smt2                                                                       |1200.131s |647.0MiB|
|scrambled55916.smt2                                                                        |1200.090s |585.0MiB|
|scrambled69775.smt2                                                                        |1200.106s |548.0MiB|
|scrambled118796.smt2                                                                       |1200.093s |545.0MiB|
|scrambled73226.smt2                                                                        |1200.115s |543.0MiB|
|scrambled7069.smt2                                                                         |1200.099s |534.0MiB|
|scrambled103636.smt2                                                                       |1200.154s |530.0MiB|
|scrambled5175.smt2                                                                         |1200.089s |523.0MiB|
|scrambled111948.smt2                                                                       |1200.123s |515.0MiB|
|scrambled103130.smt2                                                                       |1200.162s |505.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled43005.smt2                                                                        |1200.122s |658.0MiB|
|scrambled57711.smt2                                                                        |1200.103s |657.0MiB|
|scrambled68857.smt2                                                                        |1200.180s |655.0MiB|
|scrambled36439.smt2                                                                        |1200.102s |655.0MiB|
|scrambled114492.smt2                                                                       |1200.099s |655.0MiB|
|scrambled64619.smt2                                                                        |1200.175s |654.0MiB|
|scrambled106386.smt2                                                                       |1200.152s |654.0MiB|
|scrambled19322.smt2                                                                        |1200.114s |654.0MiB|
|scrambled36692.smt2                                                                        |1200.099s |651.0MiB|
|scrambled120626.smt2                                                                       |1200.174s |650.0MiB|
|scrambled116502.smt2                                                                       |1200.131s |647.0MiB|
|scrambled55916.smt2                                                                        |1200.090s |585.0MiB|
|scrambled69775.smt2                                                                        |1200.106s |548.0MiB|
|scrambled118796.smt2                                                                       |1200.093s |545.0MiB|
|scrambled73226.smt2                                                                        |1200.115s |543.0MiB|
|scrambled7069.smt2                                                                         |1200.099s |534.0MiB|
|scrambled103636.smt2                                                                       |1200.154s |530.0MiB|
|scrambled5175.smt2                                                                         |1200.089s |523.0MiB|
|scrambled111948.smt2                                                                       |1200.123s |515.0MiB|
|scrambled103130.smt2                                                                       |1200.162s |505.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.162s  |1200.162s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.154s  |1200.154s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.131s  |1200.131s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 129.519s  | 129.519s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.102s  |1200.102s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 762.359s  | 762.359s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.175s  |1200.175s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled69775.smt2                                                                         |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled7069.smt2                                                                          |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled73226.smt2                                                                         |1200.115s  |1200.115s  |   0.000s  | 0.0%|
</details>
