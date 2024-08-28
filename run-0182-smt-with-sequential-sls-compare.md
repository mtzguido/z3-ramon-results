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
Job tag: smt-with-sequential-sls
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: a941f5ae84ff5048a4cb00d09ff700cea40582a8
Z3 branch: master
Z3 options: "-T:60 -v:2 -st smt.sls.enable=true smt.sls.parallel=false model_validate=true"
Z3 inputs: inputs/QF_NIA_CInteger
Z3 commit message: reset m_conflict indicator on sls model

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-with-sequential-sls
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: a941f5ae84ff5048a4cb00d09ff700cea40582a8
Z3 branch: master
Z3 options: "-T:60 -v:2 -st smt.sls.enable=true smt.sls.parallel=false model_validate=true"
Z3 inputs: inputs/QF_NIA_CInteger
Z3 commit message: reset m_conflict indicator on sls model

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |   6.497s  |   6.497s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |  59.915s  |  59.915s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |  20.333s  |  20.333s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  59.922s  |  59.922s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  59.848s  |  59.848s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |  59.848s  |  59.848s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |  59.629s  |  59.629s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   2.451s  |   2.451s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |  59.847s  |  59.847s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   3.936s  |   3.936s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |  59.799s  |  59.799s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |   6.497s  |   6.497s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |  59.915s  |  59.915s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |  20.333s  |  20.333s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  59.922s  |  59.922s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  59.848s  |  59.848s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |  59.848s  |  59.848s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |  59.629s  |  59.629s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   2.451s  |   2.451s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |  59.847s  |  59.847s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   3.936s  |   3.936s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |  59.799s  |  59.799s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |   6.497s  |   6.497s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |  59.915s  |  59.915s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |  20.333s  |  20.333s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  59.922s  |  59.922s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  59.848s  |  59.848s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |  59.848s  |  59.848s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |  59.629s  |  59.629s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   2.451s  |   2.451s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |  59.847s  |  59.847s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   3.936s  |   3.936s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |  59.799s  |  59.799s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |   6.497s  |   6.497s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |  59.915s  |  59.915s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |  20.333s  |  20.333s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  59.922s  |  59.922s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  59.848s  |  59.848s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |  59.848s  |  59.848s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |  59.629s  |  59.629s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   2.451s  |   2.451s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |  59.847s  |  59.847s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   3.936s  |   3.936s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |  59.799s  |  59.799s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2 |  60.587s |304.0MiB|
|Stroeder_15__Pure3Phase_true-termination.c__p25531_terminationG_0.smt2                     |  60.294s |154.0MiB|
|Stroeder_15__NonTermination2_false-termination.c__p24939_edge_closing_0.smt2               |  60.137s |84.176MiB|
|Stroeder_15__MirrorInterv.c__p24450_edge_closing_0.smt2                                    |  60.086s |182.0MiB|
|Stroeder_15__svcomp_ex2.c__p25970_terminationG_0.smt2                                      |  60.060s |162.0MiB|
|Stroeder_15__svcomp_ex2.c__p25959_terminationG_0.smt2                                      |  60.022s |249.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22027_edge_closing_0.smt2 |  60.019s |210.0MiB|
|Stroeder_15__svcomp_ex2.c__p25858_terminationG_0.smt2                                      |  60.019s |176.0MiB|
|Stroeder_15__svcomp_ex2.c__p25943_terminationG_0.smt2                                      |  60.018s |403.0MiB|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26924_terminationG_0.smt2                  |  60.018s |147.0MiB|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27325_terminationG_0.smt2               |  60.013s |116.0MiB|
|Stroeder_15__Pure3Phase_true-termination.c__p25537_terminationG_0.smt2                     |  60.013s |181.0MiB|
|Stroeder_15__svcomp_ex2.c__p25964_terminationG_0.smt2                                      |  60.007s |189.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27181_terminationG_0.smt2                   |  60.005s |251.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27176_terminationG_0.smt2                   |  60.001s |228.0MiB|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27315_terminationG_0.smt2               |  60.000s |122.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21469_edge_closing_0.smt2 |  59.999s |101.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21150_edge_closing_0.smt2 |  59.997s |157.0MiB|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27326_terminationG_0.smt2               |  59.997s |134.0MiB|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20313_terminationG_0.smt2          |  59.996s |227.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2 |  60.587s |304.0MiB|
|Stroeder_15__Pure3Phase_true-termination.c__p25531_terminationG_0.smt2                     |  60.294s |154.0MiB|
|Stroeder_15__NonTermination2_false-termination.c__p24939_edge_closing_0.smt2               |  60.137s |84.176MiB|
|Stroeder_15__MirrorInterv.c__p24450_edge_closing_0.smt2                                    |  60.086s |182.0MiB|
|Stroeder_15__svcomp_ex2.c__p25970_terminationG_0.smt2                                      |  60.060s |162.0MiB|
|Stroeder_15__svcomp_ex2.c__p25959_terminationG_0.smt2                                      |  60.022s |249.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22027_edge_closing_0.smt2 |  60.019s |210.0MiB|
|Stroeder_15__svcomp_ex2.c__p25858_terminationG_0.smt2                                      |  60.019s |176.0MiB|
|Stroeder_15__svcomp_ex2.c__p25943_terminationG_0.smt2                                      |  60.018s |403.0MiB|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26924_terminationG_0.smt2                  |  60.018s |147.0MiB|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27325_terminationG_0.smt2               |  60.013s |116.0MiB|
|Stroeder_15__Pure3Phase_true-termination.c__p25537_terminationG_0.smt2                     |  60.013s |181.0MiB|
|Stroeder_15__svcomp_ex2.c__p25964_terminationG_0.smt2                                      |  60.007s |189.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27181_terminationG_0.smt2                   |  60.005s |251.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27176_terminationG_0.smt2                   |  60.001s |228.0MiB|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27315_terminationG_0.smt2               |  60.000s |122.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21469_edge_closing_0.smt2 |  59.999s |101.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21150_edge_closing_0.smt2 |  59.997s |157.0MiB|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27326_terminationG_0.smt2               |  59.997s |134.0MiB|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20313_terminationG_0.smt2          |  59.996s |227.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |81.344MiB|81.344MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |74.896MiB|74.896MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |161.0MiB|161.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |113.0MiB|113.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |123.0MiB|123.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |165.0MiB|165.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |300.0MiB|300.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |123.0MiB|123.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |180.0MiB|180.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |149.0MiB|149.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |154.0MiB|154.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |125.0MiB|125.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |147.0MiB|147.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |120.0MiB|120.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |122.0MiB|122.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |164.0MiB|164.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |127.0MiB|127.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |81.344MiB|81.344MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |74.896MiB|74.896MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |161.0MiB|161.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |113.0MiB|113.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |123.0MiB|123.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |165.0MiB|165.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |300.0MiB|300.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |123.0MiB|123.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |180.0MiB|180.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |149.0MiB|149.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |154.0MiB|154.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |125.0MiB|125.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |147.0MiB|147.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |120.0MiB|120.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |122.0MiB|122.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |164.0MiB|164.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |127.0MiB|127.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |81.344MiB|81.344MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |74.896MiB|74.896MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |161.0MiB|161.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |113.0MiB|113.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |123.0MiB|123.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |165.0MiB|165.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |300.0MiB|300.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |123.0MiB|123.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |180.0MiB|180.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |149.0MiB|149.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |154.0MiB|154.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |125.0MiB|125.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |147.0MiB|147.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |120.0MiB|120.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |122.0MiB|122.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |164.0MiB|164.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |127.0MiB|127.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |81.344MiB|81.344MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |74.896MiB|74.896MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |111.0MiB|111.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |161.0MiB|161.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |113.0MiB|113.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |123.0MiB|123.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |165.0MiB|165.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |300.0MiB|300.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |123.0MiB|123.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |180.0MiB|180.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |149.0MiB|149.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |154.0MiB|154.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |125.0MiB|125.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |147.0MiB|147.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |120.0MiB|120.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |122.0MiB|122.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |164.0MiB|164.0MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |127.0MiB|127.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27007_terminationG_0.smt2                  |  29.710s |505.0MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23340_edge_closing_0.smt2 |  59.956s |411.0MiB|
|Stroeder_15__svcomp_ex2.c__p25943_terminationG_0.smt2                                      |  60.018s |403.0MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23442_edge_closing_0.smt2 |  59.904s |402.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2 |  59.991s |370.0MiB|
|Stroeder_15__svcomp_ex2.c__p25817_terminationG_0.smt2                                      |  59.901s |353.0MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23493_edge_closing_0.smt2 |  59.813s |332.0MiB|
|Stroeder_15__WhileNestedOffset.c__p26453_terminationG_0.smt2                               |  59.921s |325.0MiB|
|Stroeder_15__Narrowing.c__p24552_edge_closing_0.smt2                                       |  59.986s |322.0MiB|
|Stroeder_15__GCD.c__p23180_terminationG_0.smt2                                             |  51.131s |319.0MiB|
|Stroeder_15__UpAndDownIneq.c__p26240_edge_closing_0.smt2                                   |   2.454s |312.0MiB|
|Stroeder_15__Lcm.c__p23906_terminationG_0.smt2                                             |   1.183s |312.0MiB|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24242_terminationG_0.smt2          |   0.853s |312.0MiB|
|Stroeder_15__NO_04.c__p24653_safety_0.smt2                                                 |  59.906s |311.0MiB|
|Stroeder_15__UpAndDownIneq.c__p26230_terminationG_0.smt2                                   |   0.996s |311.0MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23617_edge_closing_0.smt2 |  59.966s |310.0MiB|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23856_terminationG_0.smt2 |   3.012s |310.0MiB|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27385_terminationG_0.smt2                 |   2.863s |310.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21031_terminationG_0.smt2 |   2.858s |310.0MiB|
|Stroeder_15__LogMult.c__p24156_terminationG_0.smt2                                         |   2.834s |310.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27007_terminationG_0.smt2                  |  29.710s |505.0MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23340_edge_closing_0.smt2 |  59.956s |411.0MiB|
|Stroeder_15__svcomp_ex2.c__p25943_terminationG_0.smt2                                      |  60.018s |403.0MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23442_edge_closing_0.smt2 |  59.904s |402.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2 |  59.991s |370.0MiB|
|Stroeder_15__svcomp_ex2.c__p25817_terminationG_0.smt2                                      |  59.901s |353.0MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23493_edge_closing_0.smt2 |  59.813s |332.0MiB|
|Stroeder_15__WhileNestedOffset.c__p26453_terminationG_0.smt2                               |  59.921s |325.0MiB|
|Stroeder_15__Narrowing.c__p24552_edge_closing_0.smt2                                       |  59.986s |322.0MiB|
|Stroeder_15__GCD.c__p23180_terminationG_0.smt2                                             |  51.131s |319.0MiB|
|Stroeder_15__UpAndDownIneq.c__p26240_edge_closing_0.smt2                                   |   2.454s |312.0MiB|
|Stroeder_15__Lcm.c__p23906_terminationG_0.smt2                                             |   1.183s |312.0MiB|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24242_terminationG_0.smt2          |   0.853s |312.0MiB|
|Stroeder_15__NO_04.c__p24653_safety_0.smt2                                                 |  59.906s |311.0MiB|
|Stroeder_15__UpAndDownIneq.c__p26230_terminationG_0.smt2                                   |   0.996s |311.0MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23617_edge_closing_0.smt2 |  59.966s |310.0MiB|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23856_terminationG_0.smt2 |   3.012s |310.0MiB|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27385_terminationG_0.smt2                 |   2.863s |310.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21031_terminationG_0.smt2 |   2.858s |310.0MiB|
|Stroeder_15__LogMult.c__p24156_terminationG_0.smt2                                         |   2.834s |310.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |   6.497s  |   6.497s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |  59.915s  |  59.915s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |  20.333s  |  20.333s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  59.922s  |  59.922s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  59.848s  |  59.848s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |  59.848s  |  59.848s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |  59.629s  |  59.629s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |   2.451s  |   2.451s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |  59.847s  |  59.847s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |   3.936s  |   3.936s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |  59.799s  |  59.799s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20255_terminationG_0.smt2           |  59.904s  |  59.904s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20259_terminationG_0.smt2           |   2.704s  |   2.704s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20260_terminationG_0.smt2           |  59.897s  |  59.897s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20269_terminationG_0.smt2           |  13.950s  |  13.950s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20270_terminationG_0.smt2           |  59.933s  |  59.933s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20271_terminationG_0.smt2           |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20279_terminationG_0.smt2           |  11.145s  |  11.145s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20280_terminationG_0.smt2           |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20281_terminationG_0.smt2           |  59.879s  |  59.879s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20288_terminationG_0.smt2           |   8.419s  |   8.419s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20289_terminationG_0.smt2           |  43.244s  |  43.244s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20305_terminationG_0.smt2           |   9.986s  |   9.986s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20306_terminationG_0.smt2           |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20307_terminationG_0.smt2           |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20312_terminationG_0.smt2           |  11.741s  |  11.741s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20313_terminationG_0.smt2           |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20314_terminationG_0.smt2           |  59.858s  |  59.858s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20324_terminationG_0.smt2           |  12.697s  |  12.697s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20325_terminationG_0.smt2           |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20326_terminationG_0.smt2           |  59.907s  |  59.907s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_0_0.smt2                |   9.651s  |   9.651s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_2_0.smt2                |   8.886s  |   8.886s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_3_0.smt2                |   4.992s  |   4.992s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_4_0.smt2                |   2.191s  |   2.191s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-Fig1_true-termination.c__p20413_terminationG_0.smt2  |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-Fig2b_true-termination.c__p20426_terminationG_0.smt2  |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-Fig2b_true-termination.c__terminationS_1_0.smt2  |   2.300s  |   2.300s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-complex_true-termination.c__term_unfeasibility_0_0.smt2  |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-counterex1b_true-termination.c__p20394_terminationG_0.smt2  |   1.505s  |   1.505s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-counterex1b_true-termination.c__p20395_terminationG_0.smt2  |  12.651s  |  12.651s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-counterex1b_true-termination.c__p20396_terminationG_0.smt2  |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-loops_true-termination.c__p20439_terminationG_0.smt2  |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-loops_true-termination.c__p20440_terminationG_0.smt2  |   0.778s  |   0.778s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-loops_true-termination.c__term_unfeasibility_0_0.smt2  |   0.969s  |   0.969s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-nestedLoop_true-termination.c__p20452_terminationG_0.smt2  |   5.714s  |   5.714s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-nestedLoop_true-termination.c__p20453_terminationG_0.smt2  |   0.893s  |   0.893s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-speedFails4_true-termination.c__p20494_terminationG_0.smt2  |   0.594s  |   0.594s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-speedpldi4_true-termination.c__p20516_terminationG_0.smt2  |   2.100s  |   2.100s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20546_terminationG_0.smt2                                        |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20552_terminationG_0.smt2                                        |   2.250s  |   2.250s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20553_terminationG_0.smt2                                        |   3.590s  |   3.590s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20556_edge_closing_0.smt2                                        |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20557_edge_closing_0.smt2                                        |   2.899s  |   2.899s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20618_terminationG_0.smt2                                    |   2.244s  |   2.244s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20619_terminationG_0.smt2                                    |   3.947s  |   3.947s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20626_edge_closing_0.smt2                                    |   2.240s  |   2.240s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20627_edge_closing_0.smt2                                    |   3.283s  |   3.283s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20638_terminationG_0.smt2                                |   2.458s  |   2.458s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20639_terminationG_0.smt2                                |   1.644s  |   1.644s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20650_terminationG_0.smt2                                |   1.299s  |   1.299s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20651_terminationG_0.smt2                                |  59.911s  |  59.911s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20652_terminationG_0.smt2                                |  59.881s  |  59.881s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20655_terminationG_0.smt2                                |   1.023s  |   1.023s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20656_terminationG_0.smt2                                |  59.841s  |  59.841s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20657_terminationG_0.smt2                                |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20661_edge_closing_0.smt2                                |  59.913s  |  59.913s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20662_edge_closing_0.smt2                                |  59.866s  |  59.866s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20668_edge_closing_0.smt2                                |  59.812s  |  59.812s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20669_edge_closing_0.smt2                                |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__terminationQ_1_0.smt2                                     |   1.024s  |   1.024s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |   2.177s  |   2.177s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20688_terminationG_0.smt2                                       |   1.834s  |   1.834s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20689_terminationG_0.smt2                                       |   2.286s  |   2.286s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20690_terminationG_0.smt2                                       |   3.220s  |   3.220s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20693_edge_closing_0.smt2                                       |   2.394s  |   2.394s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20694_edge_closing_0.smt2                                       |  59.849s  |  59.849s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__terminationS_1_0.smt2                                            |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|Stroeder_15__Benghazi_true-termination.c__p20729_terminationG_0.smt2                        |   0.920s  |   0.920s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20762_terminationG_0.smt2  |   2.143s  |   2.143s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20763_terminationG_0.smt2  |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20774_edge_closing_0.smt2  |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20777_edge_closing_0.smt2  |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1_true-termination.c__p20785_terminationG_0.smt2  |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1_true-termination.c__p20786_terminationG_0.smt2  |   1.033s  |   1.033s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-ICALP2005-Fig1_true-termination.c__p20810_terminationG_0.smt2  |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-ICALP2005-Fig1_true-termination.c__p20814_terminationG_0.smt2  |   6.820s  |   6.820s  |   0.000s  | 0.0%|
|Stroeder_15__BrockschmidtCookFuhs-CAV2013-Fig9a_true-termination.c__p20828_terminationG_0.smt2  |   2.591s  |   2.591s  |   0.000s  | 0.0%|
|Stroeder_15__BrockschmidtCookFuhs-CAV2013-Introduction_true-termination.c__p20837_terminationG_0.smt2  |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20849_terminationG_0.smt2  |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20853_terminationG_0.smt2  |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20854_terminationG_0.smt2  |  16.273s  |  16.273s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20855_terminationG_0.smt2  |  59.898s  |  59.898s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20858_terminationG_0.smt2  |   0.942s  |   0.942s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20859_terminationG_0.smt2  |  21.825s  |  21.825s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20860_terminationG_0.smt2  |  59.736s  |  59.736s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20863_terminationG_0.smt2  |   0.714s  |   0.714s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20864_terminationG_0.smt2  |  14.386s  |  14.386s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20865_terminationG_0.smt2  |  59.889s  |  59.889s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20868_terminationG_0.smt2  |   0.966s  |   0.966s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20869_terminationG_0.smt2  |  16.535s  |  16.535s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20870_terminationG_0.smt2  |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20873_terminationG_0.smt2  |   1.112s  |   1.112s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20874_terminationG_0.smt2  |  13.780s  |  13.780s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20875_terminationG_0.smt2  |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20888_terminationG_0.smt2  |   2.188s  |   2.188s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20892_terminationG_0.smt2  |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   1.309s  |   1.309s  |   0.000s  | 0.0%|
|Stroeder_15__ChenCookFuhsNimkarOHearn-TACAS2014-Introduction_false-termination.c__p20918_terminationG_0.smt2  |   0.818s  |   0.818s  |   0.000s  | 0.0%|
|Stroeder_15__ChenCookFuhsNimkarOHearn-TACAS2014-Introduction_false-termination.c__p20919_terminationG_0.smt2  |   2.143s  |   2.143s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20939_terminationG_0.smt2  |   0.572s  |   0.572s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20940_terminationG_0.smt2  |   3.609s  |   3.609s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20941_terminationG_0.smt2  |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20944_edge_closing_0.smt2  |  59.894s  |  59.894s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20945_edge_closing_0.smt2  |  59.843s  |  59.843s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.01_true-termination.c__p20984_terminationG_0.smt2  |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.01_true-termination.c__p20989_terminationG_0.smt2  |   2.301s  |   2.301s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21003_terminationG_0.smt2  |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21008_terminationG_0.smt2  |   6.394s  |   6.394s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21011_terminationG_0.smt2  |   1.055s  |   1.055s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21012_terminationG_0.smt2  |  35.955s  |  35.955s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21013_terminationG_0.smt2  |  59.898s  |  59.898s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21016_terminationG_0.smt2  |   1.949s  |   1.949s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21017_terminationG_0.smt2  |  22.461s  |  22.461s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21018_terminationG_0.smt2  |  59.824s  |  59.824s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21021_terminationG_0.smt2  |   1.015s  |   1.015s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21022_terminationG_0.smt2  |  59.852s  |  59.852s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21023_terminationG_0.smt2  |  59.843s  |  59.843s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21026_terminationG_0.smt2  |   1.559s  |   1.559s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21027_terminationG_0.smt2  |  25.905s  |  25.905s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  |  59.799s  |  59.799s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21031_terminationG_0.smt2  |   2.858s  |   2.858s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21032_terminationG_0.smt2  |  19.952s  |  19.952s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21033_terminationG_0.smt2  |  59.890s  |  59.890s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21037_edge_closing_0.smt2  |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21040_edge_closing_0.smt2  |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21044_edge_closing_0.smt2  |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21056_terminationG_0.smt2  |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21057_terminationG_0.smt2  |  59.869s  |  59.869s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21058_terminationG_0.smt2  |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21061_edge_closing_0.smt2  |  18.998s  |  18.998s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21062_edge_closing_0.smt2  |   1.944s  |   1.944s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21079_terminationG_0.smt2  |   0.425s  |   0.425s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21083_terminationG_0.smt2  |   6.986s  |   6.986s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21084_terminationG_0.smt2  |  59.760s  |  59.760s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21085_terminationG_0.smt2  |  59.912s  |  59.912s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21107_terminationG_0.smt2  |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21108_terminationG_0.smt2  |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21112_terminationG_0.smt2  |   0.622s  |   0.622s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21113_terminationG_0.smt2  |   1.097s  |   1.097s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21116_terminationG_0.smt2  |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21118_terminationG_0.smt2  |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21122_terminationG_0.smt2  |   2.289s  |   2.289s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21123_terminationG_0.smt2  |   1.713s  |   1.713s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21126_terminationG_0.smt2  |  14.569s  |  14.569s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21127_terminationG_0.smt2  |  59.887s  |  59.887s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21128_terminationG_0.smt2  |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21131_terminationG_0.smt2  |  14.436s  |  14.436s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21132_terminationG_0.smt2  |  28.616s  |  28.616s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21136_edge_closing_0.smt2  |   2.188s  |   2.188s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21137_edge_closing_0.smt2  |  59.875s  |  59.875s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21141_edge_closing_0.smt2  |  59.915s  |  59.915s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21142_edge_closing_0.smt2  |   1.070s  |   1.070s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21143_edge_closing_0.smt2  |  59.863s  |  59.863s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21144_edge_closing_0.smt2  |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |   2.426s  |   2.426s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21148_edge_closing_0.smt2  |   2.137s  |   2.137s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21149_edge_closing_0.smt2  |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21150_edge_closing_0.smt2  |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.07_true-termination.c__p21184_terminationG_0.smt2  |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.07_true-termination.c__p21189_terminationG_0.smt2  |   1.624s  |   1.624s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.07_true-termination.c__terminationS_0_0.smt2  |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.08_true-termination.c__p21202_terminationG_0.smt2  |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.08_true-termination.c__p21203_terminationG_0.smt2  |   4.219s  |   4.219s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21242_terminationG_0.smt2  |   2.508s  |   2.508s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21246_terminationG_0.smt2  |   2.319s  |   2.319s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21258_terminationG_0.smt2  |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21260_terminationG_0.smt2  |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21265_terminationG_0.smt2  |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21280_terminationG_0.smt2  |  55.869s  |  55.869s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21283_terminationG_0.smt2  |  14.917s  |  14.917s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21285_terminationG_0.smt2  |  24.965s  |  24.965s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21288_terminationG_0.smt2  |  11.549s  |  11.549s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21290_terminationG_0.smt2  |  25.774s  |  25.774s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21293_terminationG_0.smt2  |  12.822s  |  12.822s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21294_terminationG_0.smt2  |  59.918s  |  59.918s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21295_terminationG_0.smt2  |  23.660s  |  23.660s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21298_terminationG_0.smt2  |  22.405s  |  22.405s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21299_terminationG_0.smt2  |  15.484s  |  15.484s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21300_terminationG_0.smt2  |   6.810s  |   6.810s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21303_terminationG_0.smt2  |  21.732s  |  21.732s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21304_terminationG_0.smt2  |  59.858s  |  59.858s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21305_terminationG_0.smt2  |  57.295s  |  57.295s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21308_terminationG_0.smt2  |  20.171s  |  20.171s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21309_terminationG_0.smt2  |   4.598s  |   4.598s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21310_terminationG_0.smt2  |   2.234s  |   2.234s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21313_terminationG_0.smt2  |  19.775s  |  19.775s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21314_terminationG_0.smt2  |   2.404s  |   2.404s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21315_terminationG_0.smt2  |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21318_terminationG_0.smt2  |  23.426s  |  23.426s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21319_terminationG_0.smt2  |  24.143s  |  24.143s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21320_terminationG_0.smt2  |  13.236s  |  13.236s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21323_terminationG_0.smt2  |  22.357s  |  22.357s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21324_terminationG_0.smt2  |  59.881s  |  59.881s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21325_terminationG_0.smt2  |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21328_terminationG_0.smt2  |  21.665s  |  21.665s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21329_terminationG_0.smt2  |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21330_terminationG_0.smt2  |   1.836s  |   1.836s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21334_edge_closing_0.smt2  |   6.664s  |   6.664s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21336_edge_closing_0.smt2  |   1.632s  |   1.632s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21337_edge_closing_0.smt2  |   1.408s  |   1.408s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21338_edge_closing_0.smt2  |   5.861s  |   5.861s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21342_edge_closing_0.smt2  |  17.758s  |  17.758s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21343_edge_closing_0.smt2  |  59.908s  |  59.908s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |  59.917s  |  59.917s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21351_edge_closing_0.smt2  |  13.612s  |  13.612s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21352_edge_closing_0.smt2  |  59.628s  |  59.628s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21353_edge_closing_0.smt2  |  59.811s  |  59.811s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__terminationS_0_0.smt2  |   2.414s  |   2.414s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21362_terminationG_0.smt2  |   1.768s  |   1.768s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21367_terminationG_0.smt2  |   2.302s  |   2.302s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21371_terminationG_0.smt2  |   2.188s  |   2.188s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21372_terminationG_0.smt2  |   1.655s  |   1.655s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21376_terminationG_0.smt2  |  13.453s  |  13.453s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21377_terminationG_0.smt2  |   1.118s  |   1.118s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21382_terminationG_0.smt2  |   2.036s  |   2.036s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21385_terminationG_0.smt2  |   1.404s  |   1.404s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21386_terminationG_0.smt2  |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21387_terminationG_0.smt2  |  40.436s  |  40.436s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21390_terminationG_0.smt2  |   1.457s  |   1.457s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21391_terminationG_0.smt2  |  12.835s  |  12.835s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21392_terminationG_0.smt2  |  44.894s  |  44.894s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21395_terminationG_0.smt2  |  11.459s  |  11.459s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  59.858s  |  59.858s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21400_edge_closing_0.smt2  |  59.847s  |  59.847s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21401_edge_closing_0.smt2  |  59.795s  |  59.795s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.13_true-termination.c__p21424_terminationG_0.smt2  |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21451_terminationG_0.smt2  |   2.028s  |   2.028s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21452_terminationG_0.smt2  |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21453_terminationG_0.smt2  |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21456_edge_closing_0.smt2  |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21457_edge_closing_0.smt2  |   6.331s  |   6.331s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21463_edge_closing_0.smt2  |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21464_edge_closing_0.smt2  |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21468_edge_closing_0.smt2  |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21469_edge_closing_0.smt2  |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21470_edge_closing_0.smt2  |  59.958s  |  59.958s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__terminationQ_0_0.smt2  |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.15_false-termination.c__p21487_terminationG_0.smt2  |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.15_false-termination.c__p21491_terminationG_0.smt2  |   2.203s  |   2.203s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.15_false-termination.c__p21492_terminationG_0.smt2  |  59.864s  |  59.864s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.16_true-termination.c__p21520_terminationG_0.smt2  |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.16_true-termination.c__p21525_terminationG_0.smt2  |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.16_true-termination.c__p21530_terminationG_0.smt2  |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21539_terminationG_0.smt2  |   0.721s  |   0.721s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21543_terminationG_0.smt2  |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21544_terminationG_0.smt2  |   1.736s  |   1.736s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21547_terminationG_0.smt2  |   1.428s  |   1.428s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21548_terminationG_0.smt2  |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21549_terminationG_0.smt2  |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21552_terminationG_0.smt2  |   2.585s  |   2.585s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21553_terminationG_0.smt2  |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21554_terminationG_0.smt2  |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21562_edge_closing_0.smt2  |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.18_true-termination.c__p21582_terminationG_0.smt2  |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.19_true-termination.c__p21598_terminationG_0.smt2  |   0.395s  |   0.395s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.22_true-termination.c__p21645_terminationG_0.smt2  |   0.747s  |   0.747s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.22_true-termination.c__p21649_terminationG_0.smt2  |   0.732s  |   0.732s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.22_true-termination.c__p21650_terminationG_0.smt2  |   0.841s  |   0.841s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21678_terminationG_0.smt2  |   2.301s  |   2.301s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21685_terminationG_0.smt2  |  25.343s  |  25.343s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21690_terminationG_0.smt2  |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21697_terminationG_0.smt2  |  19.083s  |  19.083s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21702_terminationG_0.smt2  |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21709_terminationG_0.smt2  |   0.594s  |   0.594s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21719_terminationG_0.smt2  |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21726_terminationG_0.smt2  |   0.914s  |   0.914s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21727_terminationG_0.smt2  |   2.282s  |   2.282s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21728_terminationG_0.smt2  |   1.134s  |   1.134s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21732_terminationG_0.smt2  |   0.718s  |   0.718s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21733_terminationG_0.smt2  |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21737_terminationG_0.smt2  |   2.246s  |   2.246s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21738_terminationG_0.smt2  |  59.922s  |  59.922s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21748_edge_closing_0.smt2  |   0.917s  |   0.917s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21772_terminationG_0.smt2  |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21774_terminationG_0.smt2  |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21780_terminationG_0.smt2  |   2.529s  |   2.529s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21781_terminationG_0.smt2  |  12.240s  |  12.240s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21788_terminationG_0.smt2  |  31.965s  |  31.965s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21793_terminationG_0.smt2  |   7.440s  |   7.440s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21794_terminationG_0.smt2  |  16.397s  |  16.397s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21795_terminationG_0.smt2  |  59.857s  |  59.857s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21802_terminationG_0.smt2  |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21803_terminationG_0.smt2  |   2.407s  |   2.407s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.04_true-termination.c__p21822_terminationG_0.smt2  |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.04_true-termination.c__p21827_terminationG_0.smt2  |   0.831s  |   0.831s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21868_terminationG_0.smt2  |   2.089s  |   2.089s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21870_terminationG_0.smt2  |  47.660s  |  47.660s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21875_terminationG_0.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21876_terminationG_0.smt2  |   6.292s  |   6.292s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21877_terminationG_0.smt2  |  59.932s  |  59.932s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21882_terminationG_0.smt2  |   2.232s  |   2.232s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21883_terminationG_0.smt2  |   1.570s  |   1.570s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21884_terminationG_0.smt2  |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21890_terminationG_0.smt2  |   2.146s  |   2.146s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21891_terminationG_0.smt2  |  41.683s  |  41.683s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21892_terminationG_0.smt2  |  59.928s  |  59.928s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21895_terminationG_0.smt2  |   8.674s  |   8.674s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21896_terminationG_0.smt2  |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21897_terminationG_0.smt2  |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21905_terminationG_0.smt2  |   3.070s  |   3.070s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21906_terminationG_0.smt2  |  10.694s  |  10.694s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21907_terminationG_0.smt2  |  59.283s  |  59.283s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21910_terminationG_0.smt2  |  14.983s  |  14.983s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21911_terminationG_0.smt2  |  59.787s  |  59.787s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21912_terminationG_0.smt2  |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21922_terminationG_0.smt2  |   2.881s  |   2.881s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21923_terminationG_0.smt2  |   2.281s  |   2.281s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21924_terminationG_0.smt2  |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21927_terminationG_0.smt2  |  14.675s  |  14.675s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21928_terminationG_0.smt2  |  59.860s  |  59.860s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21929_terminationG_0.smt2  |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21938_terminationG_0.smt2  |  10.069s  |  10.069s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21939_terminationG_0.smt2  |  59.610s  |  59.610s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21940_terminationG_0.smt2  |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21943_terminationG_0.smt2  |   3.183s  |   3.183s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21944_terminationG_0.smt2  |   5.899s  |   5.899s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21945_terminationG_0.smt2  |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21948_terminationG_0.smt2  |   4.570s  |   4.570s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21949_terminationG_0.smt2  |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |  59.917s  |  59.917s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21953_terminationG_0.smt2  |  12.142s  |  12.142s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21954_terminationG_0.smt2  |  59.865s  |  59.865s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21955_terminationG_0.smt2  |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21957_terminationG_0.smt2  |  16.368s  |  16.368s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21959_terminationG_0.smt2  |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |  59.913s  |  59.913s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21963_terminationG_0.smt2  |  13.719s  |  13.719s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21964_terminationG_0.smt2  |  59.908s  |  59.908s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21965_terminationG_0.smt2  |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21968_terminationG_0.smt2  |  13.629s  |  13.629s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21969_terminationG_0.smt2  |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21970_terminationG_0.smt2  |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21973_terminationG_0.smt2  |  15.101s  |  15.101s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21974_terminationG_0.smt2  |  10.596s  |  10.596s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21975_terminationG_0.smt2  |  59.898s  |  59.898s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21978_terminationG_0.smt2  |  16.233s  |  16.233s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21979_terminationG_0.smt2  |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21980_terminationG_0.smt2  |  24.070s  |  24.070s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21983_terminationG_0.smt2  |  21.640s  |  21.640s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21984_terminationG_0.smt2  |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21985_terminationG_0.smt2  |  59.910s  |  59.910s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21988_terminationG_0.smt2  |  16.921s  |  16.921s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21989_terminationG_0.smt2  |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21990_terminationG_0.smt2  |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21993_terminationG_0.smt2  |  15.887s  |  15.887s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21994_terminationG_0.smt2  |  59.928s  |  59.928s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21998_terminationG_0.smt2  |  16.490s  |  16.490s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21999_terminationG_0.smt2  |  59.884s  |  59.884s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22004_terminationG_0.smt2  |  15.519s  |  15.519s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22005_terminationG_0.smt2  |  59.861s  |  59.861s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22006_terminationG_0.smt2  |  59.582s  |  59.582s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22009_terminationG_0.smt2  |  18.173s  |  18.173s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22010_terminationG_0.smt2  |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22011_terminationG_0.smt2  |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22014_terminationG_0.smt2  |  19.305s  |  19.305s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22015_terminationG_0.smt2  |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22016_terminationG_0.smt2  |  59.915s  |  59.915s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22019_terminationG_0.smt2  |  18.359s  |  18.359s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22020_terminationG_0.smt2  |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22021_terminationG_0.smt2  |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22023_edge_closing_0.smt2  |   6.612s  |   6.612s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22024_edge_closing_0.smt2  |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22025_edge_closing_0.smt2  |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22027_edge_closing_0.smt2  |  60.019s  |  60.019s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |  59.862s  |  59.862s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22029_edge_closing_0.smt2  |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22031_edge_closing_0.smt2  |  59.898s  |  59.898s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__terminationQ_14_0.smt2  |   7.139s  |   7.139s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__terminationS_0_0.smt2  |  10.796s  |  10.796s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.07_true-termination.c__p22044_terminationG_0.smt2  |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.07_true-termination.c__p22045_terminationG_0.smt2  |   2.250s  |   2.250s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.08_true-termination.c__p22056_terminationG_0.smt2  |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.08_true-termination.c__p22062_terminationG_0.smt2  |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.08_true-termination.c__p22067_terminationG_0.smt2  |   0.557s  |   0.557s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22103_terminationG_0.smt2  |   0.462s  |   0.462s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22104_terminationG_0.smt2  |   0.677s  |   0.677s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22109_terminationG_0.smt2  |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22113_terminationG_0.smt2  |  39.912s  |  39.912s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22114_terminationG_0.smt2  |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22118_terminationG_0.smt2  |  18.274s  |  18.274s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22119_terminationG_0.smt2  |  58.929s  |  58.929s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22122_terminationG_0.smt2  |   3.364s  |   3.364s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22123_terminationG_0.smt2  |  25.876s  |  25.876s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22124_terminationG_0.smt2  |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22129_terminationG_0.smt2  |  59.905s  |  59.905s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22142_terminationG_0.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22147_terminationG_0.smt2  |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22148_terminationG_0.smt2  |   0.634s  |   0.634s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |  60.587s  |  60.587s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22158_terminationG_0.smt2  |   2.199s  |   2.199s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22160_terminationG_0.smt2  |   2.569s  |   2.569s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22169_terminationG_0.smt2  |  30.344s  |  30.344s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22170_terminationG_0.smt2  |  13.143s  |  13.143s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22177_terminationG_0.smt2                                           |   0.772s  |   0.772s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22178_terminationG_0.smt2                                           |   2.542s  |   2.542s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           |  59.890s  |  59.890s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22182_terminationG_0.smt2                                           |   1.224s  |   1.224s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22183_terminationG_0.smt2                                           |   2.467s  |   2.467s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22184_terminationG_0.smt2                                           |  59.881s  |  59.881s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22189_edge_closing_0.smt2                                           |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__term_unfeasibility_0_0.smt2                                          |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__terminationQ_1_0.smt2                                                |   0.916s  |   0.916s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22199_terminationG_0.smt2                                       |   2.203s  |   2.203s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22200_terminationG_0.smt2                                       |  59.803s  |  59.803s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22201_terminationG_0.smt2                                       |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22206_edge_closing_0.smt2                                       |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__term_unfeasibility_1_0.smt2                                      |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__terminationQ_0_0.smt2                                            |   1.775s  |   1.775s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22316_terminationG_0.smt2                                      |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22317_terminationG_0.smt2                                      |   1.829s  |   1.829s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22318_terminationG_0.smt2                                      |  59.924s  |  59.924s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22321_terminationG_0.smt2                                      |   0.606s  |   0.606s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22322_terminationG_0.smt2                                      |   2.369s  |   2.369s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22323_terminationG_0.smt2                                      |  59.898s  |  59.898s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv2.c__p22248_safety_0.smt2                                           |   0.907s  |   0.907s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv2.c__p22249_safety_0.smt2                                           |   2.378s  |   2.378s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22271_terminationG_0.smt2                                     |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22289_terminationG_0.smt2                                     |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22290_terminationG_0.smt2                                     |   2.119s  |   2.119s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22291_terminationG_0.smt2                                     |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22294_terminationG_0.smt2                                     |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22295_terminationG_0.smt2                                     |   2.363s  |   2.363s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22296_terminationG_0.smt2                                     |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22332_terminationG_0.smt2                                      |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22336_terminationG_0.smt2                                      |   0.679s  |   0.679s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22337_terminationG_0.smt2                                      |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22340_terminationG_0.smt2                                      |   2.488s  |   2.488s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22341_terminationG_0.smt2                                      |  59.740s  |  59.740s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      |  59.873s  |  59.873s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22345_terminationG_0.smt2                                      |  23.276s  |  23.276s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22346_terminationG_0.smt2                                      |  59.886s  |  59.886s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22347_terminationG_0.smt2                                      |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   2.582s  |   2.582s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22351_terminationG_0.smt2                                      |  59.901s  |  59.901s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22355_terminationG_0.smt2                                      |   3.601s  |   3.601s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22356_terminationG_0.smt2                                      |  59.811s  |  59.811s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22357_terminationG_0.smt2                                      |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22365_edge_closing_0.smt2                                      |   6.834s  |   6.834s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__terminationQ_3_0.smt2                                           |   2.674s  |   2.674s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__terminationS_1_0.smt2                                           |   2.414s  |   2.414s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8a-modified_true-termination.c__p22401_terminationG_0.smt2  |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8b_true-termination.c__p22418_terminationG_0.smt2  |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8b_true-termination.c__p22419_terminationG_0.smt2  |   1.376s  |   1.376s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8b_true-termination.c__p22424_terminationG_0.smt2  |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22435_terminationG_0.smt2                                           |   1.084s  |   1.084s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22436_terminationG_0.smt2                                           |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22440_terminationG_0.smt2                                           |   2.264s  |   2.264s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22442_terminationG_0.smt2                                           |  59.889s  |  59.889s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22445_terminationG_0.smt2                                           |   2.470s  |   2.470s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22446_terminationG_0.smt2                                           |  59.912s  |  59.912s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22447_terminationG_0.smt2                                           |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22450_terminationG_0.smt2                                           |   2.347s  |   2.347s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22451_terminationG_0.smt2                                           |  59.870s  |  59.870s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22452_terminationG_0.smt2                                           |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22455_terminationG_0.smt2                                           |   2.402s  |   2.402s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22456_terminationG_0.smt2                                           |  59.893s  |  59.893s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22457_terminationG_0.smt2                                           |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22460_terminationG_0.smt2                                           |   2.332s  |   2.332s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22461_terminationG_0.smt2                                           |  59.870s  |  59.870s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22462_terminationG_0.smt2                                           |  59.877s  |  59.877s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__terminationS_0_0.smt2                                                |   1.347s  |   1.347s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22480_terminationG_0.smt2                                  |   0.628s  |   0.628s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22481_terminationG_0.smt2                                  |   0.867s  |   0.867s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22484_terminationG_0.smt2                                  |   0.789s  |   0.789s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22485_terminationG_0.smt2                                  |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22491_terminationG_0.smt2                                  |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22494_terminationG_0.smt2                                  |  11.330s  |  11.330s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22495_terminationG_0.smt2                                  |  59.889s  |  59.889s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22496_terminationG_0.smt2                                  |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22499_terminationG_0.smt2                                  |  12.690s  |  12.690s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22500_terminationG_0.smt2                                  |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22501_terminationG_0.smt2                                  |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22504_terminationG_0.smt2                                  |  11.872s  |  11.872s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22505_terminationG_0.smt2                                  |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22506_terminationG_0.smt2                                  |  59.920s  |  59.920s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22514_edge_closing_0.smt2                                  |  59.928s  |  59.928s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22516_edge_closing_0.smt2                                  |   5.640s  |   5.640s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22517_edge_closing_0.smt2                                  |   2.112s  |   2.112s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22520_edge_closing_0.smt2                                  |   0.650s  |   0.650s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22522_edge_closing_0.smt2                                  |   2.342s  |   2.342s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22523_edge_closing_0.smt2                                  |   0.713s  |   0.713s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__terminationS_1_0.smt2                                       |   2.040s  |   2.040s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__terminationS_2_0.smt2                                       |   2.331s  |   2.331s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__terminationS_3_0.smt2                                       |   9.602s  |   9.602s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22530_terminationG_0.smt2                                        |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22531_terminationG_0.smt2                                        |   2.232s  |   2.232s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22535_terminationG_0.smt2                                        |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22536_terminationG_0.smt2                                        |   2.510s  |   2.510s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22537_terminationG_0.smt2                                        |  59.866s  |  59.866s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22540_terminationG_0.smt2                                        |   0.815s  |   0.815s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22541_terminationG_0.smt2                                        |   2.592s  |   2.592s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22542_terminationG_0.smt2                                        |  59.692s  |  59.692s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22545_terminationG_0.smt2                                        |   2.201s  |   2.201s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22546_terminationG_0.smt2                                        |   2.549s  |   2.549s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22547_terminationG_0.smt2                                        |  59.871s  |  59.871s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22550_terminationG_0.smt2                                        |   1.018s  |   1.018s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22551_terminationG_0.smt2                                        |  19.334s  |  19.334s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22552_terminationG_0.smt2                                        |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22555_terminationG_0.smt2                                        |   0.957s  |   0.957s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22556_terminationG_0.smt2                                        |   2.607s  |   2.607s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22557_terminationG_0.smt2                                        |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__terminationQ_5_0.smt2                                             |   0.634s  |   0.634s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22575_terminationG_0.smt2                                              |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22594_terminationG_0.smt2                                              |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|Stroeder_15__Et2.c__p22608_terminationG_0.smt2                                              |   2.187s  |   2.187s  |   0.000s  | 0.0%|
|Stroeder_15__Et2.c__p22609_terminationG_0.smt2                                              |  59.886s  |  59.886s  |   0.000s  | 0.0%|
|Stroeder_15__Et2.c__p22613_edge_closing_0.smt2                                              |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |  13.706s  |  13.706s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22640_terminationG_0.smt2                                              |  59.724s  |  59.724s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22641_terminationG_0.smt2                                              |  59.762s  |  59.762s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22653_edge_closing_0.smt2                                              |  59.912s  |  59.912s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22658_edge_closing_0.smt2                                              |   0.680s  |   0.680s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22659_edge_closing_0.smt2                                              |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__terminationS_0_0.smt2                                                   |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22671_terminationG_0.smt2                                             |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22672_terminationG_0.smt2                                             |   2.138s  |   2.138s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |  59.898s  |  59.898s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22676_terminationG_0.smt2                                             |   0.969s  |   0.969s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22677_terminationG_0.smt2                                             |   2.325s  |   2.325s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22678_terminationG_0.smt2                                             |  59.880s  |  59.880s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22698_terminationG_0.smt2                                             |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22699_terminationG_0.smt2                                             |   1.793s  |   1.793s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22700_terminationG_0.smt2                                             |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22703_terminationG_0.smt2                                             |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22704_terminationG_0.smt2                                             |   2.283s  |   2.283s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22705_terminationG_0.smt2                                             |  59.886s  |  59.886s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22750_terminationG_0.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   2.096s  |   2.096s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22752_terminationG_0.smt2                                             |   2.776s  |   2.776s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   0.704s  |   0.704s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   1.841s  |   1.841s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   3.229s  |   3.229s  |   0.000s  | 0.0%|
|Stroeder_15__Ex06.c__p22785_edge_closing_0.smt2                                             |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22818_terminationG_0.smt2                                             |   2.811s  |   2.811s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |  45.675s  |  45.675s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22820_terminationG_0.smt2                                             |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   2.283s  |   2.283s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22835_terminationG_0.smt2                                        |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22836_terminationG_0.smt2                                        |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22837_terminationG_0.smt2                                        |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22842_terminationG_0.smt2                                        |   3.099s  |   3.099s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22843_terminationG_0.smt2                                        |  39.977s  |  39.977s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22844_terminationG_0.smt2                                        |  59.362s  |  59.362s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22847_terminationG_0.smt2                                        |   2.636s  |   2.636s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22848_terminationG_0.smt2                                        |  59.820s  |  59.820s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22849_terminationG_0.smt2                                        |  59.902s  |  59.902s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   2.243s  |   2.243s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22853_terminationG_0.smt2                                        |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22857_terminationG_0.smt2                                        |   2.562s  |   2.562s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22858_terminationG_0.smt2                                        |  59.868s  |  59.868s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22859_terminationG_0.smt2                                        |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__terminationQ_3_0.smt2                                             |   1.561s  |   1.561s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22868_terminationG_0.smt2                                        |  19.242s  |  19.242s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   2.213s  |   2.213s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22873_terminationG_0.smt2                                        |   0.737s  |   0.737s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22879_terminationG_0.smt2                                        |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22880_terminationG_0.smt2                                        |  59.525s  |  59.525s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22883_terminationG_0.smt2                                        |   1.980s  |   1.980s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22884_terminationG_0.smt2                                        |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22885_terminationG_0.smt2                                        |  59.914s  |  59.914s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22888_terminationG_0.smt2                                        |   2.154s  |   2.154s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22889_terminationG_0.smt2                                        |  59.846s  |  59.846s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22890_terminationG_0.smt2                                        |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22893_terminationG_0.smt2                                        |   2.425s  |   2.425s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22895_terminationG_0.smt2                                        |  59.889s  |  59.889s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22896_terminationG_0.smt2                                        |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22899_terminationG_0.smt2                                        |   2.315s  |   2.315s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22900_terminationG_0.smt2                                        |  59.627s  |  59.627s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22901_terminationG_0.smt2                                        |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__terminationQ_3_0.smt2                                             |   2.368s  |   2.368s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p22994_terminationG_0.smt2                                             |   2.607s  |   2.607s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23021_terminationG_0.smt2                                             |  59.880s  |  59.880s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23022_terminationG_0.smt2                                             |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23033_edge_closing_0.smt2                                             |   0.608s  |   0.608s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23038_edge_closing_0.smt2                                             |   2.308s  |   2.308s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23039_edge_closing_0.smt2                                             |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22917_terminationG_0.smt2                                            |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22918_terminationG_0.smt2                                            |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22927_terminationG_0.smt2                                            |   1.165s  |   1.165s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22933_terminationG_0.smt2                                            |   1.900s  |   1.900s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22937_terminationG_0.smt2                                            |  59.386s  |  59.386s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22938_terminationG_0.smt2                                            |  59.887s  |  59.887s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22942_edge_closing_0.smt2                                            |   6.521s  |   6.521s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22953_edge_closing_0.smt2                                            |   2.176s  |   2.176s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22954_edge_closing_0.smt2                                            |  59.890s  |  59.890s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22955_edge_closing_0.smt2                                            |  59.813s  |  59.813s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23156_terminationG_0.smt2                                              |   2.146s  |   2.146s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23157_terminationG_0.smt2                                              |   5.737s  |   5.737s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23158_terminationG_0.smt2                                              |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23167_terminationG_0.smt2                                              |   2.607s  |   2.607s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23168_terminationG_0.smt2                                              |   8.175s  |   8.175s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23171_terminationG_0.smt2                                              |   6.416s  |   6.416s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23172_terminationG_0.smt2                                              |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |  59.879s  |  59.879s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23178_terminationG_0.smt2                                              |   9.658s  |   9.658s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23179_terminationG_0.smt2                                              |   7.763s  |   7.763s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23180_terminationG_0.smt2                                              |  51.131s  |  51.131s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23183_terminationG_0.smt2                                              |   2.311s  |   2.311s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23184_terminationG_0.smt2                                              |   1.548s  |   1.548s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23185_terminationG_0.smt2                                              |   1.369s  |   1.369s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23188_terminationG_0.smt2                                              |   7.460s  |   7.460s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23189_terminationG_0.smt2                                              |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23190_terminationG_0.smt2                                              |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23200_terminationG_0.smt2                                              |   0.925s  |   0.925s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23201_terminationG_0.smt2                                              |   7.151s  |   7.151s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23202_terminationG_0.smt2                                              |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23206_terminationG_0.smt2                                              |   1.032s  |   1.032s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23207_terminationG_0.smt2                                              |  59.673s  |  59.673s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23210_terminationG_0.smt2                                              |   2.352s  |   2.352s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23211_terminationG_0.smt2                                              |  59.911s  |  59.911s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23212_terminationG_0.smt2                                              |  59.835s  |  59.835s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23215_edge_closing_0.smt2                                              |   1.814s  |   1.814s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23216_edge_closing_0.smt2                                              |  59.925s  |  59.925s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23222_edge_closing_0.smt2                                              |  18.341s  |  18.341s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23223_edge_closing_0.smt2                                              |  59.262s  |  59.262s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_0_0.smt2                                                   |   2.067s  |   2.067s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_1_0.smt2                                                   |   2.211s  |   2.211s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   2.350s  |   2.350s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_8_0.smt2                                                   |   2.467s  |   2.467s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23102_terminationG_0.smt2                                             |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23106_terminationG_0.smt2                                             |   0.701s  |   0.701s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23107_terminationG_0.smt2                                             |   0.636s  |   0.636s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23110_terminationG_0.smt2                                             |   2.461s  |   2.461s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23111_terminationG_0.smt2                                             |  18.948s  |  18.948s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23112_terminationG_0.smt2                                             |  59.428s  |  59.428s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23116_terminationG_0.smt2                                             |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23117_terminationG_0.smt2                                             |   1.358s  |   1.358s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23120_terminationG_0.smt2                                             |   2.354s  |   2.354s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23121_terminationG_0.smt2                                             |  59.733s  |  59.733s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23122_terminationG_0.smt2                                             |  59.911s  |  59.911s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23125_edge_closing_0.smt2                                             |   6.309s  |   6.309s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23126_edge_closing_0.smt2                                             |  59.927s  |  59.927s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23132_edge_closing_0.smt2                                             |   1.152s  |   1.152s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23133_edge_closing_0.smt2                                             |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23050_terminationG_0.smt2                                            |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23054_terminationG_0.smt2                                            |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23055_terminationG_0.smt2                                            |   2.574s  |   2.574s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23056_terminationG_0.smt2                                            |  59.933s  |  59.933s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23059_terminationG_0.smt2                                            |   1.528s  |   1.528s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23060_terminationG_0.smt2                                            |   2.321s  |   2.321s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23061_terminationG_0.smt2                                            |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23064_terminationG_0.smt2                                            |   1.170s  |   1.170s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23065_terminationG_0.smt2                                            |   2.362s  |   2.362s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23066_terminationG_0.smt2                                            |  59.918s  |  59.918s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23069_terminationG_0.smt2                                            |   1.470s  |   1.470s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23070_terminationG_0.smt2                                            |  14.834s  |  14.834s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23071_terminationG_0.smt2                                            |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23074_terminationG_0.smt2                                            |   2.861s  |   2.861s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23075_terminationG_0.smt2                                            |  22.198s  |  22.198s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23076_terminationG_0.smt2                                            |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23080_edge_closing_0.smt2                                            |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23084_edge_closing_0.smt2                                            |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|Stroeder_15__Gothenburg_true-termination.c__p23242_terminationG_0.smt2                      |   2.294s  |   2.294s  |   0.000s  | 0.0%|
|Stroeder_15__Gothenburg_true-termination.c__p23243_terminationG_0.smt2                      |  15.193s  |  15.193s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23267_terminationG_0.smt2  |   2.380s  |   2.380s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23268_terminationG_0.smt2  |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23269_terminationG_0.smt2  |  59.895s  |  59.895s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23272_terminationG_0.smt2  |   2.286s  |   2.286s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23273_terminationG_0.smt2  |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23274_terminationG_0.smt2  |  59.894s  |  59.894s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23277_edge_closing_0.smt2  |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23278_edge_closing_0.smt2  |   0.976s  |   0.976s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23280_edge_closing_0.smt2  |   1.264s  |   1.264s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23281_edge_closing_0.smt2  |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23282_edge_closing_0.smt2  |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23283_edge_closing_0.smt2  |   2.281s  |   2.281s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23284_edge_closing_0.smt2  |   1.396s  |   1.396s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23285_edge_closing_0.smt2  |   0.630s  |   0.630s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23288_edge_closing_0.smt2  |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23291_edge_closing_0.smt2  |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23309_edge_closing_0.smt2  |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23310_edge_closing_0.smt2  |  59.806s  |  59.806s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23319_edge_closing_0.smt2  |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23321_edge_closing_0.smt2  |  59.591s  |  59.591s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23322_edge_closing_0.smt2  |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23328_edge_closing_0.smt2  |   1.328s  |   1.328s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23330_edge_closing_0.smt2  |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23331_edge_closing_0.smt2  |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23333_edge_closing_0.smt2  |  59.906s  |  59.906s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23334_edge_closing_0.smt2  |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23336_edge_closing_0.smt2  |   1.050s  |   1.050s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23339_edge_closing_0.smt2  |  59.880s  |  59.880s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23340_edge_closing_0.smt2  |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23343_edge_closing_0.smt2  |  10.777s  |  10.777s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23345_edge_closing_0.smt2  |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23346_edge_closing_0.smt2  |   6.110s  |   6.110s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23348_edge_closing_0.smt2  |  34.420s  |  34.420s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23349_edge_closing_0.smt2  |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23354_edge_closing_0.smt2  |   1.105s  |   1.105s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23367_edge_closing_0.smt2  |   1.239s  |   1.239s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23403_edge_closing_0.smt2  |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23406_edge_closing_0.smt2  |   0.790s  |   0.790s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23408_edge_closing_0.smt2  |  26.301s  |  26.301s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23409_edge_closing_0.smt2  |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23412_edge_closing_0.smt2  |   1.656s  |   1.656s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23421_edge_closing_0.smt2  |   0.806s  |   0.806s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23429_edge_closing_0.smt2  |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23430_edge_closing_0.smt2  |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23431_edge_closing_0.smt2  |   1.542s  |   1.542s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23432_edge_closing_0.smt2  |   9.399s  |   9.399s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23433_edge_closing_0.smt2  |  59.903s  |  59.903s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23435_edge_closing_0.smt2  |  20.889s  |  20.889s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23436_edge_closing_0.smt2  |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23438_edge_closing_0.smt2  |   6.090s  |   6.090s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23439_edge_closing_0.smt2  |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23441_edge_closing_0.smt2  |   1.390s  |   1.390s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23442_edge_closing_0.smt2  |  59.904s  |  59.904s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23443_edge_closing_0.smt2  |   1.985s  |   1.985s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23444_edge_closing_0.smt2  |  15.806s  |  15.806s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23445_edge_closing_0.smt2  |  59.933s  |  59.933s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23447_edge_closing_0.smt2  |   2.215s  |   2.215s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23448_edge_closing_0.smt2  |   2.382s  |   2.382s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23450_edge_closing_0.smt2  |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23451_edge_closing_0.smt2  |   8.107s  |   8.107s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23459_edge_closing_0.smt2  |   1.727s  |   1.727s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23460_edge_closing_0.smt2  |   1.412s  |   1.412s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23471_edge_closing_0.smt2  |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |   1.449s  |   1.449s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23473_edge_closing_0.smt2  |   1.192s  |   1.192s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23474_edge_closing_0.smt2  |  59.893s  |  59.893s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23475_edge_closing_0.smt2  |  59.827s  |  59.827s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23477_edge_closing_0.smt2  |   0.980s  |   0.980s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23478_edge_closing_0.smt2  |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23480_edge_closing_0.smt2  |   2.484s  |   2.484s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23482_edge_closing_0.smt2  |   1.392s  |   1.392s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23483_edge_closing_0.smt2  |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23484_edge_closing_0.smt2  |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23486_edge_closing_0.smt2  |   1.569s  |   1.569s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23487_edge_closing_0.smt2  |   6.137s  |   6.137s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23493_edge_closing_0.smt2  |  59.813s  |  59.813s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23501_edge_closing_0.smt2  |   0.627s  |   0.627s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23502_edge_closing_0.smt2  |   0.575s  |   0.575s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23510_edge_closing_0.smt2  |   0.776s  |   0.776s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23522_edge_closing_0.smt2  |   0.958s  |   0.958s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23523_edge_closing_0.smt2  |   6.554s  |   6.554s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23531_edge_closing_0.smt2  |   5.758s  |   5.758s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23532_edge_closing_0.smt2  |   1.571s  |   1.571s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23543_edge_closing_0.smt2  |   1.121s  |   1.121s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23544_edge_closing_0.smt2  |   0.702s  |   0.702s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23550_edge_closing_0.smt2  |   0.731s  |   0.731s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23551_edge_closing_0.smt2  |   5.433s  |   5.433s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23559_edge_closing_0.smt2  |  14.441s  |  14.441s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23560_edge_closing_0.smt2  |   5.685s  |   5.685s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23565_edge_closing_0.smt2  |   1.915s  |   1.915s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23566_edge_closing_0.smt2  |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23577_edge_closing_0.smt2  |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23602_edge_closing_0.smt2  |   0.723s  |   0.723s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23611_edge_closing_0.smt2  |   0.654s  |   0.654s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23616_edge_closing_0.smt2  |  27.285s  |  27.285s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23617_edge_closing_0.smt2  |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23620_edge_closing_0.smt2  |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23628_edge_closing_0.smt2  |   0.724s  |   0.724s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23629_edge_closing_0.smt2  |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23638_edge_closing_0.smt2  |   1.246s  |   1.246s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23646_edge_closing_0.smt2  |   0.568s  |   0.568s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23647_edge_closing_0.smt2  |   1.075s  |   1.075s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23649_edge_closing_0.smt2  |  59.917s  |  59.917s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23650_edge_closing_0.smt2  |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23653_edge_closing_0.smt2  |   0.671s  |   0.671s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23662_edge_closing_0.smt2  |   1.475s  |   1.475s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23667_edge_closing_0.smt2  |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23673_edge_closing_0.smt2  |   1.170s  |   1.170s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23676_edge_closing_0.smt2  |  59.696s  |  59.696s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23677_edge_closing_0.smt2  |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23679_edge_closing_0.smt2  |   5.507s  |   5.507s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23680_edge_closing_0.smt2  |   5.343s  |   5.343s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23686_edge_closing_0.smt2  |   1.683s  |   1.683s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23692_edge_closing_0.smt2  |   1.515s  |   1.515s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23693_edge_closing_0.smt2  |   1.964s  |   1.964s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23699_edge_closing_0.smt2  |   1.723s  |   1.723s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23701_edge_closing_0.smt2  |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23702_edge_closing_0.smt2  |  51.224s  |  51.224s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23703_edge_closing_0.smt2  |   2.142s  |   2.142s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23704_edge_closing_0.smt2  |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23705_edge_closing_0.smt2  |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23707_edge_closing_0.smt2  |   2.228s  |   2.228s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23708_edge_closing_0.smt2  |   2.414s  |   2.414s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23710_edge_closing_0.smt2  |   0.714s  |   0.714s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23711_edge_closing_0.smt2  |   5.476s  |   5.476s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23713_edge_closing_0.smt2  |   1.496s  |   1.496s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23714_edge_closing_0.smt2  |  22.471s  |  22.471s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23715_edge_closing_0.smt2  |   2.267s  |   2.267s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23716_edge_closing_0.smt2  |   6.115s  |   6.115s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23717_edge_closing_0.smt2  |  13.027s  |  13.027s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23719_edge_closing_0.smt2  |  59.918s  |  59.918s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23720_edge_closing_0.smt2  |  59.724s  |  59.724s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23722_edge_closing_0.smt2  |   0.978s  |   0.978s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23723_edge_closing_0.smt2  |   0.721s  |   0.721s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23731_edge_closing_0.smt2  |  59.804s  |  59.804s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23732_edge_closing_0.smt2  |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23734_edge_closing_0.smt2  |   0.822s  |   0.822s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23735_edge_closing_0.smt2  |   1.094s  |   1.094s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23750_edge_closing_0.smt2  |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23751_edge_closing_0.smt2  |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23752_edge_closing_0.smt2  |   1.458s  |   1.458s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23753_edge_closing_0.smt2  |  59.890s  |  59.890s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23754_edge_closing_0.smt2  |  59.906s  |  59.906s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23756_edge_closing_0.smt2  |   1.458s  |   1.458s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   5.974s  |   5.974s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23759_edge_closing_0.smt2  |   0.622s  |   0.622s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23760_edge_closing_0.smt2  |   0.499s  |   0.499s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23765_edge_closing_0.smt2  |   5.978s  |   5.978s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23766_edge_closing_0.smt2  |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23774_edge_closing_0.smt2  |   6.829s  |   6.829s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23775_edge_closing_0.smt2  |   9.412s  |   9.412s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23795_edge_closing_0.smt2  |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23796_edge_closing_0.smt2  |  59.835s  |  59.835s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23853_terminationG_0.smt2  |   7.355s  |   7.355s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23856_terminationG_0.smt2  |   3.012s  |   3.012s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23857_terminationG_0.smt2  |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23858_terminationG_0.smt2  |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23863_terminationG_0.smt2  |   3.189s  |   3.189s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23864_terminationG_0.smt2  |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23872_terminationG_0.smt2  |  53.184s  |  53.184s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23873_terminationG_0.smt2  |  24.829s  |  24.829s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23877_terminationG_0.smt2  |   1.830s  |   1.830s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23878_terminationG_0.smt2  |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23886_terminationG_0.smt2  |   2.528s  |   2.528s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23887_terminationG_0.smt2  |   2.418s  |   2.418s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23893_terminationG_0.smt2  |   3.494s  |   3.494s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23894_terminationG_0.smt2  |  59.819s  |  59.819s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23905_terminationG_0.smt2                                              |   5.738s  |   5.738s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23906_terminationG_0.smt2                                              |   1.183s  |   1.183s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23910_terminationG_0.smt2                                              |   1.562s  |   1.562s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23911_terminationG_0.smt2                                              |   0.901s  |   0.901s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23918_terminationG_0.smt2                                              |   8.071s  |   8.071s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23923_terminationG_0.smt2                                              |   0.933s  |   0.933s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23927_terminationG_0.smt2                                              |   6.451s  |   6.451s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23933_terminationG_0.smt2                                              |   1.034s  |   1.034s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23941_terminationG_0.smt2                                              |   0.925s  |   0.925s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23942_terminationG_0.smt2                                              |  47.369s  |  47.369s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23947_terminationG_0.smt2                                              |   8.704s  |   8.704s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23951_terminationG_0.smt2                                              |  59.868s  |  59.868s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23952_terminationG_0.smt2                                              |  59.932s  |  59.932s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23956_edge_closing_0.smt2                                              |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23960_edge_closing_0.smt2                                              |   5.635s  |   5.635s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-TACAS2014-Ex7_true-termination.c__p23983_terminationG_0.smt2     |   1.322s  |   1.322s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-TACAS2014-Fig1_true-termination.c__p24009_terminationG_0.smt2    |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24028_terminationG_0.smt2      |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24029_terminationG_0.smt2      |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24032_terminationG_0.smt2      |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24033_terminationG_0.smt2      |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24034_terminationG_0.smt2      |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24038_terminationG_0.smt2      |   0.736s  |   0.736s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24039_terminationG_0.smt2      |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24042_terminationG_0.smt2      |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24043_terminationG_0.smt2      |  59.916s  |  59.916s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24044_terminationG_0.smt2      |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24047_terminationG_0.smt2      |   0.951s  |   0.951s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24048_terminationG_0.smt2      |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24049_terminationG_0.smt2      |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24052_edge_closing_0.smt2      |   2.115s  |   2.115s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24053_edge_closing_0.smt2      |   0.937s  |   0.937s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24057_edge_closing_0.smt2      |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24084_terminationG_0.smt2      |   8.255s  |   8.255s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24085_terminationG_0.smt2      |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24086_terminationG_0.smt2      |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   1.981s  |   1.981s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24090_terminationG_0.smt2      |  59.887s  |  59.887s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24091_terminationG_0.smt2      |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24094_terminationG_0.smt2      |   2.770s  |   2.770s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24095_terminationG_0.smt2      |  59.822s  |  59.822s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24096_terminationG_0.smt2      |  59.879s  |  59.879s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24099_terminationG_0.smt2      |   2.782s  |   2.782s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24100_terminationG_0.smt2      |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24101_terminationG_0.smt2      |  59.855s  |  59.855s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   0.593s  |   0.593s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24121_terminationG_0.smt2        |   1.817s  |   1.817s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.866s  |   0.866s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24142_terminationG_0.smt2                                          |  59.933s  |  59.933s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24143_terminationG_0.smt2                                          |  59.899s  |  59.899s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24146_terminationG_0.smt2                                          |   2.703s  |   2.703s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24147_terminationG_0.smt2                                          |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24148_terminationG_0.smt2                                          |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24151_terminationG_0.smt2                                          |   2.752s  |   2.752s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24152_terminationG_0.smt2                                          |   2.434s  |   2.434s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24153_terminationG_0.smt2                                          |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24156_terminationG_0.smt2                                          |   2.834s  |   2.834s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24157_terminationG_0.smt2                                          |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24158_terminationG_0.smt2                                          |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__terminationQ_3_0.smt2                                               |   2.352s  |   2.352s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24190_terminationG_0.smt2                                          |   2.135s  |   2.135s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24191_terminationG_0.smt2                                          |  59.958s  |  59.958s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24194_terminationG_0.smt2                                          |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24195_terminationG_0.smt2                                          |   2.383s  |   2.383s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24196_terminationG_0.smt2                                          |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24211_terminationG_0.smt2                                          |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24212_terminationG_0.smt2                                          |   2.105s  |   2.105s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24213_terminationG_0.smt2                                          |   2.636s  |   2.636s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24216_terminationG_0.smt2                                          |   0.569s  |   0.569s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24217_terminationG_0.smt2                                          |   2.392s  |   2.392s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24218_terminationG_0.smt2                                          |   3.575s  |   3.575s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24236_terminationG_0.smt2           |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24237_terminationG_0.smt2           |   0.973s  |   0.973s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24238_terminationG_0.smt2           |   1.283s  |   1.283s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24241_terminationG_0.smt2           |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24242_terminationG_0.smt2           |   0.853s  |   0.853s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   2.261s  |   2.261s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24247_terminationG_0.smt2           |   2.757s  |   2.757s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24248_terminationG_0.smt2           |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24250_edge_closing_0.smt2           |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |  59.896s  |  59.896s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24252_edge_closing_0.smt2           |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|Stroeder_15__McCarthyIterative.c__term_unfeasibility_0_0.smt2                               |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|Stroeder_15__MenloPark_true-termination.c__p24273_terminationG_0.smt2                       |   1.119s  |   1.119s  |   0.000s  | 0.0%|
|Stroeder_15__MenloPark_true-termination.c__p24274_terminationG_0.smt2                       |   0.946s  |   0.946s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24281_terminationG_0.smt2                                           |   2.093s  |   2.093s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24282_terminationG_0.smt2                                           |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24283_terminationG_0.smt2                                           |   1.396s  |   1.396s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24288_terminationG_0.smt2                                           |   0.938s  |   0.938s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24289_terminationG_0.smt2                                           |   2.859s  |   2.859s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24290_terminationG_0.smt2                                           |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24301_terminationG_0.smt2                                           |   0.644s  |   0.644s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24306_terminationG_0.smt2                                           |   1.689s  |   1.689s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24309_terminationG_0.smt2                                           |   2.103s  |   2.103s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24310_terminationG_0.smt2                                           |   2.219s  |   2.219s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24311_terminationG_0.smt2                                           |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24314_terminationG_0.smt2                                           |   2.666s  |   2.666s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24315_terminationG_0.smt2                                           |   2.333s  |   2.333s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24316_terminationG_0.smt2                                           |   3.772s  |   3.772s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24319_terminationG_0.smt2                                           |   2.699s  |   2.699s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24320_terminationG_0.smt2                                           |   2.354s  |   2.354s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24321_terminationG_0.smt2                                           |  59.717s  |  59.717s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24324_terminationG_0.smt2                                           |   2.775s  |   2.775s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24325_terminationG_0.smt2                                           |   2.401s  |   2.401s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24326_terminationG_0.smt2                                           |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24329_terminationG_0.smt2                                           |   2.799s  |   2.799s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24330_terminationG_0.smt2                                           |   2.324s  |   2.324s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24331_terminationG_0.smt2                                           |  59.919s  |  59.919s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24334_terminationG_0.smt2                                           |   2.374s  |   2.374s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24335_terminationG_0.smt2                                           |   2.434s  |   2.434s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24336_terminationG_0.smt2                                           |  59.919s  |  59.919s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24339_edge_closing_0.smt2                                           |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24344_edge_closing_0.smt2                                           |   0.594s  |   0.594s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24368_terminationG_0.smt2                                     |   0.454s  |   0.454s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24373_terminationG_0.smt2                                     |   2.310s  |   2.310s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24374_terminationG_0.smt2                                     |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24377_terminationG_0.smt2                                     |   2.830s  |   2.830s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24378_terminationG_0.smt2                                     |   6.426s  |   6.426s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24379_terminationG_0.smt2                                     |   7.022s  |   7.022s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24382_terminationG_0.smt2                                     |   1.838s  |   1.838s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24383_terminationG_0.smt2                                     |   2.431s  |   2.431s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24384_terminationG_0.smt2                                     |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24387_terminationG_0.smt2                                     |   1.663s  |   1.663s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24388_terminationG_0.smt2                                     |   2.441s  |   2.441s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24389_terminationG_0.smt2                                     |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24392_terminationG_0.smt2                                     |   1.505s  |   1.505s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24393_terminationG_0.smt2                                     |  59.891s  |  59.891s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24394_terminationG_0.smt2                                     |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24397_terminationG_0.smt2                                     |   2.253s  |   2.253s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24398_terminationG_0.smt2                                     |   2.587s  |   2.587s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24399_terminationG_0.smt2                                     |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24402_terminationG_0.smt2                                     |   1.532s  |   1.532s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24403_terminationG_0.smt2                                     |  59.918s  |  59.918s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24404_terminationG_0.smt2                                     |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24407_terminationG_0.smt2                                     |   2.408s  |   2.408s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24408_terminationG_0.smt2                                     |   2.507s  |   2.507s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24409_terminationG_0.smt2                                     |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24413_edge_closing_0.smt2                                     |   6.836s  |   6.836s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24415_edge_closing_0.smt2                                     |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24422_edge_closing_0.smt2                                     |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |   9.461s  |   9.461s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24426_edge_closing_0.smt2                                     |   0.712s  |   0.712s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24432_edge_closing_0.smt2                                     |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24443_edge_closing_0.smt2                                     |   0.590s  |   0.590s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24446_edge_closing_0.smt2                                     |   1.072s  |   1.072s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24447_edge_closing_0.smt2                                     |   1.813s  |   1.813s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24449_edge_closing_0.smt2                                     |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24450_edge_closing_0.smt2                                     |  60.086s  |  60.086s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__terminationQ_5_0.smt2                                          |   2.314s  |   2.314s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__terminationS_0_0.smt2                                          |   0.847s  |   0.847s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__terminationS_1_0.smt2                                          |   2.238s  |   2.238s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24464_terminationG_0.smt2                                  |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24482_terminationG_0.smt2                                  |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24484_terminationG_0.smt2                                  |  59.885s  |  59.885s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationQ_0_0.smt2                                       |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_1_0.smt2                                       |   3.119s  |   3.119s  |   0.000s  | 0.0%|
|Stroeder_15__NO_03.c__p24634_terminationG_0.smt2                                            |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|Stroeder_15__NO_03.c__terminationQ_0_0.smt2                                                 |   0.911s  |   0.911s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24648_safety_0.smt2                                                  |   1.712s  |   1.712s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24649_safety_0.smt2                                                  |   1.875s  |   1.875s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24650_safety_0.smt2                                                  |  59.862s  |  59.862s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24651_safety_0.smt2                                                  |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24653_safety_0.smt2                                                  |  59.906s  |  59.906s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24654_safety_0.smt2                                                  |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__term_unfeasibility_0_0.smt2                                           |   2.434s  |   2.434s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__term_unfeasibility_2_0.smt2                                           |   2.431s  |   2.431s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__term_unfeasibility_4_0.smt2                                           |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24669_terminationG_0.smt2                                            |   1.644s  |   1.644s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   2.674s  |   2.674s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24671_terminationG_0.smt2                                            |  59.893s  |  59.893s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24674_terminationG_0.smt2                                            |   1.717s  |   1.717s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24675_terminationG_0.smt2                                            |   2.452s  |   2.452s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24676_terminationG_0.smt2                                            |  59.778s  |  59.778s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24679_terminationG_0.smt2                                            |   2.348s  |   2.348s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24680_terminationG_0.smt2                                            |   2.360s  |   2.360s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24681_terminationG_0.smt2                                            |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24684_terminationG_0.smt2                                            |   1.860s  |   1.860s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24685_terminationG_0.smt2                                            |   2.310s  |   2.310s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24686_terminationG_0.smt2                                            |  59.931s  |  59.931s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24689_terminationG_0.smt2                                            |   2.272s  |   2.272s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24690_terminationG_0.smt2                                            |   2.326s  |   2.326s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24691_terminationG_0.smt2                                            |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24694_terminationG_0.smt2                                            |   1.888s  |   1.888s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24695_terminationG_0.smt2                                            |   2.375s  |   2.375s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24696_terminationG_0.smt2                                            |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__terminationQ_5_0.smt2                                                 |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24711_terminationG_0.smt2                                            |   2.072s  |   2.072s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  59.906s  |  59.906s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24713_terminationG_0.smt2                                            |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24716_terminationG_0.smt2                                            |   2.378s  |   2.378s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24717_terminationG_0.smt2                                            |  59.804s  |  59.804s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24718_terminationG_0.smt2                                            |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24721_terminationG_0.smt2                                            |   1.862s  |   1.862s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24722_terminationG_0.smt2                                            |  59.887s  |  59.887s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24723_terminationG_0.smt2                                            |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24726_terminationG_0.smt2                                            |   2.323s  |   2.323s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |   2.757s  |   2.757s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24728_terminationG_0.smt2                                            |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24730_terminationG_0.smt2                                            |   2.260s  |   2.260s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24732_terminationG_0.smt2                                            |  51.689s  |  51.689s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24733_terminationG_0.smt2                                            |  59.784s  |  59.784s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24737_edge_closing_0.smt2                                            |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationQ_4_0.smt2                                                 |   2.276s  |   2.276s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   2.332s  |   2.332s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_1_0.smt2                                                 |   2.318s  |   2.318s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24748_terminationG_0.smt2                                            |   1.435s  |   1.435s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |  59.880s  |  59.880s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24750_terminationG_0.smt2                                            |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24752_edge_closing_0.smt2                                            |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__term_unfeasibility_0_0.smt2                                           |   0.430s  |   0.430s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__terminationQ_0_0.smt2                                                 |   2.313s  |   2.313s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__terminationS_0_0.smt2                                                 |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__terminationS_1_0.smt2                                                 |   0.822s  |   0.822s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24780_terminationG_0.smt2                                            |   1.234s  |   1.234s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24781_terminationG_0.smt2                                            |   2.688s  |   2.688s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24782_terminationG_0.smt2                                            |   2.951s  |   2.951s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24785_edge_closing_0.smt2                                            |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24786_edge_closing_0.smt2                                            |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__term_unfeasibility_0_0.smt2                                           |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__terminationS_0_0.smt2                                                 |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24797_terminationG_0.smt2                                            |   1.285s  |   1.285s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24798_terminationG_0.smt2                                            |  24.618s  |  24.618s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24799_terminationG_0.smt2                                            |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24804_edge_closing_0.smt2                                            |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__term_unfeasibility_0_0.smt2                                           |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__terminationQ_0_0.smt2                                                 |   0.873s  |   0.873s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__terminationS_0_0.smt2                                                 |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__terminationS_1_0.smt2                                                 |   0.686s  |   0.686s  |   0.000s  | 0.0%|
|Stroeder_15__NO_24.c__p24815_terminationG_0.smt2                                            |  16.401s  |  16.401s  |   0.000s  | 0.0%|
|Stroeder_15__NO_24.c__p24816_terminationG_0.smt2                                            |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|Stroeder_15__NO_24.c__p24820_edge_closing_0.smt2                                            |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|Stroeder_15__NarrowKonv.c__p24579_edge_closing_0.smt2                                       |   0.618s  |   0.618s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24515_terminationG_0.smt2                                        |   0.558s  |   0.558s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24516_terminationG_0.smt2                                        |   0.601s  |   0.601s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24519_terminationG_0.smt2                                        |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24520_terminationG_0.smt2                                        |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24521_terminationG_0.smt2                                        |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24524_terminationG_0.smt2                                        |   1.406s  |   1.406s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24525_terminationG_0.smt2                                        |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24526_terminationG_0.smt2                                        |   0.784s  |   0.784s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24529_terminationG_0.smt2                                        |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24530_terminationG_0.smt2                                        |   0.532s  |   0.532s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24531_terminationG_0.smt2                                        |   0.876s  |   0.876s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24534_terminationG_0.smt2                                        |  17.587s  |  17.587s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24535_terminationG_0.smt2                                        |  59.712s  |  59.712s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24536_terminationG_0.smt2                                        |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24539_terminationG_0.smt2                                        |  12.850s  |  12.850s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24540_terminationG_0.smt2                                        |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24541_terminationG_0.smt2                                        |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24544_edge_closing_0.smt2                                        |  10.611s  |  10.611s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24545_edge_closing_0.smt2                                        |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24547_edge_closing_0.smt2                                        |   1.696s  |   1.696s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24548_edge_closing_0.smt2                                        |   1.703s  |   1.703s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24549_edge_closing_0.smt2                                        |  27.862s  |  27.862s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24551_edge_closing_0.smt2                                        |  23.084s  |  23.084s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24552_edge_closing_0.smt2                                        |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__term_unfeasibility_2_0.smt2                                       |   2.596s  |   2.596s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationQ_0_0.smt2                                             |  10.924s  |  10.924s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_0_0.smt2                                             |   6.325s  |   6.325s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_1_0.smt2                                             |   7.340s  |   7.340s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_2_0.smt2                                             |   3.194s  |   3.194s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_3_0.smt2                                             |   7.292s  |   7.292s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24837_terminationG_0.smt2                |   2.136s  |   2.136s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24838_terminationG_0.smt2                |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24841_terminationG_0.smt2                |   1.444s  |   1.444s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   3.466s  |   3.466s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24843_terminationG_0.smt2                |  59.911s  |  59.911s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24848_edge_closing_0.smt2                |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24888_terminationG_0.smt2                |   1.359s  |   1.359s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24896_terminationG_0.smt2                |   2.511s  |   2.511s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24897_terminationG_0.smt2                |   3.084s  |   3.084s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24907_terminationG_0.smt2                |   2.543s  |   2.543s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24908_terminationG_0.smt2                |  15.966s  |  15.966s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24918_terminationG_0.smt2                |   2.991s  |   2.991s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24919_terminationG_0.smt2                |  40.611s  |  40.611s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24923_terminationG_0.smt2                |   2.473s  |   2.473s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24924_terminationG_0.smt2                |  21.966s  |  21.966s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |   6.717s  |   6.717s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24932_edge_closing_0.smt2                |   1.233s  |   1.233s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24935_edge_closing_0.smt2                |   1.537s  |   1.537s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24937_edge_closing_0.smt2                |   0.698s  |   0.698s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24938_edge_closing_0.smt2                |   5.661s  |   5.661s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24939_edge_closing_0.smt2                |  60.137s  |  60.137s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                |  59.863s  |  59.863s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24941_edge_closing_0.smt2                |  59.897s  |  59.897s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24949_terminationG_0.smt2                |  59.861s  |  59.861s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24950_terminationG_0.smt2                |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24953_terminationG_0.smt2                |   0.761s  |   0.761s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24954_terminationG_0.smt2                |  59.789s  |  59.789s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                |  59.899s  |  59.899s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24957_terminationG_0.smt2                |   1.968s  |   1.968s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24959_terminationG_0.smt2                |  59.879s  |  59.879s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24960_terminationG_0.smt2                |  59.720s  |  59.720s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24967_terminationG_0.smt2                |   2.330s  |   2.330s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24969_terminationG_0.smt2                |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24970_terminationG_0.smt2                |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24973_terminationG_0.smt2                |   2.837s  |   2.837s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24974_terminationG_0.smt2                |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24975_terminationG_0.smt2                |  59.901s  |  59.901s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24982_edge_closing_0.smt2                |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24983_edge_closing_0.smt2                |   5.555s  |   5.555s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__terminationQ_4_0.smt2                     |   2.059s  |   2.059s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p24995_terminationG_0.smt2          |   0.360s  |   0.360s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p24996_terminationG_0.smt2          |   1.313s  |   1.313s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p24997_terminationG_0.smt2          |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p25000_terminationG_0.smt2          |   0.671s  |   0.671s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p25001_terminationG_0.smt2          |   2.415s  |   2.415s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p25002_terminationG_0.smt2          |  59.922s  |  59.922s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple3_false-termination.c__p25033_terminationG_0.smt2          |   2.189s  |   2.189s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple3_false-termination.c__p25034_terminationG_0.smt2          |  59.887s  |  59.887s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25060_terminationG_0.smt2          |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25061_terminationG_0.smt2          |   2.154s  |   2.154s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25062_terminationG_0.smt2          |  59.804s  |  59.804s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25065_terminationG_0.smt2          |   1.023s  |   1.023s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25066_terminationG_0.smt2          |   2.402s  |   2.402s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25067_terminationG_0.smt2          |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25070_terminationG_0.smt2          |   0.894s  |   0.894s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25071_terminationG_0.smt2          |   2.551s  |   2.551s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25072_terminationG_0.smt2          |  59.801s  |  59.801s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25075_terminationG_0.smt2          |   1.461s  |   1.461s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25076_terminationG_0.smt2          |   2.497s  |   2.497s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25077_terminationG_0.smt2          |   4.377s  |   4.377s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25081_edge_closing_0.smt2          |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__terminationQ_3_0.smt2               |   0.689s  |   0.689s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple5_false-termination.c__p25094_terminationG_0.smt2          |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple5_false-termination.c__p25098_terminationG_0.smt2          |   2.488s  |   2.488s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple5_false-termination.c__p25099_terminationG_0.smt2          |   2.571s  |   2.571s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25119_terminationG_0.smt2          |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25120_terminationG_0.smt2          |   1.884s  |   1.884s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          |  59.925s  |  59.925s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25124_terminationG_0.smt2          |   0.847s  |   0.847s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25125_terminationG_0.smt2          |   2.347s  |   2.347s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25126_terminationG_0.smt2          |  59.781s  |  59.781s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25130_edge_closing_0.smt2          |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple7_false-termination.c__p25147_terminationG_0.smt2          |   1.763s  |   1.763s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple7_false-termination.c__p25148_terminationG_0.smt2          |  59.904s  |  59.904s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple7_false-termination.c__p25159_edge_closing_0.smt2          |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25174_terminationG_0.smt2          |   1.657s  |   1.657s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25175_terminationG_0.smt2          |   2.533s  |   2.533s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25176_terminationG_0.smt2          |   3.807s  |   3.807s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25179_terminationG_0.smt2          |   2.576s  |   2.576s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25180_terminationG_0.smt2          |   2.379s  |   2.379s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25181_terminationG_0.smt2          |   2.683s  |   2.683s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25184_edge_closing_0.smt2          |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25189_edge_closing_0.smt2          |   0.520s  |   0.520s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25202_terminationG_0.smt2          |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   2.138s  |   2.138s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   7.054s  |   7.054s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25336_terminationG_0.smt2                                         |  59.932s  |  59.932s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25382_terminationG_0.smt2                                         |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25387_terminationG_0.smt2                                         |   0.555s  |   0.555s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25391_terminationG_0.smt2                                         |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25392_terminationG_0.smt2                                         |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig1_true-termination.c__p25400_terminationG_0.smt2  |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25419_terminationG_0.smt2  |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25424_terminationG_0.smt2  |   2.537s  |   2.537s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25425_terminationG_0.smt2  |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25430_terminationG_0.smt2  |  16.827s  |  16.827s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25433_terminationG_0.smt2  |   2.305s  |   2.305s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25434_terminationG_0.smt2  |  15.377s  |  15.377s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25435_terminationG_0.smt2  |  59.872s  |  59.872s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25440_terminationG_0.smt2  |   1.132s  |   1.132s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25441_terminationG_0.smt2  |  42.193s  |  42.193s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25442_terminationG_0.smt2  |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25447_terminationG_0.smt2  |   3.544s  |   3.544s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25448_terminationG_0.smt2  |  15.439s  |  15.439s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25449_terminationG_0.smt2  |  59.909s  |  59.909s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25476_terminationG_0.smt2  |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25479_terminationG_0.smt2  |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25480_terminationG_0.smt2  |   1.527s  |   1.527s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25481_terminationG_0.smt2  |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25484_edge_closing_0.smt2  |   1.164s  |   1.164s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25485_edge_closing_0.smt2  |  59.928s  |  59.928s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25505_terminationG_0.smt2                      |   0.976s  |   0.976s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25506_terminationG_0.smt2                      |   2.438s  |   2.438s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25507_terminationG_0.smt2                      |  59.695s  |  59.695s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |  11.819s  |  11.819s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25519_terminationG_0.smt2                      |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25530_terminationG_0.smt2                      |  12.285s  |  12.285s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25531_terminationG_0.smt2                      |  60.294s  |  60.294s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25532_terminationG_0.smt2                      |  59.889s  |  59.889s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25536_terminationG_0.smt2                      |  32.552s  |  32.552s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25537_terminationG_0.smt2                      |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25541_terminationG_0.smt2                      |  10.087s  |  10.087s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25542_terminationG_0.smt2                      |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25546_terminationG_0.smt2                      |   1.220s  |   1.220s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25547_terminationG_0.smt2                      |   7.951s  |   7.951s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25559_terminationG_0.smt2                      |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25560_terminationG_0.smt2                      |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25566_terminationG_0.smt2                      |  59.810s  |  59.810s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25567_terminationG_0.smt2                      |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Stroeder_15__Rotation180_false-termination.c__p25579_terminationG_0.smt2                    |   6.111s  |   6.111s  |   0.000s  | 0.0%|
|Stroeder_15__Rotation180_false-termination.c__p25580_terminationG_0.smt2                    |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25604_terminationG_0.smt2                                           |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25608_terminationG_0.smt2                                           |   1.137s  |   1.137s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25609_terminationG_0.smt2                                           |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25619_terminationG_0.smt2                                           |   2.357s  |   2.357s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25622_terminationG_0.smt2                                           |   7.651s  |   7.651s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25624_terminationG_0.smt2                                           |  59.903s  |  59.903s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25629_edge_closing_0.smt2                                           |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25637_edge_closing_0.smt2                                           |   0.613s  |   0.613s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__terminationQ_0_0.smt2                                                |   0.706s  |   0.706s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__terminationS_0_0.smt2                                                |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__terminationS_1_0.smt2                                                |  59.678s  |  59.678s  |   0.000s  | 0.0%|
|Stroeder_15__Swingers.c__p26084_terminationG_0.smt2                                         |  21.052s  |  21.052s  |   0.000s  | 0.0%|
|Stroeder_15__Swingers.c__p26085_terminationG_0.smt2                                         |  59.858s  |  59.858s  |   0.000s  | 0.0%|
|Stroeder_15__Swingers.c__p26089_edge_closing_0.smt2                                         |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-BranchesToLoop_true-termination.c__p26120_terminationG_0.smt2         |   0.425s  |   0.425s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-BranchesToLoop_true-termination.c__p26125_terminationG_0.smt2         |   1.221s  |   1.221s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-MultiBranchesToLoop_true-termination.c__p26134_terminationG_0.smt2    |   0.756s  |   0.756s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-MultiBranchesToLoop_true-termination.c__p26139_terminationG_0.smt2    |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26151_terminationG_0.smt2                                          |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26152_terminationG_0.smt2                                          |   2.165s  |   2.165s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26153_terminationG_0.smt2                                          |  59.880s  |  59.880s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26156_terminationG_0.smt2                                          |   0.678s  |   0.678s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26157_terminationG_0.smt2                                          |   1.797s  |   1.797s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26158_terminationG_0.smt2                                          |  59.894s  |  59.894s  |   0.000s  | 0.0%|
|Stroeder_15__TwoFloatInterv.c__p26170_safety_0.smt2                                         |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|Stroeder_15__TwoFloatInterv.c__p26181_edge_closing_0.smt2                                   |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26197_terminationG_0.smt2                                        |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26198_terminationG_0.smt2                                        |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        |  59.874s  |  59.874s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26203_terminationG_0.smt2                                        |  59.879s  |  59.879s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26206_edge_closing_0.smt2                                        |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26207_edge_closing_0.smt2                                        |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26213_edge_closing_0.smt2                                        |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26214_edge_closing_0.smt2                                        |   0.952s  |   0.952s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__terminationS_3_0.smt2                                             |   2.276s  |   2.276s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26230_terminationG_0.smt2                                    |   0.996s  |   0.996s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26231_terminationG_0.smt2                                    |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26235_terminationG_0.smt2                                    |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26236_terminationG_0.smt2                                    |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26239_edge_closing_0.smt2                                    |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26240_edge_closing_0.smt2                                    |   2.454s  |   2.454s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26246_edge_closing_0.smt2                                    |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26247_edge_closing_0.smt2                                    |   5.968s  |   5.968s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig1_false-termination.c__p26265_safety_0.smt2                   |   2.002s  |   2.002s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig1_false-termination.c__p26266_safety_0.smt2                   |   2.408s  |   2.408s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig2-modified1000_true-termination.c__term_unfeasibility_0_0.smt2  |   0.589s  |   0.589s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig2_true-termination.c__term_unfeasibility_0_0.smt2             |   0.498s  |   0.498s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26291_terminationG_0.smt2                       |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26301_terminationG_0.smt2                       |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26335_terminationG_0.smt2                       |  59.875s  |  59.875s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26336_terminationG_0.smt2                       |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__terminationQ_0_0.smt2                            |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__terminationS_0_0.smt2                            |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__terminationS_1_0.smt2                            |   2.455s  |   2.455s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26374_terminationG_0.smt2                                        |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26375_terminationG_0.smt2                                        |   1.679s  |   1.679s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26376_terminationG_0.smt2                                        |  59.876s  |  59.876s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26380_terminationG_0.smt2                                        |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26381_terminationG_0.smt2                                        |   1.636s  |   1.636s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26407_terminationG_0.smt2                                    |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26408_terminationG_0.smt2                                    |   2.123s  |   2.123s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26409_terminationG_0.smt2                                    |  59.861s  |  59.861s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26412_terminationG_0.smt2                                    |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26413_terminationG_0.smt2                                    |   2.363s  |   2.363s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26414_terminationG_0.smt2                                    |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26429_terminationG_0.smt2                                      |   1.120s  |   1.120s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26430_terminationG_0.smt2                                      |  39.171s  |  39.171s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26431_terminationG_0.smt2                                      |  59.925s  |  59.925s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26434_terminationG_0.smt2                                      |   1.825s  |   1.825s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26435_terminationG_0.smt2                                      |   2.463s  |   2.463s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26436_terminationG_0.smt2                                      |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__terminationQ_1_0.smt2                                           |   1.334s  |   1.334s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   2.072s  |   2.072s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26452_terminationG_0.smt2                                |  59.886s  |  59.886s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26453_terminationG_0.smt2                                |  59.921s  |  59.921s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26456_terminationG_0.smt2                                |   2.304s  |   2.304s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26457_terminationG_0.smt2                                |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                |  59.882s  |  59.882s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__terminationQ_1_0.smt2                                     |   1.074s  |   1.074s  |   0.000s  | 0.0%|
|Stroeder_15__WhilePart.c__p26472_safety_0.smt2                                              |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|Stroeder_15__WhilePart.c__p26473_safety_0.smt2                                              |   2.455s  |   2.455s  |   0.000s  | 0.0%|
|Stroeder_15__WhileSingle.c__p26489_edge_closing_0.smt2                                      |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20348_terminationG_0.smt2                          |   0.633s  |   0.633s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |   1.292s  |   1.292s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   1.044s  |   1.044s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20359_terminationG_0.smt2                          |   0.575s  |   0.575s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20363_terminationG_0.smt2                          |   9.710s  |   9.710s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20364_terminationG_0.smt2                          |  59.893s  |  59.893s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20368_terminationG_0.smt2                          |   1.001s  |   1.001s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20369_terminationG_0.smt2                          |   1.319s  |   1.319s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22217_terminationG_0.smt2                                          |  10.996s  |  10.996s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22218_terminationG_0.smt2                                          |  59.829s  |  59.829s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22219_terminationG_0.smt2                                          |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22228_edge_closing_0.smt2                                          |  11.908s  |  11.908s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22230_edge_closing_0.smt2                                          |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22231_edge_closing_0.smt2                                          |  59.764s  |  59.764s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__term_unfeasibility_1_0.smt2                                         |   1.570s  |   1.570s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__terminationQ_0_0.smt2                                               |  11.531s  |  11.531s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__terminationS_0_0.smt2                                               |   2.200s  |   2.200s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__terminationS_1_0.smt2                                               |   2.208s  |   2.208s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_a.10.c__p25674_terminationG_0.smt2                                      |   0.524s  |   0.524s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_a.10.c__p25675_terminationG_0.smt2                                      |   7.955s  |   7.955s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25769_terminationG_0.smt2                               |   0.639s  |   0.639s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01_assume.c__term_unfeasibility_0_0.smt2                              |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25801_terminationG_0.smt2                                       |   0.663s  |   0.663s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25806_terminationG_0.smt2                                       |   2.458s  |   2.458s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25815_terminationG_0.smt2                                       |   1.771s  |   1.771s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   2.528s  |   2.528s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25817_terminationG_0.smt2                                       |  59.901s  |  59.901s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25820_terminationG_0.smt2                                       |   0.395s  |   0.395s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |  41.715s  |  41.715s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25825_terminationG_0.smt2                                       |   2.686s  |   2.686s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25826_terminationG_0.smt2                                       |   4.203s  |   4.203s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25827_terminationG_0.smt2                                       |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   2.431s  |   2.431s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25832_terminationG_0.smt2                                       |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25835_terminationG_0.smt2                                       |   1.056s  |   1.056s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25836_terminationG_0.smt2                                       |   2.417s  |   2.417s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |   2.674s  |   2.674s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25843_terminationG_0.smt2                                       |  12.584s  |  12.584s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   1.029s  |   1.029s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   2.380s  |   2.380s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25848_terminationG_0.smt2                                       |   3.524s  |   3.524s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25852_terminationG_0.smt2                                       |   9.588s  |   9.588s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25856_terminationG_0.smt2                                       |   3.054s  |   3.054s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25857_terminationG_0.smt2                                       |  59.892s  |  59.892s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25858_terminationG_0.smt2                                       |  60.019s  |  60.019s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25861_terminationG_0.smt2                                       |   2.506s  |   2.506s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25862_terminationG_0.smt2                                       |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25866_terminationG_0.smt2                                       |  17.713s  |  17.713s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       |  59.891s  |  59.891s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25868_terminationG_0.smt2                                       |  59.779s  |  59.779s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25871_terminationG_0.smt2                                       |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25872_terminationG_0.smt2                                       |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25873_terminationG_0.smt2                                       |  59.746s  |  59.746s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25876_terminationG_0.smt2                                       |  29.603s  |  29.603s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25877_terminationG_0.smt2                                       |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25878_terminationG_0.smt2                                       |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25881_terminationG_0.smt2                                       |  17.293s  |  17.293s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25882_terminationG_0.smt2                                       |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25883_terminationG_0.smt2                                       |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   2.740s  |   2.740s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25887_terminationG_0.smt2                                       |  59.932s  |  59.932s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25888_terminationG_0.smt2                                       |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25891_terminationG_0.smt2                                       |  24.108s  |  24.108s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25892_terminationG_0.smt2                                       |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25893_terminationG_0.smt2                                       |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25896_terminationG_0.smt2                                       |   2.592s  |   2.592s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25897_terminationG_0.smt2                                       |  59.914s  |  59.914s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25898_terminationG_0.smt2                                       |  59.880s  |  59.880s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25901_terminationG_0.smt2                                       |   2.640s  |   2.640s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25902_terminationG_0.smt2                                       |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25905_terminationG_0.smt2                                       |  24.874s  |  24.874s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25907_terminationG_0.smt2                                       |  59.783s  |  59.783s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25908_terminationG_0.smt2                                       |  59.876s  |  59.876s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25911_terminationG_0.smt2                                       |  26.483s  |  26.483s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25912_terminationG_0.smt2                                       |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25916_terminationG_0.smt2                                       |   2.944s  |   2.944s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25917_terminationG_0.smt2                                       |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25918_terminationG_0.smt2                                       |  59.918s  |  59.918s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25922_terminationG_0.smt2                                       |  23.397s  |  23.397s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25923_terminationG_0.smt2                                       |  59.811s  |  59.811s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25924_terminationG_0.smt2                                       |  59.922s  |  59.922s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25927_terminationG_0.smt2                                       |  31.480s  |  31.480s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25928_terminationG_0.smt2                                       |  59.958s  |  59.958s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25932_terminationG_0.smt2                                       |  30.118s  |  30.118s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25933_terminationG_0.smt2                                       |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25934_terminationG_0.smt2                                       |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25937_terminationG_0.smt2                                       |   3.864s  |   3.864s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25938_terminationG_0.smt2                                       |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25939_terminationG_0.smt2                                       |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25942_terminationG_0.smt2                                       |  33.009s  |  33.009s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25943_terminationG_0.smt2                                       |  60.018s  |  60.018s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25944_terminationG_0.smt2                                       |  59.898s  |  59.898s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25947_terminationG_0.smt2                                       |  27.202s  |  27.202s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25948_terminationG_0.smt2                                       |  59.915s  |  59.915s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25949_terminationG_0.smt2                                       |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25952_terminationG_0.smt2                                       |   4.471s  |   4.471s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25953_terminationG_0.smt2                                       |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25954_terminationG_0.smt2                                       |  59.921s  |  59.921s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25957_terminationG_0.smt2                                       |  24.418s  |  24.418s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25958_terminationG_0.smt2                                       |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25959_terminationG_0.smt2                                       |  60.022s  |  60.022s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25962_terminationG_0.smt2                                       |   3.928s  |   3.928s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       |  59.860s  |  59.860s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25964_terminationG_0.smt2                                       |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25968_terminationG_0.smt2                                       |   2.980s  |   2.980s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25969_terminationG_0.smt2                                       |  59.883s  |  59.883s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25970_terminationG_0.smt2                                       |  60.060s  |  60.060s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25973_terminationG_0.smt2                                       |  26.905s  |  26.905s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25974_terminationG_0.smt2                                       |  59.863s  |  59.863s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25975_terminationG_0.smt2                                       |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25978_terminationG_0.smt2                                       |  27.596s  |  27.596s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25979_terminationG_0.smt2                                       |  59.911s  |  59.911s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25980_terminationG_0.smt2                                       |  59.929s  |  59.929s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |  38.083s  |  38.083s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25984_terminationG_0.smt2                                       |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25985_terminationG_0.smt2                                       |  59.875s  |  59.875s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25988_terminationG_0.smt2                                       |  29.469s  |  29.469s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25989_terminationG_0.smt2                                       |  59.842s  |  59.842s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25990_terminationG_0.smt2                                       |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25992_terminationG_0.smt2                                       |  35.223s  |  35.223s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25994_terminationG_0.smt2                                       |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25995_terminationG_0.smt2                                       |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationQ_27_0.smt2                                           |  13.342s  |  13.342s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   1.576s  |   1.576s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__p26008_terminationG_0.smt2                                      |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__p26009_terminationG_0.smt2                                      |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__p26013_terminationG_0.smt2                                      |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__p26014_terminationG_0.smt2                                      |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__terminationQ_1_0.smt2                                           |   0.901s  |   0.901s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26023_terminationG_0.smt2                                      |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26031_terminationG_0.smt2                                      |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26032_terminationG_0.smt2                                      |  59.803s  |  59.803s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26033_terminationG_0.smt2                                      |  59.792s  |  59.792s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26036_terminationG_0.smt2                                      |   1.448s  |   1.448s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26037_terminationG_0.smt2                                      |  56.917s  |  56.917s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26038_terminationG_0.smt2                                      |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26041_terminationG_0.smt2                                      |   1.849s  |   1.849s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26042_terminationG_0.smt2                                      |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26043_terminationG_0.smt2                                      |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   2.347s  |   2.347s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26047_terminationG_0.smt2                                      |  59.906s  |  59.906s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26048_terminationG_0.smt2                                      |  59.809s  |  59.809s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__terminationQ_3_0.smt2                                           |   2.038s  |   2.038s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26532_terminationG_0.smt2                       |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26535_terminationG_0.smt2                       |   0.766s  |   0.766s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26536_terminationG_0.smt2                       |  33.026s  |  33.026s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26537_terminationG_0.smt2                       |  59.503s  |  59.503s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26540_terminationG_0.smt2                       |   1.136s  |   1.136s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26541_terminationG_0.smt2                       |  33.809s  |  33.809s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26542_terminationG_0.smt2                       |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26545_terminationG_0.smt2                       |   1.877s  |   1.877s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26546_terminationG_0.smt2                       |  32.915s  |  32.915s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       |  59.869s  |  59.869s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26550_terminationG_0.smt2                       |   1.848s  |   1.848s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26551_terminationG_0.smt2                       |  28.451s  |  28.451s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26552_terminationG_0.smt2                       |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   2.769s  |   2.769s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26556_terminationG_0.smt2                       |  22.736s  |  22.736s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26568_edge_closing_0.smt2                       |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26581_terminationG_0.smt2                     |   2.610s  |   2.610s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v2_false-termination.c__p26608_terminationG_0.smt2                  |   2.126s  |   2.126s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v2_false-termination.c__p26609_terminationG_0.smt2                  |   3.009s  |   3.009s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v2_false-termination.c__p26620_edge_closing_0.smt2                  |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v3_false-termination.c__p26641_terminationG_0.smt2                  |   2.200s  |   2.200s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v3_false-termination.c__p26642_terminationG_0.smt2                  |  59.909s  |  59.909s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26677_terminationG_0.smt2                |   0.648s  |   0.648s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   2.277s  |   2.277s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26679_terminationG_0.smt2                |   3.260s  |   3.260s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26689_terminationG_0.smt2                |   2.279s  |   2.279s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26690_terminationG_0.smt2                |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26705_terminationG_0.smt2                  |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26706_terminationG_0.smt2                  |   1.771s  |   1.771s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26707_terminationG_0.smt2                  |  59.558s  |  59.558s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26710_terminationG_0.smt2                  |   0.615s  |   0.615s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26711_terminationG_0.smt2                  |   2.288s  |   2.288s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26712_terminationG_0.smt2                  |  59.835s  |  59.835s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26727_terminationG_0.smt2                   |   0.830s  |   0.830s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26728_terminationG_0.smt2                   |   2.196s  |   2.196s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26729_terminationG_0.smt2                   |   5.127s  |   5.127s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26732_terminationG_0.smt2                   |   1.744s  |   1.744s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26733_terminationG_0.smt2                   |   2.314s  |   2.314s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26734_terminationG_0.smt2                   |   3.400s  |   3.400s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26739_edge_closing_0.smt2                   |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__terminationQ_1_0.smt2                        |   0.979s  |   0.979s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26761_terminationG_0.smt2                |   2.163s  |   2.163s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26768_terminationG_0.smt2                |   2.172s  |   2.172s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26769_terminationG_0.smt2                |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26770_terminationG_0.smt2                |   1.012s  |   1.012s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26775_terminationG_0.smt2                |   2.250s  |   2.250s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26776_terminationG_0.smt2                |   1.075s  |   1.075s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26782_terminationG_0.smt2                |   2.310s  |   2.310s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26783_terminationG_0.smt2                |   2.052s  |   2.052s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26789_terminationG_0.smt2                |   2.791s  |   2.791s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26790_terminationG_0.smt2                |   0.781s  |   0.781s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26797_terminationG_0.smt2                |   2.871s  |   2.871s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26799_terminationG_0.smt2                |   1.533s  |   1.533s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26806_terminationG_0.smt2                |   2.449s  |   2.449s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26807_terminationG_0.smt2                |   0.728s  |   0.728s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26808_terminationG_0.smt2                |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26817_terminationG_0.smt2                |   2.437s  |   2.437s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26818_terminationG_0.smt2                |  18.261s  |  18.261s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26819_terminationG_0.smt2                |  59.917s  |  59.917s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26829_terminationG_0.smt2                |   1.877s  |   1.877s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26830_terminationG_0.smt2                |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26831_terminationG_0.smt2                |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26839_terminationG_0.smt2                |   2.489s  |   2.489s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26840_terminationG_0.smt2                |  30.914s  |  30.914s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26841_terminationG_0.smt2                |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26844_terminationG_0.smt2                |   2.391s  |   2.391s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26845_terminationG_0.smt2                |   5.600s  |   5.600s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26846_terminationG_0.smt2                |  59.891s  |  59.891s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26849_edge_closing_0.smt2                |  59.915s  |  59.915s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26850_edge_closing_0.smt2                |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26853_edge_closing_0.smt2                |   1.035s  |   1.035s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |  10.969s  |  10.969s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26856_edge_closing_0.smt2                |   1.006s  |   1.006s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26857_edge_closing_0.smt2                |  59.883s  |  59.883s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26858_edge_closing_0.smt2                |   0.989s  |   0.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26859_edge_closing_0.smt2                |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26860_edge_closing_0.smt2                |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26863_edge_closing_0.smt2                |   5.528s  |   5.528s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26864_edge_closing_0.smt2                |   0.855s  |   0.855s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26865_edge_closing_0.smt2                |   1.306s  |   1.306s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26866_edge_closing_0.smt2                |  59.898s  |  59.898s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26874_terminationG_0.smt2                  |   1.769s  |   1.769s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26875_terminationG_0.smt2                  |   1.265s  |   1.265s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   2.182s  |   2.182s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26879_terminationG_0.smt2                  |   0.891s  |   0.891s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26880_terminationG_0.smt2                  |   0.940s  |   0.940s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26902_terminationG_0.smt2                   |   1.116s  |   1.116s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26903_terminationG_0.smt2                   |  25.010s  |  25.010s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26904_terminationG_0.smt2                   |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   1.581s  |   1.581s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26908_terminationG_0.smt2                   |  19.163s  |  19.163s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26909_terminationG_0.smt2                   |  59.920s  |  59.920s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26912_terminationG_0.smt2                   |   2.516s  |   2.516s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26913_terminationG_0.smt2                   |  59.893s  |  59.893s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26914_terminationG_0.smt2                   |  59.921s  |  59.921s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26917_terminationG_0.smt2                   |   2.648s  |   2.648s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26918_terminationG_0.smt2                   |  25.054s  |  25.054s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26919_terminationG_0.smt2                   |  58.841s  |  58.841s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26922_terminationG_0.smt2                   |   1.736s  |   1.736s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26923_terminationG_0.smt2                   |  29.147s  |  29.147s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26924_terminationG_0.smt2                   |  60.018s  |  60.018s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26936_edge_closing_0.smt2                   |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26953_terminationG_0.smt2                   |   1.041s  |   1.041s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26954_terminationG_0.smt2                   |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26955_terminationG_0.smt2                   |   0.683s  |   0.683s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26961_terminationG_0.smt2                   |   0.890s  |   0.890s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26962_terminationG_0.smt2                   |   0.947s  |   0.947s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26965_terminationG_0.smt2                   |   2.117s  |   2.117s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26966_terminationG_0.smt2                   |   5.540s  |   5.540s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26967_terminationG_0.smt2                   |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26970_terminationG_0.smt2                   |   2.814s  |   2.814s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26971_terminationG_0.smt2                   |   1.909s  |   1.909s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26972_terminationG_0.smt2                   |  59.920s  |  59.920s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26975_terminationG_0.smt2                   |   2.366s  |   2.366s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26976_terminationG_0.smt2                   |  17.995s  |  17.995s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26977_terminationG_0.smt2                   |  16.207s  |  16.207s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26980_terminationG_0.smt2                   |   2.173s  |   2.173s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |  16.399s  |  16.399s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26982_terminationG_0.smt2                   |  30.881s  |  30.881s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26985_terminationG_0.smt2                   |   2.414s  |   2.414s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26986_terminationG_0.smt2                   |   8.511s  |   8.511s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26987_terminationG_0.smt2                   |   7.760s  |   7.760s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   2.010s  |   2.010s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26991_terminationG_0.smt2                   |   1.379s  |   1.379s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26992_terminationG_0.smt2                   |  15.601s  |  15.601s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26995_terminationG_0.smt2                   |   4.914s  |   4.914s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26996_terminationG_0.smt2                   |  23.147s  |  23.147s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26997_terminationG_0.smt2                   |  52.361s  |  52.361s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27000_terminationG_0.smt2                   |   4.107s  |   4.107s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27001_terminationG_0.smt2                   |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27002_terminationG_0.smt2                   |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27005_terminationG_0.smt2                   |   2.375s  |   2.375s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27006_terminationG_0.smt2                   |   7.861s  |   7.861s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27007_terminationG_0.smt2                   |  29.710s  |  29.710s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27010_terminationG_0.smt2                   |   2.075s  |   2.075s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27011_terminationG_0.smt2                   |   1.186s  |   1.186s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27012_terminationG_0.smt2                   |   1.321s  |   1.321s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27015_terminationG_0.smt2                   |   1.944s  |   1.944s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27016_terminationG_0.smt2                   |   0.636s  |   0.636s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27017_terminationG_0.smt2                   |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27020_terminationG_0.smt2                   |   2.353s  |   2.353s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |  12.792s  |  12.792s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27022_terminationG_0.smt2                   |  36.137s  |  36.137s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27025_terminationG_0.smt2                   |   2.545s  |   2.545s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27026_terminationG_0.smt2                   |   0.941s  |   0.941s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27027_terminationG_0.smt2                   |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27030_terminationG_0.smt2                   |   2.893s  |   2.893s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27031_terminationG_0.smt2                   |   1.390s  |   1.390s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27032_terminationG_0.smt2                   |   7.767s  |   7.767s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27038_edge_closing_0.smt2                   |   2.133s  |   2.133s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27039_edge_closing_0.smt2                   |   7.646s  |   7.646s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27040_edge_closing_0.smt2                   |   9.744s  |   9.744s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__terminationQ_13_0.smt2                       |   2.347s  |   2.347s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__terminationS_0_0.smt2                        |   1.220s  |   1.220s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27051_terminationG_0.smt2                    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27056_terminationG_0.smt2                    |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27057_terminationG_0.smt2                    |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27061_terminationG_0.smt2                    |   8.134s  |   8.134s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27062_terminationG_0.smt2                    |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27068_terminationG_0.smt2                    |   0.866s  |   0.866s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27069_terminationG_0.smt2                    |  42.746s  |  42.746s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27077_terminationG_0.smt2                    |  18.006s  |  18.006s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27083_terminationG_0.smt2                    |   6.220s  |   6.220s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27084_terminationG_0.smt2                    |  53.242s  |  53.242s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27092_terminationG_0.smt2                    |  31.878s  |  31.878s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27093_terminationG_0.smt2                    |  38.947s  |  38.947s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27097_terminationG_0.smt2                    |  15.925s  |  15.925s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27098_terminationG_0.smt2                    |   6.668s  |   6.668s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27109_terminationG_0.smt2                    |  10.158s  |  10.158s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27110_terminationG_0.smt2                    |  23.154s  |  23.154s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27121_terminationG_0.smt2                    |   8.031s  |   8.031s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27122_terminationG_0.smt2                    |   8.183s  |   8.183s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27123_terminationG_0.smt2                    |  56.318s  |  56.318s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27134_terminationG_0.smt2                    |   9.462s  |   9.462s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27135_terminationG_0.smt2                    |   9.279s  |   9.279s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27136_terminationG_0.smt2                    |  59.875s  |  59.875s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27139_terminationG_0.smt2                    |  10.441s  |  10.441s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27140_terminationG_0.smt2                    |  16.628s  |  16.628s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27141_terminationG_0.smt2                    |  46.838s  |  46.838s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27144_terminationG_0.smt2                    |   8.686s  |   8.686s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27145_terminationG_0.smt2                    |  26.002s  |  26.002s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27146_terminationG_0.smt2                    |  43.600s  |  43.600s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27149_terminationG_0.smt2                    |   9.773s  |   9.773s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27150_terminationG_0.smt2                    |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27151_terminationG_0.smt2                    |  49.828s  |  49.828s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27154_terminationG_0.smt2                    |  12.319s  |  12.319s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27155_terminationG_0.smt2                    |  59.933s  |  59.933s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27156_terminationG_0.smt2                    |  59.707s  |  59.707s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27159_terminationG_0.smt2                    |  10.060s  |  10.060s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27160_terminationG_0.smt2                    |  27.831s  |  27.831s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27161_terminationG_0.smt2                    |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27164_terminationG_0.smt2                    |  10.020s  |  10.020s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27165_terminationG_0.smt2                    |  59.905s  |  59.905s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27166_terminationG_0.smt2                    |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27169_terminationG_0.smt2                    |   9.443s  |   9.443s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27170_terminationG_0.smt2                    |  23.567s  |  23.567s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27171_terminationG_0.smt2                    |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27174_terminationG_0.smt2                    |  12.207s  |  12.207s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27175_terminationG_0.smt2                    |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27176_terminationG_0.smt2                    |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27179_terminationG_0.smt2                    |  11.342s  |  11.342s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27180_terminationG_0.smt2                    |  17.290s  |  17.290s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27181_terminationG_0.smt2                    |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27184_terminationG_0.smt2                    |  13.059s  |  13.059s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27185_terminationG_0.smt2                    |  33.839s  |  33.839s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27186_terminationG_0.smt2                    |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27189_terminationG_0.smt2                    |  10.636s  |  10.636s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27190_terminationG_0.smt2                    |  47.411s  |  47.411s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27191_terminationG_0.smt2                    |  30.130s  |  30.130s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27194_terminationG_0.smt2                    |  12.843s  |  12.843s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27195_terminationG_0.smt2                    |  34.908s  |  34.908s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27196_terminationG_0.smt2                    |  59.830s  |  59.830s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27199_terminationG_0.smt2                    |  11.163s  |  11.163s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27200_terminationG_0.smt2                    |   9.720s  |   9.720s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27201_terminationG_0.smt2                    |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27205_terminationG_0.smt2                    |  12.663s  |  12.663s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27206_terminationG_0.smt2                    |  37.869s  |  37.869s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27207_terminationG_0.smt2                    |  39.198s  |  39.198s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27210_terminationG_0.smt2                    |  11.805s  |  11.805s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27211_terminationG_0.smt2                    |   8.538s  |   8.538s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27212_terminationG_0.smt2                    |  59.892s  |  59.892s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27215_terminationG_0.smt2                    |  11.021s  |  11.021s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27216_terminationG_0.smt2                    |  23.750s  |  23.750s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27217_terminationG_0.smt2                    |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |  12.896s  |  12.896s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27221_terminationG_0.smt2                    |  16.419s  |  16.419s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27222_terminationG_0.smt2                    |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27225_terminationG_0.smt2                    |  11.202s  |  11.202s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |   1.842s  |   1.842s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27227_terminationG_0.smt2                    |  59.897s  |  59.897s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27230_terminationG_0.smt2                    |  11.063s  |  11.063s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27231_terminationG_0.smt2                    |  17.109s  |  17.109s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27232_terminationG_0.smt2                    |  40.062s  |  40.062s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27234_edge_closing_0.smt2                    |   6.886s  |   6.886s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27235_edge_closing_0.smt2                    |  39.082s  |  39.082s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27236_edge_closing_0.smt2                    |  32.621s  |  32.621s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27238_edge_closing_0.smt2                    |  25.257s  |  25.257s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27239_edge_closing_0.smt2                    |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27240_edge_closing_0.smt2                    |  59.706s  |  59.706s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27242_edge_closing_0.smt2                    |   1.137s  |   1.137s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__terminationQ_18_0.smt2                        |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__terminationQ_19_0.smt2                        |   7.540s  |   7.540s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__terminationS_0_0.smt2                         |   1.421s  |   1.421s  |   0.000s  | 0.0%|
|Ton_Chanh_15__McCarthy91_Iteration_true-termination.c__term_unfeasibility_0_0.smt2          |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27262_terminationG_0.smt2                        |   1.338s  |   1.338s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27263_terminationG_0.smt2                        |  15.686s  |  15.686s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        |  59.835s  |  59.835s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27267_terminationG_0.smt2                        |   1.189s  |   1.189s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27268_terminationG_0.smt2                        |  23.990s  |  23.990s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27272_terminationG_0.smt2                        |   2.682s  |   2.682s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27273_terminationG_0.smt2                        |  24.147s  |  24.147s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27274_terminationG_0.smt2                        |  59.885s  |  59.885s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27277_terminationG_0.smt2                        |   2.559s  |   2.559s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27278_terminationG_0.smt2                        |  26.667s  |  26.667s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27279_terminationG_0.smt2                        |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27282_terminationG_0.smt2                        |   2.193s  |   2.193s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27283_terminationG_0.smt2                        |  59.902s  |  59.902s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27284_terminationG_0.smt2                        |  59.860s  |  59.860s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |   0.606s  |   0.606s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27301_terminationG_0.smt2                |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27304_terminationG_0.smt2                |   0.649s  |   0.649s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27305_terminationG_0.smt2                |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27306_terminationG_0.smt2                |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27309_terminationG_0.smt2                |   2.753s  |   2.753s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27310_terminationG_0.smt2                |  59.918s  |  59.918s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27311_terminationG_0.smt2                |  59.919s  |  59.919s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27314_terminationG_0.smt2                |   2.877s  |   2.877s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27315_terminationG_0.smt2                |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27316_terminationG_0.smt2                |  59.902s  |  59.902s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27319_terminationG_0.smt2                |   1.721s  |   1.721s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27320_terminationG_0.smt2                |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27321_terminationG_0.smt2                |  59.924s  |  59.924s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27324_terminationG_0.smt2                |   2.493s  |   2.493s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27325_terminationG_0.smt2                |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27326_terminationG_0.smt2                |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27334_edge_closing_0.smt2                |   0.827s  |   0.827s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27343_terminationG_0.smt2                      |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27347_terminationG_0.smt2                      |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27348_terminationG_0.smt2                      |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27352_terminationG_0.smt2                      |   0.520s  |   0.520s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27353_terminationG_0.smt2                      |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27362_terminationG_0.smt2                  |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27367_terminationG_0.smt2                  |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27370_terminationG_0.smt2                  |   1.323s  |   1.323s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27371_terminationG_0.smt2                  |  59.906s  |  59.906s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27372_terminationG_0.smt2                  |  59.819s  |  59.819s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27375_terminationG_0.smt2                  |   1.570s  |   1.570s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27376_terminationG_0.smt2                  |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27377_terminationG_0.smt2                  |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27380_terminationG_0.smt2                  |   2.741s  |   2.741s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  59.918s  |  59.918s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27385_terminationG_0.smt2                  |   2.863s  |   2.863s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27386_terminationG_0.smt2                  |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27387_terminationG_0.smt2                  |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27390_terminationG_0.smt2                  |   2.359s  |   2.359s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27391_terminationG_0.smt2                  |  59.737s  |  59.737s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27392_terminationG_0.smt2                  |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27396_edge_closing_0.smt2                  |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27409_terminationG_0.smt2                  |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27413_terminationG_0.smt2                  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27414_terminationG_0.smt2                  |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27417_terminationG_0.smt2                  |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27418_terminationG_0.smt2                  |  59.908s  |  59.908s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27419_terminationG_0.smt2                  |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27422_terminationG_0.smt2                  |   1.470s  |   1.470s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27423_terminationG_0.smt2                  |  59.883s  |  59.883s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27424_terminationG_0.smt2                  |  59.773s  |  59.773s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27427_terminationG_0.smt2                  |   2.709s  |   2.709s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27428_terminationG_0.smt2                  |  59.908s  |  59.908s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27429_terminationG_0.smt2                  |  59.901s  |  59.901s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27432_terminationG_0.smt2                  |   2.727s  |   2.727s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27433_terminationG_0.smt2                  |  59.911s  |  59.911s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27434_terminationG_0.smt2                  |  59.876s  |  59.876s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27437_terminationG_0.smt2                  |   1.712s  |   1.712s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27438_terminationG_0.smt2                  |  59.920s  |  59.920s  |   0.000s  | 0.0%|
</details>
