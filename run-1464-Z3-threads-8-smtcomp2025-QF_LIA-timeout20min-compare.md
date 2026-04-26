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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: d41610a46ca6d0169bdc562311fed3fd69e2b769
Z3 branch: d41610a46ca6d0169bdc562311fed3fd69e2b769
Z3 options: "-T:60 -v:0 smt.threads=8"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: reinstate FL check for new batch with epochs, before merge, this is a temp branch

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: d41610a46ca6d0169bdc562311fed3fd69e2b769
Z3 branch: d41610a46ca6d0169bdc562311fed3fd69e2b769
Z3 options: "-T:60 -v:0 smt.threads=8"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: reinstate FL check for new batch with epochs, before merge, this is a temp branch

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  60.224s  |  60.224s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  60.036s  |  60.036s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  60.122s  |  60.122s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  50.934s  |  50.934s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  60.155s  |  60.155s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  60.167s  |  60.167s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  60.111s  |  60.111s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  60.504s  |  60.504s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  60.309s  |  60.309s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  60.128s  |  60.128s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  60.213s  |  60.213s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  60.388s  |  60.388s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  60.347s  |  60.347s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  60.444s  |  60.444s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  60.317s  |  60.317s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  60.041s  |  60.041s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  60.130s  |  60.130s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  60.193s  |  60.193s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  60.479s  |  60.479s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  60.081s  |  60.081s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  60.224s  |  60.224s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  60.036s  |  60.036s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  60.122s  |  60.122s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  50.934s  |  50.934s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  60.155s  |  60.155s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  60.167s  |  60.167s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  60.111s  |  60.111s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  60.504s  |  60.504s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  60.309s  |  60.309s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  60.128s  |  60.128s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  60.213s  |  60.213s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  60.388s  |  60.388s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  60.347s  |  60.347s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  60.444s  |  60.444s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  60.317s  |  60.317s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  60.041s  |  60.041s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  60.130s  |  60.130s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  60.193s  |  60.193s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  60.479s  |  60.479s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  60.081s  |  60.081s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  60.224s  |  60.224s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  60.036s  |  60.036s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  60.122s  |  60.122s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  50.934s  |  50.934s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  60.155s  |  60.155s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  60.167s  |  60.167s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  60.111s  |  60.111s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  60.504s  |  60.504s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  60.309s  |  60.309s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  60.128s  |  60.128s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  60.213s  |  60.213s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  60.388s  |  60.388s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  60.347s  |  60.347s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  60.444s  |  60.444s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  60.317s  |  60.317s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  60.041s  |  60.041s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  60.130s  |  60.130s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  60.193s  |  60.193s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  60.479s  |  60.479s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  60.081s  |  60.081s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  60.224s  |  60.224s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  60.036s  |  60.036s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  60.122s  |  60.122s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  50.934s  |  50.934s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  60.155s  |  60.155s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  60.167s  |  60.167s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  60.111s  |  60.111s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  60.504s  |  60.504s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  60.309s  |  60.309s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  60.128s  |  60.128s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  60.213s  |  60.213s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  60.388s  |  60.388s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  60.347s  |  60.347s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  60.444s  |  60.444s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  60.317s  |  60.317s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  60.041s  |  60.041s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  60.130s  |  60.130s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  60.193s  |  60.193s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  60.479s  |  60.479s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  60.081s  |  60.081s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled40621.smt2                                                                        |  60.597s |3567.0MiB|
|scrambled119331.smt2                                                                       |  60.504s |3177.0MiB|
|scrambled25238.smt2                                                                        |  60.479s |3245.0MiB|
|scrambled128874.smt2                                                                       |  60.444s |2417.0MiB|
|scrambled44911.smt2                                                                        |  60.403s |2297.0MiB|
|scrambled128128.smt2                                                                       |  60.388s |2559.0MiB|
|scrambled7741.smt2                                                                         |  60.384s |2432.0MiB|
|scrambled72668.smt2                                                                        |  60.370s |2698.0MiB|
|scrambled128732.smt2                                                                       |  60.347s |2347.0MiB|
|scrambled32836.smt2                                                                        |  60.329s |1809.0MiB|
|scrambled131241.smt2                                                                       |  60.317s |2831.0MiB|
|scrambled12042.smt2                                                                        |  60.309s |2264.0MiB|
|scrambled55777.smt2                                                                        |  60.287s |2271.0MiB|
|scrambled4198.smt2                                                                         |  60.277s |2286.0MiB|
|scrambled94658.smt2                                                                        |  60.268s |2288.0MiB|
|scrambled95803.smt2                                                                        |  60.248s |1558.0MiB|
|scrambled55680.smt2                                                                        |  60.244s |2137.0MiB|
|scrambled102166.smt2                                                                       |  60.224s |1942.0MiB|
|scrambled125888.smt2                                                                       |  60.213s |1271.0MiB|
|scrambled4299.smt2                                                                         |  60.197s |1251.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled40621.smt2                                                                        |  60.597s |3567.0MiB|
|scrambled119331.smt2                                                                       |  60.504s |3177.0MiB|
|scrambled25238.smt2                                                                        |  60.479s |3245.0MiB|
|scrambled128874.smt2                                                                       |  60.444s |2417.0MiB|
|scrambled44911.smt2                                                                        |  60.403s |2297.0MiB|
|scrambled128128.smt2                                                                       |  60.388s |2559.0MiB|
|scrambled7741.smt2                                                                         |  60.384s |2432.0MiB|
|scrambled72668.smt2                                                                        |  60.370s |2698.0MiB|
|scrambled128732.smt2                                                                       |  60.347s |2347.0MiB|
|scrambled32836.smt2                                                                        |  60.329s |1809.0MiB|
|scrambled131241.smt2                                                                       |  60.317s |2831.0MiB|
|scrambled12042.smt2                                                                        |  60.309s |2264.0MiB|
|scrambled55777.smt2                                                                        |  60.287s |2271.0MiB|
|scrambled4198.smt2                                                                         |  60.277s |2286.0MiB|
|scrambled94658.smt2                                                                        |  60.268s |2288.0MiB|
|scrambled95803.smt2                                                                        |  60.248s |1558.0MiB|
|scrambled55680.smt2                                                                        |  60.244s |2137.0MiB|
|scrambled102166.smt2                                                                       |  60.224s |1942.0MiB|
|scrambled125888.smt2                                                                       |  60.213s |1271.0MiB|
|scrambled4299.smt2                                                                         |  60.197s |1251.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1942.0MiB|1942.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.316MiB|43.316MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |601.0MiB|601.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1126.0MiB|1126.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1237.0MiB|1237.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1160.0MiB|1160.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |789.0MiB|789.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3177.0MiB|3177.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2264.0MiB|2264.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |860.0MiB|860.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1271.0MiB|1271.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2559.0MiB|2559.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2347.0MiB|2347.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2417.0MiB|2417.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2831.0MiB|2831.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1118.0MiB|1118.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1290.0MiB|1290.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3245.0MiB|3245.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |642.0MiB|642.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1942.0MiB|1942.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.316MiB|43.316MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |601.0MiB|601.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1126.0MiB|1126.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1237.0MiB|1237.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1160.0MiB|1160.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |789.0MiB|789.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3177.0MiB|3177.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2264.0MiB|2264.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |860.0MiB|860.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1271.0MiB|1271.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2559.0MiB|2559.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2347.0MiB|2347.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2417.0MiB|2417.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2831.0MiB|2831.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1118.0MiB|1118.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1290.0MiB|1290.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3245.0MiB|3245.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |642.0MiB|642.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1942.0MiB|1942.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.316MiB|43.316MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |601.0MiB|601.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1126.0MiB|1126.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1237.0MiB|1237.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1160.0MiB|1160.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |789.0MiB|789.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3177.0MiB|3177.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2264.0MiB|2264.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |860.0MiB|860.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1271.0MiB|1271.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2559.0MiB|2559.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2347.0MiB|2347.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2417.0MiB|2417.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2831.0MiB|2831.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1118.0MiB|1118.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1290.0MiB|1290.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3245.0MiB|3245.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |642.0MiB|642.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1942.0MiB|1942.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.316MiB|43.316MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |601.0MiB|601.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1126.0MiB|1126.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1237.0MiB|1237.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1160.0MiB|1160.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |789.0MiB|789.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3177.0MiB|3177.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2264.0MiB|2264.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |860.0MiB|860.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1271.0MiB|1271.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2559.0MiB|2559.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2347.0MiB|2347.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2417.0MiB|2417.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2831.0MiB|2831.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1118.0MiB|1118.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1290.0MiB|1290.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3245.0MiB|3245.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |642.0MiB|642.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled40621.smt2                                                                        |  60.597s |3567.0MiB|
|scrambled25238.smt2                                                                        |  60.479s |3245.0MiB|
|scrambled119331.smt2                                                                       |  60.504s |3177.0MiB|
|scrambled131241.smt2                                                                       |  60.317s |2831.0MiB|
|scrambled72668.smt2                                                                        |  60.370s |2698.0MiB|
|scrambled128128.smt2                                                                       |  60.388s |2559.0MiB|
|scrambled7741.smt2                                                                         |  60.384s |2432.0MiB|
|scrambled128874.smt2                                                                       |  60.444s |2417.0MiB|
|scrambled128732.smt2                                                                       |  60.347s |2347.0MiB|
|scrambled44911.smt2                                                                        |  60.403s |2297.0MiB|
|scrambled94658.smt2                                                                        |  60.268s |2288.0MiB|
|scrambled4198.smt2                                                                         |  60.277s |2286.0MiB|
|scrambled55777.smt2                                                                        |  60.287s |2271.0MiB|
|scrambled12042.smt2                                                                        |  60.309s |2264.0MiB|
|scrambled55680.smt2                                                                        |  60.244s |2137.0MiB|
|scrambled102166.smt2                                                                       |  60.224s |1942.0MiB|
|scrambled32836.smt2                                                                        |  60.329s |1809.0MiB|
|scrambled95803.smt2                                                                        |  60.248s |1558.0MiB|
|scrambled20101.smt2                                                                        |  60.193s |1290.0MiB|
|scrambled125888.smt2                                                                       |  60.213s |1271.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled40621.smt2                                                                        |  60.597s |3567.0MiB|
|scrambled25238.smt2                                                                        |  60.479s |3245.0MiB|
|scrambled119331.smt2                                                                       |  60.504s |3177.0MiB|
|scrambled131241.smt2                                                                       |  60.317s |2831.0MiB|
|scrambled72668.smt2                                                                        |  60.370s |2698.0MiB|
|scrambled128128.smt2                                                                       |  60.388s |2559.0MiB|
|scrambled7741.smt2                                                                         |  60.384s |2432.0MiB|
|scrambled128874.smt2                                                                       |  60.444s |2417.0MiB|
|scrambled128732.smt2                                                                       |  60.347s |2347.0MiB|
|scrambled44911.smt2                                                                        |  60.403s |2297.0MiB|
|scrambled94658.smt2                                                                        |  60.268s |2288.0MiB|
|scrambled4198.smt2                                                                         |  60.277s |2286.0MiB|
|scrambled55777.smt2                                                                        |  60.287s |2271.0MiB|
|scrambled12042.smt2                                                                        |  60.309s |2264.0MiB|
|scrambled55680.smt2                                                                        |  60.244s |2137.0MiB|
|scrambled102166.smt2                                                                       |  60.224s |1942.0MiB|
|scrambled32836.smt2                                                                        |  60.329s |1809.0MiB|
|scrambled95803.smt2                                                                        |  60.248s |1558.0MiB|
|scrambled20101.smt2                                                                        |  60.193s |1290.0MiB|
|scrambled125888.smt2                                                                       |  60.213s |1271.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  60.224s  |  60.224s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  60.036s  |  60.036s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  60.122s  |  60.122s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  50.934s  |  50.934s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  60.155s  |  60.155s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  60.167s  |  60.167s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  60.111s  |  60.111s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  60.504s  |  60.504s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  60.309s  |  60.309s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  60.128s  |  60.128s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  60.213s  |  60.213s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  60.388s  |  60.388s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  60.347s  |  60.347s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  60.444s  |  60.444s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  60.317s  |  60.317s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  60.041s  |  60.041s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  60.130s  |  60.130s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  60.193s  |  60.193s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  60.479s  |  60.479s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  60.081s  |  60.081s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |  60.329s  |  60.329s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |  60.045s  |  60.045s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |  60.597s  |  60.597s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |  60.277s  |  60.277s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |  60.197s  |  60.197s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |  60.146s  |  60.146s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |  60.403s  |  60.403s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |  60.021s  |  60.021s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |  60.118s  |  60.118s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |  60.244s  |  60.244s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |  60.287s  |  60.287s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |  60.021s  |  60.021s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |   6.575s  |   6.575s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |  60.029s  |  60.029s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |  60.182s  |  60.182s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |  60.370s  |  60.370s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |  60.174s  |  60.174s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |  60.384s  |  60.384s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |  60.163s  |  60.163s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |  60.032s  |  60.032s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |  60.268s  |  60.268s  |   0.000s  | 0.0%|
</details>
