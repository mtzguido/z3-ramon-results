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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-auto_config-ablate
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: dd30b9eaf3624ea8d87e9e84ece5b50b171e5eda
Z3 branch: dd30b9eaf3624ea8d87e9e84ece5b50b171e5eda
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore incomplete-theory give-up paths

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-auto_config-ablate
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: dd30b9eaf3624ea8d87e9e84ece5b50b171e5eda
Z3 branch: dd30b9eaf3624ea8d87e9e84ece5b50b171e5eda
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore incomplete-theory give-up paths

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.341s  |1204.341s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.808s  |1201.808s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.741s  |1202.741s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.727s  |1203.727s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1204.111s  |1204.111s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  78.687s  |  78.687s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.764s  |1200.764s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1206.231s  |1206.231s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  39.638s  |  39.638s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 232.314s  | 232.314s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 335.828s  | 335.828s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.509s  |1200.509s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.653s  |1200.653s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.635s  |1200.635s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.975s  |1202.975s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 350.108s  | 350.108s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  89.711s  |  89.711s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.878s  |1202.878s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.341s  |1204.341s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.808s  |1201.808s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.741s  |1202.741s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.727s  |1203.727s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1204.111s  |1204.111s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  78.687s  |  78.687s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.764s  |1200.764s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1206.231s  |1206.231s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  39.638s  |  39.638s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 232.314s  | 232.314s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 335.828s  | 335.828s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.509s  |1200.509s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.653s  |1200.653s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.635s  |1200.635s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.975s  |1202.975s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 350.108s  | 350.108s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  89.711s  |  89.711s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.878s  |1202.878s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.341s  |1204.341s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.808s  |1201.808s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.741s  |1202.741s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.727s  |1203.727s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1204.111s  |1204.111s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  78.687s  |  78.687s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.764s  |1200.764s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1206.231s  |1206.231s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  39.638s  |  39.638s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 232.314s  | 232.314s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 335.828s  | 335.828s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.509s  |1200.509s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.653s  |1200.653s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.635s  |1200.635s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.975s  |1202.975s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 350.108s  | 350.108s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  89.711s  |  89.711s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.878s  |1202.878s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.341s  |1204.341s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.808s  |1201.808s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.741s  |1202.741s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.727s  |1203.727s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1204.111s  |1204.111s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  78.687s  |  78.687s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.764s  |1200.764s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1206.231s  |1206.231s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  39.638s  |  39.638s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 232.314s  | 232.314s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 335.828s  | 335.828s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.509s  |1200.509s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.653s  |1200.653s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.635s  |1200.635s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.975s  |1202.975s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 350.108s  | 350.108s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  89.711s  |  89.711s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.878s  |1202.878s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1207.013s |62.581GiB|
|scrambled12042.smt2                                                                        |1206.231s |54.035GiB|
|scrambled4299.smt2                                                                         |1205.244s |56.444GiB|
|scrambled68944.smt2                                                                        |1205.012s |46.644GiB|
|scrambled4198.smt2                                                                         |1204.886s |48.897GiB|
|scrambled55680.smt2                                                                        |1204.573s |50.279GiB|
|scrambled102166.smt2                                                                       |1204.341s |47.752GiB|
|scrambled111627.smt2                                                                       |1204.111s |37.479GiB|
|scrambled79760.smt2                                                                        |1204.086s |43.99GiB|
|scrambled108840.smt2                                                                       |1203.727s |42.728GiB|
|scrambled75189.smt2                                                                        |1203.395s |31.457GiB|
|scrambled43577.smt2                                                                        |1203.108s |33.981GiB|
|scrambled19335.smt2                                                                        |1202.975s |32.161GiB|
|scrambled27843.smt2                                                                        |1202.878s |20.866GiB|
|scrambled107826.smt2                                                                       |1202.741s |27.659GiB|
|scrambled107115.smt2                                                                       |1201.808s |17.678GiB|
|scrambled61922.smt2                                                                        |1201.345s |10.754GiB|
|scrambled40621.smt2                                                                        |1200.791s |6444.0MiB|
|scrambled119331.smt2                                                                       |1200.764s |7062.0MiB|
|scrambled7741.smt2                                                                         |1200.759s |5900.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1207.013s |62.581GiB|
|scrambled12042.smt2                                                                        |1206.231s |54.035GiB|
|scrambled4299.smt2                                                                         |1205.244s |56.444GiB|
|scrambled68944.smt2                                                                        |1205.012s |46.644GiB|
|scrambled4198.smt2                                                                         |1204.886s |48.897GiB|
|scrambled55680.smt2                                                                        |1204.573s |50.279GiB|
|scrambled102166.smt2                                                                       |1204.341s |47.752GiB|
|scrambled111627.smt2                                                                       |1204.111s |37.479GiB|
|scrambled79760.smt2                                                                        |1204.086s |43.99GiB|
|scrambled108840.smt2                                                                       |1203.727s |42.728GiB|
|scrambled75189.smt2                                                                        |1203.395s |31.457GiB|
|scrambled43577.smt2                                                                        |1203.108s |33.981GiB|
|scrambled19335.smt2                                                                        |1202.975s |32.161GiB|
|scrambled27843.smt2                                                                        |1202.878s |20.866GiB|
|scrambled107826.smt2                                                                       |1202.741s |27.659GiB|
|scrambled107115.smt2                                                                       |1201.808s |17.678GiB|
|scrambled61922.smt2                                                                        |1201.345s |10.754GiB|
|scrambled40621.smt2                                                                        |1200.791s |6444.0MiB|
|scrambled119331.smt2                                                                       |1200.764s |7062.0MiB|
|scrambled7741.smt2                                                                         |1200.759s |5900.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.752GiB|47.752GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.308MiB|42.308MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.678GiB|17.678GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.659GiB|27.659GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.728GiB|42.728GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.479GiB|37.479GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |899.0MiB|899.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |7062.0MiB|7062.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.035GiB|54.035GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |939.0MiB|939.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1550.0MiB|1550.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |4778.0MiB|4778.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4760.0MiB|4760.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4704.0MiB|4704.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5139.0MiB|5139.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.161GiB|32.161GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1648.0MiB|1648.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3600.0MiB|3600.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.866GiB|20.866GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.752GiB|47.752GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.308MiB|42.308MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.678GiB|17.678GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.659GiB|27.659GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.728GiB|42.728GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.479GiB|37.479GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |899.0MiB|899.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |7062.0MiB|7062.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.035GiB|54.035GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |939.0MiB|939.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1550.0MiB|1550.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |4778.0MiB|4778.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4760.0MiB|4760.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4704.0MiB|4704.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5139.0MiB|5139.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.161GiB|32.161GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1648.0MiB|1648.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3600.0MiB|3600.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.866GiB|20.866GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.752GiB|47.752GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.308MiB|42.308MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.678GiB|17.678GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.659GiB|27.659GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.728GiB|42.728GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.479GiB|37.479GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |899.0MiB|899.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |7062.0MiB|7062.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.035GiB|54.035GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |939.0MiB|939.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1550.0MiB|1550.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |4778.0MiB|4778.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4760.0MiB|4760.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4704.0MiB|4704.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5139.0MiB|5139.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.161GiB|32.161GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1648.0MiB|1648.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3600.0MiB|3600.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.866GiB|20.866GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.752GiB|47.752GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.308MiB|42.308MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.678GiB|17.678GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.659GiB|27.659GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.728GiB|42.728GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.479GiB|37.479GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |899.0MiB|899.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |7062.0MiB|7062.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.035GiB|54.035GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |939.0MiB|939.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1550.0MiB|1550.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |4778.0MiB|4778.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4760.0MiB|4760.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4704.0MiB|4704.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5139.0MiB|5139.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.161GiB|32.161GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1648.0MiB|1648.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3600.0MiB|3600.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.866GiB|20.866GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1207.013s |62.581GiB|
|scrambled4299.smt2                                                                         |1205.244s |56.444GiB|
|scrambled12042.smt2                                                                        |1206.231s |54.035GiB|
|scrambled55680.smt2                                                                        |1204.573s |50.279GiB|
|scrambled4198.smt2                                                                         |1204.886s |48.897GiB|
|scrambled102166.smt2                                                                       |1204.341s |47.752GiB|
|scrambled68944.smt2                                                                        |1205.012s |46.644GiB|
|scrambled79760.smt2                                                                        |1204.086s |43.99GiB|
|scrambled108840.smt2                                                                       |1203.727s |42.728GiB|
|scrambled111627.smt2                                                                       |1204.111s |37.479GiB|
|scrambled43577.smt2                                                                        |1203.108s |33.981GiB|
|scrambled19335.smt2                                                                        |1202.975s |32.161GiB|
|scrambled75189.smt2                                                                        |1203.395s |31.457GiB|
|scrambled107826.smt2                                                                       |1202.741s |27.659GiB|
|scrambled27843.smt2                                                                        |1202.878s |20.866GiB|
|scrambled107115.smt2                                                                       |1201.808s |17.678GiB|
|scrambled61922.smt2                                                                        |1201.345s |10.754GiB|
|scrambled119331.smt2                                                                       |1200.764s |7062.0MiB|
|scrambled40621.smt2                                                                        |1200.791s |6444.0MiB|
|scrambled7741.smt2                                                                         |1200.759s |5900.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1207.013s |62.581GiB|
|scrambled4299.smt2                                                                         |1205.244s |56.444GiB|
|scrambled12042.smt2                                                                        |1206.231s |54.035GiB|
|scrambled55680.smt2                                                                        |1204.573s |50.279GiB|
|scrambled4198.smt2                                                                         |1204.886s |48.897GiB|
|scrambled102166.smt2                                                                       |1204.341s |47.752GiB|
|scrambled68944.smt2                                                                        |1205.012s |46.644GiB|
|scrambled79760.smt2                                                                        |1204.086s |43.99GiB|
|scrambled108840.smt2                                                                       |1203.727s |42.728GiB|
|scrambled111627.smt2                                                                       |1204.111s |37.479GiB|
|scrambled43577.smt2                                                                        |1203.108s |33.981GiB|
|scrambled19335.smt2                                                                        |1202.975s |32.161GiB|
|scrambled75189.smt2                                                                        |1203.395s |31.457GiB|
|scrambled107826.smt2                                                                       |1202.741s |27.659GiB|
|scrambled27843.smt2                                                                        |1202.878s |20.866GiB|
|scrambled107115.smt2                                                                       |1201.808s |17.678GiB|
|scrambled61922.smt2                                                                        |1201.345s |10.754GiB|
|scrambled119331.smt2                                                                       |1200.764s |7062.0MiB|
|scrambled40621.smt2                                                                        |1200.791s |6444.0MiB|
|scrambled7741.smt2                                                                         |1200.759s |5900.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.341s  |1204.341s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.808s  |1201.808s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.741s  |1202.741s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.727s  |1203.727s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1204.111s  |1204.111s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  78.687s  |  78.687s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.764s  |1200.764s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1206.231s  |1206.231s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  39.638s  |  39.638s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 232.314s  | 232.314s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 335.828s  | 335.828s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.509s  |1200.509s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.653s  |1200.653s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.635s  |1200.635s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.975s  |1202.975s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 350.108s  | 350.108s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  89.711s  |  89.711s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.878s  |1202.878s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.408s  |1200.408s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1200.791s  |1200.791s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1204.886s  |1204.886s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1205.244s  |1205.244s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1203.108s  |1203.108s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         | 363.941s  | 363.941s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.400s  |1200.400s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1204.573s  |1204.573s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.339s  |1200.339s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1201.345s  |1201.345s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1205.012s  |1205.012s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1200.752s  |1200.752s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1203.395s  |1203.395s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.759s  |1200.759s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1204.086s  |1204.086s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.081s  |1200.081s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1207.013s  |1207.013s  |   0.000s  | 0.0%|
</details>
