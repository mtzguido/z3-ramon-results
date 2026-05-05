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
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=true smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_RDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_RDL-timeout20min-bb2-no_default_tactic-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=true smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_RDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.198s  |1200.198s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.758s  |1200.758s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.865s  |1200.865s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.657s  |1200.657s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.176s  |1200.176s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.687s  |1200.687s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.232s  |1200.232s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.875s  |1200.875s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 436.700s  | 436.700s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.549s  |1200.549s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.917s  |1200.917s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.775s  |1200.775s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.253s  |1200.253s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.610s  |1200.610s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.748s  |1200.748s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.787s  |1200.787s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.198s  |1200.198s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.758s  |1200.758s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.865s  |1200.865s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.657s  |1200.657s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.176s  |1200.176s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.687s  |1200.687s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.232s  |1200.232s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.875s  |1200.875s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 436.700s  | 436.700s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.549s  |1200.549s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.917s  |1200.917s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.775s  |1200.775s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.253s  |1200.253s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.610s  |1200.610s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.748s  |1200.748s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.787s  |1200.787s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.198s  |1200.198s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.758s  |1200.758s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.865s  |1200.865s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.657s  |1200.657s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.176s  |1200.176s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.687s  |1200.687s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.232s  |1200.232s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.875s  |1200.875s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 436.700s  | 436.700s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.549s  |1200.549s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.917s  |1200.917s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.775s  |1200.775s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.253s  |1200.253s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.610s  |1200.610s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.748s  |1200.748s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.787s  |1200.787s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.198s  |1200.198s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.758s  |1200.758s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.865s  |1200.865s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.657s  |1200.657s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.176s  |1200.176s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.687s  |1200.687s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.232s  |1200.232s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.875s  |1200.875s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 436.700s  | 436.700s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.549s  |1200.549s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.917s  |1200.917s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.775s  |1200.775s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.253s  |1200.253s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.610s  |1200.610s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.748s  |1200.748s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.787s  |1200.787s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled36692.smt2                                                                        |1200.917s |5037.0MiB|
|scrambled19322.smt2                                                                        |1200.875s |5403.0MiB|
|scrambled114492.smt2                                                                       |1200.865s |5232.0MiB|
|scrambled68857.smt2                                                                        |1200.787s |5421.0MiB|
|scrambled43005.smt2                                                                        |1200.775s |5413.0MiB|
|scrambled106386.smt2                                                                       |1200.758s |5423.0MiB|
|scrambled64619.smt2                                                                        |1200.748s |5147.0MiB|
|scrambled120626.smt2                                                                       |1200.687s |5415.0MiB|
|scrambled116502.smt2                                                                       |1200.657s |5374.0MiB|
|scrambled57711.smt2                                                                        |1200.610s |5430.0MiB|
|scrambled36439.smt2                                                                        |1200.549s |5200.0MiB|
|scrambled7069.smt2                                                                         |1200.285s |1255.0MiB|
|scrambled5175.smt2                                                                         |1200.253s |1185.0MiB|
|scrambled69775.smt2                                                                        |1200.242s |1388.0MiB|
|scrambled12077.smt2                                                                        |1200.232s |1390.0MiB|
|scrambled103130.smt2                                                                       |1200.198s |1301.0MiB|
|scrambled111948.smt2                                                                       |1200.197s |1273.0MiB|
|scrambled55916.smt2                                                                        |1200.181s |1220.0MiB|
|scrambled118796.smt2                                                                       |1200.176s |1204.0MiB|
|scrambled95269.smt2                                                                        |1200.169s |1345.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled36692.smt2                                                                        |1200.917s |5037.0MiB|
|scrambled19322.smt2                                                                        |1200.875s |5403.0MiB|
|scrambled114492.smt2                                                                       |1200.865s |5232.0MiB|
|scrambled68857.smt2                                                                        |1200.787s |5421.0MiB|
|scrambled43005.smt2                                                                        |1200.775s |5413.0MiB|
|scrambled106386.smt2                                                                       |1200.758s |5423.0MiB|
|scrambled64619.smt2                                                                        |1200.748s |5147.0MiB|
|scrambled120626.smt2                                                                       |1200.687s |5415.0MiB|
|scrambled116502.smt2                                                                       |1200.657s |5374.0MiB|
|scrambled57711.smt2                                                                        |1200.610s |5430.0MiB|
|scrambled36439.smt2                                                                        |1200.549s |5200.0MiB|
|scrambled7069.smt2                                                                         |1200.285s |1255.0MiB|
|scrambled5175.smt2                                                                         |1200.253s |1185.0MiB|
|scrambled69775.smt2                                                                        |1200.242s |1388.0MiB|
|scrambled12077.smt2                                                                        |1200.232s |1390.0MiB|
|scrambled103130.smt2                                                                       |1200.198s |1301.0MiB|
|scrambled111948.smt2                                                                       |1200.197s |1273.0MiB|
|scrambled55916.smt2                                                                        |1200.181s |1220.0MiB|
|scrambled118796.smt2                                                                       |1200.176s |1204.0MiB|
|scrambled95269.smt2                                                                        |1200.169s |1345.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1301.0MiB|1301.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |1177.0MiB|1177.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |5423.0MiB|5423.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |1273.0MiB|1273.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |5232.0MiB|5232.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |5374.0MiB|5374.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |1204.0MiB|1204.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |5415.0MiB|5415.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |1390.0MiB|1390.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |5403.0MiB|5403.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |989.0MiB|989.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |5200.0MiB|5200.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |5037.0MiB|5037.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |5413.0MiB|5413.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |1123.0MiB|1123.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |1185.0MiB|1185.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |1220.0MiB|1220.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |5430.0MiB|5430.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |5147.0MiB|5147.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |5421.0MiB|5421.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1301.0MiB|1301.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |1177.0MiB|1177.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |5423.0MiB|5423.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |1273.0MiB|1273.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |5232.0MiB|5232.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |5374.0MiB|5374.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |1204.0MiB|1204.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |5415.0MiB|5415.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |1390.0MiB|1390.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |5403.0MiB|5403.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |989.0MiB|989.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |5200.0MiB|5200.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |5037.0MiB|5037.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |5413.0MiB|5413.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |1123.0MiB|1123.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |1185.0MiB|1185.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |1220.0MiB|1220.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |5430.0MiB|5430.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |5147.0MiB|5147.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |5421.0MiB|5421.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1301.0MiB|1301.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |1177.0MiB|1177.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |5423.0MiB|5423.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |1273.0MiB|1273.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |5232.0MiB|5232.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |5374.0MiB|5374.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |1204.0MiB|1204.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |5415.0MiB|5415.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |1390.0MiB|1390.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |5403.0MiB|5403.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |989.0MiB|989.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |5200.0MiB|5200.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |5037.0MiB|5037.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |5413.0MiB|5413.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |1123.0MiB|1123.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |1185.0MiB|1185.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |1220.0MiB|1220.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |5430.0MiB|5430.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |5147.0MiB|5147.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |5421.0MiB|5421.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1301.0MiB|1301.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |1177.0MiB|1177.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |5423.0MiB|5423.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |1273.0MiB|1273.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |5232.0MiB|5232.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |5374.0MiB|5374.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |1204.0MiB|1204.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |5415.0MiB|5415.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |1390.0MiB|1390.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |5403.0MiB|5403.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |989.0MiB|989.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |5200.0MiB|5200.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |5037.0MiB|5037.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |5413.0MiB|5413.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |1123.0MiB|1123.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |1185.0MiB|1185.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |1220.0MiB|1220.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |5430.0MiB|5430.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |5147.0MiB|5147.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |5421.0MiB|5421.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled57711.smt2                                                                        |1200.610s |5430.0MiB|
|scrambled106386.smt2                                                                       |1200.758s |5423.0MiB|
|scrambled68857.smt2                                                                        |1200.787s |5421.0MiB|
|scrambled120626.smt2                                                                       |1200.687s |5415.0MiB|
|scrambled43005.smt2                                                                        |1200.775s |5413.0MiB|
|scrambled19322.smt2                                                                        |1200.875s |5403.0MiB|
|scrambled116502.smt2                                                                       |1200.657s |5374.0MiB|
|scrambled114492.smt2                                                                       |1200.865s |5232.0MiB|
|scrambled36439.smt2                                                                        |1200.549s |5200.0MiB|
|scrambled64619.smt2                                                                        |1200.748s |5147.0MiB|
|scrambled36692.smt2                                                                        |1200.917s |5037.0MiB|
|scrambled12077.smt2                                                                        |1200.232s |1390.0MiB|
|scrambled69775.smt2                                                                        |1200.242s |1388.0MiB|
|scrambled95269.smt2                                                                        |1200.169s |1345.0MiB|
|scrambled103130.smt2                                                                       |1200.198s |1301.0MiB|
|scrambled111948.smt2                                                                       |1200.197s |1273.0MiB|
|scrambled7069.smt2                                                                         |1200.285s |1255.0MiB|
|scrambled73226.smt2                                                                        |1200.166s |1225.0MiB|
|scrambled55916.smt2                                                                        |1200.181s |1220.0MiB|
|scrambled118796.smt2                                                                       |1200.176s |1204.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled57711.smt2                                                                        |1200.610s |5430.0MiB|
|scrambled106386.smt2                                                                       |1200.758s |5423.0MiB|
|scrambled68857.smt2                                                                        |1200.787s |5421.0MiB|
|scrambled120626.smt2                                                                       |1200.687s |5415.0MiB|
|scrambled43005.smt2                                                                        |1200.775s |5413.0MiB|
|scrambled19322.smt2                                                                        |1200.875s |5403.0MiB|
|scrambled116502.smt2                                                                       |1200.657s |5374.0MiB|
|scrambled114492.smt2                                                                       |1200.865s |5232.0MiB|
|scrambled36439.smt2                                                                        |1200.549s |5200.0MiB|
|scrambled64619.smt2                                                                        |1200.748s |5147.0MiB|
|scrambled36692.smt2                                                                        |1200.917s |5037.0MiB|
|scrambled12077.smt2                                                                        |1200.232s |1390.0MiB|
|scrambled69775.smt2                                                                        |1200.242s |1388.0MiB|
|scrambled95269.smt2                                                                        |1200.169s |1345.0MiB|
|scrambled103130.smt2                                                                       |1200.198s |1301.0MiB|
|scrambled111948.smt2                                                                       |1200.197s |1273.0MiB|
|scrambled7069.smt2                                                                         |1200.285s |1255.0MiB|
|scrambled73226.smt2                                                                        |1200.166s |1225.0MiB|
|scrambled55916.smt2                                                                        |1200.181s |1220.0MiB|
|scrambled118796.smt2                                                                       |1200.176s |1204.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.198s  |1200.198s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.169s  |1200.169s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.758s  |1200.758s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.197s  |1200.197s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.865s  |1200.865s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.657s  |1200.657s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.176s  |1200.176s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.687s  |1200.687s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.232s  |1200.232s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.875s  |1200.875s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 436.700s  | 436.700s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.549s  |1200.549s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.917s  |1200.917s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.775s  |1200.775s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.253s  |1200.253s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.610s  |1200.610s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.748s  |1200.748s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.787s  |1200.787s  |   0.000s  | 0.0%|
|scrambled69775.smt2                                                                         |1200.242s  |1200.242s  |   0.000s  | 0.0%|
|scrambled7069.smt2                                                                          |1200.285s  |1200.285s  |   0.000s  | 0.0%|
|scrambled73226.smt2                                                                         |1200.166s  |1200.166s  |   0.000s  | 0.0%|
</details>
