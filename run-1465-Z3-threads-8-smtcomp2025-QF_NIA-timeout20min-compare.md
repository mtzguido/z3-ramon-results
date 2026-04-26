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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: d41610a46ca6d0169bdc562311fed3fd69e2b769
Z3 branch: d41610a46ca6d0169bdc562311fed3fd69e2b769
Z3 options: "-T:60 -v:0 smt.threads=8"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: reinstate FL check for new batch with epochs, before merge, this is a temp branch

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: d41610a46ca6d0169bdc562311fed3fd69e2b769
Z3 branch: d41610a46ca6d0169bdc562311fed3fd69e2b769
Z3 options: "-T:60 -v:0 smt.threads=8"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: reinstate FL check for new batch with epochs, before merge, this is a temp branch

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |  60.047s  |  60.047s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |  60.060s  |  60.060s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |  60.063s  |  60.063s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |  60.073s  |  60.073s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |  60.071s  |  60.071s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |  60.245s  |  60.245s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |  60.091s  |  60.091s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  60.092s  |  60.092s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  60.068s  |  60.068s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |  60.100s  |  60.100s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |  60.565s  |  60.565s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  60.134s  |  60.134s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  60.102s  |  60.102s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  60.050s  |  60.050s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   1.198s  |   1.198s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  60.073s  |  60.073s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |  60.046s  |  60.046s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |  60.081s  |  60.081s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |  60.084s  |  60.084s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |  60.047s  |  60.047s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |  60.060s  |  60.060s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |  60.063s  |  60.063s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |  60.073s  |  60.073s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |  60.071s  |  60.071s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |  60.245s  |  60.245s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |  60.091s  |  60.091s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  60.092s  |  60.092s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  60.068s  |  60.068s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |  60.100s  |  60.100s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |  60.565s  |  60.565s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  60.134s  |  60.134s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  60.102s  |  60.102s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  60.050s  |  60.050s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   1.198s  |   1.198s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  60.073s  |  60.073s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |  60.046s  |  60.046s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |  60.081s  |  60.081s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |  60.084s  |  60.084s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |  60.047s  |  60.047s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |  60.060s  |  60.060s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |  60.063s  |  60.063s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |  60.073s  |  60.073s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |  60.071s  |  60.071s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |  60.245s  |  60.245s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |  60.091s  |  60.091s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  60.092s  |  60.092s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  60.068s  |  60.068s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |  60.100s  |  60.100s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |  60.565s  |  60.565s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  60.134s  |  60.134s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  60.102s  |  60.102s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  60.050s  |  60.050s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   1.198s  |   1.198s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  60.073s  |  60.073s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |  60.046s  |  60.046s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |  60.081s  |  60.081s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |  60.084s  |  60.084s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |  60.047s  |  60.047s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |  60.060s  |  60.060s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |  60.063s  |  60.063s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |  60.073s  |  60.073s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |  60.071s  |  60.071s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |  60.245s  |  60.245s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |  60.091s  |  60.091s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  60.092s  |  60.092s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  60.068s  |  60.068s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |  60.100s  |  60.100s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |  60.565s  |  60.565s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  60.134s  |  60.134s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  60.102s  |  60.102s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  60.050s  |  60.050s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   1.198s  |   1.198s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  60.073s  |  60.073s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |  60.046s  |  60.046s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |  60.081s  |  60.081s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |  60.084s  |  60.084s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |  61.118s |9573.0MiB|
|scrambled14845.smt2                                                                        |  60.565s |4941.0MiB|
|scrambled73755.smt2                                                                        |  60.503s |3304.0MiB|
|scrambled12033.smt2                                                                        |  60.245s |2064.0MiB|
|scrambled48569.smt2                                                                        |  60.189s |1049.0MiB|
|scrambled17293.smt2                                                                        |  60.134s |803.0MiB|
|scrambled91750.smt2                                                                        |  60.122s |568.0MiB|
|scrambled61060.smt2                                                                        |  60.108s |758.0MiB|
|scrambled28176.smt2                                                                        |  60.102s |428.0MiB|
|scrambled130111.smt2                                                                       |  60.100s |597.0MiB|
|scrambled129467.smt2                                                                       |  60.092s |431.0MiB|
|scrambled122926.smt2                                                                       |  60.091s |678.0MiB|
|scrambled36790.smt2                                                                        |  60.084s |522.0MiB|
|scrambled97386.smt2                                                                        |  60.083s |540.0MiB|
|scrambled35280.smt2                                                                        |  60.081s |426.0MiB|
|scrambled96401.smt2                                                                        |  60.078s |486.0MiB|
|scrambled82760.smt2                                                                        |  60.075s |312.0MiB|
|scrambled9883.smt2                                                                         |  60.074s |314.0MiB|
|scrambled31071.smt2                                                                        |  60.073s |422.0MiB|
|scrambled108663.smt2                                                                       |  60.073s |314.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |  61.118s |9573.0MiB|
|scrambled14845.smt2                                                                        |  60.565s |4941.0MiB|
|scrambled73755.smt2                                                                        |  60.503s |3304.0MiB|
|scrambled12033.smt2                                                                        |  60.245s |2064.0MiB|
|scrambled48569.smt2                                                                        |  60.189s |1049.0MiB|
|scrambled17293.smt2                                                                        |  60.134s |803.0MiB|
|scrambled91750.smt2                                                                        |  60.122s |568.0MiB|
|scrambled61060.smt2                                                                        |  60.108s |758.0MiB|
|scrambled28176.smt2                                                                        |  60.102s |428.0MiB|
|scrambled130111.smt2                                                                       |  60.100s |597.0MiB|
|scrambled129467.smt2                                                                       |  60.092s |431.0MiB|
|scrambled122926.smt2                                                                       |  60.091s |678.0MiB|
|scrambled36790.smt2                                                                        |  60.084s |522.0MiB|
|scrambled97386.smt2                                                                        |  60.083s |540.0MiB|
|scrambled35280.smt2                                                                        |  60.081s |426.0MiB|
|scrambled96401.smt2                                                                        |  60.078s |486.0MiB|
|scrambled82760.smt2                                                                        |  60.075s |312.0MiB|
|scrambled9883.smt2                                                                         |  60.074s |314.0MiB|
|scrambled31071.smt2                                                                        |  60.073s |422.0MiB|
|scrambled108663.smt2                                                                       |  60.073s |314.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |321.0MiB|321.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |357.0MiB|357.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |314.0MiB|314.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |337.0MiB|337.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2064.0MiB|2064.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |678.0MiB|678.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |431.0MiB|431.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |322.0MiB|322.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |597.0MiB|597.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |4941.0MiB|4941.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |803.0MiB|803.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |428.0MiB|428.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |272.0MiB|272.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |222.0MiB|222.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |422.0MiB|422.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |248.0MiB|248.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |426.0MiB|426.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |522.0MiB|522.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |321.0MiB|321.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |357.0MiB|357.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |314.0MiB|314.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |337.0MiB|337.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2064.0MiB|2064.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |678.0MiB|678.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |431.0MiB|431.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |322.0MiB|322.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |597.0MiB|597.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |4941.0MiB|4941.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |803.0MiB|803.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |428.0MiB|428.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |272.0MiB|272.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |222.0MiB|222.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |422.0MiB|422.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |248.0MiB|248.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |426.0MiB|426.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |522.0MiB|522.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |321.0MiB|321.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |357.0MiB|357.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |314.0MiB|314.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |337.0MiB|337.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2064.0MiB|2064.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |678.0MiB|678.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |431.0MiB|431.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |322.0MiB|322.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |597.0MiB|597.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |4941.0MiB|4941.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |803.0MiB|803.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |428.0MiB|428.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |272.0MiB|272.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |222.0MiB|222.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |422.0MiB|422.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |248.0MiB|248.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |426.0MiB|426.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |522.0MiB|522.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |321.0MiB|321.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |357.0MiB|357.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |314.0MiB|314.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |337.0MiB|337.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2064.0MiB|2064.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |678.0MiB|678.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |431.0MiB|431.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |322.0MiB|322.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |597.0MiB|597.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |4941.0MiB|4941.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |803.0MiB|803.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |428.0MiB|428.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |272.0MiB|272.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |222.0MiB|222.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |422.0MiB|422.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |248.0MiB|248.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |426.0MiB|426.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |522.0MiB|522.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |  61.118s |9573.0MiB|
|scrambled14845.smt2                                                                        |  60.565s |4941.0MiB|
|scrambled73755.smt2                                                                        |  60.503s |3304.0MiB|
|scrambled12033.smt2                                                                        |  60.245s |2064.0MiB|
|scrambled48569.smt2                                                                        |  60.189s |1049.0MiB|
|scrambled17293.smt2                                                                        |  60.134s |803.0MiB|
|scrambled61060.smt2                                                                        |  60.108s |758.0MiB|
|scrambled122926.smt2                                                                       |  60.091s |678.0MiB|
|scrambled130111.smt2                                                                       |  60.100s |597.0MiB|
|scrambled91750.smt2                                                                        |  60.122s |568.0MiB|
|scrambled97386.smt2                                                                        |  60.083s |540.0MiB|
|scrambled36790.smt2                                                                        |  60.084s |522.0MiB|
|scrambled96401.smt2                                                                        |  60.078s |486.0MiB|
|scrambled129467.smt2                                                                       |  60.092s |431.0MiB|
|scrambled28176.smt2                                                                        |  60.102s |428.0MiB|
|scrambled35280.smt2                                                                        |  60.081s |426.0MiB|
|scrambled31071.smt2                                                                        |  60.073s |422.0MiB|
|scrambled41135.smt2                                                                        |  60.061s |381.0MiB|
|scrambled108406.smt2                                                                       |  60.063s |357.0MiB|
|scrambled9548.smt2                                                                         |  10.212s |347.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |  61.118s |9573.0MiB|
|scrambled14845.smt2                                                                        |  60.565s |4941.0MiB|
|scrambled73755.smt2                                                                        |  60.503s |3304.0MiB|
|scrambled12033.smt2                                                                        |  60.245s |2064.0MiB|
|scrambled48569.smt2                                                                        |  60.189s |1049.0MiB|
|scrambled17293.smt2                                                                        |  60.134s |803.0MiB|
|scrambled61060.smt2                                                                        |  60.108s |758.0MiB|
|scrambled122926.smt2                                                                       |  60.091s |678.0MiB|
|scrambled130111.smt2                                                                       |  60.100s |597.0MiB|
|scrambled91750.smt2                                                                        |  60.122s |568.0MiB|
|scrambled97386.smt2                                                                        |  60.083s |540.0MiB|
|scrambled36790.smt2                                                                        |  60.084s |522.0MiB|
|scrambled96401.smt2                                                                        |  60.078s |486.0MiB|
|scrambled129467.smt2                                                                       |  60.092s |431.0MiB|
|scrambled28176.smt2                                                                        |  60.102s |428.0MiB|
|scrambled35280.smt2                                                                        |  60.081s |426.0MiB|
|scrambled31071.smt2                                                                        |  60.073s |422.0MiB|
|scrambled41135.smt2                                                                        |  60.061s |381.0MiB|
|scrambled108406.smt2                                                                       |  60.063s |357.0MiB|
|scrambled9548.smt2                                                                         |  10.212s |347.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |  60.047s  |  60.047s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |  60.060s  |  60.060s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |  60.063s  |  60.063s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |  60.073s  |  60.073s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |  60.071s  |  60.071s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |  60.245s  |  60.245s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |  60.091s  |  60.091s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  60.092s  |  60.092s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  60.068s  |  60.068s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |  60.100s  |  60.100s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         |  60.565s  |  60.565s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  60.134s  |  60.134s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  60.102s  |  60.102s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  60.050s  |  60.050s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   1.198s  |   1.198s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  60.073s  |  60.073s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |  60.046s  |  60.046s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |  60.081s  |  60.081s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |  60.084s  |  60.084s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |  60.071s  |  60.071s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |  60.047s  |  60.047s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |  60.061s  |  60.061s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |  60.067s  |  60.067s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |  60.189s  |  60.189s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   1.727s  |   1.727s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |  60.044s  |  60.044s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         |  60.108s  |  60.108s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |  60.072s  |  60.072s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |  60.057s  |  60.057s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |  60.503s  |  60.503s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |  60.070s  |  60.070s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         |  60.063s  |  60.063s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   8.971s  |   8.971s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |  60.075s  |  60.075s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |  61.118s  |  61.118s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |  60.063s  |  60.063s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |  60.070s  |  60.070s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |  60.122s  |  60.122s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |  10.212s  |  10.212s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |  60.078s  |  60.078s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |  60.083s  |  60.083s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |  60.047s  |  60.047s  |   0.000s  | 0.0%|
</details>
