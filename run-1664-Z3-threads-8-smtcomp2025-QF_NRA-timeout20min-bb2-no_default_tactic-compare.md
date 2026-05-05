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
Job tag: Z3-threads-8-smtcomp2025-QF_NRA-timeout20min-bb2-no_default_tactic
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NRA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NRA-timeout20min-bb2-no_default_tactic
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NRA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1201.414s  |1201.414s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.492s  |1200.492s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1201.245s  |1201.245s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.463s  |1200.463s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |  51.295s  |  51.295s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1201.685s  |1201.685s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.384s  |1200.384s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1201.414s  |1201.414s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.492s  |1200.492s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1201.245s  |1201.245s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.463s  |1200.463s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |  51.295s  |  51.295s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1201.685s  |1201.685s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.384s  |1200.384s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1201.414s  |1201.414s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.492s  |1200.492s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1201.245s  |1201.245s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.463s  |1200.463s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |  51.295s  |  51.295s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1201.685s  |1201.685s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.384s  |1200.384s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1201.414s  |1201.414s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.492s  |1200.492s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1201.245s  |1201.245s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.463s  |1200.463s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |  51.295s  |  51.295s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1201.685s  |1201.685s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.384s  |1200.384s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled5797.smt2                                                                         |1202.044s |24.915GiB|
|scrambled22492.smt2                                                                        |1201.685s |18.575GiB|
|scrambled114923.smt2                                                                       |1201.414s |16.322GiB|
|scrambled65757.smt2                                                                        |1201.286s |12.829GiB|
|scrambled124828.smt2                                                                       |1201.245s |14.182GiB|
|scrambled61896.smt2                                                                        |1200.690s |4737.0MiB|
|scrambled58292.smt2                                                                        |1200.670s |6856.0MiB|
|scrambled6476.smt2                                                                         |1200.642s |9574.0MiB|
|scrambled78428.smt2                                                                        |1200.630s |7342.0MiB|
|scrambled70990.smt2                                                                        |1200.545s |4774.0MiB|
|scrambled91241.smt2                                                                        |1200.520s |7185.0MiB|
|scrambled121780.smt2                                                                       |1200.492s |9643.0MiB|
|scrambled41575.smt2                                                                        |1200.487s |5293.0MiB|
|scrambled14016.smt2                                                                        |1200.463s |3833.0MiB|
|scrambled60239.smt2                                                                        |1200.401s |5686.0MiB|
|scrambled27426.smt2                                                                        |1200.384s |7717.0MiB|
|scrambled36539.smt2                                                                        |1200.229s |2161.0MiB|
|scrambled94319.smt2                                                                        |1200.211s |1806.0MiB|
|scrambled85895.smt2                                                                        |1200.179s |1341.0MiB|
|scrambled94768.smt2                                                                        |1200.148s |1132.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled5797.smt2                                                                         |1202.044s |24.915GiB|
|scrambled22492.smt2                                                                        |1201.685s |18.575GiB|
|scrambled114923.smt2                                                                       |1201.414s |16.322GiB|
|scrambled65757.smt2                                                                        |1201.286s |12.829GiB|
|scrambled124828.smt2                                                                       |1201.245s |14.182GiB|
|scrambled61896.smt2                                                                        |1200.690s |4737.0MiB|
|scrambled58292.smt2                                                                        |1200.670s |6856.0MiB|
|scrambled6476.smt2                                                                         |1200.642s |9574.0MiB|
|scrambled78428.smt2                                                                        |1200.630s |7342.0MiB|
|scrambled70990.smt2                                                                        |1200.545s |4774.0MiB|
|scrambled91241.smt2                                                                        |1200.520s |7185.0MiB|
|scrambled121780.smt2                                                                       |1200.492s |9643.0MiB|
|scrambled41575.smt2                                                                        |1200.487s |5293.0MiB|
|scrambled14016.smt2                                                                        |1200.463s |3833.0MiB|
|scrambled60239.smt2                                                                        |1200.401s |5686.0MiB|
|scrambled27426.smt2                                                                        |1200.384s |7717.0MiB|
|scrambled36539.smt2                                                                        |1200.229s |2161.0MiB|
|scrambled94319.smt2                                                                        |1200.211s |1806.0MiB|
|scrambled85895.smt2                                                                        |1200.179s |1341.0MiB|
|scrambled94768.smt2                                                                        |1200.148s |1132.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |332.0MiB|332.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |291.0MiB|291.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |350.0MiB|350.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |16.322GiB|16.322GiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |1097.0MiB|1097.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |307.0MiB|307.0MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |1050.0MiB|1050.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |9643.0MiB|9643.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |14.182GiB|14.182GiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |3833.0MiB|3833.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |393.0MiB|393.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |350.0MiB|350.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |18.575GiB|18.575GiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |7717.0MiB|7717.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |24.932MiB|24.932MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |295.0MiB|295.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |916.0MiB|916.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |332.0MiB|332.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |291.0MiB|291.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |350.0MiB|350.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |16.322GiB|16.322GiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |1097.0MiB|1097.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |307.0MiB|307.0MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |1050.0MiB|1050.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |9643.0MiB|9643.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |14.182GiB|14.182GiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |3833.0MiB|3833.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |393.0MiB|393.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |350.0MiB|350.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |18.575GiB|18.575GiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |7717.0MiB|7717.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |24.932MiB|24.932MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |295.0MiB|295.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |916.0MiB|916.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |332.0MiB|332.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |291.0MiB|291.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |350.0MiB|350.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |16.322GiB|16.322GiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |1097.0MiB|1097.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |307.0MiB|307.0MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |1050.0MiB|1050.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |9643.0MiB|9643.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |14.182GiB|14.182GiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |3833.0MiB|3833.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |393.0MiB|393.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |350.0MiB|350.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |18.575GiB|18.575GiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |7717.0MiB|7717.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |24.932MiB|24.932MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |295.0MiB|295.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |916.0MiB|916.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |332.0MiB|332.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |291.0MiB|291.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |350.0MiB|350.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |16.322GiB|16.322GiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |1097.0MiB|1097.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |307.0MiB|307.0MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |1050.0MiB|1050.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |9643.0MiB|9643.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |14.182GiB|14.182GiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |3833.0MiB|3833.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |393.0MiB|393.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |350.0MiB|350.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |18.575GiB|18.575GiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |7717.0MiB|7717.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |24.932MiB|24.932MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |295.0MiB|295.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |916.0MiB|916.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled5797.smt2                                                                         |1202.044s |24.915GiB|
|scrambled22492.smt2                                                                        |1201.685s |18.575GiB|
|scrambled114923.smt2                                                                       |1201.414s |16.322GiB|
|scrambled124828.smt2                                                                       |1201.245s |14.182GiB|
|scrambled65757.smt2                                                                        |1201.286s |12.829GiB|
|scrambled121780.smt2                                                                       |1200.492s |9643.0MiB|
|scrambled6476.smt2                                                                         |1200.642s |9574.0MiB|
|scrambled27426.smt2                                                                        |1200.384s |7717.0MiB|
|scrambled78428.smt2                                                                        |1200.630s |7342.0MiB|
|scrambled91241.smt2                                                                        |1200.520s |7185.0MiB|
|scrambled58292.smt2                                                                        |1200.670s |6856.0MiB|
|scrambled60239.smt2                                                                        |1200.401s |5686.0MiB|
|scrambled41575.smt2                                                                        |1200.487s |5293.0MiB|
|scrambled70990.smt2                                                                        |1200.545s |4774.0MiB|
|scrambled61896.smt2                                                                        |1200.690s |4737.0MiB|
|scrambled14016.smt2                                                                        |1200.463s |3833.0MiB|
|scrambled36539.smt2                                                                        |1200.229s |2161.0MiB|
|scrambled94319.smt2                                                                        |1200.211s |1806.0MiB|
|scrambled85895.smt2                                                                        |1200.179s |1341.0MiB|
|scrambled94768.smt2                                                                        |1200.148s |1132.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled5797.smt2                                                                         |1202.044s |24.915GiB|
|scrambled22492.smt2                                                                        |1201.685s |18.575GiB|
|scrambled114923.smt2                                                                       |1201.414s |16.322GiB|
|scrambled124828.smt2                                                                       |1201.245s |14.182GiB|
|scrambled65757.smt2                                                                        |1201.286s |12.829GiB|
|scrambled121780.smt2                                                                       |1200.492s |9643.0MiB|
|scrambled6476.smt2                                                                         |1200.642s |9574.0MiB|
|scrambled27426.smt2                                                                        |1200.384s |7717.0MiB|
|scrambled78428.smt2                                                                        |1200.630s |7342.0MiB|
|scrambled91241.smt2                                                                        |1200.520s |7185.0MiB|
|scrambled58292.smt2                                                                        |1200.670s |6856.0MiB|
|scrambled60239.smt2                                                                        |1200.401s |5686.0MiB|
|scrambled41575.smt2                                                                        |1200.487s |5293.0MiB|
|scrambled70990.smt2                                                                        |1200.545s |4774.0MiB|
|scrambled61896.smt2                                                                        |1200.690s |4737.0MiB|
|scrambled14016.smt2                                                                        |1200.463s |3833.0MiB|
|scrambled36539.smt2                                                                        |1200.229s |2161.0MiB|
|scrambled94319.smt2                                                                        |1200.211s |1806.0MiB|
|scrambled85895.smt2                                                                        |1200.179s |1341.0MiB|
|scrambled94768.smt2                                                                        |1200.148s |1132.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1201.414s  |1201.414s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.492s  |1200.492s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1201.245s  |1201.245s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.463s  |1200.463s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |  51.295s  |  51.295s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1201.685s  |1201.685s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.384s  |1200.384s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.138s  |1200.138s  |   0.000s  | 0.0%|
|scrambled34121.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled36539.smt2                                                                         |1200.229s  |1200.229s  |   0.000s  | 0.0%|
|scrambled41575.smt2                                                                         |1200.487s  |1200.487s  |   0.000s  | 0.0%|
|scrambled42946.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled54263.smt2                                                                         |1200.084s  |1200.084s  |   0.000s  | 0.0%|
|scrambled5797.smt2                                                                          |1202.044s  |1202.044s  |   0.000s  | 0.0%|
|scrambled58292.smt2                                                                         |1200.670s  |1200.670s  |   0.000s  | 0.0%|
|scrambled60239.smt2                                                                         |1200.401s  |1200.401s  |   0.000s  | 0.0%|
|scrambled61896.smt2                                                                         |1200.690s  |1200.690s  |   0.000s  | 0.0%|
|scrambled6476.smt2                                                                          |1200.642s  |1200.642s  |   0.000s  | 0.0%|
|scrambled65757.smt2                                                                         |1201.286s  |1201.286s  |   0.000s  | 0.0%|
|scrambled70990.smt2                                                                         |1200.545s  |1200.545s  |   0.000s  | 0.0%|
|scrambled73220.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled74869.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled7586.smt2                                                                          |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled78428.smt2                                                                         |1200.630s  |1200.630s  |   0.000s  | 0.0%|
|scrambled7923.smt2                                                                          |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled80728.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled82241.smt2                                                                         |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled85895.smt2                                                                         |1200.179s  |1200.179s  |   0.000s  | 0.0%|
|scrambled91241.smt2                                                                         |1200.520s  |1200.520s  |   0.000s  | 0.0%|
|scrambled94319.smt2                                                                         |1200.211s  |1200.211s  |   0.000s  | 0.0%|
|scrambled94768.smt2                                                                         |1200.148s  |1200.148s  |   0.000s  | 0.0%|
</details>
