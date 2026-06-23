# .

* SAT 1
* UNSAT 4
* TIMEOUT 2
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_LIRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_LIRA.tar.zst-do
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: f8bf10af4f032185b6bbe235abe953e38905721e
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_LIRA.tar.zst?download=1
Z3 commit message: remove NOT_IMPLEMENTED_YET

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/QF_LIRA/LCTES/cruise-control.smt2            |    0.070s | 22.116MiB| unsat | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/cruise-control.nosummaries.smt2 |    0.102s | 22.24MiB| unsat | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/smtopt.smt2                    |    0.815s | 232.0MiB| sat | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/tdf.locals.smt2                |    1.096s | 232.0MiB| unsat | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/fly-by-wire.locals.smt2        |    2.734s | 71.384MiB| unsat | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/tdf.locals.nosummaries.smt2    |   20.063s | 232.0MiB| timeout | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/fly-by-wire.locals.nosummaries.smt2 |   20.073s | 453.0MiB| timeout | 0 |  |  |
