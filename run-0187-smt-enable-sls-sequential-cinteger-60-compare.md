Comparing data and data


# SUMMARY
- LHS tests = 1818
- RHS tests = 1818
- LHS success = 1818  (100.0%)
- RHS success = 1818  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-enable-sls-sequential-cinteger-60
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 3cdcd831b1d4abad6cfba3a920590e29792569c9
Z3 branch: master
Z3 options: "-T:60 -v:2 -st  smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_NIA_CInteger
Z3 commit message: fix build breaks

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-enable-sls-sequential-cinteger-60
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 3cdcd831b1d4abad6cfba3a920590e29792569c9
Z3 branch: master
Z3 options: "-T:60 -v:2 -st  smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_NIA_CInteger
Z3 commit message: fix build breaks

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |   2.038s  |   2.038s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |   1.417s  |   1.417s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |   5.506s  |   5.506s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |   5.306s  |   5.306s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   0.636s  |   0.636s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |   1.069s  |   1.069s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |   8.139s  |   8.139s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |   1.575s  |   1.575s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   2.377s  |   2.377s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |  29.577s  |  29.577s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |   0.972s  |   0.972s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |   8.208s  |   8.208s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   8.969s  |   8.969s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |   5.520s  |   5.520s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |   2.038s  |   2.038s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |   1.417s  |   1.417s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |   5.506s  |   5.506s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |   5.306s  |   5.306s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   0.636s  |   0.636s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |   1.069s  |   1.069s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |   8.139s  |   8.139s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |   1.575s  |   1.575s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   2.377s  |   2.377s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |  29.577s  |  29.577s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |   0.972s  |   0.972s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |   8.208s  |   8.208s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   8.969s  |   8.969s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |   5.520s  |   5.520s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |   2.038s  |   2.038s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |   1.417s  |   1.417s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |   5.506s  |   5.506s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |   5.306s  |   5.306s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   0.636s  |   0.636s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |   1.069s  |   1.069s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |   8.139s  |   8.139s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |   1.575s  |   1.575s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   2.377s  |   2.377s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |  29.577s  |  29.577s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |   0.972s  |   0.972s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |   8.208s  |   8.208s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   8.969s  |   8.969s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |   5.520s  |   5.520s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |   2.038s  |   2.038s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |   1.417s  |   1.417s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |   5.506s  |   5.506s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |   5.306s  |   5.306s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   0.636s  |   0.636s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |   1.069s  |   1.069s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |   8.139s  |   8.139s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |   1.575s  |   1.575s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   2.377s  |   2.377s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |  29.577s  |  29.577s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |   0.972s  |   0.972s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |   8.208s  |   8.208s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   8.969s  |   8.969s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |   5.520s  |   5.520s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Stroeder_15__AlternDivWidening.c__p20652_terminationG_0.smt2                               |  60.207s |184.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21954_terminationG_0.smt2 |  60.197s |188.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22015_terminationG_0.smt2 |  60.107s |173.0MiB|
|Stroeder_15__Pure3Phase_true-termination.c__p25567_terminationG_0.smt2                     |  60.097s |161.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21964_terminationG_0.smt2 |  60.097s |167.0MiB|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20280_terminationG_0.smt2          |  60.062s |110.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22029_edge_closing_0.smt2 |  60.061s |1533.0MiB|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                       |  60.055s |109.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2 |  60.052s |1280.0MiB|
|Stroeder_15__NO_24.c__p24816_terminationG_0.smt2                                           |  60.049s |111.0MiB|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                     |  60.047s |108.0MiB|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20270_terminationG_0.smt2          |  60.046s |126.0MiB|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27315_terminationG_0.smt2               |  60.041s |123.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21975_terminationG_0.smt2 |  60.036s |191.0MiB|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27310_terminationG_0.smt2               |  60.035s |726.0MiB|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26707_terminationG_0.smt2                 |  60.033s |112.0MiB|
|Stroeder_15__svcomp_ex2.c__p25937_terminationG_0.smt2                                      |  60.032s |229.0MiB|
|Stroeder_15__svcomp_ex2.c__p25992_terminationG_0.smt2                                      |  60.030s |79.564MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21980_terminationG_0.smt2 |  60.028s |188.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20944_edge_closing_0.smt2 |  60.021s |76.26MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Stroeder_15__AlternDivWidening.c__p20652_terminationG_0.smt2                               |  60.207s |184.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21954_terminationG_0.smt2 |  60.197s |188.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22015_terminationG_0.smt2 |  60.107s |173.0MiB|
|Stroeder_15__Pure3Phase_true-termination.c__p25567_terminationG_0.smt2                     |  60.097s |161.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21964_terminationG_0.smt2 |  60.097s |167.0MiB|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20280_terminationG_0.smt2          |  60.062s |110.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22029_edge_closing_0.smt2 |  60.061s |1533.0MiB|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                       |  60.055s |109.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2 |  60.052s |1280.0MiB|
|Stroeder_15__NO_24.c__p24816_terminationG_0.smt2                                           |  60.049s |111.0MiB|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                     |  60.047s |108.0MiB|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20270_terminationG_0.smt2          |  60.046s |126.0MiB|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27315_terminationG_0.smt2               |  60.041s |123.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21975_terminationG_0.smt2 |  60.036s |191.0MiB|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27310_terminationG_0.smt2               |  60.035s |726.0MiB|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26707_terminationG_0.smt2                 |  60.033s |112.0MiB|
|Stroeder_15__svcomp_ex2.c__p25937_terminationG_0.smt2                                      |  60.032s |229.0MiB|
|Stroeder_15__svcomp_ex2.c__p25992_terminationG_0.smt2                                      |  60.030s |79.564MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21980_terminationG_0.smt2 |  60.028s |188.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20944_edge_closing_0.smt2 |  60.021s |76.26MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |112.0MiB|112.0MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |81.236MiB|81.236MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |110.0MiB|110.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |74.744MiB|74.744MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |110.0MiB|110.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |161.0MiB|161.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |112.0MiB|112.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |122.0MiB|122.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |160.0MiB|160.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |300.0MiB|300.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |123.0MiB|123.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |119.0MiB|119.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |109.0MiB|109.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |129.0MiB|129.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |120.0MiB|120.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |117.0MiB|117.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |117.0MiB|117.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |121.0MiB|121.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |163.0MiB|163.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |110.0MiB|110.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |112.0MiB|112.0MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |81.236MiB|81.236MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |110.0MiB|110.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |74.744MiB|74.744MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |110.0MiB|110.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |161.0MiB|161.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |112.0MiB|112.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |122.0MiB|122.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |160.0MiB|160.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |300.0MiB|300.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |123.0MiB|123.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |119.0MiB|119.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |109.0MiB|109.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |129.0MiB|129.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |120.0MiB|120.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |117.0MiB|117.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |117.0MiB|117.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |121.0MiB|121.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |163.0MiB|163.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |110.0MiB|110.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |112.0MiB|112.0MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |81.236MiB|81.236MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |110.0MiB|110.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |74.744MiB|74.744MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |110.0MiB|110.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |161.0MiB|161.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |112.0MiB|112.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |122.0MiB|122.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |160.0MiB|160.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |300.0MiB|300.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |123.0MiB|123.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |119.0MiB|119.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |109.0MiB|109.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |129.0MiB|129.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |120.0MiB|120.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |117.0MiB|117.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |117.0MiB|117.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |121.0MiB|121.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |163.0MiB|163.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |110.0MiB|110.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |112.0MiB|112.0MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |81.236MiB|81.236MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |110.0MiB|110.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |74.744MiB|74.744MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |110.0MiB|110.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |161.0MiB|161.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |112.0MiB|112.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |122.0MiB|122.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |160.0MiB|160.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |300.0MiB|300.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |123.0MiB|123.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |119.0MiB|119.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |109.0MiB|109.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |129.0MiB|129.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |120.0MiB|120.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |117.0MiB|117.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |117.0MiB|117.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |121.0MiB|121.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |163.0MiB|163.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |110.0MiB|110.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22029_edge_closing_0.smt2 |  60.061s |1533.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27240_edge_closing_0.smt2                   |   1.563s |1353.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2 |  60.052s |1280.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27239_edge_closing_0.smt2                   |   1.476s |1090.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22027_edge_closing_0.smt2 |  35.938s |1033.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27238_edge_closing_0.smt2                   |   2.169s |891.0MiB|
|Stroeder_15__svcomp_ex2.c__p25827_terminationG_0.smt2                                      |   1.158s |728.0MiB|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27310_terminationG_0.smt2               |  60.035s |726.0MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23340_edge_closing_0.smt2 |  59.869s |411.0MiB|
|Stroeder_15__svcomp_ex2.c__p25826_terminationG_0.smt2                                      |   0.661s |369.0MiB|
|Stroeder_15__svcomp_ex2.c__p25817_terminationG_0.smt2                                      |   0.753s |350.0MiB|
|Stroeder_15__Narrowing.c__p24536_terminationG_0.smt2                                       |  60.003s |343.0MiB|
|Stroeder_15__svcomp_ex2.c__p25832_terminationG_0.smt2                                      |   1.977s |320.0MiB|
|Stroeder_15__Lcm.c__p23906_terminationG_0.smt2                                             |   1.813s |312.0MiB|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24242_terminationG_0.smt2          |   0.871s |312.0MiB|
|Stroeder_15__UpAndDownIneq.c__p26240_edge_closing_0.smt2                                   |   0.833s |312.0MiB|
|Stroeder_15__NO_04.c__p24653_safety_0.smt2                                                 |  59.881s |311.0MiB|
|Stroeder_15__UpAndDownIneq.c__p26230_terminationG_0.smt2                                   |   0.737s |311.0MiB|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23856_terminationG_0.smt2 |   2.959s |310.0MiB|
|Stroeder_15__svcomp_ex3b.c__terminationQ_3_0.smt2                                          |   2.806s |310.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22029_edge_closing_0.smt2 |  60.061s |1533.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27240_edge_closing_0.smt2                   |   1.563s |1353.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2 |  60.052s |1280.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27239_edge_closing_0.smt2                   |   1.476s |1090.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22027_edge_closing_0.smt2 |  35.938s |1033.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27238_edge_closing_0.smt2                   |   2.169s |891.0MiB|
|Stroeder_15__svcomp_ex2.c__p25827_terminationG_0.smt2                                      |   1.158s |728.0MiB|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27310_terminationG_0.smt2               |  60.035s |726.0MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23340_edge_closing_0.smt2 |  59.869s |411.0MiB|
|Stroeder_15__svcomp_ex2.c__p25826_terminationG_0.smt2                                      |   0.661s |369.0MiB|
|Stroeder_15__svcomp_ex2.c__p25817_terminationG_0.smt2                                      |   0.753s |350.0MiB|
|Stroeder_15__Narrowing.c__p24536_terminationG_0.smt2                                       |  60.003s |343.0MiB|
|Stroeder_15__svcomp_ex2.c__p25832_terminationG_0.smt2                                      |   1.977s |320.0MiB|
|Stroeder_15__Lcm.c__p23906_terminationG_0.smt2                                             |   1.813s |312.0MiB|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24242_terminationG_0.smt2          |   0.871s |312.0MiB|
|Stroeder_15__UpAndDownIneq.c__p26240_edge_closing_0.smt2                                   |   0.833s |312.0MiB|
|Stroeder_15__NO_04.c__p24653_safety_0.smt2                                                 |  59.881s |311.0MiB|
|Stroeder_15__UpAndDownIneq.c__p26230_terminationG_0.smt2                                   |   0.737s |311.0MiB|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23856_terminationG_0.smt2 |   2.959s |310.0MiB|
|Stroeder_15__svcomp_ex3b.c__terminationQ_3_0.smt2                                          |   2.806s |310.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |   2.038s  |   2.038s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |   1.417s  |   1.417s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |   5.506s  |   5.506s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |   5.306s  |   5.306s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   0.636s  |   0.636s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |   1.069s  |   1.069s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |   8.139s  |   8.139s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |   1.575s  |   1.575s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   2.377s  |   2.377s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |  29.577s  |  29.577s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |   0.972s  |   0.972s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |   8.208s  |   8.208s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   8.969s  |   8.969s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |   5.520s  |   5.520s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20255_terminationG_0.smt2           |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20259_terminationG_0.smt2           |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20260_terminationG_0.smt2           |   1.030s  |   1.030s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20269_terminationG_0.smt2           |  24.103s  |  24.103s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20270_terminationG_0.smt2           |  60.046s  |  60.046s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20271_terminationG_0.smt2           |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20279_terminationG_0.smt2           |  13.745s  |  13.745s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20280_terminationG_0.smt2           |  60.062s  |  60.062s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20281_terminationG_0.smt2           |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20288_terminationG_0.smt2           |   0.575s  |   0.575s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20289_terminationG_0.smt2           |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20305_terminationG_0.smt2           |  25.950s  |  25.950s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20306_terminationG_0.smt2           |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20307_terminationG_0.smt2           |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20312_terminationG_0.smt2           |  17.474s  |  17.474s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20313_terminationG_0.smt2           |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20314_terminationG_0.smt2           |   6.738s  |   6.738s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20324_terminationG_0.smt2           |  34.785s  |  34.785s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20325_terminationG_0.smt2           |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20326_terminationG_0.smt2           |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_0_0.smt2                |  25.492s  |  25.492s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_2_0.smt2                |  22.850s  |  22.850s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_3_0.smt2                |  17.938s  |  17.938s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_4_0.smt2                |   2.405s  |   2.405s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-Fig1_true-termination.c__p20413_terminationG_0.smt2  |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-Fig2b_true-termination.c__p20426_terminationG_0.smt2  |   0.607s  |   0.607s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-Fig2b_true-termination.c__terminationS_1_0.smt2  |   2.317s  |   2.317s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-complex_true-termination.c__term_unfeasibility_0_0.smt2  |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-counterex1b_true-termination.c__p20394_terminationG_0.smt2  |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-counterex1b_true-termination.c__p20395_terminationG_0.smt2  |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-counterex1b_true-termination.c__p20396_terminationG_0.smt2  |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-loops_true-termination.c__p20439_terminationG_0.smt2  |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-loops_true-termination.c__p20440_terminationG_0.smt2  |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-loops_true-termination.c__term_unfeasibility_0_0.smt2  |   2.094s  |   2.094s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-nestedLoop_true-termination.c__p20452_terminationG_0.smt2  |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-nestedLoop_true-termination.c__p20453_terminationG_0.smt2  |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-speedFails4_true-termination.c__p20494_terminationG_0.smt2  |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-speedpldi4_true-termination.c__p20516_terminationG_0.smt2  |   0.729s  |   0.729s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20546_terminationG_0.smt2                                        |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20552_terminationG_0.smt2                                        |   2.211s  |   2.211s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20553_terminationG_0.smt2                                        |   3.479s  |   3.479s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20556_edge_closing_0.smt2                                        |   2.136s  |   2.136s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20557_edge_closing_0.smt2                                        |   2.887s  |   2.887s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20618_terminationG_0.smt2                                    |   2.228s  |   2.228s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20619_terminationG_0.smt2                                    |   3.966s  |   3.966s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20626_edge_closing_0.smt2                                    |   2.135s  |   2.135s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20627_edge_closing_0.smt2                                    |   3.221s  |   3.221s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20638_terminationG_0.smt2                                |   2.396s  |   2.396s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20639_terminationG_0.smt2                                |   1.979s  |   1.979s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20650_terminationG_0.smt2                                |   2.241s  |   2.241s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20651_terminationG_0.smt2                                |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20652_terminationG_0.smt2                                |  60.207s  |  60.207s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20655_terminationG_0.smt2                                |   2.295s  |   2.295s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20656_terminationG_0.smt2                                |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20657_terminationG_0.smt2                                |  59.919s  |  59.919s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20661_edge_closing_0.smt2                                |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20662_edge_closing_0.smt2                                |  59.919s  |  59.919s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20668_edge_closing_0.smt2                                |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20669_edge_closing_0.smt2                                |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__terminationQ_1_0.smt2                                     |   1.965s  |   1.965s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |   0.796s  |   0.796s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20688_terminationG_0.smt2                                       |   2.099s  |   2.099s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20689_terminationG_0.smt2                                       |   2.239s  |   2.239s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20690_terminationG_0.smt2                                       |   2.967s  |   2.967s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20693_edge_closing_0.smt2                                       |   2.380s  |   2.380s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20694_edge_closing_0.smt2                                       |  59.770s  |  59.770s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__terminationS_1_0.smt2                                            |   1.274s  |   1.274s  |   0.000s  | 0.0%|
|Stroeder_15__Benghazi_true-termination.c__p20729_terminationG_0.smt2                        |   0.699s  |   0.699s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20762_terminationG_0.smt2  |   2.149s  |   2.149s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20763_terminationG_0.smt2  |  59.933s  |  59.933s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20774_edge_closing_0.smt2  |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20777_edge_closing_0.smt2  |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1_true-termination.c__p20785_terminationG_0.smt2  |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1_true-termination.c__p20786_terminationG_0.smt2  |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-ICALP2005-Fig1_true-termination.c__p20810_terminationG_0.smt2  |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-ICALP2005-Fig1_true-termination.c__p20814_terminationG_0.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|Stroeder_15__BrockschmidtCookFuhs-CAV2013-Fig9a_true-termination.c__p20828_terminationG_0.smt2  |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|Stroeder_15__BrockschmidtCookFuhs-CAV2013-Introduction_true-termination.c__p20837_terminationG_0.smt2  |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20849_terminationG_0.smt2  |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20853_terminationG_0.smt2  |   1.382s  |   1.382s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20854_terminationG_0.smt2  |  47.348s  |  47.348s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20855_terminationG_0.smt2  |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20858_terminationG_0.smt2  |   2.337s  |   2.337s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20859_terminationG_0.smt2  |  54.522s  |  54.522s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20860_terminationG_0.smt2  |  60.019s  |  60.019s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20863_terminationG_0.smt2  |   2.261s  |   2.261s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20864_terminationG_0.smt2  |  46.636s  |  46.636s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20865_terminationG_0.smt2  |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20868_terminationG_0.smt2  |   2.290s  |   2.290s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20869_terminationG_0.smt2  |  45.060s  |  45.060s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20870_terminationG_0.smt2  |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20873_terminationG_0.smt2  |   2.244s  |   2.244s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20874_terminationG_0.smt2  |  31.237s  |  31.237s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20875_terminationG_0.smt2  |  59.894s  |  59.894s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20888_terminationG_0.smt2  |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20892_terminationG_0.smt2  |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|Stroeder_15__ChenCookFuhsNimkarOHearn-TACAS2014-Introduction_false-termination.c__p20918_terminationG_0.smt2  |   0.697s  |   0.697s  |   0.000s  | 0.0%|
|Stroeder_15__ChenCookFuhsNimkarOHearn-TACAS2014-Introduction_false-termination.c__p20919_terminationG_0.smt2  |   2.168s  |   2.168s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20939_terminationG_0.smt2  |   0.430s  |   0.430s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20940_terminationG_0.smt2  |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20941_terminationG_0.smt2  |  59.864s  |  59.864s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20944_edge_closing_0.smt2  |  60.021s  |  60.021s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20945_edge_closing_0.smt2  |  59.918s  |  59.918s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.01_true-termination.c__p20984_terminationG_0.smt2  |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.01_true-termination.c__p20989_terminationG_0.smt2  |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21003_terminationG_0.smt2  |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21008_terminationG_0.smt2  |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21011_terminationG_0.smt2  |   1.068s  |   1.068s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21012_terminationG_0.smt2  |  43.480s  |  43.480s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21013_terminationG_0.smt2  |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21016_terminationG_0.smt2  |   1.786s  |   1.786s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21017_terminationG_0.smt2  |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21018_terminationG_0.smt2  |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21021_terminationG_0.smt2  |   0.632s  |   0.632s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21022_terminationG_0.smt2  |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21023_terminationG_0.smt2  |  59.906s  |  59.906s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21026_terminationG_0.smt2  |   1.417s  |   1.417s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21027_terminationG_0.smt2  |  24.793s  |  24.793s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21031_terminationG_0.smt2  |   2.099s  |   2.099s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21032_terminationG_0.smt2  |  28.953s  |  28.953s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21033_terminationG_0.smt2  |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21037_edge_closing_0.smt2  |   0.473s  |   0.473s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21040_edge_closing_0.smt2  |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21044_edge_closing_0.smt2  |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21056_terminationG_0.smt2  |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21057_terminationG_0.smt2  |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21058_terminationG_0.smt2  |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21061_edge_closing_0.smt2  |  30.185s  |  30.185s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21062_edge_closing_0.smt2  |   1.248s  |   1.248s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21079_terminationG_0.smt2  |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21083_terminationG_0.smt2  |   1.596s  |   1.596s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21084_terminationG_0.smt2  |  59.908s  |  59.908s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21085_terminationG_0.smt2  |  59.894s  |  59.894s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21107_terminationG_0.smt2  |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21108_terminationG_0.smt2  |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21112_terminationG_0.smt2  |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21113_terminationG_0.smt2  |   0.915s  |   0.915s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21116_terminationG_0.smt2  |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21118_terminationG_0.smt2  |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21122_terminationG_0.smt2  |   2.279s  |   2.279s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21123_terminationG_0.smt2  |   1.181s  |   1.181s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21126_terminationG_0.smt2  |  17.742s  |  17.742s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21127_terminationG_0.smt2  |  59.928s  |  59.928s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21128_terminationG_0.smt2  |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21131_terminationG_0.smt2  |  13.572s  |  13.572s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21132_terminationG_0.smt2  |  59.931s  |  59.931s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |  59.913s  |  59.913s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21136_edge_closing_0.smt2  |   7.350s  |   7.350s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21137_edge_closing_0.smt2  |   5.603s  |   5.603s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21141_edge_closing_0.smt2  |   0.784s  |   0.784s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21142_edge_closing_0.smt2  |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21143_edge_closing_0.smt2  |  24.211s  |  24.211s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21144_edge_closing_0.smt2  |  20.870s  |  20.870s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |   1.489s  |   1.489s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21148_edge_closing_0.smt2  |   2.121s  |   2.121s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21149_edge_closing_0.smt2  |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21150_edge_closing_0.smt2  |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.07_true-termination.c__p21184_terminationG_0.smt2  |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.07_true-termination.c__p21189_terminationG_0.smt2  |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.07_true-termination.c__terminationS_0_0.smt2  |   2.111s  |   2.111s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.08_true-termination.c__p21202_terminationG_0.smt2  |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.08_true-termination.c__p21203_terminationG_0.smt2  |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21242_terminationG_0.smt2  |   0.590s  |   0.590s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21246_terminationG_0.smt2  |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   0.680s  |   0.680s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21258_terminationG_0.smt2  |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21260_terminationG_0.smt2  |   0.489s  |   0.489s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21265_terminationG_0.smt2  |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21280_terminationG_0.smt2  |   0.494s  |   0.494s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21283_terminationG_0.smt2  |  13.085s  |  13.085s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21285_terminationG_0.smt2  |   1.319s  |   1.319s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21288_terminationG_0.smt2  |  18.354s  |  18.354s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21290_terminationG_0.smt2  |   7.047s  |   7.047s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21293_terminationG_0.smt2  |   6.306s  |   6.306s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21294_terminationG_0.smt2  |   6.077s  |   6.077s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21295_terminationG_0.smt2  |  14.738s  |  14.738s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21298_terminationG_0.smt2  |  28.127s  |  28.127s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21299_terminationG_0.smt2  |   7.850s  |   7.850s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21300_terminationG_0.smt2  |   6.072s  |   6.072s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21303_terminationG_0.smt2  |  59.629s  |  59.629s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21304_terminationG_0.smt2  |  19.194s  |  19.194s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21305_terminationG_0.smt2  |   7.752s  |   7.752s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21308_terminationG_0.smt2  |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21309_terminationG_0.smt2  |   4.433s  |   4.433s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21310_terminationG_0.smt2  |   1.467s  |   1.467s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21313_terminationG_0.smt2  |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21314_terminationG_0.smt2  |   2.372s  |   2.372s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21315_terminationG_0.smt2  |   0.704s  |   0.704s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21318_terminationG_0.smt2  |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21319_terminationG_0.smt2  |   9.179s  |   9.179s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21320_terminationG_0.smt2  |   7.523s  |   7.523s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21323_terminationG_0.smt2  |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21324_terminationG_0.smt2  |  10.966s  |  10.966s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21325_terminationG_0.smt2  |   6.076s  |   6.076s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21328_terminationG_0.smt2  |  59.828s  |  59.828s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21329_terminationG_0.smt2  |  17.774s  |  17.774s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21330_terminationG_0.smt2  |   9.301s  |   9.301s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21334_edge_closing_0.smt2  |   1.060s  |   1.060s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21336_edge_closing_0.smt2  |   1.188s  |   1.188s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21337_edge_closing_0.smt2  |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21338_edge_closing_0.smt2  |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21342_edge_closing_0.smt2  |  25.171s  |  25.171s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21343_edge_closing_0.smt2  |   5.758s  |   5.758s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |  59.932s  |  59.932s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21351_edge_closing_0.smt2  |  31.721s  |  31.721s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21352_edge_closing_0.smt2  |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21353_edge_closing_0.smt2  |  59.691s  |  59.691s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__terminationS_0_0.smt2  |   2.401s  |   2.401s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21362_terminationG_0.smt2  |   0.607s  |   0.607s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21367_terminationG_0.smt2  |   1.021s  |   1.021s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21371_terminationG_0.smt2  |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21372_terminationG_0.smt2  |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21376_terminationG_0.smt2  |   0.913s  |   0.913s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21377_terminationG_0.smt2  |   2.784s  |   2.784s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21382_terminationG_0.smt2  |   1.229s  |   1.229s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21385_terminationG_0.smt2  |   2.200s  |   2.200s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21386_terminationG_0.smt2  |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21387_terminationG_0.smt2  |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21390_terminationG_0.smt2  |   1.332s  |   1.332s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21391_terminationG_0.smt2  |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21392_terminationG_0.smt2  |   5.951s  |   5.951s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21395_terminationG_0.smt2  |  25.155s  |  25.155s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21400_edge_closing_0.smt2  |   0.999s  |   0.999s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21401_edge_closing_0.smt2  |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.13_true-termination.c__p21424_terminationG_0.smt2  |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21451_terminationG_0.smt2  |   1.927s  |   1.927s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21452_terminationG_0.smt2  |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21453_terminationG_0.smt2  |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21456_edge_closing_0.smt2  |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21457_edge_closing_0.smt2  |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21463_edge_closing_0.smt2  |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21464_edge_closing_0.smt2  |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21468_edge_closing_0.smt2  |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21469_edge_closing_0.smt2  |  59.933s  |  59.933s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21470_edge_closing_0.smt2  |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__terminationQ_0_0.smt2  |   0.969s  |   0.969s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.15_false-termination.c__p21487_terminationG_0.smt2  |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.15_false-termination.c__p21491_terminationG_0.smt2  |   2.190s  |   2.190s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.15_false-termination.c__p21492_terminationG_0.smt2  |  59.881s  |  59.881s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.16_true-termination.c__p21520_terminationG_0.smt2  |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.16_true-termination.c__p21525_terminationG_0.smt2  |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.16_true-termination.c__p21530_terminationG_0.smt2  |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21539_terminationG_0.smt2  |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21543_terminationG_0.smt2  |   1.300s  |   1.300s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21544_terminationG_0.smt2  |   0.748s  |   0.748s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21547_terminationG_0.smt2  |   1.373s  |   1.373s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21548_terminationG_0.smt2  |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21549_terminationG_0.smt2  |  59.905s  |  59.905s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21552_terminationG_0.smt2  |   2.748s  |   2.748s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21553_terminationG_0.smt2  |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21554_terminationG_0.smt2  |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21562_edge_closing_0.smt2  |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.18_true-termination.c__p21582_terminationG_0.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.19_true-termination.c__p21598_terminationG_0.smt2  |   1.863s  |   1.863s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.22_true-termination.c__p21645_terminationG_0.smt2  |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.22_true-termination.c__p21649_terminationG_0.smt2  |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.22_true-termination.c__p21650_terminationG_0.smt2  |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21678_terminationG_0.smt2  |   0.771s  |   0.771s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21685_terminationG_0.smt2  |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21690_terminationG_0.smt2  |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21697_terminationG_0.smt2  |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21702_terminationG_0.smt2  |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21709_terminationG_0.smt2  |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21719_terminationG_0.smt2  |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21726_terminationG_0.smt2  |   0.580s  |   0.580s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21727_terminationG_0.smt2  |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21728_terminationG_0.smt2  |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21732_terminationG_0.smt2  |   0.686s  |   0.686s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21733_terminationG_0.smt2  |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21737_terminationG_0.smt2  |   2.239s  |   2.239s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21738_terminationG_0.smt2  |  59.901s  |  59.901s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21748_edge_closing_0.smt2  |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  |   0.702s  |   0.702s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21772_terminationG_0.smt2  |   1.157s  |   1.157s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21774_terminationG_0.smt2  |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21780_terminationG_0.smt2  |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21781_terminationG_0.smt2  |   6.253s  |   6.253s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21788_terminationG_0.smt2  |   2.396s  |   2.396s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21793_terminationG_0.smt2  |   2.126s  |   2.126s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21794_terminationG_0.smt2  |   2.178s  |   2.178s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21795_terminationG_0.smt2  |   1.104s  |   1.104s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21802_terminationG_0.smt2  |   0.566s  |   0.566s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21803_terminationG_0.smt2  |   2.368s  |   2.368s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.04_true-termination.c__p21822_terminationG_0.smt2  |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.04_true-termination.c__p21827_terminationG_0.smt2  |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21868_terminationG_0.smt2  |   1.894s  |   1.894s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21870_terminationG_0.smt2  |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21875_terminationG_0.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21876_terminationG_0.smt2  |   0.430s  |   0.430s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21877_terminationG_0.smt2  |   1.642s  |   1.642s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21882_terminationG_0.smt2  |   2.226s  |   2.226s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21883_terminationG_0.smt2  |   1.950s  |   1.950s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21884_terminationG_0.smt2  |   0.899s  |   0.899s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21890_terminationG_0.smt2  |   7.532s  |   7.532s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21891_terminationG_0.smt2  |   7.559s  |   7.559s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21892_terminationG_0.smt2  |   0.588s  |   0.588s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21895_terminationG_0.smt2  |   1.171s  |   1.171s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21896_terminationG_0.smt2  |   1.738s  |   1.738s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21897_terminationG_0.smt2  |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21905_terminationG_0.smt2  |   0.593s  |   0.593s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21906_terminationG_0.smt2  |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21907_terminationG_0.smt2  |   0.713s  |   0.713s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21910_terminationG_0.smt2  |  28.092s  |  28.092s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21911_terminationG_0.smt2  |   1.960s  |   1.960s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21912_terminationG_0.smt2  |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21922_terminationG_0.smt2  |   0.905s  |   0.905s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21923_terminationG_0.smt2  |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21924_terminationG_0.smt2  |   0.919s  |   0.919s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21927_terminationG_0.smt2  |  26.494s  |  26.494s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21928_terminationG_0.smt2  |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21929_terminationG_0.smt2  |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21938_terminationG_0.smt2  |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21939_terminationG_0.smt2  |   1.699s  |   1.699s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21940_terminationG_0.smt2  |   1.026s  |   1.026s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21943_terminationG_0.smt2  |   2.910s  |   2.910s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21944_terminationG_0.smt2  |   5.777s  |   5.777s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21945_terminationG_0.smt2  |   0.748s  |   0.748s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21948_terminationG_0.smt2  |  29.422s  |  29.422s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21949_terminationG_0.smt2  |  10.447s  |  10.447s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21953_terminationG_0.smt2  |  35.134s  |  35.134s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21954_terminationG_0.smt2  |  60.197s  |  60.197s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21955_terminationG_0.smt2  |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21957_terminationG_0.smt2  |  26.909s  |  26.909s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21959_terminationG_0.smt2  |  39.772s  |  39.772s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |  59.858s  |  59.858s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21963_terminationG_0.smt2  |  22.969s  |  22.969s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21964_terminationG_0.smt2  |  60.097s  |  60.097s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21965_terminationG_0.smt2  |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21968_terminationG_0.smt2  |  33.619s  |  33.619s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21969_terminationG_0.smt2  |  48.259s  |  48.259s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21970_terminationG_0.smt2  |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21973_terminationG_0.smt2  |  32.358s  |  32.358s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21974_terminationG_0.smt2  |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21975_terminationG_0.smt2  |  60.036s  |  60.036s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21978_terminationG_0.smt2  |  48.405s  |  48.405s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21979_terminationG_0.smt2  |  59.927s  |  59.927s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21980_terminationG_0.smt2  |  60.028s  |  60.028s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21983_terminationG_0.smt2  |  37.692s  |  37.692s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21984_terminationG_0.smt2  |  57.598s  |  57.598s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21985_terminationG_0.smt2  |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21988_terminationG_0.smt2  |  43.388s  |  43.388s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21989_terminationG_0.smt2  |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21990_terminationG_0.smt2  |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21993_terminationG_0.smt2  |  56.343s  |  56.343s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21994_terminationG_0.smt2  |  33.407s  |  33.407s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21998_terminationG_0.smt2  |   4.188s  |   4.188s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21999_terminationG_0.smt2  |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |  59.864s  |  59.864s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22004_terminationG_0.smt2  |  52.386s  |  52.386s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22005_terminationG_0.smt2  |  59.816s  |  59.816s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22006_terminationG_0.smt2  |  13.560s  |  13.560s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22009_terminationG_0.smt2  |  45.279s  |  45.279s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22010_terminationG_0.smt2  |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22011_terminationG_0.smt2  |  59.252s  |  59.252s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22014_terminationG_0.smt2  |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22015_terminationG_0.smt2  |  60.107s  |  60.107s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22016_terminationG_0.smt2  |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22019_terminationG_0.smt2  |  40.238s  |  40.238s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22020_terminationG_0.smt2  |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22021_terminationG_0.smt2  |  60.016s  |  60.016s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22023_edge_closing_0.smt2  |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22024_edge_closing_0.smt2  |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22025_edge_closing_0.smt2  |   1.220s  |   1.220s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22027_edge_closing_0.smt2  |  35.938s  |  35.938s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |  60.052s  |  60.052s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22029_edge_closing_0.smt2  |  60.061s  |  60.061s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22031_edge_closing_0.smt2  |   0.736s  |   0.736s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |   1.600s  |   1.600s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__terminationQ_14_0.smt2  |  12.096s  |  12.096s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__terminationS_0_0.smt2  |  44.773s  |  44.773s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.07_true-termination.c__p22044_terminationG_0.smt2  |   0.816s  |   0.816s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.07_true-termination.c__p22045_terminationG_0.smt2  |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.08_true-termination.c__p22056_terminationG_0.smt2  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.08_true-termination.c__p22062_terminationG_0.smt2  |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.08_true-termination.c__p22067_terminationG_0.smt2  |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22103_terminationG_0.smt2  |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22104_terminationG_0.smt2  |   0.874s  |   0.874s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22109_terminationG_0.smt2  |   0.678s  |   0.678s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22113_terminationG_0.smt2  |   0.676s  |   0.676s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22114_terminationG_0.smt2  |   1.628s  |   1.628s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22118_terminationG_0.smt2  |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22119_terminationG_0.smt2  |   0.719s  |   0.719s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22122_terminationG_0.smt2  |   0.983s  |   0.983s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22123_terminationG_0.smt2  |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22124_terminationG_0.smt2  |   1.143s  |   1.143s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22129_terminationG_0.smt2  |   0.770s  |   0.770s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22142_terminationG_0.smt2  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22147_terminationG_0.smt2  |   0.834s  |   0.834s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22148_terminationG_0.smt2  |   0.642s  |   0.642s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.729s  |   0.729s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22158_terminationG_0.smt2  |   2.178s  |   2.178s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22160_terminationG_0.smt2  |   1.176s  |   1.176s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22169_terminationG_0.smt2  |   7.141s  |   7.141s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22170_terminationG_0.smt2  |  36.290s  |  36.290s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22177_terminationG_0.smt2                                           |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22178_terminationG_0.smt2                                           |   2.475s  |   2.475s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22182_terminationG_0.smt2                                           |   0.978s  |   0.978s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22183_terminationG_0.smt2                                           |   2.423s  |   2.423s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22184_terminationG_0.smt2                                           |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22189_edge_closing_0.smt2                                           |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__term_unfeasibility_0_0.smt2                                          |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__terminationQ_1_0.smt2                                                |   1.226s  |   1.226s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22199_terminationG_0.smt2                                       |   2.155s  |   2.155s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22200_terminationG_0.smt2                                       |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22201_terminationG_0.smt2                                       |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22206_edge_closing_0.smt2                                       |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__term_unfeasibility_1_0.smt2                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__terminationQ_0_0.smt2                                            |   2.160s  |   2.160s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22316_terminationG_0.smt2                                      |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22317_terminationG_0.smt2                                      |   1.190s  |   1.190s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22318_terminationG_0.smt2                                      |  55.465s  |  55.465s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22321_terminationG_0.smt2                                      |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22322_terminationG_0.smt2                                      |   2.354s  |   2.354s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22323_terminationG_0.smt2                                      |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv2.c__p22248_safety_0.smt2                                           |   2.089s  |   2.089s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv2.c__p22249_safety_0.smt2                                           |   2.342s  |   2.342s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22271_terminationG_0.smt2                                     |   0.849s  |   0.849s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22289_terminationG_0.smt2                                     |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22290_terminationG_0.smt2                                     |   2.106s  |   2.106s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22291_terminationG_0.smt2                                     |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22294_terminationG_0.smt2                                     |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22295_terminationG_0.smt2                                     |   2.343s  |   2.343s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22296_terminationG_0.smt2                                     |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22332_terminationG_0.smt2                                      |   1.220s  |   1.220s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22336_terminationG_0.smt2                                      |   0.858s  |   0.858s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22337_terminationG_0.smt2                                      |   0.974s  |   0.974s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22340_terminationG_0.smt2                                      |   2.424s  |   2.424s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22341_terminationG_0.smt2                                      |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      |  60.047s  |  60.047s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22345_terminationG_0.smt2                                      |   4.415s  |   4.415s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22346_terminationG_0.smt2                                      |  59.591s  |  59.591s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22347_terminationG_0.smt2                                      |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   2.613s  |   2.613s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22351_terminationG_0.smt2                                      |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22355_terminationG_0.smt2                                      |   3.146s  |   3.146s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22356_terminationG_0.smt2                                      |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22357_terminationG_0.smt2                                      |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22365_edge_closing_0.smt2                                      |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__terminationQ_3_0.smt2                                           |   2.476s  |   2.476s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__terminationS_1_0.smt2                                           |   2.416s  |   2.416s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8a-modified_true-termination.c__p22401_terminationG_0.smt2  |   0.484s  |   0.484s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8b_true-termination.c__p22418_terminationG_0.smt2  |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8b_true-termination.c__p22419_terminationG_0.smt2  |   0.430s  |   0.430s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8b_true-termination.c__p22424_terminationG_0.smt2  |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22435_terminationG_0.smt2                                           |   2.117s  |   2.117s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22436_terminationG_0.smt2                                           |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22440_terminationG_0.smt2                                           |   2.342s  |   2.342s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           |  59.895s  |  59.895s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22442_terminationG_0.smt2                                           |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22445_terminationG_0.smt2                                           |   2.413s  |   2.413s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22446_terminationG_0.smt2                                           |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22447_terminationG_0.smt2                                           |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22450_terminationG_0.smt2                                           |   2.333s  |   2.333s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22451_terminationG_0.smt2                                           |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22452_terminationG_0.smt2                                           |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22455_terminationG_0.smt2                                           |   2.297s  |   2.297s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22456_terminationG_0.smt2                                           |  59.834s  |  59.834s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22457_terminationG_0.smt2                                           |  59.921s  |  59.921s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22460_terminationG_0.smt2                                           |   2.341s  |   2.341s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22461_terminationG_0.smt2                                           |  59.889s  |  59.889s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22462_terminationG_0.smt2                                           |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__terminationS_0_0.smt2                                                |   2.404s  |   2.404s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22480_terminationG_0.smt2                                  |   0.586s  |   0.586s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22481_terminationG_0.smt2                                  |   1.096s  |   1.096s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22484_terminationG_0.smt2                                  |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22485_terminationG_0.smt2                                  |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22491_terminationG_0.smt2                                  |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22494_terminationG_0.smt2                                  |  43.440s  |  43.440s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22495_terminationG_0.smt2                                  |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22496_terminationG_0.smt2                                  |  59.697s  |  59.697s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22499_terminationG_0.smt2                                  |  53.665s  |  53.665s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22500_terminationG_0.smt2                                  |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22501_terminationG_0.smt2                                  |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22504_terminationG_0.smt2                                  |  55.016s  |  55.016s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22505_terminationG_0.smt2                                  |  59.844s  |  59.844s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22506_terminationG_0.smt2                                  |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22514_edge_closing_0.smt2                                  |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22516_edge_closing_0.smt2                                  |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22517_edge_closing_0.smt2                                  |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22520_edge_closing_0.smt2                                  |   0.598s  |   0.598s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22522_edge_closing_0.smt2                                  |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22523_edge_closing_0.smt2                                  |   0.621s  |   0.621s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__terminationS_1_0.smt2                                       |   2.417s  |   2.417s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__terminationS_2_0.smt2                                       |   2.365s  |   2.365s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__terminationS_3_0.smt2                                       |  18.403s  |  18.403s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22530_terminationG_0.smt2                                        |   0.484s  |   0.484s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22531_terminationG_0.smt2                                        |   2.220s  |   2.220s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        |  59.914s  |  59.914s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22535_terminationG_0.smt2                                        |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22536_terminationG_0.smt2                                        |   2.472s  |   2.472s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22537_terminationG_0.smt2                                        |  59.920s  |  59.920s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22540_terminationG_0.smt2                                        |   0.650s  |   0.650s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22541_terminationG_0.smt2                                        |   2.527s  |   2.527s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22542_terminationG_0.smt2                                        |  59.012s  |  59.012s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22545_terminationG_0.smt2                                        |   0.962s  |   0.962s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22546_terminationG_0.smt2                                        |   2.456s  |   2.456s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22547_terminationG_0.smt2                                        |  59.157s  |  59.157s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22550_terminationG_0.smt2                                        |   1.908s  |   1.908s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22551_terminationG_0.smt2                                        |  24.666s  |  24.666s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22552_terminationG_0.smt2                                        |  58.058s  |  58.058s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22555_terminationG_0.smt2                                        |   0.979s  |   0.979s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22556_terminationG_0.smt2                                        |   2.570s  |   2.570s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22557_terminationG_0.smt2                                        |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__terminationQ_5_0.smt2                                             |   0.642s  |   0.642s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22575_terminationG_0.smt2                                              |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   0.667s  |   0.667s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22594_terminationG_0.smt2                                              |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|Stroeder_15__Et2.c__p22608_terminationG_0.smt2                                              |   2.191s  |   2.191s  |   0.000s  | 0.0%|
|Stroeder_15__Et2.c__p22609_terminationG_0.smt2                                              |  59.616s  |  59.616s  |   0.000s  | 0.0%|
|Stroeder_15__Et2.c__p22613_edge_closing_0.smt2                                              |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |  17.647s  |  17.647s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22640_terminationG_0.smt2                                              |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22641_terminationG_0.smt2                                              |  59.894s  |  59.894s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22653_edge_closing_0.smt2                                              |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22658_edge_closing_0.smt2                                              |   1.686s  |   1.686s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22659_edge_closing_0.smt2                                              |   1.743s  |   1.743s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__terminationS_0_0.smt2                                                   |   2.155s  |   2.155s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22671_terminationG_0.smt2                                             |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22672_terminationG_0.smt2                                             |   2.128s  |   2.128s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |  59.302s  |  59.302s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22676_terminationG_0.smt2                                             |   0.745s  |   0.745s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22677_terminationG_0.smt2                                             |   2.282s  |   2.282s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22678_terminationG_0.smt2                                             |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22698_terminationG_0.smt2                                             |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22699_terminationG_0.smt2                                             |   1.369s  |   1.369s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22700_terminationG_0.smt2                                             |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22703_terminationG_0.smt2                                             |   0.856s  |   0.856s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22704_terminationG_0.smt2                                             |   2.242s  |   2.242s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22705_terminationG_0.smt2                                             |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22750_terminationG_0.smt2                                             |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   2.091s  |   2.091s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22752_terminationG_0.smt2                                             |   2.795s  |   2.795s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   0.711s  |   0.711s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   2.345s  |   2.345s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   3.192s  |   3.192s  |   0.000s  | 0.0%|
|Stroeder_15__Ex06.c__p22785_edge_closing_0.smt2                                             |   0.966s  |   0.966s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22818_terminationG_0.smt2                                             |   1.166s  |   1.166s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22820_terminationG_0.smt2                                             |   8.874s  |   8.874s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   0.378s  |   0.378s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22835_terminationG_0.smt2                                        |   0.711s  |   0.711s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22836_terminationG_0.smt2                                        |   0.784s  |   0.784s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22837_terminationG_0.smt2                                        |   1.264s  |   1.264s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22842_terminationG_0.smt2                                        |   2.793s  |   2.793s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22843_terminationG_0.smt2                                        |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22844_terminationG_0.smt2                                        |  59.915s  |  59.915s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22847_terminationG_0.smt2                                        |   2.811s  |   2.811s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22848_terminationG_0.smt2                                        |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22849_terminationG_0.smt2                                        |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |  11.412s  |  11.412s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22853_terminationG_0.smt2                                        |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22857_terminationG_0.smt2                                        |   2.602s  |   2.602s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22858_terminationG_0.smt2                                        |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22859_terminationG_0.smt2                                        |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__terminationQ_3_0.smt2                                             |   3.028s  |   3.028s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22868_terminationG_0.smt2                                        |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   2.168s  |   2.168s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22873_terminationG_0.smt2                                        |   0.666s  |   0.666s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22879_terminationG_0.smt2                                        |   6.403s  |   6.403s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22880_terminationG_0.smt2                                        |   0.683s  |   0.683s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22883_terminationG_0.smt2                                        |   2.144s  |   2.144s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22884_terminationG_0.smt2                                        |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22885_terminationG_0.smt2                                        |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22888_terminationG_0.smt2                                        |   2.325s  |   2.325s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22889_terminationG_0.smt2                                        |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22890_terminationG_0.smt2                                        |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22893_terminationG_0.smt2                                        |   2.354s  |   2.354s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22895_terminationG_0.smt2                                        |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22896_terminationG_0.smt2                                        |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22899_terminationG_0.smt2                                        |   2.384s  |   2.384s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22900_terminationG_0.smt2                                        |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22901_terminationG_0.smt2                                        |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__terminationQ_3_0.smt2                                             |   2.351s  |   2.351s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p22994_terminationG_0.smt2                                             |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23021_terminationG_0.smt2                                             |  59.886s  |  59.886s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23022_terminationG_0.smt2                                             |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23033_edge_closing_0.smt2                                             |   0.563s  |   0.563s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23038_edge_closing_0.smt2                                             |   2.205s  |   2.205s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23039_edge_closing_0.smt2                                             |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22917_terminationG_0.smt2                                            |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22918_terminationG_0.smt2                                            |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22927_terminationG_0.smt2                                            |   0.859s  |   0.859s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22933_terminationG_0.smt2                                            |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22937_terminationG_0.smt2                                            |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22938_terminationG_0.smt2                                            |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22942_edge_closing_0.smt2                                            |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22953_edge_closing_0.smt2                                            |   1.647s  |   1.647s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22954_edge_closing_0.smt2                                            |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22955_edge_closing_0.smt2                                            |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23156_terminationG_0.smt2                                              |   2.068s  |   2.068s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23157_terminationG_0.smt2                                              |   0.600s  |   0.600s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23158_terminationG_0.smt2                                              |   0.695s  |   0.695s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23167_terminationG_0.smt2                                              |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23168_terminationG_0.smt2                                              |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23171_terminationG_0.smt2                                              |  11.437s  |  11.437s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23172_terminationG_0.smt2                                              |   1.909s  |   1.909s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23178_terminationG_0.smt2                                              |   0.898s  |   0.898s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23179_terminationG_0.smt2                                              |   1.968s  |   1.968s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23180_terminationG_0.smt2                                              |   6.786s  |   6.786s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23183_terminationG_0.smt2                                              |   1.820s  |   1.820s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23184_terminationG_0.smt2                                              |   1.840s  |   1.840s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23185_terminationG_0.smt2                                              |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23188_terminationG_0.smt2                                              |   2.366s  |   2.366s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23189_terminationG_0.smt2                                              |   0.628s  |   0.628s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23190_terminationG_0.smt2                                              |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23200_terminationG_0.smt2                                              |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23201_terminationG_0.smt2                                              |   5.362s  |   5.362s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23202_terminationG_0.smt2                                              |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23206_terminationG_0.smt2                                              |   0.555s  |   0.555s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23207_terminationG_0.smt2                                              |   0.641s  |   0.641s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23210_terminationG_0.smt2                                              |   2.357s  |   2.357s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23211_terminationG_0.smt2                                              |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23212_terminationG_0.smt2                                              |  59.931s  |  59.931s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23215_edge_closing_0.smt2                                              |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23216_edge_closing_0.smt2                                              |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23222_edge_closing_0.smt2                                              |   1.422s  |   1.422s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23223_edge_closing_0.smt2                                              |   2.378s  |   2.378s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_0_0.smt2                                                   |   2.172s  |   2.172s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_1_0.smt2                                                   |   2.190s  |   2.190s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   2.460s  |   2.460s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_8_0.smt2                                                   |   2.600s  |   2.600s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23102_terminationG_0.smt2                                             |   1.164s  |   1.164s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23106_terminationG_0.smt2                                             |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23107_terminationG_0.smt2                                             |   1.269s  |   1.269s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23110_terminationG_0.smt2                                             |   0.886s  |   0.886s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23111_terminationG_0.smt2                                             |   0.686s  |   0.686s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23112_terminationG_0.smt2                                             |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23116_terminationG_0.smt2                                             |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23117_terminationG_0.smt2                                             |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23120_terminationG_0.smt2                                             |   2.349s  |   2.349s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23121_terminationG_0.smt2                                             |  59.838s  |  59.838s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23122_terminationG_0.smt2                                             |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23125_edge_closing_0.smt2                                             |   0.938s  |   0.938s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23126_edge_closing_0.smt2                                             |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23132_edge_closing_0.smt2                                             |   1.314s  |   1.314s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23133_edge_closing_0.smt2                                             |   2.180s  |   2.180s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23050_terminationG_0.smt2                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23054_terminationG_0.smt2                                            |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23055_terminationG_0.smt2                                            |   2.531s  |   2.531s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23056_terminationG_0.smt2                                            |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23059_terminationG_0.smt2                                            |   1.290s  |   1.290s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23060_terminationG_0.smt2                                            |   2.297s  |   2.297s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23061_terminationG_0.smt2                                            |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23064_terminationG_0.smt2                                            |   2.211s  |   2.211s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23065_terminationG_0.smt2                                            |   2.347s  |   2.347s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23066_terminationG_0.smt2                                            |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23069_terminationG_0.smt2                                            |   2.446s  |   2.446s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23070_terminationG_0.smt2                                            |  21.942s  |  21.942s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23071_terminationG_0.smt2                                            |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23074_terminationG_0.smt2                                            |   2.405s  |   2.405s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23075_terminationG_0.smt2                                            |  18.092s  |  18.092s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23076_terminationG_0.smt2                                            |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23080_edge_closing_0.smt2                                            |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23084_edge_closing_0.smt2                                            |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|Stroeder_15__Gothenburg_true-termination.c__p23242_terminationG_0.smt2                      |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|Stroeder_15__Gothenburg_true-termination.c__p23243_terminationG_0.smt2                      |   0.378s  |   0.378s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23267_terminationG_0.smt2  |   2.372s  |   2.372s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23268_terminationG_0.smt2  |   0.625s  |   0.625s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23269_terminationG_0.smt2  |   1.154s  |   1.154s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23272_terminationG_0.smt2  |   2.255s  |   2.255s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23273_terminationG_0.smt2  |  59.824s  |  59.824s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23274_terminationG_0.smt2  |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23277_edge_closing_0.smt2  |   0.614s  |   0.614s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23278_edge_closing_0.smt2  |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23280_edge_closing_0.smt2  |   2.169s  |   2.169s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23281_edge_closing_0.smt2  |   1.053s  |   1.053s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23282_edge_closing_0.smt2  |   1.639s  |   1.639s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23283_edge_closing_0.smt2  |   2.243s  |   2.243s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23284_edge_closing_0.smt2  |   1.628s  |   1.628s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23285_edge_closing_0.smt2  |   1.566s  |   1.566s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23288_edge_closing_0.smt2  |   0.425s  |   0.425s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23291_edge_closing_0.smt2  |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23309_edge_closing_0.smt2  |  59.911s  |  59.911s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23310_edge_closing_0.smt2  |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23319_edge_closing_0.smt2  |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23321_edge_closing_0.smt2  |  59.917s  |  59.917s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23322_edge_closing_0.smt2  |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23328_edge_closing_0.smt2  |   0.691s  |   0.691s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23330_edge_closing_0.smt2  |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23331_edge_closing_0.smt2  |   0.622s  |   0.622s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23333_edge_closing_0.smt2  |  59.913s  |  59.913s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23334_edge_closing_0.smt2  |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23336_edge_closing_0.smt2  |   0.606s  |   0.606s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23339_edge_closing_0.smt2  |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23340_edge_closing_0.smt2  |  59.869s  |  59.869s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23343_edge_closing_0.smt2  |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23345_edge_closing_0.smt2  |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23346_edge_closing_0.smt2  |   0.454s  |   0.454s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23348_edge_closing_0.smt2  |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23349_edge_closing_0.smt2  |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23354_edge_closing_0.smt2  |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23367_edge_closing_0.smt2  |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23403_edge_closing_0.smt2  |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23406_edge_closing_0.smt2  |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23408_edge_closing_0.smt2  |  37.939s  |  37.939s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23409_edge_closing_0.smt2  |  59.886s  |  59.886s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23412_edge_closing_0.smt2  |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23421_edge_closing_0.smt2  |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23429_edge_closing_0.smt2  |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23430_edge_closing_0.smt2  |   0.462s  |   0.462s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23431_edge_closing_0.smt2  |   2.125s  |   2.125s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23432_edge_closing_0.smt2  |   8.161s  |   8.161s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23433_edge_closing_0.smt2  |   6.307s  |   6.307s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23435_edge_closing_0.smt2  |  59.268s  |  59.268s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23436_edge_closing_0.smt2  |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23438_edge_closing_0.smt2  |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23439_edge_closing_0.smt2  |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23441_edge_closing_0.smt2  |   2.115s  |   2.115s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23442_edge_closing_0.smt2  |   0.751s  |   0.751s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23443_edge_closing_0.smt2  |   2.236s  |   2.236s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23444_edge_closing_0.smt2  |   2.365s  |   2.365s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23445_edge_closing_0.smt2  |  14.305s  |  14.305s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23447_edge_closing_0.smt2  |   2.208s  |   2.208s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23448_edge_closing_0.smt2  |   2.401s  |   2.401s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23450_edge_closing_0.smt2  |   0.484s  |   0.484s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23451_edge_closing_0.smt2  |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23459_edge_closing_0.smt2  |   0.765s  |   0.765s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23460_edge_closing_0.smt2  |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23471_edge_closing_0.smt2  |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |   0.848s  |   0.848s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23473_edge_closing_0.smt2  |   2.127s  |   2.127s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23474_edge_closing_0.smt2  |  59.919s  |  59.919s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23475_edge_closing_0.smt2  |  59.844s  |  59.844s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23477_edge_closing_0.smt2  |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23478_edge_closing_0.smt2  |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23480_edge_closing_0.smt2  |   1.236s  |   1.236s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23482_edge_closing_0.smt2  |   2.290s  |   2.290s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23483_edge_closing_0.smt2  |  59.927s  |  59.927s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23484_edge_closing_0.smt2  |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23486_edge_closing_0.smt2  |   0.638s  |   0.638s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23487_edge_closing_0.smt2  |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23493_edge_closing_0.smt2  |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23501_edge_closing_0.smt2  |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23502_edge_closing_0.smt2  |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23510_edge_closing_0.smt2  |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23522_edge_closing_0.smt2  |   0.612s  |   0.612s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23523_edge_closing_0.smt2  |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23531_edge_closing_0.smt2  |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23532_edge_closing_0.smt2  |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23543_edge_closing_0.smt2  |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23544_edge_closing_0.smt2  |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23550_edge_closing_0.smt2  |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23551_edge_closing_0.smt2  |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23559_edge_closing_0.smt2  |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23560_edge_closing_0.smt2  |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23565_edge_closing_0.smt2  |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23566_edge_closing_0.smt2  |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23577_edge_closing_0.smt2  |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23602_edge_closing_0.smt2  |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23611_edge_closing_0.smt2  |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23616_edge_closing_0.smt2  |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23617_edge_closing_0.smt2  |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23620_edge_closing_0.smt2  |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23628_edge_closing_0.smt2  |   0.600s  |   0.600s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23629_edge_closing_0.smt2  |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23638_edge_closing_0.smt2  |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23646_edge_closing_0.smt2  |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23647_edge_closing_0.smt2  |   0.811s  |   0.811s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23649_edge_closing_0.smt2  |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23650_edge_closing_0.smt2  |  59.739s  |  59.739s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23653_edge_closing_0.smt2  |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23662_edge_closing_0.smt2  |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23667_edge_closing_0.smt2  |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23673_edge_closing_0.smt2  |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23676_edge_closing_0.smt2  |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23677_edge_closing_0.smt2  |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23679_edge_closing_0.smt2  |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23680_edge_closing_0.smt2  |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23686_edge_closing_0.smt2  |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23692_edge_closing_0.smt2  |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23693_edge_closing_0.smt2  |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23699_edge_closing_0.smt2  |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23701_edge_closing_0.smt2  |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23702_edge_closing_0.smt2  |   0.967s  |   0.967s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23703_edge_closing_0.smt2  |   2.133s  |   2.133s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23704_edge_closing_0.smt2  |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23705_edge_closing_0.smt2  |   0.598s  |   0.598s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23707_edge_closing_0.smt2  |   2.191s  |   2.191s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23708_edge_closing_0.smt2  |   2.407s  |   2.407s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23710_edge_closing_0.smt2  |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23711_edge_closing_0.smt2  |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23713_edge_closing_0.smt2  |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23714_edge_closing_0.smt2  |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23715_edge_closing_0.smt2  |   2.218s  |   2.218s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23716_edge_closing_0.smt2  |   1.279s  |   1.279s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23717_edge_closing_0.smt2  |   7.038s  |   7.038s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23719_edge_closing_0.smt2  |  59.894s  |  59.894s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23720_edge_closing_0.smt2  |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23722_edge_closing_0.smt2  |   0.748s  |   0.748s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23723_edge_closing_0.smt2  |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23731_edge_closing_0.smt2  |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23732_edge_closing_0.smt2  |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23734_edge_closing_0.smt2  |   0.395s  |   0.395s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23735_edge_closing_0.smt2  |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23750_edge_closing_0.smt2  |   0.939s  |   0.939s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23751_edge_closing_0.smt2  |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23752_edge_closing_0.smt2  |   2.170s  |   2.170s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23753_edge_closing_0.smt2  |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23754_edge_closing_0.smt2  |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23756_edge_closing_0.smt2  |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23759_edge_closing_0.smt2  |   0.678s  |   0.678s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23760_edge_closing_0.smt2  |   2.107s  |   2.107s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23765_edge_closing_0.smt2  |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23766_edge_closing_0.smt2  |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23774_edge_closing_0.smt2  |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23775_edge_closing_0.smt2  |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23795_edge_closing_0.smt2  |   0.683s  |   0.683s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23796_edge_closing_0.smt2  |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23853_terminationG_0.smt2  |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23856_terminationG_0.smt2  |   2.959s  |   2.959s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23857_terminationG_0.smt2  |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23858_terminationG_0.smt2  |   0.626s  |   0.626s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23863_terminationG_0.smt2  |   2.127s  |   2.127s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23864_terminationG_0.smt2  |   0.528s  |   0.528s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23872_terminationG_0.smt2  |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23873_terminationG_0.smt2  |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23877_terminationG_0.smt2  |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23878_terminationG_0.smt2  |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23886_terminationG_0.smt2  |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23887_terminationG_0.smt2  |   1.009s  |   1.009s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23893_terminationG_0.smt2  |   0.395s  |   0.395s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23894_terminationG_0.smt2  |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23905_terminationG_0.smt2                                              |   0.855s  |   0.855s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23906_terminationG_0.smt2                                              |   1.813s  |   1.813s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23910_terminationG_0.smt2                                              |   2.371s  |   2.371s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23911_terminationG_0.smt2                                              |   0.803s  |   0.803s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23918_terminationG_0.smt2                                              |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23923_terminationG_0.smt2                                              |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23927_terminationG_0.smt2                                              |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23933_terminationG_0.smt2                                              |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23941_terminationG_0.smt2                                              |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23942_terminationG_0.smt2                                              |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23947_terminationG_0.smt2                                              |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23951_terminationG_0.smt2                                              |  59.916s  |  59.916s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23952_terminationG_0.smt2                                              |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23956_edge_closing_0.smt2                                              |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23960_edge_closing_0.smt2                                              |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-TACAS2014-Ex7_true-termination.c__p23983_terminationG_0.smt2     |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-TACAS2014-Fig1_true-termination.c__p24009_terminationG_0.smt2    |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24028_terminationG_0.smt2      |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24029_terminationG_0.smt2      |   0.563s  |   0.563s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24032_terminationG_0.smt2      |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24033_terminationG_0.smt2      |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24034_terminationG_0.smt2      |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24038_terminationG_0.smt2      |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24039_terminationG_0.smt2      |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24042_terminationG_0.smt2      |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24043_terminationG_0.smt2      |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24044_terminationG_0.smt2      |  59.894s  |  59.894s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24047_terminationG_0.smt2      |   0.813s  |   0.813s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24048_terminationG_0.smt2      |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24049_terminationG_0.smt2      |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24052_edge_closing_0.smt2      |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24053_edge_closing_0.smt2      |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24057_edge_closing_0.smt2      |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24084_terminationG_0.smt2      |   2.137s  |   2.137s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24085_terminationG_0.smt2      |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24086_terminationG_0.smt2      |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   1.709s  |   1.709s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24090_terminationG_0.smt2      |  59.745s  |  59.745s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24091_terminationG_0.smt2      |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24094_terminationG_0.smt2      |   2.642s  |   2.642s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24095_terminationG_0.smt2      |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24096_terminationG_0.smt2      |  59.885s  |  59.885s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24099_terminationG_0.smt2      |   2.755s  |   2.755s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24100_terminationG_0.smt2      |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24101_terminationG_0.smt2      |  59.847s  |  59.847s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24121_terminationG_0.smt2        |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24142_terminationG_0.smt2                                          |  59.266s  |  59.266s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24143_terminationG_0.smt2                                          |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24146_terminationG_0.smt2                                          |   2.564s  |   2.564s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24147_terminationG_0.smt2                                          |  59.714s  |  59.714s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24148_terminationG_0.smt2                                          |  59.869s  |  59.869s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24151_terminationG_0.smt2                                          |   2.583s  |   2.583s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24152_terminationG_0.smt2                                          |   2.392s  |   2.392s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24153_terminationG_0.smt2                                          |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24156_terminationG_0.smt2                                          |   2.793s  |   2.793s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24157_terminationG_0.smt2                                          |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24158_terminationG_0.smt2                                          |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__terminationQ_3_0.smt2                                               |   2.330s  |   2.330s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24190_terminationG_0.smt2                                          |   2.126s  |   2.126s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24191_terminationG_0.smt2                                          |  59.885s  |  59.885s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24194_terminationG_0.smt2                                          |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24195_terminationG_0.smt2                                          |   2.342s  |   2.342s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24196_terminationG_0.smt2                                          |  59.748s  |  59.748s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24211_terminationG_0.smt2                                          |   0.558s  |   0.558s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24212_terminationG_0.smt2                                          |   1.569s  |   1.569s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24213_terminationG_0.smt2                                          |   2.608s  |   2.608s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24216_terminationG_0.smt2                                          |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24217_terminationG_0.smt2                                          |   2.331s  |   2.331s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24218_terminationG_0.smt2                                          |   3.546s  |   3.546s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24236_terminationG_0.smt2           |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24237_terminationG_0.smt2           |   0.617s  |   0.617s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24238_terminationG_0.smt2           |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24241_terminationG_0.smt2           |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24242_terminationG_0.smt2           |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   2.097s  |   2.097s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24247_terminationG_0.smt2           |   2.818s  |   2.818s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24248_terminationG_0.smt2           |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24250_edge_closing_0.smt2           |   2.212s  |   2.212s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |  59.932s  |  59.932s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24252_edge_closing_0.smt2           |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|Stroeder_15__McCarthyIterative.c__term_unfeasibility_0_0.smt2                               |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|Stroeder_15__MenloPark_true-termination.c__p24273_terminationG_0.smt2                       |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|Stroeder_15__MenloPark_true-termination.c__p24274_terminationG_0.smt2                       |   1.448s  |   1.448s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24281_terminationG_0.smt2                                           |   1.608s  |   1.608s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24282_terminationG_0.smt2                                           |   0.920s  |   0.920s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24283_terminationG_0.smt2                                           |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24288_terminationG_0.smt2                                           |   1.179s  |   1.179s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24289_terminationG_0.smt2                                           |   2.813s  |   2.813s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24290_terminationG_0.smt2                                           |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24301_terminationG_0.smt2                                           |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24306_terminationG_0.smt2                                           |   0.657s  |   0.657s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24309_terminationG_0.smt2                                           |   1.238s  |   1.238s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24310_terminationG_0.smt2                                           |   2.188s  |   2.188s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24311_terminationG_0.smt2                                           |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24314_terminationG_0.smt2                                           |   1.613s  |   1.613s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24315_terminationG_0.smt2                                           |   2.322s  |   2.322s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24316_terminationG_0.smt2                                           |   3.820s  |   3.820s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24319_terminationG_0.smt2                                           |   2.687s  |   2.687s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24320_terminationG_0.smt2                                           |   2.324s  |   2.324s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24321_terminationG_0.smt2                                           |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24324_terminationG_0.smt2                                           |   2.678s  |   2.678s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24325_terminationG_0.smt2                                           |   2.375s  |   2.375s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24326_terminationG_0.smt2                                           |  59.785s  |  59.785s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24329_terminationG_0.smt2                                           |   2.658s  |   2.658s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24330_terminationG_0.smt2                                           |   2.297s  |   2.297s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24331_terminationG_0.smt2                                           |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24334_terminationG_0.smt2                                           |   2.352s  |   2.352s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24335_terminationG_0.smt2                                           |   2.390s  |   2.390s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24336_terminationG_0.smt2                                           |  59.931s  |  59.931s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24339_edge_closing_0.smt2                                           |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24344_edge_closing_0.smt2                                           |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24368_terminationG_0.smt2                                     |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24373_terminationG_0.smt2                                     |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24374_terminationG_0.smt2                                     |   0.612s  |   0.612s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24377_terminationG_0.smt2                                     |   2.807s  |   2.807s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24378_terminationG_0.smt2                                     |   0.863s  |   0.863s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24379_terminationG_0.smt2                                     |   5.868s  |   5.868s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24382_terminationG_0.smt2                                     |   2.157s  |   2.157s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24383_terminationG_0.smt2                                     |   2.433s  |   2.433s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24384_terminationG_0.smt2                                     |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24387_terminationG_0.smt2                                     |   2.021s  |   2.021s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24388_terminationG_0.smt2                                     |   2.402s  |   2.402s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24389_terminationG_0.smt2                                     |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24392_terminationG_0.smt2                                     |   1.517s  |   1.517s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24393_terminationG_0.smt2                                     |  59.921s  |  59.921s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24394_terminationG_0.smt2                                     |  59.865s  |  59.865s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24397_terminationG_0.smt2                                     |   2.764s  |   2.764s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24398_terminationG_0.smt2                                     |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24399_terminationG_0.smt2                                     |  59.916s  |  59.916s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24402_terminationG_0.smt2                                     |   2.332s  |   2.332s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24403_terminationG_0.smt2                                     |   2.609s  |   2.609s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24404_terminationG_0.smt2                                     |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24407_terminationG_0.smt2                                     |   2.319s  |   2.319s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24408_terminationG_0.smt2                                     |   2.468s  |   2.468s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24409_terminationG_0.smt2                                     |  59.958s  |  59.958s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24413_edge_closing_0.smt2                                     |   1.083s  |   1.083s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24415_edge_closing_0.smt2                                     |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24422_edge_closing_0.smt2                                     |   1.794s  |   1.794s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |   7.822s  |   7.822s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24426_edge_closing_0.smt2                                     |   1.068s  |   1.068s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24432_edge_closing_0.smt2                                     |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24443_edge_closing_0.smt2                                     |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24446_edge_closing_0.smt2                                     |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24447_edge_closing_0.smt2                                     |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24449_edge_closing_0.smt2                                     |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24450_edge_closing_0.smt2                                     |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__terminationQ_5_0.smt2                                          |   2.329s  |   2.329s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__terminationS_0_0.smt2                                          |   2.323s  |   2.323s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__terminationS_1_0.smt2                                          |   2.217s  |   2.217s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24464_terminationG_0.smt2                                  |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24482_terminationG_0.smt2                                  |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24484_terminationG_0.smt2                                  |  59.908s  |  59.908s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationQ_0_0.smt2                                       |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.462s  |   0.462s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_1_0.smt2                                       |   2.450s  |   2.450s  |   0.000s  | 0.0%|
|Stroeder_15__NO_03.c__p24634_terminationG_0.smt2                                            |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Stroeder_15__NO_03.c__terminationQ_0_0.smt2                                                 |   1.552s  |   1.552s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24648_safety_0.smt2                                                  |   8.970s  |   8.970s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24649_safety_0.smt2                                                  |   2.118s  |   2.118s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24650_safety_0.smt2                                                  |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24651_safety_0.smt2                                                  |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24653_safety_0.smt2                                                  |  59.881s  |  59.881s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24654_safety_0.smt2                                                  |  59.800s  |  59.800s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__term_unfeasibility_0_0.smt2                                           |   2.338s  |   2.338s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__term_unfeasibility_2_0.smt2                                           |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__term_unfeasibility_4_0.smt2                                           |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24669_terminationG_0.smt2                                            |   0.670s  |   0.670s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   2.636s  |   2.636s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24671_terminationG_0.smt2                                            |  59.958s  |  59.958s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24674_terminationG_0.smt2                                            |   2.046s  |   2.046s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24675_terminationG_0.smt2                                            |   2.406s  |   2.406s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24676_terminationG_0.smt2                                            |  59.913s  |  59.913s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24679_terminationG_0.smt2                                            |   1.756s  |   1.756s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24680_terminationG_0.smt2                                            |   2.315s  |   2.315s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24681_terminationG_0.smt2                                            |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24684_terminationG_0.smt2                                            |   2.009s  |   2.009s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24685_terminationG_0.smt2                                            |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24686_terminationG_0.smt2                                            |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24689_terminationG_0.smt2                                            |   2.672s  |   2.672s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24690_terminationG_0.smt2                                            |   2.297s  |   2.297s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24691_terminationG_0.smt2                                            |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24694_terminationG_0.smt2                                            |   2.081s  |   2.081s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24695_terminationG_0.smt2                                            |   2.356s  |   2.356s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24696_terminationG_0.smt2                                            |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__terminationQ_5_0.smt2                                                 |   2.594s  |   2.594s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24711_terminationG_0.smt2                                            |   2.171s  |   2.171s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  59.878s  |  59.878s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24713_terminationG_0.smt2                                            |  59.924s  |  59.924s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24716_terminationG_0.smt2                                            |   2.347s  |   2.347s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24717_terminationG_0.smt2                                            |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24718_terminationG_0.smt2                                            |  59.848s  |  59.848s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24721_terminationG_0.smt2                                            |   2.299s  |   2.299s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24722_terminationG_0.smt2                                            |  59.931s  |  59.931s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24723_terminationG_0.smt2                                            |  59.932s  |  59.932s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24726_terminationG_0.smt2                                            |   2.292s  |   2.292s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |   2.882s  |   2.882s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24728_terminationG_0.smt2                                            |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24730_terminationG_0.smt2                                            |   2.199s  |   2.199s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24732_terminationG_0.smt2                                            |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24733_terminationG_0.smt2                                            |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24737_edge_closing_0.smt2                                            |   0.789s  |   0.789s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationQ_4_0.smt2                                                 |   2.273s  |   2.273s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   2.363s  |   2.363s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_1_0.smt2                                                 |   2.299s  |   2.299s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24748_terminationG_0.smt2                                            |   9.878s  |   9.878s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24750_terminationG_0.smt2                                            |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24752_edge_closing_0.smt2                                            |   2.157s  |   2.157s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__term_unfeasibility_0_0.smt2                                           |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__terminationQ_0_0.smt2                                                 |  25.037s  |  25.037s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__terminationS_0_0.smt2                                                 |   1.213s  |   1.213s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__terminationS_1_0.smt2                                                 |   1.742s  |   1.742s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24780_terminationG_0.smt2                                            |   2.095s  |   2.095s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24781_terminationG_0.smt2                                            |   2.631s  |   2.631s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24782_terminationG_0.smt2                                            |   2.570s  |   2.570s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24785_edge_closing_0.smt2                                            |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24786_edge_closing_0.smt2                                            |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__term_unfeasibility_0_0.smt2                                           |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__terminationS_0_0.smt2                                                 |   0.608s  |   0.608s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24797_terminationG_0.smt2                                            |   2.343s  |   2.343s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24798_terminationG_0.smt2                                            |  51.195s  |  51.195s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24799_terminationG_0.smt2                                            |  59.791s  |  59.791s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24804_edge_closing_0.smt2                                            |   0.604s  |   0.604s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__term_unfeasibility_0_0.smt2                                           |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__terminationQ_0_0.smt2                                                 |   1.930s  |   1.930s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__terminationS_0_0.smt2                                                 |   0.949s  |   0.949s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__terminationS_1_0.smt2                                                 |   0.973s  |   0.973s  |   0.000s  | 0.0%|
|Stroeder_15__NO_24.c__p24815_terminationG_0.smt2                                            |  37.753s  |  37.753s  |   0.000s  | 0.0%|
|Stroeder_15__NO_24.c__p24816_terminationG_0.smt2                                            |  60.049s  |  60.049s  |   0.000s  | 0.0%|
|Stroeder_15__NO_24.c__p24820_edge_closing_0.smt2                                            |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|Stroeder_15__NarrowKonv.c__p24579_edge_closing_0.smt2                                       |   0.946s  |   0.946s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24515_terminationG_0.smt2                                        |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24516_terminationG_0.smt2                                        |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24519_terminationG_0.smt2                                        |   0.667s  |   0.667s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24520_terminationG_0.smt2                                        |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24521_terminationG_0.smt2                                        |   0.625s  |   0.625s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24524_terminationG_0.smt2                                        |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24525_terminationG_0.smt2                                        |   0.801s  |   0.801s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24526_terminationG_0.smt2                                        |   0.575s  |   0.575s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24529_terminationG_0.smt2                                        |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24530_terminationG_0.smt2                                        |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24531_terminationG_0.smt2                                        |   1.653s  |   1.653s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24534_terminationG_0.smt2                                        |  35.573s  |  35.573s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24535_terminationG_0.smt2                                        |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24536_terminationG_0.smt2                                        |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24539_terminationG_0.smt2                                        |  26.931s  |  26.931s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24540_terminationG_0.smt2                                        |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24541_terminationG_0.smt2                                        |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24544_edge_closing_0.smt2                                        |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24545_edge_closing_0.smt2                                        |  59.708s  |  59.708s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24547_edge_closing_0.smt2                                        |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24548_edge_closing_0.smt2                                        |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24549_edge_closing_0.smt2                                        |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24551_edge_closing_0.smt2                                        |   1.433s  |   1.433s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24552_edge_closing_0.smt2                                        |  59.736s  |  59.736s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__term_unfeasibility_2_0.smt2                                       |   2.484s  |   2.484s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationQ_0_0.smt2                                             |  27.683s  |  27.683s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_0_0.smt2                                             |  11.536s  |  11.536s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_1_0.smt2                                             |  18.119s  |  18.119s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_2_0.smt2                                             |   3.106s  |   3.106s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_3_0.smt2                                             |  17.689s  |  17.689s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24837_terminationG_0.smt2                |   2.134s  |   2.134s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24838_terminationG_0.smt2                |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24841_terminationG_0.smt2                |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   3.412s  |   3.412s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24843_terminationG_0.smt2                |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24848_edge_closing_0.smt2                |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24888_terminationG_0.smt2                |   1.425s  |   1.425s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24896_terminationG_0.smt2                |   2.477s  |   2.477s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24897_terminationG_0.smt2                |   2.917s  |   2.917s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24907_terminationG_0.smt2                |   2.667s  |   2.667s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24908_terminationG_0.smt2                |   6.661s  |   6.661s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24918_terminationG_0.smt2                |   2.906s  |   2.906s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24919_terminationG_0.smt2                |   9.822s  |   9.822s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24923_terminationG_0.smt2                |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24924_terminationG_0.smt2                |  25.098s  |  25.098s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24932_edge_closing_0.smt2                |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24935_edge_closing_0.smt2                |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24937_edge_closing_0.smt2                |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24938_edge_closing_0.smt2                |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24939_edge_closing_0.smt2                |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24941_edge_closing_0.smt2                |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24949_terminationG_0.smt2                |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24950_terminationG_0.smt2                |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24953_terminationG_0.smt2                |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24954_terminationG_0.smt2                |  59.873s  |  59.873s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                |  59.917s  |  59.917s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24957_terminationG_0.smt2                |   1.507s  |   1.507s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24959_terminationG_0.smt2                |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24960_terminationG_0.smt2                |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24967_terminationG_0.smt2                |   2.221s  |   2.221s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24969_terminationG_0.smt2                |  59.919s  |  59.919s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24970_terminationG_0.smt2                |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24973_terminationG_0.smt2                |   2.169s  |   2.169s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24974_terminationG_0.smt2                |  59.915s  |  59.915s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24975_terminationG_0.smt2                |  59.931s  |  59.931s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24982_edge_closing_0.smt2                |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24983_edge_closing_0.smt2                |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__terminationQ_4_0.smt2                     |   2.809s  |   2.809s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p24995_terminationG_0.smt2          |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p24996_terminationG_0.smt2          |   2.098s  |   2.098s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p24997_terminationG_0.smt2          |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p25000_terminationG_0.smt2          |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p25001_terminationG_0.smt2          |   2.323s  |   2.323s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p25002_terminationG_0.smt2          |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple3_false-termination.c__p25033_terminationG_0.smt2          |   2.185s  |   2.185s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple3_false-termination.c__p25034_terminationG_0.smt2          |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25060_terminationG_0.smt2          |   0.910s  |   0.910s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25061_terminationG_0.smt2          |   2.139s  |   2.139s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25062_terminationG_0.smt2          |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25065_terminationG_0.smt2          |   0.980s  |   0.980s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25066_terminationG_0.smt2          |   2.438s  |   2.438s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25067_terminationG_0.smt2          |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25070_terminationG_0.smt2          |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25071_terminationG_0.smt2          |   2.370s  |   2.370s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25072_terminationG_0.smt2          |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25075_terminationG_0.smt2          |   1.477s  |   1.477s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25076_terminationG_0.smt2          |   2.463s  |   2.463s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25077_terminationG_0.smt2          |   4.182s  |   4.182s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25081_edge_closing_0.smt2          |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__terminationQ_3_0.smt2               |   0.635s  |   0.635s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple5_false-termination.c__p25094_terminationG_0.smt2          |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple5_false-termination.c__p25098_terminationG_0.smt2          |   2.206s  |   2.206s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple5_false-termination.c__p25099_terminationG_0.smt2          |   2.556s  |   2.556s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25119_terminationG_0.smt2          |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25120_terminationG_0.smt2          |   2.121s  |   2.121s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25124_terminationG_0.smt2          |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25125_terminationG_0.smt2          |   2.326s  |   2.326s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25126_terminationG_0.smt2          |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25130_edge_closing_0.smt2          |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple7_false-termination.c__p25147_terminationG_0.smt2          |   2.200s  |   2.200s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple7_false-termination.c__p25148_terminationG_0.smt2          |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple7_false-termination.c__p25159_edge_closing_0.smt2          |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25174_terminationG_0.smt2          |   2.207s  |   2.207s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25175_terminationG_0.smt2          |   2.426s  |   2.426s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25176_terminationG_0.smt2          |   3.412s  |   3.412s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25179_terminationG_0.smt2          |   2.254s  |   2.254s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25180_terminationG_0.smt2          |   2.351s  |   2.351s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25181_terminationG_0.smt2          |   2.662s  |   2.662s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25184_edge_closing_0.smt2          |   1.328s  |   1.328s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   0.751s  |   0.751s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25189_edge_closing_0.smt2          |   0.918s  |   0.918s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25202_terminationG_0.smt2          |   0.494s  |   0.494s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   2.144s  |   2.144s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   6.407s  |   6.407s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25336_terminationG_0.smt2                                         |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25382_terminationG_0.smt2                                         |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25387_terminationG_0.smt2                                         |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25391_terminationG_0.smt2                                         |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25392_terminationG_0.smt2                                         |   0.883s  |   0.883s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig1_true-termination.c__p25400_terminationG_0.smt2  |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25419_terminationG_0.smt2  |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25424_terminationG_0.smt2  |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25425_terminationG_0.smt2  |   0.622s  |   0.622s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25430_terminationG_0.smt2  |   6.217s  |   6.217s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25433_terminationG_0.smt2  |   2.292s  |   2.292s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25434_terminationG_0.smt2  |   9.678s  |   9.678s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25435_terminationG_0.smt2  |  12.776s  |  12.776s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25440_terminationG_0.smt2  |   1.001s  |   1.001s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25441_terminationG_0.smt2  |  59.816s  |  59.816s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25442_terminationG_0.smt2  |   5.824s  |   5.824s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25447_terminationG_0.smt2  |   4.020s  |   4.020s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25448_terminationG_0.smt2  |  59.933s  |  59.933s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25449_terminationG_0.smt2  |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25476_terminationG_0.smt2  |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25479_terminationG_0.smt2  |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25480_terminationG_0.smt2  |   9.999s  |   9.999s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25481_terminationG_0.smt2  |  59.896s  |  59.896s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25484_edge_closing_0.smt2  |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25485_edge_closing_0.smt2  |  59.912s  |  59.912s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25505_terminationG_0.smt2                      |   2.160s  |   2.160s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25506_terminationG_0.smt2                      |   2.406s  |   2.406s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25507_terminationG_0.smt2                      |   1.440s  |   1.440s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |   1.693s  |   1.693s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25519_terminationG_0.smt2                      |  55.284s  |  55.284s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25530_terminationG_0.smt2                      |   8.611s  |   8.611s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25531_terminationG_0.smt2                      |   0.639s  |   0.639s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25532_terminationG_0.smt2                      |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25536_terminationG_0.smt2                      |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25537_terminationG_0.smt2                      |   0.559s  |   0.559s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25541_terminationG_0.smt2                      |   0.619s  |   0.619s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25542_terminationG_0.smt2                      |   5.480s  |   5.480s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25546_terminationG_0.smt2                      |   0.800s  |   0.800s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25547_terminationG_0.smt2                      |   5.469s  |   5.469s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25559_terminationG_0.smt2                      |   1.003s  |   1.003s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25560_terminationG_0.smt2                      |  59.927s  |  59.927s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25566_terminationG_0.smt2                      |   9.273s  |   9.273s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25567_terminationG_0.smt2                      |  60.097s  |  60.097s  |   0.000s  | 0.0%|
|Stroeder_15__Rotation180_false-termination.c__p25579_terminationG_0.smt2                    |   1.575s  |   1.575s  |   0.000s  | 0.0%|
|Stroeder_15__Rotation180_false-termination.c__p25580_terminationG_0.smt2                    |  59.921s  |  59.921s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25604_terminationG_0.smt2                                           |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25608_terminationG_0.smt2                                           |   0.652s  |   0.652s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25609_terminationG_0.smt2                                           |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25619_terminationG_0.smt2                                           |   1.353s  |   1.353s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25622_terminationG_0.smt2                                           |  11.269s  |  11.269s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25624_terminationG_0.smt2                                           |  59.928s  |  59.928s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25629_edge_closing_0.smt2                                           |   0.588s  |   0.588s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25637_edge_closing_0.smt2                                           |   0.684s  |   0.684s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__terminationQ_0_0.smt2                                                |   7.472s  |   7.472s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__terminationS_0_0.smt2                                                |   1.650s  |   1.650s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__terminationS_1_0.smt2                                                |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__Swingers.c__p26084_terminationG_0.smt2                                         |  59.812s  |  59.812s  |   0.000s  | 0.0%|
|Stroeder_15__Swingers.c__p26085_terminationG_0.smt2                                         |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|Stroeder_15__Swingers.c__p26089_edge_closing_0.smt2                                         |   0.627s  |   0.627s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-BranchesToLoop_true-termination.c__p26120_terminationG_0.smt2         |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-BranchesToLoop_true-termination.c__p26125_terminationG_0.smt2         |   0.603s  |   0.603s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-MultiBranchesToLoop_true-termination.c__p26134_terminationG_0.smt2    |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-MultiBranchesToLoop_true-termination.c__p26139_terminationG_0.smt2    |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26151_terminationG_0.smt2                                          |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26152_terminationG_0.smt2                                          |   2.102s  |   2.102s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26153_terminationG_0.smt2                                          |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26156_terminationG_0.smt2                                          |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26157_terminationG_0.smt2                                          |   2.389s  |   2.389s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26158_terminationG_0.smt2                                          |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|Stroeder_15__TwoFloatInterv.c__p26170_safety_0.smt2                                         |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|Stroeder_15__TwoFloatInterv.c__p26181_edge_closing_0.smt2                                   |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26197_terminationG_0.smt2                                        |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26198_terminationG_0.smt2                                        |   0.612s  |   0.612s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26203_terminationG_0.smt2                                        |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26206_edge_closing_0.smt2                                        |   0.676s  |   0.676s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26207_edge_closing_0.smt2                                        |   1.316s  |   1.316s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26213_edge_closing_0.smt2                                        |   0.847s  |   0.847s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26214_edge_closing_0.smt2                                        |   1.488s  |   1.488s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__terminationS_3_0.smt2                                             |   2.242s  |   2.242s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26230_terminationG_0.smt2                                    |   0.737s  |   0.737s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26231_terminationG_0.smt2                                    |   0.519s  |   0.519s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26235_terminationG_0.smt2                                    |  59.924s  |  59.924s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26236_terminationG_0.smt2                                    |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26239_edge_closing_0.smt2                                    |   0.630s  |   0.630s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26240_edge_closing_0.smt2                                    |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26246_edge_closing_0.smt2                                    |   1.243s  |   1.243s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26247_edge_closing_0.smt2                                    |   2.328s  |   2.328s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig1_false-termination.c__p26265_safety_0.smt2                   |   2.097s  |   2.097s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig1_false-termination.c__p26266_safety_0.smt2                   |   2.415s  |   2.415s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig2-modified1000_true-termination.c__term_unfeasibility_0_0.smt2  |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig2_true-termination.c__term_unfeasibility_0_0.smt2             |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26291_terminationG_0.smt2                       |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26301_terminationG_0.smt2                       |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.528s  |   0.528s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26335_terminationG_0.smt2                       |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26336_terminationG_0.smt2                       |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__terminationQ_0_0.smt2                            |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__terminationS_0_0.smt2                            |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__terminationS_1_0.smt2                            |   1.975s  |   1.975s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26374_terminationG_0.smt2                                        |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26375_terminationG_0.smt2                                        |   2.131s  |   2.131s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26376_terminationG_0.smt2                                        |  59.870s  |  59.870s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26380_terminationG_0.smt2                                        |   0.621s  |   0.621s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26381_terminationG_0.smt2                                        |   2.127s  |   2.127s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26407_terminationG_0.smt2                                    |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26408_terminationG_0.smt2                                    |   2.125s  |   2.125s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26409_terminationG_0.smt2                                    |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26412_terminationG_0.smt2                                    |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26413_terminationG_0.smt2                                    |   2.319s  |   2.319s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26414_terminationG_0.smt2                                    |  59.836s  |  59.836s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26429_terminationG_0.smt2                                      |   2.097s  |   2.097s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26430_terminationG_0.smt2                                      |  48.195s  |  48.195s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26431_terminationG_0.smt2                                      |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26434_terminationG_0.smt2                                      |   2.234s  |   2.234s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26435_terminationG_0.smt2                                      |   2.465s  |   2.465s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26436_terminationG_0.smt2                                      |  59.867s  |  59.867s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__terminationQ_1_0.smt2                                           |   1.740s  |   1.740s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   1.669s  |   1.669s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26452_terminationG_0.smt2                                |  59.921s  |  59.921s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26453_terminationG_0.smt2                                |  59.855s  |  59.855s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26456_terminationG_0.smt2                                |   2.303s  |   2.303s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26457_terminationG_0.smt2                                |  59.907s  |  59.907s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__terminationQ_1_0.smt2                                     |   1.532s  |   1.532s  |   0.000s  | 0.0%|
|Stroeder_15__WhilePart.c__p26472_safety_0.smt2                                              |   2.099s  |   2.099s  |   0.000s  | 0.0%|
|Stroeder_15__WhilePart.c__p26473_safety_0.smt2                                              |   2.416s  |   2.416s  |   0.000s  | 0.0%|
|Stroeder_15__WhileSingle.c__p26489_edge_closing_0.smt2                                      |   0.642s  |   0.642s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20348_terminationG_0.smt2                          |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   0.809s  |   0.809s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20359_terminationG_0.smt2                          |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20363_terminationG_0.smt2                          |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20364_terminationG_0.smt2                          |   0.667s  |   0.667s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20368_terminationG_0.smt2                          |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20369_terminationG_0.smt2                          |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22217_terminationG_0.smt2                                          |  15.097s  |  15.097s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22218_terminationG_0.smt2                                          |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22219_terminationG_0.smt2                                          |  59.869s  |  59.869s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22228_edge_closing_0.smt2                                          |  35.753s  |  35.753s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22230_edge_closing_0.smt2                                          |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22231_edge_closing_0.smt2                                          |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__term_unfeasibility_1_0.smt2                                         |   2.131s  |   2.131s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__terminationQ_0_0.smt2                                               |  20.789s  |  20.789s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__terminationS_0_0.smt2                                               |   2.181s  |   2.181s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__terminationS_1_0.smt2                                               |   2.173s  |   2.173s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_a.10.c__p25674_terminationG_0.smt2                                      |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_a.10.c__p25675_terminationG_0.smt2                                      |   1.508s  |   1.508s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25769_terminationG_0.smt2                               |   0.582s  |   0.582s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01_assume.c__term_unfeasibility_0_0.smt2                              |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25801_terminationG_0.smt2                                       |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25806_terminationG_0.smt2                                       |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25815_terminationG_0.smt2                                       |   0.768s  |   0.768s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   0.494s  |   0.494s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25817_terminationG_0.smt2                                       |   0.753s  |   0.753s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25820_terminationG_0.smt2                                       |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |   5.750s  |   5.750s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25825_terminationG_0.smt2                                       |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25826_terminationG_0.smt2                                       |   0.661s  |   0.661s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25827_terminationG_0.smt2                                       |   1.158s  |   1.158s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25832_terminationG_0.smt2                                       |   1.977s  |   1.977s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25835_terminationG_0.smt2                                       |   1.120s  |   1.120s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25836_terminationG_0.smt2                                       |   1.293s  |   1.293s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |   1.161s  |   1.161s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25843_terminationG_0.smt2                                       |   0.635s  |   0.635s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   0.713s  |   0.713s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   1.081s  |   1.081s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25848_terminationG_0.smt2                                       |   3.429s  |   3.429s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25852_terminationG_0.smt2                                       |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |   0.666s  |   0.666s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25856_terminationG_0.smt2                                       |   2.890s  |   2.890s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25857_terminationG_0.smt2                                       |  59.880s  |  59.880s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25858_terminationG_0.smt2                                       |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25861_terminationG_0.smt2                                       |   2.537s  |   2.537s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25862_terminationG_0.smt2                                       |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       |  59.825s  |  59.825s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25866_terminationG_0.smt2                                       |   2.475s  |   2.475s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       |  59.702s  |  59.702s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25868_terminationG_0.smt2                                       |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25871_terminationG_0.smt2                                       |  33.962s  |  33.962s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25872_terminationG_0.smt2                                       |  59.488s  |  59.488s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25873_terminationG_0.smt2                                       |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25876_terminationG_0.smt2                                       |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25877_terminationG_0.smt2                                       |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25878_terminationG_0.smt2                                       |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25881_terminationG_0.smt2                                       |  55.308s  |  55.308s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25882_terminationG_0.smt2                                       |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25883_terminationG_0.smt2                                       |  59.958s  |  59.958s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   2.750s  |   2.750s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25887_terminationG_0.smt2                                       |  59.917s  |  59.917s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25888_terminationG_0.smt2                                       |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25891_terminationG_0.smt2                                       |   2.606s  |   2.606s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25892_terminationG_0.smt2                                       |  59.879s  |  59.879s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25893_terminationG_0.smt2                                       |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25896_terminationG_0.smt2                                       |   2.550s  |   2.550s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25897_terminationG_0.smt2                                       |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25898_terminationG_0.smt2                                       |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25901_terminationG_0.smt2                                       |   2.572s  |   2.572s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25902_terminationG_0.smt2                                       |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25905_terminationG_0.smt2                                       |  50.834s  |  50.834s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25907_terminationG_0.smt2                                       |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25908_terminationG_0.smt2                                       |  59.879s  |  59.879s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25911_terminationG_0.smt2                                       |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25912_terminationG_0.smt2                                       |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25916_terminationG_0.smt2                                       |   2.779s  |   2.779s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25917_terminationG_0.smt2                                       |  59.786s  |  59.786s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25918_terminationG_0.smt2                                       |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25922_terminationG_0.smt2                                       |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25923_terminationG_0.smt2                                       |  59.892s  |  59.892s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25924_terminationG_0.smt2                                       |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25927_terminationG_0.smt2                                       |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25928_terminationG_0.smt2                                       |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25932_terminationG_0.smt2                                       |  54.269s  |  54.269s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25933_terminationG_0.smt2                                       |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25934_terminationG_0.smt2                                       |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25937_terminationG_0.smt2                                       |  60.032s  |  60.032s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25938_terminationG_0.smt2                                       |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25939_terminationG_0.smt2                                       |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25942_terminationG_0.smt2                                       |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25943_terminationG_0.smt2                                       |  59.843s  |  59.843s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25944_terminationG_0.smt2                                       |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25947_terminationG_0.smt2                                       |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25948_terminationG_0.smt2                                       |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25949_terminationG_0.smt2                                       |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25952_terminationG_0.smt2                                       |   4.389s  |   4.389s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25953_terminationG_0.smt2                                       |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25954_terminationG_0.smt2                                       |  59.901s  |  59.901s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25957_terminationG_0.smt2                                       |  59.872s  |  59.872s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25958_terminationG_0.smt2                                       |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25959_terminationG_0.smt2                                       |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25962_terminationG_0.smt2                                       |   3.275s  |   3.275s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25964_terminationG_0.smt2                                       |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25968_terminationG_0.smt2                                       |   3.294s  |   3.294s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25969_terminationG_0.smt2                                       |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25970_terminationG_0.smt2                                       |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25973_terminationG_0.smt2                                       |   4.439s  |   4.439s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25974_terminationG_0.smt2                                       |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25975_terminationG_0.smt2                                       |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25978_terminationG_0.smt2                                       |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25979_terminationG_0.smt2                                       |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25980_terminationG_0.smt2                                       |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25984_terminationG_0.smt2                                       |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25985_terminationG_0.smt2                                       |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25988_terminationG_0.smt2                                       |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25989_terminationG_0.smt2                                       |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25990_terminationG_0.smt2                                       |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25992_terminationG_0.smt2                                       |  60.030s  |  60.030s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25994_terminationG_0.smt2                                       |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25995_terminationG_0.smt2                                       |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationQ_27_0.smt2                                           |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |  59.904s  |  59.904s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__p26008_terminationG_0.smt2                                      |   0.732s  |   0.732s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__p26009_terminationG_0.smt2                                      |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__p26013_terminationG_0.smt2                                      |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__p26014_terminationG_0.smt2                                      |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__terminationQ_1_0.smt2                                           |   1.960s  |   1.960s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26023_terminationG_0.smt2                                      |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26031_terminationG_0.smt2                                      |   2.084s  |   2.084s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26032_terminationG_0.smt2                                      |  59.822s  |  59.822s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26033_terminationG_0.smt2                                      |  59.904s  |  59.904s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26036_terminationG_0.smt2                                      |   1.651s  |   1.651s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26037_terminationG_0.smt2                                      |  57.105s  |  57.105s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26038_terminationG_0.smt2                                      |  59.912s  |  59.912s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26041_terminationG_0.smt2                                      |   1.876s  |   1.876s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26042_terminationG_0.smt2                                      |  59.927s  |  59.927s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26043_terminationG_0.smt2                                      |  59.908s  |  59.908s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   2.814s  |   2.814s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26047_terminationG_0.smt2                                      |  59.866s  |  59.866s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26048_terminationG_0.smt2                                      |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__terminationQ_3_0.smt2                                           |   2.806s  |   2.806s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26532_terminationG_0.smt2                       |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26535_terminationG_0.smt2                       |   1.167s  |   1.167s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26536_terminationG_0.smt2                       |  59.920s  |  59.920s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26537_terminationG_0.smt2                       |  59.921s  |  59.921s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26540_terminationG_0.smt2                       |   1.108s  |   1.108s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26541_terminationG_0.smt2                       |  20.522s  |  20.522s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26542_terminationG_0.smt2                       |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26545_terminationG_0.smt2                       |   1.320s  |   1.320s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26546_terminationG_0.smt2                       |  45.939s  |  45.939s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26550_terminationG_0.smt2                       |   3.080s  |   3.080s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26551_terminationG_0.smt2                       |  36.413s  |  36.413s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26552_terminationG_0.smt2                       |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   2.565s  |   2.565s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26556_terminationG_0.smt2                       |  30.763s  |  30.763s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26568_edge_closing_0.smt2                       |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26581_terminationG_0.smt2                     |   2.616s  |   2.616s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v2_false-termination.c__p26608_terminationG_0.smt2                  |   2.090s  |   2.090s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v2_false-termination.c__p26609_terminationG_0.smt2                  |   2.888s  |   2.888s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v2_false-termination.c__p26620_edge_closing_0.smt2                  |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v3_false-termination.c__p26641_terminationG_0.smt2                  |   2.168s  |   2.168s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v3_false-termination.c__p26642_terminationG_0.smt2                  |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26677_terminationG_0.smt2                |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   2.236s  |   2.236s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26679_terminationG_0.smt2                |   0.695s  |   0.695s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26689_terminationG_0.smt2                |   2.028s  |   2.028s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26690_terminationG_0.smt2                |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26705_terminationG_0.smt2                  |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26706_terminationG_0.smt2                  |   2.118s  |   2.118s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26707_terminationG_0.smt2                  |  60.033s  |  60.033s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26710_terminationG_0.smt2                  |   0.824s  |   0.824s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26711_terminationG_0.smt2                  |   1.622s  |   1.622s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26712_terminationG_0.smt2                  |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26727_terminationG_0.smt2                   |   1.660s  |   1.660s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26728_terminationG_0.smt2                   |   2.191s  |   2.191s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26729_terminationG_0.smt2                   |   5.195s  |   5.195s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26732_terminationG_0.smt2                   |   1.733s  |   1.733s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26733_terminationG_0.smt2                   |   2.306s  |   2.306s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26734_terminationG_0.smt2                   |   3.340s  |   3.340s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26739_edge_closing_0.smt2                   |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__terminationQ_1_0.smt2                        |   1.587s  |   1.587s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26761_terminationG_0.smt2                |   2.160s  |   2.160s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26768_terminationG_0.smt2                |   2.242s  |   2.242s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26769_terminationG_0.smt2                |   0.690s  |   0.690s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26770_terminationG_0.smt2                |   0.876s  |   0.876s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26775_terminationG_0.smt2                |   2.236s  |   2.236s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26776_terminationG_0.smt2                |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26782_terminationG_0.smt2                |   2.295s  |   2.295s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26783_terminationG_0.smt2                |   0.901s  |   0.901s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26789_terminationG_0.smt2                |   2.679s  |   2.679s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26790_terminationG_0.smt2                |   0.603s  |   0.603s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26797_terminationG_0.smt2                |   2.791s  |   2.791s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26799_terminationG_0.smt2                |   0.797s  |   0.797s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26806_terminationG_0.smt2                |   2.565s  |   2.565s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26807_terminationG_0.smt2                |   6.809s  |   6.809s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26808_terminationG_0.smt2                |   7.395s  |   7.395s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26817_terminationG_0.smt2                |   2.337s  |   2.337s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26818_terminationG_0.smt2                |   7.470s  |   7.470s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26819_terminationG_0.smt2                |   8.922s  |   8.922s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26829_terminationG_0.smt2                |   2.411s  |   2.411s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26830_terminationG_0.smt2                |   0.870s  |   0.870s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26831_terminationG_0.smt2                |   7.239s  |   7.239s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26839_terminationG_0.smt2                |   2.418s  |   2.418s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26840_terminationG_0.smt2                |   9.739s  |   9.739s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26841_terminationG_0.smt2                |  45.722s  |  45.722s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26844_terminationG_0.smt2                |   2.368s  |   2.368s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26845_terminationG_0.smt2                |   1.649s  |   1.649s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26846_terminationG_0.smt2                |   1.999s  |   1.999s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26849_edge_closing_0.smt2                |   1.256s  |   1.256s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26850_edge_closing_0.smt2                |   0.880s  |   0.880s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26853_edge_closing_0.smt2                |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26856_edge_closing_0.smt2                |   0.473s  |   0.473s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26857_edge_closing_0.smt2                |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26858_edge_closing_0.smt2                |   1.073s  |   1.073s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26859_edge_closing_0.smt2                |   0.615s  |   0.615s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26860_edge_closing_0.smt2                |   1.566s  |   1.566s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26863_edge_closing_0.smt2                |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26864_edge_closing_0.smt2                |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26865_edge_closing_0.smt2                |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26866_edge_closing_0.smt2                |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26874_terminationG_0.smt2                  |   1.121s  |   1.121s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26875_terminationG_0.smt2                  |   0.489s  |   0.489s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   2.181s  |   2.181s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26879_terminationG_0.smt2                  |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26880_terminationG_0.smt2                  |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26902_terminationG_0.smt2                   |   0.722s  |   0.722s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26903_terminationG_0.smt2                   |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26904_terminationG_0.smt2                   |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   1.751s  |   1.751s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26908_terminationG_0.smt2                   |  35.352s  |  35.352s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26909_terminationG_0.smt2                   |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26912_terminationG_0.smt2                   |   2.796s  |   2.796s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26913_terminationG_0.smt2                   |  58.335s  |  58.335s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26914_terminationG_0.smt2                   |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26917_terminationG_0.smt2                   |   2.307s  |   2.307s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26918_terminationG_0.smt2                   |  27.940s  |  27.940s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26919_terminationG_0.smt2                   |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26922_terminationG_0.smt2                   |   1.639s  |   1.639s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26923_terminationG_0.smt2                   |  33.759s  |  33.759s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26924_terminationG_0.smt2                   |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26936_edge_closing_0.smt2                   |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26953_terminationG_0.smt2                   |   1.471s  |   1.471s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26954_terminationG_0.smt2                   |   0.566s  |   0.566s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26955_terminationG_0.smt2                   |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26961_terminationG_0.smt2                   |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26962_terminationG_0.smt2                   |   0.893s  |   0.893s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26965_terminationG_0.smt2                   |   1.832s  |   1.832s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26966_terminationG_0.smt2                   |   5.474s  |   5.474s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26967_terminationG_0.smt2                   |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26970_terminationG_0.smt2                   |   1.925s  |   1.925s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26971_terminationG_0.smt2                   |   2.082s  |   2.082s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26972_terminationG_0.smt2                   |   6.783s  |   6.783s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26975_terminationG_0.smt2                   |   1.620s  |   1.620s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26976_terminationG_0.smt2                   |  11.892s  |  11.892s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26977_terminationG_0.smt2                   |   5.373s  |   5.373s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26980_terminationG_0.smt2                   |   1.983s  |   1.983s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |   8.764s  |   8.764s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26982_terminationG_0.smt2                   |   2.246s  |   2.246s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26985_terminationG_0.smt2                   |   2.091s  |   2.091s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26986_terminationG_0.smt2                   |   1.163s  |   1.163s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26987_terminationG_0.smt2                   |   8.530s  |   8.530s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   1.993s  |   1.993s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26991_terminationG_0.smt2                   |   1.065s  |   1.065s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26992_terminationG_0.smt2                   |   1.771s  |   1.771s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26995_terminationG_0.smt2                   |   2.327s  |   2.327s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26996_terminationG_0.smt2                   |  16.112s  |  16.112s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26997_terminationG_0.smt2                   |   6.093s  |   6.093s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27000_terminationG_0.smt2                   |   9.885s  |   9.885s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27001_terminationG_0.smt2                   |   1.328s  |   1.328s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27002_terminationG_0.smt2                   |  15.804s  |  15.804s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27005_terminationG_0.smt2                   |   2.302s  |   2.302s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27006_terminationG_0.smt2                   |   6.357s  |   6.357s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27007_terminationG_0.smt2                   |   1.082s  |   1.082s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27010_terminationG_0.smt2                   |   2.336s  |   2.336s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27011_terminationG_0.smt2                   |  12.692s  |  12.692s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27012_terminationG_0.smt2                   |   8.070s  |   8.070s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27015_terminationG_0.smt2                   |   2.491s  |   2.491s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27016_terminationG_0.smt2                   |   1.001s  |   1.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27017_terminationG_0.smt2                   |   5.567s  |   5.567s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27020_terminationG_0.smt2                   |  11.858s  |  11.858s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |  34.100s  |  34.100s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27022_terminationG_0.smt2                   |   5.989s  |   5.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27025_terminationG_0.smt2                   |   2.541s  |   2.541s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27026_terminationG_0.smt2                   |   1.154s  |   1.154s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27027_terminationG_0.smt2                   |  11.844s  |  11.844s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27030_terminationG_0.smt2                   |   2.858s  |   2.858s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27031_terminationG_0.smt2                   |   7.794s  |   7.794s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27032_terminationG_0.smt2                   |  11.644s  |  11.644s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27038_edge_closing_0.smt2                   |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27039_edge_closing_0.smt2                   |   0.532s  |   0.532s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27040_edge_closing_0.smt2                   |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__terminationQ_13_0.smt2                       |   2.300s  |   2.300s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__terminationS_0_0.smt2                        |  13.603s  |  13.603s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27051_terminationG_0.smt2                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27056_terminationG_0.smt2                    |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27057_terminationG_0.smt2                    |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27061_terminationG_0.smt2                    |   1.030s  |   1.030s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27062_terminationG_0.smt2                    |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27068_terminationG_0.smt2                    |  11.715s  |  11.715s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27069_terminationG_0.smt2                    |   0.906s  |   0.906s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27077_terminationG_0.smt2                    |   1.340s  |   1.340s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27083_terminationG_0.smt2                    |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27084_terminationG_0.smt2                    |  11.436s  |  11.436s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27092_terminationG_0.smt2                    |   5.375s  |   5.375s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27093_terminationG_0.smt2                    |   5.515s  |   5.515s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27097_terminationG_0.smt2                    |   9.450s  |   9.450s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27098_terminationG_0.smt2                    |   2.138s  |   2.138s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27109_terminationG_0.smt2                    |  16.637s  |  16.637s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27110_terminationG_0.smt2                    |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27121_terminationG_0.smt2                    |  12.639s  |  12.639s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27122_terminationG_0.smt2                    |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27123_terminationG_0.smt2                    |   5.857s  |   5.857s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27134_terminationG_0.smt2                    |  17.605s  |  17.605s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27135_terminationG_0.smt2                    |   7.227s  |   7.227s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27136_terminationG_0.smt2                    |  31.156s  |  31.156s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27139_terminationG_0.smt2                    |  14.837s  |  14.837s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27140_terminationG_0.smt2                    |   9.778s  |   9.778s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27141_terminationG_0.smt2                    |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27144_terminationG_0.smt2                    |  22.792s  |  22.792s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27145_terminationG_0.smt2                    |   7.129s  |   7.129s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27146_terminationG_0.smt2                    |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27149_terminationG_0.smt2                    |  20.943s  |  20.943s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27150_terminationG_0.smt2                    |   2.094s  |   2.094s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27151_terminationG_0.smt2                    |  34.598s  |  34.598s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27154_terminationG_0.smt2                    |  29.727s  |  29.727s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27155_terminationG_0.smt2                    |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27156_terminationG_0.smt2                    |  59.918s  |  59.918s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27159_terminationG_0.smt2                    |  33.729s  |  33.729s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27160_terminationG_0.smt2                    |  17.664s  |  17.664s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27161_terminationG_0.smt2                    |  11.162s  |  11.162s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27164_terminationG_0.smt2                    |  39.741s  |  39.741s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27165_terminationG_0.smt2                    |  22.549s  |  22.549s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27166_terminationG_0.smt2                    |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27169_terminationG_0.smt2                    |  33.319s  |  33.319s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27170_terminationG_0.smt2                    |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27171_terminationG_0.smt2                    |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27174_terminationG_0.smt2                    |  32.038s  |  32.038s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27175_terminationG_0.smt2                    |   9.721s  |   9.721s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27176_terminationG_0.smt2                    |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27179_terminationG_0.smt2                    |  36.274s  |  36.274s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27180_terminationG_0.smt2                    |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27181_terminationG_0.smt2                    |  23.402s  |  23.402s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27184_terminationG_0.smt2                    |  38.020s  |  38.020s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27185_terminationG_0.smt2                    |  38.580s  |  38.580s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27186_terminationG_0.smt2                    |  59.915s  |  59.915s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27189_terminationG_0.smt2                    |  39.371s  |  39.371s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27190_terminationG_0.smt2                    |  23.799s  |  23.799s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27191_terminationG_0.smt2                    |  59.876s  |  59.876s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27194_terminationG_0.smt2                    |  48.432s  |  48.432s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27195_terminationG_0.smt2                    |  59.917s  |  59.917s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27196_terminationG_0.smt2                    |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27199_terminationG_0.smt2                    |  30.803s  |  30.803s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27200_terminationG_0.smt2                    |  46.876s  |  46.876s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27201_terminationG_0.smt2                    |  59.877s  |  59.877s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27205_terminationG_0.smt2                    |  59.097s  |  59.097s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27206_terminationG_0.smt2                    |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27207_terminationG_0.smt2                    |  59.805s  |  59.805s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27210_terminationG_0.smt2                    |  32.421s  |  32.421s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27211_terminationG_0.smt2                    |   2.824s  |   2.824s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27212_terminationG_0.smt2                    |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27215_terminationG_0.smt2                    |  34.056s  |  34.056s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27216_terminationG_0.smt2                    |   1.879s  |   1.879s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27217_terminationG_0.smt2                    |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |  46.774s  |  46.774s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27221_terminationG_0.smt2                    |  20.323s  |  20.323s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27222_terminationG_0.smt2                    |  37.666s  |  37.666s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27225_terminationG_0.smt2                    |  37.230s  |  37.230s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |  11.874s  |  11.874s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27227_terminationG_0.smt2                    |  14.058s  |  14.058s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27230_terminationG_0.smt2                    |  28.546s  |  28.546s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27231_terminationG_0.smt2                    |  15.176s  |  15.176s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27232_terminationG_0.smt2                    |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27234_edge_closing_0.smt2                    |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27235_edge_closing_0.smt2                    |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27236_edge_closing_0.smt2                    |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27238_edge_closing_0.smt2                    |   2.169s  |   2.169s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27239_edge_closing_0.smt2                    |   1.476s  |   1.476s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27240_edge_closing_0.smt2                    |   1.563s  |   1.563s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27242_edge_closing_0.smt2                    |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__terminationQ_18_0.smt2                        |   1.196s  |   1.196s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__terminationQ_19_0.smt2                        |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__terminationS_0_0.smt2                         |   3.484s  |   3.484s  |   0.000s  | 0.0%|
|Ton_Chanh_15__McCarthy91_Iteration_true-termination.c__term_unfeasibility_0_0.smt2          |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27262_terminationG_0.smt2                        |   0.753s  |   0.753s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27263_terminationG_0.smt2                        |  15.915s  |  15.915s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27267_terminationG_0.smt2                        |   1.119s  |   1.119s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27268_terminationG_0.smt2                        |  32.448s  |  32.448s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27272_terminationG_0.smt2                        |   2.285s  |   2.285s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27273_terminationG_0.smt2                        |  38.048s  |  38.048s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27274_terminationG_0.smt2                        |  59.788s  |  59.788s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27277_terminationG_0.smt2                        |   2.523s  |   2.523s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27278_terminationG_0.smt2                        |  37.438s  |  37.438s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27279_terminationG_0.smt2                        |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27282_terminationG_0.smt2                        |   2.167s  |   2.167s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27283_terminationG_0.smt2                        |  59.856s  |  59.856s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27284_terminationG_0.smt2                        |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27301_terminationG_0.smt2                |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27304_terminationG_0.smt2                |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27305_terminationG_0.smt2                |  59.876s  |  59.876s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27306_terminationG_0.smt2                |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27309_terminationG_0.smt2                |   2.663s  |   2.663s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27310_terminationG_0.smt2                |  60.035s  |  60.035s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27311_terminationG_0.smt2                |  59.899s  |  59.899s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27314_terminationG_0.smt2                |   2.748s  |   2.748s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27315_terminationG_0.smt2                |  60.041s  |  60.041s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27316_terminationG_0.smt2                |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27319_terminationG_0.smt2                |   2.254s  |   2.254s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27320_terminationG_0.smt2                |  59.912s  |  59.912s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27321_terminationG_0.smt2                |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27324_terminationG_0.smt2                |   2.480s  |   2.480s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27325_terminationG_0.smt2                |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27326_terminationG_0.smt2                |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27334_edge_closing_0.smt2                |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27343_terminationG_0.smt2                      |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27347_terminationG_0.smt2                      |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27348_terminationG_0.smt2                      |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27352_terminationG_0.smt2                      |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27353_terminationG_0.smt2                      |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27362_terminationG_0.smt2                  |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27367_terminationG_0.smt2                  |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27370_terminationG_0.smt2                  |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27371_terminationG_0.smt2                  |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27372_terminationG_0.smt2                  |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27375_terminationG_0.smt2                  |   1.791s  |   1.791s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27376_terminationG_0.smt2                  |  59.765s  |  59.765s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27377_terminationG_0.smt2                  |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27380_terminationG_0.smt2                  |   2.721s  |   2.721s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27385_terminationG_0.smt2                  |   2.724s  |   2.724s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27386_terminationG_0.smt2                  |  59.802s  |  59.802s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27387_terminationG_0.smt2                  |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27390_terminationG_0.smt2                  |   2.555s  |   2.555s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27391_terminationG_0.smt2                  |  59.887s  |  59.887s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27392_terminationG_0.smt2                  |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27396_edge_closing_0.smt2                  |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27409_terminationG_0.smt2                  |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27413_terminationG_0.smt2                  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27414_terminationG_0.smt2                  |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27417_terminationG_0.smt2                  |   0.731s  |   0.731s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27418_terminationG_0.smt2                  |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27419_terminationG_0.smt2                  |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27422_terminationG_0.smt2                  |   1.534s  |   1.534s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27423_terminationG_0.smt2                  |  59.866s  |  59.866s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27424_terminationG_0.smt2                  |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27427_terminationG_0.smt2                  |   2.676s  |   2.676s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27428_terminationG_0.smt2                  |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27429_terminationG_0.smt2                  |  59.823s  |  59.823s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27432_terminationG_0.smt2                  |   2.794s  |   2.794s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27433_terminationG_0.smt2                  |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27434_terminationG_0.smt2                  |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27437_terminationG_0.smt2                  |   2.164s  |   2.164s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27438_terminationG_0.smt2                  |  59.930s  |  59.930s  |   0.000s  | 0.0%|
</details>
