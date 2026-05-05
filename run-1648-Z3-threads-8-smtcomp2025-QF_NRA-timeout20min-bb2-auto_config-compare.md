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
Job tag: Z3-threads-8-smtcomp2025-QF_NRA-timeout20min-bb2-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=true smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NRA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NRA-timeout20min-bb2-auto_config
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=true smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NRA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1201.643s  |1201.643s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.573s  |1200.573s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.479s  |1200.479s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1202.609s  |1202.609s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   1.160s  |   1.160s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1201.883s  |1201.883s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.394s  |1200.394s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |  49.448s  |  49.448s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1201.643s  |1201.643s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.573s  |1200.573s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.479s  |1200.479s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1202.609s  |1202.609s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   1.160s  |   1.160s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1201.883s  |1201.883s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.394s  |1200.394s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |  49.448s  |  49.448s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1201.643s  |1201.643s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.573s  |1200.573s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.479s  |1200.479s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1202.609s  |1202.609s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   1.160s  |   1.160s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1201.883s  |1201.883s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.394s  |1200.394s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |  49.448s  |  49.448s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1201.643s  |1201.643s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.573s  |1200.573s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.479s  |1200.479s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1202.609s  |1202.609s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   1.160s  |   1.160s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1201.883s  |1201.883s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.394s  |1200.394s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |  49.448s  |  49.448s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled5797.smt2                                                                         |1207.376s |85.716GiB|
|scrambled14016.smt2                                                                        |1202.609s |25.913GiB|
|scrambled22492.smt2                                                                        |1201.883s |20.329GiB|
|scrambled114923.smt2                                                                       |1201.643s |17.476GiB|
|scrambled91241.smt2                                                                        |1200.946s |7176.0MiB|
|scrambled78428.smt2                                                                        |1200.716s |7126.0MiB|
|scrambled6476.smt2                                                                         |1200.666s |9527.0MiB|
|scrambled121780.smt2                                                                       |1200.573s |9568.0MiB|
|scrambled60239.smt2                                                                        |1200.526s |5433.0MiB|
|scrambled124828.smt2                                                                       |1200.479s |3760.0MiB|
|scrambled61896.smt2                                                                        |1200.473s |5023.0MiB|
|scrambled41575.smt2                                                                        |1200.462s |4863.0MiB|
|scrambled70990.smt2                                                                        |1200.447s |4602.0MiB|
|scrambled27426.smt2                                                                        |1200.394s |7436.0MiB|
|scrambled65757.smt2                                                                        |1200.388s |3719.0MiB|
|scrambled94319.smt2                                                                        |1200.225s |2113.0MiB|
|scrambled85895.smt2                                                                        |1200.211s |1596.0MiB|
|scrambled58292.smt2                                                                        |1200.201s |1416.0MiB|
|scrambled32701.smt2                                                                        |1200.140s |881.0MiB|
|scrambled99534.smt2                                                                        |1200.089s |436.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled5797.smt2                                                                         |1207.376s |85.716GiB|
|scrambled14016.smt2                                                                        |1202.609s |25.913GiB|
|scrambled22492.smt2                                                                        |1201.883s |20.329GiB|
|scrambled114923.smt2                                                                       |1201.643s |17.476GiB|
|scrambled91241.smt2                                                                        |1200.946s |7176.0MiB|
|scrambled78428.smt2                                                                        |1200.716s |7126.0MiB|
|scrambled6476.smt2                                                                         |1200.666s |9527.0MiB|
|scrambled121780.smt2                                                                       |1200.573s |9568.0MiB|
|scrambled60239.smt2                                                                        |1200.526s |5433.0MiB|
|scrambled124828.smt2                                                                       |1200.479s |3760.0MiB|
|scrambled61896.smt2                                                                        |1200.473s |5023.0MiB|
|scrambled41575.smt2                                                                        |1200.462s |4863.0MiB|
|scrambled70990.smt2                                                                        |1200.447s |4602.0MiB|
|scrambled27426.smt2                                                                        |1200.394s |7436.0MiB|
|scrambled65757.smt2                                                                        |1200.388s |3719.0MiB|
|scrambled94319.smt2                                                                        |1200.225s |2113.0MiB|
|scrambled85895.smt2                                                                        |1200.211s |1596.0MiB|
|scrambled58292.smt2                                                                        |1200.201s |1416.0MiB|
|scrambled32701.smt2                                                                        |1200.140s |881.0MiB|
|scrambled99534.smt2                                                                        |1200.089s |436.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |334.0MiB|334.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |349.0MiB|349.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |325.0MiB|325.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |17.476GiB|17.476GiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |357.0MiB|357.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |327.0MiB|327.0MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |468.0MiB|468.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |9568.0MiB|9568.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |3760.0MiB|3760.0MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |25.913GiB|25.913GiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |347.0MiB|347.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |20.329GiB|20.329GiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |7436.0MiB|7436.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |273.0MiB|273.0MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |881.0MiB|881.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |334.0MiB|334.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |349.0MiB|349.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |325.0MiB|325.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |17.476GiB|17.476GiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |357.0MiB|357.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |327.0MiB|327.0MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |468.0MiB|468.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |9568.0MiB|9568.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |3760.0MiB|3760.0MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |25.913GiB|25.913GiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |347.0MiB|347.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |20.329GiB|20.329GiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |7436.0MiB|7436.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |273.0MiB|273.0MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |881.0MiB|881.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |334.0MiB|334.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |349.0MiB|349.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |325.0MiB|325.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |17.476GiB|17.476GiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |357.0MiB|357.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |327.0MiB|327.0MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |468.0MiB|468.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |9568.0MiB|9568.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |3760.0MiB|3760.0MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |25.913GiB|25.913GiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |347.0MiB|347.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |20.329GiB|20.329GiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |7436.0MiB|7436.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |273.0MiB|273.0MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |881.0MiB|881.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |334.0MiB|334.0MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |349.0MiB|349.0MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |325.0MiB|325.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |17.476GiB|17.476GiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |357.0MiB|357.0MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |327.0MiB|327.0MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |468.0MiB|468.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |9568.0MiB|9568.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |3760.0MiB|3760.0MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |25.913GiB|25.913GiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |347.0MiB|347.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |20.329GiB|20.329GiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |7436.0MiB|7436.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |309.0MiB|309.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |273.0MiB|273.0MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |881.0MiB|881.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled5797.smt2                                                                         |1207.376s |85.716GiB|
|scrambled14016.smt2                                                                        |1202.609s |25.913GiB|
|scrambled22492.smt2                                                                        |1201.883s |20.329GiB|
|scrambled114923.smt2                                                                       |1201.643s |17.476GiB|
|scrambled121780.smt2                                                                       |1200.573s |9568.0MiB|
|scrambled6476.smt2                                                                         |1200.666s |9527.0MiB|
|scrambled27426.smt2                                                                        |1200.394s |7436.0MiB|
|scrambled91241.smt2                                                                        |1200.946s |7176.0MiB|
|scrambled78428.smt2                                                                        |1200.716s |7126.0MiB|
|scrambled60239.smt2                                                                        |1200.526s |5433.0MiB|
|scrambled61896.smt2                                                                        |1200.473s |5023.0MiB|
|scrambled41575.smt2                                                                        |1200.462s |4863.0MiB|
|scrambled70990.smt2                                                                        |1200.447s |4602.0MiB|
|scrambled124828.smt2                                                                       |1200.479s |3760.0MiB|
|scrambled65757.smt2                                                                        |1200.388s |3719.0MiB|
|scrambled94319.smt2                                                                        |1200.225s |2113.0MiB|
|scrambled85895.smt2                                                                        |1200.211s |1596.0MiB|
|scrambled58292.smt2                                                                        |1200.201s |1416.0MiB|
|scrambled32701.smt2                                                                        |1200.140s |881.0MiB|
|scrambled73220.smt2                                                                        |1200.077s |562.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled5797.smt2                                                                         |1207.376s |85.716GiB|
|scrambled14016.smt2                                                                        |1202.609s |25.913GiB|
|scrambled22492.smt2                                                                        |1201.883s |20.329GiB|
|scrambled114923.smt2                                                                       |1201.643s |17.476GiB|
|scrambled121780.smt2                                                                       |1200.573s |9568.0MiB|
|scrambled6476.smt2                                                                         |1200.666s |9527.0MiB|
|scrambled27426.smt2                                                                        |1200.394s |7436.0MiB|
|scrambled91241.smt2                                                                        |1200.946s |7176.0MiB|
|scrambled78428.smt2                                                                        |1200.716s |7126.0MiB|
|scrambled60239.smt2                                                                        |1200.526s |5433.0MiB|
|scrambled61896.smt2                                                                        |1200.473s |5023.0MiB|
|scrambled41575.smt2                                                                        |1200.462s |4863.0MiB|
|scrambled70990.smt2                                                                        |1200.447s |4602.0MiB|
|scrambled124828.smt2                                                                       |1200.479s |3760.0MiB|
|scrambled65757.smt2                                                                        |1200.388s |3719.0MiB|
|scrambled94319.smt2                                                                        |1200.225s |2113.0MiB|
|scrambled85895.smt2                                                                        |1200.211s |1596.0MiB|
|scrambled58292.smt2                                                                        |1200.201s |1416.0MiB|
|scrambled32701.smt2                                                                        |1200.140s |881.0MiB|
|scrambled73220.smt2                                                                        |1200.077s |562.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1201.643s  |1201.643s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.573s  |1200.573s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.479s  |1200.479s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1202.609s  |1202.609s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |   1.160s  |   1.160s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1201.883s  |1201.883s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.394s  |1200.394s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |  49.448s  |  49.448s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled34121.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled36539.smt2                                                                         |   1.570s  |   1.570s  |   0.000s  | 0.0%|
|scrambled41575.smt2                                                                         |1200.462s  |1200.462s  |   0.000s  | 0.0%|
|scrambled42946.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled54263.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled5797.smt2                                                                          |1207.376s  |1207.376s  |   0.000s  | 0.0%|
|scrambled58292.smt2                                                                         |1200.201s  |1200.201s  |   0.000s  | 0.0%|
|scrambled60239.smt2                                                                         |1200.526s  |1200.526s  |   0.000s  | 0.0%|
|scrambled61896.smt2                                                                         |1200.473s  |1200.473s  |   0.000s  | 0.0%|
|scrambled6476.smt2                                                                          |1200.666s  |1200.666s  |   0.000s  | 0.0%|
|scrambled65757.smt2                                                                         |1200.388s  |1200.388s  |   0.000s  | 0.0%|
|scrambled70990.smt2                                                                         |1200.447s  |1200.447s  |   0.000s  | 0.0%|
|scrambled73220.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled74869.smt2                                                                         |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled7586.smt2                                                                          |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled78428.smt2                                                                         |1200.716s  |1200.716s  |   0.000s  | 0.0%|
|scrambled7923.smt2                                                                          |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled80728.smt2                                                                         |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled82241.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled85895.smt2                                                                         |1200.211s  |1200.211s  |   0.000s  | 0.0%|
|scrambled91241.smt2                                                                         |1200.946s  |1200.946s  |   0.000s  | 0.0%|
|scrambled94319.smt2                                                                         |1200.225s  |1200.225s  |   0.000s  | 0.0%|
|scrambled94768.smt2                                                                         |1200.075s  |1200.075s  |   0.000s  | 0.0%|
</details>
