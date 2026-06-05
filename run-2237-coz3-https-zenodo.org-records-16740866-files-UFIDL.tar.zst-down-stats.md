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
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 30c74fccee4d195424588e28574ecaf0f9335f2c
Z3 branch: 30c74fccee4d195424588e28574ecaf0f9335f2c
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFIDL.tar.zst?download=1
Z3 commit message: Go bindings: extract CGo slice-conversion helpers to eliminate boilerplate (#9465)

* Initial plan

* simplify Go bindings: extract CGo slice conversion helpers in z3.go

Agent-Logs-Url: https://github.com/Z3Prover/z3/sessions/eb6e05d8-f45a-40fb-b61f-17d4058bccb6

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFIDL/boogie/Passification_Loop-noinfer.smt2 |    0.012s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Skip0-noinfer.smt2       |    0.013s | 18.984MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/False_Test1-noinfer.smt2        |    0.013s | 18.984MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_P-vc_nested.smt2 |    0.014s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/loop0_M-infer_e-vc_local.smt2   |    0.014s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer.smt2 |    0.015s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858843.smt2 |    0.016s | 20.28MiB| sat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns2.smt2                      |    0.016s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns4.smt2                      |    0.017s | 20.288MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns3.smt2                      |    0.017s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/AssumeEnsures_Caller0-noinfer.smt2 |    0.017s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns5.smt2                      |    0.018s | 19.72MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns10.smt2                     |    0.018s | 20.388MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/heapsucc0_M-infer_eh-vc_local.smt2 |    0.018s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala10.smt2  |    0.019s | 20.072MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_or-noinfer.smt2     |    0.019s | 19.708MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_R-vc_nested.smt2 |    0.019s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/NestedVC_P-vc_nested.smt2       |    0.019s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala9.smt2   |    0.020s | 20.056MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_P1-noinfer.smt2          |    0.020s | 19.792MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_1.smt2 |    0.020s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala4.smt2   |    0.021s | 20.092MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns11.smt2                     |    0.021s | 19.912MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Skip1-noinfer.smt2       |    0.021s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Passification_UnreachableBlock-noinfer.smt2 |    0.022s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_Q-vc_nested.smt2 |    0.023s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/heapsucc1_M-infer_eh-vc_local.smt2 |    0.023s | 18.928MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858929.smt2 |    0.024s | 19.66MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns7.smt2                      |    0.024s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns0.smt2                      |    0.024s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/equiv2_M-infer_e-vc_local.smt2  |    0.024s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala13.smt2  |    0.025s | 20.788MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Old_SwapElems-noinfer.smt2      |    0.026s | 19.868MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_LESS-noinfer_3.smt2 |    0.027s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_less-noinfer_2.smt2 |    0.027s | 19.548MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/equiv3_M-infer_e-vc_local.smt2  |    0.028s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.675311.smt2 |    0.029s | 19.536MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858852.smt2 |    0.030s | 20.22MiB| sat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala0.smt2   |    0.031s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/False_Test2-noinfer.smt2        |    0.031s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Q1-noinfer.smt2          |    0.031s | 19.668MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_less-noinfer_1.smt2 |    0.031s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858765.smt2 |    0.032s | 19.732MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns12.smt2                     |    0.032s | 19.872MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns8.smt2                      |    0.032s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns13.smt2                     |    0.032s | 20.492MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns1.smt2                      |    0.033s | 19.716MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns6.smt2                      |    0.033s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns9.smt2                      |    0.033s | 20.568MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala3.smt2   |    0.034s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala8.smt2   |    0.038s | 21.196MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2   |    0.046s | 21.296MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala5.smt2   |    0.046s | 21.208MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala7.smt2   |    0.047s | 21.124MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala6.smt2   |    0.050s | 20.78MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2  |    0.057s | 21.072MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2  |    0.061s | 21.544MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_Foo-noinfer.smt2           |   20.016s | 228.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_3.smt2 |   20.018s | 227.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/boogie/NestedVC_Q-vc_nested.smt2       |   20.020s | 225.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_2.smt2 |   20.026s | 229.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.683530.smt2 |   20.238s | 2760.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.697341.smt2 |   20.268s | 2919.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.968906.smt2 |   20.315s | 4048.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.962381.smt2 |   20.328s | 4086.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976292.smt2 |   20.334s | 3864.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976791.smt2 |   20.335s | 3859.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/Fundamental_Theorem_Algebra/smtlib.1308248.smt2 |   20.402s | 4789.0MiB| timeout | 0 |  |  |
