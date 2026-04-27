# .

* SAT 4
* UNSAT 11
* TIMEOUT 29
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-v2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 8184b34a0dabc65c893123172b120d0a65a3fd28
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.failed_literal_backbones=false smt_parallel.num_global_bb_chunking_threads=0"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: add continuous checking for new batch after first pass + continous loop behavior in the chunking algorithm

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|scrambled50258.smt2                                          |    0.925s | 222.0MiB| unsat | 0 |  |  |
|scrambled30073.smt2                                          |    4.409s | 274.0MiB| unsat | 0 |  |  |
|scrambled48569.smt2                                          |    4.872s | 1140.0MiB| sat | 0 |  |  |
|scrambled9548.smt2                                           |    5.376s | 243.0MiB| unsat | 0 |  |  |
|scrambled82407.smt2                                          |    5.955s | 237.0MiB| unsat | 0 |  |  |
|scrambled129467.smt2                                         |   10.342s | 370.0MiB| unsat | 0 |  |  |
|scrambled12959.smt2                                          |   15.619s | 364.0MiB| unsat | 0 |  |  |
|scrambled29780.smt2                                          |   27.163s | 243.0MiB| unsat | 0 |  |  |
|scrambled17293.smt2                                          |   43.098s | 972.0MiB| sat | 0 |  |  |
|scrambled103775.smt2                                         |   67.297s | 327.0MiB| unsat | 0 |  |  |
|scrambled31071.smt2                                          |  139.861s | 564.0MiB| sat | 0 |  |  |
|scrambled61060.smt2                                          |  141.722s | 1314.0MiB| unsat | 0 |  |  |
|scrambled28176.smt2                                          |  168.987s | 1043.0MiB| sat | 0 |  |  |
|scrambled80288.smt2                                          |  313.209s | 786.0MiB| unsat | 0 |  |  |
|scrambled14845.smt2                                          |  718.822s | 5514.0MiB| unsat | 0 |  |  |
|scrambled35280.smt2                                          | 1200.115s | 767.0MiB| timeout | 0 |  |  |
|scrambled41135.smt2                                          | 1200.120s | 1323.0MiB| timeout | 0 |  |  |
|scrambled31575.smt2                                          | 1200.127s | 570.0MiB| timeout | 0 |  |  |
|scrambled101716.smt2                                         | 1200.146s | 1219.0MiB| timeout | 0 |  |  |
|scrambled8852.smt2                                           | 1200.147s | 1150.0MiB| timeout | 0 |  |  |
|scrambled98111.smt2                                          | 1200.152s | 949.0MiB| timeout | 0 |  |  |
|scrambled100714.smt2                                         | 1200.172s | 1113.0MiB| timeout | 0 |  |  |
|scrambled119582.smt2                                         | 1200.176s | 1266.0MiB| timeout | 0 |  |  |
|scrambled58311.smt2                                          | 1200.179s | 1763.0MiB| timeout | 0 |  |  |
|scrambled39467.smt2                                          | 1200.196s | 1666.0MiB| timeout | 0 |  |  |
|scrambled79354.smt2                                          | 1200.208s | 1309.0MiB| timeout | 0 |  |  |
|scrambled38587.smt2                                          | 1200.209s | 1183.0MiB| timeout | 0 |  |  |
|scrambled9883.smt2                                           | 1200.234s | 1459.0MiB| timeout | 0 |  |  |
|scrambled36790.smt2                                          | 1200.244s | 1456.0MiB| timeout | 0 |  |  |
|scrambled96401.smt2                                          | 1200.256s | 1508.0MiB| timeout | 0 |  |  |
|scrambled73281.smt2                                          | 1200.260s | 1425.0MiB| timeout | 0 |  |  |
|scrambled87588.smt2                                          | 1200.265s | 1833.0MiB| timeout | 0 |  |  |
|scrambled97386.smt2                                          | 1200.270s | 1372.0MiB| timeout | 0 |  |  |
|scrambled47700.smt2                                          | 1200.282s | 2605.0MiB| timeout | 0 |  |  |
|scrambled130111.smt2                                         | 1200.308s | 1833.0MiB| timeout | 0 |  |  |
|scrambled12033.smt2                                          | 1200.331s | 2345.0MiB| timeout | 0 |  |  |
|scrambled122926.smt2                                         | 1200.407s | 2896.0MiB| timeout | 0 |  |  |
|scrambled91750.smt2                                          | 1200.416s | 2054.0MiB| timeout | 0 |  |  |
|scrambled108663.smt2                                         | 1200.456s | 4506.0MiB| timeout | 0 |  |  |
|scrambled82760.smt2                                          | 1200.503s | 3975.0MiB| timeout | 0 |  |  |
|scrambled108406.smt2                                         | 1200.574s | 4415.0MiB| timeout | 0 |  |  |
|scrambled73755.smt2                                          | 1200.671s | 4312.0MiB| timeout | 0 |  |  |
|scrambled62032.smt2                                          | 1202.111s | 21.15GiB| timeout | 0 |  |  |
|scrambled85357.smt2                                          | 1202.750s | 24.429GiB| timeout | 0 |  |  |
