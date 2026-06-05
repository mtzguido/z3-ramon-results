# .

* SAT 2
* UNSAT 0
* TIMEOUT 0
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFBVFP.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFBVFP.tar.zst-dow
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 branch: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVFP.tar.zst?download=1
Z3 commit message: Use the minimum generation number among matching enodes (#9405)

* Compute term generations based on minimal match

* Tidy up get_*_f_app

* Update euf_mam to the minimum generation number among matches

* Update euf_mam.cpp

* Move the UNREACHABLE() test to smt_mam.cpp

* Enforce stickiness of max-generation

* Add current generation tracking to bind structure

* Fix build error

---------

Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFBVFP/20210301-Alive2-partial-undef/gzip/333_gzip.smt2 |    0.037s | 20.092MiB| sat | 1 |  |  |
|non-incremental/UFBVFP/20210301-Alive2/oggenc/439_oggenc.smt2 |    0.039s | 19.84MiB| sat | 1 |  |  |
