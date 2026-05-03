# .

* SAT 1
* UNSAT 3
* TIMEOUT 34
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-8-mode-partition-smtcomp2025-QF_LRA-timeout20min
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_LRA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|scrambled71015.smt2                                          |  389.279s | 1827.0MiB| unsat | 0 |  |  |
|scrambled122587.smt2                                         |  616.165s | 657.0MiB| unsat | 0 |  |  |
|scrambled88927.smt2                                          |  765.323s | 656.0MiB| unsat | 0 |  |  |
|scrambled44527.smt2                                          |  776.909s | 20.294GiB| sat | 0 |  |  |
|scrambled46192.smt2                                          | 1199.460s | 604.0MiB| timeout | 0 |  |  |
|scrambled35077.smt2                                          | 1199.527s | 401.0MiB| timeout | 0 |  |  |
|scrambled101728.smt2                                         | 1199.656s | 2598.0MiB| timeout | 0 |  |  |
|scrambled47581.smt2                                          | 1199.723s | 1103.0MiB| timeout | 0 |  |  |
|scrambled102621.smt2                                         | 1199.741s | 6809.0MiB| timeout | 0 |  |  |
|scrambled77008.smt2                                          | 1199.753s | 5466.0MiB| timeout | 0 |  |  |
|scrambled49820.smt2                                          | 1199.819s | 904.0MiB| timeout | 0 |  |  |
|scrambled117897.smt2                                         | 1199.836s | 2723.0MiB| timeout | 0 |  |  |
|scrambled37260.smt2                                          | 1199.838s | 2597.0MiB| timeout | 0 |  |  |
|scrambled8163.smt2                                           | 1199.840s | 5331.0MiB| timeout | 0 |  |  |
|scrambled59368.smt2                                          | 1199.856s | 1434.0MiB| timeout | 0 |  |  |
|scrambled76532.smt2                                          | 1199.884s | 397.0MiB| timeout | 0 |  |  |
|scrambled31085.smt2                                          | 1199.893s | 1767.0MiB| timeout | 0 |  |  |
|scrambled103576.smt2                                         | 1199.909s | 1509.0MiB| timeout | 0 |  |  |
|scrambled95284.smt2                                          | 1199.920s | 2689.0MiB| timeout | 0 |  |  |
|scrambled111949.smt2                                         | 1199.960s | 5861.0MiB| timeout | 0 |  |  |
|scrambled76525.smt2                                          | 1199.985s | 2153.0MiB| timeout | 0 |  |  |
|scrambled115671.smt2                                         | 1199.993s | 575.0MiB| timeout | 0 |  |  |
|scrambled55845.smt2                                          | 1200.009s | 1809.0MiB| timeout | 0 |  |  |
|scrambled124455.smt2                                         | 1200.027s | 2555.0MiB| timeout | 0 |  |  |
|scrambled101086.smt2                                         | 1200.031s | 804.0MiB| timeout | 0 |  |  |
|scrambled124681.smt2                                         | 1200.032s | 867.0MiB| timeout | 0 |  |  |
|scrambled17583.smt2                                          | 1200.040s | 1622.0MiB| timeout | 0 |  |  |
|scrambled92964.smt2                                          | 1200.094s | 1721.0MiB| timeout | 0 |  |  |
|scrambled98986.smt2                                          | 1200.141s | 5470.0MiB| timeout | 0 |  |  |
|scrambled109307.smt2                                         | 1200.191s | 2374.0MiB| timeout | 0 |  |  |
|scrambled13209.smt2                                          | 1200.211s | 7805.0MiB| timeout | 0 |  |  |
|scrambled55850.smt2                                          | 1200.255s | 4651.0MiB| timeout | 0 |  |  |
|scrambled25695.smt2                                          | 1200.262s | 8622.0MiB| timeout | 0 |  |  |
|scrambled65517.smt2                                          | 1200.333s | 4859.0MiB| timeout | 0 |  |  |
|scrambled77308.smt2                                          | 1200.369s | 11.639GiB| timeout | 0 |  |  |
|scrambled102680.smt2                                         | 1200.407s | 5296.0MiB| timeout | 0 |  |  |
|scrambled13169.smt2                                          | 1200.506s | 6546.0MiB| timeout | 0 |  |  |
|scrambled104811.smt2                                         | 1200.511s | 11.554GiB| timeout | 0 |  |  |
