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
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min_bb0
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6b8cb1099d311aac105cfc6fa658466f4ef6af67
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=0"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore unrelated code to master

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min_bb0
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6b8cb1099d311aac105cfc6fa658466f4ef6af67
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=0"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore unrelated code to master

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.499s  |1262.499s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.045s  |1260.045s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.092s  |1261.092s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.626s  |1261.626s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.416s  |1262.416s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.863s  |1261.863s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 132.075s  | 132.075s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.581s  |1260.581s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.828s  |1262.828s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 212.884s  | 212.884s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 356.992s  | 356.992s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.387s  |1260.387s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.418s  |1260.418s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.452s  |1260.452s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.408s  |1260.408s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.030s  |1260.030s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.778s  |1261.778s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 144.469s  | 144.469s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  98.525s  |  98.525s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.676s  |1261.676s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.499s  |1262.499s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.045s  |1260.045s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.092s  |1261.092s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.626s  |1261.626s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.416s  |1262.416s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.863s  |1261.863s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 132.075s  | 132.075s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.581s  |1260.581s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.828s  |1262.828s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 212.884s  | 212.884s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 356.992s  | 356.992s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.387s  |1260.387s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.418s  |1260.418s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.452s  |1260.452s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.408s  |1260.408s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.030s  |1260.030s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.778s  |1261.778s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 144.469s  | 144.469s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  98.525s  |  98.525s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.676s  |1261.676s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.499s  |1262.499s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.045s  |1260.045s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.092s  |1261.092s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.626s  |1261.626s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.416s  |1262.416s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.863s  |1261.863s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 132.075s  | 132.075s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.581s  |1260.581s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.828s  |1262.828s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 212.884s  | 212.884s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 356.992s  | 356.992s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.387s  |1260.387s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.418s  |1260.418s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.452s  |1260.452s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.408s  |1260.408s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.030s  |1260.030s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.778s  |1261.778s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 144.469s  | 144.469s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  98.525s  |  98.525s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.676s  |1261.676s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.499s  |1262.499s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.045s  |1260.045s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.092s  |1261.092s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.626s  |1261.626s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.416s  |1262.416s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.863s  |1261.863s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 132.075s  | 132.075s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.581s  |1260.581s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.828s  |1262.828s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 212.884s  | 212.884s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 356.992s  | 356.992s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.387s  |1260.387s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.418s  |1260.418s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.452s  |1260.452s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.408s  |1260.408s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.030s  |1260.030s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.778s  |1261.778s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 144.469s  | 144.469s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  98.525s  |  98.525s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.676s  |1261.676s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.454s |31.17GiB|
|scrambled12042.smt2                                                                        |1262.828s |29.83GiB|
|scrambled4299.smt2                                                                         |1262.518s |26.066GiB|
|scrambled102166.smt2                                                                       |1262.499s |23.381GiB|
|scrambled68944.smt2                                                                        |1262.489s |23.399GiB|
|scrambled55680.smt2                                                                        |1262.429s |25.007GiB|
|scrambled108840.smt2                                                                       |1262.416s |22.289GiB|
|scrambled79760.smt2                                                                        |1262.342s |21.921GiB|
|scrambled4198.smt2                                                                         |1262.031s |24.382GiB|
|scrambled75189.smt2                                                                        |1261.940s |17.035GiB|
|scrambled111627.smt2                                                                       |1261.863s |18.954GiB|
|scrambled19335.smt2                                                                        |1261.778s |15.592GiB|
|scrambled27843.smt2                                                                        |1261.676s |11.107GiB|
|scrambled107826.smt2                                                                       |1261.626s |14.247GiB|
|scrambled43577.smt2                                                                        |1261.571s |15.328GiB|
|scrambled107115.smt2                                                                       |1261.092s |8692.0MiB|
|scrambled61922.smt2                                                                        |1260.991s |5563.0MiB|
|scrambled40621.smt2                                                                        |1260.682s |4528.0MiB|
|scrambled119331.smt2                                                                       |1260.581s |3661.0MiB|
|scrambled7741.smt2                                                                         |1260.465s |2702.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.454s |31.17GiB|
|scrambled12042.smt2                                                                        |1262.828s |29.83GiB|
|scrambled4299.smt2                                                                         |1262.518s |26.066GiB|
|scrambled102166.smt2                                                                       |1262.499s |23.381GiB|
|scrambled68944.smt2                                                                        |1262.489s |23.399GiB|
|scrambled55680.smt2                                                                        |1262.429s |25.007GiB|
|scrambled108840.smt2                                                                       |1262.416s |22.289GiB|
|scrambled79760.smt2                                                                        |1262.342s |21.921GiB|
|scrambled4198.smt2                                                                         |1262.031s |24.382GiB|
|scrambled75189.smt2                                                                        |1261.940s |17.035GiB|
|scrambled111627.smt2                                                                       |1261.863s |18.954GiB|
|scrambled19335.smt2                                                                        |1261.778s |15.592GiB|
|scrambled27843.smt2                                                                        |1261.676s |11.107GiB|
|scrambled107826.smt2                                                                       |1261.626s |14.247GiB|
|scrambled43577.smt2                                                                        |1261.571s |15.328GiB|
|scrambled107115.smt2                                                                       |1261.092s |8692.0MiB|
|scrambled61922.smt2                                                                        |1260.991s |5563.0MiB|
|scrambled40621.smt2                                                                        |1260.682s |4528.0MiB|
|scrambled119331.smt2                                                                       |1260.581s |3661.0MiB|
|scrambled7741.smt2                                                                         |1260.465s |2702.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.381GiB|23.381GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8692.0MiB|8692.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.247GiB|14.247GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.289GiB|22.289GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.954GiB|18.954GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |371.0MiB|371.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3661.0MiB|3661.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.83GiB|29.83GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |408.0MiB|408.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2609.0MiB|2609.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2051.0MiB|2051.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2109.0MiB|2109.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2593.0MiB|2593.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.592GiB|15.592GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |646.0MiB|646.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1962.0MiB|1962.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.107GiB|11.107GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.381GiB|23.381GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8692.0MiB|8692.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.247GiB|14.247GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.289GiB|22.289GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.954GiB|18.954GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |371.0MiB|371.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3661.0MiB|3661.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.83GiB|29.83GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |408.0MiB|408.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2609.0MiB|2609.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2051.0MiB|2051.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2109.0MiB|2109.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2593.0MiB|2593.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.592GiB|15.592GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |646.0MiB|646.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1962.0MiB|1962.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.107GiB|11.107GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.381GiB|23.381GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8692.0MiB|8692.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.247GiB|14.247GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.289GiB|22.289GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.954GiB|18.954GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |371.0MiB|371.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3661.0MiB|3661.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.83GiB|29.83GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |408.0MiB|408.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2609.0MiB|2609.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2051.0MiB|2051.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2109.0MiB|2109.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2593.0MiB|2593.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.592GiB|15.592GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |646.0MiB|646.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1962.0MiB|1962.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.107GiB|11.107GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |23.381GiB|23.381GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8692.0MiB|8692.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.247GiB|14.247GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |22.289GiB|22.289GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |18.954GiB|18.954GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |371.0MiB|371.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3661.0MiB|3661.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |29.83GiB|29.83GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |408.0MiB|408.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |654.0MiB|654.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2609.0MiB|2609.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2051.0MiB|2051.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2109.0MiB|2109.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2593.0MiB|2593.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |15.592GiB|15.592GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |646.0MiB|646.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1962.0MiB|1962.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.107GiB|11.107GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.454s |31.17GiB|
|scrambled12042.smt2                                                                        |1262.828s |29.83GiB|
|scrambled4299.smt2                                                                         |1262.518s |26.066GiB|
|scrambled55680.smt2                                                                        |1262.429s |25.007GiB|
|scrambled4198.smt2                                                                         |1262.031s |24.382GiB|
|scrambled68944.smt2                                                                        |1262.489s |23.399GiB|
|scrambled102166.smt2                                                                       |1262.499s |23.381GiB|
|scrambled108840.smt2                                                                       |1262.416s |22.289GiB|
|scrambled79760.smt2                                                                        |1262.342s |21.921GiB|
|scrambled111627.smt2                                                                       |1261.863s |18.954GiB|
|scrambled75189.smt2                                                                        |1261.940s |17.035GiB|
|scrambled19335.smt2                                                                        |1261.778s |15.592GiB|
|scrambled43577.smt2                                                                        |1261.571s |15.328GiB|
|scrambled107826.smt2                                                                       |1261.626s |14.247GiB|
|scrambled27843.smt2                                                                        |1261.676s |11.107GiB|
|scrambled107115.smt2                                                                       |1261.092s |8692.0MiB|
|scrambled61922.smt2                                                                        |1260.991s |5563.0MiB|
|scrambled40621.smt2                                                                        |1260.682s |4528.0MiB|
|scrambled119331.smt2                                                                       |1260.581s |3661.0MiB|
|scrambled7741.smt2                                                                         |1260.465s |2702.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.454s |31.17GiB|
|scrambled12042.smt2                                                                        |1262.828s |29.83GiB|
|scrambled4299.smt2                                                                         |1262.518s |26.066GiB|
|scrambled55680.smt2                                                                        |1262.429s |25.007GiB|
|scrambled4198.smt2                                                                         |1262.031s |24.382GiB|
|scrambled68944.smt2                                                                        |1262.489s |23.399GiB|
|scrambled102166.smt2                                                                       |1262.499s |23.381GiB|
|scrambled108840.smt2                                                                       |1262.416s |22.289GiB|
|scrambled79760.smt2                                                                        |1262.342s |21.921GiB|
|scrambled111627.smt2                                                                       |1261.863s |18.954GiB|
|scrambled75189.smt2                                                                        |1261.940s |17.035GiB|
|scrambled19335.smt2                                                                        |1261.778s |15.592GiB|
|scrambled43577.smt2                                                                        |1261.571s |15.328GiB|
|scrambled107826.smt2                                                                       |1261.626s |14.247GiB|
|scrambled27843.smt2                                                                        |1261.676s |11.107GiB|
|scrambled107115.smt2                                                                       |1261.092s |8692.0MiB|
|scrambled61922.smt2                                                                        |1260.991s |5563.0MiB|
|scrambled40621.smt2                                                                        |1260.682s |4528.0MiB|
|scrambled119331.smt2                                                                       |1260.581s |3661.0MiB|
|scrambled7741.smt2                                                                         |1260.465s |2702.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.499s  |1262.499s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.045s  |1260.045s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1261.092s  |1261.092s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.626s  |1261.626s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.416s  |1262.416s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.863s  |1261.863s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 132.075s  | 132.075s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.581s  |1260.581s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.828s  |1262.828s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 212.884s  | 212.884s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 356.992s  | 356.992s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.387s  |1260.387s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.418s  |1260.418s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.452s  |1260.452s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.408s  |1260.408s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.030s  |1260.030s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.778s  |1261.778s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 144.469s  | 144.469s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  98.525s  |  98.525s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.676s  |1261.676s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 421.318s  | 421.318s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1260.041s  |1260.041s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1260.682s  |1260.682s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1262.031s  |1262.031s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1262.518s  |1262.518s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1261.571s  |1261.571s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1260.406s  |1260.406s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1260.023s  |1260.023s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1260.307s  |1260.307s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1262.429s  |1262.429s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1260.183s  |1260.183s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1260.023s  |1260.023s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1260.991s  |1260.991s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1260.024s  |1260.024s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1262.489s  |1262.489s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1260.304s  |1260.304s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1261.940s  |1261.940s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1260.465s  |1260.465s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1262.342s  |1262.342s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1260.041s  |1260.041s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1260.048s  |1260.048s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1263.454s  |1263.454s  |   0.000s  | 0.0%|
</details>
