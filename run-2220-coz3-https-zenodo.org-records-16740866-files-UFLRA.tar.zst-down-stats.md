# .

* SAT 2
* UNSAT 10
* TIMEOUT 3
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFLRA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFLRA.tar.zst-down
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 branch: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFLRA.tar.zst?download=1
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
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                 |    0.023s | 20.352MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                 |    0.023s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                 |    0.023s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                 |    0.023s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                 |    0.025s | 20.38MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                 |    0.025s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                 |    0.025s | 20.38MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                 |    0.025s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                 |    0.050s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                 |    0.050s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/misc/set16.smt2                        |    1.670s | 33.388MiB| sat | 0 |  |  |
|non-incremental/UFLRA/misc/set9.smt2                         |    2.655s | 40.064MiB| sat | 0 |  |  |
|non-incremental/UFLRA/misc/set14.smt2                        |   20.026s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/UFLRA/misc/set19.smt2                        |   20.027s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/UFLRA/misc/list2.smt2                        |   20.038s | 237.0MiB| timeout | 0 |  |  |
