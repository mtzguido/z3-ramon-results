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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2
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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2
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
|scrambled100714.smt2                                                                        |1200.143s  |1200.143s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.188s  |1200.188s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  54.068s  |  54.068s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.428s  |1200.428s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.553s  |1200.553s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.325s  |1200.325s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.449s  |1200.449s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.529s  |  10.529s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  14.540s  |  14.540s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.306s  |1200.306s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 503.504s  | 503.504s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.276s  |  14.276s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  29.293s  |  29.293s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.553s  |  21.553s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.472s  |   4.472s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 190.098s  | 190.098s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.126s  |1200.126s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.273s  |1200.273s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.143s  |1200.143s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.188s  |1200.188s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  54.068s  |  54.068s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.428s  |1200.428s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.553s  |1200.553s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.325s  |1200.325s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.449s  |1200.449s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.529s  |  10.529s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  14.540s  |  14.540s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.306s  |1200.306s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 503.504s  | 503.504s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.276s  |  14.276s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  29.293s  |  29.293s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.553s  |  21.553s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.472s  |   4.472s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 190.098s  | 190.098s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.126s  |1200.126s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.273s  |1200.273s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.143s  |1200.143s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.188s  |1200.188s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  54.068s  |  54.068s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.428s  |1200.428s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.553s  |1200.553s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.325s  |1200.325s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.449s  |1200.449s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.529s  |  10.529s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  14.540s  |  14.540s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.306s  |1200.306s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 503.504s  | 503.504s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.276s  |  14.276s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  29.293s  |  29.293s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.553s  |  21.553s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.472s  |   4.472s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 190.098s  | 190.098s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.126s  |1200.126s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.273s  |1200.273s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.143s  |1200.143s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.188s  |1200.188s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  54.068s  |  54.068s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.428s  |1200.428s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.553s  |1200.553s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.325s  |1200.325s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.449s  |1200.449s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.529s  |  10.529s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  14.540s  |  14.540s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.306s  |1200.306s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 503.504s  | 503.504s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.276s  |  14.276s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  29.293s  |  29.293s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.553s  |  21.553s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.472s  |   4.472s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 190.098s  | 190.098s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.126s  |1200.126s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.273s  |1200.273s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.808s |28.144GiB|
|scrambled87588.smt2                                                                        |1200.599s |5925.0MiB|
|scrambled73755.smt2                                                                        |1200.595s |5296.0MiB|
|scrambled108663.smt2                                                                       |1200.553s |3773.0MiB|
|scrambled122926.smt2                                                                       |1200.449s |3796.0MiB|
|scrambled91750.smt2                                                                        |1200.429s |2827.0MiB|
|scrambled108406.smt2                                                                       |1200.428s |3115.0MiB|
|scrambled82760.smt2                                                                        |1200.390s |3662.0MiB|
|scrambled47700.smt2                                                                        |1200.351s |3171.0MiB|
|scrambled62032.smt2                                                                        |1200.329s |3069.0MiB|
|scrambled12033.smt2                                                                        |1200.325s |2914.0MiB|
|scrambled39467.smt2                                                                        |1200.316s |2699.0MiB|
|scrambled130111.smt2                                                                       |1200.306s |1926.0MiB|
|scrambled36790.smt2                                                                        |1200.273s |1726.0MiB|
|scrambled58311.smt2                                                                        |1200.266s |2617.0MiB|
|scrambled79354.smt2                                                                        |1200.257s |1738.0MiB|
|scrambled97386.smt2                                                                        |1200.227s |1616.0MiB|
|scrambled73281.smt2                                                                        |1200.226s |1746.0MiB|
|scrambled38587.smt2                                                                        |1200.188s |1944.0MiB|
|scrambled101716.smt2                                                                       |1200.188s |1457.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.808s |28.144GiB|
|scrambled87588.smt2                                                                        |1200.599s |5925.0MiB|
|scrambled73755.smt2                                                                        |1200.595s |5296.0MiB|
|scrambled108663.smt2                                                                       |1200.553s |3773.0MiB|
|scrambled122926.smt2                                                                       |1200.449s |3796.0MiB|
|scrambled91750.smt2                                                                        |1200.429s |2827.0MiB|
|scrambled108406.smt2                                                                       |1200.428s |3115.0MiB|
|scrambled82760.smt2                                                                        |1200.390s |3662.0MiB|
|scrambled47700.smt2                                                                        |1200.351s |3171.0MiB|
|scrambled62032.smt2                                                                        |1200.329s |3069.0MiB|
|scrambled12033.smt2                                                                        |1200.325s |2914.0MiB|
|scrambled39467.smt2                                                                        |1200.316s |2699.0MiB|
|scrambled130111.smt2                                                                       |1200.306s |1926.0MiB|
|scrambled36790.smt2                                                                        |1200.273s |1726.0MiB|
|scrambled58311.smt2                                                                        |1200.266s |2617.0MiB|
|scrambled79354.smt2                                                                        |1200.257s |1738.0MiB|
|scrambled97386.smt2                                                                        |1200.227s |1616.0MiB|
|scrambled73281.smt2                                                                        |1200.226s |1746.0MiB|
|scrambled38587.smt2                                                                        |1200.188s |1944.0MiB|
|scrambled101716.smt2                                                                       |1200.188s |1457.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1236.0MiB|1236.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1457.0MiB|1457.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |454.0MiB|454.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |3115.0MiB|3115.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3773.0MiB|3773.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1462.0MiB|1462.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2914.0MiB|2914.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3796.0MiB|3796.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |450.0MiB|450.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |358.0MiB|358.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1926.0MiB|1926.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6639.0MiB|6639.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1070.0MiB|1070.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |652.0MiB|652.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |283.0MiB|283.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |832.0MiB|832.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |964.0MiB|964.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1726.0MiB|1726.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1236.0MiB|1236.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1457.0MiB|1457.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |454.0MiB|454.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |3115.0MiB|3115.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3773.0MiB|3773.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1462.0MiB|1462.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2914.0MiB|2914.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3796.0MiB|3796.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |450.0MiB|450.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |358.0MiB|358.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1926.0MiB|1926.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6639.0MiB|6639.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1070.0MiB|1070.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |652.0MiB|652.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |283.0MiB|283.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |832.0MiB|832.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |964.0MiB|964.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1726.0MiB|1726.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1236.0MiB|1236.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1457.0MiB|1457.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |454.0MiB|454.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |3115.0MiB|3115.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3773.0MiB|3773.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1462.0MiB|1462.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2914.0MiB|2914.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3796.0MiB|3796.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |450.0MiB|450.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |358.0MiB|358.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1926.0MiB|1926.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6639.0MiB|6639.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1070.0MiB|1070.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |652.0MiB|652.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |283.0MiB|283.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |832.0MiB|832.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |964.0MiB|964.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1726.0MiB|1726.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1236.0MiB|1236.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1457.0MiB|1457.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |454.0MiB|454.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |3115.0MiB|3115.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3773.0MiB|3773.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1462.0MiB|1462.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2914.0MiB|2914.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3796.0MiB|3796.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |450.0MiB|450.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |358.0MiB|358.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1926.0MiB|1926.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6639.0MiB|6639.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1070.0MiB|1070.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |652.0MiB|652.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |283.0MiB|283.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |832.0MiB|832.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |964.0MiB|964.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1726.0MiB|1726.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.808s |28.144GiB|
|scrambled14845.smt2                                                                        | 503.504s |6639.0MiB|
|scrambled87588.smt2                                                                        |1200.599s |5925.0MiB|
|scrambled73755.smt2                                                                        |1200.595s |5296.0MiB|
|scrambled122926.smt2                                                                       |1200.449s |3796.0MiB|
|scrambled108663.smt2                                                                       |1200.553s |3773.0MiB|
|scrambled82760.smt2                                                                        |1200.390s |3662.0MiB|
|scrambled47700.smt2                                                                        |1200.351s |3171.0MiB|
|scrambled108406.smt2                                                                       |1200.428s |3115.0MiB|
|scrambled62032.smt2                                                                        |1200.329s |3069.0MiB|
|scrambled12033.smt2                                                                        |1200.325s |2914.0MiB|
|scrambled91750.smt2                                                                        |1200.429s |2827.0MiB|
|scrambled39467.smt2                                                                        |1200.316s |2699.0MiB|
|scrambled58311.smt2                                                                        |1200.266s |2617.0MiB|
|scrambled8852.smt2                                                                         |1200.121s |2186.0MiB|
|scrambled38587.smt2                                                                        |1200.188s |1944.0MiB|
|scrambled130111.smt2                                                                       |1200.306s |1926.0MiB|
|scrambled41135.smt2                                                                        |1200.184s |1885.0MiB|
|scrambled73281.smt2                                                                        |1200.226s |1746.0MiB|
|scrambled79354.smt2                                                                        |1200.257s |1738.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.808s |28.144GiB|
|scrambled14845.smt2                                                                        | 503.504s |6639.0MiB|
|scrambled87588.smt2                                                                        |1200.599s |5925.0MiB|
|scrambled73755.smt2                                                                        |1200.595s |5296.0MiB|
|scrambled122926.smt2                                                                       |1200.449s |3796.0MiB|
|scrambled108663.smt2                                                                       |1200.553s |3773.0MiB|
|scrambled82760.smt2                                                                        |1200.390s |3662.0MiB|
|scrambled47700.smt2                                                                        |1200.351s |3171.0MiB|
|scrambled108406.smt2                                                                       |1200.428s |3115.0MiB|
|scrambled62032.smt2                                                                        |1200.329s |3069.0MiB|
|scrambled12033.smt2                                                                        |1200.325s |2914.0MiB|
|scrambled91750.smt2                                                                        |1200.429s |2827.0MiB|
|scrambled39467.smt2                                                                        |1200.316s |2699.0MiB|
|scrambled58311.smt2                                                                        |1200.266s |2617.0MiB|
|scrambled8852.smt2                                                                         |1200.121s |2186.0MiB|
|scrambled38587.smt2                                                                        |1200.188s |1944.0MiB|
|scrambled130111.smt2                                                                       |1200.306s |1926.0MiB|
|scrambled41135.smt2                                                                        |1200.184s |1885.0MiB|
|scrambled73281.smt2                                                                        |1200.226s |1746.0MiB|
|scrambled79354.smt2                                                                        |1200.257s |1738.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.143s  |1200.143s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.188s  |1200.188s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  54.068s  |  54.068s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.428s  |1200.428s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.553s  |1200.553s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.325s  |1200.325s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.449s  |1200.449s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.529s  |  10.529s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  14.540s  |  14.540s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.306s  |1200.306s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 503.504s  | 503.504s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.276s  |  14.276s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  29.293s  |  29.293s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.553s  |  21.553s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.472s  |   4.472s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 190.098s  | 190.098s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.126s  |1200.126s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.273s  |1200.273s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.188s  |1200.188s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.316s  |1200.316s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.351s  |1200.351s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   5.555s  |   5.555s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.953s  |   0.953s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.266s  |1200.266s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 115.792s  | 115.792s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.329s  |1200.329s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.226s  |1200.226s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.595s  |1200.595s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.257s  |1200.257s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         |  96.850s  |  96.850s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   6.420s  |   6.420s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.390s  |1200.390s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1202.808s  |1202.808s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.599s  |1200.599s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.429s  |1200.429s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   4.912s  |   4.912s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         | 768.875s  | 768.875s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.227s  |1200.227s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.180s  |1200.180s  |   0.000s  | 0.0%|
</details>
