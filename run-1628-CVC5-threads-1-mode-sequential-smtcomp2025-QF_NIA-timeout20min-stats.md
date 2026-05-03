# .

* SAT 2
* UNSAT 2
* TIMEOUT 40
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-1-mode-sequential-smtcomp2025-QF_NIA-timeout20min
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: sequential
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter decision-cube"
cvc5 partition budget: 1
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 1
cvc5 timeout: 1200
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_NIA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|scrambled48569.smt2                                          |   77.021s | 107.0MiB| sat | 0 |  |  |
|scrambled129467.smt2                                         |  642.207s | 401.0MiB| unsat | 0 |  |  |
|scrambled17293.smt2                                          |  670.292s | 383.0MiB| sat | 0 |  |  |
|scrambled14845.smt2                                          | 1070.596s | 362.0MiB| unsat | 0 |  |  |
|scrambled103775.smt2                                         | 1200.036s | 186.0MiB| timeout | 0 |  |  |
|scrambled82407.smt2                                          | 1200.038s | 223.0MiB| timeout | 0 |  |  |
|scrambled97386.smt2                                          | 1200.042s | 260.0MiB| timeout | 0 |  |  |
|scrambled50258.smt2                                          | 1200.048s | 294.0MiB| timeout | 0 |  |  |
|scrambled122926.smt2                                         | 1200.050s | 304.0MiB| timeout | 0 |  |  |
|scrambled30073.smt2                                          | 1200.051s | 172.0MiB| timeout | 0 |  |  |
|scrambled47700.smt2                                          | 1200.052s | 311.0MiB| timeout | 0 |  |  |
|scrambled80288.smt2                                          | 1200.052s | 382.0MiB| timeout | 0 |  |  |
|scrambled8852.smt2                                           | 1200.058s | 200.0MiB| timeout | 0 |  |  |
|scrambled91750.smt2                                          | 1200.059s | 347.0MiB| timeout | 0 |  |  |
|scrambled12959.smt2                                          | 1200.059s | 390.0MiB| timeout | 0 |  |  |
|scrambled130111.smt2                                         | 1200.061s | 255.0MiB| timeout | 0 |  |  |
|scrambled87588.smt2                                          | 1200.063s | 316.0MiB| timeout | 0 |  |  |
|scrambled39467.smt2                                          | 1200.063s | 399.0MiB| timeout | 0 |  |  |
|scrambled73281.smt2                                          | 1200.070s | 421.0MiB| timeout | 0 |  |  |
|scrambled82760.smt2                                          | 1200.076s | 385.0MiB| timeout | 0 |  |  |
|scrambled41135.smt2                                          | 1200.078s | 375.0MiB| timeout | 0 |  |  |
|scrambled108406.smt2                                         | 1200.083s | 302.0MiB| timeout | 0 |  |  |
|scrambled35280.smt2                                          | 1200.085s | 278.0MiB| timeout | 0 |  |  |
|scrambled119582.smt2                                         | 1200.085s | 328.0MiB| timeout | 0 |  |  |
|scrambled61060.smt2                                          | 1200.090s | 323.0MiB| timeout | 0 |  |  |
|scrambled108663.smt2                                         | 1200.092s | 382.0MiB| timeout | 0 |  |  |
|scrambled31575.smt2                                          | 1200.095s | 419.0MiB| timeout | 0 |  |  |
|scrambled58311.smt2                                          | 1200.099s | 450.0MiB| timeout | 0 |  |  |
|scrambled98111.smt2                                          | 1200.103s | 321.0MiB| timeout | 0 |  |  |
|scrambled9883.smt2                                           | 1200.107s | 818.0MiB| timeout | 0 |  |  |
|scrambled28176.smt2                                          | 1200.107s | 317.0MiB| timeout | 0 |  |  |
|scrambled101716.smt2                                         | 1200.107s | 568.0MiB| timeout | 0 |  |  |
|scrambled29780.smt2                                          | 1200.109s | 551.0MiB| timeout | 0 |  |  |
|scrambled100714.smt2                                         | 1200.114s | 387.0MiB| timeout | 0 |  |  |
|scrambled96401.smt2                                          | 1200.117s | 386.0MiB| timeout | 0 |  |  |
|scrambled79354.smt2                                          | 1200.117s | 452.0MiB| timeout | 0 |  |  |
|scrambled36790.smt2                                          | 1200.118s | 391.0MiB| timeout | 0 |  |  |
|scrambled9548.smt2                                           | 1200.127s | 503.0MiB| timeout | 0 |  |  |
|scrambled12033.smt2                                          | 1200.128s | 468.0MiB| timeout | 0 |  |  |
|scrambled62032.smt2                                          | 1200.134s | 684.0MiB| timeout | 0 |  |  |
|scrambled31071.smt2                                          | 1200.135s | 561.0MiB| timeout | 0 |  |  |
|scrambled38587.smt2                                          | 1200.137s | 593.0MiB| timeout | 0 |  |  |
|scrambled73755.smt2                                          | 1200.150s | 694.0MiB| timeout | 0 |  |  |
|scrambled85357.smt2                                          | 1200.245s | 1687.0MiB| timeout | 0 |  |  |
