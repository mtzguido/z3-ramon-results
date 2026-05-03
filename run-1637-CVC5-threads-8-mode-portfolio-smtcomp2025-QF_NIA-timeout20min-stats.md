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
Job tag: CVC5-threads-8-mode-portfolio-smtcomp2025-QF_NIA-timeout20min
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: portfolio
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
|scrambled48569.smt2                                          |   83.843s | 904.0MiB| sat | 0 |  |  |
|scrambled14845.smt2                                          |  311.653s | 2195.0MiB| unsat | 0 |  |  |
|scrambled17293.smt2                                          |  762.307s | 2362.0MiB| sat | 0 |  |  |
|scrambled129467.smt2                                         |  864.091s | 3173.0MiB| unsat | 0 |  |  |
|scrambled100714.smt2                                         | 1199.173s | 2339.0MiB| timeout | 0 |  |  |
|scrambled31575.smt2                                          | 1199.212s | 2898.0MiB| timeout | 0 |  |  |
|scrambled91750.smt2                                          | 1199.260s | 3710.0MiB| timeout | 0 |  |  |
|scrambled82760.smt2                                          | 1199.261s | 3039.0MiB| timeout | 0 |  |  |
|scrambled9883.smt2                                           | 1199.281s | 5797.0MiB| timeout | 0 |  |  |
|scrambled12959.smt2                                          | 1199.297s | 3603.0MiB| timeout | 0 |  |  |
|scrambled73755.smt2                                          | 1199.568s | 8997.0MiB| timeout | 0 |  |  |
|scrambled50258.smt2                                          | 1199.585s | 2087.0MiB| timeout | 0 |  |  |
|scrambled61060.smt2                                          | 1199.785s | 2977.0MiB| timeout | 0 |  |  |
|scrambled8852.smt2                                           | 1199.793s | 2962.0MiB| timeout | 0 |  |  |
|scrambled30073.smt2                                          | 1199.824s | 1932.0MiB| timeout | 0 |  |  |
|scrambled47700.smt2                                          | 1199.834s | 2084.0MiB| timeout | 0 |  |  |
|scrambled41135.smt2                                          | 1199.839s | 2825.0MiB| timeout | 0 |  |  |
|scrambled82407.smt2                                          | 1199.841s | 2243.0MiB| timeout | 0 |  |  |
|scrambled31071.smt2                                          | 1199.846s | 3299.0MiB| timeout | 0 |  |  |
|scrambled108406.smt2                                         | 1199.858s | 2659.0MiB| timeout | 0 |  |  |
|scrambled58311.smt2                                          | 1199.863s | 4152.0MiB| timeout | 0 |  |  |
|scrambled103775.smt2                                         | 1199.872s | 2882.0MiB| timeout | 0 |  |  |
|scrambled29780.smt2                                          | 1199.954s | 3487.0MiB| timeout | 0 |  |  |
|scrambled101716.smt2                                         | 1199.959s | 3853.0MiB| timeout | 0 |  |  |
|scrambled130111.smt2                                         | 1199.962s | 4857.0MiB| timeout | 0 |  |  |
|scrambled79354.smt2                                          | 1199.983s | 3150.0MiB| timeout | 0 |  |  |
|scrambled122926.smt2                                         | 1199.999s | 2784.0MiB| timeout | 0 |  |  |
|scrambled9548.smt2                                           | 1200.006s | 6590.0MiB| timeout | 0 |  |  |
|scrambled98111.smt2                                          | 1200.019s | 2990.0MiB| timeout | 0 |  |  |
|scrambled28176.smt2                                          | 1200.034s | 3632.0MiB| timeout | 0 |  |  |
|scrambled36790.smt2                                          | 1200.035s | 2810.0MiB| timeout | 0 |  |  |
|scrambled35280.smt2                                          | 1200.036s | 3236.0MiB| timeout | 0 |  |  |
|scrambled108663.smt2                                         | 1200.036s | 3190.0MiB| timeout | 0 |  |  |
|scrambled73281.smt2                                          | 1200.048s | 3326.0MiB| timeout | 0 |  |  |
|scrambled12033.smt2                                          | 1200.068s | 4980.0MiB| timeout | 0 |  |  |
|scrambled87588.smt2                                          | 1200.091s | 2979.0MiB| timeout | 0 |  |  |
|scrambled97386.smt2                                          | 1200.211s | 2074.0MiB| timeout | 0 |  |  |
|scrambled119582.smt2                                         | 1200.220s | 2266.0MiB| timeout | 0 |  |  |
|scrambled80288.smt2                                          | 1200.226s | 2132.0MiB| timeout | 0 |  |  |
|scrambled96401.smt2                                          | 1200.236s | 3166.0MiB| timeout | 0 |  |  |
|scrambled62032.smt2                                          | 1200.239s | 2898.0MiB| timeout | 0 |  |  |
|scrambled38587.smt2                                          | 1200.243s | 3796.0MiB| timeout | 0 |  |  |
|scrambled39467.smt2                                          | 1200.245s | 3106.0MiB| timeout | 0 |  |  |
|scrambled85357.smt2                                          | 1200.447s | 13.983GiB| timeout | 0 |  |  |
