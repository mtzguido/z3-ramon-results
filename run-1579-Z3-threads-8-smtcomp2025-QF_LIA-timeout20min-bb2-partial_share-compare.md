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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-partial_share
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6045ce393fc70dffef4ebb7a9ce331b9ce5095c6
Z3 branch: 6045ce393fc70dffef4ebb7a9ce331b9ce5095c6
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: change share units ordering

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-partial_share
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6045ce393fc70dffef4ebb7a9ce331b9ce5095c6
Z3 branch: 6045ce393fc70dffef4ebb7a9ce331b9ce5095c6
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: change share units ordering

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.279s  |1204.279s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.741s  |1201.741s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.609s  |1202.609s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.903s  |1203.903s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.735s  |1203.735s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 222.419s  | 222.419s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.892s  |1200.892s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.892s  |1204.892s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 140.868s  | 140.868s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 140.458s  | 140.458s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.632s  |1200.632s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.593s  |1200.593s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.626s  |1200.626s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.974s  |1200.974s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.805s  |1203.805s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 133.688s  | 133.688s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 213.766s  | 213.766s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.586s  |1202.586s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.279s  |1204.279s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.741s  |1201.741s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.609s  |1202.609s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.903s  |1203.903s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.735s  |1203.735s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 222.419s  | 222.419s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.892s  |1200.892s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.892s  |1204.892s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 140.868s  | 140.868s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 140.458s  | 140.458s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.632s  |1200.632s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.593s  |1200.593s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.626s  |1200.626s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.974s  |1200.974s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.805s  |1203.805s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 133.688s  | 133.688s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 213.766s  | 213.766s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.586s  |1202.586s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.279s  |1204.279s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.741s  |1201.741s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.609s  |1202.609s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.903s  |1203.903s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.735s  |1203.735s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 222.419s  | 222.419s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.892s  |1200.892s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.892s  |1204.892s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 140.868s  | 140.868s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 140.458s  | 140.458s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.632s  |1200.632s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.593s  |1200.593s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.626s  |1200.626s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.974s  |1200.974s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.805s  |1203.805s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 133.688s  | 133.688s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 213.766s  | 213.766s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.586s  |1202.586s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.279s  |1204.279s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.741s  |1201.741s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.609s  |1202.609s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.903s  |1203.903s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.735s  |1203.735s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 222.419s  | 222.419s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.892s  |1200.892s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.892s  |1204.892s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 140.868s  | 140.868s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 140.458s  | 140.458s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.632s  |1200.632s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.593s  |1200.593s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.626s  |1200.626s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.974s  |1200.974s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.805s  |1203.805s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 133.688s  | 133.688s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 213.766s  | 213.766s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.586s  |1202.586s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.968s |63.01GiB|
|scrambled4299.smt2                                                                         |1204.981s |56.788GiB|
|scrambled12042.smt2                                                                        |1204.892s |54.502GiB|
|scrambled55680.smt2                                                                        |1204.452s |50.682GiB|
|scrambled4198.smt2                                                                         |1204.450s |48.996GiB|
|scrambled68944.smt2                                                                        |1204.447s |46.888GiB|
|scrambled102166.smt2                                                                       |1204.279s |48.143GiB|
|scrambled79760.smt2                                                                        |1204.007s |44.262GiB|
|scrambled43577.smt2                                                                        |1203.916s |34.289GiB|
|scrambled108840.smt2                                                                       |1203.903s |43.071GiB|
|scrambled19335.smt2                                                                        |1203.805s |32.17GiB|
|scrambled111627.smt2                                                                       |1203.735s |37.746GiB|
|scrambled75189.smt2                                                                        |1202.923s |31.688GiB|
|scrambled107826.smt2                                                                       |1202.609s |27.974GiB|
|scrambled27843.smt2                                                                        |1202.586s |20.887GiB|
|scrambled107115.smt2                                                                       |1201.741s |17.784GiB|
|scrambled61922.smt2                                                                        |1201.277s |10.831GiB|
|scrambled40621.smt2                                                                        |1201.142s |11.042GiB|
|scrambled131241.smt2                                                                       |1200.974s |6432.0MiB|
|scrambled119331.smt2                                                                       |1200.892s |9414.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.968s |63.01GiB|
|scrambled4299.smt2                                                                         |1204.981s |56.788GiB|
|scrambled12042.smt2                                                                        |1204.892s |54.502GiB|
|scrambled55680.smt2                                                                        |1204.452s |50.682GiB|
|scrambled4198.smt2                                                                         |1204.450s |48.996GiB|
|scrambled68944.smt2                                                                        |1204.447s |46.888GiB|
|scrambled102166.smt2                                                                       |1204.279s |48.143GiB|
|scrambled79760.smt2                                                                        |1204.007s |44.262GiB|
|scrambled43577.smt2                                                                        |1203.916s |34.289GiB|
|scrambled108840.smt2                                                                       |1203.903s |43.071GiB|
|scrambled19335.smt2                                                                        |1203.805s |32.17GiB|
|scrambled111627.smt2                                                                       |1203.735s |37.746GiB|
|scrambled75189.smt2                                                                        |1202.923s |31.688GiB|
|scrambled107826.smt2                                                                       |1202.609s |27.974GiB|
|scrambled27843.smt2                                                                        |1202.586s |20.887GiB|
|scrambled107115.smt2                                                                       |1201.741s |17.784GiB|
|scrambled61922.smt2                                                                        |1201.277s |10.831GiB|
|scrambled40621.smt2                                                                        |1201.142s |11.042GiB|
|scrambled131241.smt2                                                                       |1200.974s |6432.0MiB|
|scrambled119331.smt2                                                                       |1200.892s |9414.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.143GiB|48.143GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.804MiB|42.804MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.784GiB|17.784GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.974GiB|27.974GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.071GiB|43.071GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.746GiB|37.746GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |989.0MiB|989.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9414.0MiB|9414.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.502GiB|54.502GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1010.0MiB|1010.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1608.0MiB|1608.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6483.0MiB|6483.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5200.0MiB|5200.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5188.0MiB|5188.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6432.0MiB|6432.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |374.0MiB|374.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.17GiB|32.17GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1640.0MiB|1640.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5932.0MiB|5932.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.887GiB|20.887GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.143GiB|48.143GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.804MiB|42.804MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.784GiB|17.784GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.974GiB|27.974GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.071GiB|43.071GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.746GiB|37.746GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |989.0MiB|989.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9414.0MiB|9414.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.502GiB|54.502GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1010.0MiB|1010.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1608.0MiB|1608.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6483.0MiB|6483.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5200.0MiB|5200.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5188.0MiB|5188.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6432.0MiB|6432.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |374.0MiB|374.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.17GiB|32.17GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1640.0MiB|1640.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5932.0MiB|5932.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.887GiB|20.887GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.143GiB|48.143GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.804MiB|42.804MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.784GiB|17.784GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.974GiB|27.974GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.071GiB|43.071GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.746GiB|37.746GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |989.0MiB|989.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9414.0MiB|9414.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.502GiB|54.502GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1010.0MiB|1010.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1608.0MiB|1608.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6483.0MiB|6483.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5200.0MiB|5200.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5188.0MiB|5188.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6432.0MiB|6432.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |374.0MiB|374.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.17GiB|32.17GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1640.0MiB|1640.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5932.0MiB|5932.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.887GiB|20.887GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.143GiB|48.143GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.804MiB|42.804MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.784GiB|17.784GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.974GiB|27.974GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.071GiB|43.071GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.746GiB|37.746GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |989.0MiB|989.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9414.0MiB|9414.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.502GiB|54.502GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1010.0MiB|1010.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1608.0MiB|1608.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6483.0MiB|6483.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5200.0MiB|5200.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5188.0MiB|5188.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6432.0MiB|6432.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |374.0MiB|374.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.17GiB|32.17GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1640.0MiB|1640.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5932.0MiB|5932.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.887GiB|20.887GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.968s |63.01GiB|
|scrambled4299.smt2                                                                         |1204.981s |56.788GiB|
|scrambled12042.smt2                                                                        |1204.892s |54.502GiB|
|scrambled55680.smt2                                                                        |1204.452s |50.682GiB|
|scrambled4198.smt2                                                                         |1204.450s |48.996GiB|
|scrambled102166.smt2                                                                       |1204.279s |48.143GiB|
|scrambled68944.smt2                                                                        |1204.447s |46.888GiB|
|scrambled79760.smt2                                                                        |1204.007s |44.262GiB|
|scrambled108840.smt2                                                                       |1203.903s |43.071GiB|
|scrambled111627.smt2                                                                       |1203.735s |37.746GiB|
|scrambled43577.smt2                                                                        |1203.916s |34.289GiB|
|scrambled19335.smt2                                                                        |1203.805s |32.17GiB|
|scrambled75189.smt2                                                                        |1202.923s |31.688GiB|
|scrambled107826.smt2                                                                       |1202.609s |27.974GiB|
|scrambled27843.smt2                                                                        |1202.586s |20.887GiB|
|scrambled107115.smt2                                                                       |1201.741s |17.784GiB|
|scrambled40621.smt2                                                                        |1201.142s |11.042GiB|
|scrambled61922.smt2                                                                        |1201.277s |10.831GiB|
|scrambled119331.smt2                                                                       |1200.892s |9414.0MiB|
|scrambled7741.smt2                                                                         |1200.761s |6731.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.968s |63.01GiB|
|scrambled4299.smt2                                                                         |1204.981s |56.788GiB|
|scrambled12042.smt2                                                                        |1204.892s |54.502GiB|
|scrambled55680.smt2                                                                        |1204.452s |50.682GiB|
|scrambled4198.smt2                                                                         |1204.450s |48.996GiB|
|scrambled102166.smt2                                                                       |1204.279s |48.143GiB|
|scrambled68944.smt2                                                                        |1204.447s |46.888GiB|
|scrambled79760.smt2                                                                        |1204.007s |44.262GiB|
|scrambled108840.smt2                                                                       |1203.903s |43.071GiB|
|scrambled111627.smt2                                                                       |1203.735s |37.746GiB|
|scrambled43577.smt2                                                                        |1203.916s |34.289GiB|
|scrambled19335.smt2                                                                        |1203.805s |32.17GiB|
|scrambled75189.smt2                                                                        |1202.923s |31.688GiB|
|scrambled107826.smt2                                                                       |1202.609s |27.974GiB|
|scrambled27843.smt2                                                                        |1202.586s |20.887GiB|
|scrambled107115.smt2                                                                       |1201.741s |17.784GiB|
|scrambled40621.smt2                                                                        |1201.142s |11.042GiB|
|scrambled61922.smt2                                                                        |1201.277s |10.831GiB|
|scrambled119331.smt2                                                                       |1200.892s |9414.0MiB|
|scrambled7741.smt2                                                                         |1200.761s |6731.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.279s  |1204.279s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.741s  |1201.741s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.609s  |1202.609s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.903s  |1203.903s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.735s  |1203.735s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 222.419s  | 222.419s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.892s  |1200.892s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.892s  |1204.892s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 140.868s  | 140.868s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 140.458s  | 140.458s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.632s  |1200.632s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.593s  |1200.593s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.626s  |1200.626s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.974s  |1200.974s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.805s  |1203.805s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 133.688s  | 133.688s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 213.766s  | 213.766s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.586s  |1202.586s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.495s  |1200.495s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1201.142s  |1201.142s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1204.450s  |1204.450s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1204.981s  |1204.981s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1203.916s  |1203.916s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.711s  |1200.711s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.394s  |1200.394s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1204.452s  |1204.452s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.569s  |1200.569s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1201.277s  |1201.277s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1204.447s  |1204.447s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1143.780s  |1143.780s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1202.923s  |1202.923s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.761s  |1200.761s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1204.007s  |1204.007s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1205.968s  |1205.968s  |   0.000s  | 0.0%|
</details>
