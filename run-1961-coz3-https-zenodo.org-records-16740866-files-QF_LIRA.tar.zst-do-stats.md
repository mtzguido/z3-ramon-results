# .

* SAT 0
* UNSAT 0
* TIMEOUT 7
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
Z3 commit: 459629c662eb7abf25a010b7383431a9f729d234
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_LIRA.tar.zst?download=1
Z3 commit message: bugfixes to ho_matcher

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/QF_LIRA/LCTES/cruise-control.nosummaries.smt2 |   20.021s | 21.724MiB| timeout | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/cruise-control.smt2            |   20.027s | 21.936MiB| timeout | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/fly-by-wire.locals.smt2        |   20.033s | 76.752MiB| timeout | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/smtopt.smt2                    |   20.046s | 238.0MiB| timeout | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/tdf.locals.smt2                |   20.048s | 245.0MiB| timeout | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/tdf.locals.nosummaries.smt2    |   20.051s | 245.0MiB| timeout | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/fly-by-wire.locals.nosummaries.smt2 |   20.062s | 453.0MiB| timeout | 0 |  |  |
