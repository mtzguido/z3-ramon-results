# .

* SAT 2
* UNSAT 55
* TIMEOUT 11
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFIDL.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFIDL.tar.zst-down
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 branch: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFIDL.tar.zst?download=1
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
|non-incremental/UFIDL/boogie/False_Test1-noinfer.smt2        |    0.020s | 19.652MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Passification_Loop-noinfer.smt2 |    0.021s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/NestedVC_P-vc_nested.smt2       |    0.022s | 19.612MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_less-noinfer_2.smt2 |    0.023s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns3.smt2                      |    0.025s | 20.276MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns11.smt2                     |    0.026s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Skip0-noinfer.smt2       |    0.026s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/heapsucc1_M-infer_eh-vc_local.smt2 |    0.026s | 20.072MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858929.smt2 |    0.027s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala10.smt2  |    0.028s | 20.492MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_Q-vc_nested.smt2 |    0.029s | 19.604MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/AssumeEnsures_Caller0-noinfer.smt2 |    0.029s | 19.96MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_1.smt2 |    0.029s | 20.136MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Skip1-noinfer.smt2       |    0.030s | 20.588MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/loop0_M-infer_e-vc_local.smt2   |    0.030s | 19.98MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Old_SwapElems-noinfer.smt2      |    0.031s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/equiv2_M-infer_e-vc_local.smt2  |    0.031s | 19.816MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.675311.smt2 |    0.033s | 19.984MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala13.smt2  |    0.034s | 21.412MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala6.smt2   |    0.038s | 21.584MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns8.smt2                      |    0.038s | 20.468MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Passification_UnreachableBlock-noinfer.smt2 |    0.039s | 19.608MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala7.smt2   |    0.042s | 21.7MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns6.smt2                      |    0.043s | 21.136MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns4.smt2                      |    0.043s | 20.808MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala0.smt2   |    0.045s | 20.652MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_P-vc_nested.smt2 |    0.045s | 19.664MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/heapsucc0_M-infer_eh-vc_local.smt2 |    0.045s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala8.smt2   |    0.046s | 21.732MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_less-noinfer_1.smt2 |    0.046s | 19.872MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala5.smt2   |    0.047s | 21.72MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns12.smt2                     |    0.047s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/False_Test2-noinfer.smt2        |    0.047s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858852.smt2 |    0.048s | 20.824MiB| sat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858765.smt2 |    0.048s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2  |    0.048s | 21.748MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858843.smt2 |    0.050s | 20.928MiB| sat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2   |    0.050s | 21.688MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns7.smt2                      |    0.050s | 20.46MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns2.smt2                      |    0.050s | 20.264MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns10.smt2                     |    0.050s | 21.068MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/equiv3_M-infer_e-vc_local.smt2  |    0.050s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_R-vc_nested.smt2 |    0.050s | 19.52MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns1.smt2                      |    0.051s | 20.496MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer.smt2 |    0.051s | 19.832MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Q1-noinfer.smt2          |    0.051s | 20.26MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala9.smt2   |    0.052s | 20.596MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns9.smt2                      |    0.052s | 21.332MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns13.smt2                     |    0.053s | 21.128MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala3.smt2   |    0.054s | 20.704MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns5.smt2                      |    0.054s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala4.smt2   |    0.055s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns0.smt2                      |    0.055s | 20.384MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_LESS-noinfer_3.smt2 |    0.055s | 20.432MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_P1-noinfer.smt2          |    0.056s | 20.656MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_or-noinfer.smt2     |    0.056s | 20.428MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2  |    0.078s | 21.94MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/NestedVC_Q-vc_nested.smt2       |   20.028s | 225.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_2.smt2 |   20.035s | 230.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_3.smt2 |   20.043s | 228.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_Foo-noinfer.smt2           |   20.054s | 229.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.697341.smt2 |   20.291s | 2834.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.683530.smt2 |   20.312s | 2761.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.962381.smt2 |   20.380s | 4087.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976791.smt2 |   20.408s | 4089.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.968906.smt2 |   20.438s | 4049.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976292.smt2 |   20.495s | 4085.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/Fundamental_Theorem_Algebra/smtlib.1308248.smt2 |   20.586s | 5106.0MiB| timeout | 0 |  |  |
