# .

* SAT 98
* UNSAT 81
* TIMEOUT 76
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfrdl-threads-4
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 477a1d817da44f7615fa53a10b4bd03d2cc84e48
Z3 branch: master
Z3 options: "-T:60 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false"
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
|SMT-Temporal-Planning-Benchmarks/tempo-matrix1x1.pddl.smt2   |    0.077s | 90.836MiB| sat | 0 |  |  |
|check/bignum_rdl1.smt2                                       |    0.079s | 90.072MiB| sat | 0 |  |  |
|check/bignum_rdl2.smt2                                       |    0.079s | 90.108MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2              |    0.099s | 93.968MiB| sat | 0 |  |  |
|sal/fischer6-mutex-1.smt2                                    |    0.100s | 91.888MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-width-1.smt2          |    0.106s | 90.844MiB| sat | 0 |  |  |
|sal/fischer3-mutex-2.smt2                                    |    0.106s | 91.988MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2              |    0.109s | 96.216MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-depth-2.smt2          |    0.111s | 95.78MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2              |    0.112s | 92.632MiB| sat | 0 |  |  |
|sal/fischer3-mutex-1.smt2                                    |    0.113s | 91.092MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-03.smt2       |    0.115s | 95.848MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-width-2.smt2          |    0.117s | 96.26MiB| sat | 0 |  |  |
|sal/fischer6-mutex-4.smt2                                    |    0.118s | 97.244MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2              |    0.119s | 97.756MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-04.smt2       |    0.119s | 96.372MiB| sat | 0 |  |  |
|sal/fischer3-mutex-3.smt2                                    |    0.120s | 92.9MiB| unsat | 0 |  |  |
|sal/fischer6-mutex-2.smt2                                    |    0.123s | 93.372MiB| unsat | 0 |  |  |
|sal/fischer9-mutex-1.smt2                                    |    0.126s | 92.372MiB| unsat | 0 |  |  |
|sal/fischer6-mutex-3.smt2                                    |    0.126s | 95.032MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2              |    0.127s | 94.936MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-06.smt2       |    0.131s | 98.94MiB| sat | 0 |  |  |
|sal/fischer3-mutex-4.smt2                                    |    0.131s | 93.4MiB| unsat | 0 |  |  |
|sal/fischer9-mutex-2.smt2                                    |    0.133s | 94.932MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-6.smt2                                    |    0.138s | 95.972MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-5.smt2                                    |    0.140s | 94.788MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-7.smt2                                    |    0.140s | 97.204MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-07.smt2       |    0.143s | 98.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2              |    0.144s | 99.04MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-08.smt2       |    0.144s | 99.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2              |    0.145s | 99.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2              |    0.149s | 98.112MiB| sat | 0 |  |  |
|sal/fischer9-mutex-3.smt2                                    |    0.150s | 97.46MiB| unsat | 0 |  |  |
|scheduling/abz5_1000.smt2                                    |    0.153s | 103.0MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-05.smt2       |    0.153s | 98.4MiB| sat | 0 |  |  |
|scheduling/orb07_250.smt2                                    |    0.159s | 98.0MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2              |    0.159s | 101.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2              |    0.163s | 103.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2              |    0.163s | 97.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-10.smt2       |    0.164s | 101.0MiB| sat | 0 |  |  |
|scheduling/orb07_330.smt2                                    |    0.165s | 101.0MiB| unsat | 0 |  |  |
|scheduling/abz6_800.smt2                                     |    0.168s | 100.0MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2              |    0.174s | 104.0MiB| sat | 0 |  |  |
|scheduling/orb02_700.smt2                                    |    0.175s | 99.0MiB| unsat | 0 |  |  |
|sal/fischer6-mutex-5.smt2                                    |    0.176s | 99.448MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2              |    0.179s | 104.0MiB| sat | 0 |  |  |
|scheduling/orb05_700.smt2                                    |    0.180s | 103.0MiB| unsat | 0 |  |  |
|sal/fischer6-mutex-6.smt2                                    |    0.183s | 99.0MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-09.smt2       |    0.186s | 101.0MiB| sat | 0 |  |  |
|sal/fischer9-mutex-4.smt2                                    |    0.188s | 98.0MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2              |    0.191s | 102.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-depth-3.smt2          |    0.191s | 104.0MiB| sat | 0 |  |  |
|scheduling/orb04_850.smt2                                    |    0.194s | 103.0MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2              |    0.209s | 111.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2              |    0.213s | 105.0MiB| sat | 0 |  |  |
|scheduling/orb07_550.smt2                                    |    0.214s | 107.0MiB| sat | 0 |  |  |
|sal/fischer3-mutex-8.smt2                                    |    0.218s | 98.752MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2              |    0.221s | 108.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2              |    0.224s | 112.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2              |    0.228s | 109.0MiB| sat | 0 |  |  |
|sal/fischer9-mutex-5.smt2                                    |    0.239s | 103.0MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2              |    0.242s | 110.0MiB| sat | 0 |  |  |
|scheduling/orb08_700.smt2                                    |    0.244s | 104.0MiB| unsat | 0 |  |  |
|sal/fischer6-mutex-7.smt2                                    |    0.246s | 103.0MiB| unsat | 0 |  |  |
|scheduling/orb10_800.smt2                                    |    0.251s | 105.0MiB| unsat | 0 |  |  |
|scheduling/orb02_800.smt2                                    |    0.257s | 104.0MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking21.smt2              |    0.257s | 114.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/cooking22.smt2              |    0.260s | 115.0MiB| sat | 0 |  |  |
|scheduling/orb04_1200.smt2                                   |    0.266s | 108.0MiB| sat | 0 |  |  |
|sal/fischer9-mutex-6.smt2                                    |    0.268s | 107.0MiB| unsat | 0 |  |  |
|scheduling/orb09_800.smt2                                    |    0.273s | 105.0MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-20.smt2       |    0.274s | 115.0MiB| sat | 0 |  |  |
|scheduling/abz5_1400.smt2                                    |    0.275s | 108.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-width-3.smt2          |    0.277s | 112.0MiB| sat | 0 |  |  |
|scheduling/orb09_1100.smt2                                   |    0.324s | 109.0MiB| sat | 0 |  |  |
|scheduling/orb06_1200.smt2                                   |    0.339s | 109.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-30.smt2       |    0.346s | 129.0MiB| sat | 0 |  |  |
|sal/fischer3-mutex-9.smt2                                    |    0.353s | 98.0MiB| unsat | 0 |  |  |
|scheduling/orb10_1100.smt2                                   |    0.367s | 109.0MiB| sat | 0 |  |  |
|scheduling/abz6_900.smt2                                     |    0.380s | 106.0MiB| unsat | 0 |  |  |
|scheduling/orb03_850.smt2                                    |    0.383s | 107.0MiB| unsat | 0 |  |  |
|scheduling/abz6_1100.smt2                                    |    0.388s | 109.0MiB| sat | 0 |  |  |
|scheduling/orb02_1000.smt2                                   |    0.396s | 109.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-depth-4.smt2          |    0.403s | 128.0MiB| sat | 0 |  |  |
|scheduling/orb04_1100.smt2                                   |    0.407s | 109.0MiB| sat | 0 |  |  |
|scheduling/orb08_830.smt2                                    |    0.413s | 108.0MiB| unsat | 0 |  |  |
|sal/fischer9-mutex-7.smt2                                    |    0.434s | 113.0MiB| unsat | 0 |  |  |
|scheduling/orb05_1000.smt2                                   |    0.440s | 109.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-40.smt2       |    0.481s | 141.0MiB| sat | 0 |  |  |
|scheduling/abz6_1000.smt2                                    |    0.493s | 109.0MiB| sat | 0 |  |  |
|scheduling/orb05_800.smt2                                    |    0.515s | 107.0MiB| unsat | 0 |  |  |
|scheduling/orb07_430.smt2                                    |    0.536s | 110.0MiB| sat | 0 |  |  |
|sal/fischer6-mutex-8.smt2                                    |    0.551s | 105.0MiB| unsat | 0 |  |  |
|scheduling/orb06_900.smt2                                    |    0.580s | 108.0MiB| unsat | 0 |  |  |
|scheduling/orb04_950.smt2                                    |    0.589s | 109.0MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-60.smt2       |    0.683s | 167.0MiB| sat | 0 |  |  |
|sal/fischer3-mutex-10.smt2                                   |    0.693s | 100.0MiB| unsat | 0 |  |  |
|scheduling/orb01_900.smt2                                    |    0.725s | 108.0MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-depth-5.smt2          |    0.749s | 164.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-70.smt2       |    0.783s | 185.0MiB| sat | 0 |  |  |
|scheduling/orb10_1000.smt2                                   |    0.833s | 111.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-80.smt2       |    0.855s | 189.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-width-4.smt2          |    0.856s | 162.0MiB| sat | 0 |  |  |
|scheduling/orb08_1000.smt2                                   |    0.870s | 112.0MiB| sat | 0 |  |  |
|sal/fischer3-mutex-11.smt2                                   |    0.961s | 102.0MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-90.smt2       |    0.979s | 212.0MiB| sat | 0 |  |  |
|sal/fischer9-mutex-8.smt2                                    |    1.113s | 120.0MiB| unsat | 0 |  |  |
|scheduling/orb03_1200.smt2                                   |    1.258s | 114.0MiB| sat | 0 |  |  |
|skdmxa/skdmxa-3x3-5.smt2                                     |    1.292s | 180.0MiB| unsat | 0 |  |  |
|scheduling/orb09_1000.smt2                                   |    1.307s | 113.0MiB| sat | 0 |  |  |
|scheduling/abz5_1300.smt2                                    |    1.387s | 113.0MiB| sat | 0 |  |  |
|scheduling/abz6_943.smt2                                     |    1.409s | 111.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-depth-6.smt2          |    1.412s | 231.0MiB| sat | 0 |  |  |
|scheduling/orb02_900.smt2                                    |    1.428s | 112.0MiB| sat | 0 |  |  |
|scheduling/abz7_500.smt2                                     |    1.488s | 205.0MiB| unsat | 0 |  |  |
|scheduling/orb10_900.smt2                                    |    1.726s | 110.0MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-12.smt2                                   |    1.748s | 104.0MiB| unsat | 0 |  |  |
|scheduling/yn3_750.smt2                                      |    1.829s | 273.0MiB| unsat | 0 |  |  |
|scheduling/yn1_750.smt2                                      |    1.852s | 265.0MiB| unsat | 0 |  |  |
|scheduling/orb05_900.smt2                                    |    1.879s | 111.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-5.induction.cvc.smt2                      |    1.885s | 269.0MiB| sat | 0 |  |  |
|scheduling/orb01_1200.smt2                                   |    1.962s | 115.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-5.base.cvc.smt2                           |    2.068s | 256.0MiB| unsat | 0 |  |  |
|scheduling/orb06_1100.smt2                                   |    2.144s | 114.0MiB| sat | 0 |  |  |
|scheduling/yn2_750.smt2                                      |    2.335s | 270.0MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-6.induction.cvc.smt2                      |    2.476s | 344.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-depth-7.smt2          |    2.714s | 355.0MiB| sat | 0 |  |  |
|sal/fischer6-mutex-9.smt2                                    |    2.719s | 114.0MiB| unsat | 0 |  |  |
|scheduling/orb09_900.smt2                                    |    2.720s | 112.0MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-width-5.smt2          |    2.936s | 296.0MiB| sat | 0 |  |  |
|sal/fischer3-mutex-13.smt2                                   |    2.979s | 107.0MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-6.base.cvc.smt2                           |    3.066s | 343.0MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-14.smt2                                   |    3.437s | 109.0MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-15.smt2                                   |    3.681s | 110.0MiB| unsat | 0 |  |  |
|scheduling/abz5_1234.smt2                                    |    3.686s | 113.0MiB| sat | 0 |  |  |
|scheduling/abz5_1200.smt2                                    |    3.812s | 112.0MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-16.smt2                                   |    3.951s | 113.0MiB| unsat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-matrix2x2.pddl.smt2   |    4.163s | 510.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-8.induction.cvc.smt2                      |    4.394s | 460.0MiB| sat | 0 |  |  |
|scheduling/orb02_888.smt2                                    |    4.788s | 114.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-7.base.cvc.smt2                           |    5.068s | 397.0MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-7.induction.cvc.smt2                      |    5.179s | 441.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-8.base.cvc.smt2                           |    6.273s | 504.0MiB| unsat | 0 |  |  |
|scheduling/orb08_930.smt2                                    |    6.838s | 116.0MiB| sat | 0 |  |  |
|sal/fischer3-mutex-17.smt2                                   |    7.087s | 116.0MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-9.induction.cvc.smt2                      |    7.125s | 537.0MiB| sat | 0 |  |  |
|scheduling/orb07_397.smt2                                    |    7.495s | 114.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-10.induction.cvc.smt2                     |    7.644s | 586.0MiB| sat | 0 |  |  |
|sal/fischer6-mutex-10.smt2                                   |    7.899s | 120.0MiB| unsat | 0 |  |  |
|scheduling/orb10_944.smt2                                    |    8.776s | 116.0MiB| sat | 0 |  |  |
|SMT-Temporal-Planning-Benchmarks/tempo-width-6.smt2          |    9.084s | 552.0MiB| sat | 0 |  |  |
|scheduling/orb09_934.smt2                                    |    9.406s | 116.0MiB| sat | 0 |  |  |
|skdmxa/skdmxa-3x3-10.smt2                                    |   10.880s | 331.0MiB| unsat | 0 |  |  |
|scheduling/orb05_887.smt2                                    |   11.047s | 116.0MiB| sat | 0 |  |  |
|scheduling/orb03_950.smt2                                    |   11.397s | 116.0MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-11.induction.cvc.smt2                     |   11.868s | 683.0MiB| sat | 0 |  |  |
|sal/fischer9-mutex-9.smt2                                    |   12.239s | 139.0MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-18.smt2                                   |   12.592s | 118.0MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-12.induction.cvc.smt2                     |   13.262s | 786.0MiB| sat | 0 |  |  |
|sal/fischer3-mutex-19.smt2                                   |   14.451s | 120.0MiB| unsat | 0 |  |  |
|scheduling/orb04_1005.smt2                                   |   14.803s | 117.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-9.base.cvc.smt2                           |   15.162s | 690.0MiB| unsat | 0 |  |  |
|sal/fischer3-mutex-20.smt2                                   |   17.532s | 124.0MiB| unsat | 0 |  |  |
|scheduling/orb03_1100.smt2                                   |   20.083s | 121.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                     |   21.785s | 983.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-13.induction.cvc.smt2                     |   22.864s | 933.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                     |   23.810s | 1093.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-10.base.cvc.smt2                          |   24.387s | 768.0MiB| unsat | 0 |  |  |
|sal/fischer9-mutex-10.smt2                                   |   25.705s | 149.0MiB| unsat | 0 |  |  |
|sal/fischer6-mutex-11.smt2                                   |   25.852s | 131.0MiB| unsat | 0 |  |  |
|scheduling/orb08_888.smt2                                    |   28.323s | 120.0MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                     |   28.944s | 1112.0MiB| sat | 0 |  |  |
|scheduling/orb01_1000.smt2                                   |   39.129s | 121.0MiB| unsat | 0 |  |  |
|scheduling/orb01_1100.smt2                                   |   39.450s | 124.0MiB| sat | 0 |  |  |
|sal/fischer6-mutex-12.smt2                                   |   40.362s | 140.0MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-11.base.cvc.smt2                          |   45.273s | 838.0MiB| unsat | 0 |  |  |
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                     |   51.076s | 1399.0MiB| sat | 0 |  |  |
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                     |   53.359s | 1674.0MiB| sat | 0 |  |  |
|sal/fischer9-mutex-11.smt2                                   |   58.101s | 163.0MiB| unsat | 0 |  |  |
|sal/fischer6-mutex-13.smt2                                   |   60.027s | 148.0MiB| timeout | 0 |  |  |
|sal/fischer6-mutex-14.smt2                                   |   60.031s | 150.0MiB| timeout | 0 |  |  |
|scheduling/orb03_1005.smt2                                   |   60.036s | 126.0MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-18.smt2                                   |   60.043s | 239.0MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-13.smt2                                   |   60.046s | 185.0MiB| timeout | 0 |  |  |
|scheduling/orb06_1000.smt2                                   |   60.050s | 126.0MiB| timeout | 0 |  |  |
|scheduling/orb01_1059.smt2                                   |   60.050s | 125.0MiB| timeout | 0 |  |  |
|sal/fischer6-mutex-16.smt2                                   |   60.053s | 159.0MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-14.smt2                                   |   60.054s | 202.0MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-19.smt2                                   |   60.056s | 244.0MiB| timeout | 0 |  |  |
|sal/fischer6-mutex-15.smt2                                   |   60.058s | 156.0MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-12.smt2                                   |   60.058s | 170.0MiB| timeout | 0 |  |  |
|sal/fischer6-mutex-20.smt2                                   |   60.063s | 182.0MiB| timeout | 0 |  |  |
|sal/fischer6-mutex-18.smt2                                   |   60.064s | 168.0MiB| timeout | 0 |  |  |
|scheduling/yn2_910.smt2                                      |   60.066s | 412.0MiB| timeout | 0 |  |  |
|scheduling/orb06_1010.smt2                                   |   60.067s | 126.0MiB| timeout | 0 |  |  |
|scheduling/yn3_860.smt2                                      |   60.068s | 385.0MiB| timeout | 0 |  |  |
|scheduling/abz7_600.smt2                                     |   60.069s | 299.0MiB| timeout | 0 |  |  |
|sal/fischer6-mutex-17.smt2                                   |   60.069s | 166.0MiB| timeout | 0 |  |  |
|scheduling/yn4_1000.smt2                                     |   60.072s | 431.0MiB| timeout | 0 |  |  |
|sal/fischer6-mutex-19.smt2                                   |   60.072s | 177.0MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-15.smt2                                   |   60.072s | 208.0MiB| timeout | 0 |  |  |
|scheduling/yn3_828.smt2                                      |   60.074s | 374.0MiB| timeout | 0 |  |  |
|scheduling/abz7_670.smt2                                     |   60.075s | 330.0MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-20.smt2                                   |   60.075s | 253.0MiB| timeout | 0 |  |  |
|scheduling/yn4_919.smt2                                      |   60.078s | 396.0MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-17.smt2                                   |   60.080s | 227.0MiB| timeout | 0 |  |  |
|sal/fischer9-mutex-16.smt2                                   |   60.080s | 220.0MiB| timeout | 0 |  |  |
|scheduling/abz7_700.smt2                                     |   60.082s | 346.0MiB| timeout | 0 |  |  |
|scheduling/yn1_950.smt2                                      |   60.082s | 428.0MiB| timeout | 0 |  |  |
|scheduling/yn1_827.smt2                                      |   60.087s | 372.0MiB| timeout | 0 |  |  |
|scheduling/abz7_691.smt2                                     |   60.088s | 345.0MiB| timeout | 0 |  |  |
|scheduling/yn2_890.smt2                                      |   60.090s | 397.0MiB| timeout | 0 |  |  |
|scheduling/abz7_667.smt2                                     |   60.090s | 332.0MiB| timeout | 0 |  |  |
|scheduling/yn2_862.smt2                                      |   60.092s | 387.0MiB| timeout | 0 |  |  |
|scheduling/yn2_950.smt2                                      |   60.095s | 435.0MiB| timeout | 0 |  |  |
|scheduling/yn1_850.smt2                                      |   60.099s | 379.0MiB| timeout | 0 |  |  |
|scheduling/yn4_969.smt2                                      |   60.104s | 418.0MiB| timeout | 0 |  |  |
|skdmxa/skdmxa-3x3-15.smt2                                    |   60.106s | 642.0MiB| timeout | 0 |  |  |
|scheduling/yn4_850.smt2                                      |   60.107s | 347.0MiB| timeout | 0 |  |  |
|scheduling/yn4_950.smt2                                      |   60.109s | 407.0MiB| timeout | 0 |  |  |
|scheduling/yn3_894.smt2                                      |   60.110s | 405.0MiB| timeout | 0 |  |  |
|scheduling/abz7_800.smt2                                     |   60.112s | 369.0MiB| timeout | 0 |  |  |
|scheduling/yn3_950.smt2                                      |   60.114s | 428.0MiB| timeout | 0 |  |  |
|scheduling/yn1_887.smt2                                      |   60.116s | 402.0MiB| timeout | 0 |  |  |
|scheduling/swv14_2895.smt2                                   |   60.142s | 1035.0MiB| timeout | 0 |  |  |
|scheduling/swv13_3000.smt2                                   |   60.150s | 1030.0MiB| timeout | 0 |  |  |
|skdmxa/skdmxa-3x3-20.smt2                                    |   60.156s | 911.0MiB| timeout | 0 |  |  |
|scheduling/swv12_3050.smt2                                   |   60.156s | 1045.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                          |   60.157s | 1118.0MiB| timeout | 0 |  |  |
|scheduling/swv11_2983.smt2                                   |   60.160s | 1035.0MiB| timeout | 0 |  |  |
|scheduling/swv14_2800.smt2                                   |   60.170s | 1047.0MiB| timeout | 0 |  |  |
|scheduling/swv13_3150.smt2                                   |   60.170s | 1030.0MiB| timeout | 0 |  |  |
|scheduling/swv14_2885.smt2                                   |   60.171s | 1029.0MiB| timeout | 0 |  |  |
|scheduling/swv12_2900.smt2                                   |   60.171s | 1021.0MiB| timeout | 0 |  |  |
|scheduling/swv11_2992.smt2                                   |   60.176s | 1019.0MiB| timeout | 0 |  |  |
|scheduling/swv11_3050.smt2                                   |   60.178s | 1036.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                          |   60.186s | 1283.0MiB| timeout | 0 |  |  |
|scheduling/swv13_3200.smt2                                   |   60.187s | 1032.0MiB| timeout | 0 |  |  |
|scheduling/swv12_2990.smt2                                   |   60.187s | 1036.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-12.base.cvc.smt2                          |   60.188s | 1006.0MiB| timeout | 0 |  |  |
|scheduling/swv14_3000.smt2                                   |   60.193s | 1028.0MiB| timeout | 0 |  |  |
|scheduling/swv11_2988.smt2                                   |   60.195s | 1041.0MiB| timeout | 0 |  |  |
|scheduling/swv14_2905.smt2                                   |   60.215s | 1029.0MiB| timeout | 0 |  |  |
|scheduling/swv12_3004.smt2                                   |   60.220s | 1036.0MiB| timeout | 0 |  |  |
|scheduling/swv11_2900.smt2                                   |   60.223s | 1047.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                     |   60.229s | 1527.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                          |   60.233s | 1792.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                     |   60.240s | 1565.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                          |   60.244s | 1897.0MiB| timeout | 0 |  |  |
|scheduling/swv13_3104.smt2                                   |   60.245s | 1024.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                          |   60.265s | 1647.0MiB| timeout | 0 |  |  |
|scheduling/swv12_2972.smt2                                   |   60.271s | 1043.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                          |   60.300s | 2454.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                          |   60.310s | 2545.0MiB| timeout | 0 |  |  |
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                          |   60.365s | 2034.0MiB| timeout | 0 |  |  |
