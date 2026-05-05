Comparing data and data


# SUMMARY
- LHS tests = 44
- RHS tests = 44
- LHS success = 44  (100.0%)
- RHS success = 44  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-no_default_tactic
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-no_default_tactic
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.130s  |1200.130s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.433s  |1200.433s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |1200.141s  |1200.141s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   1.630s  |   1.630s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.130s  |1200.130s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.433s  |1200.433s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |1200.141s  |1200.141s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   1.630s  |   1.630s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.130s  |1200.130s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.433s  |1200.433s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |1200.141s  |1200.141s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   1.630s  |   1.630s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.130s  |1200.130s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.433s  |1200.433s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |1200.141s  |1200.141s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   1.630s  |   1.630s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.049s |31.463GiB|
|scrambled73755.smt2                                                                        |1200.636s |5001.0MiB|
|scrambled12033.smt2                                                                        |1200.433s |3027.0MiB|
|scrambled14845.smt2                                                                        |1200.141s |1146.0MiB|
|scrambled98111.smt2                                                                        |1200.139s |267.0MiB|
|scrambled48569.smt2                                                                        |1200.138s |777.0MiB|
|scrambled122926.smt2                                                                       |1200.137s |696.0MiB|
|scrambled73281.smt2                                                                        |1200.135s |319.0MiB|
|scrambled108663.smt2                                                                       |1200.130s |338.0MiB|
|scrambled61060.smt2                                                                        |1200.129s |658.0MiB|
|scrambled17293.smt2                                                                        |1200.112s |619.0MiB|
|scrambled41135.smt2                                                                        |1200.112s |420.0MiB|
|scrambled108406.smt2                                                                       |1200.110s |424.0MiB|
|scrambled97386.smt2                                                                        |1200.109s |586.0MiB|
|scrambled130111.smt2                                                                       |1200.106s |557.0MiB|
|scrambled36790.smt2                                                                        |1200.097s |472.0MiB|
|scrambled31071.smt2                                                                        |1200.097s |466.0MiB|
|scrambled91750.smt2                                                                        |1200.093s |595.0MiB|
|scrambled96401.smt2                                                                        |1200.087s |511.0MiB|
|scrambled87588.smt2                                                                        |1200.083s |302.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.049s |31.463GiB|
|scrambled73755.smt2                                                                        |1200.636s |5001.0MiB|
|scrambled12033.smt2                                                                        |1200.433s |3027.0MiB|
|scrambled14845.smt2                                                                        |1200.141s |1146.0MiB|
|scrambled98111.smt2                                                                        |1200.139s |267.0MiB|
|scrambled48569.smt2                                                                        |1200.138s |777.0MiB|
|scrambled122926.smt2                                                                       |1200.137s |696.0MiB|
|scrambled73281.smt2                                                                        |1200.135s |319.0MiB|
|scrambled108663.smt2                                                                       |1200.130s |338.0MiB|
|scrambled61060.smt2                                                                        |1200.129s |658.0MiB|
|scrambled17293.smt2                                                                        |1200.112s |619.0MiB|
|scrambled41135.smt2                                                                        |1200.112s |420.0MiB|
|scrambled108406.smt2                                                                       |1200.110s |424.0MiB|
|scrambled97386.smt2                                                                        |1200.109s |586.0MiB|
|scrambled130111.smt2                                                                       |1200.106s |557.0MiB|
|scrambled36790.smt2                                                                        |1200.097s |472.0MiB|
|scrambled31071.smt2                                                                        |1200.097s |466.0MiB|
|scrambled91750.smt2                                                                        |1200.093s |595.0MiB|
|scrambled96401.smt2                                                                        |1200.087s |511.0MiB|
|scrambled87588.smt2                                                                        |1200.083s |302.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |259.0MiB|259.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |254.0MiB|254.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |424.0MiB|424.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |338.0MiB|338.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |378.0MiB|378.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |3027.0MiB|3027.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |696.0MiB|696.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |321.0MiB|321.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |281.0MiB|281.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |557.0MiB|557.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |1146.0MiB|1146.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |619.0MiB|619.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |240.0MiB|240.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |278.0MiB|278.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |466.0MiB|466.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |264.0MiB|264.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |257.0MiB|257.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |472.0MiB|472.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |259.0MiB|259.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |254.0MiB|254.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |424.0MiB|424.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |338.0MiB|338.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |378.0MiB|378.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |3027.0MiB|3027.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |696.0MiB|696.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |321.0MiB|321.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |281.0MiB|281.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |557.0MiB|557.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |1146.0MiB|1146.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |619.0MiB|619.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |240.0MiB|240.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |278.0MiB|278.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |466.0MiB|466.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |264.0MiB|264.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |257.0MiB|257.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |472.0MiB|472.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |259.0MiB|259.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |254.0MiB|254.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |424.0MiB|424.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |338.0MiB|338.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |378.0MiB|378.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |3027.0MiB|3027.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |696.0MiB|696.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |321.0MiB|321.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |281.0MiB|281.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |557.0MiB|557.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |1146.0MiB|1146.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |619.0MiB|619.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |240.0MiB|240.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |278.0MiB|278.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |466.0MiB|466.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |264.0MiB|264.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |257.0MiB|257.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |472.0MiB|472.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |259.0MiB|259.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |254.0MiB|254.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |424.0MiB|424.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |338.0MiB|338.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |378.0MiB|378.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |3027.0MiB|3027.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |696.0MiB|696.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |321.0MiB|321.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |281.0MiB|281.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |557.0MiB|557.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |1146.0MiB|1146.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |619.0MiB|619.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |240.0MiB|240.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |278.0MiB|278.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |466.0MiB|466.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |264.0MiB|264.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |257.0MiB|257.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |472.0MiB|472.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.049s |31.463GiB|
|scrambled73755.smt2                                                                        |1200.636s |5001.0MiB|
|scrambled12033.smt2                                                                        |1200.433s |3027.0MiB|
|scrambled14845.smt2                                                                        |1200.141s |1146.0MiB|
|scrambled48569.smt2                                                                        |1200.138s |777.0MiB|
|scrambled122926.smt2                                                                       |1200.137s |696.0MiB|
|scrambled61060.smt2                                                                        |1200.129s |658.0MiB|
|scrambled17293.smt2                                                                        |1200.112s |619.0MiB|
|scrambled91750.smt2                                                                        |1200.093s |595.0MiB|
|scrambled97386.smt2                                                                        |1200.109s |586.0MiB|
|scrambled130111.smt2                                                                       |1200.106s |557.0MiB|
|scrambled96401.smt2                                                                        |1200.087s |511.0MiB|
|scrambled47700.smt2                                                                        |1200.083s |475.0MiB|
|scrambled36790.smt2                                                                        |1200.097s |472.0MiB|
|scrambled31071.smt2                                                                        |1200.097s |466.0MiB|
|scrambled108406.smt2                                                                       |1200.110s |424.0MiB|
|scrambled41135.smt2                                                                        |1200.112s |420.0MiB|
|scrambled119582.smt2                                                                       |1200.057s |378.0MiB|
|scrambled28176.smt2                                                                        |1200.070s |354.0MiB|
|scrambled101716.smt2                                                                       |1200.064s |354.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.049s |31.463GiB|
|scrambled73755.smt2                                                                        |1200.636s |5001.0MiB|
|scrambled12033.smt2                                                                        |1200.433s |3027.0MiB|
|scrambled14845.smt2                                                                        |1200.141s |1146.0MiB|
|scrambled48569.smt2                                                                        |1200.138s |777.0MiB|
|scrambled122926.smt2                                                                       |1200.137s |696.0MiB|
|scrambled61060.smt2                                                                        |1200.129s |658.0MiB|
|scrambled17293.smt2                                                                        |1200.112s |619.0MiB|
|scrambled91750.smt2                                                                        |1200.093s |595.0MiB|
|scrambled97386.smt2                                                                        |1200.109s |586.0MiB|
|scrambled130111.smt2                                                                       |1200.106s |557.0MiB|
|scrambled96401.smt2                                                                        |1200.087s |511.0MiB|
|scrambled47700.smt2                                                                        |1200.083s |475.0MiB|
|scrambled36790.smt2                                                                        |1200.097s |472.0MiB|
|scrambled31071.smt2                                                                        |1200.097s |466.0MiB|
|scrambled108406.smt2                                                                       |1200.110s |424.0MiB|
|scrambled41135.smt2                                                                        |1200.112s |420.0MiB|
|scrambled119582.smt2                                                                       |1200.057s |378.0MiB|
|scrambled28176.smt2                                                                        |1200.070s |354.0MiB|
|scrambled101716.smt2                                                                       |1200.064s |354.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.130s  |1200.130s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.433s  |1200.433s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |1200.141s  |1200.141s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   1.630s  |   1.630s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.071s  |1200.071s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   1.187s  |   1.187s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.071s  |1200.071s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         |1200.129s  |1200.129s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.636s  |1200.636s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1203.049s  |1203.049s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
</details>
