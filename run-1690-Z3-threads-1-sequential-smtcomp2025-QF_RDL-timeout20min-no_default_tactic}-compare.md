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
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_RDL-timeout20min-no_default_tactic}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 smt.auto_config=false smt.arith.solver=4"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_RDL
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_RDL-timeout20min-no_default_tactic}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 smt.auto_config=false smt.arith.solver=4"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_RDL
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.026s  |1200.026s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.023s  |1200.023s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 126.938s  | 126.938s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 547.829s  | 547.829s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.026s  |1200.026s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.023s  |1200.023s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 126.938s  | 126.938s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 547.829s  | 547.829s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.026s  |1200.026s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.023s  |1200.023s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 126.938s  | 126.938s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 547.829s  | 547.829s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.026s  |1200.026s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.023s  |1200.023s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 126.938s  | 126.938s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 547.829s  | 547.829s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled120626.smt2                                                                       |1200.043s |88.156MiB|
|scrambled36692.smt2                                                                        |1200.030s |89.204MiB|
|scrambled68857.smt2                                                                        |1200.028s |89.376MiB|
|scrambled36439.smt2                                                                        |1200.028s |88.084MiB|
|scrambled43005.smt2                                                                        |1200.028s |89.628MiB|
|scrambled114492.smt2                                                                       |1200.028s |87.724MiB|
|scrambled69775.smt2                                                                        |1200.027s |61.208MiB|
|scrambled7069.smt2                                                                         |1200.027s |64.556MiB|
|scrambled19322.smt2                                                                        |1200.027s |88.072MiB|
|scrambled118796.smt2                                                                       |1200.027s |64.044MiB|
|scrambled55916.smt2                                                                        |1200.027s |64.792MiB|
|scrambled5175.smt2                                                                         |1200.027s |61.356MiB|
|scrambled111948.smt2                                                                       |1200.026s |58.688MiB|
|scrambled95269.smt2                                                                        |1200.025s |60.1MiB|
|scrambled106386.smt2                                                                       |1200.025s |88.064MiB|
|scrambled116502.smt2                                                                       |1200.023s |90.6MiB|
|scrambled73226.smt2                                                                        |1200.020s |64.176MiB|
|scrambled57711.smt2                                                                        |1200.019s |90.368MiB|
|scrambled64619.smt2                                                                        |1200.019s |90.516MiB|
|scrambled103636.smt2                                                                       |1200.018s |63.516MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled120626.smt2                                                                       |1200.043s |88.156MiB|
|scrambled36692.smt2                                                                        |1200.030s |89.204MiB|
|scrambled68857.smt2                                                                        |1200.028s |89.376MiB|
|scrambled36439.smt2                                                                        |1200.028s |88.084MiB|
|scrambled43005.smt2                                                                        |1200.028s |89.628MiB|
|scrambled114492.smt2                                                                       |1200.028s |87.724MiB|
|scrambled69775.smt2                                                                        |1200.027s |61.208MiB|
|scrambled7069.smt2                                                                         |1200.027s |64.556MiB|
|scrambled19322.smt2                                                                        |1200.027s |88.072MiB|
|scrambled118796.smt2                                                                       |1200.027s |64.044MiB|
|scrambled55916.smt2                                                                        |1200.027s |64.792MiB|
|scrambled5175.smt2                                                                         |1200.027s |61.356MiB|
|scrambled111948.smt2                                                                       |1200.026s |58.688MiB|
|scrambled95269.smt2                                                                        |1200.025s |60.1MiB|
|scrambled106386.smt2                                                                       |1200.025s |88.064MiB|
|scrambled116502.smt2                                                                       |1200.023s |90.6MiB|
|scrambled73226.smt2                                                                        |1200.020s |64.176MiB|
|scrambled57711.smt2                                                                        |1200.019s |90.368MiB|
|scrambled64619.smt2                                                                        |1200.019s |90.516MiB|
|scrambled103636.smt2                                                                       |1200.018s |63.516MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |59.808MiB|59.808MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |63.516MiB|63.516MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |88.064MiB|88.064MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |58.688MiB|58.688MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |87.724MiB|87.724MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |90.6MiB|90.6MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |64.044MiB|64.044MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |88.156MiB|88.156MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |56.184MiB|56.184MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |88.072MiB|88.072MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |43.792MiB|43.792MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |88.084MiB|88.084MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |89.204MiB|89.204MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |89.628MiB|89.628MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |54.188MiB|54.188MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |61.356MiB|61.356MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |64.792MiB|64.792MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |90.368MiB|90.368MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |90.516MiB|90.516MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |89.376MiB|89.376MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |59.808MiB|59.808MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |63.516MiB|63.516MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |88.064MiB|88.064MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |58.688MiB|58.688MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |87.724MiB|87.724MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |90.6MiB|90.6MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |64.044MiB|64.044MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |88.156MiB|88.156MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |56.184MiB|56.184MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |88.072MiB|88.072MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |43.792MiB|43.792MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |88.084MiB|88.084MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |89.204MiB|89.204MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |89.628MiB|89.628MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |54.188MiB|54.188MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |61.356MiB|61.356MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |64.792MiB|64.792MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |90.368MiB|90.368MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |90.516MiB|90.516MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |89.376MiB|89.376MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |59.808MiB|59.808MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |63.516MiB|63.516MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |88.064MiB|88.064MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |58.688MiB|58.688MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |87.724MiB|87.724MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |90.6MiB|90.6MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |64.044MiB|64.044MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |88.156MiB|88.156MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |56.184MiB|56.184MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |88.072MiB|88.072MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |43.792MiB|43.792MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |88.084MiB|88.084MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |89.204MiB|89.204MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |89.628MiB|89.628MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |54.188MiB|54.188MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |61.356MiB|61.356MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |64.792MiB|64.792MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |90.368MiB|90.368MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |90.516MiB|90.516MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |89.376MiB|89.376MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |59.808MiB|59.808MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |63.516MiB|63.516MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |88.064MiB|88.064MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |58.688MiB|58.688MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |87.724MiB|87.724MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |90.6MiB|90.6MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |64.044MiB|64.044MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |88.156MiB|88.156MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |56.184MiB|56.184MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |88.072MiB|88.072MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |43.792MiB|43.792MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |88.084MiB|88.084MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |89.204MiB|89.204MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |89.628MiB|89.628MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |54.188MiB|54.188MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |61.356MiB|61.356MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |64.792MiB|64.792MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |90.368MiB|90.368MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |90.516MiB|90.516MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |89.376MiB|89.376MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled116502.smt2                                                                       |1200.023s |90.6MiB|
|scrambled64619.smt2                                                                        |1200.019s |90.516MiB|
|scrambled57711.smt2                                                                        |1200.019s |90.368MiB|
|scrambled43005.smt2                                                                        |1200.028s |89.628MiB|
|scrambled68857.smt2                                                                        |1200.028s |89.376MiB|
|scrambled36692.smt2                                                                        |1200.030s |89.204MiB|
|scrambled120626.smt2                                                                       |1200.043s |88.156MiB|
|scrambled36439.smt2                                                                        |1200.028s |88.084MiB|
|scrambled19322.smt2                                                                        |1200.027s |88.072MiB|
|scrambled106386.smt2                                                                       |1200.025s |88.064MiB|
|scrambled114492.smt2                                                                       |1200.028s |87.724MiB|
|scrambled55916.smt2                                                                        |1200.027s |64.792MiB|
|scrambled7069.smt2                                                                         |1200.027s |64.556MiB|
|scrambled73226.smt2                                                                        |1200.020s |64.176MiB|
|scrambled118796.smt2                                                                       |1200.027s |64.044MiB|
|scrambled103636.smt2                                                                       |1200.018s |63.516MiB|
|scrambled5175.smt2                                                                         |1200.027s |61.356MiB|
|scrambled69775.smt2                                                                        |1200.027s |61.208MiB|
|scrambled95269.smt2                                                                        |1200.025s |60.1MiB|
|scrambled103130.smt2                                                                       |1200.018s |59.808MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled116502.smt2                                                                       |1200.023s |90.6MiB|
|scrambled64619.smt2                                                                        |1200.019s |90.516MiB|
|scrambled57711.smt2                                                                        |1200.019s |90.368MiB|
|scrambled43005.smt2                                                                        |1200.028s |89.628MiB|
|scrambled68857.smt2                                                                        |1200.028s |89.376MiB|
|scrambled36692.smt2                                                                        |1200.030s |89.204MiB|
|scrambled120626.smt2                                                                       |1200.043s |88.156MiB|
|scrambled36439.smt2                                                                        |1200.028s |88.084MiB|
|scrambled19322.smt2                                                                        |1200.027s |88.072MiB|
|scrambled106386.smt2                                                                       |1200.025s |88.064MiB|
|scrambled114492.smt2                                                                       |1200.028s |87.724MiB|
|scrambled55916.smt2                                                                        |1200.027s |64.792MiB|
|scrambled7069.smt2                                                                         |1200.027s |64.556MiB|
|scrambled73226.smt2                                                                        |1200.020s |64.176MiB|
|scrambled118796.smt2                                                                       |1200.027s |64.044MiB|
|scrambled103636.smt2                                                                       |1200.018s |63.516MiB|
|scrambled5175.smt2                                                                         |1200.027s |61.356MiB|
|scrambled69775.smt2                                                                        |1200.027s |61.208MiB|
|scrambled95269.smt2                                                                        |1200.025s |60.1MiB|
|scrambled103130.smt2                                                                       |1200.018s |59.808MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.026s  |1200.026s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.023s  |1200.023s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         | 126.938s  | 126.938s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         | 547.829s  | 547.829s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled69775.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled7069.smt2                                                                          |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled73226.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
</details>
