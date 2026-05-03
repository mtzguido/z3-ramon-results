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
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-8-mode-partition-smtcomp2025-QF_LRA-timeout20min
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: partition
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter decision-cube"
cvc5 partition budget: 8
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 8
cvc5 timeout: 1200
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_LRA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-8-mode-partition-smtcomp2025-QF_LRA-timeout20min
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: partition
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter decision-cube"
cvc5 partition budget: 8
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 8
cvc5 timeout: 1200
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_LRA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1199.656s  |1199.656s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1199.741s  |1199.741s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.407s  |1200.407s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1199.909s  |1199.909s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.511s  |1200.511s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1199.960s  |1199.960s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1199.993s  |1199.993s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1199.836s  |1199.836s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 616.165s  | 616.165s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.506s  |1200.506s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.211s  |1200.211s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.262s  |1200.262s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1199.893s  |1199.893s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1199.527s  |1199.527s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1199.838s  |1199.838s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1199.656s  |1199.656s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1199.741s  |1199.741s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.407s  |1200.407s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1199.909s  |1199.909s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.511s  |1200.511s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1199.960s  |1199.960s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1199.993s  |1199.993s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1199.836s  |1199.836s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 616.165s  | 616.165s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.506s  |1200.506s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.211s  |1200.211s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.262s  |1200.262s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1199.893s  |1199.893s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1199.527s  |1199.527s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1199.838s  |1199.838s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1199.656s  |1199.656s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1199.741s  |1199.741s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.407s  |1200.407s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1199.909s  |1199.909s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.511s  |1200.511s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1199.960s  |1199.960s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1199.993s  |1199.993s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1199.836s  |1199.836s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 616.165s  | 616.165s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.506s  |1200.506s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.211s  |1200.211s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.262s  |1200.262s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1199.893s  |1199.893s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1199.527s  |1199.527s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1199.838s  |1199.838s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1199.656s  |1199.656s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1199.741s  |1199.741s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.407s  |1200.407s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1199.909s  |1199.909s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.511s  |1200.511s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1199.960s  |1199.960s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1199.993s  |1199.993s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1199.836s  |1199.836s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 616.165s  | 616.165s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.506s  |1200.506s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.211s  |1200.211s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.262s  |1200.262s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1199.893s  |1199.893s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1199.527s  |1199.527s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1199.838s  |1199.838s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled104811.smt2                                                                       |1200.511s |11.554GiB|
|scrambled13169.smt2                                                                        |1200.506s |6546.0MiB|
|scrambled102680.smt2                                                                       |1200.407s |5296.0MiB|
|scrambled77308.smt2                                                                        |1200.369s |11.639GiB|
|scrambled65517.smt2                                                                        |1200.333s |4859.0MiB|
|scrambled25695.smt2                                                                        |1200.262s |8622.0MiB|
|scrambled55850.smt2                                                                        |1200.255s |4651.0MiB|
|scrambled13209.smt2                                                                        |1200.211s |7805.0MiB|
|scrambled109307.smt2                                                                       |1200.191s |2374.0MiB|
|scrambled98986.smt2                                                                        |1200.141s |5470.0MiB|
|scrambled92964.smt2                                                                        |1200.094s |1721.0MiB|
|scrambled17583.smt2                                                                        |1200.040s |1622.0MiB|
|scrambled124681.smt2                                                                       |1200.032s |867.0MiB|
|scrambled101086.smt2                                                                       |1200.031s |804.0MiB|
|scrambled124455.smt2                                                                       |1200.027s |2555.0MiB|
|scrambled55845.smt2                                                                        |1200.009s |1809.0MiB|
|scrambled115671.smt2                                                                       |1199.993s |575.0MiB|
|scrambled76525.smt2                                                                        |1199.985s |2153.0MiB|
|scrambled111949.smt2                                                                       |1199.960s |5861.0MiB|
|scrambled95284.smt2                                                                        |1199.920s |2689.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled104811.smt2                                                                       |1200.511s |11.554GiB|
|scrambled13169.smt2                                                                        |1200.506s |6546.0MiB|
|scrambled102680.smt2                                                                       |1200.407s |5296.0MiB|
|scrambled77308.smt2                                                                        |1200.369s |11.639GiB|
|scrambled65517.smt2                                                                        |1200.333s |4859.0MiB|
|scrambled25695.smt2                                                                        |1200.262s |8622.0MiB|
|scrambled55850.smt2                                                                        |1200.255s |4651.0MiB|
|scrambled13209.smt2                                                                        |1200.211s |7805.0MiB|
|scrambled109307.smt2                                                                       |1200.191s |2374.0MiB|
|scrambled98986.smt2                                                                        |1200.141s |5470.0MiB|
|scrambled92964.smt2                                                                        |1200.094s |1721.0MiB|
|scrambled17583.smt2                                                                        |1200.040s |1622.0MiB|
|scrambled124681.smt2                                                                       |1200.032s |867.0MiB|
|scrambled101086.smt2                                                                       |1200.031s |804.0MiB|
|scrambled124455.smt2                                                                       |1200.027s |2555.0MiB|
|scrambled55845.smt2                                                                        |1200.009s |1809.0MiB|
|scrambled115671.smt2                                                                       |1199.993s |575.0MiB|
|scrambled76525.smt2                                                                        |1199.985s |2153.0MiB|
|scrambled111949.smt2                                                                       |1199.960s |5861.0MiB|
|scrambled95284.smt2                                                                        |1199.920s |2689.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |804.0MiB|804.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |2598.0MiB|2598.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |6809.0MiB|6809.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |5296.0MiB|5296.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |1509.0MiB|1509.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |11.554GiB|11.554GiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |2374.0MiB|2374.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |5861.0MiB|5861.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |575.0MiB|575.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |2723.0MiB|2723.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |657.0MiB|657.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |2555.0MiB|2555.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |867.0MiB|867.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |6546.0MiB|6546.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |7805.0MiB|7805.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |1622.0MiB|1622.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |8622.0MiB|8622.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1767.0MiB|1767.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |401.0MiB|401.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |2597.0MiB|2597.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |804.0MiB|804.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |2598.0MiB|2598.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |6809.0MiB|6809.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |5296.0MiB|5296.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |1509.0MiB|1509.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |11.554GiB|11.554GiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |2374.0MiB|2374.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |5861.0MiB|5861.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |575.0MiB|575.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |2723.0MiB|2723.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |657.0MiB|657.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |2555.0MiB|2555.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |867.0MiB|867.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |6546.0MiB|6546.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |7805.0MiB|7805.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |1622.0MiB|1622.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |8622.0MiB|8622.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1767.0MiB|1767.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |401.0MiB|401.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |2597.0MiB|2597.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |804.0MiB|804.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |2598.0MiB|2598.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |6809.0MiB|6809.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |5296.0MiB|5296.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |1509.0MiB|1509.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |11.554GiB|11.554GiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |2374.0MiB|2374.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |5861.0MiB|5861.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |575.0MiB|575.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |2723.0MiB|2723.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |657.0MiB|657.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |2555.0MiB|2555.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |867.0MiB|867.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |6546.0MiB|6546.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |7805.0MiB|7805.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |1622.0MiB|1622.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |8622.0MiB|8622.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1767.0MiB|1767.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |401.0MiB|401.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |2597.0MiB|2597.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |804.0MiB|804.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |2598.0MiB|2598.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |6809.0MiB|6809.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |5296.0MiB|5296.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |1509.0MiB|1509.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |11.554GiB|11.554GiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |2374.0MiB|2374.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |5861.0MiB|5861.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |575.0MiB|575.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |2723.0MiB|2723.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |657.0MiB|657.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |2555.0MiB|2555.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |867.0MiB|867.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |6546.0MiB|6546.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |7805.0MiB|7805.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |1622.0MiB|1622.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |8622.0MiB|8622.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1767.0MiB|1767.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |401.0MiB|401.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |2597.0MiB|2597.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled44527.smt2                                                                        | 776.909s |20.294GiB|
|scrambled77308.smt2                                                                        |1200.369s |11.639GiB|
|scrambled104811.smt2                                                                       |1200.511s |11.554GiB|
|scrambled25695.smt2                                                                        |1200.262s |8622.0MiB|
|scrambled13209.smt2                                                                        |1200.211s |7805.0MiB|
|scrambled102621.smt2                                                                       |1199.741s |6809.0MiB|
|scrambled13169.smt2                                                                        |1200.506s |6546.0MiB|
|scrambled111949.smt2                                                                       |1199.960s |5861.0MiB|
|scrambled98986.smt2                                                                        |1200.141s |5470.0MiB|
|scrambled77008.smt2                                                                        |1199.753s |5466.0MiB|
|scrambled8163.smt2                                                                         |1199.840s |5331.0MiB|
|scrambled102680.smt2                                                                       |1200.407s |5296.0MiB|
|scrambled65517.smt2                                                                        |1200.333s |4859.0MiB|
|scrambled55850.smt2                                                                        |1200.255s |4651.0MiB|
|scrambled117897.smt2                                                                       |1199.836s |2723.0MiB|
|scrambled95284.smt2                                                                        |1199.920s |2689.0MiB|
|scrambled101728.smt2                                                                       |1199.656s |2598.0MiB|
|scrambled37260.smt2                                                                        |1199.838s |2597.0MiB|
|scrambled124455.smt2                                                                       |1200.027s |2555.0MiB|
|scrambled109307.smt2                                                                       |1200.191s |2374.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled44527.smt2                                                                        | 776.909s |20.294GiB|
|scrambled77308.smt2                                                                        |1200.369s |11.639GiB|
|scrambled104811.smt2                                                                       |1200.511s |11.554GiB|
|scrambled25695.smt2                                                                        |1200.262s |8622.0MiB|
|scrambled13209.smt2                                                                        |1200.211s |7805.0MiB|
|scrambled102621.smt2                                                                       |1199.741s |6809.0MiB|
|scrambled13169.smt2                                                                        |1200.506s |6546.0MiB|
|scrambled111949.smt2                                                                       |1199.960s |5861.0MiB|
|scrambled98986.smt2                                                                        |1200.141s |5470.0MiB|
|scrambled77008.smt2                                                                        |1199.753s |5466.0MiB|
|scrambled8163.smt2                                                                         |1199.840s |5331.0MiB|
|scrambled102680.smt2                                                                       |1200.407s |5296.0MiB|
|scrambled65517.smt2                                                                        |1200.333s |4859.0MiB|
|scrambled55850.smt2                                                                        |1200.255s |4651.0MiB|
|scrambled117897.smt2                                                                       |1199.836s |2723.0MiB|
|scrambled95284.smt2                                                                        |1199.920s |2689.0MiB|
|scrambled101728.smt2                                                                       |1199.656s |2598.0MiB|
|scrambled37260.smt2                                                                        |1199.838s |2597.0MiB|
|scrambled124455.smt2                                                                       |1200.027s |2555.0MiB|
|scrambled109307.smt2                                                                       |1200.191s |2374.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1199.656s  |1199.656s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1199.741s  |1199.741s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.407s  |1200.407s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1199.909s  |1199.909s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.511s  |1200.511s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1199.960s  |1199.960s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1199.993s  |1199.993s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1199.836s  |1199.836s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 616.165s  | 616.165s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.506s  |1200.506s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.211s  |1200.211s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.262s  |1200.262s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1199.893s  |1199.893s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1199.527s  |1199.527s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1199.838s  |1199.838s  |   0.000s  | 0.0%|
|scrambled44527.smt2                                                                         | 776.909s  | 776.909s  |   0.000s  | 0.0%|
|scrambled46192.smt2                                                                         |1199.460s  |1199.460s  |   0.000s  | 0.0%|
|scrambled47581.smt2                                                                         |1199.723s  |1199.723s  |   0.000s  | 0.0%|
|scrambled49820.smt2                                                                         |1199.819s  |1199.819s  |   0.000s  | 0.0%|
|scrambled55845.smt2                                                                         |1200.009s  |1200.009s  |   0.000s  | 0.0%|
|scrambled55850.smt2                                                                         |1200.255s  |1200.255s  |   0.000s  | 0.0%|
|scrambled59368.smt2                                                                         |1199.856s  |1199.856s  |   0.000s  | 0.0%|
|scrambled65517.smt2                                                                         |1200.333s  |1200.333s  |   0.000s  | 0.0%|
|scrambled71015.smt2                                                                         | 389.279s  | 389.279s  |   0.000s  | 0.0%|
|scrambled76525.smt2                                                                         |1199.985s  |1199.985s  |   0.000s  | 0.0%|
|scrambled76532.smt2                                                                         |1199.884s  |1199.884s  |   0.000s  | 0.0%|
|scrambled77008.smt2                                                                         |1199.753s  |1199.753s  |   0.000s  | 0.0%|
|scrambled77308.smt2                                                                         |1200.369s  |1200.369s  |   0.000s  | 0.0%|
|scrambled8163.smt2                                                                          |1199.840s  |1199.840s  |   0.000s  | 0.0%|
|scrambled88927.smt2                                                                         | 765.323s  | 765.323s  |   0.000s  | 0.0%|
|scrambled92964.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled95284.smt2                                                                         |1199.920s  |1199.920s  |   0.000s  | 0.0%|
</details>
