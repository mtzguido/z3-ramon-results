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
Job tag: CVC5-threads-8-mode-partition-smtcomp2025-QF_LIA-timeout20min
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_LIA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|scrambled125827.smt2                                         |  318.803s | 744.0MiB| sat | 0 |  |  |
|scrambled95803.smt2                                          | 1066.673s | 1307.0MiB| sat | 0 |  |  |
|scrambled125888.smt2                                         | 1199.332s | 1128.0MiB| timeout | 0 |  |  |
|scrambled128732.smt2                                         | 1199.380s | 2273.0MiB| timeout | 0 |  |  |
|scrambled32836.smt2                                          | 1199.410s | 1489.0MiB| timeout | 0 |  |  |
|scrambled25238.smt2                                          | 1199.411s | 3066.0MiB| timeout | 0 |  |  |
|scrambled131241.smt2                                         | 1199.415s | 2896.0MiB| timeout | 0 |  |  |
|scrambled40621.smt2                                          | 1199.425s | 3958.0MiB| timeout | 0 |  |  |
|scrambled128128.smt2                                         | 1199.427s | 2636.0MiB| timeout | 0 |  |  |
|scrambled128874.smt2                                         | 1199.443s | 1804.0MiB| timeout | 0 |  |  |
|scrambled7741.smt2                                           | 1199.512s | 3515.0MiB| timeout | 0 |  |  |
|scrambled118793.smt2                                         | 1199.535s | 765.0MiB| timeout | 0 |  |  |
|scrambled20101.smt2                                          | 1199.562s | 1159.0MiB| timeout | 0 |  |  |
|scrambled55777.smt2                                          | 1199.636s | 2312.0MiB| timeout | 0 |  |  |
|scrambled72668.smt2                                          | 1199.892s | 2189.0MiB| timeout | 0 |  |  |
|scrambled44911.smt2                                          | 1199.901s | 2151.0MiB| timeout | 0 |  |  |
|scrambled65181.smt2                                          | 1200.061s | 141.0MiB| timeout | 0 |  |  |
|scrambled3854.smt2                                           | 1200.061s | 142.0MiB| timeout | 0 |  |  |
|scrambled45952.smt2                                          | 1200.063s | 144.0MiB| timeout | 0 |  |  |
|scrambled59713.smt2                                          | 1200.064s | 144.0MiB| timeout | 0 |  |  |
|scrambled79766.smt2                                          | 1200.070s | 143.0MiB| timeout | 0 |  |  |
|scrambled79867.smt2                                          | 1200.072s | 147.0MiB| timeout | 0 |  |  |
|scrambled39514.smt2                                          | 1200.073s | 147.0MiB| timeout | 0 |  |  |
|scrambled103783.smt2                                         | 1200.101s | 141.0MiB| timeout | 0 |  |  |
|scrambled51053.smt2                                          | 1200.139s | 393.0MiB| timeout | 0 |  |  |
|scrambled61922.smt2                                          | 1200.195s | 848.0MiB| timeout | 0 |  |  |
|scrambled107115.smt2                                         | 1200.232s | 2416.0MiB| timeout | 0 |  |  |
|scrambled119331.smt2                                         | 1200.266s | 3173.0MiB| timeout | 0 |  |  |
|scrambled111627.smt2                                         | 1200.279s | 2258.0MiB| timeout | 0 |  |  |
|scrambled68944.smt2                                          | 1200.316s | 3092.0MiB| timeout | 0 |  |  |
|scrambled19335.smt2                                          | 1200.324s | 3145.0MiB| timeout | 0 |  |  |
|scrambled27843.smt2                                          | 1200.345s | 1804.0MiB| timeout | 0 |  |  |
|scrambled102166.smt2                                         | 1200.354s | 3509.0MiB| timeout | 0 |  |  |
|scrambled43577.smt2                                          | 1200.355s | 3200.0MiB| timeout | 0 |  |  |
|scrambled79760.smt2                                          | 1200.377s | 3177.0MiB| timeout | 0 |  |  |
|scrambled107826.smt2                                         | 1200.422s | 3202.0MiB| timeout | 0 |  |  |
|scrambled4198.smt2                                           | 1200.476s | 4292.0MiB| timeout | 0 |  |  |
|scrambled108840.smt2                                         | 1200.536s | 3459.0MiB| timeout | 0 |  |  |
|scrambled1417.smt2                                           | 1200.566s | 34.982GiB| timeout | 0 |  |  |
|scrambled75189.smt2                                          | 1200.573s | 2974.0MiB| timeout | 0 |  |  |
|scrambled94658.smt2                                          | 1200.728s | 4184.0MiB| timeout | 0 |  |  |
|scrambled55680.smt2                                          | 1200.805s | 3854.0MiB| timeout | 0 |  |  |
|scrambled12042.smt2                                          | 1200.819s | 4249.0MiB| timeout | 0 |  |  |
|scrambled4299.smt2                                           | 1200.937s | 5308.0MiB| timeout | 0 |  |  |
