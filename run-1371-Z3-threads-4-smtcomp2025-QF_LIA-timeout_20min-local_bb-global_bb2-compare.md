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
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-local_bb-global_bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 221b4f8f5e042d1c9e27a0c93a866e096588830a
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.local_backbones=true smt_parallel.num_global_bb_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: re-ablate restore local bb phase/activity after search, due to positive experimental signal on smt comp LIA

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-local_bb-global_bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 221b4f8f5e042d1c9e27a0c93a866e096588830a
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.local_backbones=true smt_parallel.num_global_bb_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: re-ablate restore local bb phase/activity after search, due to positive experimental signal on smt comp LIA

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.389s  |1262.389s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.838s  |1260.838s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.480s  |1261.480s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.757s  |1262.757s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.943s  |1261.943s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1231.432s  |1231.432s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.643s  |1260.643s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.977s  |1262.977s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 242.973s  | 242.973s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1007.291s  |1007.291s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.534s  |1260.534s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.428s  |1260.428s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.395s  |1260.395s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.494s  |1260.494s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.048s  |1260.048s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.576s  |1261.576s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1212.500s  |1212.500s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1233.037s  |1233.037s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.183s  |1261.183s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.389s  |1262.389s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.838s  |1260.838s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.480s  |1261.480s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.757s  |1262.757s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.943s  |1261.943s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1231.432s  |1231.432s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.643s  |1260.643s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.977s  |1262.977s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 242.973s  | 242.973s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1007.291s  |1007.291s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.534s  |1260.534s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.428s  |1260.428s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.395s  |1260.395s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.494s  |1260.494s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.048s  |1260.048s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.576s  |1261.576s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1212.500s  |1212.500s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1233.037s  |1233.037s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.183s  |1261.183s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.389s  |1262.389s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.838s  |1260.838s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.480s  |1261.480s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.757s  |1262.757s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.943s  |1261.943s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1231.432s  |1231.432s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.643s  |1260.643s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.977s  |1262.977s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 242.973s  | 242.973s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1007.291s  |1007.291s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.534s  |1260.534s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.428s  |1260.428s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.395s  |1260.395s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.494s  |1260.494s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.048s  |1260.048s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.576s  |1261.576s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1212.500s  |1212.500s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1233.037s  |1233.037s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.183s  |1261.183s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.389s  |1262.389s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.838s  |1260.838s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.480s  |1261.480s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.757s  |1262.757s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.943s  |1261.943s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1231.432s  |1231.432s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.643s  |1260.643s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.977s  |1262.977s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 242.973s  | 242.973s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1007.291s  |1007.291s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.534s  |1260.534s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.428s  |1260.428s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.395s  |1260.395s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.494s  |1260.494s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.048s  |1260.048s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.576s  |1261.576s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1212.500s  |1212.500s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1233.037s  |1233.037s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.183s  |1261.183s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.577s |32.143GiB|
|scrambled4198.smt2                                                                         |1263.253s |25.703GiB|
|scrambled12042.smt2                                                                        |1262.977s |31.659GiB|
|scrambled108840.smt2                                                                       |1262.757s |23.355GiB|
|scrambled4299.smt2                                                                         |1262.644s |27.404GiB|
|scrambled55680.smt2                                                                        |1262.490s |26.361GiB|
|scrambled68944.smt2                                                                        |1262.395s |24.765GiB|
|scrambled102166.smt2                                                                       |1262.389s |24.734GiB|
|scrambled79760.smt2                                                                        |1262.104s |22.829GiB|
|scrambled111627.smt2                                                                       |1261.943s |19.804GiB|
|scrambled75189.smt2                                                                        |1261.784s |17.95GiB|
|scrambled43577.smt2                                                                        |1261.592s |16.171GiB|
|scrambled19335.smt2                                                                        |1261.576s |16.454GiB|
|scrambled107826.smt2                                                                       |1261.480s |15.194GiB|
|scrambled27843.smt2                                                                        |1261.183s |11.562GiB|
|scrambled107115.smt2                                                                       |1260.838s |9055.0MiB|
|scrambled40621.smt2                                                                        |1260.678s |6462.0MiB|
|scrambled119331.smt2                                                                       |1260.643s |6229.0MiB|
|scrambled61922.smt2                                                                        |1260.615s |5774.0MiB|
|scrambled128128.smt2                                                                       |1260.534s |3776.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.577s |32.143GiB|
|scrambled4198.smt2                                                                         |1263.253s |25.703GiB|
|scrambled12042.smt2                                                                        |1262.977s |31.659GiB|
|scrambled108840.smt2                                                                       |1262.757s |23.355GiB|
|scrambled4299.smt2                                                                         |1262.644s |27.404GiB|
|scrambled55680.smt2                                                                        |1262.490s |26.361GiB|
|scrambled68944.smt2                                                                        |1262.395s |24.765GiB|
|scrambled102166.smt2                                                                       |1262.389s |24.734GiB|
|scrambled79760.smt2                                                                        |1262.104s |22.829GiB|
|scrambled111627.smt2                                                                       |1261.943s |19.804GiB|
|scrambled75189.smt2                                                                        |1261.784s |17.95GiB|
|scrambled43577.smt2                                                                        |1261.592s |16.171GiB|
|scrambled19335.smt2                                                                        |1261.576s |16.454GiB|
|scrambled107826.smt2                                                                       |1261.480s |15.194GiB|
|scrambled27843.smt2                                                                        |1261.183s |11.562GiB|
|scrambled107115.smt2                                                                       |1260.838s |9055.0MiB|
|scrambled40621.smt2                                                                        |1260.678s |6462.0MiB|
|scrambled119331.smt2                                                                       |1260.643s |6229.0MiB|
|scrambled61922.smt2                                                                        |1260.615s |5774.0MiB|
|scrambled128128.smt2                                                                       |1260.534s |3776.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.734GiB|24.734GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.56MiB|42.56MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9055.0MiB|9055.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |15.194GiB|15.194GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |23.355GiB|23.355GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |19.804GiB|19.804GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |610.0MiB|610.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |6229.0MiB|6229.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |31.659GiB|31.659GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |602.0MiB|602.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1011.0MiB|1011.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3776.0MiB|3776.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2979.0MiB|2979.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2984.0MiB|2984.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3853.0MiB|3853.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |220.0MiB|220.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.454GiB|16.454GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1059.0MiB|1059.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4471.0MiB|4471.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.562GiB|11.562GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.734GiB|24.734GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.56MiB|42.56MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9055.0MiB|9055.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |15.194GiB|15.194GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |23.355GiB|23.355GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |19.804GiB|19.804GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |610.0MiB|610.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |6229.0MiB|6229.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |31.659GiB|31.659GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |602.0MiB|602.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1011.0MiB|1011.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3776.0MiB|3776.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2979.0MiB|2979.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2984.0MiB|2984.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3853.0MiB|3853.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |220.0MiB|220.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.454GiB|16.454GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1059.0MiB|1059.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4471.0MiB|4471.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.562GiB|11.562GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.734GiB|24.734GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.56MiB|42.56MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9055.0MiB|9055.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |15.194GiB|15.194GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |23.355GiB|23.355GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |19.804GiB|19.804GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |610.0MiB|610.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |6229.0MiB|6229.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |31.659GiB|31.659GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |602.0MiB|602.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1011.0MiB|1011.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3776.0MiB|3776.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2979.0MiB|2979.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2984.0MiB|2984.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3853.0MiB|3853.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |220.0MiB|220.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.454GiB|16.454GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1059.0MiB|1059.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4471.0MiB|4471.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.562GiB|11.562GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.734GiB|24.734GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.56MiB|42.56MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9055.0MiB|9055.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |15.194GiB|15.194GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |23.355GiB|23.355GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |19.804GiB|19.804GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |610.0MiB|610.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |6229.0MiB|6229.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |31.659GiB|31.659GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |602.0MiB|602.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1011.0MiB|1011.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3776.0MiB|3776.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2979.0MiB|2979.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2984.0MiB|2984.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3853.0MiB|3853.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |220.0MiB|220.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.454GiB|16.454GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1059.0MiB|1059.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4471.0MiB|4471.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.562GiB|11.562GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.577s |32.143GiB|
|scrambled12042.smt2                                                                        |1262.977s |31.659GiB|
|scrambled4299.smt2                                                                         |1262.644s |27.404GiB|
|scrambled55680.smt2                                                                        |1262.490s |26.361GiB|
|scrambled4198.smt2                                                                         |1263.253s |25.703GiB|
|scrambled68944.smt2                                                                        |1262.395s |24.765GiB|
|scrambled102166.smt2                                                                       |1262.389s |24.734GiB|
|scrambled108840.smt2                                                                       |1262.757s |23.355GiB|
|scrambled79760.smt2                                                                        |1262.104s |22.829GiB|
|scrambled111627.smt2                                                                       |1261.943s |19.804GiB|
|scrambled75189.smt2                                                                        |1261.784s |17.95GiB|
|scrambled19335.smt2                                                                        |1261.576s |16.454GiB|
|scrambled43577.smt2                                                                        |1261.592s |16.171GiB|
|scrambled107826.smt2                                                                       |1261.480s |15.194GiB|
|scrambled27843.smt2                                                                        |1261.183s |11.562GiB|
|scrambled107115.smt2                                                                       |1260.838s |9055.0MiB|
|scrambled40621.smt2                                                                        |1260.678s |6462.0MiB|
|scrambled119331.smt2                                                                       |1260.643s |6229.0MiB|
|scrambled61922.smt2                                                                        |1260.615s |5774.0MiB|
|scrambled25238.smt2                                                                        |1233.037s |4471.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.577s |32.143GiB|
|scrambled12042.smt2                                                                        |1262.977s |31.659GiB|
|scrambled4299.smt2                                                                         |1262.644s |27.404GiB|
|scrambled55680.smt2                                                                        |1262.490s |26.361GiB|
|scrambled4198.smt2                                                                         |1263.253s |25.703GiB|
|scrambled68944.smt2                                                                        |1262.395s |24.765GiB|
|scrambled102166.smt2                                                                       |1262.389s |24.734GiB|
|scrambled108840.smt2                                                                       |1262.757s |23.355GiB|
|scrambled79760.smt2                                                                        |1262.104s |22.829GiB|
|scrambled111627.smt2                                                                       |1261.943s |19.804GiB|
|scrambled75189.smt2                                                                        |1261.784s |17.95GiB|
|scrambled19335.smt2                                                                        |1261.576s |16.454GiB|
|scrambled43577.smt2                                                                        |1261.592s |16.171GiB|
|scrambled107826.smt2                                                                       |1261.480s |15.194GiB|
|scrambled27843.smt2                                                                        |1261.183s |11.562GiB|
|scrambled107115.smt2                                                                       |1260.838s |9055.0MiB|
|scrambled40621.smt2                                                                        |1260.678s |6462.0MiB|
|scrambled119331.smt2                                                                       |1260.643s |6229.0MiB|
|scrambled61922.smt2                                                                        |1260.615s |5774.0MiB|
|scrambled25238.smt2                                                                        |1233.037s |4471.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.389s  |1262.389s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.838s  |1260.838s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.480s  |1261.480s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.757s  |1262.757s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.943s  |1261.943s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1231.432s  |1231.432s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.643s  |1260.643s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.977s  |1262.977s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 242.973s  | 242.973s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1007.291s  |1007.291s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.534s  |1260.534s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.428s  |1260.428s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.395s  |1260.395s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.494s  |1260.494s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.048s  |1260.048s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.576s  |1261.576s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1212.500s  |1212.500s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1233.037s  |1233.037s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.183s  |1261.183s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 764.084s  | 764.084s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1260.023s  |1260.023s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1260.061s  |1260.061s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1260.678s  |1260.678s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1263.253s  |1263.253s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1262.644s  |1262.644s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1261.592s  |1261.592s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1260.390s  |1260.390s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1260.023s  |1260.023s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1260.264s  |1260.264s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1262.490s  |1262.490s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1260.521s  |1260.521s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1260.015s  |1260.015s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1260.615s  |1260.615s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1260.024s  |1260.024s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1262.395s  |1262.395s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         | 761.564s  | 761.564s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1261.784s  |1261.784s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1260.484s  |1260.484s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1262.104s  |1262.104s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1260.021s  |1260.021s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1260.040s  |1260.040s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1263.577s  |1263.577s  |   0.000s  | 0.0%|
</details>
