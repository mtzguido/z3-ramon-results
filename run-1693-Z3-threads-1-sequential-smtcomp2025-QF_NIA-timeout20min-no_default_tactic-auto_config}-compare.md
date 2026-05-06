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
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_NIA-timeout20min-no_default_tactic-auto_config}
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
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_NIA-timeout20min-no_default_tactic-auto_config}
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
|scrambled100714.smt2                                                                        |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   7.699s  |   7.699s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  49.306s  |  49.306s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 527.965s  | 527.965s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  16.038s  |  16.038s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  86.562s  |  86.562s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  44.961s  |  44.961s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   2.688s  |   2.688s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.058s  |1200.058s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   7.699s  |   7.699s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  49.306s  |  49.306s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 527.965s  | 527.965s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  16.038s  |  16.038s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  86.562s  |  86.562s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  44.961s  |  44.961s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   2.688s  |   2.688s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.058s  |1200.058s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   7.699s  |   7.699s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  49.306s  |  49.306s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 527.965s  | 527.965s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  16.038s  |  16.038s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  86.562s  |  86.562s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  44.961s  |  44.961s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   2.688s  |   2.688s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.058s  |1200.058s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   7.699s  |   7.699s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  49.306s  |  49.306s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 527.965s  | 527.965s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  16.038s  |  16.038s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  86.562s  |  86.562s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  44.961s  |  44.961s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   2.688s  |   2.688s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.058s  |1200.058s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.452s |3806.0MiB|
|scrambled73755.smt2                                                                        |1200.108s |483.0MiB|
|scrambled98111.smt2                                                                        |1200.095s |429.0MiB|
|scrambled39467.smt2                                                                        |1200.093s |508.0MiB|
|scrambled82760.smt2                                                                        |1200.085s |593.0MiB|
|scrambled91750.smt2                                                                        |1200.081s |339.0MiB|
|scrambled108406.smt2                                                                       |1200.079s |227.0MiB|
|scrambled31071.smt2                                                                        |1200.078s |248.0MiB|
|scrambled122926.smt2                                                                       |1200.076s |409.0MiB|
|scrambled100714.smt2                                                                       |1200.073s |328.0MiB|
|scrambled79354.smt2                                                                        |1200.073s |204.0MiB|
|scrambled108663.smt2                                                                       |1200.072s |289.0MiB|
|scrambled12033.smt2                                                                        |1200.070s |307.0MiB|
|scrambled87588.smt2                                                                        |1200.068s |150.0MiB|
|scrambled130111.smt2                                                                       |1200.068s |241.0MiB|
|scrambled80288.smt2                                                                        |1200.067s |213.0MiB|
|scrambled9883.smt2                                                                         |1200.066s |323.0MiB|
|scrambled73281.smt2                                                                        |1200.065s |196.0MiB|
|scrambled101716.smt2                                                                       |1200.065s |187.0MiB|
|scrambled62032.smt2                                                                        |1200.063s |709.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.452s |3806.0MiB|
|scrambled73755.smt2                                                                        |1200.108s |483.0MiB|
|scrambled98111.smt2                                                                        |1200.095s |429.0MiB|
|scrambled39467.smt2                                                                        |1200.093s |508.0MiB|
|scrambled82760.smt2                                                                        |1200.085s |593.0MiB|
|scrambled91750.smt2                                                                        |1200.081s |339.0MiB|
|scrambled108406.smt2                                                                       |1200.079s |227.0MiB|
|scrambled31071.smt2                                                                        |1200.078s |248.0MiB|
|scrambled122926.smt2                                                                       |1200.076s |409.0MiB|
|scrambled100714.smt2                                                                       |1200.073s |328.0MiB|
|scrambled79354.smt2                                                                        |1200.073s |204.0MiB|
|scrambled108663.smt2                                                                       |1200.072s |289.0MiB|
|scrambled12033.smt2                                                                        |1200.070s |307.0MiB|
|scrambled87588.smt2                                                                        |1200.068s |150.0MiB|
|scrambled130111.smt2                                                                       |1200.068s |241.0MiB|
|scrambled80288.smt2                                                                        |1200.067s |213.0MiB|
|scrambled9883.smt2                                                                         |1200.066s |323.0MiB|
|scrambled73281.smt2                                                                        |1200.065s |196.0MiB|
|scrambled101716.smt2                                                                       |1200.065s |187.0MiB|
|scrambled62032.smt2                                                                        |1200.063s |709.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |328.0MiB|328.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |187.0MiB|187.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |166.0MiB|166.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |227.0MiB|227.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |289.0MiB|289.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |199.0MiB|199.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |307.0MiB|307.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |409.0MiB|409.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |41.676MiB|41.676MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |61.532MiB|61.532MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |726.0MiB|726.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |101.0MiB|101.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |139.0MiB|139.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |32.508MiB|32.508MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |22.724MiB|22.724MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |248.0MiB|248.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |22.484MiB|22.484MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |80.972MiB|80.972MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |233.0MiB|233.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |328.0MiB|328.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |187.0MiB|187.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |166.0MiB|166.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |227.0MiB|227.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |289.0MiB|289.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |199.0MiB|199.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |307.0MiB|307.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |409.0MiB|409.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |41.676MiB|41.676MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |61.532MiB|61.532MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |726.0MiB|726.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |101.0MiB|101.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |139.0MiB|139.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |32.508MiB|32.508MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |22.724MiB|22.724MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |248.0MiB|248.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |22.484MiB|22.484MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |80.972MiB|80.972MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |233.0MiB|233.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |328.0MiB|328.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |187.0MiB|187.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |166.0MiB|166.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |227.0MiB|227.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |289.0MiB|289.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |199.0MiB|199.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |307.0MiB|307.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |409.0MiB|409.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |41.676MiB|41.676MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |61.532MiB|61.532MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |726.0MiB|726.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |101.0MiB|101.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |139.0MiB|139.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |32.508MiB|32.508MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |22.724MiB|22.724MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |248.0MiB|248.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |22.484MiB|22.484MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |80.972MiB|80.972MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |233.0MiB|233.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |328.0MiB|328.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |187.0MiB|187.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |166.0MiB|166.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |227.0MiB|227.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |289.0MiB|289.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |199.0MiB|199.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |307.0MiB|307.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |409.0MiB|409.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |41.676MiB|41.676MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |61.532MiB|61.532MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |726.0MiB|726.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |101.0MiB|101.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |139.0MiB|139.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |32.508MiB|32.508MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |22.724MiB|22.724MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |248.0MiB|248.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |22.484MiB|22.484MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |80.972MiB|80.972MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |233.0MiB|233.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.452s |3806.0MiB|
|scrambled41135.smt2                                                                        |1200.050s |1394.0MiB|
|scrambled14845.smt2                                                                        | 527.965s |726.0MiB|
|scrambled62032.smt2                                                                        |1200.063s |709.0MiB|
|scrambled82760.smt2                                                                        |1200.085s |593.0MiB|
|scrambled39467.smt2                                                                        |1200.093s |508.0MiB|
|scrambled73755.smt2                                                                        |1200.108s |483.0MiB|
|scrambled98111.smt2                                                                        |1200.095s |429.0MiB|
|scrambled122926.smt2                                                                       |1200.076s |409.0MiB|
|scrambled47700.smt2                                                                        |1200.045s |341.0MiB|
|scrambled91750.smt2                                                                        |1200.081s |339.0MiB|
|scrambled38587.smt2                                                                        |1200.063s |335.0MiB|
|scrambled100714.smt2                                                                       |1200.073s |328.0MiB|
|scrambled9883.smt2                                                                         |1200.066s |323.0MiB|
|scrambled12033.smt2                                                                        |1200.070s |307.0MiB|
|scrambled108663.smt2                                                                       |1200.072s |289.0MiB|
|scrambled31071.smt2                                                                        |1200.078s |248.0MiB|
|scrambled97386.smt2                                                                        |1200.059s |245.0MiB|
|scrambled130111.smt2                                                                       |1200.068s |241.0MiB|
|scrambled36790.smt2                                                                        |1200.058s |233.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.452s |3806.0MiB|
|scrambled41135.smt2                                                                        |1200.050s |1394.0MiB|
|scrambled14845.smt2                                                                        | 527.965s |726.0MiB|
|scrambled62032.smt2                                                                        |1200.063s |709.0MiB|
|scrambled82760.smt2                                                                        |1200.085s |593.0MiB|
|scrambled39467.smt2                                                                        |1200.093s |508.0MiB|
|scrambled73755.smt2                                                                        |1200.108s |483.0MiB|
|scrambled98111.smt2                                                                        |1200.095s |429.0MiB|
|scrambled122926.smt2                                                                       |1200.076s |409.0MiB|
|scrambled47700.smt2                                                                        |1200.045s |341.0MiB|
|scrambled91750.smt2                                                                        |1200.081s |339.0MiB|
|scrambled38587.smt2                                                                        |1200.063s |335.0MiB|
|scrambled100714.smt2                                                                       |1200.073s |328.0MiB|
|scrambled9883.smt2                                                                         |1200.066s |323.0MiB|
|scrambled12033.smt2                                                                        |1200.070s |307.0MiB|
|scrambled108663.smt2                                                                       |1200.072s |289.0MiB|
|scrambled31071.smt2                                                                        |1200.078s |248.0MiB|
|scrambled97386.smt2                                                                        |1200.059s |245.0MiB|
|scrambled130111.smt2                                                                       |1200.068s |241.0MiB|
|scrambled36790.smt2                                                                        |1200.058s |233.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   7.699s  |   7.699s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  49.306s  |  49.306s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 527.965s  | 527.965s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  16.038s  |  16.038s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  86.562s  |  86.562s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  44.961s  |  44.961s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   2.688s  |   2.688s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   2.997s  |   2.997s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   4.024s  |   4.024s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 359.558s  | 359.558s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   6.956s  |   6.956s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1200.452s  |1200.452s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.081s  |1200.081s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |  19.233s  |  19.233s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         | 227.371s  | 227.371s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
</details>
