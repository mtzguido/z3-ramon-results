# .

* SAT 2
* UNSAT 3
* TIMEOUT 33
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-8-mode-portfolio-smtcomp2025-QF_LRA-timeout20min
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_LRA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|scrambled44527.smt2                                          |  353.167s | 19.049GiB| sat | 0 |  |  |
|scrambled71015.smt2                                          |  578.079s | 2316.0MiB| unsat | 0 |  |  |
|scrambled122587.smt2                                         |  679.686s | 747.0MiB| unsat | 0 |  |  |
|scrambled109307.smt2                                         |  782.232s | 3390.0MiB| sat | 0 |  |  |
|scrambled88927.smt2                                          |  958.381s | 857.0MiB| unsat | 0 |  |  |
|scrambled35077.smt2                                          | 1199.175s | 497.0MiB| timeout | 0 |  |  |
|scrambled102680.smt2                                         | 1199.425s | 8002.0MiB| timeout | 0 |  |  |
|scrambled76532.smt2                                          | 1199.554s | 503.0MiB| timeout | 0 |  |  |
|scrambled47581.smt2                                          | 1199.649s | 2060.0MiB| timeout | 0 |  |  |
|scrambled25695.smt2                                          | 1199.669s | 12.026GiB| timeout | 0 |  |  |
|scrambled59368.smt2                                          | 1199.705s | 1470.0MiB| timeout | 0 |  |  |
|scrambled115671.smt2                                         | 1199.708s | 972.0MiB| timeout | 0 |  |  |
|scrambled124681.smt2                                         | 1199.712s | 1567.0MiB| timeout | 0 |  |  |
|scrambled46192.smt2                                          | 1199.727s | 1078.0MiB| timeout | 0 |  |  |
|scrambled124455.smt2                                         | 1199.738s | 2296.0MiB| timeout | 0 |  |  |
|scrambled31085.smt2                                          | 1199.746s | 1448.0MiB| timeout | 0 |  |  |
|scrambled55845.smt2                                          | 1199.747s | 1619.0MiB| timeout | 0 |  |  |
|scrambled103576.smt2                                         | 1199.762s | 1069.0MiB| timeout | 0 |  |  |
|scrambled17583.smt2                                          | 1199.772s | 2460.0MiB| timeout | 0 |  |  |
|scrambled95284.smt2                                          | 1199.787s | 2436.0MiB| timeout | 0 |  |  |
|scrambled37260.smt2                                          | 1199.794s | 2394.0MiB| timeout | 0 |  |  |
|scrambled76525.smt2                                          | 1199.796s | 2329.0MiB| timeout | 0 |  |  |
|scrambled49820.smt2                                          | 1199.809s | 1960.0MiB| timeout | 0 |  |  |
|scrambled92964.smt2                                          | 1199.814s | 1730.0MiB| timeout | 0 |  |  |
|scrambled117897.smt2                                         | 1199.823s | 2641.0MiB| timeout | 0 |  |  |
|scrambled101728.smt2                                         | 1199.841s | 5340.0MiB| timeout | 0 |  |  |
|scrambled101086.smt2                                         | 1199.862s | 2254.0MiB| timeout | 0 |  |  |
|scrambled104811.smt2                                         | 1199.953s | 4727.0MiB| timeout | 0 |  |  |
|scrambled77008.smt2                                          | 1199.973s | 5564.0MiB| timeout | 0 |  |  |
|scrambled65517.smt2                                          | 1200.029s | 4252.0MiB| timeout | 0 |  |  |
|scrambled111949.smt2                                         | 1200.041s | 11.012GiB| timeout | 0 |  |  |
|scrambled102621.smt2                                         | 1200.050s | 10.294GiB| timeout | 0 |  |  |
|scrambled8163.smt2                                           | 1200.050s | 12.718GiB| timeout | 0 |  |  |
|scrambled55850.smt2                                          | 1200.052s | 9609.0MiB| timeout | 0 |  |  |
|scrambled98986.smt2                                          | 1200.055s | 9195.0MiB| timeout | 0 |  |  |
|scrambled13169.smt2                                          | 1200.055s | 12.359GiB| timeout | 0 |  |  |
|scrambled13209.smt2                                          | 1200.068s | 13.061GiB| timeout | 0 |  |  |
|scrambled77308.smt2                                          | 1200.310s | 5045.0MiB| timeout | 0 |  |  |
