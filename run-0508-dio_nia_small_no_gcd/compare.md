Comparing data and data


# SUMMARY
- LHS tests = 2313
- RHS tests = 2313
- LHS success = 2313  (100.0%)
- RHS success = 2313  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: dio_nia_small_no_gcd
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 36a0006f595c746a98c133ba38671ab5659dacf6
Z3 branch: 
Z3 options: "-T:600 -st lp.dio=true lp.dio_run_gcd=false"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: remove testing code in is_big_term_on_no_term

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: dio_nia_small_no_gcd
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 36a0006f595c746a98c133ba38671ab5659dacf6
Z3 branch: 
Z3 options: "-T:600 -st lp.dio=true lp.dio_run_gcd=false"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: remove testing code in is_big_term_on_no_term

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 594.258s  | 594.258s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 599.680s  | 599.680s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.926s  |   1.926s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.419s  |   0.419s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 599.153s  | 599.153s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.299s  |   0.299s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 594.258s  | 594.258s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 599.680s  | 599.680s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.926s  |   1.926s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.419s  |   0.419s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 599.153s  | 599.153s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.299s  |   0.299s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 594.258s  | 594.258s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 599.680s  | 599.680s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.926s  |   1.926s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.419s  |   0.419s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 599.153s  | 599.153s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.299s  |   0.299s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 594.258s  | 594.258s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 599.680s  | 599.680s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.926s  |   1.926s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.419s  |   0.419s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 599.153s  | 599.153s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.299s  |   0.299s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                            | 600.301s |1703.0MiB|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                         | 600.183s |811.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 600.166s |2122.0MiB|
|185.smt2                                                                                   | 600.037s |1129.0MiB|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                       | 600.023s |428.0MiB|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                | 600.017s |757.0MiB|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2              | 600.011s |324.0MiB|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                   | 600.003s |971.0MiB|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                              | 599.974s |1125.0MiB|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                        | 599.935s |985.0MiB|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                            | 599.931s |1259.0MiB|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                              | 599.914s |517.0MiB|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                | 599.909s |211.0MiB|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                     | 599.908s |375.0MiB|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                         | 599.903s |1497.0MiB|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                  | 599.901s |816.0MiB|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                         | 599.886s |578.0MiB|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                           | 599.884s |453.0MiB|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                     | 599.876s |979.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                              | 599.873s |352.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                            | 600.301s |1703.0MiB|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                         | 600.183s |811.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 600.166s |2122.0MiB|
|185.smt2                                                                                   | 600.037s |1129.0MiB|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                       | 600.023s |428.0MiB|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                | 600.017s |757.0MiB|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2              | 600.011s |324.0MiB|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                   | 600.003s |971.0MiB|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                              | 599.974s |1125.0MiB|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                        | 599.935s |985.0MiB|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                            | 599.931s |1259.0MiB|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                              | 599.914s |517.0MiB|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                | 599.909s |211.0MiB|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                     | 599.908s |375.0MiB|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                         | 599.903s |1497.0MiB|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                  | 599.901s |816.0MiB|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                         | 599.886s |578.0MiB|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                           | 599.884s |453.0MiB|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                     | 599.876s |979.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                              | 599.873s |352.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |92.6MiB|92.6MiB|0B| 0.0%|
|04.smt2                                                                                     |73.644MiB|73.644MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |28.332MiB|28.332MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.772MiB|30.772MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.392MiB|23.392MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.788MiB|23.788MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.312MiB|24.312MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.788MiB|24.788MiB|0B| 0.0%|
|107.smt2                                                                                    |22.296MiB|22.296MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.304MiB|27.304MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.348MiB|80.348MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.116MiB|23.116MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.78MiB|22.78MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.536MiB|23.536MiB|0B| 0.0%|
|11.smt2                                                                                     |68.08MiB|68.08MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.98MiB|23.98MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.224MiB|23.224MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.704MiB|23.704MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.628MiB|25.628MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |92.6MiB|92.6MiB|0B| 0.0%|
|04.smt2                                                                                     |73.644MiB|73.644MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |28.332MiB|28.332MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.772MiB|30.772MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.392MiB|23.392MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.788MiB|23.788MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.312MiB|24.312MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.788MiB|24.788MiB|0B| 0.0%|
|107.smt2                                                                                    |22.296MiB|22.296MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.304MiB|27.304MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.348MiB|80.348MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.116MiB|23.116MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.78MiB|22.78MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.536MiB|23.536MiB|0B| 0.0%|
|11.smt2                                                                                     |68.08MiB|68.08MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.98MiB|23.98MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.224MiB|23.224MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.704MiB|23.704MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.628MiB|25.628MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |92.6MiB|92.6MiB|0B| 0.0%|
|04.smt2                                                                                     |73.644MiB|73.644MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |28.332MiB|28.332MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.772MiB|30.772MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.392MiB|23.392MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.788MiB|23.788MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.312MiB|24.312MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.788MiB|24.788MiB|0B| 0.0%|
|107.smt2                                                                                    |22.296MiB|22.296MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.304MiB|27.304MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.348MiB|80.348MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.116MiB|23.116MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.78MiB|22.78MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.536MiB|23.536MiB|0B| 0.0%|
|11.smt2                                                                                     |68.08MiB|68.08MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.98MiB|23.98MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.224MiB|23.224MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.704MiB|23.704MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.628MiB|25.628MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |92.6MiB|92.6MiB|0B| 0.0%|
|04.smt2                                                                                     |73.644MiB|73.644MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |28.332MiB|28.332MiB|0B| 0.0%|
|1010.smt2                                                                                   |30.772MiB|30.772MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.392MiB|23.392MiB|0B| 0.0%|
|1021.smt2                                                                                   |23.788MiB|23.788MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.312MiB|24.312MiB|0B| 0.0%|
|1063.smt2                                                                                   |24.788MiB|24.788MiB|0B| 0.0%|
|107.smt2                                                                                    |22.296MiB|22.296MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.304MiB|27.304MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.348MiB|80.348MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.116MiB|23.116MiB|0B| 0.0%|
|1090.smt2                                                                                   |22.78MiB|22.78MiB|0B| 0.0%|
|1092.smt2                                                                                   |23.536MiB|23.536MiB|0B| 0.0%|
|11.smt2                                                                                     |68.08MiB|68.08MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.98MiB|23.98MiB|0B| 0.0%|
|1112.smt2                                                                                   |23.224MiB|23.224MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.704MiB|23.704MiB|0B| 0.0%|
|1126.smt2                                                                                   |25.628MiB|25.628MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 599.715s |2685.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 599.782s |2643.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 599.829s |2430.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 600.166s |2122.0MiB|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                               | 599.416s |1842.0MiB|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                               | 599.684s |1726.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 599.036s |1714.0MiB|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                            | 600.301s |1703.0MiB|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 599.848s |1622.0MiB|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                               | 599.536s |1593.0MiB|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                            | 599.661s |1576.0MiB|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                           | 599.567s |1571.0MiB|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                           | 599.346s |1543.0MiB|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                       | 599.262s |1542.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                         | 599.241s |1522.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                         | 599.582s |1518.0MiB|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                         | 599.903s |1497.0MiB|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                 | 599.794s |1484.0MiB|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                            | 592.195s |1483.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        | 599.465s |1456.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 599.715s |2685.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 599.782s |2643.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 599.829s |2430.0MiB|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                       | 600.166s |2122.0MiB|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                               | 599.416s |1842.0MiB|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                               | 599.684s |1726.0MiB|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                               | 599.036s |1714.0MiB|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                            | 600.301s |1703.0MiB|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                  | 599.848s |1622.0MiB|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                               | 599.536s |1593.0MiB|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                            | 599.661s |1576.0MiB|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                           | 599.567s |1571.0MiB|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                           | 599.346s |1543.0MiB|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                       | 599.262s |1542.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                         | 599.241s |1522.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                         | 599.582s |1518.0MiB|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                         | 599.903s |1497.0MiB|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                 | 599.794s |1484.0MiB|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                            | 592.195s |1483.0MiB|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                        | 599.465s |1456.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 594.258s  | 594.258s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 599.680s  | 599.680s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.926s  |   1.926s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.419s  |   0.419s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 599.153s  | 599.153s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|124.smt2                                                                                    | 598.605s  | 598.605s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   1.391s  |   1.391s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.702s  |   0.702s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|140.smt2                                                                                    | 599.175s  | 599.175s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   1.848s  |   1.848s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   1.545s  |   1.545s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.907s  |   0.907s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   1.246s  |   1.246s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   6.255s  |   6.255s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   2.438s  |   2.438s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   1.882s  |   1.882s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|177.smt2                                                                                    | 599.094s  | 599.094s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   1.656s  |   1.656s  |   0.000s  | 0.0%|
|181.smt2                                                                                    | 599.208s  | 599.208s  |   0.000s  | 0.0%|
|182.smt2                                                                                    | 599.490s  | 599.490s  |   0.000s  | 0.0%|
|183.smt2                                                                                    | 599.242s  | 599.242s  |   0.000s  | 0.0%|
|185.smt2                                                                                    | 600.037s  | 600.037s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.641s  |   0.641s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   2.218s  |   2.218s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   1.468s  |   1.468s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   1.536s  |   1.536s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   2.473s  |   2.473s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   4.054s  |   4.054s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   5.596s  |   5.596s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   6.272s  |   6.272s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   2.167s  |   2.167s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   1.992s  |   1.992s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   1.806s  |   1.806s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   1.161s  |   1.161s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   1.149s  |   1.149s  |   0.000s  | 0.0%|
|35.smt2                                                                                     | 599.639s  | 599.639s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|40.smt2                                                                                     | 599.256s  | 599.256s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   1.832s  |   1.832s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   1.084s  |   1.084s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|54.smt2                                                                                     | 599.585s  | 599.585s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   1.460s  |   1.460s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   2.599s  |   2.599s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   1.808s  |   1.808s  |   0.000s  | 0.0%|
|58.smt2                                                                                     | 599.025s  | 599.025s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   1.529s  |   1.529s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   3.562s  |   3.562s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   5.293s  |   5.293s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|65.smt2                                                                                     | 599.471s  | 599.471s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   1.271s  |   1.271s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   5.421s  |   5.421s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|73.smt2                                                                                     | 598.461s  | 598.461s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   2.916s  |   2.916s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   1.201s  |   1.201s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   4.314s  |   4.314s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|966.smt2                                                                                    |   3.952s  |   3.952s  |   0.000s  | 0.0%|
|98.smt2                                                                                     | 599.745s  | 599.745s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|99.smt2                                                                                     | 598.992s  | 598.992s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  | 309.019s  | 309.019s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.603s  |   0.603s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   3.966s  |   3.966s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          | 599.299s  | 599.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               | 372.470s  | 372.470s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   1.171s  |   1.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    |  26.045s  |  26.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          | 269.955s  | 269.955s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |   8.808s  |   8.808s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   2.509s  |   2.509s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            | 599.835s  | 599.835s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   5.021s  |   5.021s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   4.053s  |   4.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       | 599.639s  | 599.639s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   3.523s  |   3.523s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          | 130.006s  | 130.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   4.867s  |   4.867s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |  82.307s  |  82.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   2.818s  |   2.818s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   1.625s  |   1.625s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           | 599.722s  | 599.722s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           | 350.970s  | 350.970s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         |   3.134s  |   3.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   5.742s  |   5.742s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |  17.162s  |  17.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   3.963s  |   3.963s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |   9.001s  |   9.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         | 599.086s  | 599.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             | 599.661s  | 599.661s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |  49.093s  |  49.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |  57.047s  |  57.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             | 599.274s  | 599.274s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 | 599.607s  | 599.607s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   2.543s  |   2.543s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   5.686s  |   5.686s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |   9.354s  |   9.354s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   2.086s  |   2.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              |  11.072s  |  11.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |  47.908s  |  47.908s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   1.429s  |   1.429s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |  11.057s  |  11.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               | 599.412s  | 599.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         | 599.058s  | 599.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   7.580s  |   7.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |  14.667s  |  14.667s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       | 599.549s  | 599.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 | 232.183s  | 232.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      | 599.635s  | 599.635s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   3.105s  |   3.105s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   4.316s  |   4.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              | 598.939s  | 598.939s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   3.291s  |   3.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |   4.825s  |   4.825s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          | 599.150s  | 599.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   1.561s  |   1.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          | 599.271s  | 599.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |   3.351s  |   3.351s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         |  77.059s  |  77.059s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   2.747s  |   2.747s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      | 599.188s  | 599.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |   2.870s  |   2.870s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |   4.052s  |   4.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |   5.119s  |   5.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         | 599.323s  | 599.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      | 599.789s  | 599.789s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               | 599.003s  | 599.003s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |  59.575s  |  59.575s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   | 136.779s  | 136.779s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |   6.138s  |   6.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           | 599.372s  | 599.372s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               | 434.832s  | 434.832s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   1.993s  |   1.993s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               |  78.838s  |  78.838s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |  20.702s  |  20.702s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   4.917s  |   4.917s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |  13.385s  |  13.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            |  23.538s  |  23.538s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |   8.434s  |   8.434s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   | 598.898s  | 598.898s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   | 599.790s  | 599.790s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   | 104.431s  | 104.431s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             | 599.931s  | 599.931s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |  13.188s  |  13.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   1.760s  |   1.760s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    | 600.003s  | 600.003s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |   6.082s  |   6.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        | 137.216s  | 137.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |  59.221s  |  59.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  67.567s  |  67.567s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     | 599.642s  | 599.642s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               | 598.919s  | 598.919s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               | 599.358s  | 599.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   6.658s  |   6.658s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   6.209s  |   6.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |   3.577s  |   3.577s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |  37.529s  |  37.529s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               | 598.695s  | 598.695s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   1.258s  |   1.258s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   4.582s  |   4.582s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   3.939s  |   3.939s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   3.495s  |   3.495s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   4.882s  |   4.882s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   6.633s  |   6.633s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                | 599.478s  | 599.478s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   1.286s  |   1.286s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              | 599.464s  | 599.464s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              | 101.616s  | 101.616s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   1.759s  |   1.759s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |   7.418s  |   7.418s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |  28.662s  |  28.662s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              | 122.741s  | 122.741s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   2.781s  |   2.781s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |  33.825s  |  33.825s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          | 280.632s  | 280.632s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          | 598.574s  | 598.574s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          | 599.903s  | 599.903s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |  10.005s  |  10.005s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          | 599.199s  | 599.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          | 599.849s  | 599.849s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |  42.322s  |  42.322s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   9.033s  |   9.033s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |  24.455s  |  24.455s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   4.065s  |   4.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    | 598.807s  | 598.807s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   3.754s  |   3.754s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   2.832s  |   2.832s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    | 599.631s  | 599.631s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   4.440s  |   4.440s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   4.196s  |   4.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |  26.084s  |  26.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        |  25.865s  |  25.865s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        | 599.350s  | 599.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        |   4.932s  |   4.932s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |  24.194s  |  24.194s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   6.271s  |   6.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        |  15.778s  |  15.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  55.433s  |  55.433s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |  69.993s  |  69.993s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  61.519s  |  61.519s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |  84.679s  |  84.679s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   | 101.067s  | 101.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              |  36.741s  |  36.741s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |  25.785s  |  25.785s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  | 160.428s  | 160.428s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  | 153.590s  | 153.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |  89.312s  |  89.312s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   1.830s  |   1.830s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.628s  |   0.628s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              | 599.423s  | 599.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   3.155s  |   3.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             |  57.196s  |  57.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |  10.737s  |  10.737s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   4.499s  |   4.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |  23.891s  |  23.891s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        | 154.054s  | 154.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.606s  |   0.606s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   3.307s  |   3.307s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             |  26.442s  |  26.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |   3.588s  |   3.588s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   | 599.423s  | 599.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   | 599.499s  | 599.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     | 599.579s  | 599.579s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   4.111s  |   4.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   2.606s  |   2.606s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   2.818s  |   2.818s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     | 599.294s  | 599.294s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 | 599.435s  | 599.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                |  66.232s  |  66.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   9.883s  |   9.883s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                | 599.437s  | 599.437s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      | 598.963s  | 598.963s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |  10.914s  |  10.914s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      | 599.318s  | 599.318s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      | 599.398s  | 599.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   7.790s  |   7.790s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      | 599.068s  | 599.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |  14.622s  |  14.622s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   0.876s  |   0.876s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   2.134s  |   2.134s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   4.856s  |   4.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   4.867s  |   4.867s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |  17.918s  |  17.918s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   5.383s  |   5.383s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   | 324.972s  | 324.972s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |  14.602s  |  14.602s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             |  17.472s  |  17.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |   5.820s  |   5.820s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          | 598.880s  | 598.880s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               | 600.011s  | 600.011s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                | 274.014s  | 274.014s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |   5.570s  |   5.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |  10.478s  |  10.478s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   1.874s  |   1.874s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   3.047s  |   3.047s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   3.874s  |   3.874s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   7.737s  |   7.737s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   1.344s  |   1.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              | 599.419s  | 599.419s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   8.397s  |   8.397s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   3.182s  |   3.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   8.222s  |   8.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   3.495s  |   3.495s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |  18.014s  |  18.014s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          | 599.287s  | 599.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |   5.451s  |   5.451s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          | 599.439s  | 599.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          | 600.183s  | 600.183s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |  14.299s  |  14.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          | 599.661s  | 599.661s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          | 599.326s  | 599.326s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |  15.905s  |  15.905s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          | 599.029s  | 599.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   6.601s  |   6.601s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            | 599.126s  | 599.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   5.003s  |   5.003s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |  24.162s  |  24.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |  14.872s  |  14.872s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            | 595.648s  | 595.648s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   1.890s  |   1.890s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |   6.692s  |   6.692s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           | 599.185s  | 599.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   2.322s  |   2.322s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |   3.511s  |   3.511s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   1.108s  |   1.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   3.026s  |   3.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |   6.622s  |   6.622s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   3.309s  |   3.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |   2.792s  |   2.792s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           | 144.918s  | 144.918s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                           | 599.171s  | 599.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           | 599.802s  | 599.802s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           | 302.252s  | 302.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   2.753s  |   2.753s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |   1.430s  |   1.430s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           | 599.622s  | 599.622s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   2.471s  |   2.471s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   2.263s  |   2.263s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           |   4.481s  |   4.481s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |  13.417s  |  13.417s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   1.412s  |   1.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           | 599.055s  | 599.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   2.301s  |   2.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |   1.176s  |   1.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           |  52.086s  |  52.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           |  22.793s  |  22.793s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           |   1.878s  |   1.878s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           | 103.046s  | 103.046s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           |  10.126s  |  10.126s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           | 599.804s  | 599.804s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |   1.349s  |   1.349s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   2.350s  |   2.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |  13.382s  |  13.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   2.148s  |   2.148s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           | 599.521s  | 599.521s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   2.209s  |   2.209s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |   6.017s  |   6.017s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |   3.458s  |   3.458s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |  53.907s  |  53.907s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   2.123s  |   2.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |  47.942s  |  47.942s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   2.217s  |   2.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           | 598.971s  | 598.971s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           | 235.266s  | 235.266s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           | 599.288s  | 599.288s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   2.275s  |   2.275s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           | 599.366s  | 599.366s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     | 592.635s  | 592.635s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   2.092s  |   2.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   1.774s  |   1.774s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     | 598.696s  | 598.696s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   2.631s  |   2.631s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     |   7.292s  |   7.292s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     | 114.872s  | 114.872s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   2.150s  |   2.150s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     |  23.268s  |  23.268s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     | 598.801s  | 598.801s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     | 116.179s  | 116.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     |  16.035s  |  16.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     |  11.987s  |  11.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     |   1.463s  |   1.463s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   1.417s  |   1.417s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |   6.162s  |   6.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   2.818s  |   2.818s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   3.152s  |   3.152s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   2.384s  |   2.384s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   2.680s  |   2.680s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |   4.750s  |   4.750s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |   5.326s  |   5.326s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     | 598.811s  | 598.811s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |   5.006s  |   5.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |  11.876s  |  11.876s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   1.427s  |   1.427s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   3.111s  |   3.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |   1.798s  |   1.798s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               | 596.005s  | 596.005s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     |  21.608s  |  21.608s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   2.553s  |   2.553s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     | 599.187s  | 599.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     |   6.688s  |   6.688s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |   4.006s  |   4.006s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   2.154s  |   2.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |  52.466s  |  52.466s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |  33.805s  |  33.805s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   3.640s  |   3.640s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |   0.489s  |   0.489s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |  12.835s  |  12.835s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |   8.154s  |   8.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     |   1.784s  |   1.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     | 102.974s  | 102.974s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     | 599.190s  | 599.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |  23.810s  |  23.810s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               |   5.854s  |   5.854s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               | 598.999s  | 598.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |   1.199s  |   1.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   2.322s  |   2.322s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               |  16.210s  |  16.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               | 599.477s  | 599.477s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |  16.023s  |  16.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               |   7.334s  |   7.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |   4.257s  |   4.257s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               | 599.721s  | 599.721s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               | 598.820s  | 598.820s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |  60.918s  |  60.918s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               | 599.492s  | 599.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               | 599.166s  | 599.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               | 599.472s  | 599.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               | 599.135s  | 599.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |  85.482s  |  85.482s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |   2.569s  |   2.569s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   2.177s  |   2.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  43.692s  |  43.692s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               | 599.460s  | 599.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   1.861s  |   1.861s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               | 599.391s  | 599.391s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   6.487s  |   6.487s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   1.411s  |   1.411s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               |   1.984s  |   1.984s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               | 599.264s  | 599.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               | 149.757s  | 149.757s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   0.863s  |   0.863s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   2.837s  |   2.837s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   6.283s  |   6.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   1.521s  |   1.521s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   1.419s  |   1.419s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               | 599.162s  | 599.162s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               | 156.769s  | 156.769s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   2.202s  |   2.202s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   3.373s  |   3.373s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               | 599.486s  | 599.486s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   8.558s  |   8.558s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               | 599.606s  | 599.606s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               | 599.158s  | 599.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   2.499s  |   2.499s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               | 126.308s  | 126.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |  22.043s  |  22.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |   7.522s  |   7.522s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   5.388s  |   5.388s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |   9.604s  |   9.604s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             | 599.338s  | 599.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   1.035s  |   1.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |  15.299s  |  15.299s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             | 599.447s  | 599.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             |   7.673s  |   7.673s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   2.340s  |   2.340s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   5.716s  |   5.716s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |   6.184s  |   6.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   2.196s  |   2.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |   2.392s  |   2.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |  16.616s  |  16.616s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             |   1.905s  |   1.905s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |  15.923s  |  15.923s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   2.864s  |   2.864s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             | 599.510s  | 599.510s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |  24.874s  |  24.874s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             |   1.175s  |   1.175s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   5.168s  |   5.168s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.821s  |   0.821s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   2.199s  |   2.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             | 599.846s  | 599.846s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   2.199s  |   2.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             | 598.999s  | 598.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             |  37.316s  |  37.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |   2.379s  |   2.379s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |  13.420s  |  13.420s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             |  38.958s  |  38.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   1.373s  |   1.373s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |   8.000s  |   8.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |  12.137s  |  12.137s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             | 599.704s  | 599.704s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   5.681s  |   5.681s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             | 599.085s  | 599.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             | 599.024s  | 599.024s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             | 599.315s  | 599.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |   1.007s  |   1.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             | 599.509s  | 599.509s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   0.885s  |   0.885s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             | 599.358s  | 599.358s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |  60.364s  |  60.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |  66.582s  |  66.582s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               | 599.847s  | 599.847s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |   9.252s  |   9.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |   8.050s  |   8.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         | 511.325s  | 511.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        | 206.007s  | 206.007s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              |  62.203s  |  62.203s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   1.277s  |   1.277s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   2.193s  |   2.193s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |   0.839s  |   0.839s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   1.730s  |   1.730s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    | 599.043s  | 599.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |   1.542s  |   1.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |   8.596s  |   8.596s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   2.171s  |   2.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |   2.434s  |   2.434s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   8.164s  |   8.164s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |  85.589s  |  85.589s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    | 599.522s  | 599.522s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   2.176s  |   2.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    | 599.747s  | 599.747s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   5.287s  |   5.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   2.211s  |   2.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   2.542s  |   2.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    | 599.089s  | 599.089s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    | 599.386s  | 599.386s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    | 598.912s  | 598.912s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   2.302s  |   2.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   2.552s  |   2.552s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |  55.297s  |  55.297s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   1.984s  |   1.984s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    | 599.421s  | 599.421s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |  30.991s  |  30.991s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    | 599.446s  | 599.446s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   1.022s  |   1.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |  13.207s  |  13.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              |  75.731s  |  75.731s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    |  20.397s  |  20.397s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   2.349s  |   2.349s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    | 598.861s  | 598.861s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    |  47.616s  |  47.616s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |  20.244s  |  20.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   2.218s  |   2.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    | 599.364s  | 599.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   3.405s  |   3.405s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    | 599.078s  | 599.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    | 599.208s  | 599.208s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    |   7.613s  |   7.613s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   2.405s  |   2.405s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |   6.214s  |   6.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    |  13.171s  |  13.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   1.235s  |   1.235s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   2.222s  |   2.222s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |  12.746s  |  12.746s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   2.389s  |   2.389s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          | 599.710s  | 599.710s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |   2.782s  |   2.782s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          | 599.645s  | 599.645s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |   8.719s  |   8.719s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2          | 599.373s  | 599.373s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |  22.752s  |  22.752s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          | 599.314s  | 599.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |  13.536s  |  13.536s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          | 598.288s  | 598.288s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   8.250s  |   8.250s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          | 598.951s  | 598.951s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |   6.362s  |   6.362s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |   6.796s  |   6.796s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   2.385s  |   2.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   2.166s  |   2.166s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          | 599.259s  | 599.259s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          | 599.400s  | 599.400s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   1.556s  |   1.556s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   1.763s  |   1.763s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          | 599.334s  | 599.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   6.018s  |   6.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   2.285s  |   2.285s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |   5.769s  |   5.769s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        | 599.506s  | 599.506s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   8.515s  |   8.515s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        | 599.304s  | 599.304s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |   7.146s  |   7.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |  17.596s  |  17.596s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |  14.314s  |  14.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |   1.669s  |   1.669s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |   9.812s  |   9.812s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |  43.437s  |  43.437s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   2.305s  |   2.305s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |  11.541s  |  11.541s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   2.906s  |   2.906s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        | 599.503s  | 599.503s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |   1.489s  |   1.489s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |   6.023s  |   6.023s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   0.944s  |   0.944s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |   3.543s  |   3.543s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   2.445s  |   2.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   7.411s  |   7.411s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |   1.545s  |   1.545s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   2.370s  |   2.370s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        | 599.474s  | 599.474s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   2.192s  |   2.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        | 599.450s  | 599.450s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        | 599.259s  | 599.259s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        | 109.420s  | 109.420s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   2.321s  |   2.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |  15.620s  |  15.620s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   2.316s  |   2.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        | 599.133s  | 599.133s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        | 599.583s  | 599.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        | 598.826s  | 598.826s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |   5.942s  |   5.942s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   2.344s  |   2.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |  53.405s  |  53.405s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        |  11.387s  |  11.387s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        | 599.227s  | 599.227s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |   7.893s  |   7.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        | 599.364s  | 599.364s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |   5.365s  |   5.365s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  | 598.908s  | 598.908s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   0.558s  |   0.558s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   2.196s  |   2.196s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |   6.214s  |   6.214s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |   6.260s  |   6.260s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                     |  15.265s  |  15.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     |   2.141s  |   2.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   8.425s  |   8.425s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |  31.621s  |  31.621s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   1.302s  |   1.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     | 598.784s  | 598.784s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |   9.799s  |   9.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   0.604s  |   0.604s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   2.165s  |   2.165s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |   3.284s  |   3.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     | 599.108s  | 599.108s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     | 599.725s  | 599.725s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     | 599.127s  | 599.127s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |   3.321s  |   3.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |  15.564s  |  15.564s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   6.400s  |   6.400s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       | 599.497s  | 599.497s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |   6.953s  |   6.953s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |   9.583s  |   9.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |   3.045s  |   3.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |  35.799s  |  35.799s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       |  15.803s  |  15.803s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       | 598.490s  | 598.490s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   4.445s  |   4.445s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |  91.535s  |  91.535s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       | 598.964s  | 598.964s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   2.406s  |   2.406s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   3.083s  |   3.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   2.170s  |   2.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |   2.611s  |   2.611s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       | 599.098s  | 599.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       | 599.650s  | 599.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 | 234.690s  | 234.690s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   2.437s  |   2.437s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   1.480s  |   1.480s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   2.620s  |   2.620s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       | 599.277s  | 599.277s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       | 599.020s  | 599.020s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |  27.391s  |  27.391s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 | 599.469s  | 599.469s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |  62.583s  |  62.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |  19.487s  |  19.487s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  59.107s  |  59.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |  11.381s  |  11.381s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |  10.994s  |  10.994s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |  15.656s  |  15.656s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   1.334s  |   1.334s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            | 599.070s  | 599.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  92.648s  |  92.648s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |  10.103s  |  10.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            | 153.800s  | 153.800s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |  15.828s  |  15.828s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   1.605s  |   1.605s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  | 598.738s  | 598.738s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            | 324.581s  | 324.581s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   2.769s  |   2.769s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |   3.791s  |   3.791s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   3.030s  |   3.030s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   3.668s  |   3.668s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   2.634s  |   2.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   3.146s  |   3.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   2.709s  |   2.709s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |  23.828s  |  23.828s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |   3.138s  |   3.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   4.300s  |   4.300s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   3.253s  |   3.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   1.456s  |   1.456s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |   8.909s  |   8.909s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   2.553s  |   2.553s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   4.940s  |   4.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   5.339s  |   5.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   9.044s  |   9.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |  14.661s  |  14.661s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |  21.524s  |  21.524s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                |  46.877s  |  46.877s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   1.441s  |   1.441s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |   2.583s  |   2.583s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   3.525s  |   3.525s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   4.172s  |   4.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   4.055s  |   4.055s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  16.130s  |  16.130s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   8.582s  |   8.582s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |  38.311s  |  38.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |   8.350s  |   8.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   5.375s  |   5.375s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |  19.090s  |  19.090s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  31.893s  |  31.893s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   2.570s  |   2.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   1.460s  |   1.460s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   2.456s  |   2.456s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |  33.482s  |  33.482s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   3.440s  |   3.440s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   2.392s  |   2.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   1.703s  |   1.703s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   4.074s  |   4.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   3.400s  |   3.400s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |   8.972s  |   8.972s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   1.271s  |   1.271s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   1.443s  |   1.443s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   3.944s  |   3.944s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |   3.261s  |   3.261s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |   3.767s  |   3.767s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   3.699s  |   3.699s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   3.243s  |   3.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   3.674s  |   3.674s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   3.538s  |   3.538s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   2.121s  |   2.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   2.244s  |   2.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |  22.205s  |  22.205s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   3.123s  |   3.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   3.557s  |   3.557s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                |  17.470s  |  17.470s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   0.945s  |   0.945s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |  15.720s  |  15.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   2.373s  |   2.373s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |   9.253s  |   9.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |   2.782s  |   2.782s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  16.604s  |  16.604s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |  10.965s  |  10.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                |   1.947s  |   1.947s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   5.387s  |   5.387s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |  74.492s  |  74.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   3.027s  |   3.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   1.919s  |   1.919s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   3.997s  |   3.997s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   7.361s  |   7.361s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                |  12.896s  |  12.896s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   5.716s  |   5.716s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |   2.573s  |   2.573s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |   4.543s  |   4.543s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |  21.324s  |  21.324s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |  11.727s  |  11.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |   7.621s  |   7.621s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   2.841s  |   2.841s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |   9.737s  |   9.737s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   3.385s  |   3.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   8.558s  |   8.558s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   2.770s  |   2.770s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2                |  27.442s  |  27.442s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |  21.742s  |  21.742s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |  21.697s  |  21.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   1.586s  |   1.586s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                | 116.934s  | 116.934s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  34.651s  |  34.651s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   3.199s  |   3.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   1.984s  |   1.984s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   3.650s  |   3.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |   2.596s  |   2.596s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   3.250s  |   3.250s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   2.050s  |   2.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |  69.177s  |  69.177s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   3.142s  |   3.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |  10.605s  |  10.605s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   1.333s  |   1.333s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |   2.285s  |   2.285s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   2.683s  |   2.683s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   2.556s  |   2.556s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |   3.101s  |   3.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   2.241s  |   2.241s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                |  15.001s  |  15.001s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |  12.426s  |  12.426s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   3.677s  |   3.677s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   2.810s  |   2.810s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   3.690s  |   3.690s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   1.749s  |   1.749s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   5.074s  |   5.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   7.917s  |   7.917s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |   2.944s  |   2.944s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |  11.158s  |  11.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |  11.344s  |  11.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |  14.924s  |  14.924s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |   7.454s  |   7.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   2.732s  |   2.732s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   7.629s  |   7.629s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   7.641s  |   7.641s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          | 317.378s  | 317.378s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          | 249.844s  | 249.844s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          | 598.857s  | 598.857s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   7.142s  |   7.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   7.563s  |   7.563s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             | 598.658s  | 598.658s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            | 599.527s  | 599.527s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            | 599.453s  | 599.453s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   4.255s  |   4.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   2.810s  |   2.810s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   2.598s  |   2.598s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   4.861s  |   4.861s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    |  16.123s  |  16.123s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   5.298s  |   5.298s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       | 134.908s  | 134.908s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |   3.351s  |   3.351s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      | 599.621s  | 599.621s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   7.890s  |   7.890s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   5.766s  |   5.766s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   1.228s  |   1.228s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |   4.395s  |   4.395s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   4.385s  |   4.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       |  39.342s  |  39.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |   9.676s  |   9.676s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   2.077s  |   2.077s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   1.220s  |   1.220s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   5.390s  |   5.390s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   | 599.091s  | 599.091s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |  12.757s  |  12.757s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |   3.212s  |   3.212s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |  10.014s  |  10.014s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.869s  |   0.869s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               |  40.694s  |  40.694s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               |  51.267s  |  51.267s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |  11.217s  |  11.217s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   4.701s  |   4.701s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          | 598.374s  | 598.374s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          | 599.409s  | 599.409s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   1.637s  |   1.637s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   1.244s  |   1.244s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               |  44.077s  |  44.077s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               | 599.506s  | 599.506s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  22.386s  |  22.386s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               | 599.127s  | 599.127s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               | 598.346s  | 598.346s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |  11.171s  |  11.171s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         | 599.413s  | 599.413s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         | 599.935s  | 599.935s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         | 353.640s  | 353.640s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2                               |   7.022s  |   7.022s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               | 599.303s  | 599.303s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  84.748s  |  84.748s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |  10.781s  |  10.781s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         | 598.990s  | 598.990s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         | 599.568s  | 599.568s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |  18.300s  |  18.300s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         | 597.815s  | 597.815s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |  28.897s  |  28.897s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  76.030s  |  76.030s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    | 599.051s  | 599.051s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  28.209s  |  28.209s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                    | 599.423s  | 599.423s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |  14.692s  |  14.692s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |   3.520s  |   3.520s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   2.332s  |   2.332s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              | 599.010s  | 599.010s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   | 268.273s  | 268.273s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |   4.989s  |   4.989s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |   5.942s  |   5.942s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |  28.566s  |  28.566s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |   7.923s  |   7.923s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |  11.206s  |  11.206s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |   5.576s  |   5.576s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   2.870s  |   2.870s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |   4.568s  |   4.568s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   2.993s  |   2.993s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  | 599.794s  | 599.794s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   3.797s  |   3.797s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  53.453s  |  53.453s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 | 599.417s  | 599.417s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 | 598.991s  | 598.991s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |  14.208s  |  14.208s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           | 599.265s  | 599.265s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |   3.984s  |   3.984s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              | 598.783s  | 598.783s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              | 599.360s  | 599.360s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |   4.025s  |   4.025s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              | 598.896s  | 598.896s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              | 599.256s  | 599.256s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |  18.546s  |  18.546s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              | 598.059s  | 598.059s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              | 599.471s  | 599.471s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |  32.395s  |  32.395s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              | 598.888s  | 598.888s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              | 598.560s  | 598.560s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   3.515s  |   3.515s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |  42.136s  |  42.136s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |  43.170s  |  43.170s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |  15.022s  |  15.022s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      | 288.064s  | 288.064s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     | 128.283s  | 128.283s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          | 111.229s  | 111.229s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  44.706s  |  44.706s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  67.087s  |  67.087s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            |  58.835s  |  58.835s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             |   3.330s  |   3.330s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             | 599.422s  | 599.422s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   2.559s  |   2.559s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             | 599.257s  | 599.257s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             | 599.643s  | 599.643s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   1.840s  |   1.840s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             | 599.201s  | 599.201s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             | 599.758s  | 599.758s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   2.420s  |   2.420s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 | 599.466s  | 599.466s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   0.729s  |   0.729s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  | 599.161s  | 599.161s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |  16.691s  |  16.691s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |   4.207s  |   4.207s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             | 599.355s  | 599.355s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   2.329s  |   2.329s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   4.454s  |   4.454s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |  12.446s  |  12.446s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   3.997s  |   3.997s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |  15.607s  |  15.607s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   2.348s  |   2.348s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             | 599.176s  | 599.176s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   2.688s  |   2.688s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   8.800s  |   8.800s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   4.273s  |   4.273s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   1.450s  |   1.450s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |   4.941s  |   4.941s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   1.931s  |   1.931s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |   4.813s  |   4.813s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               | 599.829s  | 599.829s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   1.957s  |   1.957s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            | 598.807s  | 598.807s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   1.466s  |   1.466s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 | 599.271s  | 599.271s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |  15.114s  |  15.114s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  27.394s  |  27.394s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |  10.502s  |  10.502s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           | 599.126s  | 599.126s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |  13.439s  |  13.439s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |  15.660s  |  15.660s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 | 598.557s  | 598.557s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      | 302.126s  | 302.126s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |   9.875s  |   9.875s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |  15.496s  |  15.496s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           | 598.867s  | 598.867s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  22.042s  |  22.042s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |  10.197s  |  10.197s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  25.917s  |  25.917s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              | 599.826s  | 599.826s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    |   4.019s  |   4.019s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   5.314s  |   5.314s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   4.103s  |   4.103s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      | 346.581s  | 346.581s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               | 599.446s  | 599.446s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              | 598.988s  | 598.988s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   2.415s  |   2.415s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       | 599.405s  | 599.405s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |   4.925s  |   4.925s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   1.840s  |   1.840s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       | 134.559s  | 134.559s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   1.322s  |   1.322s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       | 599.736s  | 599.736s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       |   2.535s  |   2.535s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       | 599.655s  | 599.655s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   0.966s  |   0.966s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |   3.734s  |   3.734s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |  19.069s  |  19.069s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |  32.644s  |  32.644s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       | 599.438s  | 599.438s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       |  16.895s  |  16.895s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       | 599.259s  | 599.259s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |   7.513s  |   7.513s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   3.300s  |   3.300s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       | 111.195s  | 111.195s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |   3.997s  |   3.997s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   1.056s  |   1.056s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   2.442s  |   2.442s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       |  79.294s  |  79.294s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       | 139.504s  | 139.504s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   9.752s  |   9.752s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |   1.836s  |   1.836s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       | 397.604s  | 397.604s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       |   2.734s  |   2.734s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   1.391s  |   1.391s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.678s  |   0.678s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               | 457.115s  | 457.115s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         | 594.394s  | 594.394s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   3.536s  |   3.536s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   0.495s  |   0.495s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   3.407s  |   3.407s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   1.140s  |   1.140s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 | 599.754s  | 599.754s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   1.226s  |   1.226s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |  12.732s  |  12.732s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |  10.451s  |  10.451s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |   8.768s  |   8.768s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   3.421s  |   3.421s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   4.471s  |   4.471s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                | 595.434s  | 595.434s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   1.170s  |   1.170s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   4.473s  |   4.473s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                | 599.411s  | 599.411s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   2.773s  |   2.773s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |  30.905s  |  30.905s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   2.938s  |   2.938s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      | 599.908s  | 599.908s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   2.244s  |   2.244s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   3.426s  |   3.426s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |   7.861s  |   7.861s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   3.225s  |   3.225s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |  14.508s  |  14.508s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   1.078s  |   1.078s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   2.182s  |   2.182s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   1.477s  |   1.477s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   1.703s  |   1.703s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |  96.118s  |  96.118s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   4.242s  |   4.242s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   7.486s  |   7.486s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   1.975s  |   1.975s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |  26.799s  |  26.799s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.395s  |   0.395s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   2.995s  |   2.995s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      | 599.213s  | 599.213s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   2.022s  |   2.022s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      | 599.663s  | 599.663s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   4.370s  |   4.370s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   9.023s  |   9.023s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   2.880s  |   2.880s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   1.779s  |   1.779s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   2.749s  |   2.749s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |   8.402s  |   8.402s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   3.019s  |   3.019s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   5.467s  |   5.467s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   4.748s  |   4.748s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   1.407s  |   1.407s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |   1.840s  |   1.840s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   4.497s  |   4.497s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      | 598.727s  | 598.727s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      |   8.793s  |   8.793s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   4.409s  |   4.409s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   3.392s  |   3.392s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      |   5.035s  |   5.035s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   3.605s  |   3.605s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   2.348s  |   2.348s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |   9.975s  |   9.975s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      |   8.631s  |   8.631s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   1.677s  |   1.677s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   8.038s  |   8.038s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   1.416s  |   1.416s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      | 598.818s  | 598.818s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   0.865s  |   0.865s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      | 599.438s  | 599.438s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   2.720s  |   2.720s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   4.504s  |   4.504s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      |  10.291s  |  10.291s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   3.089s  |   3.089s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      | 596.254s  | 596.254s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   6.899s  |   6.899s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   3.486s  |   3.486s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      |  22.892s  |  22.892s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |   3.065s  |   3.065s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   5.987s  |   5.987s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   0.747s  |   0.747s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   4.867s  |   4.867s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   2.805s  |   2.805s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   6.698s  |   6.698s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   3.101s  |   3.101s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   3.387s  |   3.387s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   3.922s  |   3.922s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   8.039s  |   8.039s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   2.604s  |   2.604s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   2.949s  |   2.949s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   2.089s  |   2.089s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   2.328s  |   2.328s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |   9.868s  |   9.868s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |   9.003s  |   9.003s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   2.052s  |   2.052s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   9.321s  |   9.321s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   2.876s  |   2.876s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   2.720s  |   2.720s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   9.486s  |   9.486s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |  12.474s  |  12.474s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   5.748s  |   5.748s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |  13.669s  |  13.669s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            | 599.346s  | 599.346s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |  16.268s  |  16.268s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  56.739s  |  56.739s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |  33.869s  |  33.869s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |  26.104s  |  26.104s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |  25.980s  |  25.980s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                        | 599.199s  | 599.199s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        | 600.166s  | 600.166s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |  35.524s  |  35.524s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       |  25.412s  |  25.412s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |   6.527s  |   6.527s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   4.524s  |   4.524s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     | 599.408s  | 599.408s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     | 598.966s  | 598.966s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     | 599.109s  | 599.109s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |  14.384s  |  14.384s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2                         | 599.247s  | 599.247s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               | 599.873s  | 599.873s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         | 599.359s  | 599.359s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               | 598.698s  | 598.698s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   2.753s  |   2.753s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |  15.910s  |  15.910s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               | 599.859s  | 599.859s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  | 598.922s  | 598.922s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  | 106.157s  | 106.157s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     |  84.527s  |  84.527s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |  50.290s  |  50.290s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  15.697s  |  15.697s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            | 227.088s  | 227.088s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            | 599.290s  | 599.290s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   4.152s  |   4.152s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   1.946s  |   1.946s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                | 599.349s  | 599.349s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   2.123s  |   2.123s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 |  47.705s  |  47.705s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 | 315.470s  | 315.470s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 | 598.918s  | 598.918s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  38.305s  |  38.305s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 | 600.017s  | 600.017s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |  21.075s  |  21.075s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |  60.617s  |  60.617s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           | 598.966s  | 598.966s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           | 599.362s  | 599.362s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           | 205.596s  | 205.596s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |  34.483s  |  34.483s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |  55.301s  |  55.301s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 | 165.827s  | 165.827s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   5.253s  |   5.253s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |  26.878s  |  26.878s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                                                 | 599.195s  | 599.195s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  52.422s  |  52.422s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 | 368.248s  | 368.248s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   3.949s  |   3.949s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 | 186.298s  | 186.298s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 | 599.715s  | 599.715s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |  34.285s  |  34.285s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  32.055s  |  32.055s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 | 109.090s  | 109.090s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   5.861s  |   5.861s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 | 451.393s  | 451.393s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |  16.846s  |  16.846s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |  22.999s  |  22.999s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 | 169.787s  | 169.787s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   6.692s  |   6.692s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |   9.835s  |   9.835s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 | 598.989s  | 598.989s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  40.839s  |  40.839s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |   9.120s  |   9.120s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 | 113.721s  | 113.721s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 | 165.543s  | 165.543s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |   6.298s  |   6.298s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |   6.002s  |   6.002s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 | 599.662s  | 599.662s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |   3.332s  |   3.332s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 | 156.576s  | 156.576s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   1.790s  |   1.790s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 | 167.526s  | 167.526s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |   6.007s  |   6.007s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |   9.199s  |   9.199s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   6.047s  |   6.047s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |   3.373s  |   3.373s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              | 599.462s  | 599.462s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |  27.678s  |  27.678s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 |  65.633s  |  65.633s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 |  76.826s  |  76.826s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 | 107.371s  | 107.371s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |  19.739s  |  19.739s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        | 599.001s  | 599.001s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |  43.058s  |  43.058s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  33.022s  |  33.022s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           |  73.742s  |  73.742s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           | 236.863s  | 236.863s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    | 599.343s  | 599.343s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    | 599.726s  | 599.726s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       | 107.756s  | 107.756s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       |  68.745s  |  68.745s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  50.371s  |  50.371s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       |  75.584s  |  75.584s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |  10.395s  |  10.395s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              | 599.449s  | 599.449s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 |  72.032s  |  72.032s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |  18.715s  |  18.715s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |  69.546s  |  69.546s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  57.161s  |  57.161s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |  26.556s  |  26.556s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  | 599.602s  | 599.602s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     |  47.852s  |  47.852s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  34.804s  |  34.804s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |   4.247s  |   4.247s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |  60.015s  |  60.015s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     |  45.538s  |  45.538s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  53.080s  |  53.080s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            | 599.728s  | 599.728s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          | 148.626s  | 148.626s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  39.588s  |  39.588s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  25.779s  |  25.779s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  55.023s  |  55.023s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               |  64.783s  |  64.783s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   3.018s  |   3.018s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |  12.359s  |  12.359s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        | 600.023s  | 600.023s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        | 599.848s  | 599.848s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |   4.985s  |   4.985s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        |   3.196s  |   3.196s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        | 599.319s  | 599.319s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        | 480.494s  | 480.494s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        | 599.187s  | 599.187s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        | 599.448s  | 599.448s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        | 489.367s  | 489.367s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  | 598.873s  | 598.873s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   1.692s  |   1.692s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     |  18.011s  |  18.011s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   2.327s  |   2.327s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |   5.236s  |   5.236s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |  56.252s  |  56.252s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 | 599.525s  | 599.525s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   3.984s  |   3.984s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 | 598.652s  | 598.652s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 | 598.632s  | 598.632s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |  21.988s  |  21.988s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 | 599.391s  | 599.391s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 | 599.766s  | 599.766s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |  10.236s  |  10.236s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   7.465s  |   7.465s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   3.318s  |   3.318s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |  28.174s  |  28.174s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |  16.179s  |  16.179s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             | 377.126s  | 377.126s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             | 592.195s  | 592.195s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   9.144s  |   9.144s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             | 599.606s  | 599.606s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             | 598.882s  | 598.882s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |   8.786s  |   8.786s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             | 239.475s  | 239.475s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             | 599.481s  | 599.481s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |   6.303s  |   6.303s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             | 317.283s  | 317.283s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             | 598.458s  | 598.458s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |  19.949s  |  19.949s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             | 598.921s  | 598.921s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             | 600.301s  | 600.301s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   6.175s  |   6.175s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   3.585s  |   3.585s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  | 141.541s  | 141.541s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   4.637s  |   4.637s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                | 599.407s  | 599.407s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   0.970s  |   0.970s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |  11.963s  |  11.963s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           | 599.562s  | 599.562s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 | 599.029s  | 599.029s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   3.759s  |   3.759s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 | 599.909s  | 599.909s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 | 598.775s  | 598.775s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   2.505s  |   2.505s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 | 599.325s  | 599.325s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 | 599.314s  | 599.314s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   2.220s  |   2.220s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           | 598.508s  | 598.508s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |   5.156s  |   5.156s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 | 598.265s  | 598.265s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 | 599.456s  | 599.456s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           | 598.858s  | 598.858s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  | 389.291s  | 389.291s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |  12.105s  |  12.105s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 | 598.746s  | 598.746s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 | 599.399s  | 599.399s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   2.772s  |   2.772s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   3.717s  |   3.717s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |   5.474s  |   5.474s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 | 599.020s  | 599.020s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   3.016s  |   3.016s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 | 599.433s  | 599.433s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 | 598.672s  | 598.672s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   3.842s  |   3.842s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 | 598.789s  | 598.789s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   5.488s  |   5.488s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |   5.862s  |   5.862s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  | 130.443s  | 130.443s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   9.985s  |   9.985s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |  13.573s  |  13.573s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            |  33.940s  |  33.940s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  73.147s  |  73.147s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   1.966s  |   1.966s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  | 599.647s  | 599.647s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   2.040s  |   2.040s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  | 599.106s  | 599.106s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  |  71.353s  |  71.353s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            | 599.532s  | 599.532s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   2.220s  |   2.220s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 | 599.487s  | 599.487s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  |  26.222s  |  26.222s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  | 598.970s  | 598.970s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   2.879s  |   2.879s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  | 599.093s  | 599.093s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  | 599.652s  | 599.652s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   2.740s  |   2.740s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  | 599.438s  | 599.438s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  | 599.034s  | 599.034s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |   2.016s  |   2.016s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  | 599.158s  | 599.158s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  | 599.344s  | 599.344s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |  90.809s  |  90.809s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            | 599.192s  | 599.192s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   2.938s  |   2.938s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |  12.617s  |  12.617s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   1.544s  |   1.544s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |   8.754s  |   8.754s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           | 599.387s  | 599.387s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           | 599.295s  | 599.295s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           | 599.562s  | 599.562s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |  77.545s  |  77.545s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               | 119.325s  | 119.325s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               | 598.442s  | 598.442s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               | 286.556s  | 286.556s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               | 599.974s  | 599.974s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               | 599.305s  | 599.305s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |  23.932s  |  23.932s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   |  98.545s  |  98.545s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 | 257.258s  | 257.258s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |  13.916s  |  13.916s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   3.806s  |   3.806s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   2.419s  |   2.419s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             | 599.402s  | 599.402s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |   5.056s  |   5.056s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   5.242s  |   5.242s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |  10.321s  |  10.321s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |  11.363s  |  11.363s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   4.892s  |   4.892s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |  95.451s  |  95.451s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |  29.035s  |  29.035s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |  32.301s  |  32.301s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            | 599.884s  | 599.884s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    | 586.666s  | 586.666s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   7.490s  |   7.490s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               | 599.914s  | 599.914s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             | 599.803s  | 599.803s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             | 599.122s  | 599.122s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             | 599.703s  | 599.703s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   4.657s  |   4.657s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             | 599.310s  | 599.310s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             | 599.569s  | 599.569s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   8.856s  |   8.856s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             | 599.534s  | 599.534s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             | 598.747s  | 598.747s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |  26.754s  |  26.754s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |   7.703s  |   7.703s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               | 417.637s  | 417.637s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         | 599.465s  | 599.465s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |  14.668s  |  14.668s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |  18.353s  |  18.353s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |  18.557s  |  18.557s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  44.922s  |  44.922s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        | 599.259s  | 599.259s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   0.769s  |   0.769s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            | 338.293s  | 338.293s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            | 599.700s  | 599.700s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   8.108s  |   8.108s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |   5.317s  |   5.317s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   5.426s  |   5.426s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            |  94.189s  |  94.189s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   3.219s  |   3.219s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |  19.658s  |  19.658s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              | 599.032s  | 599.032s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              |  13.204s  |  13.204s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              | 599.145s  | 599.145s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   2.743s  |   2.743s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |  24.271s  |  24.271s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          | 596.677s  | 596.677s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   2.857s  |   2.857s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |  32.596s  |  32.596s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |  19.286s  |  19.286s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       | 598.940s  | 598.940s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   2.692s  |   2.692s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       |  22.375s  |  22.375s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   5.381s  |   5.381s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   3.352s  |   3.352s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |   6.608s  |   6.608s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         | 576.227s  | 576.227s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |  16.175s  |  16.175s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           | 599.512s  | 599.512s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |   3.932s  |   3.932s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  | 599.403s  | 599.403s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            | 598.264s  | 598.264s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              | 346.956s  | 346.956s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   4.733s  |   4.733s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |  13.651s  |  13.651s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |  10.088s  |  10.088s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          | 599.160s  | 599.160s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                          | 599.663s  | 599.663s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |  25.354s  |  25.354s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          | 598.981s  | 598.981s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          | 599.241s  | 599.241s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |  14.416s  |  14.416s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          | 599.582s  | 599.582s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          | 599.715s  | 599.715s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |  15.680s  |  15.680s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                | 599.684s  | 599.684s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                                                | 599.438s  | 599.438s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |   9.137s  |   9.137s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                | 599.416s  | 599.416s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                                | 599.713s  | 599.713s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |  10.068s  |  10.068s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                | 599.536s  | 599.536s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                | 599.526s  | 599.526s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |  15.128s  |  15.128s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                | 599.452s  | 599.452s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                | 599.036s  | 599.036s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          | 599.500s  | 599.500s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |  21.178s  |  21.178s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          | 599.609s  | 599.609s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |   9.160s  |   9.160s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |  17.852s  |  17.852s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          | 599.532s  | 599.532s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                |  31.515s  |  31.515s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                | 599.473s  | 599.473s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   9.122s  |   9.122s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |  11.783s  |  11.783s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |   9.869s  |   9.869s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   5.125s  |   5.125s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   5.338s  |   5.338s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                |  46.958s  |  46.958s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                |  22.426s  |  22.426s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   0.941s  |   0.941s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                | 599.154s  | 599.154s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                |   8.633s  |   8.633s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                | 599.201s  | 599.201s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                |   8.009s  |   8.009s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                |   4.443s  |   4.443s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |  51.346s  |  51.346s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   6.296s  |   6.296s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                | 599.630s  | 599.630s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   6.381s  |   6.381s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |  14.313s  |  14.313s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   2.444s  |   2.444s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                | 599.161s  | 599.161s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |  10.260s  |  10.260s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                |  41.360s  |  41.360s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   4.152s  |   4.152s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |  10.787s  |  10.787s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   8.061s  |   8.061s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                |  12.852s  |  12.852s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   6.291s  |   6.291s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                | 599.456s  | 599.456s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   2.781s  |   2.781s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   1.087s  |   1.087s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |  13.692s  |  13.692s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                | 599.375s  | 599.375s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                | 599.681s  | 599.681s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |  19.948s  |  19.948s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |  14.302s  |  14.302s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   4.973s  |   4.973s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          |  14.703s  |  14.703s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          | 599.242s  | 599.242s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          | 593.007s  | 593.007s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   2.879s  |   2.879s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   3.268s  |   3.268s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |   2.141s  |   2.141s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   7.859s  |   7.859s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |  10.343s  |  10.343s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          |  23.629s  |  23.629s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   2.741s  |   2.741s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   2.462s  |   2.462s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |  11.322s  |  11.322s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          |   8.847s  |   8.847s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          | 599.526s  | 599.526s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |  11.352s  |  11.352s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   1.668s  |   1.668s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   8.261s  |   8.261s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |   7.537s  |   7.537s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |   2.383s  |   2.383s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          |   4.358s  |   4.358s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |  10.954s  |  10.954s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |  14.093s  |  14.093s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          | 599.402s  | 599.402s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          | 599.558s  | 599.558s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          | 599.118s  | 599.118s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          | 599.399s  | 599.399s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |  10.919s  |  10.919s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   2.398s  |   2.398s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          | 104.266s  | 104.266s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |  62.802s  |  62.802s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     | 137.673s  | 137.673s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           |  38.573s  |  38.573s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           | 599.193s  | 599.193s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           | 598.779s  | 598.779s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   2.729s  |   2.729s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  |  77.641s  |  77.641s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   5.810s  |   5.810s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   1.731s  |   1.731s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        | 599.340s  | 599.340s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   4.832s  |   4.832s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        |   9.533s  |   9.533s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        |   4.690s  |   4.690s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   5.156s  |   5.156s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        |  35.922s  |  35.922s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   1.459s  |   1.459s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |  11.265s  |  11.265s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        | 599.812s  | 599.812s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        |   9.010s  |   9.010s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        |  29.499s  |  29.499s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |  13.689s  |  13.689s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        |  20.983s  |  20.983s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |  20.309s  |  20.309s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   2.433s  |   2.433s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |  15.840s  |  15.840s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |  13.243s  |  13.243s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |  14.155s  |  14.155s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |   2.619s  |   2.619s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        | 599.705s  | 599.705s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   5.259s  |   5.259s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   5.954s  |   5.954s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |   3.267s  |   3.267s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   9.277s  |   9.277s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        |  16.367s  |  16.367s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        | 599.530s  | 599.530s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   6.000s  |   6.000s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        | 599.517s  | 599.517s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |  32.549s  |  32.549s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   3.216s  |   3.216s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   0.958s  |   0.958s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   4.939s  |   4.939s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        | 599.367s  | 599.367s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        | 599.390s  | 599.390s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   3.531s  |   3.531s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        |  21.858s  |  21.858s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        |  60.048s  |  60.048s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            |  71.441s  |  71.441s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            | 268.671s  | 268.671s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  | 599.800s  | 599.800s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  | 598.463s  | 598.463s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |   9.030s  |   9.030s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  | 598.740s  | 598.740s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  | 599.086s  | 599.086s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   2.830s  |   2.830s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   1.630s  |   1.630s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   2.528s  |   2.528s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   2.376s  |   2.376s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   7.055s  |   7.055s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   0.619s  |   0.619s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  | 599.281s  | 599.281s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |  13.289s  |  13.289s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   4.306s  |   4.306s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  | 599.120s  | 599.120s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  | 599.835s  | 599.835s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   2.270s  |   2.270s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |  50.262s  |  50.262s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                | 598.871s  | 598.871s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |  52.432s  |  52.432s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   2.945s  |   2.945s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              | 204.460s  | 204.460s  |   0.000s  | 0.0%|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                        | 599.405s  | 599.405s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   | 598.756s  | 598.756s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   | 599.848s  | 599.848s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |   7.893s  |   7.893s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   | 599.309s  | 599.309s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   | 599.901s  | 599.901s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |  17.809s  |  17.809s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   | 598.591s  | 598.591s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   | 599.518s  | 599.518s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |  18.866s  |  18.866s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   | 599.744s  | 599.744s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         | 346.182s  | 346.182s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |   2.328s  |   2.328s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   2.816s  |   2.816s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |   8.309s  |   8.309s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         | 599.804s  | 599.804s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |   6.257s  |   6.257s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        | 598.751s  | 598.751s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        | 599.661s  | 599.661s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |  10.725s  |  10.725s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        | 599.401s  | 599.401s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        | 599.262s  | 599.262s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |  10.445s  |  10.445s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        | 598.611s  | 598.611s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   5.174s  |   5.174s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   2.481s  |   2.481s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   2.394s  |   2.394s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  35.178s  |  35.178s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   6.236s  |   6.236s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   4.309s  |   4.309s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |  40.260s  |  40.260s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |  29.582s  |  29.582s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      | 111.458s  | 111.458s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |   3.013s  |   3.013s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            | 599.751s  | 599.751s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            | 599.567s  | 599.567s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |  10.889s  |  10.889s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            | 598.770s  | 598.770s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            | 598.583s  | 598.583s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |   9.061s  |   9.061s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            | 595.084s  | 595.084s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  | 599.642s  | 599.642s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   4.619s  |   4.619s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  | 599.323s  | 599.323s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   3.496s  |   3.496s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            | 598.925s  | 598.925s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |  30.672s  |  30.672s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  32.535s  |  32.535s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |  41.974s  |  41.974s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |  73.021s  |  73.021s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   8.546s  |   8.546s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         | 599.531s  | 599.531s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   |  89.028s  |  89.028s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         |  23.549s  |  23.549s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   1.704s  |   1.704s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         | 598.886s  | 598.886s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |  11.315s  |  11.315s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |   6.097s  |   6.097s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   5.362s  |   5.362s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |   3.100s  |   3.100s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         | 599.147s  | 599.147s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |   8.828s  |   8.828s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   6.878s  |   6.878s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   6.646s  |   6.646s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   4.242s  |   4.242s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         |   3.023s  |   3.023s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   4.958s  |   4.958s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |  11.908s  |  11.908s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   6.453s  |   6.453s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   | 599.344s  | 599.344s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           |   5.148s  |   5.148s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           | 599.133s  | 599.133s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           | 185.748s  | 185.748s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   1.326s  |   1.326s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           |  75.003s  |  75.003s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           | 111.001s  | 111.001s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           | 599.382s  | 599.382s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           | 599.405s  | 599.405s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   1.042s  |   1.042s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  | 599.506s  | 599.506s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   2.375s  |   2.375s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   2.742s  |   2.742s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   2.026s  |   2.026s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   4.510s  |   4.510s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   3.071s  |   3.071s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   3.075s  |   3.075s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             | 599.323s  | 599.323s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   2.958s  |   2.958s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   1.787s  |   1.787s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   4.928s  |   4.928s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   3.050s  |   3.050s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             |  31.200s  |  31.200s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             | 598.713s  | 598.713s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   1.113s  |   1.113s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             |  70.728s  |  70.728s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   5.023s  |   5.023s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |   3.835s  |   3.835s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             | 599.521s  | 599.521s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   6.090s  |   6.090s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   1.215s  |   1.215s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |  20.563s  |  20.563s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             | 598.587s  | 598.587s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   4.111s  |   4.111s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             |  75.662s  |  75.662s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             | 599.215s  | 599.215s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   6.704s  |   6.704s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |  25.707s  |  25.707s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              | 597.873s  | 597.873s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      | 599.347s  | 599.347s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   3.567s  |   3.567s  |   0.000s  | 0.0%|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                          | 599.782s  | 599.782s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                | 599.166s  | 599.166s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                |  24.872s  |  24.872s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                | 140.915s  | 140.915s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                | 599.461s  | 599.461s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                | 599.837s  | 599.837s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |  29.153s  |  29.153s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                | 599.611s  | 599.611s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                | 599.075s  | 599.075s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |   3.819s  |   3.819s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          | 598.920s  | 598.920s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |  20.594s  |  20.594s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   4.936s  |   4.936s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   3.890s  |   3.890s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              | 599.308s  | 599.308s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2                       | 599.721s  | 599.721s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       | 599.356s  | 599.356s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  14.152s  |  14.152s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |  29.475s  |  29.475s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  45.716s  |  45.716s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |  84.968s  |  84.968s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           | 228.308s  | 228.308s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  51.091s  |  51.091s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |  10.523s  |  10.523s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   5.098s  |   5.098s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             | 599.302s  | 599.302s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  77.461s  |  77.461s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 | 126.797s  | 126.797s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |  33.293s  |  33.293s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  80.276s  |  80.276s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  98.257s  |  98.257s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 | 104.657s  | 104.657s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  43.948s  |  43.948s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |  83.541s  |  83.541s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           | 599.274s  | 599.274s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           | 599.549s  | 599.549s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           |  61.272s  |  61.272s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |  19.528s  |  19.528s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 | 599.491s  | 599.491s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 | 599.452s  | 599.452s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |   2.849s  |   2.849s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |  40.599s  |  40.599s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                | 599.315s  | 599.315s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                | 599.422s  | 599.422s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  11.995s  |  11.995s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |  74.758s  |  74.758s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          | 599.886s  | 599.886s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          | 599.240s  | 599.240s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          | 231.689s  | 231.689s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |  18.270s  |  18.270s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  25.318s  |  25.318s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     | 271.085s  | 271.085s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   2.987s  |   2.987s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                | 164.400s  | 164.400s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                | 599.219s  | 599.219s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   3.559s  |   3.559s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   4.398s  |   4.398s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            | 599.157s  | 599.157s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            |  17.149s  |  17.149s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   4.793s  |   4.793s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  40.780s  |  40.780s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   2.337s  |   2.337s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |   2.077s  |   2.077s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   1.884s  |   1.884s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   1.168s  |   1.168s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |  14.835s  |  14.835s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            | 593.886s  | 593.886s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      | 599.876s  | 599.876s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   3.092s  |   3.092s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   1.330s  |   1.330s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      | 404.280s  | 404.280s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   1.665s  |   1.665s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   2.339s  |   2.339s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   1.230s  |   1.230s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       |  30.286s  |  30.286s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 |  54.964s  |  54.964s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   3.006s  |   3.006s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  26.904s  |  26.904s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   4.485s  |   4.485s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        |  96.194s  |  96.194s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |  41.623s  |  41.623s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   2.181s  |   2.181s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           | 599.450s  | 599.450s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           | 599.120s  | 599.120s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |  52.987s  |  52.987s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  | 599.202s  | 599.202s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  |  15.135s  |  15.135s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           | 599.349s  | 599.349s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      | 598.845s  | 598.845s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   4.248s  |   4.248s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      | 598.379s  | 598.379s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           | 599.059s  | 599.059s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           | 228.806s  | 228.806s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        | 599.590s  | 599.590s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   2.793s  |   2.793s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              |   4.184s  |   4.184s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   1.697s  |   1.697s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             | 599.240s  | 599.240s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   2.611s  |   2.611s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   7.081s  |   7.081s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   6.594s  |   6.594s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |  16.379s  |  16.379s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   7.855s  |   7.855s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   2.240s  |   2.240s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        | 598.258s  | 598.258s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   1.965s  |   1.965s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   1.367s  |   1.367s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |  11.452s  |  11.452s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   4.414s  |   4.414s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  |  92.570s  |  92.570s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |  10.074s  |  10.074s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   3.794s  |   3.794s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   3.098s  |   3.098s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   3.295s  |   3.295s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   2.687s  |   2.687s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           | 598.916s  | 598.916s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  26.652s  |  26.652s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |  10.535s  |  10.535s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   5.673s  |   5.673s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |  49.229s  |  49.229s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |  38.077s  |  38.077s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   3.019s  |   3.019s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |  40.827s  |  40.827s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   7.105s  |   7.105s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |  26.014s  |  26.014s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                | 598.759s  | 598.759s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                | 599.468s  | 599.468s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   4.735s  |   4.735s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          | 599.620s  | 599.620s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   2.263s  |   2.263s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   1.182s  |   1.182s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   2.480s  |   2.480s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   0.814s  |   0.814s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |  11.681s  |  11.681s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           | 599.177s  | 599.177s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        | 161.505s  | 161.505s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |  22.974s  |  22.974s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                | 599.721s  | 599.721s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |  18.675s  |  18.675s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   5.055s  |   5.055s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |  12.555s  |  12.555s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   1.436s  |   1.436s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   4.103s  |   4.103s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       |  22.808s  |  22.808s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |   3.601s  |   3.601s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       |   4.612s  |   4.612s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   9.774s  |   9.774s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   3.856s  |   3.856s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       | 157.430s  | 157.430s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       | 599.856s  | 599.856s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       | 599.696s  | 599.696s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |  16.842s  |  16.842s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       | 599.291s  | 599.291s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       | 599.052s  | 599.052s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       | 598.994s  | 598.994s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       | 599.140s  | 599.140s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |  10.345s  |  10.345s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   4.756s  |   4.756s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       | 599.059s  | 599.059s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |  19.717s  |  19.717s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       | 599.169s  | 599.169s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     | 599.267s  | 599.267s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   2.899s  |   2.899s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                | 599.382s  | 599.382s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   1.110s  |   1.110s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   8.428s  |   8.428s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   3.777s  |   3.777s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |  70.913s  |  70.913s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   4.978s  |   4.978s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |   2.106s  |   2.106s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   2.457s  |   2.457s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |   3.200s  |   3.200s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |  12.247s  |  12.247s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        | 598.861s  | 598.861s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        | 599.721s  | 599.721s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |   7.900s  |   7.900s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  45.354s  |  45.354s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  | 599.398s  | 599.398s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  | 599.500s  | 599.500s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.545s  |   0.545s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  40.332s  |  40.332s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.760s  |   0.760s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |  24.360s  |  24.360s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   8.839s  |   8.839s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           | 119.616s  | 119.616s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           | 299.029s  | 299.029s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   2.027s  |   2.027s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   3.529s  |   3.529s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   4.724s  |   4.724s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   4.142s  |   4.142s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   3.966s  |   3.966s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   0.873s  |   0.873s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           | 599.514s  | 599.514s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   2.909s  |   2.909s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   0.942s  |   0.942s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           | 126.088s  | 126.088s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   1.612s  |   1.612s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   0.945s  |   0.945s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           | 599.789s  | 599.789s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   2.254s  |   2.254s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   0.945s  |   0.945s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   4.406s  |   4.406s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   1.008s  |   1.008s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   1.460s  |   1.460s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   3.862s  |   3.862s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   1.359s  |   1.359s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   5.558s  |   5.558s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |   6.098s  |   6.098s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   4.178s  |   4.178s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   3.282s  |   3.282s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           | 436.097s  | 436.097s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   4.964s  |   4.964s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           | 599.783s  | 599.783s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   2.628s  |   2.628s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   5.347s  |   5.347s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.741s  |   0.741s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   1.821s  |   1.821s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   2.215s  |   2.215s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           | 198.669s  | 198.669s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   2.236s  |   2.236s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           |  73.360s  |  73.360s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   2.417s  |   2.417s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   2.373s  |   2.373s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   6.954s  |   6.954s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   2.530s  |   2.530s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   4.659s  |   4.659s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           | 101.035s  | 101.035s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   6.010s  |   6.010s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   4.876s  |   4.876s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   2.707s  |   2.707s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   2.818s  |   2.818s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |  11.440s  |  11.440s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |   2.375s  |   2.375s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   0.839s  |   0.839s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   1.911s  |   1.911s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  19.010s  |  19.010s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   3.518s  |   3.518s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |   3.821s  |   3.821s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   2.471s  |   2.471s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            |  91.657s  |  91.657s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   2.877s  |   2.877s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |   4.001s  |   4.001s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   6.853s  |   6.853s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   3.858s  |   3.858s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   1.605s  |   1.605s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           | 124.338s  | 124.338s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           |  90.670s  |  90.670s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   3.268s  |   3.268s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   6.197s  |   6.197s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  64.822s  |  64.822s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   0.959s  |   0.959s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   2.096s  |   2.096s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   3.665s  |   3.665s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   2.127s  |   2.127s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   2.231s  |   2.231s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   4.124s  |   4.124s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           | 164.581s  | 164.581s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   4.310s  |   4.310s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |   2.718s  |   2.718s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           | 599.085s  | 599.085s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |   7.771s  |   7.771s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   4.672s  |   4.672s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           | 599.813s  | 599.813s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   3.091s  |   3.091s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   1.331s  |   1.331s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   8.326s  |   8.326s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           | 211.861s  | 211.861s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   0.748s  |   0.748s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |   5.961s  |   5.961s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           | 599.415s  | 599.415s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   2.251s  |   2.251s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |   5.320s  |   5.320s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   3.984s  |   3.984s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   6.593s  |   6.593s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   4.946s  |   4.946s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |   7.411s  |   7.411s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   1.990s  |   1.990s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           | 599.168s  | 599.168s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  49.398s  |  49.398s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   2.335s  |   2.335s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   1.534s  |   1.534s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   5.248s  |   5.248s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   4.268s  |   4.268s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   2.329s  |   2.329s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |   7.406s  |   7.406s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   4.278s  |   4.278s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |  86.585s  |  86.585s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |   2.940s  |   2.940s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.843s  |   0.843s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   1.015s  |   1.015s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   1.586s  |   1.586s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   1.848s  |   1.848s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   1.734s  |   1.734s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   1.620s  |   1.620s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |   2.378s  |   2.378s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   7.769s  |   7.769s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            | 599.007s  | 599.007s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            |  21.441s  |  21.441s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            | 599.686s  | 599.686s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            | 599.331s  | 599.331s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            | 598.834s  | 598.834s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            | 245.665s  | 245.665s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            | 599.344s  | 599.344s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|term-tEmpby.smt2                                                                            |   0.085s  |   0.085s  |   0.000s  | 0.0%|
</details>
