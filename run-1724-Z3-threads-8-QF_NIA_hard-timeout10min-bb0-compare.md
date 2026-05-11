Comparing data and data


# SUMMARY
- LHS tests = 800
- RHS tests = 800
- LHS success = 800  (100.0%)
- RHS success = 800  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-QF_NIA_hard-timeout10min-bb0
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: f880fdccee614547c38c19beb7af5a027961646b
Z3 branch: core_min
Z3 options: "-T:600 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=0"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_NIA.tar.zst?download=1
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-QF_NIA_hard-timeout10min-bb0
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: f880fdccee614547c38c19beb7af5a027961646b
Z3 branch: core_min
Z3 options: "-T:600 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=0"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_NIA.tar.zst?download=1
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  | 600.166s  | 600.166s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |  22.091s  |  22.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   7.293s  |   7.293s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |   5.480s  |   5.480s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  38.938s  |  38.938s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |  43.339s  |  43.339s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |  94.358s  |  94.358s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  63.586s  |  63.586s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  | 562.199s  | 562.199s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  | 594.096s  | 594.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  51.353s  |  51.353s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.832s  |   0.832s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |  86.712s  |  86.712s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  | 222.827s  | 222.827s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |  25.934s  |  25.934s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   4.421s  |   4.421s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  | 600.166s  | 600.166s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |  22.091s  |  22.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   7.293s  |   7.293s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |   5.480s  |   5.480s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  38.938s  |  38.938s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |  43.339s  |  43.339s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |  94.358s  |  94.358s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  63.586s  |  63.586s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  | 562.199s  | 562.199s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  | 594.096s  | 594.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  51.353s  |  51.353s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.832s  |   0.832s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |  86.712s  |  86.712s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  | 222.827s  | 222.827s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |  25.934s  |  25.934s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   4.421s  |   4.421s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  | 600.166s  | 600.166s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |  22.091s  |  22.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   7.293s  |   7.293s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |   5.480s  |   5.480s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  38.938s  |  38.938s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |  43.339s  |  43.339s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |  94.358s  |  94.358s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  63.586s  |  63.586s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  | 562.199s  | 562.199s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  | 594.096s  | 594.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  51.353s  |  51.353s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.832s  |   0.832s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |  86.712s  |  86.712s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  | 222.827s  | 222.827s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |  25.934s  |  25.934s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   4.421s  |   4.421s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  | 600.166s  | 600.166s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |  22.091s  |  22.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   7.293s  |   7.293s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |   5.480s  |   5.480s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  38.938s  |  38.938s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |  43.339s  |  43.339s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |  94.358s  |  94.358s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  63.586s  |  63.586s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  | 562.199s  | 562.199s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  | 594.096s  | 594.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  51.353s  |  51.353s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.832s  |   0.832s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |  86.712s  |  86.712s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  | 222.827s  | 222.827s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |  25.934s  |  25.934s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   4.421s  |   4.421s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_NIA/20220315-MathProblems/RTA_093.smt2                                  | 600.703s |6776.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_24_0.smt2        | 600.663s |5726.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_19_0.smt2        | 600.639s |5753.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_3_0.smt2         | 600.603s |5467.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_22_0.smt2        | 600.591s |5751.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_2_0.smt2         | 600.591s |5367.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_17_0.smt2        | 600.587s |5602.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3.t2_fixed__p22135_terminationG_0.smt2 | 600.583s |5377.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_31_0.smt2        | 600.565s |5644.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_15_0.smt2        | 600.564s |5625.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_18_0.smt2        | 600.563s |5725.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_32_0.smt2        | 600.556s |5453.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_14_0.smt2        | 600.556s |5774.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_6_0.smt2         | 600.553s |5422.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_26_0.smt2        | 600.552s |5651.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_13_0.smt2        | 600.542s |5633.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3-new.t2_fixed__p21803_terminationG_0.smt2 | 600.538s |4686.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_28_0.smt2        | 600.515s |5536.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_7_0.smt2         | 600.510s |5395.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2__p15941_terminationG_0.smt2 | 600.472s |2614.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_NIA/20220315-MathProblems/RTA_093.smt2                                  | 600.703s |6776.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_24_0.smt2        | 600.663s |5726.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_19_0.smt2        | 600.639s |5753.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_3_0.smt2         | 600.603s |5467.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_22_0.smt2        | 600.591s |5751.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_2_0.smt2         | 600.591s |5367.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_17_0.smt2        | 600.587s |5602.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3.t2_fixed__p22135_terminationG_0.smt2 | 600.583s |5377.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_31_0.smt2        | 600.565s |5644.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_15_0.smt2        | 600.564s |5625.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_18_0.smt2        | 600.563s |5725.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_32_0.smt2        | 600.556s |5453.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_14_0.smt2        | 600.556s |5774.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_6_0.smt2         | 600.553s |5422.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_26_0.smt2        | 600.552s |5651.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_13_0.smt2        | 600.542s |5633.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3-new.t2_fixed__p21803_terminationG_0.smt2 | 600.538s |4686.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_28_0.smt2        | 600.515s |5536.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_7_0.smt2         | 600.510s |5395.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2__p15941_terminationG_0.smt2 | 600.472s |2614.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  |1499.0MiB|1499.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |234.0MiB|234.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |1068.0MiB|1068.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |192.0MiB|192.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |443.0MiB|443.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |418.0MiB|418.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |255.0MiB|255.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |270.0MiB|270.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |639.0MiB|639.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |894.0MiB|894.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |706.0MiB|706.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |796.0MiB|796.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |1349.0MiB|1349.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |1147.0MiB|1147.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |748.0MiB|748.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |234.0MiB|234.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |921.0MiB|921.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |1186.0MiB|1186.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |395.0MiB|395.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |429.0MiB|429.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  |1499.0MiB|1499.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |234.0MiB|234.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |1068.0MiB|1068.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |192.0MiB|192.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |443.0MiB|443.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |418.0MiB|418.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |255.0MiB|255.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |270.0MiB|270.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |639.0MiB|639.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |894.0MiB|894.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |706.0MiB|706.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |796.0MiB|796.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |1349.0MiB|1349.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |1147.0MiB|1147.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |748.0MiB|748.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |234.0MiB|234.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |921.0MiB|921.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |1186.0MiB|1186.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |395.0MiB|395.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |429.0MiB|429.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  |1499.0MiB|1499.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |234.0MiB|234.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |1068.0MiB|1068.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |192.0MiB|192.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |443.0MiB|443.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |418.0MiB|418.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |255.0MiB|255.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |270.0MiB|270.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |639.0MiB|639.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |894.0MiB|894.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |706.0MiB|706.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |796.0MiB|796.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |1349.0MiB|1349.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |1147.0MiB|1147.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |748.0MiB|748.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |234.0MiB|234.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |921.0MiB|921.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |1186.0MiB|1186.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |395.0MiB|395.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |429.0MiB|429.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  |1499.0MiB|1499.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |234.0MiB|234.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |1068.0MiB|1068.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |192.0MiB|192.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |443.0MiB|443.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |418.0MiB|418.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |255.0MiB|255.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |270.0MiB|270.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |639.0MiB|639.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |894.0MiB|894.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |706.0MiB|706.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |796.0MiB|796.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |1349.0MiB|1349.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |1147.0MiB|1147.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |748.0MiB|748.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |234.0MiB|234.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |921.0MiB|921.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |1186.0MiB|1186.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |395.0MiB|395.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |429.0MiB|429.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_NIA/20220315-MathProblems/RTA_093.smt2                                  | 600.703s |6776.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_14_0.smt2        | 600.556s |5774.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_19_0.smt2        | 600.639s |5753.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_22_0.smt2        | 600.591s |5751.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_24_0.smt2        | 600.663s |5726.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_18_0.smt2        | 600.563s |5725.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_26_0.smt2        | 600.552s |5651.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_31_0.smt2        | 600.565s |5644.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_13_0.smt2        | 600.542s |5633.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_15_0.smt2        | 600.564s |5625.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_17_0.smt2        | 600.587s |5602.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_16_0.smt2        | 596.307s |5602.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_20_0.smt2        | 521.788s |5579.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_28_0.smt2        | 600.515s |5536.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_3_0.smt2         | 600.603s |5467.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_32_0.smt2        | 600.556s |5453.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_6_0.smt2         | 600.553s |5422.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_7_0.smt2         | 600.510s |5395.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3.t2_fixed__p22135_terminationG_0.smt2 | 600.583s |5377.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_2_0.smt2         | 600.591s |5367.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_NIA/20220315-MathProblems/RTA_093.smt2                                  | 600.703s |6776.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_14_0.smt2        | 600.556s |5774.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_19_0.smt2        | 600.639s |5753.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_22_0.smt2        | 600.591s |5751.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_24_0.smt2        | 600.663s |5726.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_18_0.smt2        | 600.563s |5725.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_26_0.smt2        | 600.552s |5651.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_31_0.smt2        | 600.565s |5644.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_13_0.smt2        | 600.542s |5633.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_15_0.smt2        | 600.564s |5625.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_17_0.smt2        | 600.587s |5602.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_16_0.smt2        | 596.307s |5602.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_20_0.smt2        | 521.788s |5579.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_28_0.smt2        | 600.515s |5536.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_3_0.smt2         | 600.603s |5467.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_32_0.smt2        | 600.556s |5453.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_6_0.smt2         | 600.553s |5422.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_7_0.smt2         | 600.510s |5395.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3.t2_fixed__p22135_terminationG_0.smt2 | 600.583s |5377.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_2_0.smt2         | 600.591s |5367.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  | 600.166s  | 600.166s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |  22.091s  |  22.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   7.293s  |   7.293s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |   5.480s  |   5.480s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  38.938s  |  38.938s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |  43.339s  |  43.339s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |  94.358s  |  94.358s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  63.586s  |  63.586s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  | 562.199s  | 562.199s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  | 594.096s  | 594.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  51.353s  |  51.353s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.832s  |   0.832s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |  86.712s  |  86.712s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  | 222.827s  | 222.827s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |  25.934s  |  25.934s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   4.421s  |   4.421s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__MirrorInterv.c__p24379_terminationG_0.smt2  |   1.908s  |   1.908s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__MirrorInterv.c__p24450_edge_closing_0.smt2  | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__MirrorIntervSim.c__p24484_terminationG_0.smt2  | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__NO_03.c__p24634_terminationG_0.smt2  |   4.499s  |   4.499s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__NO_13.c__p24750_terminationG_0.smt2  | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__NO_24.c__p24816_terminationG_0.smt2  | 348.551s  | 348.551s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Narrowing.c__p24540_terminationG_0.smt2  | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__NonTerminationSimple7_false-termination.c__p25148_terminationG_0.smt2  | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25430_terminationG_0.smt2  |   1.688s  |   1.688s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Pure3Phase_true-termination.c__p25560_terminationG_0.smt2  | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Swingers.c__p26085_terminationG_0.smt2  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2  |  10.354s  |  10.354s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__UpAndDown.c__p26203_terminationG_0.smt2  | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__UpAndDownIneq.c__p26235_terminationG_0.smt2  |  11.652s  |  11.652s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__UpAndDownIneq.c__p26236_terminationG_0.smt2  | 600.131s  | 600.131s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2  |   2.898s  |   2.898s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2  |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27027_terminationG_0.smt2  |   7.230s  |   7.230s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27084_terminationG_0.smt2  |   1.406s  |   1.406s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27136_terminationG_0.smt2  | 217.015s  | 217.015s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27151_terminationG_0.smt2  |  47.096s  |  47.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27166_terminationG_0.smt2  |   3.502s  |   3.502s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27186_terminationG_0.smt2  |  33.097s  |  33.097s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27222_terminationG_0.smt2  |  87.074s  |  87.074s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27236_edge_closing_0.smt2  |   3.042s  |   3.042s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27239_edge_closing_0.smt2  |   9.333s  |   9.333s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27687_edge_closing_0.smt2  | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__p27530_edge_closing_0.smt2  |   1.607s  |   1.607s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__BinTreeChanger.jar-obl-10__p27729_terminationG_0.smt2  | 123.709s  | 123.709s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2  |   9.899s  |   9.899s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Count.jar-obl-10-2__p28115_terminationG_0.smt2  |   9.543s  |   9.543s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Count.jar-obl-10-2__p28120_terminationG_0.smt2  |  26.918s  |  26.918s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2  |  17.411s  |  17.411s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__DivTernary.jar-obl-10__terminationQ_0_0.smt2  |  25.804s  |  25.804s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Flatten.jar-obl-10__p29378_safety_0.smt2  |   3.638s  |   3.638s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Graph.jar-obl-17__p29763_edge_closing_0.smt2  |  54.733s  |  54.733s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Graph.jar-obl-17__p29774_edge_closing_0.smt2  |   6.587s  |   6.587s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__LessLeaves.jar-obl-10__p10002_edge_closing_0.smt2  | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__LessLeaves.jar-obl-10__p10014_edge_closing_0.smt2  | 600.242s  | 600.242s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__LessLeavesRec.jar-obl-10__p10043_terminationG_0.smt2  |  25.164s  |  25.164s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__List.jar-obl-12__p10223_edge_closing_0.smt2  |   0.846s  |   0.846s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MainFind.jar-obl-10__p10608_edge_closing_0.smt2  |   3.414s  |   3.414s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MainFind.jar-obl-10__p10621_edge_closing_0.smt2  |  62.158s  |  62.158s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MainGet.jar-obl-10__p10695_edge_closing_0.smt2  |  53.517s  |  53.517s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MainMove.jar-obl-11__p10745_edge_closing_0.smt2  |   0.524s  |   0.524s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MainMove.jar-obl-11__p10752_edge_closing_0.smt2  |   0.960s  |   0.960s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Matrix.jar-obl-16__p10775_terminationG_0.smt2  |  18.482s  |  18.482s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Matrix.jar-obl-16__p10815_safety_0.smt2  |   6.349s  |   6.349s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Matrix.jar-obl-16__p10849_edge_closing_0.smt2  | 249.855s  | 249.855s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10899_terminationG_0.smt2  |  29.122s  |  29.122s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MysteriousProgram.jar-obl-12__p11031_terminationG_0.smt2  | 129.628s  | 129.628s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationQ_0_0.smt2  |  47.387s  |  47.387s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__NO_13.jar-obl-8__p11405_terminationG_0.smt2  | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__NO_13.jar-obl-8__p11419_edge_closing_0.smt2  |   5.089s  |   5.089s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__NO_13.jar-obl-8__p11440_edge_closing_0.smt2  | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__NO_13.jar-obl-8__p11459_terminationG_0.smt2  |  19.132s  |  19.132s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__NO_24.jar-obl-8__p11510_terminationG_0.smt2  | 600.187s  | 600.187s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Power.jar-obl-10__p11798_terminationG_0.smt2  |  11.895s  |  11.895s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__RandomHard.jar-obl-10__p11831_safety_0.smt2  |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Samefringe.jar-obl-10__p11982_edge_closing_0.smt2  |  62.630s  |  62.630s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12121_terminationG_0.smt2  | 332.338s  | 332.338s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12128_terminationG_0.smt2  | 600.224s  | 600.224s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12142_terminationG_0.smt2  |  38.972s  |  38.972s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12155_terminationG_0.smt2  | 600.308s  | 600.308s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12183_terminationG_0.smt2  |  35.528s  |  35.528s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12184_terminationG_0.smt2  | 600.265s  | 600.265s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12223_terminationG_0.smt2  | 466.908s  | 466.908s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12232_terminationG_0.smt2  | 527.721s  | 527.721s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12239_terminationG_0.smt2  |   8.881s  |   8.881s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12256_terminationG_0.smt2  | 600.211s  | 600.211s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Swingers.jar-obl-8__p12435_terminationG_0.smt2  | 600.172s  | 600.172s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12477_terminationG_0.smt2  | 273.618s  | 273.618s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Test1.jar-obl-8__p12801_terminationG_0.smt2  | 511.291s  | 511.291s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Test6.jar-obl-13__terminationS_13_0.smt2  |  17.739s  |  17.739s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Test6.jar-obl-13__terminationS_24_0.smt2  |   6.011s  |   6.011s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13881_terminationG_0.smt2  | 600.230s  | 600.230s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13896_terminationG_0.smt2  | 600.193s  | 600.193s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13930_edge_closing_0.smt2  |   5.427s  |   5.427s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14126_edge_closing_0.smt2  |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14269_terminationG_0.smt2  |   1.146s  |   1.146s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14289_edge_closing_0.smt2  |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2  |  29.752s  |  29.752s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14386_terminationG_0.smt2  | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14482_terminationG_0.smt2  |   3.996s  |   3.996s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p4392_safety_0.smt2  |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2  |   1.034s  |   1.034s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p4624_safety_0.smt2  |   2.236s  |   2.236s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p4709_terminationG_0.smt2  |  12.249s  |  12.249s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p5104_safety_0.smt2  |   1.142s  |   1.142s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p5158_safety_0.smt2  |   1.760s  |   1.760s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2  |   3.409s  |   3.409s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29915_safety_0.smt2  |   1.787s  |   1.787s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30004_terminationG_0.smt2  |  14.995s  |  14.995s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30026_safety_0.smt2  |   0.978s  |   0.978s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30127_safety_0.smt2  |   1.052s  |   1.052s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30313_safety_0.smt2  |   2.818s  |   2.818s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30338_terminationG_0.smt2  |  61.891s  |  61.891s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30539_safety_0.smt2  |   1.317s  |   1.317s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30824_terminationG_0.smt2  | 103.286s  | 103.286s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31063_safety_0.smt2  |   1.848s  |   1.848s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2  |   2.091s  |   2.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31152_safety_0.smt2  |   1.105s  |   1.105s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31167_terminationG_0.smt2  |  15.700s  |  15.700s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2  |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31295_safety_0.smt2  |   1.667s  |   1.667s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31303_safety_0.smt2  |   2.683s  |   2.683s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31345_terminationG_0.smt2  |  26.644s  |  26.644s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31805_safety_0.smt2  |   1.526s  |   1.526s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31859_terminationG_0.smt2  |   5.018s  |   5.018s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31928_safety_0.smt2  |   5.179s  |   5.179s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31947_safety_0.smt2  |   3.739s  |   3.739s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32020_terminationG_0.smt2  |   2.086s  |   2.086s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p322_safety_0.smt2  |   2.253s  |   2.253s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32401_safety_0.smt2  |   1.641s  |   1.641s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32720_terminationG_0.smt2  |   4.906s  |   4.906s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1606_safety_0.smt2  |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1659_safety_0.smt2  |   1.210s  |   1.210s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1691_safety_0.smt2  |   0.741s  |   0.741s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2113_safety_0.smt2  |   1.967s  |   1.967s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2225_safety_0.smt2  |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2436_safety_0.smt2  |   0.679s  |   0.679s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2746_safety_0.smt2  |   1.454s  |   1.454s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3008_safety_0.smt2  |   2.197s  |   2.197s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3178_safety_0.smt2  |   2.105s  |   2.105s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3188_terminationG_0.smt2  |  28.581s  |  28.581s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3358_terminationG_0.smt2  | 112.474s  | 112.474s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3363_edge_closing_0.smt2  | 600.218s  | 600.218s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3697_safety_0.smt2  |   1.971s  |   1.971s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5497_safety_0.smt2  |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6135_terminationG_0.smt2  |  43.095s  |  43.095s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6217_safety_0.smt2  |   1.096s  |   1.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6354_safety_0.smt2  |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6496_terminationG_0.smt2  | 126.531s  | 126.531s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6506_edge_closing_0.smt2  | 600.291s  | 600.291s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6932_safety_0.smt2  |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7017_terminationG_0.smt2  |   3.231s  |   3.231s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7192_safety_0.smt2  |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7210_terminationG_0.smt2  |   8.414s  |   8.414s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7211_terminationG_0.smt2  |  20.210s  |  20.210s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7322_safety_0.smt2  |   1.953s  |   1.953s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7607_terminationG_0.smt2  |  86.138s  |  86.138s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9479_terminationG_0.smt2  |  74.624s  |  74.624s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9558_terminationG_0.smt2  |   2.170s  |   2.170s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7969_safety_0.smt2  |   6.533s  |   6.533s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8073_terminationG_0.smt2  |   8.433s  |   8.433s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8337_safety_0.smt2  |   8.172s  |   8.172s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8348_safety_0.smt2  |   9.061s  |   9.061s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8402_safety_0.smt2  |   5.783s  |   5.783s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2  |   6.832s  |   6.832s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9027_safety_0.smt2  |   8.194s  |   8.194s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_11_0.smt2  |  22.905s  |  22.905s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_14_0.smt2  |  21.400s  |  21.400s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_15_0.smt2  |  22.013s  |  22.013s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_16_0.smt2  |  22.865s  |  22.865s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_19_0.smt2  |  25.835s  |  25.835s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_24_0.smt2  |  19.035s  |  19.035s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_28_0.smt2  |  16.703s  |  16.703s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_2_0.smt2  |  23.333s  |  23.333s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2  |  20.659s  |  20.659s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_31_0.smt2  |  18.300s  |  18.300s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_5_0.smt2  |  16.334s  |  16.334s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2  | 237.793s  | 237.793s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_10_0.smt2  |  44.870s  |  44.870s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_11_0.smt2  |  40.400s  |  40.400s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_12_0.smt2  |  43.253s  |  43.253s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_13_0.smt2  |  44.767s  |  44.767s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_14_0.smt2  |  41.715s  |  41.715s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_15_0.smt2  |  41.792s  |  41.792s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_16_0.smt2  |  51.796s  |  51.796s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_17_0.smt2  |  40.515s  |  40.515s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_18_0.smt2  |  39.854s  |  39.854s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2  |  47.843s  |  47.843s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_1_0.smt2  | 207.289s  | 207.289s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_20_0.smt2  |  37.130s  |  37.130s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_21_0.smt2  |  44.730s  |  44.730s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_22_0.smt2  |  51.863s  |  51.863s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_23_0.smt2  |  47.547s  |  47.547s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_24_0.smt2  |  55.596s  |  55.596s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_25_0.smt2  |  55.876s  |  55.876s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_26_0.smt2  |  58.861s  |  58.861s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_27_0.smt2  |  67.117s  |  67.117s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2  |  38.663s  |  38.663s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_29_0.smt2  |  53.887s  |  53.887s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_2_0.smt2  | 199.435s  | 199.435s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_3_0.smt2  | 166.555s  | 166.555s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_4_0.smt2  | 189.545s  | 189.545s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_5_0.smt2  | 229.755s  | 229.755s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_6_0.smt2  | 225.662s  | 225.662s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_7_0.smt2  | 264.577s  | 264.577s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_8_0.smt2  | 359.060s  | 359.060s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_9_0.smt2  | 183.784s  | 183.784s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__narrowKonv_rec.jar-obl-8__p11136_edge_closing_0.smt2  |   6.919s  |   6.919s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__narrowing_rec.jar-obl-8__p11066_terminationG_0.smt2  |  32.188s  |  32.188s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__narrowing_rec.jar-obl-8__p11067_terminationG_0.smt2  | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__upAndDown_rec.jar-obl-8__p13161_edge_closing_0.smt2  | 199.721s  | 199.721s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14933_safety_0.smt2  |  23.059s  |  23.059s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__whileSingle_rec.jar-obl-8__p15018_terminationG_0.smt2  | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__Prim_4.t2__p7936_terminationG_0.smt2   |   1.159s  |   1.159s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__Prim_4.t2__p7976_terminationG_0.smt2   |   1.441s  |   1.441s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__Prim_4.t2__p8016_terminationG_0.smt2   |   1.052s  |   1.052s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__Prim_4.t2__p8035_terminationG_0.smt2   |   2.397s  |   2.397s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__afagp-fail.t2__p15516_edge_closing_0.smt2  |  40.047s  |  40.047s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__agafp.t2__p15626_terminationG_0.smt2   |  10.849s  |  10.849s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__agafp.t2__p15636_terminationG_0.smt2   |  21.304s  |  21.304s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__agafp.t2__terminationS_0_0.smt2        | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2__p15941_terminationG_0.smt2  | 600.472s  | 600.472s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2__p16000_terminationG_0.smt2  | 382.485s  | 382.485s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2__p16028_terminationG_0.smt2  | 600.301s  | 600.301s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2_fixed__p15799_terminationG_0.smt2  | 600.464s  | 600.464s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2_fixed__p15830_terminationG_0.smt2  | 151.309s  | 151.309s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2_fixed__p15846_terminationG_0.smt2  | 600.326s  | 600.326s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted.t2__p16269_terminationG_0.smt2  | 431.865s  | 431.865s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2  | 600.331s  | 600.331s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted.t2__p16298_terminationG_0.smt2  | 600.356s  | 600.356s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted.t2_fixed__p16101_terminationG_0.smt2  | 326.396s  | 326.396s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted.t2_fixed__p16110_terminationG_0.smt2  |  37.403s  |  37.403s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-live.t2__p16639_terminationG_0.smt2  | 109.877s  | 109.877s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-live.t2_fixed__p16559_terminationG_0.smt2  |   3.691s  |   3.691s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-live.t2_fixed__p16560_terminationG_0.smt2  | 367.012s  | 367.012s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-live.t2_fixed__p16564_terminationG_0.smt2  |   3.920s  |   3.920s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2  | 408.037s  | 408.037s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchildlive-succeed.t2__p16426_terminationG_0.smt2  | 600.442s  | 600.442s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__brp_withassume.t2__p17437_edge_closing_0.smt2  | 600.246s  | 600.246s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__bs.t2_fixed__p17456_terminationG_0.smt2  |  61.196s  |  61.196s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__db2.t2__term_unfeasibility_0_0.smt2    |  25.406s  |  25.406s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__db2.t2__terminationQ_0_0.smt2          | 103.915s  | 103.915s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__db3.t2__term_unfeasibility_0_0.smt2    |  21.462s  |  21.462s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__db3.t2__terminationQ_0_0.smt2          |  87.136s  |  87.136s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__destroy_seg_leak.t2_fixed__p18858_edge_closing_0.smt2  | 600.407s  | 600.407s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__dumper.t2__p19134_terminationG_0.smt2  | 600.167s  | 600.167s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__edn.t2__p20326_safety_0.smt2           |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__edn.t2__p20632_safety_0.smt2           |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__edn.t2__p20710_safety_0.smt2           |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__efegp.t2__p21961_edge_closing_0.smt2   | 186.572s  | 186.572s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ex11.t2__p22126_terminationG_0.smt2    |  28.826s  |  28.826s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ex36.t2__p30283_safety_0.smt2          |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ex36.t2__p31845_safety_0.smt2          |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ex36.t2__p31955_safety_0.smt2          |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ex36.t2_fixed__p23592_safety_0.smt2    |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__firewire.t2__p32301_edge_closing_0.smt2  | 208.045s  | 208.045s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__firewire.t2__terminationS_19_0.smt2    |   9.859s  |   9.859s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__florian_sas2.t2__p32380_terminationG_0.smt2  | 549.842s  | 549.842s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__florian_sas2.t2__p32384_terminationG_0.smt2  |  39.202s  |  39.202s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__florian_sas2.t2__p32399_terminationG_0.smt2  |  27.939s  |  27.939s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_13_0.smt2         | 600.542s  | 600.542s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_14_0.smt2         | 600.556s  | 600.556s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_15_0.smt2         | 600.564s  | 600.564s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_16_0.smt2         | 596.307s  | 596.307s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_17_0.smt2         | 600.587s  | 600.587s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_18_0.smt2         | 600.563s  | 600.563s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_19_0.smt2         | 600.639s  | 600.639s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_20_0.smt2         | 521.788s  | 521.788s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_22_0.smt2         | 600.591s  | 600.591s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_24_0.smt2         | 600.663s  | 600.663s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_26_0.smt2         | 600.552s  | 600.552s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_28_0.smt2         | 600.515s  | 600.515s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_2_0.smt2          | 600.591s  | 600.591s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_31_0.smt2         | 600.565s  | 600.565s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_32_0.smt2         | 600.556s  | 600.556s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_3_0.smt2          | 600.603s  | 600.603s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_4_0.smt2          | 450.633s  | 450.633s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_6_0.smt2          | 600.553s  | 600.553s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_7_0.smt2          | 600.510s  | 600.510s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_8_0.smt2          | 597.629s  | 597.629s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32602_terminationG_0.smt2  | 600.191s  | 600.191s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32699_edge_closing_0.smt2  | 600.176s  | 600.176s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fourn.t2__p32708_terminationG_0.smt2   | 600.261s  | 600.261s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fourn.t2__p32713_terminationG_0.smt2   | 600.198s  | 600.198s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1.t2__terminationQ_0_0.smt2         |  25.579s  |  25.579s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1.t2_fixed__p705_terminationG_0.smt2  |  36.149s  |  36.149s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1.t2_fixed__p721_terminationG_0.smt2  |  32.143s  |  32.143s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1.t2_fixed__p784_terminationG_0.smt2  |  32.126s  |  32.126s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2__p597_terminationG_0.smt2     |  40.623s  |  40.623s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2__p626_terminationG_0.smt2     | 277.733s  | 277.733s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2__p679_terminationG_0.smt2     |   9.788s  |   9.788s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2__p680_terminationG_0.smt2     |  22.152s  |  22.152s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2__terminationQ_0_0.smt2        |  25.118s  |  25.118s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2  |   7.050s  |   7.050s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2_fixed__p551_terminationG_0.smt2  |  68.300s  |  68.300s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2  |  33.868s  |  33.868s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun6.t2__p1092_terminationG_0.smt2     |  17.096s  |  17.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun6.t2_fixed__p1055_terminationG_0.smt2  | 134.342s  | 134.342s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun6.t2_fixed__p1066_edge_closing_0.smt2  | 600.176s  | 600.176s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun7.t2__p1142_terminationG_0.smt2     |  21.849s  |  21.849s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun7.t2__p1167_edge_closing_0.smt2     | 600.256s  | 600.256s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1287_edge_closing_0.smt2     |   1.756s  |   1.756s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1309_edge_closing_0.smt2     |  17.179s  |  17.179s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1314_edge_closing_0.smt2     |   8.121s  |   8.121s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1320_edge_closing_0.smt2     |   3.398s  |   3.398s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1354_edge_closing_0.smt2     |  16.126s  |  16.126s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1357_edge_closing_0.smt2     |  10.849s  |  10.849s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1377_edge_closing_0.smt2     |   1.176s  |   1.176s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1378_edge_closing_0.smt2     |   5.739s  |   5.739s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1393_edge_closing_0.smt2     |  30.695s  |  30.695s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1398_edge_closing_0.smt2     |   0.630s  |   0.630s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1406_edge_closing_0.smt2     |  26.788s  |  26.788s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1409_edge_closing_0.smt2     |  23.232s  |  23.232s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1413_edge_closing_0.smt2     |   6.595s  |   6.595s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1437_edge_closing_0.smt2     |  13.625s  |  13.625s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1440_edge_closing_0.smt2     |   4.404s  |   4.404s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1460_edge_closing_0.smt2     |   3.474s  |   3.474s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1467_edge_closing_0.smt2     |  55.136s  |  55.136s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1485_edge_closing_0.smt2     |  28.961s  |  28.961s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2  | 600.207s  | 600.207s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_19_0.smt2  |  30.740s  |  30.740s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_21_0.smt2  |  27.739s  |  27.739s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2  |  16.596s  |  16.596s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_26_0.smt2  |  19.728s  |  19.728s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_49_0.smt2  |  27.419s  |  27.419s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_50_0.smt2  |  48.193s  |  48.193s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1608_terminationG_0.smt2  | 600.330s  | 600.330s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_25_0.smt2  |   8.857s  |   8.857s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_26_0.smt2  |   9.219s  |   9.219s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_27_0.smt2  |  16.174s  |  16.174s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_55_0.smt2  |   7.647s  |   7.647s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_25_0.smt2  |  16.757s  |  16.757s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2  |  14.637s  |  14.637s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_49_0.smt2  |  27.472s  |  27.472s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_51_0.smt2  |  54.880s  |  54.880s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_26_0.smt2  |   9.272s  |   9.272s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2  |   9.967s  |   9.967s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_57_0.smt2  |  21.092s  |  21.092s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_62_0.smt2  |   8.730s  |   8.730s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2__p1768_terminationG_0.smt2      | 248.390s  | 248.390s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2__terminationS_25_0.smt2         |  13.787s  |  13.787s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2_fixed__terminationS_24_0.smt2   |   8.154s  |   8.154s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2_fixed__terminationS_53_0.smt2   |  29.560s  |  29.560s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2_fixed__terminationS_54_0.smt2   |   8.371s  |   8.371s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2_fixed__terminationS_55_0.smt2   |  10.823s  |  10.823s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__janne_complex.t2__p2020_terminationG_0.smt2  |   5.726s  |   5.726s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__janne_complex.t2__p2041_terminationG_0.smt2  |  33.021s  |  33.021s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__janne_complex.t2__p2193_terminationG_0.smt2  |   5.619s  |   5.619s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__janne_complex.t2__p2254_terminationG_0.smt2  |   5.479s  |   5.479s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__janne_complex.t2__p2263_terminationG_0.smt2  |   5.769s  |   5.769s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__matmul.t2_fixed__p2649_terminationG_0.smt2  |   6.626s  |   6.626s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91.t2__p2940_edge_closing_0.smt2     |   0.578s  |   0.578s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3164_terminationG_0.smt2  | 190.140s  | 190.140s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3169_terminationG_0.smt2  |  33.729s  |  33.729s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3221_terminationG_0.smt2  | 121.489s  | 121.489s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3249_terminationG_0.smt2  | 359.776s  | 359.776s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3256_terminationG_0.smt2  |  63.506s  |  63.506s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3301_terminationG_0.smt2  | 156.000s  | 156.000s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3311_terminationG_0.smt2  | 148.346s  | 148.346s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3358_terminationG_0.smt2  |  19.746s  |  19.746s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n-5.t2__p4677_terminationG_0.smt2      |  33.919s  |  33.919s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n-5.t2__p4682_terminationG_0.smt2      |  25.053s  |  25.053s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n-5.t2__p4703_edge_closing_0.smt2      |   6.257s  |   6.257s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n-5.t2_fixed__p4589_terminationG_0.smt2  |   0.599s  |   0.599s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6188_terminationG_0.smt2  | 600.184s  | 600.184s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6193_terminationG_0.smt2  | 600.188s  | 600.188s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6198_terminationG_0.smt2  | 600.172s  | 600.172s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6202_terminationG_0.smt2  | 600.172s  | 600.172s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6218_terminationG_0.smt2  | 600.147s  | 600.147s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6219_terminationG_0.smt2  | 600.235s  | 600.235s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6225_edge_closing_0.smt2  |   6.925s  |   6.925s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__nakata.t2__p5305_terminationG_0.smt2   |   2.229s  |   2.229s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__nakata.t2__p5310_terminationG_0.smt2   | 600.275s  | 600.275s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__nakata.t2__p5352_edge_closing_0.smt2   | 600.394s  | 600.394s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__nakata.t2__terminationS_6_0.smt2       |  10.520s  |  10.520s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__opt-tree.c.t2__p6339_terminationG_0.smt2  |   1.158s  |   1.158s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__opt-tree.c.t2__p6340_terminationG_0.smt2  |  39.698s  |  39.698s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__p-5.t2_fixed__p6782_edge_closing_0.smt2  |   4.529s  |   4.529s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__pgarch.t2__p7283_terminationG_0.smt2   |   1.887s  |   1.887s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__polyrank4.t2__p7477_terminationG_0.smt2  |   1.498s  |   1.498s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__polyrank4.t2__p7482_terminationG_0.smt2  |   1.378s  |   1.378s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__polyrank4.t2__p7520_terminationG_0.smt2  |  19.719s  |  19.719s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__polyrank5.t2__p7556_terminationG_0.smt2  |   7.649s  |   7.649s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ppblock.t2__p7746_edge_closing_0.smt2  |   1.509s  |   1.509s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ppblockterm.t2__p7916_edge_closing_0.smt2  |   2.863s  |   2.863s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__randomwalk.t2__p8416_terminationG_0.smt2  |  56.920s  |  56.920s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1-striped.t2__p12897_safety_0.smt2    |   1.223s  |   1.223s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1-striped.t2__p12943_safety_0.smt2    |   3.010s  |   3.010s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1-striped.t2_fixed__p9299_terminationG_0.smt2  |  89.103s  |  89.103s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1-striped.t2_fixed__p9992_safety_0.smt2  |   4.903s  |   4.903s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p17922_terminationG_0.smt2      | 170.173s  | 170.173s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p17931_terminationG_0.smt2      |  21.290s  |  21.290s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p18338_safety_0.smt2            |   1.602s  |   1.602s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p18948_safety_0.smt2            |   2.460s  |   2.460s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p19377_safety_0.smt2            |   4.234s  |   4.234s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p19834_safety_0.smt2            |   1.445s  |   1.445s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p19848_safety_0.smt2            |   0.947s  |   0.947s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2_fixed__p15165_terminationG_0.smt2  | 253.568s  | 253.568s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2_fixed__p15180_terminationG_0.smt2  | 108.596s  | 108.596s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sas2.t2__p21297_terminationG_0.smt2    | 600.171s  | 600.171s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sas2.t2__p21302_terminationG_0.smt2    | 182.188s  | 182.188s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sas2.t2__p21311_terminationG_0.smt2    |  36.451s  |  36.451s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sas2.t2__terminationS_1_0.smt2         |  12.581s  |  12.581s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__select.t2__p21400_edge_closing_0.smt2  | 462.550s  | 462.550s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3-new.t2__p22118_edge_closing_0.smt2  |  27.352s  |  27.352s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3-new.t2_fixed__p21803_terminationG_0.smt2  | 600.538s  | 600.538s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3.t2_fixed__p22135_terminationG_0.smt2  | 600.583s  | 600.583s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22479_terminationG_0.smt2  |  22.392s  |  22.392s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22519_safety_0.smt2  |   9.137s  |   9.137s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22531_terminationG_0.smt2  |  97.541s  |  97.541s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22603_safety_0.smt2  |   3.562s  |   3.562s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22607_safety_0.smt2  |   1.704s  |   1.704s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22639_terminationG_0.smt2  |  74.415s  |  74.415s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22640_terminationG_0.smt2  | 447.641s  | 447.641s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22688_terminationG_0.smt2  | 330.998s  | 330.998s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-5-filtered.t2__p22882_terminationG_0.smt2  |   0.600s  |   0.600s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2  |   1.113s  |   1.113s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__small15.t2__p23742_terminationG_0.smt2  |   4.137s  |   4.137s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__small15.t2__p23781_edge_closing_0.smt2  |   2.057s  |   2.057s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__st88.t2__p24217_terminationG_0.smt2    |   4.031s  |   4.031s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2__p24620_terminationG_0.smt2  |  49.624s  |  49.624s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2__p24634_terminationG_0.smt2  | 170.916s  | 170.916s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2__p24649_terminationG_0.smt2  | 600.237s  | 600.237s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2__p24820_edge_closing_0.smt2  |   9.012s  |   9.012s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2__p24821_edge_closing_0.smt2  |  69.493s  |  69.493s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2_fixed__p24590_edge_closing_0.smt2  |  40.845s  |  40.845s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2_fixed__p24591_edge_closing_0.smt2  | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver.bug.t2__p24573_terminationG_0.smt2  | 306.592s  | 306.592s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sudoku.t2__p24862_terminationG_0.smt2  | 175.744s  | 175.744s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sudoku.t2__p24867_terminationG_0.smt2  | 102.114s  | 102.114s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2  |  22.669s  |  22.669s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_28_0.smt2  |  26.163s  |  26.163s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2  |  21.920s  |  21.920s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__svdcmp.t2__term_unfeasibility_8_0.smt2  |   7.906s  |   7.906s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25001_terminationG_0.smt2  | 600.341s  | 600.341s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25046_edge_closing_0.smt2  | 427.827s  | 427.827s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2  | 418.906s  | 418.906s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__tqli.t2__p25217_terminationG_0.smt2    | 600.271s  | 600.271s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__tqli.t2_fixed__p25201_edge_closing_0.smt2  | 600.173s  | 600.173s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2  |   2.465s  |   2.465s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/SAT14/1813.smt2                                     |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/SAT14/585.smt2                                      |   1.625s  |   1.625s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/MC_03.smt2                                     | 600.147s  | 600.147s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/MC_09.smt2                                     | 600.286s  | 600.286s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/MC_11.smt2                                     | 600.406s  | 600.406s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/MF_03.smt2                                     | 600.164s  | 600.164s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/MS_04.smt2                                     | 600.174s  | 600.174s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/RTA_093.smt2                                   | 600.703s  | 600.703s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/SC_08.smt2                                     | 600.183s  | 600.183s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0013.smt2                                  | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0014.smt2                                  | 600.142s  | 600.142s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0022.smt2                                  | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0023.smt2                                  | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0031.smt2                                  | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0032.smt2                                  | 600.183s  | 600.183s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0040.smt2                                  | 600.133s  | 600.133s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0041.smt2                                  | 600.140s  | 600.140s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0049.smt2                                  | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0050.smt2                                  | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0052.smt2                                  | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0058.smt2                                  | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0066.smt2                                  | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0067.smt2                                  | 600.131s  | 600.131s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0068.smt2                                  | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0070.smt2                                  | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0076.smt2                                  | 600.151s  | 600.151s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0077.smt2                                  | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0085.smt2                                  | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0097.smt2                                  |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0099.smt2                                  |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0100.smt2                                  | 600.159s  | 600.159s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0103.smt2                                  | 600.174s  | 600.174s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0104.smt2                                  | 600.141s  | 600.141s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0110.smt2                                  | 600.147s  | 600.147s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0112.smt2                                  | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0113.smt2                                  | 600.165s  | 600.165s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0121.smt2                                  | 600.159s  | 600.159s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0122.smt2                                  | 600.131s  | 600.131s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0130.smt2                                  | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0131.smt2                                  | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0136.smt2                                  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0138.smt2                                  | 600.157s  | 600.157s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0139.smt2                                  | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0140.smt2                                  | 600.142s  | 600.142s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0148.smt2                                  | 600.126s  | 600.126s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0149.smt2                                  | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0153.smt2                                  |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0157.smt2                                  | 600.212s  | 600.212s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0158.smt2                                  | 600.227s  | 600.227s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0163.smt2                                  | 600.160s  | 600.160s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0175.smt2                                  | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0176.smt2                                  | 600.158s  | 600.158s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0184.smt2                                  | 600.221s  | 600.221s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0190.smt2                                  |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0193.smt2                                  | 600.216s  | 600.216s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0194.smt2                                  | 600.156s  | 600.156s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0202.smt2                                  | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0203.smt2                                  | 600.126s  | 600.126s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0211.smt2                                  | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0212.smt2                                  | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0220.smt2                                  | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0221.smt2                                  | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0226.smt2                                  | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0229.smt2                                  | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0230.smt2                                  | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0236.smt2                                  | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0238.smt2                                  | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0239.smt2                                  | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0244.smt2                                  |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0247.smt2                                  | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0248.smt2                                  | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0257.smt2                                  | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0265.smt2                                  | 600.066s  | 600.066s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0266.smt2                                  | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0268.smt2                                  | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0274.smt2                                  | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0275.smt2                                  | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0283.smt2                                  | 600.141s  | 600.141s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0284.smt2                                  | 600.193s  | 600.193s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0286.smt2                                  | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0292.smt2                                  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0293.smt2                                  | 600.153s  | 600.153s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0300.smt2                                  | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0301.smt2                                  | 600.117s  | 600.117s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0302.smt2                                  | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0310.smt2                                  | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0311.smt2                                  | 600.133s  | 600.133s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0315.smt2                                  |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0319.smt2                                  | 600.166s  | 600.166s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0320.smt2                                  | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0325.smt2                                  | 600.165s  | 600.165s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0328.smt2                                  | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0329.smt2                                  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0330.smt2                                  |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0334.smt2                                  |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0337.smt2                                  | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0338.smt2                                  | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0346.smt2                                  | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0347.smt2                                  | 600.117s  | 600.117s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0350.smt2                                  | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0355.smt2                                  | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0356.smt2                                  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0364.smt2                                  | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0365.smt2                                  | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0366.smt2                                  | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0367.smt2                                  | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0368.smt2                                  | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0369.smt2                                  |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0373.smt2                                  | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0374.smt2                                  | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0382.smt2                                  | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0383.smt2                                  | 600.126s  | 600.126s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0389.smt2                                  | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0391.smt2                                  | 600.169s  | 600.169s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0392.smt2                                  | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0394.smt2                                  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0400.smt2                                  | 600.156s  | 600.156s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0401.smt2                                  | 600.130s  | 600.130s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0402.smt2                                  | 600.156s  | 600.156s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0409.smt2                                  | 600.127s  | 600.127s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0410.smt2                                  | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0411.smt2                                  | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0418.smt2                                  | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0419.smt2                                  | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0424.smt2                                  | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0426.smt2                                  | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0427.smt2                                  | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0428.smt2                                  | 600.166s  | 600.166s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0436.smt2                                  | 600.141s  | 600.141s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0437.smt2                                  | 600.201s  | 600.201s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0441.smt2                                  | 600.126s  | 600.126s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0445.smt2                                  | 600.154s  | 600.154s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0446.smt2                                  | 600.133s  | 600.133s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0451.smt2                                  | 600.175s  | 600.175s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0454.smt2                                  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0455.smt2                                  | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0463.smt2                                  | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0464.smt2                                  | 600.155s  | 600.155s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0472.smt2                                  | 600.127s  | 600.127s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0473.smt2                                  | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0481.smt2                                  | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0482.smt2                                  | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0483.smt2                                  | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0484.smt2                                  |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0486.smt2                                  |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0490.smt2                                  | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0493.smt2                                  |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0496.smt2                                  |  33.763s  |  33.763s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0498.smt2                                  | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0499.smt2                                  | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0500.smt2                                  | 600.086s  | 600.086s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0502.smt2                                  | 600.086s  | 600.086s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0508.smt2                                  | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0509.smt2                                  | 600.057s  | 600.057s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0517.smt2                                  | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0518.smt2                                  | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0527.smt2                                  | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0529.smt2                                  | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0530.smt2                                  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0535.smt2                                  | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0536.smt2                                  | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0537.smt2                                  | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0540.smt2                                  |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0544.smt2                                  | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0545.smt2                                  | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0551.smt2                                  | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0553.smt2                                  | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0554.smt2                                  | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0562.smt2                                  | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0563.smt2                                  | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0569.smt2                                  | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0571.smt2                                  | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0572.smt2                                  | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0578.smt2                                  | 600.177s  | 600.177s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0580.smt2                                  | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0581.smt2                                  | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0582.smt2                                  | 600.130s  | 600.130s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0589.smt2                                  | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0590.smt2                                  | 600.177s  | 600.177s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0592.smt2                                  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0597.smt2                                  | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0598.smt2                                  | 600.160s  | 600.160s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0599.smt2                                  | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0603.smt2                                  |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0607.smt2                                  | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0608.smt2                                  | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0611.smt2                                  | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0616.smt2                                  | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0617.smt2                                  | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0625.smt2                                  | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0626.smt2                                  | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0635.smt2                                  | 600.124s  | 600.124s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0642.smt2                                  | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0643.smt2                                  | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0644.smt2                                  | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0653.smt2                                  | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0656.smt2                                  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0661.smt2                                  | 600.151s  | 600.151s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0662.smt2                                  | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0670.smt2                                  | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0671.smt2                                  | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0678.smt2                                  |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0679.smt2                                  | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0680.smt2                                  | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0684.smt2                                  |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0688.smt2                                  | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0689.smt2                                  | 600.126s  | 600.126s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0697.smt2                                  | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0698.smt2                                  | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0703.smt2                                  |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0706.smt2                                  | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0707.smt2                                  | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0715.smt2                                  | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0716.smt2                                  | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0717.smt2                                  | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0719.smt2                                  | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0722.smt2                                  |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0723.smt2                                  | 600.154s  | 600.154s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0724.smt2                                  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0725.smt2                                  | 600.133s  | 600.133s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0733.smt2                                  | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0734.smt2                                  | 600.086s  | 600.086s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0740.smt2                                  | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0742.smt2                                  | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0743.smt2                                  | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0745.smt2                                  | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0751.smt2                                  | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0752.smt2                                  | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0760.smt2                                  | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0761.smt2                                  | 600.093s  | 600.093s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0768.smt2                                  | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0769.smt2                                  | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0770.smt2                                  | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0776.smt2                                  | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0778.smt2                                  | 600.086s  | 600.086s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0779.smt2                                  | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0787.smt2                                  | 600.055s  | 600.055s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0788.smt2                                  | 600.050s  | 600.050s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0796.smt2                                  | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0797.smt2                                  | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0805.smt2                                  | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0806.smt2                                  | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0814.smt2                                  | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0815.smt2                                  | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0816.smt2                                  |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0823.smt2                                  | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0824.smt2                                  | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0825.smt2                                  |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0832.smt2                                  | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0833.smt2                                  | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0834.smt2                                  | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0841.smt2                                  | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0842.smt2                                  | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0850.smt2                                  | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0851.smt2                                  | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0859.smt2                                  | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0860.smt2                                  | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0868.smt2                                  | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0869.smt2                                  | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0877.smt2                                  | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0878.smt2                                  | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0883.smt2                                  |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0884.smt2                                  | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0886.smt2                                  | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0887.smt2                                  | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0895.smt2                                  | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0896.smt2                                  | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0898.smt2                                  | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0901.smt2                                  | 600.124s  | 600.124s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0904.smt2                                  | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0906.smt2                                  | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0913.smt2                                  | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0914.smt2                                  | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0920.smt2                                  |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0922.smt2                                  | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0923.smt2                                  | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0931.smt2                                  | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0932.smt2                                  | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0940.smt2                                  | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0941.smt2                                  | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0944.smt2                                  |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0949.smt2                                  | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0950.smt2                                  | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0958.smt2                                  | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0959.smt2                                  | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0963.smt2                                  |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0967.smt2                                  | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0968.smt2                                  | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0976.smt2                                  | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0977.smt2                                  | 600.093s  | 600.093s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0983.smt2                                  | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0985.smt2                                  | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0986.smt2                                  | 600.086s  | 600.086s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0994.smt2                                  | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0995.smt2                                  | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/TA_03.smt2                                     | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/TA_05.smt2                                     | 600.158s  | 600.158s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/TA_13.smt2                                     | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInv128.smt2                          | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInv16.smt2                           | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInv32.smt2                           | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInv64.smt2                           | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInv8.smt2                            | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInvFull.smt2                         | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInvInitial.smt2                      | 600.069s  | 600.069s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInvStep.smt2                         | 600.140s  | 600.140s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInvStepSimplified.smt2               | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInvVar1.smt2                         | 600.133s  | 600.133s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/sqrtStepFinal.smt2                      | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/sqrtStepFinala.smt2                     | 600.151s  | 600.151s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT1335852993657230070.smt2                             |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT1437438160177275586.smt2                             |   2.776s  |   2.776s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT1700028870436976635.smt2                             |   2.491s  |   2.491s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT180444191153863419.smt2                              |   8.479s  |   8.479s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT1813676864021281701.smt2                             |  21.882s  |  21.882s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT2214668917450755150.smt2                             |   6.572s  |   6.572s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT2276070888632403184.smt2                             |  11.884s  |  11.884s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT3457830339872275636.smt2                             |   0.922s  |   0.922s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT3678576972294594665.smt2                             |  59.658s  |  59.658s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT3712394338782947208.smt2                             |  15.793s  |  15.793s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT3839584170547805483.smt2                             |  23.671s  |  23.671s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT4259464554444412647.smt2                             |   1.199s  |   1.199s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT463192377960637155.smt2                              |   4.693s  |   4.693s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT5210162955256537540.smt2                             |  16.476s  |  16.476s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT5468773551032053543.smt2                             |   6.692s  |   6.692s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT5521985939949569030.smt2                             |   3.001s  |   3.001s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT5642158517481563632.smt2                             |   3.733s  |   3.733s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT5753280746557461985.smt2                             |   0.830s  |   0.830s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT6531155344723557531.smt2                             |   3.405s  |   3.405s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT6545992645874542347.smt2                             | 600.117s  | 600.117s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT6647586385534524663.smt2                             |   7.526s  |   7.526s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT6828719750442006249.smt2                             |  24.530s  |  24.530s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT6981420136966712689.smt2                             |  10.809s  |  10.809s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT7201733644041072759.smt2                             |   5.003s  |   5.003s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT725924178667047452.smt2                              |   5.788s  |   5.788s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT7924349461296395393.smt2                             | 600.127s  | 600.127s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT8619300169146917506.smt2                             |   4.734s  |   4.734s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT9062228803117299674.smt2                             |  12.956s  |  12.956s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT9064001295904670492.smt2                             |   1.817s  |   1.817s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/LCTES/digital-stopwatch.locals.nosummaries.smt2                      | 387.781s  | 387.781s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/LCTES/digital-stopwatch.locals.smt2                                  |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/LassoRanker/ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.607s  |   0.607s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-3wwoHp.smt2                                             | 557.460s  | 557.460s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-607QpU.smt2                                             |  13.630s  |  13.630s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-6k3pKM.smt2                                             |   0.895s  |   0.895s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-7fXGzy.smt2                                             |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-K5O3aH.smt2                                             |  69.161s  |  69.161s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-MVylXc.smt2                                             | 600.221s  | 600.221s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-l6cqQI.smt2                                             | 600.236s  | 600.236s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-p9MQp4.smt2                                             |   3.103s  |   3.103s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-unsat-02.smt2                                           | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-unsat-03.smt2                                           | 600.211s  | 600.211s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-unsat-04.smt2                                           | 600.160s  | 600.160s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-unsat-05.smt2                                           | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/mcm/26.smt2                                                          | 600.149s  | 600.149s  |   0.000s  | 0.0%|
</details>
