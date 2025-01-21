Comparing data and data


# SUMMARY
- LHS tests = 1818
- RHS tests = 1818
- LHS success = 1475  (81.13311331133113%)
- RHS success = 1475  (81.13311331133113%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: CInteger
Job tag: smt-sls-clausal-lookahead
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 22e4054674a291d83f59019273ff0b24f24295bf
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_NIA_CInteger
Z3 commit message: add clausal lookahead to arithmetic solver as part of portfolio

have legacy qfbv-sls solver use nnf pre-processing. It relies on it for correctness of the score updates.

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: CInteger
Job tag: smt-sls-clausal-lookahead
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 22e4054674a291d83f59019273ff0b24f24295bf
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_NIA_CInteger
Z3 commit message: add clausal lookahead to arithmetic solver as part of portfolio

have legacy qfbv-sls solver use nnf pre-processing. It relies on it for correctness of the score updates.

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   6.098s  |   6.098s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   8.581s  |   8.581s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   4.799s  |   4.799s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   0.711s  |   0.711s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |   1.694s  |   1.694s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |   1.398s  |   1.398s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   6.573s  |   6.573s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |   3.001s  |   3.001s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   6.098s  |   6.098s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   8.581s  |   8.581s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   4.799s  |   4.799s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   0.711s  |   0.711s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |   1.694s  |   1.694s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |   1.398s  |   1.398s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   6.573s  |   6.573s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |   3.001s  |   3.001s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   6.098s  |   6.098s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   8.581s  |   8.581s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   4.799s  |   4.799s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   0.711s  |   0.711s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |   1.694s  |   1.694s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |   1.398s  |   1.398s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   6.573s  |   6.573s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |   3.001s  |   3.001s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   6.098s  |   6.098s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   8.581s  |   8.581s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   4.799s  |   4.799s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   0.711s  |   0.711s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |   1.694s  |   1.694s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |   1.398s  |   1.398s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   6.573s  |   6.573s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |   3.001s  |   3.001s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Stroeder_15__Flip2.c__p22938_terminationG_0.smt2                                           |  20.565s |22.04MiB|
|Stroeder_15__Marbie2.c__p24218_terminationG_0.smt2                                         |  20.450s |19.064MiB|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                 |  20.250s |19.764MiB|
|Stroeder_15__ChooseLife.c__p22200_terminationG_0.smt2                                      |  20.234s |19.16MiB|
|Stroeder_15__Fibonacci.c__p22888_terminationG_0.smt2                                       |  20.225s |19.24MiB|
|Stroeder_15__DoubleNeg.c__p22557_terminationG_0.smt2                                       |  20.161s |19.48MiB|
|Stroeder_15__Fibonacci.c__p22901_terminationG_0.smt2                                       |  20.157s |20.44MiB|
|Stroeder_15__svcomp_ex2.c__p25836_terminationG_0.smt2                                      |  20.150s |31.428MiB|
|Stroeder_15__Velroyen_false-termination.c__p26335_terminationG_0.smt2                      |  20.144s |18.992MiB|
|Stroeder_15__DivWithoutMinus.c__p22495_terminationG_0.smt2                                 |  20.144s |20.564MiB|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24252_edge_closing_0.smt2          |  20.139s |19.708MiB|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27437_terminationG_0.smt2                 |  20.127s |19.276MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27136_terminationG_0.smt2                   |  20.109s |33.432MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27230_terminationG_0.smt2                   |  20.109s |23.464MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27011_terminationG_0.smt2                  |  20.088s |20.04MiB|
|Stroeder_15__Gauss.c__p23054_terminationG_0.smt2                                           |  20.086s |19.076MiB|
|Stroeder_15__AlternDivWidening.c__p20650_terminationG_0.smt2                               |  20.082s |19.452MiB|
|Stroeder_15__GCD2.c__p23120_terminationG_0.smt2                                            |  20.082s |19.608MiB|
|Stroeder_15__DoubleNeg.c__p22545_terminationG_0.smt2                                       |  20.082s |18.916MiB|
|Stroeder_15__DoubleNeg.c__p22546_terminationG_0.smt2                                       |  20.081s |19.104MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Stroeder_15__Flip2.c__p22938_terminationG_0.smt2                                           |  20.565s |22.04MiB|
|Stroeder_15__Marbie2.c__p24218_terminationG_0.smt2                                         |  20.450s |19.064MiB|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                 |  20.250s |19.764MiB|
|Stroeder_15__ChooseLife.c__p22200_terminationG_0.smt2                                      |  20.234s |19.16MiB|
|Stroeder_15__Fibonacci.c__p22888_terminationG_0.smt2                                       |  20.225s |19.24MiB|
|Stroeder_15__DoubleNeg.c__p22557_terminationG_0.smt2                                       |  20.161s |19.48MiB|
|Stroeder_15__Fibonacci.c__p22901_terminationG_0.smt2                                       |  20.157s |20.44MiB|
|Stroeder_15__svcomp_ex2.c__p25836_terminationG_0.smt2                                      |  20.150s |31.428MiB|
|Stroeder_15__Velroyen_false-termination.c__p26335_terminationG_0.smt2                      |  20.144s |18.992MiB|
|Stroeder_15__DivWithoutMinus.c__p22495_terminationG_0.smt2                                 |  20.144s |20.564MiB|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24252_edge_closing_0.smt2          |  20.139s |19.708MiB|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27437_terminationG_0.smt2                 |  20.127s |19.276MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27136_terminationG_0.smt2                   |  20.109s |33.432MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27230_terminationG_0.smt2                   |  20.109s |23.464MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27011_terminationG_0.smt2                  |  20.088s |20.04MiB|
|Stroeder_15__Gauss.c__p23054_terminationG_0.smt2                                           |  20.086s |19.076MiB|
|Stroeder_15__AlternDivWidening.c__p20650_terminationG_0.smt2                               |  20.082s |19.452MiB|
|Stroeder_15__GCD2.c__p23120_terminationG_0.smt2                                            |  20.082s |19.608MiB|
|Stroeder_15__DoubleNeg.c__p22545_terminationG_0.smt2                                       |  20.082s |18.916MiB|
|Stroeder_15__DoubleNeg.c__p22546_terminationG_0.smt2                                       |  20.081s |19.104MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |19.232MiB|19.232MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |19.136MiB|19.136MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |19.236MiB|19.236MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |18.94MiB|18.94MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |19.312MiB|19.312MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |19.52MiB|19.52MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |20.972MiB|20.972MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |22.568MiB|22.568MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |19.808MiB|19.808MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |20.948MiB|20.948MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |24.596MiB|24.596MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |28.804MiB|28.804MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |24.176MiB|24.176MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |27.556MiB|27.556MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |23.268MiB|23.268MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |25.876MiB|25.876MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |21.672MiB|21.672MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |23.54MiB|23.54MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |20.34MiB|20.34MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |21.644MiB|21.644MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |19.232MiB|19.232MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |19.136MiB|19.136MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |19.236MiB|19.236MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |18.94MiB|18.94MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |19.312MiB|19.312MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |19.52MiB|19.52MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |20.972MiB|20.972MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |22.568MiB|22.568MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |19.808MiB|19.808MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |20.948MiB|20.948MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |24.596MiB|24.596MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |28.804MiB|28.804MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |24.176MiB|24.176MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |27.556MiB|27.556MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |23.268MiB|23.268MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |25.876MiB|25.876MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |21.672MiB|21.672MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |23.54MiB|23.54MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |20.34MiB|20.34MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |21.644MiB|21.644MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |19.232MiB|19.232MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |19.136MiB|19.136MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |19.236MiB|19.236MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |18.94MiB|18.94MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |19.312MiB|19.312MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |19.52MiB|19.52MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |20.972MiB|20.972MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |22.568MiB|22.568MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |19.808MiB|19.808MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |20.948MiB|20.948MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |24.596MiB|24.596MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |28.804MiB|28.804MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |24.176MiB|24.176MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |27.556MiB|27.556MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |23.268MiB|23.268MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |25.876MiB|25.876MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |21.672MiB|21.672MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |23.54MiB|23.54MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |20.34MiB|20.34MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |21.644MiB|21.644MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |19.232MiB|19.232MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |19.136MiB|19.136MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |19.236MiB|19.236MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |18.94MiB|18.94MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |19.312MiB|19.312MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |19.52MiB|19.52MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |20.972MiB|20.972MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |22.568MiB|22.568MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |19.808MiB|19.808MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |20.948MiB|20.948MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |24.596MiB|24.596MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |28.804MiB|28.804MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |24.176MiB|24.176MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |27.556MiB|27.556MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |23.268MiB|23.268MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |25.876MiB|25.876MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |21.672MiB|21.672MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |23.54MiB|23.54MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |20.34MiB|20.34MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |21.644MiB|21.644MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27240_edge_closing_0.smt2                   |   9.825s |1059.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22029_edge_closing_0.smt2 |   7.762s |939.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27239_edge_closing_0.smt2                   |   9.068s |839.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2 |   7.068s |756.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27238_edge_closing_0.smt2                   |   8.067s |656.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22027_edge_closing_0.smt2 |   6.704s |587.0MiB|
|Stroeder_15__svcomp_ex2.c__p25827_terminationG_0.smt2                                      |  20.003s |128.0MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27040_edge_closing_0.smt2                  |   0.522s |119.0MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27039_edge_closing_0.smt2                  |   0.483s |95.296MiB|
|Stroeder_15__Narrowing.c__p24549_edge_closing_0.smt2                                       |   0.559s |78.116MiB|
|Stroeder_15__svcomp_ex2.c__p25826_terminationG_0.smt2                                      |  20.007s |68.872MiB|
|Stroeder_15__svcomp_ex2.c__p25817_terminationG_0.smt2                                      |  10.100s |65.352MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27038_edge_closing_0.smt2                  |   0.429s |64.764MiB|
|Stroeder_15__Narrowing.c__p24548_edge_closing_0.smt2                                       |   0.306s |59.588MiB|
|Stroeder_15__svcomp_ex2.c__p25832_terminationG_0.smt2                                      |  20.001s |58.048MiB|
|Stroeder_15__GCD.c__p23180_terminationG_0.smt2                                             |  19.994s |47.004MiB|
|Stroeder_15__svcomp_ex2.c__p25843_terminationG_0.smt2                                      |   0.395s |46.76MiB|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                      |   8.778s |46.548MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27236_edge_closing_0.smt2                   |   5.751s |46.2MiB|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                      |  12.352s |45.104MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27240_edge_closing_0.smt2                   |   9.825s |1059.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22029_edge_closing_0.smt2 |   7.762s |939.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27239_edge_closing_0.smt2                   |   9.068s |839.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2 |   7.068s |756.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27238_edge_closing_0.smt2                   |   8.067s |656.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22027_edge_closing_0.smt2 |   6.704s |587.0MiB|
|Stroeder_15__svcomp_ex2.c__p25827_terminationG_0.smt2                                      |  20.003s |128.0MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27040_edge_closing_0.smt2                  |   0.522s |119.0MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27039_edge_closing_0.smt2                  |   0.483s |95.296MiB|
|Stroeder_15__Narrowing.c__p24549_edge_closing_0.smt2                                       |   0.559s |78.116MiB|
|Stroeder_15__svcomp_ex2.c__p25826_terminationG_0.smt2                                      |  20.007s |68.872MiB|
|Stroeder_15__svcomp_ex2.c__p25817_terminationG_0.smt2                                      |  10.100s |65.352MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27038_edge_closing_0.smt2                  |   0.429s |64.764MiB|
|Stroeder_15__Narrowing.c__p24548_edge_closing_0.smt2                                       |   0.306s |59.588MiB|
|Stroeder_15__svcomp_ex2.c__p25832_terminationG_0.smt2                                      |  20.001s |58.048MiB|
|Stroeder_15__GCD.c__p23180_terminationG_0.smt2                                             |  19.994s |47.004MiB|
|Stroeder_15__svcomp_ex2.c__p25843_terminationG_0.smt2                                      |   0.395s |46.76MiB|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                      |   8.778s |46.548MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27236_edge_closing_0.smt2                   |   5.751s |46.2MiB|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                      |  12.352s |45.104MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   6.098s  |   6.098s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   8.581s  |   8.581s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   4.799s  |   4.799s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   0.711s  |   0.711s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |   1.694s  |   1.694s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |   1.398s  |   1.398s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   6.573s  |   6.573s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |   3.001s  |   3.001s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20255_terminationG_0.smt2           |   3.094s  |   3.094s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20259_terminationG_0.smt2           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20260_terminationG_0.smt2           |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20269_terminationG_0.smt2           |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20270_terminationG_0.smt2           |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20271_terminationG_0.smt2           |  15.771s  |  15.771s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20279_terminationG_0.smt2           |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20280_terminationG_0.smt2           |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20281_terminationG_0.smt2           |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20288_terminationG_0.smt2           |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20289_terminationG_0.smt2           |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20305_terminationG_0.smt2           |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20306_terminationG_0.smt2           |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20307_terminationG_0.smt2           |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20312_terminationG_0.smt2           |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20313_terminationG_0.smt2           |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20314_terminationG_0.smt2           |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20324_terminationG_0.smt2           |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20325_terminationG_0.smt2           |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20326_terminationG_0.smt2           |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_0_0.smt2                |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_2_0.smt2                |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_3_0.smt2                |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_4_0.smt2                |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-Fig1_true-termination.c__p20413_terminationG_0.smt2  |   6.239s  |   6.239s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-Fig2b_true-termination.c__terminationS_1_0.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-complex_true-termination.c__term_unfeasibility_0_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-counterex1b_true-termination.c__p20394_terminationG_0.smt2  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-counterex1b_true-termination.c__p20395_terminationG_0.smt2  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-counterex1b_true-termination.c__p20396_terminationG_0.smt2  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-loops_true-termination.c__p20439_terminationG_0.smt2  |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-loops_true-termination.c__p20440_terminationG_0.smt2  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-loops_true-termination.c__term_unfeasibility_0_0.smt2  |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-speedFails4_true-termination.c__p20494_terminationG_0.smt2  |  17.275s  |  17.275s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20546_terminationG_0.smt2                                        |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20552_terminationG_0.smt2                                        |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20553_terminationG_0.smt2                                        |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20556_edge_closing_0.smt2                                        |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20557_edge_closing_0.smt2                                        |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20618_terminationG_0.smt2                                    |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20619_terminationG_0.smt2                                    |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20626_edge_closing_0.smt2                                    |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20627_edge_closing_0.smt2                                    |  19.939s  |  19.939s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20638_terminationG_0.smt2                                |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20639_terminationG_0.smt2                                |  19.963s  |  19.963s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20650_terminationG_0.smt2                                |  20.082s  |  20.082s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20651_terminationG_0.smt2                                |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20652_terminationG_0.smt2                                |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20655_terminationG_0.smt2                                |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20656_terminationG_0.smt2                                |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20657_terminationG_0.smt2                                |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20661_edge_closing_0.smt2                                |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20662_edge_closing_0.smt2                                |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20668_edge_closing_0.smt2                                |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20669_edge_closing_0.smt2                                |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__terminationQ_1_0.smt2                                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |   0.927s  |   0.927s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20688_terminationG_0.smt2                                       |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20689_terminationG_0.smt2                                       |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20690_terminationG_0.smt2                                       |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20693_edge_closing_0.smt2                                       |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20694_edge_closing_0.smt2                                       |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__terminationS_1_0.smt2                                            |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|Stroeder_15__Benghazi_true-termination.c__p20729_terminationG_0.smt2                        |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20762_terminationG_0.smt2  |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20763_terminationG_0.smt2  |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20774_edge_closing_0.smt2  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20777_edge_closing_0.smt2  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-ICALP2005-Fig1_true-termination.c__p20810_terminationG_0.smt2  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-ICALP2005-Fig1_true-termination.c__p20814_terminationG_0.smt2  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Stroeder_15__BrockschmidtCookFuhs-CAV2013-Introduction_true-termination.c__p20837_terminationG_0.smt2  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20849_terminationG_0.smt2  |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20853_terminationG_0.smt2  |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20854_terminationG_0.smt2  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20855_terminationG_0.smt2  |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20858_terminationG_0.smt2  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20859_terminationG_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20860_terminationG_0.smt2  |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20863_terminationG_0.smt2  |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20864_terminationG_0.smt2  |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20865_terminationG_0.smt2  |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20868_terminationG_0.smt2  |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20869_terminationG_0.smt2  |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20870_terminationG_0.smt2  |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20873_terminationG_0.smt2  |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20874_terminationG_0.smt2  |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20875_terminationG_0.smt2  |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20888_terminationG_0.smt2  |   2.500s  |   2.500s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20892_terminationG_0.smt2  |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__ChenCookFuhsNimkarOHearn-TACAS2014-Introduction_false-termination.c__p20918_terminationG_0.smt2  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__ChenCookFuhsNimkarOHearn-TACAS2014-Introduction_false-termination.c__p20919_terminationG_0.smt2  |  19.943s  |  19.943s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20939_terminationG_0.smt2  |  19.172s  |  19.172s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20940_terminationG_0.smt2  |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20941_terminationG_0.smt2  |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.01_true-termination.c__p20984_terminationG_0.smt2  |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.01_true-termination.c__p20989_terminationG_0.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21003_terminationG_0.smt2  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21008_terminationG_0.smt2  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21011_terminationG_0.smt2  |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21012_terminationG_0.smt2  |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21013_terminationG_0.smt2  |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21016_terminationG_0.smt2  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21017_terminationG_0.smt2  |  19.909s  |  19.909s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21018_terminationG_0.smt2  |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21021_terminationG_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21022_terminationG_0.smt2  |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21023_terminationG_0.smt2  |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21026_terminationG_0.smt2  |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21027_terminationG_0.smt2  |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21031_terminationG_0.smt2  |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21032_terminationG_0.smt2  |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21033_terminationG_0.smt2  |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21056_terminationG_0.smt2  |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21057_terminationG_0.smt2  |  19.818s  |  19.818s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21058_terminationG_0.smt2  |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21079_terminationG_0.smt2  |   0.914s  |   0.914s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21083_terminationG_0.smt2  |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21084_terminationG_0.smt2  |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21085_terminationG_0.smt2  |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21107_terminationG_0.smt2  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21108_terminationG_0.smt2  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21112_terminationG_0.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21113_terminationG_0.smt2  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21116_terminationG_0.smt2  |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21118_terminationG_0.smt2  |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21122_terminationG_0.smt2  |   1.686s  |   1.686s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21123_terminationG_0.smt2  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21126_terminationG_0.smt2  |  19.740s  |  19.740s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21127_terminationG_0.smt2  |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21128_terminationG_0.smt2  |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21131_terminationG_0.smt2  |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21132_terminationG_0.smt2  |   6.803s  |   6.803s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21136_edge_closing_0.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21137_edge_closing_0.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21141_edge_closing_0.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21142_edge_closing_0.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21143_edge_closing_0.smt2  |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21144_edge_closing_0.smt2  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21148_edge_closing_0.smt2  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21149_edge_closing_0.smt2  |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21150_edge_closing_0.smt2  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.07_true-termination.c__terminationS_0_0.smt2  |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.08_true-termination.c__p21202_terminationG_0.smt2  |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.08_true-termination.c__p21203_terminationG_0.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21258_terminationG_0.smt2  |  19.467s  |  19.467s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21260_terminationG_0.smt2  |   1.604s  |   1.604s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21265_terminationG_0.smt2  |   2.303s  |   2.303s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21280_terminationG_0.smt2  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21283_terminationG_0.smt2  |   1.027s  |   1.027s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21285_terminationG_0.smt2  |   2.789s  |   2.789s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21288_terminationG_0.smt2  |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21290_terminationG_0.smt2  |   8.984s  |   8.984s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21293_terminationG_0.smt2  |   6.176s  |   6.176s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21294_terminationG_0.smt2  |   1.429s  |   1.429s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21295_terminationG_0.smt2  |   8.472s  |   8.472s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21298_terminationG_0.smt2  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21299_terminationG_0.smt2  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21300_terminationG_0.smt2  |  11.835s  |  11.835s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21303_terminationG_0.smt2  |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21304_terminationG_0.smt2  |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21305_terminationG_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21308_terminationG_0.smt2  |  19.921s  |  19.921s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21309_terminationG_0.smt2  |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21310_terminationG_0.smt2  |  19.952s  |  19.952s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21313_terminationG_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21314_terminationG_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21315_terminationG_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21318_terminationG_0.smt2  |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21319_terminationG_0.smt2  |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21320_terminationG_0.smt2  |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21323_terminationG_0.smt2  |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21324_terminationG_0.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21325_terminationG_0.smt2  |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21328_terminationG_0.smt2  |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21329_terminationG_0.smt2  |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21330_terminationG_0.smt2  |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__terminationS_0_0.smt2  |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21362_terminationG_0.smt2  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21367_terminationG_0.smt2  |   7.534s  |   7.534s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21371_terminationG_0.smt2  |   0.600s  |   0.600s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21372_terminationG_0.smt2  |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21376_terminationG_0.smt2  |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21377_terminationG_0.smt2  |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21382_terminationG_0.smt2  |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21385_terminationG_0.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21386_terminationG_0.smt2  |   0.589s  |   0.589s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21387_terminationG_0.smt2  |   1.010s  |   1.010s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21390_terminationG_0.smt2  |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21391_terminationG_0.smt2  |   5.683s  |   5.683s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21392_terminationG_0.smt2  |   4.684s  |   4.684s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21395_terminationG_0.smt2  |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21400_edge_closing_0.smt2  |   4.661s  |   4.661s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21401_edge_closing_0.smt2  |   2.839s  |   2.839s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.13_true-termination.c__p21424_terminationG_0.smt2  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21451_terminationG_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21452_terminationG_0.smt2  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21453_terminationG_0.smt2  |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__terminationQ_0_0.smt2  |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.15_false-termination.c__p21487_terminationG_0.smt2  |   2.235s  |   2.235s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.15_false-termination.c__p21491_terminationG_0.smt2  |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.15_false-termination.c__p21492_terminationG_0.smt2  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.16_true-termination.c__p21520_terminationG_0.smt2  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.16_true-termination.c__p21525_terminationG_0.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.16_true-termination.c__p21530_terminationG_0.smt2  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21539_terminationG_0.smt2  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21543_terminationG_0.smt2  |  10.313s  |  10.313s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21544_terminationG_0.smt2  |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21547_terminationG_0.smt2  |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21548_terminationG_0.smt2  |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21549_terminationG_0.smt2  |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21552_terminationG_0.smt2  |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21553_terminationG_0.smt2  |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21554_terminationG_0.smt2  |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.18_true-termination.c__p21582_terminationG_0.smt2  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.19_true-termination.c__p21598_terminationG_0.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.22_true-termination.c__p21645_terminationG_0.smt2  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.22_true-termination.c__p21649_terminationG_0.smt2  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.22_true-termination.c__p21650_terminationG_0.smt2  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21678_terminationG_0.smt2  |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21685_terminationG_0.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21690_terminationG_0.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21697_terminationG_0.smt2  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21702_terminationG_0.smt2  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21709_terminationG_0.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21719_terminationG_0.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21726_terminationG_0.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21727_terminationG_0.smt2  |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21728_terminationG_0.smt2  |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21732_terminationG_0.smt2  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21733_terminationG_0.smt2  |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21737_terminationG_0.smt2  |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21738_terminationG_0.smt2  |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21772_terminationG_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21774_terminationG_0.smt2  |   5.344s  |   5.344s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21780_terminationG_0.smt2  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21781_terminationG_0.smt2  |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21788_terminationG_0.smt2  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21793_terminationG_0.smt2  |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21794_terminationG_0.smt2  |   1.753s  |   1.753s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21795_terminationG_0.smt2  |   0.849s  |   0.849s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21802_terminationG_0.smt2  |   1.685s  |   1.685s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21803_terminationG_0.smt2  |   2.507s  |   2.507s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.04_true-termination.c__p21822_terminationG_0.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.04_true-termination.c__p21827_terminationG_0.smt2  |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21868_terminationG_0.smt2  |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21870_terminationG_0.smt2  |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21875_terminationG_0.smt2  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21876_terminationG_0.smt2  |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21877_terminationG_0.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21882_terminationG_0.smt2  |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21883_terminationG_0.smt2  |   2.361s  |   2.361s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21884_terminationG_0.smt2  |   0.946s  |   0.946s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21890_terminationG_0.smt2  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21891_terminationG_0.smt2  |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21892_terminationG_0.smt2  |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21895_terminationG_0.smt2  |   2.164s  |   2.164s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21896_terminationG_0.smt2  |   3.283s  |   3.283s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21897_terminationG_0.smt2  |   4.029s  |   4.029s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21905_terminationG_0.smt2  |   0.923s  |   0.923s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21906_terminationG_0.smt2  |   1.947s  |   1.947s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21907_terminationG_0.smt2  |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21910_terminationG_0.smt2  |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21911_terminationG_0.smt2  |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21912_terminationG_0.smt2  |  10.559s  |  10.559s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21922_terminationG_0.smt2  |  11.793s  |  11.793s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21923_terminationG_0.smt2  |   8.352s  |   8.352s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21924_terminationG_0.smt2  |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21927_terminationG_0.smt2  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21928_terminationG_0.smt2  |  18.781s  |  18.781s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21929_terminationG_0.smt2  |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21938_terminationG_0.smt2  |   9.645s  |   9.645s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21939_terminationG_0.smt2  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21940_terminationG_0.smt2  |   5.928s  |   5.928s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21943_terminationG_0.smt2  |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21944_terminationG_0.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21945_terminationG_0.smt2  |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21948_terminationG_0.smt2  |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21949_terminationG_0.smt2  |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21953_terminationG_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21954_terminationG_0.smt2  |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21955_terminationG_0.smt2  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21957_terminationG_0.smt2  |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21959_terminationG_0.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |  16.502s  |  16.502s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21963_terminationG_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21964_terminationG_0.smt2  |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21965_terminationG_0.smt2  |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21968_terminationG_0.smt2  |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21969_terminationG_0.smt2  |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21970_terminationG_0.smt2  |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21973_terminationG_0.smt2  |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21974_terminationG_0.smt2  |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21975_terminationG_0.smt2  |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21978_terminationG_0.smt2  |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21979_terminationG_0.smt2  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21980_terminationG_0.smt2  |  19.938s  |  19.938s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21983_terminationG_0.smt2  |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21984_terminationG_0.smt2  |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21985_terminationG_0.smt2  |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21988_terminationG_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21989_terminationG_0.smt2  |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21990_terminationG_0.smt2  |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21993_terminationG_0.smt2  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21994_terminationG_0.smt2  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21998_terminationG_0.smt2  |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21999_terminationG_0.smt2  |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22004_terminationG_0.smt2  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22005_terminationG_0.smt2  |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22006_terminationG_0.smt2  |  19.920s  |  19.920s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22009_terminationG_0.smt2  |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22010_terminationG_0.smt2  |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22011_terminationG_0.smt2  |  19.827s  |  19.827s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22014_terminationG_0.smt2  |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22015_terminationG_0.smt2  |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22016_terminationG_0.smt2  |  18.766s  |  18.766s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22019_terminationG_0.smt2  |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22020_terminationG_0.smt2  |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22021_terminationG_0.smt2  |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22023_edge_closing_0.smt2  |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22024_edge_closing_0.smt2  |   1.121s  |   1.121s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22025_edge_closing_0.smt2  |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__terminationQ_14_0.smt2  |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__terminationS_0_0.smt2  |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.07_true-termination.c__p22044_terminationG_0.smt2  |  19.804s  |  19.804s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.07_true-termination.c__p22045_terminationG_0.smt2  |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.08_true-termination.c__p22056_terminationG_0.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.08_true-termination.c__p22062_terminationG_0.smt2  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.08_true-termination.c__p22067_terminationG_0.smt2  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22103_terminationG_0.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22104_terminationG_0.smt2  |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22109_terminationG_0.smt2  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22113_terminationG_0.smt2  |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22114_terminationG_0.smt2  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22118_terminationG_0.smt2  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22119_terminationG_0.smt2  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22122_terminationG_0.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22123_terminationG_0.smt2  |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22124_terminationG_0.smt2  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22129_terminationG_0.smt2  |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22142_terminationG_0.smt2  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22147_terminationG_0.smt2  |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22148_terminationG_0.smt2  |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22158_terminationG_0.smt2  |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22160_terminationG_0.smt2  |   2.561s  |   2.561s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22169_terminationG_0.smt2  |   1.145s  |   1.145s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22170_terminationG_0.smt2  |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22177_terminationG_0.smt2                                           |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22178_terminationG_0.smt2                                           |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22182_terminationG_0.smt2                                           |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22183_terminationG_0.smt2                                           |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22184_terminationG_0.smt2                                           |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22189_edge_closing_0.smt2                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__term_unfeasibility_0_0.smt2                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__terminationQ_1_0.smt2                                                |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22199_terminationG_0.smt2                                       |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22200_terminationG_0.smt2                                       |  20.234s  |  20.234s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22201_terminationG_0.smt2                                       |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__term_unfeasibility_1_0.smt2                                      |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__terminationQ_0_0.smt2                                            |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22316_terminationG_0.smt2                                      |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22317_terminationG_0.smt2                                      |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22318_terminationG_0.smt2                                      |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22321_terminationG_0.smt2                                      |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22322_terminationG_0.smt2                                      |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22323_terminationG_0.smt2                                      |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22271_terminationG_0.smt2                                     |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22289_terminationG_0.smt2                                     |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22290_terminationG_0.smt2                                     |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22291_terminationG_0.smt2                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22294_terminationG_0.smt2                                     |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22295_terminationG_0.smt2                                     |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22296_terminationG_0.smt2                                     |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22332_terminationG_0.smt2                                      |   0.510s  |   0.510s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22336_terminationG_0.smt2                                      |   1.249s  |   1.249s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22337_terminationG_0.smt2                                      |   1.171s  |   1.171s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22340_terminationG_0.smt2                                      |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22341_terminationG_0.smt2                                      |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22365_edge_closing_0.smt2                                      |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__terminationQ_3_0.smt2                                           |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__terminationS_1_0.smt2                                           |  19.685s  |  19.685s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8a-modified_true-termination.c__p22401_terminationG_0.smt2  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22435_terminationG_0.smt2                                           |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22436_terminationG_0.smt2                                           |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22440_terminationG_0.smt2                                           |  19.759s  |  19.759s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22442_terminationG_0.smt2                                           |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22445_terminationG_0.smt2                                           |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22446_terminationG_0.smt2                                           |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22447_terminationG_0.smt2                                           |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22450_terminationG_0.smt2                                           |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22451_terminationG_0.smt2                                           |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22452_terminationG_0.smt2                                           |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22455_terminationG_0.smt2                                           |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22456_terminationG_0.smt2                                           |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22457_terminationG_0.smt2                                           |  19.926s  |  19.926s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22460_terminationG_0.smt2                                           |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22461_terminationG_0.smt2                                           |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22462_terminationG_0.smt2                                           |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__terminationS_0_0.smt2                                                |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22480_terminationG_0.smt2                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22481_terminationG_0.smt2                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22484_terminationG_0.smt2                                  |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22485_terminationG_0.smt2                                  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22494_terminationG_0.smt2                                  |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22495_terminationG_0.smt2                                  |  20.144s  |  20.144s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22496_terminationG_0.smt2                                  |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22499_terminationG_0.smt2                                  |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22500_terminationG_0.smt2                                  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22501_terminationG_0.smt2                                  |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22504_terminationG_0.smt2                                  |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22505_terminationG_0.smt2                                  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22506_terminationG_0.smt2                                  |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22514_edge_closing_0.smt2                                  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__terminationS_1_0.smt2                                       |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__terminationS_2_0.smt2                                       |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__terminationS_3_0.smt2                                       |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22530_terminationG_0.smt2                                        |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22531_terminationG_0.smt2                                        |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22535_terminationG_0.smt2                                        |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22536_terminationG_0.smt2                                        |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22537_terminationG_0.smt2                                        |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22540_terminationG_0.smt2                                        |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22541_terminationG_0.smt2                                        |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22542_terminationG_0.smt2                                        |  19.902s  |  19.902s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22545_terminationG_0.smt2                                        |  20.082s  |  20.082s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22546_terminationG_0.smt2                                        |  20.081s  |  20.081s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22547_terminationG_0.smt2                                        |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22550_terminationG_0.smt2                                        |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22551_terminationG_0.smt2                                        |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22552_terminationG_0.smt2                                        |  19.944s  |  19.944s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22555_terminationG_0.smt2                                        |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22556_terminationG_0.smt2                                        |  19.521s  |  19.521s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22557_terminationG_0.smt2                                        |  20.161s  |  20.161s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__terminationQ_5_0.smt2                                             |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22575_terminationG_0.smt2                                              |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22594_terminationG_0.smt2                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|Stroeder_15__Et2.c__p22608_terminationG_0.smt2                                              |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__Et2.c__p22609_terminationG_0.smt2                                              |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22640_terminationG_0.smt2                                              |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22641_terminationG_0.smt2                                              |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22653_edge_closing_0.smt2                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22658_edge_closing_0.smt2                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22659_edge_closing_0.smt2                                              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__terminationS_0_0.smt2                                                   |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22671_terminationG_0.smt2                                             |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22672_terminationG_0.smt2                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |  19.863s  |  19.863s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22676_terminationG_0.smt2                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22677_terminationG_0.smt2                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22678_terminationG_0.smt2                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22698_terminationG_0.smt2                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22699_terminationG_0.smt2                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22700_terminationG_0.smt2                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22750_terminationG_0.smt2                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22752_terminationG_0.smt2                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__Ex06.c__p22785_edge_closing_0.smt2                                             |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22818_terminationG_0.smt2                                             |   2.694s  |   2.694s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |   1.247s  |   1.247s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22820_terminationG_0.smt2                                             |   6.953s  |   6.953s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22835_terminationG_0.smt2                                        |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22836_terminationG_0.smt2                                        |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22837_terminationG_0.smt2                                        |   6.268s  |   6.268s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22842_terminationG_0.smt2                                        |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22843_terminationG_0.smt2                                        |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22844_terminationG_0.smt2                                        |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22847_terminationG_0.smt2                                        |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22848_terminationG_0.smt2                                        |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22849_terminationG_0.smt2                                        |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22853_terminationG_0.smt2                                        |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22857_terminationG_0.smt2                                        |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22858_terminationG_0.smt2                                        |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22859_terminationG_0.smt2                                        |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__terminationQ_3_0.smt2                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   2.685s  |   2.685s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22868_terminationG_0.smt2                                        |   9.367s  |   9.367s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22873_terminationG_0.smt2                                        |  14.075s  |  14.075s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22879_terminationG_0.smt2                                        |   2.081s  |   2.081s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22880_terminationG_0.smt2                                        |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22883_terminationG_0.smt2                                        |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22884_terminationG_0.smt2                                        |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22885_terminationG_0.smt2                                        |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22888_terminationG_0.smt2                                        |  20.225s  |  20.225s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22889_terminationG_0.smt2                                        |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22890_terminationG_0.smt2                                        |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22893_terminationG_0.smt2                                        |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22895_terminationG_0.smt2                                        |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22896_terminationG_0.smt2                                        |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22899_terminationG_0.smt2                                        |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22900_terminationG_0.smt2                                        |  19.952s  |  19.952s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22901_terminationG_0.smt2                                        |  20.157s  |  20.157s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__terminationQ_3_0.smt2                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p22994_terminationG_0.smt2                                             |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23021_terminationG_0.smt2                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23022_terminationG_0.smt2                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23033_edge_closing_0.smt2                                             |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23038_edge_closing_0.smt2                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23039_edge_closing_0.smt2                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22917_terminationG_0.smt2                                            |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22918_terminationG_0.smt2                                            |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22927_terminationG_0.smt2                                            |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22933_terminationG_0.smt2                                            |   2.213s  |   2.213s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22937_terminationG_0.smt2                                            |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22938_terminationG_0.smt2                                            |  20.565s  |  20.565s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22942_edge_closing_0.smt2                                            |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23156_terminationG_0.smt2                                              |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23157_terminationG_0.smt2                                              |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23158_terminationG_0.smt2                                              |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23167_terminationG_0.smt2                                              |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23168_terminationG_0.smt2                                              |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23171_terminationG_0.smt2                                              |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23172_terminationG_0.smt2                                              |   3.552s  |   3.552s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23178_terminationG_0.smt2                                              |   2.974s  |   2.974s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23179_terminationG_0.smt2                                              |  19.895s  |  19.895s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23180_terminationG_0.smt2                                              |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23183_terminationG_0.smt2                                              |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23184_terminationG_0.smt2                                              |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23185_terminationG_0.smt2                                              |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23188_terminationG_0.smt2                                              |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23189_terminationG_0.smt2                                              |   1.845s  |   1.845s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23190_terminationG_0.smt2                                              |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23200_terminationG_0.smt2                                              |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23201_terminationG_0.smt2                                              |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23202_terminationG_0.smt2                                              |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23206_terminationG_0.smt2                                              |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23207_terminationG_0.smt2                                              |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23210_terminationG_0.smt2                                              |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23211_terminationG_0.smt2                                              |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23212_terminationG_0.smt2                                              |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23215_edge_closing_0.smt2                                              |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23216_edge_closing_0.smt2                                              |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23222_edge_closing_0.smt2                                              |   2.330s  |   2.330s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23223_edge_closing_0.smt2                                              |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_0_0.smt2                                                   |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_1_0.smt2                                                   |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_8_0.smt2                                                   |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23102_terminationG_0.smt2                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23106_terminationG_0.smt2                                             |  14.731s  |  14.731s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23107_terminationG_0.smt2                                             |  17.591s  |  17.591s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23110_terminationG_0.smt2                                             |   6.208s  |   6.208s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23111_terminationG_0.smt2                                             |   7.942s  |   7.942s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23112_terminationG_0.smt2                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23116_terminationG_0.smt2                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23117_terminationG_0.smt2                                             |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23120_terminationG_0.smt2                                             |  20.082s  |  20.082s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23121_terminationG_0.smt2                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23122_terminationG_0.smt2                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23125_edge_closing_0.smt2                                             |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23126_edge_closing_0.smt2                                             |   1.465s  |   1.465s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23050_terminationG_0.smt2                                            |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23054_terminationG_0.smt2                                            |  20.086s  |  20.086s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23055_terminationG_0.smt2                                            |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23056_terminationG_0.smt2                                            |  19.878s  |  19.878s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23059_terminationG_0.smt2                                            |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23060_terminationG_0.smt2                                            |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23061_terminationG_0.smt2                                            |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23064_terminationG_0.smt2                                            |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23065_terminationG_0.smt2                                            |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23066_terminationG_0.smt2                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23069_terminationG_0.smt2                                            |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23070_terminationG_0.smt2                                            |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23071_terminationG_0.smt2                                            |  19.811s  |  19.811s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23074_terminationG_0.smt2                                            |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23075_terminationG_0.smt2                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23076_terminationG_0.smt2                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__Gothenburg_true-termination.c__p23242_terminationG_0.smt2                      |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__Gothenburg_true-termination.c__p23243_terminationG_0.smt2                      |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23267_terminationG_0.smt2  |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23268_terminationG_0.smt2  |  10.308s  |  10.308s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23269_terminationG_0.smt2  |   3.720s  |   3.720s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23272_terminationG_0.smt2  |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23273_terminationG_0.smt2  |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23274_terminationG_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23277_edge_closing_0.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23278_edge_closing_0.smt2  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23280_edge_closing_0.smt2  |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23281_edge_closing_0.smt2  |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23282_edge_closing_0.smt2  |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23283_edge_closing_0.smt2  |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23284_edge_closing_0.smt2  |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23285_edge_closing_0.smt2  |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23288_edge_closing_0.smt2  |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23291_edge_closing_0.smt2  |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23319_edge_closing_0.smt2  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23321_edge_closing_0.smt2  |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23322_edge_closing_0.smt2  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23328_edge_closing_0.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23330_edge_closing_0.smt2  |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23331_edge_closing_0.smt2  |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23333_edge_closing_0.smt2  |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23334_edge_closing_0.smt2  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23336_edge_closing_0.smt2  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23339_edge_closing_0.smt2  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23340_edge_closing_0.smt2  |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23343_edge_closing_0.smt2  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23367_edge_closing_0.smt2  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23403_edge_closing_0.smt2  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23406_edge_closing_0.smt2  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23408_edge_closing_0.smt2  |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23409_edge_closing_0.smt2  |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23412_edge_closing_0.smt2  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23421_edge_closing_0.smt2  |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23429_edge_closing_0.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23430_edge_closing_0.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23431_edge_closing_0.smt2  |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23432_edge_closing_0.smt2  |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23433_edge_closing_0.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23435_edge_closing_0.smt2  |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23436_edge_closing_0.smt2  |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23438_edge_closing_0.smt2  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23439_edge_closing_0.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23441_edge_closing_0.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23442_edge_closing_0.smt2  |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23443_edge_closing_0.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23444_edge_closing_0.smt2  |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23445_edge_closing_0.smt2  |   0.462s  |   0.462s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23450_edge_closing_0.smt2  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23451_edge_closing_0.smt2  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23459_edge_closing_0.smt2  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23460_edge_closing_0.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23471_edge_closing_0.smt2  |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23473_edge_closing_0.smt2  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23474_edge_closing_0.smt2  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23475_edge_closing_0.smt2  |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23477_edge_closing_0.smt2  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23478_edge_closing_0.smt2  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23480_edge_closing_0.smt2  |   0.969s  |   0.969s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23482_edge_closing_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23483_edge_closing_0.smt2  |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23484_edge_closing_0.smt2  |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23486_edge_closing_0.smt2  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23487_edge_closing_0.smt2  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23493_edge_closing_0.smt2  |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23501_edge_closing_0.smt2  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23502_edge_closing_0.smt2  |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23510_edge_closing_0.smt2  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23522_edge_closing_0.smt2  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23523_edge_closing_0.smt2  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23531_edge_closing_0.smt2  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23532_edge_closing_0.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23543_edge_closing_0.smt2  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23544_edge_closing_0.smt2  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23550_edge_closing_0.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23551_edge_closing_0.smt2  |   1.094s  |   1.094s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23559_edge_closing_0.smt2  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23560_edge_closing_0.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23565_edge_closing_0.smt2  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23566_edge_closing_0.smt2  |   3.626s  |   3.626s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23577_edge_closing_0.smt2  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23602_edge_closing_0.smt2  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23611_edge_closing_0.smt2  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23616_edge_closing_0.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23617_edge_closing_0.smt2  |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23620_edge_closing_0.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23628_edge_closing_0.smt2  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23629_edge_closing_0.smt2  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23638_edge_closing_0.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23646_edge_closing_0.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23647_edge_closing_0.smt2  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23649_edge_closing_0.smt2  |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23650_edge_closing_0.smt2  |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23653_edge_closing_0.smt2  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23662_edge_closing_0.smt2  |   0.495s  |   0.495s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23667_edge_closing_0.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23673_edge_closing_0.smt2  |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23676_edge_closing_0.smt2  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23677_edge_closing_0.smt2  |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23679_edge_closing_0.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23680_edge_closing_0.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23686_edge_closing_0.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23692_edge_closing_0.smt2  |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23693_edge_closing_0.smt2  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23699_edge_closing_0.smt2  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23701_edge_closing_0.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23702_edge_closing_0.smt2  |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23703_edge_closing_0.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23704_edge_closing_0.smt2  |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23705_edge_closing_0.smt2  |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23710_edge_closing_0.smt2  |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23711_edge_closing_0.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23713_edge_closing_0.smt2  |   1.515s  |   1.515s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23714_edge_closing_0.smt2  |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23715_edge_closing_0.smt2  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23716_edge_closing_0.smt2  |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23717_edge_closing_0.smt2  |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23722_edge_closing_0.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23723_edge_closing_0.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23731_edge_closing_0.smt2  |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23732_edge_closing_0.smt2  |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23734_edge_closing_0.smt2  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23735_edge_closing_0.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23750_edge_closing_0.smt2  |   0.378s  |   0.378s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23751_edge_closing_0.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23752_edge_closing_0.smt2  |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23753_edge_closing_0.smt2  |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23754_edge_closing_0.smt2  |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23756_edge_closing_0.smt2  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   0.714s  |   0.714s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23759_edge_closing_0.smt2  |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23760_edge_closing_0.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23765_edge_closing_0.smt2  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23766_edge_closing_0.smt2  |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23774_edge_closing_0.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23775_edge_closing_0.smt2  |   1.361s  |   1.361s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23795_edge_closing_0.smt2  |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23796_edge_closing_0.smt2  |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23863_terminationG_0.smt2  |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23864_terminationG_0.smt2  |   0.679s  |   0.679s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23872_terminationG_0.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23873_terminationG_0.smt2  |   6.438s  |   6.438s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23877_terminationG_0.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23878_terminationG_0.smt2  |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23886_terminationG_0.smt2  |   3.235s  |   3.235s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23887_terminationG_0.smt2  |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23893_terminationG_0.smt2  |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23894_terminationG_0.smt2  |   2.705s  |   2.705s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23905_terminationG_0.smt2                                              |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23906_terminationG_0.smt2                                              |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23910_terminationG_0.smt2                                              |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23911_terminationG_0.smt2                                              |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23918_terminationG_0.smt2                                              |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23923_terminationG_0.smt2                                              |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23927_terminationG_0.smt2                                              |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23933_terminationG_0.smt2                                              |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23941_terminationG_0.smt2                                              |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23942_terminationG_0.smt2                                              |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23947_terminationG_0.smt2                                              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23951_terminationG_0.smt2                                              |  19.901s  |  19.901s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23952_terminationG_0.smt2                                              |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23956_edge_closing_0.smt2                                              |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23960_edge_closing_0.smt2                                              |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-TACAS2014-Ex7_true-termination.c__p23983_terminationG_0.smt2     |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-TACAS2014-Fig1_true-termination.c__p24009_terminationG_0.smt2    |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24084_terminationG_0.smt2      |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24085_terminationG_0.smt2      |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24086_terminationG_0.smt2      |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24090_terminationG_0.smt2      |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24091_terminationG_0.smt2      |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24094_terminationG_0.smt2      |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24095_terminationG_0.smt2      |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24096_terminationG_0.smt2      |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24099_terminationG_0.smt2      |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24100_terminationG_0.smt2      |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24101_terminationG_0.smt2      |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24121_terminationG_0.smt2        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__terminationQ_3_0.smt2                                               |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24211_terminationG_0.smt2                                          |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24212_terminationG_0.smt2                                          |  19.942s  |  19.942s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24213_terminationG_0.smt2                                          |  19.880s  |  19.880s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24216_terminationG_0.smt2                                          |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24217_terminationG_0.smt2                                          |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24218_terminationG_0.smt2                                          |  20.450s  |  20.450s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24236_terminationG_0.smt2           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24237_terminationG_0.smt2           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24238_terminationG_0.smt2           |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24241_terminationG_0.smt2           |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24242_terminationG_0.smt2           |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24247_terminationG_0.smt2           |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24248_terminationG_0.smt2           |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24250_edge_closing_0.smt2           |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24252_edge_closing_0.smt2           |  20.139s  |  20.139s  |   0.000s  | 0.0%|
|Stroeder_15__McCarthyIterative.c__term_unfeasibility_0_0.smt2                               |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__MenloPark_true-termination.c__p24273_terminationG_0.smt2                       |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__MenloPark_true-termination.c__p24274_terminationG_0.smt2                       |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24281_terminationG_0.smt2                                           |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24282_terminationG_0.smt2                                           |   1.183s  |   1.183s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24283_terminationG_0.smt2                                           |   5.598s  |   5.598s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24288_terminationG_0.smt2                                           |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24289_terminationG_0.smt2                                           |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24290_terminationG_0.smt2                                           |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24301_terminationG_0.smt2                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24306_terminationG_0.smt2                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24309_terminationG_0.smt2                                           |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24310_terminationG_0.smt2                                           |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24311_terminationG_0.smt2                                           |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24314_terminationG_0.smt2                                           |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24315_terminationG_0.smt2                                           |  19.943s  |  19.943s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24316_terminationG_0.smt2                                           |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24319_terminationG_0.smt2                                           |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24320_terminationG_0.smt2                                           |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24321_terminationG_0.smt2                                           |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24324_terminationG_0.smt2                                           |  19.912s  |  19.912s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24325_terminationG_0.smt2                                           |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24326_terminationG_0.smt2                                           |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24329_terminationG_0.smt2                                           |  19.872s  |  19.872s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24330_terminationG_0.smt2                                           |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24331_terminationG_0.smt2                                           |  19.875s  |  19.875s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24334_terminationG_0.smt2                                           |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24335_terminationG_0.smt2                                           |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24336_terminationG_0.smt2                                           |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24339_edge_closing_0.smt2                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24344_edge_closing_0.smt2                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24368_terminationG_0.smt2                                     |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24373_terminationG_0.smt2                                     |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24374_terminationG_0.smt2                                     |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24377_terminationG_0.smt2                                     |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24378_terminationG_0.smt2                                     |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24379_terminationG_0.smt2                                     |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24413_edge_closing_0.smt2                                     |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24415_edge_closing_0.smt2                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24422_edge_closing_0.smt2                                     |   4.503s  |   4.503s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24426_edge_closing_0.smt2                                     |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24432_edge_closing_0.smt2                                     |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24443_edge_closing_0.smt2                                     |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24446_edge_closing_0.smt2                                     |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24447_edge_closing_0.smt2                                     |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24449_edge_closing_0.smt2                                     |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24450_edge_closing_0.smt2                                     |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__terminationQ_5_0.smt2                                          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__terminationS_0_0.smt2                                          |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__terminationS_1_0.smt2                                          |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24464_terminationG_0.smt2                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24482_terminationG_0.smt2                                  |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24484_terminationG_0.smt2                                  |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationQ_0_0.smt2                                       |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_1_0.smt2                                       |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__NO_03.c__p24634_terminationG_0.smt2                                            |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__NO_03.c__terminationQ_0_0.smt2                                                 |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24648_safety_0.smt2                                                  |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24649_safety_0.smt2                                                  |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24650_safety_0.smt2                                                  |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24651_safety_0.smt2                                                  |  19.829s  |  19.829s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24653_safety_0.smt2                                                  |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24654_safety_0.smt2                                                  |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__term_unfeasibility_0_0.smt2                                           |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__term_unfeasibility_2_0.smt2                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__term_unfeasibility_4_0.smt2                                           |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24669_terminationG_0.smt2                                            |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24671_terminationG_0.smt2                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24674_terminationG_0.smt2                                            |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24675_terminationG_0.smt2                                            |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24676_terminationG_0.smt2                                            |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24679_terminationG_0.smt2                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24680_terminationG_0.smt2                                            |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24681_terminationG_0.smt2                                            |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24684_terminationG_0.smt2                                            |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24685_terminationG_0.smt2                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24686_terminationG_0.smt2                                            |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24689_terminationG_0.smt2                                            |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24690_terminationG_0.smt2                                            |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24691_terminationG_0.smt2                                            |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24694_terminationG_0.smt2                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24695_terminationG_0.smt2                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24696_terminationG_0.smt2                                            |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__terminationQ_5_0.smt2                                                 |  19.807s  |  19.807s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24711_terminationG_0.smt2                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24713_terminationG_0.smt2                                            |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24716_terminationG_0.smt2                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24717_terminationG_0.smt2                                            |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24718_terminationG_0.smt2                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24721_terminationG_0.smt2                                            |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24722_terminationG_0.smt2                                            |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24723_terminationG_0.smt2                                            |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24726_terminationG_0.smt2                                            |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24728_terminationG_0.smt2                                            |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24730_terminationG_0.smt2                                            |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24732_terminationG_0.smt2                                            |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24733_terminationG_0.smt2                                            |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24737_edge_closing_0.smt2                                            |   6.224s  |   6.224s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationQ_4_0.smt2                                                 |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_1_0.smt2                                                 |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24748_terminationG_0.smt2                                            |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24750_terminationG_0.smt2                                            |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24752_edge_closing_0.smt2                                            |  19.603s  |  19.603s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__term_unfeasibility_0_0.smt2                                           |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__terminationQ_0_0.smt2                                                 |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__terminationS_0_0.smt2                                                 |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__terminationS_1_0.smt2                                                 |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24780_terminationG_0.smt2                                            |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24781_terminationG_0.smt2                                            |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24782_terminationG_0.smt2                                            |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24785_edge_closing_0.smt2                                            |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24786_edge_closing_0.smt2                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__term_unfeasibility_0_0.smt2                                           |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__terminationS_0_0.smt2                                                 |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24797_terminationG_0.smt2                                            |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24798_terminationG_0.smt2                                            |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24799_terminationG_0.smt2                                            |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24804_edge_closing_0.smt2                                            |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__term_unfeasibility_0_0.smt2                                           |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__terminationQ_0_0.smt2                                                 |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__terminationS_0_0.smt2                                                 |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__terminationS_1_0.smt2                                                 |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__NO_24.c__p24815_terminationG_0.smt2                                            |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__NO_24.c__p24816_terminationG_0.smt2                                            |  19.839s  |  19.839s  |   0.000s  | 0.0%|
|Stroeder_15__NO_24.c__p24820_edge_closing_0.smt2                                            |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|Stroeder_15__NarrowKonv.c__p24579_edge_closing_0.smt2                                       |   4.560s  |   4.560s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24515_terminationG_0.smt2                                        |   4.422s  |   4.422s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24516_terminationG_0.smt2                                        |   3.256s  |   3.256s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24519_terminationG_0.smt2                                        |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24520_terminationG_0.smt2                                        |   2.217s  |   2.217s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24521_terminationG_0.smt2                                        |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24524_terminationG_0.smt2                                        |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24525_terminationG_0.smt2                                        |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24526_terminationG_0.smt2                                        |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24529_terminationG_0.smt2                                        |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24530_terminationG_0.smt2                                        |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24531_terminationG_0.smt2                                        |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24534_terminationG_0.smt2                                        |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24535_terminationG_0.smt2                                        |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24536_terminationG_0.smt2                                        |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24544_edge_closing_0.smt2                                        |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24545_edge_closing_0.smt2                                        |  19.886s  |  19.886s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24547_edge_closing_0.smt2                                        |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24548_edge_closing_0.smt2                                        |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24549_edge_closing_0.smt2                                        |   0.559s  |   0.559s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__term_unfeasibility_2_0.smt2                                       |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationQ_0_0.smt2                                             |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_0_0.smt2                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_1_0.smt2                                             |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_2_0.smt2                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_3_0.smt2                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24888_terminationG_0.smt2                |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24896_terminationG_0.smt2                |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24897_terminationG_0.smt2                |  11.609s  |  11.609s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24907_terminationG_0.smt2                |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24908_terminationG_0.smt2                |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24918_terminationG_0.smt2                |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24919_terminationG_0.smt2                |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24923_terminationG_0.smt2                |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24924_terminationG_0.smt2                |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |   1.798s  |   1.798s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24935_edge_closing_0.smt2                |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24939_edge_closing_0.smt2                |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24941_edge_closing_0.smt2                |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24949_terminationG_0.smt2                |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24950_terminationG_0.smt2                |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24953_terminationG_0.smt2                |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24954_terminationG_0.smt2                |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24957_terminationG_0.smt2                |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24959_terminationG_0.smt2                |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24960_terminationG_0.smt2                |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24967_terminationG_0.smt2                |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24969_terminationG_0.smt2                |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24970_terminationG_0.smt2                |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24973_terminationG_0.smt2                |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24974_terminationG_0.smt2                |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24975_terminationG_0.smt2                |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__terminationQ_4_0.smt2                     |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p24995_terminationG_0.smt2          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p24996_terminationG_0.smt2          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p24997_terminationG_0.smt2          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p25000_terminationG_0.smt2          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p25001_terminationG_0.smt2          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p25002_terminationG_0.smt2          |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple3_false-termination.c__p25033_terminationG_0.smt2          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple3_false-termination.c__p25034_terminationG_0.smt2          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25081_edge_closing_0.smt2          |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__terminationQ_3_0.smt2               |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple5_false-termination.c__p25094_terminationG_0.smt2          |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple5_false-termination.c__p25098_terminationG_0.smt2          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple5_false-termination.c__p25099_terminationG_0.smt2          |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25119_terminationG_0.smt2          |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25120_terminationG_0.smt2          |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25124_terminationG_0.smt2          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25125_terminationG_0.smt2          |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25126_terminationG_0.smt2          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25130_edge_closing_0.smt2          |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple7_false-termination.c__p25147_terminationG_0.smt2          |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple7_false-termination.c__p25148_terminationG_0.smt2          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple7_false-termination.c__p25159_edge_closing_0.smt2          |  11.826s  |  11.826s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25174_terminationG_0.smt2          |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25175_terminationG_0.smt2          |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25176_terminationG_0.smt2          |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25179_terminationG_0.smt2          |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25180_terminationG_0.smt2          |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25181_terminationG_0.smt2          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25184_edge_closing_0.smt2          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25189_edge_closing_0.smt2          |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25202_terminationG_0.smt2          |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |  19.930s  |  19.930s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25336_terminationG_0.smt2                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25382_terminationG_0.smt2                                         |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25387_terminationG_0.smt2                                         |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25391_terminationG_0.smt2                                         |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25392_terminationG_0.smt2                                         |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig1_true-termination.c__p25400_terminationG_0.smt2  |   1.614s  |   1.614s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25419_terminationG_0.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25424_terminationG_0.smt2  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25425_terminationG_0.smt2  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25430_terminationG_0.smt2  |   0.954s  |   0.954s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25433_terminationG_0.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25434_terminationG_0.smt2  |  10.717s  |  10.717s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25435_terminationG_0.smt2  |   5.984s  |   5.984s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25440_terminationG_0.smt2  |   7.152s  |   7.152s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25441_terminationG_0.smt2  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25442_terminationG_0.smt2  |  19.932s  |  19.932s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25447_terminationG_0.smt2  |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25448_terminationG_0.smt2  |  14.676s  |  14.676s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25449_terminationG_0.smt2  |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25476_terminationG_0.smt2  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25479_terminationG_0.smt2  |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25480_terminationG_0.smt2  |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25481_terminationG_0.smt2  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25484_edge_closing_0.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25485_edge_closing_0.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25505_terminationG_0.smt2                      |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25506_terminationG_0.smt2                      |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25507_terminationG_0.smt2                      |   8.816s  |   8.816s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25519_terminationG_0.smt2                      |   3.683s  |   3.683s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25530_terminationG_0.smt2                      |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25531_terminationG_0.smt2                      |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25532_terminationG_0.smt2                      |   2.979s  |   2.979s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25536_terminationG_0.smt2                      |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25537_terminationG_0.smt2                      |   1.304s  |   1.304s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25541_terminationG_0.smt2                      |   0.625s  |   0.625s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25542_terminationG_0.smt2                      |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25546_terminationG_0.smt2                      |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25547_terminationG_0.smt2                      |   2.075s  |   2.075s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25559_terminationG_0.smt2                      |   8.227s  |   8.227s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25560_terminationG_0.smt2                      |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25566_terminationG_0.smt2                      |   0.360s  |   0.360s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25567_terminationG_0.smt2                      |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|Stroeder_15__Rotation180_false-termination.c__p25579_terminationG_0.smt2                    |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__Rotation180_false-termination.c__p25580_terminationG_0.smt2                    |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25604_terminationG_0.smt2                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25629_edge_closing_0.smt2                                           |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__terminationQ_0_0.smt2                                                |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__terminationS_0_0.smt2                                                |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__terminationS_1_0.smt2                                                |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__Swingers.c__p26084_terminationG_0.smt2                                         |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|Stroeder_15__Swingers.c__p26085_terminationG_0.smt2                                         |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Stroeder_15__Swingers.c__p26089_edge_closing_0.smt2                                         |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-BranchesToLoop_true-termination.c__p26120_terminationG_0.smt2         |  19.928s  |  19.928s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-BranchesToLoop_true-termination.c__p26125_terminationG_0.smt2         |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-MultiBranchesToLoop_true-termination.c__p26134_terminationG_0.smt2    |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-MultiBranchesToLoop_true-termination.c__p26139_terminationG_0.smt2    |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|Stroeder_15__TwoFloatInterv.c__p26181_edge_closing_0.smt2                                   |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26197_terminationG_0.smt2                                        |   4.740s  |   4.740s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26198_terminationG_0.smt2                                        |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26203_terminationG_0.smt2                                        |  19.864s  |  19.864s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26206_edge_closing_0.smt2                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26207_edge_closing_0.smt2                                        |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26213_edge_closing_0.smt2                                        |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26214_edge_closing_0.smt2                                        |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__terminationS_3_0.smt2                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26230_terminationG_0.smt2                                    |   0.921s  |   0.921s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26231_terminationG_0.smt2                                    |   1.939s  |   1.939s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26235_terminationG_0.smt2                                    |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26236_terminationG_0.smt2                                    |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26239_edge_closing_0.smt2                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26240_edge_closing_0.smt2                                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26246_edge_closing_0.smt2                                    |  14.305s  |  14.305s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26247_edge_closing_0.smt2                                    |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig1_false-termination.c__p26265_safety_0.smt2                   |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig1_false-termination.c__p26266_safety_0.smt2                   |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig2-modified1000_true-termination.c__term_unfeasibility_0_0.smt2  |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig2_true-termination.c__term_unfeasibility_0_0.smt2             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26291_terminationG_0.smt2                       |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26301_terminationG_0.smt2                       |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26335_terminationG_0.smt2                       |  20.144s  |  20.144s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26336_terminationG_0.smt2                       |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__terminationQ_0_0.smt2                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__terminationS_0_0.smt2                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__terminationS_1_0.smt2                            |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26374_terminationG_0.smt2                                        |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26375_terminationG_0.smt2                                        |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26376_terminationG_0.smt2                                        |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26380_terminationG_0.smt2                                        |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26381_terminationG_0.smt2                                        |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26429_terminationG_0.smt2                                      |  19.925s  |  19.925s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26430_terminationG_0.smt2                                      |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26431_terminationG_0.smt2                                      |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26434_terminationG_0.smt2                                      |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26435_terminationG_0.smt2                                      |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26436_terminationG_0.smt2                                      |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__terminationQ_1_0.smt2                                           |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26452_terminationG_0.smt2                                |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26453_terminationG_0.smt2                                |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26456_terminationG_0.smt2                                |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26457_terminationG_0.smt2                                |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__terminationQ_1_0.smt2                                     |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|Stroeder_15__WhileSingle.c__p26489_edge_closing_0.smt2                                      |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20348_terminationG_0.smt2                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20359_terminationG_0.smt2                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20363_terminationG_0.smt2                          |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20364_terminationG_0.smt2                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20368_terminationG_0.smt2                          |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20369_terminationG_0.smt2                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__term_unfeasibility_1_0.smt2                                         |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__terminationQ_0_0.smt2                                               |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__terminationS_0_0.smt2                                               |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__terminationS_1_0.smt2                                               |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_a.10.c__p25674_terminationG_0.smt2                                      |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_a.10.c__p25675_terminationG_0.smt2                                      |   2.864s  |   2.864s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   1.693s  |   1.693s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25769_terminationG_0.smt2                               |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01_assume.c__term_unfeasibility_0_0.smt2                              |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25801_terminationG_0.smt2                                       |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25806_terminationG_0.smt2                                       |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25815_terminationG_0.smt2                                       |   2.587s  |   2.587s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   5.426s  |   5.426s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25817_terminationG_0.smt2                                       |  10.100s  |  10.100s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25820_terminationG_0.smt2                                       |  13.606s  |  13.606s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |   8.778s  |   8.778s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25825_terminationG_0.smt2                                       |   5.408s  |   5.408s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25826_terminationG_0.smt2                                       |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25827_terminationG_0.smt2                                       |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25832_terminationG_0.smt2                                       |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25835_terminationG_0.smt2                                       |  19.836s  |  19.836s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25836_terminationG_0.smt2                                       |  20.150s  |  20.150s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |  12.352s  |  12.352s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25843_terminationG_0.smt2                                       |   0.395s  |   0.395s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   5.589s  |   5.589s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   1.663s  |   1.663s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25848_terminationG_0.smt2                                       |   9.398s  |   9.398s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25852_terminationG_0.smt2                                       |   1.888s  |   1.888s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  10.438s  |  10.438s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationQ_27_0.smt2                                           |  19.933s  |  19.933s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__terminationQ_1_0.smt2                                           |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26023_terminationG_0.smt2                                      |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__terminationQ_3_0.smt2                                           |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26532_terminationG_0.smt2                       |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26535_terminationG_0.smt2                       |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26536_terminationG_0.smt2                       |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26537_terminationG_0.smt2                       |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26540_terminationG_0.smt2                       |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26541_terminationG_0.smt2                       |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26542_terminationG_0.smt2                       |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26545_terminationG_0.smt2                       |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26546_terminationG_0.smt2                       |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       |  19.930s  |  19.930s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26550_terminationG_0.smt2                       |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26551_terminationG_0.smt2                       |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26552_terminationG_0.smt2                       |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26556_terminationG_0.smt2                       |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26568_edge_closing_0.smt2                       |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26581_terminationG_0.smt2                     |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v2_false-termination.c__p26608_terminationG_0.smt2                  |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v2_false-termination.c__p26609_terminationG_0.smt2                  |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v3_false-termination.c__p26641_terminationG_0.smt2                  |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v3_false-termination.c__p26642_terminationG_0.smt2                  |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26677_terminationG_0.smt2                |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   1.845s  |   1.845s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26679_terminationG_0.smt2                |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26689_terminationG_0.smt2                |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26690_terminationG_0.smt2                |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26705_terminationG_0.smt2                  |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26706_terminationG_0.smt2                  |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26707_terminationG_0.smt2                  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26710_terminationG_0.smt2                  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26711_terminationG_0.smt2                  |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26712_terminationG_0.smt2                  |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26739_edge_closing_0.smt2                   |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__terminationQ_1_0.smt2                        |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26761_terminationG_0.smt2                |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26768_terminationG_0.smt2                |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26769_terminationG_0.smt2                |   1.449s  |   1.449s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26770_terminationG_0.smt2                |   2.215s  |   2.215s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26775_terminationG_0.smt2                |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26776_terminationG_0.smt2                |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26782_terminationG_0.smt2                |  19.948s  |  19.948s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26783_terminationG_0.smt2                |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26789_terminationG_0.smt2                |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26790_terminationG_0.smt2                |   1.762s  |   1.762s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26797_terminationG_0.smt2                |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26799_terminationG_0.smt2                |   1.476s  |   1.476s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26806_terminationG_0.smt2                |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26807_terminationG_0.smt2                |   4.113s  |   4.113s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26808_terminationG_0.smt2                |   4.821s  |   4.821s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26817_terminationG_0.smt2                |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26818_terminationG_0.smt2                |   4.502s  |   4.502s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26819_terminationG_0.smt2                |  11.357s  |  11.357s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26829_terminationG_0.smt2                |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26830_terminationG_0.smt2                |  11.265s  |  11.265s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26831_terminationG_0.smt2                |   6.675s  |   6.675s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26839_terminationG_0.smt2                |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26840_terminationG_0.smt2                |   5.147s  |   5.147s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26841_terminationG_0.smt2                |  17.908s  |  17.908s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26844_terminationG_0.smt2                |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26845_terminationG_0.smt2                |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26846_terminationG_0.smt2                |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26849_edge_closing_0.smt2                |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26850_edge_closing_0.smt2                |   2.505s  |   2.505s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26853_edge_closing_0.smt2                |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26856_edge_closing_0.smt2                |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26857_edge_closing_0.smt2                |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26858_edge_closing_0.smt2                |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26859_edge_closing_0.smt2                |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26860_edge_closing_0.smt2                |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26902_terminationG_0.smt2                   |  19.956s  |  19.956s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26903_terminationG_0.smt2                   |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26904_terminationG_0.smt2                   |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26908_terminationG_0.smt2                   |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26909_terminationG_0.smt2                   |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26912_terminationG_0.smt2                   |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26913_terminationG_0.smt2                   |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26914_terminationG_0.smt2                   |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26917_terminationG_0.smt2                   |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26918_terminationG_0.smt2                   |  19.860s  |  19.860s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26919_terminationG_0.smt2                   |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26922_terminationG_0.smt2                   |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26923_terminationG_0.smt2                   |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26924_terminationG_0.smt2                   |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26953_terminationG_0.smt2                   |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26954_terminationG_0.smt2                   |   1.267s  |   1.267s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26955_terminationG_0.smt2                   |   2.628s  |   2.628s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26961_terminationG_0.smt2                   |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26962_terminationG_0.smt2                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26965_terminationG_0.smt2                   |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26966_terminationG_0.smt2                   |  10.086s  |  10.086s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26967_terminationG_0.smt2                   |   4.004s  |   4.004s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26970_terminationG_0.smt2                   |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26971_terminationG_0.smt2                   |   1.197s  |   1.197s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26972_terminationG_0.smt2                   |   5.925s  |   5.925s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26975_terminationG_0.smt2                   |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26976_terminationG_0.smt2                   |   2.223s  |   2.223s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26977_terminationG_0.smt2                   |   1.493s  |   1.493s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26980_terminationG_0.smt2                   |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |   8.572s  |   8.572s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26982_terminationG_0.smt2                   |   7.890s  |   7.890s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26985_terminationG_0.smt2                   |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26986_terminationG_0.smt2                   |   0.900s  |   0.900s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26987_terminationG_0.smt2                   |   1.770s  |   1.770s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26991_terminationG_0.smt2                   |   1.860s  |   1.860s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26992_terminationG_0.smt2                   |   8.569s  |   8.569s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26995_terminationG_0.smt2                   |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26996_terminationG_0.smt2                   |   3.349s  |   3.349s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26997_terminationG_0.smt2                   |  14.128s  |  14.128s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27000_terminationG_0.smt2                   |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27001_terminationG_0.smt2                   |   8.432s  |   8.432s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27002_terminationG_0.smt2                   |   5.223s  |   5.223s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27005_terminationG_0.smt2                   |  19.949s  |  19.949s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27006_terminationG_0.smt2                   |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27007_terminationG_0.smt2                   |   2.395s  |   2.395s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27010_terminationG_0.smt2                   |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27011_terminationG_0.smt2                   |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27012_terminationG_0.smt2                   |   3.668s  |   3.668s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27015_terminationG_0.smt2                   |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27016_terminationG_0.smt2                   |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27017_terminationG_0.smt2                   |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27020_terminationG_0.smt2                   |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27022_terminationG_0.smt2                   |  19.915s  |  19.915s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27025_terminationG_0.smt2                   |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27026_terminationG_0.smt2                   |   4.586s  |   4.586s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27027_terminationG_0.smt2                   |  18.529s  |  18.529s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27030_terminationG_0.smt2                   |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27031_terminationG_0.smt2                   |   4.584s  |   4.584s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27032_terminationG_0.smt2                   |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__terminationQ_13_0.smt2                       |  19.890s  |  19.890s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__terminationS_0_0.smt2                        |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27051_terminationG_0.smt2                    |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27056_terminationG_0.smt2                    |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27057_terminationG_0.smt2                    |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27061_terminationG_0.smt2                    |   6.042s  |   6.042s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27062_terminationG_0.smt2                    |  19.918s  |  19.918s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27068_terminationG_0.smt2                    |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27069_terminationG_0.smt2                    |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27077_terminationG_0.smt2                    |   2.207s  |   2.207s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27083_terminationG_0.smt2                    |   0.847s  |   0.847s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27084_terminationG_0.smt2                    |   1.032s  |   1.032s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27092_terminationG_0.smt2                    |   2.322s  |   2.322s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27093_terminationG_0.smt2                    |   1.626s  |   1.626s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27097_terminationG_0.smt2                    |   0.779s  |   0.779s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27098_terminationG_0.smt2                    |   4.715s  |   4.715s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27109_terminationG_0.smt2                    |  16.298s  |  16.298s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27110_terminationG_0.smt2                    |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27121_terminationG_0.smt2                    |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27122_terminationG_0.smt2                    |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27123_terminationG_0.smt2                    |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27134_terminationG_0.smt2                    |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27135_terminationG_0.smt2                    |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27136_terminationG_0.smt2                    |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27139_terminationG_0.smt2                    |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27140_terminationG_0.smt2                    |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27141_terminationG_0.smt2                    |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27144_terminationG_0.smt2                    |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27145_terminationG_0.smt2                    |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27146_terminationG_0.smt2                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27149_terminationG_0.smt2                    |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27150_terminationG_0.smt2                    |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27151_terminationG_0.smt2                    |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27154_terminationG_0.smt2                    |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27155_terminationG_0.smt2                    |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27156_terminationG_0.smt2                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27159_terminationG_0.smt2                    |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27160_terminationG_0.smt2                    |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27161_terminationG_0.smt2                    |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27164_terminationG_0.smt2                    |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27165_terminationG_0.smt2                    |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27166_terminationG_0.smt2                    |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27169_terminationG_0.smt2                    |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27170_terminationG_0.smt2                    |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27171_terminationG_0.smt2                    |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27174_terminationG_0.smt2                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27175_terminationG_0.smt2                    |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27176_terminationG_0.smt2                    |  19.854s  |  19.854s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27179_terminationG_0.smt2                    |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27180_terminationG_0.smt2                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27181_terminationG_0.smt2                    |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27184_terminationG_0.smt2                    |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27185_terminationG_0.smt2                    |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27186_terminationG_0.smt2                    |  19.949s  |  19.949s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27189_terminationG_0.smt2                    |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27190_terminationG_0.smt2                    |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27191_terminationG_0.smt2                    |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27194_terminationG_0.smt2                    |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27195_terminationG_0.smt2                    |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27196_terminationG_0.smt2                    |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27199_terminationG_0.smt2                    |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27200_terminationG_0.smt2                    |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27201_terminationG_0.smt2                    |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27205_terminationG_0.smt2                    |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27206_terminationG_0.smt2                    |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27207_terminationG_0.smt2                    |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27210_terminationG_0.smt2                    |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27211_terminationG_0.smt2                    |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27212_terminationG_0.smt2                    |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27215_terminationG_0.smt2                    |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27216_terminationG_0.smt2                    |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27217_terminationG_0.smt2                    |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27221_terminationG_0.smt2                    |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27222_terminationG_0.smt2                    |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27225_terminationG_0.smt2                    |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27227_terminationG_0.smt2                    |  19.495s  |  19.495s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27230_terminationG_0.smt2                    |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27231_terminationG_0.smt2                    |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27232_terminationG_0.smt2                    |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27234_edge_closing_0.smt2                    |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27235_edge_closing_0.smt2                    |   0.878s  |   0.878s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27236_edge_closing_0.smt2                    |   5.751s  |   5.751s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27242_edge_closing_0.smt2                    |   2.871s  |   2.871s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__terminationQ_18_0.smt2                        |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__terminationQ_19_0.smt2                        |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__terminationS_0_0.smt2                         |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Ton_Chanh_15__McCarthy91_Iteration_true-termination.c__term_unfeasibility_0_0.smt2          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27301_terminationG_0.smt2                |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27304_terminationG_0.smt2                |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27305_terminationG_0.smt2                |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27306_terminationG_0.smt2                |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27309_terminationG_0.smt2                |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27310_terminationG_0.smt2                |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27311_terminationG_0.smt2                |  19.845s  |  19.845s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27314_terminationG_0.smt2                |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27315_terminationG_0.smt2                |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27316_terminationG_0.smt2                |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27319_terminationG_0.smt2                |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27320_terminationG_0.smt2                |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27321_terminationG_0.smt2                |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27324_terminationG_0.smt2                |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27325_terminationG_0.smt2                |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27326_terminationG_0.smt2                |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27343_terminationG_0.smt2                      |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27347_terminationG_0.smt2                      |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27348_terminationG_0.smt2                      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27352_terminationG_0.smt2                      |   4.181s  |   4.181s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27353_terminationG_0.smt2                      |   6.591s  |   6.591s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27362_terminationG_0.smt2                  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27367_terminationG_0.smt2                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27370_terminationG_0.smt2                  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27371_terminationG_0.smt2                  |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27372_terminationG_0.smt2                  |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27375_terminationG_0.smt2                  |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27376_terminationG_0.smt2                  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27377_terminationG_0.smt2                  |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27380_terminationG_0.smt2                  |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27385_terminationG_0.smt2                  |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27386_terminationG_0.smt2                  |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27387_terminationG_0.smt2                  |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27390_terminationG_0.smt2                  |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27391_terminationG_0.smt2                  |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27392_terminationG_0.smt2                  |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27409_terminationG_0.smt2                  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27413_terminationG_0.smt2                  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27414_terminationG_0.smt2                  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27417_terminationG_0.smt2                  |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27418_terminationG_0.smt2                  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27419_terminationG_0.smt2                  |  19.912s  |  19.912s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27422_terminationG_0.smt2                  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27423_terminationG_0.smt2                  |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27424_terminationG_0.smt2                  |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27427_terminationG_0.smt2                  |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27428_terminationG_0.smt2                  |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27429_terminationG_0.smt2                  |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27432_terminationG_0.smt2                  |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27433_terminationG_0.smt2                  |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27434_terminationG_0.smt2                  |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27437_terminationG_0.smt2                  |  20.127s  |  20.127s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27438_terminationG_0.smt2                  |  19.998s  |  19.998s  |   0.000s  | 0.0%|
</details>
