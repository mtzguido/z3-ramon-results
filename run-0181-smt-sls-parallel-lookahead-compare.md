Comparing data and data


# SUMMARY
- LHS tests = 1818
- RHS tests = 1818
- LHS success = 1812  (99.66996699669967%)
- RHS success = 1812  (99.66996699669967%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-parallel-lookahead
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: a941f5ae84ff5048a4cb00d09ff700cea40582a8
Z3 branch: master
Z3 options: "-T:60 -v:2 -st smt.sls.enable=true smt.sls.parallel=true model_validate=true sls.arith_use_lookahead=true"
Z3 inputs: inputs/QF_NIA_CInteger
Z3 commit message: reset m_conflict indicator on sls model

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-parallel-lookahead
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: a941f5ae84ff5048a4cb00d09ff700cea40582a8
Z3 branch: master
Z3 options: "-T:60 -v:2 -st smt.sls.enable=true smt.sls.parallel=true model_validate=true sls.arith_use_lookahead=true"
Z3 inputs: inputs/QF_NIA_CInteger
Z3 commit message: reset m_conflict indicator on sls model

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |   9.163s  |   9.163s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |   7.946s  |   7.946s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |  58.678s  |  58.678s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  93.775s  |  93.775s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   4.084s  |   4.084s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |   2.300s  |   2.300s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |  11.278s  |  11.278s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |  81.783s  |  81.783s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |  65.162s  |  65.162s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  80.623s  |  80.623s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   2.628s  |   2.628s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           | 101.136s  | 101.136s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |  13.803s  |  13.803s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |  86.667s  |  86.667s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   1.667s  |   1.667s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |  50.723s  |  50.723s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |   9.163s  |   9.163s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |   7.946s  |   7.946s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |  58.678s  |  58.678s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  93.775s  |  93.775s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   4.084s  |   4.084s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |   2.300s  |   2.300s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |  11.278s  |  11.278s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |  81.783s  |  81.783s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |  65.162s  |  65.162s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  80.623s  |  80.623s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   2.628s  |   2.628s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           | 101.136s  | 101.136s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |  13.803s  |  13.803s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |  86.667s  |  86.667s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   1.667s  |   1.667s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |  50.723s  |  50.723s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |   9.163s  |   9.163s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |   7.946s  |   7.946s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |  58.678s  |  58.678s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  93.775s  |  93.775s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   4.084s  |   4.084s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |   2.300s  |   2.300s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |  11.278s  |  11.278s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |  81.783s  |  81.783s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |  65.162s  |  65.162s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  80.623s  |  80.623s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   2.628s  |   2.628s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           | 101.136s  | 101.136s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |  13.803s  |  13.803s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |  86.667s  |  86.667s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   1.667s  |   1.667s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |  50.723s  |  50.723s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |   9.163s  |   9.163s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |   7.946s  |   7.946s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |  58.678s  |  58.678s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  93.775s  |  93.775s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   4.084s  |   4.084s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |   2.300s  |   2.300s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |  11.278s  |  11.278s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |  81.783s  |  81.783s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |  65.162s  |  65.162s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  80.623s  |  80.623s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   2.628s  |   2.628s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           | 101.136s  | 101.136s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |  13.803s  |  13.803s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |  86.667s  |  86.667s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   1.667s  |   1.667s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |  50.723s  |  50.723s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                     | 109.789s |229.0MiB|
|Stroeder_15__NonTermination1_false-termination.c__p24843_terminationG_0.smt2               | 108.506s |139.0MiB|
|Stroeder_15__svcomp_ex2.c__p25953_terminationG_0.smt2                                      | 107.573s |277.0MiB|
|Stroeder_15__svcomp_ex2.c__p25902_terminationG_0.smt2                                      | 107.553s |249.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21549_terminationG_0.smt2 | 106.581s |177.0MiB|
|Stroeder_15__svcomp_ex2.c__p25970_terminationG_0.smt2                                      | 106.364s |225.0MiB|
|Stroeder_15__svcomp_ex2.c__p25873_terminationG_0.smt2                                      | 105.749s |276.0MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23269_terminationG_0.smt2 | 105.266s |139.0MiB|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20306_terminationG_0.smt2          | 105.086s |221.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21929_terminationG_0.smt2 | 104.608s |133.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21452_terminationG_0.smt2 | 103.821s |128.0MiB|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                          | 102.752s |187.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27180_terminationG_0.smt2                   | 102.297s |244.0MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27039_edge_closing_0.smt2                  | 102.151s |282.0MiB|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2          | 101.136s |152.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21802_terminationG_0.smt2 | 100.862s |202.0MiB|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2               | 100.819s |105.0MiB|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20326_terminationG_0.smt2          | 100.627s |169.0MiB|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20270_terminationG_0.smt2          | 100.592s |128.0MiB|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24091_terminationG_0.smt2     | 100.485s |133.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                     | 109.789s |229.0MiB|
|Stroeder_15__NonTermination1_false-termination.c__p24843_terminationG_0.smt2               | 108.506s |139.0MiB|
|Stroeder_15__svcomp_ex2.c__p25953_terminationG_0.smt2                                      | 107.573s |277.0MiB|
|Stroeder_15__svcomp_ex2.c__p25902_terminationG_0.smt2                                      | 107.553s |249.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21549_terminationG_0.smt2 | 106.581s |177.0MiB|
|Stroeder_15__svcomp_ex2.c__p25970_terminationG_0.smt2                                      | 106.364s |225.0MiB|
|Stroeder_15__svcomp_ex2.c__p25873_terminationG_0.smt2                                      | 105.749s |276.0MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23269_terminationG_0.smt2 | 105.266s |139.0MiB|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20306_terminationG_0.smt2          | 105.086s |221.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21929_terminationG_0.smt2 | 104.608s |133.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21452_terminationG_0.smt2 | 103.821s |128.0MiB|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                          | 102.752s |187.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27180_terminationG_0.smt2                   | 102.297s |244.0MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27039_edge_closing_0.smt2                  | 102.151s |282.0MiB|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2          | 101.136s |152.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21802_terminationG_0.smt2 | 100.862s |202.0MiB|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2               | 100.819s |105.0MiB|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20326_terminationG_0.smt2          | 100.627s |169.0MiB|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20270_terminationG_0.smt2          | 100.592s |128.0MiB|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24091_terminationG_0.smt2     | 100.485s |133.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |81.26MiB|81.26MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |112.0MiB|112.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |74.696MiB|74.696MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |160.0MiB|160.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |115.0MiB|115.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |141.0MiB|141.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |160.0MiB|160.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |300.0MiB|300.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |124.0MiB|124.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |186.0MiB|186.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |136.0MiB|136.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |121.0MiB|121.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |152.0MiB|152.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |118.0MiB|118.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |143.0MiB|143.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |164.0MiB|164.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |126.0MiB|126.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |81.26MiB|81.26MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |112.0MiB|112.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |74.696MiB|74.696MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |160.0MiB|160.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |115.0MiB|115.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |141.0MiB|141.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |160.0MiB|160.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |300.0MiB|300.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |124.0MiB|124.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |186.0MiB|186.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |136.0MiB|136.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |121.0MiB|121.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |152.0MiB|152.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |118.0MiB|118.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |143.0MiB|143.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |164.0MiB|164.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |126.0MiB|126.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |81.26MiB|81.26MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |112.0MiB|112.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |74.696MiB|74.696MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |160.0MiB|160.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |115.0MiB|115.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |141.0MiB|141.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |160.0MiB|160.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |300.0MiB|300.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |124.0MiB|124.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |186.0MiB|186.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |136.0MiB|136.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |121.0MiB|121.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |152.0MiB|152.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |118.0MiB|118.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |143.0MiB|143.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |164.0MiB|164.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |126.0MiB|126.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |81.26MiB|81.26MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |112.0MiB|112.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |74.696MiB|74.696MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |160.0MiB|160.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |115.0MiB|115.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |141.0MiB|141.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |160.0MiB|160.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |300.0MiB|300.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |124.0MiB|124.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |186.0MiB|186.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |136.0MiB|136.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |121.0MiB|121.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |152.0MiB|152.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |118.0MiB|118.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |143.0MiB|143.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |164.0MiB|164.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |126.0MiB|126.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Stroeder_15__DivWithoutMinus.c__p22506_terminationG_0.smt2                                 |  67.724s |611.0MiB|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                             |  17.810s |454.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22029_edge_closing_0.smt2 |  80.605s |409.0MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23442_edge_closing_0.smt2 |  23.278s |394.0MiB|
|Stroeder_15__svcomp_ex2.c__p25827_terminationG_0.smt2                                      |  84.977s |389.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22020_terminationG_0.smt2 |  67.144s |388.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27240_edge_closing_0.smt2                   |  72.140s |351.0MiB|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                      |  81.523s |339.0MiB|
|Stroeder_15__GCD.c__p23180_terminationG_0.smt2                                             |  83.895s |329.0MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27012_terminationG_0.smt2                  |  63.387s |317.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2 |  75.256s |316.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27239_edge_closing_0.smt2                   |  83.551s |313.0MiB|
|Stroeder_15__Lcm.c__p23906_terminationG_0.smt2                                             |  49.482s |312.0MiB|
|Stroeder_15__UpAndDownIneq.c__p26240_edge_closing_0.smt2                                   |   1.180s |312.0MiB|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24242_terminationG_0.smt2          |   1.141s |312.0MiB|
|Stroeder_15__NO_04.c__p24653_safety_0.smt2                                                 |  54.770s |311.0MiB|
|Stroeder_15__LogMult.c__p24156_terminationG_0.smt2                                         |   1.852s |311.0MiB|
|Stroeder_15__UpAndDownIneq.c__p26230_terminationG_0.smt2                                   |   1.154s |311.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21031_terminationG_0.smt2 |   0.949s |311.0MiB|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24099_terminationG_0.smt2     |   1.359s |310.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Stroeder_15__DivWithoutMinus.c__p22506_terminationG_0.smt2                                 |  67.724s |611.0MiB|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                             |  17.810s |454.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22029_edge_closing_0.smt2 |  80.605s |409.0MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23442_edge_closing_0.smt2 |  23.278s |394.0MiB|
|Stroeder_15__svcomp_ex2.c__p25827_terminationG_0.smt2                                      |  84.977s |389.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22020_terminationG_0.smt2 |  67.144s |388.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27240_edge_closing_0.smt2                   |  72.140s |351.0MiB|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                      |  81.523s |339.0MiB|
|Stroeder_15__GCD.c__p23180_terminationG_0.smt2                                             |  83.895s |329.0MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27012_terminationG_0.smt2                  |  63.387s |317.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2 |  75.256s |316.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27239_edge_closing_0.smt2                   |  83.551s |313.0MiB|
|Stroeder_15__Lcm.c__p23906_terminationG_0.smt2                                             |  49.482s |312.0MiB|
|Stroeder_15__UpAndDownIneq.c__p26240_edge_closing_0.smt2                                   |   1.180s |312.0MiB|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24242_terminationG_0.smt2          |   1.141s |312.0MiB|
|Stroeder_15__NO_04.c__p24653_safety_0.smt2                                                 |  54.770s |311.0MiB|
|Stroeder_15__LogMult.c__p24156_terminationG_0.smt2                                         |   1.852s |311.0MiB|
|Stroeder_15__UpAndDownIneq.c__p26230_terminationG_0.smt2                                   |   1.154s |311.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21031_terminationG_0.smt2 |   0.949s |311.0MiB|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24099_terminationG_0.smt2     |   1.359s |310.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |   9.163s  |   9.163s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |   7.946s  |   7.946s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |  58.678s  |  58.678s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  93.775s  |  93.775s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |   4.084s  |   4.084s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |   2.300s  |   2.300s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |  11.278s  |  11.278s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |  81.783s  |  81.783s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |  65.162s  |  65.162s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  80.623s  |  80.623s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   2.628s  |   2.628s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           | 101.136s  | 101.136s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |  13.803s  |  13.803s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |  86.667s  |  86.667s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   1.667s  |   1.667s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |  50.723s  |  50.723s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20255_terminationG_0.smt2           |  68.378s  |  68.378s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20259_terminationG_0.smt2           |  45.913s  |  45.913s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20260_terminationG_0.smt2           |  34.798s  |  34.798s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20269_terminationG_0.smt2           |   5.829s  |   5.829s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20270_terminationG_0.smt2           | 100.592s  | 100.592s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20271_terminationG_0.smt2           |  93.080s  |  93.080s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20279_terminationG_0.smt2           |   9.496s  |   9.496s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20280_terminationG_0.smt2           |  76.619s  |  76.619s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20281_terminationG_0.smt2           |  69.075s  |  69.075s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20288_terminationG_0.smt2           |  10.589s  |  10.589s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20289_terminationG_0.smt2           |  17.056s  |  17.056s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20305_terminationG_0.smt2           |  12.732s  |  12.732s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20306_terminationG_0.smt2           | 105.086s  | 105.086s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20307_terminationG_0.smt2           |  74.292s  |  74.292s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20312_terminationG_0.smt2           |   7.306s  |   7.306s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20313_terminationG_0.smt2           |  46.428s  |  46.428s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20314_terminationG_0.smt2           |  74.023s  |  74.023s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20324_terminationG_0.smt2           |   7.591s  |   7.591s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20325_terminationG_0.smt2           |  73.480s  |  73.480s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20326_terminationG_0.smt2           | 100.627s  | 100.627s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_0_0.smt2                |   1.976s  |   1.976s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_2_0.smt2                |   0.703s  |   0.703s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_3_0.smt2                |   0.685s  |   0.685s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_4_0.smt2                |   1.938s  |   1.938s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-Fig1_true-termination.c__p20413_terminationG_0.smt2  |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-Fig2b_true-termination.c__p20426_terminationG_0.smt2  |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-Fig2b_true-termination.c__terminationS_1_0.smt2  |   1.513s  |   1.513s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-complex_true-termination.c__term_unfeasibility_0_0.smt2  |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-counterex1b_true-termination.c__p20394_terminationG_0.smt2  |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-counterex1b_true-termination.c__p20395_terminationG_0.smt2  |  13.131s  |  13.131s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-counterex1b_true-termination.c__p20396_terminationG_0.smt2  |  18.827s  |  18.827s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-loops_true-termination.c__p20439_terminationG_0.smt2  |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-loops_true-termination.c__p20440_terminationG_0.smt2  |   1.601s  |   1.601s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-loops_true-termination.c__term_unfeasibility_0_0.smt2  |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-nestedLoop_true-termination.c__p20452_terminationG_0.smt2  |   4.718s  |   4.718s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-nestedLoop_true-termination.c__p20453_terminationG_0.smt2  |  10.768s  |  10.768s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-speedFails4_true-termination.c__p20494_terminationG_0.smt2  |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-speedpldi4_true-termination.c__p20516_terminationG_0.smt2  |   1.699s  |   1.699s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20546_terminationG_0.smt2                                        |   1.868s  |   1.868s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20552_terminationG_0.smt2                                        |   0.791s  |   0.791s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20553_terminationG_0.smt2                                        |   2.867s  |   2.867s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20556_edge_closing_0.smt2                                        |   1.911s  |   1.911s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20557_edge_closing_0.smt2                                        |   6.071s  |   6.071s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20618_terminationG_0.smt2                                    |   2.929s  |   2.929s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20619_terminationG_0.smt2                                    |   2.356s  |   2.356s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20626_edge_closing_0.smt2                                    |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20627_edge_closing_0.smt2                                    |   1.859s  |   1.859s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20638_terminationG_0.smt2                                |   1.137s  |   1.137s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20639_terminationG_0.smt2                                |   1.733s  |   1.733s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20650_terminationG_0.smt2                                |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20651_terminationG_0.smt2                                |  81.297s  |  81.297s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20652_terminationG_0.smt2                                |  89.808s  |  89.808s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20655_terminationG_0.smt2                                |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20656_terminationG_0.smt2                                |  85.216s  |  85.216s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20657_terminationG_0.smt2                                |  68.023s  |  68.023s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20661_edge_closing_0.smt2                                |  75.760s  |  75.760s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20662_edge_closing_0.smt2                                |  84.149s  |  84.149s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20668_edge_closing_0.smt2                                |  14.089s  |  14.089s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20669_edge_closing_0.smt2                                |  75.903s  |  75.903s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__terminationQ_1_0.smt2                                     |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |  69.820s  |  69.820s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20688_terminationG_0.smt2                                       |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20689_terminationG_0.smt2                                       |   0.978s  |   0.978s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20690_terminationG_0.smt2                                       |   2.158s  |   2.158s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20693_edge_closing_0.smt2                                       |   2.126s  |   2.126s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20694_edge_closing_0.smt2                                       |  56.090s  |  56.090s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__terminationS_1_0.smt2                                            |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|Stroeder_15__Benghazi_true-termination.c__p20729_terminationG_0.smt2                        |   0.901s  |   0.901s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20762_terminationG_0.smt2  |   0.879s  |   0.879s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20763_terminationG_0.smt2  |  70.204s  |  70.204s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20774_edge_closing_0.smt2  |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20777_edge_closing_0.smt2  |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1_true-termination.c__p20785_terminationG_0.smt2  |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1_true-termination.c__p20786_terminationG_0.smt2  |   1.987s  |   1.987s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-ICALP2005-Fig1_true-termination.c__p20810_terminationG_0.smt2  |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-ICALP2005-Fig1_true-termination.c__p20814_terminationG_0.smt2  |   8.610s  |   8.610s  |   0.000s  | 0.0%|
|Stroeder_15__BrockschmidtCookFuhs-CAV2013-Fig9a_true-termination.c__p20828_terminationG_0.smt2  |   1.216s  |   1.216s  |   0.000s  | 0.0%|
|Stroeder_15__BrockschmidtCookFuhs-CAV2013-Introduction_true-termination.c__p20837_terminationG_0.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20849_terminationG_0.smt2  |   0.873s  |   0.873s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20853_terminationG_0.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20854_terminationG_0.smt2  |  10.110s  |  10.110s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20855_terminationG_0.smt2  |  95.333s  |  95.333s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20858_terminationG_0.smt2  |   0.674s  |   0.674s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20859_terminationG_0.smt2  |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20860_terminationG_0.smt2  |  82.114s  |  82.114s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20863_terminationG_0.smt2  |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20864_terminationG_0.smt2  |   2.562s  |   2.562s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20865_terminationG_0.smt2  |  96.941s  |  96.941s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20868_terminationG_0.smt2  |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20869_terminationG_0.smt2  |   7.847s  |   7.847s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20870_terminationG_0.smt2  |  94.376s  |  94.376s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20873_terminationG_0.smt2  |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20874_terminationG_0.smt2  |   6.562s  |   6.562s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20875_terminationG_0.smt2  |  87.067s  |  87.067s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20888_terminationG_0.smt2  |   1.043s  |   1.043s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20892_terminationG_0.smt2  |   1.820s  |   1.820s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |  15.911s  |  15.911s  |   0.000s  | 0.0%|
|Stroeder_15__ChenCookFuhsNimkarOHearn-TACAS2014-Introduction_false-termination.c__p20918_terminationG_0.smt2  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|Stroeder_15__ChenCookFuhsNimkarOHearn-TACAS2014-Introduction_false-termination.c__p20919_terminationG_0.smt2  |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20939_terminationG_0.smt2  |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20940_terminationG_0.smt2  |   5.225s  |   5.225s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20941_terminationG_0.smt2  |  85.533s  |  85.533s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20944_edge_closing_0.smt2  |  85.276s  |  85.276s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20945_edge_closing_0.smt2  |  73.817s  |  73.817s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.01_true-termination.c__p20984_terminationG_0.smt2  |   0.598s  |   0.598s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.01_true-termination.c__p20989_terminationG_0.smt2  |   2.373s  |   2.373s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21003_terminationG_0.smt2  |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21008_terminationG_0.smt2  |   7.489s  |   7.489s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21011_terminationG_0.smt2  |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21012_terminationG_0.smt2  |  41.460s  |  41.460s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21013_terminationG_0.smt2  |  76.339s  |  76.339s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21016_terminationG_0.smt2  |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21017_terminationG_0.smt2  |  42.906s  |  42.906s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21018_terminationG_0.smt2  |  75.722s  |  75.722s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21021_terminationG_0.smt2  |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21022_terminationG_0.smt2  |  63.880s  |  63.880s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21023_terminationG_0.smt2  |  99.723s  |  99.723s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21026_terminationG_0.smt2  |   0.776s  |   0.776s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21027_terminationG_0.smt2  |  18.545s  |  18.545s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  |  87.130s  |  87.130s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21031_terminationG_0.smt2  |   0.949s  |   0.949s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21032_terminationG_0.smt2  |   7.006s  |   7.006s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21033_terminationG_0.smt2  |  74.519s  |  74.519s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21037_edge_closing_0.smt2  |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21040_edge_closing_0.smt2  |   1.379s  |   1.379s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21044_edge_closing_0.smt2  |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21056_terminationG_0.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21057_terminationG_0.smt2  |  80.776s  |  80.776s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21058_terminationG_0.smt2  |  93.841s  |  93.841s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21061_edge_closing_0.smt2  |  17.837s  |  17.837s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21062_edge_closing_0.smt2  |  12.947s  |  12.947s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21079_terminationG_0.smt2  |   0.599s  |   0.599s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21083_terminationG_0.smt2  |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21084_terminationG_0.smt2  |  53.185s  |  53.185s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21085_terminationG_0.smt2  |  65.895s  |  65.895s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21107_terminationG_0.smt2  |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21108_terminationG_0.smt2  |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21112_terminationG_0.smt2  |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21113_terminationG_0.smt2  |   1.820s  |   1.820s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21116_terminationG_0.smt2  |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21118_terminationG_0.smt2  |   3.133s  |   3.133s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21122_terminationG_0.smt2  |   1.687s  |   1.687s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21123_terminationG_0.smt2  |   9.770s  |   9.770s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21126_terminationG_0.smt2  |   1.911s  |   1.911s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21127_terminationG_0.smt2  |  46.712s  |  46.712s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21128_terminationG_0.smt2  |  71.379s  |  71.379s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21131_terminationG_0.smt2  |   5.242s  |   5.242s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21132_terminationG_0.smt2  |  88.672s  |  88.672s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |  77.235s  |  77.235s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21136_edge_closing_0.smt2  |   1.442s  |   1.442s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21137_edge_closing_0.smt2  |  40.263s  |  40.263s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   8.191s  |   8.191s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21141_edge_closing_0.smt2  |   8.311s  |   8.311s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21142_edge_closing_0.smt2  |   1.223s  |   1.223s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21143_edge_closing_0.smt2  |  80.567s  |  80.567s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21144_edge_closing_0.smt2  |  84.661s  |  84.661s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |  39.775s  |  39.775s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21148_edge_closing_0.smt2  |   1.126s  |   1.126s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21149_edge_closing_0.smt2  |  47.745s  |  47.745s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21150_edge_closing_0.smt2  |  89.675s  |  89.675s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.07_true-termination.c__p21184_terminationG_0.smt2  |   1.376s  |   1.376s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.07_true-termination.c__p21189_terminationG_0.smt2  |   2.362s  |   2.362s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.07_true-termination.c__terminationS_0_0.smt2  |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.08_true-termination.c__p21202_terminationG_0.smt2  |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.08_true-termination.c__p21203_terminationG_0.smt2  |   0.864s  |   0.864s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21242_terminationG_0.smt2  |   2.045s  |   2.045s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21246_terminationG_0.smt2  |   1.219s  |   1.219s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   2.100s  |   2.100s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21258_terminationG_0.smt2  |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21260_terminationG_0.smt2  |   0.532s  |   0.532s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21265_terminationG_0.smt2  |   0.612s  |   0.612s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21280_terminationG_0.smt2  |   9.051s  |   9.051s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21283_terminationG_0.smt2  |   6.052s  |   6.052s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21285_terminationG_0.smt2  |  11.041s  |  11.041s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21288_terminationG_0.smt2  |   1.520s  |   1.520s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21290_terminationG_0.smt2  |   9.398s  |   9.398s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21293_terminationG_0.smt2  |   2.261s  |   2.261s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21294_terminationG_0.smt2  |   1.398s  |   1.398s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21295_terminationG_0.smt2  |   1.645s  |   1.645s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21298_terminationG_0.smt2  |   7.026s  |   7.026s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21299_terminationG_0.smt2  |   4.212s  |   4.212s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21300_terminationG_0.smt2  |  11.134s  |  11.134s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21303_terminationG_0.smt2  |   7.664s  |   7.664s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21304_terminationG_0.smt2  |   8.219s  |   8.219s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21305_terminationG_0.smt2  |  12.497s  |  12.497s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21308_terminationG_0.smt2  |   6.786s  |   6.786s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21309_terminationG_0.smt2  |   3.835s  |   3.835s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21310_terminationG_0.smt2  |   7.008s  |   7.008s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21313_terminationG_0.smt2  |   6.831s  |   6.831s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21314_terminationG_0.smt2  |   2.139s  |   2.139s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21315_terminationG_0.smt2  |   1.385s  |   1.385s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21318_terminationG_0.smt2  |   7.408s  |   7.408s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21319_terminationG_0.smt2  |   6.904s  |   6.904s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21320_terminationG_0.smt2  |  64.670s  |  64.670s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21323_terminationG_0.smt2  |   8.838s  |   8.838s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21324_terminationG_0.smt2  |   7.290s  |   7.290s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21325_terminationG_0.smt2  |   1.602s  |   1.602s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21328_terminationG_0.smt2  |   3.411s  |   3.411s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21329_terminationG_0.smt2  |   7.263s  |   7.263s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21330_terminationG_0.smt2  |   7.106s  |   7.106s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21334_edge_closing_0.smt2  |  23.457s  |  23.457s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21336_edge_closing_0.smt2  |   5.813s  |   5.813s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21337_edge_closing_0.smt2  |  86.804s  |  86.804s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21338_edge_closing_0.smt2  |  89.542s  |  89.542s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21342_edge_closing_0.smt2  |   8.088s  |   8.088s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21343_edge_closing_0.smt2  |  15.093s  |  15.093s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |  25.640s  |  25.640s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21351_edge_closing_0.smt2  |   1.247s  |   1.247s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21352_edge_closing_0.smt2  |  73.511s  |  73.511s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21353_edge_closing_0.smt2  |  74.095s  |  74.095s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__terminationS_0_0.smt2  |   1.417s  |   1.417s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21362_terminationG_0.smt2  |   1.236s  |   1.236s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21367_terminationG_0.smt2  |   0.690s  |   0.690s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21371_terminationG_0.smt2  |   2.142s  |   2.142s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21372_terminationG_0.smt2  |   3.256s  |   3.256s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21376_terminationG_0.smt2  |   5.129s  |   5.129s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21377_terminationG_0.smt2  |   2.584s  |   2.584s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21382_terminationG_0.smt2  |   1.421s  |   1.421s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21385_terminationG_0.smt2  |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21386_terminationG_0.smt2  |  51.135s  |  51.135s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21387_terminationG_0.smt2  |  77.162s  |  77.162s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21390_terminationG_0.smt2  |   0.723s  |   0.723s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21391_terminationG_0.smt2  |   2.252s  |   2.252s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21392_terminationG_0.smt2  |   9.749s  |   9.749s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21395_terminationG_0.smt2  |   1.432s  |   1.432s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  80.901s  |  80.901s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |  70.356s  |  70.356s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21400_edge_closing_0.smt2  |   1.500s  |   1.500s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21401_edge_closing_0.smt2  |  71.638s  |  71.638s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.13_true-termination.c__p21424_terminationG_0.smt2  |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21451_terminationG_0.smt2  |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21452_terminationG_0.smt2  | 103.821s  | 103.821s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21453_terminationG_0.smt2  |  85.436s  |  85.436s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21456_edge_closing_0.smt2  |   0.820s  |   0.820s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21457_edge_closing_0.smt2  |   2.449s  |   2.449s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21463_edge_closing_0.smt2  |   0.555s  |   0.555s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21464_edge_closing_0.smt2  |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21468_edge_closing_0.smt2  |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21469_edge_closing_0.smt2  |  62.547s  |  62.547s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21470_edge_closing_0.smt2  |  71.012s  |  71.012s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__terminationQ_0_0.smt2  |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.15_false-termination.c__p21487_terminationG_0.smt2  |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.15_false-termination.c__p21491_terminationG_0.smt2  |   2.255s  |   2.255s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.15_false-termination.c__p21492_terminationG_0.smt2  |  73.444s  |  73.444s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.16_true-termination.c__p21520_terminationG_0.smt2  |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.16_true-termination.c__p21525_terminationG_0.smt2  |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.16_true-termination.c__p21530_terminationG_0.smt2  |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21539_terminationG_0.smt2  |   0.630s  |   0.630s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21543_terminationG_0.smt2  |   2.319s  |   2.319s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21544_terminationG_0.smt2  |   3.341s  |   3.341s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21547_terminationG_0.smt2  |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21548_terminationG_0.smt2  |  97.129s  |  97.129s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21549_terminationG_0.smt2  | 106.581s  | 106.581s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21552_terminationG_0.smt2  |   1.267s  |   1.267s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21553_terminationG_0.smt2  |  52.763s  |  52.763s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21554_terminationG_0.smt2  |  84.034s  |  84.034s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21562_edge_closing_0.smt2  |   0.834s  |   0.834s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.18_true-termination.c__p21582_terminationG_0.smt2  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.19_true-termination.c__p21598_terminationG_0.smt2  |   0.834s  |   0.834s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.22_true-termination.c__p21645_terminationG_0.smt2  |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.22_true-termination.c__p21649_terminationG_0.smt2  |   1.033s  |   1.033s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.22_true-termination.c__p21650_terminationG_0.smt2  |   2.422s  |   2.422s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21678_terminationG_0.smt2  |   4.226s  |   4.226s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21685_terminationG_0.smt2  |  20.286s  |  20.286s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21690_terminationG_0.smt2  |   1.910s  |   1.910s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21697_terminationG_0.smt2  |  29.355s  |  29.355s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21702_terminationG_0.smt2  |   0.953s  |   0.953s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21709_terminationG_0.smt2  |  67.206s  |  67.206s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21719_terminationG_0.smt2  |   0.998s  |   0.998s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21726_terminationG_0.smt2  |   0.869s  |   0.869s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21727_terminationG_0.smt2  |   7.526s  |   7.526s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21728_terminationG_0.smt2  |   1.457s  |   1.457s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21732_terminationG_0.smt2  |   5.188s  |   5.188s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21733_terminationG_0.smt2  |   6.831s  |   6.831s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21737_terminationG_0.smt2  |   1.822s  |   1.822s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21738_terminationG_0.smt2  |  44.452s  |  44.452s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21748_edge_closing_0.smt2  |   2.462s  |   2.462s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  |  13.659s  |  13.659s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21772_terminationG_0.smt2  |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21774_terminationG_0.smt2  |   2.536s  |   2.536s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21780_terminationG_0.smt2  |   5.881s  |   5.881s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21781_terminationG_0.smt2  |  12.699s  |  12.699s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21788_terminationG_0.smt2  |   1.685s  |   1.685s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21793_terminationG_0.smt2  |   0.562s  |   0.562s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21794_terminationG_0.smt2  |  46.675s  |  46.675s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21795_terminationG_0.smt2  |  32.412s  |  32.412s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21802_terminationG_0.smt2  | 100.862s  | 100.862s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21803_terminationG_0.smt2  |   1.180s  |   1.180s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.04_true-termination.c__p21822_terminationG_0.smt2  |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.04_true-termination.c__p21827_terminationG_0.smt2  |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21868_terminationG_0.smt2  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21870_terminationG_0.smt2  |  28.071s  |  28.071s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21875_terminationG_0.smt2  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21876_terminationG_0.smt2  |  26.752s  |  26.752s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21877_terminationG_0.smt2  |  52.539s  |  52.539s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21882_terminationG_0.smt2  |   0.966s  |   0.966s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21883_terminationG_0.smt2  |  90.010s  |  90.010s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21884_terminationG_0.smt2  |  25.685s  |  25.685s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21890_terminationG_0.smt2  |   1.383s  |   1.383s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21891_terminationG_0.smt2  |  76.223s  |  76.223s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21892_terminationG_0.smt2  |  52.287s  |  52.287s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21895_terminationG_0.smt2  |   1.528s  |   1.528s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21896_terminationG_0.smt2  |  33.617s  |  33.617s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21897_terminationG_0.smt2  |  63.432s  |  63.432s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21905_terminationG_0.smt2  |   1.491s  |   1.491s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21906_terminationG_0.smt2  |  55.680s  |  55.680s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21907_terminationG_0.smt2  |  73.447s  |  73.447s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21910_terminationG_0.smt2  |   2.516s  |   2.516s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21911_terminationG_0.smt2  |  74.627s  |  74.627s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21912_terminationG_0.smt2  |  56.056s  |  56.056s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21922_terminationG_0.smt2  |   1.160s  |   1.160s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21923_terminationG_0.smt2  |  42.328s  |  42.328s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21924_terminationG_0.smt2  |  68.216s  |  68.216s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21927_terminationG_0.smt2  |   2.962s  |   2.962s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21929_terminationG_0.smt2  | 104.608s  | 104.608s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21938_terminationG_0.smt2  |   2.696s  |   2.696s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21939_terminationG_0.smt2  |  67.818s  |  67.818s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21940_terminationG_0.smt2  |  70.545s  |  70.545s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21943_terminationG_0.smt2  |   1.344s  |   1.344s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21944_terminationG_0.smt2  |  93.740s  |  93.740s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21945_terminationG_0.smt2  |  76.520s  |  76.520s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21948_terminationG_0.smt2  |   5.832s  |   5.832s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21949_terminationG_0.smt2  |  74.186s  |  74.186s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |  93.495s  |  93.495s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21953_terminationG_0.smt2  |   3.769s  |   3.769s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21954_terminationG_0.smt2  |  82.723s  |  82.723s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21955_terminationG_0.smt2  |  72.451s  |  72.451s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21957_terminationG_0.smt2  |   2.150s  |   2.150s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21959_terminationG_0.smt2  |  87.208s  |  87.208s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |  81.412s  |  81.412s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21963_terminationG_0.smt2  |   2.157s  |   2.157s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21964_terminationG_0.smt2  |  75.794s  |  75.794s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21965_terminationG_0.smt2  |  97.951s  |  97.951s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21968_terminationG_0.smt2  |   8.536s  |   8.536s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21969_terminationG_0.smt2  |  74.147s  |  74.147s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21970_terminationG_0.smt2  |  84.670s  |  84.670s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21973_terminationG_0.smt2  |   7.380s  |   7.380s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21974_terminationG_0.smt2  |  69.431s  |  69.431s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21975_terminationG_0.smt2  |  77.579s  |  77.579s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21978_terminationG_0.smt2  |   6.151s  |   6.151s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21979_terminationG_0.smt2  |  36.659s  |  36.659s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21980_terminationG_0.smt2  |  79.228s  |  79.228s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21983_terminationG_0.smt2  |  10.151s  |  10.151s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21984_terminationG_0.smt2  |  76.541s  |  76.541s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21985_terminationG_0.smt2  |  92.082s  |  92.082s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21988_terminationG_0.smt2  |   8.723s  |   8.723s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21989_terminationG_0.smt2  |  17.491s  |  17.491s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21990_terminationG_0.smt2  |  73.966s  |  73.966s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21993_terminationG_0.smt2  |  10.328s  |  10.328s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21994_terminationG_0.smt2  |  87.213s  |  87.213s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  78.569s  |  78.569s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21998_terminationG_0.smt2  |   5.975s  |   5.975s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21999_terminationG_0.smt2  |  82.762s  |  82.762s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |  97.955s  |  97.955s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22004_terminationG_0.smt2  |   1.369s  |   1.369s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22005_terminationG_0.smt2  |  26.581s  |  26.581s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22006_terminationG_0.smt2  |  66.903s  |  66.903s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22009_terminationG_0.smt2  |   2.381s  |   2.381s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22010_terminationG_0.smt2  |  35.405s  |  35.405s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22011_terminationG_0.smt2  |  79.753s  |  79.753s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22014_terminationG_0.smt2  |   9.028s  |   9.028s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22015_terminationG_0.smt2  |  61.734s  |  61.734s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22016_terminationG_0.smt2  |  66.392s  |  66.392s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22019_terminationG_0.smt2  |   8.519s  |   8.519s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22020_terminationG_0.smt2  |  67.144s  |  67.144s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22021_terminationG_0.smt2  |  65.502s  |  65.502s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22023_edge_closing_0.smt2  |   3.761s  |   3.761s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22024_edge_closing_0.smt2  |  63.242s  |  63.242s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22025_edge_closing_0.smt2  |  93.693s  |  93.693s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22027_edge_closing_0.smt2  |  56.807s  |  56.807s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |  75.256s  |  75.256s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22029_edge_closing_0.smt2  |  80.605s  |  80.605s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22031_edge_closing_0.smt2  |  70.641s  |  70.641s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  60.977s  |  60.977s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__terminationQ_14_0.smt2  |   1.080s  |   1.080s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__terminationS_0_0.smt2  |   1.888s  |   1.888s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.07_true-termination.c__p22044_terminationG_0.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.07_true-termination.c__p22045_terminationG_0.smt2  |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.08_true-termination.c__p22056_terminationG_0.smt2  |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.08_true-termination.c__p22062_terminationG_0.smt2  |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.08_true-termination.c__p22067_terminationG_0.smt2  |   2.097s  |   2.097s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22103_terminationG_0.smt2  |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22104_terminationG_0.smt2  |   0.618s  |   0.618s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22109_terminationG_0.smt2  |   1.383s  |   1.383s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22113_terminationG_0.smt2  |  10.268s  |  10.268s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22114_terminationG_0.smt2  |   3.956s  |   3.956s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22118_terminationG_0.smt2  |  20.960s  |  20.960s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22119_terminationG_0.smt2  |   7.311s  |   7.311s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22122_terminationG_0.smt2  |   4.724s  |   4.724s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22123_terminationG_0.smt2  |   7.970s  |   7.970s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22124_terminationG_0.smt2  |   5.800s  |   5.800s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22129_terminationG_0.smt2  |  23.868s  |  23.868s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22142_terminationG_0.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22147_terminationG_0.smt2  |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22148_terminationG_0.smt2  |   5.673s  |   5.673s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |  46.191s  |  46.191s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22158_terminationG_0.smt2  |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22160_terminationG_0.smt2  |   2.398s  |   2.398s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22169_terminationG_0.smt2  |   2.431s  |   2.431s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22170_terminationG_0.smt2  |  42.314s  |  42.314s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22177_terminationG_0.smt2                                           |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22178_terminationG_0.smt2                                           |   0.809s  |   0.809s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           |  71.745s  |  71.745s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22182_terminationG_0.smt2                                           |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22183_terminationG_0.smt2                                           |   2.963s  |   2.963s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22184_terminationG_0.smt2                                           |  62.538s  |  62.538s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22189_edge_closing_0.smt2                                           |   1.298s  |   1.298s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__term_unfeasibility_0_0.smt2                                          |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__terminationQ_1_0.smt2                                                |   1.204s  |   1.204s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22199_terminationG_0.smt2                                       |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22200_terminationG_0.smt2                                       |  66.749s  |  66.749s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22201_terminationG_0.smt2                                       |  87.568s  |  87.568s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22206_edge_closing_0.smt2                                       |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__term_unfeasibility_1_0.smt2                                      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__terminationQ_0_0.smt2                                            |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22316_terminationG_0.smt2                                      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22317_terminationG_0.smt2                                      |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22318_terminationG_0.smt2                                      |  23.485s  |  23.485s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22321_terminationG_0.smt2                                      |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22322_terminationG_0.smt2                                      |   1.172s  |   1.172s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22323_terminationG_0.smt2                                      |  56.129s  |  56.129s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv2.c__p22248_safety_0.smt2                                           |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv2.c__p22249_safety_0.smt2                                           |   2.202s  |   2.202s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22271_terminationG_0.smt2                                     |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22289_terminationG_0.smt2                                     |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22290_terminationG_0.smt2                                     |   0.952s  |   0.952s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22291_terminationG_0.smt2                                     |  93.151s  |  93.151s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22294_terminationG_0.smt2                                     |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22295_terminationG_0.smt2                                     |   1.000s  |   1.000s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22296_terminationG_0.smt2                                     |  87.086s  |  87.086s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22332_terminationG_0.smt2                                      |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22336_terminationG_0.smt2                                      |   0.594s  |   0.594s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22337_terminationG_0.smt2                                      |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22340_terminationG_0.smt2                                      |   2.137s  |   2.137s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22341_terminationG_0.smt2                                      |  49.891s  |  49.891s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      |  84.420s  |  84.420s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22345_terminationG_0.smt2                                      |   1.482s  |   1.482s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22346_terminationG_0.smt2                                      |  77.082s  |  77.082s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22347_terminationG_0.smt2                                      |  86.068s  |  86.068s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   1.687s  |   1.687s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22351_terminationG_0.smt2                                      |  63.111s  |  63.111s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      | 109.789s  | 109.789s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22355_terminationG_0.smt2                                      |   4.289s  |   4.289s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22356_terminationG_0.smt2                                      |  68.813s  |  68.813s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22357_terminationG_0.smt2                                      |  85.149s  |  85.149s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22365_edge_closing_0.smt2                                      |  14.942s  |  14.942s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__terminationQ_3_0.smt2                                           |   1.087s  |   1.087s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__terminationS_1_0.smt2                                           |   0.900s  |   0.900s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8a-modified_true-termination.c__p22401_terminationG_0.smt2  |   3.105s  |   3.105s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8b_true-termination.c__p22418_terminationG_0.smt2  |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8b_true-termination.c__p22419_terminationG_0.smt2  |   2.681s  |   2.681s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8b_true-termination.c__p22424_terminationG_0.smt2  |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22435_terminationG_0.smt2                                           |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22436_terminationG_0.smt2                                           |  79.042s  |  79.042s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           | 102.752s  | 102.752s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22440_terminationG_0.smt2                                           |   0.843s  |   0.843s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           |  56.369s  |  56.369s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22442_terminationG_0.smt2                                           |  78.750s  |  78.750s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22445_terminationG_0.smt2                                           |   0.878s  |   0.878s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22446_terminationG_0.smt2                                           |  63.228s  |  63.228s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22447_terminationG_0.smt2                                           |  82.542s  |  82.542s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22450_terminationG_0.smt2                                           |   0.860s  |   0.860s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22451_terminationG_0.smt2                                           |  60.731s  |  60.731s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22452_terminationG_0.smt2                                           |  77.968s  |  77.968s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22455_terminationG_0.smt2                                           |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22456_terminationG_0.smt2                                           |  98.285s  |  98.285s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22457_terminationG_0.smt2                                           |  75.969s  |  75.969s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22460_terminationG_0.smt2                                           |   1.005s  |   1.005s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22461_terminationG_0.smt2                                           |  89.373s  |  89.373s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22462_terminationG_0.smt2                                           |  87.056s  |  87.056s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__terminationS_0_0.smt2                                                |   1.080s  |   1.080s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22480_terminationG_0.smt2                                  |   0.557s  |   0.557s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22481_terminationG_0.smt2                                  |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22484_terminationG_0.smt2                                  |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22485_terminationG_0.smt2                                  |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22491_terminationG_0.smt2                                  |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22494_terminationG_0.smt2                                  |   2.840s  |   2.840s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22495_terminationG_0.smt2                                  |  54.432s  |  54.432s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22496_terminationG_0.smt2                                  |  63.303s  |  63.303s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22499_terminationG_0.smt2                                  |   1.546s  |   1.546s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22500_terminationG_0.smt2                                  |  77.289s  |  77.289s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22501_terminationG_0.smt2                                  |  84.645s  |  84.645s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22504_terminationG_0.smt2                                  |   7.437s  |   7.437s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22505_terminationG_0.smt2                                  |  59.876s  |  59.876s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22506_terminationG_0.smt2                                  |  67.724s  |  67.724s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22514_edge_closing_0.smt2                                  |  93.582s  |  93.582s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22516_edge_closing_0.smt2                                  |  13.656s  |  13.656s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22517_edge_closing_0.smt2                                  |  12.771s  |  12.771s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22520_edge_closing_0.smt2                                  |   0.826s  |   0.826s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22522_edge_closing_0.smt2                                  |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22523_edge_closing_0.smt2                                  |   1.104s  |   1.104s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__terminationS_1_0.smt2                                       |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__terminationS_2_0.smt2                                       |   1.275s  |   1.275s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__terminationS_3_0.smt2                                       |   2.095s  |   2.095s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22530_terminationG_0.smt2                                        |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22531_terminationG_0.smt2                                        |   1.496s  |   1.496s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        |  66.498s  |  66.498s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22535_terminationG_0.smt2                                        |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22536_terminationG_0.smt2                                        |   1.362s  |   1.362s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22537_terminationG_0.smt2                                        |  61.437s  |  61.437s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22540_terminationG_0.smt2                                        |   0.620s  |   0.620s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22541_terminationG_0.smt2                                        |   3.189s  |   3.189s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22542_terminationG_0.smt2                                        |  73.517s  |  73.517s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22545_terminationG_0.smt2                                        |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22546_terminationG_0.smt2                                        |   1.654s  |   1.654s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22547_terminationG_0.smt2                                        |  73.618s  |  73.618s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22550_terminationG_0.smt2                                        |   1.069s  |   1.069s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22551_terminationG_0.smt2                                        |   8.214s  |   8.214s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22552_terminationG_0.smt2                                        |  98.502s  |  98.502s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22555_terminationG_0.smt2                                        |   0.825s  |   0.825s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22556_terminationG_0.smt2                                        |   1.579s  |   1.579s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22557_terminationG_0.smt2                                        |  85.173s  |  85.173s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__terminationQ_5_0.smt2                                             |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22575_terminationG_0.smt2                                              |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22594_terminationG_0.smt2                                              |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   2.999s  |   2.999s  |   0.000s  | 0.0%|
|Stroeder_15__Et2.c__p22608_terminationG_0.smt2                                              |   1.026s  |   1.026s  |   0.000s  | 0.0%|
|Stroeder_15__Et2.c__p22609_terminationG_0.smt2                                              |  54.067s  |  54.067s  |   0.000s  | 0.0%|
|Stroeder_15__Et2.c__p22613_edge_closing_0.smt2                                              |   0.425s  |   0.425s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   2.270s  |   2.270s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22640_terminationG_0.smt2                                              |  91.139s  |  91.139s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22641_terminationG_0.smt2                                              |  87.337s  |  87.337s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22653_edge_closing_0.smt2                                              |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22658_edge_closing_0.smt2                                              |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22659_edge_closing_0.smt2                                              |  35.779s  |  35.779s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__terminationS_0_0.smt2                                                   |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22671_terminationG_0.smt2                                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22672_terminationG_0.smt2                                             |   1.182s  |   1.182s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |  70.700s  |  70.700s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22676_terminationG_0.smt2                                             |   0.498s  |   0.498s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22677_terminationG_0.smt2                                             |   1.547s  |   1.547s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22678_terminationG_0.smt2                                             |  65.316s  |  65.316s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22698_terminationG_0.smt2                                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22699_terminationG_0.smt2                                             |   0.936s  |   0.936s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22700_terminationG_0.smt2                                             |  75.734s  |  75.734s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22703_terminationG_0.smt2                                             |   0.525s  |   0.525s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22704_terminationG_0.smt2                                             |   1.029s  |   1.029s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22705_terminationG_0.smt2                                             |  72.016s  |  72.016s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22750_terminationG_0.smt2                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22752_terminationG_0.smt2                                             |   1.918s  |   1.918s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   0.630s  |   0.630s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   2.829s  |   2.829s  |   0.000s  | 0.0%|
|Stroeder_15__Ex06.c__p22785_edge_closing_0.smt2                                             |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22818_terminationG_0.smt2                                             |   1.108s  |   1.108s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |  42.578s  |  42.578s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22820_terminationG_0.smt2                                             |  52.394s  |  52.394s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   2.739s  |   2.739s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22835_terminationG_0.smt2                                        |   2.553s  |   2.553s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22836_terminationG_0.smt2                                        |   2.155s  |   2.155s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22837_terminationG_0.smt2                                        |   4.413s  |   4.413s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22842_terminationG_0.smt2                                        |   0.525s  |   0.525s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22843_terminationG_0.smt2                                        |  92.131s  |  92.131s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22844_terminationG_0.smt2                                        |  81.747s  |  81.747s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22847_terminationG_0.smt2                                        |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22848_terminationG_0.smt2                                        |  88.356s  |  88.356s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22849_terminationG_0.smt2                                        |  76.878s  |  76.878s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   0.562s  |   0.562s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22853_terminationG_0.smt2                                        |  83.011s  |  83.011s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        |  81.718s  |  81.718s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22857_terminationG_0.smt2                                        |   0.718s  |   0.718s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22858_terminationG_0.smt2                                        |  73.117s  |  73.117s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22859_terminationG_0.smt2                                        |  87.087s  |  87.087s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__terminationQ_3_0.smt2                                             |   0.473s  |   0.473s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22868_terminationG_0.smt2                                        |   9.438s  |   9.438s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22873_terminationG_0.smt2                                        |   0.967s  |   0.967s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22879_terminationG_0.smt2                                        |   1.999s  |   1.999s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22880_terminationG_0.smt2                                        |  68.234s  |  68.234s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22883_terminationG_0.smt2                                        |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22884_terminationG_0.smt2                                        |  62.828s  |  62.828s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22885_terminationG_0.smt2                                        |  96.075s  |  96.075s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22888_terminationG_0.smt2                                        |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22889_terminationG_0.smt2                                        |  72.232s  |  72.232s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22890_terminationG_0.smt2                                        |  96.446s  |  96.446s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22893_terminationG_0.smt2                                        |   0.890s  |   0.890s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22895_terminationG_0.smt2                                        |  88.161s  |  88.161s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22896_terminationG_0.smt2                                        |  93.744s  |  93.744s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22899_terminationG_0.smt2                                        |   0.614s  |   0.614s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22900_terminationG_0.smt2                                        |  41.763s  |  41.763s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22901_terminationG_0.smt2                                        |  74.070s  |  74.070s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__terminationQ_3_0.smt2                                             |   0.746s  |   0.746s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p22994_terminationG_0.smt2                                             |   2.123s  |   2.123s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23021_terminationG_0.smt2                                             |  28.850s  |  28.850s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23022_terminationG_0.smt2                                             |  68.759s  |  68.759s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23033_edge_closing_0.smt2                                             |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23038_edge_closing_0.smt2                                             |   3.526s  |   3.526s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23039_edge_closing_0.smt2                                             |  66.019s  |  66.019s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22917_terminationG_0.smt2                                            |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22918_terminationG_0.smt2                                            |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22927_terminationG_0.smt2                                            |   1.581s  |   1.581s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22933_terminationG_0.smt2                                            |   1.445s  |   1.445s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22937_terminationG_0.smt2                                            |  73.070s  |  73.070s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22938_terminationG_0.smt2                                            |  82.261s  |  82.261s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22942_edge_closing_0.smt2                                            |   9.557s  |   9.557s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22953_edge_closing_0.smt2                                            |   0.867s  |   0.867s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22954_edge_closing_0.smt2                                            |  74.829s  |  74.829s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22955_edge_closing_0.smt2                                            |  77.672s  |  77.672s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23156_terminationG_0.smt2                                              |   0.972s  |   0.972s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23157_terminationG_0.smt2                                              |  17.079s  |  17.079s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23167_terminationG_0.smt2                                              |   1.973s  |   1.973s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23168_terminationG_0.smt2                                              |  31.682s  |  31.682s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23171_terminationG_0.smt2                                              |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23172_terminationG_0.smt2                                              |   2.491s  |   2.491s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |  17.810s  |  17.810s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23178_terminationG_0.smt2                                              |   2.794s  |   2.794s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23179_terminationG_0.smt2                                              |  13.929s  |  13.929s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23180_terminationG_0.smt2                                              |  83.895s  |  83.895s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23183_terminationG_0.smt2                                              |   6.204s  |   6.204s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23184_terminationG_0.smt2                                              |   6.680s  |   6.680s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23185_terminationG_0.smt2                                              |  70.125s  |  70.125s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23188_terminationG_0.smt2                                              |   0.812s  |   0.812s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23189_terminationG_0.smt2                                              |  27.260s  |  27.260s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23190_terminationG_0.smt2                                              |  19.908s  |  19.908s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23200_terminationG_0.smt2                                              |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23201_terminationG_0.smt2                                              |  38.652s  |  38.652s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23202_terminationG_0.smt2                                              |  84.748s  |  84.748s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23206_terminationG_0.smt2                                              |  32.367s  |  32.367s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23207_terminationG_0.smt2                                              |  12.219s  |  12.219s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23210_terminationG_0.smt2                                              |   0.590s  |   0.590s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23211_terminationG_0.smt2                                              |  93.358s  |  93.358s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23212_terminationG_0.smt2                                              |  71.676s  |  71.676s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23215_edge_closing_0.smt2                                              |   6.749s  |   6.749s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23216_edge_closing_0.smt2                                              |  15.017s  |  15.017s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23222_edge_closing_0.smt2                                              |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23223_edge_closing_0.smt2                                              |  74.866s  |  74.866s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_0_0.smt2                                                   |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_1_0.smt2                                                   |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   0.566s  |   0.566s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_8_0.smt2                                                   |   0.759s  |   0.759s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23102_terminationG_0.smt2                                             |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23106_terminationG_0.smt2                                             |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23107_terminationG_0.smt2                                             |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23110_terminationG_0.smt2                                             |   1.661s  |   1.661s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23111_terminationG_0.smt2                                             |  74.892s  |  74.892s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23112_terminationG_0.smt2                                             |   5.872s  |   5.872s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23116_terminationG_0.smt2                                             |   0.680s  |   0.680s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23117_terminationG_0.smt2                                             |  37.073s  |  37.073s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23120_terminationG_0.smt2                                             |   0.679s  |   0.679s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23121_terminationG_0.smt2                                             |  80.985s  |  80.985s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23122_terminationG_0.smt2                                             |  85.761s  |  85.761s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23125_edge_closing_0.smt2                                             |   2.019s  |   2.019s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23126_edge_closing_0.smt2                                             |  14.528s  |  14.528s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23132_edge_closing_0.smt2                                             |   1.414s  |   1.414s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23133_edge_closing_0.smt2                                             |   0.530s  |   0.530s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23050_terminationG_0.smt2                                            |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23054_terminationG_0.smt2                                            |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23055_terminationG_0.smt2                                            |   1.145s  |   1.145s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23056_terminationG_0.smt2                                            |  74.571s  |  74.571s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23059_terminationG_0.smt2                                            |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23060_terminationG_0.smt2                                            |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23061_terminationG_0.smt2                                            |  60.143s  |  60.143s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23064_terminationG_0.smt2                                            |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23065_terminationG_0.smt2                                            |   1.404s  |   1.404s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23066_terminationG_0.smt2                                            |  77.933s  |  77.933s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23069_terminationG_0.smt2                                            |   0.966s  |   0.966s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23070_terminationG_0.smt2                                            |   1.986s  |   1.986s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23071_terminationG_0.smt2                                            |  74.322s  |  74.322s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23074_terminationG_0.smt2                                            |   1.121s  |   1.121s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23075_terminationG_0.smt2                                            |   2.064s  |   2.064s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23076_terminationG_0.smt2                                            |  79.756s  |  79.756s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23080_edge_closing_0.smt2                                            |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23084_edge_closing_0.smt2                                            |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|Stroeder_15__Gothenburg_true-termination.c__p23242_terminationG_0.smt2                      |   1.133s  |   1.133s  |   0.000s  | 0.0%|
|Stroeder_15__Gothenburg_true-termination.c__p23243_terminationG_0.smt2                      |  14.771s  |  14.771s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23267_terminationG_0.smt2  |   1.048s  |   1.048s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23268_terminationG_0.smt2  |  77.762s  |  77.762s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23269_terminationG_0.smt2  | 105.266s  | 105.266s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23272_terminationG_0.smt2  |   1.044s  |   1.044s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23273_terminationG_0.smt2  |  61.711s  |  61.711s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23274_terminationG_0.smt2  |  74.168s  |  74.168s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23277_edge_closing_0.smt2  |   1.388s  |   1.388s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23278_edge_closing_0.smt2  |  60.281s  |  60.281s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23280_edge_closing_0.smt2  |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23281_edge_closing_0.smt2  |   0.842s  |   0.842s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23282_edge_closing_0.smt2  |   2.051s  |   2.051s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23283_edge_closing_0.smt2  |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23284_edge_closing_0.smt2  |   1.151s  |   1.151s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23285_edge_closing_0.smt2  |   0.594s  |   0.594s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23288_edge_closing_0.smt2  |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23291_edge_closing_0.smt2  |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23309_edge_closing_0.smt2  |  69.724s  |  69.724s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23310_edge_closing_0.smt2  |  75.249s  |  75.249s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23319_edge_closing_0.smt2  |   5.721s  |   5.721s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23321_edge_closing_0.smt2  |  66.438s  |  66.438s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23322_edge_closing_0.smt2  |  35.794s  |  35.794s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23328_edge_closing_0.smt2  |   1.184s  |   1.184s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23330_edge_closing_0.smt2  |   0.772s  |   0.772s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23331_edge_closing_0.smt2  |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23333_edge_closing_0.smt2  |  65.128s  |  65.128s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23334_edge_closing_0.smt2  |  62.791s  |  62.791s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23336_edge_closing_0.smt2  |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23339_edge_closing_0.smt2  |   7.265s  |   7.265s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23340_edge_closing_0.smt2  |  72.003s  |  72.003s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23343_edge_closing_0.smt2  |   4.854s  |   4.854s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23345_edge_closing_0.smt2  |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23346_edge_closing_0.smt2  |   1.643s  |   1.643s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23348_edge_closing_0.smt2  |  16.928s  |  16.928s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23349_edge_closing_0.smt2  |  87.976s  |  87.976s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23354_edge_closing_0.smt2  |   0.999s  |   0.999s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23367_edge_closing_0.smt2  |  12.824s  |  12.824s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23403_edge_closing_0.smt2  |  16.821s  |  16.821s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23406_edge_closing_0.smt2  |   1.078s  |   1.078s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23408_edge_closing_0.smt2  |   7.400s  |   7.400s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23409_edge_closing_0.smt2  |  59.223s  |  59.223s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23412_edge_closing_0.smt2  |   7.046s  |   7.046s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23421_edge_closing_0.smt2  |  13.086s  |  13.086s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23429_edge_closing_0.smt2  |   5.951s  |   5.951s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23430_edge_closing_0.smt2  |  14.437s  |  14.437s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23431_edge_closing_0.smt2  |   1.255s  |   1.255s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23432_edge_closing_0.smt2  |   5.361s  |   5.361s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23433_edge_closing_0.smt2  |   6.860s  |   6.860s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23435_edge_closing_0.smt2  |  74.176s  |  74.176s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23436_edge_closing_0.smt2  |  63.302s  |  63.302s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23438_edge_closing_0.smt2  |   1.225s  |   1.225s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23439_edge_closing_0.smt2  |   0.523s  |   0.523s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23441_edge_closing_0.smt2  |  19.701s  |  19.701s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23442_edge_closing_0.smt2  |  23.278s  |  23.278s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23443_edge_closing_0.smt2  |   0.599s  |   0.599s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23444_edge_closing_0.smt2  |  16.040s  |  16.040s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23445_edge_closing_0.smt2  |  12.073s  |  12.073s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23447_edge_closing_0.smt2  |   1.161s  |   1.161s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23448_edge_closing_0.smt2  |   4.150s  |   4.150s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23450_edge_closing_0.smt2  |   0.773s  |   0.773s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23451_edge_closing_0.smt2  |  19.320s  |  19.320s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23459_edge_closing_0.smt2  |   6.727s  |   6.727s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23460_edge_closing_0.smt2  |   0.798s  |   0.798s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23471_edge_closing_0.smt2  |   0.648s  |   0.648s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |   0.886s  |   0.886s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23473_edge_closing_0.smt2  |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23474_edge_closing_0.smt2  |  88.790s  |  88.790s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23475_edge_closing_0.smt2  |  82.562s  |  82.562s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23477_edge_closing_0.smt2  |   7.478s  |   7.478s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23478_edge_closing_0.smt2  |  21.596s  |  21.596s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23480_edge_closing_0.smt2  |   1.132s  |   1.132s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |   1.535s  |   1.535s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23482_edge_closing_0.smt2  |   0.591s  |   0.591s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23483_edge_closing_0.smt2  |  53.280s  |  53.280s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23484_edge_closing_0.smt2  |  83.206s  |  83.206s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23486_edge_closing_0.smt2  |   1.335s  |   1.335s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23487_edge_closing_0.smt2  |   8.679s  |   8.679s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23493_edge_closing_0.smt2  |  11.495s  |  11.495s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23501_edge_closing_0.smt2  |   1.375s  |   1.375s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23502_edge_closing_0.smt2  |   9.937s  |   9.937s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23510_edge_closing_0.smt2  |   4.271s  |   4.271s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23522_edge_closing_0.smt2  |   8.080s  |   8.080s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23523_edge_closing_0.smt2  |  58.864s  |  58.864s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23531_edge_closing_0.smt2  |   6.746s  |   6.746s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23532_edge_closing_0.smt2  |  21.381s  |  21.381s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23543_edge_closing_0.smt2  |   8.481s  |   8.481s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23544_edge_closing_0.smt2  |   0.966s  |   0.966s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23550_edge_closing_0.smt2  |   5.903s  |   5.903s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23551_edge_closing_0.smt2  |  17.137s  |  17.137s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23559_edge_closing_0.smt2  |   4.297s  |   4.297s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23560_edge_closing_0.smt2  |   9.604s  |   9.604s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23565_edge_closing_0.smt2  |  34.650s  |  34.650s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23566_edge_closing_0.smt2  |   6.428s  |   6.428s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23577_edge_closing_0.smt2  |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23602_edge_closing_0.smt2  |   9.267s  |   9.267s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23611_edge_closing_0.smt2  |  14.412s  |  14.412s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23616_edge_closing_0.smt2  |   7.025s  |   7.025s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23617_edge_closing_0.smt2  |  76.976s  |  76.976s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23620_edge_closing_0.smt2  |  13.147s  |  13.147s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23628_edge_closing_0.smt2  |   6.805s  |   6.805s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23629_edge_closing_0.smt2  |   0.894s  |   0.894s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23638_edge_closing_0.smt2  |  11.519s  |  11.519s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23646_edge_closing_0.smt2  |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23647_edge_closing_0.smt2  |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23649_edge_closing_0.smt2  |  63.432s  |  63.432s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23650_edge_closing_0.smt2  |  78.180s  |  78.180s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23653_edge_closing_0.smt2  |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23662_edge_closing_0.smt2  |   1.628s  |   1.628s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23667_edge_closing_0.smt2  |   0.880s  |   0.880s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23673_edge_closing_0.smt2  |   2.377s  |   2.377s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23676_edge_closing_0.smt2  |  79.787s  |  79.787s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23677_edge_closing_0.smt2  |  49.052s  |  49.052s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23679_edge_closing_0.smt2  |   1.592s  |   1.592s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23680_edge_closing_0.smt2  |  10.662s  |  10.662s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23686_edge_closing_0.smt2  |   2.592s  |   2.592s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23692_edge_closing_0.smt2  |   1.627s  |   1.627s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23693_edge_closing_0.smt2  |   9.515s  |   9.515s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23699_edge_closing_0.smt2  |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23701_edge_closing_0.smt2  |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23702_edge_closing_0.smt2  |  19.189s  |  19.189s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23703_edge_closing_0.smt2  |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23704_edge_closing_0.smt2  |   2.016s  |   2.016s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23705_edge_closing_0.smt2  |   2.358s  |   2.358s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23707_edge_closing_0.smt2  |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23708_edge_closing_0.smt2  |   2.934s  |   2.934s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23710_edge_closing_0.smt2  |   1.729s  |   1.729s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23711_edge_closing_0.smt2  |   6.116s  |   6.116s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23713_edge_closing_0.smt2  |   3.193s  |   3.193s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23714_edge_closing_0.smt2  |   2.109s  |   2.109s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23715_edge_closing_0.smt2  |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23716_edge_closing_0.smt2  |   1.840s  |   1.840s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23717_edge_closing_0.smt2  |   1.368s  |   1.368s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23719_edge_closing_0.smt2  |   5.813s  |   5.813s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23720_edge_closing_0.smt2  |  90.770s  |  90.770s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23722_edge_closing_0.smt2  |   4.868s  |   4.868s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23723_edge_closing_0.smt2  |  25.910s  |  25.910s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23731_edge_closing_0.smt2  |  56.416s  |  56.416s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23732_edge_closing_0.smt2  |  63.786s  |  63.786s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23734_edge_closing_0.smt2  |   9.244s  |   9.244s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23735_edge_closing_0.smt2  |  23.525s  |  23.525s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |   1.401s  |   1.401s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23750_edge_closing_0.smt2  |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23751_edge_closing_0.smt2  |   0.910s  |   0.910s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23752_edge_closing_0.smt2  |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23753_edge_closing_0.smt2  |  68.858s  |  68.858s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23754_edge_closing_0.smt2  |  64.021s  |  64.021s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23756_edge_closing_0.smt2  |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   3.343s  |   3.343s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23759_edge_closing_0.smt2  |   0.711s  |   0.711s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23760_edge_closing_0.smt2  |   9.591s  |   9.591s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23765_edge_closing_0.smt2  |   0.911s  |   0.911s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23766_edge_closing_0.smt2  |   0.739s  |   0.739s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23774_edge_closing_0.smt2  |   5.811s  |   5.811s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23775_edge_closing_0.smt2  |   8.725s  |   8.725s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23795_edge_closing_0.smt2  |   7.033s  |   7.033s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23796_edge_closing_0.smt2  |   7.479s  |   7.479s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23853_terminationG_0.smt2  |   0.594s  |   0.594s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23856_terminationG_0.smt2  |   1.348s  |   1.348s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23857_terminationG_0.smt2  |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23858_terminationG_0.smt2  |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23863_terminationG_0.smt2  |   1.362s  |   1.362s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23864_terminationG_0.smt2  |   1.736s  |   1.736s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23872_terminationG_0.smt2  |   7.002s  |   7.002s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23873_terminationG_0.smt2  |  50.331s  |  50.331s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23877_terminationG_0.smt2  |   6.082s  |   6.082s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23878_terminationG_0.smt2  |  15.156s  |  15.156s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23886_terminationG_0.smt2  |   1.646s  |   1.646s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23887_terminationG_0.smt2  |   1.613s  |   1.613s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23893_terminationG_0.smt2  |   3.365s  |   3.365s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23894_terminationG_0.smt2  |   8.022s  |   8.022s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23905_terminationG_0.smt2                                              |   8.278s  |   8.278s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23906_terminationG_0.smt2                                              |  49.482s  |  49.482s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23910_terminationG_0.smt2                                              |   2.323s  |   2.323s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23911_terminationG_0.smt2                                              |   0.801s  |   0.801s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23918_terminationG_0.smt2                                              |  54.605s  |  54.605s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23923_terminationG_0.smt2                                              |  53.225s  |  53.225s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23927_terminationG_0.smt2                                              |  36.431s  |  36.431s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23933_terminationG_0.smt2                                              |  12.273s  |  12.273s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23941_terminationG_0.smt2                                              |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23942_terminationG_0.smt2                                              |  10.572s  |  10.572s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23947_terminationG_0.smt2                                              |   9.651s  |   9.651s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23951_terminationG_0.smt2                                              |  79.806s  |  79.806s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23952_terminationG_0.smt2                                              |  80.030s  |  80.030s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23956_edge_closing_0.smt2                                              |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23960_edge_closing_0.smt2                                              |   9.747s  |   9.747s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-TACAS2014-Ex7_true-termination.c__p23983_terminationG_0.smt2     |   0.524s  |   0.524s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-TACAS2014-Fig1_true-termination.c__p24009_terminationG_0.smt2    |   0.714s  |   0.714s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24028_terminationG_0.smt2      |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24029_terminationG_0.smt2      |   0.528s  |   0.528s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24032_terminationG_0.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24033_terminationG_0.smt2      |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24034_terminationG_0.smt2      |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24038_terminationG_0.smt2      |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24039_terminationG_0.smt2      |   1.109s  |   1.109s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24042_terminationG_0.smt2      |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24043_terminationG_0.smt2      |  94.866s  |  94.866s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24044_terminationG_0.smt2      |  86.565s  |  86.565s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24047_terminationG_0.smt2      |   0.626s  |   0.626s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24048_terminationG_0.smt2      |  84.354s  |  84.354s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24049_terminationG_0.smt2      |  69.194s  |  69.194s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24052_edge_closing_0.smt2      |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24053_edge_closing_0.smt2      |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24057_edge_closing_0.smt2      |   5.653s  |   5.653s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24084_terminationG_0.smt2      |   0.775s  |   0.775s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24085_terminationG_0.smt2      |  68.456s  |  68.456s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24086_terminationG_0.smt2      |  73.840s  |  73.840s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   1.914s  |   1.914s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24090_terminationG_0.smt2      |  88.349s  |  88.349s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24091_terminationG_0.smt2      | 100.485s  | 100.485s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24094_terminationG_0.smt2      |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24095_terminationG_0.smt2      |  59.503s  |  59.503s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24096_terminationG_0.smt2      |  83.109s  |  83.109s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24099_terminationG_0.smt2      |   1.359s  |   1.359s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24100_terminationG_0.smt2      |  87.448s  |  87.448s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24101_terminationG_0.smt2      |  54.751s  |  54.751s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   1.090s  |   1.090s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24121_terminationG_0.smt2        |   0.680s  |   0.680s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24142_terminationG_0.smt2                                          |  55.509s  |  55.509s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24143_terminationG_0.smt2                                          |  70.253s  |  70.253s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24146_terminationG_0.smt2                                          |   0.823s  |   0.823s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24147_terminationG_0.smt2                                          |  72.578s  |  72.578s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24148_terminationG_0.smt2                                          |  58.020s  |  58.020s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24151_terminationG_0.smt2                                          |   0.878s  |   0.878s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24152_terminationG_0.smt2                                          |   1.717s  |   1.717s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24153_terminationG_0.smt2                                          |  60.307s  |  60.307s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24156_terminationG_0.smt2                                          |   1.852s  |   1.852s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24157_terminationG_0.smt2                                          |  78.223s  |  78.223s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24158_terminationG_0.smt2                                          |  73.399s  |  73.399s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__terminationQ_3_0.smt2                                               |   1.170s  |   1.170s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24190_terminationG_0.smt2                                          |   1.886s  |   1.886s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24191_terminationG_0.smt2                                          |  63.624s  |  63.624s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24194_terminationG_0.smt2                                          |   0.495s  |   0.495s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24195_terminationG_0.smt2                                          |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24196_terminationG_0.smt2                                          |  42.711s  |  42.711s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24211_terminationG_0.smt2                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24212_terminationG_0.smt2                                          |   0.759s  |   0.759s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24213_terminationG_0.smt2                                          |   2.425s  |   2.425s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24216_terminationG_0.smt2                                          |   0.764s  |   0.764s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24217_terminationG_0.smt2                                          |   1.646s  |   1.646s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24218_terminationG_0.smt2                                          |   4.160s  |   4.160s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24236_terminationG_0.smt2           |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24237_terminationG_0.smt2           |   1.101s  |   1.101s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24238_terminationG_0.smt2           |   1.659s  |   1.659s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24241_terminationG_0.smt2           |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24242_terminationG_0.smt2           |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   2.223s  |   2.223s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24247_terminationG_0.smt2           |   1.863s  |   1.863s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24248_terminationG_0.smt2           |  81.855s  |  81.855s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24250_edge_closing_0.smt2           |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |  79.553s  |  79.553s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24252_edge_closing_0.smt2           |  95.234s  |  95.234s  |   0.000s  | 0.0%|
|Stroeder_15__McCarthyIterative.c__term_unfeasibility_0_0.smt2                               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|Stroeder_15__MenloPark_true-termination.c__p24273_terminationG_0.smt2                       |   2.576s  |   2.576s  |   0.000s  | 0.0%|
|Stroeder_15__MenloPark_true-termination.c__p24274_terminationG_0.smt2                       |   1.261s  |   1.261s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24281_terminationG_0.smt2                                           |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24282_terminationG_0.smt2                                           |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24283_terminationG_0.smt2                                           |   4.853s  |   4.853s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24288_terminationG_0.smt2                                           |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24289_terminationG_0.smt2                                           |   3.747s  |   3.747s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24290_terminationG_0.smt2                                           |  71.076s  |  71.076s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24301_terminationG_0.smt2                                           |   2.221s  |   2.221s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24306_terminationG_0.smt2                                           |   1.863s  |   1.863s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24309_terminationG_0.smt2                                           |   1.602s  |   1.602s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24310_terminationG_0.smt2                                           |   2.263s  |   2.263s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24311_terminationG_0.smt2                                           |  66.710s  |  66.710s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24314_terminationG_0.smt2                                           |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24315_terminationG_0.smt2                                           |   1.700s  |   1.700s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24316_terminationG_0.smt2                                           |   2.827s  |   2.827s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24319_terminationG_0.smt2                                           |   0.992s  |   0.992s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24320_terminationG_0.smt2                                           |   1.020s  |   1.020s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24321_terminationG_0.smt2                                           |  87.883s  |  87.883s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24324_terminationG_0.smt2                                           |   1.249s  |   1.249s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24325_terminationG_0.smt2                                           |   1.867s  |   1.867s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24326_terminationG_0.smt2                                           |  73.146s  |  73.146s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24329_terminationG_0.smt2                                           |   1.062s  |   1.062s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24330_terminationG_0.smt2                                           |   2.773s  |   2.773s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24331_terminationG_0.smt2                                           |  87.804s  |  87.804s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24334_terminationG_0.smt2                                           |   0.502s  |   0.502s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24335_terminationG_0.smt2                                           |   0.589s  |   0.589s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24336_terminationG_0.smt2                                           |  84.500s  |  84.500s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24339_edge_closing_0.smt2                                           |   0.690s  |   0.690s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24344_edge_closing_0.smt2                                           |   1.215s  |   1.215s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24368_terminationG_0.smt2                                     |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24373_terminationG_0.smt2                                     |   1.884s  |   1.884s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24374_terminationG_0.smt2                                     |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24377_terminationG_0.smt2                                     |   1.247s  |   1.247s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24378_terminationG_0.smt2                                     |  13.826s  |  13.826s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24379_terminationG_0.smt2                                     |  17.734s  |  17.734s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24382_terminationG_0.smt2                                     |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24383_terminationG_0.smt2                                     |   1.873s  |   1.873s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24384_terminationG_0.smt2                                     |  40.114s  |  40.114s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24387_terminationG_0.smt2                                     |   0.932s  |   0.932s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24388_terminationG_0.smt2                                     |   1.491s  |   1.491s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24389_terminationG_0.smt2                                     |  63.433s  |  63.433s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24392_terminationG_0.smt2                                     |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24393_terminationG_0.smt2                                     |  80.801s  |  80.801s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24394_terminationG_0.smt2                                     |  68.985s  |  68.985s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24397_terminationG_0.smt2                                     |   0.997s  |   0.997s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24398_terminationG_0.smt2                                     |  51.350s  |  51.350s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24399_terminationG_0.smt2                                     |  80.799s  |  80.799s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24402_terminationG_0.smt2                                     |   0.649s  |   0.649s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24403_terminationG_0.smt2                                     |  91.172s  |  91.172s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24404_terminationG_0.smt2                                     |  94.406s  |  94.406s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24407_terminationG_0.smt2                                     |   0.741s  |   0.741s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24408_terminationG_0.smt2                                     |   2.086s  |   2.086s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24409_terminationG_0.smt2                                     |  75.473s  |  75.473s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24413_edge_closing_0.smt2                                     |   6.396s  |   6.396s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24415_edge_closing_0.smt2                                     |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24422_edge_closing_0.smt2                                     |   7.245s  |   7.245s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  11.497s  |  11.497s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24426_edge_closing_0.smt2                                     |   0.918s  |   0.918s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24432_edge_closing_0.smt2                                     |   0.764s  |   0.764s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24443_edge_closing_0.smt2                                     |   1.413s  |   1.413s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24446_edge_closing_0.smt2                                     |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24447_edge_closing_0.smt2                                     |   6.436s  |   6.436s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24449_edge_closing_0.smt2                                     |  14.128s  |  14.128s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24450_edge_closing_0.smt2                                     |  62.424s  |  62.424s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__terminationQ_5_0.smt2                                          |   0.916s  |   0.916s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__terminationS_0_0.smt2                                          |   0.494s  |   0.494s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__terminationS_1_0.smt2                                          |   0.498s  |   0.498s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24464_terminationG_0.smt2                                  |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24482_terminationG_0.smt2                                  |   1.180s  |   1.180s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |  75.999s  |  75.999s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24484_terminationG_0.smt2                                  |  89.153s  |  89.153s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationQ_0_0.smt2                                       |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_1_0.smt2                                       |   1.310s  |   1.310s  |   0.000s  | 0.0%|
|Stroeder_15__NO_03.c__p24634_terminationG_0.smt2                                            |  34.314s  |  34.314s  |   0.000s  | 0.0%|
|Stroeder_15__NO_03.c__terminationQ_0_0.smt2                                                 |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24648_safety_0.smt2                                                  |   0.961s  |   0.961s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24649_safety_0.smt2                                                  |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24650_safety_0.smt2                                                  |  78.268s  |  78.268s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24651_safety_0.smt2                                                  |  77.800s  |  77.800s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24653_safety_0.smt2                                                  |  54.770s  |  54.770s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24654_safety_0.smt2                                                  |  67.761s  |  67.761s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__term_unfeasibility_0_0.smt2                                           |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__term_unfeasibility_2_0.smt2                                           |   1.807s  |   1.807s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__term_unfeasibility_4_0.smt2                                           |  59.514s  |  59.514s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24669_terminationG_0.smt2                                            |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   1.294s  |   1.294s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24671_terminationG_0.smt2                                            |  81.433s  |  81.433s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24674_terminationG_0.smt2                                            |   1.422s  |   1.422s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24675_terminationG_0.smt2                                            |   4.504s  |   4.504s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24676_terminationG_0.smt2                                            |  70.530s  |  70.530s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24679_terminationG_0.smt2                                            |   1.052s  |   1.052s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24680_terminationG_0.smt2                                            |   2.619s  |   2.619s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24681_terminationG_0.smt2                                            |  98.153s  |  98.153s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24684_terminationG_0.smt2                                            |   0.925s  |   0.925s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24685_terminationG_0.smt2                                            |   2.023s  |   2.023s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24686_terminationG_0.smt2                                            |  70.584s  |  70.584s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24689_terminationG_0.smt2                                            |   1.155s  |   1.155s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24690_terminationG_0.smt2                                            |   2.183s  |   2.183s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24691_terminationG_0.smt2                                            |  79.711s  |  79.711s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24694_terminationG_0.smt2                                            |   0.616s  |   0.616s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24695_terminationG_0.smt2                                            |   1.891s  |   1.891s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24696_terminationG_0.smt2                                            |  69.111s  |  69.111s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__terminationQ_5_0.smt2                                                 |   0.785s  |   0.785s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24711_terminationG_0.smt2                                            |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  47.231s  |  47.231s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24713_terminationG_0.smt2                                            |  68.664s  |  68.664s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24716_terminationG_0.smt2                                            |   0.419s  |   0.419s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24717_terminationG_0.smt2                                            |  66.091s  |  66.091s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24718_terminationG_0.smt2                                            |  70.864s  |  70.864s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24721_terminationG_0.smt2                                            |   0.792s  |   0.792s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24722_terminationG_0.smt2                                            |  83.428s  |  83.428s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24723_terminationG_0.smt2                                            |  91.167s  |  91.167s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24726_terminationG_0.smt2                                            |   1.640s  |   1.640s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |  22.519s  |  22.519s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24728_terminationG_0.smt2                                            |  64.684s  |  64.684s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24730_terminationG_0.smt2                                            |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24732_terminationG_0.smt2                                            |  51.973s  |  51.973s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24733_terminationG_0.smt2                                            |  64.580s  |  64.580s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24737_edge_closing_0.smt2                                            |   0.615s  |   0.615s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationQ_4_0.smt2                                                 |   1.728s  |   1.728s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   0.770s  |   0.770s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_1_0.smt2                                                 |   0.683s  |   0.683s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24748_terminationG_0.smt2                                            |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |  83.133s  |  83.133s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24750_terminationG_0.smt2                                            |  74.211s  |  74.211s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24752_edge_closing_0.smt2                                            |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__term_unfeasibility_0_0.smt2                                           |   1.116s  |   1.116s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__terminationQ_0_0.smt2                                                 |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__terminationS_0_0.smt2                                                 |   0.519s  |   0.519s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__terminationS_1_0.smt2                                                 |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24780_terminationG_0.smt2                                            |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24781_terminationG_0.smt2                                            |   2.501s  |   2.501s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24782_terminationG_0.smt2                                            |   3.057s  |   3.057s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24785_edge_closing_0.smt2                                            |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24786_edge_closing_0.smt2                                            |   0.831s  |   0.831s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__term_unfeasibility_0_0.smt2                                           |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__terminationS_0_0.smt2                                                 |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24797_terminationG_0.smt2                                            |   0.524s  |   0.524s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24798_terminationG_0.smt2                                            |   1.298s  |   1.298s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24799_terminationG_0.smt2                                            |  86.423s  |  86.423s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24804_edge_closing_0.smt2                                            |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__term_unfeasibility_0_0.smt2                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__terminationQ_0_0.smt2                                                 |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__terminationS_0_0.smt2                                                 |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__terminationS_1_0.smt2                                                 |   0.499s  |   0.499s  |   0.000s  | 0.0%|
|Stroeder_15__NO_24.c__p24815_terminationG_0.smt2                                            |   1.490s  |   1.490s  |   0.000s  | 0.0%|
|Stroeder_15__NO_24.c__p24816_terminationG_0.smt2                                            |  47.999s  |  47.999s  |   0.000s  | 0.0%|
|Stroeder_15__NO_24.c__p24820_edge_closing_0.smt2                                            |   0.832s  |   0.832s  |   0.000s  | 0.0%|
|Stroeder_15__NarrowKonv.c__p24579_edge_closing_0.smt2                                       |   1.335s  |   1.335s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24515_terminationG_0.smt2                                        |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24516_terminationG_0.smt2                                        |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24519_terminationG_0.smt2                                        |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24520_terminationG_0.smt2                                        |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24521_terminationG_0.smt2                                        |   1.700s  |   1.700s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24524_terminationG_0.smt2                                        |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24525_terminationG_0.smt2                                        |   0.826s  |   0.826s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24526_terminationG_0.smt2                                        |   7.185s  |   7.185s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24529_terminationG_0.smt2                                        |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24530_terminationG_0.smt2                                        |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24531_terminationG_0.smt2                                        |   1.704s  |   1.704s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24534_terminationG_0.smt2                                        |  16.302s  |  16.302s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24536_terminationG_0.smt2                                        |  49.994s  |  49.994s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24539_terminationG_0.smt2                                        |  16.948s  |  16.948s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24540_terminationG_0.smt2                                        |  71.982s  |  71.982s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24541_terminationG_0.smt2                                        |  97.477s  |  97.477s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24544_edge_closing_0.smt2                                        |  69.823s  |  69.823s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24545_edge_closing_0.smt2                                        |  84.289s  |  84.289s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24547_edge_closing_0.smt2                                        |   5.899s  |   5.899s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24548_edge_closing_0.smt2                                        |  11.548s  |  11.548s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24549_edge_closing_0.smt2                                        |  17.205s  |  17.205s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24551_edge_closing_0.smt2                                        |  12.712s  |  12.712s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24552_edge_closing_0.smt2                                        |  91.167s  |  91.167s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__term_unfeasibility_2_0.smt2                                       |   0.999s  |   0.999s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationQ_0_0.smt2                                             |   8.441s  |   8.441s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_0_0.smt2                                             |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_1_0.smt2                                             |   0.759s  |   0.759s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_2_0.smt2                                             |   0.893s  |   0.893s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_3_0.smt2                                             |   0.673s  |   0.673s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24837_terminationG_0.smt2                |   2.178s  |   2.178s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24838_terminationG_0.smt2                |  73.876s  |  73.876s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24841_terminationG_0.smt2                |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   2.392s  |   2.392s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24843_terminationG_0.smt2                | 108.506s  | 108.506s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24848_edge_closing_0.smt2                |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24888_terminationG_0.smt2                |   1.184s  |   1.184s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24896_terminationG_0.smt2                |   1.984s  |   1.984s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24897_terminationG_0.smt2                |   2.833s  |   2.833s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24907_terminationG_0.smt2                |   2.592s  |   2.592s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24908_terminationG_0.smt2                |  31.931s  |  31.931s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24918_terminationG_0.smt2                |   2.392s  |   2.392s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24919_terminationG_0.smt2                |  56.046s  |  56.046s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24923_terminationG_0.smt2                |   2.444s  |   2.444s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24924_terminationG_0.smt2                |  44.334s  |  44.334s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |  14.051s  |  14.051s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24932_edge_closing_0.smt2                |   0.781s  |   0.781s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24935_edge_closing_0.smt2                |   4.846s  |   4.846s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24937_edge_closing_0.smt2                |   2.608s  |   2.608s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24938_edge_closing_0.smt2                |   8.972s  |   8.972s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24939_edge_closing_0.smt2                |  66.948s  |  66.948s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                | 100.819s  | 100.819s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24941_edge_closing_0.smt2                |  72.964s  |  72.964s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24949_terminationG_0.smt2                |  40.439s  |  40.439s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24950_terminationG_0.smt2                |  60.951s  |  60.951s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24953_terminationG_0.smt2                |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24954_terminationG_0.smt2                |  83.333s  |  83.333s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                |  57.030s  |  57.030s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24957_terminationG_0.smt2                |   0.868s  |   0.868s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24959_terminationG_0.smt2                |  82.478s  |  82.478s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24960_terminationG_0.smt2                |  66.842s  |  66.842s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24967_terminationG_0.smt2                |   1.008s  |   1.008s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24969_terminationG_0.smt2                |  64.341s  |  64.341s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24970_terminationG_0.smt2                |  70.316s  |  70.316s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24973_terminationG_0.smt2                |   1.148s  |   1.148s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24974_terminationG_0.smt2                |  66.967s  |  66.967s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24975_terminationG_0.smt2                |  69.403s  |  69.403s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24982_edge_closing_0.smt2                |   1.344s  |   1.344s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24983_edge_closing_0.smt2                |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__terminationQ_4_0.smt2                     |   1.409s  |   1.409s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p24995_terminationG_0.smt2          |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p24996_terminationG_0.smt2          |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p24997_terminationG_0.smt2          |  80.577s  |  80.577s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p25000_terminationG_0.smt2          |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p25001_terminationG_0.smt2          |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p25002_terminationG_0.smt2          |  76.306s  |  76.306s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple3_false-termination.c__p25033_terminationG_0.smt2          |   0.711s  |   0.711s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple3_false-termination.c__p25034_terminationG_0.smt2          |  82.469s  |  82.469s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25060_terminationG_0.smt2          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25061_terminationG_0.smt2          |   1.223s  |   1.223s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25062_terminationG_0.smt2          |  76.867s  |  76.867s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25065_terminationG_0.smt2          |   0.586s  |   0.586s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25066_terminationG_0.smt2          |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25067_terminationG_0.smt2          |  71.631s  |  71.631s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25070_terminationG_0.smt2          |   0.903s  |   0.903s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25071_terminationG_0.smt2          |   1.398s  |   1.398s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25072_terminationG_0.smt2          |  68.930s  |  68.930s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25075_terminationG_0.smt2          |   0.656s  |   0.656s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25076_terminationG_0.smt2          |   1.941s  |   1.941s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25077_terminationG_0.smt2          |   5.068s  |   5.068s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25081_edge_closing_0.smt2          |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__terminationQ_3_0.smt2               |   0.650s  |   0.650s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple5_false-termination.c__p25094_terminationG_0.smt2          |   0.562s  |   0.562s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple5_false-termination.c__p25098_terminationG_0.smt2          |   0.565s  |   0.565s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple5_false-termination.c__p25099_terminationG_0.smt2          |   2.596s  |   2.596s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25119_terminationG_0.smt2          |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25120_terminationG_0.smt2          |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          |  86.919s  |  86.919s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25124_terminationG_0.smt2          |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25125_terminationG_0.smt2          |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25126_terminationG_0.smt2          |  60.468s  |  60.468s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25130_edge_closing_0.smt2          |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple7_false-termination.c__p25147_terminationG_0.smt2          |   0.732s  |   0.732s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple7_false-termination.c__p25148_terminationG_0.smt2          |  65.263s  |  65.263s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple7_false-termination.c__p25159_edge_closing_0.smt2          |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25174_terminationG_0.smt2          |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25175_terminationG_0.smt2          |   1.567s  |   1.567s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25176_terminationG_0.smt2          |   6.581s  |   6.581s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25179_terminationG_0.smt2          |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25180_terminationG_0.smt2          |   4.045s  |   4.045s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25181_terminationG_0.smt2          |   2.258s  |   2.258s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25184_edge_closing_0.smt2          |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   0.880s  |   0.880s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25189_edge_closing_0.smt2          |   3.005s  |   3.005s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25202_terminationG_0.smt2          |   0.776s  |   0.776s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25336_terminationG_0.smt2                                         |  59.288s  |  59.288s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25382_terminationG_0.smt2                                         |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25387_terminationG_0.smt2                                         |   2.838s  |   2.838s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25391_terminationG_0.smt2                                         |   0.749s  |   0.749s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25392_terminationG_0.smt2                                         |   2.312s  |   2.312s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig1_true-termination.c__p25400_terminationG_0.smt2  |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25419_terminationG_0.smt2  |   0.530s  |   0.530s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25424_terminationG_0.smt2  |   1.360s  |   1.360s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25425_terminationG_0.smt2  |  84.849s  |  84.849s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25430_terminationG_0.smt2  |  95.713s  |  95.713s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25433_terminationG_0.smt2  |   1.829s  |   1.829s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25434_terminationG_0.smt2  |  16.123s  |  16.123s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25435_terminationG_0.smt2  |  60.237s  |  60.237s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25440_terminationG_0.smt2  |   0.806s  |   0.806s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25441_terminationG_0.smt2  |  55.163s  |  55.163s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25442_terminationG_0.smt2  |  82.497s  |  82.497s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25447_terminationG_0.smt2  |   4.439s  |   4.439s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25448_terminationG_0.smt2  |  81.306s  |  81.306s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25449_terminationG_0.smt2  |  76.777s  |  76.777s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25476_terminationG_0.smt2  |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25479_terminationG_0.smt2  |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25480_terminationG_0.smt2  |   0.876s  |   0.876s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25481_terminationG_0.smt2  |  74.004s  |  74.004s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25484_edge_closing_0.smt2  |   1.333s  |   1.333s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25485_edge_closing_0.smt2  |  66.250s  |  66.250s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25505_terminationG_0.smt2                      |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25506_terminationG_0.smt2                      |   2.034s  |   2.034s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25507_terminationG_0.smt2                      |  96.281s  |  96.281s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |  34.141s  |  34.141s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25519_terminationG_0.smt2                      |  19.438s  |  19.438s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25530_terminationG_0.smt2                      |   1.911s  |   1.911s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25531_terminationG_0.smt2                      |  82.824s  |  82.824s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25532_terminationG_0.smt2                      |  73.348s  |  73.348s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25536_terminationG_0.smt2                      |   5.532s  |   5.532s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25537_terminationG_0.smt2                      |  92.771s  |  92.771s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25541_terminationG_0.smt2                      |  31.009s  |  31.009s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25542_terminationG_0.smt2                      |  26.269s  |  26.269s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25546_terminationG_0.smt2                      |   2.725s  |   2.725s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25547_terminationG_0.smt2                      |  67.162s  |  67.162s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25559_terminationG_0.smt2                      |  79.449s  |  79.449s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25560_terminationG_0.smt2                      |  50.707s  |  50.707s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25566_terminationG_0.smt2                      |  48.740s  |  48.740s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25567_terminationG_0.smt2                      |  76.178s  |  76.178s  |   0.000s  | 0.0%|
|Stroeder_15__Rotation180_false-termination.c__p25579_terminationG_0.smt2                    |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|Stroeder_15__Rotation180_false-termination.c__p25580_terminationG_0.smt2                    |  75.969s  |  75.969s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25604_terminationG_0.smt2                                           |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25608_terminationG_0.smt2                                           |   0.831s  |   0.831s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25609_terminationG_0.smt2                                           |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25619_terminationG_0.smt2                                           |   1.873s  |   1.873s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25622_terminationG_0.smt2                                           |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           |  69.335s  |  69.335s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25624_terminationG_0.smt2                                           |  78.503s  |  78.503s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25629_edge_closing_0.smt2                                           |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25637_edge_closing_0.smt2                                           |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__terminationQ_0_0.smt2                                                |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__terminationS_0_0.smt2                                                |   0.971s  |   0.971s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__terminationS_1_0.smt2                                                |  69.834s  |  69.834s  |   0.000s  | 0.0%|
|Stroeder_15__Swingers.c__p26084_terminationG_0.smt2                                         |  20.420s  |  20.420s  |   0.000s  | 0.0%|
|Stroeder_15__Swingers.c__p26085_terminationG_0.smt2                                         |  88.886s  |  88.886s  |   0.000s  | 0.0%|
|Stroeder_15__Swingers.c__p26089_edge_closing_0.smt2                                         |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-BranchesToLoop_true-termination.c__p26120_terminationG_0.smt2         |   1.639s  |   1.639s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-BranchesToLoop_true-termination.c__p26125_terminationG_0.smt2         |   0.797s  |   0.797s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-MultiBranchesToLoop_true-termination.c__p26134_terminationG_0.smt2    |   0.781s  |   0.781s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-MultiBranchesToLoop_true-termination.c__p26139_terminationG_0.smt2    |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26151_terminationG_0.smt2                                          |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26152_terminationG_0.smt2                                          |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26153_terminationG_0.smt2                                          |  66.126s  |  66.126s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26156_terminationG_0.smt2                                          |   0.462s  |   0.462s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26157_terminationG_0.smt2                                          |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26158_terminationG_0.smt2                                          |  66.945s  |  66.945s  |   0.000s  | 0.0%|
|Stroeder_15__TwoFloatInterv.c__p26170_safety_0.smt2                                         |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|Stroeder_15__TwoFloatInterv.c__p26181_edge_closing_0.smt2                                   |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26197_terminationG_0.smt2                                        |   0.622s  |   0.622s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26198_terminationG_0.smt2                                        |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        |  76.952s  |  76.952s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26203_terminationG_0.smt2                                        |  79.664s  |  79.664s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26206_edge_closing_0.smt2                                        |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26207_edge_closing_0.smt2                                        |   0.454s  |   0.454s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26213_edge_closing_0.smt2                                        |   1.688s  |   1.688s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26214_edge_closing_0.smt2                                        |  90.862s  |  90.862s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__terminationS_3_0.smt2                                             |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26230_terminationG_0.smt2                                    |   1.154s  |   1.154s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26231_terminationG_0.smt2                                    |   1.146s  |   1.146s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26235_terminationG_0.smt2                                    |  85.660s  |  85.660s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26236_terminationG_0.smt2                                    |  94.810s  |  94.810s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26239_edge_closing_0.smt2                                    |   0.590s  |   0.590s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26240_edge_closing_0.smt2                                    |   1.180s  |   1.180s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26246_edge_closing_0.smt2                                    |   1.682s  |   1.682s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26247_edge_closing_0.smt2                                    |   8.218s  |   8.218s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig1_false-termination.c__p26265_safety_0.smt2                   |   1.808s  |   1.808s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig1_false-termination.c__p26266_safety_0.smt2                   |   1.776s  |   1.776s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig2-modified1000_true-termination.c__term_unfeasibility_0_0.smt2  |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig2_true-termination.c__term_unfeasibility_0_0.smt2             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26291_terminationG_0.smt2                       |   1.350s  |   1.350s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26301_terminationG_0.smt2                       |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26335_terminationG_0.smt2                       |  71.293s  |  71.293s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26336_terminationG_0.smt2                       |  71.928s  |  71.928s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__terminationQ_0_0.smt2                            |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__terminationS_0_0.smt2                            |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__terminationS_1_0.smt2                            |   0.695s  |   0.695s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26374_terminationG_0.smt2                                        |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26375_terminationG_0.smt2                                        |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26376_terminationG_0.smt2                                        |  69.779s  |  69.779s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26380_terminationG_0.smt2                                        |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26381_terminationG_0.smt2                                        |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  65.822s  |  65.822s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26407_terminationG_0.smt2                                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26408_terminationG_0.smt2                                    |   1.309s  |   1.309s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26409_terminationG_0.smt2                                    |  71.772s  |  71.772s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26412_terminationG_0.smt2                                    |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26413_terminationG_0.smt2                                    |   1.322s  |   1.322s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26414_terminationG_0.smt2                                    |  72.231s  |  72.231s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26429_terminationG_0.smt2                                      |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26430_terminationG_0.smt2                                      |  79.398s  |  79.398s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26431_terminationG_0.smt2                                      |  61.156s  |  61.156s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26434_terminationG_0.smt2                                      |   0.702s  |   0.702s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26435_terminationG_0.smt2                                      |   3.349s  |   3.349s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26436_terminationG_0.smt2                                      |  67.915s  |  67.915s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__terminationQ_1_0.smt2                                           |   1.186s  |   1.186s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26452_terminationG_0.smt2                                |  65.832s  |  65.832s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26453_terminationG_0.smt2                                |  71.446s  |  71.446s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26456_terminationG_0.smt2                                |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26457_terminationG_0.smt2                                |  73.019s  |  73.019s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                |  63.608s  |  63.608s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__terminationQ_1_0.smt2                                     |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|Stroeder_15__WhilePart.c__p26472_safety_0.smt2                                              |   2.029s  |   2.029s  |   0.000s  | 0.0%|
|Stroeder_15__WhilePart.c__p26473_safety_0.smt2                                              |   2.399s  |   2.399s  |   0.000s  | 0.0%|
|Stroeder_15__WhileSingle.c__p26489_edge_closing_0.smt2                                      |   0.613s  |   0.613s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20348_terminationG_0.smt2                          |   0.618s  |   0.618s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |  84.587s  |  84.587s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   0.898s  |   0.898s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20359_terminationG_0.smt2                          |   8.202s  |   8.202s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20363_terminationG_0.smt2                          |  53.213s  |  53.213s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20364_terminationG_0.smt2                          |  68.617s  |  68.617s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20368_terminationG_0.smt2                          |   0.718s  |   0.718s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20369_terminationG_0.smt2                          |   2.895s  |   2.895s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22217_terminationG_0.smt2                                          |   1.708s  |   1.708s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22218_terminationG_0.smt2                                          |  73.512s  |  73.512s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22219_terminationG_0.smt2                                          |  99.178s  |  99.178s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22228_edge_closing_0.smt2                                          |   4.213s  |   4.213s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22230_edge_closing_0.smt2                                          |  74.227s  |  74.227s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22231_edge_closing_0.smt2                                          |  83.208s  |  83.208s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__term_unfeasibility_1_0.smt2                                         |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__terminationQ_0_0.smt2                                               |   1.639s  |   1.639s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__terminationS_0_0.smt2                                               |   0.881s  |   0.881s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__terminationS_1_0.smt2                                               |   1.002s  |   1.002s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_a.10.c__p25674_terminationG_0.smt2                                      |   0.510s  |   0.510s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_a.10.c__p25675_terminationG_0.smt2                                      |   2.006s  |   2.006s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25769_terminationG_0.smt2                               |   0.762s  |   0.762s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01_assume.c__term_unfeasibility_0_0.smt2                              |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25801_terminationG_0.smt2                                       |   0.585s  |   0.585s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25806_terminationG_0.smt2                                       |   2.177s  |   2.177s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25815_terminationG_0.smt2                                       |   1.247s  |   1.247s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   2.094s  |   2.094s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25817_terminationG_0.smt2                                       |  88.225s  |  88.225s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25820_terminationG_0.smt2                                       |   0.791s  |   0.791s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |  10.907s  |  10.907s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25825_terminationG_0.smt2                                       |   2.284s  |   2.284s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25826_terminationG_0.smt2                                       |   3.603s  |   3.603s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25827_terminationG_0.smt2                                       |  84.977s  |  84.977s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   2.359s  |   2.359s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25832_terminationG_0.smt2                                       |  94.789s  |  94.789s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25835_terminationG_0.smt2                                       |   1.707s  |   1.707s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25836_terminationG_0.smt2                                       |   1.783s  |   1.783s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |   6.044s  |   6.044s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25843_terminationG_0.smt2                                       |  71.476s  |  71.476s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   1.971s  |   1.971s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   2.012s  |   2.012s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25848_terminationG_0.smt2                                       |   3.688s  |   3.688s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25852_terminationG_0.smt2                                       |  88.935s  |  88.935s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  90.829s  |  90.829s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25856_terminationG_0.smt2                                       |   4.629s  |   4.629s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25857_terminationG_0.smt2                                       |  75.652s  |  75.652s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25858_terminationG_0.smt2                                       |  88.283s  |  88.283s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25861_terminationG_0.smt2                                       |   3.151s  |   3.151s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25862_terminationG_0.smt2                                       |  82.740s  |  82.740s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       |  77.607s  |  77.607s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25866_terminationG_0.smt2                                       |   3.281s  |   3.281s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       |  72.946s  |  72.946s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25868_terminationG_0.smt2                                       |  43.926s  |  43.926s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25871_terminationG_0.smt2                                       |   8.090s  |   8.090s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25872_terminationG_0.smt2                                       |  60.880s  |  60.880s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25873_terminationG_0.smt2                                       | 105.749s  | 105.749s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25876_terminationG_0.smt2                                       |   3.715s  |   3.715s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25877_terminationG_0.smt2                                       |  74.993s  |  74.993s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25878_terminationG_0.smt2                                       |  89.617s  |  89.617s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25881_terminationG_0.smt2                                       |   6.070s  |   6.070s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25882_terminationG_0.smt2                                       |  83.186s  |  83.186s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25883_terminationG_0.smt2                                       |  58.520s  |  58.520s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   7.475s  |   7.475s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25887_terminationG_0.smt2                                       |  85.032s  |  85.032s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25888_terminationG_0.smt2                                       |  70.326s  |  70.326s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25891_terminationG_0.smt2                                       |   9.587s  |   9.587s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25892_terminationG_0.smt2                                       |  81.935s  |  81.935s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25893_terminationG_0.smt2                                       |  61.179s  |  61.179s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25896_terminationG_0.smt2                                       |   3.521s  |   3.521s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25897_terminationG_0.smt2                                       |  75.631s  |  75.631s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25898_terminationG_0.smt2                                       |  71.205s  |  71.205s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25901_terminationG_0.smt2                                       |   2.297s  |   2.297s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25902_terminationG_0.smt2                                       | 107.553s  | 107.553s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       |  72.780s  |  72.780s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25905_terminationG_0.smt2                                       |  15.576s  |  15.576s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25907_terminationG_0.smt2                                       |  73.807s  |  73.807s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25908_terminationG_0.smt2                                       |  71.553s  |  71.553s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25911_terminationG_0.smt2                                       |  10.227s  |  10.227s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25912_terminationG_0.smt2                                       |  96.949s  |  96.949s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       |  66.182s  |  66.182s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25916_terminationG_0.smt2                                       |   3.560s  |   3.560s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25917_terminationG_0.smt2                                       |  87.400s  |  87.400s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25918_terminationG_0.smt2                                       |  79.505s  |  79.505s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25922_terminationG_0.smt2                                       |  10.601s  |  10.601s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25923_terminationG_0.smt2                                       |  60.373s  |  60.373s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25924_terminationG_0.smt2                                       |  93.295s  |  93.295s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25928_terminationG_0.smt2                                       |  63.095s  |  63.095s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       |  87.552s  |  87.552s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25932_terminationG_0.smt2                                       |   8.724s  |   8.724s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25933_terminationG_0.smt2                                       |  99.946s  |  99.946s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25934_terminationG_0.smt2                                       |  72.053s  |  72.053s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25937_terminationG_0.smt2                                       |  15.443s  |  15.443s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25938_terminationG_0.smt2                                       | 100.186s  | 100.186s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25939_terminationG_0.smt2                                       |  73.925s  |  73.925s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25942_terminationG_0.smt2                                       |  20.402s  |  20.402s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25943_terminationG_0.smt2                                       |  73.157s  |  73.157s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25944_terminationG_0.smt2                                       |  78.652s  |  78.652s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25947_terminationG_0.smt2                                       |  11.098s  |  11.098s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25948_terminationG_0.smt2                                       |  93.280s  |  93.280s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25949_terminationG_0.smt2                                       |  69.853s  |  69.853s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25952_terminationG_0.smt2                                       |   3.077s  |   3.077s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25953_terminationG_0.smt2                                       | 107.573s  | 107.573s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25954_terminationG_0.smt2                                       |  80.222s  |  80.222s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25957_terminationG_0.smt2                                       |   9.329s  |   9.329s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25958_terminationG_0.smt2                                       |  62.169s  |  62.169s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25959_terminationG_0.smt2                                       |  87.460s  |  87.460s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25962_terminationG_0.smt2                                       |   2.085s  |   2.085s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       |  81.523s  |  81.523s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25964_terminationG_0.smt2                                       |  63.006s  |  63.006s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25968_terminationG_0.smt2                                       |   2.232s  |   2.232s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25969_terminationG_0.smt2                                       |  93.330s  |  93.330s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25970_terminationG_0.smt2                                       | 106.364s  | 106.364s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25973_terminationG_0.smt2                                       |   4.034s  |   4.034s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25975_terminationG_0.smt2                                       |  89.961s  |  89.961s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25978_terminationG_0.smt2                                       |  19.465s  |  19.465s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25979_terminationG_0.smt2                                       |  62.312s  |  62.312s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25980_terminationG_0.smt2                                       |  58.301s  |  58.301s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |  18.010s  |  18.010s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25984_terminationG_0.smt2                                       |  72.731s  |  72.731s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25985_terminationG_0.smt2                                       |  71.319s  |  71.319s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25988_terminationG_0.smt2                                       |  19.799s  |  19.799s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25989_terminationG_0.smt2                                       |  75.410s  |  75.410s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25990_terminationG_0.smt2                                       |  76.617s  |  76.617s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25992_terminationG_0.smt2                                       |  24.247s  |  24.247s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25994_terminationG_0.smt2                                       |  73.969s  |  73.969s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25995_terminationG_0.smt2                                       |  85.685s  |  85.685s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationQ_27_0.smt2                                           |   1.552s  |   1.552s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__p26008_terminationG_0.smt2                                      |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__p26009_terminationG_0.smt2                                      |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__p26013_terminationG_0.smt2                                      |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__p26014_terminationG_0.smt2                                      |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__terminationQ_1_0.smt2                                           |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26023_terminationG_0.smt2                                      |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26031_terminationG_0.smt2                                      |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26032_terminationG_0.smt2                                      |  58.370s  |  58.370s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26033_terminationG_0.smt2                                      |  70.813s  |  70.813s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26036_terminationG_0.smt2                                      |   0.663s  |   0.663s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26037_terminationG_0.smt2                                      |  10.459s  |  10.459s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26038_terminationG_0.smt2                                      |  89.393s  |  89.393s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26041_terminationG_0.smt2                                      |   1.079s  |   1.079s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26042_terminationG_0.smt2                                      |  77.844s  |  77.844s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26043_terminationG_0.smt2                                      | 100.013s  | 100.013s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   1.159s  |   1.159s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26047_terminationG_0.smt2                                      |  67.345s  |  67.345s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26048_terminationG_0.smt2                                      |  84.497s  |  84.497s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__terminationQ_3_0.smt2                                           |   0.925s  |   0.925s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26532_terminationG_0.smt2                       |  10.190s  |  10.190s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26535_terminationG_0.smt2                       |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26536_terminationG_0.smt2                       |   6.599s  |   6.599s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26537_terminationG_0.smt2                       |  67.547s  |  67.547s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26540_terminationG_0.smt2                       |   0.674s  |   0.674s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26541_terminationG_0.smt2                       |   5.650s  |   5.650s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26542_terminationG_0.smt2                       |  55.535s  |  55.535s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26545_terminationG_0.smt2                       |   0.746s  |   0.746s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26546_terminationG_0.smt2                       |  12.645s  |  12.645s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       |  74.549s  |  74.549s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26550_terminationG_0.smt2                       |   1.159s  |   1.159s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26551_terminationG_0.smt2                       |   7.572s  |   7.572s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26552_terminationG_0.smt2                       |  85.447s  |  85.447s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26556_terminationG_0.smt2                       |   8.746s  |   8.746s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       |  93.733s  |  93.733s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26568_edge_closing_0.smt2                       |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26581_terminationG_0.smt2                     |   1.608s  |   1.608s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     |  51.492s  |  51.492s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v2_false-termination.c__p26608_terminationG_0.smt2                  |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v2_false-termination.c__p26609_terminationG_0.smt2                  |   2.351s  |   2.351s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v2_false-termination.c__p26620_edge_closing_0.smt2                  |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v3_false-termination.c__p26641_terminationG_0.smt2                  |   1.733s  |   1.733s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v3_false-termination.c__p26642_terminationG_0.smt2                  |  60.575s  |  60.575s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26677_terminationG_0.smt2                |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   4.287s  |   4.287s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26679_terminationG_0.smt2                |   3.688s  |   3.688s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26689_terminationG_0.smt2                |   1.649s  |   1.649s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26690_terminationG_0.smt2                |   2.919s  |   2.919s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26705_terminationG_0.smt2                  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26706_terminationG_0.smt2                  |   2.441s  |   2.441s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26707_terminationG_0.smt2                  |  79.514s  |  79.514s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26710_terminationG_0.smt2                  |   1.147s  |   1.147s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26711_terminationG_0.smt2                  |   2.660s  |   2.660s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26712_terminationG_0.smt2                  |  83.057s  |  83.057s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26727_terminationG_0.smt2                   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26728_terminationG_0.smt2                   |   1.506s  |   1.506s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26729_terminationG_0.smt2                   |   3.856s  |   3.856s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26732_terminationG_0.smt2                   |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26733_terminationG_0.smt2                   |   1.612s  |   1.612s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26734_terminationG_0.smt2                   |   3.385s  |   3.385s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26739_edge_closing_0.smt2                   |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__terminationQ_1_0.smt2                        |   0.686s  |   0.686s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26761_terminationG_0.smt2                |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26768_terminationG_0.smt2                |   0.846s  |   0.846s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26769_terminationG_0.smt2                |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26770_terminationG_0.smt2                |   0.812s  |   0.812s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26775_terminationG_0.smt2                |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26776_terminationG_0.smt2                |   1.316s  |   1.316s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26782_terminationG_0.smt2                |   1.249s  |   1.249s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26783_terminationG_0.smt2                |   1.228s  |   1.228s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26789_terminationG_0.smt2                |   1.048s  |   1.048s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26790_terminationG_0.smt2                |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26797_terminationG_0.smt2                |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26799_terminationG_0.smt2                |   1.757s  |   1.757s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26806_terminationG_0.smt2                |   0.739s  |   0.739s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26807_terminationG_0.smt2                |   8.749s  |   8.749s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26808_terminationG_0.smt2                |  69.857s  |  69.857s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26817_terminationG_0.smt2                |   1.229s  |   1.229s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26818_terminationG_0.smt2                |  76.251s  |  76.251s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26819_terminationG_0.smt2                |  76.253s  |  76.253s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26829_terminationG_0.smt2                |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26830_terminationG_0.smt2                |   0.634s  |   0.634s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26831_terminationG_0.smt2                |  38.319s  |  38.319s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26839_terminationG_0.smt2                |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26840_terminationG_0.smt2                |   2.510s  |   2.510s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26841_terminationG_0.smt2                |  86.548s  |  86.548s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26844_terminationG_0.smt2                |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26845_terminationG_0.smt2                |  63.204s  |  63.204s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26846_terminationG_0.smt2                |  61.721s  |  61.721s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26849_edge_closing_0.smt2                |   5.707s  |   5.707s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26850_edge_closing_0.smt2                |  88.066s  |  88.066s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26853_edge_closing_0.smt2                |   9.858s  |   9.858s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |  19.628s  |  19.628s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26856_edge_closing_0.smt2                |   9.879s  |   9.879s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26857_edge_closing_0.smt2                |  33.968s  |  33.968s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26858_edge_closing_0.smt2                |   0.918s  |   0.918s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26859_edge_closing_0.smt2                |  69.047s  |  69.047s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26860_edge_closing_0.smt2                |  83.021s  |  83.021s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26863_edge_closing_0.smt2                |  21.865s  |  21.865s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26864_edge_closing_0.smt2                |   0.956s  |   0.956s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26865_edge_closing_0.smt2                |   1.396s  |   1.396s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26866_edge_closing_0.smt2                |  58.474s  |  58.474s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26874_terminationG_0.smt2                  |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26875_terminationG_0.smt2                  |  16.134s  |  16.134s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26879_terminationG_0.smt2                  |   2.515s  |   2.515s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26880_terminationG_0.smt2                  |   1.288s  |   1.288s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26902_terminationG_0.smt2                   |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26903_terminationG_0.smt2                   |   6.934s  |   6.934s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26904_terminationG_0.smt2                   |  88.113s  |  88.113s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   1.131s  |   1.131s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26908_terminationG_0.smt2                   |   7.091s  |   7.091s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26909_terminationG_0.smt2                   |  93.502s  |  93.502s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26912_terminationG_0.smt2                   |   0.898s  |   0.898s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26913_terminationG_0.smt2                   |   4.984s  |   4.984s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26914_terminationG_0.smt2                   |  53.605s  |  53.605s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26917_terminationG_0.smt2                   |   1.360s  |   1.360s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26918_terminationG_0.smt2                   |  36.793s  |  36.793s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26919_terminationG_0.smt2                   |  77.271s  |  77.271s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26922_terminationG_0.smt2                   |   0.907s  |   0.907s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26923_terminationG_0.smt2                   |  21.684s  |  21.684s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26924_terminationG_0.smt2                   |  88.253s  |  88.253s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26936_edge_closing_0.smt2                   |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26953_terminationG_0.smt2                   |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26954_terminationG_0.smt2                   |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26955_terminationG_0.smt2                   |   9.970s  |   9.970s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26961_terminationG_0.smt2                   |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26962_terminationG_0.smt2                   |  15.750s  |  15.750s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26965_terminationG_0.smt2                   |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26966_terminationG_0.smt2                   |  57.496s  |  57.496s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26967_terminationG_0.smt2                   |  14.858s  |  14.858s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26970_terminationG_0.smt2                   |   0.827s  |   0.827s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26971_terminationG_0.smt2                   |   0.691s  |   0.691s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26972_terminationG_0.smt2                   |  63.230s  |  63.230s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26975_terminationG_0.smt2                   |   0.676s  |   0.676s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26976_terminationG_0.smt2                   |   1.848s  |   1.848s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26977_terminationG_0.smt2                   |  81.825s  |  81.825s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26980_terminationG_0.smt2                   |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |  61.560s  |  61.560s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26982_terminationG_0.smt2                   |  78.420s  |  78.420s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26985_terminationG_0.smt2                   |   0.898s  |   0.898s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26986_terminationG_0.smt2                   |   1.731s  |   1.731s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26987_terminationG_0.smt2                   |  50.122s  |  50.122s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26991_terminationG_0.smt2                   |   5.311s  |   5.311s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26992_terminationG_0.smt2                   |  12.376s  |  12.376s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26995_terminationG_0.smt2                   |   0.985s  |   0.985s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26996_terminationG_0.smt2                   |  68.015s  |  68.015s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26997_terminationG_0.smt2                   |  60.990s  |  60.990s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27000_terminationG_0.smt2                   |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27001_terminationG_0.smt2                   |  68.664s  |  68.664s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27002_terminationG_0.smt2                   |  49.977s  |  49.977s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27005_terminationG_0.smt2                   |   1.593s  |   1.593s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27006_terminationG_0.smt2                   |  18.302s  |  18.302s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27007_terminationG_0.smt2                   |  82.419s  |  82.419s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27010_terminationG_0.smt2                   |   0.548s  |   0.548s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27011_terminationG_0.smt2                   |   1.557s  |   1.557s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27012_terminationG_0.smt2                   |  63.387s  |  63.387s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27015_terminationG_0.smt2                   |   0.634s  |   0.634s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27016_terminationG_0.smt2                   |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27017_terminationG_0.smt2                   |  55.121s  |  55.121s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27020_terminationG_0.smt2                   |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |   6.536s  |   6.536s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27022_terminationG_0.smt2                   |  49.538s  |  49.538s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27025_terminationG_0.smt2                   |   0.781s  |   0.781s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27026_terminationG_0.smt2                   |   8.054s  |   8.054s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27027_terminationG_0.smt2                   |  90.429s  |  90.429s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27030_terminationG_0.smt2                   |   0.790s  |   0.790s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27031_terminationG_0.smt2                   |   1.253s  |   1.253s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27032_terminationG_0.smt2                   |  29.276s  |  29.276s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27038_edge_closing_0.smt2                   |   3.721s  |   3.721s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27039_edge_closing_0.smt2                   | 102.151s  | 102.151s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27040_edge_closing_0.smt2                   |  65.312s  |  65.312s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__terminationQ_13_0.smt2                       |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__terminationS_0_0.smt2                        |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27051_terminationG_0.smt2                    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27056_terminationG_0.smt2                    |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27057_terminationG_0.smt2                    |   0.425s  |   0.425s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27061_terminationG_0.smt2                    |   1.387s  |   1.387s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27062_terminationG_0.smt2                    |   5.369s  |   5.369s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27068_terminationG_0.smt2                    |   1.239s  |   1.239s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27069_terminationG_0.smt2                    |   1.768s  |   1.768s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27077_terminationG_0.smt2                    |  65.526s  |  65.526s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27083_terminationG_0.smt2                    |  10.481s  |  10.481s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27084_terminationG_0.smt2                    |  23.149s  |  23.149s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27092_terminationG_0.smt2                    |   6.105s  |   6.105s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27097_terminationG_0.smt2                    |  70.574s  |  70.574s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27098_terminationG_0.smt2                    |  81.978s  |  81.978s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27109_terminationG_0.smt2                    |  20.446s  |  20.446s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27110_terminationG_0.smt2                    |  81.042s  |  81.042s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27121_terminationG_0.smt2                    |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27122_terminationG_0.smt2                    |  56.486s  |  56.486s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27123_terminationG_0.smt2                    |  50.918s  |  50.918s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27134_terminationG_0.smt2                    |   1.996s  |   1.996s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27135_terminationG_0.smt2                    |  71.030s  |  71.030s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27136_terminationG_0.smt2                    |  12.368s  |  12.368s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27139_terminationG_0.smt2                    |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27140_terminationG_0.smt2                    |  60.135s  |  60.135s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27141_terminationG_0.smt2                    |  70.072s  |  70.072s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27144_terminationG_0.smt2                    |   4.745s  |   4.745s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27145_terminationG_0.smt2                    |  67.833s  |  67.833s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27146_terminationG_0.smt2                    |  82.099s  |  82.099s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27149_terminationG_0.smt2                    |   1.667s  |   1.667s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27150_terminationG_0.smt2                    |  80.257s  |  80.257s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27151_terminationG_0.smt2                    |  75.846s  |  75.846s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27154_terminationG_0.smt2                    |   1.074s  |   1.074s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27155_terminationG_0.smt2                    |  64.614s  |  64.614s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27156_terminationG_0.smt2                    |  48.402s  |  48.402s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27159_terminationG_0.smt2                    |   1.265s  |   1.265s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27160_terminationG_0.smt2                    |  47.088s  |  47.088s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27161_terminationG_0.smt2                    |  69.753s  |  69.753s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27164_terminationG_0.smt2                    |   1.190s  |   1.190s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27165_terminationG_0.smt2                    |  26.181s  |  26.181s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27166_terminationG_0.smt2                    |  53.220s  |  53.220s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27169_terminationG_0.smt2                    |   1.497s  |   1.497s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27170_terminationG_0.smt2                    |  16.614s  |  16.614s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27171_terminationG_0.smt2                    |  21.145s  |  21.145s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27174_terminationG_0.smt2                    |   2.874s  |   2.874s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27175_terminationG_0.smt2                    |  26.568s  |  26.568s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27176_terminationG_0.smt2                    |  62.735s  |  62.735s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27179_terminationG_0.smt2                    |   1.085s  |   1.085s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27180_terminationG_0.smt2                    | 102.297s  | 102.297s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27181_terminationG_0.smt2                    |  17.771s  |  17.771s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27184_terminationG_0.smt2                    |   3.751s  |   3.751s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27185_terminationG_0.smt2                    |  26.096s  |  26.096s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27186_terminationG_0.smt2                    |  71.245s  |  71.245s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27189_terminationG_0.smt2                    |   0.722s  |   0.722s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27190_terminationG_0.smt2                    |  83.455s  |  83.455s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27191_terminationG_0.smt2                    |  57.973s  |  57.973s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27194_terminationG_0.smt2                    |   0.683s  |   0.683s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27195_terminationG_0.smt2                    |  79.945s  |  79.945s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27196_terminationG_0.smt2                    |  81.401s  |  81.401s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27199_terminationG_0.smt2                    |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27200_terminationG_0.smt2                    |  32.293s  |  32.293s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27201_terminationG_0.smt2                    |  60.161s  |  60.161s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27205_terminationG_0.smt2                    |   1.157s  |   1.157s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27206_terminationG_0.smt2                    |  28.294s  |  28.294s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27207_terminationG_0.smt2                    |  81.062s  |  81.062s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27210_terminationG_0.smt2                    |   0.852s  |   0.852s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27211_terminationG_0.smt2                    |   2.358s  |   2.358s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27212_terminationG_0.smt2                    |  94.041s  |  94.041s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27215_terminationG_0.smt2                    |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27216_terminationG_0.smt2                    |   9.389s  |   9.389s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27217_terminationG_0.smt2                    |  55.885s  |  55.885s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |   0.992s  |   0.992s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27221_terminationG_0.smt2                    |  46.261s  |  46.261s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27222_terminationG_0.smt2                    |  13.002s  |  13.002s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27225_terminationG_0.smt2                    |   0.886s  |   0.886s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |  30.184s  |  30.184s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27227_terminationG_0.smt2                    |  80.864s  |  80.864s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27230_terminationG_0.smt2                    |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27231_terminationG_0.smt2                    |  58.178s  |  58.178s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27232_terminationG_0.smt2                    |  94.114s  |  94.114s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27234_edge_closing_0.smt2                    |   3.959s  |   3.959s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27235_edge_closing_0.smt2                    |  38.902s  |  38.902s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27236_edge_closing_0.smt2                    |  72.376s  |  72.376s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27238_edge_closing_0.smt2                    |  15.597s  |  15.597s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27239_edge_closing_0.smt2                    |  83.551s  |  83.551s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27240_edge_closing_0.smt2                    |  72.140s  |  72.140s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27242_edge_closing_0.smt2                    |   6.947s  |   6.947s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__terminationQ_18_0.smt2                        |   0.677s  |   0.677s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__terminationQ_19_0.smt2                        |   1.503s  |   1.503s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__terminationS_0_0.smt2                         |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|Ton_Chanh_15__McCarthy91_Iteration_true-termination.c__term_unfeasibility_0_0.smt2          |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27262_terminationG_0.smt2                        |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27263_terminationG_0.smt2                        |   7.395s  |   7.395s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        |  85.527s  |  85.527s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27267_terminationG_0.smt2                        |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27268_terminationG_0.smt2                        |   6.304s  |   6.304s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        |  89.239s  |  89.239s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27272_terminationG_0.smt2                        |   0.702s  |   0.702s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27273_terminationG_0.smt2                        |   7.196s  |   7.196s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27274_terminationG_0.smt2                        |  92.422s  |  92.422s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27277_terminationG_0.smt2                        |   0.848s  |   0.848s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27278_terminationG_0.smt2                        |   6.154s  |   6.154s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27279_terminationG_0.smt2                        |  81.416s  |  81.416s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27282_terminationG_0.smt2                        |   0.962s  |   0.962s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27283_terminationG_0.smt2                        |  14.690s  |  14.690s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27284_terminationG_0.smt2                        |  72.438s  |  72.438s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |  35.573s  |  35.573s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27301_terminationG_0.smt2                |   2.077s  |   2.077s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27304_terminationG_0.smt2                |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27305_terminationG_0.smt2                |  66.321s  |  66.321s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27306_terminationG_0.smt2                |  68.812s  |  68.812s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27309_terminationG_0.smt2                |   1.400s  |   1.400s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27310_terminationG_0.smt2                |  70.707s  |  70.707s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27311_terminationG_0.smt2                |  65.414s  |  65.414s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27314_terminationG_0.smt2                |   1.631s  |   1.631s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27315_terminationG_0.smt2                |  93.881s  |  93.881s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27316_terminationG_0.smt2                |  88.453s  |  88.453s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27319_terminationG_0.smt2                |   0.860s  |   0.860s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27320_terminationG_0.smt2                |  77.247s  |  77.247s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27321_terminationG_0.smt2                |  74.134s  |  74.134s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27324_terminationG_0.smt2                |   0.971s  |   0.971s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27325_terminationG_0.smt2                |  63.777s  |  63.777s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27326_terminationG_0.smt2                |  84.324s  |  84.324s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27334_edge_closing_0.smt2                |   2.745s  |   2.745s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27343_terminationG_0.smt2                      |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27347_terminationG_0.smt2                      |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27348_terminationG_0.smt2                      |   1.249s  |   1.249s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27352_terminationG_0.smt2                      |   0.626s  |   0.626s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27353_terminationG_0.smt2                      |   2.409s  |   2.409s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27362_terminationG_0.smt2                  |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27367_terminationG_0.smt2                  |   0.498s  |   0.498s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27370_terminationG_0.smt2                  |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27371_terminationG_0.smt2                  |  59.058s  |  59.058s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27372_terminationG_0.smt2                  |  61.899s  |  61.899s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27375_terminationG_0.smt2                  |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27376_terminationG_0.smt2                  |  76.501s  |  76.501s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27377_terminationG_0.smt2                  |  89.294s  |  89.294s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27380_terminationG_0.smt2                  |   1.738s  |   1.738s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  97.794s  |  97.794s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  |  93.654s  |  93.654s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27385_terminationG_0.smt2                  |   1.268s  |   1.268s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27386_terminationG_0.smt2                  |  73.221s  |  73.221s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27387_terminationG_0.smt2                  |  89.297s  |  89.297s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27390_terminationG_0.smt2                  |   0.925s  |   0.925s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27391_terminationG_0.smt2                  |  72.659s  |  72.659s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27392_terminationG_0.smt2                  |  78.402s  |  78.402s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27396_edge_closing_0.smt2                  |   1.314s  |   1.314s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27409_terminationG_0.smt2                  |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27413_terminationG_0.smt2                  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27414_terminationG_0.smt2                  |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27417_terminationG_0.smt2                  |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27418_terminationG_0.smt2                  |  72.354s  |  72.354s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27419_terminationG_0.smt2                  |  70.213s  |  70.213s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27422_terminationG_0.smt2                  |   0.920s  |   0.920s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27423_terminationG_0.smt2                  |  67.160s  |  67.160s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27424_terminationG_0.smt2                  |  81.645s  |  81.645s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27427_terminationG_0.smt2                  |   1.723s  |   1.723s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27428_terminationG_0.smt2                  |  75.036s  |  75.036s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27429_terminationG_0.smt2                  |  98.302s  |  98.302s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27432_terminationG_0.smt2                  |   1.212s  |   1.212s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27433_terminationG_0.smt2                  |  78.297s  |  78.297s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27434_terminationG_0.smt2                  |  80.629s  |  80.629s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27437_terminationG_0.smt2                  |   0.502s  |   0.502s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27438_terminationG_0.smt2                  |  78.985s  |  78.985s  |   0.000s  | 0.0%|
</details>
