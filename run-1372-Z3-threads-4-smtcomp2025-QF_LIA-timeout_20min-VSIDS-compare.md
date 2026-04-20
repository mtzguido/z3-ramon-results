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
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-VSIDS
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: c5aca49e70b70d2369035ad83eb4c9ad36027da1
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: change split policy from lightweight proof skeleton to VSIDS. NOTE: enabling local bb will mess with this since we aren't restoring activities right now

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-VSIDS
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: c5aca49e70b70d2369035ad83eb4c9ad36027da1
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: change split policy from lightweight proof skeleton to VSIDS. NOTE: enabling local bb will mess with this since we aren't restoring activities right now

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.386s  |1262.386s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.027s  |1261.027s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.700s  |1261.700s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.253s  |1262.253s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.963s  |1261.963s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  63.813s  |  63.813s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.707s  |1260.707s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.926s  |1262.926s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1023.077s  |1023.077s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 204.575s  | 204.575s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.550s  |1260.550s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.488s  |1260.488s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.349s  |1260.349s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.611s  |1260.611s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.087s  |1260.087s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.678s  |1261.678s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 446.041s  | 446.041s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 927.819s  | 927.819s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.827s  |1261.827s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.386s  |1262.386s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.027s  |1261.027s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.700s  |1261.700s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.253s  |1262.253s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.963s  |1261.963s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  63.813s  |  63.813s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.707s  |1260.707s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.926s  |1262.926s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1023.077s  |1023.077s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 204.575s  | 204.575s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.550s  |1260.550s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.488s  |1260.488s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.349s  |1260.349s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.611s  |1260.611s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.087s  |1260.087s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.678s  |1261.678s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 446.041s  | 446.041s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 927.819s  | 927.819s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.827s  |1261.827s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.386s  |1262.386s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.027s  |1261.027s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.700s  |1261.700s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.253s  |1262.253s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.963s  |1261.963s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  63.813s  |  63.813s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.707s  |1260.707s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.926s  |1262.926s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1023.077s  |1023.077s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 204.575s  | 204.575s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.550s  |1260.550s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.488s  |1260.488s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.349s  |1260.349s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.611s  |1260.611s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.087s  |1260.087s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.678s  |1261.678s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 446.041s  | 446.041s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 927.819s  | 927.819s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.827s  |1261.827s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.386s  |1262.386s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.027s  |1261.027s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.700s  |1261.700s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.253s  |1262.253s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.963s  |1261.963s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  63.813s  |  63.813s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.707s  |1260.707s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.926s  |1262.926s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1023.077s  |1023.077s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 204.575s  | 204.575s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.550s  |1260.550s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.488s  |1260.488s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.349s  |1260.349s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.611s  |1260.611s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.087s  |1260.087s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.678s  |1261.678s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 446.041s  | 446.041s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 927.819s  | 927.819s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.827s  |1261.827s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.200s |31.382GiB|
|scrambled12042.smt2                                                                        |1262.926s |29.965GiB|
|scrambled55680.smt2                                                                        |1262.683s |24.99GiB|
|scrambled4299.smt2                                                                         |1262.542s |25.395GiB|
|scrambled102166.smt2                                                                       |1262.386s |23.383GiB|
|scrambled79760.smt2                                                                        |1262.385s |21.872GiB|
|scrambled4198.smt2                                                                         |1262.313s |26.309GiB|
|scrambled68944.smt2                                                                        |1262.297s |22.57GiB|
|scrambled108840.smt2                                                                       |1262.253s |22.187GiB|
|scrambled75189.smt2                                                                        |1261.974s |17.036GiB|
|scrambled111627.smt2                                                                       |1261.963s |18.972GiB|
|scrambled43577.smt2                                                                        |1261.830s |15.286GiB|
|scrambled27843.smt2                                                                        |1261.827s |11.107GiB|
|scrambled107826.smt2                                                                       |1261.700s |14.247GiB|
|scrambled19335.smt2                                                                        |1261.678s |15.596GiB|
|scrambled107115.smt2                                                                       |1261.027s |8688.0MiB|
|scrambled61922.smt2                                                                        |1260.726s |5569.0MiB|
|scrambled119331.smt2                                                                       |1260.707s |3803.0MiB|
|scrambled131241.smt2                                                                       |1260.611s |2572.0MiB|
|scrambled40621.smt2                                                                        |1260.605s |4657.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.200s |31.382GiB|
|scrambled12042.smt2                                                                        |1262.926s |29.965GiB|
|scrambled55680.smt2                                                                        |1262.683s |24.99GiB|
|scrambled4299.smt2                                                                         |1262.542s |25.395GiB|
|scrambled102166.smt2                                                                       |1262.386s |23.383GiB|
|scrambled79760.smt2                                                                        |1262.385s |21.872GiB|
|scrambled4198.smt2                                                                         |1262.313s |26.309GiB|
|scrambled68944.smt2                                                                        |1262.297s |22.57GiB|
|scrambled108840.smt2                                                                       |1262.253s |22.187GiB|
|scrambled75189.smt2                                                                        |1261.974s |17.036GiB|
|scrambled111627.smt2                                                                       |1261.963s |18.972GiB|
|scrambled43577.smt2                                                                        |1261.830s |15.286GiB|
|scrambled27843.smt2                                                                        |1261.827s |11.107GiB|
|scrambled107826.smt2                                                                       |1261.700s |14.247GiB|
|scrambled19335.smt2                                                                        |1261.678s |15.596GiB|
|scrambled107115.smt2                                                                       |1261.027s |8688.0MiB|
|scrambled61922.smt2                                                                        |1260.726s |5569.0MiB|
|scrambled119331.smt2                                                                       |1260.707s |3803.0MiB|
|scrambled131241.smt2                                                                       |1260.611s |2572.0MiB|
|scrambled40621.smt2                                                                        |1260.605s |4657.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.383GiB|23.383GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8688.0MiB|8688.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.247GiB|14.247GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.187GiB|22.187GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.972GiB|18.972GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |360.0MiB|360.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3803.0MiB|3803.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.965GiB|29.965GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |414.0MiB|414.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |645.0MiB|645.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2571.0MiB|2571.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2072.0MiB|2072.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2088.0MiB|2088.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2572.0MiB|2572.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.596GiB|15.596GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |690.0MiB|690.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2955.0MiB|2955.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.107GiB|11.107GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.383GiB|23.383GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8688.0MiB|8688.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.247GiB|14.247GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.187GiB|22.187GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.972GiB|18.972GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |360.0MiB|360.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3803.0MiB|3803.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.965GiB|29.965GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |414.0MiB|414.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |645.0MiB|645.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2571.0MiB|2571.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2072.0MiB|2072.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2088.0MiB|2088.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2572.0MiB|2572.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.596GiB|15.596GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |690.0MiB|690.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2955.0MiB|2955.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.107GiB|11.107GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.383GiB|23.383GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8688.0MiB|8688.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.247GiB|14.247GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.187GiB|22.187GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.972GiB|18.972GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |360.0MiB|360.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3803.0MiB|3803.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.965GiB|29.965GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |414.0MiB|414.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |645.0MiB|645.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2571.0MiB|2571.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2072.0MiB|2072.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2088.0MiB|2088.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2572.0MiB|2572.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.596GiB|15.596GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |690.0MiB|690.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2955.0MiB|2955.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.107GiB|11.107GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.383GiB|23.383GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8688.0MiB|8688.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.247GiB|14.247GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.187GiB|22.187GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.972GiB|18.972GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |360.0MiB|360.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3803.0MiB|3803.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.965GiB|29.965GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |414.0MiB|414.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |645.0MiB|645.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2571.0MiB|2571.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2072.0MiB|2072.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2088.0MiB|2088.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2572.0MiB|2572.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.596GiB|15.596GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |690.0MiB|690.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2955.0MiB|2955.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.107GiB|11.107GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.200s |31.382GiB|
|scrambled12042.smt2                                                                        |1262.926s |29.965GiB|
|scrambled4198.smt2                                                                         |1262.313s |26.309GiB|
|scrambled4299.smt2                                                                         |1262.542s |25.395GiB|
|scrambled55680.smt2                                                                        |1262.683s |24.99GiB|
|scrambled102166.smt2                                                                       |1262.386s |23.383GiB|
|scrambled68944.smt2                                                                        |1262.297s |22.57GiB|
|scrambled108840.smt2                                                                       |1262.253s |22.187GiB|
|scrambled79760.smt2                                                                        |1262.385s |21.872GiB|
|scrambled111627.smt2                                                                       |1261.963s |18.972GiB|
|scrambled75189.smt2                                                                        |1261.974s |17.036GiB|
|scrambled19335.smt2                                                                        |1261.678s |15.596GiB|
|scrambled43577.smt2                                                                        |1261.830s |15.286GiB|
|scrambled107826.smt2                                                                       |1261.700s |14.247GiB|
|scrambled27843.smt2                                                                        |1261.827s |11.107GiB|
|scrambled107115.smt2                                                                       |1261.027s |8688.0MiB|
|scrambled61922.smt2                                                                        |1260.726s |5569.0MiB|
|scrambled40621.smt2                                                                        |1260.605s |4657.0MiB|
|scrambled119331.smt2                                                                       |1260.707s |3803.0MiB|
|scrambled25238.smt2                                                                        | 927.819s |2955.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.200s |31.382GiB|
|scrambled12042.smt2                                                                        |1262.926s |29.965GiB|
|scrambled4198.smt2                                                                         |1262.313s |26.309GiB|
|scrambled4299.smt2                                                                         |1262.542s |25.395GiB|
|scrambled55680.smt2                                                                        |1262.683s |24.99GiB|
|scrambled102166.smt2                                                                       |1262.386s |23.383GiB|
|scrambled68944.smt2                                                                        |1262.297s |22.57GiB|
|scrambled108840.smt2                                                                       |1262.253s |22.187GiB|
|scrambled79760.smt2                                                                        |1262.385s |21.872GiB|
|scrambled111627.smt2                                                                       |1261.963s |18.972GiB|
|scrambled75189.smt2                                                                        |1261.974s |17.036GiB|
|scrambled19335.smt2                                                                        |1261.678s |15.596GiB|
|scrambled43577.smt2                                                                        |1261.830s |15.286GiB|
|scrambled107826.smt2                                                                       |1261.700s |14.247GiB|
|scrambled27843.smt2                                                                        |1261.827s |11.107GiB|
|scrambled107115.smt2                                                                       |1261.027s |8688.0MiB|
|scrambled61922.smt2                                                                        |1260.726s |5569.0MiB|
|scrambled40621.smt2                                                                        |1260.605s |4657.0MiB|
|scrambled119331.smt2                                                                       |1260.707s |3803.0MiB|
|scrambled25238.smt2                                                                        | 927.819s |2955.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.386s  |1262.386s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.027s  |1261.027s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.700s  |1261.700s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.253s  |1262.253s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.963s  |1261.963s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  63.813s  |  63.813s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.707s  |1260.707s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.926s  |1262.926s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1023.077s  |1023.077s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 204.575s  | 204.575s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.550s  |1260.550s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.488s  |1260.488s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.349s  |1260.349s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.611s  |1260.611s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.087s  |1260.087s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.678s  |1261.678s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 446.041s  | 446.041s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 927.819s  | 927.819s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.827s  |1261.827s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 463.785s  | 463.785s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1260.045s  |1260.045s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1260.039s  |1260.039s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1260.605s  |1260.605s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1262.313s  |1262.313s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1262.542s  |1262.542s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1261.830s  |1261.830s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1260.258s  |1260.258s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1260.356s  |1260.356s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1262.683s  |1262.683s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1260.216s  |1260.216s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1260.015s  |1260.015s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1260.726s  |1260.726s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1260.046s  |1260.046s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1262.297s  |1262.297s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1260.354s  |1260.354s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1261.974s  |1261.974s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1260.571s  |1260.571s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1262.385s  |1262.385s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1260.016s  |1260.016s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1260.044s  |1260.044s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1263.200s  |1263.200s  |   0.000s  | 0.0%|
</details>
