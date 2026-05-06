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
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_NIA-timeout20min-auto_config}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_NIA-timeout20min-auto_config}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   7.787s  |   7.787s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  48.742s  |  48.742s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 548.533s  | 548.533s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  19.820s  |  19.820s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  84.213s  |  84.213s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  45.202s  |  45.202s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   2.695s  |   2.695s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   7.787s  |   7.787s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  48.742s  |  48.742s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 548.533s  | 548.533s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  19.820s  |  19.820s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  84.213s  |  84.213s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  45.202s  |  45.202s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   2.695s  |   2.695s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   7.787s  |   7.787s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  48.742s  |  48.742s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 548.533s  | 548.533s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  19.820s  |  19.820s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  84.213s  |  84.213s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  45.202s  |  45.202s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   2.695s  |   2.695s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   7.787s  |   7.787s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  48.742s  |  48.742s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 548.533s  | 548.533s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  19.820s  |  19.820s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  84.213s  |  84.213s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  45.202s  |  45.202s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   2.695s  |   2.695s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.372s |4056.0MiB|
|scrambled82760.smt2                                                                        |1200.096s |593.0MiB|
|scrambled39467.smt2                                                                        |1200.088s |508.0MiB|
|scrambled73755.smt2                                                                        |1200.085s |483.0MiB|
|scrambled98111.smt2                                                                        |1200.078s |429.0MiB|
|scrambled41135.smt2                                                                        |1200.076s |1394.0MiB|
|scrambled47700.smt2                                                                        |1200.071s |340.0MiB|
|scrambled108663.smt2                                                                       |1200.066s |287.0MiB|
|scrambled31071.smt2                                                                        |1200.064s |246.0MiB|
|scrambled91750.smt2                                                                        |1200.063s |307.0MiB|
|scrambled130111.smt2                                                                       |1200.063s |236.0MiB|
|scrambled9883.smt2                                                                         |1200.054s |323.0MiB|
|scrambled12033.smt2                                                                        |1200.054s |307.0MiB|
|scrambled122926.smt2                                                                       |1200.050s |407.0MiB|
|scrambled101716.smt2                                                                       |1200.049s |187.0MiB|
|scrambled36790.smt2                                                                        |1200.047s |234.0MiB|
|scrambled108406.smt2                                                                       |1200.047s |227.0MiB|
|scrambled35280.smt2                                                                        |1200.043s |86.28MiB|
|scrambled62032.smt2                                                                        |1200.042s |709.0MiB|
|scrambled100714.smt2                                                                       |1200.041s |328.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.372s |4056.0MiB|
|scrambled82760.smt2                                                                        |1200.096s |593.0MiB|
|scrambled39467.smt2                                                                        |1200.088s |508.0MiB|
|scrambled73755.smt2                                                                        |1200.085s |483.0MiB|
|scrambled98111.smt2                                                                        |1200.078s |429.0MiB|
|scrambled41135.smt2                                                                        |1200.076s |1394.0MiB|
|scrambled47700.smt2                                                                        |1200.071s |340.0MiB|
|scrambled108663.smt2                                                                       |1200.066s |287.0MiB|
|scrambled31071.smt2                                                                        |1200.064s |246.0MiB|
|scrambled91750.smt2                                                                        |1200.063s |307.0MiB|
|scrambled130111.smt2                                                                       |1200.063s |236.0MiB|
|scrambled9883.smt2                                                                         |1200.054s |323.0MiB|
|scrambled12033.smt2                                                                        |1200.054s |307.0MiB|
|scrambled122926.smt2                                                                       |1200.050s |407.0MiB|
|scrambled101716.smt2                                                                       |1200.049s |187.0MiB|
|scrambled36790.smt2                                                                        |1200.047s |234.0MiB|
|scrambled108406.smt2                                                                       |1200.047s |227.0MiB|
|scrambled35280.smt2                                                                        |1200.043s |86.28MiB|
|scrambled62032.smt2                                                                        |1200.042s |709.0MiB|
|scrambled100714.smt2                                                                       |1200.041s |328.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |328.0MiB|328.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |187.0MiB|187.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |166.0MiB|166.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |227.0MiB|227.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |287.0MiB|287.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |199.0MiB|199.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |307.0MiB|307.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |407.0MiB|407.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |41.42MiB|41.42MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |61.276MiB|61.276MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |236.0MiB|236.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |726.0MiB|726.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |101.0MiB|101.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |139.0MiB|139.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |32.64MiB|32.64MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |22.396MiB|22.396MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |246.0MiB|246.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |22.432MiB|22.432MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |86.28MiB|86.28MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |234.0MiB|234.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |328.0MiB|328.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |187.0MiB|187.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |166.0MiB|166.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |227.0MiB|227.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |287.0MiB|287.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |199.0MiB|199.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |307.0MiB|307.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |407.0MiB|407.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |41.42MiB|41.42MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |61.276MiB|61.276MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |236.0MiB|236.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |726.0MiB|726.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |101.0MiB|101.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |139.0MiB|139.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |32.64MiB|32.64MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |22.396MiB|22.396MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |246.0MiB|246.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |22.432MiB|22.432MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |86.28MiB|86.28MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |234.0MiB|234.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |328.0MiB|328.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |187.0MiB|187.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |166.0MiB|166.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |227.0MiB|227.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |287.0MiB|287.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |199.0MiB|199.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |307.0MiB|307.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |407.0MiB|407.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |41.42MiB|41.42MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |61.276MiB|61.276MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |236.0MiB|236.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |726.0MiB|726.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |101.0MiB|101.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |139.0MiB|139.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |32.64MiB|32.64MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |22.396MiB|22.396MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |246.0MiB|246.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |22.432MiB|22.432MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |86.28MiB|86.28MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |234.0MiB|234.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |328.0MiB|328.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |187.0MiB|187.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |166.0MiB|166.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |227.0MiB|227.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |287.0MiB|287.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |199.0MiB|199.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |307.0MiB|307.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |407.0MiB|407.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |41.42MiB|41.42MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |61.276MiB|61.276MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |236.0MiB|236.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |726.0MiB|726.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |101.0MiB|101.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |139.0MiB|139.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |32.64MiB|32.64MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |22.396MiB|22.396MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |246.0MiB|246.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |22.432MiB|22.432MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |86.28MiB|86.28MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |234.0MiB|234.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.372s |4056.0MiB|
|scrambled41135.smt2                                                                        |1200.076s |1394.0MiB|
|scrambled14845.smt2                                                                        | 548.533s |726.0MiB|
|scrambled62032.smt2                                                                        |1200.042s |709.0MiB|
|scrambled82760.smt2                                                                        |1200.096s |593.0MiB|
|scrambled39467.smt2                                                                        |1200.088s |508.0MiB|
|scrambled73755.smt2                                                                        |1200.085s |483.0MiB|
|scrambled98111.smt2                                                                        |1200.078s |429.0MiB|
|scrambled122926.smt2                                                                       |1200.050s |407.0MiB|
|scrambled47700.smt2                                                                        |1200.071s |340.0MiB|
|scrambled38587.smt2                                                                        |1200.035s |335.0MiB|
|scrambled100714.smt2                                                                       |1200.041s |328.0MiB|
|scrambled9883.smt2                                                                         |1200.054s |323.0MiB|
|scrambled91750.smt2                                                                        |1200.063s |307.0MiB|
|scrambled12033.smt2                                                                        |1200.054s |307.0MiB|
|scrambled108663.smt2                                                                       |1200.066s |287.0MiB|
|scrambled31071.smt2                                                                        |1200.064s |246.0MiB|
|scrambled97386.smt2                                                                        |1200.031s |245.0MiB|
|scrambled130111.smt2                                                                       |1200.063s |236.0MiB|
|scrambled36790.smt2                                                                        |1200.047s |234.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.372s |4056.0MiB|
|scrambled41135.smt2                                                                        |1200.076s |1394.0MiB|
|scrambled14845.smt2                                                                        | 548.533s |726.0MiB|
|scrambled62032.smt2                                                                        |1200.042s |709.0MiB|
|scrambled82760.smt2                                                                        |1200.096s |593.0MiB|
|scrambled39467.smt2                                                                        |1200.088s |508.0MiB|
|scrambled73755.smt2                                                                        |1200.085s |483.0MiB|
|scrambled98111.smt2                                                                        |1200.078s |429.0MiB|
|scrambled122926.smt2                                                                       |1200.050s |407.0MiB|
|scrambled47700.smt2                                                                        |1200.071s |340.0MiB|
|scrambled38587.smt2                                                                        |1200.035s |335.0MiB|
|scrambled100714.smt2                                                                       |1200.041s |328.0MiB|
|scrambled9883.smt2                                                                         |1200.054s |323.0MiB|
|scrambled91750.smt2                                                                        |1200.063s |307.0MiB|
|scrambled12033.smt2                                                                        |1200.054s |307.0MiB|
|scrambled108663.smt2                                                                       |1200.066s |287.0MiB|
|scrambled31071.smt2                                                                        |1200.064s |246.0MiB|
|scrambled97386.smt2                                                                        |1200.031s |245.0MiB|
|scrambled130111.smt2                                                                       |1200.063s |236.0MiB|
|scrambled36790.smt2                                                                        |1200.047s |234.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   7.787s  |   7.787s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  48.742s  |  48.742s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 548.533s  | 548.533s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  19.820s  |  19.820s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  84.213s  |  84.213s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  45.202s  |  45.202s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   2.695s  |   2.695s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.071s  |1200.071s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   2.876s  |   2.876s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   4.004s  |   4.004s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 357.679s  | 357.679s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.029s  |1200.029s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   6.930s  |   6.930s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1200.372s  |1200.372s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |  19.465s  |  19.465s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         | 227.233s  | 227.233s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.078s  |1200.078s  |   0.000s  | 0.0%|
</details>
