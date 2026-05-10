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
Job tag: Z3-threads-8-QF_NIA_hard-timeout10min-bb1
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: f880fdccee614547c38c19beb7af5a027961646b
Z3 branch: core_min
Z3 options: "-T:600 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=1"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_NIA.tar.zst?download=1
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-QF_NIA_hard-timeout10min-bb1
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: f880fdccee614547c38c19beb7af5a027961646b
Z3 branch: core_min
Z3 options: "-T:600 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=1"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_NIA.tar.zst?download=1
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  | 600.230s  | 600.230s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  | 133.587s  | 133.587s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  | 600.152s  | 600.152s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   7.406s  |   7.406s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |   6.199s  |   6.199s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  49.507s  |  49.507s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  | 127.491s  | 127.491s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |  60.384s  |  60.384s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  11.907s  |  11.907s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  | 205.524s  | 205.524s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |  53.108s  |  53.108s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  47.057s  |  47.057s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.879s  |   0.879s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |  12.712s  |  12.712s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |   1.697s  |   1.697s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |  46.801s  |  46.801s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   4.737s  |   4.737s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  | 600.230s  | 600.230s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  | 133.587s  | 133.587s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  | 600.152s  | 600.152s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   7.406s  |   7.406s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |   6.199s  |   6.199s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  49.507s  |  49.507s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  | 127.491s  | 127.491s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |  60.384s  |  60.384s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  11.907s  |  11.907s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  | 205.524s  | 205.524s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |  53.108s  |  53.108s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  47.057s  |  47.057s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.879s  |   0.879s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |  12.712s  |  12.712s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |   1.697s  |   1.697s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |  46.801s  |  46.801s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   4.737s  |   4.737s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  | 600.230s  | 600.230s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  | 133.587s  | 133.587s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  | 600.152s  | 600.152s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   7.406s  |   7.406s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |   6.199s  |   6.199s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  49.507s  |  49.507s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  | 127.491s  | 127.491s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |  60.384s  |  60.384s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  11.907s  |  11.907s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  | 205.524s  | 205.524s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |  53.108s  |  53.108s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  47.057s  |  47.057s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.879s  |   0.879s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |  12.712s  |  12.712s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |   1.697s  |   1.697s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |  46.801s  |  46.801s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   4.737s  |   4.737s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  | 600.230s  | 600.230s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  | 133.587s  | 133.587s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  | 600.152s  | 600.152s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   7.406s  |   7.406s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |   6.199s  |   6.199s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  49.507s  |  49.507s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  | 127.491s  | 127.491s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |  60.384s  |  60.384s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  11.907s  |  11.907s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  | 205.524s  | 205.524s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |  53.108s  |  53.108s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  47.057s  |  47.057s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.879s  |   0.879s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |  12.712s  |  12.712s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |   1.697s  |   1.697s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |  46.801s  |  46.801s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   4.737s  |   4.737s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_NIA/20220315-MathProblems/RTA_093.smt2                                  | 600.825s |7602.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_14_0.smt2        | 600.693s |6473.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_19_0.smt2        | 600.689s |6465.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_3_0.smt2         | 600.671s |6096.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_22_0.smt2        | 600.649s |6320.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_24_0.smt2        | 600.649s |6374.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_6_0.smt2         | 600.645s |5872.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_26_0.smt2        | 600.643s |6348.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_18_0.smt2        | 600.632s |6423.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_28_0.smt2        | 600.630s |6291.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3.t2_fixed__p22135_terminationG_0.smt2 | 600.623s |5881.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_31_0.smt2        | 600.621s |6064.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_32_0.smt2        | 600.617s |6198.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_17_0.smt2        | 600.603s |6107.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_15_0.smt2        | 600.594s |6345.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_13_0.smt2        | 600.592s |6142.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3-new.t2_fixed__p21803_terminationG_0.smt2 | 600.573s |5262.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_4_0.smt2         | 600.572s |5913.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_2_0.smt2         | 600.563s |5991.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_7_0.smt2         | 600.544s |5982.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_NIA/20220315-MathProblems/RTA_093.smt2                                  | 600.825s |7602.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_14_0.smt2        | 600.693s |6473.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_19_0.smt2        | 600.689s |6465.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_3_0.smt2         | 600.671s |6096.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_22_0.smt2        | 600.649s |6320.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_24_0.smt2        | 600.649s |6374.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_6_0.smt2         | 600.645s |5872.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_26_0.smt2        | 600.643s |6348.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_18_0.smt2        | 600.632s |6423.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_28_0.smt2        | 600.630s |6291.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3.t2_fixed__p22135_terminationG_0.smt2 | 600.623s |5881.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_31_0.smt2        | 600.621s |6064.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_32_0.smt2        | 600.617s |6198.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_17_0.smt2        | 600.603s |6107.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_15_0.smt2        | 600.594s |6345.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_13_0.smt2        | 600.592s |6142.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3-new.t2_fixed__p21803_terminationG_0.smt2 | 600.573s |5262.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_4_0.smt2         | 600.572s |5913.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_2_0.smt2         | 600.563s |5991.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_7_0.smt2         | 600.544s |5982.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  |2152.0MiB|2152.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |259.0MiB|259.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |975.0MiB|975.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |211.0MiB|211.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |3666.0MiB|3666.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |575.0MiB|575.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |309.0MiB|309.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |336.0MiB|336.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |695.0MiB|695.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |944.0MiB|944.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |685.0MiB|685.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |393.0MiB|393.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |1096.0MiB|1096.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |979.0MiB|979.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |789.0MiB|789.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |251.0MiB|251.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |390.0MiB|390.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |305.0MiB|305.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |780.0MiB|780.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |443.0MiB|443.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  |2152.0MiB|2152.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |259.0MiB|259.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |975.0MiB|975.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |211.0MiB|211.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |3666.0MiB|3666.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |575.0MiB|575.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |309.0MiB|309.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |336.0MiB|336.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |695.0MiB|695.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |944.0MiB|944.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |685.0MiB|685.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |393.0MiB|393.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |1096.0MiB|1096.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |979.0MiB|979.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |789.0MiB|789.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |251.0MiB|251.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |390.0MiB|390.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |305.0MiB|305.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |780.0MiB|780.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |443.0MiB|443.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  |2152.0MiB|2152.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |259.0MiB|259.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |975.0MiB|975.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |211.0MiB|211.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |3666.0MiB|3666.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |575.0MiB|575.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |309.0MiB|309.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |336.0MiB|336.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |695.0MiB|695.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |944.0MiB|944.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |685.0MiB|685.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |393.0MiB|393.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |1096.0MiB|1096.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |979.0MiB|979.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |789.0MiB|789.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |251.0MiB|251.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |390.0MiB|390.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |305.0MiB|305.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |780.0MiB|780.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |443.0MiB|443.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  |2152.0MiB|2152.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |259.0MiB|259.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  |975.0MiB|975.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |211.0MiB|211.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  |3666.0MiB|3666.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |575.0MiB|575.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |309.0MiB|309.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |336.0MiB|336.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  |695.0MiB|695.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  |944.0MiB|944.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |685.0MiB|685.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |393.0MiB|393.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  |1096.0MiB|1096.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |979.0MiB|979.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |789.0MiB|789.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |251.0MiB|251.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |390.0MiB|390.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |305.0MiB|305.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |780.0MiB|780.0MiB|0B| 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |443.0MiB|443.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22640_terminationG_0.smt2 | 573.957s |18.808GiB|
|non-incremental/QF_NIA/20220315-MathProblems/RTA_093.smt2                                  | 600.825s |7602.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_14_0.smt2        | 600.693s |6473.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_19_0.smt2        | 600.689s |6465.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_18_0.smt2        | 600.632s |6423.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_24_0.smt2        | 600.649s |6374.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_26_0.smt2        | 600.643s |6348.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_15_0.smt2        | 600.594s |6345.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_20_0.smt2        | 552.155s |6331.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_22_0.smt2        | 600.649s |6320.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_28_0.smt2        | 600.630s |6291.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_32_0.smt2        | 600.617s |6198.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_16_0.smt2        | 565.126s |6173.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_13_0.smt2        | 600.592s |6142.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_17_0.smt2        | 600.603s |6107.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_3_0.smt2         | 600.671s |6096.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_31_0.smt2        | 600.621s |6064.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_2_0.smt2         | 600.563s |5991.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_7_0.smt2         | 600.544s |5982.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_8_0.smt2         | 506.022s |5938.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22640_terminationG_0.smt2 | 573.957s |18.808GiB|
|non-incremental/QF_NIA/20220315-MathProblems/RTA_093.smt2                                  | 600.825s |7602.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_14_0.smt2        | 600.693s |6473.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_19_0.smt2        | 600.689s |6465.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_18_0.smt2        | 600.632s |6423.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_24_0.smt2        | 600.649s |6374.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_26_0.smt2        | 600.643s |6348.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_15_0.smt2        | 600.594s |6345.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_20_0.smt2        | 552.155s |6331.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_22_0.smt2        | 600.649s |6320.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_28_0.smt2        | 600.630s |6291.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_32_0.smt2        | 600.617s |6198.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_16_0.smt2        | 565.126s |6173.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_13_0.smt2        | 600.592s |6142.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_17_0.smt2        | 600.603s |6107.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_3_0.smt2         | 600.671s |6096.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_31_0.smt2        | 600.621s |6064.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_2_0.smt2         | 600.563s |5991.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_7_0.smt2         | 600.544s |5982.0MiB|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_8_0.smt2         | 506.022s |5938.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2  | 600.230s  | 600.230s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChawdharyCookGulwaniSagivYang-ESOP2008-aaron4_true-termination.c__p20893_terminationG_0.smt2  |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21133_terminationG_0.smt2  | 133.587s  | 133.587s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21140_edge_closing_0.smt2  |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c__p21147_edge_closing_0.smt2  | 600.152s  | 600.152s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.09_true-termination.c__p21247_terminationG_0.smt2  |   7.406s  |   7.406s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c__p21344_edge_closing_0.smt2  |   6.199s  |   6.199s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21396_terminationG_0.smt2  |  49.507s  |  49.507s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.12_false-termination.c__p21397_terminationG_0.smt2  | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21950_terminationG_0.smt2  | 127.491s  | 127.491s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21960_terminationG_0.smt2  |  60.384s  |  60.384s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p21995_terminationG_0.smt2  |  11.907s  |  11.907s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22000_terminationG_0.smt2  | 205.524s  | 205.524s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22028_edge_closing_0.smt2  |  53.108s  |  53.108s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.06_false-termination.c__p22032_edge_closing_0.smt2  |  47.057s  |  47.057s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Fig1_true-termination.c__p22155_terminationG_0.smt2  |   0.879s  |   0.879s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Et4.c__p22658_edge_closing_0.smt2  |  12.712s  |  12.712s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23472_edge_closing_0.smt2  |   1.697s  |   1.697s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23748_edge_closing_0.smt2  |  46.801s  |  46.801s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23757_edge_closing_0.smt2  |   4.737s  |   4.737s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__MirrorInterv.c__p24379_terminationG_0.smt2  |   1.863s  |   1.863s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__MirrorInterv.c__p24450_edge_closing_0.smt2  | 600.086s  | 600.086s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__MirrorIntervSim.c__p24484_terminationG_0.smt2  | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__NO_03.c__p24634_terminationG_0.smt2  |   4.469s  |   4.469s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__NO_13.c__p24750_terminationG_0.smt2  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__NO_24.c__p24816_terminationG_0.smt2  | 259.337s  | 259.337s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Narrowing.c__p24540_terminationG_0.smt2  | 600.173s  | 600.173s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__NonTerminationSimple7_false-termination.c__p25148_terminationG_0.smt2  | 600.117s  | 600.117s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__PodelskiRybalchenko-LICS2004-Fig2-TACAS2011-Fig3_true-termination.c__p25430_terminationG_0.smt2  |   1.703s  |   1.703s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Pure3Phase_true-termination.c__p25560_terminationG_0.smt2  | 118.943s  | 118.943s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__Swingers.c__p26085_terminationG_0.smt2  | 600.147s  | 600.147s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2  |  10.307s  |  10.307s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__UpAndDown.c__p26203_terminationG_0.smt2  | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__UpAndDownIneq.c__p26235_terminationG_0.smt2  |   7.765s  |   7.765s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__UpAndDownIneq.c__p26236_terminationG_0.smt2  | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2  |   2.635s  |   2.635s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2  |   0.528s  |   0.528s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27027_terminationG_0.smt2  |   0.664s  |   0.664s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27084_terminationG_0.smt2  |   5.729s  |   5.729s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27136_terminationG_0.smt2  | 253.275s  | 253.275s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27151_terminationG_0.smt2  |   7.605s  |   7.605s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27166_terminationG_0.smt2  |   3.539s  |   3.539s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27186_terminationG_0.smt2  |  17.369s  |  17.369s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27222_terminationG_0.smt2  |  40.626s  |  40.626s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27236_edge_closing_0.smt2  |   3.282s  |   3.282s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/CInteger/Ton_Chanh_15__Hanoi_plus_false-termination.c__p27239_edge_closing_0.smt2  |   3.358s  |   3.358s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27687_edge_closing_0.smt2  |   1.471s  |   1.471s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__p27530_edge_closing_0.smt2  |   1.548s  |   1.548s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__BinTreeChanger.jar-obl-10__p27729_terminationG_0.smt2  |   1.239s  |   1.239s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2  |  12.273s  |  12.273s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Count.jar-obl-10-2__p28115_terminationG_0.smt2  |   9.818s  |   9.818s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Count.jar-obl-10-2__p28120_terminationG_0.smt2  |  24.265s  |  24.265s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2  |   6.390s  |   6.390s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__DivTernary.jar-obl-10__terminationQ_0_0.smt2  |  31.559s  |  31.559s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Flatten.jar-obl-10__p29378_safety_0.smt2  |   1.083s  |   1.083s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Graph.jar-obl-17__p29763_edge_closing_0.smt2  | 416.384s  | 416.384s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Graph.jar-obl-17__p29774_edge_closing_0.smt2  |   6.757s  |   6.757s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__LessLeaves.jar-obl-10__p10002_edge_closing_0.smt2  | 600.197s  | 600.197s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__LessLeaves.jar-obl-10__p10014_edge_closing_0.smt2  | 600.257s  | 600.257s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__LessLeavesRec.jar-obl-10__p10043_terminationG_0.smt2  |  24.258s  |  24.258s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__List.jar-obl-12__p10223_edge_closing_0.smt2  |   0.532s  |   0.532s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MainFind.jar-obl-10__p10608_edge_closing_0.smt2  |   0.655s  |   0.655s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MainFind.jar-obl-10__p10621_edge_closing_0.smt2  |   0.578s  |   0.578s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MainGet.jar-obl-10__p10695_edge_closing_0.smt2  |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MainMove.jar-obl-11__p10745_edge_closing_0.smt2  |   0.686s  |   0.686s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MainMove.jar-obl-11__p10752_edge_closing_0.smt2  |   0.903s  |   0.903s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Matrix.jar-obl-16__p10775_terminationG_0.smt2  |  21.811s  |  21.811s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Matrix.jar-obl-16__p10815_safety_0.smt2  |   6.511s  |   6.511s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Matrix.jar-obl-16__p10849_edge_closing_0.smt2  | 158.382s  | 158.382s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10899_terminationG_0.smt2  |  29.388s  |  29.388s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MysteriousProgram.jar-obl-12__p11031_terminationG_0.smt2  | 100.385s  | 100.385s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationQ_0_0.smt2  |  64.682s  |  64.682s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__NO_13.jar-obl-8__p11405_terminationG_0.smt2  | 600.165s  | 600.165s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__NO_13.jar-obl-8__p11419_edge_closing_0.smt2  |   2.401s  |   2.401s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__NO_13.jar-obl-8__p11440_edge_closing_0.smt2  | 600.137s  | 600.137s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__NO_13.jar-obl-8__p11459_terminationG_0.smt2  |  15.117s  |  15.117s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__NO_24.jar-obl-8__p11510_terminationG_0.smt2  | 600.396s  | 600.396s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Power.jar-obl-10__p11798_terminationG_0.smt2  |  10.703s  |  10.703s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__RandomHard.jar-obl-10__p11831_safety_0.smt2  |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Samefringe.jar-obl-10__p11982_edge_closing_0.smt2  |   0.699s  |   0.699s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12121_terminationG_0.smt2  | 600.232s  | 600.232s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12128_terminationG_0.smt2  | 600.164s  | 600.164s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12142_terminationG_0.smt2  |  20.516s  |  20.516s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12155_terminationG_0.smt2  | 600.199s  | 600.199s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12183_terminationG_0.smt2  | 600.265s  | 600.265s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12184_terminationG_0.smt2  | 600.241s  | 600.241s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12223_terminationG_0.smt2  | 108.800s  | 108.800s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12232_terminationG_0.smt2  | 600.177s  | 600.177s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12239_terminationG_0.smt2  |  10.590s  |  10.590s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__SortCount.jar-obl-10__p12256_terminationG_0.smt2  | 600.204s  | 600.204s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Swingers.jar-obl-8__p12435_terminationG_0.smt2  | 600.179s  | 600.179s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12477_terminationG_0.smt2  | 291.804s  | 291.804s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Test1.jar-obl-8__p12801_terminationG_0.smt2  | 211.849s  | 211.849s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Test6.jar-obl-13__terminationS_13_0.smt2  |  22.500s  |  22.500s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Test6.jar-obl-13__terminationS_24_0.smt2  |   6.362s  |   6.362s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13881_terminationG_0.smt2  | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13896_terminationG_0.smt2  | 123.798s  | 123.798s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13930_edge_closing_0.smt2  |   5.139s  |   5.139s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14126_edge_closing_0.smt2  |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14269_terminationG_0.smt2  |   1.183s  |   1.183s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14289_edge_closing_0.smt2  |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2  |  34.393s  |  34.393s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14386_terminationG_0.smt2  | 600.140s  | 600.140s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14482_terminationG_0.smt2  |  17.680s  |  17.680s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p4392_safety_0.smt2  |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2  |   1.134s  |   1.134s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p4624_safety_0.smt2  |   2.423s  |   2.423s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p4709_terminationG_0.smt2  |  11.138s  |  11.138s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p5104_safety_0.smt2  |   1.199s  |   1.199s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p5158_safety_0.smt2  |   1.400s  |   1.400s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2  |   0.941s  |   0.941s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29915_safety_0.smt2  |   1.711s  |   1.711s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30004_terminationG_0.smt2  |  15.439s  |  15.439s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30026_safety_0.smt2  |   0.897s  |   0.897s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30127_safety_0.smt2  |   1.102s  |   1.102s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30313_safety_0.smt2  |   3.044s  |   3.044s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30338_terminationG_0.smt2  |  30.416s  |  30.416s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30539_safety_0.smt2  |   1.395s  |   1.395s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30824_terminationG_0.smt2  | 106.646s  | 106.646s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31063_safety_0.smt2  |   0.978s  |   0.978s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2  |   2.074s  |   2.074s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31152_safety_0.smt2  |   1.081s  |   1.081s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31167_terminationG_0.smt2  |  29.376s  |  29.376s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2  |   0.639s  |   0.639s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31295_safety_0.smt2  |   0.918s  |   0.918s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31303_safety_0.smt2  |   2.491s  |   2.491s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31345_terminationG_0.smt2  |  12.903s  |  12.903s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31805_safety_0.smt2  |   1.569s  |   1.569s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31859_terminationG_0.smt2  |   5.126s  |   5.126s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31928_safety_0.smt2  |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31947_safety_0.smt2  |   2.989s  |   2.989s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32020_terminationG_0.smt2  |   1.798s  |   1.798s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p322_safety_0.smt2  |   0.560s  |   0.560s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32401_safety_0.smt2  |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32720_terminationG_0.smt2  |   4.916s  |   4.916s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1606_safety_0.smt2  |   0.543s  |   0.543s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1659_safety_0.smt2  |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1691_safety_0.smt2  |   0.822s  |   0.822s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2113_safety_0.smt2  |   2.060s  |   2.060s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2225_safety_0.smt2  |   0.778s  |   0.778s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2436_safety_0.smt2  |   0.654s  |   0.654s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2746_safety_0.smt2  |   1.602s  |   1.602s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3008_safety_0.smt2  |   2.378s  |   2.378s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3178_safety_0.smt2  |   1.355s  |   1.355s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3188_terminationG_0.smt2  |  28.605s  |  28.605s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3358_terminationG_0.smt2  | 126.992s  | 126.992s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3363_edge_closing_0.smt2  | 600.257s  | 600.257s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3697_safety_0.smt2  |   2.379s  |   2.379s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5497_safety_0.smt2  |   0.586s  |   0.586s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6135_terminationG_0.smt2  |  41.523s  |  41.523s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6217_safety_0.smt2  |   1.393s  |   1.393s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6354_safety_0.smt2  |   0.591s  |   0.591s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6496_terminationG_0.smt2  |  86.260s  |  86.260s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6506_edge_closing_0.smt2  | 600.293s  | 600.293s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6932_safety_0.smt2  |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7017_terminationG_0.smt2  |   3.291s  |   3.291s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7192_safety_0.smt2  |   0.640s  |   0.640s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7210_terminationG_0.smt2  |  10.748s  |  10.748s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7211_terminationG_0.smt2  |  20.562s  |  20.562s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7322_safety_0.smt2  |   2.042s  |   2.042s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7607_terminationG_0.smt2  |  94.611s  |  94.611s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9479_terminationG_0.smt2  | 105.136s  | 105.136s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9558_terminationG_0.smt2  |   2.223s  |   2.223s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7969_safety_0.smt2  |   7.875s  |   7.875s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8073_terminationG_0.smt2  |   8.644s  |   8.644s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8337_safety_0.smt2  |   8.670s  |   8.670s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8348_safety_0.smt2  |   9.493s  |   9.493s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8402_safety_0.smt2  |   6.127s  |   6.127s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2  |   7.367s  |   7.367s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9027_safety_0.smt2  |   8.830s  |   8.830s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_11_0.smt2  |  22.448s  |  22.448s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_14_0.smt2  |  23.282s  |  23.282s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_15_0.smt2  |  23.165s  |  23.165s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_16_0.smt2  |  22.040s  |  22.040s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_19_0.smt2  |  29.354s  |  29.354s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_24_0.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_28_0.smt2  |  16.655s  |  16.655s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_2_0.smt2  |  29.123s  |  29.123s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_31_0.smt2  |  20.155s  |  20.155s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_5_0.smt2  |  17.972s  |  17.972s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2  | 193.725s  | 193.725s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_10_0.smt2  |  47.275s  |  47.275s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_11_0.smt2  |  56.337s  |  56.337s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_12_0.smt2  |  47.105s  |  47.105s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_13_0.smt2  |  42.679s  |  42.679s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_14_0.smt2  |  42.423s  |  42.423s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_15_0.smt2  |  47.029s  |  47.029s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_16_0.smt2  |  53.384s  |  53.384s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_17_0.smt2  |  43.354s  |  43.354s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_18_0.smt2  |  41.345s  |  41.345s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2  |  48.571s  |  48.571s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_1_0.smt2  | 146.778s  | 146.778s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_20_0.smt2  |  42.488s  |  42.488s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_21_0.smt2  |  53.719s  |  53.719s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_22_0.smt2  |  54.306s  |  54.306s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_23_0.smt2  |  54.338s  |  54.338s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_24_0.smt2  |  59.000s  |  59.000s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_25_0.smt2  |  55.619s  |  55.619s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_26_0.smt2  |  55.376s  |  55.376s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_27_0.smt2  |  67.791s  |  67.791s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2  |  39.971s  |  39.971s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_29_0.smt2  |  61.473s  |  61.473s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_2_0.smt2  | 176.797s  | 176.797s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_3_0.smt2  | 118.120s  | 118.120s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_4_0.smt2  | 200.298s  | 200.298s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_5_0.smt2  | 209.237s  | 209.237s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_6_0.smt2  | 388.703s  | 388.703s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_7_0.smt2  | 307.542s  | 307.542s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_8_0.smt2  | 223.701s  | 223.701s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_9_0.smt2  | 242.140s  | 242.140s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__narrowKonv_rec.jar-obl-8__p11136_edge_closing_0.smt2  |   9.119s  |   9.119s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__narrowing_rec.jar-obl-8__p11066_terminationG_0.smt2  |  31.700s  |  31.700s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__narrowing_rec.jar-obl-8__p11067_terminationG_0.smt2  | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__upAndDown_rec.jar-obl-8__p13161_edge_closing_0.smt2  | 557.460s  | 557.460s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14933_safety_0.smt2  |  70.761s  |  70.761s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_AProVE_2014__whileSingle_rec.jar-obl-8__p15018_terminationG_0.smt2  | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__Prim_4.t2__p7936_terminationG_0.smt2   |   1.226s  |   1.226s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__Prim_4.t2__p7976_terminationG_0.smt2   |   1.437s  |   1.437s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__Prim_4.t2__p8016_terminationG_0.smt2   |   1.225s  |   1.225s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__Prim_4.t2__p8035_terminationG_0.smt2   |   1.787s  |   1.787s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__afagp-fail.t2__p15516_edge_closing_0.smt2  |  29.830s  |  29.830s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__agafp.t2__p15626_terminationG_0.smt2   |   8.186s  |   8.186s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__agafp.t2__p15636_terminationG_0.smt2   |  31.704s  |  31.704s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__agafp.t2__terminationS_0_0.smt2        | 386.699s  | 386.699s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2__p15941_terminationG_0.smt2  | 592.616s  | 592.616s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2__p16000_terminationG_0.smt2  | 505.851s  | 505.851s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2__p16028_terminationG_0.smt2  | 600.361s  | 600.361s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2_fixed__p15799_terminationG_0.smt2  | 600.413s  | 600.413s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2_fixed__p15830_terminationG_0.smt2  | 164.531s  | 164.531s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted-fail.t2_fixed__p15846_terminationG_0.smt2  | 433.990s  | 433.990s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted.t2__p16269_terminationG_0.smt2  | 600.480s  | 600.480s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2  | 600.289s  | 600.289s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted.t2__p16298_terminationG_0.smt2  | 600.361s  | 600.361s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted.t2_fixed__p16101_terminationG_0.smt2  | 600.458s  | 600.458s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-accepted.t2_fixed__p16110_terminationG_0.smt2  |  37.362s  |  37.362s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-live.t2__p16639_terminationG_0.smt2  |  97.766s  |  97.766s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-live.t2_fixed__p16559_terminationG_0.smt2  |   3.421s  |   3.421s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-live.t2_fixed__p16560_terminationG_0.smt2  | 223.050s  | 223.050s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-live.t2_fixed__p16564_terminationG_0.smt2  |   4.011s  |   4.011s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2  | 223.811s  | 223.811s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__apchildlive-succeed.t2__p16426_terminationG_0.smt2  | 600.458s  | 600.458s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__brp_withassume.t2__p17437_edge_closing_0.smt2  | 600.249s  | 600.249s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__bs.t2_fixed__p17456_terminationG_0.smt2  |  38.664s  |  38.664s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__db2.t2__term_unfeasibility_0_0.smt2    |  27.937s  |  27.937s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__db2.t2__terminationQ_0_0.smt2          | 116.721s  | 116.721s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__db3.t2__term_unfeasibility_0_0.smt2    |  26.512s  |  26.512s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__db3.t2__terminationQ_0_0.smt2          |  95.231s  |  95.231s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__destroy_seg_leak.t2_fixed__p18858_edge_closing_0.smt2  | 531.899s  | 531.899s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__dumper.t2__p19134_terminationG_0.smt2  | 600.185s  | 600.185s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__edn.t2__p20326_safety_0.smt2           |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__edn.t2__p20632_safety_0.smt2           |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__edn.t2__p20710_safety_0.smt2           |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__efegp.t2__p21961_edge_closing_0.smt2   | 153.917s  | 153.917s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ex11.t2__p22126_terminationG_0.smt2    |  22.000s  |  22.000s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ex36.t2__p30283_safety_0.smt2          |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ex36.t2__p31845_safety_0.smt2          |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ex36.t2__p31955_safety_0.smt2          |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ex36.t2_fixed__p23592_safety_0.smt2    |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__firewire.t2__p32301_edge_closing_0.smt2  | 175.613s  | 175.613s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__firewire.t2__terminationS_19_0.smt2    |  10.386s  |  10.386s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__florian_sas2.t2__p32380_terminationG_0.smt2  | 405.981s  | 405.981s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__florian_sas2.t2__p32384_terminationG_0.smt2  |  74.565s  |  74.565s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__florian_sas2.t2__p32399_terminationG_0.smt2  | 238.098s  | 238.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_13_0.smt2         | 600.592s  | 600.592s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_14_0.smt2         | 600.693s  | 600.693s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_15_0.smt2         | 600.594s  | 600.594s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_16_0.smt2         | 565.126s  | 565.126s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_17_0.smt2         | 600.603s  | 600.603s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_18_0.smt2         | 600.632s  | 600.632s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_19_0.smt2         | 600.689s  | 600.689s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_20_0.smt2         | 552.155s  | 552.155s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_22_0.smt2         | 600.649s  | 600.649s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_24_0.smt2         | 600.649s  | 600.649s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_26_0.smt2         | 600.643s  | 600.643s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_28_0.smt2         | 600.630s  | 600.630s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_2_0.smt2          | 600.563s  | 600.563s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_31_0.smt2         | 600.621s  | 600.621s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_32_0.smt2         | 600.617s  | 600.617s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_3_0.smt2          | 600.671s  | 600.671s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_4_0.smt2          | 600.572s  | 600.572s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_6_0.smt2          | 600.645s  | 600.645s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_7_0.smt2          | 600.544s  | 600.544s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__foo.t2__terminationS_8_0.smt2          | 506.022s  | 506.022s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32602_terminationG_0.smt2  | 600.193s  | 600.193s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32699_edge_closing_0.smt2  | 600.170s  | 600.170s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fourn.t2__p32708_terminationG_0.smt2   | 600.266s  | 600.266s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fourn.t2__p32713_terminationG_0.smt2   | 600.201s  | 600.201s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1.t2__terminationQ_0_0.smt2         |  25.033s  |  25.033s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1.t2_fixed__p705_terminationG_0.smt2  |  83.658s  |  83.658s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1.t2_fixed__p721_terminationG_0.smt2  |  30.591s  |  30.591s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1.t2_fixed__p784_terminationG_0.smt2  |  54.713s  |  54.713s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2__p597_terminationG_0.smt2     |  40.753s  |  40.753s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2__p626_terminationG_0.smt2     | 162.945s  | 162.945s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2__p679_terminationG_0.smt2     |  11.010s  |  11.010s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2__p680_terminationG_0.smt2     |  23.234s  |  23.234s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2__terminationQ_0_0.smt2        |  22.317s  |  22.317s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2  |   7.558s  |   7.558s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2_fixed__p551_terminationG_0.smt2  |  24.933s  |  24.933s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2  |  61.560s  |  61.560s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun6.t2__p1092_terminationG_0.smt2     |  18.425s  |  18.425s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun6.t2_fixed__p1055_terminationG_0.smt2  | 155.990s  | 155.990s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun6.t2_fixed__p1066_edge_closing_0.smt2  | 600.174s  | 600.174s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun7.t2__p1142_terminationG_0.smt2     |   7.117s  |   7.117s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun7.t2__p1167_edge_closing_0.smt2     | 600.201s  | 600.201s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1287_edge_closing_0.smt2     |   1.811s  |   1.811s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1309_edge_closing_0.smt2     |  11.492s  |  11.492s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1314_edge_closing_0.smt2     |   3.924s  |   3.924s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1320_edge_closing_0.smt2     |   3.615s  |   3.615s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1354_edge_closing_0.smt2     |   5.559s  |   5.559s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1357_edge_closing_0.smt2     |  59.458s  |  59.458s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1377_edge_closing_0.smt2     |   1.145s  |   1.145s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1378_edge_closing_0.smt2     |   5.420s  |   5.420s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1393_edge_closing_0.smt2     |  14.971s  |  14.971s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1398_edge_closing_0.smt2     |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1406_edge_closing_0.smt2     |  25.970s  |  25.970s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1409_edge_closing_0.smt2     |  23.557s  |  23.557s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1413_edge_closing_0.smt2     |   4.277s  |   4.277s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1437_edge_closing_0.smt2     |  12.749s  |  12.749s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1440_edge_closing_0.smt2     |   4.668s  |   4.668s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1460_edge_closing_0.smt2     |   3.324s  |   3.324s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1467_edge_closing_0.smt2     | 114.227s  | 114.227s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__fun9.t2__p1485_edge_closing_0.smt2     |   2.403s  |   2.403s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2  | 600.234s  | 600.234s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_19_0.smt2  |  29.065s  |  29.065s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_21_0.smt2  |  14.875s  |  14.875s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2  |  15.147s  |  15.147s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_26_0.smt2  |  17.737s  |  17.737s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_49_0.smt2  |  25.527s  |  25.527s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_50_0.smt2  |  52.659s  |  52.659s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1608_terminationG_0.smt2  | 600.302s  | 600.302s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_25_0.smt2  |   9.043s  |   9.043s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_26_0.smt2  |  10.009s  |  10.009s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_27_0.smt2  |  10.701s  |  10.701s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_55_0.smt2  |   8.080s  |   8.080s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_25_0.smt2  |  16.438s  |  16.438s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2  |  15.594s  |  15.594s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_49_0.smt2  |  29.235s  |  29.235s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_51_0.smt2  |  59.029s  |  59.029s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_26_0.smt2  |   9.981s  |   9.981s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2  |  10.595s  |  10.595s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_57_0.smt2  |  17.803s  |  17.803s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_62_0.smt2  |   9.038s  |   9.038s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2__p1768_terminationG_0.smt2      | 178.492s  | 178.492s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2__terminationS_25_0.smt2         |  12.044s  |  12.044s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2_fixed__terminationS_24_0.smt2   |   8.140s  |   8.140s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2_fixed__terminationS_53_0.smt2   |  33.261s  |  33.261s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2_fixed__terminationS_54_0.smt2   |  11.239s  |  11.239s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__hqr.t2_fixed__terminationS_55_0.smt2   |   7.700s  |   7.700s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__janne_complex.t2__p2020_terminationG_0.smt2  |   5.021s  |   5.021s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__janne_complex.t2__p2041_terminationG_0.smt2  |  49.768s  |  49.768s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__janne_complex.t2__p2193_terminationG_0.smt2  |  11.771s  |  11.771s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__janne_complex.t2__p2254_terminationG_0.smt2  |   3.442s  |   3.442s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__janne_complex.t2__p2263_terminationG_0.smt2  |   6.180s  |   6.180s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__matmul.t2_fixed__p2649_terminationG_0.smt2  |   6.440s  |   6.440s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91.t2__p2940_edge_closing_0.smt2     |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3164_terminationG_0.smt2  | 353.510s  | 353.510s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3169_terminationG_0.smt2  | 274.612s  | 274.612s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3221_terminationG_0.smt2  | 476.099s  | 476.099s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3249_terminationG_0.smt2  | 357.821s  | 357.821s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3256_terminationG_0.smt2  |  13.194s  |  13.194s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3301_terminationG_0.smt2  |  96.097s  |  96.097s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3311_terminationG_0.smt2  | 160.412s  | 160.412s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__mc91test.t2__p3358_terminationG_0.smt2  |   6.914s  |   6.914s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n-5.t2__p4677_terminationG_0.smt2      | 112.541s  | 112.541s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n-5.t2__p4682_terminationG_0.smt2      |  14.166s  |  14.166s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n-5.t2__p4703_edge_closing_0.smt2      |   5.866s  |   5.866s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n-5.t2_fixed__p4589_terminationG_0.smt2  |   0.852s  |   0.852s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6188_terminationG_0.smt2  | 600.203s  | 600.203s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6193_terminationG_0.smt2  | 600.193s  | 600.193s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6198_terminationG_0.smt2  | 600.192s  | 600.192s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6202_terminationG_0.smt2  | 600.166s  | 600.166s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6218_terminationG_0.smt2  | 600.159s  | 600.159s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6219_terminationG_0.smt2  | 600.224s  | 600.224s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__n_firewire_instrumented-PP.t2__p6225_edge_closing_0.smt2  |   7.206s  |   7.206s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__nakata.t2__p5305_terminationG_0.smt2   |   2.339s  |   2.339s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__nakata.t2__p5310_terminationG_0.smt2   | 600.176s  | 600.176s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__nakata.t2__p5352_edge_closing_0.smt2   | 600.228s  | 600.228s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__nakata.t2__terminationS_6_0.smt2       |   8.430s  |   8.430s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__opt-tree.c.t2__p6339_terminationG_0.smt2  |   1.256s  |   1.256s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__opt-tree.c.t2__p6340_terminationG_0.smt2  |  41.694s  |  41.694s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__p-5.t2_fixed__p6782_edge_closing_0.smt2  |   4.378s  |   4.378s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__pgarch.t2__p7283_terminationG_0.smt2   |   2.243s  |   2.243s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__polyrank4.t2__p7477_terminationG_0.smt2  |   1.459s  |   1.459s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__polyrank4.t2__p7482_terminationG_0.smt2  |   1.662s  |   1.662s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__polyrank4.t2__p7520_terminationG_0.smt2  |  11.588s  |  11.588s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__polyrank5.t2__p7556_terminationG_0.smt2  |   8.033s  |   8.033s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ppblock.t2__p7746_edge_closing_0.smt2  |   1.329s  |   1.329s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__ppblockterm.t2__p7916_edge_closing_0.smt2  |   2.813s  |   2.813s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__randomwalk.t2__p8416_terminationG_0.smt2  |  33.282s  |  33.282s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1-striped.t2__p12897_safety_0.smt2    |   1.183s  |   1.183s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1-striped.t2__p12943_safety_0.smt2    |   2.770s  |   2.770s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1-striped.t2_fixed__p9299_terminationG_0.smt2  | 426.826s  | 426.826s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1-striped.t2_fixed__p9992_safety_0.smt2  |   4.386s  |   4.386s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p17922_terminationG_0.smt2      | 136.632s  | 136.632s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p17931_terminationG_0.smt2      |  23.390s  |  23.390s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p18338_safety_0.smt2            |   1.666s  |   1.666s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p18948_safety_0.smt2            |   2.396s  |   2.396s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p19377_safety_0.smt2            |   3.190s  |   3.190s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p19834_safety_0.smt2            |   1.491s  |   1.491s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2__p19848_safety_0.smt2            |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2_fixed__p15165_terminationG_0.smt2  | 209.957s  | 209.957s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__s1.t2_fixed__p15180_terminationG_0.smt2  | 102.323s  | 102.323s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sas2.t2__p21297_terminationG_0.smt2    | 600.173s  | 600.173s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sas2.t2__p21302_terminationG_0.smt2    | 411.899s  | 411.899s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sas2.t2__p21311_terminationG_0.smt2    |  32.908s  |  32.908s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sas2.t2__terminationS_1_0.smt2         |  14.140s  |  14.140s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__select.t2__p21400_edge_closing_0.smt2  | 182.475s  | 182.475s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3-new.t2__p22118_edge_closing_0.smt2  |  27.383s  |  27.383s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3-new.t2_fixed__p21803_terminationG_0.smt2  | 600.573s  | 600.573s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-3.t2_fixed__p22135_terminationG_0.smt2  | 600.623s  | 600.623s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22479_terminationG_0.smt2  |  23.011s  |  23.011s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22519_safety_0.smt2  |  20.763s  |  20.763s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22531_terminationG_0.smt2  |  96.931s  |  96.931s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22603_safety_0.smt2  |   5.561s  |   5.561s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22607_safety_0.smt2  |   1.591s  |   1.591s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22639_terminationG_0.smt2  |  55.273s  |  55.273s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22640_terminationG_0.smt2  | 573.957s  | 573.957s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-4-filtered.t2__p22688_terminationG_0.smt2  | 600.331s  | 600.331s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-5-filtered.t2__p22882_terminationG_0.smt2  |   0.677s  |   0.677s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2  |   1.239s  |   1.239s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__small15.t2__p23742_terminationG_0.smt2  |   1.513s  |   1.513s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__small15.t2__p23781_edge_closing_0.smt2  |   2.101s  |   2.101s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__st88.t2__p24217_terminationG_0.smt2    |   4.030s  |   4.030s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2__p24620_terminationG_0.smt2  | 114.785s  | 114.785s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2__p24634_terminationG_0.smt2  | 386.752s  | 386.752s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2__p24649_terminationG_0.smt2  | 600.245s  | 600.245s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2__p24820_edge_closing_0.smt2  |  10.350s  |  10.350s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2__p24821_edge_closing_0.smt2  |  62.753s  |  62.753s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2_fixed__p24590_edge_closing_0.smt2  |  37.401s  |  37.401s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver-succeed.t2_fixed__p24591_edge_closing_0.smt2  | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__streamserver.bug.t2__p24573_terminationG_0.smt2  | 408.040s  | 408.040s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sudoku.t2__p24862_terminationG_0.smt2  | 600.185s  | 600.185s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__sudoku.t2__p24867_terminationG_0.smt2  | 107.211s  | 107.211s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2  |  24.257s  |  24.257s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_28_0.smt2  |  18.367s  |  18.367s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2  |  23.281s  |  23.281s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__svdcmp.t2__term_unfeasibility_8_0.smt2  |   7.553s  |   7.553s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25001_terminationG_0.smt2  | 600.299s  | 600.299s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25046_edge_closing_0.smt2  | 541.130s  | 541.130s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2  | 600.213s  | 600.213s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__tqli.t2__p25217_terminationG_0.smt2    | 600.302s  | 600.302s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__tqli.t2_fixed__p25201_edge_closing_0.smt2  | 600.171s  | 600.171s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/ITS/From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2  |   7.255s  |   7.255s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/SAT14/1813.smt2                                     |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20170427-VeryMax/SAT14/585.smt2                                      |   2.190s  |   2.190s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/MC_03.smt2                                     | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/MC_09.smt2                                     | 600.311s  | 600.311s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/MC_11.smt2                                     | 600.444s  | 600.444s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/MF_03.smt2                                     | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/MS_04.smt2                                     | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/RTA_093.smt2                                   | 600.825s  | 600.825s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/SC_08.smt2                                     | 600.205s  | 600.205s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0013.smt2                                  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0014.smt2                                  | 600.156s  | 600.156s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0022.smt2                                  | 600.126s  | 600.126s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0023.smt2                                  | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0031.smt2                                  | 600.117s  | 600.117s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0032.smt2                                  | 600.172s  | 600.172s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0040.smt2                                  | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0041.smt2                                  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0049.smt2                                  | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0050.smt2                                  | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0052.smt2                                  | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0058.smt2                                  | 600.069s  | 600.069s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0066.smt2                                  | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0067.smt2                                  | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0068.smt2                                  | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0070.smt2                                  | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0076.smt2                                  | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0077.smt2                                  | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0085.smt2                                  | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0097.smt2                                  |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0099.smt2                                  |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0100.smt2                                  | 600.160s  | 600.160s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0103.smt2                                  | 600.142s  | 600.142s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0104.smt2                                  | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0110.smt2                                  | 600.175s  | 600.175s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0112.smt2                                  | 600.124s  | 600.124s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0113.smt2                                  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0121.smt2                                  | 600.150s  | 600.150s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0122.smt2                                  | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0130.smt2                                  | 600.168s  | 600.168s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0131.smt2                                  | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0136.smt2                                  | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0138.smt2                                  | 600.124s  | 600.124s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0139.smt2                                  | 600.127s  | 600.127s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0140.smt2                                  | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0148.smt2                                  | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0149.smt2                                  | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0153.smt2                                  |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0157.smt2                                  | 600.198s  | 600.198s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0158.smt2                                  | 600.266s  | 600.266s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0163.smt2                                  | 600.181s  | 600.181s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0175.smt2                                  | 600.150s  | 600.150s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0176.smt2                                  | 600.155s  | 600.155s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0184.smt2                                  | 600.222s  | 600.222s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0190.smt2                                  |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0193.smt2                                  | 600.209s  | 600.209s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0194.smt2                                  | 600.180s  | 600.180s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0202.smt2                                  | 600.161s  | 600.161s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0203.smt2                                  | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0211.smt2                                  | 600.140s  | 600.140s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0212.smt2                                  | 600.177s  | 600.177s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0220.smt2                                  | 600.051s  | 600.051s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0221.smt2                                  | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0226.smt2                                  | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0229.smt2                                  | 600.127s  | 600.127s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0230.smt2                                  | 600.093s  | 600.093s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0236.smt2                                  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0238.smt2                                  | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0239.smt2                                  | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0244.smt2                                  |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0247.smt2                                  | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0248.smt2                                  | 600.127s  | 600.127s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0257.smt2                                  | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0265.smt2                                  | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0266.smt2                                  | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0268.smt2                                  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0274.smt2                                  | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0275.smt2                                  | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0283.smt2                                  | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0284.smt2                                  | 600.153s  | 600.153s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0286.smt2                                  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0292.smt2                                  | 600.127s  | 600.127s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0293.smt2                                  | 600.157s  | 600.157s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0300.smt2                                  | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0301.smt2                                  | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0302.smt2                                  | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0310.smt2                                  | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0311.smt2                                  | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0315.smt2                                  |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0319.smt2                                  | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0320.smt2                                  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0325.smt2                                  | 600.184s  | 600.184s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0328.smt2                                  | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0329.smt2                                  | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0330.smt2                                  |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0334.smt2                                  |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0337.smt2                                  | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0338.smt2                                  | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0346.smt2                                  | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0347.smt2                                  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0350.smt2                                  | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0355.smt2                                  | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0356.smt2                                  | 600.131s  | 600.131s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0364.smt2                                  | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0365.smt2                                  | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0366.smt2                                  | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0367.smt2                                  | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0368.smt2                                  | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0369.smt2                                  |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0373.smt2                                  | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0374.smt2                                  | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0382.smt2                                  | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0383.smt2                                  | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0389.smt2                                  | 600.175s  | 600.175s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0391.smt2                                  | 600.178s  | 600.178s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0392.smt2                                  | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0394.smt2                                  | 600.164s  | 600.164s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0400.smt2                                  | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0401.smt2                                  | 600.148s  | 600.148s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0402.smt2                                  | 600.156s  | 600.156s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0409.smt2                                  | 600.154s  | 600.154s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0410.smt2                                  | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0411.smt2                                  | 600.160s  | 600.160s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0418.smt2                                  | 600.151s  | 600.151s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0419.smt2                                  | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0424.smt2                                  | 600.178s  | 600.178s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0426.smt2                                  | 600.124s  | 600.124s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0427.smt2                                  | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0428.smt2                                  | 600.195s  | 600.195s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0436.smt2                                  | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0437.smt2                                  | 600.158s  | 600.158s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0441.smt2                                  | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0445.smt2                                  | 600.170s  | 600.170s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0446.smt2                                  | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0451.smt2                                  | 600.204s  | 600.204s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0454.smt2                                  | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0455.smt2                                  | 600.140s  | 600.140s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0463.smt2                                  | 600.127s  | 600.127s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0464.smt2                                  | 600.157s  | 600.157s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0472.smt2                                  | 600.137s  | 600.137s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0473.smt2                                  | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0481.smt2                                  | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0482.smt2                                  | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0483.smt2                                  | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0484.smt2                                  |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0486.smt2                                  |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0490.smt2                                  | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0493.smt2                                  |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0496.smt2                                  |  33.054s  |  33.054s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0498.smt2                                  | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0499.smt2                                  | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0500.smt2                                  | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0502.smt2                                  | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0508.smt2                                  | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0509.smt2                                  | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0517.smt2                                  | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0518.smt2                                  | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0527.smt2                                  | 600.130s  | 600.130s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0529.smt2                                  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0530.smt2                                  | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0535.smt2                                  | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0536.smt2                                  | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0537.smt2                                  | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0540.smt2                                  |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0544.smt2                                  | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0545.smt2                                  | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0551.smt2                                  | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0553.smt2                                  | 600.069s  | 600.069s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0554.smt2                                  | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0562.smt2                                  | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0563.smt2                                  | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0569.smt2                                  | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0571.smt2                                  | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0572.smt2                                  | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0578.smt2                                  | 600.219s  | 600.219s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0580.smt2                                  | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0581.smt2                                  | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0582.smt2                                  | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0589.smt2                                  | 600.149s  | 600.149s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0590.smt2                                  | 600.154s  | 600.154s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0592.smt2                                  | 600.159s  | 600.159s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0597.smt2                                  | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0598.smt2                                  | 600.184s  | 600.184s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0599.smt2                                  | 600.124s  | 600.124s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0603.smt2                                  |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0607.smt2                                  | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0608.smt2                                  | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0611.smt2                                  | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0616.smt2                                  | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0617.smt2                                  | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0625.smt2                                  | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0626.smt2                                  | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0635.smt2                                  | 600.140s  | 600.140s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0642.smt2                                  | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0643.smt2                                  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0644.smt2                                  | 600.130s  | 600.130s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0653.smt2                                  | 600.140s  | 600.140s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0656.smt2                                  |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0661.smt2                                  | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0662.smt2                                  | 600.149s  | 600.149s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0670.smt2                                  | 600.130s  | 600.130s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0671.smt2                                  | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0678.smt2                                  |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0679.smt2                                  | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0680.smt2                                  | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0684.smt2                                  |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0688.smt2                                  | 600.131s  | 600.131s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0689.smt2                                  | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0697.smt2                                  | 600.170s  | 600.170s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0698.smt2                                  | 600.176s  | 600.176s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0703.smt2                                  |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0706.smt2                                  | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0707.smt2                                  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0715.smt2                                  | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0716.smt2                                  | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0717.smt2                                  | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0719.smt2                                  | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0722.smt2                                  |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0723.smt2                                  | 600.170s  | 600.170s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0724.smt2                                  | 600.165s  | 600.165s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0725.smt2                                  | 600.150s  | 600.150s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0733.smt2                                  | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0734.smt2                                  | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0740.smt2                                  | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0742.smt2                                  | 600.148s  | 600.148s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0743.smt2                                  | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0745.smt2                                  | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0751.smt2                                  | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0752.smt2                                  | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0760.smt2                                  | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0761.smt2                                  | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0768.smt2                                  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0769.smt2                                  | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0770.smt2                                  | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0776.smt2                                  | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0778.smt2                                  | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0779.smt2                                  | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0787.smt2                                  | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0788.smt2                                  | 600.066s  | 600.066s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0796.smt2                                  | 600.147s  | 600.147s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0797.smt2                                  | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0805.smt2                                  | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0806.smt2                                  | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0814.smt2                                  | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0815.smt2                                  | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0816.smt2                                  |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0823.smt2                                  | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0824.smt2                                  | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0825.smt2                                  |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0832.smt2                                  | 600.152s  | 600.152s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0833.smt2                                  | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0834.smt2                                  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0841.smt2                                  | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0842.smt2                                  | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0850.smt2                                  | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0851.smt2                                  | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0859.smt2                                  | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0860.smt2                                  | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0868.smt2                                  | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0869.smt2                                  | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0877.smt2                                  | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0878.smt2                                  | 600.124s  | 600.124s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0883.smt2                                  |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0884.smt2                                  | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0886.smt2                                  | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0887.smt2                                  | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0895.smt2                                  | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0896.smt2                                  | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0898.smt2                                  | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0901.smt2                                  | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0904.smt2                                  | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0906.smt2                                  | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0913.smt2                                  | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0914.smt2                                  | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0920.smt2                                  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0922.smt2                                  | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0923.smt2                                  | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0931.smt2                                  | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0932.smt2                                  | 600.080s  | 600.080s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0940.smt2                                  | 600.117s  | 600.117s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0941.smt2                                  | 600.152s  | 600.152s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0944.smt2                                  |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0949.smt2                                  | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0950.smt2                                  | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0958.smt2                                  | 600.125s  | 600.125s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0959.smt2                                  | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0963.smt2                                  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0967.smt2                                  | 600.141s  | 600.141s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0968.smt2                                  | 600.142s  | 600.142s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0976.smt2                                  | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0977.smt2                                  | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0983.smt2                                  | 600.127s  | 600.127s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0985.smt2                                  | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0986.smt2                                  | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0994.smt2                                  | 600.108s  | 600.108s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/STC_0995.smt2                                  | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/TA_03.smt2                                     | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/TA_05.smt2                                     | 600.180s  | 600.180s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20220315-MathProblems/TA_13.smt2                                     | 600.141s  | 600.141s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInv128.smt2                          | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInv16.smt2                           | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInv32.smt2                           | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInv64.smt2                           | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInv8.smt2                            | 600.066s  | 600.066s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInvFull.smt2                         | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInvInitial.smt2                      | 600.054s  | 600.054s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInvStep.smt2                         | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInvStepSimplified.smt2               | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/modInvVar1.smt2                         | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/sqrtStepFinal.smt2                      | 600.165s  | 600.165s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/20230328-sqrtmodinv-hoenicke/sqrtStepFinala.smt2                     | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT1335852993657230070.smt2                             |   0.872s  |   0.872s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT1437438160177275586.smt2                             |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT1700028870436976635.smt2                             |   2.412s  |   2.412s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT180444191153863419.smt2                              |   6.547s  |   6.547s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT1813676864021281701.smt2                             |  13.335s  |  13.335s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT2214668917450755150.smt2                             |   8.301s  |   8.301s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT2276070888632403184.smt2                             |  15.042s  |  15.042s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT3457830339872275636.smt2                             |   0.946s  |   0.946s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT3678576972294594665.smt2                             |  60.663s  |  60.663s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT3712394338782947208.smt2                             |  16.792s  |  16.792s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT3839584170547805483.smt2                             |  23.887s  |  23.887s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT4259464554444412647.smt2                             |   1.127s  |   1.127s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT463192377960637155.smt2                              |   5.399s  |   5.399s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT5210162955256537540.smt2                             |  45.218s  |  45.218s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT5468773551032053543.smt2                             |   6.522s  |   6.522s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT5521985939949569030.smt2                             |   3.014s  |   3.014s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT5642158517481563632.smt2                             |   6.973s  |   6.973s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT5753280746557461985.smt2                             |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT6531155344723557531.smt2                             |   3.645s  |   3.645s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT6545992645874542347.smt2                             | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT6647586385534524663.smt2                             |   6.964s  |   6.964s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT6828719750442006249.smt2                             |  18.742s  |  18.742s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT6981420136966712689.smt2                             |  11.089s  |  11.089s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT7201733644041072759.smt2                             |   5.988s  |   5.988s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT725924178667047452.smt2                              |   5.958s  |   5.958s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT7924349461296395393.smt2                             | 113.196s  | 113.196s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT8619300169146917506.smt2                             |   4.685s  |   4.685s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT9062228803117299674.smt2                             |  72.876s  |  72.876s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/AProVE/aproveSMT9064001295904670492.smt2                             |   1.975s  |   1.975s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/LCTES/digital-stopwatch.locals.nosummaries.smt2                      | 485.859s  | 485.859s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/LCTES/digital-stopwatch.locals.smt2                                  |   0.558s  |   0.558s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/LassoRanker/ChenFlurMukhopadhyay-SAS2012-Ex2.11_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-3wwoHp.smt2                                             | 101.688s  | 101.688s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-607QpU.smt2                                             |  13.925s  |  13.925s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-6k3pKM.smt2                                             |   0.926s  |   0.926s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-7fXGzy.smt2                                             |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-K5O3aH.smt2                                             | 157.672s  | 157.672s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-MVylXc.smt2                                             | 600.362s  | 600.362s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-l6cqQI.smt2                                             | 600.188s  | 600.188s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-p9MQp4.smt2                                             |   3.080s  |   3.080s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-unsat-02.smt2                                           | 600.166s  | 600.166s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-unsat-03.smt2                                           | 600.224s  | 600.224s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-unsat-04.smt2                                           | 600.149s  | 600.149s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/leipzig/term-unsat-05.smt2                                           | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|non-incremental/QF_NIA/mcm/26.smt2                                                          | 600.141s  | 600.141s  |   0.000s  | 0.0%|
</details>
