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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-FL2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 4e0f9c891a995745172a1fc312ffb9b4544561e3
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_fl_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: ablate continuous checking for batch bb mode

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-FL2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 4e0f9c891a995745172a1fc312ffb9b4544561e3
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_fl_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: ablate continuous checking for batch bb mode

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.359s  |1204.359s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.732s  |1201.732s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.618s  |1202.618s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.995s  |1203.995s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.663s  |1203.663s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 120.093s  | 120.093s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.985s  |1200.985s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.919s  |1204.919s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  91.625s  |  91.625s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  68.095s  |  68.095s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.615s  |1200.615s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.537s  |1200.537s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.648s  |1200.648s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.761s  |1200.761s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1204.139s  |1204.139s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 108.701s  | 108.701s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 211.439s  | 211.439s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.506s  |1202.506s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.359s  |1204.359s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.732s  |1201.732s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.618s  |1202.618s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.995s  |1203.995s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.663s  |1203.663s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 120.093s  | 120.093s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.985s  |1200.985s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.919s  |1204.919s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  91.625s  |  91.625s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  68.095s  |  68.095s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.615s  |1200.615s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.537s  |1200.537s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.648s  |1200.648s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.761s  |1200.761s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1204.139s  |1204.139s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 108.701s  | 108.701s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 211.439s  | 211.439s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.506s  |1202.506s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.359s  |1204.359s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.732s  |1201.732s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.618s  |1202.618s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.995s  |1203.995s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.663s  |1203.663s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 120.093s  | 120.093s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.985s  |1200.985s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.919s  |1204.919s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  91.625s  |  91.625s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  68.095s  |  68.095s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.615s  |1200.615s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.537s  |1200.537s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.648s  |1200.648s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.761s  |1200.761s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1204.139s  |1204.139s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 108.701s  | 108.701s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 211.439s  | 211.439s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.506s  |1202.506s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.359s  |1204.359s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.732s  |1201.732s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.618s  |1202.618s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.995s  |1203.995s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.663s  |1203.663s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 120.093s  | 120.093s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.985s  |1200.985s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.919s  |1204.919s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  91.625s  |  91.625s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  68.095s  |  68.095s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.615s  |1200.615s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.537s  |1200.537s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.648s  |1200.648s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.761s  |1200.761s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1204.139s  |1204.139s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 108.701s  | 108.701s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 211.439s  | 211.439s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.506s  |1202.506s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.214s |63.454GiB|
|scrambled4299.smt2                                                                         |1206.129s |56.589GiB|
|scrambled79760.smt2                                                                        |1205.146s |43.999GiB|
|scrambled12042.smt2                                                                        |1204.919s |54.51GiB|
|scrambled68944.smt2                                                                        |1204.693s |46.416GiB|
|scrambled55680.smt2                                                                        |1204.620s |50.724GiB|
|scrambled4198.smt2                                                                         |1204.369s |49.031GiB|
|scrambled102166.smt2                                                                       |1204.359s |48.183GiB|
|scrambled19335.smt2                                                                        |1204.139s |32.354GiB|
|scrambled108840.smt2                                                                       |1203.995s |43.09GiB|
|scrambled111627.smt2                                                                       |1203.663s |37.773GiB|
|scrambled43577.smt2                                                                        |1203.144s |34.362GiB|
|scrambled75189.smt2                                                                        |1202.869s |31.687GiB|
|scrambled107826.smt2                                                                       |1202.618s |27.943GiB|
|scrambled27843.smt2                                                                        |1202.506s |21.025GiB|
|scrambled61922.smt2                                                                        |1202.122s |10.841GiB|
|scrambled107115.smt2                                                                       |1201.732s |17.778GiB|
|scrambled40621.smt2                                                                        |1201.176s |11.637GiB|
|scrambled44911.smt2                                                                        |1201.115s |5077.0MiB|
|scrambled119331.smt2                                                                       |1200.985s |9740.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.214s |63.454GiB|
|scrambled4299.smt2                                                                         |1206.129s |56.589GiB|
|scrambled79760.smt2                                                                        |1205.146s |43.999GiB|
|scrambled12042.smt2                                                                        |1204.919s |54.51GiB|
|scrambled68944.smt2                                                                        |1204.693s |46.416GiB|
|scrambled55680.smt2                                                                        |1204.620s |50.724GiB|
|scrambled4198.smt2                                                                         |1204.369s |49.031GiB|
|scrambled102166.smt2                                                                       |1204.359s |48.183GiB|
|scrambled19335.smt2                                                                        |1204.139s |32.354GiB|
|scrambled108840.smt2                                                                       |1203.995s |43.09GiB|
|scrambled111627.smt2                                                                       |1203.663s |37.773GiB|
|scrambled43577.smt2                                                                        |1203.144s |34.362GiB|
|scrambled75189.smt2                                                                        |1202.869s |31.687GiB|
|scrambled107826.smt2                                                                       |1202.618s |27.943GiB|
|scrambled27843.smt2                                                                        |1202.506s |21.025GiB|
|scrambled61922.smt2                                                                        |1202.122s |10.841GiB|
|scrambled107115.smt2                                                                       |1201.732s |17.778GiB|
|scrambled40621.smt2                                                                        |1201.176s |11.637GiB|
|scrambled44911.smt2                                                                        |1201.115s |5077.0MiB|
|scrambled119331.smt2                                                                       |1200.985s |9740.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.183GiB|48.183GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.812MiB|42.812MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.778GiB|17.778GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.943GiB|27.943GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.09GiB|43.09GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.773GiB|37.773GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |962.0MiB|962.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9740.0MiB|9740.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.51GiB|54.51GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1014.0MiB|1014.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1551.0MiB|1551.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6564.0MiB|6564.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5212.0MiB|5212.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5177.0MiB|5177.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6487.0MiB|6487.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |403.0MiB|403.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.354GiB|32.354GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1634.0MiB|1634.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5987.0MiB|5987.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.025GiB|21.025GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.183GiB|48.183GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.812MiB|42.812MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.778GiB|17.778GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.943GiB|27.943GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.09GiB|43.09GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.773GiB|37.773GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |962.0MiB|962.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9740.0MiB|9740.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.51GiB|54.51GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1014.0MiB|1014.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1551.0MiB|1551.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6564.0MiB|6564.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5212.0MiB|5212.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5177.0MiB|5177.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6487.0MiB|6487.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |403.0MiB|403.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.354GiB|32.354GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1634.0MiB|1634.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5987.0MiB|5987.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.025GiB|21.025GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.183GiB|48.183GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.812MiB|42.812MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.778GiB|17.778GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.943GiB|27.943GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.09GiB|43.09GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.773GiB|37.773GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |962.0MiB|962.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9740.0MiB|9740.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.51GiB|54.51GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1014.0MiB|1014.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1551.0MiB|1551.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6564.0MiB|6564.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5212.0MiB|5212.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5177.0MiB|5177.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6487.0MiB|6487.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |403.0MiB|403.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.354GiB|32.354GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1634.0MiB|1634.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5987.0MiB|5987.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.025GiB|21.025GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.183GiB|48.183GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.812MiB|42.812MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.778GiB|17.778GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.943GiB|27.943GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.09GiB|43.09GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.773GiB|37.773GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |962.0MiB|962.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9740.0MiB|9740.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.51GiB|54.51GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1014.0MiB|1014.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1551.0MiB|1551.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6564.0MiB|6564.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5212.0MiB|5212.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5177.0MiB|5177.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6487.0MiB|6487.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |403.0MiB|403.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.354GiB|32.354GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1634.0MiB|1634.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5987.0MiB|5987.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.025GiB|21.025GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.214s |63.454GiB|
|scrambled4299.smt2                                                                         |1206.129s |56.589GiB|
|scrambled12042.smt2                                                                        |1204.919s |54.51GiB|
|scrambled55680.smt2                                                                        |1204.620s |50.724GiB|
|scrambled4198.smt2                                                                         |1204.369s |49.031GiB|
|scrambled102166.smt2                                                                       |1204.359s |48.183GiB|
|scrambled68944.smt2                                                                        |1204.693s |46.416GiB|
|scrambled79760.smt2                                                                        |1205.146s |43.999GiB|
|scrambled108840.smt2                                                                       |1203.995s |43.09GiB|
|scrambled111627.smt2                                                                       |1203.663s |37.773GiB|
|scrambled43577.smt2                                                                        |1203.144s |34.362GiB|
|scrambled19335.smt2                                                                        |1204.139s |32.354GiB|
|scrambled75189.smt2                                                                        |1202.869s |31.687GiB|
|scrambled107826.smt2                                                                       |1202.618s |27.943GiB|
|scrambled27843.smt2                                                                        |1202.506s |21.025GiB|
|scrambled107115.smt2                                                                       |1201.732s |17.778GiB|
|scrambled40621.smt2                                                                        |1201.176s |11.637GiB|
|scrambled61922.smt2                                                                        |1202.122s |10.841GiB|
|scrambled119331.smt2                                                                       |1200.985s |9740.0MiB|
|scrambled7741.smt2                                                                         |1200.770s |6783.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.214s |63.454GiB|
|scrambled4299.smt2                                                                         |1206.129s |56.589GiB|
|scrambled12042.smt2                                                                        |1204.919s |54.51GiB|
|scrambled55680.smt2                                                                        |1204.620s |50.724GiB|
|scrambled4198.smt2                                                                         |1204.369s |49.031GiB|
|scrambled102166.smt2                                                                       |1204.359s |48.183GiB|
|scrambled68944.smt2                                                                        |1204.693s |46.416GiB|
|scrambled79760.smt2                                                                        |1205.146s |43.999GiB|
|scrambled108840.smt2                                                                       |1203.995s |43.09GiB|
|scrambled111627.smt2                                                                       |1203.663s |37.773GiB|
|scrambled43577.smt2                                                                        |1203.144s |34.362GiB|
|scrambled19335.smt2                                                                        |1204.139s |32.354GiB|
|scrambled75189.smt2                                                                        |1202.869s |31.687GiB|
|scrambled107826.smt2                                                                       |1202.618s |27.943GiB|
|scrambled27843.smt2                                                                        |1202.506s |21.025GiB|
|scrambled107115.smt2                                                                       |1201.732s |17.778GiB|
|scrambled40621.smt2                                                                        |1201.176s |11.637GiB|
|scrambled61922.smt2                                                                        |1202.122s |10.841GiB|
|scrambled119331.smt2                                                                       |1200.985s |9740.0MiB|
|scrambled7741.smt2                                                                         |1200.770s |6783.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.359s  |1204.359s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.732s  |1201.732s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.618s  |1202.618s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.995s  |1203.995s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.663s  |1203.663s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 120.093s  | 120.093s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.985s  |1200.985s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.919s  |1204.919s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  91.625s  |  91.625s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  68.095s  |  68.095s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.615s  |1200.615s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.537s  |1200.537s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.648s  |1200.648s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.761s  |1200.761s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1204.139s  |1204.139s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 108.701s  | 108.701s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 211.439s  | 211.439s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.506s  |1202.506s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.495s  |1200.495s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1201.176s  |1201.176s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1204.369s  |1204.369s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1206.129s  |1206.129s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1203.144s  |1203.144s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1201.115s  |1201.115s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.494s  |1200.494s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1204.620s  |1204.620s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.497s  |1200.497s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1202.122s  |1202.122s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1204.693s  |1204.693s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         | 212.077s  | 212.077s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1202.869s  |1202.869s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.770s  |1200.770s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1205.146s  |1205.146s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1206.214s  |1206.214s  |   0.000s  | 0.0%|
</details>
