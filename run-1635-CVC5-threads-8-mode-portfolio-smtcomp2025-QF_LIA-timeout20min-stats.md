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
Job tag: CVC5-threads-8-mode-portfolio-smtcomp2025-QF_LIA-timeout20min
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_LIA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|scrambled25238.smt2                                          |  121.052s | 2136.0MiB| sat | 0 |  |  |
|scrambled125888.smt2                                         |  488.863s | 907.0MiB| sat | 0 |  |  |
|scrambled79867.smt2                                          | 1130.758s | 14.874GiB| unsat | 0 |  |  |
|scrambled20101.smt2                                          | 1199.480s | 1152.0MiB| timeout | 0 |  |  |
|scrambled118793.smt2                                         | 1199.571s | 712.0MiB| timeout | 0 |  |  |
|scrambled44911.smt2                                          | 1199.624s | 2015.0MiB| timeout | 0 |  |  |
|scrambled72668.smt2                                          | 1199.644s | 2162.0MiB| timeout | 0 |  |  |
|scrambled32836.smt2                                          | 1199.655s | 1537.0MiB| timeout | 0 |  |  |
|scrambled128732.smt2                                         | 1199.656s | 2262.0MiB| timeout | 0 |  |  |
|scrambled128874.smt2                                         | 1199.699s | 1827.0MiB| timeout | 0 |  |  |
|scrambled95803.smt2                                          | 1199.735s | 1432.0MiB| timeout | 0 |  |  |
|scrambled125827.smt2                                         | 1199.740s | 753.0MiB| timeout | 0 |  |  |
|scrambled40621.smt2                                          | 1199.806s | 3254.0MiB| timeout | 0 |  |  |
|scrambled128128.smt2                                         | 1199.857s | 2552.0MiB| timeout | 0 |  |  |
|scrambled51053.smt2                                          | 1199.870s | 2518.0MiB| timeout | 0 |  |  |
|scrambled61922.smt2                                          | 1199.970s | 5379.0MiB| timeout | 0 |  |  |
|scrambled119331.smt2                                         | 1199.973s | 3160.0MiB| timeout | 0 |  |  |
|scrambled131241.smt2                                         | 1199.973s | 3265.0MiB| timeout | 0 |  |  |
|scrambled7741.smt2                                           | 1200.011s | 2847.0MiB| timeout | 0 |  |  |
|scrambled55777.smt2                                          | 1200.045s | 2412.0MiB| timeout | 0 |  |  |
|scrambled55680.smt2                                          | 1200.054s | 23.938GiB| timeout | 0 |  |  |
|scrambled12042.smt2                                          | 1200.055s | 28.349GiB| timeout | 0 |  |  |
|scrambled4299.smt2                                           | 1200.055s | 18.891GiB| timeout | 0 |  |  |
|scrambled45952.smt2                                          | 1200.057s | 14.808GiB| timeout | 0 |  |  |
|scrambled59713.smt2                                          | 1200.058s | 14.953GiB| timeout | 0 |  |  |
|scrambled107826.smt2                                         | 1200.059s | 14.793GiB| timeout | 0 |  |  |
|scrambled108840.smt2                                         | 1200.059s | 20.875GiB| timeout | 0 |  |  |
|scrambled75189.smt2                                          | 1200.070s | 15.016GiB| timeout | 0 |  |  |
|scrambled3854.smt2                                           | 1200.070s | 14.741GiB| timeout | 0 |  |  |
|scrambled65181.smt2                                          | 1200.071s | 14.454GiB| timeout | 0 |  |  |
|scrambled103783.smt2                                         | 1200.072s | 14.676GiB| timeout | 0 |  |  |
|scrambled4198.smt2                                           | 1200.075s | 28.344GiB| timeout | 0 |  |  |
|scrambled102166.smt2                                         | 1200.083s | 21.232GiB| timeout | 0 |  |  |
|scrambled94658.smt2                                          | 1200.084s | 27.047GiB| timeout | 0 |  |  |
|scrambled39514.smt2                                          | 1200.085s | 15.201GiB| timeout | 0 |  |  |
|scrambled111627.smt2                                         | 1200.088s | 17.403GiB| timeout | 0 |  |  |
|scrambled27843.smt2                                          | 1200.098s | 11.186GiB| timeout | 0 |  |  |
|scrambled68944.smt2                                          | 1200.103s | 15.874GiB| timeout | 0 |  |  |
|scrambled19335.smt2                                          | 1200.122s | 16.48GiB| timeout | 0 |  |  |
|scrambled79760.smt2                                          | 1200.123s | 23.012GiB| timeout | 0 |  |  |
|scrambled107115.smt2                                         | 1200.131s | 9411.0MiB| timeout | 0 |  |  |
|scrambled43577.smt2                                          | 1200.149s | 19.082GiB| timeout | 0 |  |  |
|scrambled79766.smt2                                          | 1200.211s | 14.717GiB| timeout | 0 |  |  |
|scrambled1417.smt2                                           | 1200.466s | 15.143GiB| timeout | 0 |  |  |
