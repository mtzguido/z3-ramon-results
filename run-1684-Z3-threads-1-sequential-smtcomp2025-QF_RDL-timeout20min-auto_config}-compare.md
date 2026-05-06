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
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_RDL-timeout20min-auto_config}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=true smt.arith.solver=4"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_RDL
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_RDL-timeout20min-auto_config}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=true smt.arith.solver=4"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_RDL
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 353.291s  | 353.291s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 353.291s  | 353.291s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 353.291s  | 353.291s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 353.291s  | 353.291s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled64619.smt2                                                                        |1200.117s |594.0MiB|
|scrambled116502.smt2                                                                       |1200.101s |642.0MiB|
|scrambled68857.smt2                                                                        |1200.101s |646.0MiB|
|scrambled120626.smt2                                                                       |1200.100s |623.0MiB|
|scrambled19322.smt2                                                                        |1200.099s |637.0MiB|
|scrambled106386.smt2                                                                       |1200.098s |621.0MiB|
|scrambled43005.smt2                                                                        |1200.098s |641.0MiB|
|scrambled57711.smt2                                                                        |1200.078s |609.0MiB|
|scrambled36692.smt2                                                                        |1200.077s |601.0MiB|
|scrambled36439.smt2                                                                        |1200.076s |616.0MiB|
|scrambled114492.smt2                                                                       |1200.075s |599.0MiB|
|scrambled103130.smt2                                                                       |1200.052s |139.0MiB|
|scrambled103636.smt2                                                                       |1200.049s |123.0MiB|
|scrambled73226.smt2                                                                        |1200.048s |132.0MiB|
|scrambled69775.smt2                                                                        |1200.040s |137.0MiB|
|scrambled118796.smt2                                                                       |1200.040s |118.0MiB|
|scrambled43798.smt2                                                                        |1200.037s |116.0MiB|
|scrambled111948.smt2                                                                       |1200.036s |137.0MiB|
|scrambled12077.smt2                                                                        |1200.035s |153.0MiB|
|scrambled55916.smt2                                                                        |1200.035s |132.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled64619.smt2                                                                        |1200.117s |594.0MiB|
|scrambled116502.smt2                                                                       |1200.101s |642.0MiB|
|scrambled68857.smt2                                                                        |1200.101s |646.0MiB|
|scrambled120626.smt2                                                                       |1200.100s |623.0MiB|
|scrambled19322.smt2                                                                        |1200.099s |637.0MiB|
|scrambled106386.smt2                                                                       |1200.098s |621.0MiB|
|scrambled43005.smt2                                                                        |1200.098s |641.0MiB|
|scrambled57711.smt2                                                                        |1200.078s |609.0MiB|
|scrambled36692.smt2                                                                        |1200.077s |601.0MiB|
|scrambled36439.smt2                                                                        |1200.076s |616.0MiB|
|scrambled114492.smt2                                                                       |1200.075s |599.0MiB|
|scrambled103130.smt2                                                                       |1200.052s |139.0MiB|
|scrambled103636.smt2                                                                       |1200.049s |123.0MiB|
|scrambled73226.smt2                                                                        |1200.048s |132.0MiB|
|scrambled69775.smt2                                                                        |1200.040s |137.0MiB|
|scrambled118796.smt2                                                                       |1200.040s |118.0MiB|
|scrambled43798.smt2                                                                        |1200.037s |116.0MiB|
|scrambled111948.smt2                                                                       |1200.036s |137.0MiB|
|scrambled12077.smt2                                                                        |1200.035s |153.0MiB|
|scrambled55916.smt2                                                                        |1200.035s |132.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |139.0MiB|139.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |123.0MiB|123.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |621.0MiB|621.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |137.0MiB|137.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |599.0MiB|599.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |642.0MiB|642.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |118.0MiB|118.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |623.0MiB|623.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |153.0MiB|153.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |637.0MiB|637.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |96.836MiB|96.836MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |616.0MiB|616.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |601.0MiB|601.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |641.0MiB|641.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |116.0MiB|116.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |126.0MiB|126.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |132.0MiB|132.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |609.0MiB|609.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |594.0MiB|594.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |646.0MiB|646.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |139.0MiB|139.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |123.0MiB|123.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |621.0MiB|621.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |137.0MiB|137.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |599.0MiB|599.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |642.0MiB|642.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |118.0MiB|118.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |623.0MiB|623.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |153.0MiB|153.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |637.0MiB|637.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |96.836MiB|96.836MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |616.0MiB|616.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |601.0MiB|601.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |641.0MiB|641.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |116.0MiB|116.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |126.0MiB|126.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |132.0MiB|132.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |609.0MiB|609.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |594.0MiB|594.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |646.0MiB|646.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |139.0MiB|139.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |123.0MiB|123.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |621.0MiB|621.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |137.0MiB|137.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |599.0MiB|599.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |642.0MiB|642.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |118.0MiB|118.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |623.0MiB|623.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |153.0MiB|153.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |637.0MiB|637.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |96.836MiB|96.836MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |616.0MiB|616.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |601.0MiB|601.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |641.0MiB|641.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |116.0MiB|116.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |126.0MiB|126.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |132.0MiB|132.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |609.0MiB|609.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |594.0MiB|594.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |646.0MiB|646.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |139.0MiB|139.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |123.0MiB|123.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |621.0MiB|621.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |137.0MiB|137.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |599.0MiB|599.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |642.0MiB|642.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |118.0MiB|118.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |623.0MiB|623.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |153.0MiB|153.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |637.0MiB|637.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |96.836MiB|96.836MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |616.0MiB|616.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |601.0MiB|601.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |641.0MiB|641.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |116.0MiB|116.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |126.0MiB|126.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |132.0MiB|132.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |609.0MiB|609.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |594.0MiB|594.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |646.0MiB|646.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled68857.smt2                                                                        |1200.101s |646.0MiB|
|scrambled116502.smt2                                                                       |1200.101s |642.0MiB|
|scrambled43005.smt2                                                                        |1200.098s |641.0MiB|
|scrambled19322.smt2                                                                        |1200.099s |637.0MiB|
|scrambled120626.smt2                                                                       |1200.100s |623.0MiB|
|scrambled106386.smt2                                                                       |1200.098s |621.0MiB|
|scrambled36439.smt2                                                                        |1200.076s |616.0MiB|
|scrambled57711.smt2                                                                        |1200.078s |609.0MiB|
|scrambled36692.smt2                                                                        |1200.077s |601.0MiB|
|scrambled114492.smt2                                                                       |1200.075s |599.0MiB|
|scrambled64619.smt2                                                                        |1200.117s |594.0MiB|
|scrambled12077.smt2                                                                        |1200.035s |153.0MiB|
|scrambled95269.smt2                                                                        |1200.032s |146.0MiB|
|scrambled103130.smt2                                                                       |1200.052s |139.0MiB|
|scrambled69775.smt2                                                                        |1200.040s |137.0MiB|
|scrambled111948.smt2                                                                       |1200.036s |137.0MiB|
|scrambled7069.smt2                                                                         |1200.032s |134.0MiB|
|scrambled73226.smt2                                                                        |1200.048s |132.0MiB|
|scrambled55916.smt2                                                                        |1200.035s |132.0MiB|
|scrambled5175.smt2                                                                         |1200.032s |126.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled68857.smt2                                                                        |1200.101s |646.0MiB|
|scrambled116502.smt2                                                                       |1200.101s |642.0MiB|
|scrambled43005.smt2                                                                        |1200.098s |641.0MiB|
|scrambled19322.smt2                                                                        |1200.099s |637.0MiB|
|scrambled120626.smt2                                                                       |1200.100s |623.0MiB|
|scrambled106386.smt2                                                                       |1200.098s |621.0MiB|
|scrambled36439.smt2                                                                        |1200.076s |616.0MiB|
|scrambled57711.smt2                                                                        |1200.078s |609.0MiB|
|scrambled36692.smt2                                                                        |1200.077s |601.0MiB|
|scrambled114492.smt2                                                                       |1200.075s |599.0MiB|
|scrambled64619.smt2                                                                        |1200.117s |594.0MiB|
|scrambled12077.smt2                                                                        |1200.035s |153.0MiB|
|scrambled95269.smt2                                                                        |1200.032s |146.0MiB|
|scrambled103130.smt2                                                                       |1200.052s |139.0MiB|
|scrambled69775.smt2                                                                        |1200.040s |137.0MiB|
|scrambled111948.smt2                                                                       |1200.036s |137.0MiB|
|scrambled7069.smt2                                                                         |1200.032s |134.0MiB|
|scrambled73226.smt2                                                                        |1200.048s |132.0MiB|
|scrambled55916.smt2                                                                        |1200.035s |132.0MiB|
|scrambled5175.smt2                                                                         |1200.032s |126.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.100s  |1200.100s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 353.291s  | 353.291s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.117s  |1200.117s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled69775.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled7069.smt2                                                                          |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled73226.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
</details>
