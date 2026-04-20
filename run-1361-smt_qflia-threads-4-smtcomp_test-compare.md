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
Job tag: smt_qflia-threads-4-smtcomp_test
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6b8cb1099d311aac105cfc6fa658466f4ef6af67
Z3 branch: backbones
Z3 options: "-T:1 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=1"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore unrelated code to master

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qflia-threads-4-smtcomp_test
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6b8cb1099d311aac105cfc6fa658466f4ef6af67
Z3 branch: backbones
Z3 options: "-T:1 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=1"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore unrelated code to master

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   1.043s  |   1.043s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   1.025s  |   1.025s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   1.041s  |   1.041s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   1.037s  |   1.037s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   1.042s  |   1.042s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   1.054s  |   1.054s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   1.036s  |   1.036s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   1.062s  |   1.062s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   1.055s  |   1.055s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   1.024s  |   1.024s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   1.043s  |   1.043s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   1.025s  |   1.025s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   1.041s  |   1.041s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   1.037s  |   1.037s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   1.042s  |   1.042s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   1.054s  |   1.054s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   1.036s  |   1.036s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   1.062s  |   1.062s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   1.055s  |   1.055s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   1.024s  |   1.024s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   1.043s  |   1.043s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   1.025s  |   1.025s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   1.041s  |   1.041s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   1.037s  |   1.037s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   1.042s  |   1.042s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   1.054s  |   1.054s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   1.036s  |   1.036s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   1.062s  |   1.062s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   1.055s  |   1.055s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   1.024s  |   1.024s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   1.043s  |   1.043s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   1.025s  |   1.025s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   1.041s  |   1.041s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   1.037s  |   1.037s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   1.042s  |   1.042s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   1.054s  |   1.054s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   1.036s  |   1.036s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   1.062s  |   1.062s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   1.055s  |   1.055s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   1.024s  |   1.024s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled128874.smt2                                                                       |   1.062s |293.0MiB|
|scrambled125888.smt2                                                                       |   1.059s |304.0MiB|
|scrambled32836.smt2                                                                        |   1.058s |286.0MiB|
|scrambled20101.smt2                                                                        |   1.055s |293.0MiB|
|scrambled125827.smt2                                                                       |   1.054s |324.0MiB|
|scrambled51053.smt2                                                                        |   1.054s |176.0MiB|
|scrambled68944.smt2                                                                        |   1.053s |233.0MiB|
|scrambled95803.smt2                                                                        |   1.052s |242.0MiB|
|scrambled118793.smt2                                                                       |   1.051s |277.0MiB|
|scrambled119331.smt2                                                                       |   1.051s |284.0MiB|
|scrambled40621.smt2                                                                        |   1.049s |283.0MiB|
|scrambled7741.smt2                                                                         |   1.049s |277.0MiB|
|scrambled25238.smt2                                                                        |   1.047s |265.0MiB|
|scrambled128128.smt2                                                                       |   1.047s |262.0MiB|
|scrambled131241.smt2                                                                       |   1.046s |258.0MiB|
|scrambled43577.smt2                                                                        |   1.043s |232.0MiB|
|scrambled102166.smt2                                                                       |   1.043s |229.0MiB|
|scrambled108840.smt2                                                                       |   1.042s |230.0MiB|
|scrambled4299.smt2                                                                         |   1.041s |233.0MiB|
|scrambled55680.smt2                                                                        |   1.041s |228.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled128874.smt2                                                                       |   1.062s |293.0MiB|
|scrambled125888.smt2                                                                       |   1.059s |304.0MiB|
|scrambled32836.smt2                                                                        |   1.058s |286.0MiB|
|scrambled20101.smt2                                                                        |   1.055s |293.0MiB|
|scrambled125827.smt2                                                                       |   1.054s |324.0MiB|
|scrambled51053.smt2                                                                        |   1.054s |176.0MiB|
|scrambled68944.smt2                                                                        |   1.053s |233.0MiB|
|scrambled95803.smt2                                                                        |   1.052s |242.0MiB|
|scrambled118793.smt2                                                                       |   1.051s |277.0MiB|
|scrambled119331.smt2                                                                       |   1.051s |284.0MiB|
|scrambled40621.smt2                                                                        |   1.049s |283.0MiB|
|scrambled7741.smt2                                                                         |   1.049s |277.0MiB|
|scrambled25238.smt2                                                                        |   1.047s |265.0MiB|
|scrambled128128.smt2                                                                       |   1.047s |262.0MiB|
|scrambled131241.smt2                                                                       |   1.046s |258.0MiB|
|scrambled43577.smt2                                                                        |   1.043s |232.0MiB|
|scrambled102166.smt2                                                                       |   1.043s |229.0MiB|
|scrambled108840.smt2                                                                       |   1.042s |230.0MiB|
|scrambled4299.smt2                                                                         |   1.041s |233.0MiB|
|scrambled55680.smt2                                                                        |   1.041s |228.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |229.0MiB|229.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.236MiB|42.236MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |174.0MiB|174.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |231.0MiB|231.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |230.0MiB|230.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |232.0MiB|232.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |277.0MiB|277.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |284.0MiB|284.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |229.0MiB|229.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |324.0MiB|324.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |304.0MiB|304.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |262.0MiB|262.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |300.0MiB|300.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |258.0MiB|258.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |132.0MiB|132.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |232.0MiB|232.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |237.0MiB|237.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |229.0MiB|229.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.236MiB|42.236MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |174.0MiB|174.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |231.0MiB|231.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |230.0MiB|230.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |232.0MiB|232.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |277.0MiB|277.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |284.0MiB|284.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |229.0MiB|229.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |324.0MiB|324.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |304.0MiB|304.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |262.0MiB|262.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |300.0MiB|300.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |258.0MiB|258.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |132.0MiB|132.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |232.0MiB|232.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |237.0MiB|237.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |229.0MiB|229.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.236MiB|42.236MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |174.0MiB|174.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |231.0MiB|231.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |230.0MiB|230.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |232.0MiB|232.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |277.0MiB|277.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |284.0MiB|284.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |229.0MiB|229.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |324.0MiB|324.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |304.0MiB|304.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |262.0MiB|262.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |300.0MiB|300.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |258.0MiB|258.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |132.0MiB|132.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |232.0MiB|232.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |237.0MiB|237.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |229.0MiB|229.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.236MiB|42.236MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |174.0MiB|174.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |231.0MiB|231.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |230.0MiB|230.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |232.0MiB|232.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |277.0MiB|277.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |284.0MiB|284.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |229.0MiB|229.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |324.0MiB|324.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |304.0MiB|304.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |262.0MiB|262.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |300.0MiB|300.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |258.0MiB|258.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |132.0MiB|132.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |232.0MiB|232.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |237.0MiB|237.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled125827.smt2                                                                       |   1.054s |324.0MiB|
|scrambled125888.smt2                                                                       |   1.059s |304.0MiB|
|scrambled128732.smt2                                                                       |   1.036s |300.0MiB|
|scrambled72668.smt2                                                                        |   1.033s |300.0MiB|
|scrambled44911.smt2                                                                        |   1.036s |298.0MiB|
|scrambled55777.smt2                                                                        |   1.041s |297.0MiB|
|scrambled128874.smt2                                                                       |   1.062s |293.0MiB|
|scrambled20101.smt2                                                                        |   1.055s |293.0MiB|
|scrambled32836.smt2                                                                        |   1.058s |286.0MiB|
|scrambled119331.smt2                                                                       |   1.051s |284.0MiB|
|scrambled40621.smt2                                                                        |   1.049s |283.0MiB|
|scrambled118793.smt2                                                                       |   1.051s |277.0MiB|
|scrambled7741.smt2                                                                         |   1.049s |277.0MiB|
|scrambled25238.smt2                                                                        |   1.047s |265.0MiB|
|scrambled128128.smt2                                                                       |   1.047s |262.0MiB|
|scrambled131241.smt2                                                                       |   1.046s |258.0MiB|
|scrambled95803.smt2                                                                        |   1.052s |242.0MiB|
|scrambled27843.smt2                                                                        |   1.024s |237.0MiB|
|scrambled75189.smt2                                                                        |   1.038s |234.0MiB|
|scrambled68944.smt2                                                                        |   1.053s |233.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled125827.smt2                                                                       |   1.054s |324.0MiB|
|scrambled125888.smt2                                                                       |   1.059s |304.0MiB|
|scrambled128732.smt2                                                                       |   1.036s |300.0MiB|
|scrambled72668.smt2                                                                        |   1.033s |300.0MiB|
|scrambled44911.smt2                                                                        |   1.036s |298.0MiB|
|scrambled55777.smt2                                                                        |   1.041s |297.0MiB|
|scrambled128874.smt2                                                                       |   1.062s |293.0MiB|
|scrambled20101.smt2                                                                        |   1.055s |293.0MiB|
|scrambled32836.smt2                                                                        |   1.058s |286.0MiB|
|scrambled119331.smt2                                                                       |   1.051s |284.0MiB|
|scrambled40621.smt2                                                                        |   1.049s |283.0MiB|
|scrambled118793.smt2                                                                       |   1.051s |277.0MiB|
|scrambled7741.smt2                                                                         |   1.049s |277.0MiB|
|scrambled25238.smt2                                                                        |   1.047s |265.0MiB|
|scrambled128128.smt2                                                                       |   1.047s |262.0MiB|
|scrambled131241.smt2                                                                       |   1.046s |258.0MiB|
|scrambled95803.smt2                                                                        |   1.052s |242.0MiB|
|scrambled27843.smt2                                                                        |   1.024s |237.0MiB|
|scrambled75189.smt2                                                                        |   1.038s |234.0MiB|
|scrambled68944.smt2                                                                        |   1.053s |233.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   1.043s  |   1.043s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   1.025s  |   1.025s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   1.041s  |   1.041s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   1.037s  |   1.037s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   1.042s  |   1.042s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   1.054s  |   1.054s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   1.036s  |   1.036s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   1.062s  |   1.062s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   1.055s  |   1.055s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   1.024s  |   1.024s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |   1.058s  |   1.058s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |   1.026s  |   1.026s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |   1.026s  |   1.026s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |   1.049s  |   1.049s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |   1.041s  |   1.041s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |   1.043s  |   1.043s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |   1.036s  |   1.036s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |   1.027s  |   1.027s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |   1.054s  |   1.054s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |   1.041s  |   1.041s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |   1.041s  |   1.041s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |   1.026s  |   1.026s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |   1.022s  |   1.022s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |   1.040s  |   1.040s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |   1.053s  |   1.053s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |   1.033s  |   1.033s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |   1.049s  |   1.049s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |   1.040s  |   1.040s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |   1.029s  |   1.029s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |   1.040s  |   1.040s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |   1.032s  |   1.032s  |   0.000s  | 0.0%|
</details>
