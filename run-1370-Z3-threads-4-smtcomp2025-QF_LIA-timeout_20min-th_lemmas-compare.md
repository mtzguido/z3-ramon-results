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
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-th_lemmas
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bdff96fde97215ca1c28b4d30df7a4a20cbfc050
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.share_theory_lemmas=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: undo local bb ablation about resetting phase/activities, and reinstate the shared lemmas of length 2 and 3 experiment

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-th_lemmas
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bdff96fde97215ca1c28b4d30df7a4a20cbfc050
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.share_theory_lemmas=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: undo local bb ablation about resetting phase/activities, and reinstate the shared lemmas of length 2 and 3 experiment

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.263s  |1262.263s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.982s  |1260.982s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.444s  |1261.444s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.220s  |1262.220s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.928s  |1261.928s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 232.996s  | 232.996s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.469s  |1260.469s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.870s  |1262.870s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 339.064s  | 339.064s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 375.338s  | 375.338s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.398s  |1260.398s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.386s  |1260.386s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.370s  |1260.370s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.382s  |1260.382s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.066s  |1260.066s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.599s  |1261.599s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1260.116s  |1260.116s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 640.727s  | 640.727s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.264s  |1261.264s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.263s  |1262.263s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.982s  |1260.982s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.444s  |1261.444s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.220s  |1262.220s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.928s  |1261.928s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 232.996s  | 232.996s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.469s  |1260.469s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.870s  |1262.870s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 339.064s  | 339.064s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 375.338s  | 375.338s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.398s  |1260.398s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.386s  |1260.386s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.370s  |1260.370s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.382s  |1260.382s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.066s  |1260.066s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.599s  |1261.599s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1260.116s  |1260.116s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 640.727s  | 640.727s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.264s  |1261.264s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.263s  |1262.263s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.982s  |1260.982s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.444s  |1261.444s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.220s  |1262.220s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.928s  |1261.928s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 232.996s  | 232.996s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.469s  |1260.469s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.870s  |1262.870s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 339.064s  | 339.064s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 375.338s  | 375.338s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.398s  |1260.398s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.386s  |1260.386s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.370s  |1260.370s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.382s  |1260.382s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.066s  |1260.066s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.599s  |1261.599s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1260.116s  |1260.116s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 640.727s  | 640.727s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.264s  |1261.264s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.263s  |1262.263s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.982s  |1260.982s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.444s  |1261.444s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.220s  |1262.220s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.928s  |1261.928s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 232.996s  | 232.996s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.469s  |1260.469s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.870s  |1262.870s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 339.064s  | 339.064s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 375.338s  | 375.338s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.398s  |1260.398s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.386s  |1260.386s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.370s  |1260.370s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.382s  |1260.382s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.066s  |1260.066s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.599s  |1261.599s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1260.116s  |1260.116s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 640.727s  | 640.727s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.264s  |1261.264s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.301s |31.353GiB|
|scrambled4198.smt2                                                                         |1262.941s |25.24GiB|
|scrambled12042.smt2                                                                        |1262.870s |29.951GiB|
|scrambled4299.smt2                                                                         |1262.447s |25.643GiB|
|scrambled55680.smt2                                                                        |1262.407s |25.034GiB|
|scrambled68944.smt2                                                                        |1262.322s |23.367GiB|
|scrambled102166.smt2                                                                       |1262.263s |23.481GiB|
|scrambled108840.smt2                                                                       |1262.220s |22.259GiB|
|scrambled79760.smt2                                                                        |1262.151s |21.892GiB|
|scrambled111627.smt2                                                                       |1261.928s |18.976GiB|
|scrambled75189.smt2                                                                        |1261.757s |17.036GiB|
|scrambled19335.smt2                                                                        |1261.599s |15.599GiB|
|scrambled43577.smt2                                                                        |1261.590s |15.333GiB|
|scrambled107826.smt2                                                                       |1261.444s |14.244GiB|
|scrambled27843.smt2                                                                        |1261.264s |11.142GiB|
|scrambled107115.smt2                                                                       |1260.982s |8691.0MiB|
|scrambled61922.smt2                                                                        |1260.921s |5568.0MiB|
|scrambled40621.smt2                                                                        |1260.605s |4269.0MiB|
|scrambled119331.smt2                                                                       |1260.469s |3558.0MiB|
|scrambled7741.smt2                                                                         |1260.460s |2711.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.301s |31.353GiB|
|scrambled4198.smt2                                                                         |1262.941s |25.24GiB|
|scrambled12042.smt2                                                                        |1262.870s |29.951GiB|
|scrambled4299.smt2                                                                         |1262.447s |25.643GiB|
|scrambled55680.smt2                                                                        |1262.407s |25.034GiB|
|scrambled68944.smt2                                                                        |1262.322s |23.367GiB|
|scrambled102166.smt2                                                                       |1262.263s |23.481GiB|
|scrambled108840.smt2                                                                       |1262.220s |22.259GiB|
|scrambled79760.smt2                                                                        |1262.151s |21.892GiB|
|scrambled111627.smt2                                                                       |1261.928s |18.976GiB|
|scrambled75189.smt2                                                                        |1261.757s |17.036GiB|
|scrambled19335.smt2                                                                        |1261.599s |15.599GiB|
|scrambled43577.smt2                                                                        |1261.590s |15.333GiB|
|scrambled107826.smt2                                                                       |1261.444s |14.244GiB|
|scrambled27843.smt2                                                                        |1261.264s |11.142GiB|
|scrambled107115.smt2                                                                       |1260.982s |8691.0MiB|
|scrambled61922.smt2                                                                        |1260.921s |5568.0MiB|
|scrambled40621.smt2                                                                        |1260.605s |4269.0MiB|
|scrambled119331.smt2                                                                       |1260.469s |3558.0MiB|
|scrambled7741.smt2                                                                         |1260.460s |2711.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.481GiB|23.481GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8691.0MiB|8691.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.244GiB|14.244GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.259GiB|22.259GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.976GiB|18.976GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |385.0MiB|385.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3558.0MiB|3558.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.951GiB|29.951GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |410.0MiB|410.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |644.0MiB|644.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2578.0MiB|2578.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1954.0MiB|1954.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2118.0MiB|2118.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2595.0MiB|2595.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |161.0MiB|161.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.599GiB|15.599GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |714.0MiB|714.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2836.0MiB|2836.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.142GiB|11.142GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.481GiB|23.481GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8691.0MiB|8691.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.244GiB|14.244GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.259GiB|22.259GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.976GiB|18.976GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |385.0MiB|385.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3558.0MiB|3558.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.951GiB|29.951GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |410.0MiB|410.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |644.0MiB|644.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2578.0MiB|2578.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1954.0MiB|1954.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2118.0MiB|2118.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2595.0MiB|2595.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |161.0MiB|161.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.599GiB|15.599GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |714.0MiB|714.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2836.0MiB|2836.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.142GiB|11.142GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.481GiB|23.481GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8691.0MiB|8691.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.244GiB|14.244GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.259GiB|22.259GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.976GiB|18.976GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |385.0MiB|385.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3558.0MiB|3558.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.951GiB|29.951GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |410.0MiB|410.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |644.0MiB|644.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2578.0MiB|2578.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1954.0MiB|1954.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2118.0MiB|2118.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2595.0MiB|2595.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |161.0MiB|161.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.599GiB|15.599GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |714.0MiB|714.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2836.0MiB|2836.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.142GiB|11.142GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.481GiB|23.481GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8691.0MiB|8691.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.244GiB|14.244GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.259GiB|22.259GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.976GiB|18.976GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |385.0MiB|385.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3558.0MiB|3558.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.951GiB|29.951GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |410.0MiB|410.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |644.0MiB|644.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2578.0MiB|2578.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1954.0MiB|1954.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2118.0MiB|2118.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2595.0MiB|2595.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |161.0MiB|161.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.599GiB|15.599GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |714.0MiB|714.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2836.0MiB|2836.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.142GiB|11.142GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.301s |31.353GiB|
|scrambled12042.smt2                                                                        |1262.870s |29.951GiB|
|scrambled4299.smt2                                                                         |1262.447s |25.643GiB|
|scrambled4198.smt2                                                                         |1262.941s |25.24GiB|
|scrambled55680.smt2                                                                        |1262.407s |25.034GiB|
|scrambled102166.smt2                                                                       |1262.263s |23.481GiB|
|scrambled68944.smt2                                                                        |1262.322s |23.367GiB|
|scrambled108840.smt2                                                                       |1262.220s |22.259GiB|
|scrambled79760.smt2                                                                        |1262.151s |21.892GiB|
|scrambled111627.smt2                                                                       |1261.928s |18.976GiB|
|scrambled75189.smt2                                                                        |1261.757s |17.036GiB|
|scrambled19335.smt2                                                                        |1261.599s |15.599GiB|
|scrambled43577.smt2                                                                        |1261.590s |15.333GiB|
|scrambled107826.smt2                                                                       |1261.444s |14.244GiB|
|scrambled27843.smt2                                                                        |1261.264s |11.142GiB|
|scrambled107115.smt2                                                                       |1260.982s |8691.0MiB|
|scrambled61922.smt2                                                                        |1260.921s |5568.0MiB|
|scrambled40621.smt2                                                                        |1260.605s |4269.0MiB|
|scrambled119331.smt2                                                                       |1260.469s |3558.0MiB|
|scrambled25238.smt2                                                                        | 640.727s |2836.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.301s |31.353GiB|
|scrambled12042.smt2                                                                        |1262.870s |29.951GiB|
|scrambled4299.smt2                                                                         |1262.447s |25.643GiB|
|scrambled4198.smt2                                                                         |1262.941s |25.24GiB|
|scrambled55680.smt2                                                                        |1262.407s |25.034GiB|
|scrambled102166.smt2                                                                       |1262.263s |23.481GiB|
|scrambled68944.smt2                                                                        |1262.322s |23.367GiB|
|scrambled108840.smt2                                                                       |1262.220s |22.259GiB|
|scrambled79760.smt2                                                                        |1262.151s |21.892GiB|
|scrambled111627.smt2                                                                       |1261.928s |18.976GiB|
|scrambled75189.smt2                                                                        |1261.757s |17.036GiB|
|scrambled19335.smt2                                                                        |1261.599s |15.599GiB|
|scrambled43577.smt2                                                                        |1261.590s |15.333GiB|
|scrambled107826.smt2                                                                       |1261.444s |14.244GiB|
|scrambled27843.smt2                                                                        |1261.264s |11.142GiB|
|scrambled107115.smt2                                                                       |1260.982s |8691.0MiB|
|scrambled61922.smt2                                                                        |1260.921s |5568.0MiB|
|scrambled40621.smt2                                                                        |1260.605s |4269.0MiB|
|scrambled119331.smt2                                                                       |1260.469s |3558.0MiB|
|scrambled25238.smt2                                                                        | 640.727s |2836.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.263s  |1262.263s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.982s  |1260.982s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.444s  |1261.444s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.220s  |1262.220s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.928s  |1261.928s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 232.996s  | 232.996s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.469s  |1260.469s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.870s  |1262.870s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 339.064s  | 339.064s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 375.338s  | 375.338s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.398s  |1260.398s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.386s  |1260.386s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.370s  |1260.370s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.382s  |1260.382s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.066s  |1260.066s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.599s  |1261.599s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1260.116s  |1260.116s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 640.727s  | 640.727s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.264s  |1261.264s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1260.194s  |1260.194s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1260.029s  |1260.029s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1260.116s  |1260.116s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1260.605s  |1260.605s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1262.941s  |1262.941s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1262.447s  |1262.447s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1261.590s  |1261.590s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1260.410s  |1260.410s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1260.030s  |1260.030s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1260.239s  |1260.239s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1262.407s  |1262.407s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1260.201s  |1260.201s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1260.035s  |1260.035s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1260.921s  |1260.921s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1260.030s  |1260.030s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1262.322s  |1262.322s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1260.251s  |1260.251s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1261.757s  |1261.757s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1260.460s  |1260.460s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1262.151s  |1262.151s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1260.033s  |1260.033s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1263.301s  |1263.301s  |   0.000s  | 0.0%|
</details>
