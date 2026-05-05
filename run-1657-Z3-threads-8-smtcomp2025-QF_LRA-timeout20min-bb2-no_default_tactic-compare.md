Comparing data and data


# SUMMARY
- LHS tests = 38
- RHS tests = 38
- LHS success = 38  (100.0%)
- RHS success = 38  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LRA-timeout20min-bb2-no_default_tactic
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LRA-timeout20min-bb2-no_default_tactic
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 51b65dd20e8f6976ead894f2a5db45cce220ca6c
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.504s  |1201.504s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.506s  |1201.506s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1201.333s  |1201.333s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.620s  |1200.620s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1202.383s  |1202.383s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.111s  |1200.111s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1079.224s  |1079.224s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 104.693s  | 104.693s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.539s  |1200.539s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.051s  |1201.051s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.041s  |1202.041s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.136s  |1201.136s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.780s  |1200.780s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.504s  |1201.504s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.506s  |1201.506s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1201.333s  |1201.333s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.620s  |1200.620s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1202.383s  |1202.383s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.111s  |1200.111s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1079.224s  |1079.224s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 104.693s  | 104.693s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.539s  |1200.539s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.051s  |1201.051s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.041s  |1202.041s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.136s  |1201.136s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.780s  |1200.780s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.504s  |1201.504s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.506s  |1201.506s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1201.333s  |1201.333s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.620s  |1200.620s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1202.383s  |1202.383s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.111s  |1200.111s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1079.224s  |1079.224s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 104.693s  | 104.693s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.539s  |1200.539s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.051s  |1201.051s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.041s  |1202.041s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.136s  |1201.136s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.780s  |1200.780s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.504s  |1201.504s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.506s  |1201.506s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1201.333s  |1201.333s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.620s  |1200.620s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1202.383s  |1202.383s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.111s  |1200.111s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1079.224s  |1079.224s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 104.693s  | 104.693s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.539s  |1200.539s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.051s  |1201.051s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.041s  |1202.041s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.136s  |1201.136s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.780s  |1200.780s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled111949.smt2                                                                       |1202.383s |16.061GiB|
|scrambled13209.smt2                                                                        |1202.041s |21.067GiB|
|scrambled98986.smt2                                                                        |1201.687s |10.876GiB|
|scrambled102621.smt2                                                                       |1201.506s |11.457GiB|
|scrambled101728.smt2                                                                       |1201.504s |10.054GiB|
|scrambled102680.smt2                                                                       |1201.333s |13.256GiB|
|scrambled25695.smt2                                                                        |1201.136s |11.231GiB|
|scrambled8163.smt2                                                                         |1201.088s |11.264GiB|
|scrambled13169.smt2                                                                        |1201.051s |11.659GiB|
|scrambled55850.smt2                                                                        |1201.012s |10.455GiB|
|scrambled37260.smt2                                                                        |1200.780s |6465.0MiB|
|scrambled77008.smt2                                                                        |1200.729s |6275.0MiB|
|scrambled109307.smt2                                                                       |1200.620s |6013.0MiB|
|scrambled124455.smt2                                                                       |1200.539s |4175.0MiB|
|scrambled59368.smt2                                                                        |1200.517s |2863.0MiB|
|scrambled95284.smt2                                                                        |1200.443s |3580.0MiB|
|scrambled47581.smt2                                                                        |1200.423s |3158.0MiB|
|scrambled76525.smt2                                                                        |1200.412s |3092.0MiB|
|scrambled17583.smt2                                                                        |1200.319s |2959.0MiB|
|scrambled55845.smt2                                                                        |1200.218s |1632.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled111949.smt2                                                                       |1202.383s |16.061GiB|
|scrambled13209.smt2                                                                        |1202.041s |21.067GiB|
|scrambled98986.smt2                                                                        |1201.687s |10.876GiB|
|scrambled102621.smt2                                                                       |1201.506s |11.457GiB|
|scrambled101728.smt2                                                                       |1201.504s |10.054GiB|
|scrambled102680.smt2                                                                       |1201.333s |13.256GiB|
|scrambled25695.smt2                                                                        |1201.136s |11.231GiB|
|scrambled8163.smt2                                                                         |1201.088s |11.264GiB|
|scrambled13169.smt2                                                                        |1201.051s |11.659GiB|
|scrambled55850.smt2                                                                        |1201.012s |10.455GiB|
|scrambled37260.smt2                                                                        |1200.780s |6465.0MiB|
|scrambled77008.smt2                                                                        |1200.729s |6275.0MiB|
|scrambled109307.smt2                                                                       |1200.620s |6013.0MiB|
|scrambled124455.smt2                                                                       |1200.539s |4175.0MiB|
|scrambled59368.smt2                                                                        |1200.517s |2863.0MiB|
|scrambled95284.smt2                                                                        |1200.443s |3580.0MiB|
|scrambled47581.smt2                                                                        |1200.423s |3158.0MiB|
|scrambled76525.smt2                                                                        |1200.412s |3092.0MiB|
|scrambled17583.smt2                                                                        |1200.319s |2959.0MiB|
|scrambled55845.smt2                                                                        |1200.218s |1632.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |574.0MiB|574.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |10.054GiB|10.054GiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |11.457GiB|11.457GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |13.256GiB|13.256GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |296.0MiB|296.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |376.0MiB|376.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |6013.0MiB|6013.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |16.061GiB|16.061GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |6854.0MiB|6854.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |509.0MiB|509.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |4175.0MiB|4175.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |11.659GiB|11.659GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |21.067GiB|21.067GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2959.0MiB|2959.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |11.231GiB|11.231GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |479.0MiB|479.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |605.0MiB|605.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |6465.0MiB|6465.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |574.0MiB|574.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |10.054GiB|10.054GiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |11.457GiB|11.457GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |13.256GiB|13.256GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |296.0MiB|296.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |376.0MiB|376.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |6013.0MiB|6013.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |16.061GiB|16.061GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |6854.0MiB|6854.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |509.0MiB|509.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |4175.0MiB|4175.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |11.659GiB|11.659GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |21.067GiB|21.067GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2959.0MiB|2959.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |11.231GiB|11.231GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |479.0MiB|479.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |605.0MiB|605.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |6465.0MiB|6465.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |574.0MiB|574.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |10.054GiB|10.054GiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |11.457GiB|11.457GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |13.256GiB|13.256GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |296.0MiB|296.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |376.0MiB|376.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |6013.0MiB|6013.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |16.061GiB|16.061GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |6854.0MiB|6854.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |509.0MiB|509.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |4175.0MiB|4175.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |11.659GiB|11.659GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |21.067GiB|21.067GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2959.0MiB|2959.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |11.231GiB|11.231GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |479.0MiB|479.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |605.0MiB|605.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |6465.0MiB|6465.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |574.0MiB|574.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |10.054GiB|10.054GiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |11.457GiB|11.457GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |13.256GiB|13.256GiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |296.0MiB|296.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |376.0MiB|376.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |6013.0MiB|6013.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |16.061GiB|16.061GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |586.0MiB|586.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |6854.0MiB|6854.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |509.0MiB|509.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |4175.0MiB|4175.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |305.0MiB|305.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |11.659GiB|11.659GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |21.067GiB|21.067GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2959.0MiB|2959.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |11.231GiB|11.231GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |479.0MiB|479.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |605.0MiB|605.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |6465.0MiB|6465.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1202.041s |21.067GiB|
|scrambled111949.smt2                                                                       |1202.383s |16.061GiB|
|scrambled102680.smt2                                                                       |1201.333s |13.256GiB|
|scrambled44527.smt2                                                                        | 422.766s |12.532GiB|
|scrambled13169.smt2                                                                        |1201.051s |11.659GiB|
|scrambled102621.smt2                                                                       |1201.506s |11.457GiB|
|scrambled8163.smt2                                                                         |1201.088s |11.264GiB|
|scrambled25695.smt2                                                                        |1201.136s |11.231GiB|
|scrambled98986.smt2                                                                        |1201.687s |10.876GiB|
|scrambled55850.smt2                                                                        |1201.012s |10.455GiB|
|scrambled101728.smt2                                                                       |1201.504s |10.054GiB|
|scrambled117897.smt2                                                                       |1079.224s |6854.0MiB|
|scrambled37260.smt2                                                                        |1200.780s |6465.0MiB|
|scrambled77008.smt2                                                                        |1200.729s |6275.0MiB|
|scrambled109307.smt2                                                                       |1200.620s |6013.0MiB|
|scrambled124455.smt2                                                                       |1200.539s |4175.0MiB|
|scrambled95284.smt2                                                                        |1200.443s |3580.0MiB|
|scrambled47581.smt2                                                                        |1200.423s |3158.0MiB|
|scrambled76525.smt2                                                                        |1200.412s |3092.0MiB|
|scrambled17583.smt2                                                                        |1200.319s |2959.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1202.041s |21.067GiB|
|scrambled111949.smt2                                                                       |1202.383s |16.061GiB|
|scrambled102680.smt2                                                                       |1201.333s |13.256GiB|
|scrambled44527.smt2                                                                        | 422.766s |12.532GiB|
|scrambled13169.smt2                                                                        |1201.051s |11.659GiB|
|scrambled102621.smt2                                                                       |1201.506s |11.457GiB|
|scrambled8163.smt2                                                                         |1201.088s |11.264GiB|
|scrambled25695.smt2                                                                        |1201.136s |11.231GiB|
|scrambled98986.smt2                                                                        |1201.687s |10.876GiB|
|scrambled55850.smt2                                                                        |1201.012s |10.455GiB|
|scrambled101728.smt2                                                                       |1201.504s |10.054GiB|
|scrambled117897.smt2                                                                       |1079.224s |6854.0MiB|
|scrambled37260.smt2                                                                        |1200.780s |6465.0MiB|
|scrambled77008.smt2                                                                        |1200.729s |6275.0MiB|
|scrambled109307.smt2                                                                       |1200.620s |6013.0MiB|
|scrambled124455.smt2                                                                       |1200.539s |4175.0MiB|
|scrambled95284.smt2                                                                        |1200.443s |3580.0MiB|
|scrambled47581.smt2                                                                        |1200.423s |3158.0MiB|
|scrambled76525.smt2                                                                        |1200.412s |3092.0MiB|
|scrambled17583.smt2                                                                        |1200.319s |2959.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1201.504s  |1201.504s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1201.506s  |1201.506s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1201.333s  |1201.333s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.620s  |1200.620s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1202.383s  |1202.383s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.111s  |1200.111s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1079.224s  |1079.224s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 104.693s  | 104.693s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.539s  |1200.539s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1201.051s  |1201.051s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1202.041s  |1202.041s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.319s  |1200.319s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1201.136s  |1201.136s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.780s  |1200.780s  |   0.000s  | 0.0%|
|scrambled44527.smt2                                                                         | 422.766s  | 422.766s  |   0.000s  | 0.0%|
|scrambled46192.smt2                                                                         |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled47581.smt2                                                                         |1200.423s  |1200.423s  |   0.000s  | 0.0%|
|scrambled49820.smt2                                                                         |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled55845.smt2                                                                         |1200.218s  |1200.218s  |   0.000s  | 0.0%|
|scrambled55850.smt2                                                                         |1201.012s  |1201.012s  |   0.000s  | 0.0%|
|scrambled59368.smt2                                                                         |1200.517s  |1200.517s  |   0.000s  | 0.0%|
|scrambled65517.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled71015.smt2                                                                         |1200.164s  |1200.164s  |   0.000s  | 0.0%|
|scrambled76525.smt2                                                                         |1200.412s  |1200.412s  |   0.000s  | 0.0%|
|scrambled76532.smt2                                                                         |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled77008.smt2                                                                         |1200.729s  |1200.729s  |   0.000s  | 0.0%|
|scrambled77308.smt2                                                                         |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled8163.smt2                                                                          |1201.088s  |1201.088s  |   0.000s  | 0.0%|
|scrambled88927.smt2                                                                         |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled92964.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled95284.smt2                                                                         |1200.443s  |1200.443s  |   0.000s  | 0.0%|
</details>
