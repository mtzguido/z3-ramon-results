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
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-bb2-v1
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 8184b34a0dabc65c893123172b120d0a65a3fd28
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.failed_literal_backbones=false smt_parallel.num_global_bb_chunking_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: add continuous checking for new batch after first pass + continous loop behavior in the chunking algorithm

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|scrambled50258.smt2                                          |    0.993s | 263.0MiB| unsat | 0 |  |  |
|scrambled9548.smt2                                           |    4.078s | 283.0MiB| unsat | 0 |  |  |
|scrambled30073.smt2                                          |    4.184s | 253.0MiB| unsat | 0 |  |  |
|scrambled48569.smt2                                          |    5.929s | 1394.0MiB| sat | 0 |  |  |
|scrambled82407.smt2                                          |    6.134s | 279.0MiB| unsat | 0 |  |  |
|scrambled129467.smt2                                         |   11.090s | 442.0MiB| unsat | 0 |  |  |
|scrambled17293.smt2                                          |   18.631s | 1098.0MiB| sat | 0 |  |  |
|scrambled12959.smt2                                          |   19.181s | 367.0MiB| unsat | 0 |  |  |
|scrambled29780.smt2                                          |   30.084s | 298.0MiB| unsat | 0 |  |  |
|scrambled103775.smt2                                         |   33.522s | 387.0MiB| unsat | 0 |  |  |
|scrambled28176.smt2                                          |   65.662s | 848.0MiB| sat | 0 |  |  |
|scrambled80288.smt2                                          |  201.960s | 1468.0MiB| unsat | 0 |  |  |
|scrambled61060.smt2                                          |  204.090s | 1681.0MiB| unsat | 0 |  |  |
|scrambled14845.smt2                                          |  496.684s | 6742.0MiB| unsat | 0 |  |  |
|scrambled31071.smt2                                          | 1020.878s | 1725.0MiB| sat | 0 |  |  |
|scrambled98111.smt2                                          | 1200.155s | 1282.0MiB| timeout | 0 |  |  |
|scrambled101716.smt2                                         | 1200.158s | 1330.0MiB| timeout | 0 |  |  |
|scrambled41135.smt2                                          | 1200.172s | 1866.0MiB| timeout | 0 |  |  |
|scrambled31575.smt2                                          | 1200.174s | 585.0MiB| timeout | 0 |  |  |
|scrambled100714.smt2                                         | 1200.178s | 1236.0MiB| timeout | 0 |  |  |
|scrambled35280.smt2                                          | 1200.183s | 1098.0MiB| timeout | 0 |  |  |
|scrambled96401.smt2                                          | 1200.202s | 1553.0MiB| timeout | 0 |  |  |
|scrambled79354.smt2                                          | 1200.215s | 1665.0MiB| timeout | 0 |  |  |
|scrambled97386.smt2                                          | 1200.222s | 1654.0MiB| timeout | 0 |  |  |
|scrambled119582.smt2                                         | 1200.222s | 1466.0MiB| timeout | 0 |  |  |
|scrambled8852.smt2                                           | 1200.223s | 1839.0MiB| timeout | 0 |  |  |
|scrambled36790.smt2                                          | 1200.234s | 1869.0MiB| timeout | 0 |  |  |
|scrambled38587.smt2                                          | 1200.257s | 1466.0MiB| timeout | 0 |  |  |
|scrambled9883.smt2                                           | 1200.259s | 1527.0MiB| timeout | 0 |  |  |
|scrambled62032.smt2                                          | 1200.266s | 1632.0MiB| timeout | 0 |  |  |
|scrambled39467.smt2                                          | 1200.274s | 2275.0MiB| timeout | 0 |  |  |
|scrambled130111.smt2                                         | 1200.293s | 1982.0MiB| timeout | 0 |  |  |
|scrambled58311.smt2                                          | 1200.300s | 1796.0MiB| timeout | 0 |  |  |
|scrambled108406.smt2                                         | 1200.310s | 2649.0MiB| timeout | 0 |  |  |
|scrambled12033.smt2                                          | 1200.338s | 2922.0MiB| timeout | 0 |  |  |
|scrambled73281.smt2                                          | 1200.363s | 2733.0MiB| timeout | 0 |  |  |
|scrambled108663.smt2                                         | 1200.419s | 3128.0MiB| timeout | 0 |  |  |
|scrambled122926.smt2                                         | 1200.430s | 3843.0MiB| timeout | 0 |  |  |
|scrambled82760.smt2                                          | 1200.491s | 2463.0MiB| timeout | 0 |  |  |
|scrambled91750.smt2                                          | 1200.508s | 2620.0MiB| timeout | 0 |  |  |
|scrambled73755.smt2                                          | 1200.672s | 5242.0MiB| timeout | 0 |  |  |
|scrambled87588.smt2                                          | 1200.701s | 7244.0MiB| timeout | 0 |  |  |
|scrambled47700.smt2                                          | 1200.724s | 5445.0MiB| timeout | 0 |  |  |
|scrambled85357.smt2                                          | 1202.534s | 29.278GiB| timeout | 0 |  |  |
