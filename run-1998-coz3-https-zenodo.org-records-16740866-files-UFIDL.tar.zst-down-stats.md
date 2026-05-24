# .

* SAT 0
* UNSAT 19
* TIMEOUT 0
* UNKNOWN 49

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFIDL.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFIDL.tar.zst-down
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 459629c662eb7abf25a010b7383431a9f729d234
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFIDL.tar.zst?download=1
Z3 commit message: bugfixes to ho_matcher

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFIDL/boogie/equiv2_M-infer_e-vc_local.smt2  |    0.021s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns3.smt2                      |    0.022s | 19.844MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_R-vc_nested.smt2 |    0.022s | 20.236MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_Foo-noinfer.smt2           |    0.022s | 19.86MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2   |    0.023s | 19.632MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala4.smt2   |    0.023s | 19.848MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/Burns/burns12.smt2                     |    0.023s | 19.592MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/Burns/burns1.smt2                      |    0.023s | 19.648MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/Burns/burns11.smt2                     |    0.023s | 19.876MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/Burns/burns4.smt2                      |    0.023s | 19.652MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/boogie/heapsucc0_M-infer_eh-vc_local.smt2 |    0.023s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Passification_UnreachableBlock-noinfer.smt2 |    0.023s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala7.smt2   |    0.024s | 19.596MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/Burns/burns6.smt2                      |    0.024s | 19.6MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/Burns/burns10.smt2                     |    0.024s | 19.6MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_P-vc_nested.smt2 |    0.024s | 20.324MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_or-noinfer.smt2     |    0.024s | 20.048MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_less-noinfer_1.smt2 |    0.024s | 19.616MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/Fundamental_Theorem_Algebra/smtlib.1308248.smt2 |    0.025s | 19.852MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/boogie/NestedVC_Q-vc_nested.smt2       |    0.025s | 19.776MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala5.smt2   |    0.026s | 19.848MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala10.smt2  |    0.028s | 19.86MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858765.smt2 |    0.029s | 19.704MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala9.smt2   |    0.030s | 19.816MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858852.smt2 |    0.032s | 19.628MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala3.smt2   |    0.034s | 19.764MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.675311.smt2 |    0.037s | 20.088MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.968906.smt2 |    0.050s | 20.596MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_LESS-noinfer_3.smt2 |    0.056s | 19.868MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858843.smt2 |    0.057s | 19.604MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2  |    0.057s | 19.704MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/Burns/burns5.smt2                      |    0.057s | 19.856MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/boogie/equiv3_M-infer_e-vc_local.smt2  |    0.057s | 20.024MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer.smt2 |    0.057s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/AssumeEnsures_Caller0-noinfer.smt2 |    0.057s | 19.588MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/heapsucc1_M-infer_eh-vc_local.smt2 |    0.057s | 19.984MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns9.smt2                      |    0.058s | 19.624MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_Q-vc_nested.smt2 |    0.058s | 19.832MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/NestedVC_P-vc_nested.smt2       |    0.058s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns0.smt2                      |    0.059s | 19.876MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_P1-noinfer.smt2          |    0.060s | 19.636MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858929.smt2 |    0.061s | 19.92MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala0.smt2   |    0.061s | 19.62MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/Burns/burns7.smt2                      |    0.061s | 19.612MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/Burns/burns13.smt2                     |    0.061s | 19.588MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Skip0-noinfer.smt2       |    0.061s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/False_Test2-noinfer.smt2        |    0.061s | 19.868MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Passification_Loop-noinfer.smt2 |    0.061s | 19.936MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_2.smt2 |    0.061s | 19.636MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_3.smt2 |    0.061s | 19.676MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/boogie/False_Test1-noinfer.smt2        |    0.061s | 19.632MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Q1-noinfer.smt2          |    0.061s | 19.876MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_less-noinfer_2.smt2 |    0.061s | 19.636MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976791.smt2 |    0.062s | 19.664MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala6.smt2   |    0.062s | 19.612MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2  |    0.062s | 19.592MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala8.smt2   |    0.062s | 19.808MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala13.smt2  |    0.062s | 19.9MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/Burns/burns2.smt2                      |    0.062s | 20.124MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/Burns/burns8.smt2                      |    0.062s | 19.668MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/boogie/Old_SwapElems-noinfer.smt2      |    0.062s | 19.9MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_1.smt2 |    0.062s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976292.smt2 |    0.063s | 19.904MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/boogie/loop0_M-infer_e-vc_local.smt2   |    0.063s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Skip1-noinfer.smt2       |    0.065s | 19.86MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.962381.smt2 |    0.075s | 20.412MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.697341.smt2 |    0.077s | 20.712MiB| unknown | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.683530.smt2 |    0.079s | 20.76MiB| unknown | 0 |  |  |
