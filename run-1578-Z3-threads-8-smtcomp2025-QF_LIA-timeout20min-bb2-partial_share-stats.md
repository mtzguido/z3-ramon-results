# .

* SAT 6
* UNSAT 0
* TIMEOUT 38
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-partial_share
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: fc6e0e2742443c693f569ba295c61781ffcc3916
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: core min and bb threads share units as global bb ONLY and do not actually send them to the worker threads, just use for pruning

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|scrambled125888.smt2                                         |   95.489s | 1581.0MiB| sat | 0 |  |  |
|scrambled20101.smt2                                          |  114.381s | 1627.0MiB| sat | 0 |  |  |
|scrambled118793.smt2                                         |  117.685s | 948.0MiB| sat | 0 |  |  |
|scrambled25238.smt2                                          |  215.662s | 5904.0MiB| sat | 0 |  |  |
|scrambled32836.smt2                                          |  509.773s | 2573.0MiB| sat | 0 |  |  |
|scrambled125827.smt2                                         |  672.401s | 1032.0MiB| sat | 0 |  |  |
|scrambled3854.smt2                                           | 1200.013s | 42.808MiB| timeout | 0 |  |  |
|scrambled45952.smt2                                          | 1200.016s | 42.036MiB| timeout | 0 |  |  |
|scrambled65181.smt2                                          | 1200.017s | 43.116MiB| timeout | 0 |  |  |
|scrambled59713.smt2                                          | 1200.017s | 41.784MiB| timeout | 0 |  |  |
|scrambled79867.smt2                                          | 1200.038s | 41.804MiB| timeout | 0 |  |  |
|scrambled103783.smt2                                         | 1200.040s | 42.312MiB| timeout | 0 |  |  |
|scrambled39514.smt2                                          | 1200.044s | 74.692MiB| timeout | 0 |  |  |
|scrambled79766.smt2                                          | 1200.060s | 42.56MiB| timeout | 0 |  |  |
|scrambled1417.smt2                                           | 1200.118s | 370.0MiB| timeout | 0 |  |  |
|scrambled95803.smt2                                          | 1200.297s | 2559.0MiB| timeout | 0 |  |  |
|scrambled51053.smt2                                          | 1200.401s | 2914.0MiB| timeout | 0 |  |  |
|scrambled55777.smt2                                          | 1200.505s | 4576.0MiB| timeout | 0 |  |  |
|scrambled128732.smt2                                         | 1200.520s | 5187.0MiB| timeout | 0 |  |  |
|scrambled128874.smt2                                         | 1200.576s | 5194.0MiB| timeout | 0 |  |  |
|scrambled128128.smt2                                         | 1200.683s | 6581.0MiB| timeout | 0 |  |  |
|scrambled44911.smt2                                          | 1200.733s | 5033.0MiB| timeout | 0 |  |  |
|scrambled131241.smt2                                         | 1200.735s | 6453.0MiB| timeout | 0 |  |  |
|scrambled7741.smt2                                           | 1200.826s | 6721.0MiB| timeout | 0 |  |  |
|scrambled119331.smt2                                         | 1200.922s | 9255.0MiB| timeout | 0 |  |  |
|scrambled40621.smt2                                          | 1201.125s | 10.832GiB| timeout | 0 |  |  |
|scrambled61922.smt2                                          | 1201.164s | 10.83GiB| timeout | 0 |  |  |
|scrambled72668.smt2                                          | 1201.244s | 5315.0MiB| timeout | 0 |  |  |
|scrambled107115.smt2                                         | 1201.758s | 17.79GiB| timeout | 0 |  |  |
|scrambled107826.smt2                                         | 1202.401s | 27.972GiB| timeout | 0 |  |  |
|scrambled27843.smt2                                          | 1202.541s | 21.031GiB| timeout | 0 |  |  |
|scrambled75189.smt2                                          | 1202.864s | 31.696GiB| timeout | 0 |  |  |
|scrambled19335.smt2                                          | 1203.408s | 32.372GiB| timeout | 0 |  |  |
|scrambled43577.smt2                                          | 1203.568s | 34.26GiB| timeout | 0 |  |  |
|scrambled108840.smt2                                         | 1203.826s | 43.146GiB| timeout | 0 |  |  |
|scrambled102166.smt2                                         | 1204.190s | 48.152GiB| timeout | 0 |  |  |
|scrambled111627.smt2                                         | 1204.441s | 37.747GiB| timeout | 0 |  |  |
|scrambled55680.smt2                                          | 1204.557s | 50.685GiB| timeout | 0 |  |  |
|scrambled4198.smt2                                           | 1204.567s | 49.22GiB| timeout | 0 |  |  |
|scrambled68944.smt2                                          | 1204.716s | 46.324GiB| timeout | 0 |  |  |
|scrambled79760.smt2                                          | 1204.824s | 44.244GiB| timeout | 0 |  |  |
|scrambled4299.smt2                                           | 1204.922s | 56.789GiB| timeout | 0 |  |  |
|scrambled12042.smt2                                          | 1204.934s | 54.639GiB| timeout | 0 |  |  |
|scrambled94658.smt2                                          | 1206.716s | 63.257GiB| timeout | 0 |  |  |
