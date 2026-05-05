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
Job tag: Z3-threads-8-smtcomp2025-QF_NRA-timeout20min-bb2-no_default_tactic-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=true smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NRA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NRA-timeout20min-bb2-no_default_tactic-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=true smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NRA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1201.619s  |1201.619s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.183s  |1200.183s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.416s  |1200.416s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.457s  |1200.457s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1201.528s  |1201.528s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1222.154s  |1222.154s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |  51.481s  |  51.481s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1202.807s  |1202.807s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.428s  |1200.428s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1201.619s  |1201.619s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.183s  |1200.183s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.416s  |1200.416s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.457s  |1200.457s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1201.528s  |1201.528s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1222.154s  |1222.154s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |  51.481s  |  51.481s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1202.807s  |1202.807s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.428s  |1200.428s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1201.619s  |1201.619s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.183s  |1200.183s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.416s  |1200.416s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.457s  |1200.457s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1201.528s  |1201.528s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1222.154s  |1222.154s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |  51.481s  |  51.481s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1202.807s  |1202.807s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.428s  |1200.428s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1201.619s  |1201.619s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.183s  |1200.183s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.416s  |1200.416s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.457s  |1200.457s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1201.528s  |1201.528s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1222.154s  |1222.154s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |  51.481s  |  51.481s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1202.807s  |1202.807s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.428s  |1200.428s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled14016.smt2                                                                        |1222.154s |262.0GiB|
|scrambled5797.smt2                                                                         |1203.092s |38.124GiB|
|scrambled22492.smt2                                                                        |1202.807s |33.879GiB|
|scrambled114923.smt2                                                                       |1201.619s |15.167GiB|
|scrambled124828.smt2                                                                       |1201.528s |18.252GiB|
|scrambled70990.smt2                                                                        |1200.687s |4772.0MiB|
|scrambled91241.smt2                                                                        |1200.582s |7185.0MiB|
|scrambled78428.smt2                                                                        |1200.558s |7341.0MiB|
|scrambled6476.smt2                                                                         |1200.516s |9580.0MiB|
|scrambled41575.smt2                                                                        |1200.472s |5273.0MiB|
|scrambled121780.smt2                                                                       |1200.457s |9619.0MiB|
|scrambled65757.smt2                                                                        |1200.435s |3643.0MiB|
|scrambled60239.smt2                                                                        |1200.428s |5684.0MiB|
|scrambled27426.smt2                                                                        |1200.428s |7711.0MiB|
|scrambled118224.smt2                                                                       |1200.416s |3368.0MiB|
|scrambled61896.smt2                                                                        |1200.391s |4362.0MiB|
|scrambled58292.smt2                                                                        |1200.384s |4173.0MiB|
|scrambled36539.smt2                                                                        |1200.289s |2131.0MiB|
|scrambled94319.smt2                                                                        |1200.227s |1829.0MiB|
|scrambled85895.smt2                                                                        |1200.194s |1550.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled14016.smt2                                                                        |1222.154s |262.0GiB|
|scrambled5797.smt2                                                                         |1203.092s |38.124GiB|
|scrambled22492.smt2                                                                        |1202.807s |33.879GiB|
|scrambled114923.smt2                                                                       |1201.619s |15.167GiB|
|scrambled124828.smt2                                                                       |1201.528s |18.252GiB|
|scrambled70990.smt2                                                                        |1200.687s |4772.0MiB|
|scrambled91241.smt2                                                                        |1200.582s |7185.0MiB|
|scrambled78428.smt2                                                                        |1200.558s |7341.0MiB|
|scrambled6476.smt2                                                                         |1200.516s |9580.0MiB|
|scrambled41575.smt2                                                                        |1200.472s |5273.0MiB|
|scrambled121780.smt2                                                                       |1200.457s |9619.0MiB|
|scrambled65757.smt2                                                                        |1200.435s |3643.0MiB|
|scrambled60239.smt2                                                                        |1200.428s |5684.0MiB|
|scrambled27426.smt2                                                                        |1200.428s |7711.0MiB|
|scrambled118224.smt2                                                                       |1200.416s |3368.0MiB|
|scrambled61896.smt2                                                                        |1200.391s |4362.0MiB|
|scrambled58292.smt2                                                                        |1200.384s |4173.0MiB|
|scrambled36539.smt2                                                                        |1200.289s |2131.0MiB|
|scrambled94319.smt2                                                                        |1200.227s |1829.0MiB|
|scrambled85895.smt2                                                                        |1200.194s |1550.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |436.0MiB|436.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |298.0MiB|298.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |330.0MiB|330.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |15.167GiB|15.167GiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |1192.0MiB|1192.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |742.0MiB|742.0MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |3368.0MiB|3368.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |9619.0MiB|9619.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |18.252GiB|18.252GiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |262.0GiB|262.0GiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |289.0MiB|289.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |399.0MiB|399.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |355.0MiB|355.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |33.879GiB|33.879GiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |7711.0MiB|7711.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |323.0MiB|323.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |24.812MiB|24.812MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |301.0MiB|301.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |868.0MiB|868.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |436.0MiB|436.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |298.0MiB|298.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |330.0MiB|330.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |15.167GiB|15.167GiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |1192.0MiB|1192.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |742.0MiB|742.0MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |3368.0MiB|3368.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |9619.0MiB|9619.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |18.252GiB|18.252GiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |262.0GiB|262.0GiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |289.0MiB|289.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |399.0MiB|399.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |355.0MiB|355.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |33.879GiB|33.879GiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |7711.0MiB|7711.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |323.0MiB|323.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |24.812MiB|24.812MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |301.0MiB|301.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |868.0MiB|868.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |436.0MiB|436.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |298.0MiB|298.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |330.0MiB|330.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |15.167GiB|15.167GiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |1192.0MiB|1192.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |742.0MiB|742.0MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |3368.0MiB|3368.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |9619.0MiB|9619.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |18.252GiB|18.252GiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |262.0GiB|262.0GiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |289.0MiB|289.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |399.0MiB|399.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |355.0MiB|355.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |33.879GiB|33.879GiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |7711.0MiB|7711.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |323.0MiB|323.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |24.812MiB|24.812MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |301.0MiB|301.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |868.0MiB|868.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |436.0MiB|436.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |298.0MiB|298.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |330.0MiB|330.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |15.167GiB|15.167GiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |1192.0MiB|1192.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |742.0MiB|742.0MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |3368.0MiB|3368.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |9619.0MiB|9619.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |18.252GiB|18.252GiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |262.0GiB|262.0GiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |289.0MiB|289.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |399.0MiB|399.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |355.0MiB|355.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |33.879GiB|33.879GiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |7711.0MiB|7711.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |323.0MiB|323.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |24.812MiB|24.812MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |301.0MiB|301.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |868.0MiB|868.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled14016.smt2                                                                        |1222.154s |262.0GiB|
|scrambled5797.smt2                                                                         |1203.092s |38.124GiB|
|scrambled22492.smt2                                                                        |1202.807s |33.879GiB|
|scrambled124828.smt2                                                                       |1201.528s |18.252GiB|
|scrambled114923.smt2                                                                       |1201.619s |15.167GiB|
|scrambled121780.smt2                                                                       |1200.457s |9619.0MiB|
|scrambled6476.smt2                                                                         |1200.516s |9580.0MiB|
|scrambled27426.smt2                                                                        |1200.428s |7711.0MiB|
|scrambled78428.smt2                                                                        |1200.558s |7341.0MiB|
|scrambled91241.smt2                                                                        |1200.582s |7185.0MiB|
|scrambled60239.smt2                                                                        |1200.428s |5684.0MiB|
|scrambled41575.smt2                                                                        |1200.472s |5273.0MiB|
|scrambled70990.smt2                                                                        |1200.687s |4772.0MiB|
|scrambled61896.smt2                                                                        |1200.391s |4362.0MiB|
|scrambled58292.smt2                                                                        |1200.384s |4173.0MiB|
|scrambled65757.smt2                                                                        |1200.435s |3643.0MiB|
|scrambled118224.smt2                                                                       |1200.416s |3368.0MiB|
|scrambled36539.smt2                                                                        |1200.289s |2131.0MiB|
|scrambled94319.smt2                                                                        |1200.227s |1829.0MiB|
|scrambled85895.smt2                                                                        |1200.194s |1550.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled14016.smt2                                                                        |1222.154s |262.0GiB|
|scrambled5797.smt2                                                                         |1203.092s |38.124GiB|
|scrambled22492.smt2                                                                        |1202.807s |33.879GiB|
|scrambled124828.smt2                                                                       |1201.528s |18.252GiB|
|scrambled114923.smt2                                                                       |1201.619s |15.167GiB|
|scrambled121780.smt2                                                                       |1200.457s |9619.0MiB|
|scrambled6476.smt2                                                                         |1200.516s |9580.0MiB|
|scrambled27426.smt2                                                                        |1200.428s |7711.0MiB|
|scrambled78428.smt2                                                                        |1200.558s |7341.0MiB|
|scrambled91241.smt2                                                                        |1200.582s |7185.0MiB|
|scrambled60239.smt2                                                                        |1200.428s |5684.0MiB|
|scrambled41575.smt2                                                                        |1200.472s |5273.0MiB|
|scrambled70990.smt2                                                                        |1200.687s |4772.0MiB|
|scrambled61896.smt2                                                                        |1200.391s |4362.0MiB|
|scrambled58292.smt2                                                                        |1200.384s |4173.0MiB|
|scrambled65757.smt2                                                                        |1200.435s |3643.0MiB|
|scrambled118224.smt2                                                                       |1200.416s |3368.0MiB|
|scrambled36539.smt2                                                                        |1200.289s |2131.0MiB|
|scrambled94319.smt2                                                                        |1200.227s |1829.0MiB|
|scrambled85895.smt2                                                                        |1200.194s |1550.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1201.619s  |1201.619s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.183s  |1200.183s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.416s  |1200.416s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.457s  |1200.457s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1201.528s  |1201.528s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1222.154s  |1222.154s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |  51.481s  |  51.481s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1202.807s  |1202.807s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.428s  |1200.428s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled34121.smt2                                                                         |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled36539.smt2                                                                         |1200.289s  |1200.289s  |   0.000s  | 0.0%|
|scrambled41575.smt2                                                                         |1200.472s  |1200.472s  |   0.000s  | 0.0%|
|scrambled42946.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled54263.smt2                                                                         |1200.081s  |1200.081s  |   0.000s  | 0.0%|
|scrambled5797.smt2                                                                          |1203.092s  |1203.092s  |   0.000s  | 0.0%|
|scrambled58292.smt2                                                                         |1200.384s  |1200.384s  |   0.000s  | 0.0%|
|scrambled60239.smt2                                                                         |1200.428s  |1200.428s  |   0.000s  | 0.0%|
|scrambled61896.smt2                                                                         |1200.391s  |1200.391s  |   0.000s  | 0.0%|
|scrambled6476.smt2                                                                          |1200.516s  |1200.516s  |   0.000s  | 0.0%|
|scrambled65757.smt2                                                                         |1200.435s  |1200.435s  |   0.000s  | 0.0%|
|scrambled70990.smt2                                                                         |1200.687s  |1200.687s  |   0.000s  | 0.0%|
|scrambled73220.smt2                                                                         |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled74869.smt2                                                                         |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled7586.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled78428.smt2                                                                         |1200.558s  |1200.558s  |   0.000s  | 0.0%|
|scrambled7923.smt2                                                                          |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled80728.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled82241.smt2                                                                         |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled85895.smt2                                                                         |1200.194s  |1200.194s  |   0.000s  | 0.0%|
|scrambled91241.smt2                                                                         |1200.582s  |1200.582s  |   0.000s  | 0.0%|
|scrambled94319.smt2                                                                         |1200.227s  |1200.227s  |   0.000s  | 0.0%|
|scrambled94768.smt2                                                                         |1200.080s  |1200.080s  |   0.000s  | 0.0%|
</details>
