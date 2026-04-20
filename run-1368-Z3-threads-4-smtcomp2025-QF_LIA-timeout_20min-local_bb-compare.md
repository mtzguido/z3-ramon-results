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
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-local_bb
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bdff96fde97215ca1c28b4d30df7a4a20cbfc050
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.local_backbones=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: undo local bb ablation about resetting phase/activities, and reinstate the shared lemmas of length 2 and 3 experiment

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-local_bb
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bdff96fde97215ca1c28b4d30df7a4a20cbfc050
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.local_backbones=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: undo local bb ablation about resetting phase/activities, and reinstate the shared lemmas of length 2 and 3 experiment

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.409s  |1262.409s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.036s  |1260.036s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.048s  |1261.048s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.632s  |1261.632s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.386s  |1262.386s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.063s  |1262.063s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 601.349s  | 601.349s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.549s  |1260.549s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.009s  |1263.009s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 113.420s  | 113.420s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  63.487s  |  63.487s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.430s  |1260.430s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.405s  |1260.405s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.351s  |1260.351s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.536s  |1260.536s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.652s  |1261.652s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 437.276s  | 437.276s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 975.750s  | 975.750s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.699s  |1261.699s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.409s  |1262.409s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.036s  |1260.036s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.048s  |1261.048s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.632s  |1261.632s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.386s  |1262.386s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.063s  |1262.063s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 601.349s  | 601.349s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.549s  |1260.549s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.009s  |1263.009s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 113.420s  | 113.420s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  63.487s  |  63.487s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.430s  |1260.430s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.405s  |1260.405s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.351s  |1260.351s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.536s  |1260.536s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.652s  |1261.652s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 437.276s  | 437.276s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 975.750s  | 975.750s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.699s  |1261.699s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.409s  |1262.409s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.036s  |1260.036s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.048s  |1261.048s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.632s  |1261.632s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.386s  |1262.386s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.063s  |1262.063s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 601.349s  | 601.349s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.549s  |1260.549s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.009s  |1263.009s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 113.420s  | 113.420s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  63.487s  |  63.487s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.430s  |1260.430s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.405s  |1260.405s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.351s  |1260.351s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.536s  |1260.536s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.652s  |1261.652s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 437.276s  | 437.276s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 975.750s  | 975.750s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.699s  |1261.699s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.409s  |1262.409s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.036s  |1260.036s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.048s  |1261.048s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.632s  |1261.632s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.386s  |1262.386s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.063s  |1262.063s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 601.349s  | 601.349s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.549s  |1260.549s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.009s  |1263.009s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 113.420s  | 113.420s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  63.487s  |  63.487s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.430s  |1260.430s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.405s  |1260.405s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.351s  |1260.351s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.536s  |1260.536s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.652s  |1261.652s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 437.276s  | 437.276s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 975.750s  | 975.750s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.699s  |1261.699s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1264.165s |31.38GiB|
|scrambled12042.smt2                                                                        |1263.009s |29.83GiB|
|scrambled4299.smt2                                                                         |1262.594s |26.197GiB|
|scrambled55680.smt2                                                                        |1262.580s |24.856GiB|
|scrambled102166.smt2                                                                       |1262.409s |23.481GiB|
|scrambled108840.smt2                                                                       |1262.386s |22.296GiB|
|scrambled68944.smt2                                                                        |1262.365s |22.766GiB|
|scrambled79760.smt2                                                                        |1262.353s |21.912GiB|
|scrambled4198.smt2                                                                         |1262.159s |24.776GiB|
|scrambled111627.smt2                                                                       |1262.063s |18.962GiB|
|scrambled75189.smt2                                                                        |1261.957s |17.039GiB|
|scrambled43577.smt2                                                                        |1261.726s |15.333GiB|
|scrambled27843.smt2                                                                        |1261.699s |11.144GiB|
|scrambled19335.smt2                                                                        |1261.652s |15.63GiB|
|scrambled107826.smt2                                                                       |1261.632s |14.244GiB|
|scrambled107115.smt2                                                                       |1261.048s |8687.0MiB|
|scrambled61922.smt2                                                                        |1261.026s |5568.0MiB|
|scrambled40621.smt2                                                                        |1260.628s |4289.0MiB|
|scrambled119331.smt2                                                                       |1260.549s |3861.0MiB|
|scrambled131241.smt2                                                                       |1260.536s |2569.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1264.165s |31.38GiB|
|scrambled12042.smt2                                                                        |1263.009s |29.83GiB|
|scrambled4299.smt2                                                                         |1262.594s |26.197GiB|
|scrambled55680.smt2                                                                        |1262.580s |24.856GiB|
|scrambled102166.smt2                                                                       |1262.409s |23.481GiB|
|scrambled108840.smt2                                                                       |1262.386s |22.296GiB|
|scrambled68944.smt2                                                                        |1262.365s |22.766GiB|
|scrambled79760.smt2                                                                        |1262.353s |21.912GiB|
|scrambled4198.smt2                                                                         |1262.159s |24.776GiB|
|scrambled111627.smt2                                                                       |1262.063s |18.962GiB|
|scrambled75189.smt2                                                                        |1261.957s |17.039GiB|
|scrambled43577.smt2                                                                        |1261.726s |15.333GiB|
|scrambled27843.smt2                                                                        |1261.699s |11.144GiB|
|scrambled19335.smt2                                                                        |1261.652s |15.63GiB|
|scrambled107826.smt2                                                                       |1261.632s |14.244GiB|
|scrambled107115.smt2                                                                       |1261.048s |8687.0MiB|
|scrambled61922.smt2                                                                        |1261.026s |5568.0MiB|
|scrambled40621.smt2                                                                        |1260.628s |4289.0MiB|
|scrambled119331.smt2                                                                       |1260.549s |3861.0MiB|
|scrambled131241.smt2                                                                       |1260.536s |2569.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.481GiB|23.481GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.3MiB|42.3MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8687.0MiB|8687.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.244GiB|14.244GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.296GiB|22.296GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.962GiB|18.962GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |414.0MiB|414.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3861.0MiB|3861.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.83GiB|29.83GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |414.0MiB|414.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |620.0MiB|620.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2498.0MiB|2498.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2095.0MiB|2095.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2002.0MiB|2002.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2569.0MiB|2569.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |162.0MiB|162.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.63GiB|15.63GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |696.0MiB|696.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2984.0MiB|2984.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.144GiB|11.144GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.481GiB|23.481GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.3MiB|42.3MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8687.0MiB|8687.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.244GiB|14.244GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.296GiB|22.296GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.962GiB|18.962GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |414.0MiB|414.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3861.0MiB|3861.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.83GiB|29.83GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |414.0MiB|414.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |620.0MiB|620.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2498.0MiB|2498.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2095.0MiB|2095.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2002.0MiB|2002.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2569.0MiB|2569.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |162.0MiB|162.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.63GiB|15.63GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |696.0MiB|696.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2984.0MiB|2984.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.144GiB|11.144GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.481GiB|23.481GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.3MiB|42.3MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8687.0MiB|8687.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.244GiB|14.244GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.296GiB|22.296GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.962GiB|18.962GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |414.0MiB|414.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3861.0MiB|3861.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.83GiB|29.83GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |414.0MiB|414.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |620.0MiB|620.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2498.0MiB|2498.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2095.0MiB|2095.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2002.0MiB|2002.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2569.0MiB|2569.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |162.0MiB|162.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.63GiB|15.63GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |696.0MiB|696.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2984.0MiB|2984.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.144GiB|11.144GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.481GiB|23.481GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.3MiB|42.3MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8687.0MiB|8687.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.244GiB|14.244GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.296GiB|22.296GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.962GiB|18.962GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |414.0MiB|414.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3861.0MiB|3861.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.83GiB|29.83GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |414.0MiB|414.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |620.0MiB|620.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2498.0MiB|2498.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2095.0MiB|2095.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2002.0MiB|2002.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2569.0MiB|2569.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |162.0MiB|162.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.63GiB|15.63GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |696.0MiB|696.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2984.0MiB|2984.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.144GiB|11.144GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1264.165s |31.38GiB|
|scrambled12042.smt2                                                                        |1263.009s |29.83GiB|
|scrambled4299.smt2                                                                         |1262.594s |26.197GiB|
|scrambled55680.smt2                                                                        |1262.580s |24.856GiB|
|scrambled4198.smt2                                                                         |1262.159s |24.776GiB|
|scrambled102166.smt2                                                                       |1262.409s |23.481GiB|
|scrambled68944.smt2                                                                        |1262.365s |22.766GiB|
|scrambled108840.smt2                                                                       |1262.386s |22.296GiB|
|scrambled79760.smt2                                                                        |1262.353s |21.912GiB|
|scrambled111627.smt2                                                                       |1262.063s |18.962GiB|
|scrambled75189.smt2                                                                        |1261.957s |17.039GiB|
|scrambled19335.smt2                                                                        |1261.652s |15.63GiB|
|scrambled43577.smt2                                                                        |1261.726s |15.333GiB|
|scrambled107826.smt2                                                                       |1261.632s |14.244GiB|
|scrambled27843.smt2                                                                        |1261.699s |11.144GiB|
|scrambled107115.smt2                                                                       |1261.048s |8687.0MiB|
|scrambled61922.smt2                                                                        |1261.026s |5568.0MiB|
|scrambled40621.smt2                                                                        |1260.628s |4289.0MiB|
|scrambled119331.smt2                                                                       |1260.549s |3861.0MiB|
|scrambled25238.smt2                                                                        | 975.750s |2984.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1264.165s |31.38GiB|
|scrambled12042.smt2                                                                        |1263.009s |29.83GiB|
|scrambled4299.smt2                                                                         |1262.594s |26.197GiB|
|scrambled55680.smt2                                                                        |1262.580s |24.856GiB|
|scrambled4198.smt2                                                                         |1262.159s |24.776GiB|
|scrambled102166.smt2                                                                       |1262.409s |23.481GiB|
|scrambled68944.smt2                                                                        |1262.365s |22.766GiB|
|scrambled108840.smt2                                                                       |1262.386s |22.296GiB|
|scrambled79760.smt2                                                                        |1262.353s |21.912GiB|
|scrambled111627.smt2                                                                       |1262.063s |18.962GiB|
|scrambled75189.smt2                                                                        |1261.957s |17.039GiB|
|scrambled19335.smt2                                                                        |1261.652s |15.63GiB|
|scrambled43577.smt2                                                                        |1261.726s |15.333GiB|
|scrambled107826.smt2                                                                       |1261.632s |14.244GiB|
|scrambled27843.smt2                                                                        |1261.699s |11.144GiB|
|scrambled107115.smt2                                                                       |1261.048s |8687.0MiB|
|scrambled61922.smt2                                                                        |1261.026s |5568.0MiB|
|scrambled40621.smt2                                                                        |1260.628s |4289.0MiB|
|scrambled119331.smt2                                                                       |1260.549s |3861.0MiB|
|scrambled25238.smt2                                                                        | 975.750s |2984.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.409s  |1262.409s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.036s  |1260.036s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.048s  |1261.048s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.632s  |1261.632s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.386s  |1262.386s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.063s  |1262.063s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 601.349s  | 601.349s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.549s  |1260.549s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.009s  |1263.009s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 113.420s  | 113.420s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  63.487s  |  63.487s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.430s  |1260.430s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.405s  |1260.405s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.351s  |1260.351s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.536s  |1260.536s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.652s  |1261.652s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 437.276s  | 437.276s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 975.750s  | 975.750s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.699s  |1261.699s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1260.275s  |1260.275s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1260.025s  |1260.025s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1260.035s  |1260.035s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1260.628s  |1260.628s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1262.159s  |1262.159s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1262.594s  |1262.594s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1261.726s  |1261.726s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1260.319s  |1260.319s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1260.026s  |1260.026s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1260.290s  |1260.290s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1262.580s  |1262.580s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1260.171s  |1260.171s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1260.035s  |1260.035s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1261.026s  |1261.026s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1260.035s  |1260.035s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1262.365s  |1262.365s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1260.442s  |1260.442s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1261.957s  |1261.957s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1260.462s  |1260.462s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1262.353s  |1262.353s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1260.037s  |1260.037s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1260.036s  |1260.036s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1264.165s  |1264.165s  |   0.000s  | 0.0%|
</details>
