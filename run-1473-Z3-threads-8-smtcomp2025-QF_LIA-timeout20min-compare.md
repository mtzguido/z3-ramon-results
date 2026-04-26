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
Z3 options: "-T:1200 -v:0 smt.threads=8"
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
Z3 options: "-T:1200 -v:0 smt.threads=8"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: reinstate FL check for new batch with epochs, before merge, this is a temp branch

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.283s  |1200.283s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.111s  |1200.111s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  46.222s  |  46.222s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.166s  |1200.166s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.685s  |1200.685s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.347s  |1200.347s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 315.610s  | 315.610s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 124.360s  | 124.360s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.597s  |1200.597s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.472s  |1200.472s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.590s  |1200.590s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.577s  |1200.577s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.167s  |1200.167s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1077.291s  |1077.291s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 949.618s  | 949.618s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.283s  |1200.283s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.111s  |1200.111s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  46.222s  |  46.222s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.166s  |1200.166s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.685s  |1200.685s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.347s  |1200.347s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 315.610s  | 315.610s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 124.360s  | 124.360s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.597s  |1200.597s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.472s  |1200.472s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.590s  |1200.590s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.577s  |1200.577s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.167s  |1200.167s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1077.291s  |1077.291s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 949.618s  | 949.618s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.283s  |1200.283s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.111s  |1200.111s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  46.222s  |  46.222s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.166s  |1200.166s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.685s  |1200.685s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.347s  |1200.347s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 315.610s  | 315.610s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 124.360s  | 124.360s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.597s  |1200.597s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.472s  |1200.472s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.590s  |1200.590s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.577s  |1200.577s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.167s  |1200.167s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1077.291s  |1077.291s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 949.618s  | 949.618s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.283s  |1200.283s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.111s  |1200.111s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  46.222s  |  46.222s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.166s  |1200.166s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.685s  |1200.685s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.347s  |1200.347s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 315.610s  | 315.610s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 124.360s  | 124.360s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.597s  |1200.597s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.472s  |1200.472s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.590s  |1200.590s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.577s  |1200.577s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.167s  |1200.167s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1077.291s  |1077.291s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 949.618s  | 949.618s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled7741.smt2                                                                         |1200.929s |5385.0MiB|
|scrambled40621.smt2                                                                        |1200.910s |6434.0MiB|
|scrambled119331.smt2                                                                       |1200.685s |5734.0MiB|
|scrambled128128.smt2                                                                       |1200.597s |5064.0MiB|
|scrambled128874.smt2                                                                       |1200.590s |4241.0MiB|
|scrambled131241.smt2                                                                       |1200.577s |4848.0MiB|
|scrambled44911.smt2                                                                        |1200.520s |3676.0MiB|
|scrambled128732.smt2                                                                       |1200.472s |4052.0MiB|
|scrambled55777.smt2                                                                        |1200.452s |3231.0MiB|
|scrambled95803.smt2                                                                        |1200.386s |2075.0MiB|
|scrambled32836.smt2                                                                        |1200.377s |2329.0MiB|
|scrambled4198.smt2                                                                         |1200.375s |2555.0MiB|
|scrambled12042.smt2                                                                        |1200.347s |2587.0MiB|
|scrambled4299.smt2                                                                         |1200.329s |2033.0MiB|
|scrambled94658.smt2                                                                        |1200.283s |2755.0MiB|
|scrambled102166.smt2                                                                       |1200.283s |2800.0MiB|
|scrambled55680.smt2                                                                        |1200.267s |2501.0MiB|
|scrambled68944.smt2                                                                        |1200.253s |1769.0MiB|
|scrambled79760.smt2                                                                        |1200.233s |1688.0MiB|
|scrambled43577.smt2                                                                        |1200.225s |1420.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled7741.smt2                                                                         |1200.929s |5385.0MiB|
|scrambled40621.smt2                                                                        |1200.910s |6434.0MiB|
|scrambled119331.smt2                                                                       |1200.685s |5734.0MiB|
|scrambled128128.smt2                                                                       |1200.597s |5064.0MiB|
|scrambled128874.smt2                                                                       |1200.590s |4241.0MiB|
|scrambled131241.smt2                                                                       |1200.577s |4848.0MiB|
|scrambled44911.smt2                                                                        |1200.520s |3676.0MiB|
|scrambled128732.smt2                                                                       |1200.472s |4052.0MiB|
|scrambled55777.smt2                                                                        |1200.452s |3231.0MiB|
|scrambled95803.smt2                                                                        |1200.386s |2075.0MiB|
|scrambled32836.smt2                                                                        |1200.377s |2329.0MiB|
|scrambled4198.smt2                                                                         |1200.375s |2555.0MiB|
|scrambled12042.smt2                                                                        |1200.347s |2587.0MiB|
|scrambled4299.smt2                                                                         |1200.329s |2033.0MiB|
|scrambled94658.smt2                                                                        |1200.283s |2755.0MiB|
|scrambled102166.smt2                                                                       |1200.283s |2800.0MiB|
|scrambled55680.smt2                                                                        |1200.267s |2501.0MiB|
|scrambled68944.smt2                                                                        |1200.253s |1769.0MiB|
|scrambled79760.smt2                                                                        |1200.233s |1688.0MiB|
|scrambled43577.smt2                                                                        |1200.225s |1420.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2800.0MiB|2800.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.064MiB|43.064MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |601.0MiB|601.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1132.0MiB|1132.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1473.0MiB|1473.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1210.0MiB|1210.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |888.0MiB|888.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5734.0MiB|5734.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2587.0MiB|2587.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |932.0MiB|932.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1339.0MiB|1339.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |5064.0MiB|5064.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4052.0MiB|4052.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4241.0MiB|4241.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |4848.0MiB|4848.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |259.0MiB|259.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1198.0MiB|1198.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1565.0MiB|1565.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5973.0MiB|5973.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |641.0MiB|641.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2800.0MiB|2800.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.064MiB|43.064MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |601.0MiB|601.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1132.0MiB|1132.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1473.0MiB|1473.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1210.0MiB|1210.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |888.0MiB|888.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5734.0MiB|5734.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2587.0MiB|2587.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |932.0MiB|932.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1339.0MiB|1339.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |5064.0MiB|5064.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4052.0MiB|4052.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4241.0MiB|4241.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |4848.0MiB|4848.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |259.0MiB|259.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1198.0MiB|1198.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1565.0MiB|1565.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5973.0MiB|5973.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |641.0MiB|641.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2800.0MiB|2800.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.064MiB|43.064MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |601.0MiB|601.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1132.0MiB|1132.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1473.0MiB|1473.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1210.0MiB|1210.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |888.0MiB|888.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5734.0MiB|5734.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2587.0MiB|2587.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |932.0MiB|932.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1339.0MiB|1339.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |5064.0MiB|5064.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4052.0MiB|4052.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4241.0MiB|4241.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |4848.0MiB|4848.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |259.0MiB|259.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1198.0MiB|1198.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1565.0MiB|1565.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5973.0MiB|5973.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |641.0MiB|641.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2800.0MiB|2800.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.064MiB|43.064MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |601.0MiB|601.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1132.0MiB|1132.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1473.0MiB|1473.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1210.0MiB|1210.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |888.0MiB|888.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5734.0MiB|5734.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2587.0MiB|2587.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |932.0MiB|932.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1339.0MiB|1339.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |5064.0MiB|5064.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4052.0MiB|4052.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4241.0MiB|4241.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |4848.0MiB|4848.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |259.0MiB|259.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1198.0MiB|1198.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1565.0MiB|1565.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5973.0MiB|5973.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |641.0MiB|641.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled40621.smt2                                                                        |1200.910s |6434.0MiB|
|scrambled25238.smt2                                                                        | 949.618s |5973.0MiB|
|scrambled119331.smt2                                                                       |1200.685s |5734.0MiB|
|scrambled7741.smt2                                                                         |1200.929s |5385.0MiB|
|scrambled128128.smt2                                                                       |1200.597s |5064.0MiB|
|scrambled131241.smt2                                                                       |1200.577s |4848.0MiB|
|scrambled128874.smt2                                                                       |1200.590s |4241.0MiB|
|scrambled128732.smt2                                                                       |1200.472s |4052.0MiB|
|scrambled72668.smt2                                                                        | 248.365s |3748.0MiB|
|scrambled44911.smt2                                                                        |1200.520s |3676.0MiB|
|scrambled55777.smt2                                                                        |1200.452s |3231.0MiB|
|scrambled102166.smt2                                                                       |1200.283s |2800.0MiB|
|scrambled94658.smt2                                                                        |1200.283s |2755.0MiB|
|scrambled12042.smt2                                                                        |1200.347s |2587.0MiB|
|scrambled4198.smt2                                                                         |1200.375s |2555.0MiB|
|scrambled55680.smt2                                                                        |1200.267s |2501.0MiB|
|scrambled32836.smt2                                                                        |1200.377s |2329.0MiB|
|scrambled95803.smt2                                                                        |1200.386s |2075.0MiB|
|scrambled4299.smt2                                                                         |1200.329s |2033.0MiB|
|scrambled68944.smt2                                                                        |1200.253s |1769.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled40621.smt2                                                                        |1200.910s |6434.0MiB|
|scrambled25238.smt2                                                                        | 949.618s |5973.0MiB|
|scrambled119331.smt2                                                                       |1200.685s |5734.0MiB|
|scrambled7741.smt2                                                                         |1200.929s |5385.0MiB|
|scrambled128128.smt2                                                                       |1200.597s |5064.0MiB|
|scrambled131241.smt2                                                                       |1200.577s |4848.0MiB|
|scrambled128874.smt2                                                                       |1200.590s |4241.0MiB|
|scrambled128732.smt2                                                                       |1200.472s |4052.0MiB|
|scrambled72668.smt2                                                                        | 248.365s |3748.0MiB|
|scrambled44911.smt2                                                                        |1200.520s |3676.0MiB|
|scrambled55777.smt2                                                                        |1200.452s |3231.0MiB|
|scrambled102166.smt2                                                                       |1200.283s |2800.0MiB|
|scrambled94658.smt2                                                                        |1200.283s |2755.0MiB|
|scrambled12042.smt2                                                                        |1200.347s |2587.0MiB|
|scrambled4198.smt2                                                                         |1200.375s |2555.0MiB|
|scrambled55680.smt2                                                                        |1200.267s |2501.0MiB|
|scrambled32836.smt2                                                                        |1200.377s |2329.0MiB|
|scrambled95803.smt2                                                                        |1200.386s |2075.0MiB|
|scrambled4299.smt2                                                                         |1200.329s |2033.0MiB|
|scrambled68944.smt2                                                                        |1200.253s |1769.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.283s  |1200.283s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.111s  |1200.111s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  46.222s  |  46.222s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.166s  |1200.166s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.685s  |1200.685s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.347s  |1200.347s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 315.610s  | 315.610s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 124.360s  | 124.360s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.597s  |1200.597s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.472s  |1200.472s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.590s  |1200.590s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.577s  |1200.577s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.167s  |1200.167s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1077.291s  |1077.291s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 949.618s  | 949.618s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.377s  |1200.377s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1200.910s  |1200.910s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1200.375s  |1200.375s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1200.329s  |1200.329s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1200.225s  |1200.225s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.520s  |1200.520s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.024s  |1200.024s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         | 183.004s  | 183.004s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1200.267s  |1200.267s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.452s  |1200.452s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |   7.040s  |   7.040s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1200.253s  |1200.253s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         | 248.365s  | 248.365s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.929s  |1200.929s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1200.233s  |1200.233s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1200.283s  |1200.283s  |   0.000s  | 0.0%|
</details>
