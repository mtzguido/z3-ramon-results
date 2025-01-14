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
Job tag: smt-sls-no-lookahead-cinteger
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: a08a3ee32b01c87fd49e325db590231bd4a44834
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic=sls-smt model_validate=true"
Z3 inputs: inputs/QF_NIA_CInteger
Z3 commit message: align reslimit with ddfw

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-no-lookahead-cinteger
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: a08a3ee32b01c87fd49e325db590231bd4a44834
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic=sls-smt model_validate=true"
Z3 inputs: inputs/QF_NIA_CInteger
Z3 commit message: align reslimit with ddfw

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   7.218s  |   7.218s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |  56.090s  |  56.090s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |  32.887s  |  32.887s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |  57.721s  |  57.721s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |  60.045s  |  60.045s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  59.814s  |  59.814s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |  20.837s  |  20.837s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |  59.907s  |  59.907s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |  10.767s  |  10.767s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |  53.557s  |  53.557s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   7.218s  |   7.218s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |  56.090s  |  56.090s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |  32.887s  |  32.887s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |  57.721s  |  57.721s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |  60.045s  |  60.045s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  59.814s  |  59.814s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |  20.837s  |  20.837s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |  59.907s  |  59.907s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |  10.767s  |  10.767s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |  53.557s  |  53.557s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   7.218s  |   7.218s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |  56.090s  |  56.090s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |  32.887s  |  32.887s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |  57.721s  |  57.721s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |  60.045s  |  60.045s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  59.814s  |  59.814s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |  20.837s  |  20.837s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |  59.907s  |  59.907s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |  10.767s  |  10.767s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |  53.557s  |  53.557s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   7.218s  |   7.218s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |  56.090s  |  56.090s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |  32.887s  |  32.887s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |  57.721s  |  57.721s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |  60.045s  |  60.045s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  59.814s  |  59.814s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |  20.837s  |  20.837s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |  59.907s  |  59.907s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |  10.767s  |  10.767s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |  53.557s  |  53.557s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Stroeder_15__Gauss.c__p23064_terminationG_0.smt2                                           |  62.829s |18.996MiB|
|Stroeder_15__NonTermination4_false-termination.c__p24957_terminationG_0.smt2               |  61.769s |20.56MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21026_terminationG_0.smt2 |  61.576s |19.3MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27141_terminationG_0.smt2                   |  60.975s |22.98MiB|
|Stroeder_15__MirrorInterv.c__p24402_terminationG_0.smt2                                    |  60.482s |19.032MiB|
|Stroeder_15__DivWithoutMinus.c__p22504_terminationG_0.smt2                                 |  60.465s |21.436MiB|
|Stroeder_15__svcomp_ex2.c__p25923_terminationG_0.smt2                                      |  60.425s |21.416MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21954_terminationG_0.smt2 |  60.283s |20.492MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23707_edge_closing_0.smt2 |  60.278s |19.268MiB|
|Stroeder_15__WhileIncr.c__p26381_terminationG_0.smt2                                       |  60.186s |19.0MiB|
|Stroeder_15__svcomp_ex2.c__p25902_terminationG_0.smt2                                      |  60.160s |21.616MiB|
|Stroeder_15__svcomp_ex2.c__p25933_terminationG_0.smt2                                      |  60.153s |21.612MiB|
|Stroeder_15__WhileSingle.c__p26489_edge_closing_0.smt2                                     |  60.140s |20.94MiB|
|Stroeder_15__MirrorInterv.c__p24398_terminationG_0.smt2                                    |  60.106s |19.024MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21351_edge_closing_0.smt2 |  60.099s |18.868MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21989_terminationG_0.smt2 |  60.096s |20.896MiB|
|Stroeder_15__svcomp_ex2.c__p25852_terminationG_0.smt2                                      |  60.082s |22.224MiB|
|Stroeder_15__MirrorIntervSim.c__terminationQ_0_0.smt2                                      |  60.079s |18.764MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2 |  60.072s |20.44MiB|
|Stroeder_15__AlternDivWidening.c__p20655_terminationG_0.smt2                               |  60.065s |19.16MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Stroeder_15__Gauss.c__p23064_terminationG_0.smt2                                           |  62.829s |18.996MiB|
|Stroeder_15__NonTermination4_false-termination.c__p24957_terminationG_0.smt2               |  61.769s |20.56MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21026_terminationG_0.smt2 |  61.576s |19.3MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27141_terminationG_0.smt2                   |  60.975s |22.98MiB|
|Stroeder_15__MirrorInterv.c__p24402_terminationG_0.smt2                                    |  60.482s |19.032MiB|
|Stroeder_15__DivWithoutMinus.c__p22504_terminationG_0.smt2                                 |  60.465s |21.436MiB|
|Stroeder_15__svcomp_ex2.c__p25923_terminationG_0.smt2                                      |  60.425s |21.416MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21954_terminationG_0.smt2 |  60.283s |20.492MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23707_edge_closing_0.smt2 |  60.278s |19.268MiB|
|Stroeder_15__WhileIncr.c__p26381_terminationG_0.smt2                                       |  60.186s |19.0MiB|
|Stroeder_15__svcomp_ex2.c__p25902_terminationG_0.smt2                                      |  60.160s |21.616MiB|
|Stroeder_15__svcomp_ex2.c__p25933_terminationG_0.smt2                                      |  60.153s |21.612MiB|
|Stroeder_15__WhileSingle.c__p26489_edge_closing_0.smt2                                     |  60.140s |20.94MiB|
|Stroeder_15__MirrorInterv.c__p24398_terminationG_0.smt2                                    |  60.106s |19.024MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21351_edge_closing_0.smt2 |  60.099s |18.868MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21989_terminationG_0.smt2 |  60.096s |20.896MiB|
|Stroeder_15__svcomp_ex2.c__p25852_terminationG_0.smt2                                      |  60.082s |22.224MiB|
|Stroeder_15__MirrorIntervSim.c__terminationQ_0_0.smt2                                      |  60.079s |18.764MiB|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2 |  60.072s |20.44MiB|
|Stroeder_15__AlternDivWidening.c__p20655_terminationG_0.smt2                               |  60.065s |19.16MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |18.996MiB|18.996MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |18.832MiB|18.832MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |18.932MiB|18.932MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |19.044MiB|19.044MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |18.964MiB|18.964MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |20.956MiB|20.956MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |19.8MiB|19.8MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |20.496MiB|20.496MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |19.464MiB|19.464MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |19.648MiB|19.648MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |20.904MiB|20.904MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |21.744MiB|21.744MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |20.648MiB|20.648MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |21.36MiB|21.36MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |20.5MiB|20.5MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |21.096MiB|21.096MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |20.116MiB|20.116MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |20.54MiB|20.54MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |21.344MiB|21.344MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |20.088MiB|20.088MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |18.996MiB|18.996MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |18.832MiB|18.832MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |18.932MiB|18.932MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |19.044MiB|19.044MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |18.964MiB|18.964MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |20.956MiB|20.956MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |19.8MiB|19.8MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |20.496MiB|20.496MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |19.464MiB|19.464MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |19.648MiB|19.648MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |20.904MiB|20.904MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |21.744MiB|21.744MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |20.648MiB|20.648MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |21.36MiB|21.36MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |20.5MiB|20.5MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |21.096MiB|21.096MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |20.116MiB|20.116MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |20.54MiB|20.54MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |21.344MiB|21.344MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |20.088MiB|20.088MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |18.996MiB|18.996MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |18.832MiB|18.832MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |18.932MiB|18.932MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |19.044MiB|19.044MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |18.964MiB|18.964MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |20.956MiB|20.956MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |19.8MiB|19.8MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |20.496MiB|20.496MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |19.464MiB|19.464MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |19.648MiB|19.648MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |20.904MiB|20.904MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |21.744MiB|21.744MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |20.648MiB|20.648MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |21.36MiB|21.36MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |20.5MiB|20.5MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |21.096MiB|21.096MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |20.116MiB|20.116MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |20.54MiB|20.54MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |21.344MiB|21.344MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |20.088MiB|20.088MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |18.996MiB|18.996MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |18.832MiB|18.832MiB|0B| 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |18.932MiB|18.932MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |19.044MiB|19.044MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |18.964MiB|18.964MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |20.956MiB|20.956MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |19.8MiB|19.8MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |20.496MiB|20.496MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |19.464MiB|19.464MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |19.648MiB|19.648MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |20.904MiB|20.904MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |21.744MiB|21.744MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |20.648MiB|20.648MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |21.36MiB|21.36MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |20.5MiB|20.5MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |21.096MiB|21.096MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |20.116MiB|20.116MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |20.54MiB|20.54MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |21.344MiB|21.344MiB|0B| 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |20.088MiB|20.088MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27240_edge_closing_0.smt2                   |  55.861s |128.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22029_edge_closing_0.smt2 |  59.973s |124.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27239_edge_closing_0.smt2                   |  56.567s |91.784MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27238_edge_closing_0.smt2                   |  59.813s |84.748MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2 |  59.253s |84.48MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22027_edge_closing_0.smt2 |  59.981s |79.648MiB|
|Stroeder_15__svcomp_ex2.c__p25827_terminationG_0.smt2                                      |  59.935s |30.708MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27040_edge_closing_0.smt2                  |  59.982s |30.64MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27039_edge_closing_0.smt2                  |   3.314s |29.28MiB|
|Stroeder_15__Narrowing.c__p24549_edge_closing_0.smt2                                       |  59.994s |27.668MiB|
|Stroeder_15__Narrowing.c__p24548_edge_closing_0.smt2                                       |  59.407s |27.588MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27038_edge_closing_0.smt2                  |   1.580s |27.58MiB|
|Stroeder_15__svcomp_ex2.c__p25826_terminationG_0.smt2                                      |  60.003s |26.556MiB|
|Stroeder_15__Narrowing.c__p24547_edge_closing_0.smt2                                       |  59.018s |26.02MiB|
|Stroeder_15__svcomp_ex2.c__p25817_terminationG_0.smt2                                      |  59.350s |25.92MiB|
|Stroeder_15__svcomp_ex2.c__p25832_terminationG_0.smt2                                      |  58.551s |25.704MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27217_terminationG_0.smt2                   |  53.328s |25.08MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27222_terminationG_0.smt2                   |  60.025s |24.908MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27201_terminationG_0.smt2                   |  59.982s |24.86MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27212_terminationG_0.smt2                   |  57.789s |24.824MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27240_edge_closing_0.smt2                   |  55.861s |128.0MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22029_edge_closing_0.smt2 |  59.973s |124.0MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27239_edge_closing_0.smt2                   |  56.567s |91.784MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27238_edge_closing_0.smt2                   |  59.813s |84.748MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2 |  59.253s |84.48MiB|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22027_edge_closing_0.smt2 |  59.981s |79.648MiB|
|Stroeder_15__svcomp_ex2.c__p25827_terminationG_0.smt2                                      |  59.935s |30.708MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27040_edge_closing_0.smt2                  |  59.982s |30.64MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27039_edge_closing_0.smt2                  |   3.314s |29.28MiB|
|Stroeder_15__Narrowing.c__p24549_edge_closing_0.smt2                                       |  59.994s |27.668MiB|
|Stroeder_15__Narrowing.c__p24548_edge_closing_0.smt2                                       |  59.407s |27.588MiB|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27038_edge_closing_0.smt2                  |   1.580s |27.58MiB|
|Stroeder_15__svcomp_ex2.c__p25826_terminationG_0.smt2                                      |  60.003s |26.556MiB|
|Stroeder_15__Narrowing.c__p24547_edge_closing_0.smt2                                       |  59.018s |26.02MiB|
|Stroeder_15__svcomp_ex2.c__p25817_terminationG_0.smt2                                      |  59.350s |25.92MiB|
|Stroeder_15__svcomp_ex2.c__p25832_terminationG_0.smt2                                      |  58.551s |25.704MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27217_terminationG_0.smt2                   |  53.328s |25.08MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27222_terminationG_0.smt2                   |  60.025s |24.908MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27201_terminationG_0.smt2                   |  59.982s |24.86MiB|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27212_terminationG_0.smt2                   |  57.789s |24.824MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|Stroeder_15__2Nested_true-termination.c__p20185_terminationG_0.smt2                         |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20189_terminationG_0.smt2                         |   7.218s  |   7.218s  |   0.000s  | 0.0%|
|Stroeder_15__2Nested_true-termination.c__p20190_terminationG_0.smt2                         |  56.090s  |  56.090s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20202_terminationG_0.smt2           |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20203_terminationG_0.smt2           |  32.887s  |  32.887s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20204_terminationG_0.smt2           |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20211_terminationG_0.smt2           |  57.721s  |  57.721s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20217_terminationG_0.smt2           |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20227_terminationG_0.smt2           |  60.045s  |  60.045s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20228_terminationG_0.smt2           |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20232_terminationG_0.smt2           |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20233_terminationG_0.smt2           |  59.814s  |  59.814s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20238_terminationG_0.smt2           |  20.837s  |  20.837s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20239_terminationG_0.smt2           |  59.907s  |  59.907s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20246_terminationG_0.smt2           |  10.767s  |  10.767s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20247_terminationG_0.smt2           |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20253_terminationG_0.smt2           |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20254_terminationG_0.smt2           |  53.557s  |  53.557s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20255_terminationG_0.smt2           |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20259_terminationG_0.smt2           |   7.682s  |   7.682s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20260_terminationG_0.smt2           |  21.924s  |  21.924s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20269_terminationG_0.smt2           |  59.829s  |  59.829s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20270_terminationG_0.smt2           |  58.466s  |  58.466s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20271_terminationG_0.smt2           |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20279_terminationG_0.smt2           |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20280_terminationG_0.smt2           |  57.033s  |  57.033s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20281_terminationG_0.smt2           |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20288_terminationG_0.smt2           |  59.919s  |  59.919s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20289_terminationG_0.smt2           |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20305_terminationG_0.smt2           |  59.347s  |  59.347s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20306_terminationG_0.smt2           |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20307_terminationG_0.smt2           |  59.814s  |  59.814s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20312_terminationG_0.smt2           |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20313_terminationG_0.smt2           |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20314_terminationG_0.smt2           |  59.342s  |  59.342s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20324_terminationG_0.smt2           |  54.303s  |  54.303s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20325_terminationG_0.smt2           |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20326_terminationG_0.smt2           |  59.933s  |  59.933s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_0_0.smt2                |  58.184s  |  58.184s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_2_0.smt2                |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_3_0.smt2                |  57.313s  |  57.313s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__terminationS_4_0.smt2                |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-Fig1_true-termination.c__p20413_terminationG_0.smt2  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-Fig2b_true-termination.c__p20426_terminationG_0.smt2  |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-Fig2b_true-termination.c__terminationS_1_0.smt2  |  60.053s  |  60.053s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-complex_true-termination.c__term_unfeasibility_0_0.smt2  |  60.025s  |  60.025s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-counterex1b_true-termination.c__p20394_terminationG_0.smt2  |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-counterex1b_true-termination.c__p20395_terminationG_0.smt2  |  13.291s  |  13.291s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-counterex1b_true-termination.c__p20396_terminationG_0.smt2  |  59.633s  |  59.633s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-loops_true-termination.c__p20439_terminationG_0.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-loops_true-termination.c__p20440_terminationG_0.smt2  |  13.295s  |  13.295s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-loops_true-termination.c__term_unfeasibility_0_0.smt2  |  56.085s  |  56.085s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-nestedLoop_true-termination.c__p20452_terminationG_0.smt2  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-nestedLoop_true-termination.c__p20453_terminationG_0.smt2  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-speedFails4_true-termination.c__p20494_terminationG_0.smt2  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Stroeder_15__AliasDarteFeautrierGonnord-SAS2010-speedpldi4_true-termination.c__p20516_terminationG_0.smt2  |  59.803s  |  59.803s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20546_terminationG_0.smt2                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20552_terminationG_0.smt2                                        |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20553_terminationG_0.smt2                                        |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20556_edge_closing_0.smt2                                        |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDiv.c__p20557_edge_closing_0.smt2                                        |  59.559s  |  59.559s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20618_terminationG_0.smt2                                    |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20619_terminationG_0.smt2                                    |  57.442s  |  57.442s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20626_edge_closing_0.smt2                                    |  59.480s  |  59.480s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWide.c__p20627_edge_closing_0.smt2                                    |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20638_terminationG_0.smt2                                |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20639_terminationG_0.smt2                                |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20650_terminationG_0.smt2                                |  59.481s  |  59.481s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20651_terminationG_0.smt2                                |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20652_terminationG_0.smt2                                |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20655_terminationG_0.smt2                                |  60.065s  |  60.065s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20656_terminationG_0.smt2                                |  57.603s  |  57.603s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20657_terminationG_0.smt2                                |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20661_edge_closing_0.smt2                                |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20662_edge_closing_0.smt2                                |  56.833s  |  56.833s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20668_edge_closing_0.smt2                                |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__p20669_edge_closing_0.smt2                                |  58.421s  |  58.421s  |   0.000s  | 0.0%|
|Stroeder_15__AlternDivWidening.c__terminationQ_1_0.smt2                                     |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |  22.713s  |  22.713s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20688_terminationG_0.smt2                                       |  58.495s  |  58.495s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20689_terminationG_0.smt2                                       |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20690_terminationG_0.smt2                                       |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20693_edge_closing_0.smt2                                       |  58.403s  |  58.403s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20694_edge_closing_0.smt2                                       |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__terminationS_1_0.smt2                                            |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__Benghazi_true-termination.c__p20729_terminationG_0.smt2                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20762_terminationG_0.smt2  |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20763_terminationG_0.smt2  |  59.804s  |  59.804s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20774_edge_closing_0.smt2  |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1-modified_false-termination.c__p20777_edge_closing_0.smt2  |  22.428s  |  22.428s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1_true-termination.c__p20785_terminationG_0.smt2  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-CAV2005-Fig1_true-termination.c__p20786_terminationG_0.smt2  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-ICALP2005-Fig1_true-termination.c__p20810_terminationG_0.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|Stroeder_15__BradleyMannaSipma-ICALP2005-Fig1_true-termination.c__p20814_terminationG_0.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|Stroeder_15__BrockschmidtCookFuhs-CAV2013-Fig9a_true-termination.c__p20828_terminationG_0.smt2  |  55.179s  |  55.179s  |   0.000s  | 0.0%|
|Stroeder_15__BrockschmidtCookFuhs-CAV2013-Introduction_true-termination.c__p20837_terminationG_0.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20849_terminationG_0.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20853_terminationG_0.smt2  |  59.882s  |  59.882s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20854_terminationG_0.smt2  |  59.220s  |  59.220s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20855_terminationG_0.smt2  |  59.408s  |  59.408s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20858_terminationG_0.smt2  |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20859_terminationG_0.smt2  |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20860_terminationG_0.smt2  |  59.921s  |  59.921s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20863_terminationG_0.smt2  |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20864_terminationG_0.smt2  |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20865_terminationG_0.smt2  |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20868_terminationG_0.smt2  |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20869_terminationG_0.smt2  |  60.016s  |  60.016s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20870_terminationG_0.smt2  |  59.924s  |  59.924s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20873_terminationG_0.smt2  |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20874_terminationG_0.smt2  |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron12_true-termination.c__p20875_terminationG_0.smt2  |  59.371s  |  59.371s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20888_terminationG_0.smt2  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20892_terminationG_0.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.826s  |   0.826s  |   0.000s  | 0.0%|
|Stroeder_15__ChenCookFuhsNimkarOHearn-TACAS2014-Introduction_false-termination.c__p20918_terminationG_0.smt2  |  56.535s  |  56.535s  |   0.000s  | 0.0%|
|Stroeder_15__ChenCookFuhsNimkarOHearn-TACAS2014-Introduction_false-termination.c__p20919_terminationG_0.smt2  |  59.714s  |  59.714s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20939_terminationG_0.smt2  |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20940_terminationG_0.smt2  |  58.147s  |  58.147s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20941_terminationG_0.smt2  |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20944_edge_closing_0.smt2  |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex1.01_true-termination.c__p20945_edge_closing_0.smt2  |  60.004s  |  60.004s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.01_true-termination.c__p20984_terminationG_0.smt2  |   3.302s  |   3.302s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.01_true-termination.c__p20989_terminationG_0.smt2  |   6.552s  |   6.552s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21003_terminationG_0.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21008_terminationG_0.smt2  |  19.343s  |  19.343s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21011_terminationG_0.smt2  |  59.958s  |  59.958s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21012_terminationG_0.smt2  |  59.246s  |  59.246s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21013_terminationG_0.smt2  |  59.132s  |  59.132s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21016_terminationG_0.smt2  |  59.142s  |  59.142s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21017_terminationG_0.smt2  |  59.747s  |  59.747s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21018_terminationG_0.smt2  |  59.837s  |  59.837s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21021_terminationG_0.smt2  |  59.860s  |  59.860s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21022_terminationG_0.smt2  |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21023_terminationG_0.smt2  |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21026_terminationG_0.smt2  |  61.576s  |  61.576s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21027_terminationG_0.smt2  |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  |  59.894s  |  59.894s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21031_terminationG_0.smt2  |  59.523s  |  59.523s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21032_terminationG_0.smt2  |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21033_terminationG_0.smt2  |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21037_edge_closing_0.smt2  |   1.283s  |   1.283s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21040_edge_closing_0.smt2  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21044_edge_closing_0.smt2  |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21056_terminationG_0.smt2  |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21057_terminationG_0.smt2  |  59.444s  |  59.444s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21058_terminationG_0.smt2  |  59.044s  |  59.044s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21061_edge_closing_0.smt2  |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.03_false-termination.c__p21062_edge_closing_0.smt2  |  58.327s  |  58.327s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21079_terminationG_0.smt2  |  22.682s  |  22.682s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21083_terminationG_0.smt2  |  57.740s  |  57.740s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21084_terminationG_0.smt2  |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.04_false-termination.c__p21085_terminationG_0.smt2  |  59.018s  |  59.018s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21107_terminationG_0.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21108_terminationG_0.smt2  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21112_terminationG_0.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21113_terminationG_0.smt2  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21116_terminationG_0.smt2  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21118_terminationG_0.smt2  |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21122_terminationG_0.smt2  |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21123_terminationG_0.smt2  |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21126_terminationG_0.smt2  |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21127_terminationG_0.smt2  |  59.053s  |  59.053s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21128_terminationG_0.smt2  |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21131_terminationG_0.smt2  |  57.923s  |  57.923s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21132_terminationG_0.smt2  |  59.842s  |  59.842s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |  59.114s  |  59.114s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21136_edge_closing_0.smt2  |  59.886s  |  59.886s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21137_edge_closing_0.smt2  |  59.769s  |  59.769s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |  59.809s  |  59.809s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21141_edge_closing_0.smt2  |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21142_edge_closing_0.smt2  |  58.747s  |  58.747s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21143_edge_closing_0.smt2  |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21144_edge_closing_0.smt2  |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |  59.675s  |  59.675s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21148_edge_closing_0.smt2  |  60.029s  |  60.029s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21149_edge_closing_0.smt2  |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21150_edge_closing_0.smt2  |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.07_true-termination.c__p21184_terminationG_0.smt2  |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.07_true-termination.c__p21189_terminationG_0.smt2  |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.07_true-termination.c__terminationS_0_0.smt2  |  59.750s  |  59.750s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.08_true-termination.c__p21202_terminationG_0.smt2  |   3.279s  |   3.279s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.08_true-termination.c__p21203_terminationG_0.smt2  |   2.506s  |   2.506s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21242_terminationG_0.smt2  |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21246_terminationG_0.smt2  |  59.787s  |  59.787s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |  59.402s  |  59.402s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21258_terminationG_0.smt2  |   8.236s  |   8.236s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21260_terminationG_0.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21265_terminationG_0.smt2  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21280_terminationG_0.smt2  |  59.419s  |  59.419s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21283_terminationG_0.smt2  |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21285_terminationG_0.smt2  |  58.073s  |  58.073s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21288_terminationG_0.smt2  |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21290_terminationG_0.smt2  |  59.437s  |  59.437s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21293_terminationG_0.smt2  |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21294_terminationG_0.smt2  |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21295_terminationG_0.smt2  |  59.737s  |  59.737s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21298_terminationG_0.smt2  |  59.893s  |  59.893s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21299_terminationG_0.smt2  |  59.925s  |  59.925s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21300_terminationG_0.smt2  |  59.260s  |  59.260s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21303_terminationG_0.smt2  |  58.598s  |  58.598s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21304_terminationG_0.smt2  |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21305_terminationG_0.smt2  |  59.621s  |  59.621s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21308_terminationG_0.smt2  |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21309_terminationG_0.smt2  |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21310_terminationG_0.smt2  |  58.536s  |  58.536s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21313_terminationG_0.smt2  |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21314_terminationG_0.smt2  |  57.406s  |  57.406s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21315_terminationG_0.smt2  |  59.886s  |  59.886s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21318_terminationG_0.smt2  |  59.838s  |  59.838s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21319_terminationG_0.smt2  |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21320_terminationG_0.smt2  |  59.882s  |  59.882s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21323_terminationG_0.smt2  |  60.016s  |  60.016s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21324_terminationG_0.smt2  |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21325_terminationG_0.smt2  |  59.574s  |  59.574s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21328_terminationG_0.smt2  |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21329_terminationG_0.smt2  |  59.733s  |  59.733s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21330_terminationG_0.smt2  |  59.578s  |  59.578s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21334_edge_closing_0.smt2  |  59.783s  |  59.783s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21336_edge_closing_0.smt2  |  59.882s  |  59.882s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21337_edge_closing_0.smt2  |  59.717s  |  59.717s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21338_edge_closing_0.smt2  |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21342_edge_closing_0.smt2  |  58.655s  |  58.655s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21343_edge_closing_0.smt2  |  59.865s  |  59.865s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21351_edge_closing_0.smt2  |  60.099s  |  60.099s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21352_edge_closing_0.smt2  |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21353_edge_closing_0.smt2  |  58.768s  |  58.768s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__terminationS_0_0.smt2  |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21362_terminationG_0.smt2  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21367_terminationG_0.smt2  |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21371_terminationG_0.smt2  |  58.047s  |  58.047s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21372_terminationG_0.smt2  |  59.958s  |  59.958s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21376_terminationG_0.smt2  |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21377_terminationG_0.smt2  |  57.519s  |  57.519s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21382_terminationG_0.smt2  |  59.760s  |  59.760s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21385_terminationG_0.smt2  |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21386_terminationG_0.smt2  |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21387_terminationG_0.smt2  |  59.599s  |  59.599s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21390_terminationG_0.smt2  |  59.521s  |  59.521s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21391_terminationG_0.smt2  |  59.013s  |  59.013s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21392_terminationG_0.smt2  |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21395_terminationG_0.smt2  |  59.893s  |  59.893s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21400_edge_closing_0.smt2  |   1.650s  |   1.650s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21401_edge_closing_0.smt2  |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.13_true-termination.c__p21424_terminationG_0.smt2  |   1.357s  |   1.357s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21451_terminationG_0.smt2  |  59.316s  |  59.316s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21452_terminationG_0.smt2  |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21453_terminationG_0.smt2  |  59.718s  |  59.718s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21456_edge_closing_0.smt2  |   4.959s  |   4.959s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21457_edge_closing_0.smt2  |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21463_edge_closing_0.smt2  |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21464_edge_closing_0.smt2  |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21468_edge_closing_0.smt2  |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21469_edge_closing_0.smt2  |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__p21470_edge_closing_0.smt2  |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.14_false-termination.c__terminationQ_0_0.smt2  |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.15_false-termination.c__p21487_terminationG_0.smt2  |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.15_false-termination.c__p21491_terminationG_0.smt2  |  59.873s  |  59.873s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.15_false-termination.c__p21492_terminationG_0.smt2  |  59.372s  |  59.372s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.16_true-termination.c__p21520_terminationG_0.smt2  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.16_true-termination.c__p21525_terminationG_0.smt2  |   2.117s  |   2.117s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.16_true-termination.c__p21530_terminationG_0.smt2  |  56.108s  |  56.108s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21539_terminationG_0.smt2  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21543_terminationG_0.smt2  |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21544_terminationG_0.smt2  |  59.732s  |  59.732s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21547_terminationG_0.smt2  |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21548_terminationG_0.smt2  |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21549_terminationG_0.smt2  |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21552_terminationG_0.smt2  |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21553_terminationG_0.smt2  |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21554_terminationG_0.smt2  |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.17_false-termination.c__p21562_edge_closing_0.smt2  |  59.593s  |  59.593s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.18_true-termination.c__p21582_terminationG_0.smt2  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.19_true-termination.c__p21598_terminationG_0.smt2  |   6.910s  |   6.910s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.22_true-termination.c__p21645_terminationG_0.smt2  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.22_true-termination.c__p21649_terminationG_0.smt2  |   1.386s  |   1.386s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.22_true-termination.c__p21650_terminationG_0.smt2  |  40.163s  |  40.163s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21678_terminationG_0.smt2  |  17.160s  |  17.160s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21685_terminationG_0.smt2  |  10.742s  |  10.742s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21690_terminationG_0.smt2  |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21697_terminationG_0.smt2  |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21702_terminationG_0.smt2  |  59.693s  |  59.693s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21709_terminationG_0.smt2  |   8.727s  |   8.727s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21719_terminationG_0.smt2  |  10.784s  |  10.784s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21726_terminationG_0.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21727_terminationG_0.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21728_terminationG_0.smt2  |  26.522s  |  26.522s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21732_terminationG_0.smt2  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21733_terminationG_0.smt2  |  21.370s  |  21.370s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21737_terminationG_0.smt2  |  59.665s  |  59.665s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21738_terminationG_0.smt2  |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21748_edge_closing_0.smt2  |   0.613s  |   0.613s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21772_terminationG_0.smt2  |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21774_terminationG_0.smt2  |  22.813s  |  22.813s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21780_terminationG_0.smt2  |  55.427s  |  55.427s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21781_terminationG_0.smt2  |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21788_terminationG_0.smt2  |  56.658s  |  56.658s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21793_terminationG_0.smt2  |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21794_terminationG_0.smt2  |  57.809s  |  57.809s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21795_terminationG_0.smt2  |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21802_terminationG_0.smt2  |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.03_true-termination.c__p21803_terminationG_0.smt2  |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.04_true-termination.c__p21822_terminationG_0.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.04_true-termination.c__p21827_terminationG_0.smt2  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21868_terminationG_0.smt2  |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21870_terminationG_0.smt2  |  37.597s  |  37.597s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21875_terminationG_0.smt2  |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21876_terminationG_0.smt2  |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21877_terminationG_0.smt2  |  58.170s  |  58.170s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21882_terminationG_0.smt2  |  59.637s  |  59.637s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21883_terminationG_0.smt2  |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21884_terminationG_0.smt2  |  59.748s  |  59.748s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21890_terminationG_0.smt2  |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21891_terminationG_0.smt2  |  24.762s  |  24.762s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21892_terminationG_0.smt2  |  58.479s  |  58.479s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21895_terminationG_0.smt2  |  59.542s  |  59.542s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21896_terminationG_0.smt2  |  60.017s  |  60.017s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21897_terminationG_0.smt2  |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21905_terminationG_0.smt2  |  17.746s  |  17.746s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21906_terminationG_0.smt2  |  59.898s  |  59.898s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21907_terminationG_0.smt2  |  59.838s  |  59.838s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21910_terminationG_0.smt2  |  59.224s  |  59.224s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21911_terminationG_0.smt2  |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21912_terminationG_0.smt2  |  59.349s  |  59.349s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21922_terminationG_0.smt2  |  11.498s  |  11.498s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21923_terminationG_0.smt2  |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21924_terminationG_0.smt2  |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21927_terminationG_0.smt2  |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21928_terminationG_0.smt2  |  58.065s  |  58.065s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21929_terminationG_0.smt2  |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21938_terminationG_0.smt2  |  59.370s  |  59.370s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21939_terminationG_0.smt2  |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21940_terminationG_0.smt2  |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21943_terminationG_0.smt2  |  59.055s  |  59.055s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21944_terminationG_0.smt2  |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21945_terminationG_0.smt2  |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21948_terminationG_0.smt2  |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21949_terminationG_0.smt2  |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21953_terminationG_0.smt2  |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21954_terminationG_0.smt2  |  60.283s  |  60.283s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21955_terminationG_0.smt2  |  58.528s  |  58.528s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21957_terminationG_0.smt2  |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21959_terminationG_0.smt2  |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |  57.672s  |  57.672s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21963_terminationG_0.smt2  |  59.367s  |  59.367s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21964_terminationG_0.smt2  |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21965_terminationG_0.smt2  |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21968_terminationG_0.smt2  |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21969_terminationG_0.smt2  |  59.816s  |  59.816s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21970_terminationG_0.smt2  |  58.606s  |  58.606s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21973_terminationG_0.smt2  |  59.371s  |  59.371s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21974_terminationG_0.smt2  |  59.446s  |  59.446s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21975_terminationG_0.smt2  |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21978_terminationG_0.smt2  |  58.343s  |  58.343s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21979_terminationG_0.smt2  |  59.619s  |  59.619s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21980_terminationG_0.smt2  |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21983_terminationG_0.smt2  |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21984_terminationG_0.smt2  |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21985_terminationG_0.smt2  |  58.988s  |  58.988s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21988_terminationG_0.smt2  |  51.660s  |  51.660s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21989_terminationG_0.smt2  |  60.096s  |  60.096s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21990_terminationG_0.smt2  |  59.519s  |  59.519s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21993_terminationG_0.smt2  |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21994_terminationG_0.smt2  |  52.632s  |  52.632s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21998_terminationG_0.smt2  |  59.823s  |  59.823s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21999_terminationG_0.smt2  |  59.722s  |  59.722s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |  56.789s  |  56.789s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22004_terminationG_0.smt2  |  59.898s  |  59.898s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22005_terminationG_0.smt2  |  58.512s  |  58.512s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22006_terminationG_0.smt2  |  57.728s  |  57.728s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22009_terminationG_0.smt2  |  58.692s  |  58.692s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22010_terminationG_0.smt2  |  60.009s  |  60.009s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22011_terminationG_0.smt2  |  59.920s  |  59.920s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22014_terminationG_0.smt2  |  59.332s  |  59.332s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22015_terminationG_0.smt2  |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22016_terminationG_0.smt2  |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22019_terminationG_0.smt2  |  59.004s  |  59.004s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22020_terminationG_0.smt2  |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22021_terminationG_0.smt2  |  59.871s  |  59.871s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22023_edge_closing_0.smt2  |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22024_edge_closing_0.smt2  |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22025_edge_closing_0.smt2  |  58.867s  |  58.867s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22027_edge_closing_0.smt2  |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |  59.253s  |  59.253s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22029_edge_closing_0.smt2  |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22031_edge_closing_0.smt2  |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__terminationQ_14_0.smt2  |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__terminationS_0_0.smt2  |  59.192s  |  59.192s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.07_true-termination.c__p22044_terminationG_0.smt2  |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.07_true-termination.c__p22045_terminationG_0.smt2  |  22.351s  |  22.351s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.08_true-termination.c__p22056_terminationG_0.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.08_true-termination.c__p22062_terminationG_0.smt2  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.08_true-termination.c__p22067_terminationG_0.smt2  |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22103_terminationG_0.smt2  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22104_terminationG_0.smt2  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22109_terminationG_0.smt2  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22113_terminationG_0.smt2  |  59.361s  |  59.361s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22114_terminationG_0.smt2  |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22118_terminationG_0.smt2  |  59.232s  |  59.232s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22119_terminationG_0.smt2  |  59.070s  |  59.070s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22122_terminationG_0.smt2  |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22123_terminationG_0.smt2  |  59.776s  |  59.776s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22124_terminationG_0.smt2  |  58.845s  |  58.845s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex4.01_true-termination.c__p22129_terminationG_0.smt2  |  59.266s  |  59.266s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22142_terminationG_0.smt2  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22147_terminationG_0.smt2  |  10.209s  |  10.209s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22148_terminationG_0.smt2  |  14.405s  |  14.405s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |  42.794s  |  42.794s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22158_terminationG_0.smt2  |  58.873s  |  58.873s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22160_terminationG_0.smt2  |  60.048s  |  60.048s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22169_terminationG_0.smt2  |  34.028s  |  34.028s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22170_terminationG_0.smt2  |  57.395s  |  57.395s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22177_terminationG_0.smt2                                           |  59.855s  |  59.855s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22178_terminationG_0.smt2                                           |  59.395s  |  59.395s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           |  59.817s  |  59.817s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22182_terminationG_0.smt2                                           |  59.730s  |  59.730s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22183_terminationG_0.smt2                                           |  59.882s  |  59.882s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22184_terminationG_0.smt2                                           |  59.730s  |  59.730s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22189_edge_closing_0.smt2                                           |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__term_unfeasibility_0_0.smt2                                          |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__terminationQ_1_0.smt2                                                |  58.688s  |  58.688s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22199_terminationG_0.smt2                                       |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22200_terminationG_0.smt2                                       |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22201_terminationG_0.smt2                                       |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__p22206_edge_closing_0.smt2                                       |  28.254s  |  28.254s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__term_unfeasibility_1_0.smt2                                      |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__ChooseLife.c__terminationQ_0_0.smt2                                            |  59.178s  |  59.178s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22316_terminationG_0.smt2                                      |  59.775s  |  59.775s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22317_terminationG_0.smt2                                      |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22318_terminationG_0.smt2                                      |  60.004s  |  60.004s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22321_terminationG_0.smt2                                      |  59.319s  |  59.319s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22322_terminationG_0.smt2                                      |  59.462s  |  59.462s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv.c__p22323_terminationG_0.smt2                                      |  58.532s  |  58.532s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv2.c__p22248_safety_0.smt2                                           |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv2.c__p22249_safety_0.smt2                                           |  58.464s  |  58.464s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22271_terminationG_0.smt2                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22289_terminationG_0.smt2                                     |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22290_terminationG_0.smt2                                     |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22291_terminationG_0.smt2                                     |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22294_terminationG_0.smt2                                     |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22295_terminationG_0.smt2                                     |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|Stroeder_15__ComplInterv3.c__p22296_terminationG_0.smt2                                     |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22332_terminationG_0.smt2                                      |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22336_terminationG_0.smt2                                      |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22337_terminationG_0.smt2                                      |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22340_terminationG_0.smt2                                      |  59.182s  |  59.182s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22341_terminationG_0.smt2                                      |  59.853s  |  59.853s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      |  59.226s  |  59.226s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22345_terminationG_0.smt2                                      |  56.901s  |  56.901s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22346_terminationG_0.smt2                                      |  59.932s  |  59.932s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22347_terminationG_0.smt2                                      |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |  59.184s  |  59.184s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22351_terminationG_0.smt2                                      |  59.279s  |  59.279s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      |  59.934s  |  59.934s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22355_terminationG_0.smt2                                      |  60.021s  |  60.021s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22356_terminationG_0.smt2                                      |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22357_terminationG_0.smt2                                      |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22365_edge_closing_0.smt2                                      |  59.662s  |  59.662s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__terminationQ_3_0.smt2                                           |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__terminationS_1_0.smt2                                           |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8a-modified_true-termination.c__p22401_terminationG_0.smt2  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8b_true-termination.c__p22418_terminationG_0.smt2  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8b_true-termination.c__p22419_terminationG_0.smt2  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__CookSeeZuleger-TACAS2013-Fig8b_true-termination.c__p22424_terminationG_0.smt2  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22435_terminationG_0.smt2                                           |  59.651s  |  59.651s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22436_terminationG_0.smt2                                           |  59.581s  |  59.581s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22440_terminationG_0.smt2                                           |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           |  58.053s  |  58.053s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22442_terminationG_0.smt2                                           |  59.756s  |  59.756s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22445_terminationG_0.smt2                                           |  59.558s  |  59.558s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22446_terminationG_0.smt2                                           |  58.823s  |  58.823s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22447_terminationG_0.smt2                                           |  59.823s  |  59.823s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22450_terminationG_0.smt2                                           |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22451_terminationG_0.smt2                                           |  59.830s  |  59.830s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22452_terminationG_0.smt2                                           |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22455_terminationG_0.smt2                                           |  60.061s  |  60.061s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22456_terminationG_0.smt2                                           |  58.491s  |  58.491s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22457_terminationG_0.smt2                                           |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22460_terminationG_0.smt2                                           |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22461_terminationG_0.smt2                                           |  59.242s  |  59.242s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22462_terminationG_0.smt2                                           |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__terminationS_0_0.smt2                                                |  59.087s  |  59.087s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22480_terminationG_0.smt2                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22481_terminationG_0.smt2                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22484_terminationG_0.smt2                                  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22485_terminationG_0.smt2                                  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22491_terminationG_0.smt2                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22494_terminationG_0.smt2                                  |  58.066s  |  58.066s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22495_terminationG_0.smt2                                  |  58.923s  |  58.923s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22496_terminationG_0.smt2                                  |  58.958s  |  58.958s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22499_terminationG_0.smt2                                  |  59.877s  |  59.877s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22500_terminationG_0.smt2                                  |  59.341s  |  59.341s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22501_terminationG_0.smt2                                  |  58.910s  |  58.910s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22504_terminationG_0.smt2                                  |  60.465s  |  60.465s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22505_terminationG_0.smt2                                  |  59.810s  |  59.810s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22506_terminationG_0.smt2                                  |  59.463s  |  59.463s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22514_edge_closing_0.smt2                                  |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22516_edge_closing_0.smt2                                  |   7.223s  |   7.223s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22517_edge_closing_0.smt2                                  |  59.667s  |  59.667s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22520_edge_closing_0.smt2                                  |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22522_edge_closing_0.smt2                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__p22523_edge_closing_0.smt2                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__terminationS_1_0.smt2                                       |  59.508s  |  59.508s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__terminationS_2_0.smt2                                       |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__DivWithoutMinus.c__terminationS_3_0.smt2                                       |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22530_terminationG_0.smt2                                        |  55.706s  |  55.706s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22531_terminationG_0.smt2                                        |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        |  59.595s  |  59.595s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22535_terminationG_0.smt2                                        |  58.890s  |  58.890s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22536_terminationG_0.smt2                                        |  59.634s  |  59.634s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22537_terminationG_0.smt2                                        |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22540_terminationG_0.smt2                                        |  59.893s  |  59.893s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22541_terminationG_0.smt2                                        |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22542_terminationG_0.smt2                                        |  55.320s  |  55.320s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22545_terminationG_0.smt2                                        |  58.273s  |  58.273s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22546_terminationG_0.smt2                                        |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22547_terminationG_0.smt2                                        |  59.514s  |  59.514s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22550_terminationG_0.smt2                                        |  59.702s  |  59.702s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22551_terminationG_0.smt2                                        |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22552_terminationG_0.smt2                                        |  58.722s  |  58.722s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22555_terminationG_0.smt2                                        |  59.913s  |  59.913s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22556_terminationG_0.smt2                                        |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22557_terminationG_0.smt2                                        |  59.914s  |  59.914s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__terminationQ_5_0.smt2                                             |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22575_terminationG_0.smt2                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22594_terminationG_0.smt2                                              |   2.125s  |   2.125s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   4.278s  |   4.278s  |   0.000s  | 0.0%|
|Stroeder_15__Et2.c__p22608_terminationG_0.smt2                                              |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__Et2.c__p22609_terminationG_0.smt2                                              |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__Et2.c__p22613_edge_closing_0.smt2                                              |  59.117s  |  59.117s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |  57.279s  |  57.279s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22640_terminationG_0.smt2                                              |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22641_terminationG_0.smt2                                              |  59.859s  |  59.859s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22653_edge_closing_0.smt2                                              |  59.557s  |  59.557s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22658_edge_closing_0.smt2                                              |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22659_edge_closing_0.smt2                                              |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__terminationS_0_0.smt2                                                   |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22671_terminationG_0.smt2                                             |  59.932s  |  59.932s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22672_terminationG_0.smt2                                             |  59.156s  |  59.156s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22676_terminationG_0.smt2                                             |  59.750s  |  59.750s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22677_terminationG_0.smt2                                             |  60.019s  |  60.019s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22678_terminationG_0.smt2                                             |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22698_terminationG_0.smt2                                             |  60.014s  |  60.014s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22699_terminationG_0.smt2                                             |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22700_terminationG_0.smt2                                             |  60.021s  |  60.021s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22703_terminationG_0.smt2                                             |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22704_terminationG_0.smt2                                             |  59.894s  |  59.894s  |   0.000s  | 0.0%|
|Stroeder_15__Ex01.c__p22705_terminationG_0.smt2                                             |  58.524s  |  58.524s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22750_terminationG_0.smt2                                             |  59.913s  |  59.913s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22752_terminationG_0.smt2                                             |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |  58.828s  |  58.828s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |  56.986s  |  56.986s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |  59.683s  |  59.683s  |   0.000s  | 0.0%|
|Stroeder_15__Ex06.c__p22785_edge_closing_0.smt2                                             |  32.828s  |  32.828s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22818_terminationG_0.smt2                                             |   5.284s  |   5.284s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |  59.213s  |  59.213s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22820_terminationG_0.smt2                                             |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |  59.837s  |  59.837s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22835_terminationG_0.smt2                                        |  59.253s  |  59.253s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22836_terminationG_0.smt2                                        |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22837_terminationG_0.smt2                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22842_terminationG_0.smt2                                        |  59.568s  |  59.568s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22843_terminationG_0.smt2                                        |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22844_terminationG_0.smt2                                        |  57.066s  |  57.066s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22847_terminationG_0.smt2                                        |  60.020s  |  60.020s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22848_terminationG_0.smt2                                        |  56.133s  |  56.133s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22849_terminationG_0.smt2                                        |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |  59.635s  |  59.635s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22853_terminationG_0.smt2                                        |  59.791s  |  59.791s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        |  59.167s  |  59.167s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22857_terminationG_0.smt2                                        |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22858_terminationG_0.smt2                                        |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22859_terminationG_0.smt2                                        |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__terminationQ_3_0.smt2                                             |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22868_terminationG_0.smt2                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |  59.819s  |  59.819s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22873_terminationG_0.smt2                                        |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22879_terminationG_0.smt2                                        |  59.721s  |  59.721s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22880_terminationG_0.smt2                                        |  59.296s  |  59.296s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22883_terminationG_0.smt2                                        |  58.202s  |  58.202s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22884_terminationG_0.smt2                                        |  59.927s  |  59.927s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22885_terminationG_0.smt2                                        |  59.619s  |  59.619s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22888_terminationG_0.smt2                                        |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22889_terminationG_0.smt2                                        |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22890_terminationG_0.smt2                                        |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22893_terminationG_0.smt2                                        |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22895_terminationG_0.smt2                                        |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22896_terminationG_0.smt2                                        |  59.309s  |  59.309s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22899_terminationG_0.smt2                                        |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22900_terminationG_0.smt2                                        |  55.890s  |  55.890s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22901_terminationG_0.smt2                                        |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__terminationQ_3_0.smt2                                             |  58.748s  |  58.748s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p22994_terminationG_0.smt2                                             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23021_terminationG_0.smt2                                             |  59.187s  |  59.187s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23022_terminationG_0.smt2                                             |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23033_edge_closing_0.smt2                                             |  59.958s  |  59.958s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23038_edge_closing_0.smt2                                             |  60.008s  |  60.008s  |   0.000s  | 0.0%|
|Stroeder_15__Flip.c__p23039_edge_closing_0.smt2                                             |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22917_terminationG_0.smt2                                            |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22918_terminationG_0.smt2                                            |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22927_terminationG_0.smt2                                            |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22933_terminationG_0.smt2                                            |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22937_terminationG_0.smt2                                            |  60.018s  |  60.018s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22938_terminationG_0.smt2                                            |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22942_edge_closing_0.smt2                                            |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22953_edge_closing_0.smt2                                            |  59.389s  |  59.389s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22954_edge_closing_0.smt2                                            |  51.496s  |  51.496s  |   0.000s  | 0.0%|
|Stroeder_15__Flip2.c__p22955_edge_closing_0.smt2                                            |  55.175s  |  55.175s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23156_terminationG_0.smt2                                              |  55.062s  |  55.062s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23157_terminationG_0.smt2                                              |   0.737s  |   0.737s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23158_terminationG_0.smt2                                              |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23167_terminationG_0.smt2                                              |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23168_terminationG_0.smt2                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23171_terminationG_0.smt2                                              |  49.840s  |  49.840s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23172_terminationG_0.smt2                                              |   2.769s  |   2.769s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23178_terminationG_0.smt2                                              |   5.692s  |   5.692s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23179_terminationG_0.smt2                                              |   0.675s  |   0.675s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23180_terminationG_0.smt2                                              |   0.795s  |   0.795s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23183_terminationG_0.smt2                                              |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23184_terminationG_0.smt2                                              |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23185_terminationG_0.smt2                                              |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23188_terminationG_0.smt2                                              |  59.715s  |  59.715s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23189_terminationG_0.smt2                                              |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23190_terminationG_0.smt2                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23200_terminationG_0.smt2                                              |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23201_terminationG_0.smt2                                              |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23202_terminationG_0.smt2                                              |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23206_terminationG_0.smt2                                              |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23207_terminationG_0.smt2                                              |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23210_terminationG_0.smt2                                              |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23211_terminationG_0.smt2                                              |  58.819s  |  58.819s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23212_terminationG_0.smt2                                              |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23215_edge_closing_0.smt2                                              |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23216_edge_closing_0.smt2                                              |  59.489s  |  59.489s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23222_edge_closing_0.smt2                                              |  31.731s  |  31.731s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23223_edge_closing_0.smt2                                              |  31.060s  |  31.060s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_0_0.smt2                                                   |  56.145s  |  56.145s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_1_0.smt2                                                   |  59.648s  |  59.648s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |  58.805s  |  58.805s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_8_0.smt2                                                   |  59.349s  |  59.349s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23102_terminationG_0.smt2                                             |   0.877s  |   0.877s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23106_terminationG_0.smt2                                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23107_terminationG_0.smt2                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23110_terminationG_0.smt2                                             |  19.058s  |  19.058s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23111_terminationG_0.smt2                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23112_terminationG_0.smt2                                             |  11.625s  |  11.625s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23116_terminationG_0.smt2                                             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23117_terminationG_0.smt2                                             |   3.265s  |   3.265s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23120_terminationG_0.smt2                                             |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23121_terminationG_0.smt2                                             |  59.913s  |  59.913s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23122_terminationG_0.smt2                                             |  55.987s  |  55.987s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23125_edge_closing_0.smt2                                             |   0.519s  |   0.519s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23126_edge_closing_0.smt2                                             |  47.402s  |  47.402s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23132_edge_closing_0.smt2                                             |   1.484s  |   1.484s  |   0.000s  | 0.0%|
|Stroeder_15__GCD2.c__p23133_edge_closing_0.smt2                                             |  58.913s  |  58.913s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23050_terminationG_0.smt2                                            |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23054_terminationG_0.smt2                                            |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23055_terminationG_0.smt2                                            |  59.872s  |  59.872s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23056_terminationG_0.smt2                                            |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23059_terminationG_0.smt2                                            |  59.747s  |  59.747s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23060_terminationG_0.smt2                                            |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23061_terminationG_0.smt2                                            |  59.628s  |  59.628s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23064_terminationG_0.smt2                                            |  62.829s  |  62.829s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23065_terminationG_0.smt2                                            |  59.896s  |  59.896s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23066_terminationG_0.smt2                                            |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23069_terminationG_0.smt2                                            |  59.595s  |  59.595s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23070_terminationG_0.smt2                                            |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23071_terminationG_0.smt2                                            |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23074_terminationG_0.smt2                                            |  59.633s  |  59.633s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23075_terminationG_0.smt2                                            |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23076_terminationG_0.smt2                                            |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23080_edge_closing_0.smt2                                            |   8.524s  |   8.524s  |   0.000s  | 0.0%|
|Stroeder_15__Gauss.c__p23084_edge_closing_0.smt2                                            |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|Stroeder_15__Gothenburg_true-termination.c__p23242_terminationG_0.smt2                      |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|Stroeder_15__Gothenburg_true-termination.c__p23243_terminationG_0.smt2                      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23267_terminationG_0.smt2  |  59.113s  |  59.113s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23268_terminationG_0.smt2  |  20.311s  |  20.311s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23269_terminationG_0.smt2  |  59.893s  |  59.893s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23272_terminationG_0.smt2  |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23273_terminationG_0.smt2  |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23274_terminationG_0.smt2  |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23277_edge_closing_0.smt2  |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23278_edge_closing_0.smt2  |  59.868s  |  59.868s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23280_edge_closing_0.smt2  |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23281_edge_closing_0.smt2  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23282_edge_closing_0.smt2  |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23283_edge_closing_0.smt2  |  59.873s  |  59.873s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23284_edge_closing_0.smt2  |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23285_edge_closing_0.smt2  |  59.664s  |  59.664s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23288_edge_closing_0.smt2  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23291_edge_closing_0.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23309_edge_closing_0.smt2  |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23310_edge_closing_0.smt2  |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23319_edge_closing_0.smt2  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23321_edge_closing_0.smt2  |  59.570s  |  59.570s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23322_edge_closing_0.smt2  |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23328_edge_closing_0.smt2  |   2.758s  |   2.758s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23330_edge_closing_0.smt2  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23331_edge_closing_0.smt2  |   0.974s  |   0.974s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23333_edge_closing_0.smt2  |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23334_edge_closing_0.smt2  |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23336_edge_closing_0.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23339_edge_closing_0.smt2  |  59.730s  |  59.730s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23340_edge_closing_0.smt2  |  59.486s  |  59.486s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23343_edge_closing_0.smt2  |   1.187s  |   1.187s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23345_edge_closing_0.smt2  |   0.981s  |   0.981s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23346_edge_closing_0.smt2  |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23348_edge_closing_0.smt2  |  59.860s  |  59.860s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23349_edge_closing_0.smt2  |  58.684s  |  58.684s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23354_edge_closing_0.smt2  |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23367_edge_closing_0.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23403_edge_closing_0.smt2  |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23406_edge_closing_0.smt2  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23408_edge_closing_0.smt2  |  59.826s  |  59.826s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23409_edge_closing_0.smt2  |  59.788s  |  59.788s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23412_edge_closing_0.smt2  |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23421_edge_closing_0.smt2  |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23429_edge_closing_0.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23430_edge_closing_0.smt2  |   4.462s  |   4.462s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23431_edge_closing_0.smt2  |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23432_edge_closing_0.smt2  |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23433_edge_closing_0.smt2  |   9.253s  |   9.253s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23435_edge_closing_0.smt2  |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23436_edge_closing_0.smt2  |  59.630s  |  59.630s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23438_edge_closing_0.smt2  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23439_edge_closing_0.smt2  |   1.593s  |   1.593s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23441_edge_closing_0.smt2  |   1.199s  |   1.199s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23442_edge_closing_0.smt2  |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23443_edge_closing_0.smt2  |  59.800s  |  59.800s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23444_edge_closing_0.smt2  |   7.435s  |   7.435s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23445_edge_closing_0.smt2  |  59.858s  |  59.858s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23447_edge_closing_0.smt2  |  60.060s  |  60.060s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23448_edge_closing_0.smt2  |  59.922s  |  59.922s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23450_edge_closing_0.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23451_edge_closing_0.smt2  |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23459_edge_closing_0.smt2  |   4.474s  |   4.474s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23460_edge_closing_0.smt2  |  51.582s  |  51.582s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23471_edge_closing_0.smt2  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23473_edge_closing_0.smt2  |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23474_edge_closing_0.smt2  |  59.701s  |  59.701s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23475_edge_closing_0.smt2  |  59.568s  |  59.568s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23477_edge_closing_0.smt2  |   0.987s  |   0.987s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23478_edge_closing_0.smt2  |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23480_edge_closing_0.smt2  |   4.328s  |   4.328s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |  59.652s  |  59.652s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23482_edge_closing_0.smt2  |  59.579s  |  59.579s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23483_edge_closing_0.smt2  |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23484_edge_closing_0.smt2  |  59.865s  |  59.865s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23486_edge_closing_0.smt2  |   0.888s  |   0.888s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23487_edge_closing_0.smt2  |  59.791s  |  59.791s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23493_edge_closing_0.smt2  |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23501_edge_closing_0.smt2  |   0.494s  |   0.494s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23502_edge_closing_0.smt2  |   1.651s  |   1.651s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23510_edge_closing_0.smt2  |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23522_edge_closing_0.smt2  |   1.243s  |   1.243s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23523_edge_closing_0.smt2  |   2.831s  |   2.831s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23531_edge_closing_0.smt2  |   6.325s  |   6.325s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23532_edge_closing_0.smt2  |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23543_edge_closing_0.smt2  |   0.998s  |   0.998s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23544_edge_closing_0.smt2  |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23550_edge_closing_0.smt2  |   2.148s  |   2.148s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23551_edge_closing_0.smt2  |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23559_edge_closing_0.smt2  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23560_edge_closing_0.smt2  |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23565_edge_closing_0.smt2  |   6.227s  |   6.227s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23566_edge_closing_0.smt2  |  58.293s  |  58.293s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23577_edge_closing_0.smt2  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23602_edge_closing_0.smt2  |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23611_edge_closing_0.smt2  |   4.065s  |   4.065s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23616_edge_closing_0.smt2  |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23617_edge_closing_0.smt2  |  58.212s  |  58.212s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23620_edge_closing_0.smt2  |   6.604s  |   6.604s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23628_edge_closing_0.smt2  |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23629_edge_closing_0.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23638_edge_closing_0.smt2  |   0.706s  |   0.706s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23646_edge_closing_0.smt2  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23647_edge_closing_0.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23649_edge_closing_0.smt2  |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23650_edge_closing_0.smt2  |  59.405s  |  59.405s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23653_edge_closing_0.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23662_edge_closing_0.smt2  |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23667_edge_closing_0.smt2  |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23673_edge_closing_0.smt2  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23676_edge_closing_0.smt2  |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23677_edge_closing_0.smt2  |  59.597s  |  59.597s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23679_edge_closing_0.smt2  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23680_edge_closing_0.smt2  |   1.195s  |   1.195s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23686_edge_closing_0.smt2  |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23692_edge_closing_0.smt2  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23693_edge_closing_0.smt2  |   1.082s  |   1.082s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23699_edge_closing_0.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23701_edge_closing_0.smt2  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23702_edge_closing_0.smt2  |   3.777s  |   3.777s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23703_edge_closing_0.smt2  |  59.932s  |  59.932s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23704_edge_closing_0.smt2  |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23705_edge_closing_0.smt2  |  58.381s  |  58.381s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23707_edge_closing_0.smt2  |  60.278s  |  60.278s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23708_edge_closing_0.smt2  |  54.301s  |  54.301s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23710_edge_closing_0.smt2  |   1.136s  |   1.136s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23711_edge_closing_0.smt2  |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23713_edge_closing_0.smt2  |   1.508s  |   1.508s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23714_edge_closing_0.smt2  |  51.605s  |  51.605s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23715_edge_closing_0.smt2  |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23716_edge_closing_0.smt2  |   7.275s  |   7.275s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23717_edge_closing_0.smt2  |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23719_edge_closing_0.smt2  |  58.760s  |  58.760s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23720_edge_closing_0.smt2  |  59.626s  |  59.626s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23722_edge_closing_0.smt2  |   1.035s  |   1.035s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23723_edge_closing_0.smt2  |   5.677s  |   5.677s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23731_edge_closing_0.smt2  |  60.010s  |  60.010s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23732_edge_closing_0.smt2  |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23734_edge_closing_0.smt2  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23735_edge_closing_0.smt2  |  59.906s  |  59.906s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23750_edge_closing_0.smt2  |   4.912s  |   4.912s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23751_edge_closing_0.smt2  |  60.028s  |  60.028s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23752_edge_closing_0.smt2  |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23753_edge_closing_0.smt2  |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23754_edge_closing_0.smt2  |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23756_edge_closing_0.smt2  |   1.005s  |   1.005s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |  60.072s  |  60.072s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23759_edge_closing_0.smt2  |  16.824s  |  16.824s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23760_edge_closing_0.smt2  |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23765_edge_closing_0.smt2  |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23766_edge_closing_0.smt2  |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23774_edge_closing_0.smt2  |   4.537s  |   4.537s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23775_edge_closing_0.smt2  |  56.840s  |  56.840s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23795_edge_closing_0.smt2  |   1.447s  |   1.447s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23796_edge_closing_0.smt2  |  59.296s  |  59.296s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23853_terminationG_0.smt2  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23856_terminationG_0.smt2  |  59.075s  |  59.075s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23857_terminationG_0.smt2  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23858_terminationG_0.smt2  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23863_terminationG_0.smt2  |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23864_terminationG_0.smt2  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23872_terminationG_0.smt2  |   1.470s  |   1.470s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23873_terminationG_0.smt2  |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23877_terminationG_0.smt2  |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23878_terminationG_0.smt2  |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23886_terminationG_0.smt2  |   0.701s  |   0.701s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23887_terminationG_0.smt2  |  58.488s  |  58.488s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23893_terminationG_0.smt2  |   7.208s  |   7.208s  |   0.000s  | 0.0%|
|Stroeder_15__LarrazOliverasRodriguez-CarbonellRubio-FMCAD2013-Fig1_true-termination.c__p23894_terminationG_0.smt2  |  59.625s  |  59.625s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23905_terminationG_0.smt2                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23906_terminationG_0.smt2                                              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23910_terminationG_0.smt2                                              |   3.060s  |   3.060s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23911_terminationG_0.smt2                                              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23918_terminationG_0.smt2                                              |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23923_terminationG_0.smt2                                              |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23927_terminationG_0.smt2                                              |   1.988s  |   1.988s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23933_terminationG_0.smt2                                              |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23941_terminationG_0.smt2                                              |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23942_terminationG_0.smt2                                              |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23947_terminationG_0.smt2                                              |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23951_terminationG_0.smt2                                              |  59.902s  |  59.902s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23952_terminationG_0.smt2                                              |  58.976s  |  58.976s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23956_edge_closing_0.smt2                                              |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|Stroeder_15__Lcm.c__p23960_edge_closing_0.smt2                                              |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-TACAS2014-Ex7_true-termination.c__p23983_terminationG_0.smt2     |   4.888s  |   4.888s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-TACAS2014-Fig1_true-termination.c__p24009_terminationG_0.smt2    |   3.283s  |   3.283s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24028_terminationG_0.smt2      |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24029_terminationG_0.smt2      |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24032_terminationG_0.smt2      |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24033_terminationG_0.smt2      |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24034_terminationG_0.smt2      |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24038_terminationG_0.smt2      |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24039_terminationG_0.smt2      |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24042_terminationG_0.smt2      |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24043_terminationG_0.smt2      |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24044_terminationG_0.smt2      |  59.509s  |  59.509s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24047_terminationG_0.smt2      |  59.402s  |  59.402s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24048_terminationG_0.smt2      |  58.714s  |  58.714s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24049_terminationG_0.smt2      |  55.578s  |  55.578s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24052_edge_closing_0.smt2      |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24053_edge_closing_0.smt2      |  60.052s  |  60.052s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   1.662s  |   1.662s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24057_edge_closing_0.smt2      |  59.931s  |  59.931s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24084_terminationG_0.smt2      |  59.224s  |  59.224s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24085_terminationG_0.smt2      |  59.123s  |  59.123s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24086_terminationG_0.smt2      |  55.021s  |  55.021s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24090_terminationG_0.smt2      |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24091_terminationG_0.smt2      |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24094_terminationG_0.smt2      |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24095_terminationG_0.smt2      |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24096_terminationG_0.smt2      |  59.882s  |  59.882s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24099_terminationG_0.smt2      |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24100_terminationG_0.smt2      |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24101_terminationG_0.smt2      |  59.817s  |  59.817s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24121_terminationG_0.smt2        |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |  59.802s  |  59.802s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24142_terminationG_0.smt2                                          |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24143_terminationG_0.smt2                                          |  59.509s  |  59.509s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24146_terminationG_0.smt2                                          |  59.722s  |  59.722s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24147_terminationG_0.smt2                                          |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24148_terminationG_0.smt2                                          |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24151_terminationG_0.smt2                                          |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24152_terminationG_0.smt2                                          |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24153_terminationG_0.smt2                                          |  59.225s  |  59.225s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24156_terminationG_0.smt2                                          |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24157_terminationG_0.smt2                                          |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24158_terminationG_0.smt2                                          |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__terminationQ_3_0.smt2                                               |  59.647s  |  59.647s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |  59.055s  |  59.055s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24190_terminationG_0.smt2                                          |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24191_terminationG_0.smt2                                          |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24194_terminationG_0.smt2                                          |  59.237s  |  59.237s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24195_terminationG_0.smt2                                          |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24196_terminationG_0.smt2                                          |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24211_terminationG_0.smt2                                          |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24212_terminationG_0.smt2                                          |  58.486s  |  58.486s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24213_terminationG_0.smt2                                          |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24216_terminationG_0.smt2                                          |  54.124s  |  54.124s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24217_terminationG_0.smt2                                          |  59.792s  |  59.792s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie2.c__p24218_terminationG_0.smt2                                          |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24236_terminationG_0.smt2           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24237_terminationG_0.smt2           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24238_terminationG_0.smt2           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24241_terminationG_0.smt2           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24242_terminationG_0.smt2           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |  58.326s  |  58.326s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24247_terminationG_0.smt2           |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24248_terminationG_0.smt2           |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24250_edge_closing_0.smt2           |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24252_edge_closing_0.smt2           |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|Stroeder_15__McCarthyIterative.c__term_unfeasibility_0_0.smt2                               |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__MenloPark_true-termination.c__p24273_terminationG_0.smt2                       |  24.411s  |  24.411s  |   0.000s  | 0.0%|
|Stroeder_15__MenloPark_true-termination.c__p24274_terminationG_0.smt2                       |  59.222s  |  59.222s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24281_terminationG_0.smt2                                           |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24282_terminationG_0.smt2                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24283_terminationG_0.smt2                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24288_terminationG_0.smt2                                           |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24289_terminationG_0.smt2                                           |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24290_terminationG_0.smt2                                           |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24301_terminationG_0.smt2                                           |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24306_terminationG_0.smt2                                           |  59.933s  |  59.933s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24309_terminationG_0.smt2                                           |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24310_terminationG_0.smt2                                           |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24311_terminationG_0.smt2                                           |  59.771s  |  59.771s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24314_terminationG_0.smt2                                           |  59.512s  |  59.512s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24315_terminationG_0.smt2                                           |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24316_terminationG_0.smt2                                           |  59.241s  |  59.241s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24319_terminationG_0.smt2                                           |  52.629s  |  52.629s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24320_terminationG_0.smt2                                           |  59.277s  |  59.277s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24321_terminationG_0.smt2                                           |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24324_terminationG_0.smt2                                           |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24325_terminationG_0.smt2                                           |  58.545s  |  58.545s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24326_terminationG_0.smt2                                           |  59.774s  |  59.774s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24329_terminationG_0.smt2                                           |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24330_terminationG_0.smt2                                           |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24331_terminationG_0.smt2                                           |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24334_terminationG_0.smt2                                           |  58.601s  |  58.601s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24335_terminationG_0.smt2                                           |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24336_terminationG_0.smt2                                           |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24339_edge_closing_0.smt2                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|Stroeder_15__Middle.c__p24344_edge_closing_0.smt2                                           |  19.182s  |  19.182s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24368_terminationG_0.smt2                                     |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24373_terminationG_0.smt2                                     |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24374_terminationG_0.smt2                                     |   3.631s  |   3.631s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24377_terminationG_0.smt2                                     |  55.978s  |  55.978s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24378_terminationG_0.smt2                                     |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24379_terminationG_0.smt2                                     |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24382_terminationG_0.smt2                                     |  59.507s  |  59.507s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24383_terminationG_0.smt2                                     |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24384_terminationG_0.smt2                                     |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24387_terminationG_0.smt2                                     |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24388_terminationG_0.smt2                                     |  60.018s  |  60.018s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24389_terminationG_0.smt2                                     |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24392_terminationG_0.smt2                                     |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24393_terminationG_0.smt2                                     |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24394_terminationG_0.smt2                                     |  57.824s  |  57.824s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24397_terminationG_0.smt2                                     |  59.601s  |  59.601s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24398_terminationG_0.smt2                                     |  60.106s  |  60.106s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24399_terminationG_0.smt2                                     |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24402_terminationG_0.smt2                                     |  60.482s  |  60.482s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24403_terminationG_0.smt2                                     |  59.262s  |  59.262s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24404_terminationG_0.smt2                                     |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24407_terminationG_0.smt2                                     |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24408_terminationG_0.smt2                                     |  59.251s  |  59.251s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24409_terminationG_0.smt2                                     |  59.770s  |  59.770s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24413_edge_closing_0.smt2                                     |  14.197s  |  14.197s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24415_edge_closing_0.smt2                                     |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24422_edge_closing_0.smt2                                     |  12.053s  |  12.053s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  23.460s  |  23.460s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24426_edge_closing_0.smt2                                     |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24432_edge_closing_0.smt2                                     |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24443_edge_closing_0.smt2                                     |   0.867s  |   0.867s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24446_edge_closing_0.smt2                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24447_edge_closing_0.smt2                                     |  59.674s  |  59.674s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24449_edge_closing_0.smt2                                     |  56.878s  |  56.878s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24450_edge_closing_0.smt2                                     |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__terminationQ_5_0.smt2                                          |  57.509s  |  57.509s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__terminationS_0_0.smt2                                          |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__terminationS_1_0.smt2                                          |  59.788s  |  59.788s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24464_terminationG_0.smt2                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24482_terminationG_0.smt2                                  |  59.871s  |  59.871s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |  59.132s  |  59.132s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24484_terminationG_0.smt2                                  |  59.668s  |  59.668s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationQ_0_0.smt2                                       |  60.079s  |  60.079s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |  57.813s  |  57.813s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_1_0.smt2                                       |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Stroeder_15__NO_03.c__p24634_terminationG_0.smt2                                            |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__NO_03.c__terminationQ_0_0.smt2                                                 |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24648_safety_0.smt2                                                  |  58.152s  |  58.152s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24649_safety_0.smt2                                                  |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24650_safety_0.smt2                                                  |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24651_safety_0.smt2                                                  |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24653_safety_0.smt2                                                  |  57.214s  |  57.214s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__p24654_safety_0.smt2                                                  |  59.504s  |  59.504s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__term_unfeasibility_0_0.smt2                                           |   1.156s  |   1.156s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__term_unfeasibility_2_0.smt2                                           |   0.889s  |   0.889s  |   0.000s  | 0.0%|
|Stroeder_15__NO_04.c__term_unfeasibility_4_0.smt2                                           |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24669_terminationG_0.smt2                                            |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24671_terminationG_0.smt2                                            |  57.121s  |  57.121s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24674_terminationG_0.smt2                                            |  59.411s  |  59.411s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24675_terminationG_0.smt2                                            |  59.931s  |  59.931s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24676_terminationG_0.smt2                                            |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24679_terminationG_0.smt2                                            |  59.917s  |  59.917s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24680_terminationG_0.smt2                                            |  59.922s  |  59.922s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24681_terminationG_0.smt2                                            |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24684_terminationG_0.smt2                                            |  59.928s  |  59.928s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24685_terminationG_0.smt2                                            |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24686_terminationG_0.smt2                                            |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24689_terminationG_0.smt2                                            |  58.156s  |  58.156s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24690_terminationG_0.smt2                                            |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24691_terminationG_0.smt2                                            |  58.851s  |  58.851s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24694_terminationG_0.smt2                                            |  60.022s  |  60.022s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24695_terminationG_0.smt2                                            |  58.874s  |  58.874s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24696_terminationG_0.smt2                                            |  55.443s  |  55.443s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__terminationQ_5_0.smt2                                                 |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24711_terminationG_0.smt2                                            |  59.228s  |  59.228s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24713_terminationG_0.smt2                                            |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24716_terminationG_0.smt2                                            |  59.339s  |  59.339s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24717_terminationG_0.smt2                                            |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24718_terminationG_0.smt2                                            |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24721_terminationG_0.smt2                                            |  58.940s  |  58.940s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24722_terminationG_0.smt2                                            |  59.927s  |  59.927s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24723_terminationG_0.smt2                                            |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24726_terminationG_0.smt2                                            |  59.175s  |  59.175s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |  59.919s  |  59.919s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24728_terminationG_0.smt2                                            |  59.011s  |  59.011s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24730_terminationG_0.smt2                                            |  59.911s  |  59.911s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24732_terminationG_0.smt2                                            |  59.886s  |  59.886s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24733_terminationG_0.smt2                                            |  59.837s  |  59.837s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24737_edge_closing_0.smt2                                            |  48.928s  |  48.928s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationQ_4_0.smt2                                                 |  59.433s  |  59.433s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |  60.026s  |  60.026s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_1_0.smt2                                                 |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24748_terminationG_0.smt2                                            |  59.398s  |  59.398s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |  57.990s  |  57.990s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24750_terminationG_0.smt2                                            |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24752_edge_closing_0.smt2                                            |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__term_unfeasibility_0_0.smt2                                           |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__terminationQ_0_0.smt2                                                 |  58.043s  |  58.043s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__terminationS_0_0.smt2                                                 |  59.958s  |  59.958s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__terminationS_1_0.smt2                                                 |  59.505s  |  59.505s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24780_terminationG_0.smt2                                            |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24781_terminationG_0.smt2                                            |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24782_terminationG_0.smt2                                            |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24785_edge_closing_0.smt2                                            |  22.733s  |  22.733s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__p24786_edge_closing_0.smt2                                            |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__term_unfeasibility_0_0.smt2                                           |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__NO_22.c__terminationS_0_0.smt2                                                 |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24797_terminationG_0.smt2                                            |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24798_terminationG_0.smt2                                            |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24799_terminationG_0.smt2                                            |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__p24804_edge_closing_0.smt2                                            |  58.641s  |  58.641s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__term_unfeasibility_0_0.smt2                                           |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__terminationQ_0_0.smt2                                                 |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__terminationS_0_0.smt2                                                 |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|Stroeder_15__NO_23.c__terminationS_1_0.smt2                                                 |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|Stroeder_15__NO_24.c__p24815_terminationG_0.smt2                                            |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__NO_24.c__p24816_terminationG_0.smt2                                            |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__NO_24.c__p24820_edge_closing_0.smt2                                            |   5.647s  |   5.647s  |   0.000s  | 0.0%|
|Stroeder_15__NarrowKonv.c__p24579_edge_closing_0.smt2                                       |   4.651s  |   4.651s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24515_terminationG_0.smt2                                        |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24516_terminationG_0.smt2                                        |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24519_terminationG_0.smt2                                        |  39.489s  |  39.489s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24520_terminationG_0.smt2                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24521_terminationG_0.smt2                                        |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24524_terminationG_0.smt2                                        |  41.933s  |  41.933s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24525_terminationG_0.smt2                                        |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24526_terminationG_0.smt2                                        |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24529_terminationG_0.smt2                                        |  60.032s  |  60.032s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24530_terminationG_0.smt2                                        |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24531_terminationG_0.smt2                                        |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24534_terminationG_0.smt2                                        |  57.026s  |  57.026s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24535_terminationG_0.smt2                                        |  60.045s  |  60.045s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24536_terminationG_0.smt2                                        |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24539_terminationG_0.smt2                                        |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24540_terminationG_0.smt2                                        |  56.008s  |  56.008s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24541_terminationG_0.smt2                                        |  59.819s  |  59.819s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24544_edge_closing_0.smt2                                        |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24545_edge_closing_0.smt2                                        |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24547_edge_closing_0.smt2                                        |  59.018s  |  59.018s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24548_edge_closing_0.smt2                                        |  59.407s  |  59.407s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24549_edge_closing_0.smt2                                        |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24551_edge_closing_0.smt2                                        |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__p24552_edge_closing_0.smt2                                        |  59.891s  |  59.891s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__term_unfeasibility_2_0.smt2                                       |  58.942s  |  58.942s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationQ_0_0.smt2                                             |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_0_0.smt2                                             |  59.876s  |  59.876s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_1_0.smt2                                             |  59.076s  |  59.076s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_2_0.smt2                                             |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__Narrowing.c__terminationS_3_0.smt2                                             |  59.712s  |  59.712s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24837_terminationG_0.smt2                |  59.764s  |  59.764s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24838_terminationG_0.smt2                |  59.846s  |  59.846s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24841_terminationG_0.smt2                |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24843_terminationG_0.smt2                |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24848_edge_closing_0.smt2                |  10.198s  |  10.198s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24888_terminationG_0.smt2                |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24896_terminationG_0.smt2                |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24897_terminationG_0.smt2                |   5.682s  |   5.682s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24907_terminationG_0.smt2                |  54.185s  |  54.185s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24908_terminationG_0.smt2                |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24918_terminationG_0.smt2                |  59.828s  |  59.828s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24919_terminationG_0.smt2                |   3.629s  |   3.629s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24923_terminationG_0.smt2                |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24924_terminationG_0.smt2                |   5.638s  |   5.638s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |  59.381s  |  59.381s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24932_edge_closing_0.smt2                |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24935_edge_closing_0.smt2                |  59.106s  |  59.106s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24937_edge_closing_0.smt2                |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24938_edge_closing_0.smt2                |  60.031s  |  60.031s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24939_edge_closing_0.smt2                |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24941_edge_closing_0.smt2                |  59.895s  |  59.895s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24949_terminationG_0.smt2                |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24950_terminationG_0.smt2                |  53.775s  |  53.775s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24953_terminationG_0.smt2                |  59.902s  |  59.902s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24954_terminationG_0.smt2                |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                |  59.881s  |  59.881s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24957_terminationG_0.smt2                |  61.769s  |  61.769s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24959_terminationG_0.smt2                |  59.926s  |  59.926s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24960_terminationG_0.smt2                |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24967_terminationG_0.smt2                |  59.085s  |  59.085s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24969_terminationG_0.smt2                |  59.886s  |  59.886s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24970_terminationG_0.smt2                |  59.713s  |  59.713s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24973_terminationG_0.smt2                |  58.860s  |  58.860s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24974_terminationG_0.smt2                |  58.158s  |  58.158s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24975_terminationG_0.smt2                |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   0.862s  |   0.862s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24982_edge_closing_0.smt2                |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24983_edge_closing_0.smt2                |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__terminationQ_4_0.smt2                     |  59.858s  |  59.858s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p24995_terminationG_0.smt2          |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p24996_terminationG_0.smt2          |  59.831s  |  59.831s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p24997_terminationG_0.smt2          |  58.864s  |  58.864s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p25000_terminationG_0.smt2          |  58.449s  |  58.449s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p25001_terminationG_0.smt2          |  59.641s  |  59.641s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple2_false-termination.c__p25002_terminationG_0.smt2          |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple3_false-termination.c__p25033_terminationG_0.smt2          |  60.048s  |  60.048s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple3_false-termination.c__p25034_terminationG_0.smt2          |  59.319s  |  59.319s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25060_terminationG_0.smt2          |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25061_terminationG_0.smt2          |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25062_terminationG_0.smt2          |  59.341s  |  59.341s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25065_terminationG_0.smt2          |  59.905s  |  59.905s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25066_terminationG_0.smt2          |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25067_terminationG_0.smt2          |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25070_terminationG_0.smt2          |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25071_terminationG_0.smt2          |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25072_terminationG_0.smt2          |  58.688s  |  58.688s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25075_terminationG_0.smt2          |  58.140s  |  58.140s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25076_terminationG_0.smt2          |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25077_terminationG_0.smt2          |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__p25081_edge_closing_0.smt2          |   8.422s  |   8.422s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple4_false-termination.c__terminationQ_3_0.smt2               |  59.043s  |  59.043s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple5_false-termination.c__p25094_terminationG_0.smt2          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple5_false-termination.c__p25098_terminationG_0.smt2          |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple5_false-termination.c__p25099_terminationG_0.smt2          |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25119_terminationG_0.smt2          |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25120_terminationG_0.smt2          |  59.692s  |  59.692s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          |  59.901s  |  59.901s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25124_terminationG_0.smt2          |  57.196s  |  57.196s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25125_terminationG_0.smt2          |  59.203s  |  59.203s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25126_terminationG_0.smt2          |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25130_edge_closing_0.smt2          |   2.000s  |   2.000s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple7_false-termination.c__p25147_terminationG_0.smt2          |  59.433s  |  59.433s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple7_false-termination.c__p25148_terminationG_0.smt2          |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple7_false-termination.c__p25159_edge_closing_0.smt2          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25174_terminationG_0.smt2          |  59.512s  |  59.512s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25175_terminationG_0.smt2          |  59.896s  |  59.896s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25176_terminationG_0.smt2          |  58.885s  |  58.885s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25179_terminationG_0.smt2          |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25180_terminationG_0.smt2          |  59.506s  |  59.506s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25181_terminationG_0.smt2          |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25184_edge_closing_0.smt2          |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |  57.886s  |  57.886s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25189_edge_closing_0.smt2          |  59.508s  |  59.508s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25202_terminationG_0.smt2          |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |  59.454s  |  59.454s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25336_terminationG_0.smt2                                         |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25382_terminationG_0.smt2                                         |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25387_terminationG_0.smt2                                         |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25391_terminationG_0.smt2                                         |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|Stroeder_15__PlusSwap.c__p25392_terminationG_0.smt2                                         |   7.166s  |   7.166s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig1_true-termination.c__p25400_terminationG_0.smt2  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25419_terminationG_0.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25424_terminationG_0.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25425_terminationG_0.smt2  |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25430_terminationG_0.smt2  |  59.933s  |  59.933s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25433_terminationG_0.smt2  |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25434_terminationG_0.smt2  |  59.918s  |  59.918s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25435_terminationG_0.smt2  |  57.434s  |  57.434s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25440_terminationG_0.smt2  |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25441_terminationG_0.smt2  |  59.200s  |  59.200s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25442_terminationG_0.smt2  |  59.715s  |  59.715s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25447_terminationG_0.smt2  |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25448_terminationG_0.smt2  |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25449_terminationG_0.smt2  |  59.595s  |  59.595s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25476_terminationG_0.smt2  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25479_terminationG_0.smt2  |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25480_terminationG_0.smt2  |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25481_terminationG_0.smt2  |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25484_edge_closing_0.smt2  |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__PodelskiRybalchenko-VMCAI2004-Ex2_true-termination.c__p25485_edge_closing_0.smt2  |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25505_terminationG_0.smt2                      |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25506_terminationG_0.smt2                      |  30.554s  |  30.554s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25507_terminationG_0.smt2                      |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |   0.958s  |   0.958s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25519_terminationG_0.smt2                      |  58.373s  |  58.373s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25530_terminationG_0.smt2                      |  59.672s  |  59.672s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25531_terminationG_0.smt2                      |  10.930s  |  10.930s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25532_terminationG_0.smt2                      |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25536_terminationG_0.smt2                      |   2.398s  |   2.398s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25537_terminationG_0.smt2                      |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25541_terminationG_0.smt2                      |   9.983s  |   9.983s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25542_terminationG_0.smt2                      |  59.886s  |  59.886s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25546_terminationG_0.smt2                      |   2.022s  |   2.022s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25547_terminationG_0.smt2                      |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25559_terminationG_0.smt2                      |   2.924s  |   2.924s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25560_terminationG_0.smt2                      |   2.558s  |   2.558s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25566_terminationG_0.smt2                      |  57.807s  |  57.807s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25567_terminationG_0.smt2                      |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|Stroeder_15__Rotation180_false-termination.c__p25579_terminationG_0.smt2                    |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|Stroeder_15__Rotation180_false-termination.c__p25580_terminationG_0.smt2                    |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25604_terminationG_0.smt2                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25608_terminationG_0.smt2                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25609_terminationG_0.smt2                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25619_terminationG_0.smt2                                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25622_terminationG_0.smt2                                           |  59.842s  |  59.842s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           |  59.748s  |  59.748s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25624_terminationG_0.smt2                                           |  58.620s  |  58.620s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25629_edge_closing_0.smt2                                           |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25637_edge_closing_0.smt2                                           |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__terminationQ_0_0.smt2                                                |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__terminationS_0_0.smt2                                                |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__terminationS_1_0.smt2                                                |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Stroeder_15__Swingers.c__p26084_terminationG_0.smt2                                         |  59.537s  |  59.537s  |   0.000s  | 0.0%|
|Stroeder_15__Swingers.c__p26085_terminationG_0.smt2                                         |  58.115s  |  58.115s  |   0.000s  | 0.0%|
|Stroeder_15__Swingers.c__p26089_edge_closing_0.smt2                                         |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-BranchesToLoop_true-termination.c__p26120_terminationG_0.smt2         |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-BranchesToLoop_true-termination.c__p26125_terminationG_0.smt2         |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-MultiBranchesToLoop_true-termination.c__p26134_terminationG_0.smt2    |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Stroeder_15__Toulouse-MultiBranchesToLoop_true-termination.c__p26139_terminationG_0.smt2    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26151_terminationG_0.smt2                                          |  59.877s  |  59.877s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26152_terminationG_0.smt2                                          |  59.621s  |  59.621s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26153_terminationG_0.smt2                                          |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26156_terminationG_0.smt2                                          |  59.437s  |  59.437s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26157_terminationG_0.smt2                                          |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__TrueDiv.c__p26158_terminationG_0.smt2                                          |  58.255s  |  58.255s  |   0.000s  | 0.0%|
|Stroeder_15__TwoFloatInterv.c__p26170_safety_0.smt2                                         |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|Stroeder_15__TwoFloatInterv.c__p26181_edge_closing_0.smt2                                   |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26197_terminationG_0.smt2                                        |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26198_terminationG_0.smt2                                        |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        |  58.004s  |  58.004s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26203_terminationG_0.smt2                                        |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26206_edge_closing_0.smt2                                        |   4.085s  |   4.085s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26207_edge_closing_0.smt2                                        |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26213_edge_closing_0.smt2                                        |  15.527s  |  15.527s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26214_edge_closing_0.smt2                                        |  59.867s  |  59.867s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__terminationS_3_0.smt2                                             |  59.796s  |  59.796s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26230_terminationG_0.smt2                                    |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26231_terminationG_0.smt2                                    |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26235_terminationG_0.smt2                                    |  59.933s  |  59.933s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26236_terminationG_0.smt2                                    |  59.893s  |  59.893s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26239_edge_closing_0.smt2                                    |  31.280s  |  31.280s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26240_edge_closing_0.smt2                                    |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26246_edge_closing_0.smt2                                    |  13.216s  |  13.216s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDownIneq.c__p26247_edge_closing_0.smt2                                    |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig1_false-termination.c__p26265_safety_0.smt2                   |  59.309s  |  59.309s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig1_false-termination.c__p26266_safety_0.smt2                   |  54.915s  |  54.915s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig2-modified1000_true-termination.c__term_unfeasibility_0_0.smt2  |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Stroeder_15__Urban-WST2013-Fig2_true-termination.c__term_unfeasibility_0_0.smt2             |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26291_terminationG_0.smt2                       |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26301_terminationG_0.smt2                       |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26335_terminationG_0.smt2                       |  59.747s  |  59.747s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26336_terminationG_0.smt2                       |  59.861s  |  59.861s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__terminationQ_0_0.smt2                            |  59.730s  |  59.730s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__terminationS_0_0.smt2                            |  59.598s  |  59.598s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__terminationS_1_0.smt2                            |  59.782s  |  59.782s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26374_terminationG_0.smt2                                        |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26375_terminationG_0.smt2                                        |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26376_terminationG_0.smt2                                        |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26380_terminationG_0.smt2                                        |  59.655s  |  59.655s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26381_terminationG_0.smt2                                        |  60.186s  |  60.186s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  59.246s  |  59.246s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26407_terminationG_0.smt2                                    |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26408_terminationG_0.smt2                                    |  59.781s  |  59.781s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26409_terminationG_0.smt2                                    |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26412_terminationG_0.smt2                                    |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26413_terminationG_0.smt2                                    |  59.674s  |  59.674s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncrPart.c__p26414_terminationG_0.smt2                                    |  59.720s  |  59.720s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26429_terminationG_0.smt2                                      |  58.836s  |  58.836s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26430_terminationG_0.smt2                                      |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26431_terminationG_0.smt2                                      |  59.890s  |  59.890s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26434_terminationG_0.smt2                                      |  59.882s  |  59.882s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26435_terminationG_0.smt2                                      |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__p26436_terminationG_0.smt2                                      |  59.639s  |  59.639s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNested.c__terminationQ_1_0.smt2                                           |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |  57.802s  |  57.802s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26452_terminationG_0.smt2                                |  59.899s  |  59.899s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26453_terminationG_0.smt2                                |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26456_terminationG_0.smt2                                |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26457_terminationG_0.smt2                                |  57.609s  |  57.609s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                |  59.844s  |  59.844s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__terminationQ_1_0.smt2                                     |  60.044s  |  60.044s  |   0.000s  | 0.0%|
|Stroeder_15__WhilePart.c__p26472_safety_0.smt2                                              |  60.053s  |  60.053s  |   0.000s  | 0.0%|
|Stroeder_15__WhilePart.c__p26473_safety_0.smt2                                              |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__WhileSingle.c__p26489_edge_closing_0.smt2                                      |  60.140s  |  60.140s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20348_terminationG_0.smt2                          |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20359_terminationG_0.smt2                          |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20363_terminationG_0.smt2                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20364_terminationG_0.smt2                          |  59.844s  |  59.844s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20368_terminationG_0.smt2                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20369_terminationG_0.smt2                          |  59.079s  |  59.079s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22217_terminationG_0.smt2                                          |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22218_terminationG_0.smt2                                          |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22219_terminationG_0.smt2                                          |  59.440s  |  59.440s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22228_edge_closing_0.smt2                                          |  59.607s  |  59.607s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22230_edge_closing_0.smt2                                          |  58.782s  |  58.782s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22231_edge_closing_0.smt2                                          |  59.572s  |  59.572s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__term_unfeasibility_1_0.smt2                                         |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__terminationQ_0_0.smt2                                               |  58.486s  |  58.486s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__terminationS_0_0.smt2                                               |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__terminationS_1_0.smt2                                               |  59.278s  |  59.278s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_a.10.c__p25674_terminationG_0.smt2                                      |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_a.10.c__p25675_terminationG_0.smt2                                      |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25769_terminationG_0.smt2                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01_assume.c__term_unfeasibility_0_0.smt2                              |  59.691s  |  59.691s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25801_terminationG_0.smt2                                       |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25806_terminationG_0.smt2                                       |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25815_terminationG_0.smt2                                       |  24.867s  |  24.867s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |  11.119s  |  11.119s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25817_terminationG_0.smt2                                       |  59.350s  |  59.350s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25820_terminationG_0.smt2                                       |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25825_terminationG_0.smt2                                       |  56.774s  |  56.774s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25826_terminationG_0.smt2                                       |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25827_terminationG_0.smt2                                       |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25832_terminationG_0.smt2                                       |  58.551s  |  58.551s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25835_terminationG_0.smt2                                       |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25836_terminationG_0.smt2                                       |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |  59.510s  |  59.510s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25843_terminationG_0.smt2                                       |  59.779s  |  59.779s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   5.747s  |   5.747s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25848_terminationG_0.smt2                                       |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25852_terminationG_0.smt2                                       |  60.082s  |  60.082s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25856_terminationG_0.smt2                                       |  58.953s  |  58.953s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25857_terminationG_0.smt2                                       |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25858_terminationG_0.smt2                                       |  59.911s  |  59.911s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25861_terminationG_0.smt2                                       |  59.690s  |  59.690s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25862_terminationG_0.smt2                                       |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25866_terminationG_0.smt2                                       |  59.945s  |  59.945s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       |  59.955s  |  59.955s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25868_terminationG_0.smt2                                       |  59.918s  |  59.918s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25871_terminationG_0.smt2                                       |  57.883s  |  57.883s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25872_terminationG_0.smt2                                       |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25873_terminationG_0.smt2                                       |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25876_terminationG_0.smt2                                       |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25877_terminationG_0.smt2                                       |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25878_terminationG_0.smt2                                       |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25881_terminationG_0.smt2                                       |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25882_terminationG_0.smt2                                       |  59.895s  |  59.895s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25883_terminationG_0.smt2                                       |  58.573s  |  58.573s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |  59.861s  |  59.861s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25887_terminationG_0.smt2                                       |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25888_terminationG_0.smt2                                       |  57.505s  |  57.505s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25891_terminationG_0.smt2                                       |  56.046s  |  56.046s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25892_terminationG_0.smt2                                       |  59.863s  |  59.863s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25893_terminationG_0.smt2                                       |  59.938s  |  59.938s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25896_terminationG_0.smt2                                       |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25897_terminationG_0.smt2                                       |  59.793s  |  59.793s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25898_terminationG_0.smt2                                       |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25901_terminationG_0.smt2                                       |  57.264s  |  57.264s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25902_terminationG_0.smt2                                       |  60.160s  |  60.160s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       |  59.725s  |  59.725s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25905_terminationG_0.smt2                                       |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25907_terminationG_0.smt2                                       |  59.591s  |  59.591s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25908_terminationG_0.smt2                                       |  59.471s  |  59.471s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25911_terminationG_0.smt2                                       |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25912_terminationG_0.smt2                                       |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25916_terminationG_0.smt2                                       |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25917_terminationG_0.smt2                                       |  59.542s  |  59.542s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25918_terminationG_0.smt2                                       |  60.010s  |  60.010s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25922_terminationG_0.smt2                                       |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25923_terminationG_0.smt2                                       |  60.425s  |  60.425s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25924_terminationG_0.smt2                                       |  59.724s  |  59.724s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25927_terminationG_0.smt2                                       |  59.753s  |  59.753s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25928_terminationG_0.smt2                                       |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       |  59.907s  |  59.907s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25932_terminationG_0.smt2                                       |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25933_terminationG_0.smt2                                       |  60.153s  |  60.153s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25934_terminationG_0.smt2                                       |  59.749s  |  59.749s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25937_terminationG_0.smt2                                       |  59.866s  |  59.866s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25938_terminationG_0.smt2                                       |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25939_terminationG_0.smt2                                       |  55.578s  |  55.578s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25942_terminationG_0.smt2                                       |  59.530s  |  59.530s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25943_terminationG_0.smt2                                       |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25944_terminationG_0.smt2                                       |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25947_terminationG_0.smt2                                       |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25948_terminationG_0.smt2                                       |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25949_terminationG_0.smt2                                       |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25952_terminationG_0.smt2                                       |  59.904s  |  59.904s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25953_terminationG_0.smt2                                       |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25954_terminationG_0.smt2                                       |  59.783s  |  59.783s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25957_terminationG_0.smt2                                       |  59.804s  |  59.804s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25958_terminationG_0.smt2                                       |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25959_terminationG_0.smt2                                       |  56.686s  |  56.686s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25962_terminationG_0.smt2                                       |  59.279s  |  59.279s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25964_terminationG_0.smt2                                       |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25968_terminationG_0.smt2                                       |  59.931s  |  59.931s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25969_terminationG_0.smt2                                       |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25970_terminationG_0.smt2                                       |  59.848s  |  59.848s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25973_terminationG_0.smt2                                       |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25974_terminationG_0.smt2                                       |  59.925s  |  59.925s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25975_terminationG_0.smt2                                       |  59.886s  |  59.886s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25978_terminationG_0.smt2                                       |  57.686s  |  57.686s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25979_terminationG_0.smt2                                       |  56.917s  |  56.917s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25980_terminationG_0.smt2                                       |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25984_terminationG_0.smt2                                       |  59.176s  |  59.176s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25985_terminationG_0.smt2                                       |  52.685s  |  52.685s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25988_terminationG_0.smt2                                       |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25989_terminationG_0.smt2                                       |  59.698s  |  59.698s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25990_terminationG_0.smt2                                       |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25992_terminationG_0.smt2                                       |  55.407s  |  55.407s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25994_terminationG_0.smt2                                       |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25995_terminationG_0.smt2                                       |  59.461s  |  59.461s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationQ_27_0.smt2                                           |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__p26008_terminationG_0.smt2                                      |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__p26009_terminationG_0.smt2                                      |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__p26013_terminationG_0.smt2                                      |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__p26014_terminationG_0.smt2                                      |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3a.c__terminationQ_1_0.smt2                                           |  58.575s  |  58.575s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26023_terminationG_0.smt2                                      |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26031_terminationG_0.smt2                                      |  59.375s  |  59.375s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26032_terminationG_0.smt2                                      |  59.654s  |  59.654s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26033_terminationG_0.smt2                                      |  59.858s  |  59.858s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26036_terminationG_0.smt2                                      |  57.752s  |  57.752s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26037_terminationG_0.smt2                                      |  59.843s  |  59.843s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26038_terminationG_0.smt2                                      |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26041_terminationG_0.smt2                                      |  59.855s  |  59.855s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26042_terminationG_0.smt2                                      |  54.992s  |  54.992s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26043_terminationG_0.smt2                                      |  59.815s  |  59.815s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26047_terminationG_0.smt2                                      |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26048_terminationG_0.smt2                                      |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__terminationQ_3_0.smt2                                           |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26532_terminationG_0.smt2                       |   7.503s  |   7.503s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26535_terminationG_0.smt2                       |  59.190s  |  59.190s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26536_terminationG_0.smt2                       |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26537_terminationG_0.smt2                       |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26540_terminationG_0.smt2                       |  60.004s  |  60.004s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26541_terminationG_0.smt2                       |  59.923s  |  59.923s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26542_terminationG_0.smt2                       |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26545_terminationG_0.smt2                       |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26546_terminationG_0.smt2                       |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26550_terminationG_0.smt2                       |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26551_terminationG_0.smt2                       |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26552_terminationG_0.smt2                       |  57.205s  |  57.205s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26556_terminationG_0.smt2                       |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       |  58.901s  |  58.901s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26568_edge_closing_0.smt2                       |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26581_terminationG_0.smt2                     |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     |  58.639s  |  58.639s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v2_false-termination.c__p26608_terminationG_0.smt2                  |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v2_false-termination.c__p26609_terminationG_0.smt2                  |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v2_false-termination.c__p26620_edge_closing_0.smt2                  |  13.954s  |  13.954s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v3_false-termination.c__p26641_terminationG_0.smt2                  |  59.292s  |  59.292s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_v3_false-termination.c__p26642_terminationG_0.smt2                  |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26677_terminationG_0.smt2                |  59.123s  |  59.123s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |  34.139s  |  34.139s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26679_terminationG_0.smt2                |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26689_terminationG_0.smt2                |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26690_terminationG_0.smt2                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26705_terminationG_0.smt2                  |  57.749s  |  57.749s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26706_terminationG_0.smt2                  |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26707_terminationG_0.smt2                  |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26710_terminationG_0.smt2                  |  58.931s  |  58.931s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26711_terminationG_0.smt2                  |  59.661s  |  59.661s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_nondet_false-termination.c__p26712_terminationG_0.smt2                  |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26727_terminationG_0.smt2                   |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26728_terminationG_0.smt2                   |  59.718s  |  59.718s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26729_terminationG_0.smt2                   |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26732_terminationG_0.smt2                   |  59.801s  |  59.801s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26733_terminationG_0.smt2                   |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26734_terminationG_0.smt2                   |  57.982s  |  57.982s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__p26739_edge_closing_0.smt2                   |   3.117s  |   3.117s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Cairo_step2_false-termination.c__terminationQ_1_0.smt2                        |  58.534s  |  58.534s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26761_terminationG_0.smt2                |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26768_terminationG_0.smt2                |  59.672s  |  59.672s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26769_terminationG_0.smt2                |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26770_terminationG_0.smt2                |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26775_terminationG_0.smt2                |  59.896s  |  59.896s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26776_terminationG_0.smt2                |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26782_terminationG_0.smt2                |  58.291s  |  58.291s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26783_terminationG_0.smt2                |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26789_terminationG_0.smt2                |  59.681s  |  59.681s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26790_terminationG_0.smt2                |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26797_terminationG_0.smt2                |  57.073s  |  57.073s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26799_terminationG_0.smt2                |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26806_terminationG_0.smt2                |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26807_terminationG_0.smt2                |  43.580s  |  43.580s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26808_terminationG_0.smt2                |  59.901s  |  59.901s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26817_terminationG_0.smt2                |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26818_terminationG_0.smt2                |  15.755s  |  15.755s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26819_terminationG_0.smt2                |  59.366s  |  59.366s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26829_terminationG_0.smt2                |  59.163s  |  59.163s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26830_terminationG_0.smt2                |  50.492s  |  50.492s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26831_terminationG_0.smt2                |  58.494s  |  58.494s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26839_terminationG_0.smt2                |  59.365s  |  59.365s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26840_terminationG_0.smt2                |  41.521s  |  41.521s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26841_terminationG_0.smt2                |  58.072s  |  58.072s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26844_terminationG_0.smt2                |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26845_terminationG_0.smt2                |  59.827s  |  59.827s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26846_terminationG_0.smt2                |  59.434s  |  59.434s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26849_edge_closing_0.smt2                |  59.625s  |  59.625s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26850_edge_closing_0.smt2                |  59.762s  |  59.762s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26853_edge_closing_0.smt2                |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |  59.676s  |  59.676s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26856_edge_closing_0.smt2                |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26857_edge_closing_0.smt2                |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26858_edge_closing_0.smt2                |   9.753s  |   9.753s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26859_edge_closing_0.smt2                |  59.405s  |  59.405s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26860_edge_closing_0.smt2                |  56.913s  |  56.913s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26863_edge_closing_0.smt2                |  59.128s  |  59.128s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26864_edge_closing_0.smt2                |   6.428s  |   6.428s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26865_edge_closing_0.smt2                |  16.198s  |  16.198s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26866_edge_closing_0.smt2                |  56.867s  |  56.867s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26874_terminationG_0.smt2                  |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26875_terminationG_0.smt2                  |   1.159s  |   1.159s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |  59.297s  |  59.297s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26879_terminationG_0.smt2                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26880_terminationG_0.smt2                  |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   7.725s  |   7.725s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26902_terminationG_0.smt2                   |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26903_terminationG_0.smt2                   |  60.008s  |  60.008s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26904_terminationG_0.smt2                   |  58.539s  |  58.539s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |  59.838s  |  59.838s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26908_terminationG_0.smt2                   |  59.482s  |  59.482s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26909_terminationG_0.smt2                   |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26912_terminationG_0.smt2                   |  59.912s  |  59.912s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26913_terminationG_0.smt2                   |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26914_terminationG_0.smt2                   |  59.903s  |  59.903s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26917_terminationG_0.smt2                   |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26918_terminationG_0.smt2                   |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26919_terminationG_0.smt2                   |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26922_terminationG_0.smt2                   |  58.940s  |  58.940s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26923_terminationG_0.smt2                   |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26924_terminationG_0.smt2                   |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26936_edge_closing_0.smt2                   |   0.989s  |   0.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26953_terminationG_0.smt2                   |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26954_terminationG_0.smt2                   |  12.527s  |  12.527s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26955_terminationG_0.smt2                   |  20.242s  |  20.242s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26961_terminationG_0.smt2                   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26962_terminationG_0.smt2                   |  29.454s  |  29.454s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26965_terminationG_0.smt2                   |  59.825s  |  59.825s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26966_terminationG_0.smt2                   |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26967_terminationG_0.smt2                   |  59.420s  |  59.420s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26970_terminationG_0.smt2                   |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26971_terminationG_0.smt2                   |  59.429s  |  59.429s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26972_terminationG_0.smt2                   |  59.869s  |  59.869s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26975_terminationG_0.smt2                   |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26976_terminationG_0.smt2                   |  56.200s  |  56.200s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26977_terminationG_0.smt2                   |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26980_terminationG_0.smt2                   |  59.868s  |  59.868s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26982_terminationG_0.smt2                   |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26985_terminationG_0.smt2                   |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26986_terminationG_0.smt2                   |   3.166s  |   3.166s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26987_terminationG_0.smt2                   |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26991_terminationG_0.smt2                   |  51.330s  |  51.330s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26992_terminationG_0.smt2                   |  59.824s  |  59.824s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26995_terminationG_0.smt2                   |  59.786s  |  59.786s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26996_terminationG_0.smt2                   |  18.145s  |  18.145s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26997_terminationG_0.smt2                   |  59.920s  |  59.920s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27000_terminationG_0.smt2                   |  59.944s  |  59.944s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27001_terminationG_0.smt2                   |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27002_terminationG_0.smt2                   |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27005_terminationG_0.smt2                   |  59.856s  |  59.856s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27006_terminationG_0.smt2                   |   5.002s  |   5.002s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27007_terminationG_0.smt2                   |  58.983s  |  58.983s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27010_terminationG_0.smt2                   |  59.383s  |  59.383s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27011_terminationG_0.smt2                   |  16.542s  |  16.542s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27012_terminationG_0.smt2                   |  58.965s  |  58.965s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27015_terminationG_0.smt2                   |  54.229s  |  54.229s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27016_terminationG_0.smt2                   |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27017_terminationG_0.smt2                   |  59.672s  |  59.672s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27020_terminationG_0.smt2                   |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27022_terminationG_0.smt2                   |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27025_terminationG_0.smt2                   |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27026_terminationG_0.smt2                   |  59.836s  |  59.836s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27027_terminationG_0.smt2                   |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27030_terminationG_0.smt2                   |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27031_terminationG_0.smt2                   |  59.076s  |  59.076s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27032_terminationG_0.smt2                   |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27038_edge_closing_0.smt2                   |   1.580s  |   1.580s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27039_edge_closing_0.smt2                   |   3.314s  |   3.314s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27040_edge_closing_0.smt2                   |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__terminationQ_13_0.smt2                       |  59.804s  |  59.804s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__terminationS_0_0.smt2                        |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27051_terminationG_0.smt2                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27056_terminationG_0.smt2                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27057_terminationG_0.smt2                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27061_terminationG_0.smt2                    |  59.122s  |  59.122s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27062_terminationG_0.smt2                    |  59.957s  |  59.957s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27068_terminationG_0.smt2                    |  59.920s  |  59.920s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27069_terminationG_0.smt2                    |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27077_terminationG_0.smt2                    |  28.173s  |  28.173s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27083_terminationG_0.smt2                    |  59.325s  |  59.325s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27084_terminationG_0.smt2                    |  59.912s  |  59.912s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27092_terminationG_0.smt2                    |   1.340s  |   1.340s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27093_terminationG_0.smt2                    |  59.121s  |  59.121s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27097_terminationG_0.smt2                    |  15.034s  |  15.034s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27098_terminationG_0.smt2                    |  59.886s  |  59.886s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27109_terminationG_0.smt2                    |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27110_terminationG_0.smt2                    |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27121_terminationG_0.smt2                    |  59.941s  |  59.941s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27122_terminationG_0.smt2                    |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27123_terminationG_0.smt2                    |  59.737s  |  59.737s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27134_terminationG_0.smt2                    |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27135_terminationG_0.smt2                    |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27136_terminationG_0.smt2                    |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27139_terminationG_0.smt2                    |  58.689s  |  58.689s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27140_terminationG_0.smt2                    |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27141_terminationG_0.smt2                    |  60.975s  |  60.975s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27144_terminationG_0.smt2                    |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27145_terminationG_0.smt2                    |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27146_terminationG_0.smt2                    |  59.079s  |  59.079s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27149_terminationG_0.smt2                    |  57.922s  |  57.922s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27150_terminationG_0.smt2                    |  59.940s  |  59.940s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27151_terminationG_0.smt2                    |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27154_terminationG_0.smt2                    |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27155_terminationG_0.smt2                    |  59.365s  |  59.365s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27156_terminationG_0.smt2                    |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27159_terminationG_0.smt2                    |  59.673s  |  59.673s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27160_terminationG_0.smt2                    |  59.873s  |  59.873s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27161_terminationG_0.smt2                    |  58.530s  |  58.530s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27164_terminationG_0.smt2                    |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27165_terminationG_0.smt2                    |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27166_terminationG_0.smt2                    |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27169_terminationG_0.smt2                    |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27170_terminationG_0.smt2                    |  39.769s  |  39.769s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27171_terminationG_0.smt2                    |  59.621s  |  59.621s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27174_terminationG_0.smt2                    |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27175_terminationG_0.smt2                    |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27176_terminationG_0.smt2                    |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27179_terminationG_0.smt2                    |  59.058s  |  59.058s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27180_terminationG_0.smt2                    |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27181_terminationG_0.smt2                    |  55.555s  |  55.555s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27184_terminationG_0.smt2                    |  59.912s  |  59.912s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27185_terminationG_0.smt2                    |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27186_terminationG_0.smt2                    |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27189_terminationG_0.smt2                    |  58.103s  |  58.103s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27190_terminationG_0.smt2                    |  58.601s  |  58.601s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27191_terminationG_0.smt2                    |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27194_terminationG_0.smt2                    |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27195_terminationG_0.smt2                    |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27196_terminationG_0.smt2                    |  59.040s  |  59.040s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27199_terminationG_0.smt2                    |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27200_terminationG_0.smt2                    |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27201_terminationG_0.smt2                    |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27205_terminationG_0.smt2                    |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27206_terminationG_0.smt2                    |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27207_terminationG_0.smt2                    |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27210_terminationG_0.smt2                    |  59.850s  |  59.850s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27211_terminationG_0.smt2                    |   3.795s  |   3.795s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27212_terminationG_0.smt2                    |  57.789s  |  57.789s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27215_terminationG_0.smt2                    |  58.165s  |  58.165s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27216_terminationG_0.smt2                    |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27217_terminationG_0.smt2                    |  53.328s  |  53.328s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27221_terminationG_0.smt2                    |  59.672s  |  59.672s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27222_terminationG_0.smt2                    |  60.025s  |  60.025s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27225_terminationG_0.smt2                    |  58.108s  |  58.108s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27227_terminationG_0.smt2                    |  59.956s  |  59.956s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27230_terminationG_0.smt2                    |  59.801s  |  59.801s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27231_terminationG_0.smt2                    |  59.689s  |  59.689s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27232_terminationG_0.smt2                    |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27234_edge_closing_0.smt2                    |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27235_edge_closing_0.smt2                    |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27236_edge_closing_0.smt2                    |  59.888s  |  59.888s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27238_edge_closing_0.smt2                    |  59.813s  |  59.813s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27239_edge_closing_0.smt2                    |  56.567s  |  56.567s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27240_edge_closing_0.smt2                    |  55.861s  |  55.861s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27242_edge_closing_0.smt2                    |  59.789s  |  59.789s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__terminationQ_18_0.smt2                        |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__terminationQ_19_0.smt2                        |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__terminationS_0_0.smt2                         |  59.454s  |  59.454s  |   0.000s  | 0.0%|
|Ton_Chanh_15__McCarthy91_Iteration_true-termination.c__term_unfeasibility_0_0.smt2          |  58.704s  |  58.704s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27262_terminationG_0.smt2                        |  59.913s  |  59.913s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27263_terminationG_0.smt2                        |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        |  59.865s  |  59.865s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27267_terminationG_0.smt2                        |  59.684s  |  59.684s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27268_terminationG_0.smt2                        |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27272_terminationG_0.smt2                        |  59.366s  |  59.366s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27273_terminationG_0.smt2                        |  59.154s  |  59.154s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27274_terminationG_0.smt2                        |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27277_terminationG_0.smt2                        |  58.252s  |  58.252s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27278_terminationG_0.smt2                        |  59.664s  |  59.664s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27279_terminationG_0.smt2                        |  59.609s  |  59.609s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27282_terminationG_0.smt2                        |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27283_terminationG_0.smt2                        |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27284_terminationG_0.smt2                        |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27301_terminationG_0.smt2                |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27304_terminationG_0.smt2                |  59.801s  |  59.801s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27305_terminationG_0.smt2                |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27306_terminationG_0.smt2                |  59.331s  |  59.331s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27309_terminationG_0.smt2                |  59.461s  |  59.461s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27310_terminationG_0.smt2                |  57.331s  |  57.331s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27311_terminationG_0.smt2                |  59.648s  |  59.648s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27314_terminationG_0.smt2                |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27315_terminationG_0.smt2                |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27316_terminationG_0.smt2                |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27319_terminationG_0.smt2                |  55.248s  |  55.248s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27320_terminationG_0.smt2                |  59.676s  |  59.676s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27321_terminationG_0.smt2                |  59.608s  |  59.608s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27324_terminationG_0.smt2                |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27325_terminationG_0.smt2                |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27326_terminationG_0.smt2                |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_plus_false-termination.c__p27334_edge_closing_0.smt2                |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27343_terminationG_0.smt2                      |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27347_terminationG_0.smt2                      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27348_terminationG_0.smt2                      |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27352_terminationG_0.smt2                      |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_true-termination.c__p27353_terminationG_0.smt2                      |  59.947s  |  59.947s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27362_terminationG_0.smt2                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27367_terminationG_0.smt2                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27370_terminationG_0.smt2                  |  59.631s  |  59.631s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27371_terminationG_0.smt2                  |  58.160s  |  58.160s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27372_terminationG_0.smt2                  |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27375_terminationG_0.smt2                  |  57.419s  |  57.419s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27376_terminationG_0.smt2                  |  56.094s  |  56.094s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27377_terminationG_0.smt2                  |  57.554s  |  57.554s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27380_terminationG_0.smt2                  |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  60.016s  |  60.016s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27385_terminationG_0.smt2                  |  58.757s  |  58.757s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27386_terminationG_0.smt2                  |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27387_terminationG_0.smt2                  |  57.512s  |  57.512s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27390_terminationG_0.smt2                  |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27391_terminationG_0.smt2                  |  54.602s  |  54.602s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27392_terminationG_0.smt2                  |  59.541s  |  59.541s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27396_edge_closing_0.smt2                  |  13.582s  |  13.582s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27409_terminationG_0.smt2                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27413_terminationG_0.smt2                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27414_terminationG_0.smt2                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27417_terminationG_0.smt2                  |  59.863s  |  59.863s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27418_terminationG_0.smt2                  |  59.681s  |  59.681s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27419_terminationG_0.smt2                  |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27422_terminationG_0.smt2                  |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27423_terminationG_0.smt2                  |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27424_terminationG_0.smt2                  |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27427_terminationG_0.smt2                  |  59.703s  |  59.703s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27428_terminationG_0.smt2                  |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27429_terminationG_0.smt2                  |  59.871s  |  59.871s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27432_terminationG_0.smt2                  |  59.853s  |  59.853s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27433_terminationG_0.smt2                  |  58.463s  |  58.463s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27434_terminationG_0.smt2                  |  58.804s  |  58.804s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27437_terminationG_0.smt2                  |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27438_terminationG_0.smt2                  |  59.936s  |  59.936s  |   0.000s  | 0.0%|
</details>
