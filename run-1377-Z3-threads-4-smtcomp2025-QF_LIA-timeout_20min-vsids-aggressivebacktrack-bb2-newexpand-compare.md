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
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-vsids-aggressivebacktrack-bb2-newexpand
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
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-vsids-aggressivebacktrack-bb2-newexpand
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
|scrambled102166.smt2                                                                        |1262.323s  |1262.323s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.051s  |1260.051s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.858s  |1260.858s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.442s  |1261.442s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.184s  |1262.184s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.098s  |1262.098s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 122.821s  | 122.821s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.549s  |1260.549s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.956s  |1262.956s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 476.205s  | 476.205s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 168.393s  | 168.393s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.484s  |1260.484s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.392s  |1260.392s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.488s  |1260.488s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.499s  |1260.499s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.052s  |1260.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.651s  |1261.651s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  68.601s  |  68.601s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1118.957s  |1118.957s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.232s  |1261.232s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.323s  |1262.323s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.051s  |1260.051s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.858s  |1260.858s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.442s  |1261.442s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.184s  |1262.184s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.098s  |1262.098s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 122.821s  | 122.821s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.549s  |1260.549s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.956s  |1262.956s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 476.205s  | 476.205s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 168.393s  | 168.393s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.484s  |1260.484s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.392s  |1260.392s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.488s  |1260.488s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.499s  |1260.499s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.052s  |1260.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.651s  |1261.651s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  68.601s  |  68.601s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1118.957s  |1118.957s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.232s  |1261.232s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.323s  |1262.323s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.051s  |1260.051s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.858s  |1260.858s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.442s  |1261.442s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.184s  |1262.184s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.098s  |1262.098s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 122.821s  | 122.821s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.549s  |1260.549s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.956s  |1262.956s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 476.205s  | 476.205s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 168.393s  | 168.393s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.484s  |1260.484s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.392s  |1260.392s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.488s  |1260.488s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.499s  |1260.499s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.052s  |1260.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.651s  |1261.651s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  68.601s  |  68.601s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1118.957s  |1118.957s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.232s  |1261.232s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.323s  |1262.323s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.051s  |1260.051s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.858s  |1260.858s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.442s  |1261.442s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.184s  |1262.184s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.098s  |1262.098s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 122.821s  | 122.821s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.549s  |1260.549s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.956s  |1262.956s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 476.205s  | 476.205s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 168.393s  | 168.393s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.484s  |1260.484s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.392s  |1260.392s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.488s  |1260.488s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.499s  |1260.499s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.052s  |1260.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.651s  |1261.651s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  68.601s  |  68.601s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1118.957s  |1118.957s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.232s  |1261.232s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.880s |32.378GiB|
|scrambled12042.smt2                                                                        |1262.956s |31.652GiB|
|scrambled79760.smt2                                                                        |1262.665s |22.863GiB|
|scrambled4299.smt2                                                                         |1262.512s |27.482GiB|
|scrambled55680.smt2                                                                        |1262.493s |26.361GiB|
|scrambled68944.smt2                                                                        |1262.378s |25.297GiB|
|scrambled4198.smt2                                                                         |1262.375s |25.752GiB|
|scrambled102166.smt2                                                                       |1262.323s |24.727GiB|
|scrambled108840.smt2                                                                       |1262.184s |23.383GiB|
|scrambled111627.smt2                                                                       |1262.098s |19.822GiB|
|scrambled75189.smt2                                                                        |1261.698s |17.935GiB|
|scrambled19335.smt2                                                                        |1261.651s |16.45GiB|
|scrambled43577.smt2                                                                        |1261.544s |16.2GiB|
|scrambled107826.smt2                                                                       |1261.442s |15.218GiB|
|scrambled27843.smt2                                                                        |1261.232s |11.61GiB|
|scrambled107115.smt2                                                                       |1260.858s |9052.0MiB|
|scrambled40621.smt2                                                                        |1260.758s |6958.0MiB|
|scrambled7741.smt2                                                                         |1260.689s |4047.0MiB|
|scrambled61922.smt2                                                                        |1260.609s |5776.0MiB|
|scrambled119331.smt2                                                                       |1260.549s |5652.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.880s |32.378GiB|
|scrambled12042.smt2                                                                        |1262.956s |31.652GiB|
|scrambled79760.smt2                                                                        |1262.665s |22.863GiB|
|scrambled4299.smt2                                                                         |1262.512s |27.482GiB|
|scrambled55680.smt2                                                                        |1262.493s |26.361GiB|
|scrambled68944.smt2                                                                        |1262.378s |25.297GiB|
|scrambled4198.smt2                                                                         |1262.375s |25.752GiB|
|scrambled102166.smt2                                                                       |1262.323s |24.727GiB|
|scrambled108840.smt2                                                                       |1262.184s |23.383GiB|
|scrambled111627.smt2                                                                       |1262.098s |19.822GiB|
|scrambled75189.smt2                                                                        |1261.698s |17.935GiB|
|scrambled19335.smt2                                                                        |1261.651s |16.45GiB|
|scrambled43577.smt2                                                                        |1261.544s |16.2GiB|
|scrambled107826.smt2                                                                       |1261.442s |15.218GiB|
|scrambled27843.smt2                                                                        |1261.232s |11.61GiB|
|scrambled107115.smt2                                                                       |1260.858s |9052.0MiB|
|scrambled40621.smt2                                                                        |1260.758s |6958.0MiB|
|scrambled7741.smt2                                                                         |1260.689s |4047.0MiB|
|scrambled61922.smt2                                                                        |1260.609s |5776.0MiB|
|scrambled119331.smt2                                                                       |1260.549s |5652.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.727GiB|24.727GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.312MiB|42.312MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9052.0MiB|9052.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |15.218GiB|15.218GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |23.383GiB|23.383GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |19.822GiB|19.822GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5652.0MiB|5652.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |31.652GiB|31.652GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |606.0MiB|606.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |968.0MiB|968.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3865.0MiB|3865.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |3054.0MiB|3054.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3127.0MiB|3127.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3851.0MiB|3851.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |217.0MiB|217.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.45GiB|16.45GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |923.0MiB|923.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4415.0MiB|4415.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.61GiB|11.61GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.727GiB|24.727GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.312MiB|42.312MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9052.0MiB|9052.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |15.218GiB|15.218GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |23.383GiB|23.383GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |19.822GiB|19.822GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5652.0MiB|5652.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |31.652GiB|31.652GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |606.0MiB|606.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |968.0MiB|968.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3865.0MiB|3865.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |3054.0MiB|3054.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3127.0MiB|3127.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3851.0MiB|3851.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |217.0MiB|217.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.45GiB|16.45GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |923.0MiB|923.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4415.0MiB|4415.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.61GiB|11.61GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.727GiB|24.727GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.312MiB|42.312MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9052.0MiB|9052.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |15.218GiB|15.218GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |23.383GiB|23.383GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |19.822GiB|19.822GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5652.0MiB|5652.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |31.652GiB|31.652GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |606.0MiB|606.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |968.0MiB|968.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3865.0MiB|3865.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |3054.0MiB|3054.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3127.0MiB|3127.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3851.0MiB|3851.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |217.0MiB|217.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.45GiB|16.45GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |923.0MiB|923.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4415.0MiB|4415.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.61GiB|11.61GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |24.727GiB|24.727GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.312MiB|42.312MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9052.0MiB|9052.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |15.218GiB|15.218GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |23.383GiB|23.383GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |19.822GiB|19.822GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |553.0MiB|553.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5652.0MiB|5652.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |31.652GiB|31.652GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |606.0MiB|606.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |968.0MiB|968.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3865.0MiB|3865.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |3054.0MiB|3054.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3127.0MiB|3127.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3851.0MiB|3851.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |217.0MiB|217.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.45GiB|16.45GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |923.0MiB|923.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4415.0MiB|4415.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.61GiB|11.61GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.880s |32.378GiB|
|scrambled12042.smt2                                                                        |1262.956s |31.652GiB|
|scrambled4299.smt2                                                                         |1262.512s |27.482GiB|
|scrambled55680.smt2                                                                        |1262.493s |26.361GiB|
|scrambled4198.smt2                                                                         |1262.375s |25.752GiB|
|scrambled68944.smt2                                                                        |1262.378s |25.297GiB|
|scrambled102166.smt2                                                                       |1262.323s |24.727GiB|
|scrambled108840.smt2                                                                       |1262.184s |23.383GiB|
|scrambled79760.smt2                                                                        |1262.665s |22.863GiB|
|scrambled111627.smt2                                                                       |1262.098s |19.822GiB|
|scrambled75189.smt2                                                                        |1261.698s |17.935GiB|
|scrambled19335.smt2                                                                        |1261.651s |16.45GiB|
|scrambled43577.smt2                                                                        |1261.544s |16.2GiB|
|scrambled107826.smt2                                                                       |1261.442s |15.218GiB|
|scrambled27843.smt2                                                                        |1261.232s |11.61GiB|
|scrambled107115.smt2                                                                       |1260.858s |9052.0MiB|
|scrambled40621.smt2                                                                        |1260.758s |6958.0MiB|
|scrambled61922.smt2                                                                        |1260.609s |5776.0MiB|
|scrambled119331.smt2                                                                       |1260.549s |5652.0MiB|
|scrambled25238.smt2                                                                        |1118.957s |4415.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1263.880s |32.378GiB|
|scrambled12042.smt2                                                                        |1262.956s |31.652GiB|
|scrambled4299.smt2                                                                         |1262.512s |27.482GiB|
|scrambled55680.smt2                                                                        |1262.493s |26.361GiB|
|scrambled4198.smt2                                                                         |1262.375s |25.752GiB|
|scrambled68944.smt2                                                                        |1262.378s |25.297GiB|
|scrambled102166.smt2                                                                       |1262.323s |24.727GiB|
|scrambled108840.smt2                                                                       |1262.184s |23.383GiB|
|scrambled79760.smt2                                                                        |1262.665s |22.863GiB|
|scrambled111627.smt2                                                                       |1262.098s |19.822GiB|
|scrambled75189.smt2                                                                        |1261.698s |17.935GiB|
|scrambled19335.smt2                                                                        |1261.651s |16.45GiB|
|scrambled43577.smt2                                                                        |1261.544s |16.2GiB|
|scrambled107826.smt2                                                                       |1261.442s |15.218GiB|
|scrambled27843.smt2                                                                        |1261.232s |11.61GiB|
|scrambled107115.smt2                                                                       |1260.858s |9052.0MiB|
|scrambled40621.smt2                                                                        |1260.758s |6958.0MiB|
|scrambled61922.smt2                                                                        |1260.609s |5776.0MiB|
|scrambled119331.smt2                                                                       |1260.549s |5652.0MiB|
|scrambled25238.smt2                                                                        |1118.957s |4415.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1262.323s  |1262.323s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.051s  |1260.051s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.858s  |1260.858s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1261.442s  |1261.442s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1262.184s  |1262.184s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1262.098s  |1262.098s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 122.821s  | 122.821s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.549s  |1260.549s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1262.956s  |1262.956s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 476.205s  | 476.205s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 168.393s  | 168.393s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1260.484s  |1260.484s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.392s  |1260.392s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1260.488s  |1260.488s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1260.499s  |1260.499s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.052s  |1260.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1261.651s  |1261.651s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  68.601s  |  68.601s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1118.957s  |1118.957s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1261.232s  |1261.232s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 413.999s  | 413.999s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1260.029s  |1260.029s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1260.039s  |1260.039s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1260.758s  |1260.758s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1262.375s  |1262.375s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1262.512s  |1262.512s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1261.544s  |1261.544s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1260.327s  |1260.327s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1260.015s  |1260.015s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1260.228s  |1260.228s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1262.493s  |1262.493s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1260.352s  |1260.352s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1260.029s  |1260.029s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1260.609s  |1260.609s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1260.014s  |1260.014s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1262.378s  |1262.378s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1260.376s  |1260.376s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1261.698s  |1261.698s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1260.689s  |1260.689s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1262.665s  |1262.665s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1260.028s  |1260.028s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1260.030s  |1260.030s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1263.880s  |1263.880s  |   0.000s  | 0.0%|
</details>
