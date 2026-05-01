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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 16130e3063965c4ae1cb3c04f2feebb678ee84ae
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore unit sharing as bb collection on workers

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 16130e3063965c4ae1cb3c04f2feebb678ee84ae
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore unit sharing as bb collection on workers

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.488s  |1204.488s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.915s  |1201.915s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1203.588s  |1203.588s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1204.081s  |1204.081s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.591s  |1203.591s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 111.490s  | 111.490s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.938s  |1200.938s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1205.669s  |1205.669s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 542.310s  | 542.310s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 138.650s  | 138.650s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.630s  |1200.630s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.522s  |1200.522s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.641s  |1200.641s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.973s  |1200.973s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.071s  |1200.071s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.553s  |1203.553s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  68.220s  |  68.220s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 193.412s  | 193.412s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.817s  |1202.817s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.488s  |1204.488s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.915s  |1201.915s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1203.588s  |1203.588s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1204.081s  |1204.081s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.591s  |1203.591s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 111.490s  | 111.490s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.938s  |1200.938s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1205.669s  |1205.669s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 542.310s  | 542.310s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 138.650s  | 138.650s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.630s  |1200.630s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.522s  |1200.522s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.641s  |1200.641s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.973s  |1200.973s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.071s  |1200.071s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.553s  |1203.553s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  68.220s  |  68.220s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 193.412s  | 193.412s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.817s  |1202.817s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.488s  |1204.488s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.915s  |1201.915s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1203.588s  |1203.588s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1204.081s  |1204.081s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.591s  |1203.591s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 111.490s  | 111.490s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.938s  |1200.938s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1205.669s  |1205.669s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 542.310s  | 542.310s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 138.650s  | 138.650s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.630s  |1200.630s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.522s  |1200.522s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.641s  |1200.641s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.973s  |1200.973s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.071s  |1200.071s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.553s  |1203.553s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  68.220s  |  68.220s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 193.412s  | 193.412s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.817s  |1202.817s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.488s  |1204.488s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.915s  |1201.915s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1203.588s  |1203.588s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1204.081s  |1204.081s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.591s  |1203.591s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 111.490s  | 111.490s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.938s  |1200.938s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1205.669s  |1205.669s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 542.310s  | 542.310s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 138.650s  | 138.650s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.630s  |1200.630s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.522s  |1200.522s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.641s  |1200.641s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.973s  |1200.973s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.071s  |1200.071s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.553s  |1203.553s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  68.220s  |  68.220s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 193.412s  | 193.412s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.817s  |1202.817s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.839s |63.094GiB|
|scrambled12042.smt2                                                                        |1205.669s |54.312GiB|
|scrambled4299.smt2                                                                         |1205.196s |56.793GiB|
|scrambled55680.smt2                                                                        |1204.697s |50.699GiB|
|scrambled102166.smt2                                                                       |1204.488s |48.145GiB|
|scrambled68944.smt2                                                                        |1204.439s |46.998GiB|
|scrambled4198.smt2                                                                         |1204.323s |49.033GiB|
|scrambled108840.smt2                                                                       |1204.081s |43.053GiB|
|scrambled79760.smt2                                                                        |1203.899s |44.258GiB|
|scrambled111627.smt2                                                                       |1203.591s |37.787GiB|
|scrambled107826.smt2                                                                       |1203.588s |27.961GiB|
|scrambled19335.smt2                                                                        |1203.553s |32.407GiB|
|scrambled43577.smt2                                                                        |1203.253s |34.259GiB|
|scrambled75189.smt2                                                                        |1202.903s |31.713GiB|
|scrambled27843.smt2                                                                        |1202.817s |21.026GiB|
|scrambled107115.smt2                                                                       |1201.915s |17.776GiB|
|scrambled40621.smt2                                                                        |1201.252s |11.238GiB|
|scrambled61922.smt2                                                                        |1201.107s |10.835GiB|
|scrambled131241.smt2                                                                       |1200.973s |6445.0MiB|
|scrambled119331.smt2                                                                       |1200.938s |9511.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.839s |63.094GiB|
|scrambled12042.smt2                                                                        |1205.669s |54.312GiB|
|scrambled4299.smt2                                                                         |1205.196s |56.793GiB|
|scrambled55680.smt2                                                                        |1204.697s |50.699GiB|
|scrambled102166.smt2                                                                       |1204.488s |48.145GiB|
|scrambled68944.smt2                                                                        |1204.439s |46.998GiB|
|scrambled4198.smt2                                                                         |1204.323s |49.033GiB|
|scrambled108840.smt2                                                                       |1204.081s |43.053GiB|
|scrambled79760.smt2                                                                        |1203.899s |44.258GiB|
|scrambled111627.smt2                                                                       |1203.591s |37.787GiB|
|scrambled107826.smt2                                                                       |1203.588s |27.961GiB|
|scrambled19335.smt2                                                                        |1203.553s |32.407GiB|
|scrambled43577.smt2                                                                        |1203.253s |34.259GiB|
|scrambled75189.smt2                                                                        |1202.903s |31.713GiB|
|scrambled27843.smt2                                                                        |1202.817s |21.026GiB|
|scrambled107115.smt2                                                                       |1201.915s |17.776GiB|
|scrambled40621.smt2                                                                        |1201.252s |11.238GiB|
|scrambled61922.smt2                                                                        |1201.107s |10.835GiB|
|scrambled131241.smt2                                                                       |1200.973s |6445.0MiB|
|scrambled119331.smt2                                                                       |1200.938s |9511.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.145GiB|48.145GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.548MiB|42.548MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.776GiB|17.776GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.961GiB|27.961GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.053GiB|43.053GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.787GiB|37.787GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |948.0MiB|948.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9511.0MiB|9511.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.312GiB|54.312GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1032.0MiB|1032.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1607.0MiB|1607.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6509.0MiB|6509.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5151.0MiB|5151.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5205.0MiB|5205.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6445.0MiB|6445.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |377.0MiB|377.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.407GiB|32.407GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1584.0MiB|1584.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5848.0MiB|5848.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.026GiB|21.026GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.145GiB|48.145GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.548MiB|42.548MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.776GiB|17.776GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.961GiB|27.961GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.053GiB|43.053GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.787GiB|37.787GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |948.0MiB|948.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9511.0MiB|9511.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.312GiB|54.312GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1032.0MiB|1032.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1607.0MiB|1607.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6509.0MiB|6509.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5151.0MiB|5151.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5205.0MiB|5205.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6445.0MiB|6445.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |377.0MiB|377.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.407GiB|32.407GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1584.0MiB|1584.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5848.0MiB|5848.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.026GiB|21.026GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.145GiB|48.145GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.548MiB|42.548MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.776GiB|17.776GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.961GiB|27.961GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.053GiB|43.053GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.787GiB|37.787GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |948.0MiB|948.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9511.0MiB|9511.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.312GiB|54.312GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1032.0MiB|1032.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1607.0MiB|1607.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6509.0MiB|6509.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5151.0MiB|5151.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5205.0MiB|5205.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6445.0MiB|6445.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |377.0MiB|377.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.407GiB|32.407GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1584.0MiB|1584.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5848.0MiB|5848.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.026GiB|21.026GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.145GiB|48.145GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.548MiB|42.548MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.776GiB|17.776GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.961GiB|27.961GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.053GiB|43.053GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.787GiB|37.787GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |948.0MiB|948.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9511.0MiB|9511.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.312GiB|54.312GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1032.0MiB|1032.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1607.0MiB|1607.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6509.0MiB|6509.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5151.0MiB|5151.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5205.0MiB|5205.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6445.0MiB|6445.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |377.0MiB|377.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.407GiB|32.407GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1584.0MiB|1584.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5848.0MiB|5848.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.026GiB|21.026GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.839s |63.094GiB|
|scrambled4299.smt2                                                                         |1205.196s |56.793GiB|
|scrambled12042.smt2                                                                        |1205.669s |54.312GiB|
|scrambled55680.smt2                                                                        |1204.697s |50.699GiB|
|scrambled4198.smt2                                                                         |1204.323s |49.033GiB|
|scrambled102166.smt2                                                                       |1204.488s |48.145GiB|
|scrambled68944.smt2                                                                        |1204.439s |46.998GiB|
|scrambled79760.smt2                                                                        |1203.899s |44.258GiB|
|scrambled108840.smt2                                                                       |1204.081s |43.053GiB|
|scrambled111627.smt2                                                                       |1203.591s |37.787GiB|
|scrambled43577.smt2                                                                        |1203.253s |34.259GiB|
|scrambled19335.smt2                                                                        |1203.553s |32.407GiB|
|scrambled75189.smt2                                                                        |1202.903s |31.713GiB|
|scrambled107826.smt2                                                                       |1203.588s |27.961GiB|
|scrambled27843.smt2                                                                        |1202.817s |21.026GiB|
|scrambled107115.smt2                                                                       |1201.915s |17.776GiB|
|scrambled40621.smt2                                                                        |1201.252s |11.238GiB|
|scrambled61922.smt2                                                                        |1201.107s |10.835GiB|
|scrambled119331.smt2                                                                       |1200.938s |9511.0MiB|
|scrambled7741.smt2                                                                         |1200.772s |6775.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.839s |63.094GiB|
|scrambled4299.smt2                                                                         |1205.196s |56.793GiB|
|scrambled12042.smt2                                                                        |1205.669s |54.312GiB|
|scrambled55680.smt2                                                                        |1204.697s |50.699GiB|
|scrambled4198.smt2                                                                         |1204.323s |49.033GiB|
|scrambled102166.smt2                                                                       |1204.488s |48.145GiB|
|scrambled68944.smt2                                                                        |1204.439s |46.998GiB|
|scrambled79760.smt2                                                                        |1203.899s |44.258GiB|
|scrambled108840.smt2                                                                       |1204.081s |43.053GiB|
|scrambled111627.smt2                                                                       |1203.591s |37.787GiB|
|scrambled43577.smt2                                                                        |1203.253s |34.259GiB|
|scrambled19335.smt2                                                                        |1203.553s |32.407GiB|
|scrambled75189.smt2                                                                        |1202.903s |31.713GiB|
|scrambled107826.smt2                                                                       |1203.588s |27.961GiB|
|scrambled27843.smt2                                                                        |1202.817s |21.026GiB|
|scrambled107115.smt2                                                                       |1201.915s |17.776GiB|
|scrambled40621.smt2                                                                        |1201.252s |11.238GiB|
|scrambled61922.smt2                                                                        |1201.107s |10.835GiB|
|scrambled119331.smt2                                                                       |1200.938s |9511.0MiB|
|scrambled7741.smt2                                                                         |1200.772s |6775.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.488s  |1204.488s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.915s  |1201.915s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1203.588s  |1203.588s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1204.081s  |1204.081s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.591s  |1203.591s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 111.490s  | 111.490s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.938s  |1200.938s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1205.669s  |1205.669s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 542.310s  | 542.310s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 138.650s  | 138.650s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.630s  |1200.630s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.522s  |1200.522s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.641s  |1200.641s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.973s  |1200.973s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.071s  |1200.071s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.553s  |1203.553s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  68.220s  |  68.220s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 193.412s  | 193.412s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.817s  |1202.817s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 444.985s  | 444.985s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1201.252s  |1201.252s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1204.323s  |1204.323s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1205.196s  |1205.196s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1203.253s  |1203.253s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.726s  |1200.726s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.399s  |1200.399s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1204.697s  |1204.697s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.510s  |1200.510s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1201.107s  |1201.107s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1204.439s  |1204.439s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         | 651.169s  | 651.169s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1202.903s  |1202.903s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.772s  |1200.772s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1203.899s  |1203.899s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1205.839s  |1205.839s  |   0.000s  | 0.0%|
</details>
