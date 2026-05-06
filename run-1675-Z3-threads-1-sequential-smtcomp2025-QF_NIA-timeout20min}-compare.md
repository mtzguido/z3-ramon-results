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
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_NIA-timeout20min}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_NIA-timeout20min}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.012s  |1200.012s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        | 599.089s  | 599.089s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   8.337s  |   8.337s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  51.795s  |  51.795s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 307.802s  | 307.802s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |   5.217s  |   5.217s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  42.322s  |  42.322s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   5.241s  |   5.241s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 672.668s  | 672.668s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.012s  |1200.012s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        | 599.089s  | 599.089s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   8.337s  |   8.337s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  51.795s  |  51.795s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 307.802s  | 307.802s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |   5.217s  |   5.217s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  42.322s  |  42.322s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   5.241s  |   5.241s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 672.668s  | 672.668s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.012s  |1200.012s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        | 599.089s  | 599.089s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   8.337s  |   8.337s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  51.795s  |  51.795s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 307.802s  | 307.802s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |   5.217s  |   5.217s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  42.322s  |  42.322s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   5.241s  |   5.241s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 672.668s  | 672.668s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.012s  |1200.012s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        | 599.089s  | 599.089s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   8.337s  |   8.337s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  51.795s  |  51.795s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 307.802s  | 307.802s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |   5.217s  |   5.217s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  42.322s  |  42.322s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   5.241s  |   5.241s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 672.668s  | 672.668s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.554s |4053.0MiB|
|scrambled80288.smt2                                                                        |1200.189s |1295.0MiB|
|scrambled39467.smt2                                                                        |1200.127s |424.0MiB|
|scrambled122926.smt2                                                                       |1200.120s |378.0MiB|
|scrambled73755.smt2                                                                        |1200.107s |501.0MiB|
|scrambled12033.smt2                                                                        |1200.101s |300.0MiB|
|scrambled108406.smt2                                                                       |1200.090s |299.0MiB|
|scrambled97386.smt2                                                                        |1200.088s |249.0MiB|
|scrambled62032.smt2                                                                        |1200.084s |199.0MiB|
|scrambled28176.smt2                                                                        |1200.080s |1183.0MiB|
|scrambled130111.smt2                                                                       |1200.074s |260.0MiB|
|scrambled119582.smt2                                                                       |1200.070s |200.0MiB|
|scrambled9883.smt2                                                                         |1200.069s |324.0MiB|
|scrambled36790.smt2                                                                        |1200.065s |198.0MiB|
|scrambled58311.smt2                                                                        |1200.065s |114.0MiB|
|scrambled79354.smt2                                                                        |1200.062s |194.0MiB|
|scrambled96401.smt2                                                                        |1200.060s |154.0MiB|
|scrambled101716.smt2                                                                       |1200.055s |188.0MiB|
|scrambled91750.smt2                                                                        |1200.054s |350.0MiB|
|scrambled82760.smt2                                                                        |1200.051s |182.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.554s |4053.0MiB|
|scrambled80288.smt2                                                                        |1200.189s |1295.0MiB|
|scrambled39467.smt2                                                                        |1200.127s |424.0MiB|
|scrambled122926.smt2                                                                       |1200.120s |378.0MiB|
|scrambled73755.smt2                                                                        |1200.107s |501.0MiB|
|scrambled12033.smt2                                                                        |1200.101s |300.0MiB|
|scrambled108406.smt2                                                                       |1200.090s |299.0MiB|
|scrambled97386.smt2                                                                        |1200.088s |249.0MiB|
|scrambled62032.smt2                                                                        |1200.084s |199.0MiB|
|scrambled28176.smt2                                                                        |1200.080s |1183.0MiB|
|scrambled130111.smt2                                                                       |1200.074s |260.0MiB|
|scrambled119582.smt2                                                                       |1200.070s |200.0MiB|
|scrambled9883.smt2                                                                         |1200.069s |324.0MiB|
|scrambled36790.smt2                                                                        |1200.065s |198.0MiB|
|scrambled58311.smt2                                                                        |1200.065s |114.0MiB|
|scrambled79354.smt2                                                                        |1200.062s |194.0MiB|
|scrambled96401.smt2                                                                        |1200.060s |154.0MiB|
|scrambled101716.smt2                                                                       |1200.055s |188.0MiB|
|scrambled91750.smt2                                                                        |1200.054s |350.0MiB|
|scrambled82760.smt2                                                                        |1200.051s |182.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |23.02MiB|23.02MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |188.0MiB|188.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |81.932MiB|81.932MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |299.0MiB|299.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |206.0MiB|206.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |200.0MiB|200.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |300.0MiB|300.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |378.0MiB|378.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |43.032MiB|43.032MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |79.52MiB|79.52MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |260.0MiB|260.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |605.0MiB|605.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |95.58MiB|95.58MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1183.0MiB|1183.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |31.492MiB|31.492MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |26.708MiB|26.708MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |178.0MiB|178.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |20.824MiB|20.824MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |47.048MiB|47.048MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |198.0MiB|198.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |23.02MiB|23.02MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |188.0MiB|188.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |81.932MiB|81.932MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |299.0MiB|299.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |206.0MiB|206.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |200.0MiB|200.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |300.0MiB|300.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |378.0MiB|378.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |43.032MiB|43.032MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |79.52MiB|79.52MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |260.0MiB|260.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |605.0MiB|605.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |95.58MiB|95.58MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1183.0MiB|1183.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |31.492MiB|31.492MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |26.708MiB|26.708MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |178.0MiB|178.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |20.824MiB|20.824MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |47.048MiB|47.048MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |198.0MiB|198.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |23.02MiB|23.02MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |188.0MiB|188.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |81.932MiB|81.932MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |299.0MiB|299.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |206.0MiB|206.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |200.0MiB|200.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |300.0MiB|300.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |378.0MiB|378.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |43.032MiB|43.032MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |79.52MiB|79.52MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |260.0MiB|260.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |605.0MiB|605.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |95.58MiB|95.58MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1183.0MiB|1183.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |31.492MiB|31.492MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |26.708MiB|26.708MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |178.0MiB|178.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |20.824MiB|20.824MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |47.048MiB|47.048MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |198.0MiB|198.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |23.02MiB|23.02MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |188.0MiB|188.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |81.932MiB|81.932MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |299.0MiB|299.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |206.0MiB|206.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |200.0MiB|200.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |300.0MiB|300.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |378.0MiB|378.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |43.032MiB|43.032MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |79.52MiB|79.52MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |260.0MiB|260.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |605.0MiB|605.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |95.58MiB|95.58MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |1183.0MiB|1183.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |31.492MiB|31.492MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |26.708MiB|26.708MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |178.0MiB|178.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |20.824MiB|20.824MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |47.048MiB|47.048MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |198.0MiB|198.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.554s |4053.0MiB|
|scrambled80288.smt2                                                                        |1200.189s |1295.0MiB|
|scrambled28176.smt2                                                                        |1200.080s |1183.0MiB|
|scrambled14845.smt2                                                                        | 307.802s |605.0MiB|
|scrambled73755.smt2                                                                        |1200.107s |501.0MiB|
|scrambled39467.smt2                                                                        |1200.127s |424.0MiB|
|scrambled122926.smt2                                                                       |1200.120s |378.0MiB|
|scrambled91750.smt2                                                                        |1200.054s |350.0MiB|
|scrambled38587.smt2                                                                        |1200.039s |334.0MiB|
|scrambled9883.smt2                                                                         |1200.069s |324.0MiB|
|scrambled12033.smt2                                                                        |1200.101s |300.0MiB|
|scrambled108406.smt2                                                                       |1200.090s |299.0MiB|
|scrambled130111.smt2                                                                       |1200.074s |260.0MiB|
|scrambled97386.smt2                                                                        |1200.088s |249.0MiB|
|scrambled8852.smt2                                                                         |1200.050s |248.0MiB|
|scrambled108663.smt2                                                                       |1200.051s |206.0MiB|
|scrambled119582.smt2                                                                       |1200.070s |200.0MiB|
|scrambled62032.smt2                                                                        |1200.084s |199.0MiB|
|scrambled36790.smt2                                                                        |1200.065s |198.0MiB|
|scrambled79354.smt2                                                                        |1200.062s |194.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1200.554s |4053.0MiB|
|scrambled80288.smt2                                                                        |1200.189s |1295.0MiB|
|scrambled28176.smt2                                                                        |1200.080s |1183.0MiB|
|scrambled14845.smt2                                                                        | 307.802s |605.0MiB|
|scrambled73755.smt2                                                                        |1200.107s |501.0MiB|
|scrambled39467.smt2                                                                        |1200.127s |424.0MiB|
|scrambled122926.smt2                                                                       |1200.120s |378.0MiB|
|scrambled91750.smt2                                                                        |1200.054s |350.0MiB|
|scrambled38587.smt2                                                                        |1200.039s |334.0MiB|
|scrambled9883.smt2                                                                         |1200.069s |324.0MiB|
|scrambled12033.smt2                                                                        |1200.101s |300.0MiB|
|scrambled108406.smt2                                                                       |1200.090s |299.0MiB|
|scrambled130111.smt2                                                                       |1200.074s |260.0MiB|
|scrambled97386.smt2                                                                        |1200.088s |249.0MiB|
|scrambled8852.smt2                                                                         |1200.050s |248.0MiB|
|scrambled108663.smt2                                                                       |1200.051s |206.0MiB|
|scrambled119582.smt2                                                                       |1200.070s |200.0MiB|
|scrambled62032.smt2                                                                        |1200.084s |199.0MiB|
|scrambled36790.smt2                                                                        |1200.065s |198.0MiB|
|scrambled79354.smt2                                                                        |1200.062s |194.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.012s  |1200.012s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        | 599.089s  | 599.089s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   8.337s  |   8.337s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  51.795s  |  51.795s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 307.802s  | 307.802s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |   5.217s  |   5.217s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  42.322s  |  42.322s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   5.241s  |   5.241s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 672.668s  | 672.668s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.029s  |1200.029s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   6.811s  |   6.811s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   1.211s  |   1.211s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 272.631s  | 272.631s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.084s  |1200.084s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         |1200.189s  |1200.189s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   8.648s  |   8.648s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1200.554s  |1200.554s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |  32.427s  |  32.427s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.029s  |1200.029s  |   0.000s  | 0.0%|
</details>
