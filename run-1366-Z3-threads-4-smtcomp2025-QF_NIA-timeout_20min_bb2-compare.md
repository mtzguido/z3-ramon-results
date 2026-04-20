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
Job tag: Z3-threads-4-smtcomp2025-QF_NIA-timeout_20min_bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6b8cb1099d311aac105cfc6fa658466f4ef6af67
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore unrelated code to master

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-smtcomp2025-QF_NIA-timeout_20min_bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6b8cb1099d311aac105cfc6fa658466f4ef6af67
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: restore unrelated code to master

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1260.122s  |1260.122s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1260.095s  |1260.095s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        | 141.347s  | 141.347s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1260.918s  |1260.918s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1260.439s  |1260.439s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1260.121s  |1260.121s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1260.208s  |1260.208s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1260.239s  |1260.239s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.053s  |  12.053s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  19.679s  |  19.679s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1260.347s  |1260.347s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 719.274s  | 719.274s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  22.023s  |  22.023s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 346.287s  | 346.287s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  39.354s  |  39.354s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   5.000s  |   5.000s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 444.917s  | 444.917s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1260.090s  |1260.090s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1260.175s  |1260.175s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1260.122s  |1260.122s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1260.095s  |1260.095s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        | 141.347s  | 141.347s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1260.918s  |1260.918s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1260.439s  |1260.439s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1260.121s  |1260.121s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1260.208s  |1260.208s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1260.239s  |1260.239s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.053s  |  12.053s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  19.679s  |  19.679s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1260.347s  |1260.347s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 719.274s  | 719.274s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  22.023s  |  22.023s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 346.287s  | 346.287s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  39.354s  |  39.354s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   5.000s  |   5.000s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 444.917s  | 444.917s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1260.090s  |1260.090s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1260.175s  |1260.175s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1260.122s  |1260.122s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1260.095s  |1260.095s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        | 141.347s  | 141.347s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1260.918s  |1260.918s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1260.439s  |1260.439s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1260.121s  |1260.121s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1260.208s  |1260.208s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1260.239s  |1260.239s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.053s  |  12.053s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  19.679s  |  19.679s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1260.347s  |1260.347s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 719.274s  | 719.274s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  22.023s  |  22.023s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 346.287s  | 346.287s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  39.354s  |  39.354s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   5.000s  |   5.000s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 444.917s  | 444.917s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1260.090s  |1260.090s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1260.175s  |1260.175s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1260.122s  |1260.122s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1260.095s  |1260.095s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        | 141.347s  | 141.347s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1260.918s  |1260.918s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1260.439s  |1260.439s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1260.121s  |1260.121s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1260.208s  |1260.208s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1260.239s  |1260.239s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.053s  |  12.053s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  19.679s  |  19.679s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1260.347s  |1260.347s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 719.274s  | 719.274s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  22.023s  |  22.023s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 346.287s  | 346.287s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  39.354s  |  39.354s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   5.000s  |   5.000s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 444.917s  | 444.917s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1260.090s  |1260.090s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1260.175s  |1260.175s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1261.777s |18.459GiB|
|scrambled108406.smt2                                                                       |1260.918s |4998.0MiB|
|scrambled82760.smt2                                                                        |1260.546s |4638.0MiB|
|scrambled108663.smt2                                                                       |1260.439s |3128.0MiB|
|scrambled130111.smt2                                                                       |1260.347s |1737.0MiB|
|scrambled39467.smt2                                                                        |1260.315s |2286.0MiB|
|scrambled73755.smt2                                                                        |1260.306s |2159.0MiB|
|scrambled91750.smt2                                                                        |1260.252s |1614.0MiB|
|scrambled122926.smt2                                                                       |1260.239s |2326.0MiB|
|scrambled47700.smt2                                                                        |1260.237s |1791.0MiB|
|scrambled12033.smt2                                                                        |1260.208s |1683.0MiB|
|scrambled97386.smt2                                                                        |1260.198s |1155.0MiB|
|scrambled58311.smt2                                                                        |1260.196s |1420.0MiB|
|scrambled62032.smt2                                                                        |1260.180s |1324.0MiB|
|scrambled36790.smt2                                                                        |1260.175s |1769.0MiB|
|scrambled79354.smt2                                                                        |1260.166s |881.0MiB|
|scrambled41135.smt2                                                                        |1260.159s |1013.0MiB|
|scrambled87588.smt2                                                                        |1260.139s |1033.0MiB|
|scrambled38587.smt2                                                                        |1260.134s |954.0MiB|
|scrambled100714.smt2                                                                       |1260.122s |787.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1261.777s |18.459GiB|
|scrambled108406.smt2                                                                       |1260.918s |4998.0MiB|
|scrambled82760.smt2                                                                        |1260.546s |4638.0MiB|
|scrambled108663.smt2                                                                       |1260.439s |3128.0MiB|
|scrambled130111.smt2                                                                       |1260.347s |1737.0MiB|
|scrambled39467.smt2                                                                        |1260.315s |2286.0MiB|
|scrambled73755.smt2                                                                        |1260.306s |2159.0MiB|
|scrambled91750.smt2                                                                        |1260.252s |1614.0MiB|
|scrambled122926.smt2                                                                       |1260.239s |2326.0MiB|
|scrambled47700.smt2                                                                        |1260.237s |1791.0MiB|
|scrambled12033.smt2                                                                        |1260.208s |1683.0MiB|
|scrambled97386.smt2                                                                        |1260.198s |1155.0MiB|
|scrambled58311.smt2                                                                        |1260.196s |1420.0MiB|
|scrambled62032.smt2                                                                        |1260.180s |1324.0MiB|
|scrambled36790.smt2                                                                        |1260.175s |1769.0MiB|
|scrambled79354.smt2                                                                        |1260.166s |881.0MiB|
|scrambled41135.smt2                                                                        |1260.159s |1013.0MiB|
|scrambled87588.smt2                                                                        |1260.139s |1033.0MiB|
|scrambled38587.smt2                                                                        |1260.134s |954.0MiB|
|scrambled100714.smt2                                                                       |1260.122s |787.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |787.0MiB|787.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |856.0MiB|856.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |270.0MiB|270.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |4998.0MiB|4998.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3128.0MiB|3128.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |812.0MiB|812.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |1683.0MiB|1683.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |2326.0MiB|2326.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |256.0MiB|256.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1737.0MiB|1737.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |4362.0MiB|4362.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |647.0MiB|647.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |899.0MiB|899.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |225.0MiB|225.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |206.0MiB|206.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |690.0MiB|690.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |127.0MiB|127.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |592.0MiB|592.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1769.0MiB|1769.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |787.0MiB|787.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |856.0MiB|856.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |270.0MiB|270.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |4998.0MiB|4998.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3128.0MiB|3128.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |812.0MiB|812.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |1683.0MiB|1683.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |2326.0MiB|2326.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |256.0MiB|256.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1737.0MiB|1737.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |4362.0MiB|4362.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |647.0MiB|647.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |899.0MiB|899.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |225.0MiB|225.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |206.0MiB|206.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |690.0MiB|690.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |127.0MiB|127.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |592.0MiB|592.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1769.0MiB|1769.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |787.0MiB|787.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |856.0MiB|856.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |270.0MiB|270.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |4998.0MiB|4998.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3128.0MiB|3128.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |812.0MiB|812.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |1683.0MiB|1683.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |2326.0MiB|2326.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |256.0MiB|256.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1737.0MiB|1737.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |4362.0MiB|4362.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |647.0MiB|647.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |899.0MiB|899.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |225.0MiB|225.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |206.0MiB|206.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |690.0MiB|690.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |127.0MiB|127.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |592.0MiB|592.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1769.0MiB|1769.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |787.0MiB|787.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |856.0MiB|856.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |270.0MiB|270.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |4998.0MiB|4998.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3128.0MiB|3128.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |812.0MiB|812.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |1683.0MiB|1683.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |2326.0MiB|2326.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |256.0MiB|256.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1737.0MiB|1737.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |4362.0MiB|4362.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |647.0MiB|647.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |899.0MiB|899.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |225.0MiB|225.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |206.0MiB|206.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |690.0MiB|690.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |127.0MiB|127.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |592.0MiB|592.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1769.0MiB|1769.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1261.777s |18.459GiB|
|scrambled108406.smt2                                                                       |1260.918s |4998.0MiB|
|scrambled82760.smt2                                                                        |1260.546s |4638.0MiB|
|scrambled14845.smt2                                                                        | 719.274s |4362.0MiB|
|scrambled108663.smt2                                                                       |1260.439s |3128.0MiB|
|scrambled122926.smt2                                                                       |1260.239s |2326.0MiB|
|scrambled39467.smt2                                                                        |1260.315s |2286.0MiB|
|scrambled73755.smt2                                                                        |1260.306s |2159.0MiB|
|scrambled47700.smt2                                                                        |1260.237s |1791.0MiB|
|scrambled36790.smt2                                                                        |1260.175s |1769.0MiB|
|scrambled130111.smt2                                                                       |1260.347s |1737.0MiB|
|scrambled12033.smt2                                                                        |1260.208s |1683.0MiB|
|scrambled91750.smt2                                                                        |1260.252s |1614.0MiB|
|scrambled58311.smt2                                                                        |1260.196s |1420.0MiB|
|scrambled62032.smt2                                                                        |1260.180s |1324.0MiB|
|scrambled97386.smt2                                                                        |1260.198s |1155.0MiB|
|scrambled98111.smt2                                                                        |1260.122s |1044.0MiB|
|scrambled87588.smt2                                                                        |1260.139s |1033.0MiB|
|scrambled41135.smt2                                                                        |1260.159s |1013.0MiB|
|scrambled73281.smt2                                                                        |1260.119s |982.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1261.777s |18.459GiB|
|scrambled108406.smt2                                                                       |1260.918s |4998.0MiB|
|scrambled82760.smt2                                                                        |1260.546s |4638.0MiB|
|scrambled14845.smt2                                                                        | 719.274s |4362.0MiB|
|scrambled108663.smt2                                                                       |1260.439s |3128.0MiB|
|scrambled122926.smt2                                                                       |1260.239s |2326.0MiB|
|scrambled39467.smt2                                                                        |1260.315s |2286.0MiB|
|scrambled73755.smt2                                                                        |1260.306s |2159.0MiB|
|scrambled47700.smt2                                                                        |1260.237s |1791.0MiB|
|scrambled36790.smt2                                                                        |1260.175s |1769.0MiB|
|scrambled130111.smt2                                                                       |1260.347s |1737.0MiB|
|scrambled12033.smt2                                                                        |1260.208s |1683.0MiB|
|scrambled91750.smt2                                                                        |1260.252s |1614.0MiB|
|scrambled58311.smt2                                                                        |1260.196s |1420.0MiB|
|scrambled62032.smt2                                                                        |1260.180s |1324.0MiB|
|scrambled97386.smt2                                                                        |1260.198s |1155.0MiB|
|scrambled98111.smt2                                                                        |1260.122s |1044.0MiB|
|scrambled87588.smt2                                                                        |1260.139s |1033.0MiB|
|scrambled41135.smt2                                                                        |1260.159s |1013.0MiB|
|scrambled73281.smt2                                                                        |1260.119s |982.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1260.122s  |1260.122s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1260.095s  |1260.095s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        | 141.347s  | 141.347s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1260.918s  |1260.918s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1260.439s  |1260.439s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1260.121s  |1260.121s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1260.208s  |1260.208s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1260.239s  |1260.239s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  12.053s  |  12.053s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  19.679s  |  19.679s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1260.347s  |1260.347s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 719.274s  | 719.274s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  22.023s  |  22.023s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         | 346.287s  | 346.287s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  39.354s  |  39.354s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   5.000s  |   5.000s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         | 444.917s  | 444.917s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1260.090s  |1260.090s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1260.175s  |1260.175s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1260.134s  |1260.134s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1260.315s  |1260.315s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1260.159s  |1260.159s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1260.237s  |1260.237s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   9.115s  |   9.115s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.864s  |   0.864s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1260.196s  |1260.196s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 168.198s  | 168.198s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1260.180s  |1260.180s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1260.119s  |1260.119s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1260.306s  |1260.306s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1260.166s  |1260.166s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 233.020s  | 233.020s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   8.273s  |   8.273s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1260.546s  |1260.546s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1261.777s  |1261.777s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1260.139s  |1260.139s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1260.108s  |1260.108s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1260.252s  |1260.252s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   7.006s  |   7.006s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         | 239.827s  | 239.827s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1260.198s  |1260.198s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1260.122s  |1260.122s  |   0.000s  | 0.0%|
</details>
