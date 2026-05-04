# .

* SAT 0
* UNSAT 1
* TIMEOUT 44
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-8-mode-portfolio-smtcomp2025-QF_IDL-timeout20min
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_IDL
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|scrambled96514.smt2                                          |  802.480s | 4149.0MiB| unsat | 0 |  |  |
|scrambled100416.smt2                                         | 1199.530s | 2117.0MiB| timeout | 0 |  |  |
|scrambled1379.smt2                                           | 1199.543s | 1542.0MiB| timeout | 0 |  |  |
|scrambled116992.smt2                                         | 1199.546s | 1599.0MiB| timeout | 0 |  |  |
|scrambled35345.smt2                                          | 1199.559s | 1830.0MiB| timeout | 0 |  |  |
|scrambled119992.smt2                                         | 1199.586s | 1706.0MiB| timeout | 0 |  |  |
|scrambled122413.smt2                                         | 1199.602s | 2147.0MiB| timeout | 0 |  |  |
|scrambled62859.smt2                                          | 1199.609s | 3125.0MiB| timeout | 0 |  |  |
|scrambled41801.smt2                                          | 1199.643s | 1694.0MiB| timeout | 0 |  |  |
|scrambled89071.smt2                                          | 1199.664s | 3836.0MiB| timeout | 0 |  |  |
|scrambled58720.smt2                                          | 1199.686s | 2166.0MiB| timeout | 0 |  |  |
|scrambled90733.smt2                                          | 1199.691s | 4299.0MiB| timeout | 0 |  |  |
|scrambled54073.smt2                                          | 1199.692s | 4150.0MiB| timeout | 0 |  |  |
|scrambled117178.smt2                                         | 1199.704s | 3108.0MiB| timeout | 0 |  |  |
|scrambled124624.smt2                                         | 1199.706s | 5013.0MiB| timeout | 0 |  |  |
|scrambled15552.smt2                                          | 1199.706s | 5695.0MiB| timeout | 0 |  |  |
|scrambled23483.smt2                                          | 1199.723s | 1324.0MiB| timeout | 0 |  |  |
|scrambled41773.smt2                                          | 1199.754s | 1530.0MiB| timeout | 0 |  |  |
|scrambled75206.smt2                                          | 1199.755s | 1522.0MiB| timeout | 0 |  |  |
|scrambled96733.smt2                                          | 1199.773s | 1365.0MiB| timeout | 0 |  |  |
|scrambled6373.smt2                                           | 1199.781s | 1839.0MiB| timeout | 0 |  |  |
|scrambled97138.smt2                                          | 1199.806s | 2554.0MiB| timeout | 0 |  |  |
|scrambled103851.smt2                                         | 1199.836s | 3017.0MiB| timeout | 0 |  |  |
|scrambled21544.smt2                                          | 1199.838s | 2865.0MiB| timeout | 0 |  |  |
|scrambled15284.smt2                                          | 1199.838s | 1321.0MiB| timeout | 0 |  |  |
|scrambled78606.smt2                                          | 1199.864s | 3968.0MiB| timeout | 0 |  |  |
|scrambled4441.smt2                                           | 1199.895s | 4642.0MiB| timeout | 0 |  |  |
|scrambled27577.smt2                                          | 1199.910s | 2824.0MiB| timeout | 0 |  |  |
|scrambled9927.smt2                                           | 1199.950s | 4020.0MiB| timeout | 0 |  |  |
|scrambled78432.smt2                                          | 1199.956s | 4117.0MiB| timeout | 0 |  |  |
|scrambled14967.smt2                                          | 1199.966s | 2218.0MiB| timeout | 0 |  |  |
|scrambled1447.smt2                                           | 1199.971s | 2197.0MiB| timeout | 0 |  |  |
|scrambled62536.smt2                                          | 1199.972s | 5343.0MiB| timeout | 0 |  |  |
|scrambled62810.smt2                                          | 1199.978s | 2202.0MiB| timeout | 0 |  |  |
|scrambled42287.smt2                                          | 1200.018s | 2435.0MiB| timeout | 0 |  |  |
|scrambled82743.smt2                                          | 1200.046s | 5215.0MiB| timeout | 0 |  |  |
|scrambled122058.smt2                                         | 1200.047s | 5320.0MiB| timeout | 0 |  |  |
|scrambled41312.smt2                                          | 1200.048s | 2317.0MiB| timeout | 0 |  |  |
|scrambled25140.smt2                                          | 1200.049s | 67.277GiB| timeout | 0 |  |  |
|scrambled92133.smt2                                          | 1200.049s | 7181.0MiB| timeout | 0 |  |  |
|scrambled98799.smt2                                          | 1200.053s | 4480.0MiB| timeout | 0 |  |  |
|scrambled128361.smt2                                         | 1200.053s | 4235.0MiB| timeout | 0 |  |  |
|scrambled109208.smt2                                         | 1200.063s | 6449.0MiB| timeout | 0 |  |  |
|scrambled38610.smt2                                          | 1200.064s | 2703.0MiB| timeout | 0 |  |  |
|scrambled79181.smt2                                          | 1200.210s | 2140.0MiB| timeout | 0 |  |  |
