# .

* SAT 0
* UNSAT 0
* TIMEOUT 0
* UNKNOWN 2

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFBVFP.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFBVFP.tar.zst-dow
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 459629c662eb7abf25a010b7383431a9f729d234
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVFP.tar.zst?download=1
Z3 commit message: bugfixes to ho_matcher

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFBVFP/20210301-Alive2-partial-undef/gzip/333_gzip.smt2 |    0.040s | 20.352MiB| unknown | 0 |  |  |
|non-incremental/UFBVFP/20210301-Alive2/oggenc/439_oggenc.smt2 |    0.050s | 20.848MiB| unknown | 0 |  |  |
