# .

* SAT 5
* UNSAT 0
* TIMEOUT 39
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-atom_candidates
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: cea3155f42fe2ffe6f9a934176262a783e8fcf11
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: bb candidates are atoms, not literals, since we currently test both polarities in parallel.
batch mode retry terminates if we made zero progress after a retry round to avoid resource stress
fix bug about bb ranking being backwards for how we process them

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|scrambled125827.smt2                                         |  103.871s | 1009.0MiB| sat | 0 |  |  |
|scrambled125888.smt2                                         |  163.959s | 1628.0MiB| sat | 0 |  |  |
|scrambled118793.smt2                                         |  199.582s | 977.0MiB| sat | 0 |  |  |
|scrambled25238.smt2                                          |  205.640s | 5855.0MiB| sat | 0 |  |  |
|scrambled20101.smt2                                          |  322.346s | 1720.0MiB| sat | 0 |  |  |
|scrambled3854.smt2                                           | 1200.015s | 42.632MiB| timeout | 0 |  |  |
|scrambled45952.smt2                                          | 1200.015s | 41.516MiB| timeout | 0 |  |  |
|scrambled65181.smt2                                          | 1200.034s | 42.292MiB| timeout | 0 |  |  |
|scrambled59713.smt2                                          | 1200.034s | 41.816MiB| timeout | 0 |  |  |
|scrambled103783.smt2                                         | 1200.035s | 43.032MiB| timeout | 0 |  |  |
|scrambled39514.smt2                                          | 1200.036s | 74.732MiB| timeout | 0 |  |  |
|scrambled79867.smt2                                          | 1200.037s | 41.796MiB| timeout | 0 |  |  |
|scrambled79766.smt2                                          | 1200.042s | 42.564MiB| timeout | 0 |  |  |
|scrambled1417.smt2                                           | 1200.086s | 379.0MiB| timeout | 0 |  |  |
|scrambled95803.smt2                                          | 1200.313s | 2606.0MiB| timeout | 0 |  |  |
|scrambled32836.smt2                                          | 1200.376s | 2681.0MiB| timeout | 0 |  |  |
|scrambled51053.smt2                                          | 1200.399s | 2917.0MiB| timeout | 0 |  |  |
|scrambled128732.smt2                                         | 1200.571s | 5224.0MiB| timeout | 0 |  |  |
|scrambled128128.smt2                                         | 1200.600s | 6541.0MiB| timeout | 0 |  |  |
|scrambled128874.smt2                                         | 1200.645s | 5179.0MiB| timeout | 0 |  |  |
|scrambled55777.smt2                                          | 1200.696s | 4595.0MiB| timeout | 0 |  |  |
|scrambled131241.smt2                                         | 1200.721s | 6451.0MiB| timeout | 0 |  |  |
|scrambled7741.smt2                                           | 1200.793s | 6833.0MiB| timeout | 0 |  |  |
|scrambled44911.smt2                                          | 1200.931s | 5031.0MiB| timeout | 0 |  |  |
|scrambled119331.smt2                                         | 1200.956s | 9452.0MiB| timeout | 0 |  |  |
|scrambled72668.smt2                                          | 1200.968s | 5318.0MiB| timeout | 0 |  |  |
|scrambled40621.smt2                                          | 1201.070s | 10.791GiB| timeout | 0 |  |  |
|scrambled61922.smt2                                          | 1201.559s | 10.797GiB| timeout | 0 |  |  |
|scrambled107115.smt2                                         | 1201.732s | 17.782GiB| timeout | 0 |  |  |
|scrambled27843.smt2                                          | 1202.175s | 20.922GiB| timeout | 0 |  |  |
|scrambled107826.smt2                                         | 1202.511s | 27.945GiB| timeout | 0 |  |  |
|scrambled75189.smt2                                          | 1202.883s | 31.699GiB| timeout | 0 |  |  |
|scrambled43577.smt2                                          | 1203.353s | 34.249GiB| timeout | 0 |  |  |
|scrambled111627.smt2                                         | 1203.708s | 37.745GiB| timeout | 0 |  |  |
|scrambled108840.smt2                                         | 1203.736s | 43.1GiB| timeout | 0 |  |  |
|scrambled19335.smt2                                          | 1203.924s | 32.359GiB| timeout | 0 |  |  |
|scrambled79760.smt2                                          | 1203.963s | 44.273GiB| timeout | 0 |  |  |
|scrambled4198.smt2                                           | 1204.299s | 49.045GiB| timeout | 0 |  |  |
|scrambled102166.smt2                                         | 1204.360s | 48.154GiB| timeout | 0 |  |  |
|scrambled68944.smt2                                          | 1204.457s | 46.209GiB| timeout | 0 |  |  |
|scrambled55680.smt2                                          | 1204.493s | 50.677GiB| timeout | 0 |  |  |
|scrambled12042.smt2                                          | 1204.854s | 54.546GiB| timeout | 0 |  |  |
|scrambled4299.smt2                                           | 1204.905s | 56.698GiB| timeout | 0 |  |  |
|scrambled94658.smt2                                          | 1205.638s | 63.063GiB| timeout | 0 |  |  |
