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
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_LIA-timeout20min}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_LIA-timeout20min}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.762s  |1200.762s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.438s  |1200.438s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.607s  |1200.607s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.602s  |1200.602s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.868s  |1200.868s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.023s  |1200.023s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.178s  |1200.178s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.902s  |1200.902s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 839.540s  | 839.540s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1175.478s  |1175.478s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.084s  |1200.084s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.427s  |1200.427s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.150s  |1200.150s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.331s  |1200.331s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.762s  |1200.762s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.438s  |1200.438s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.607s  |1200.607s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.602s  |1200.602s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.868s  |1200.868s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.023s  |1200.023s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.178s  |1200.178s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.902s  |1200.902s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 839.540s  | 839.540s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1175.478s  |1175.478s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.084s  |1200.084s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.427s  |1200.427s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.150s  |1200.150s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.331s  |1200.331s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.762s  |1200.762s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.438s  |1200.438s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.607s  |1200.607s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.602s  |1200.602s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.868s  |1200.868s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.023s  |1200.023s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.178s  |1200.178s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.902s  |1200.902s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 839.540s  | 839.540s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1175.478s  |1175.478s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.084s  |1200.084s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.427s  |1200.427s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.150s  |1200.150s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.331s  |1200.331s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.762s  |1200.762s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.438s  |1200.438s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.607s  |1200.607s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.602s  |1200.602s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.868s  |1200.868s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.023s  |1200.023s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.178s  |1200.178s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.902s  |1200.902s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 839.540s  | 839.540s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1175.478s  |1175.478s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.084s  |1200.084s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.427s  |1200.427s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.150s  |1200.150s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.331s  |1200.331s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled4299.smt2                                                                         |1200.974s |6809.0MiB|
|scrambled94658.smt2                                                                        |1200.964s |6800.0MiB|
|scrambled12042.smt2                                                                        |1200.902s |6170.0MiB|
|scrambled55680.smt2                                                                        |1200.893s |6055.0MiB|
|scrambled111627.smt2                                                                       |1200.868s |5803.0MiB|
|scrambled68944.smt2                                                                        |1200.764s |4740.0MiB|
|scrambled102166.smt2                                                                       |1200.762s |7350.0MiB|
|scrambled4198.smt2                                                                         |1200.758s |7173.0MiB|
|scrambled75189.smt2                                                                        |1200.722s |4318.0MiB|
|scrambled79760.smt2                                                                        |1200.648s |5940.0MiB|
|scrambled107826.smt2                                                                       |1200.607s |3503.0MiB|
|scrambled108840.smt2                                                                       |1200.602s |5439.0MiB|
|scrambled43577.smt2                                                                        |1200.504s |4184.0MiB|
|scrambled107115.smt2                                                                       |1200.438s |1957.0MiB|
|scrambled19335.smt2                                                                        |1200.427s |3354.0MiB|
|scrambled27843.smt2                                                                        |1200.331s |2317.0MiB|
|scrambled61922.smt2                                                                        |1200.330s |1254.0MiB|
|scrambled72668.smt2                                                                        |1200.199s |527.0MiB|
|scrambled44911.smt2                                                                        |1200.196s |502.0MiB|
|scrambled128732.smt2                                                                       |1200.195s |521.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled4299.smt2                                                                         |1200.974s |6809.0MiB|
|scrambled94658.smt2                                                                        |1200.964s |6800.0MiB|
|scrambled12042.smt2                                                                        |1200.902s |6170.0MiB|
|scrambled55680.smt2                                                                        |1200.893s |6055.0MiB|
|scrambled111627.smt2                                                                       |1200.868s |5803.0MiB|
|scrambled68944.smt2                                                                        |1200.764s |4740.0MiB|
|scrambled102166.smt2                                                                       |1200.762s |7350.0MiB|
|scrambled4198.smt2                                                                         |1200.758s |7173.0MiB|
|scrambled75189.smt2                                                                        |1200.722s |4318.0MiB|
|scrambled79760.smt2                                                                        |1200.648s |5940.0MiB|
|scrambled107826.smt2                                                                       |1200.607s |3503.0MiB|
|scrambled108840.smt2                                                                       |1200.602s |5439.0MiB|
|scrambled43577.smt2                                                                        |1200.504s |4184.0MiB|
|scrambled107115.smt2                                                                       |1200.438s |1957.0MiB|
|scrambled19335.smt2                                                                        |1200.427s |3354.0MiB|
|scrambled27843.smt2                                                                        |1200.331s |2317.0MiB|
|scrambled61922.smt2                                                                        |1200.330s |1254.0MiB|
|scrambled72668.smt2                                                                        |1200.199s |527.0MiB|
|scrambled44911.smt2                                                                        |1200.196s |502.0MiB|
|scrambled128732.smt2                                                                       |1200.195s |521.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7350.0MiB|7350.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.304MiB|42.304MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1957.0MiB|1957.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3503.0MiB|3503.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |5439.0MiB|5439.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |5803.0MiB|5803.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |969.0MiB|969.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |6170.0MiB|6170.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |164.0MiB|164.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |683.0MiB|683.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |521.0MiB|521.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |490.0MiB|490.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |568.0MiB|568.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |45.54MiB|45.54MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3354.0MiB|3354.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |173.0MiB|173.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |724.0MiB|724.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2317.0MiB|2317.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7350.0MiB|7350.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.304MiB|42.304MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1957.0MiB|1957.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3503.0MiB|3503.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |5439.0MiB|5439.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |5803.0MiB|5803.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |969.0MiB|969.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |6170.0MiB|6170.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |164.0MiB|164.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |683.0MiB|683.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |521.0MiB|521.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |490.0MiB|490.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |568.0MiB|568.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |45.54MiB|45.54MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3354.0MiB|3354.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |173.0MiB|173.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |724.0MiB|724.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2317.0MiB|2317.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7350.0MiB|7350.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.304MiB|42.304MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1957.0MiB|1957.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3503.0MiB|3503.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |5439.0MiB|5439.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |5803.0MiB|5803.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |969.0MiB|969.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |6170.0MiB|6170.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |164.0MiB|164.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |683.0MiB|683.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |521.0MiB|521.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |490.0MiB|490.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |568.0MiB|568.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |45.54MiB|45.54MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3354.0MiB|3354.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |173.0MiB|173.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |724.0MiB|724.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2317.0MiB|2317.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7350.0MiB|7350.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.304MiB|42.304MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1957.0MiB|1957.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3503.0MiB|3503.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |5439.0MiB|5439.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |5803.0MiB|5803.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |969.0MiB|969.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |6170.0MiB|6170.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |164.0MiB|164.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |683.0MiB|683.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |521.0MiB|521.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |490.0MiB|490.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |568.0MiB|568.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |45.54MiB|45.54MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3354.0MiB|3354.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |173.0MiB|173.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |724.0MiB|724.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2317.0MiB|2317.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled102166.smt2                                                                       |1200.762s |7350.0MiB|
|scrambled4198.smt2                                                                         |1200.758s |7173.0MiB|
|scrambled4299.smt2                                                                         |1200.974s |6809.0MiB|
|scrambled94658.smt2                                                                        |1200.964s |6800.0MiB|
|scrambled12042.smt2                                                                        |1200.902s |6170.0MiB|
|scrambled55680.smt2                                                                        |1200.893s |6055.0MiB|
|scrambled79760.smt2                                                                        |1200.648s |5940.0MiB|
|scrambled111627.smt2                                                                       |1200.868s |5803.0MiB|
|scrambled108840.smt2                                                                       |1200.602s |5439.0MiB|
|scrambled68944.smt2                                                                        |1200.764s |4740.0MiB|
|scrambled75189.smt2                                                                        |1200.722s |4318.0MiB|
|scrambled43577.smt2                                                                        |1200.504s |4184.0MiB|
|scrambled107826.smt2                                                                       |1200.607s |3503.0MiB|
|scrambled19335.smt2                                                                        |1200.427s |3354.0MiB|
|scrambled27843.smt2                                                                        |1200.331s |2317.0MiB|
|scrambled107115.smt2                                                                       |1200.438s |1957.0MiB|
|scrambled61922.smt2                                                                        |1200.330s |1254.0MiB|
|scrambled119331.smt2                                                                       |1200.178s |969.0MiB|
|scrambled40621.smt2                                                                        |1200.149s |763.0MiB|
|scrambled25238.smt2                                                                        |1200.150s |724.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled102166.smt2                                                                       |1200.762s |7350.0MiB|
|scrambled4198.smt2                                                                         |1200.758s |7173.0MiB|
|scrambled4299.smt2                                                                         |1200.974s |6809.0MiB|
|scrambled94658.smt2                                                                        |1200.964s |6800.0MiB|
|scrambled12042.smt2                                                                        |1200.902s |6170.0MiB|
|scrambled55680.smt2                                                                        |1200.893s |6055.0MiB|
|scrambled79760.smt2                                                                        |1200.648s |5940.0MiB|
|scrambled111627.smt2                                                                       |1200.868s |5803.0MiB|
|scrambled108840.smt2                                                                       |1200.602s |5439.0MiB|
|scrambled68944.smt2                                                                        |1200.764s |4740.0MiB|
|scrambled75189.smt2                                                                        |1200.722s |4318.0MiB|
|scrambled43577.smt2                                                                        |1200.504s |4184.0MiB|
|scrambled107826.smt2                                                                       |1200.607s |3503.0MiB|
|scrambled19335.smt2                                                                        |1200.427s |3354.0MiB|
|scrambled27843.smt2                                                                        |1200.331s |2317.0MiB|
|scrambled107115.smt2                                                                       |1200.438s |1957.0MiB|
|scrambled61922.smt2                                                                        |1200.330s |1254.0MiB|
|scrambled119331.smt2                                                                       |1200.178s |969.0MiB|
|scrambled40621.smt2                                                                        |1200.149s |763.0MiB|
|scrambled25238.smt2                                                                        |1200.150s |724.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.762s  |1200.762s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.438s  |1200.438s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.607s  |1200.607s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.602s  |1200.602s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.868s  |1200.868s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.023s  |1200.023s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.178s  |1200.178s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.902s  |1200.902s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 839.540s  | 839.540s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1175.478s  |1175.478s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.084s  |1200.084s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.427s  |1200.427s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.150s  |1200.150s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.331s  |1200.331s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1200.149s  |1200.149s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1200.758s  |1200.758s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1200.974s  |1200.974s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1200.504s  |1200.504s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.196s  |1200.196s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1200.893s  |1200.893s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.185s  |1200.185s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1200.330s  |1200.330s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1200.764s  |1200.764s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1200.199s  |1200.199s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1200.722s  |1200.722s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.186s  |1200.186s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1200.648s  |1200.648s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1200.964s  |1200.964s  |   0.000s  | 0.0%|
</details>
