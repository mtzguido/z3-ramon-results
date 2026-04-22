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
Ramon benchmark for SMTS
-
Job description: 
Job tag: SMTS_z3-threads-8-smtcomp2025-QF_LIA-timeout_20min
Runner: rise-runner-2
SMTS repo: ilanashapiro/SMTS
SMTS commit: 6fbca23b525b880620030507e997cbbe14ae1a90
SMTS branch: master
SMTS options: "-oz 8 -p -l"
SMTS solver mode: z3
SMTS timeout: 1200
SMTS inputs: inputs/smt_comp_2025_parallel/QF_LIA
SMTS commit message: fix more semantic bugs between SMTS+Z3 and the original SMTS+OpenSMT2

</pre>
# RHS
<pre>
Ramon benchmark for SMTS
-
Job description: 
Job tag: SMTS_z3-threads-8-smtcomp2025-QF_LIA-timeout_20min
Runner: rise-runner-2
SMTS repo: ilanashapiro/SMTS
SMTS commit: 6fbca23b525b880620030507e997cbbe14ae1a90
SMTS branch: master
SMTS options: "-oz 8 -p -l"
SMTS solver mode: z3
SMTS timeout: 1200
SMTS inputs: inputs/smt_comp_2025_parallel/QF_LIA
SMTS commit message: fix more semantic bugs between SMTS+Z3 and the original SMTS+OpenSMT2

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.370s  |1200.370s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.262s  |1200.262s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.075s  |1200.075s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.370s  |1200.370s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.262s  |1200.262s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.075s  |1200.075s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.370s  |1200.370s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.262s  |1200.262s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.075s  |1200.075s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.370s  |1200.370s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.262s  |1200.262s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.075s  |1200.075s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled43577.smt2                                                                        |1200.370s |2830.0MiB|
|scrambled19335.smt2                                                                        |1200.370s |2635.0MiB|
|scrambled102166.smt2                                                                       |1200.276s |3471.0MiB|
|scrambled25238.smt2                                                                        |1200.262s |242.0MiB|
|scrambled55680.smt2                                                                        |1200.138s |4268.0MiB|
|scrambled12042.smt2                                                                        |1200.128s |5212.0MiB|
|scrambled108840.smt2                                                                       |1200.127s |3378.0MiB|
|scrambled4299.smt2                                                                         |1200.121s |3259.0MiB|
|scrambled128874.smt2                                                                       |1200.121s |188.0MiB|
|scrambled40621.smt2                                                                        |1200.112s |332.0MiB|
|scrambled68944.smt2                                                                        |1200.102s |2617.0MiB|
|scrambled95803.smt2                                                                        |1200.093s |147.0MiB|
|scrambled3854.smt2                                                                         |1200.092s |12.068GiB|
|scrambled94658.smt2                                                                        |1200.086s |5027.0MiB|
|scrambled131241.smt2                                                                       |1200.085s |233.0MiB|
|scrambled51053.smt2                                                                        |1200.077s |927.0MiB|
|scrambled27843.smt2                                                                        |1200.075s |1807.0MiB|
|scrambled1417.smt2                                                                         |1200.073s |34.9MiB|
|scrambled107115.smt2                                                                       |1200.073s |1060.0MiB|
|scrambled61922.smt2                                                                        |1200.072s |781.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled43577.smt2                                                                        |1200.370s |2830.0MiB|
|scrambled19335.smt2                                                                        |1200.370s |2635.0MiB|
|scrambled102166.smt2                                                                       |1200.276s |3471.0MiB|
|scrambled25238.smt2                                                                        |1200.262s |242.0MiB|
|scrambled55680.smt2                                                                        |1200.138s |4268.0MiB|
|scrambled12042.smt2                                                                        |1200.128s |5212.0MiB|
|scrambled108840.smt2                                                                       |1200.127s |3378.0MiB|
|scrambled4299.smt2                                                                         |1200.121s |3259.0MiB|
|scrambled128874.smt2                                                                       |1200.121s |188.0MiB|
|scrambled40621.smt2                                                                        |1200.112s |332.0MiB|
|scrambled68944.smt2                                                                        |1200.102s |2617.0MiB|
|scrambled95803.smt2                                                                        |1200.093s |147.0MiB|
|scrambled3854.smt2                                                                         |1200.092s |12.068GiB|
|scrambled94658.smt2                                                                        |1200.086s |5027.0MiB|
|scrambled131241.smt2                                                                       |1200.085s |233.0MiB|
|scrambled51053.smt2                                                                        |1200.077s |927.0MiB|
|scrambled27843.smt2                                                                        |1200.075s |1807.0MiB|
|scrambled1417.smt2                                                                         |1200.073s |34.9MiB|
|scrambled107115.smt2                                                                       |1200.073s |1060.0MiB|
|scrambled61922.smt2                                                                        |1200.072s |781.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3471.0MiB|3471.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |11.952GiB|11.952GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1060.0MiB|1060.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |2676.0MiB|2676.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3378.0MiB|3378.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2753.0MiB|2753.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |81.404MiB|81.404MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |324.0MiB|324.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |5212.0MiB|5212.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |88.608MiB|88.608MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |105.0MiB|105.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |239.0MiB|239.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |192.0MiB|192.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |188.0MiB|188.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |233.0MiB|233.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |34.9MiB|34.9MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |2635.0MiB|2635.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |109.0MiB|109.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |242.0MiB|242.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1807.0MiB|1807.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3471.0MiB|3471.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |11.952GiB|11.952GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1060.0MiB|1060.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |2676.0MiB|2676.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3378.0MiB|3378.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2753.0MiB|2753.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |81.404MiB|81.404MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |324.0MiB|324.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |5212.0MiB|5212.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |88.608MiB|88.608MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |105.0MiB|105.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |239.0MiB|239.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |192.0MiB|192.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |188.0MiB|188.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |233.0MiB|233.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |34.9MiB|34.9MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |2635.0MiB|2635.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |109.0MiB|109.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |242.0MiB|242.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1807.0MiB|1807.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3471.0MiB|3471.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |11.952GiB|11.952GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1060.0MiB|1060.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |2676.0MiB|2676.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3378.0MiB|3378.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2753.0MiB|2753.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |81.404MiB|81.404MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |324.0MiB|324.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |5212.0MiB|5212.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |88.608MiB|88.608MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |105.0MiB|105.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |239.0MiB|239.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |192.0MiB|192.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |188.0MiB|188.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |233.0MiB|233.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |34.9MiB|34.9MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |2635.0MiB|2635.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |109.0MiB|109.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |242.0MiB|242.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1807.0MiB|1807.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3471.0MiB|3471.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |11.952GiB|11.952GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1060.0MiB|1060.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |2676.0MiB|2676.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3378.0MiB|3378.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2753.0MiB|2753.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |81.404MiB|81.404MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |324.0MiB|324.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |5212.0MiB|5212.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |88.608MiB|88.608MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |105.0MiB|105.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |239.0MiB|239.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |192.0MiB|192.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |188.0MiB|188.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |233.0MiB|233.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |34.9MiB|34.9MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |2635.0MiB|2635.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |109.0MiB|109.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |242.0MiB|242.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1807.0MiB|1807.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled79867.smt2                                                                        |1200.026s |12.732GiB|
|scrambled39514.smt2                                                                        |1200.032s |12.492GiB|
|scrambled45952.smt2                                                                        |1200.072s |12.434GiB|
|scrambled59713.smt2                                                                        |1200.053s |12.232GiB|
|scrambled3854.smt2                                                                         |1200.092s |12.068GiB|
|scrambled79766.smt2                                                                        |1200.069s |11.972GiB|
|scrambled103783.smt2                                                                       |1200.033s |11.952GiB|
|scrambled65181.smt2                                                                        |1200.023s |11.707GiB|
|scrambled4198.smt2                                                                         |1200.067s |5345.0MiB|
|scrambled12042.smt2                                                                        |1200.128s |5212.0MiB|
|scrambled94658.smt2                                                                        |1200.086s |5027.0MiB|
|scrambled55680.smt2                                                                        |1200.138s |4268.0MiB|
|scrambled102166.smt2                                                                       |1200.276s |3471.0MiB|
|scrambled108840.smt2                                                                       |1200.127s |3378.0MiB|
|scrambled4299.smt2                                                                         |1200.121s |3259.0MiB|
|scrambled43577.smt2                                                                        |1200.370s |2830.0MiB|
|scrambled111627.smt2                                                                       |1200.062s |2753.0MiB|
|scrambled79760.smt2                                                                        |1200.044s |2749.0MiB|
|scrambled107826.smt2                                                                       |1200.057s |2676.0MiB|
|scrambled19335.smt2                                                                        |1200.370s |2635.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled79867.smt2                                                                        |1200.026s |12.732GiB|
|scrambled39514.smt2                                                                        |1200.032s |12.492GiB|
|scrambled45952.smt2                                                                        |1200.072s |12.434GiB|
|scrambled59713.smt2                                                                        |1200.053s |12.232GiB|
|scrambled3854.smt2                                                                         |1200.092s |12.068GiB|
|scrambled79766.smt2                                                                        |1200.069s |11.972GiB|
|scrambled103783.smt2                                                                       |1200.033s |11.952GiB|
|scrambled65181.smt2                                                                        |1200.023s |11.707GiB|
|scrambled4198.smt2                                                                         |1200.067s |5345.0MiB|
|scrambled12042.smt2                                                                        |1200.128s |5212.0MiB|
|scrambled94658.smt2                                                                        |1200.086s |5027.0MiB|
|scrambled55680.smt2                                                                        |1200.138s |4268.0MiB|
|scrambled102166.smt2                                                                       |1200.276s |3471.0MiB|
|scrambled108840.smt2                                                                       |1200.127s |3378.0MiB|
|scrambled4299.smt2                                                                         |1200.121s |3259.0MiB|
|scrambled43577.smt2                                                                        |1200.370s |2830.0MiB|
|scrambled111627.smt2                                                                       |1200.062s |2753.0MiB|
|scrambled79760.smt2                                                                        |1200.044s |2749.0MiB|
|scrambled107826.smt2                                                                       |1200.057s |2676.0MiB|
|scrambled19335.smt2                                                                        |1200.370s |2635.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.128s  |1200.128s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.370s  |1200.370s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.262s  |1200.262s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1200.370s  |1200.370s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.023s  |1200.023s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1200.102s  |1200.102s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1200.024s  |1200.024s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.026s  |1200.026s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1200.086s  |1200.086s  |   0.000s  | 0.0%|
</details>
