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
Job tag: CVC5-threads-8-mode-portfolio-smtcomp2025-QF_NRA-timeout20min
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: portfolio
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
Job tag: CVC5-threads-8-mode-portfolio-smtcomp2025-QF_NRA-timeout20min
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: portfolio
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
|scrambled101086.smt2                                                                        |1199.624s  |1199.624s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1199.647s  |1199.647s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1199.530s  |1199.530s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1199.944s  |1199.944s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 754.321s  | 754.321s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1199.925s  |1199.925s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1199.557s  |1199.557s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1199.639s  |1199.639s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 650.906s  | 650.906s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1199.582s  |1199.582s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1199.584s  |1199.584s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1199.975s  |1199.975s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.000s  |1200.000s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1199.630s  |1199.630s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1199.719s  |1199.719s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1199.710s  |1199.710s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1199.155s  |1199.155s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1199.638s  |1199.638s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1199.624s  |1199.624s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1199.647s  |1199.647s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1199.530s  |1199.530s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1199.944s  |1199.944s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 754.321s  | 754.321s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1199.925s  |1199.925s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1199.557s  |1199.557s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1199.639s  |1199.639s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 650.906s  | 650.906s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1199.582s  |1199.582s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1199.584s  |1199.584s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1199.975s  |1199.975s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.000s  |1200.000s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1199.630s  |1199.630s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1199.719s  |1199.719s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1199.710s  |1199.710s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1199.155s  |1199.155s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1199.638s  |1199.638s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1199.624s  |1199.624s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1199.647s  |1199.647s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1199.530s  |1199.530s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1199.944s  |1199.944s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 754.321s  | 754.321s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1199.925s  |1199.925s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1199.557s  |1199.557s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1199.639s  |1199.639s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 650.906s  | 650.906s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1199.582s  |1199.582s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1199.584s  |1199.584s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1199.975s  |1199.975s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.000s  |1200.000s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1199.630s  |1199.630s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1199.719s  |1199.719s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1199.710s  |1199.710s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1199.155s  |1199.155s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1199.638s  |1199.638s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1199.624s  |1199.624s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1199.647s  |1199.647s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1199.530s  |1199.530s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1199.944s  |1199.944s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 754.321s  | 754.321s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1199.925s  |1199.925s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1199.557s  |1199.557s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1199.639s  |1199.639s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 650.906s  | 650.906s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1199.582s  |1199.582s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1199.584s  |1199.584s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1199.975s  |1199.975s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.000s  |1200.000s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1199.630s  |1199.630s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1199.719s  |1199.719s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1199.710s  |1199.710s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1199.155s  |1199.155s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1199.638s  |1199.638s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled77308.smt2                                                                        |1200.240s |4999.0MiB|
|scrambled98986.smt2                                                                        |1200.138s |9187.0MiB|
|scrambled102680.smt2                                                                       |1200.068s |7993.0MiB|
|scrambled102621.smt2                                                                       |1200.057s |10.331GiB|
|scrambled8163.smt2                                                                         |1200.057s |12.71GiB|
|scrambled55850.smt2                                                                        |1200.048s |9608.0MiB|
|scrambled13209.smt2                                                                        |1200.000s |13.077GiB|
|scrambled13169.smt2                                                                        |1199.975s |12.344GiB|
|scrambled104811.smt2                                                                       |1199.944s |4781.0MiB|
|scrambled111949.smt2                                                                       |1199.925s |11.012GiB|
|scrambled77008.smt2                                                                        |1199.900s |5547.0MiB|
|scrambled65517.smt2                                                                        |1199.821s |4410.0MiB|
|scrambled76525.smt2                                                                        |1199.734s |2319.0MiB|
|scrambled95284.smt2                                                                        |1199.732s |2438.0MiB|
|scrambled25695.smt2                                                                        |1199.719s |11.738GiB|
|scrambled31085.smt2                                                                        |1199.710s |1441.0MiB|
|scrambled101728.smt2                                                                       |1199.647s |5337.0MiB|
|scrambled117897.smt2                                                                       |1199.639s |2642.0MiB|
|scrambled37260.smt2                                                                        |1199.638s |2394.0MiB|
|scrambled17583.smt2                                                                        |1199.630s |2471.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled77308.smt2                                                                        |1200.240s |4999.0MiB|
|scrambled98986.smt2                                                                        |1200.138s |9187.0MiB|
|scrambled102680.smt2                                                                       |1200.068s |7993.0MiB|
|scrambled102621.smt2                                                                       |1200.057s |10.331GiB|
|scrambled8163.smt2                                                                         |1200.057s |12.71GiB|
|scrambled55850.smt2                                                                        |1200.048s |9608.0MiB|
|scrambled13209.smt2                                                                        |1200.000s |13.077GiB|
|scrambled13169.smt2                                                                        |1199.975s |12.344GiB|
|scrambled104811.smt2                                                                       |1199.944s |4781.0MiB|
|scrambled111949.smt2                                                                       |1199.925s |11.012GiB|
|scrambled77008.smt2                                                                        |1199.900s |5547.0MiB|
|scrambled65517.smt2                                                                        |1199.821s |4410.0MiB|
|scrambled76525.smt2                                                                        |1199.734s |2319.0MiB|
|scrambled95284.smt2                                                                        |1199.732s |2438.0MiB|
|scrambled25695.smt2                                                                        |1199.719s |11.738GiB|
|scrambled31085.smt2                                                                        |1199.710s |1441.0MiB|
|scrambled101728.smt2                                                                       |1199.647s |5337.0MiB|
|scrambled117897.smt2                                                                       |1199.639s |2642.0MiB|
|scrambled37260.smt2                                                                        |1199.638s |2394.0MiB|
|scrambled17583.smt2                                                                        |1199.630s |2471.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |2245.0MiB|2245.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |5337.0MiB|5337.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |10.331GiB|10.331GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |7993.0MiB|7993.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |1054.0MiB|1054.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |4781.0MiB|4781.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |3392.0MiB|3392.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |11.012GiB|11.012GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |939.0MiB|939.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |2642.0MiB|2642.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |746.0MiB|746.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |2287.0MiB|2287.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |1553.0MiB|1553.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |12.344GiB|12.344GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |13.077GiB|13.077GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2471.0MiB|2471.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |11.738GiB|11.738GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1441.0MiB|1441.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |499.0MiB|499.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |2394.0MiB|2394.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |2245.0MiB|2245.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |5337.0MiB|5337.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |10.331GiB|10.331GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |7993.0MiB|7993.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |1054.0MiB|1054.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |4781.0MiB|4781.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |3392.0MiB|3392.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |11.012GiB|11.012GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |939.0MiB|939.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |2642.0MiB|2642.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |746.0MiB|746.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |2287.0MiB|2287.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |1553.0MiB|1553.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |12.344GiB|12.344GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |13.077GiB|13.077GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2471.0MiB|2471.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |11.738GiB|11.738GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1441.0MiB|1441.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |499.0MiB|499.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |2394.0MiB|2394.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |2245.0MiB|2245.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |5337.0MiB|5337.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |10.331GiB|10.331GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |7993.0MiB|7993.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |1054.0MiB|1054.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |4781.0MiB|4781.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |3392.0MiB|3392.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |11.012GiB|11.012GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |939.0MiB|939.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |2642.0MiB|2642.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |746.0MiB|746.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |2287.0MiB|2287.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |1553.0MiB|1553.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |12.344GiB|12.344GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |13.077GiB|13.077GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2471.0MiB|2471.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |11.738GiB|11.738GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1441.0MiB|1441.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |499.0MiB|499.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |2394.0MiB|2394.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |2245.0MiB|2245.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |5337.0MiB|5337.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |10.331GiB|10.331GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |7993.0MiB|7993.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |1054.0MiB|1054.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |4781.0MiB|4781.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |3392.0MiB|3392.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |11.012GiB|11.012GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |939.0MiB|939.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |2642.0MiB|2642.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |746.0MiB|746.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |2287.0MiB|2287.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |1553.0MiB|1553.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |12.344GiB|12.344GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |13.077GiB|13.077GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2471.0MiB|2471.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |11.738GiB|11.738GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1441.0MiB|1441.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |499.0MiB|499.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |2394.0MiB|2394.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled44527.smt2                                                                        | 345.074s |19.047GiB|
|scrambled13209.smt2                                                                        |1200.000s |13.077GiB|
|scrambled8163.smt2                                                                         |1200.057s |12.71GiB|
|scrambled13169.smt2                                                                        |1199.975s |12.344GiB|
|scrambled25695.smt2                                                                        |1199.719s |11.738GiB|
|scrambled111949.smt2                                                                       |1199.925s |11.012GiB|
|scrambled102621.smt2                                                                       |1200.057s |10.331GiB|
|scrambled55850.smt2                                                                        |1200.048s |9608.0MiB|
|scrambled98986.smt2                                                                        |1200.138s |9187.0MiB|
|scrambled102680.smt2                                                                       |1200.068s |7993.0MiB|
|scrambled77008.smt2                                                                        |1199.900s |5547.0MiB|
|scrambled101728.smt2                                                                       |1199.647s |5337.0MiB|
|scrambled77308.smt2                                                                        |1200.240s |4999.0MiB|
|scrambled104811.smt2                                                                       |1199.944s |4781.0MiB|
|scrambled65517.smt2                                                                        |1199.821s |4410.0MiB|
|scrambled109307.smt2                                                                       | 754.321s |3392.0MiB|
|scrambled117897.smt2                                                                       |1199.639s |2642.0MiB|
|scrambled17583.smt2                                                                        |1199.630s |2471.0MiB|
|scrambled95284.smt2                                                                        |1199.732s |2438.0MiB|
|scrambled37260.smt2                                                                        |1199.638s |2394.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled44527.smt2                                                                        | 345.074s |19.047GiB|
|scrambled13209.smt2                                                                        |1200.000s |13.077GiB|
|scrambled8163.smt2                                                                         |1200.057s |12.71GiB|
|scrambled13169.smt2                                                                        |1199.975s |12.344GiB|
|scrambled25695.smt2                                                                        |1199.719s |11.738GiB|
|scrambled111949.smt2                                                                       |1199.925s |11.012GiB|
|scrambled102621.smt2                                                                       |1200.057s |10.331GiB|
|scrambled55850.smt2                                                                        |1200.048s |9608.0MiB|
|scrambled98986.smt2                                                                        |1200.138s |9187.0MiB|
|scrambled102680.smt2                                                                       |1200.068s |7993.0MiB|
|scrambled77008.smt2                                                                        |1199.900s |5547.0MiB|
|scrambled101728.smt2                                                                       |1199.647s |5337.0MiB|
|scrambled77308.smt2                                                                        |1200.240s |4999.0MiB|
|scrambled104811.smt2                                                                       |1199.944s |4781.0MiB|
|scrambled65517.smt2                                                                        |1199.821s |4410.0MiB|
|scrambled109307.smt2                                                                       | 754.321s |3392.0MiB|
|scrambled117897.smt2                                                                       |1199.639s |2642.0MiB|
|scrambled17583.smt2                                                                        |1199.630s |2471.0MiB|
|scrambled95284.smt2                                                                        |1199.732s |2438.0MiB|
|scrambled37260.smt2                                                                        |1199.638s |2394.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1199.624s  |1199.624s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1199.647s  |1199.647s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1199.530s  |1199.530s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1199.944s  |1199.944s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 754.321s  | 754.321s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1199.925s  |1199.925s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1199.557s  |1199.557s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1199.639s  |1199.639s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 650.906s  | 650.906s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1199.582s  |1199.582s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1199.584s  |1199.584s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1199.975s  |1199.975s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.000s  |1200.000s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1199.630s  |1199.630s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1199.719s  |1199.719s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1199.710s  |1199.710s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1199.155s  |1199.155s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1199.638s  |1199.638s  |   0.000s  | 0.0%|
|scrambled44527.smt2                                                                         | 345.074s  | 345.074s  |   0.000s  | 0.0%|
|scrambled46192.smt2                                                                         |1199.287s  |1199.287s  |   0.000s  | 0.0%|
|scrambled47581.smt2                                                                         |1199.543s  |1199.543s  |   0.000s  | 0.0%|
|scrambled49820.smt2                                                                         |1199.617s  |1199.617s  |   0.000s  | 0.0%|
|scrambled55845.smt2                                                                         |1199.557s  |1199.557s  |   0.000s  | 0.0%|
|scrambled55850.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled59368.smt2                                                                         |1199.629s  |1199.629s  |   0.000s  | 0.0%|
|scrambled65517.smt2                                                                         |1199.821s  |1199.821s  |   0.000s  | 0.0%|
|scrambled71015.smt2                                                                         | 555.157s  | 555.157s  |   0.000s  | 0.0%|
|scrambled76525.smt2                                                                         |1199.734s  |1199.734s  |   0.000s  | 0.0%|
|scrambled76532.smt2                                                                         |1199.416s  |1199.416s  |   0.000s  | 0.0%|
|scrambled77008.smt2                                                                         |1199.900s  |1199.900s  |   0.000s  | 0.0%|
|scrambled77308.smt2                                                                         |1200.240s  |1200.240s  |   0.000s  | 0.0%|
|scrambled8163.smt2                                                                          |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled88927.smt2                                                                         | 961.385s  | 961.385s  |   0.000s  | 0.0%|
|scrambled92964.smt2                                                                         |1199.583s  |1199.583s  |   0.000s  | 0.0%|
|scrambled95284.smt2                                                                         |1199.732s  |1199.732s  |   0.000s  | 0.0%|
</details>
