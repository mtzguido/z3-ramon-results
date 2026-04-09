# .

* SAT 97
* UNSAT 80
* TIMEOUT 78
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfrdl-sequential
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 477a1d817da44f7615fa53a10b4bd03d2cc84e48
Z3 branch: master
Z3 options: "-T:60 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/QF_RDL
Z3 commit message: Add mod-factor-propagation lemma to NLA divisions solver (#9235)

When a monic x*y has a factor x with mod(x, p) = 0 (fixed), propagate
mod(x*y, p) = 0. This enables Z3 to prove divisibility properties like
x mod p = 0 => (x*y) mod p = 0, which previously timed out even for
p = 2. The lemma fires in the NLA divisions check and allows Gröbner
basis and LIA to subsequently derive distributivity of div over addition.

Extends division tuples from (q, x, y) to (q, x, y, r) to track the
mod lpvar. Also registers bounded divisions from the mod internalization
path in theory_lra, not just the idiv path.

Co-authored-by: Claude Opus 4.6 (1M context) <noreply@anthropic.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|check/bignum_rdl2.smt2                                       |    0.024s | 19.668MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-2.smt2                                    |    0.025s | 20.688MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-4.smt2                                    |    0.028s | 20.968MiB| unsat | 0 |  |  |
|sal/fischer6-mutex-2.smt2                                    |    0.031s | 20.78MiB| unsat | 0 |  |  |
|sal/fischer6-mutex-1.smt2                                    |    0.032s | 20.18MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-1.smt2                                    |    0.032s | 20.376MiB| unsat | 0 |  |  |
|sal/fischer6-mutex-3.smt2                                    |    0.033s | 21.24MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-03.smt2       |    0.037s | 21.424MiB| sat | 0 |  |  |
|sal/fischer3-mutex-5.smt2                                    |    0.040s | 21.456MiB| unsat | 0 |  |  |
|check/bignum_rdl1.smt2                                       |    0.041s | 19.764MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2              |    0.044s | 22.744MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2              |    0.049s | 23.588MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2              |    0.054s | 21.224MiB| sat | 0 |  |  |
|sal/fischer6-mutex-5.smt2                                    |    0.054s | 22.232MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-3.smt2                                    |    0.054s | 20.592MiB| unsat | 0 |  |  |
|sal/fischer9-mutex-1.smt2                                    |    0.055s | 20.648MiB| unsat | 0 |  |  |
|sal/fischer9-mutex-4.smt2                                    |    0.055s | 22.764MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-width-1.smt2          |    0.058s | 19.944MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-matrix1x1.pddl.smt2   |    0.058s | 20.184MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2              |    0.063s | 20.816MiB| sat | 0 |  |  |
|sal/fischer9-mutex-2.smt2                                    |    0.064s | 21.216MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-7.smt2                                    |    0.065s | 21.9MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-6.smt2                                    |    0.066s | 21.46MiB| unsat | 0 |  |  |
|sal/fischer9-mutex-3.smt2                                    |    0.066s | 21.972MiB| unsat | 0 |  |  |
|sal/fischer6-mutex-4.smt2                                    |    0.067s | 21.972MiB| unsat | 0 |  |  |
|scheduling/abz6_800.smt2                                     |    0.068s | 23.512MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2              |    0.068s | 22.388MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-06.smt2       |    0.068s | 22.44MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-width-2.smt2          |    0.070s | 21.988MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-04.smt2       |    0.070s | 21.72MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2              |    0.073s | 22.444MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2              |    0.075s | 22.696MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-05.smt2       |    0.078s | 22.332MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2              |    0.082s | 24.748MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2              |    0.083s | 23.828MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-09.smt2       |    0.087s | 23.852MiB| sat | 0 |  |  |
|sal/fischer6-mutex-6.smt2                                    |    0.088s | 23.288MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2              |    0.094s | 25.564MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2              |    0.097s | 26.832MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2              |    0.097s | 25.692MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2              |    0.099s | 26.072MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking21.smt2              |    0.105s | 27.344MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking22.smt2              |    0.107s | 27.316MiB| sat | 0 |  |  |
|sal/fischer9-mutex-5.smt2                                    |    0.107s | 24.084MiB| unsat | 0 |  |  |
|sal/fischer9-mutex-6.smt2                                    |    0.109s | 25.132MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2              |    0.113s | 24.112MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2              |    0.114s | 25.22MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2              |    0.114s | 26.796MiB| sat | 0 |  |  |
|scheduling/orb08_700.smt2                                    |    0.115s | 24.792MiB| unsat | 0 |  |  |
|scheduling/orb07_250.smt2                                    |    0.117s | 23.0MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-width-3.smt2          |    0.117s | 26.876MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2              |    0.118s | 20.952MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-20.smt2       |    0.119s | 27.9MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-depth-2.smt2          |    0.121s | 21.46MiB| sat | 0 |  |  |
|scheduling/orb07_330.smt2                                    |    0.123s | 23.512MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2              |    0.125s | 21.732MiB| sat | 0 |  |  |
|scheduling/orb07_550.smt2                                    |    0.126s | 25.556MiB| sat | 0 |  |  |
|sal/fischer3-mutex-8.smt2                                    |    0.126s | 22.692MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2              |    0.127s | 23.252MiB| sat | 0 |  |  |
|scheduling/orb02_700.smt2                                    |    0.131s | 23.376MiB| unsat | 0 |  |  |
|scheduling/orb04_850.smt2                                    |    0.133s | 24.276MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-depth-3.smt2          |    0.133s | 24.816MiB| sat | 0 |  |  |
|scheduling/orb05_700.smt2                                    |    0.138s | 24.28MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-07.smt2       |    0.140s | 23.092MiB| sat | 0 |  |  |
|scheduling/orb10_800.smt2                                    |    0.141s | 24.384MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-08.smt2       |    0.141s | 23.348MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2              |    0.143s | 24.62MiB| sat | 0 |  |  |
|scheduling/abz5_1000.smt2                                    |    0.144s | 24.296MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-10.smt2       |    0.151s | 24.112MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-depth-4.smt2          |    0.154s | 31.576MiB| sat | 0 |  |  |
|sal/fischer6-mutex-7.smt2                                    |    0.172s | 23.876MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-40.smt2       |    0.180s | 35.208MiB| sat | 0 |  |  |
|scheduling/orb09_800.smt2                                    |    0.181s | 24.788MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-30.smt2       |    0.199s | 31.54MiB| sat | 0 |  |  |
|scheduling/orb04_1200.smt2                                   |    0.208s | 25.784MiB| sat | 0 |  |  |
|sal/fischer3-mutex-9.smt2                                    |    0.231s | 22.74MiB| unsat | 0 |  |  |
|scheduling/abz5_1400.smt2                                    |    0.233s | 26.04MiB| sat | 0 |  |  |
|scheduling/orb02_800.smt2                                    |    0.245s | 25.044MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-depth-5.smt2          |    0.293s | 42.204MiB| sat | 0 |  |  |
|scheduling/abz6_1100.smt2                                    |    0.308s | 25.808MiB| sat | 0 |  |  |
|sal/fischer9-mutex-7.smt2                                    |    0.316s | 26.544MiB| unsat | 0 |  |  |
|scheduling/orb03_850.smt2                                    |    0.318s | 25.036MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-60.smt2       |    0.324s | 43.136MiB| sat | 0 |  |  |
|scheduling/orb02_1000.smt2                                   |    0.333s | 26.056MiB| sat | 0 |  |  |
|scheduling/orb05_1000.smt2                                   |    0.338s | 26.068MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-70.smt2       |    0.358s | 54.776MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-width-4.smt2          |    0.371s | 47.928MiB| sat | 0 |  |  |
|sal/fischer6-mutex-8.smt2                                    |    0.414s | 24.896MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-80.smt2       |    0.423s | 57.72MiB| sat | 0 |  |  |
|scheduling/abz6_900.smt2                                     |    0.450s | 25.556MiB| unsat | 0 |  |  |
|scheduling/abz6_1000.smt2                                    |    0.472s | 26.052MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-90.smt2       |    0.477s | 62.072MiB| sat | 0 |  |  |
|scheduling/orb05_800.smt2                                    |    0.535s | 25.296MiB| unsat | 0 |  |  |
|scheduling/orb10_1100.smt2                                   |    0.538s | 26.072MiB| sat | 0 |  |  |
|sal/fischer3-mutex-10.smt2                                   |    0.548s | 23.252MiB| unsat | 0 |  |  |
|scheduling/orb09_1100.smt2                                   |    0.636s | 26.588MiB| sat | 0 |  |  |
|scheduling/orb06_900.smt2                                    |    0.651s | 25.56MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-depth-6.smt2          |    0.663s | 67.672MiB| sat | 0 |  |  |
|scheduling/orb01_900.smt2                                    |    0.686s | 25.296MiB| unsat | 0 |  |  |
|scheduling/orb04_950.smt2                                    |    0.705s | 25.532MiB| unsat | 0 |  |  |
|scheduling/abz5_1300.smt2                                    |    0.770s | 26.324MiB| sat | 0 |  |  |
|scheduling/orb07_430.smt2                                    |    0.808s | 26.324MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-width-5.smt2          |    0.900s | 92.888MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-5.base.cvc.smt2                           |    0.939s | 66.624MiB| unsat | 0 |  |  |
|sal/fischer9-mutex-8.smt2                                    |    1.018s | 28.52MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-depth-7.smt2          |    1.113s | 107.0MiB| sat | 0 |  |  |
|scheduling/orb02_900.smt2                                    |    1.207s | 26.556MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-5.induction.cvc.smt2                      |    1.238s | 86.764MiB| sat | 0 |  |  |
|scheduling/yn3_750.smt2                                      |    1.321s | 67.16MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-11.smt2                                   |    1.345s | 24.116MiB| unsat | 0 |  |  |
|scheduling/yn1_750.smt2                                      |    1.364s | 66.128MiB| unsat | 0 |  |  |
|scheduling/orb10_900.smt2                                    |    1.391s | 25.704MiB| unsat | 0 |  |  |
|scheduling/orb06_1200.smt2                                   |    1.411s | 27.096MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-matrix2x2.pddl.smt2   |    1.510s | 156.0MiB| sat | 0 |  |  |
|scheduling/orb09_1000.smt2                                   |    1.534s | 26.584MiB| sat | 0 |  |  |
|skdmxa/skdmxa-3x3-5.smt2                                     |    1.610s | 45.188MiB| unsat | 0 |  |  |
|scheduling/yn2_750.smt2                                      |    1.716s | 67.672MiB| unsat | 0 |  |  |
|scheduling/orb03_1200.smt2                                   |    1.864s | 27.092MiB| sat | 0 |  |  |
|scheduling/orb08_830.smt2                                    |    2.051s | 26.328MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-12.smt2                                   |    2.264s | 24.584MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-6.base.cvc.smt2                           |    2.355s | 94.348MiB| unsat | 0 |  |  |
|scheduling/abz6_943.smt2                                     |    2.416s | 26.584MiB| sat | 0 |  |  |
|sal/fischer6-mutex-9.smt2                                    |    2.508s | 27.184MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-width-6.smt2          |    2.564s | 176.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-6.induction.cvc.smt2                      |    2.569s | 95.684MiB| sat | 0 |  |  |
|scheduling/abz7_500.smt2                                     |    2.689s | 53.184MiB| unsat | 0 |  |  |
|scheduling/orb01_1200.smt2                                   |    2.709s | 27.244MiB| sat | 0 |  |  |
|sal/fischer3-mutex-13.smt2                                   |    2.965s | 25.392MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-14.smt2                                   |    3.110s | 25.788MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-15.smt2                                   |    3.442s | 26.756MiB| unsat | 0 |  |  |
|scheduling/orb04_1100.smt2                                   |    3.514s | 27.38MiB| sat | 0 |  |  |
|sal/fischer3-mutex-16.smt2                                   |    3.896s | 26.852MiB| unsat | 0 |  |  |
|scheduling/orb10_1000.smt2                                   |    4.184s | 27.096MiB| sat | 0 |  |  |
|scheduling/orb09_900.smt2                                    |    4.194s | 26.788MiB| unsat | 0 |  |  |
|scheduling/orb02_888.smt2                                    |    4.797s | 27.0MiB| sat | 0 |  |  |
|scheduling/orb08_1000.smt2                                   |    5.002s | 27.86MiB| sat | 0 |  |  |
|scheduling/abz5_1200.smt2                                    |    5.049s | 26.328MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-9.induction.cvc.smt2                      |    5.134s | 177.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-10.induction.cvc.smt2                     |    5.460s | 182.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-7.induction.cvc.smt2                      |    5.773s | 115.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-8.base.cvc.smt2                           |    6.370s | 123.0MiB| unsat | 0 |  |  |
|scheduling/orb07_397.smt2                                    |    6.834s | 27.08MiB| sat | 0 |  |  |
|scheduling/orb03_1100.smt2                                   |    7.358s | 28.12MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-7.base.cvc.smt2                           |    7.439s | 109.0MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-8.induction.cvc.smt2                      |    7.629s | 126.0MiB| sat | 0 |  |  |
|sal/fischer3-mutex-18.smt2                                   |    8.029s | 28.188MiB| unsat | 0 |  |  |
|scheduling/abz5_1234.smt2                                    |    8.355s | 27.616MiB| sat | 0 |  |  |
|sal/fischer3-mutex-17.smt2                                   |    8.507s | 27.984MiB| unsat | 0 |  |  |
|sal/fischer6-mutex-10.smt2                                   |    8.741s | 28.848MiB| unsat | 0 |  |  |
|sal/fischer9-mutex-9.smt2                                    |    8.805s | 32.42MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-11.induction.cvc.smt2                     |    8.977s | 188.0MiB| sat | 0 |  |  |
|scheduling/orb03_950.smt2                                    |   10.448s | 27.864MiB| unsat | 0 |  |  |
|scheduling/orb05_900.smt2                                    |   11.001s | 28.296MiB| sat | 0 |  |  |
|scheduling/orb08_930.smt2                                    |   13.004s | 29.088MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-9.base.cvc.smt2                           |   13.618s | 145.0MiB| unsat | 0 |  |  |
|scheduling/orb06_1100.smt2                                   |   13.655s | 28.632MiB| sat | 0 |  |  |
|scheduling/orb10_944.smt2                                    |   14.095s | 28.536MiB| sat | 0 |  |  |
|skdmxa/skdmxa-3x3-10.smt2                                    |   14.622s | 88.008MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-19.smt2                                   |   15.595s | 29.668MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                     |   15.867s | 236.0MiB| sat | 0 |  |  |
|sal/fischer6-mutex-11.smt2                                   |   16.009s | 31.4MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-10.base.cvc.smt2                          |   16.433s | 198.0MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-12.induction.cvc.smt2                     |   17.314s | 210.0MiB| sat | 0 |  |  |
|scheduling/orb08_888.smt2                                    |   18.491s | 28.756MiB| unsat | 0 |  |  |
|scheduling/orb09_934.smt2                                    |   18.996s | 29.496MiB| sat | 0 |  |  |
|scheduling/orb05_887.smt2                                    |   19.633s | 28.632MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-13.induction.cvc.smt2                     |   20.795s | 267.0MiB| sat | 0 |  |  |
|scheduling/orb04_1005.smt2                                   |   20.917s | 29.052MiB| sat | 0 |  |  |
|sal/fischer3-mutex-20.smt2                                   |   27.549s | 30.228MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-11.base.cvc.smt2                          |   38.967s | 228.0MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                     |   43.763s | 334.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                     |   45.723s | 375.0MiB| sat | 0 |  |  |
|scheduling/orb01_1000.smt2                                   |   45.794s | 30.852MiB| unsat | 0 |  |  |
|scheduling/orb01_1100.smt2                                   |   47.294s | 31.188MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                     |   51.768s | 394.0MiB| sat | 0 |  |  |
|sal/fischer9-mutex-10.smt2                                   |   52.238s | 38.116MiB| unsat | 0 |  |  |
|sal/fischer6-mutex-12.smt2                                   |   59.848s | 34.832MiB| unsat | 0 |  |  |
|sal/fischer6-mutex-17.smt2                                   |   60.011s | 40.652MiB| timeout | 0 |  |  |
|scheduling/orb06_1010.smt2                                   |   60.012s | 32.172MiB| timeout | 0 |  |  |
|sal/fischer6-mutex-19.smt2                                   |   60.012s | 43.3MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-12.smt2                                   |   60.013s | 42.14MiB| timeout | 0 |  |  |
|sal/fischer6-mutex-18.smt2                                   |   60.014s | 42.632MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-18.smt2                                   |   60.016s | 60.18MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-17.smt2                                   |   60.016s | 55.852MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-11.smt2                                   |   60.016s | 39.708MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-15.smt2                                   |   60.016s | 52.94MiB| timeout | 0 |  |  |
|scheduling/abz7_800.smt2                                     |   60.018s | 93.164MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-13.smt2                                   |   60.018s | 46.676MiB| timeout | 0 |  |  |
|scheduling/yn4_850.smt2                                      |   60.031s | 87.384MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-14.smt2                                   |   60.032s | 49.82MiB| timeout | 0 |  |  |
|skdmxa/skdmxa-3x3-15.smt2                                    |   60.033s | 145.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-12.base.cvc.smt2                          |   60.033s | 241.0MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-19.smt2                                   |   60.034s | 61.972MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-20.smt2                                   |   60.034s | 66.472MiB| timeout | 0 |  |  |
|sal/fischer6-mutex-14.smt2                                   |   60.034s | 37.724MiB| timeout | 0 |  |  |
|sal/fischer6-mutex-16.smt2                                   |   60.037s | 40.188MiB| timeout | 0 |  |  |
|scheduling/yn3_894.smt2                                      |   60.038s | 103.0MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-16.smt2                                   |   60.038s | 54.916MiB| timeout | 0 |  |  |
|skdmxa/skdmxa-3x3-20.smt2                                    |   60.039s | 248.0MiB| timeout | 0 |  |  |
|sal/fischer6-mutex-15.smt2                                   |   60.040s | 38.664MiB| timeout | 0 |  |  |
|scheduling/swv13_3104.smt2                                   |   60.041s | 281.0MiB| timeout | 0 |  |  |
|sal/fischer6-mutex-13.smt2                                   |   60.041s | 36.324MiB| timeout | 0 |  |  |
|scheduling/yn1_827.smt2                                      |   60.042s | 95.28MiB| timeout | 0 |  |  |
|sal/fischer6-mutex-20.smt2                                   |   60.042s | 48.112MiB| timeout | 0 |  |  |
|scheduling/swv11_2900.smt2                                   |   60.046s | 279.0MiB| timeout | 0 |  |  |
|scheduling/swv12_2972.smt2                                   |   60.047s | 279.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                          |   60.047s | 302.0MiB| timeout | 0 |  |  |
|scheduling/swv11_2983.smt2                                   |   60.048s | 278.0MiB| timeout | 0 |  |  |
|scheduling/abz7_691.smt2                                     |   60.049s | 87.048MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                          |   60.049s | 347.0MiB| timeout | 0 |  |  |
|scheduling/swv13_3150.smt2                                   |   60.050s | 281.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                     |   60.052s | 326.0MiB| timeout | 0 |  |  |
|scheduling/yn4_1000.smt2                                     |   60.055s | 109.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                          |   60.057s | 413.0MiB| timeout | 0 |  |  |
|scheduling/swv12_3004.smt2                                   |   60.058s | 276.0MiB| timeout | 0 |  |  |
|scheduling/swv11_2992.smt2                                   |   60.058s | 274.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                     |   60.061s | 419.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                          |   60.063s | 506.0MiB| timeout | 0 |  |  |
|scheduling/swv14_2905.smt2                                   |   60.069s | 282.0MiB| timeout | 0 |  |  |
|scheduling/yn3_828.smt2                                      |   60.069s | 96.036MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                     |   60.070s | 409.0MiB| timeout | 0 |  |  |
|scheduling/swv14_3000.smt2                                   |   60.071s | 280.0MiB| timeout | 0 |  |  |
|scheduling/swv11_3050.smt2                                   |   60.071s | 272.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                          |   60.071s | 345.0MiB| timeout | 0 |  |  |
|scheduling/abz7_670.smt2                                     |   60.073s | 85.804MiB| timeout | 0 |  |  |
|scheduling/swv14_2800.smt2                                   |   60.074s | 279.0MiB| timeout | 0 |  |  |
|scheduling/yn2_950.smt2                                      |   60.079s | 111.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                          |   60.081s | 480.0MiB| timeout | 0 |  |  |
|scheduling/orb03_1005.smt2                                   |   60.082s | 32.788MiB| timeout | 0 |  |  |
|scheduling/abz7_667.smt2                                     |   60.084s | 86.632MiB| timeout | 0 |  |  |
|scheduling/swv12_2990.smt2                                   |   60.085s | 286.0MiB| timeout | 0 |  |  |
|scheduling/yn4_969.smt2                                      |   60.086s | 108.0MiB| timeout | 0 |  |  |
|scheduling/yn2_910.smt2                                      |   60.087s | 104.0MiB| timeout | 0 |  |  |
|scheduling/yn2_862.smt2                                      |   60.087s | 100.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                          |   60.087s | 628.0MiB| timeout | 0 |  |  |
|scheduling/yn1_850.smt2                                      |   60.092s | 97.992MiB| timeout | 0 |  |  |
|scheduling/abz7_600.smt2                                     |   60.093s | 78.108MiB| timeout | 0 |  |  |
|scheduling/yn2_890.smt2                                      |   60.095s | 102.0MiB| timeout | 0 |  |  |
|scheduling/yn4_919.smt2                                      |   60.095s | 102.0MiB| timeout | 0 |  |  |
|scheduling/swv14_2885.smt2                                   |   60.096s | 278.0MiB| timeout | 0 |  |  |
|scheduling/yn3_860.smt2                                      |   60.097s | 97.0MiB| timeout | 0 |  |  |
|scheduling/swv12_2900.smt2                                   |   60.097s | 283.0MiB| timeout | 0 |  |  |
|scheduling/orb06_1000.smt2                                   |   60.098s | 32.908MiB| timeout | 0 |  |  |
|scheduling/yn3_950.smt2                                      |   60.099s | 103.0MiB| timeout | 0 |  |  |
|scheduling/orb01_1059.smt2                                   |   60.100s | 31.624MiB| timeout | 0 |  |  |
|scheduling/yn1_887.smt2                                      |   60.101s | 102.0MiB| timeout | 0 |  |  |
|scheduling/yn1_950.smt2                                      |   60.104s | 108.0MiB| timeout | 0 |  |  |
|scheduling/swv11_2988.smt2                                   |   60.110s | 291.0MiB| timeout | 0 |  |  |
|scheduling/swv14_2895.smt2                                   |   60.112s | 272.0MiB| timeout | 0 |  |  |
|scheduling/swv12_3050.smt2                                   |   60.114s | 281.0MiB| timeout | 0 |  |  |
|scheduling/abz7_700.smt2                                     |   60.115s | 89.424MiB| timeout | 0 |  |  |
|scheduling/yn4_950.smt2                                      |   60.116s | 102.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                          |   60.119s | 717.0MiB| timeout | 0 |  |  |
|scheduling/swv13_3000.smt2                                   |   60.124s | 279.0MiB| timeout | 0 |  |  |
|scheduling/swv13_3200.smt2                                   |   60.127s | 284.0MiB| timeout | 0 |  |  |
