Comparing data and data


# SUMMARY
- LHS tests = 45
- RHS tests = 45
- LHS success = 45  (100.0%)
- RHS success = 45  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-8-mode-partition-smtcomp2025-QF_IDL-timeout20min
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_IDL
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-8-mode-partition-smtcomp2025-QF_IDL-timeout20min
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_IDL
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.439s  |1200.439s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1199.871s  |1199.871s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.405s  |1200.405s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.521s  |1200.521s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.381s  |1200.381s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1199.714s  |1199.714s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.448s  |1200.448s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.518s  |1200.518s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1199.985s  |1199.985s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.363s  |1200.363s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1199.850s  |1199.850s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1199.895s  |1199.895s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1199.901s  |1199.901s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.596s  |1200.596s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1199.777s  |1199.777s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1199.840s  |1199.840s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.828s  |1200.828s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1199.782s  |1199.782s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.369s  |1200.369s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.439s  |1200.439s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1199.871s  |1199.871s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.405s  |1200.405s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.521s  |1200.521s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.381s  |1200.381s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1199.714s  |1199.714s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.448s  |1200.448s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.518s  |1200.518s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1199.985s  |1199.985s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.363s  |1200.363s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1199.850s  |1199.850s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1199.895s  |1199.895s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1199.901s  |1199.901s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.596s  |1200.596s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1199.777s  |1199.777s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1199.840s  |1199.840s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.828s  |1200.828s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1199.782s  |1199.782s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.369s  |1200.369s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.439s  |1200.439s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1199.871s  |1199.871s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.405s  |1200.405s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.521s  |1200.521s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.381s  |1200.381s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1199.714s  |1199.714s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.448s  |1200.448s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.518s  |1200.518s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1199.985s  |1199.985s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.363s  |1200.363s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1199.850s  |1199.850s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1199.895s  |1199.895s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1199.901s  |1199.901s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.596s  |1200.596s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1199.777s  |1199.777s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1199.840s  |1199.840s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.828s  |1200.828s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1199.782s  |1199.782s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.369s  |1200.369s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.439s  |1200.439s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1199.871s  |1199.871s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.405s  |1200.405s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.521s  |1200.521s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.381s  |1200.381s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1199.714s  |1199.714s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.448s  |1200.448s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.518s  |1200.518s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1199.985s  |1199.985s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.363s  |1200.363s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1199.850s  |1199.850s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1199.895s  |1199.895s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1199.901s  |1199.901s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.596s  |1200.596s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1199.777s  |1199.777s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1199.840s  |1199.840s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.828s  |1200.828s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1199.782s  |1199.782s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.369s  |1200.369s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1200.828s |9039.0MiB|
|scrambled15552.smt2                                                                        |1200.596s |9704.0MiB|
|scrambled117178.smt2                                                                       |1200.521s |5312.0MiB|
|scrambled124624.smt2                                                                       |1200.518s |5333.0MiB|
|scrambled90733.smt2                                                                        |1200.506s |4240.0MiB|
|scrambled58720.smt2                                                                        |1200.496s |3679.0MiB|
|scrambled54073.smt2                                                                        |1200.453s |2425.0MiB|
|scrambled122413.smt2                                                                       |1200.448s |2940.0MiB|
|scrambled100416.smt2                                                                       |1200.439s |2966.0MiB|
|scrambled116992.smt2                                                                       |1200.405s |2083.0MiB|
|scrambled41801.smt2                                                                        |1200.383s |1841.0MiB|
|scrambled119992.smt2                                                                       |1200.381s |1619.0MiB|
|scrambled35345.smt2                                                                        |1200.369s |2097.0MiB|
|scrambled1379.smt2                                                                         |1200.363s |1499.0MiB|
|scrambled62859.smt2                                                                        |1200.271s |3183.0MiB|
|scrambled109208.smt2                                                                       |1200.219s |9778.0MiB|
|scrambled41312.smt2                                                                        |1200.019s |1606.0MiB|
|scrambled78432.smt2                                                                        |1200.007s |2773.0MiB|
|scrambled38610.smt2                                                                        |1200.002s |2791.0MiB|
|scrambled98799.smt2                                                                        |1199.992s |3577.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1200.828s |9039.0MiB|
|scrambled15552.smt2                                                                        |1200.596s |9704.0MiB|
|scrambled117178.smt2                                                                       |1200.521s |5312.0MiB|
|scrambled124624.smt2                                                                       |1200.518s |5333.0MiB|
|scrambled90733.smt2                                                                        |1200.506s |4240.0MiB|
|scrambled58720.smt2                                                                        |1200.496s |3679.0MiB|
|scrambled54073.smt2                                                                        |1200.453s |2425.0MiB|
|scrambled122413.smt2                                                                       |1200.448s |2940.0MiB|
|scrambled100416.smt2                                                                       |1200.439s |2966.0MiB|
|scrambled116992.smt2                                                                       |1200.405s |2083.0MiB|
|scrambled41801.smt2                                                                        |1200.383s |1841.0MiB|
|scrambled119992.smt2                                                                       |1200.381s |1619.0MiB|
|scrambled35345.smt2                                                                        |1200.369s |2097.0MiB|
|scrambled1379.smt2                                                                         |1200.363s |1499.0MiB|
|scrambled62859.smt2                                                                        |1200.271s |3183.0MiB|
|scrambled109208.smt2                                                                       |1200.219s |9778.0MiB|
|scrambled41312.smt2                                                                        |1200.019s |1606.0MiB|
|scrambled78432.smt2                                                                        |1200.007s |2773.0MiB|
|scrambled38610.smt2                                                                        |1200.002s |2791.0MiB|
|scrambled98799.smt2                                                                        |1199.992s |3577.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |2966.0MiB|2966.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |3086.0MiB|3086.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |9778.0MiB|9778.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |2083.0MiB|2083.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |5312.0MiB|5312.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |1619.0MiB|1619.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |9151.0MiB|9151.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |2940.0MiB|2940.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |5333.0MiB|5333.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |3051.0MiB|3051.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |1499.0MiB|1499.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |2136.0MiB|2136.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |3514.0MiB|3514.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1782.0MiB|1782.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |9704.0MiB|9704.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |2718.0MiB|2718.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |1448.0MiB|1448.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |9039.0MiB|9039.0MiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |3585.0MiB|3585.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |2097.0MiB|2097.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |2966.0MiB|2966.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |3086.0MiB|3086.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |9778.0MiB|9778.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |2083.0MiB|2083.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |5312.0MiB|5312.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |1619.0MiB|1619.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |9151.0MiB|9151.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |2940.0MiB|2940.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |5333.0MiB|5333.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |3051.0MiB|3051.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |1499.0MiB|1499.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |2136.0MiB|2136.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |3514.0MiB|3514.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1782.0MiB|1782.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |9704.0MiB|9704.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |2718.0MiB|2718.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |1448.0MiB|1448.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |9039.0MiB|9039.0MiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |3585.0MiB|3585.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |2097.0MiB|2097.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |2966.0MiB|2966.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |3086.0MiB|3086.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |9778.0MiB|9778.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |2083.0MiB|2083.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |5312.0MiB|5312.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |1619.0MiB|1619.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |9151.0MiB|9151.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |2940.0MiB|2940.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |5333.0MiB|5333.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |3051.0MiB|3051.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |1499.0MiB|1499.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |2136.0MiB|2136.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |3514.0MiB|3514.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1782.0MiB|1782.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |9704.0MiB|9704.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |2718.0MiB|2718.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |1448.0MiB|1448.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |9039.0MiB|9039.0MiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |3585.0MiB|3585.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |2097.0MiB|2097.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |2966.0MiB|2966.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |3086.0MiB|3086.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |9778.0MiB|9778.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |2083.0MiB|2083.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |5312.0MiB|5312.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |1619.0MiB|1619.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |9151.0MiB|9151.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |2940.0MiB|2940.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |5333.0MiB|5333.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |3051.0MiB|3051.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |1499.0MiB|1499.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |2136.0MiB|2136.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |3514.0MiB|3514.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1782.0MiB|1782.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |9704.0MiB|9704.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |2718.0MiB|2718.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |1448.0MiB|1448.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |9039.0MiB|9039.0MiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |3585.0MiB|3585.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |2097.0MiB|2097.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled109208.smt2                                                                       |1200.219s |9778.0MiB|
|scrambled15552.smt2                                                                        |1200.596s |9704.0MiB|
|scrambled122058.smt2                                                                       |1199.714s |9151.0MiB|
|scrambled25140.smt2                                                                        |1200.828s |9039.0MiB|
|scrambled92133.smt2                                                                        |1199.911s |7502.0MiB|
|scrambled124624.smt2                                                                       |1200.518s |5333.0MiB|
|scrambled117178.smt2                                                                       |1200.521s |5312.0MiB|
|scrambled4441.smt2                                                                         |1199.963s |4294.0MiB|
|scrambled90733.smt2                                                                        |1200.506s |4240.0MiB|
|scrambled58720.smt2                                                                        |1200.496s |3679.0MiB|
|scrambled27577.smt2                                                                        |1199.782s |3585.0MiB|
|scrambled98799.smt2                                                                        |1199.992s |3577.0MiB|
|scrambled14967.smt2                                                                        |1199.895s |3514.0MiB|
|scrambled79181.smt2                                                                        |1199.972s |3285.0MiB|
|scrambled62859.smt2                                                                        |1200.271s |3183.0MiB|
|scrambled103851.smt2                                                                       |1199.871s |3086.0MiB|
|scrambled128361.smt2                                                                       |1199.985s |3051.0MiB|
|scrambled100416.smt2                                                                       |1200.439s |2966.0MiB|
|scrambled122413.smt2                                                                       |1200.448s |2940.0MiB|
|scrambled38610.smt2                                                                        |1200.002s |2791.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled109208.smt2                                                                       |1200.219s |9778.0MiB|
|scrambled15552.smt2                                                                        |1200.596s |9704.0MiB|
|scrambled122058.smt2                                                                       |1199.714s |9151.0MiB|
|scrambled25140.smt2                                                                        |1200.828s |9039.0MiB|
|scrambled92133.smt2                                                                        |1199.911s |7502.0MiB|
|scrambled124624.smt2                                                                       |1200.518s |5333.0MiB|
|scrambled117178.smt2                                                                       |1200.521s |5312.0MiB|
|scrambled4441.smt2                                                                         |1199.963s |4294.0MiB|
|scrambled90733.smt2                                                                        |1200.506s |4240.0MiB|
|scrambled58720.smt2                                                                        |1200.496s |3679.0MiB|
|scrambled27577.smt2                                                                        |1199.782s |3585.0MiB|
|scrambled98799.smt2                                                                        |1199.992s |3577.0MiB|
|scrambled14967.smt2                                                                        |1199.895s |3514.0MiB|
|scrambled79181.smt2                                                                        |1199.972s |3285.0MiB|
|scrambled62859.smt2                                                                        |1200.271s |3183.0MiB|
|scrambled103851.smt2                                                                       |1199.871s |3086.0MiB|
|scrambled128361.smt2                                                                       |1199.985s |3051.0MiB|
|scrambled100416.smt2                                                                       |1200.439s |2966.0MiB|
|scrambled122413.smt2                                                                       |1200.448s |2940.0MiB|
|scrambled38610.smt2                                                                        |1200.002s |2791.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.439s  |1200.439s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1199.871s  |1199.871s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.219s  |1200.219s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.405s  |1200.405s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.521s  |1200.521s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.381s  |1200.381s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1199.714s  |1199.714s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.448s  |1200.448s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.518s  |1200.518s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1199.985s  |1199.985s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.363s  |1200.363s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1199.850s  |1199.850s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1199.895s  |1199.895s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1199.901s  |1199.901s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.596s  |1200.596s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1199.777s  |1199.777s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1199.840s  |1199.840s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.828s  |1200.828s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1199.782s  |1199.782s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.369s  |1200.369s  |   0.000s  | 0.0%|
|scrambled38610.smt2                                                                         |1200.002s  |1200.002s  |   0.000s  | 0.0%|
|scrambled41312.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled41773.smt2                                                                         |1199.863s  |1199.863s  |   0.000s  | 0.0%|
|scrambled41801.smt2                                                                         |1200.383s  |1200.383s  |   0.000s  | 0.0%|
|scrambled42287.smt2                                                                         |1199.896s  |1199.896s  |   0.000s  | 0.0%|
|scrambled4441.smt2                                                                          |1199.963s  |1199.963s  |   0.000s  | 0.0%|
|scrambled54073.smt2                                                                         |1200.453s  |1200.453s  |   0.000s  | 0.0%|
|scrambled58720.smt2                                                                         |1200.496s  |1200.496s  |   0.000s  | 0.0%|
|scrambled62536.smt2                                                                         |1199.982s  |1199.982s  |   0.000s  | 0.0%|
|scrambled62810.smt2                                                                         |1199.729s  |1199.729s  |   0.000s  | 0.0%|
|scrambled62859.smt2                                                                         |1200.271s  |1200.271s  |   0.000s  | 0.0%|
|scrambled6373.smt2                                                                          |1199.698s  |1199.698s  |   0.000s  | 0.0%|
|scrambled75206.smt2                                                                         |1199.895s  |1199.895s  |   0.000s  | 0.0%|
|scrambled78432.smt2                                                                         |1200.007s  |1200.007s  |   0.000s  | 0.0%|
|scrambled78606.smt2                                                                         |1199.919s  |1199.919s  |   0.000s  | 0.0%|
|scrambled79181.smt2                                                                         |1199.972s  |1199.972s  |   0.000s  | 0.0%|
|scrambled82743.smt2                                                                         |1199.817s  |1199.817s  |   0.000s  | 0.0%|
|scrambled89071.smt2                                                                         |1189.366s  |1189.366s  |   0.000s  | 0.0%|
|scrambled90733.smt2                                                                         |1200.506s  |1200.506s  |   0.000s  | 0.0%|
|scrambled92133.smt2                                                                         |1199.911s  |1199.911s  |   0.000s  | 0.0%|
|scrambled96514.smt2                                                                         |1121.113s  |1121.113s  |   0.000s  | 0.0%|
|scrambled96733.smt2                                                                         |1199.677s  |1199.677s  |   0.000s  | 0.0%|
|scrambled97138.smt2                                                                         |1199.856s  |1199.856s  |   0.000s  | 0.0%|
|scrambled98799.smt2                                                                         |1199.992s  |1199.992s  |   0.000s  | 0.0%|
</details>
