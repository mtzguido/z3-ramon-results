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
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 30c74fccee4d195424588e28574ecaf0f9335f2c
Z3 branch: 30c74fccee4d195424588e28574ecaf0f9335f2c
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFLRA.tar.zst?download=1
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
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                 |    0.013s | 19.544MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                 |    0.013s | 19.552MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                 |    0.013s | 20.064MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                 |    0.014s | 19.448MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                 |    0.014s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                 |    0.014s | 19.536MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                 |    0.014s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                 |    0.014s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                 |    0.014s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                 |    0.015s | 20.268MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/misc/set16.smt2                        |    1.785s | 32.372MiB| sat | 0 |  |  |
|non-incremental/UFLRA/misc/set9.smt2                         |    3.221s | 40.016MiB| sat | 0 |  |  |
|non-incremental/UFLRA/misc/list2.smt2                        |   20.019s | 236.0MiB| timeout | 0 |  |  |
|non-incremental/UFLRA/misc/set19.smt2                        |   20.039s | 132.0MiB| timeout | 0 |  |  |
|non-incremental/UFLRA/misc/set14.smt2                        |   20.040s | 125.0MiB| timeout | 0 |  |  |
