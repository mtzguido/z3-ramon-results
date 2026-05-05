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
Job tag: Z3-threads-8-smtcomp2025-QF_NRA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NRA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NRA-timeout20min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NRA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.071s  |1200.071s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.081s  |1200.081s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1202.001s  |1202.001s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.440s  |1200.440s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.983s  |1200.983s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.499s  |1200.499s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1201.692s  |1201.692s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.477s  |1200.477s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.972s  |   0.972s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.164s  |1200.164s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.071s  |1200.071s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.081s  |1200.081s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1202.001s  |1202.001s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.440s  |1200.440s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.983s  |1200.983s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.499s  |1200.499s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1201.692s  |1201.692s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.477s  |1200.477s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.972s  |   0.972s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.164s  |1200.164s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.071s  |1200.071s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.081s  |1200.081s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1202.001s  |1202.001s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.440s  |1200.440s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.983s  |1200.983s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.499s  |1200.499s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1201.692s  |1201.692s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.477s  |1200.477s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.972s  |   0.972s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.164s  |1200.164s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.071s  |1200.071s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.081s  |1200.081s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1202.001s  |1202.001s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.440s  |1200.440s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.983s  |1200.983s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.499s  |1200.499s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1201.692s  |1201.692s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.477s  |1200.477s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.972s  |   0.972s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.164s  |1200.164s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled5797.smt2                                                                         |1203.778s |45.166GiB|
|scrambled114923.smt2                                                                       |1202.001s |18.555GiB|
|scrambled22492.smt2                                                                        |1201.692s |17.874GiB|
|scrambled124828.smt2                                                                       |1200.983s |9155.0MiB|
|scrambled41575.smt2                                                                        |1200.855s |4879.0MiB|
|scrambled70990.smt2                                                                        |1200.777s |4603.0MiB|
|scrambled65757.smt2                                                                        |1200.721s |5435.0MiB|
|scrambled78428.smt2                                                                        |1200.695s |7130.0MiB|
|scrambled58292.smt2                                                                        |1200.605s |4801.0MiB|
|scrambled61896.smt2                                                                        |1200.598s |4072.0MiB|
|scrambled91241.smt2                                                                        |1200.580s |7177.0MiB|
|scrambled6476.smt2                                                                         |1200.570s |9534.0MiB|
|scrambled14016.smt2                                                                        |1200.499s |4143.0MiB|
|scrambled27426.smt2                                                                        |1200.477s |7457.0MiB|
|scrambled121780.smt2                                                                       |1200.440s |9576.0MiB|
|scrambled60239.smt2                                                                        |1200.411s |5432.0MiB|
|scrambled94768.smt2                                                                        |1200.244s |1286.0MiB|
|scrambled94319.smt2                                                                        |1200.211s |1616.0MiB|
|scrambled32701.smt2                                                                        |1200.164s |930.0MiB|
|scrambled85895.smt2                                                                        |1200.144s |972.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled5797.smt2                                                                         |1203.778s |45.166GiB|
|scrambled114923.smt2                                                                       |1202.001s |18.555GiB|
|scrambled22492.smt2                                                                        |1201.692s |17.874GiB|
|scrambled124828.smt2                                                                       |1200.983s |9155.0MiB|
|scrambled41575.smt2                                                                        |1200.855s |4879.0MiB|
|scrambled70990.smt2                                                                        |1200.777s |4603.0MiB|
|scrambled65757.smt2                                                                        |1200.721s |5435.0MiB|
|scrambled78428.smt2                                                                        |1200.695s |7130.0MiB|
|scrambled58292.smt2                                                                        |1200.605s |4801.0MiB|
|scrambled61896.smt2                                                                        |1200.598s |4072.0MiB|
|scrambled91241.smt2                                                                        |1200.580s |7177.0MiB|
|scrambled6476.smt2                                                                         |1200.570s |9534.0MiB|
|scrambled14016.smt2                                                                        |1200.499s |4143.0MiB|
|scrambled27426.smt2                                                                        |1200.477s |7457.0MiB|
|scrambled121780.smt2                                                                       |1200.440s |9576.0MiB|
|scrambled60239.smt2                                                                        |1200.411s |5432.0MiB|
|scrambled94768.smt2                                                                        |1200.244s |1286.0MiB|
|scrambled94319.smt2                                                                        |1200.211s |1616.0MiB|
|scrambled32701.smt2                                                                        |1200.164s |930.0MiB|
|scrambled85895.smt2                                                                        |1200.144s |972.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |322.0MiB|322.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |312.0MiB|312.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |316.0MiB|316.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |18.555GiB|18.555GiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |334.0MiB|334.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |300.0MiB|300.0MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |457.0MiB|457.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |9576.0MiB|9576.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |9155.0MiB|9155.0MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |4143.0MiB|4143.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |291.0MiB|291.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |308.0MiB|308.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |17.874GiB|17.874GiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |7457.0MiB|7457.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |302.0MiB|302.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |271.0MiB|271.0MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |337.0MiB|337.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |930.0MiB|930.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |322.0MiB|322.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |312.0MiB|312.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |316.0MiB|316.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |18.555GiB|18.555GiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |334.0MiB|334.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |300.0MiB|300.0MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |457.0MiB|457.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |9576.0MiB|9576.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |9155.0MiB|9155.0MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |4143.0MiB|4143.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |291.0MiB|291.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |308.0MiB|308.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |17.874GiB|17.874GiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |7457.0MiB|7457.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |302.0MiB|302.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |271.0MiB|271.0MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |337.0MiB|337.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |930.0MiB|930.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |322.0MiB|322.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |312.0MiB|312.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |316.0MiB|316.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |18.555GiB|18.555GiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |334.0MiB|334.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |300.0MiB|300.0MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |457.0MiB|457.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |9576.0MiB|9576.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |9155.0MiB|9155.0MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |4143.0MiB|4143.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |291.0MiB|291.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |308.0MiB|308.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |17.874GiB|17.874GiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |7457.0MiB|7457.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |302.0MiB|302.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |271.0MiB|271.0MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |337.0MiB|337.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |930.0MiB|930.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |322.0MiB|322.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |312.0MiB|312.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |316.0MiB|316.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |18.555GiB|18.555GiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |334.0MiB|334.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |300.0MiB|300.0MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |457.0MiB|457.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |9576.0MiB|9576.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |9155.0MiB|9155.0MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |4143.0MiB|4143.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |291.0MiB|291.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |308.0MiB|308.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |354.0MiB|354.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |17.874GiB|17.874GiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |7457.0MiB|7457.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |302.0MiB|302.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |271.0MiB|271.0MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |337.0MiB|337.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |930.0MiB|930.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled5797.smt2                                                                         |1203.778s |45.166GiB|
|scrambled114923.smt2                                                                       |1202.001s |18.555GiB|
|scrambled22492.smt2                                                                        |1201.692s |17.874GiB|
|scrambled121780.smt2                                                                       |1200.440s |9576.0MiB|
|scrambled6476.smt2                                                                         |1200.570s |9534.0MiB|
|scrambled124828.smt2                                                                       |1200.983s |9155.0MiB|
|scrambled27426.smt2                                                                        |1200.477s |7457.0MiB|
|scrambled91241.smt2                                                                        |1200.580s |7177.0MiB|
|scrambled78428.smt2                                                                        |1200.695s |7130.0MiB|
|scrambled65757.smt2                                                                        |1200.721s |5435.0MiB|
|scrambled60239.smt2                                                                        |1200.411s |5432.0MiB|
|scrambled41575.smt2                                                                        |1200.855s |4879.0MiB|
|scrambled58292.smt2                                                                        |1200.605s |4801.0MiB|
|scrambled70990.smt2                                                                        |1200.777s |4603.0MiB|
|scrambled14016.smt2                                                                        |1200.499s |4143.0MiB|
|scrambled61896.smt2                                                                        |1200.598s |4072.0MiB|
|scrambled94319.smt2                                                                        |1200.211s |1616.0MiB|
|scrambled94768.smt2                                                                        |1200.244s |1286.0MiB|
|scrambled85895.smt2                                                                        |1200.144s |972.0MiB|
|scrambled32701.smt2                                                                        |1200.164s |930.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled5797.smt2                                                                         |1203.778s |45.166GiB|
|scrambled114923.smt2                                                                       |1202.001s |18.555GiB|
|scrambled22492.smt2                                                                        |1201.692s |17.874GiB|
|scrambled121780.smt2                                                                       |1200.440s |9576.0MiB|
|scrambled6476.smt2                                                                         |1200.570s |9534.0MiB|
|scrambled124828.smt2                                                                       |1200.983s |9155.0MiB|
|scrambled27426.smt2                                                                        |1200.477s |7457.0MiB|
|scrambled91241.smt2                                                                        |1200.580s |7177.0MiB|
|scrambled78428.smt2                                                                        |1200.695s |7130.0MiB|
|scrambled65757.smt2                                                                        |1200.721s |5435.0MiB|
|scrambled60239.smt2                                                                        |1200.411s |5432.0MiB|
|scrambled41575.smt2                                                                        |1200.855s |4879.0MiB|
|scrambled58292.smt2                                                                        |1200.605s |4801.0MiB|
|scrambled70990.smt2                                                                        |1200.777s |4603.0MiB|
|scrambled14016.smt2                                                                        |1200.499s |4143.0MiB|
|scrambled61896.smt2                                                                        |1200.598s |4072.0MiB|
|scrambled94319.smt2                                                                        |1200.211s |1616.0MiB|
|scrambled94768.smt2                                                                        |1200.244s |1286.0MiB|
|scrambled85895.smt2                                                                        |1200.144s |972.0MiB|
|scrambled32701.smt2                                                                        |1200.164s |930.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.071s  |1200.071s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.081s  |1200.081s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1202.001s  |1202.001s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.440s  |1200.440s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.983s  |1200.983s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.499s  |1200.499s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1201.692s  |1201.692s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.477s  |1200.477s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.972s  |   0.972s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled34121.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled36539.smt2                                                                         |   1.874s  |   1.874s  |   0.000s  | 0.0%|
|scrambled41575.smt2                                                                         |1200.855s  |1200.855s  |   0.000s  | 0.0%|
|scrambled42946.smt2                                                                         |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled54263.smt2                                                                         |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled5797.smt2                                                                          |1203.778s  |1203.778s  |   0.000s  | 0.0%|
|scrambled58292.smt2                                                                         |1200.605s  |1200.605s  |   0.000s  | 0.0%|
|scrambled60239.smt2                                                                         |1200.411s  |1200.411s  |   0.000s  | 0.0%|
|scrambled61896.smt2                                                                         |1200.598s  |1200.598s  |   0.000s  | 0.0%|
|scrambled6476.smt2                                                                          |1200.570s  |1200.570s  |   0.000s  | 0.0%|
|scrambled65757.smt2                                                                         |1200.721s  |1200.721s  |   0.000s  | 0.0%|
|scrambled70990.smt2                                                                         |1200.777s  |1200.777s  |   0.000s  | 0.0%|
|scrambled73220.smt2                                                                         |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled74869.smt2                                                                         |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled7586.smt2                                                                          |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled78428.smt2                                                                         |1200.695s  |1200.695s  |   0.000s  | 0.0%|
|scrambled7923.smt2                                                                          |1200.084s  |1200.084s  |   0.000s  | 0.0%|
|scrambled80728.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled82241.smt2                                                                         |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled85895.smt2                                                                         |1200.144s  |1200.144s  |   0.000s  | 0.0%|
|scrambled91241.smt2                                                                         |1200.580s  |1200.580s  |   0.000s  | 0.0%|
|scrambled94319.smt2                                                                         |1200.211s  |1200.211s  |   0.000s  | 0.0%|
|scrambled94768.smt2                                                                         |1200.244s  |1200.244s  |   0.000s  | 0.0%|
</details>
