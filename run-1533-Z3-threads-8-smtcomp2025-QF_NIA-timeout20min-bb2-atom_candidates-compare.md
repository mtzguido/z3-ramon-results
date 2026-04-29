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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-atom_candidates
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: cea3155f42fe2ffe6f9a934176262a783e8fcf11
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: bb candidates are atoms, not literals, since we currently test both polarities in parallel.
batch mode retry terminates if we made zero progress after a retry round to avoid resource stress
fix bug about bb ranking being backwards for how we process them

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-atom_candidates
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: cea3155f42fe2ffe6f9a934176262a783e8fcf11
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: bb candidates are atoms, not literals, since we currently test both polarities in parallel.
batch mode retry terminates if we made zero progress after a retry round to avoid resource stress
fix bug about bb ranking being backwards for how we process them

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.201s  |1200.201s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  47.536s  |  47.536s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.348s  |1200.348s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.412s  |1200.412s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.220s  |1200.220s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.335s  |1200.335s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.392s  |1200.392s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.462s  |  10.462s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  17.397s  |  17.397s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.258s  |1200.258s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 586.488s  | 586.488s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.492s  |  14.492s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   3.593s  |   3.593s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.016s  |  21.016s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.531s  |   4.531s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  48.727s  |  48.727s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.119s  |1200.119s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.219s  |1200.219s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.201s  |1200.201s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  47.536s  |  47.536s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.348s  |1200.348s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.412s  |1200.412s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.220s  |1200.220s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.335s  |1200.335s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.392s  |1200.392s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.462s  |  10.462s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  17.397s  |  17.397s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.258s  |1200.258s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 586.488s  | 586.488s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.492s  |  14.492s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   3.593s  |   3.593s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.016s  |  21.016s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.531s  |   4.531s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  48.727s  |  48.727s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.119s  |1200.119s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.219s  |1200.219s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.201s  |1200.201s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  47.536s  |  47.536s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.348s  |1200.348s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.412s  |1200.412s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.220s  |1200.220s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.335s  |1200.335s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.392s  |1200.392s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.462s  |  10.462s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  17.397s  |  17.397s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.258s  |1200.258s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 586.488s  | 586.488s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.492s  |  14.492s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   3.593s  |   3.593s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.016s  |  21.016s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.531s  |   4.531s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  48.727s  |  48.727s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.119s  |1200.119s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.219s  |1200.219s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.201s  |1200.201s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  47.536s  |  47.536s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.348s  |1200.348s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.412s  |1200.412s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.220s  |1200.220s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.335s  |1200.335s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.392s  |1200.392s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.462s  |  10.462s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  17.397s  |  17.397s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.258s  |1200.258s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 586.488s  | 586.488s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.492s  |  14.492s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   3.593s  |   3.593s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.016s  |  21.016s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.531s  |   4.531s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  48.727s  |  48.727s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.119s  |1200.119s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.219s  |1200.219s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.730s |30.857GiB|
|scrambled47700.smt2                                                                        |1200.746s |7385.0MiB|
|scrambled73755.smt2                                                                        |1200.598s |5246.0MiB|
|scrambled91750.smt2                                                                        |1200.458s |2579.0MiB|
|scrambled108663.smt2                                                                       |1200.412s |3325.0MiB|
|scrambled87588.smt2                                                                        |1200.394s |3392.0MiB|
|scrambled122926.smt2                                                                       |1200.392s |3836.0MiB|
|scrambled108406.smt2                                                                       |1200.348s |2968.0MiB|
|scrambled97386.smt2                                                                        |1200.343s |1667.0MiB|
|scrambled12033.smt2                                                                        |1200.335s |2949.0MiB|
|scrambled79354.smt2                                                                        |1200.325s |1735.0MiB|
|scrambled62032.smt2                                                                        |1200.294s |1565.0MiB|
|scrambled39467.smt2                                                                        |1200.284s |2772.0MiB|
|scrambled82760.smt2                                                                        |1200.280s |2086.0MiB|
|scrambled130111.smt2                                                                       |1200.258s |1885.0MiB|
|scrambled9883.smt2                                                                         |1200.239s |1468.0MiB|
|scrambled98111.smt2                                                                        |1200.234s |1560.0MiB|
|scrambled58311.smt2                                                                        |1200.227s |949.0MiB|
|scrambled119582.smt2                                                                       |1200.220s |1413.0MiB|
|scrambled36790.smt2                                                                        |1200.219s |1746.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.730s |30.857GiB|
|scrambled47700.smt2                                                                        |1200.746s |7385.0MiB|
|scrambled73755.smt2                                                                        |1200.598s |5246.0MiB|
|scrambled91750.smt2                                                                        |1200.458s |2579.0MiB|
|scrambled108663.smt2                                                                       |1200.412s |3325.0MiB|
|scrambled87588.smt2                                                                        |1200.394s |3392.0MiB|
|scrambled122926.smt2                                                                       |1200.392s |3836.0MiB|
|scrambled108406.smt2                                                                       |1200.348s |2968.0MiB|
|scrambled97386.smt2                                                                        |1200.343s |1667.0MiB|
|scrambled12033.smt2                                                                        |1200.335s |2949.0MiB|
|scrambled79354.smt2                                                                        |1200.325s |1735.0MiB|
|scrambled62032.smt2                                                                        |1200.294s |1565.0MiB|
|scrambled39467.smt2                                                                        |1200.284s |2772.0MiB|
|scrambled82760.smt2                                                                        |1200.280s |2086.0MiB|
|scrambled130111.smt2                                                                       |1200.258s |1885.0MiB|
|scrambled9883.smt2                                                                         |1200.239s |1468.0MiB|
|scrambled98111.smt2                                                                        |1200.234s |1560.0MiB|
|scrambled58311.smt2                                                                        |1200.227s |949.0MiB|
|scrambled119582.smt2                                                                       |1200.220s |1413.0MiB|
|scrambled36790.smt2                                                                        |1200.219s |1746.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1206.0MiB|1206.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1414.0MiB|1414.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |413.0MiB|413.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2968.0MiB|2968.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3325.0MiB|3325.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1413.0MiB|1413.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2949.0MiB|2949.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3836.0MiB|3836.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |442.0MiB|442.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |358.0MiB|358.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1885.0MiB|1885.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6627.0MiB|6627.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1063.0MiB|1063.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |404.0MiB|404.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |283.0MiB|283.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |275.0MiB|275.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |537.0MiB|537.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1144.0MiB|1144.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1746.0MiB|1746.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1206.0MiB|1206.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1414.0MiB|1414.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |413.0MiB|413.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2968.0MiB|2968.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3325.0MiB|3325.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1413.0MiB|1413.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2949.0MiB|2949.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3836.0MiB|3836.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |442.0MiB|442.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |358.0MiB|358.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1885.0MiB|1885.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6627.0MiB|6627.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1063.0MiB|1063.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |404.0MiB|404.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |283.0MiB|283.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |275.0MiB|275.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |537.0MiB|537.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1144.0MiB|1144.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1746.0MiB|1746.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1206.0MiB|1206.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1414.0MiB|1414.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |413.0MiB|413.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2968.0MiB|2968.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3325.0MiB|3325.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1413.0MiB|1413.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2949.0MiB|2949.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3836.0MiB|3836.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |442.0MiB|442.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |358.0MiB|358.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1885.0MiB|1885.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6627.0MiB|6627.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1063.0MiB|1063.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |404.0MiB|404.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |283.0MiB|283.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |275.0MiB|275.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |537.0MiB|537.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1144.0MiB|1144.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1746.0MiB|1746.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1206.0MiB|1206.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1414.0MiB|1414.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |413.0MiB|413.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |2968.0MiB|2968.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3325.0MiB|3325.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1413.0MiB|1413.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2949.0MiB|2949.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3836.0MiB|3836.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |442.0MiB|442.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |358.0MiB|358.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |1885.0MiB|1885.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6627.0MiB|6627.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1063.0MiB|1063.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |404.0MiB|404.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |283.0MiB|283.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |275.0MiB|275.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |537.0MiB|537.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1144.0MiB|1144.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1746.0MiB|1746.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.730s |30.857GiB|
|scrambled47700.smt2                                                                        |1200.746s |7385.0MiB|
|scrambled14845.smt2                                                                        | 586.488s |6627.0MiB|
|scrambled73755.smt2                                                                        |1200.598s |5246.0MiB|
|scrambled122926.smt2                                                                       |1200.392s |3836.0MiB|
|scrambled87588.smt2                                                                        |1200.394s |3392.0MiB|
|scrambled108663.smt2                                                                       |1200.412s |3325.0MiB|
|scrambled108406.smt2                                                                       |1200.348s |2968.0MiB|
|scrambled12033.smt2                                                                        |1200.335s |2949.0MiB|
|scrambled39467.smt2                                                                        |1200.284s |2772.0MiB|
|scrambled91750.smt2                                                                        |1200.458s |2579.0MiB|
|scrambled82760.smt2                                                                        |1200.280s |2086.0MiB|
|scrambled130111.smt2                                                                       |1200.258s |1885.0MiB|
|scrambled8852.smt2                                                                         |1200.201s |1807.0MiB|
|scrambled36790.smt2                                                                        |1200.219s |1746.0MiB|
|scrambled79354.smt2                                                                        |1200.325s |1735.0MiB|
|scrambled38587.smt2                                                                        |1200.207s |1716.0MiB|
|scrambled73281.smt2                                                                        |1200.213s |1693.0MiB|
|scrambled97386.smt2                                                                        |1200.343s |1667.0MiB|
|scrambled61060.smt2                                                                        | 199.652s |1664.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.730s |30.857GiB|
|scrambled47700.smt2                                                                        |1200.746s |7385.0MiB|
|scrambled14845.smt2                                                                        | 586.488s |6627.0MiB|
|scrambled73755.smt2                                                                        |1200.598s |5246.0MiB|
|scrambled122926.smt2                                                                       |1200.392s |3836.0MiB|
|scrambled87588.smt2                                                                        |1200.394s |3392.0MiB|
|scrambled108663.smt2                                                                       |1200.412s |3325.0MiB|
|scrambled108406.smt2                                                                       |1200.348s |2968.0MiB|
|scrambled12033.smt2                                                                        |1200.335s |2949.0MiB|
|scrambled39467.smt2                                                                        |1200.284s |2772.0MiB|
|scrambled91750.smt2                                                                        |1200.458s |2579.0MiB|
|scrambled82760.smt2                                                                        |1200.280s |2086.0MiB|
|scrambled130111.smt2                                                                       |1200.258s |1885.0MiB|
|scrambled8852.smt2                                                                         |1200.201s |1807.0MiB|
|scrambled36790.smt2                                                                        |1200.219s |1746.0MiB|
|scrambled79354.smt2                                                                        |1200.325s |1735.0MiB|
|scrambled38587.smt2                                                                        |1200.207s |1716.0MiB|
|scrambled73281.smt2                                                                        |1200.213s |1693.0MiB|
|scrambled97386.smt2                                                                        |1200.343s |1667.0MiB|
|scrambled61060.smt2                                                                        | 199.652s |1664.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.201s  |1200.201s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  47.536s  |  47.536s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.348s  |1200.348s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.412s  |1200.412s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.220s  |1200.220s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.335s  |1200.335s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.392s  |1200.392s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |  10.462s  |  10.462s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  17.397s  |  17.397s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.258s  |1200.258s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 586.488s  | 586.488s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  14.492s  |  14.492s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |   3.593s  |   3.593s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  21.016s  |  21.016s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   4.531s  |   4.531s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |  48.727s  |  48.727s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.119s  |1200.119s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.207s  |1200.207s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.284s  |1200.284s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.152s  |1200.152s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.746s  |1200.746s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   5.942s  |   5.942s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.957s  |   0.957s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.227s  |1200.227s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 199.652s  | 199.652s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.294s  |1200.294s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.213s  |1200.213s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.598s  |1200.598s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.325s  |1200.325s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 285.495s  | 285.495s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   6.034s  |   6.034s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.280s  |1200.280s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1202.730s  |1202.730s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1200.394s  |1200.394s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.201s  |1200.201s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.458s  |1200.458s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   4.203s  |   4.203s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1198.415s  |1198.415s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.343s  |1200.343s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.234s  |1200.234s  |   0.000s  | 0.0%|
</details>
