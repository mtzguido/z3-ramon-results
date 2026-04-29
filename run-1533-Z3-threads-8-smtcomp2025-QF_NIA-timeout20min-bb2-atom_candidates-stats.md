# .

* SAT 5
* UNSAT 11
* TIMEOUT 28
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

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


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|scrambled50258.smt2                                          |    0.957s | 262.0MiB| unsat | 0 |  |  |
|scrambled28176.smt2                                          |    3.593s | 404.0MiB| sat | 0 |  |  |
|scrambled9548.smt2                                           |    4.203s | 293.0MiB| unsat | 0 |  |  |
|scrambled30073.smt2                                          |    4.531s | 275.0MiB| unsat | 0 |  |  |
|scrambled48569.smt2                                          |    5.942s | 1396.0MiB| sat | 0 |  |  |
|scrambled82407.smt2                                          |    6.034s | 277.0MiB| unsat | 0 |  |  |
|scrambled129467.smt2                                         |   10.462s | 442.0MiB| unsat | 0 |  |  |
|scrambled17293.smt2                                          |   14.492s | 1063.0MiB| sat | 0 |  |  |
|scrambled12959.smt2                                          |   17.397s | 358.0MiB| unsat | 0 |  |  |
|scrambled29780.smt2                                          |   21.016s | 283.0MiB| unsat | 0 |  |  |
|scrambled103775.smt2                                         |   47.536s | 413.0MiB| unsat | 0 |  |  |
|scrambled31071.smt2                                          |   48.727s | 537.0MiB| sat | 0 |  |  |
|scrambled61060.smt2                                          |  199.652s | 1664.0MiB| unsat | 0 |  |  |
|scrambled80288.smt2                                          |  285.495s | 824.0MiB| unsat | 0 |  |  |
|scrambled14845.smt2                                          |  586.488s | 6627.0MiB| unsat | 0 |  |  |
|scrambled96401.smt2                                          | 1198.415s | 1557.0MiB| sat | 0 |  |  |
|scrambled31575.smt2                                          | 1200.119s | 586.0MiB| timeout | 0 |  |  |
|scrambled35280.smt2                                          | 1200.140s | 1144.0MiB| timeout | 0 |  |  |
|scrambled41135.smt2                                          | 1200.152s | 1618.0MiB| timeout | 0 |  |  |
|scrambled101716.smt2                                         | 1200.164s | 1414.0MiB| timeout | 0 |  |  |
|scrambled8852.smt2                                           | 1200.201s | 1807.0MiB| timeout | 0 |  |  |
|scrambled100714.smt2                                         | 1200.201s | 1206.0MiB| timeout | 0 |  |  |
|scrambled38587.smt2                                          | 1200.207s | 1716.0MiB| timeout | 0 |  |  |
|scrambled73281.smt2                                          | 1200.213s | 1693.0MiB| timeout | 0 |  |  |
|scrambled36790.smt2                                          | 1200.219s | 1746.0MiB| timeout | 0 |  |  |
|scrambled119582.smt2                                         | 1200.220s | 1413.0MiB| timeout | 0 |  |  |
|scrambled58311.smt2                                          | 1200.227s | 949.0MiB| timeout | 0 |  |  |
|scrambled98111.smt2                                          | 1200.234s | 1560.0MiB| timeout | 0 |  |  |
|scrambled9883.smt2                                           | 1200.239s | 1468.0MiB| timeout | 0 |  |  |
|scrambled130111.smt2                                         | 1200.258s | 1885.0MiB| timeout | 0 |  |  |
|scrambled82760.smt2                                          | 1200.280s | 2086.0MiB| timeout | 0 |  |  |
|scrambled39467.smt2                                          | 1200.284s | 2772.0MiB| timeout | 0 |  |  |
|scrambled62032.smt2                                          | 1200.294s | 1565.0MiB| timeout | 0 |  |  |
|scrambled79354.smt2                                          | 1200.325s | 1735.0MiB| timeout | 0 |  |  |
|scrambled12033.smt2                                          | 1200.335s | 2949.0MiB| timeout | 0 |  |  |
|scrambled97386.smt2                                          | 1200.343s | 1667.0MiB| timeout | 0 |  |  |
|scrambled108406.smt2                                         | 1200.348s | 2968.0MiB| timeout | 0 |  |  |
|scrambled122926.smt2                                         | 1200.392s | 3836.0MiB| timeout | 0 |  |  |
|scrambled87588.smt2                                          | 1200.394s | 3392.0MiB| timeout | 0 |  |  |
|scrambled108663.smt2                                         | 1200.412s | 3325.0MiB| timeout | 0 |  |  |
|scrambled91750.smt2                                          | 1200.458s | 2579.0MiB| timeout | 0 |  |  |
|scrambled73755.smt2                                          | 1200.598s | 5246.0MiB| timeout | 0 |  |  |
|scrambled47700.smt2                                          | 1200.746s | 7385.0MiB| timeout | 0 |  |  |
|scrambled85357.smt2                                          | 1202.730s | 30.857GiB| timeout | 0 |  |  |
