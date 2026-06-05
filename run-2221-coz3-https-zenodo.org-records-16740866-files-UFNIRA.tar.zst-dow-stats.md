# .

* SAT 15
* UNSAT 94
* TIMEOUT 151
* UNKNOWN 6

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFNIRA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFNIRA.tar.zst-dow
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 branch: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFNIRA.tar.zst?download=1
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
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U19_sol1.smt2 |    0.025s | 20.064MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U25_sol2.smt2 |    0.027s | 19.912MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C2_sol1.smt2 |    0.027s | 20.088MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U41.smt2 |    0.027s | 20.764MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9a_sol1.smt2 |    0.028s | 19.996MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U46.smt2 |    0.028s | 20.536MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U75_sol2.smt2 |    0.029s | 19.972MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U3_sol1.smt2 |    0.031s | 20.272MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U17_sol1.smt2 |    0.032s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U92_sol1.smt2 |    0.034s | 19.924MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U1.smt2 |    0.034s | 20.78MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U81.smt2 |    0.038s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U51_sol1.smt2 |    0.039s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol3.smt2 |    0.039s | 19.912MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U8_sol1.smt2 |    0.040s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U48_sol2.smt2 |    0.042s | 20.012MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C3_sol1.smt2 |    0.043s | 20.304MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U82_sol1.smt2 |    0.043s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U67_sol1.smt2 |    0.043s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U23_sol1.smt2 |    0.043s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U24_sol1.smt2 |    0.043s | 20.024MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U9_sol1.smt2 |    0.044s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol1.smt2 |    0.044s | 19.964MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U46_sol2.smt2 |    0.045s | 20.096MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U39_sol1.smt2 |    0.046s | 20.012MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U81_sol1.smt2 |    0.047s | 20.496MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U49_sol2.smt2 |    0.048s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U91_sol2.smt2 |    0.048s | 20.336MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C10.smt2 |    0.050s | 20.06MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U53_sol1.smt2 |    0.051s | 20.332MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U57_sol1.smt2 |    0.052s | 20.496MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U45_sol2.smt2 |    0.053s | 20.02MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U56_sol1.smt2 |    0.053s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U46_sol1.smt2 |    0.053s | 20.204MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U87_sol1.smt2 |    0.053s | 19.98MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol3.smt2 |    0.054s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U14_sol1.smt2 |    0.054s | 20.452MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C1_sol1.smt2 |    0.055s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol1.smt2 |    0.055s | 20.124MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U45_sol1.smt2 |    0.055s | 20.124MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U49_sol1.smt2 |    0.055s | 20.096MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U66_sol1.smt2 |    0.055s | 20.28MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C10_sol1.smt2 |    0.056s | 20.164MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U87_sol2.smt2 |    0.056s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C12_sol1.smt2 |    0.057s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U75.smt2 |    0.057s | 20.916MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U68.smt2 |    0.058s | 20.6MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U57.smt2 |    0.059s | 20.528MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U66.smt2 |    0.059s | 20.668MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U64_sol1.smt2 |    0.061s | 20.204MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U54_sol1.smt2 |    0.062s | 20.66MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U4_sol1.smt2 |    0.063s | 20.648MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U71_sol1.smt2 |    0.064s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U6_sol1.smt2 |    0.067s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U75_sol1.smt2 |    0.069s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C6_sol1.smt2 |    0.070s | 20.332MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U72_sol2.smt2 |    0.077s | 20.184MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C5_sol1.smt2 |    0.078s | 20.852MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U89_sol1.smt2 |    0.082s | 20.192MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9_sol1.smt2 |    0.083s | 20.72MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U17.smt2 |    0.084s | 20.404MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U61_sol1.smt2 |    0.087s | 20.812MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U42_sol1.smt2 |    0.090s | 20.588MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C5.smt2 |    0.091s | 20.644MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U48_sol1.smt2 |    0.097s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U37_sol1.smt2 |    0.104s | 21.124MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U91_sol1.smt2 |    0.109s | 20.052MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U20.smt2 |    0.109s | 21.132MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U56_sol2.smt2 |    0.112s | 19.976MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U4.smt2 |    0.113s | 21.332MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol2.smt2 |    0.115s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U8_sol2.smt2 |    0.116s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U11.smt2 |    0.119s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U5_sol1.smt2 |    0.123s | 19.912MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U66_sol2.smt2 |    0.124s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U54_sol2.smt2 |    0.124s | 20.588MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol2.smt2 |    0.125s | 20.012MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U10_sol1.smt2 |    0.125s | 20.14MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U13_sol1.smt2 |    0.125s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U23.smt2 |    0.127s | 20.876MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U89.smt2 |    0.127s | 20.62MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U90_sol1.smt2 |    0.128s | 20.096MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U72.smt2 |    0.129s | 20.672MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C13_sol1.smt2 |    0.131s | 20.18MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U62_sol1.smt2 |    0.131s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C4_sol1.smt2 |    0.132s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U7_sol1.smt2 |    0.135s | 20.124MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U93_sol1.smt2 |    0.135s | 20.904MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U26_sol2.smt2 |    0.137s | 20.628MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol2.smt2 |    0.137s | 20.14MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U27_sol1.smt2 |    0.138s | 20.352MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U26.smt2 |    0.138s | 22.448MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U51.smt2 |    0.140s | 21.148MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U11_sol1.smt2 |    0.141s | 20.408MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U26_sol1.smt2 |    0.142s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U44_sol1.smt2 |    0.147s | 20.76MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U76_sol1.smt2 |    0.149s | 20.892MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol1.smt2 |    0.158s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U68_sol1.smt2 |    0.159s | 20.208MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U72_sol1.smt2 |    0.159s | 20.188MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U71.smt2 |    0.159s | 21.14MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol3.smt2 |    0.160s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U2_sol1.smt2 |    0.160s | 19.944MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U25_sol1.smt2 |    0.160s | 19.908MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U48.smt2 |    0.161s | 21.156MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U62.smt2 |    0.161s | 20.528MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U79.smt2 |    0.170s | 32.484MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U44_sol2.smt2 |    0.187s | 20.78MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U12_sol1.smt2 |    0.333s | 21.152MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U7.smt2 |    4.752s | 26.46MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C6.smt2 |    5.756s | 45.48MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U14.smt2 |    8.735s | 29.864MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U17.smt2 |   12.229s | 143.0MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U14.smt2 |   12.364s | 30.592MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U16_sol1.smt2 |   15.356s | 33.228MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U30.smt2 |   20.025s | 23.708MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C4.smt2 |   20.025s | 65.924MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U27.smt2 |   20.031s | 25.332MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U57.smt2 |   20.038s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C9a.smt2 |   20.039s | 48.012MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C13.smt2 |   20.040s | 266.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C9.smt2 |   20.046s | 38.52MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C8_sol1.smt2 |   20.050s | 39.816MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U34.smt2 |   20.051s | 80.652MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U53.smt2 |   20.052s | 49.472MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U23.smt2 |   20.053s | 50.988MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C7.smt2 |   20.053s | 28.92MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U93.smt2 |   20.055s | 28.184MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C3.smt2 |   20.055s | 86.536MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U47.smt2 |   20.060s | 28.368MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U81.smt2 |   20.061s | 56.732MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U40_sol1.smt2 |   20.064s | 36.128MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U76.smt2 |   20.069s | 27.916MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U11.smt2 |   20.069s | 56.284MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U12.smt2 |   20.069s | 32.568MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C5.smt2 |   20.074s | 22.812MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U33.smt2 |   20.078s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U88.smt2 |   20.079s | 36.268MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U10.smt2 |   20.083s | 104.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U12.smt2 |   20.092s | 28.84MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C6.smt2 |   20.094s | 38.44MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U38.smt2 |   20.095s | 38.928MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U7.smt2 |   20.098s | 37.768MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U45.smt2 |   20.099s | 213.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C10.smt2 |   20.101s | 233.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C9.smt2 |   20.103s | 55.04MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U44.smt2 |   20.105s | 42.22MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U1.smt2 |   20.108s | 24.268MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U4.smt2 |   20.109s | 486.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C7.smt2 |   20.111s | 28.408MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U53.smt2 |   20.114s | 48.132MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U1_sol1.smt2 |   20.128s | 26.68MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U45.smt2 |   20.128s | 28.54MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U93.smt2 |   20.129s | 28.432MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U90.smt2 |   20.133s | 62.728MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C7_sol1.smt2 |   20.137s | 30.236MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U66.smt2 |   20.141s | 32.596MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U26.smt2 |   20.143s | 33.268MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U87.smt2 |   20.147s | 67.888MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U33_sol1.smt2 |   20.150s | 339.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C3.smt2 |   20.154s | 63.608MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U39.smt2 |   20.154s | 66.468MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol1.smt2 |   20.155s | 29.768MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U76.smt2 |   20.155s | 27.724MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C9a.smt2 |   20.160s | 74.096MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U90.smt2 |   20.165s | 94.628MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U27.smt2 |   20.166s | 23.444MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U6.smt2 |   20.186s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U16.smt2 |   20.189s | 267.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U9.smt2 |   20.194s | 153.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U39.smt2 |   20.224s | 325.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U5.smt2 |   20.226s | 392.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U28.smt2 |   20.230s | 280.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U33.smt2 |   20.233s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U6.smt2 |   20.277s | 190.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C13.smt2 |   20.285s | 239.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U72.smt2 |   20.309s | 301.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C4.smt2 |   20.310s | 266.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U9.smt2 |   20.320s | 284.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U68.smt2 |   20.322s | 452.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U44.smt2 |   20.328s | 516.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U91.smt2 |   20.331s | 471.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U10.smt2 |   20.348s | 264.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C8.smt2 |   20.435s | 480.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C2.smt2 |   20.471s | 570.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U19.smt2 |   20.511s | 719.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U71.smt2 |   20.514s | 659.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U37.smt2 |   20.535s | 1694.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U51.smt2 |   20.548s | 970.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U70.smt2 |   20.556s | 645.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U91.smt2 |   20.653s | 1081.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U16.smt2 |   20.729s | 961.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C8.smt2 |   20.733s | 1385.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U92.smt2 |   20.869s | 1277.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U19.smt2 |   20.966s | 1788.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U37.smt2 |   21.041s | 2020.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U67.smt2 |   21.071s | 2221.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U87.smt2 |   21.074s | 1799.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U43.smt2 |   21.076s | 1754.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U21.smt2 |   21.090s | 2128.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U8.smt2 |   21.101s | 2305.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U43.smt2 |   21.117s | 1905.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U48.smt2 |   21.134s | 2284.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U67.smt2 |   21.154s | 1751.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U8.smt2 |   21.156s | 2329.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U41.smt2 |   21.192s | 2176.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U64.smt2 |   21.201s | 2700.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U54.smt2 |   21.212s | 2733.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U82.smt2 |   21.238s | 2589.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U54.smt2 |   21.261s | 2721.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U73_sol1.smt2 |   21.276s | 2861.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U25.smt2 |   21.282s | 2725.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U40.smt2 |   21.302s | 2993.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U61.smt2 |   21.306s | 2423.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U29.smt2 |   21.313s | 2448.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C12.smt2 |   21.327s | 3132.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U15.smt2 |   21.341s | 2239.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U73.smt2 |   21.351s | 2880.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U49.smt2 |   21.384s | 2591.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U50.smt2 |   21.390s | 2297.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U65.smt2 |   21.395s | 3174.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U29.smt2 |   21.396s | 2410.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U62.smt2 |   21.403s | 3844.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol2.smt2 |   21.430s | 2257.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U2.smt2 |   21.438s | 3753.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U56.smt2 |   21.448s | 2193.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U29_sol1.smt2 |   21.449s | 4575.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U61.smt2 |   21.452s | 2529.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U3.smt2 |   21.463s | 3948.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U22_sol1.smt2 |   21.472s | 2322.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U56.smt2 |   21.472s | 2869.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U50.smt2 |   21.498s | 3228.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U13.smt2 |   21.526s | 2469.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U20.smt2 |   21.527s | 2497.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C12.smt2 |   21.530s | 3424.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U46.smt2 |   21.546s | 2843.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U21.smt2 |   21.562s | 3521.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U15.smt2 |   21.563s | 2783.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C11.smt2 |   21.578s | 2963.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U92.smt2 |   21.586s | 4296.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U31.smt2 |   21.592s | 2820.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U89.smt2 |   21.593s | 5271.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U40.smt2 |   21.606s | 2929.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U42.smt2 |   21.607s | 2805.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U22.smt2 |   21.617s | 3525.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U5.smt2 |   21.646s | 2632.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C1.smt2 |   21.665s | 3847.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U24.smt2 |   21.694s | 3784.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U75.smt2 |   21.706s | 6682.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C1.smt2 |   21.716s | 7344.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U25.smt2 |   21.734s | 3401.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U22.smt2 |   21.735s | 3525.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U24.smt2 |   21.750s | 3728.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C11.smt2 |   21.754s | 3476.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C11_sol1.smt2 |   21.778s | 3185.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U21_sol1.smt2 |   21.803s | 4279.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U49.smt2 |   21.820s | 3730.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U43_sol1.smt2 |   21.856s | 4122.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U13.smt2 |   21.862s | 4105.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U42.smt2 |   21.863s | 4781.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U64.smt2 |   21.873s | 3493.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C2.smt2 |   21.904s | 3923.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U2.smt2 |   21.915s | 4308.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U3.smt2 |   21.977s | 4225.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U73.smt2 |   22.055s | 4414.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U82.smt2 |   22.081s | 3797.0MiB| timeout | 0 |  |  |
