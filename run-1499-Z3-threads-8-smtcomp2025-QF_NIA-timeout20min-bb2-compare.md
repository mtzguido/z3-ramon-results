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
Z3 commit: 4e9e3413ec6d3ed78d31f91f5c563e3531e9b393
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt_parallel.failed_literal_backbones=false smt_parallel.num_global_bb_chunking_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore old changes

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 4e9e3413ec6d3ed78d31f91f5c563e3531e9b393
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt_parallel.failed_literal_backbones=false smt_parallel.num_global_bb_chunking_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore old changes

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.445s  |1200.445s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.126s  |1200.126s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 342.657s  | 342.657s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   1.223s  |   1.223s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.109s  |1200.109s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.445s  |1200.445s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.126s  |1200.126s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 342.657s  | 342.657s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   1.223s  |   1.223s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.109s  |1200.109s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.445s  |1200.445s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.126s  |1200.126s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 342.657s  | 342.657s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   1.223s  |   1.223s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.109s  |1200.109s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.445s  |1200.445s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.126s  |1200.126s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 342.657s  | 342.657s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   1.223s  |   1.223s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.109s  |1200.109s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.433s |36.933GiB|
|scrambled73755.smt2                                                                        |1200.904s |5471.0MiB|
|scrambled12033.smt2                                                                        |1200.445s |3069.0MiB|
|scrambled122926.smt2                                                                       |1200.159s |725.0MiB|
|scrambled91750.smt2                                                                        |1200.156s |618.0MiB|
|scrambled17293.smt2                                                                        |1200.138s |840.0MiB|
|scrambled61060.smt2                                                                        |1200.129s |819.0MiB|
|scrambled130111.smt2                                                                       |1200.126s |659.0MiB|
|scrambled82760.smt2                                                                        |1200.120s |343.0MiB|
|scrambled36790.smt2                                                                        |1200.109s |560.0MiB|
|scrambled9883.smt2                                                                         |1200.109s |339.0MiB|
|scrambled119582.smt2                                                                       |1200.109s |367.0MiB|
|scrambled12959.smt2                                                                        |1200.105s |324.0MiB|
|scrambled62032.smt2                                                                        |1200.104s |330.0MiB|
|scrambled96401.smt2                                                                        |1200.098s |523.0MiB|
|scrambled47700.smt2                                                                        |1200.098s |393.0MiB|
|scrambled29780.smt2                                                                        |1200.090s |291.0MiB|
|scrambled97386.smt2                                                                        |1200.089s |585.0MiB|
|scrambled80288.smt2                                                                        |1200.088s |269.0MiB|
|scrambled129467.smt2                                                                       |1200.086s |465.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.433s |36.933GiB|
|scrambled73755.smt2                                                                        |1200.904s |5471.0MiB|
|scrambled12033.smt2                                                                        |1200.445s |3069.0MiB|
|scrambled122926.smt2                                                                       |1200.159s |725.0MiB|
|scrambled91750.smt2                                                                        |1200.156s |618.0MiB|
|scrambled17293.smt2                                                                        |1200.138s |840.0MiB|
|scrambled61060.smt2                                                                        |1200.129s |819.0MiB|
|scrambled130111.smt2                                                                       |1200.126s |659.0MiB|
|scrambled82760.smt2                                                                        |1200.120s |343.0MiB|
|scrambled36790.smt2                                                                        |1200.109s |560.0MiB|
|scrambled9883.smt2                                                                         |1200.109s |339.0MiB|
|scrambled119582.smt2                                                                       |1200.109s |367.0MiB|
|scrambled12959.smt2                                                                        |1200.105s |324.0MiB|
|scrambled62032.smt2                                                                        |1200.104s |330.0MiB|
|scrambled96401.smt2                                                                        |1200.098s |523.0MiB|
|scrambled47700.smt2                                                                        |1200.098s |393.0MiB|
|scrambled29780.smt2                                                                        |1200.090s |291.0MiB|
|scrambled97386.smt2                                                                        |1200.089s |585.0MiB|
|scrambled80288.smt2                                                                        |1200.088s |269.0MiB|
|scrambled129467.smt2                                                                       |1200.086s |465.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |258.0MiB|258.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |348.0MiB|348.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |329.0MiB|329.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |382.0MiB|382.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |343.0MiB|343.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |367.0MiB|367.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |3069.0MiB|3069.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |725.0MiB|725.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |465.0MiB|465.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |324.0MiB|324.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |659.0MiB|659.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5854.0MiB|5854.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |840.0MiB|840.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |470.0MiB|470.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |291.0MiB|291.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |240.0MiB|240.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |454.0MiB|454.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |449.0MiB|449.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |560.0MiB|560.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |258.0MiB|258.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |348.0MiB|348.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |329.0MiB|329.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |382.0MiB|382.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |343.0MiB|343.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |367.0MiB|367.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |3069.0MiB|3069.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |725.0MiB|725.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |465.0MiB|465.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |324.0MiB|324.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |659.0MiB|659.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5854.0MiB|5854.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |840.0MiB|840.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |470.0MiB|470.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |291.0MiB|291.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |240.0MiB|240.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |454.0MiB|454.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |449.0MiB|449.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |560.0MiB|560.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |258.0MiB|258.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |348.0MiB|348.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |329.0MiB|329.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |382.0MiB|382.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |343.0MiB|343.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |367.0MiB|367.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |3069.0MiB|3069.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |725.0MiB|725.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |465.0MiB|465.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |324.0MiB|324.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |659.0MiB|659.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5854.0MiB|5854.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |840.0MiB|840.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |470.0MiB|470.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |291.0MiB|291.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |240.0MiB|240.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |454.0MiB|454.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |449.0MiB|449.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |560.0MiB|560.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |258.0MiB|258.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |348.0MiB|348.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |329.0MiB|329.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |382.0MiB|382.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |343.0MiB|343.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |367.0MiB|367.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |3069.0MiB|3069.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |725.0MiB|725.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |465.0MiB|465.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |324.0MiB|324.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |659.0MiB|659.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |5854.0MiB|5854.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |840.0MiB|840.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |470.0MiB|470.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |291.0MiB|291.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |240.0MiB|240.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |454.0MiB|454.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |449.0MiB|449.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |560.0MiB|560.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.433s |36.933GiB|
|scrambled14845.smt2                                                                        | 342.657s |5854.0MiB|
|scrambled73755.smt2                                                                        |1200.904s |5471.0MiB|
|scrambled12033.smt2                                                                        |1200.445s |3069.0MiB|
|scrambled48569.smt2                                                                        |  41.390s |1324.0MiB|
|scrambled17293.smt2                                                                        |1200.138s |840.0MiB|
|scrambled61060.smt2                                                                        |1200.129s |819.0MiB|
|scrambled122926.smt2                                                                       |1200.159s |725.0MiB|
|scrambled130111.smt2                                                                       |1200.126s |659.0MiB|
|scrambled91750.smt2                                                                        |1200.156s |618.0MiB|
|scrambled97386.smt2                                                                        |1200.089s |585.0MiB|
|scrambled36790.smt2                                                                        |1200.109s |560.0MiB|
|scrambled96401.smt2                                                                        |1200.098s |523.0MiB|
|scrambled28176.smt2                                                                        |1200.074s |470.0MiB|
|scrambled129467.smt2                                                                       |1200.086s |465.0MiB|
|scrambled31071.smt2                                                                        |1200.079s |454.0MiB|
|scrambled35280.smt2                                                                        |1200.067s |449.0MiB|
|scrambled41135.smt2                                                                        |1200.085s |419.0MiB|
|scrambled47700.smt2                                                                        |1200.098s |393.0MiB|
|scrambled108406.smt2                                                                       |1200.060s |382.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1203.433s |36.933GiB|
|scrambled14845.smt2                                                                        | 342.657s |5854.0MiB|
|scrambled73755.smt2                                                                        |1200.904s |5471.0MiB|
|scrambled12033.smt2                                                                        |1200.445s |3069.0MiB|
|scrambled48569.smt2                                                                        |  41.390s |1324.0MiB|
|scrambled17293.smt2                                                                        |1200.138s |840.0MiB|
|scrambled61060.smt2                                                                        |1200.129s |819.0MiB|
|scrambled122926.smt2                                                                       |1200.159s |725.0MiB|
|scrambled130111.smt2                                                                       |1200.126s |659.0MiB|
|scrambled91750.smt2                                                                        |1200.156s |618.0MiB|
|scrambled97386.smt2                                                                        |1200.089s |585.0MiB|
|scrambled36790.smt2                                                                        |1200.109s |560.0MiB|
|scrambled96401.smt2                                                                        |1200.098s |523.0MiB|
|scrambled28176.smt2                                                                        |1200.074s |470.0MiB|
|scrambled129467.smt2                                                                       |1200.086s |465.0MiB|
|scrambled31071.smt2                                                                        |1200.079s |454.0MiB|
|scrambled35280.smt2                                                                        |1200.067s |449.0MiB|
|scrambled41135.smt2                                                                        |1200.085s |419.0MiB|
|scrambled47700.smt2                                                                        |1200.098s |393.0MiB|
|scrambled108406.smt2                                                                       |1200.060s |382.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.445s  |1200.445s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.159s  |1200.159s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.126s  |1200.126s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 342.657s  | 342.657s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   1.223s  |   1.223s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |  41.390s  |  41.390s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   1.744s  |   1.744s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         |1200.129s  |1200.129s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.104s  |1200.104s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.904s  |1200.904s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   8.841s  |   8.841s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1203.433s  |1203.433s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.156s  |1200.156s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.049s  |1200.049s  |   0.000s  | 0.0%|
</details>
