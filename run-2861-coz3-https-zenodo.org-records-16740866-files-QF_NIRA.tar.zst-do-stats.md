# .

* SAT 0
* UNSAT 2
* TIMEOUT 1
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_NIRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_NIRA.tar.zst-do
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: f8bf10af4f032185b6bbe235abe953e38905721e
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_NIRA.tar.zst?download=1
Z3 commit message: remove NOT_IMPLEMENTED_YET

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/QF_NIRA/UltimateAutomizer/test_union_cast-1_true-unreach-call.i.smt2 |    0.025s | 20.612MiB| unsat | 0 |  |  |
|non-incremental/QF_NIRA/LCTES/miniflight.smt2                |    3.177s | 122.0MiB| unsat | 0 |  |  |
|non-incremental/QF_NIRA/LCTES/miniflight.nosummaries.smt2    |   20.054s | 454.0MiB| timeout | 0 |  |  |
