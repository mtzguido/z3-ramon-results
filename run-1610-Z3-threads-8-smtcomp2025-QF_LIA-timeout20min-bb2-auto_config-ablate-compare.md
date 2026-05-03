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
Z3 commit: 00f2b5e671e82aec1f9a4a88741b8e2b10ac0ea1
Z3 branch: 00f2b5e671e82aec1f9a4a88741b8e2b10ac0ea1
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-auto_config-ablate
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 00f2b5e671e82aec1f9a4a88741b8e2b10ac0ea1
Z3 branch: 00f2b5e671e82aec1f9a4a88741b8e2b10ac0ea1
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.223s  |1204.223s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.703s  |1201.703s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.652s  |1202.652s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.749s  |1203.749s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.676s  |1203.676s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 835.515s  | 835.515s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.738s  |1200.738s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.781s  |1204.781s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  40.534s  |  40.534s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 599.596s  | 599.596s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 324.730s  | 324.730s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.471s  |1200.471s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.644s  |1200.644s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.624s  |1200.624s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.960s  |1202.960s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 686.503s  | 686.503s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  86.487s  |  86.487s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1203.136s  |1203.136s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.223s  |1204.223s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.703s  |1201.703s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.652s  |1202.652s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.749s  |1203.749s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.676s  |1203.676s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 835.515s  | 835.515s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.738s  |1200.738s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.781s  |1204.781s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  40.534s  |  40.534s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 599.596s  | 599.596s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 324.730s  | 324.730s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.471s  |1200.471s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.644s  |1200.644s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.624s  |1200.624s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.960s  |1202.960s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 686.503s  | 686.503s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  86.487s  |  86.487s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1203.136s  |1203.136s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.223s  |1204.223s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.703s  |1201.703s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.652s  |1202.652s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.749s  |1203.749s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.676s  |1203.676s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 835.515s  | 835.515s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.738s  |1200.738s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.781s  |1204.781s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  40.534s  |  40.534s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 599.596s  | 599.596s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 324.730s  | 324.730s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.471s  |1200.471s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.644s  |1200.644s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.624s  |1200.624s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.960s  |1202.960s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 686.503s  | 686.503s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  86.487s  |  86.487s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1203.136s  |1203.136s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.223s  |1204.223s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.703s  |1201.703s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.652s  |1202.652s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.749s  |1203.749s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.676s  |1203.676s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 835.515s  | 835.515s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.738s  |1200.738s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.781s  |1204.781s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  40.534s  |  40.534s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 599.596s  | 599.596s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 324.730s  | 324.730s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.471s  |1200.471s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.644s  |1200.644s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.624s  |1200.624s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.960s  |1202.960s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 686.503s  | 686.503s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  86.487s  |  86.487s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1203.136s  |1203.136s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.703s |62.593GiB|
|scrambled4299.smt2                                                                         |1205.217s |56.475GiB|
|scrambled12042.smt2                                                                        |1204.781s |54.122GiB|
|scrambled55680.smt2                                                                        |1204.392s |50.305GiB|
|scrambled4198.smt2                                                                         |1204.327s |48.976GiB|
|scrambled102166.smt2                                                                       |1204.223s |47.797GiB|
|scrambled68944.smt2                                                                        |1204.194s |46.51GiB|
|scrambled79760.smt2                                                                        |1203.831s |44.157GiB|
|scrambled108840.smt2                                                                       |1203.749s |42.78GiB|
|scrambled111627.smt2                                                                       |1203.676s |37.481GiB|
|scrambled27843.smt2                                                                        |1203.136s |20.818GiB|
|scrambled43577.smt2                                                                        |1202.987s |34.098GiB|
|scrambled19335.smt2                                                                        |1202.960s |32.099GiB|
|scrambled75189.smt2                                                                        |1202.898s |31.477GiB|
|scrambled107826.smt2                                                                       |1202.652s |27.653GiB|
|scrambled107115.smt2                                                                       |1201.703s |17.681GiB|
|scrambled61922.smt2                                                                        |1201.097s |10.755GiB|
|scrambled44911.smt2                                                                        |1200.831s |4706.0MiB|
|scrambled40621.smt2                                                                        |1200.824s |6364.0MiB|
|scrambled119331.smt2                                                                       |1200.738s |7102.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.703s |62.593GiB|
|scrambled4299.smt2                                                                         |1205.217s |56.475GiB|
|scrambled12042.smt2                                                                        |1204.781s |54.122GiB|
|scrambled55680.smt2                                                                        |1204.392s |50.305GiB|
|scrambled4198.smt2                                                                         |1204.327s |48.976GiB|
|scrambled102166.smt2                                                                       |1204.223s |47.797GiB|
|scrambled68944.smt2                                                                        |1204.194s |46.51GiB|
|scrambled79760.smt2                                                                        |1203.831s |44.157GiB|
|scrambled108840.smt2                                                                       |1203.749s |42.78GiB|
|scrambled111627.smt2                                                                       |1203.676s |37.481GiB|
|scrambled27843.smt2                                                                        |1203.136s |20.818GiB|
|scrambled43577.smt2                                                                        |1202.987s |34.098GiB|
|scrambled19335.smt2                                                                        |1202.960s |32.099GiB|
|scrambled75189.smt2                                                                        |1202.898s |31.477GiB|
|scrambled107826.smt2                                                                       |1202.652s |27.653GiB|
|scrambled107115.smt2                                                                       |1201.703s |17.681GiB|
|scrambled61922.smt2                                                                        |1201.097s |10.755GiB|
|scrambled44911.smt2                                                                        |1200.831s |4706.0MiB|
|scrambled40621.smt2                                                                        |1200.824s |6364.0MiB|
|scrambled119331.smt2                                                                       |1200.738s |7102.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.797GiB|47.797GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.681GiB|17.681GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.653GiB|27.653GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.78GiB|42.78GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.481GiB|37.481GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |987.0MiB|987.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |7102.0MiB|7102.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.122GiB|54.122GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |934.0MiB|934.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1608.0MiB|1608.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |4759.0MiB|4759.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4675.0MiB|4675.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4749.0MiB|4749.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5037.0MiB|5037.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |515.0MiB|515.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.099GiB|32.099GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1676.0MiB|1676.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3597.0MiB|3597.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.818GiB|20.818GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.797GiB|47.797GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.681GiB|17.681GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.653GiB|27.653GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.78GiB|42.78GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.481GiB|37.481GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |987.0MiB|987.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |7102.0MiB|7102.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.122GiB|54.122GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |934.0MiB|934.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1608.0MiB|1608.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |4759.0MiB|4759.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4675.0MiB|4675.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4749.0MiB|4749.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5037.0MiB|5037.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |515.0MiB|515.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.099GiB|32.099GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1676.0MiB|1676.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3597.0MiB|3597.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.818GiB|20.818GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.797GiB|47.797GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.681GiB|17.681GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.653GiB|27.653GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.78GiB|42.78GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.481GiB|37.481GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |987.0MiB|987.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |7102.0MiB|7102.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.122GiB|54.122GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |934.0MiB|934.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1608.0MiB|1608.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |4759.0MiB|4759.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4675.0MiB|4675.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4749.0MiB|4749.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5037.0MiB|5037.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |515.0MiB|515.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.099GiB|32.099GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1676.0MiB|1676.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3597.0MiB|3597.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.818GiB|20.818GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.797GiB|47.797GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.681GiB|17.681GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.653GiB|27.653GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.78GiB|42.78GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.481GiB|37.481GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |987.0MiB|987.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |7102.0MiB|7102.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.122GiB|54.122GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |934.0MiB|934.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1608.0MiB|1608.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |4759.0MiB|4759.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4675.0MiB|4675.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4749.0MiB|4749.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5037.0MiB|5037.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |515.0MiB|515.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.099GiB|32.099GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1676.0MiB|1676.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3597.0MiB|3597.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.818GiB|20.818GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.703s |62.593GiB|
|scrambled4299.smt2                                                                         |1205.217s |56.475GiB|
|scrambled12042.smt2                                                                        |1204.781s |54.122GiB|
|scrambled55680.smt2                                                                        |1204.392s |50.305GiB|
|scrambled4198.smt2                                                                         |1204.327s |48.976GiB|
|scrambled102166.smt2                                                                       |1204.223s |47.797GiB|
|scrambled68944.smt2                                                                        |1204.194s |46.51GiB|
|scrambled79760.smt2                                                                        |1203.831s |44.157GiB|
|scrambled108840.smt2                                                                       |1203.749s |42.78GiB|
|scrambled111627.smt2                                                                       |1203.676s |37.481GiB|
|scrambled43577.smt2                                                                        |1202.987s |34.098GiB|
|scrambled19335.smt2                                                                        |1202.960s |32.099GiB|
|scrambled75189.smt2                                                                        |1202.898s |31.477GiB|
|scrambled107826.smt2                                                                       |1202.652s |27.653GiB|
|scrambled27843.smt2                                                                        |1203.136s |20.818GiB|
|scrambled107115.smt2                                                                       |1201.703s |17.681GiB|
|scrambled61922.smt2                                                                        |1201.097s |10.755GiB|
|scrambled119331.smt2                                                                       |1200.738s |7102.0MiB|
|scrambled40621.smt2                                                                        |1200.824s |6364.0MiB|
|scrambled7741.smt2                                                                         |1200.640s |5949.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.703s |62.593GiB|
|scrambled4299.smt2                                                                         |1205.217s |56.475GiB|
|scrambled12042.smt2                                                                        |1204.781s |54.122GiB|
|scrambled55680.smt2                                                                        |1204.392s |50.305GiB|
|scrambled4198.smt2                                                                         |1204.327s |48.976GiB|
|scrambled102166.smt2                                                                       |1204.223s |47.797GiB|
|scrambled68944.smt2                                                                        |1204.194s |46.51GiB|
|scrambled79760.smt2                                                                        |1203.831s |44.157GiB|
|scrambled108840.smt2                                                                       |1203.749s |42.78GiB|
|scrambled111627.smt2                                                                       |1203.676s |37.481GiB|
|scrambled43577.smt2                                                                        |1202.987s |34.098GiB|
|scrambled19335.smt2                                                                        |1202.960s |32.099GiB|
|scrambled75189.smt2                                                                        |1202.898s |31.477GiB|
|scrambled107826.smt2                                                                       |1202.652s |27.653GiB|
|scrambled27843.smt2                                                                        |1203.136s |20.818GiB|
|scrambled107115.smt2                                                                       |1201.703s |17.681GiB|
|scrambled61922.smt2                                                                        |1201.097s |10.755GiB|
|scrambled119331.smt2                                                                       |1200.738s |7102.0MiB|
|scrambled40621.smt2                                                                        |1200.824s |6364.0MiB|
|scrambled7741.smt2                                                                         |1200.640s |5949.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.223s  |1204.223s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.703s  |1201.703s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.652s  |1202.652s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.749s  |1203.749s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.676s  |1203.676s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 835.515s  | 835.515s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.738s  |1200.738s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.781s  |1204.781s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  40.534s  |  40.534s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 599.596s  | 599.596s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 324.730s  | 324.730s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.471s  |1200.471s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.644s  |1200.644s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.624s  |1200.624s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.960s  |1202.960s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 686.503s  | 686.503s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  86.487s  |  86.487s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1203.136s  |1203.136s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.415s  |1200.415s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1200.824s  |1200.824s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1204.327s  |1204.327s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1205.217s  |1205.217s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1202.987s  |1202.987s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.831s  |1200.831s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.379s  |1200.379s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1204.392s  |1204.392s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.380s  |1200.380s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1201.097s  |1201.097s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1204.194s  |1204.194s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         | 971.956s  | 971.956s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1202.898s  |1202.898s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.640s  |1200.640s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1203.831s  |1203.831s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.030s  |1200.030s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1205.703s  |1205.703s  |   0.000s  | 0.0%|
</details>
