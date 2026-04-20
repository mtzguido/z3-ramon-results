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
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min_bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6b8cb1099d311aac105cfc6fa658466f4ef6af67
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore unrelated code to master

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min_bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6b8cb1099d311aac105cfc6fa658466f4ef6af67
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore unrelated code to master

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.298s  |1262.298s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.869s  |1260.869s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.481s  |1261.481s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.058s  |1262.058s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.000s  |1262.000s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 126.307s  | 126.307s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.541s  |1260.541s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.930s  |1262.930s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 177.703s  | 177.703s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 156.428s  | 156.428s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.400s  |1260.400s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.427s  |1260.427s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.406s  |1260.406s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.765s  |1260.765s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.052s  |1260.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.916s  |1261.916s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  91.764s  |  91.764s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 619.836s  | 619.836s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.121s  |1261.121s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.298s  |1262.298s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.869s  |1260.869s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.481s  |1261.481s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.058s  |1262.058s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.000s  |1262.000s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 126.307s  | 126.307s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.541s  |1260.541s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.930s  |1262.930s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 177.703s  | 177.703s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 156.428s  | 156.428s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.400s  |1260.400s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.427s  |1260.427s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.406s  |1260.406s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.765s  |1260.765s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.052s  |1260.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.916s  |1261.916s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  91.764s  |  91.764s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 619.836s  | 619.836s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.121s  |1261.121s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.298s  |1262.298s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.869s  |1260.869s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.481s  |1261.481s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.058s  |1262.058s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.000s  |1262.000s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 126.307s  | 126.307s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.541s  |1260.541s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.930s  |1262.930s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 177.703s  | 177.703s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 156.428s  | 156.428s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.400s  |1260.400s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.427s  |1260.427s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.406s  |1260.406s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.765s  |1260.765s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.052s  |1260.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.916s  |1261.916s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  91.764s  |  91.764s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 619.836s  | 619.836s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.121s  |1261.121s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.298s  |1262.298s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.869s  |1260.869s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.481s  |1261.481s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.058s  |1262.058s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.000s  |1262.000s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 126.307s  | 126.307s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.541s  |1260.541s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.930s  |1262.930s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 177.703s  | 177.703s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 156.428s  | 156.428s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.400s  |1260.400s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.427s  |1260.427s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.406s  |1260.406s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.765s  |1260.765s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.052s  |1260.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.916s  |1261.916s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  91.764s  |  91.764s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 619.836s  | 619.836s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.121s  |1261.121s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled12042.smt2                                                                        |1262.930s |31.668GiB|
|scrambled94658.smt2                                                                        |1262.920s |32.394GiB|
|scrambled68944.smt2                                                                        |1262.591s |25.419GiB|
|scrambled55680.smt2                                                                        |1262.447s |26.41GiB|
|scrambled4299.smt2                                                                         |1262.409s |27.447GiB|
|scrambled4198.smt2                                                                         |1262.409s |25.78GiB|
|scrambled102166.smt2                                                                       |1262.298s |24.757GiB|
|scrambled79760.smt2                                                                        |1262.063s |23.362GiB|
|scrambled108840.smt2                                                                       |1262.058s |23.371GiB|
|scrambled111627.smt2                                                                       |1262.000s |20.001GiB|
|scrambled19335.smt2                                                                        |1261.916s |16.467GiB|
|scrambled75189.smt2                                                                        |1261.720s |17.943GiB|
|scrambled43577.smt2                                                                        |1261.575s |16.261GiB|
|scrambled107826.smt2                                                                       |1261.481s |15.252GiB|
|scrambled27843.smt2                                                                        |1261.121s |11.603GiB|
|scrambled107115.smt2                                                                       |1260.869s |9056.0MiB|
|scrambled131241.smt2                                                                       |1260.765s |3853.0MiB|
|scrambled40621.smt2                                                                        |1260.637s |6759.0MiB|
|scrambled61922.smt2                                                                        |1260.615s |5787.0MiB|
|scrambled119331.smt2                                                                       |1260.541s |5817.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled12042.smt2                                                                        |1262.930s |31.668GiB|
|scrambled94658.smt2                                                                        |1262.920s |32.394GiB|
|scrambled68944.smt2                                                                        |1262.591s |25.419GiB|
|scrambled55680.smt2                                                                        |1262.447s |26.41GiB|
|scrambled4299.smt2                                                                         |1262.409s |27.447GiB|
|scrambled4198.smt2                                                                         |1262.409s |25.78GiB|
|scrambled102166.smt2                                                                       |1262.298s |24.757GiB|
|scrambled79760.smt2                                                                        |1262.063s |23.362GiB|
|scrambled108840.smt2                                                                       |1262.058s |23.371GiB|
|scrambled111627.smt2                                                                       |1262.000s |20.001GiB|
|scrambled19335.smt2                                                                        |1261.916s |16.467GiB|
|scrambled75189.smt2                                                                        |1261.720s |17.943GiB|
|scrambled43577.smt2                                                                        |1261.575s |16.261GiB|
|scrambled107826.smt2                                                                       |1261.481s |15.252GiB|
|scrambled27843.smt2                                                                        |1261.121s |11.603GiB|
|scrambled107115.smt2                                                                       |1260.869s |9056.0MiB|
|scrambled131241.smt2                                                                       |1260.765s |3853.0MiB|
|scrambled40621.smt2                                                                        |1260.637s |6759.0MiB|
|scrambled61922.smt2                                                                        |1260.615s |5787.0MiB|
|scrambled119331.smt2                                                                       |1260.541s |5817.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.757GiB|24.757GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.336MiB|42.336MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9056.0MiB|9056.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |15.252GiB|15.252GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |23.371GiB|23.371GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |20.001GiB|20.001GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5817.0MiB|5817.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |31.668GiB|31.668GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |598.0MiB|598.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |963.0MiB|963.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3901.0MiB|3901.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2985.0MiB|2985.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3129.0MiB|3129.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3853.0MiB|3853.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |223.0MiB|223.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.467GiB|16.467GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |955.0MiB|955.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4260.0MiB|4260.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.603GiB|11.603GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.757GiB|24.757GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.336MiB|42.336MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9056.0MiB|9056.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |15.252GiB|15.252GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |23.371GiB|23.371GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |20.001GiB|20.001GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5817.0MiB|5817.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |31.668GiB|31.668GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |598.0MiB|598.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |963.0MiB|963.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3901.0MiB|3901.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2985.0MiB|2985.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3129.0MiB|3129.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3853.0MiB|3853.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |223.0MiB|223.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.467GiB|16.467GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |955.0MiB|955.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4260.0MiB|4260.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.603GiB|11.603GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.757GiB|24.757GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.336MiB|42.336MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9056.0MiB|9056.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |15.252GiB|15.252GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |23.371GiB|23.371GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |20.001GiB|20.001GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5817.0MiB|5817.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |31.668GiB|31.668GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |598.0MiB|598.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |963.0MiB|963.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3901.0MiB|3901.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2985.0MiB|2985.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3129.0MiB|3129.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3853.0MiB|3853.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |223.0MiB|223.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.467GiB|16.467GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |955.0MiB|955.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4260.0MiB|4260.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.603GiB|11.603GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.757GiB|24.757GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.336MiB|42.336MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9056.0MiB|9056.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |15.252GiB|15.252GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |23.371GiB|23.371GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |20.001GiB|20.001GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5817.0MiB|5817.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |31.668GiB|31.668GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |598.0MiB|598.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |963.0MiB|963.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3901.0MiB|3901.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2985.0MiB|2985.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3129.0MiB|3129.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3853.0MiB|3853.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |223.0MiB|223.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.467GiB|16.467GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |955.0MiB|955.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4260.0MiB|4260.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.603GiB|11.603GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1262.920s |32.394GiB|
|scrambled12042.smt2                                                                        |1262.930s |31.668GiB|
|scrambled4299.smt2                                                                         |1262.409s |27.447GiB|
|scrambled55680.smt2                                                                        |1262.447s |26.41GiB|
|scrambled4198.smt2                                                                         |1262.409s |25.78GiB|
|scrambled68944.smt2                                                                        |1262.591s |25.419GiB|
|scrambled102166.smt2                                                                       |1262.298s |24.757GiB|
|scrambled108840.smt2                                                                       |1262.058s |23.371GiB|
|scrambled79760.smt2                                                                        |1262.063s |23.362GiB|
|scrambled111627.smt2                                                                       |1262.000s |20.001GiB|
|scrambled75189.smt2                                                                        |1261.720s |17.943GiB|
|scrambled19335.smt2                                                                        |1261.916s |16.467GiB|
|scrambled43577.smt2                                                                        |1261.575s |16.261GiB|
|scrambled107826.smt2                                                                       |1261.481s |15.252GiB|
|scrambled27843.smt2                                                                        |1261.121s |11.603GiB|
|scrambled107115.smt2                                                                       |1260.869s |9056.0MiB|
|scrambled40621.smt2                                                                        |1260.637s |6759.0MiB|
|scrambled119331.smt2                                                                       |1260.541s |5817.0MiB|
|scrambled61922.smt2                                                                        |1260.615s |5787.0MiB|
|scrambled25238.smt2                                                                        | 619.836s |4260.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1262.920s |32.394GiB|
|scrambled12042.smt2                                                                        |1262.930s |31.668GiB|
|scrambled4299.smt2                                                                         |1262.409s |27.447GiB|
|scrambled55680.smt2                                                                        |1262.447s |26.41GiB|
|scrambled4198.smt2                                                                         |1262.409s |25.78GiB|
|scrambled68944.smt2                                                                        |1262.591s |25.419GiB|
|scrambled102166.smt2                                                                       |1262.298s |24.757GiB|
|scrambled108840.smt2                                                                       |1262.058s |23.371GiB|
|scrambled79760.smt2                                                                        |1262.063s |23.362GiB|
|scrambled111627.smt2                                                                       |1262.000s |20.001GiB|
|scrambled75189.smt2                                                                        |1261.720s |17.943GiB|
|scrambled19335.smt2                                                                        |1261.916s |16.467GiB|
|scrambled43577.smt2                                                                        |1261.575s |16.261GiB|
|scrambled107826.smt2                                                                       |1261.481s |15.252GiB|
|scrambled27843.smt2                                                                        |1261.121s |11.603GiB|
|scrambled107115.smt2                                                                       |1260.869s |9056.0MiB|
|scrambled40621.smt2                                                                        |1260.637s |6759.0MiB|
|scrambled119331.smt2                                                                       |1260.541s |5817.0MiB|
|scrambled61922.smt2                                                                        |1260.615s |5787.0MiB|
|scrambled25238.smt2                                                                        | 619.836s |4260.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.298s  |1262.298s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.869s  |1260.869s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.481s  |1261.481s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.058s  |1262.058s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.000s  |1262.000s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 126.307s  | 126.307s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.541s  |1260.541s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.930s  |1262.930s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 177.703s  | 177.703s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 156.428s  | 156.428s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.400s  |1260.400s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.427s  |1260.427s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.406s  |1260.406s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.765s  |1260.765s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.052s  |1260.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.916s  |1261.916s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  91.764s  |  91.764s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 619.836s  | 619.836s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.121s  |1261.121s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 541.981s  | 541.981s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1260.021s  |1260.021s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1260.061s  |1260.061s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1260.637s  |1260.637s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1262.409s  |1262.409s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1262.409s  |1262.409s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1261.575s  |1261.575s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1260.445s  |1260.445s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1260.027s  |1260.027s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1260.186s  |1260.186s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1262.447s  |1262.447s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1260.341s  |1260.341s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1260.025s  |1260.025s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1260.615s  |1260.615s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1260.031s  |1260.031s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1262.591s  |1262.591s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1186.352s  |1186.352s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1261.720s  |1261.720s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1260.496s  |1260.496s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1262.063s  |1262.063s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1260.021s  |1260.021s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1260.032s  |1260.032s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1262.920s  |1262.920s  |   0.000s  | 0.0%|
</details>
