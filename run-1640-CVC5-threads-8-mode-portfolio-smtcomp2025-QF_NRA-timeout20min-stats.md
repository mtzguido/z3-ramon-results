# .

* SAT 1
* UNSAT 1
* TIMEOUT 42
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_NRA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|scrambled14368.smt2                                          |   74.729s | 1579.0MiB| sat | 0 |  |  |
|scrambled114923.smt2                                         |  832.081s | 11.435GiB| unsat | 0 |  |  |
|scrambled100912.smt2                                         | 1199.366s | 421.0MiB| timeout | 0 |  |  |
|scrambled78428.smt2                                          | 1199.438s | 1382.0MiB| timeout | 0 |  |  |
|scrambled27426.smt2                                          | 1199.440s | 1342.0MiB| timeout | 0 |  |  |
|scrambled6476.smt2                                           | 1199.444s | 1226.0MiB| timeout | 0 |  |  |
|scrambled41575.smt2                                          | 1199.450s | 1439.0MiB| timeout | 0 |  |  |
|scrambled80728.smt2                                          | 1199.506s | 1068.0MiB| timeout | 0 |  |  |
|scrambled42946.smt2                                          | 1199.529s | 1169.0MiB| timeout | 0 |  |  |
|scrambled5797.smt2                                           | 1199.536s | 2593.0MiB| timeout | 0 |  |  |
|scrambled34121.smt2                                          | 1199.548s | 1120.0MiB| timeout | 0 |  |  |
|scrambled85895.smt2                                          | 1199.582s | 2094.0MiB| timeout | 0 |  |  |
|scrambled73220.smt2                                          | 1199.591s | 764.0MiB| timeout | 0 |  |  |
|scrambled94768.smt2                                          | 1199.623s | 3687.0MiB| timeout | 0 |  |  |
|scrambled22492.smt2                                          | 1199.624s | 3194.0MiB| timeout | 0 |  |  |
|scrambled32701.smt2                                          | 1199.645s | 4071.0MiB| timeout | 0 |  |  |
|scrambled118224.smt2                                         | 1199.695s | 4484.0MiB| timeout | 0 |  |  |
|scrambled14880.smt2                                          | 1199.721s | 2914.0MiB| timeout | 0 |  |  |
|scrambled18831.smt2                                          | 1199.756s | 1200.0MiB| timeout | 0 |  |  |
|scrambled70990.smt2                                          | 1199.770s | 1350.0MiB| timeout | 0 |  |  |
|scrambled112083.smt2                                         | 1199.780s | 446.0MiB| timeout | 0 |  |  |
|scrambled82241.smt2                                          | 1199.786s | 5223.0MiB| timeout | 0 |  |  |
|scrambled36539.smt2                                          | 1199.787s | 1359.0MiB| timeout | 0 |  |  |
|scrambled7923.smt2                                           | 1199.792s | 1553.0MiB| timeout | 0 |  |  |
|scrambled61896.smt2                                          | 1199.794s | 1119.0MiB| timeout | 0 |  |  |
|scrambled32269.smt2                                          | 1199.808s | 1779.0MiB| timeout | 0 |  |  |
|scrambled91241.smt2                                          | 1199.827s | 1901.0MiB| timeout | 0 |  |  |
|scrambled60239.smt2                                          | 1199.831s | 1286.0MiB| timeout | 0 |  |  |
|scrambled7586.smt2                                           | 1199.846s | 1278.0MiB| timeout | 0 |  |  |
|scrambled117334.smt2                                         | 1199.846s | 1027.0MiB| timeout | 0 |  |  |
|scrambled121780.smt2                                         | 1199.856s | 1491.0MiB| timeout | 0 |  |  |
|scrambled28630.smt2                                          | 1199.872s | 1282.0MiB| timeout | 0 |  |  |
|scrambled29556.smt2                                          | 1199.884s | 1783.0MiB| timeout | 0 |  |  |
|scrambled54263.smt2                                          | 1199.885s | 938.0MiB| timeout | 0 |  |  |
|scrambled99534.smt2                                          | 1199.890s | 1107.0MiB| timeout | 0 |  |  |
|scrambled21647.smt2                                          | 1199.944s | 2118.0MiB| timeout | 0 |  |  |
|scrambled124828.smt2                                         | 1199.954s | 4962.0MiB| timeout | 0 |  |  |
|scrambled65757.smt2                                          | 1199.958s | 1376.0MiB| timeout | 0 |  |  |
|scrambled58292.smt2                                          | 1199.986s | 5006.0MiB| timeout | 0 |  |  |
|scrambled74869.smt2                                          | 1199.993s | 2532.0MiB| timeout | 0 |  |  |
|scrambled112144.smt2                                         | 1200.022s | 2279.0MiB| timeout | 0 |  |  |
|scrambled94319.smt2                                          | 1200.032s | 3178.0MiB| timeout | 0 |  |  |
|scrambled14016.smt2                                          | 1200.076s | 5947.0MiB| timeout | 0 |  |  |
|scrambled117944.smt2                                         | 1200.150s | 10.47GiB| timeout | 0 |  |  |
