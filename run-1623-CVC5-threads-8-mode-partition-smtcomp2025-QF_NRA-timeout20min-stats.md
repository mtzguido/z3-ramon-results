# .

* SAT 2
* UNSAT 0
* TIMEOUT 42
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-8-mode-partition-smtcomp2025-QF_NRA-timeout20min
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_NRA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|scrambled14016.smt2                                          |   35.053s | 506.0MiB| sat | 0 |  |  |
|scrambled118224.smt2                                         |  420.572s | 1186.0MiB| sat | 0 |  |  |
|scrambled70990.smt2                                          | 1199.627s | 955.0MiB| timeout | 0 |  |  |
|scrambled117334.smt2                                         | 1199.658s | 400.0MiB| timeout | 0 |  |  |
|scrambled41575.smt2                                          | 1199.664s | 614.0MiB| timeout | 0 |  |  |
|scrambled61896.smt2                                          | 1199.714s | 460.0MiB| timeout | 0 |  |  |
|scrambled7586.smt2                                           | 1199.790s | 1288.0MiB| timeout | 0 |  |  |
|scrambled60239.smt2                                          | 1199.798s | 518.0MiB| timeout | 0 |  |  |
|scrambled94319.smt2                                          | 1199.836s | 1418.0MiB| timeout | 0 |  |  |
|scrambled6476.smt2                                           | 1199.840s | 530.0MiB| timeout | 0 |  |  |
|scrambled99534.smt2                                          | 1199.848s | 532.0MiB| timeout | 0 |  |  |
|scrambled27426.smt2                                          | 1199.849s | 560.0MiB| timeout | 0 |  |  |
|scrambled78428.smt2                                          | 1199.854s | 588.0MiB| timeout | 0 |  |  |
|scrambled112144.smt2                                         | 1199.878s | 1154.0MiB| timeout | 0 |  |  |
|scrambled91241.smt2                                          | 1199.880s | 770.0MiB| timeout | 0 |  |  |
|scrambled42946.smt2                                          | 1199.892s | 1937.0MiB| timeout | 0 |  |  |
|scrambled85895.smt2                                          | 1199.893s | 675.0MiB| timeout | 0 |  |  |
|scrambled32269.smt2                                          | 1199.896s | 5157.0MiB| timeout | 0 |  |  |
|scrambled80728.smt2                                          | 1199.901s | 3063.0MiB| timeout | 0 |  |  |
|scrambled34121.smt2                                          | 1199.905s | 1063.0MiB| timeout | 0 |  |  |
|scrambled5797.smt2                                           | 1199.914s | 3303.0MiB| timeout | 0 |  |  |
|scrambled7923.smt2                                           | 1199.920s | 995.0MiB| timeout | 0 |  |  |
|scrambled112083.smt2                                         | 1199.924s | 1016.0MiB| timeout | 0 |  |  |
|scrambled22492.smt2                                          | 1199.929s | 2344.0MiB| timeout | 0 |  |  |
|scrambled82241.smt2                                          | 1199.956s | 1347.0MiB| timeout | 0 |  |  |
|scrambled124828.smt2                                         | 1199.972s | 10.179GiB| timeout | 0 |  |  |
|scrambled121780.smt2                                         | 1199.982s | 575.0MiB| timeout | 0 |  |  |
|scrambled65757.smt2                                          | 1200.034s | 78.544MiB| timeout | 0 |  |  |
|scrambled18831.smt2                                          | 1200.036s | 45.448MiB| timeout | 0 |  |  |
|scrambled114923.smt2                                         | 1200.040s | 5680.0MiB| timeout | 0 |  |  |
|scrambled14880.smt2                                          | 1200.045s | 795.0MiB| timeout | 0 |  |  |
|scrambled21647.smt2                                          | 1200.057s | 351.0MiB| timeout | 0 |  |  |
|scrambled14368.smt2                                          | 1200.069s | 4913.0MiB| timeout | 0 |  |  |
|scrambled74869.smt2                                          | 1200.070s | 5048.0MiB| timeout | 0 |  |  |
|scrambled54263.smt2                                          | 1200.077s | 85.104MiB| timeout | 0 |  |  |
|scrambled117944.smt2                                         | 1200.091s | 62.384MiB| timeout | 0 |  |  |
|scrambled36539.smt2                                          | 1200.093s | 234.0MiB| timeout | 0 |  |  |
|scrambled29556.smt2                                          | 1200.096s | 313.0MiB| timeout | 0 |  |  |
|scrambled94768.smt2                                          | 1200.098s | 629.0MiB| timeout | 0 |  |  |
|scrambled28630.smt2                                          | 1200.107s | 2396.0MiB| timeout | 0 |  |  |
|scrambled32701.smt2                                          | 1200.123s | 766.0MiB| timeout | 0 |  |  |
|scrambled58292.smt2                                          | 1200.147s | 725.0MiB| timeout | 0 |  |  |
|scrambled73220.smt2                                          | 1200.170s | 1132.0MiB| timeout | 0 |  |  |
|scrambled100912.smt2                                         | 1200.645s | 627.0MiB| timeout | 0 |  |  |
