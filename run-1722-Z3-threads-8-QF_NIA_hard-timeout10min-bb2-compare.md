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
Job tag: Z3-threads-8-QF_NIA_hard-timeout10min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: f880fdccee614547c38c19beb7af5a027961646b
Z3 branch: core_min
Z3 options: "-T:600 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_NIA.tar.zst?download=1
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-QF_NIA_hard-timeout10min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: f880fdccee614547c38c19beb7af5a027961646b
Z3 branch: core_min
Z3 options: "-T:600 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_NIA.tar.zst?download=1
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  | 600.224s  | 600.224s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |   6.209s  |   6.209s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   7.421s  |   7.421s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |  59.785s  |  59.785s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  46.720s  |  46.720s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  | 600.155s  | 600.155s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |  53.408s  |  53.408s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  | 133.549s  | 133.549s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  11.932s  |  11.932s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  | 120.502s  | 120.502s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |  44.678s  |  44.678s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  28.865s  |  28.865s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.881s  |   0.881s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  | 101.293s  | 101.293s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |   1.725s  |   1.725s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |  58.525s  |  58.525s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   4.280s  |   4.280s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  | 600.224s  | 600.224s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |   6.209s  |   6.209s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   7.421s  |   7.421s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |  59.785s  |  59.785s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  46.720s  |  46.720s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  | 600.155s  | 600.155s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |  53.408s  |  53.408s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  | 133.549s  | 133.549s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  11.932s  |  11.932s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  | 120.502s  | 120.502s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |  44.678s  |  44.678s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  28.865s  |  28.865s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.881s  |   0.881s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  | 101.293s  | 101.293s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |   1.725s  |   1.725s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |  58.525s  |  58.525s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   4.280s  |   4.280s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  | 600.224s  | 600.224s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |   6.209s  |   6.209s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   7.421s  |   7.421s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |  59.785s  |  59.785s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  46.720s  |  46.720s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  | 600.155s  | 600.155s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |  53.408s  |  53.408s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  | 133.549s  | 133.549s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  11.932s  |  11.932s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  | 120.502s  | 120.502s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |  44.678s  |  44.678s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  28.865s  |  28.865s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.881s  |   0.881s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  | 101.293s  | 101.293s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |   1.725s  |   1.725s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |  58.525s  |  58.525s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   4.280s  |   4.280s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  | 600.224s  | 600.224s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |   6.209s  |   6.209s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   7.421s  |   7.421s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |  59.785s  |  59.785s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  46.720s  |  46.720s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  | 600.155s  | 600.155s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |  53.408s  |  53.408s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  | 133.549s  | 133.549s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  11.932s  |  11.932s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  | 120.502s  | 120.502s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |  44.678s  |  44.678s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  28.865s  |  28.865s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.881s  |   0.881s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  | 101.293s  | 101.293s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |   1.725s  |   1.725s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |  58.525s  |  58.525s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   4.280s  |   4.280s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_NIA/20220315-MathProblems/RTA_093.smt2                                  | 601.085s |8230.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_19_0.smt2        | 600.798s |7021.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_15_0.smt2        | 600.779s |7156.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_26_0.smt2        | 600.773s |7178.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_24_0.smt2        | 600.771s |7155.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_14_0.smt2        | 600.768s |7073.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_28_0.smt2        | 600.727s |6899.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_6_0.smt2         | 600.722s |6596.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3-new.t2_fixed__p21803_terminationG_0.smt2 | 600.700s |5599.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_31_0.smt2        | 600.697s |6867.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_13_0.smt2        | 600.684s |6891.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_18_0.smt2        | 600.671s |6898.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_32_0.smt2        | 600.669s |6844.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3.t2_fixed__p22135_terminationG_0.smt2 | 600.667s |6358.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_7_0.smt2         | 600.664s |6616.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_22_0.smt2        | 600.662s |6835.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_3_0.smt2         | 600.653s |6723.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_8_0.smt2         | 600.653s |6543.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_17_0.smt2        | 600.604s |6746.0MiB|
|non-incremental/QF_NIA/20220315-MathProblems/MC_11.smt2                                    | 600.488s |4153.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_NIA/20220315-MathProblems/RTA_093.smt2                                  | 601.085s |8230.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_19_0.smt2        | 600.798s |7021.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_15_0.smt2        | 600.779s |7156.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_26_0.smt2        | 600.773s |7178.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_24_0.smt2        | 600.771s |7155.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_14_0.smt2        | 600.768s |7073.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_28_0.smt2        | 600.727s |6899.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_6_0.smt2         | 600.722s |6596.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3-new.t2_fixed__p21803_terminationG_0.smt2 | 600.700s |5599.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_31_0.smt2        | 600.697s |6867.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_13_0.smt2        | 600.684s |6891.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_18_0.smt2        | 600.671s |6898.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_32_0.smt2        | 600.669s |6844.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3.t2_fixed__p22135_terminationG_0.smt2 | 600.667s |6358.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_7_0.smt2         | 600.664s |6616.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_22_0.smt2        | 600.662s |6835.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_3_0.smt2         | 600.653s |6723.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_8_0.smt2         | 600.653s |6543.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_17_0.smt2        | 600.604s |6746.0MiB|
|non-incremental/QF_NIA/20220315-MathProblems/MC_11.smt2                                    | 600.488s |4153.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  |2349.0MiB|2349.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |284.0MiB|284.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |388.0MiB|388.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |231.0MiB|231.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |1877.0MiB|1877.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |540.0MiB|540.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |542.0MiB|542.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |340.0MiB|340.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |841.0MiB|841.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |884.0MiB|884.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |1249.0MiB|1249.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |439.0MiB|439.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |1064.0MiB|1064.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |1049.0MiB|1049.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |763.0MiB|763.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |282.0MiB|282.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |2080.0MiB|2080.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |329.0MiB|329.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |794.0MiB|794.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |505.0MiB|505.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  |2349.0MiB|2349.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |284.0MiB|284.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |388.0MiB|388.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |231.0MiB|231.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |1877.0MiB|1877.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |540.0MiB|540.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |542.0MiB|542.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |340.0MiB|340.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |841.0MiB|841.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |884.0MiB|884.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |1249.0MiB|1249.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |439.0MiB|439.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |1064.0MiB|1064.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |1049.0MiB|1049.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |763.0MiB|763.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |282.0MiB|282.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |2080.0MiB|2080.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |329.0MiB|329.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |794.0MiB|794.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |505.0MiB|505.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  |2349.0MiB|2349.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |284.0MiB|284.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |388.0MiB|388.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |231.0MiB|231.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |1877.0MiB|1877.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |540.0MiB|540.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |542.0MiB|542.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |340.0MiB|340.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |841.0MiB|841.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |884.0MiB|884.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |1249.0MiB|1249.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |439.0MiB|439.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |1064.0MiB|1064.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |1049.0MiB|1049.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |763.0MiB|763.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |282.0MiB|282.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |2080.0MiB|2080.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |329.0MiB|329.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |794.0MiB|794.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |505.0MiB|505.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  |2349.0MiB|2349.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |284.0MiB|284.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |388.0MiB|388.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |231.0MiB|231.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |1877.0MiB|1877.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |540.0MiB|540.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |542.0MiB|542.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |340.0MiB|340.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |841.0MiB|841.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |884.0MiB|884.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |1249.0MiB|1249.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |439.0MiB|439.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |1064.0MiB|1064.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |1049.0MiB|1049.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |763.0MiB|763.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |282.0MiB|282.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |2080.0MiB|2080.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |329.0MiB|329.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |794.0MiB|794.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |505.0MiB|505.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_NIA/20220315-MathProblems/RTA_093.smt2                                  | 601.085s |8230.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_26_0.smt2        | 600.773s |7178.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_15_0.smt2        | 600.779s |7156.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_24_0.smt2        | 600.771s |7155.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_14_0.smt2        | 600.768s |7073.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_19_0.smt2        | 600.798s |7021.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_28_0.smt2        | 600.727s |6899.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_18_0.smt2        | 600.671s |6898.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_13_0.smt2        | 600.684s |6891.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_31_0.smt2        | 600.697s |6867.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_32_0.smt2        | 600.669s |6844.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_22_0.smt2        | 600.662s |6835.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_16_0.smt2        | 551.093s |6833.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_20_0.smt2        | 523.819s |6787.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_17_0.smt2        | 600.604s |6746.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_3_0.smt2         | 600.653s |6723.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_7_0.smt2         | 600.664s |6616.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_6_0.smt2         | 600.722s |6596.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_2_0.smt2         | 578.942s |6586.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_8_0.smt2         | 600.653s |6543.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_NIA/20220315-MathProblems/RTA_093.smt2                                  | 601.085s |8230.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_26_0.smt2        | 600.773s |7178.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_15_0.smt2        | 600.779s |7156.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_24_0.smt2        | 600.771s |7155.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_14_0.smt2        | 600.768s |7073.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_19_0.smt2        | 600.798s |7021.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_28_0.smt2        | 600.727s |6899.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_18_0.smt2        | 600.671s |6898.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_13_0.smt2        | 600.684s |6891.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_31_0.smt2        | 600.697s |6867.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_32_0.smt2        | 600.669s |6844.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_22_0.smt2        | 600.662s |6835.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_16_0.smt2        | 551.093s |6833.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_20_0.smt2        | 523.819s |6787.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_17_0.smt2        | 600.604s |6746.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_3_0.smt2         | 600.653s |6723.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_7_0.smt2         | 600.664s |6616.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_6_0.smt2         | 600.722s |6596.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_2_0.smt2         | 578.942s |6586.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_8_0.smt2         | 600.653s |6543.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  | 600.224s  | 600.224s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |   6.209s  |   6.209s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   7.421s  |   7.421s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |  59.785s  |  59.785s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  46.720s  |  46.720s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  | 600.155s  | 600.155s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |  53.408s  |  53.408s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  | 133.549s  | 133.549s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  11.932s  |  11.932s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  | 120.502s  | 120.502s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |  44.678s  |  44.678s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  28.865s  |  28.865s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.881s  |   0.881s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  | 101.293s  | 101.293s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |   1.725s  |   1.725s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |  58.525s  |  58.525s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   4.280s  |   4.280s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__MirrorInterv.c__p24379_terminationG_0.smt2  |   1.911s  |   1.911s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__MirrorInterv.c__p24450_edge_closing_0.smt2  | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__MirrorIntervSim.c__p24484_terminationG_0.smt2  | 600.198s  | 600.198s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__NO_03.c__p24634_terminationG_0.smt2  |   4.673s  |   4.673s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__NO_13.c__p24750_terminationG_0.smt2  | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__NO_24.c__p24816_terminationG_0.smt2  | 436.041s  | 436.041s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Narrowing.c__p24540_terminationG_0.smt2  | 600.225s  | 600.225s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__NonTerminationSimple7_false-termination.c__p25148_terminationG_0.smt2  | 600.152s  | 600.152s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25430_terminationG_0.smt2  |   1.801s  |   1.801s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Pure3Phase_true-termination.c__p25560_terminationG_0.smt2  | 213.431s  | 213.431s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Swingers.c__p26085_terminationG_0.smt2  | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2  |  10.511s  |  10.511s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__UpAndDown.c__p26203_terminationG_0.smt2  | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__UpAndDownIneq.c__p26235_terminationG_0.smt2  |   8.400s  |   8.400s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__UpAndDownIneq.c__p26236_terminationG_0.smt2  | 600.156s  | 600.156s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2  |   2.784s  |   2.784s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2  |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27027_terminationG_0.smt2  |   0.790s  |   0.790s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27084_terminationG_0.smt2  |  36.909s  |  36.909s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27136_terminationG_0.smt2  |  20.659s  |  20.659s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27151_terminationG_0.smt2  |  20.082s  |  20.082s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27166_terminationG_0.smt2  |   3.888s  |   3.888s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27186_terminationG_0.smt2  |  13.551s  |  13.551s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27222_terminationG_0.smt2  |  10.956s  |  10.956s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27236_edge_closing_0.smt2  |   3.155s  |   3.155s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27239_edge_closing_0.smt2  |   3.608s  |   3.608s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27687_edge_closing_0.smt2  |   1.301s  |   1.301s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__p27530_edge_closing_0.smt2  |   1.660s  |   1.660s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__BinTreeChanger.jar-obl-10__p27729_terminationG_0.smt2  |   1.325s  |   1.325s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2  |  12.768s  |  12.768s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Count.jar-obl-10-2__p28115_terminationG_0.smt2  |  11.098s  |  11.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Count.jar-obl-10-2__p28120_terminationG_0.smt2  |  22.451s  |  22.451s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2  |   7.130s  |   7.130s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__DivTernary.jar-obl-10__terminationQ_0_0.smt2  |  34.134s  |  34.134s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Flatten.jar-obl-10__p29378_safety_0.smt2  |   1.066s  |   1.066s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Graph.jar-obl-17__p29763_edge_closing_0.smt2  | 532.528s  | 532.528s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Graph.jar-obl-17__p29774_edge_closing_0.smt2  |   4.810s  |   4.810s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__LessLeaves.jar-obl-10__p10002_edge_closing_0.smt2  | 600.245s  | 600.245s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__LessLeaves.jar-obl-10__p10014_edge_closing_0.smt2  | 600.238s  | 600.238s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__LessLeavesRec.jar-obl-10__p10043_terminationG_0.smt2  |  22.238s  |  22.238s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__List.jar-obl-12__p10223_edge_closing_0.smt2  |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MainFind.jar-obl-10__p10608_edge_closing_0.smt2  |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MainFind.jar-obl-10__p10621_edge_closing_0.smt2  |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MainGet.jar-obl-10__p10695_edge_closing_0.smt2  |   0.896s  |   0.896s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MainMove.jar-obl-11__p10745_edge_closing_0.smt2  |   0.596s  |   0.596s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MainMove.jar-obl-11__p10752_edge_closing_0.smt2  |   0.971s  |   0.971s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Matrix.jar-obl-16__p10775_terminationG_0.smt2  |  41.452s  |  41.452s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Matrix.jar-obl-16__p10815_safety_0.smt2  |   2.786s  |   2.786s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Matrix.jar-obl-16__p10849_edge_closing_0.smt2  | 126.221s  | 126.221s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10899_terminationG_0.smt2  |  26.037s  |  26.037s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MysteriousProgram.jar-obl-12__p11031_terminationG_0.smt2  |  88.814s  |  88.814s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationQ_0_0.smt2  |  67.916s  |  67.916s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__NO_13.jar-obl-8__p11405_terminationG_0.smt2  | 600.187s  | 600.187s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__NO_13.jar-obl-8__p11419_edge_closing_0.smt2  |   2.468s  |   2.468s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__NO_13.jar-obl-8__p11440_edge_closing_0.smt2  | 600.137s  | 600.137s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__NO_13.jar-obl-8__p11459_terminationG_0.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__NO_24.jar-obl-8__p11510_terminationG_0.smt2  | 600.257s  | 600.257s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Power.jar-obl-10__p11798_terminationG_0.smt2  |  25.573s  |  25.573s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__RandomHard.jar-obl-10__p11831_safety_0.smt2  |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Samefringe.jar-obl-10__p11982_edge_closing_0.smt2  |   0.706s  |   0.706s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12121_terminationG_0.smt2  | 600.236s  | 600.236s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12128_terminationG_0.smt2  | 469.711s  | 469.711s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12142_terminationG_0.smt2  |  36.474s  |  36.474s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12155_terminationG_0.smt2  | 600.247s  | 600.247s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12183_terminationG_0.smt2  | 341.514s  | 341.514s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12184_terminationG_0.smt2  | 600.259s  | 600.259s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12223_terminationG_0.smt2  |  48.702s  |  48.702s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12232_terminationG_0.smt2  |  24.661s  |  24.661s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12239_terminationG_0.smt2  |  10.148s  |  10.148s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12256_terminationG_0.smt2  | 600.249s  | 600.249s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Swingers.jar-obl-8__p12435_terminationG_0.smt2  | 600.199s  | 600.199s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12477_terminationG_0.smt2  | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Test1.jar-obl-8__p12801_terminationG_0.smt2  | 600.416s  | 600.416s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Test6.jar-obl-13__terminationS_13_0.smt2  |  20.365s  |  20.365s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Test6.jar-obl-13__terminationS_24_0.smt2  |   6.592s  |   6.592s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13881_terminationG_0.smt2  | 600.166s  | 600.166s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13896_terminationG_0.smt2  | 600.376s  | 600.376s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13930_edge_closing_0.smt2  |   5.333s  |   5.333s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14126_edge_closing_0.smt2  |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14269_terminationG_0.smt2  |   1.194s  |   1.194s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14289_edge_closing_0.smt2  |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2  |  33.123s  |  33.123s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14386_terminationG_0.smt2  | 600.142s  | 600.142s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14482_terminationG_0.smt2  |  32.280s  |  32.280s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p4392_safety_0.smt2  |   0.604s  |   0.604s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2  |   1.202s  |   1.202s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p4624_safety_0.smt2  |   2.527s  |   2.527s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p4709_terminationG_0.smt2  |  11.690s  |  11.690s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p5104_safety_0.smt2  |   1.189s  |   1.189s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p5158_safety_0.smt2  |   1.433s  |   1.433s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2  |   0.808s  |   0.808s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29915_safety_0.smt2  |   1.715s  |   1.715s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30004_terminationG_0.smt2  |  41.418s  |  41.418s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30026_safety_0.smt2  |   0.990s  |   0.990s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30127_safety_0.smt2  |   1.074s  |   1.074s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30313_safety_0.smt2  |   2.981s  |   2.981s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30338_terminationG_0.smt2  |  21.009s  |  21.009s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30539_safety_0.smt2  |   1.473s  |   1.473s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30824_terminationG_0.smt2  | 103.563s  | 103.563s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31063_safety_0.smt2  |   0.851s  |   0.851s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2  |   2.175s  |   2.175s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31152_safety_0.smt2  |   1.120s  |   1.120s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31167_terminationG_0.smt2  |  22.493s  |  22.493s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2  |   0.632s  |   0.632s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31295_safety_0.smt2  |   0.784s  |   0.784s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31303_safety_0.smt2  |   2.582s  |   2.582s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31345_terminationG_0.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31805_safety_0.smt2  |   1.641s  |   1.641s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31859_terminationG_0.smt2  |   4.865s  |   4.865s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31928_safety_0.smt2  |   0.761s  |   0.761s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31947_safety_0.smt2  |   2.719s  |   2.719s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32020_terminationG_0.smt2  |   1.946s  |   1.946s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p322_safety_0.smt2  |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32401_safety_0.smt2  |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32720_terminationG_0.smt2  |   5.154s  |   5.154s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1606_safety_0.smt2  |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1659_safety_0.smt2  |   0.850s  |   0.850s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1691_safety_0.smt2  |   0.798s  |   0.798s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2113_safety_0.smt2  |   2.010s  |   2.010s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2225_safety_0.smt2  |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2436_safety_0.smt2  |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2746_safety_0.smt2  |   1.657s  |   1.657s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3008_safety_0.smt2  |   2.620s  |   2.620s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3178_safety_0.smt2  |   1.505s  |   1.505s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3188_terminationG_0.smt2  |  12.758s  |  12.758s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3358_terminationG_0.smt2  |  98.669s  |  98.669s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3363_edge_closing_0.smt2  | 600.307s  | 600.307s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3697_safety_0.smt2  |   1.370s  |   1.370s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5497_safety_0.smt2  |   0.627s  |   0.627s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6135_terminationG_0.smt2  |  47.662s  |  47.662s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6217_safety_0.smt2  |   1.206s  |   1.206s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6354_safety_0.smt2  |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6496_terminationG_0.smt2  |  95.127s  |  95.127s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6506_edge_closing_0.smt2  | 600.299s  | 600.299s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6932_safety_0.smt2  |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7017_terminationG_0.smt2  |   3.255s  |   3.255s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7192_safety_0.smt2  |   0.699s  |   0.699s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7210_terminationG_0.smt2  |  17.694s  |  17.694s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7211_terminationG_0.smt2  |  23.915s  |  23.915s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7322_safety_0.smt2  |   2.302s  |   2.302s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7607_terminationG_0.smt2  | 124.321s  | 124.321s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9479_terminationG_0.smt2  |  73.283s  |  73.283s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9558_terminationG_0.smt2  |   2.771s  |   2.771s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7969_safety_0.smt2  |   7.209s  |   7.209s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8073_terminationG_0.smt2  |   9.048s  |   9.048s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8337_safety_0.smt2  |   8.683s  |   8.683s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8348_safety_0.smt2  |  10.067s  |  10.067s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8402_safety_0.smt2  |   6.016s  |   6.016s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2  |   7.838s  |   7.838s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9027_safety_0.smt2  |   9.130s  |   9.130s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_11_0.smt2  |  24.789s  |  24.789s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_14_0.smt2  |  22.971s  |  22.971s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_15_0.smt2  |  22.519s  |  22.519s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_16_0.smt2  |  26.887s  |  26.887s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_19_0.smt2  |  29.475s  |  29.475s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_24_0.smt2  |  21.599s  |  21.599s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_28_0.smt2  |  18.407s  |  18.407s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_2_0.smt2  |  29.263s  |  29.263s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2  |  21.671s  |  21.671s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_31_0.smt2  |  21.114s  |  21.114s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_5_0.smt2  |  19.147s  |  19.147s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2  | 154.390s  | 154.390s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_10_0.smt2  |  55.319s  |  55.319s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_11_0.smt2  |  47.842s  |  47.842s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_12_0.smt2  |  45.957s  |  45.957s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_13_0.smt2  |  48.765s  |  48.765s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_14_0.smt2  |  46.370s  |  46.370s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_15_0.smt2  |  47.617s  |  47.617s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_16_0.smt2  |  56.440s  |  56.440s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_17_0.smt2  |  46.513s  |  46.513s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_18_0.smt2  |  43.047s  |  43.047s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2  |  43.513s  |  43.513s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_1_0.smt2  | 159.898s  | 159.898s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_20_0.smt2  |  44.265s  |  44.265s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_21_0.smt2  |  55.388s  |  55.388s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_22_0.smt2  |  57.274s  |  57.274s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_23_0.smt2  |  56.822s  |  56.822s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_24_0.smt2  |  60.879s  |  60.879s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_25_0.smt2  |  58.490s  |  58.490s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_26_0.smt2  |  60.081s  |  60.081s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_27_0.smt2  |  71.497s  |  71.497s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2  |  49.576s  |  49.576s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_29_0.smt2  |  58.323s  |  58.323s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_2_0.smt2  | 178.393s  | 178.393s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_3_0.smt2  | 153.652s  | 153.652s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_4_0.smt2  | 156.603s  | 156.603s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_5_0.smt2  | 332.835s  | 332.835s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_6_0.smt2  | 334.754s  | 334.754s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_7_0.smt2  | 326.903s  | 326.903s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_8_0.smt2  | 245.128s  | 245.128s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_9_0.smt2  | 183.046s  | 183.046s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__narrowKonv_rec.jar-obl-8__p11136_edge_closing_0.smt2  |   6.825s  |   6.825s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__narrowing_rec.jar-obl-8__p11066_terminationG_0.smt2  |  28.985s  |  28.985s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__narrowing_rec.jar-obl-8__p11067_terminationG_0.smt2  | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__upAndDown_rec.jar-obl-8__p13161_edge_closing_0.smt2  |   7.724s  |   7.724s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14933_safety_0.smt2  |  36.282s  |  36.282s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__whileSingle_rec.jar-obl-8__p15018_terminationG_0.smt2  | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__Prim_4.t2__p7936_terminationG_0.smt2   |   1.678s  |   1.678s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__Prim_4.t2__p7976_terminationG_0.smt2   |   1.490s  |   1.490s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__Prim_4.t2__p8016_terminationG_0.smt2   |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__Prim_4.t2__p8035_terminationG_0.smt2   |   2.091s  |   2.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__afagp-fail.t2__p15516_edge_closing_0.smt2  | 307.415s  | 307.415s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__agafp.t2__p15626_terminationG_0.smt2   |  11.722s  |  11.722s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__agafp.t2__p15636_terminationG_0.smt2   |  35.106s  |  35.106s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__agafp.t2__terminationS_0_0.smt2        |  42.813s  |  42.813s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2__p15941_terminationG_0.smt2  | 600.399s  | 600.399s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2__p16000_terminationG_0.smt2  | 320.233s  | 320.233s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2__p16028_terminationG_0.smt2  | 600.371s  | 600.371s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2_fixed__p15799_terminationG_0.smt2  | 600.463s  | 600.463s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2_fixed__p15830_terminationG_0.smt2  | 164.182s  | 164.182s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2_fixed__p15846_terminationG_0.smt2  | 520.118s  | 520.118s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted.t2__p16269_terminationG_0.smt2  | 458.786s  | 458.786s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2  | 600.395s  | 600.395s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted.t2__p16298_terminationG_0.smt2  | 600.484s  | 600.484s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted.t2_fixed__p16101_terminationG_0.smt2  | 376.911s  | 376.911s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted.t2_fixed__p16110_terminationG_0.smt2  |  38.916s  |  38.916s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-live.t2__p16639_terminationG_0.smt2  | 110.223s  | 110.223s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-live.t2_fixed__p16559_terminationG_0.smt2  |   3.588s  |   3.588s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-live.t2_fixed__p16560_terminationG_0.smt2  | 386.790s  | 386.790s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-live.t2_fixed__p16564_terminationG_0.smt2  |   4.192s  |   4.192s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2  | 124.375s  | 124.375s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchildlive-succeed.t2__p16426_terminationG_0.smt2  | 600.460s  | 600.460s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__brp_withassume.t2__p17437_edge_closing_0.smt2  | 600.356s  | 600.356s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__bs.t2_fixed__p17456_terminationG_0.smt2  |  75.759s  |  75.759s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__db2.t2__term_unfeasibility_0_0.smt2    |  26.613s  |  26.613s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__db2.t2__terminationQ_0_0.smt2          | 125.857s  | 125.857s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__db3.t2__term_unfeasibility_0_0.smt2    |  24.261s  |  24.261s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__db3.t2__terminationQ_0_0.smt2          |  91.742s  |  91.742s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__destroy_seg_leak.t2_fixed__p18858_edge_closing_0.smt2  | 600.274s  | 600.274s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__dumper.t2__p19134_terminationG_0.smt2  | 600.232s  | 600.232s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__edn.t2__p20326_safety_0.smt2           |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__edn.t2__p20632_safety_0.smt2           |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__edn.t2__p20710_safety_0.smt2           |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__efegp.t2__p21961_edge_closing_0.smt2   | 102.555s  | 102.555s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ex11.t2__p22126_terminationG_0.smt2    |  26.293s  |  26.293s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ex36.t2__p30283_safety_0.smt2          |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ex36.t2__p31845_safety_0.smt2          |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ex36.t2__p31955_safety_0.smt2          |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ex36.t2_fixed__p23592_safety_0.smt2    |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__firewire.t2__p32301_edge_closing_0.smt2  | 359.382s  | 359.382s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__firewire.t2__terminationS_19_0.smt2    |   9.731s  |   9.731s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__florian_sas2.t2__p32380_terminationG_0.smt2  | 600.216s  | 600.216s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__florian_sas2.t2__p32384_terminationG_0.smt2  | 481.809s  | 481.809s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__florian_sas2.t2__p32399_terminationG_0.smt2  | 431.475s  | 431.475s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_13_0.smt2         | 600.684s  | 600.684s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_14_0.smt2         | 600.768s  | 600.768s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_15_0.smt2         | 600.779s  | 600.779s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_16_0.smt2         | 551.093s  | 551.093s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_17_0.smt2         | 600.604s  | 600.604s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_18_0.smt2         | 600.671s  | 600.671s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_19_0.smt2         | 600.798s  | 600.798s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_20_0.smt2         | 523.819s  | 523.819s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_22_0.smt2         | 600.662s  | 600.662s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_24_0.smt2         | 600.771s  | 600.771s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_26_0.smt2         | 600.773s  | 600.773s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_28_0.smt2         | 600.727s  | 600.727s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_2_0.smt2          | 578.942s  | 578.942s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_31_0.smt2         | 600.697s  | 600.697s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_32_0.smt2         | 600.669s  | 600.669s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_3_0.smt2          | 600.653s  | 600.653s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_4_0.smt2          | 479.811s  | 479.811s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_6_0.smt2          | 600.722s  | 600.722s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_7_0.smt2          | 600.664s  | 600.664s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_8_0.smt2          | 600.653s  | 600.653s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32602_terminationG_0.smt2  | 600.203s  | 600.203s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32699_edge_closing_0.smt2  | 600.195s  | 600.195s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fourn.t2__p32708_terminationG_0.smt2   | 600.269s  | 600.269s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fourn.t2__p32713_terminationG_0.smt2   | 600.225s  | 600.225s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1.t2__terminationQ_0_0.smt2         |  27.352s  |  27.352s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1.t2_fixed__p705_terminationG_0.smt2  | 104.717s  | 104.717s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1.t2_fixed__p721_terminationG_0.smt2  |  32.099s  |  32.099s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1.t2_fixed__p784_terminationG_0.smt2  |  41.693s  |  41.693s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2__p597_terminationG_0.smt2     |  36.049s  |  36.049s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2__p626_terminationG_0.smt2     | 277.081s  | 277.081s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2__p679_terminationG_0.smt2     |  11.420s  |  11.420s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2__p680_terminationG_0.smt2     |  22.796s  |  22.796s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2__terminationQ_0_0.smt2        |  32.269s  |  32.269s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2  |   8.489s  |   8.489s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2_fixed__p551_terminationG_0.smt2  |  64.637s  |  64.637s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2  |  47.680s  |  47.680s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun6.t2__p1092_terminationG_0.smt2     |  28.858s  |  28.858s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun6.t2_fixed__p1055_terminationG_0.smt2  |  68.160s  |  68.160s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun6.t2_fixed__p1066_edge_closing_0.smt2  | 600.254s  | 600.254s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun7.t2__p1142_terminationG_0.smt2     |  25.463s  |  25.463s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun7.t2__p1167_edge_closing_0.smt2     | 600.233s  | 600.233s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1287_edge_closing_0.smt2     |   1.763s  |   1.763s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1309_edge_closing_0.smt2     |  16.958s  |  16.958s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1314_edge_closing_0.smt2     |   4.047s  |   4.047s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1320_edge_closing_0.smt2     |   4.556s  |   4.556s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1354_edge_closing_0.smt2     |   5.759s  |   5.759s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1357_edge_closing_0.smt2     | 326.419s  | 326.419s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1377_edge_closing_0.smt2     |   1.212s  |   1.212s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1378_edge_closing_0.smt2     |   4.820s  |   4.820s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1393_edge_closing_0.smt2     |  14.453s  |  14.453s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1398_edge_closing_0.smt2     |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1406_edge_closing_0.smt2     |  10.193s  |  10.193s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1409_edge_closing_0.smt2     |  19.126s  |  19.126s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1413_edge_closing_0.smt2     |   6.323s  |   6.323s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1437_edge_closing_0.smt2     |   7.265s  |   7.265s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1440_edge_closing_0.smt2     |   4.402s  |   4.402s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1460_edge_closing_0.smt2     |   3.631s  |   3.631s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1467_edge_closing_0.smt2     |  85.597s  |  85.597s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1485_edge_closing_0.smt2     |   2.465s  |   2.465s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2  | 600.239s  | 600.239s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_19_0.smt2  |  19.127s  |  19.127s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_21_0.smt2  |  20.810s  |  20.810s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2  |  16.915s  |  16.915s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_26_0.smt2  |  18.379s  |  18.379s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_49_0.smt2  |  26.191s  |  26.191s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_50_0.smt2  |  54.512s  |  54.512s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1608_terminationG_0.smt2  | 600.342s  | 600.342s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_25_0.smt2  |   9.219s  |   9.219s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_26_0.smt2  |  11.071s  |  11.071s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_27_0.smt2  |   9.584s  |   9.584s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_55_0.smt2  |   9.119s  |   9.119s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_25_0.smt2  |  14.816s  |  14.816s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2  |  14.855s  |  14.855s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_49_0.smt2  |  20.646s  |  20.646s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_51_0.smt2  |  55.522s  |  55.522s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_26_0.smt2  |  10.420s  |  10.420s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2  |  10.360s  |  10.360s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_57_0.smt2  |  16.918s  |  16.918s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_62_0.smt2  |   9.116s  |   9.116s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2__p1768_terminationG_0.smt2      | 316.373s  | 316.373s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2__terminationS_25_0.smt2         |  14.899s  |  14.899s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2_fixed__terminationS_24_0.smt2   |   7.341s  |   7.341s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2_fixed__terminationS_53_0.smt2   |  29.706s  |  29.706s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2_fixed__terminationS_54_0.smt2   |   9.129s  |   9.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2_fixed__terminationS_55_0.smt2   |   8.017s  |   8.017s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__janne_complex.t2__p2020_terminationG_0.smt2  |   5.755s  |   5.755s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__janne_complex.t2__p2041_terminationG_0.smt2  |  63.768s  |  63.768s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__janne_complex.t2__p2193_terminationG_0.smt2  |  11.072s  |  11.072s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__janne_complex.t2__p2254_terminationG_0.smt2  |   5.664s  |   5.664s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__janne_complex.t2__p2263_terminationG_0.smt2  |  18.146s  |  18.146s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__matmul.t2_fixed__p2649_terminationG_0.smt2  |   5.667s  |   5.667s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91.t2__p2940_edge_closing_0.smt2     |   0.627s  |   0.627s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3164_terminationG_0.smt2  | 409.313s  | 409.313s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3169_terminationG_0.smt2  |  83.780s  |  83.780s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3221_terminationG_0.smt2  | 171.234s  | 171.234s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3249_terminationG_0.smt2  | 236.822s  | 236.822s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3256_terminationG_0.smt2  |  47.344s  |  47.344s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3301_terminationG_0.smt2  | 210.146s  | 210.146s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3311_terminationG_0.smt2  | 122.018s  | 122.018s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3358_terminationG_0.smt2  |  20.639s  |  20.639s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n-5.t2__p4677_terminationG_0.smt2      | 600.431s  | 600.431s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n-5.t2__p4682_terminationG_0.smt2      | 290.094s  | 290.094s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n-5.t2__p4703_edge_closing_0.smt2      |   6.678s  |   6.678s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n-5.t2_fixed__p4589_terminationG_0.smt2  |   0.642s  |   0.642s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6188_terminationG_0.smt2  | 600.218s  | 600.218s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6193_terminationG_0.smt2  | 600.213s  | 600.213s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6198_terminationG_0.smt2  | 600.238s  | 600.238s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6202_terminationG_0.smt2  | 600.170s  | 600.170s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6218_terminationG_0.smt2  | 600.245s  | 600.245s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6219_terminationG_0.smt2  | 600.244s  | 600.244s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6225_edge_closing_0.smt2  |   6.815s  |   6.815s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__nakata.t2__p5305_terminationG_0.smt2   |   1.885s  |   1.885s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__nakata.t2__p5310_terminationG_0.smt2   | 600.201s  | 600.201s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__nakata.t2__p5352_edge_closing_0.smt2   | 600.252s  | 600.252s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__nakata.t2__terminationS_6_0.smt2       |  10.395s  |  10.395s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__opt-tree.c.t2__p6339_terminationG_0.smt2  |   1.349s  |   1.349s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__opt-tree.c.t2__p6340_terminationG_0.smt2  |  57.255s  |  57.255s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__p-5.t2_fixed__p6782_edge_closing_0.smt2  |   4.115s  |   4.115s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__pgarch.t2__p7283_terminationG_0.smt2   |   1.763s  |   1.763s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__polyrank4.t2__p7477_terminationG_0.smt2  |   1.628s  |   1.628s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__polyrank4.t2__p7482_terminationG_0.smt2  |   1.549s  |   1.549s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__polyrank4.t2__p7520_terminationG_0.smt2  |  14.289s  |  14.289s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__polyrank5.t2__p7556_terminationG_0.smt2  |   7.475s  |   7.475s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ppblock.t2__p7746_edge_closing_0.smt2  |   1.179s  |   1.179s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ppblockterm.t2__p7916_edge_closing_0.smt2  |   2.827s  |   2.827s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__randomwalk.t2__p8416_terminationG_0.smt2  |  16.001s  |  16.001s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1-striped.t2__p12897_safety_0.smt2    |   1.434s  |   1.434s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1-striped.t2__p12943_safety_0.smt2    |   2.767s  |   2.767s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1-striped.t2_fixed__p9299_terminationG_0.smt2  | 193.022s  | 193.022s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1-striped.t2_fixed__p9992_safety_0.smt2  |   1.778s  |   1.778s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p17922_terminationG_0.smt2      |  29.522s  |  29.522s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p17931_terminationG_0.smt2      |  11.682s  |  11.682s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p18338_safety_0.smt2            |   1.802s  |   1.802s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p18948_safety_0.smt2            |   2.374s  |   2.374s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p19377_safety_0.smt2            |   4.762s  |   4.762s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p19834_safety_0.smt2            |   1.648s  |   1.648s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p19848_safety_0.smt2            |   1.296s  |   1.296s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2_fixed__p15165_terminationG_0.smt2  | 240.278s  | 240.278s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2_fixed__p15180_terminationG_0.smt2  |  48.351s  |  48.351s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sas2.t2__p21297_terminationG_0.smt2    | 600.165s  | 600.165s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sas2.t2__p21302_terminationG_0.smt2    | 359.701s  | 359.701s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sas2.t2__p21311_terminationG_0.smt2    |  39.434s  |  39.434s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sas2.t2__terminationS_1_0.smt2         |  13.985s  |  13.985s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__select.t2__p21400_edge_closing_0.smt2  | 600.184s  | 600.184s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3-new.t2__p22118_edge_closing_0.smt2  |  29.720s  |  29.720s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3-new.t2_fixed__p21803_terminationG_0.smt2  | 600.700s  | 600.700s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3.t2_fixed__p22135_terminationG_0.smt2  | 600.667s  | 600.667s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22479_terminationG_0.smt2  |  24.585s  |  24.585s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22519_safety_0.smt2  |  20.450s  |  20.450s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22531_terminationG_0.smt2  | 147.073s  | 147.073s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22603_safety_0.smt2  |   3.456s  |   3.456s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22607_safety_0.smt2  |   1.781s  |   1.781s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22639_terminationG_0.smt2  |  25.786s  |  25.786s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22640_terminationG_0.smt2  | 354.684s  | 354.684s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22688_terminationG_0.smt2  | 600.295s  | 600.295s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-5-filtered.t2__p22882_terminationG_0.smt2  |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2  |   1.418s  |   1.418s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__small15.t2__p23742_terminationG_0.smt2  |   1.495s  |   1.495s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__small15.t2__p23781_edge_closing_0.smt2  |   1.663s  |   1.663s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__st88.t2__p24217_terminationG_0.smt2    |   4.154s  |   4.154s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2__p24620_terminationG_0.smt2  |  51.273s  |  51.273s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2__p24634_terminationG_0.smt2  | 576.193s  | 576.193s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2__p24649_terminationG_0.smt2  | 600.287s  | 600.287s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2__p24820_edge_closing_0.smt2  |   9.653s  |   9.653s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2__p24821_edge_closing_0.smt2  |  29.133s  |  29.133s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2_fixed__p24590_edge_closing_0.smt2  |  41.572s  |  41.572s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2_fixed__p24591_edge_closing_0.smt2  | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver.bug.t2__p24573_terminationG_0.smt2  | 491.160s  | 491.160s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sudoku.t2__p24862_terminationG_0.smt2  | 575.535s  | 575.535s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sudoku.t2__p24867_terminationG_0.smt2  | 101.253s  | 101.253s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2  |  19.234s  |  19.234s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_28_0.smt2  |  29.601s  |  29.601s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2  |  17.592s  |  17.592s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__svdcmp.t2__term_unfeasibility_8_0.smt2  |   8.414s  |   8.414s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25001_terminationG_0.smt2  | 600.321s  | 600.321s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25046_edge_closing_0.smt2  | 600.196s  | 600.196s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2  | 600.239s  | 600.239s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__tqli.t2__p25217_terminationG_0.smt2    | 600.473s  | 600.473s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__tqli.t2_fixed__p25201_edge_closing_0.smt2  | 600.192s  | 600.192s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2  |   7.915s  |   7.915s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/SAT14/1813.smt2                                     |   0.577s  |   0.577s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/SAT14/585.smt2                                      |   2.443s  |   2.443s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/MC_03.smt2                                     | 600.127s  | 600.127s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/MC_09.smt2                                     | 600.365s  | 600.365s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/MC_11.smt2                                     | 600.488s  | 600.488s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/MF_03.smt2                                     | 600.197s  | 600.197s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/MS_04.smt2                                     | 600.196s  | 600.196s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/RTA_093.smt2                                   | 601.085s  | 601.085s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/SC_08.smt2                                     | 600.214s  | 600.214s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0013.smt2                                  | 600.130s  | 600.130s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0014.smt2                                  | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0022.smt2                                  | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0023.smt2                                  | 600.141s  | 600.141s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0031.smt2                                  | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0032.smt2                                  | 600.183s  | 600.183s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0040.smt2                                  | 600.126s  | 600.126s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0041.smt2                                  | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0049.smt2                                  | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0050.smt2                                  | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0052.smt2                                  | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0058.smt2                                  | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0066.smt2                                  | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0067.smt2                                  | 600.151s  | 600.151s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0068.smt2                                  | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0070.smt2                                  | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0076.smt2                                  | 600.191s  | 600.191s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0077.smt2                                  | 600.181s  | 600.181s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0085.smt2                                  | 600.174s  | 600.174s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0097.smt2                                  |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0099.smt2                                  |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0100.smt2                                  | 600.161s  | 600.161s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0103.smt2                                  | 600.226s  | 600.226s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0104.smt2                                  | 600.186s  | 600.186s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0110.smt2                                  | 600.176s  | 600.176s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0112.smt2                                  | 600.159s  | 600.159s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0113.smt2                                  | 600.172s  | 600.172s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0121.smt2                                  | 600.189s  | 600.189s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0122.smt2                                  | 600.177s  | 600.177s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0130.smt2                                  | 600.191s  | 600.191s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0131.smt2                                  | 600.133s  | 600.133s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0136.smt2                                  | 600.193s  | 600.193s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0138.smt2                                  | 600.149s  | 600.149s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0139.smt2                                  | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0140.smt2                                  | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0148.smt2                                  | 600.131s  | 600.131s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0149.smt2                                  | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0153.smt2                                  |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0157.smt2                                  | 600.292s  | 600.292s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0158.smt2                                  | 600.314s  | 600.314s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0163.smt2                                  | 600.213s  | 600.213s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0175.smt2                                  | 600.231s  | 600.231s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0176.smt2                                  | 600.236s  | 600.236s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0184.smt2                                  | 600.263s  | 600.263s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0190.smt2                                  |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0193.smt2                                  | 600.201s  | 600.201s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0194.smt2                                  | 600.206s  | 600.206s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0202.smt2                                  | 600.175s  | 600.175s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0203.smt2                                  | 600.254s  | 600.254s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0211.smt2                                  | 600.243s  | 600.243s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0212.smt2                                  | 600.223s  | 600.223s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0220.smt2                                  | 600.069s  | 600.069s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0221.smt2                                  | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0226.smt2                                  | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0229.smt2                                  | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0230.smt2                                  | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0236.smt2                                  | 600.133s  | 600.133s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0238.smt2                                  | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0239.smt2                                  | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0244.smt2                                  |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0247.smt2                                  | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0248.smt2                                  | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0257.smt2                                  | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0265.smt2                                  | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0266.smt2                                  | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0268.smt2                                  | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0274.smt2                                  | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0275.smt2                                  | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0283.smt2                                  | 600.186s  | 600.186s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0284.smt2                                  | 600.164s  | 600.164s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0286.smt2                                  | 600.137s  | 600.137s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0292.smt2                                  | 600.147s  | 600.147s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0293.smt2                                  | 600.156s  | 600.156s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0300.smt2                                  | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0301.smt2                                  | 600.150s  | 600.150s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0302.smt2                                  | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0310.smt2                                  | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0311.smt2                                  | 600.160s  | 600.160s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0315.smt2                                  |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0319.smt2                                  | 600.164s  | 600.164s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0320.smt2                                  | 600.152s  | 600.152s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0325.smt2                                  | 600.177s  | 600.177s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0328.smt2                                  | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0329.smt2                                  | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0330.smt2                                  |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0334.smt2                                  |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0337.smt2                                  | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0338.smt2                                  | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0346.smt2                                  | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0347.smt2                                  | 600.133s  | 600.133s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0350.smt2                                  | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0355.smt2                                  | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0356.smt2                                  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0364.smt2                                  | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0365.smt2                                  | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0366.smt2                                  | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0367.smt2                                  | 600.127s  | 600.127s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0368.smt2                                  | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0369.smt2                                  |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0373.smt2                                  | 600.171s  | 600.171s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0374.smt2                                  | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0382.smt2                                  | 600.171s  | 600.171s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0383.smt2                                  | 600.148s  | 600.148s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0389.smt2                                  | 600.218s  | 600.218s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0391.smt2                                  | 600.148s  | 600.148s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0392.smt2                                  | 600.169s  | 600.169s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0394.smt2                                  | 600.153s  | 600.153s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0400.smt2                                  | 600.150s  | 600.150s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0401.smt2                                  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0402.smt2                                  | 600.249s  | 600.249s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0409.smt2                                  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0410.smt2                                  | 600.175s  | 600.175s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0411.smt2                                  | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0418.smt2                                  | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0419.smt2                                  | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0424.smt2                                  | 600.226s  | 600.226s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0426.smt2                                  | 600.149s  | 600.149s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0427.smt2                                  | 600.133s  | 600.133s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0428.smt2                                  | 600.152s  | 600.152s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0436.smt2                                  | 600.157s  | 600.157s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0437.smt2                                  | 600.211s  | 600.211s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0441.smt2                                  | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0445.smt2                                  | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0446.smt2                                  | 600.191s  | 600.191s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0451.smt2                                  | 600.190s  | 600.190s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0454.smt2                                  | 600.161s  | 600.161s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0455.smt2                                  | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0463.smt2                                  | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0464.smt2                                  | 600.169s  | 600.169s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0472.smt2                                  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0473.smt2                                  | 600.150s  | 600.150s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0481.smt2                                  | 600.154s  | 600.154s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0482.smt2                                  | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0483.smt2                                  | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0484.smt2                                  |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0486.smt2                                  |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0490.smt2                                  | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0493.smt2                                  |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0496.smt2                                  |  32.669s  |  32.669s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0498.smt2                                  | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0499.smt2                                  | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0500.smt2                                  | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0502.smt2                                  | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0508.smt2                                  | 600.045s  | 600.045s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0509.smt2                                  | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0517.smt2                                  | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0518.smt2                                  | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0527.smt2                                  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0529.smt2                                  | 600.197s  | 600.197s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0530.smt2                                  | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0535.smt2                                  | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0536.smt2                                  | 600.180s  | 600.180s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0537.smt2                                  | 600.170s  | 600.170s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0540.smt2                                  |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0544.smt2                                  | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0545.smt2                                  | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0551.smt2                                  | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0553.smt2                                  | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0554.smt2                                  | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0562.smt2                                  | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0563.smt2                                  | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0569.smt2                                  | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0571.smt2                                  | 600.156s  | 600.156s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0572.smt2                                  | 600.117s  | 600.117s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0578.smt2                                  | 600.257s  | 600.257s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0580.smt2                                  | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0581.smt2                                  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0582.smt2                                  | 600.161s  | 600.161s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0589.smt2                                  | 600.200s  | 600.200s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0590.smt2                                  | 600.170s  | 600.170s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0592.smt2                                  | 600.164s  | 600.164s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0597.smt2                                  | 600.160s  | 600.160s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0598.smt2                                  | 600.162s  | 600.162s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0599.smt2                                  | 600.157s  | 600.157s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0603.smt2                                  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0607.smt2                                  | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0608.smt2                                  | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0611.smt2                                  | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0616.smt2                                  | 600.157s  | 600.157s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0617.smt2                                  | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0625.smt2                                  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0626.smt2                                  | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0635.smt2                                  | 600.157s  | 600.157s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0642.smt2                                  | 600.153s  | 600.153s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0643.smt2                                  | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0644.smt2                                  | 600.154s  | 600.154s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0653.smt2                                  | 600.205s  | 600.205s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0656.smt2                                  |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0661.smt2                                  | 600.228s  | 600.228s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0662.smt2                                  | 600.209s  | 600.209s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0670.smt2                                  | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0671.smt2                                  | 600.137s  | 600.137s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0678.smt2                                  |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0679.smt2                                  | 600.153s  | 600.153s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0680.smt2                                  | 600.165s  | 600.165s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0684.smt2                                  |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0688.smt2                                  | 600.181s  | 600.181s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0689.smt2                                  | 600.140s  | 600.140s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0697.smt2                                  | 600.174s  | 600.174s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0698.smt2                                  | 600.185s  | 600.185s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0703.smt2                                  |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0706.smt2                                  | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0707.smt2                                  | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0715.smt2                                  | 600.184s  | 600.184s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0716.smt2                                  | 600.156s  | 600.156s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0717.smt2                                  | 600.159s  | 600.159s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0719.smt2                                  | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0722.smt2                                  |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0723.smt2                                  | 600.165s  | 600.165s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0724.smt2                                  | 600.213s  | 600.213s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0725.smt2                                  | 600.193s  | 600.193s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0733.smt2                                  | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0734.smt2                                  | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0740.smt2                                  | 600.153s  | 600.153s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0742.smt2                                  | 600.166s  | 600.166s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0743.smt2                                  | 600.249s  | 600.249s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0745.smt2                                  | 600.171s  | 600.171s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0751.smt2                                  | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0752.smt2                                  | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0760.smt2                                  | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0761.smt2                                  | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0768.smt2                                  | 600.093s  | 600.093s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0769.smt2                                  | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0770.smt2                                  | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0776.smt2                                  | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0778.smt2                                  | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0779.smt2                                  | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0787.smt2                                  | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0788.smt2                                  | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0796.smt2                                  | 600.173s  | 600.173s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0797.smt2                                  | 600.149s  | 600.149s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0805.smt2                                  | 600.126s  | 600.126s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0806.smt2                                  | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0814.smt2                                  | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0815.smt2                                  | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0816.smt2                                  |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0823.smt2                                  | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0824.smt2                                  | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0825.smt2                                  |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0832.smt2                                  | 600.158s  | 600.158s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0833.smt2                                  | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0834.smt2                                  | 600.153s  | 600.153s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0841.smt2                                  | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0842.smt2                                  | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0850.smt2                                  | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0851.smt2                                  | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0859.smt2                                  | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0860.smt2                                  | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0868.smt2                                  | 600.079s  | 600.079s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0869.smt2                                  | 600.124s  | 600.124s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0877.smt2                                  | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0878.smt2                                  | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0883.smt2                                  |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0884.smt2                                  | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0886.smt2                                  | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0887.smt2                                  | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0895.smt2                                  | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0896.smt2                                  | 600.158s  | 600.158s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0898.smt2                                  | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0901.smt2                                  | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0904.smt2                                  | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0906.smt2                                  | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0913.smt2                                  | 600.128s  | 600.128s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0914.smt2                                  | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0920.smt2                                  |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0922.smt2                                  | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0923.smt2                                  | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0931.smt2                                  | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0932.smt2                                  | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0940.smt2                                  | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0941.smt2                                  | 600.151s  | 600.151s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0944.smt2                                  |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0949.smt2                                  | 600.155s  | 600.155s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0950.smt2                                  | 600.131s  | 600.131s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0958.smt2                                  | 600.148s  | 600.148s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0959.smt2                                  | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0963.smt2                                  |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0967.smt2                                  | 600.162s  | 600.162s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0968.smt2                                  | 600.191s  | 600.191s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0976.smt2                                  | 600.149s  | 600.149s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0977.smt2                                  | 600.203s  | 600.203s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0983.smt2                                  | 600.196s  | 600.196s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0985.smt2                                  | 600.141s  | 600.141s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0986.smt2                                  | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0994.smt2                                  | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0995.smt2                                  | 600.137s  | 600.137s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/TA_03.smt2                                     | 600.131s  | 600.131s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/TA_05.smt2                                     | 600.211s  | 600.211s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/TA_13.smt2                                     | 600.189s  | 600.189s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInv128.smt2                          | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInv16.smt2                           | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInv32.smt2                           | 600.126s  | 600.126s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInv64.smt2                           | 600.117s  | 600.117s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInv8.smt2                            | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInvFull.smt2                         | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInvInitial.smt2                      | 600.066s  | 600.066s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInvStep.smt2                         | 600.152s  | 600.152s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInvStepSimplified.smt2               | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInvVar1.smt2                         | 600.186s  | 600.186s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/sqrtStepFinal.smt2                      | 600.184s  | 600.184s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/sqrtStepFinala.smt2                     | 600.174s  | 600.174s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT1335852993657230070.smt2                             |   0.655s  |   0.655s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT1437438160177275586.smt2                             |   3.161s  |   3.161s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT1700028870436976635.smt2                             |   3.505s  |   3.505s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT180444191153863419.smt2                              |   5.825s  |   5.825s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT1813676864021281701.smt2                             |  10.675s  |  10.675s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT2214668917450755150.smt2                             |   8.641s  |   8.641s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT2276070888632403184.smt2                             |  11.694s  |  11.694s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT3457830339872275636.smt2                             |   0.898s  |   0.898s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT3678576972294594665.smt2                             |  59.765s  |  59.765s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT3712394338782947208.smt2                             |  14.497s  |  14.497s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT3839584170547805483.smt2                             |  41.421s  |  41.421s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT4259464554444412647.smt2                             |   1.259s  |   1.259s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT463192377960637155.smt2                              |   5.205s  |   5.205s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT5210162955256537540.smt2                             |  17.738s  |  17.738s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT5468773551032053543.smt2                             |   6.248s  |   6.248s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT5521985939949569030.smt2                             |   3.002s  |   3.002s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT5642158517481563632.smt2                             |   4.554s  |   4.554s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT5753280746557461985.smt2                             |   0.852s  |   0.852s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT6531155344723557531.smt2                             |   9.513s  |   9.513s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT6545992645874542347.smt2                             | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT6647586385534524663.smt2                             |   7.105s  |   7.105s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT6828719750442006249.smt2                             |  29.207s  |  29.207s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT6981420136966712689.smt2                             |  14.499s  |  14.499s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT7201733644041072759.smt2                             |   5.352s  |   5.352s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT725924178667047452.smt2                              |   5.876s  |   5.876s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT7924349461296395393.smt2                             | 385.863s  | 385.863s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT8619300169146917506.smt2                             |   4.784s  |   4.784s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT9062228803117299674.smt2                             |   6.139s  |   6.139s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT9064001295904670492.smt2                             |   1.711s  |   1.711s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/LCTES/digital-stopwatch.locals.nosummaries.smt2                      | 600.178s  | 600.178s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/LCTES/digital-stopwatch.locals.smt2                                  |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/LassoRanker/ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.785s  |   0.785s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-3wwoHp.smt2                                             | 111.369s  | 111.369s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-607QpU.smt2                                             |  13.846s  |  13.846s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-6k3pKM.smt2                                             |   0.959s  |   0.959s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-7fXGzy.smt2                                             |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-K5O3aH.smt2                                             | 600.247s  | 600.247s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-MVylXc.smt2                                             | 600.430s  | 600.430s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-l6cqQI.smt2                                             | 600.300s  | 600.300s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-p9MQp4.smt2                                             |   3.155s  |   3.155s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-unsat-02.smt2                                           | 600.201s  | 600.201s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-unsat-03.smt2                                           | 600.279s  | 600.279s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-unsat-04.smt2                                           | 600.279s  | 600.279s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-unsat-05.smt2                                           | 600.192s  | 600.192s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/mcm/26.smt2                                                          | 600.118s  | 600.118s  |   0.000s  | 0.0%|
</details>
