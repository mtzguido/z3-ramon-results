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
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFIDL.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFIDL.tar.zst-down
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFIDL.tar.zst?download=1
Z3 commit message: Fix instance of "flexible array member". (#9883)

This is another PR towards the goal of getting a clean build with clang,
using the compiler options used in building clang-tidy.

In https://github.com/Z3Prover/z3/pull/9800, we changed the build flags
to eliminate a warning for zero-length arrays. In that PR, I missed this
one: there was one instance of m_arr[] instead of m_arr[0]. In the
clang-tidy build, that gives warnings like:
```
/Users/daviddetlefs/llvm-project/build_dbg/_deps/z3-src/src/model/func_interp.h:43:12: warning: flexible array members are a C99 feature [-Wc99-extensions]
```

The PR fixes this, making it a zero-length array, the idiom used in all
the other similar cases. I also added the compiler flag that produced
this warning, so we can notice such changes in the future.

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFIDL/boogie/False_Test1-noinfer.smt2        |    0.012s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/equiv3_M-infer_e-vc_local.smt2  |    0.013s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Skip0-noinfer.smt2       |    0.013s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns2.smt2                      |    0.014s | 19.952MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer.smt2 |    0.014s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/False_Test2-noinfer.smt2        |    0.014s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/loop0_M-infer_e-vc_local.smt2   |    0.014s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns4.smt2                      |    0.015s | 20.308MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns10.smt2                     |    0.016s | 20.404MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_P1-noinfer.smt2          |    0.017s | 19.704MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala10.smt2  |    0.018s | 20.06MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_Q-vc_nested.smt2 |    0.018s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala9.smt2   |    0.020s | 20.14MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Skip1-noinfer.smt2       |    0.020s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_1.smt2 |    0.020s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns13.smt2                     |    0.023s | 20.476MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/AssumeEnsures_Caller0-noinfer.smt2 |    0.024s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Passification_Loop-noinfer.smt2 |    0.025s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_less-noinfer_2.smt2 |    0.025s | 19.496MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/NestedVC_P-vc_nested.smt2       |    0.025s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/heapsucc1_M-infer_eh-vc_local.smt2 |    0.026s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.675311.smt2 |    0.027s | 19.556MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_P-vc_nested.smt2 |    0.028s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_R-vc_nested.smt2 |    0.028s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858765.smt2 |    0.029s | 19.624MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala3.smt2   |    0.029s | 20.044MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns7.smt2                      |    0.029s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/equiv2_M-infer_e-vc_local.smt2  |    0.029s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns1.smt2                      |    0.030s | 19.732MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala4.smt2   |    0.031s | 20.016MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala0.smt2   |    0.031s | 20.044MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns6.smt2                      |    0.031s | 20.536MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858852.smt2 |    0.032s | 20.264MiB| sat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns8.smt2                      |    0.033s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns9.smt2                      |    0.033s | 20.392MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/heapsucc0_M-infer_eh-vc_local.smt2 |    0.033s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Passification_UnreachableBlock-noinfer.smt2 |    0.033s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns3.smt2                      |    0.034s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala13.smt2  |    0.035s | 20.828MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns0.smt2                      |    0.035s | 19.724MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_less-noinfer_1.smt2 |    0.035s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858843.smt2 |    0.037s | 20.256MiB| sat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_or-noinfer.smt2     |    0.037s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858929.smt2 |    0.038s | 19.528MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Q1-noinfer.smt2          |    0.038s | 19.832MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns12.smt2                     |    0.039s | 19.72MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns5.smt2                      |    0.039s | 19.78MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_LESS-noinfer_3.smt2 |    0.039s | 19.792MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Old_SwapElems-noinfer.smt2      |    0.040s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns11.smt2                     |    0.041s | 19.704MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala6.smt2   |    0.045s | 20.868MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala7.smt2   |    0.047s | 20.952MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala8.smt2   |    0.048s | 21.172MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala5.smt2   |    0.048s | 21.072MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2  |    0.050s | 21.188MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2  |    0.058s | 21.424MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2   |    0.061s | 21.188MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_Foo-noinfer.smt2           |   20.018s | 228.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_2.smt2 |   20.026s | 229.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_3.smt2 |   20.038s | 227.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/boogie/NestedVC_Q-vc_nested.smt2       |   20.039s | 225.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.683530.smt2 |   20.278s | 2703.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.697341.smt2 |   20.299s | 2829.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.968906.smt2 |   20.370s | 4027.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.962381.smt2 |   20.379s | 4065.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976292.smt2 |   20.385s | 3858.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/Fundamental_Theorem_Algebra/smtlib.1308248.smt2 |   20.392s | 3796.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976791.smt2 |   20.396s | 3871.0MiB| timeout | 0 |  |  |
