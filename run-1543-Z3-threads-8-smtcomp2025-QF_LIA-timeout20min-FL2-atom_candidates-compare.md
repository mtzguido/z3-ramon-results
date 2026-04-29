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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-FL2-atom_candidates
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 8721242318d35ebfaa6de4932f4825950ff87bc7
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_fl_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: fix polarity bug for FL mode dedup

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-FL2-atom_candidates
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 8721242318d35ebfaa6de4932f4825950ff87bc7
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_fl_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: fix polarity bug for FL mode dedup

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.006s  |1205.006s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.765s  |1201.765s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.571s  |1202.571s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.923s  |1203.923s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.463s  |1203.463s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 117.182s  | 117.182s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.960s  |1200.960s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.762s  |1204.762s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 274.408s  | 274.408s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 138.821s  | 138.821s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.610s  |1200.610s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        | 800.386s  | 800.386s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.885s  |1200.885s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.798s  |1200.798s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.978s  |1202.978s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 110.780s  | 110.780s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 205.587s  | 205.587s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1203.078s  |1203.078s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.006s  |1205.006s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.765s  |1201.765s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.571s  |1202.571s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.923s  |1203.923s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.463s  |1203.463s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 117.182s  | 117.182s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.960s  |1200.960s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.762s  |1204.762s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 274.408s  | 274.408s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 138.821s  | 138.821s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.610s  |1200.610s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        | 800.386s  | 800.386s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.885s  |1200.885s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.798s  |1200.798s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.978s  |1202.978s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 110.780s  | 110.780s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 205.587s  | 205.587s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1203.078s  |1203.078s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.006s  |1205.006s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.765s  |1201.765s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.571s  |1202.571s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.923s  |1203.923s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.463s  |1203.463s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 117.182s  | 117.182s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.960s  |1200.960s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.762s  |1204.762s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 274.408s  | 274.408s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 138.821s  | 138.821s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.610s  |1200.610s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        | 800.386s  | 800.386s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.885s  |1200.885s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.798s  |1200.798s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.978s  |1202.978s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 110.780s  | 110.780s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 205.587s  | 205.587s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1203.078s  |1203.078s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.006s  |1205.006s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.765s  |1201.765s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.571s  |1202.571s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.923s  |1203.923s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.463s  |1203.463s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 117.182s  | 117.182s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.960s  |1200.960s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.762s  |1204.762s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 274.408s  | 274.408s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 138.821s  | 138.821s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.610s  |1200.610s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        | 800.386s  | 800.386s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.885s  |1200.885s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.798s  |1200.798s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.978s  |1202.978s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 110.780s  | 110.780s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 205.587s  | 205.587s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1203.078s  |1203.078s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.233s |63.342GiB|
|scrambled102166.smt2                                                                       |1205.006s |48.049GiB|
|scrambled4299.smt2                                                                         |1204.979s |56.779GiB|
|scrambled12042.smt2                                                                        |1204.762s |54.515GiB|
|scrambled55680.smt2                                                                        |1204.468s |50.663GiB|
|scrambled68944.smt2                                                                        |1204.408s |46.846GiB|
|scrambled4198.smt2                                                                         |1204.313s |49.465GiB|
|scrambled108840.smt2                                                                       |1203.923s |43.041GiB|
|scrambled79760.smt2                                                                        |1203.875s |44.264GiB|
|scrambled111627.smt2                                                                       |1203.463s |37.764GiB|
|scrambled43577.smt2                                                                        |1203.111s |34.371GiB|
|scrambled27843.smt2                                                                        |1203.078s |21.02GiB|
|scrambled75189.smt2                                                                        |1203.055s |31.687GiB|
|scrambled19335.smt2                                                                        |1202.978s |32.43GiB|
|scrambled107826.smt2                                                                       |1202.571s |27.848GiB|
|scrambled107115.smt2                                                                       |1201.765s |17.773GiB|
|scrambled40621.smt2                                                                        |1201.233s |11.573GiB|
|scrambled61922.smt2                                                                        |1201.162s |10.832GiB|
|scrambled119331.smt2                                                                       |1200.960s |9873.0MiB|
|scrambled72668.smt2                                                                        |1200.953s |5344.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.233s |63.342GiB|
|scrambled102166.smt2                                                                       |1205.006s |48.049GiB|
|scrambled4299.smt2                                                                         |1204.979s |56.779GiB|
|scrambled12042.smt2                                                                        |1204.762s |54.515GiB|
|scrambled55680.smt2                                                                        |1204.468s |50.663GiB|
|scrambled68944.smt2                                                                        |1204.408s |46.846GiB|
|scrambled4198.smt2                                                                         |1204.313s |49.465GiB|
|scrambled108840.smt2                                                                       |1203.923s |43.041GiB|
|scrambled79760.smt2                                                                        |1203.875s |44.264GiB|
|scrambled111627.smt2                                                                       |1203.463s |37.764GiB|
|scrambled43577.smt2                                                                        |1203.111s |34.371GiB|
|scrambled27843.smt2                                                                        |1203.078s |21.02GiB|
|scrambled75189.smt2                                                                        |1203.055s |31.687GiB|
|scrambled19335.smt2                                                                        |1202.978s |32.43GiB|
|scrambled107826.smt2                                                                       |1202.571s |27.848GiB|
|scrambled107115.smt2                                                                       |1201.765s |17.773GiB|
|scrambled40621.smt2                                                                        |1201.233s |11.573GiB|
|scrambled61922.smt2                                                                        |1201.162s |10.832GiB|
|scrambled119331.smt2                                                                       |1200.960s |9873.0MiB|
|scrambled72668.smt2                                                                        |1200.953s |5344.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.049GiB|48.049GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.308MiB|42.308MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.773GiB|17.773GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.848GiB|27.848GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.041GiB|43.041GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.764GiB|37.764GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |957.0MiB|957.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9873.0MiB|9873.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.515GiB|54.515GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1027.0MiB|1027.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1608.0MiB|1608.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6512.0MiB|6512.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5117.0MiB|5117.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5195.0MiB|5195.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6458.0MiB|6458.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |393.0MiB|393.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.43GiB|32.43GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1630.0MiB|1630.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |6024.0MiB|6024.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.02GiB|21.02GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.049GiB|48.049GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.308MiB|42.308MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.773GiB|17.773GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.848GiB|27.848GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.041GiB|43.041GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.764GiB|37.764GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |957.0MiB|957.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9873.0MiB|9873.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.515GiB|54.515GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1027.0MiB|1027.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1608.0MiB|1608.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6512.0MiB|6512.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5117.0MiB|5117.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5195.0MiB|5195.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6458.0MiB|6458.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |393.0MiB|393.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.43GiB|32.43GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1630.0MiB|1630.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |6024.0MiB|6024.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.02GiB|21.02GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.049GiB|48.049GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.308MiB|42.308MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.773GiB|17.773GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.848GiB|27.848GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.041GiB|43.041GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.764GiB|37.764GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |957.0MiB|957.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9873.0MiB|9873.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.515GiB|54.515GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1027.0MiB|1027.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1608.0MiB|1608.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6512.0MiB|6512.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5117.0MiB|5117.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5195.0MiB|5195.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6458.0MiB|6458.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |393.0MiB|393.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.43GiB|32.43GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1630.0MiB|1630.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |6024.0MiB|6024.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.02GiB|21.02GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.049GiB|48.049GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.308MiB|42.308MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.773GiB|17.773GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.848GiB|27.848GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.041GiB|43.041GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.764GiB|37.764GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |957.0MiB|957.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9873.0MiB|9873.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.515GiB|54.515GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1027.0MiB|1027.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1608.0MiB|1608.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6512.0MiB|6512.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5117.0MiB|5117.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5195.0MiB|5195.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6458.0MiB|6458.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |393.0MiB|393.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.43GiB|32.43GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1630.0MiB|1630.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |6024.0MiB|6024.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.02GiB|21.02GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.233s |63.342GiB|
|scrambled4299.smt2                                                                         |1204.979s |56.779GiB|
|scrambled12042.smt2                                                                        |1204.762s |54.515GiB|
|scrambled55680.smt2                                                                        |1204.468s |50.663GiB|
|scrambled4198.smt2                                                                         |1204.313s |49.465GiB|
|scrambled102166.smt2                                                                       |1205.006s |48.049GiB|
|scrambled68944.smt2                                                                        |1204.408s |46.846GiB|
|scrambled79760.smt2                                                                        |1203.875s |44.264GiB|
|scrambled108840.smt2                                                                       |1203.923s |43.041GiB|
|scrambled111627.smt2                                                                       |1203.463s |37.764GiB|
|scrambled43577.smt2                                                                        |1203.111s |34.371GiB|
|scrambled19335.smt2                                                                        |1202.978s |32.43GiB|
|scrambled75189.smt2                                                                        |1203.055s |31.687GiB|
|scrambled107826.smt2                                                                       |1202.571s |27.848GiB|
|scrambled27843.smt2                                                                        |1203.078s |21.02GiB|
|scrambled107115.smt2                                                                       |1201.765s |17.773GiB|
|scrambled40621.smt2                                                                        |1201.233s |11.573GiB|
|scrambled61922.smt2                                                                        |1201.162s |10.832GiB|
|scrambled119331.smt2                                                                       |1200.960s |9873.0MiB|
|scrambled7741.smt2                                                                         |1200.810s |6778.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.233s |63.342GiB|
|scrambled4299.smt2                                                                         |1204.979s |56.779GiB|
|scrambled12042.smt2                                                                        |1204.762s |54.515GiB|
|scrambled55680.smt2                                                                        |1204.468s |50.663GiB|
|scrambled4198.smt2                                                                         |1204.313s |49.465GiB|
|scrambled102166.smt2                                                                       |1205.006s |48.049GiB|
|scrambled68944.smt2                                                                        |1204.408s |46.846GiB|
|scrambled79760.smt2                                                                        |1203.875s |44.264GiB|
|scrambled108840.smt2                                                                       |1203.923s |43.041GiB|
|scrambled111627.smt2                                                                       |1203.463s |37.764GiB|
|scrambled43577.smt2                                                                        |1203.111s |34.371GiB|
|scrambled19335.smt2                                                                        |1202.978s |32.43GiB|
|scrambled75189.smt2                                                                        |1203.055s |31.687GiB|
|scrambled107826.smt2                                                                       |1202.571s |27.848GiB|
|scrambled27843.smt2                                                                        |1203.078s |21.02GiB|
|scrambled107115.smt2                                                                       |1201.765s |17.773GiB|
|scrambled40621.smt2                                                                        |1201.233s |11.573GiB|
|scrambled61922.smt2                                                                        |1201.162s |10.832GiB|
|scrambled119331.smt2                                                                       |1200.960s |9873.0MiB|
|scrambled7741.smt2                                                                         |1200.810s |6778.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1205.006s  |1205.006s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.765s  |1201.765s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.571s  |1202.571s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.923s  |1203.923s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.463s  |1203.463s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 117.182s  | 117.182s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.960s  |1200.960s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.762s  |1204.762s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 274.408s  | 274.408s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 138.821s  | 138.821s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.610s  |1200.610s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        | 800.386s  | 800.386s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.885s  |1200.885s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.798s  |1200.798s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.978s  |1202.978s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 110.780s  | 110.780s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 205.587s  | 205.587s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1203.078s  |1203.078s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.423s  |1200.423s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1201.233s  |1201.233s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1204.313s  |1204.313s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1204.979s  |1204.979s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1203.111s  |1203.111s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.808s  |1200.808s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.585s  |1200.585s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1204.468s  |1204.468s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.570s  |1200.570s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.026s  |1200.026s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1201.162s  |1201.162s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1204.408s  |1204.408s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1200.953s  |1200.953s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1203.055s  |1203.055s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.810s  |1200.810s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1203.875s  |1203.875s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1206.233s  |1206.233s  |   0.000s  | 0.0%|
</details>
