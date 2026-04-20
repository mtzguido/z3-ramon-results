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
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min_bb1
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6b8cb1099d311aac105cfc6fa658466f4ef6af67
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=1"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore unrelated code to master

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min_bb1
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6b8cb1099d311aac105cfc6fa658466f4ef6af67
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=1"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore unrelated code to master

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.380s  |1262.380s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.013s  |1260.013s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.079s  |1261.079s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.552s  |1261.552s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.784s  |1262.784s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.756s  |1261.756s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 111.173s  | 111.173s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.629s  |1260.629s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.119s  |1263.119s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 165.681s  | 165.681s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 318.656s  | 318.656s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.419s  |1260.419s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        | 949.638s  | 949.638s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.447s  |1260.447s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.512s  |1260.512s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.061s  |1260.061s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.720s  |1261.720s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 167.040s  | 167.040s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 991.332s  | 991.332s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.591s  |1261.591s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.380s  |1262.380s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.013s  |1260.013s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.079s  |1261.079s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.552s  |1261.552s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.784s  |1262.784s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.756s  |1261.756s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 111.173s  | 111.173s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.629s  |1260.629s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.119s  |1263.119s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 165.681s  | 165.681s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 318.656s  | 318.656s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.419s  |1260.419s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        | 949.638s  | 949.638s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.447s  |1260.447s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.512s  |1260.512s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.061s  |1260.061s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.720s  |1261.720s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 167.040s  | 167.040s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 991.332s  | 991.332s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.591s  |1261.591s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.380s  |1262.380s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.013s  |1260.013s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.079s  |1261.079s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.552s  |1261.552s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.784s  |1262.784s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.756s  |1261.756s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 111.173s  | 111.173s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.629s  |1260.629s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.119s  |1263.119s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 165.681s  | 165.681s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 318.656s  | 318.656s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.419s  |1260.419s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        | 949.638s  | 949.638s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.447s  |1260.447s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.512s  |1260.512s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.061s  |1260.061s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.720s  |1261.720s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 167.040s  | 167.040s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 991.332s  | 991.332s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.591s  |1261.591s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.380s  |1262.380s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.013s  |1260.013s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.079s  |1261.079s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.552s  |1261.552s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.784s  |1262.784s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.756s  |1261.756s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 111.173s  | 111.173s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.629s  |1260.629s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.119s  |1263.119s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 165.681s  | 165.681s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 318.656s  | 318.656s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.419s  |1260.419s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        | 949.638s  | 949.638s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.447s  |1260.447s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.512s  |1260.512s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.061s  |1260.061s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.720s  |1261.720s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 167.040s  | 167.040s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 991.332s  | 991.332s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.591s  |1261.591s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.577s |31.664GiB|
|scrambled12042.smt2                                                                        |1263.119s |30.92GiB|
|scrambled4198.smt2                                                                         |1263.109s |25.134GiB|
|scrambled108840.smt2                                                                       |1262.784s |22.874GiB|
|scrambled4299.smt2                                                                         |1262.742s |26.869GiB|
|scrambled55680.smt2                                                                        |1262.671s |25.727GiB|
|scrambled102166.smt2                                                                       |1262.380s |24.175GiB|
|scrambled79760.smt2                                                                        |1262.364s |22.812GiB|
|scrambled68944.smt2                                                                        |1262.187s |24.856GiB|
|scrambled75189.smt2                                                                        |1261.811s |17.507GiB|
|scrambled111627.smt2                                                                       |1261.756s |20.312GiB|
|scrambled19335.smt2                                                                        |1261.720s |16.152GiB|
|scrambled43577.smt2                                                                        |1261.643s |15.764GiB|
|scrambled27843.smt2                                                                        |1261.591s |11.349GiB|
|scrambled107826.smt2                                                                       |1261.552s |14.789GiB|
|scrambled107115.smt2                                                                       |1261.079s |8882.0MiB|
|scrambled40621.smt2                                                                        |1260.778s |5576.0MiB|
|scrambled61922.smt2                                                                        |1260.704s |5673.0MiB|
|scrambled119331.smt2                                                                       |1260.629s |4823.0MiB|
|scrambled72668.smt2                                                                        |1260.596s |2630.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.577s |31.664GiB|
|scrambled12042.smt2                                                                        |1263.119s |30.92GiB|
|scrambled4198.smt2                                                                         |1263.109s |25.134GiB|
|scrambled108840.smt2                                                                       |1262.784s |22.874GiB|
|scrambled4299.smt2                                                                         |1262.742s |26.869GiB|
|scrambled55680.smt2                                                                        |1262.671s |25.727GiB|
|scrambled102166.smt2                                                                       |1262.380s |24.175GiB|
|scrambled79760.smt2                                                                        |1262.364s |22.812GiB|
|scrambled68944.smt2                                                                        |1262.187s |24.856GiB|
|scrambled75189.smt2                                                                        |1261.811s |17.507GiB|
|scrambled111627.smt2                                                                       |1261.756s |20.312GiB|
|scrambled19335.smt2                                                                        |1261.720s |16.152GiB|
|scrambled43577.smt2                                                                        |1261.643s |15.764GiB|
|scrambled27843.smt2                                                                        |1261.591s |11.349GiB|
|scrambled107826.smt2                                                                       |1261.552s |14.789GiB|
|scrambled107115.smt2                                                                       |1261.079s |8882.0MiB|
|scrambled40621.smt2                                                                        |1260.778s |5576.0MiB|
|scrambled61922.smt2                                                                        |1260.704s |5673.0MiB|
|scrambled119331.smt2                                                                       |1260.629s |4823.0MiB|
|scrambled72668.smt2                                                                        |1260.596s |2630.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.175GiB|24.175GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.696MiB|42.696MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8882.0MiB|8882.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.789GiB|14.789GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.874GiB|22.874GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |20.312GiB|20.312GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |466.0MiB|466.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |4823.0MiB|4823.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |30.92GiB|30.92GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |505.0MiB|505.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |823.0MiB|823.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3255.0MiB|3255.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2414.0MiB|2414.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2648.0MiB|2648.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3232.0MiB|3232.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |190.0MiB|190.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.152GiB|16.152GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |820.0MiB|820.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3700.0MiB|3700.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.349GiB|11.349GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.175GiB|24.175GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.696MiB|42.696MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8882.0MiB|8882.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.789GiB|14.789GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.874GiB|22.874GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |20.312GiB|20.312GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |466.0MiB|466.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |4823.0MiB|4823.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |30.92GiB|30.92GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |505.0MiB|505.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |823.0MiB|823.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3255.0MiB|3255.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2414.0MiB|2414.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2648.0MiB|2648.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3232.0MiB|3232.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |190.0MiB|190.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.152GiB|16.152GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |820.0MiB|820.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3700.0MiB|3700.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.349GiB|11.349GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.175GiB|24.175GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.696MiB|42.696MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8882.0MiB|8882.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.789GiB|14.789GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.874GiB|22.874GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |20.312GiB|20.312GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |466.0MiB|466.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |4823.0MiB|4823.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |30.92GiB|30.92GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |505.0MiB|505.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |823.0MiB|823.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3255.0MiB|3255.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2414.0MiB|2414.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2648.0MiB|2648.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3232.0MiB|3232.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |190.0MiB|190.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.152GiB|16.152GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |820.0MiB|820.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3700.0MiB|3700.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.349GiB|11.349GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.175GiB|24.175GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.696MiB|42.696MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8882.0MiB|8882.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.789GiB|14.789GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.874GiB|22.874GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |20.312GiB|20.312GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |466.0MiB|466.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |4823.0MiB|4823.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |30.92GiB|30.92GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |505.0MiB|505.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |823.0MiB|823.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3255.0MiB|3255.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2414.0MiB|2414.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2648.0MiB|2648.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3232.0MiB|3232.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |190.0MiB|190.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.152GiB|16.152GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |820.0MiB|820.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3700.0MiB|3700.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.349GiB|11.349GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.577s |31.664GiB|
|scrambled12042.smt2                                                                        |1263.119s |30.92GiB|
|scrambled4299.smt2                                                                         |1262.742s |26.869GiB|
|scrambled55680.smt2                                                                        |1262.671s |25.727GiB|
|scrambled4198.smt2                                                                         |1263.109s |25.134GiB|
|scrambled68944.smt2                                                                        |1262.187s |24.856GiB|
|scrambled102166.smt2                                                                       |1262.380s |24.175GiB|
|scrambled108840.smt2                                                                       |1262.784s |22.874GiB|
|scrambled79760.smt2                                                                        |1262.364s |22.812GiB|
|scrambled111627.smt2                                                                       |1261.756s |20.312GiB|
|scrambled75189.smt2                                                                        |1261.811s |17.507GiB|
|scrambled19335.smt2                                                                        |1261.720s |16.152GiB|
|scrambled43577.smt2                                                                        |1261.643s |15.764GiB|
|scrambled107826.smt2                                                                       |1261.552s |14.789GiB|
|scrambled27843.smt2                                                                        |1261.591s |11.349GiB|
|scrambled107115.smt2                                                                       |1261.079s |8882.0MiB|
|scrambled61922.smt2                                                                        |1260.704s |5673.0MiB|
|scrambled40621.smt2                                                                        |1260.778s |5576.0MiB|
|scrambled119331.smt2                                                                       |1260.629s |4823.0MiB|
|scrambled25238.smt2                                                                        | 991.332s |3700.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.577s |31.664GiB|
|scrambled12042.smt2                                                                        |1263.119s |30.92GiB|
|scrambled4299.smt2                                                                         |1262.742s |26.869GiB|
|scrambled55680.smt2                                                                        |1262.671s |25.727GiB|
|scrambled4198.smt2                                                                         |1263.109s |25.134GiB|
|scrambled68944.smt2                                                                        |1262.187s |24.856GiB|
|scrambled102166.smt2                                                                       |1262.380s |24.175GiB|
|scrambled108840.smt2                                                                       |1262.784s |22.874GiB|
|scrambled79760.smt2                                                                        |1262.364s |22.812GiB|
|scrambled111627.smt2                                                                       |1261.756s |20.312GiB|
|scrambled75189.smt2                                                                        |1261.811s |17.507GiB|
|scrambled19335.smt2                                                                        |1261.720s |16.152GiB|
|scrambled43577.smt2                                                                        |1261.643s |15.764GiB|
|scrambled107826.smt2                                                                       |1261.552s |14.789GiB|
|scrambled27843.smt2                                                                        |1261.591s |11.349GiB|
|scrambled107115.smt2                                                                       |1261.079s |8882.0MiB|
|scrambled61922.smt2                                                                        |1260.704s |5673.0MiB|
|scrambled40621.smt2                                                                        |1260.778s |5576.0MiB|
|scrambled119331.smt2                                                                       |1260.629s |4823.0MiB|
|scrambled25238.smt2                                                                        | 991.332s |3700.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.380s  |1262.380s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.013s  |1260.013s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.079s  |1261.079s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.552s  |1261.552s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.784s  |1262.784s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.756s  |1261.756s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 111.173s  | 111.173s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.629s  |1260.629s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.119s  |1263.119s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 165.681s  | 165.681s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 318.656s  | 318.656s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.419s  |1260.419s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        | 949.638s  | 949.638s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.447s  |1260.447s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.512s  |1260.512s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.061s  |1260.061s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.720s  |1261.720s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 167.040s  | 167.040s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 991.332s  | 991.332s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.591s  |1261.591s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 560.452s  | 560.452s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1260.036s  |1260.036s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1260.014s  |1260.014s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1260.778s  |1260.778s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1263.109s  |1263.109s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1262.742s  |1262.742s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1261.643s  |1261.643s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1260.485s  |1260.485s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1260.025s  |1260.025s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1260.180s  |1260.180s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1262.671s  |1262.671s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1260.356s  |1260.356s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1260.016s  |1260.016s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1260.704s  |1260.704s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1260.038s  |1260.038s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1262.187s  |1262.187s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1260.596s  |1260.596s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1261.811s  |1261.811s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1260.577s  |1260.577s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1262.364s  |1262.364s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1260.036s  |1260.036s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1260.038s  |1260.038s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1263.577s  |1263.577s  |   0.000s  | 0.0%|
</details>
