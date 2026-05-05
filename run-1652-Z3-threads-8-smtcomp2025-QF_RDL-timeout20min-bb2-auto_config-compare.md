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
Job tag: Z3-threads-8-smtcomp2025-QF_RDL-timeout20min-bb2-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=true smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_RDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_RDL-timeout20min-bb2-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=true smt.arith.solver=4 smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_RDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.225s  |1200.225s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.198s  |1200.198s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.687s  |1200.687s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.812s  |1200.812s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.661s  |1200.661s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.872s  |1200.872s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.741s  |1200.741s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 507.598s  | 507.598s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.835s  |1200.835s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.608s  |1200.608s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.858s  |1200.858s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.239s  |1200.239s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.955s  |1200.955s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.764s  |1200.764s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.759s  |1200.759s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.225s  |1200.225s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.198s  |1200.198s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.687s  |1200.687s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.812s  |1200.812s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.661s  |1200.661s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.872s  |1200.872s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.741s  |1200.741s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 507.598s  | 507.598s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.835s  |1200.835s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.608s  |1200.608s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.858s  |1200.858s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.239s  |1200.239s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.955s  |1200.955s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.764s  |1200.764s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.759s  |1200.759s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.225s  |1200.225s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.198s  |1200.198s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.687s  |1200.687s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.812s  |1200.812s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.661s  |1200.661s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.872s  |1200.872s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.741s  |1200.741s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 507.598s  | 507.598s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.835s  |1200.835s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.608s  |1200.608s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.858s  |1200.858s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.239s  |1200.239s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.955s  |1200.955s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.764s  |1200.764s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.759s  |1200.759s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.225s  |1200.225s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.198s  |1200.198s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.687s  |1200.687s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.812s  |1200.812s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.661s  |1200.661s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.872s  |1200.872s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.741s  |1200.741s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 507.598s  | 507.598s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.835s  |1200.835s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.608s  |1200.608s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.858s  |1200.858s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.239s  |1200.239s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.955s  |1200.955s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.764s  |1200.764s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.759s  |1200.759s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled57711.smt2                                                                        |1200.955s |5526.0MiB|
|scrambled120626.smt2                                                                       |1200.872s |5332.0MiB|
|scrambled43005.smt2                                                                        |1200.858s |5520.0MiB|
|scrambled36439.smt2                                                                        |1200.835s |5188.0MiB|
|scrambled114492.smt2                                                                       |1200.812s |5239.0MiB|
|scrambled64619.smt2                                                                        |1200.764s |5217.0MiB|
|scrambled68857.smt2                                                                        |1200.759s |5462.0MiB|
|scrambled19322.smt2                                                                        |1200.741s |5477.0MiB|
|scrambled106386.smt2                                                                       |1200.687s |5494.0MiB|
|scrambled116502.smt2                                                                       |1200.661s |5469.0MiB|
|scrambled36692.smt2                                                                        |1200.608s |5211.0MiB|
|scrambled5175.smt2                                                                         |1200.239s |1123.0MiB|
|scrambled69775.smt2                                                                        |1200.226s |1335.0MiB|
|scrambled103130.smt2                                                                       |1200.225s |1247.0MiB|
|scrambled73226.smt2                                                                        |1200.204s |1180.0MiB|
|scrambled111948.smt2                                                                       |1200.199s |1220.0MiB|
|scrambled103636.smt2                                                                       |1200.198s |1126.0MiB|
|scrambled7069.smt2                                                                         |1200.189s |1201.0MiB|
|scrambled12077.smt2                                                                        |1200.181s |1350.0MiB|
|scrambled95269.smt2                                                                        |1200.167s |1302.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled57711.smt2                                                                        |1200.955s |5526.0MiB|
|scrambled120626.smt2                                                                       |1200.872s |5332.0MiB|
|scrambled43005.smt2                                                                        |1200.858s |5520.0MiB|
|scrambled36439.smt2                                                                        |1200.835s |5188.0MiB|
|scrambled114492.smt2                                                                       |1200.812s |5239.0MiB|
|scrambled64619.smt2                                                                        |1200.764s |5217.0MiB|
|scrambled68857.smt2                                                                        |1200.759s |5462.0MiB|
|scrambled19322.smt2                                                                        |1200.741s |5477.0MiB|
|scrambled106386.smt2                                                                       |1200.687s |5494.0MiB|
|scrambled116502.smt2                                                                       |1200.661s |5469.0MiB|
|scrambled36692.smt2                                                                        |1200.608s |5211.0MiB|
|scrambled5175.smt2                                                                         |1200.239s |1123.0MiB|
|scrambled69775.smt2                                                                        |1200.226s |1335.0MiB|
|scrambled103130.smt2                                                                       |1200.225s |1247.0MiB|
|scrambled73226.smt2                                                                        |1200.204s |1180.0MiB|
|scrambled111948.smt2                                                                       |1200.199s |1220.0MiB|
|scrambled103636.smt2                                                                       |1200.198s |1126.0MiB|
|scrambled7069.smt2                                                                         |1200.189s |1201.0MiB|
|scrambled12077.smt2                                                                        |1200.181s |1350.0MiB|
|scrambled95269.smt2                                                                        |1200.167s |1302.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1247.0MiB|1247.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |1126.0MiB|1126.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |5494.0MiB|5494.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |1220.0MiB|1220.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |5239.0MiB|5239.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |5469.0MiB|5469.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |1141.0MiB|1141.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |5332.0MiB|5332.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |1350.0MiB|1350.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |5477.0MiB|5477.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |978.0MiB|978.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |5188.0MiB|5188.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |5211.0MiB|5211.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |5520.0MiB|5520.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |1095.0MiB|1095.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |1123.0MiB|1123.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |1188.0MiB|1188.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |5526.0MiB|5526.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |5217.0MiB|5217.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |5462.0MiB|5462.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1247.0MiB|1247.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |1126.0MiB|1126.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |5494.0MiB|5494.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |1220.0MiB|1220.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |5239.0MiB|5239.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |5469.0MiB|5469.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |1141.0MiB|1141.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |5332.0MiB|5332.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |1350.0MiB|1350.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |5477.0MiB|5477.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |978.0MiB|978.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |5188.0MiB|5188.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |5211.0MiB|5211.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |5520.0MiB|5520.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |1095.0MiB|1095.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |1123.0MiB|1123.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |1188.0MiB|1188.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |5526.0MiB|5526.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |5217.0MiB|5217.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |5462.0MiB|5462.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1247.0MiB|1247.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |1126.0MiB|1126.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |5494.0MiB|5494.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |1220.0MiB|1220.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |5239.0MiB|5239.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |5469.0MiB|5469.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |1141.0MiB|1141.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |5332.0MiB|5332.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |1350.0MiB|1350.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |5477.0MiB|5477.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |978.0MiB|978.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |5188.0MiB|5188.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |5211.0MiB|5211.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |5520.0MiB|5520.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |1095.0MiB|1095.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |1123.0MiB|1123.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |1188.0MiB|1188.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |5526.0MiB|5526.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |5217.0MiB|5217.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |5462.0MiB|5462.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1247.0MiB|1247.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |1126.0MiB|1126.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |5494.0MiB|5494.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |1220.0MiB|1220.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |5239.0MiB|5239.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |5469.0MiB|5469.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |1141.0MiB|1141.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |5332.0MiB|5332.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |1350.0MiB|1350.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |5477.0MiB|5477.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |978.0MiB|978.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |5188.0MiB|5188.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |5211.0MiB|5211.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |5520.0MiB|5520.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |1095.0MiB|1095.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |1123.0MiB|1123.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |1188.0MiB|1188.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |5526.0MiB|5526.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |5217.0MiB|5217.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |5462.0MiB|5462.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled57711.smt2                                                                        |1200.955s |5526.0MiB|
|scrambled43005.smt2                                                                        |1200.858s |5520.0MiB|
|scrambled106386.smt2                                                                       |1200.687s |5494.0MiB|
|scrambled19322.smt2                                                                        |1200.741s |5477.0MiB|
|scrambled116502.smt2                                                                       |1200.661s |5469.0MiB|
|scrambled68857.smt2                                                                        |1200.759s |5462.0MiB|
|scrambled120626.smt2                                                                       |1200.872s |5332.0MiB|
|scrambled114492.smt2                                                                       |1200.812s |5239.0MiB|
|scrambled64619.smt2                                                                        |1200.764s |5217.0MiB|
|scrambled36692.smt2                                                                        |1200.608s |5211.0MiB|
|scrambled36439.smt2                                                                        |1200.835s |5188.0MiB|
|scrambled12077.smt2                                                                        |1200.181s |1350.0MiB|
|scrambled69775.smt2                                                                        |1200.226s |1335.0MiB|
|scrambled95269.smt2                                                                        |1200.167s |1302.0MiB|
|scrambled103130.smt2                                                                       |1200.225s |1247.0MiB|
|scrambled111948.smt2                                                                       |1200.199s |1220.0MiB|
|scrambled7069.smt2                                                                         |1200.189s |1201.0MiB|
|scrambled55916.smt2                                                                        |1200.160s |1188.0MiB|
|scrambled73226.smt2                                                                        |1200.204s |1180.0MiB|
|scrambled118796.smt2                                                                       |1200.163s |1141.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled57711.smt2                                                                        |1200.955s |5526.0MiB|
|scrambled43005.smt2                                                                        |1200.858s |5520.0MiB|
|scrambled106386.smt2                                                                       |1200.687s |5494.0MiB|
|scrambled19322.smt2                                                                        |1200.741s |5477.0MiB|
|scrambled116502.smt2                                                                       |1200.661s |5469.0MiB|
|scrambled68857.smt2                                                                        |1200.759s |5462.0MiB|
|scrambled120626.smt2                                                                       |1200.872s |5332.0MiB|
|scrambled114492.smt2                                                                       |1200.812s |5239.0MiB|
|scrambled64619.smt2                                                                        |1200.764s |5217.0MiB|
|scrambled36692.smt2                                                                        |1200.608s |5211.0MiB|
|scrambled36439.smt2                                                                        |1200.835s |5188.0MiB|
|scrambled12077.smt2                                                                        |1200.181s |1350.0MiB|
|scrambled69775.smt2                                                                        |1200.226s |1335.0MiB|
|scrambled95269.smt2                                                                        |1200.167s |1302.0MiB|
|scrambled103130.smt2                                                                       |1200.225s |1247.0MiB|
|scrambled111948.smt2                                                                       |1200.199s |1220.0MiB|
|scrambled7069.smt2                                                                         |1200.189s |1201.0MiB|
|scrambled55916.smt2                                                                        |1200.160s |1188.0MiB|
|scrambled73226.smt2                                                                        |1200.204s |1180.0MiB|
|scrambled118796.smt2                                                                       |1200.163s |1141.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.225s  |1200.225s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.198s  |1200.198s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.687s  |1200.687s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.812s  |1200.812s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.661s  |1200.661s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.163s  |1200.163s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.872s  |1200.872s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.741s  |1200.741s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 507.598s  | 507.598s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.835s  |1200.835s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.608s  |1200.608s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.858s  |1200.858s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.239s  |1200.239s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.955s  |1200.955s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.764s  |1200.764s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.759s  |1200.759s  |   0.000s  | 0.0%|
|scrambled69775.smt2                                                                         |1200.226s  |1200.226s  |   0.000s  | 0.0%|
|scrambled7069.smt2                                                                          |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled73226.smt2                                                                         |1200.204s  |1200.204s  |   0.000s  | 0.0%|
</details>
