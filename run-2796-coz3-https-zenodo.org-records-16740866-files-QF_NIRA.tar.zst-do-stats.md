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
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: f487af30719c0717f47198b4baac9294519561b7
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_NIRA.tar.zst?download=1
Z3 commit message: use empty sequence regex instead of empty set regex

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/QF_NIRA/UltimateAutomizer/test_union_cast-1_true-unreach-call.i.smt2 |    0.026s | 19.928MiB| unsat | 0 |  |  |
|non-incremental/QF_NIRA/LCTES/miniflight.smt2                |    3.102s | 122.0MiB| unsat | 0 |  |  |
|non-incremental/QF_NIRA/LCTES/miniflight.nosummaries.smt2    |   20.040s | 453.0MiB| timeout | 0 |  |  |
