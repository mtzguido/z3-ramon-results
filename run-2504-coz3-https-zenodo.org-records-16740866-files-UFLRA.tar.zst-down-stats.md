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
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFLRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFLRA.tar.zst-down
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFLRA.tar.zst?download=1
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
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                 |    0.013s | 19.588MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                 |    0.013s | 19.82MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                 |    0.014s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                 |    0.015s | 20.312MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                 |    0.015s | 19.524MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                 |    0.015s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                 |    0.015s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                 |    0.016s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                 |    0.016s | 20.008MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                 |    0.016s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/misc/set9.smt2                         |    3.891s | 40.908MiB| sat | 0 |  |  |
|non-incremental/UFLRA/misc/set16.smt2                        |    5.989s | 45.904MiB| sat | 0 |  |  |
|non-incremental/UFLRA/misc/list2.smt2                        |   20.020s | 247.0MiB| timeout | 0 |  |  |
|non-incremental/UFLRA/misc/set14.smt2                        |   20.037s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/UFLRA/misc/set19.smt2                        |   20.038s | 138.0MiB| timeout | 0 |  |  |
