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
Job tag: CVC5-threads-8-mode-portfolio-smtcomp2025-QF_NRA-timeout20min
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
|scrambled44527.smt2                                          |  345.074s | 19.047GiB| sat | 0 |  |  |
|scrambled71015.smt2                                          |  555.157s | 2273.0MiB| unsat | 0 |  |  |
|scrambled122587.smt2                                         |  650.906s | 746.0MiB| unsat | 0 |  |  |
|scrambled109307.smt2                                         |  754.321s | 3392.0MiB| sat | 0 |  |  |
|scrambled88927.smt2                                          |  961.385s | 858.0MiB| unsat | 0 |  |  |
|scrambled35077.smt2                                          | 1199.155s | 499.0MiB| timeout | 0 |  |  |
|scrambled46192.smt2                                          | 1199.287s | 1042.0MiB| timeout | 0 |  |  |
|scrambled76532.smt2                                          | 1199.416s | 504.0MiB| timeout | 0 |  |  |
|scrambled103576.smt2                                         | 1199.530s | 1054.0MiB| timeout | 0 |  |  |
|scrambled47581.smt2                                          | 1199.543s | 2041.0MiB| timeout | 0 |  |  |
|scrambled55845.smt2                                          | 1199.557s | 1604.0MiB| timeout | 0 |  |  |
|scrambled115671.smt2                                         | 1199.557s | 939.0MiB| timeout | 0 |  |  |
|scrambled124455.smt2                                         | 1199.582s | 2287.0MiB| timeout | 0 |  |  |
|scrambled92964.smt2                                          | 1199.583s | 1750.0MiB| timeout | 0 |  |  |
|scrambled124681.smt2                                         | 1199.584s | 1553.0MiB| timeout | 0 |  |  |
|scrambled49820.smt2                                          | 1199.617s | 1920.0MiB| timeout | 0 |  |  |
|scrambled101086.smt2                                         | 1199.624s | 2245.0MiB| timeout | 0 |  |  |
|scrambled59368.smt2                                          | 1199.629s | 1470.0MiB| timeout | 0 |  |  |
|scrambled17583.smt2                                          | 1199.630s | 2471.0MiB| timeout | 0 |  |  |
|scrambled37260.smt2                                          | 1199.638s | 2394.0MiB| timeout | 0 |  |  |
|scrambled117897.smt2                                         | 1199.639s | 2642.0MiB| timeout | 0 |  |  |
|scrambled101728.smt2                                         | 1199.647s | 5337.0MiB| timeout | 0 |  |  |
|scrambled31085.smt2                                          | 1199.710s | 1441.0MiB| timeout | 0 |  |  |
|scrambled25695.smt2                                          | 1199.719s | 11.738GiB| timeout | 0 |  |  |
|scrambled95284.smt2                                          | 1199.732s | 2438.0MiB| timeout | 0 |  |  |
|scrambled76525.smt2                                          | 1199.734s | 2319.0MiB| timeout | 0 |  |  |
|scrambled65517.smt2                                          | 1199.821s | 4410.0MiB| timeout | 0 |  |  |
|scrambled77008.smt2                                          | 1199.900s | 5547.0MiB| timeout | 0 |  |  |
|scrambled111949.smt2                                         | 1199.925s | 11.012GiB| timeout | 0 |  |  |
|scrambled104811.smt2                                         | 1199.944s | 4781.0MiB| timeout | 0 |  |  |
|scrambled13169.smt2                                          | 1199.975s | 12.344GiB| timeout | 0 |  |  |
|scrambled13209.smt2                                          | 1200.000s | 13.077GiB| timeout | 0 |  |  |
|scrambled55850.smt2                                          | 1200.048s | 9608.0MiB| timeout | 0 |  |  |
|scrambled102621.smt2                                         | 1200.057s | 10.331GiB| timeout | 0 |  |  |
|scrambled8163.smt2                                           | 1200.057s | 12.71GiB| timeout | 0 |  |  |
|scrambled102680.smt2                                         | 1200.068s | 7993.0MiB| timeout | 0 |  |  |
|scrambled98986.smt2                                          | 1200.138s | 9187.0MiB| timeout | 0 |  |  |
|scrambled77308.smt2                                          | 1200.240s | 4999.0MiB| timeout | 0 |  |  |
