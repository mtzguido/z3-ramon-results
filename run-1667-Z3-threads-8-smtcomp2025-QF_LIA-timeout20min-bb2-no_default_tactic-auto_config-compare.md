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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-no_default_tactic-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=true smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-no_default_tactic-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=true smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.428s  |1200.428s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.125s  |1200.125s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 212.597s  | 212.597s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.757s  |1200.757s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.307s  |1200.307s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 838.021s  | 838.021s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 110.471s  | 110.471s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.589s  |1200.589s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.852s  |1200.852s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.457s  |1200.457s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.525s  |1200.525s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1024.651s  |1024.651s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1181.624s  |1181.624s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 870.426s  | 870.426s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.088s  |1200.088s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.428s  |1200.428s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.125s  |1200.125s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 212.597s  | 212.597s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.757s  |1200.757s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.307s  |1200.307s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 838.021s  | 838.021s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 110.471s  | 110.471s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.589s  |1200.589s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.852s  |1200.852s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.457s  |1200.457s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.525s  |1200.525s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1024.651s  |1024.651s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1181.624s  |1181.624s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 870.426s  | 870.426s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.088s  |1200.088s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.428s  |1200.428s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.125s  |1200.125s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 212.597s  | 212.597s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.757s  |1200.757s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.307s  |1200.307s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 838.021s  | 838.021s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 110.471s  | 110.471s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.589s  |1200.589s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.852s  |1200.852s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.457s  |1200.457s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.525s  |1200.525s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1024.651s  |1024.651s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1181.624s  |1181.624s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 870.426s  | 870.426s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.088s  |1200.088s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.428s  |1200.428s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.125s  |1200.125s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 212.597s  | 212.597s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.757s  |1200.757s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.307s  |1200.307s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 838.021s  | 838.021s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 110.471s  | 110.471s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.589s  |1200.589s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.852s  |1200.852s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.457s  |1200.457s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.525s  |1200.525s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1024.651s  |1024.651s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1181.624s  |1181.624s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 870.426s  | 870.426s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.088s  |1200.088s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled72668.smt2                                                                        |1200.891s |5108.0MiB|
|scrambled128732.smt2                                                                       |1200.852s |4557.0MiB|
|scrambled44911.smt2                                                                        |1200.779s |4055.0MiB|
|scrambled119331.smt2                                                                       |1200.757s |6763.0MiB|
|scrambled40621.smt2                                                                        |1200.745s |7363.0MiB|
|scrambled7741.smt2                                                                         |1200.745s |6134.0MiB|
|scrambled128128.smt2                                                                       |1200.589s |5615.0MiB|
|scrambled131241.smt2                                                                       |1200.525s |5251.0MiB|
|scrambled128874.smt2                                                                       |1200.457s |4600.0MiB|
|scrambled102166.smt2                                                                       |1200.428s |2942.0MiB|
|scrambled4198.smt2                                                                         |1200.421s |2767.0MiB|
|scrambled55777.smt2                                                                        |1200.358s |3597.0MiB|
|scrambled94658.smt2                                                                        |1200.333s |2913.0MiB|
|scrambled55680.smt2                                                                        |1200.320s |2742.0MiB|
|scrambled68944.smt2                                                                        |1200.311s |1814.0MiB|
|scrambled12042.smt2                                                                        |1200.307s |2906.0MiB|
|scrambled95803.smt2                                                                        |1200.285s |2348.0MiB|
|scrambled4299.smt2                                                                         |1200.227s |2136.0MiB|
|scrambled79760.smt2                                                                        |1200.223s |1799.0MiB|
|scrambled43577.smt2                                                                        |1200.176s |1184.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled72668.smt2                                                                        |1200.891s |5108.0MiB|
|scrambled128732.smt2                                                                       |1200.852s |4557.0MiB|
|scrambled44911.smt2                                                                        |1200.779s |4055.0MiB|
|scrambled119331.smt2                                                                       |1200.757s |6763.0MiB|
|scrambled40621.smt2                                                                        |1200.745s |7363.0MiB|
|scrambled7741.smt2                                                                         |1200.745s |6134.0MiB|
|scrambled128128.smt2                                                                       |1200.589s |5615.0MiB|
|scrambled131241.smt2                                                                       |1200.525s |5251.0MiB|
|scrambled128874.smt2                                                                       |1200.457s |4600.0MiB|
|scrambled102166.smt2                                                                       |1200.428s |2942.0MiB|
|scrambled4198.smt2                                                                         |1200.421s |2767.0MiB|
|scrambled55777.smt2                                                                        |1200.358s |3597.0MiB|
|scrambled94658.smt2                                                                        |1200.333s |2913.0MiB|
|scrambled55680.smt2                                                                        |1200.320s |2742.0MiB|
|scrambled68944.smt2                                                                        |1200.311s |1814.0MiB|
|scrambled12042.smt2                                                                        |1200.307s |2906.0MiB|
|scrambled95803.smt2                                                                        |1200.285s |2348.0MiB|
|scrambled4299.smt2                                                                         |1200.227s |2136.0MiB|
|scrambled79760.smt2                                                                        |1200.223s |1799.0MiB|
|scrambled43577.smt2                                                                        |1200.176s |1184.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2942.0MiB|2942.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.072MiB|43.072MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |641.0MiB|641.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1162.0MiB|1162.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1553.0MiB|1553.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1292.0MiB|1292.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |932.0MiB|932.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |6763.0MiB|6763.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2906.0MiB|2906.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1025.0MiB|1025.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1495.0MiB|1495.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |5615.0MiB|5615.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4557.0MiB|4557.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4600.0MiB|4600.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5251.0MiB|5251.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |284.0MiB|284.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1276.0MiB|1276.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1700.0MiB|1700.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |6552.0MiB|6552.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |682.0MiB|682.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2942.0MiB|2942.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.072MiB|43.072MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |641.0MiB|641.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1162.0MiB|1162.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1553.0MiB|1553.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1292.0MiB|1292.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |932.0MiB|932.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |6763.0MiB|6763.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2906.0MiB|2906.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1025.0MiB|1025.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1495.0MiB|1495.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |5615.0MiB|5615.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4557.0MiB|4557.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4600.0MiB|4600.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5251.0MiB|5251.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |284.0MiB|284.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1276.0MiB|1276.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1700.0MiB|1700.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |6552.0MiB|6552.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |682.0MiB|682.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2942.0MiB|2942.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.072MiB|43.072MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |641.0MiB|641.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1162.0MiB|1162.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1553.0MiB|1553.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1292.0MiB|1292.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |932.0MiB|932.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |6763.0MiB|6763.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2906.0MiB|2906.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1025.0MiB|1025.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1495.0MiB|1495.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |5615.0MiB|5615.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4557.0MiB|4557.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4600.0MiB|4600.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5251.0MiB|5251.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |284.0MiB|284.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1276.0MiB|1276.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1700.0MiB|1700.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |6552.0MiB|6552.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |682.0MiB|682.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2942.0MiB|2942.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.072MiB|43.072MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |641.0MiB|641.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1162.0MiB|1162.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1553.0MiB|1553.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1292.0MiB|1292.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |932.0MiB|932.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |6763.0MiB|6763.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2906.0MiB|2906.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1025.0MiB|1025.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1495.0MiB|1495.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |5615.0MiB|5615.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4557.0MiB|4557.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4600.0MiB|4600.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5251.0MiB|5251.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |284.0MiB|284.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1276.0MiB|1276.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1700.0MiB|1700.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |6552.0MiB|6552.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |682.0MiB|682.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled40621.smt2                                                                        |1200.745s |7363.0MiB|
|scrambled119331.smt2                                                                       |1200.757s |6763.0MiB|
|scrambled25238.smt2                                                                        | 870.426s |6552.0MiB|
|scrambled7741.smt2                                                                         |1200.745s |6134.0MiB|
|scrambled128128.smt2                                                                       |1200.589s |5615.0MiB|
|scrambled131241.smt2                                                                       |1200.525s |5251.0MiB|
|scrambled72668.smt2                                                                        |1200.891s |5108.0MiB|
|scrambled128874.smt2                                                                       |1200.457s |4600.0MiB|
|scrambled128732.smt2                                                                       |1200.852s |4557.0MiB|
|scrambled44911.smt2                                                                        |1200.779s |4055.0MiB|
|scrambled55777.smt2                                                                        |1200.358s |3597.0MiB|
|scrambled102166.smt2                                                                       |1200.428s |2942.0MiB|
|scrambled94658.smt2                                                                        |1200.333s |2913.0MiB|
|scrambled12042.smt2                                                                        |1200.307s |2906.0MiB|
|scrambled4198.smt2                                                                         |1200.421s |2767.0MiB|
|scrambled55680.smt2                                                                        |1200.320s |2742.0MiB|
|scrambled32836.smt2                                                                        |1109.388s |2637.0MiB|
|scrambled95803.smt2                                                                        |1200.285s |2348.0MiB|
|scrambled4299.smt2                                                                         |1200.227s |2136.0MiB|
|scrambled68944.smt2                                                                        |1200.311s |1814.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled40621.smt2                                                                        |1200.745s |7363.0MiB|
|scrambled119331.smt2                                                                       |1200.757s |6763.0MiB|
|scrambled25238.smt2                                                                        | 870.426s |6552.0MiB|
|scrambled7741.smt2                                                                         |1200.745s |6134.0MiB|
|scrambled128128.smt2                                                                       |1200.589s |5615.0MiB|
|scrambled131241.smt2                                                                       |1200.525s |5251.0MiB|
|scrambled72668.smt2                                                                        |1200.891s |5108.0MiB|
|scrambled128874.smt2                                                                       |1200.457s |4600.0MiB|
|scrambled128732.smt2                                                                       |1200.852s |4557.0MiB|
|scrambled44911.smt2                                                                        |1200.779s |4055.0MiB|
|scrambled55777.smt2                                                                        |1200.358s |3597.0MiB|
|scrambled102166.smt2                                                                       |1200.428s |2942.0MiB|
|scrambled94658.smt2                                                                        |1200.333s |2913.0MiB|
|scrambled12042.smt2                                                                        |1200.307s |2906.0MiB|
|scrambled4198.smt2                                                                         |1200.421s |2767.0MiB|
|scrambled55680.smt2                                                                        |1200.320s |2742.0MiB|
|scrambled32836.smt2                                                                        |1109.388s |2637.0MiB|
|scrambled95803.smt2                                                                        |1200.285s |2348.0MiB|
|scrambled4299.smt2                                                                         |1200.227s |2136.0MiB|
|scrambled68944.smt2                                                                        |1200.311s |1814.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.428s  |1200.428s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.116s  |1200.116s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.155s  |1200.155s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.125s  |1200.125s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 212.597s  | 212.597s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.757s  |1200.757s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.307s  |1200.307s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 838.021s  | 838.021s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 110.471s  | 110.471s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.589s  |1200.589s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.852s  |1200.852s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.457s  |1200.457s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.525s  |1200.525s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1024.651s  |1024.651s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1181.624s  |1181.624s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 870.426s  | 870.426s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1109.388s  |1109.388s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.012s  |1200.012s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1200.745s  |1200.745s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1200.421s  |1200.421s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1200.227s  |1200.227s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1200.176s  |1200.176s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.779s  |1200.779s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         | 223.404s  | 223.404s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1200.320s  |1200.320s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.358s  |1200.358s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |   7.448s  |   7.448s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1200.311s  |1200.311s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1200.891s  |1200.891s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1200.114s  |1200.114s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.745s  |1200.745s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1200.223s  |1200.223s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1200.333s  |1200.333s  |   0.000s  | 0.0%|
</details>
