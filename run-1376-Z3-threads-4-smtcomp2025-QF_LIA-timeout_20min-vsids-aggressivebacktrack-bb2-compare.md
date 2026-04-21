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
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-vsids-aggressivebacktrack-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 8e294820a0bcdbe59f6282f7a0a3f73f594bd601
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: backtrack more aggressively in search tree: close matching external targets (i.e. repeat literals on other branches)

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-vsids-aggressivebacktrack-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 8e294820a0bcdbe59f6282f7a0a3f73f594bd601
Z3 branch: backbones
Z3 options: "-T:1260 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: backtrack more aggressively in search tree: close matching external targets (i.e. repeat literals on other branches)

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.380s  |1262.380s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.046s  |1260.046s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.851s  |1260.851s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.515s  |1261.515s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.267s  |1262.267s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.889s  |1261.889s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 116.532s  | 116.532s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.635s  |1260.635s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.526s  |1263.526s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 505.296s  | 505.296s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 677.504s  | 677.504s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.461s  |1260.461s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.506s  |1260.506s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.376s  |1260.376s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.473s  |1260.473s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.058s  |1260.058s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.609s  |1261.609s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 308.644s  | 308.644s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1260.538s  |1260.538s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.154s  |1261.154s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.380s  |1262.380s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.046s  |1260.046s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.851s  |1260.851s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.515s  |1261.515s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.267s  |1262.267s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.889s  |1261.889s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 116.532s  | 116.532s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.635s  |1260.635s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.526s  |1263.526s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 505.296s  | 505.296s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 677.504s  | 677.504s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.461s  |1260.461s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.506s  |1260.506s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.376s  |1260.376s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.473s  |1260.473s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.058s  |1260.058s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.609s  |1261.609s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 308.644s  | 308.644s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1260.538s  |1260.538s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.154s  |1261.154s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.380s  |1262.380s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.046s  |1260.046s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.851s  |1260.851s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.515s  |1261.515s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.267s  |1262.267s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.889s  |1261.889s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 116.532s  | 116.532s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.635s  |1260.635s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.526s  |1263.526s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 505.296s  | 505.296s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 677.504s  | 677.504s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.461s  |1260.461s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.506s  |1260.506s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.376s  |1260.376s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.473s  |1260.473s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.058s  |1260.058s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.609s  |1261.609s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 308.644s  | 308.644s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1260.538s  |1260.538s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.154s  |1261.154s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.380s  |1262.380s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.046s  |1260.046s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.851s  |1260.851s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.515s  |1261.515s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.267s  |1262.267s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.889s  |1261.889s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 116.532s  | 116.532s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.635s  |1260.635s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.526s  |1263.526s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 505.296s  | 505.296s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 677.504s  | 677.504s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.461s  |1260.461s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.506s  |1260.506s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.376s  |1260.376s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.473s  |1260.473s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.058s  |1260.058s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.609s  |1261.609s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 308.644s  | 308.644s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1260.538s  |1260.538s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.154s  |1261.154s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled12042.smt2                                                                        |1263.526s |31.615GiB|
|scrambled94658.smt2                                                                        |1262.899s |32.313GiB|
|scrambled4299.smt2                                                                         |1262.697s |27.439GiB|
|scrambled55680.smt2                                                                        |1262.487s |26.432GiB|
|scrambled102166.smt2                                                                       |1262.380s |24.742GiB|
|scrambled4198.smt2                                                                         |1262.362s |25.723GiB|
|scrambled68944.smt2                                                                        |1262.347s |25.149GiB|
|scrambled108840.smt2                                                                       |1262.267s |23.36GiB|
|scrambled79760.smt2                                                                        |1262.038s |23.011GiB|
|scrambled111627.smt2                                                                       |1261.889s |19.996GiB|
|scrambled75189.smt2                                                                        |1261.802s |17.942GiB|
|scrambled43577.smt2                                                                        |1261.618s |16.17GiB|
|scrambled19335.smt2                                                                        |1261.609s |16.465GiB|
|scrambled107826.smt2                                                                       |1261.515s |15.255GiB|
|scrambled27843.smt2                                                                        |1261.154s |11.597GiB|
|scrambled40621.smt2                                                                        |1260.958s |7086.0MiB|
|scrambled107115.smt2                                                                       |1260.851s |9046.0MiB|
|scrambled61922.smt2                                                                        |1260.668s |5772.0MiB|
|scrambled119331.smt2                                                                       |1260.635s |5899.0MiB|
|scrambled25238.smt2                                                                        |1260.538s |4459.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled12042.smt2                                                                        |1263.526s |31.615GiB|
|scrambled94658.smt2                                                                        |1262.899s |32.313GiB|
|scrambled4299.smt2                                                                         |1262.697s |27.439GiB|
|scrambled55680.smt2                                                                        |1262.487s |26.432GiB|
|scrambled102166.smt2                                                                       |1262.380s |24.742GiB|
|scrambled4198.smt2                                                                         |1262.362s |25.723GiB|
|scrambled68944.smt2                                                                        |1262.347s |25.149GiB|
|scrambled108840.smt2                                                                       |1262.267s |23.36GiB|
|scrambled79760.smt2                                                                        |1262.038s |23.011GiB|
|scrambled111627.smt2                                                                       |1261.889s |19.996GiB|
|scrambled75189.smt2                                                                        |1261.802s |17.942GiB|
|scrambled43577.smt2                                                                        |1261.618s |16.17GiB|
|scrambled19335.smt2                                                                        |1261.609s |16.465GiB|
|scrambled107826.smt2                                                                       |1261.515s |15.255GiB|
|scrambled27843.smt2                                                                        |1261.154s |11.597GiB|
|scrambled40621.smt2                                                                        |1260.958s |7086.0MiB|
|scrambled107115.smt2                                                                       |1260.851s |9046.0MiB|
|scrambled61922.smt2                                                                        |1260.668s |5772.0MiB|
|scrambled119331.smt2                                                                       |1260.635s |5899.0MiB|
|scrambled25238.smt2                                                                        |1260.538s |4459.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.742GiB|24.742GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9046.0MiB|9046.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |15.255GiB|15.255GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |23.36GiB|23.36GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |19.996GiB|19.996GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |552.0MiB|552.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5899.0MiB|5899.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |31.615GiB|31.615GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |605.0MiB|605.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1000.0MiB|1000.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3859.0MiB|3859.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |3058.0MiB|3058.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3106.0MiB|3106.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3836.0MiB|3836.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |218.0MiB|218.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.465GiB|16.465GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1027.0MiB|1027.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4459.0MiB|4459.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.597GiB|11.597GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.742GiB|24.742GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9046.0MiB|9046.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |15.255GiB|15.255GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |23.36GiB|23.36GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |19.996GiB|19.996GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |552.0MiB|552.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5899.0MiB|5899.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |31.615GiB|31.615GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |605.0MiB|605.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1000.0MiB|1000.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3859.0MiB|3859.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |3058.0MiB|3058.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3106.0MiB|3106.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3836.0MiB|3836.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |218.0MiB|218.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.465GiB|16.465GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1027.0MiB|1027.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4459.0MiB|4459.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.597GiB|11.597GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.742GiB|24.742GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9046.0MiB|9046.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |15.255GiB|15.255GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |23.36GiB|23.36GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |19.996GiB|19.996GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |552.0MiB|552.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5899.0MiB|5899.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |31.615GiB|31.615GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |605.0MiB|605.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1000.0MiB|1000.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3859.0MiB|3859.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |3058.0MiB|3058.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3106.0MiB|3106.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3836.0MiB|3836.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |218.0MiB|218.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.465GiB|16.465GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1027.0MiB|1027.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4459.0MiB|4459.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.597GiB|11.597GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.742GiB|24.742GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.556MiB|42.556MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9046.0MiB|9046.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |15.255GiB|15.255GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |23.36GiB|23.36GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |19.996GiB|19.996GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |552.0MiB|552.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5899.0MiB|5899.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |31.615GiB|31.615GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |605.0MiB|605.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1000.0MiB|1000.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3859.0MiB|3859.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |3058.0MiB|3058.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3106.0MiB|3106.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3836.0MiB|3836.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |218.0MiB|218.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.465GiB|16.465GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1027.0MiB|1027.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4459.0MiB|4459.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.597GiB|11.597GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1262.899s |32.313GiB|
|scrambled12042.smt2                                                                        |1263.526s |31.615GiB|
|scrambled4299.smt2                                                                         |1262.697s |27.439GiB|
|scrambled55680.smt2                                                                        |1262.487s |26.432GiB|
|scrambled4198.smt2                                                                         |1262.362s |25.723GiB|
|scrambled68944.smt2                                                                        |1262.347s |25.149GiB|
|scrambled102166.smt2                                                                       |1262.380s |24.742GiB|
|scrambled108840.smt2                                                                       |1262.267s |23.36GiB|
|scrambled79760.smt2                                                                        |1262.038s |23.011GiB|
|scrambled111627.smt2                                                                       |1261.889s |19.996GiB|
|scrambled75189.smt2                                                                        |1261.802s |17.942GiB|
|scrambled19335.smt2                                                                        |1261.609s |16.465GiB|
|scrambled43577.smt2                                                                        |1261.618s |16.17GiB|
|scrambled107826.smt2                                                                       |1261.515s |15.255GiB|
|scrambled27843.smt2                                                                        |1261.154s |11.597GiB|
|scrambled107115.smt2                                                                       |1260.851s |9046.0MiB|
|scrambled40621.smt2                                                                        |1260.958s |7086.0MiB|
|scrambled119331.smt2                                                                       |1260.635s |5899.0MiB|
|scrambled61922.smt2                                                                        |1260.668s |5772.0MiB|
|scrambled25238.smt2                                                                        |1260.538s |4459.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1262.899s |32.313GiB|
|scrambled12042.smt2                                                                        |1263.526s |31.615GiB|
|scrambled4299.smt2                                                                         |1262.697s |27.439GiB|
|scrambled55680.smt2                                                                        |1262.487s |26.432GiB|
|scrambled4198.smt2                                                                         |1262.362s |25.723GiB|
|scrambled68944.smt2                                                                        |1262.347s |25.149GiB|
|scrambled102166.smt2                                                                       |1262.380s |24.742GiB|
|scrambled108840.smt2                                                                       |1262.267s |23.36GiB|
|scrambled79760.smt2                                                                        |1262.038s |23.011GiB|
|scrambled111627.smt2                                                                       |1261.889s |19.996GiB|
|scrambled75189.smt2                                                                        |1261.802s |17.942GiB|
|scrambled19335.smt2                                                                        |1261.609s |16.465GiB|
|scrambled43577.smt2                                                                        |1261.618s |16.17GiB|
|scrambled107826.smt2                                                                       |1261.515s |15.255GiB|
|scrambled27843.smt2                                                                        |1261.154s |11.597GiB|
|scrambled107115.smt2                                                                       |1260.851s |9046.0MiB|
|scrambled40621.smt2                                                                        |1260.958s |7086.0MiB|
|scrambled119331.smt2                                                                       |1260.635s |5899.0MiB|
|scrambled61922.smt2                                                                        |1260.668s |5772.0MiB|
|scrambled25238.smt2                                                                        |1260.538s |4459.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.380s  |1262.380s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.046s  |1260.046s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.851s  |1260.851s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.515s  |1261.515s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.267s  |1262.267s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1261.889s  |1261.889s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 116.532s  | 116.532s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.635s  |1260.635s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1263.526s  |1263.526s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 505.296s  | 505.296s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 677.504s  | 677.504s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.461s  |1260.461s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.506s  |1260.506s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.376s  |1260.376s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.473s  |1260.473s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.058s  |1260.058s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.609s  |1261.609s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 308.644s  | 308.644s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1260.538s  |1260.538s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.154s  |1261.154s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 986.459s  | 986.459s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1260.026s  |1260.026s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1260.044s  |1260.044s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1260.958s  |1260.958s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1262.362s  |1262.362s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1262.697s  |1262.697s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1261.618s  |1261.618s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1260.370s  |1260.370s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1260.016s  |1260.016s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1260.286s  |1260.286s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1262.487s  |1262.487s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1260.399s  |1260.399s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1260.023s  |1260.023s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1260.668s  |1260.668s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1260.034s  |1260.034s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1262.347s  |1262.347s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1260.420s  |1260.420s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1261.802s  |1261.802s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1260.469s  |1260.469s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1262.038s  |1262.038s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1260.018s  |1260.018s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1260.032s  |1260.032s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1262.899s  |1262.899s  |   0.000s  | 0.0%|
</details>
