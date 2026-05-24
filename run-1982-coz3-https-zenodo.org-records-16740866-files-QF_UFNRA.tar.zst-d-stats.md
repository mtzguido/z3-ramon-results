# .

* SAT 2
* UNSAT 4
* TIMEOUT 52
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFNRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFNRA.tar.zst-d
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 459629c662eb7abf25a010b7383431a9f729d234
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFNRA.tar.zst?download=1
Z3 commit message: bugfixes to ho_matcher

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/QF_UFNRA/20190906-CLEARSY/0004/00003.smt2    |    0.022s | 19.848MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.640350.smt2              |    0.030s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/l40f.smt2                       |    0.045s | 21.236MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/z3.641736.smt2                  |    0.052s | 19.572MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/z3.630166.smt2                  |    0.053s | 19.792MiB| sat | 0 |  |  |
|non-incremental/QF_UFNRA/cas/l40m.smt2                       |    0.073s | 21.5MiB| unsat | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modSimpleTest.smt2 |   20.010s | 20.112MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep4.smt2 |   20.010s | 20.628MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40m50.smt2                      |   20.011s | 26.704MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40s50.smt2                      |   20.011s | 27.16MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40f10.smt2                      |   20.011s | 26.692MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep6.smt2 |   20.011s | 21.156MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modInvVar1.smt2 |   20.011s | 20.336MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/20u10.09.smt2                   |   20.012s | 24.96MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep3.smt2 |   20.012s | 20.584MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep4a.smt2 |   20.012s | 20.876MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep3a.smt2 |   20.012s | 20.608MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40u20.19.smt2                   |   20.014s | 29.144MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40m99.smt2                      |   20.014s | 26.468MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40f99.smt2                      |   20.014s | 26.596MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40f50.smt2                      |   20.014s | 26.612MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep7a.smt2 |   20.014s | 20.876MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStepFinal.smt2 |   20.014s | 20.312MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/30u15.14.smt2                   |   20.015s | 26.896MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/m40.smt2                        |   20.016s | 29.26MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/10u05.04.smt2                   |   20.017s | 23.136MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep7.smt2 |   20.017s | 20.88MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.631277.smt2              |   20.019s | 19.9MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep2.smt2 |   20.019s | 20.876MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep5.smt2 |   20.019s | 20.62MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep1a.smt2 |   20.019s | 20.652MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.630785.smt2              |   20.020s | 19.852MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep6a.smt2 |   20.020s | 20.964MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep1.smt2 |   20.020s | 20.308MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.630867.smt2              |   20.021s | 20.012MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/s40.smt2                        |   20.022s | 26.808MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.630949.smt2              |   20.022s | 19.86MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40s10.smt2                      |   20.025s | 26.768MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/20revert.u.smt2                 |   20.027s | 25.188MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/l40s.smt2                       |   20.030s | 26.876MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/c40f.smt2                       |   20.033s | 26.628MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep5a.smt2 |   20.036s | 20.42MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.631031.smt2              |   20.041s | 19.856MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.631195.smt2              |   20.042s | 19.928MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/FFT/smtlib.631113.smt2              |   20.042s | 20.032MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40f25.smt2                      |   20.044s | 26.656MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40m25.smt2                      |   20.045s | 26.832MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modInvInitial.smt2 |   20.045s | 20.408MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modInvFull.smt2 |   20.045s | 21.14MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40s99.smt2                      |   20.046s | 27.184MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/m40.easy.smt2                   |   20.046s | 26.4MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/modInvStep.smt2 |   20.046s | 20.652MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStepFinala.smt2 |   20.046s | 20.316MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/c40m.smt2                       |   20.047s | 26.792MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/c40s.smt2                       |   20.047s | 26.96MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40m10.smt2                      |   20.047s | 26.608MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/cas/40s25.smt2                      |   20.047s | 26.72MiB| timeout | 0 |  |  |
|non-incremental/QF_UFNRA/20230328-sqrtmodinv-hoenicke/sqrtStep2a.smt2 |   20.047s | 20.916MiB| timeout | 0 |  |  |
