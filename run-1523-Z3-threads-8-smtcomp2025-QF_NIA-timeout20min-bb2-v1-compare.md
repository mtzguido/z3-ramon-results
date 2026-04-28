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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-v1
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 4e0f9c891a995745172a1fc312ffb9b4544561e3
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: ablate continuous checking for batch bb mode

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-v1
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 4e0f9c891a995745172a1fc312ffb9b4544561e3
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: ablate continuous checking for batch bb mode

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.153s  |1200.153s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  46.688s  |  46.688s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.400s  |1200.400s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.465s  |1200.465s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.341s  |1200.341s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.315s  |1200.315s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.464s  |1200.464s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.519s  |  11.519s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  20.812s  |  20.812s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.307s  |1200.307s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 492.136s  | 492.136s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  26.712s  |  26.712s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 187.244s  | 187.244s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  28.987s  |  28.987s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.936s  |   4.936s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.263s  |1200.263s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.165s  |1200.165s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.345s  |1200.345s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.153s  |1200.153s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  46.688s  |  46.688s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.400s  |1200.400s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.465s  |1200.465s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.341s  |1200.341s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.315s  |1200.315s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.464s  |1200.464s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.519s  |  11.519s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  20.812s  |  20.812s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.307s  |1200.307s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 492.136s  | 492.136s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  26.712s  |  26.712s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 187.244s  | 187.244s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  28.987s  |  28.987s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.936s  |   4.936s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.263s  |1200.263s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.165s  |1200.165s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.345s  |1200.345s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.153s  |1200.153s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  46.688s  |  46.688s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.400s  |1200.400s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.465s  |1200.465s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.341s  |1200.341s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.315s  |1200.315s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.464s  |1200.464s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.519s  |  11.519s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  20.812s  |  20.812s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.307s  |1200.307s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 492.136s  | 492.136s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  26.712s  |  26.712s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 187.244s  | 187.244s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  28.987s  |  28.987s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.936s  |   4.936s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.263s  |1200.263s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.165s  |1200.165s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.345s  |1200.345s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.153s  |1200.153s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  46.688s  |  46.688s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.400s  |1200.400s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.465s  |1200.465s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.341s  |1200.341s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.315s  |1200.315s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.464s  |1200.464s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.519s  |  11.519s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  20.812s  |  20.812s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.307s  |1200.307s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 492.136s  | 492.136s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  26.712s  |  26.712s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 187.244s  | 187.244s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  28.987s  |  28.987s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.936s  |   4.936s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.263s  |1200.263s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.165s  |1200.165s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.345s  |1200.345s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.694s |29.827GiB|
|scrambled73755.smt2                                                                        |1200.581s |5266.0MiB|
|scrambled82760.smt2                                                                        |1200.532s |2054.0MiB|
|scrambled108663.smt2                                                                       |1200.465s |3375.0MiB|
|scrambled122926.smt2                                                                       |1200.464s |3764.0MiB|
|scrambled47700.smt2                                                                        |1200.425s |3599.0MiB|
|scrambled97386.smt2                                                                        |1200.401s |1611.0MiB|
|scrambled108406.smt2                                                                       |1200.400s |3802.0MiB|
|scrambled9883.smt2                                                                         |1200.346s |1392.0MiB|
|scrambled36790.smt2                                                                        |1200.345s |1772.0MiB|
|scrambled62032.smt2                                                                        |1200.345s |3213.0MiB|
|scrambled38587.smt2                                                                        |1200.345s |1966.0MiB|
|scrambled119582.smt2                                                                       |1200.341s |1452.0MiB|
|scrambled39467.smt2                                                                        |1200.339s |2709.0MiB|
|scrambled12033.smt2                                                                        |1200.315s |2977.0MiB|
|scrambled130111.smt2                                                                       |1200.307s |1971.0MiB|
|scrambled91750.smt2                                                                        |1200.306s |2811.0MiB|
|scrambled87588.smt2                                                                        |1200.300s |2709.0MiB|
|scrambled73281.smt2                                                                        |1200.265s |2179.0MiB|
|scrambled31071.smt2                                                                        |1200.263s |2112.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.694s |29.827GiB|
|scrambled73755.smt2                                                                        |1200.581s |5266.0MiB|
|scrambled82760.smt2                                                                        |1200.532s |2054.0MiB|
|scrambled108663.smt2                                                                       |1200.465s |3375.0MiB|
|scrambled122926.smt2                                                                       |1200.464s |3764.0MiB|
|scrambled47700.smt2                                                                        |1200.425s |3599.0MiB|
|scrambled97386.smt2                                                                        |1200.401s |1611.0MiB|
|scrambled108406.smt2                                                                       |1200.400s |3802.0MiB|
|scrambled9883.smt2                                                                         |1200.346s |1392.0MiB|
|scrambled36790.smt2                                                                        |1200.345s |1772.0MiB|
|scrambled62032.smt2                                                                        |1200.345s |3213.0MiB|
|scrambled38587.smt2                                                                        |1200.345s |1966.0MiB|
|scrambled119582.smt2                                                                       |1200.341s |1452.0MiB|
|scrambled39467.smt2                                                                        |1200.339s |2709.0MiB|
|scrambled12033.smt2                                                                        |1200.315s |2977.0MiB|
|scrambled130111.smt2                                                                       |1200.307s |1971.0MiB|
|scrambled91750.smt2                                                                        |1200.306s |2811.0MiB|
|scrambled87588.smt2                                                                        |1200.300s |2709.0MiB|
|scrambled73281.smt2                                                                        |1200.265s |2179.0MiB|
|scrambled31071.smt2                                                                        |1200.263s |2112.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1212.0MiB|1212.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1464.0MiB|1464.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |3802.0MiB|3802.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3375.0MiB|3375.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1452.0MiB|1452.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2977.0MiB|2977.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3764.0MiB|3764.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |439.0MiB|439.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |416.0MiB|416.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1971.0MiB|1971.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6742.0MiB|6742.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1151.0MiB|1151.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1322.0MiB|1322.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |294.0MiB|294.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |311.0MiB|311.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |2112.0MiB|2112.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |965.0MiB|965.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1772.0MiB|1772.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1212.0MiB|1212.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1464.0MiB|1464.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |3802.0MiB|3802.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3375.0MiB|3375.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1452.0MiB|1452.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2977.0MiB|2977.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3764.0MiB|3764.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |439.0MiB|439.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |416.0MiB|416.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1971.0MiB|1971.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6742.0MiB|6742.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1151.0MiB|1151.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1322.0MiB|1322.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |294.0MiB|294.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |311.0MiB|311.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |2112.0MiB|2112.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |965.0MiB|965.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1772.0MiB|1772.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1212.0MiB|1212.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1464.0MiB|1464.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |3802.0MiB|3802.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3375.0MiB|3375.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1452.0MiB|1452.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2977.0MiB|2977.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3764.0MiB|3764.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |439.0MiB|439.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |416.0MiB|416.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1971.0MiB|1971.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6742.0MiB|6742.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1151.0MiB|1151.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1322.0MiB|1322.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |294.0MiB|294.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |311.0MiB|311.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |2112.0MiB|2112.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |965.0MiB|965.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1772.0MiB|1772.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1212.0MiB|1212.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1464.0MiB|1464.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |370.0MiB|370.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |3802.0MiB|3802.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3375.0MiB|3375.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1452.0MiB|1452.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2977.0MiB|2977.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3764.0MiB|3764.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |439.0MiB|439.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |416.0MiB|416.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1971.0MiB|1971.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6742.0MiB|6742.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1151.0MiB|1151.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1322.0MiB|1322.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |294.0MiB|294.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |311.0MiB|311.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |2112.0MiB|2112.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |965.0MiB|965.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1772.0MiB|1772.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.694s |29.827GiB|
|scrambled14845.smt2                                                                        | 492.136s |6742.0MiB|
|scrambled73755.smt2                                                                        |1200.581s |5266.0MiB|
|scrambled108406.smt2                                                                       |1200.400s |3802.0MiB|
|scrambled122926.smt2                                                                       |1200.464s |3764.0MiB|
|scrambled47700.smt2                                                                        |1200.425s |3599.0MiB|
|scrambled108663.smt2                                                                       |1200.465s |3375.0MiB|
|scrambled62032.smt2                                                                        |1200.345s |3213.0MiB|
|scrambled12033.smt2                                                                        |1200.315s |2977.0MiB|
|scrambled91750.smt2                                                                        |1200.306s |2811.0MiB|
|scrambled39467.smt2                                                                        |1200.339s |2709.0MiB|
|scrambled87588.smt2                                                                        |1200.300s |2709.0MiB|
|scrambled73281.smt2                                                                        |1200.265s |2179.0MiB|
|scrambled31071.smt2                                                                        |1200.263s |2112.0MiB|
|scrambled82760.smt2                                                                        |1200.532s |2054.0MiB|
|scrambled130111.smt2                                                                       |1200.307s |1971.0MiB|
|scrambled38587.smt2                                                                        |1200.345s |1966.0MiB|
|scrambled58311.smt2                                                                        |1200.201s |1810.0MiB|
|scrambled41135.smt2                                                                        |1200.233s |1804.0MiB|
|scrambled36790.smt2                                                                        |1200.345s |1772.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.694s |29.827GiB|
|scrambled14845.smt2                                                                        | 492.136s |6742.0MiB|
|scrambled73755.smt2                                                                        |1200.581s |5266.0MiB|
|scrambled108406.smt2                                                                       |1200.400s |3802.0MiB|
|scrambled122926.smt2                                                                       |1200.464s |3764.0MiB|
|scrambled47700.smt2                                                                        |1200.425s |3599.0MiB|
|scrambled108663.smt2                                                                       |1200.465s |3375.0MiB|
|scrambled62032.smt2                                                                        |1200.345s |3213.0MiB|
|scrambled12033.smt2                                                                        |1200.315s |2977.0MiB|
|scrambled91750.smt2                                                                        |1200.306s |2811.0MiB|
|scrambled39467.smt2                                                                        |1200.339s |2709.0MiB|
|scrambled87588.smt2                                                                        |1200.300s |2709.0MiB|
|scrambled73281.smt2                                                                        |1200.265s |2179.0MiB|
|scrambled31071.smt2                                                                        |1200.263s |2112.0MiB|
|scrambled82760.smt2                                                                        |1200.532s |2054.0MiB|
|scrambled130111.smt2                                                                       |1200.307s |1971.0MiB|
|scrambled38587.smt2                                                                        |1200.345s |1966.0MiB|
|scrambled58311.smt2                                                                        |1200.201s |1810.0MiB|
|scrambled41135.smt2                                                                        |1200.233s |1804.0MiB|
|scrambled36790.smt2                                                                        |1200.345s |1772.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.153s  |1200.153s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  46.688s  |  46.688s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.400s  |1200.400s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.465s  |1200.465s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.341s  |1200.341s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.315s  |1200.315s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.464s  |1200.464s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  11.519s  |  11.519s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  20.812s  |  20.812s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.307s  |1200.307s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 492.136s  | 492.136s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  26.712s  |  26.712s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 187.244s  | 187.244s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  28.987s  |  28.987s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.936s  |   4.936s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.263s  |1200.263s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.165s  |1200.165s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.345s  |1200.345s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.345s  |1200.345s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.339s  |1200.339s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.233s  |1200.233s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.425s  |1200.425s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   5.724s  |   5.724s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.969s  |   0.969s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.201s  |1200.201s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 217.510s  | 217.510s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.345s  |1200.345s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.265s  |1200.265s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.581s  |1200.581s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.220s  |1200.220s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 239.287s  | 239.287s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   6.784s  |   6.784s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.532s  |1200.532s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1202.694s  |1202.694s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.300s  |1200.300s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.221s  |1200.221s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.306s  |1200.306s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   4.681s  |   4.681s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         | 737.985s  | 737.985s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.401s  |1200.401s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.168s  |1200.168s  |   0.000s  | 0.0%|
</details>
