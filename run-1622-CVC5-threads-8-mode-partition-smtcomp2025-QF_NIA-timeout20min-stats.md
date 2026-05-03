# .

* SAT 2
* UNSAT 1
* TIMEOUT 41
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-8-mode-partition-smtcomp2025-QF_NIA-timeout20min
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: partition
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter decision-cube"
cvc5 partition budget: 8
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 8
cvc5 timeout: 1200
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_NIA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|scrambled48569.smt2                                          |   73.889s | 773.0MiB| sat | 0 |  |  |
|scrambled17293.smt2                                          |   86.539s | 889.0MiB| sat | 0 |  |  |
|scrambled38587.smt2                                          | 1021.082s | 1306.0MiB| unsat | 0 |  |  |
|scrambled103775.smt2                                         | 1199.391s | 1764.0MiB| timeout | 0 |  |  |
|scrambled50258.smt2                                          | 1199.658s | 1603.0MiB| timeout | 0 |  |  |
|scrambled58311.smt2                                          | 1199.748s | 3078.0MiB| timeout | 0 |  |  |
|scrambled98111.smt2                                          | 1199.749s | 2226.0MiB| timeout | 0 |  |  |
|scrambled73281.smt2                                          | 1199.758s | 2647.0MiB| timeout | 0 |  |  |
|scrambled87588.smt2                                          | 1199.797s | 3030.0MiB| timeout | 0 |  |  |
|scrambled35280.smt2                                          | 1199.797s | 2224.0MiB| timeout | 0 |  |  |
|scrambled28176.smt2                                          | 1199.797s | 2661.0MiB| timeout | 0 |  |  |
|scrambled36790.smt2                                          | 1199.797s | 2537.0MiB| timeout | 0 |  |  |
|scrambled9548.smt2                                           | 1199.797s | 6176.0MiB| timeout | 0 |  |  |
|scrambled47700.smt2                                          | 1199.805s | 2135.0MiB| timeout | 0 |  |  |
|scrambled41135.smt2                                          | 1199.807s | 2476.0MiB| timeout | 0 |  |  |
|scrambled61060.smt2                                          | 1199.815s | 2403.0MiB| timeout | 0 |  |  |
|scrambled30073.smt2                                          | 1199.828s | 1744.0MiB| timeout | 0 |  |  |
|scrambled122926.smt2                                         | 1199.844s | 2337.0MiB| timeout | 0 |  |  |
|scrambled12033.smt2                                          | 1199.857s | 3641.0MiB| timeout | 0 |  |  |
|scrambled82407.smt2                                          | 1199.858s | 2295.0MiB| timeout | 0 |  |  |
|scrambled29780.smt2                                          | 1199.877s | 3286.0MiB| timeout | 0 |  |  |
|scrambled108406.smt2                                         | 1199.904s | 1618.0MiB| timeout | 0 |  |  |
|scrambled130111.smt2                                         | 1199.914s | 2189.0MiB| timeout | 0 |  |  |
|scrambled14845.smt2                                          | 1199.942s | 1889.0MiB| timeout | 0 |  |  |
|scrambled129467.smt2                                         | 1199.946s | 2234.0MiB| timeout | 0 |  |  |
|scrambled101716.smt2                                         | 1199.950s | 3248.0MiB| timeout | 0 |  |  |
|scrambled108663.smt2                                         | 1199.965s | 2225.0MiB| timeout | 0 |  |  |
|scrambled31071.smt2                                          | 1199.978s | 3167.0MiB| timeout | 0 |  |  |
|scrambled8852.smt2                                           | 1200.000s | 3394.0MiB| timeout | 0 |  |  |
|scrambled79354.smt2                                          | 1200.015s | 3446.0MiB| timeout | 0 |  |  |
|scrambled97386.smt2                                          | 1200.111s | 1448.0MiB| timeout | 0 |  |  |
|scrambled31575.smt2                                          | 1200.212s | 1944.0MiB| timeout | 0 |  |  |
|scrambled96401.smt2                                          | 1200.219s | 2531.0MiB| timeout | 0 |  |  |
|scrambled39467.smt2                                          | 1200.224s | 1856.0MiB| timeout | 0 |  |  |
|scrambled119582.smt2                                         | 1200.226s | 2399.0MiB| timeout | 0 |  |  |
|scrambled100714.smt2                                         | 1200.243s | 2338.0MiB| timeout | 0 |  |  |
|scrambled80288.smt2                                          | 1200.246s | 1758.0MiB| timeout | 0 |  |  |
|scrambled12959.smt2                                          | 1200.255s | 2045.0MiB| timeout | 0 |  |  |
|scrambled82760.smt2                                          | 1200.257s | 2384.0MiB| timeout | 0 |  |  |
|scrambled91750.smt2                                          | 1200.281s | 2943.0MiB| timeout | 0 |  |  |
|scrambled62032.smt2                                          | 1200.303s | 3198.0MiB| timeout | 0 |  |  |
|scrambled73755.smt2                                          | 1200.311s | 5040.0MiB| timeout | 0 |  |  |
|scrambled9883.smt2                                           | 1200.335s | 3682.0MiB| timeout | 0 |  |  |
|scrambled85357.smt2                                          | 1200.448s | 13.413GiB| timeout | 0 |  |  |
