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
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_RDL-timeout20min-no_default_tactic-auto_config}
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
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_RDL-timeout20min-no_default_tactic-auto_config}
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
|scrambled103130.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 371.610s  | 371.610s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 371.610s  | 371.610s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 371.610s  | 371.610s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 371.610s  | 371.610s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled120626.smt2                                                                       |1200.108s |622.0MiB|
|scrambled68857.smt2                                                                        |1200.097s |648.0MiB|
|scrambled64619.smt2                                                                        |1200.095s |608.0MiB|
|scrambled36692.smt2                                                                        |1200.093s |618.0MiB|
|scrambled43005.smt2                                                                        |1200.092s |646.0MiB|
|scrambled19322.smt2                                                                        |1200.091s |634.0MiB|
|scrambled106386.smt2                                                                       |1200.090s |606.0MiB|
|scrambled114492.smt2                                                                       |1200.087s |589.0MiB|
|scrambled36439.smt2                                                                        |1200.079s |624.0MiB|
|scrambled116502.smt2                                                                       |1200.077s |620.0MiB|
|scrambled57711.smt2                                                                        |1200.075s |613.0MiB|
|scrambled103130.smt2                                                                       |1200.050s |139.0MiB|
|scrambled103636.smt2                                                                       |1200.048s |124.0MiB|
|scrambled69775.smt2                                                                        |1200.034s |139.0MiB|
|scrambled95269.smt2                                                                        |1200.033s |144.0MiB|
|scrambled43798.smt2                                                                        |1200.031s |115.0MiB|
|scrambled73226.smt2                                                                        |1200.031s |132.0MiB|
|scrambled5175.smt2                                                                         |1200.031s |124.0MiB|
|scrambled12077.smt2                                                                        |1200.030s |154.0MiB|
|scrambled118796.smt2                                                                       |1200.030s |119.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled120626.smt2                                                                       |1200.108s |622.0MiB|
|scrambled68857.smt2                                                                        |1200.097s |648.0MiB|
|scrambled64619.smt2                                                                        |1200.095s |608.0MiB|
|scrambled36692.smt2                                                                        |1200.093s |618.0MiB|
|scrambled43005.smt2                                                                        |1200.092s |646.0MiB|
|scrambled19322.smt2                                                                        |1200.091s |634.0MiB|
|scrambled106386.smt2                                                                       |1200.090s |606.0MiB|
|scrambled114492.smt2                                                                       |1200.087s |589.0MiB|
|scrambled36439.smt2                                                                        |1200.079s |624.0MiB|
|scrambled116502.smt2                                                                       |1200.077s |620.0MiB|
|scrambled57711.smt2                                                                        |1200.075s |613.0MiB|
|scrambled103130.smt2                                                                       |1200.050s |139.0MiB|
|scrambled103636.smt2                                                                       |1200.048s |124.0MiB|
|scrambled69775.smt2                                                                        |1200.034s |139.0MiB|
|scrambled95269.smt2                                                                        |1200.033s |144.0MiB|
|scrambled43798.smt2                                                                        |1200.031s |115.0MiB|
|scrambled73226.smt2                                                                        |1200.031s |132.0MiB|
|scrambled5175.smt2                                                                         |1200.031s |124.0MiB|
|scrambled12077.smt2                                                                        |1200.030s |154.0MiB|
|scrambled118796.smt2                                                                       |1200.030s |119.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |139.0MiB|139.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |124.0MiB|124.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |606.0MiB|606.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |135.0MiB|135.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |589.0MiB|589.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |620.0MiB|620.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |119.0MiB|119.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |622.0MiB|622.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |154.0MiB|154.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |634.0MiB|634.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |96.868MiB|96.868MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |624.0MiB|624.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |618.0MiB|618.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |646.0MiB|646.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |115.0MiB|115.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |124.0MiB|124.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |131.0MiB|131.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |613.0MiB|613.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |608.0MiB|608.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |648.0MiB|648.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |139.0MiB|139.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |124.0MiB|124.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |606.0MiB|606.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |135.0MiB|135.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |589.0MiB|589.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |620.0MiB|620.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |119.0MiB|119.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |622.0MiB|622.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |154.0MiB|154.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |634.0MiB|634.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |96.868MiB|96.868MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |624.0MiB|624.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |618.0MiB|618.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |646.0MiB|646.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |115.0MiB|115.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |124.0MiB|124.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |131.0MiB|131.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |613.0MiB|613.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |608.0MiB|608.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |648.0MiB|648.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |139.0MiB|139.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |124.0MiB|124.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |606.0MiB|606.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |135.0MiB|135.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |589.0MiB|589.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |620.0MiB|620.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |119.0MiB|119.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |622.0MiB|622.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |154.0MiB|154.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |634.0MiB|634.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |96.868MiB|96.868MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |624.0MiB|624.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |618.0MiB|618.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |646.0MiB|646.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |115.0MiB|115.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |124.0MiB|124.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |131.0MiB|131.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |613.0MiB|613.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |608.0MiB|608.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |648.0MiB|648.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |139.0MiB|139.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |124.0MiB|124.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |606.0MiB|606.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |135.0MiB|135.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |589.0MiB|589.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |620.0MiB|620.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |119.0MiB|119.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |622.0MiB|622.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |154.0MiB|154.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |634.0MiB|634.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |96.868MiB|96.868MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |624.0MiB|624.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |618.0MiB|618.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |646.0MiB|646.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |115.0MiB|115.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |124.0MiB|124.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |131.0MiB|131.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |613.0MiB|613.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |608.0MiB|608.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |648.0MiB|648.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled68857.smt2                                                                        |1200.097s |648.0MiB|
|scrambled43005.smt2                                                                        |1200.092s |646.0MiB|
|scrambled19322.smt2                                                                        |1200.091s |634.0MiB|
|scrambled36439.smt2                                                                        |1200.079s |624.0MiB|
|scrambled120626.smt2                                                                       |1200.108s |622.0MiB|
|scrambled116502.smt2                                                                       |1200.077s |620.0MiB|
|scrambled36692.smt2                                                                        |1200.093s |618.0MiB|
|scrambled57711.smt2                                                                        |1200.075s |613.0MiB|
|scrambled64619.smt2                                                                        |1200.095s |608.0MiB|
|scrambled106386.smt2                                                                       |1200.090s |606.0MiB|
|scrambled114492.smt2                                                                       |1200.087s |589.0MiB|
|scrambled12077.smt2                                                                        |1200.030s |154.0MiB|
|scrambled95269.smt2                                                                        |1200.033s |144.0MiB|
|scrambled103130.smt2                                                                       |1200.050s |139.0MiB|
|scrambled69775.smt2                                                                        |1200.034s |139.0MiB|
|scrambled7069.smt2                                                                         |1200.028s |137.0MiB|
|scrambled111948.smt2                                                                       |1200.030s |135.0MiB|
|scrambled73226.smt2                                                                        |1200.031s |132.0MiB|
|scrambled55916.smt2                                                                        |1200.027s |131.0MiB|
|scrambled103636.smt2                                                                       |1200.048s |124.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled68857.smt2                                                                        |1200.097s |648.0MiB|
|scrambled43005.smt2                                                                        |1200.092s |646.0MiB|
|scrambled19322.smt2                                                                        |1200.091s |634.0MiB|
|scrambled36439.smt2                                                                        |1200.079s |624.0MiB|
|scrambled120626.smt2                                                                       |1200.108s |622.0MiB|
|scrambled116502.smt2                                                                       |1200.077s |620.0MiB|
|scrambled36692.smt2                                                                        |1200.093s |618.0MiB|
|scrambled57711.smt2                                                                        |1200.075s |613.0MiB|
|scrambled64619.smt2                                                                        |1200.095s |608.0MiB|
|scrambled106386.smt2                                                                       |1200.090s |606.0MiB|
|scrambled114492.smt2                                                                       |1200.087s |589.0MiB|
|scrambled12077.smt2                                                                        |1200.030s |154.0MiB|
|scrambled95269.smt2                                                                        |1200.033s |144.0MiB|
|scrambled103130.smt2                                                                       |1200.050s |139.0MiB|
|scrambled69775.smt2                                                                        |1200.034s |139.0MiB|
|scrambled7069.smt2                                                                         |1200.028s |137.0MiB|
|scrambled111948.smt2                                                                       |1200.030s |135.0MiB|
|scrambled73226.smt2                                                                        |1200.031s |132.0MiB|
|scrambled55916.smt2                                                                        |1200.027s |131.0MiB|
|scrambled103636.smt2                                                                       |1200.048s |124.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 371.610s  | 371.610s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled69775.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled7069.smt2                                                                          |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled73226.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
</details>
