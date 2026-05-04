Comparing data and data


# SUMMARY
- LHS tests = 38
- RHS tests = 38
- LHS success = 38  (100.0%)
- RHS success = 38  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LRA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LRA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.006s  |1201.006s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.259s  |1201.259s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1201.669s  |1201.669s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.693s  |1200.693s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.629s  |1201.629s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        | 942.152s  | 942.152s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 310.842s  | 310.842s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.452s  |1200.452s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.483s  |1201.483s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.117s  |1202.117s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.419s  |1200.419s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.158s  |1201.158s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.736s  |1200.736s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.006s  |1201.006s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.259s  |1201.259s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1201.669s  |1201.669s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.693s  |1200.693s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.629s  |1201.629s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        | 942.152s  | 942.152s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 310.842s  | 310.842s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.452s  |1200.452s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.483s  |1201.483s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.117s  |1202.117s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.419s  |1200.419s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.158s  |1201.158s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.736s  |1200.736s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.006s  |1201.006s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.259s  |1201.259s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1201.669s  |1201.669s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.693s  |1200.693s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.629s  |1201.629s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        | 942.152s  | 942.152s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 310.842s  | 310.842s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.452s  |1200.452s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.483s  |1201.483s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.117s  |1202.117s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.419s  |1200.419s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.158s  |1201.158s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.736s  |1200.736s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.006s  |1201.006s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.259s  |1201.259s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1201.669s  |1201.669s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.693s  |1200.693s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.629s  |1201.629s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        | 942.152s  | 942.152s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 310.842s  | 310.842s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.452s  |1200.452s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.483s  |1201.483s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.117s  |1202.117s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.419s  |1200.419s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.158s  |1201.158s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.736s  |1200.736s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1202.117s |21.2GiB|
|scrambled102680.smt2                                                                       |1201.669s |12.969GiB|
|scrambled111949.smt2                                                                       |1201.629s |16.483GiB|
|scrambled13169.smt2                                                                        |1201.483s |11.819GiB|
|scrambled55850.smt2                                                                        |1201.478s |10.571GiB|
|scrambled102621.smt2                                                                       |1201.259s |11.702GiB|
|scrambled8163.smt2                                                                         |1201.213s |11.874GiB|
|scrambled98986.smt2                                                                        |1201.204s |11.235GiB|
|scrambled25695.smt2                                                                        |1201.158s |11.637GiB|
|scrambled101728.smt2                                                                       |1201.006s |9696.0MiB|
|scrambled37260.smt2                                                                        |1200.736s |6466.0MiB|
|scrambled77008.smt2                                                                        |1200.712s |6305.0MiB|
|scrambled109307.smt2                                                                       |1200.693s |6179.0MiB|
|scrambled47581.smt2                                                                        |1200.623s |3144.0MiB|
|scrambled95284.smt2                                                                        |1200.465s |3676.0MiB|
|scrambled124455.smt2                                                                       |1200.452s |4034.0MiB|
|scrambled76525.smt2                                                                        |1200.420s |3005.0MiB|
|scrambled17583.smt2                                                                        |1200.419s |2883.0MiB|
|scrambled55845.smt2                                                                        |1200.281s |1683.0MiB|
|scrambled71015.smt2                                                                        |1200.153s |1049.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1202.117s |21.2GiB|
|scrambled102680.smt2                                                                       |1201.669s |12.969GiB|
|scrambled111949.smt2                                                                       |1201.629s |16.483GiB|
|scrambled13169.smt2                                                                        |1201.483s |11.819GiB|
|scrambled55850.smt2                                                                        |1201.478s |10.571GiB|
|scrambled102621.smt2                                                                       |1201.259s |11.702GiB|
|scrambled8163.smt2                                                                         |1201.213s |11.874GiB|
|scrambled98986.smt2                                                                        |1201.204s |11.235GiB|
|scrambled25695.smt2                                                                        |1201.158s |11.637GiB|
|scrambled101728.smt2                                                                       |1201.006s |9696.0MiB|
|scrambled37260.smt2                                                                        |1200.736s |6466.0MiB|
|scrambled77008.smt2                                                                        |1200.712s |6305.0MiB|
|scrambled109307.smt2                                                                       |1200.693s |6179.0MiB|
|scrambled47581.smt2                                                                        |1200.623s |3144.0MiB|
|scrambled95284.smt2                                                                        |1200.465s |3676.0MiB|
|scrambled124455.smt2                                                                       |1200.452s |4034.0MiB|
|scrambled76525.smt2                                                                        |1200.420s |3005.0MiB|
|scrambled17583.smt2                                                                        |1200.419s |2883.0MiB|
|scrambled55845.smt2                                                                        |1200.281s |1683.0MiB|
|scrambled71015.smt2                                                                        |1200.153s |1049.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |9696.0MiB|9696.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |11.702GiB|11.702GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |12.969GiB|12.969GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |292.0MiB|292.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |376.0MiB|376.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |6179.0MiB|6179.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |16.483GiB|16.483GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |558.0MiB|558.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |6835.0MiB|6835.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |532.0MiB|532.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |4034.0MiB|4034.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |307.0MiB|307.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |11.819GiB|11.819GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |21.2GiB|21.2GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2883.0MiB|2883.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |11.637GiB|11.637GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |473.0MiB|473.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |605.0MiB|605.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |6466.0MiB|6466.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |9696.0MiB|9696.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |11.702GiB|11.702GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |12.969GiB|12.969GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |292.0MiB|292.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |376.0MiB|376.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |6179.0MiB|6179.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |16.483GiB|16.483GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |558.0MiB|558.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |6835.0MiB|6835.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |532.0MiB|532.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |4034.0MiB|4034.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |307.0MiB|307.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |11.819GiB|11.819GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |21.2GiB|21.2GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2883.0MiB|2883.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |11.637GiB|11.637GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |473.0MiB|473.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |605.0MiB|605.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |6466.0MiB|6466.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |9696.0MiB|9696.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |11.702GiB|11.702GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |12.969GiB|12.969GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |292.0MiB|292.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |376.0MiB|376.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |6179.0MiB|6179.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |16.483GiB|16.483GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |558.0MiB|558.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |6835.0MiB|6835.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |532.0MiB|532.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |4034.0MiB|4034.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |307.0MiB|307.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |11.819GiB|11.819GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |21.2GiB|21.2GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2883.0MiB|2883.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |11.637GiB|11.637GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |473.0MiB|473.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |605.0MiB|605.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |6466.0MiB|6466.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |9696.0MiB|9696.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |11.702GiB|11.702GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |12.969GiB|12.969GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |292.0MiB|292.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |376.0MiB|376.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |6179.0MiB|6179.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |16.483GiB|16.483GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |558.0MiB|558.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |6835.0MiB|6835.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |532.0MiB|532.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |4034.0MiB|4034.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |307.0MiB|307.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |11.819GiB|11.819GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |21.2GiB|21.2GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2883.0MiB|2883.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |11.637GiB|11.637GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |473.0MiB|473.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |605.0MiB|605.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |6466.0MiB|6466.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1202.117s |21.2GiB|
|scrambled111949.smt2                                                                       |1201.629s |16.483GiB|
|scrambled102680.smt2                                                                       |1201.669s |12.969GiB|
|scrambled44527.smt2                                                                        | 546.169s |12.547GiB|
|scrambled8163.smt2                                                                         |1201.213s |11.874GiB|
|scrambled13169.smt2                                                                        |1201.483s |11.819GiB|
|scrambled102621.smt2                                                                       |1201.259s |11.702GiB|
|scrambled25695.smt2                                                                        |1201.158s |11.637GiB|
|scrambled98986.smt2                                                                        |1201.204s |11.235GiB|
|scrambled55850.smt2                                                                        |1201.478s |10.571GiB|
|scrambled101728.smt2                                                                       |1201.006s |9696.0MiB|
|scrambled117897.smt2                                                                       | 942.152s |6835.0MiB|
|scrambled37260.smt2                                                                        |1200.736s |6466.0MiB|
|scrambled77008.smt2                                                                        |1200.712s |6305.0MiB|
|scrambled109307.smt2                                                                       |1200.693s |6179.0MiB|
|scrambled124455.smt2                                                                       |1200.452s |4034.0MiB|
|scrambled95284.smt2                                                                        |1200.465s |3676.0MiB|
|scrambled47581.smt2                                                                        |1200.623s |3144.0MiB|
|scrambled76525.smt2                                                                        |1200.420s |3005.0MiB|
|scrambled17583.smt2                                                                        |1200.419s |2883.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1202.117s |21.2GiB|
|scrambled111949.smt2                                                                       |1201.629s |16.483GiB|
|scrambled102680.smt2                                                                       |1201.669s |12.969GiB|
|scrambled44527.smt2                                                                        | 546.169s |12.547GiB|
|scrambled8163.smt2                                                                         |1201.213s |11.874GiB|
|scrambled13169.smt2                                                                        |1201.483s |11.819GiB|
|scrambled102621.smt2                                                                       |1201.259s |11.702GiB|
|scrambled25695.smt2                                                                        |1201.158s |11.637GiB|
|scrambled98986.smt2                                                                        |1201.204s |11.235GiB|
|scrambled55850.smt2                                                                        |1201.478s |10.571GiB|
|scrambled101728.smt2                                                                       |1201.006s |9696.0MiB|
|scrambled117897.smt2                                                                       | 942.152s |6835.0MiB|
|scrambled37260.smt2                                                                        |1200.736s |6466.0MiB|
|scrambled77008.smt2                                                                        |1200.712s |6305.0MiB|
|scrambled109307.smt2                                                                       |1200.693s |6179.0MiB|
|scrambled124455.smt2                                                                       |1200.452s |4034.0MiB|
|scrambled95284.smt2                                                                        |1200.465s |3676.0MiB|
|scrambled47581.smt2                                                                        |1200.623s |3144.0MiB|
|scrambled76525.smt2                                                                        |1200.420s |3005.0MiB|
|scrambled17583.smt2                                                                        |1200.419s |2883.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.006s  |1201.006s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.259s  |1201.259s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1201.669s  |1201.669s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.693s  |1200.693s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1201.629s  |1201.629s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        | 942.152s  | 942.152s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 310.842s  | 310.842s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.452s  |1200.452s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.483s  |1201.483s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.117s  |1202.117s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.419s  |1200.419s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.158s  |1201.158s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.736s  |1200.736s  |   0.000s  | 0.0%|
|scrambled44527.smt2                                                                         | 546.169s  | 546.169s  |   0.000s  | 0.0%|
|scrambled46192.smt2                                                                         |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled47581.smt2                                                                         |1200.623s  |1200.623s  |   0.000s  | 0.0%|
|scrambled49820.smt2                                                                         |1200.132s  |1200.132s  |   0.000s  | 0.0%|
|scrambled55845.smt2                                                                         |1200.281s  |1200.281s  |   0.000s  | 0.0%|
|scrambled55850.smt2                                                                         |1201.478s  |1201.478s  |   0.000s  | 0.0%|
|scrambled59368.smt2                                                                         | 286.934s  | 286.934s  |   0.000s  | 0.0%|
|scrambled65517.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled71015.smt2                                                                         |1200.153s  |1200.153s  |   0.000s  | 0.0%|
|scrambled76525.smt2                                                                         |1200.420s  |1200.420s  |   0.000s  | 0.0%|
|scrambled76532.smt2                                                                         |1200.125s  |1200.125s  |   0.000s  | 0.0%|
|scrambled77008.smt2                                                                         |1200.712s  |1200.712s  |   0.000s  | 0.0%|
|scrambled77308.smt2                                                                         |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled8163.smt2                                                                          |1201.213s  |1201.213s  |   0.000s  | 0.0%|
|scrambled88927.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled92964.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled95284.smt2                                                                         |1200.465s  |1200.465s  |   0.000s  | 0.0%|
</details>
