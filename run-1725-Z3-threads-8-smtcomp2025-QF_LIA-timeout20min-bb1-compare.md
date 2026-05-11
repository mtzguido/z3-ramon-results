Comparing data and data


# SUMMARY
- LHS tests = 44
- RHS tests = 44
- LHS success = 44  (100.0%)
- RHS success = 44  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb1
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: c383004968f5bf66a9668a7ae254c83d45ac3afe
Z3 branch: fmcad26_artifact
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=1"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: add ablate_backtracking experiment

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb1
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: c383004968f5bf66a9668a7ae254c83d45ac3afe
Z3 branch: fmcad26_artifact
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=1"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: add ablate_backtracking experiment

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.546s  |1204.546s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1202.428s  |1202.428s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.393s  |1202.393s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.864s  |1203.864s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.371s  |1203.371s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 101.818s  | 101.818s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.959s  |1200.959s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.775s  |1204.775s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 370.759s  | 370.759s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  92.745s  |  92.745s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.580s  |1200.580s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.550s  |1200.550s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.683s  |1200.683s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.685s  |1200.685s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.167s  |1203.167s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 110.509s  | 110.509s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 197.520s  | 197.520s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.129s  |1202.129s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.546s  |1204.546s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1202.428s  |1202.428s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.393s  |1202.393s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.864s  |1203.864s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.371s  |1203.371s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 101.818s  | 101.818s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.959s  |1200.959s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.775s  |1204.775s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 370.759s  | 370.759s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  92.745s  |  92.745s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.580s  |1200.580s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.550s  |1200.550s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.683s  |1200.683s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.685s  |1200.685s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.167s  |1203.167s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 110.509s  | 110.509s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 197.520s  | 197.520s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.129s  |1202.129s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.546s  |1204.546s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1202.428s  |1202.428s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.393s  |1202.393s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.864s  |1203.864s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.371s  |1203.371s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 101.818s  | 101.818s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.959s  |1200.959s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.775s  |1204.775s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 370.759s  | 370.759s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  92.745s  |  92.745s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.580s  |1200.580s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.550s  |1200.550s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.683s  |1200.683s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.685s  |1200.685s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.167s  |1203.167s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 110.509s  | 110.509s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 197.520s  | 197.520s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.129s  |1202.129s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.546s  |1204.546s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1202.428s  |1202.428s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.393s  |1202.393s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.864s  |1203.864s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.371s  |1203.371s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 101.818s  | 101.818s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.959s  |1200.959s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.775s  |1204.775s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 370.759s  | 370.759s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  92.745s  |  92.745s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.580s  |1200.580s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.550s  |1200.550s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.683s  |1200.683s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.685s  |1200.685s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.167s  |1203.167s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 110.509s  | 110.509s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 197.520s  | 197.520s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.129s  |1202.129s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1207.195s |62.059GiB|
|scrambled55680.smt2                                                                        |1205.675s |50.069GiB|
|scrambled4299.smt2                                                                         |1204.958s |56.341GiB|
|scrambled68944.smt2                                                                        |1204.845s |46.803GiB|
|scrambled12042.smt2                                                                        |1204.775s |53.827GiB|
|scrambled102166.smt2                                                                       |1204.546s |47.578GiB|
|scrambled4198.smt2                                                                         |1204.347s |48.455GiB|
|scrambled79760.smt2                                                                        |1203.917s |43.896GiB|
|scrambled108840.smt2                                                                       |1203.864s |42.579GiB|
|scrambled111627.smt2                                                                       |1203.371s |37.451GiB|
|scrambled43577.smt2                                                                        |1203.261s |33.847GiB|
|scrambled19335.smt2                                                                        |1203.167s |32.06GiB|
|scrambled75189.smt2                                                                        |1202.890s |31.365GiB|
|scrambled107115.smt2                                                                       |1202.428s |17.528GiB|
|scrambled107826.smt2                                                                       |1202.393s |27.573GiB|
|scrambled27843.smt2                                                                        |1202.129s |20.717GiB|
|scrambled61922.smt2                                                                        |1201.173s |10.707GiB|
|scrambled7741.smt2                                                                         |1201.127s |6165.0MiB|
|scrambled40621.smt2                                                                        |1201.040s |10.169GiB|
|scrambled119331.smt2                                                                       |1200.959s |8720.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1207.195s |62.059GiB|
|scrambled55680.smt2                                                                        |1205.675s |50.069GiB|
|scrambled4299.smt2                                                                         |1204.958s |56.341GiB|
|scrambled68944.smt2                                                                        |1204.845s |46.803GiB|
|scrambled12042.smt2                                                                        |1204.775s |53.827GiB|
|scrambled102166.smt2                                                                       |1204.546s |47.578GiB|
|scrambled4198.smt2                                                                         |1204.347s |48.455GiB|
|scrambled79760.smt2                                                                        |1203.917s |43.896GiB|
|scrambled108840.smt2                                                                       |1203.864s |42.579GiB|
|scrambled111627.smt2                                                                       |1203.371s |37.451GiB|
|scrambled43577.smt2                                                                        |1203.261s |33.847GiB|
|scrambled19335.smt2                                                                        |1203.167s |32.06GiB|
|scrambled75189.smt2                                                                        |1202.890s |31.365GiB|
|scrambled107115.smt2                                                                       |1202.428s |17.528GiB|
|scrambled107826.smt2                                                                       |1202.393s |27.573GiB|
|scrambled27843.smt2                                                                        |1202.129s |20.717GiB|
|scrambled61922.smt2                                                                        |1201.173s |10.707GiB|
|scrambled7741.smt2                                                                         |1201.127s |6165.0MiB|
|scrambled40621.smt2                                                                        |1201.040s |10.169GiB|
|scrambled119331.smt2                                                                       |1200.959s |8720.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.578GiB|47.578GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.912MiB|42.912MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.528GiB|17.528GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.573GiB|27.573GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.579GiB|42.579GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.451GiB|37.451GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |849.0MiB|849.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |8720.0MiB|8720.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |53.827GiB|53.827GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |926.0MiB|926.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1418.0MiB|1418.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |5840.0MiB|5840.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4595.0MiB|4595.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4675.0MiB|4675.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5782.0MiB|5782.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |346.0MiB|346.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.06GiB|32.06GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1475.0MiB|1475.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5310.0MiB|5310.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.717GiB|20.717GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.578GiB|47.578GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.912MiB|42.912MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.528GiB|17.528GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.573GiB|27.573GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.579GiB|42.579GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.451GiB|37.451GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |849.0MiB|849.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |8720.0MiB|8720.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |53.827GiB|53.827GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |926.0MiB|926.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1418.0MiB|1418.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |5840.0MiB|5840.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4595.0MiB|4595.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4675.0MiB|4675.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5782.0MiB|5782.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |346.0MiB|346.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.06GiB|32.06GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1475.0MiB|1475.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5310.0MiB|5310.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.717GiB|20.717GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.578GiB|47.578GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.912MiB|42.912MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.528GiB|17.528GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.573GiB|27.573GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.579GiB|42.579GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.451GiB|37.451GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |849.0MiB|849.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |8720.0MiB|8720.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |53.827GiB|53.827GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |926.0MiB|926.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1418.0MiB|1418.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |5840.0MiB|5840.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4595.0MiB|4595.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4675.0MiB|4675.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5782.0MiB|5782.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |346.0MiB|346.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.06GiB|32.06GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1475.0MiB|1475.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5310.0MiB|5310.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.717GiB|20.717GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.578GiB|47.578GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.912MiB|42.912MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.528GiB|17.528GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.573GiB|27.573GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.579GiB|42.579GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.451GiB|37.451GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |849.0MiB|849.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |8720.0MiB|8720.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |53.827GiB|53.827GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |926.0MiB|926.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1418.0MiB|1418.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |5840.0MiB|5840.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4595.0MiB|4595.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4675.0MiB|4675.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5782.0MiB|5782.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |346.0MiB|346.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.06GiB|32.06GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1475.0MiB|1475.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5310.0MiB|5310.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.717GiB|20.717GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1207.195s |62.059GiB|
|scrambled4299.smt2                                                                         |1204.958s |56.341GiB|
|scrambled12042.smt2                                                                        |1204.775s |53.827GiB|
|scrambled55680.smt2                                                                        |1205.675s |50.069GiB|
|scrambled4198.smt2                                                                         |1204.347s |48.455GiB|
|scrambled102166.smt2                                                                       |1204.546s |47.578GiB|
|scrambled68944.smt2                                                                        |1204.845s |46.803GiB|
|scrambled79760.smt2                                                                        |1203.917s |43.896GiB|
|scrambled108840.smt2                                                                       |1203.864s |42.579GiB|
|scrambled111627.smt2                                                                       |1203.371s |37.451GiB|
|scrambled43577.smt2                                                                        |1203.261s |33.847GiB|
|scrambled19335.smt2                                                                        |1203.167s |32.06GiB|
|scrambled75189.smt2                                                                        |1202.890s |31.365GiB|
|scrambled107826.smt2                                                                       |1202.393s |27.573GiB|
|scrambled27843.smt2                                                                        |1202.129s |20.717GiB|
|scrambled107115.smt2                                                                       |1202.428s |17.528GiB|
|scrambled61922.smt2                                                                        |1201.173s |10.707GiB|
|scrambled40621.smt2                                                                        |1201.040s |10.169GiB|
|scrambled119331.smt2                                                                       |1200.959s |8720.0MiB|
|scrambled7741.smt2                                                                         |1201.127s |6165.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1207.195s |62.059GiB|
|scrambled4299.smt2                                                                         |1204.958s |56.341GiB|
|scrambled12042.smt2                                                                        |1204.775s |53.827GiB|
|scrambled55680.smt2                                                                        |1205.675s |50.069GiB|
|scrambled4198.smt2                                                                         |1204.347s |48.455GiB|
|scrambled102166.smt2                                                                       |1204.546s |47.578GiB|
|scrambled68944.smt2                                                                        |1204.845s |46.803GiB|
|scrambled79760.smt2                                                                        |1203.917s |43.896GiB|
|scrambled108840.smt2                                                                       |1203.864s |42.579GiB|
|scrambled111627.smt2                                                                       |1203.371s |37.451GiB|
|scrambled43577.smt2                                                                        |1203.261s |33.847GiB|
|scrambled19335.smt2                                                                        |1203.167s |32.06GiB|
|scrambled75189.smt2                                                                        |1202.890s |31.365GiB|
|scrambled107826.smt2                                                                       |1202.393s |27.573GiB|
|scrambled27843.smt2                                                                        |1202.129s |20.717GiB|
|scrambled107115.smt2                                                                       |1202.428s |17.528GiB|
|scrambled61922.smt2                                                                        |1201.173s |10.707GiB|
|scrambled40621.smt2                                                                        |1201.040s |10.169GiB|
|scrambled119331.smt2                                                                       |1200.959s |8720.0MiB|
|scrambled7741.smt2                                                                         |1201.127s |6165.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.546s  |1204.546s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1202.428s  |1202.428s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.393s  |1202.393s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.864s  |1203.864s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.371s  |1203.371s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 101.818s  | 101.818s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.959s  |1200.959s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.775s  |1204.775s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 370.759s  | 370.759s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  92.745s  |  92.745s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.580s  |1200.580s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.550s  |1200.550s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.683s  |1200.683s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.685s  |1200.685s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.167s  |1203.167s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 110.509s  | 110.509s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 197.520s  | 197.520s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.129s  |1202.129s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 923.687s  | 923.687s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1201.040s  |1201.040s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1204.347s  |1204.347s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1204.958s  |1204.958s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1203.261s  |1203.261s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.609s  |1200.609s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.300s  |1200.300s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1205.675s  |1205.675s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.777s  |1200.777s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1201.173s  |1201.173s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1204.845s  |1204.845s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1200.772s  |1200.772s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1202.890s  |1202.890s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1201.127s  |1201.127s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1203.917s  |1203.917s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1207.195s  |1207.195s  |   0.000s  | 0.0%|
</details>
